# День переезда: план по шагам

Написан 6 октября 2026 ночью как подготовка (решение Дениса «Хочу сейчас»). Ни один шаг отсюда не выполняется, пока Денис не скажет «переезжаем». Порядок важен: сначала всё, что не трогает домен, потом смена nameservers, потом само переключение одним движением.

Слова: nameservers это два адреса, которые говорят интернету, где искать записи домена. Зона это записи домена в Cloudflare. «Без прокси» (серое облако) значит, что Cloudflare только отвечает, куда идти, и трафик через себя не пропускает. Pages это хостинг нового сайта, проект fppplumbing-preview. Access это вход по почте на тестовом адресе.

## До дня переезда (сделано или делается заранее)

- Зона fppplumbing.com добавлена в аккаунт Дениса (один шаг в панели, docs/dns-before-move.md), записи сверены скриптом `python3 tools/dns_zone.py check`: все записи HOSTiQ стоят один к одному, все без прокси, A и www ведут на HOSTiQ. Две записи google-site-verification тоже там: подтверждение Search Console держится после смены nameservers само.
- Проверка всех адресов скриптом `python3 tools/check_migration.py`: каждый старый адрес отвечает 200 или правильным 301, title, H1 и описания совпадают с утверждёнными, sitemap и robots в порядке, сборка «как для живого сайта» без noindex (docs/migration-check-2026-10-06.md).
- От Дениса: хостинг HOSTiQ оплачен минимум на 30 дней вперёд, домен с автопродлением (24 декабря 2026), ответ, идёт ли реклама в Google Ads.
- Форма заявки уже работает через функцию Pages и секреты проекта; Turnstile знает оба адреса. На живом домене ничего не меняется.

## Шаг 1. Подключить Google-теги и собрать сайт как живой (Claude Code, утро дня переезда)

1. Подключить компонент GoogleTags (site/src/components/GoogleTags.astro) в head и GoogleTagsNoscript после body в site/src/layouts/Base.astro, как написано в самом компоненте. Это тег GT-PJ4NVLSP (GA4 и Google Ads через него), Google Ads AW-9807662480 и Tag Manager GTM-NVSNS9FK, те же, что на живом сайте.
2. Собрать сайт с `SITE_STAGING=0`: уходит тег noindex со всех страниц, а заголовок X-Robots-Tag остаётся только для адресов *.pages.dev (так тестовый адрес никогда не попадёт в поиск, а живой домен чистый).
3. `SITE_STAGING=0 python3 tools/check_site.py` и `python3 tools/check_migration.py`: все проверки чистые.
4. Выложить в проект Pages (`npx wrangler pages deploy dist --project-name fppplumbing-preview --branch main`). Тестовый адрес остаётся за Access, поэтому Google его не видит, хотя noindex там уже нет.
5. Проверить теги на тестовом адресе из браузера, где есть вход по Access: в консоли браузера должны загрузиться gtag/js и gtm.js после загрузки страницы.

Почему теги до смены nameservers: правило проекта (Денис, 2 октября 2026). Если реклама идёт, учёт не прерывается ни на час.

## Шаг 2. Смена nameservers у HOSTiQ (Денис, единственное действие у HOSTiQ)

В панели HOSTiQ (управление доменом fppplumbing.com, раздел nameservers): заменить dns1.hostiq.ua и dns2.hostiq.ua на два адреса Cloudflare, которые показала панель при добавлении зоны (вида xxx.ns.cloudflare.com). Больше ничего у HOSTiQ не менять: ни записи DNS, ни хостинг, ни WordPress.

После этого шага для посетителей не меняется ничего: в зоне Cloudflare A и www ведут на тот же сервер HOSTiQ без прокси, почта на тех же записях.

## Шаг 3. Ждать, пока зона станет активной (Claude Code проверяет)

- Проверка: `dig +short NS fppplumbing.com @1.1.1.1` показывает адреса Cloudflare; `python3 tools/dns_zone.py check` показывает status active. Обычно от минут до нескольких часов, в правилах DNS до двух суток.
- Сертификат (окно сертификата): после активации Cloudflare сам выпускает сертификат для домена (Universal SSL). Пока он не выпущен, включать прокси нельзя: посетители увидят ошибку сертификата. Проверка по API (`/zones/<id>/ssl/certificate_packs`, статус active) или в панели SSL/TLS, Edge Certificates. Обычно минуты, редко до суток.
- Проверить почту: письмо на request@fppplumbing.com с другого ящика и ответ с него (Денис). MX не менялся, но проверка обязательна.

## Шаг 4. Переключение (одно движение, Claude Code с Денисом на связи)

1. Привязать домены к проекту Pages: fppplumbing.com и www.fppplumbing.com (панель Cloudflare, Workers & Pages, проект fppplumbing-preview, Custom domains, Set up a custom domain; или по API). Cloudflare предложит создать записи сам: согласиться. В зоне запись A fppplumbing.com заменяется на CNAME fppplumbing.com → fppplumbing-preview.pages.dev с прокси, запись www тоже. С этой секунды сайт отдаёт Cloudflare Pages. (Если делать по API, записи DNS ставит `python3 tools/dns_zone.py` с токеном из скрытого окна, как при копировании.)
2. Правило www → fppplumbing.com: в зоне Rules, Redirect Rules, Create rule: если Hostname equals www.fppplumbing.com, то Dynamic redirect, выражение `concat("https://fppplumbing.com", http.request.uri.path)`, код 301, Preserve query string включить. На живом сайте www отвечает 301 на fppplumbing.com, это правило повторяет то же.
3. Always Use HTTPS: в SSL/TLS, Edge Certificates проверить, что включено (http → https 301, как сейчас). Режим шифрования Full (strict) можно включить сразу: Pages говорит с Cloudflare по https.

Откат с этого шага: docs/rollback.md, раздел «Быстрый откат», минуты.

## Шаг 5. Проверки сразу после переключения (Claude Code)

- `curl -sI https://fppplumbing.com/` отвечает 200, в заголовках server: cloudflare, нет X-Robots-Tag; в HTML нет `<meta name="robots" content="noindex">`.
- https://www.fppplumbing.com/ отвечает 301 на https://fppplumbing.com/; http://fppplumbing.com/ отвечает 301 на https.
- `python3 tools/check_migration.py --live https://fppplumbing.com`: все 64 адреса и все старые адреса отвечают как в проверке до переезда.
- Страница /?attachment_id=3509 отвечает 301 на /gallery/ (функция Pages работает на живом домене).
- Телефонные ссылки на главной открывают номер (Денис с телефона).
- Форма: одна настоящая заявка с fppplumbing.com (Денис), она приходит в Telegram и на экране стоит галочка.
- Теги: в GA4 в реальном времени виден визит (Денис открывает сайт с телефона, Claude Code или чат смотрит отчёт Realtime по доступу Дениса), Google Ads и Tag Manager загружаются.
- Почта: ещё одно письмо туда и обратно.

## Шаг 6. Search Console и остальное (в тот же день)

- Search Console, собственность fppplumbing.com (домен): раздел Sitemaps: добавить https://fppplumbing.com/sitemap.xml; старый sitemap_index.xml теперь отвечает 301 на него. Запросить индексирование главной, Frisco, Plano и emergency (URL Inspection, Request indexing).
- Google Business Profile: ссылки на сайт не меняются (те же адреса /plumber-frisco-tx/ и /plumber-plano-tx/); ничего не делать.
- Yelp, Thumbtack, BBB, соцсети: адреса те же; ничего не делать.
- Журнал проекта: запись о переезде со временем каждого шага и результатами проверок.

## Что остаётся как есть

- Тестовый адрес fppplumbing-preview.pages.dev остаётся за Access и с X-Robots-Tag noindex: так у сайта нет открытой копии.
- WordPress и хостинг HOSTiQ не трогаются минимум 30 дней: это откат. Зона DNS у HOSTiQ тоже остаётся, как была.
- Секреты формы живут в проекте Pages; старая форма WordPress остаётся на старом сайте и больше никому не видна.
- Записи почты (MX, SPF, DKIM, DMARC) один к одному; два улучшения почты из docs/dns-before-move.md делаются отдельно и позже.

## Через 30 дней (отдельное решение Дениса)

Если за 30 дней не понадобился откат: решение, что делать с хостингом HOSTiQ. Копию WordPress (файлы и база) сохранить перед любым отключением. Это не часть переезда.
