# Drain cleaning: живая страница и Search Console (3 октября 2026)

Страница: https://fppplumbing.com/clogged-drain-cleaning-frisco-plano/ . Сейчас не переписывается, текста страницы здесь нет. Данные: краул живого сайта от 30 сентября 2026 (`source/crawl/pages/clogged-drain-cleaning-frisco-plano.json`, код `source/crawl/html/clogged-drain-cleaning-frisco-plano.html`, остальные 63 файла в `source/crawl/pages/`: 62 страницы с текстом и `/blog/author/admin/`, который отдаёт 301); новый сайт `site/src/content/pages/clogged-drain-cleaning-frisco-plano.md` и собранная `site/dist/clogged-drain-cleaning-frisco-plano/index.html` (прочитаны 3 октября); правки `tools/build_launch_content.py` и `site/src/data/launch-changes.csv`; одобренный текст `source/FPP-Drain-Cleaning-Page.docx`; Search Console `source/gsc/page-query-3m.csv`, `page-query-16m.csv`, `performance-3m/Pages.csv`, `performance-16m/Pages.csv`, `page-query-coverage.csv`; `seo/keyword-map.md` и `.csv`, `seo/cannibalization-findings.md`, `docs/pages-plan.md`; отзывы `reviews/all-reviews.csv`, `site-ledger.md`, `site-reviews.json`; фото `photos/captions-en.csv`.

Страница отвечает 200, есть в page-sitemap.xml, canonical на себя, index и follow. Опубликована 6 мая 2025, последняя правка 27 июня 2026. План (`docs/pages-plan.md`, группа 3, номер 13): 1,577 показов, место 24.8, 0 кликов. Карта ключей: главный "drain cleaning frisco", вторые "drain cleaning plano; clogged drain frisco; clogged drain plano", нельзя "sewer line repair; sewer camera inspection (drain services page); hydro jetting (not offered)", решение "deepen".

Файлы с длинными таблицами, `docs/briefs/services/drain-cleaning/`:
- `drain-cleaning-gsc-table-3m.md` (все 29 запросов) и `drain-cleaning-gsc-table-16m.md` (все 114): клики, показы, место, другой период, группа, слова в живом тексте, где стоит точная фраза, чей запрос.
- `drain-cleaning-gsc-top30-and-phrases.md`: первые 30 по показам за оба периода и проверка целой фразы.
- `drain-cleaning-gsc-other-pages-3m.md` (297 строк) и `drain-cleaning-gsc-other-pages-16m.md` (659 строк): запросы про чистку, где другая страница выше этой, берёт больше показов или этой страницы нет.
- `drain-cleaning-links-to-page.md`: 27 ссылок на страницу из текста 25 других страниц.

## Коротко

1. Кормит сейчас: кликов ноль за 3 и за 16 месяцев. 3 мес: 1,577 показов, место 24.8; 16 мес: 12,971 показ, место 46.8 (итоги Google со скрытыми запросами). Показы держат "drain cleaning frisco" (422 за 3 мес, место 22.5), "frisco drain cleaning" (408, 23.5), "clogged drain plano" (121, 23.9).
2. Нельзя потерять: title "Clogged Drain? We Clear Drains Fast in Frisco & Plano" держит clogged drain(s) с Frisco и Plano (7 запросов, 2,293 показа за 16 мес, лучший "clogged drains frisco" 804, место 14.8); H2 "FAQ - Drain Cleaning" единственный несёт фразу "drain cleaning" (355 показов); адрес страницы. По кликам терять нечего.
3. Главная дыра: фраза главного запроса "drain cleaning frisco" и все "drain cleaning + город" на странице не стоят нигде. H1 не держит ни одного запроса. Слова "blocked" (433 показа за 16 мес) на странице нет.
4. Запросы про чистку берут другие страницы: за 3 мес Plano (2,541 показ) и Frisco (2,440) каждая больше этой (1,392), в основном через карточки Google; за 16 мес главная 9,373 показа и стоит выше этой на 27 запросах; на "drain cleaning frisco" выше этой стоят `/drain-services/`, Frisco и Plano; `/drain-services/` почти одна стоит на "drain cleaning mckinney" (660 из 666). Чистка с восемью другими городами уходит на их городские страницы.
5. Против правил на живой странице: hydro jetting в схеме, "We’ll show up fast", "North Dallas", два длинных тире, "FAQ - Drain Cleaning", ответы FAQ тегом H2. На новом сайте это исправлено. Остались: заход на тему `/drain-services/` (H2 про камеру, "That section has to be replaced", cast iron, "Sewer smell inside the house") без ссылки на неё; "always a camera afterward" против слов Дениса от 2 октября; "Fast" в title, H1, описании и схеме Service; H2 "Let’s Clear It Today"; "We’re already nearby"; лозунги и вопросы в заголовках; ссылка на главную в конце, а не во вступлении.
6. Чего нет по правилу 8: 885 слов против около 2,500; 5 содержательных H2 против 10 до 16, ключ "drain cleaning" только в H2 FAQ; список симптомов без ссылок; раздела «если это происходит сейчас» нет (одна фраза); FAQ 3 против 5 до 7; из десяти городов в тексте только Frisco и Plano; из 12 других услуг только emergency; нет ссылок на `/drain-services/`, toilet, disposal, гайд про перекрытие воды; нет внешней официальной ссылки; нет ни слова о линии кондиционера, хотя главная отправляет сюда (`docs/pages-plan.md`).
7. Новый сайт: старый текст с пятью точечными правками плюс шаблон (FAQ жирным, новая схема, два отзыва, блок «What is happening right now?», на первом экране фото 49 из Prosper вместо старого снимка, старый снимок ушёл в текст). Одобренный `source/FPP-Drain-Cleaning-Page.docx` (1,861 слово, 10 H2, 6 FAQ, все десять городов) есть, но на новом сайте не стоит.
8. Живая суть: «одна раковина или вся линия», история с garden trowel и пятью сантехниками, разница cable и chain snake.

## 1. Живая страница

### 1.1. Title, описание, H1, заголовки, объём

| Что | На живой странице |
|---|---|
| Title (53 знака) | "Clogged Drain? We Clear Drains Fast in Frisco & Plano" |
| Meta description (179 знаков) | "Slow sink or sewer backup? We unclog drains fast in Frisco, Plano & McKinney. Licensed plumber near you with clean, same-day service. If it’s urgent, check our Emergency Services." |
| H1 (14 слов) | "Sink Won’t Drain? Shower Backed Up? We Unclog Drains Fast in Frisco & Plano" |
| OG title | "Drain Cleaning & Unclogging" (по правилу должен совпадать с title) |

H2 по порядку (слов в разделе без заголовка):
1. "Drain Backed Up? Here’s How You Know It’s Serious" (120)
2. "What Actually Causes a Clogged Drain Line" (133)
3. "Why a Camera Inspection Saves You From Clogging Again" (87)
4. "The Tools We Actually Use (Not Just a Snake)" (134)
5. "Why Frisco & Plano Homeowners Call Us Back" (79)
6. "FAQ - Drain Cleaning" (вопросы 29 слов, ответы 86)
7, 8, 9. Три ответа FAQ, свёрстанные тегом H2 (текст в 1.2).
10. "Clogged Drain? Let’s Clear It Today" (заключение, 62 слова; в коде после "Today" невидимый знак нулевой ширины)
11. "980-899-7997 469-998-8999" (телефоны нижней панели тегом H2, шаблон)

H3 нет. Объём: 885 слов по краулу, это весь свой текст от H1 до конца (меню и подвал не входят), вступление 89 слов. До около 2,500 не хватает примерно 1,600.

### 1.2. FAQ, слово в слово

| № | Вопрос | Ответ |
|---|---|---|
| 1 | "My sink is draining slow. Do I need a plumber?" | "If it’s just one sink, it might be a minor clog. But if multiple drains are slow, you likely need a pro to clean the line." |
| 2 | "What’s the difference between a regular snake and a chain snake?" | "A regular snake punches through the clog. A chain snake spins and scrubs the pipe walls clean, it pulls off grease, scale, and roots a cable just slides past. Light clog, cable’s enough. Built-up gunk or roots, you need the chain." |
| 3 | "How do I keep drains from clogging again?" | "Don’t pour grease down the sink. Use hair catchers. And get your drains cleaned professionally every year or two." |

- Вопросы стоят текстом в раскрывающемся списке Elementor (`summary`), не заголовками; ответы свёрстаны тегом H2.
- В схеме два узла FAQPage; в первом ответ 2 с длинным тире ("scrubs the pipe walls clean [длинное тире] it pulls off") и прямыми апострофами.
- Слово в слово ни один вопрос на других 62 страницах краула с текстом не повторяется. Близко по теме: пост `/blog/clogged-kitchen-sink-chain-snake/` ("why a chain snake works better than a regular snake for grease buildup"), гайд про ванну (вопрос "Why is my bathtub draining slowly?"), пост `/blog/clogged-shower-drain-little-elm-case/` ("...or keeps clogging again").
- Вопросов 3, нужно 5 до 7.

### 1.3. Отзывы

На живой странице отзывов нет (ни блока, ни ссылок на Google, Yelp, Thumbtack); в `reviews/all-reviews.csv` у этой страницы нет ни одной строки `on_old_site`. На новом сайте шаблон сам ставит блок (`ReviewCards`, метки `<!-- reviews -->` в файле нет), из `reviews/site-reviews.json` два отзыва Google из профиля Plano:
- Joel Brown, 27 мая 2025, "★★★★★ · Local Guide Level 4 · May 2025 · Google", про "our drain problem", говорит о Денисе по имени.
- David Baez, 14 августа 2025, "★★★★★ · Local Guide Level 4 · August 2025 · Google", про засор дренажа кондиционера и воду с потолка ("flushed the drain line").

David Baez тоже называет Дениса по имени ("Denys and his team"). Оба текста совпадают с архивом знак в знак, даты и Local Guide 4 тоже; по `reviews/site-ledger.md` (40 авторов, 0 на двух страницах) оба стоят только здесь. Города в текстах нет, в подписях нет. "showed up really fast" и "issue - boom" это слова клиента, по решению Дениса не трогаются. Ответ компании на отзыв David Baez в архиве называет Frisco, а отзыв в профиле Plano: город работы по файлам не ясен.

### 1.4. Фото

Фото одно: `/wp-content/uploads/2025/05/drain-cleaning-unclogging-snake-frisco.jpg` (720 на 1280), alt "Drain cleaning with snake tool for clogged pipes in Frisco", оно же OG картинка, грузится лениво. Я открыл файл: барабанная машина Milwaukee FUEL на раме, трос уходит в наружный клинаут (две белые крышки в мульче) у кирпичной стены. По виду настоящий снимок с работы; номеров домов и знаков я не увидел; Frisco называет только alt. По имени файла в `photos/index.csv` и `photos/captions-en.csv` снимка нет. Остальное шаблон: логотип дважды, знак BBB.

В `photos/captions-en.csv` для этой страницы отмечены 21 фото и клип. На живой странице нет ни одного. На новом сайте фото 49 стоит главным фото первого экрана (`site/src/design/design.json`, раздел heroes; alt "Milwaukee chain snake clearing a kitchen drain line through a wall cleanout, Prosper", грузится сразу), остальные 20 на странице не стоят. Список: 15 (Plano), 38, 39, 40, 204 (Little Elm), 49 (Prosper, chain snake на кухонной линии, отмечено главным фото этой страницы), 53, 96, 130 (Frisco), 57, 58 (Carrollton, до и после), 74 (McKinney), 91, 157 (Plano), 90, 129, 183, 184, 185 (без города), 201 и 203 (Frisco, линия кондиционера врезана в слив раковины).

### 1.5. Ссылки

Со страницы, в тексте 6 внутренних:

| Где | Анкор | Куда |
|---|---|---|
| Вступление | "plumber in Frisco" | `/plumber-frisco-tx/` |
| Вступление | "plumber in Plano" | `/plumber-plano-tx/` |
| Drain Backed Up | "step-by-step DIY guide" | `/plumbing-guide/bathtub-drain-slow-draining-tips-2026/` |
| The Tools We Actually Use | "clearing a clogged kitchen drain with a chain snake on a service call in Frisco" | `/blog/clogged-kitchen-sink-chain-snake/` |
| Заключение | "24/7 emergency plumbing" | `/emergency-plumbing-services/` |
| Заключение, последняя фраза | "plumber near me" | `/` |

Шаблон: 108 внутренних в крауле (меню трижды: 13 услуг, "TOP 5 emergency calls", "General Drain Services", десять городов и прочее; подвал "Frisco Office", "Plano Office"; "Request Service"). Внешних 19: соцсети, восемь `tel:`, "Found us" (share.google), почта, BBB. Внешней официальной ссылки (TSBPE, город, производитель) нет.

Против правил: из десяти городов ссылки только на Frisco и Plano ("Need a plumber in Frisco or a plumber in Plano ? We’re already nearby."), McKinney и Allen названы без ссылки, шесть не названы. Из 12 других услуг ссылка только на emergency. Ссылка на главную "plumber near me" стоит в последней фразе страницы ("Looking for a straight-shooting plumber near me ? That’s us."), а по правилу 6 в последнем абзаце вступления. Пост про chain snake записан как Frisco ("On this Frisco call"), а фото 49, которое архив привязывает и к посту, и к этой странице, по `city_final` из Prosper.

На страницу: шаблон "Drain Cleaning & Unclogging" 189 раз; в тексте 27 ссылок на 25 страницах (таблица в `drain-cleaning-links-to-page.md`). Это главная ("Clogged Drain" и картинка плитки), восемь городских страниц пунктом списка "Slow sinks, tubs, and showers: drain cleaning" (The Colony ещё раз в тексте), Plano ("Drain backups"), Frisco ("shower drains"), `/drain-services/`, `/toilet-repair-frisco-plano/`, `/top-emergency-plumber-calls-frisco/` (строки-подсказки), `/garbage-disposal-repair-frisco-plano/` (анкор "drain" про подключение слива), шесть постов и четыре гайда. Emergency, faucet, water heater, slab leak, leak detection и water lines в тексте сюда не ссылаются.

### 1.6. Что идёт против CLAUDE.md, дословно, и что на новом сайте

**Услуги, которых нет.** Схема Service: "Fast drain cleaning and clog removal in Frisco, Plano & McKinney [длинное тире] from slow sinks to full sewer backups. Licensed plumber, same-day, snaking, chain snake, hydro-jetting and camera inspection." Hydro jetting названо услугой. Новый сайт: схема собрана заново, hydro нет. В тексте tankless, reroute, gas нет.

**Цены и гарантия.** В тексте нет. В схеме `"priceRange": "$$"`. Новый сайт: нет.

**Время приезда и скорость своими словами** (запрещены часы и минуты; "same-day" правилами прямо не запрещено, на главной разрешено в названных местах):
- "Call or text. We’ll show up fast with the right tools." Новый сайт: "We’ll show up with the right tools." Исправлено.
- "Need a plumber in Frisco or a plumber in Plano ? We’re already nearby." Новый сайт: стоит.
- "We Clear Drains Fast" (title), "We Unclog Drains Fast" (H1), "We unclog drains fast ... clean, same-day service" (description). Новый сайт: стоит, и в схеме Service тоже (name повторяет H1, description повторяет описание).
- H2 "Clogged Drain? Let’s Clear It Today": срок «сегодня» своими словами, того же рода, что same-day (часов и минут нет). Новый сайт: стоит.
- "Same-day service, evenings and weekends included" и "We cover Frisco, Plano, McKinney, Allen, and North Dallas, same-day." Новый сайт: "same-day" стоит.
- Не обещание: "a surface clog you can clear yourself in 30 minutes".

**Регион и города.** "...and North Dallas, same-day." Новый сайт: "the North Dallas suburbs". Исправлено. Схема: "surrounding North Dallas communities", `areaServed` только Frisco, Plano, McKinney, Allen, Little Elm. Новый сайт: десять городов и Highland Park, University Park. Запрещённых городов в тексте нет.

**Граница с чужой темой (правило 9), на новом сайте всё стоит:**
- H2 "Why a Camera Inspection Saves You From Clogging Again" и "A sewer camera tells us: • What actually caused the clog • Whether the pipe is cracked, broken, or sagging • Whether roots are growing in". Камера как осмотр трубы по карте ключей у `/drain-services/`; камера при чистке здесь уместна, отдельный раздел про осмотр нет.
- "When roots have cracked the pipe, clearing it isn’t enough. That section has to be replaced or it just clogs again." Замена участка это `/drain-services/`, ссылки на неё нет.
- "Cast iron pipes layered with years of calcium, sludge, and corrosion." Чугун в CLAUDE.md относится к sewer line repair.
- "Sewer smell inside the house" (список признаков). Запах канализации и smoke test у `/drain-services/`.
- "We run a high-def camera after every major clog" и "And always a camera afterward". Денис 2 октября: камера до чистки, когда линия пропускает, и после, когда линия забита.

**Телефоны в тексте.** Нет. Панель шаблона несёт номера тегом H2; на новом сайте такого H2 нет.

**Owner.** Нет, только "Homeowners" в H2.

**FAQ тегами заголовков.** Вопросы не заголовки, но три ответа тегом H2. Новый сайт: вопросы жирным в `summary`, ответы абзацами, одна FAQPage слово в слово. Исправлено.

**Тире.** "We run a high-def camera after every major clog [длинное тире] to prove it’s clear..." и "...or the line’s fully stopped [длинное тире] don’t wait for water on the floor." Новый сайт: двоеточия. H2 "FAQ - Drain Cleaning": новый сайт "FAQ: Drain Cleaning". Длинные тире в схеме: новый сайт без них. Всё исправлено.

**Лозунги, вода, вопросы вместо ответа (на новом сайте всё стоит):**
- Вопросы: title "Clogged Drain? ...", H1 "Sink Won’t Drain? Shower Backed Up? ...", H2 "Drain Backed Up? Here’s How You Know It’s Serious", H2 "Clogged Drain? Let’s Clear It Today", description "Slow sink or sewer backup? ...", "Flooding right now? ...", "Looking for a straight-shooting plumber near me ? That’s us." Правило 4: title и H1 с ключом и городами, без лозунгов.
- "It’s stressful, disgusting, and sometimes a real health hazard."; "we don’t just punch a hole through the clog and run"; "You don’t need to be a plumber to know something’s wrong."; "Without that, your next clog could be days away."; "We tell you the truth, even when it’s not what you want to hear"; "Licensed and insured, no untrained techs in your house"; "We’ve seen the weird stuff, so we know what to look for"; "Most plumbers just want to clear the line and leave. We’d rather you not need us again, until the next thing breaks."
- Нет в фактах Дениса: "get your drains cleaned professionally every year or two"; "We’ve pulled roots longer than 10 feet" (в одобренном тексте "Roots longer than a person").
- Набор: "Wipes , even “flushable” ones" (пробел перед запятой, стоит и на новом сайте).

**Схема, прочее** (новый сайт собрал заново, исправлено): provider `#business` только с адресом и телефоном Plano; "Texas Master Plumber License M-44816"; `legalName` "FPP Plumbing, LLC"; `numberOfEmployees` 1 до 10; крошки "Main"; `og:type` article.

### 1.7. Живая суть, которую стоит взять (пересказом, не дословно)

- "One slow drain is usually a local clog. Two or more at once means the main line, that’s a pro job, not a plunger job." и совет про одну ванну "you can clear yourself in 30 minutes" со ссылкой на гайд.
- "One customer had five different plumbers out. Every one just ran a snake and left, and it kept clogging every week. We put a camera down the line and found a garden trowel sitting in the pipe, catching everything like a net." Совпадает с диктовкой (`source/dictation/2026-10-01-warranty-and-care.md`: из главной линии доставали термос, кружки, "even a small garden shovel").
- "A chain snake spins and scrubs the pipe walls clean, it pulls off grease, scale, and roots a cable just slides past. Light clog, cable’s enough. Built-up gunk or roots, you need the chain."
- Что вытаскивают: wipes ("even “flushable” ones don’t break down"), жир, игрушки, зубные щётки, расчёски, "a Hot Wheels truck".
- Признаки главной линии: "Toilets bubbling or backing up", "More than one fixture draining slow at the same time", "Gurgling sounds from the drains", "Run the washer and the tub floods".

### 1.8. Новый сайт против живой страницы

Файл нового сайта это старый текст, title, description и H1 те же. Пять изменений (`launch-changes.csv`; первое это точечная правка в `tools/build_launch_content.py`, строка 957): "show up fast" убрано; два длинных тире стали двоеточиями; "FAQ - Drain Cleaning" стало "FAQ: Drain Cleaning"; "North Dallas" стало "the North Dallas suburbs". Шаблон (`ServicePage.astro`): noindex; FAQ жирным; одна FAQPage; Service с provider `#organization`; OG title равен title; блок двух отзывов; на первом экране фото 49 (Prosper, из `site/src/design/design.json`, heroes), загрузка сразу; боковой блок «What is happening right now?» (четыре ссылки на emergency, гайд про перекрытие воды, кнопки офисов), он шаблонный и раздел правила 8 в тексте не заменяет; старое фото стоит в теле, `loading="lazy"`.

Одобренный `source/FPP-Drain-Cleaning-Page.docx` (30 сентября) на новом сайте НЕ стоит. В нём title "Drain Cleaning in Frisco & Plano, TX | Clogs Cleared Today", H1 "Drain Cleaning That Clears the Clog and Finds What Caused It", 1,861 слово, 10 H2 (среди них "Kitchen Sink Drain Cleaning", "Main Line Stoppage: Cleared Today", "Camera Inspection After Every Main Line Clearing", "What Drain Cleaning Costs", "Backing Up Into the Tub Right Now?"), 6 вопросов жирным, все десять городов, ссылка на главную во вступлении, ссылки на sewer line repair, toilet, disposal, гайд, пост, emergency. Что в нём задевают более поздние решения: камера после каждой чистки главной линии (H2 "Camera Inspection After Every Main Line Clearing"; Денис 2 октября: до или после, по засору); "when they ask about hydro jetting" (упомянуто не как услуга); в title нет "Clogged Drain", а эти слова держат clogged drain(s) с городами (2.3). Срок в нём тоже словами «today» и «the same day» ("Clogs Cleared Today", "Main Line Stoppage: Cleared Today"), часов и минут нет. Карта ключей пишет "deepen to 3,000+ words", CLAUDE.md около 2,500.

## 2. Search Console

Как считали: скрипт `gsc_drain.py` в `scratchpad/services/drain-cleaning/` рядом с копиями `gsc_plano_lib.py` и `gsc_plano_live.py` (оригиналы не менялись, `tools/gsc_page_table.py` не запускался). Правила как для Plano: запрос «покрыт», когда каждое значимое слово стоит в тексте; in, tx, near, me не считаются; множественное число и clogged приводятся к drain и clog; чужие места, услуги, которых нет, оценочные слова, опечатки отложены. Отличие: страница сервисная, десять городов считаются словами текста. «Чей запрос» по карте ключей и правилу 9. «Карта» по правилу `tools/cannibalization_report.py`: страница Frisco или Plano на месте 3 и выше по запросу без своего города; выгрузка показы карточки от выдачи не отделяет. В ячейках «показы · место · клики».

Второй счёт: модуль csv, разбор строк без него (с остановкой при расхождении) и awk дали одно: 3 мес 29 запросов, 0 кликов, 1,415 показов, место 24.37; 16 мес 114, 0, 12,232, 47.13. Те же числа в `page-query-coverage.csv`. Суммы групп сходятся с итогом.

### 2.1. Итоги

| Период | Запросов | Клики | Показы | Место | Google со скрытыми: клики · показы · место | Доля показов с известным запросом |
|---|---|---|---|---|---|---|
| 3 мес (1 июля до 28 сентября 2026) | 29 | 0 | 1,415 | 24.4 | 0 · 1,577 · 24.8 | 90% |
| 16 мес (31 мая 2025 до 28 сентября 2026) | 114 | 0 | 12,232 | 47.1 | 0 · 12,971 · 46.8 | 94% |

| Группа | 3 мес: запросов · показы · место | 16 мес |
|---|---|---|
| с frisco | 9 · 1,146 · 25.0 | 33 · 6,285 · 38.5 |
| с plano | 4 · 170 · 26.1 | 45 · 5,075 · 61.7 |
| без города | 11 · 82 · 14.8 | 21 · 808 · 22.4 |
| другой город из десяти | 0 | 9 · 29 · 79.7 |
| чужое место | 3 · 3 · 20.3 | 4 · 16 · 40.8 |
| бренд "fpp plumbing" | 1 · 13 · 2.0 | 1 · 18 · 2.2 |
| "site:fppplumbing.com" | 1 · 1 · 27.0 | 1 · 1 · 27.0 |

- Все 29 запросов трёх месяцев есть в шестнадцати, поэтому старый период получается вычитанием: за 13 месяцев до июля 2026 у страницы 10,817 показов, место 50.1, кликов 0.
- По местам, 3 мес: 1 до 3 один запрос (бренд, 13 показов), 3 до 10 пять (7), 10 до 20 восемь (147), 20 до 50 пятнадцать (1,248). 16 мес: 1 до 3 один (18), 3 до 10 семь (12), 10 до 20 десять (1,153), 20 до 50 тридцать (6,466), ниже 50 шестьдесят шесть (4,583).
- С plano за 3 месяца почти ничего: 4 запроса, 170 показов, против 45 и 5,075 за 16. "drain cleaning plano" (1,703 за 16 мес) и "plano drain cleaning" (1,341) в трёх месяцах у страницы нет; "drain cleaning plano tx" (171, место 1.0) и "plano tx drain cleaning" (72, место 1.2) за 3 месяца взяла страница Plano.

### 2.2. Запросы страницы

Кликов нет ни у одного запроса. Первые 30 за оба периода и все запросы: файлы `drain-cleaning-gsc-top30-and-phrases.md`, `drain-cleaning-gsc-table-3m.md`, `drain-cleaning-gsc-table-16m.md`. Первые 10:

| № | 3 мес: запрос | показы · место | 16 мес: запрос | показы · место |
|---|---|---|---|---|
| 1 | drain cleaning frisco | 422 · 22.5 | drain cleaning frisco | 2,244 · 43.4 |
| 2 | frisco drain cleaning | 408 · 23.5 | drain cleaning plano | 1,703 · 67.4 |
| 3 | clogged drain plano | 121 · 23.9 | frisco drain cleaning | 1,568 · 40.4 |
| 4 | frisco tx drain cleaning | 89 · 38.5 | plano drain cleaning | 1,341 · 73.2 |
| 5 | drain cleaning frisco tx | 81 · 34.9 | clogged drains frisco | 804 · 14.8 |
| 6 | blocked drain cleaning frisco | 54 · 19.3 | clogged drain plano | 563 · 27.2 |
| 7 | clogged drain near me | 40 · 11.2 | clogged drains plano | 480 · 40.5 |
| 8 | clogged drain frisco | 36 · 17.3 | drain cleaning | 355 · 27.8 |
| 9 | clogged drain frisco tx | 27 · 35.7 | blocked drain cleaning frisco | 320 · 21.6 |
| 10 | clogged drains plano | 23 · 30.0 | clogged drain frisco tx | 181 · 67.8 |

Дальше за 16 мес заметны чужие темы: "cast iron pipe replacement frisco" (149, место 32.0), "sewer cleaning frisco" (138), "blocked toilet frisco" (112). По словам живого текста: за 3 мес полностью 23 запроса (1,356 показов), частично 2 (55: нет "blocked", "unblocking"), чужое место 3, не покрыт 1 (site:). За 16 мес полностью 76 (11,328), частично 28 (844), не наше 5 (43, hydro jetting), чужое место 4 (16), не покрыт 1.

### 2.3. Что держит каждый заголовок

Заголовок «держит» запрос, когда все значимые слова запроса (и город) стоят в нём.

| Заголовок | 3 мес: запросов · показы | 16 мес: запросов · показы · место | Запросы (16 мес: показы · место) |
|---|---|---|---|
| title | 6 · 236 | 7 · 2,293 · 28.9 | "clogged drains frisco" 804 · 14.8; "clogged drain plano" 563 · 27.2; "clogged drains plano" 480 · 40.5; "clogged drain frisco tx" 181 · 67.8; "drain clog plano" 144 · 29.3; "clogged drain frisco" 91 · 15.3; "clogged drain plano tx" 30 · 56.7 |
| meta description | 1 · 2 | 5 · 64 · 73.2 | "drain service plano" 37 · 89.9; "drain service frisco" 13 · 58.7; "sewer and drain services in plano" 10 · 46.5; "plumber unclog sink" 2 · 8.0; "sewer and drain services plano" 2 · 58.5 |
| H1 | 0 | 0 | ни одного: есть "Unclog" и "Drains", нет "cleaning" и "clogged" |
| H2 "FAQ - Drain Cleaning" | 0 | 1 · 355 · 27.8 | "drain cleaning", фраза целиком |
| остальные шесть H2 и три вопроса FAQ | 0 | 0 | ни одного (в "What Actually Causes a Clogged Drain Line" и "Clogged Drain? Let’s Clear It Today" нет города) |

Слова запросов (16 мес) и где стоят: "drain" 11,268 показов (везде); "cleaning" 8,472 (только H2 FAQ, alt и "We inspect the line after cleaning"); "frisco" 6,285 и "plano" 5,075 (title, description, H1, H2, текст); "clog" 2,807 (title, H2, текст); "sewer" 719 (description, текст); "blocked" 433 (нигде); "replacement" 178, "repair" 125, "cleanout" 63 (нигде, это слова темы `/drain-services/`).

Нельзя потерять: "Clogged Drain" вместе с "Frisco" и "Plano" в title (вся группа clogged drain(s) с городом); фразу "Drain Cleaning" в заголовке (единственное место, где запрос "drain cleaning" стоит целиком; на новом сайте "FAQ: Drain Cleaning"); адрес страницы и пункт меню "Drain Cleaning & Unclogging". H1 сейчас ничего не держит, описание держит мелочь (64 показа).

### 2.4. Целая фраза

Проверены первые 20 запросов обоих периодов, вместе 28 (запросов с кликами нет); таблица в `drain-cleaning-gsc-top30-and-phrases.md`. Целиком на живой странице стоят только два: "drain cleaning" (H2 "FAQ - Drain Cleaning" и alt фото) и "fpp plumbing" (вступление, "At FPP Plumbing, we..."). Ни один запрос с городом не стоит целиком нигде, даже с перестановкой слов: ни "drain cleaning frisco", ни "frisco drain cleaning", ни "clogged drain plano". У "clogged drain near me" слова "Clogged Drain" стоят в title, "near me" там нет.

### 2.5. Другие страницы на запросах про чистку

Запрос «про чистку»: есть drain, clog, unclog, unblock, snake, rooter или auger, и по карте ключей он не чужой (унитаз, измельчитель, водонагреватель, ремонт канализации, камера, чугун, гайд про ванну), не "how to" и "why", не про чужую компанию. На всём сайте: за 3 мес 229 таких запросов и 7,504 показа, у этой страницы 1,392 (19%) по 26 запросам; за 16 мес 478 и 40,062, у этой 10,921 (27%) по 61. Клики по ним на всём сайте: за 3 мес 3 (главная "plumber to clean drains", быстрая ссылка главной, пост про chain snake), за 16 мес 5 (те же три, главная "drain cleaning the colony tx", Frisco "drain cleaning frisco"); у этой 0.

| Страница | 3 мес: запросов · показы · место | выше этой | этой нет | «карта» | 16 мес: запросов · показы · место | выше этой | этой нет | «карта» |
|---|---|---|---|---|---|---|---|---|
| `/` | 19 · 140 · 8.1 | 2 · 52 | 17 · 88 | 0 | 233 · 9,373 · 25.4 | 27 · 3,716 | 196 · 2,636 | 0 |
| `/plumber-frisco-tx/` | 51 · 2,440 · 4.1 | 10 · 220 | 41 · 2,220 | 18 · 1,917 | 60 · 3,847 · 18.4 | 13 · 1,996 | 43 · 1,310 | 19 · 990 |
| `/plumber-plano-tx/` | 123 · 2,541 · 2.1 | 9 · 140 | 113 · 2,391 | 65 · 1,791 | 140 · 3,446 · 18.7 | 18 · 1,184 | 115 · 1,719 | 65 · 1,791 |
| `/plumber-the-colony-tx/` | 13 · 466 · 9.9 | 2 · 45 | 11 · 421 | 0 | 23 · 3,710 · 28.4 | 6 · 812 | 17 · 2,898 | 0 |
| `/drain-services/` | 7 · 77 · 43.6 | 0 | 4 · 19 | 0 | 50 · 2,641 · 70.9 | 5 · 731 | 27 · 1,317 | 0 |
| `/plumber-lewisville-tx/` | нет | | | | 10 · 1,550 · 80.6 | 0 | 10 · 1,550 | 0 |
| `/plumber-little-elm-tx/` | 6 · 57 · 27.3 | 0 | 6 · 57 | 0 | 10 · 1,381 · 62.0 | 0 | 10 · 1,381 | 0 |
| `/plumber-mckinney-tx/` | нет | | | | 10 · 743 · 72.6 | 1 · 182 | 8 · 557 | 0 |
| `/plumber-allen-tx/` | 1 · 1 · 22.0 | 0 | 1 · 1 | 0 | 9 · 733 · 52.3 | 1 · 85 | 8 · 648 | 0 |
| `/emergency-plumbing-services/` | 5 · 32 · 10.7 | 1 · 18 | 4 · 14 | 0 | 16 · 314 · 41.1 | 2 · 148 | 13 · 164 | 0 |
| `/blog/clogged-kitchen-sink-chain-snake/` | 30 · 134 · 34.0 | 0 | 30 · 134 | 0 | 39 · 199 · 40.1 | 0 | 39 · 199 | 0 |
| гайд про ванну | 16 · 44 · 40.9 | 0 | 16 · 44 | 0 | 17 · 52 · 42.1 | 0 | 17 · 52 | 0 |

(«нет»: за 3 мес у страницы ни одного такого запроса. Остальные страницы мельче, числа в файлах.)

Самые крупные строки (полностью в `drain-cleaning-gsc-other-pages-3m.md` и `-16m.md`):
- 3 мес, "drain cleaning": Frisco 1,054 · 2.8, Plano 761 · 1.5, обе «карта»; этой нет. "plumbing clog": Frisco 782 · 1.0, Plano 336 · 1.0, «карта».
- 3 мес, "drain cleaning frisco": Frisco 57 · 6.1 и Plano 25 · 6.8 против этой 422 · 22.5; "frisco drain cleaning": Frisco 60 · 9.4 против 408 · 23.5. Страница Frisco выше по главному ключу этой страницы.
- 3 мес: "drain cleaning plano tx" Plano 171 · 1.0; "the colony tx drain cleaning" The Colony 138 · 10.9; "emergency drain cleaning frisco" главная 60 · 8.4; этой нет.
- 16 мес, "drain cleaning": главная 2,218 · 1.2 и Frisco 1,540 · 5.3 против этой 355 · 27.8.
- 16 мес, "drain cleaning frisco": выше этой (2,244 · 43.4) стоят `/drain-services/` 715 · 39.0, Frisco 97 · 14.5 (1 клик) и Plano 25 · 6.8; главная 974 · 66.2 ниже. "drain cleaning frisco tx": главная 753 · 64.3 против 140 · 58.4. "emergency drain cleaning frisco": главная 453 · 7.5 против 42 · 30.5.
- 16 мес, "drain cleaning mckinney" `/drain-services/` 660 · 93.9 и "mckinney drain cleaning" 466 · 87.9, этой нет (пункт 6 в `seo/cannibalization-findings.md`). "the colony drain cleaning": The Colony 553 · 29.3 против этой 5 · 69.6.

Обратная сторона: запросы этой страницы, которые по карте ключей принадлежат другим (16 мес, показы · место; за 3 мес осталось только "clogged toilet plano" 9 · 22.2 и бренд):

| Чей | Запросы |
|---|---|
| `/drain-services/`, 10 запросов, 279 показов | "cast iron pipe replacement frisco" 149 · 32.0; "cast iron drain pipe repair frisco" 46 · 34.6; "cast iron pipe repair frisco" 40 · 34.4; "main sewer line replacement frisco" 14 · 59.1; "plano drain inspection" 11 · 82.5; "sewer replacement frisco" 10 · 76.0; ещё 4 по 1 до 5 |
| `/toilet-repair-frisco-plano/` (правило 9), 9 запросов, 185 | "blocked toilet frisco" 112 · 20.4; "clogged toilet plano" 53 · 24.3; "toilet frisco" 10 · 90.7; ещё 6 по 1 до 3 |
| спорно, чистка канализации (карта прямо не называет), 19 запросов, 687 | "sewer cleaning frisco" 138 · 54.0; "sewer drain cleaning in plano" 107 · 67.3; "sewer line clean out plano" 81 · 80.4; "sewer drain cleaning plano" 61 · 75.1; "frisco sewer line backup" 58 · 20.4; "sewer line clean out in plano" 55 · 81.0; остальные мельче |
| спорно, слова как у `/drain-services/` ("General Drain Services" в меню), 4 запроса, 70 | "drain service plano" 37 · 89.9; "drain company frisco" 19 · 70.0; "drain service frisco" 13 · 58.7; "drain service the colony" 1 |
| не наше, hydro jetting, 5 запросов, 43 | "hydro jetting frisco" 29 · 49.7; "hydrojetting plano" 10 · 58.6; ещё 3 по 1 до 2 |
| ничей по карте, ближе `/water-lines/` | "pipe breaks frisco" 17 · 69.9; "pipe breaks plano" 7 · 90.6 |
| `/fixture-installation-repair/` | "plano shower repair" 3 · 68.3 |
| бренд | "fpp plumbing" 18 · 2.2; "site:fppplumbing.com" 1 · 27.0 |

### 2.6. Чистка с каждым из десяти городов

Запросы «про чистку» (как в 2.5) с названием города, все страницы сайта.

| Город | 3 мес: запросов · показы | 3 мес: эта (показы · место) | 3 мес: больше всех | 16 мес: запросов · показы | 16 мес: эта (показы · место · запросов) | 16 мес: больше всех (показы · место) |
|---|---|---|---|---|---|---|
| Frisco | 15 · 1,723 | 1,146 · 25.0 | эта; `/plumber-frisco-tx/` 272 · 8.2 | 25 · 12,134 | 5,606 · 38.3 · 16 | эта; `/` 3,915 · 52.8; `/drain-services/` 1,115 · 46.6 |
| Plano | 21 · 640 | 161 · 26.4 | `/plumber-plano-tx/` 479 · 2.2; эта | 47 · 6,894 | 4,466 · 59.9 · 15 | эта; `/plumber-plano-tx/` 1,380 · 43.6; `/` 782 · 16.3 |
| McKinney | 1 · 1 | нет | `/drain-services/` 1 · 18.0 | 17 · 2,022 | 6 · 74.7 · 2 | `/drain-services/` 1,182 · 90.7; `/plumber-mckinney-tx/` 743 · 72.6 |
| Allen | 1 · 1 | нет | `/plumber-allen-tx/` 1 · 22.0 | 9 · 734 | 1 · 66.0 · 1 | `/plumber-allen-tx/` 733 · 52.3 |
| Prosper | 2 · 3 | нет | по 1 показу у трёх страниц | 4 · 116 | нет | `/plumber-prosper-tx/` 114 · 58.6 |
| Celina | 0 | нет | нет | 4 · 180 | нет | `/plumber-celina-tx/` 180 · 28.7 |
| Little Elm | 6 · 57 | нет | `/plumber-little-elm-tx/` 57 · 27.3 | 9 · 1,581 | нет | `/plumber-little-elm-tx/` 1,380 · 62.0; пост Little Elm 170 · 52.3 |
| The Colony | 9 · 437 | нет | `/plumber-the-colony-tx/` 390 · 10.8; `/plumber-plano-tx/` 45 · 1.2 | 20 · 4,504 | 19 · 82.4 · 3 | `/plumber-the-colony-tx/` 3,634 · 28.9; `/` 587 · 1.2 (1 клик) |
| Carrollton | 2 · 13 | нет | `/plumber-plano-tx/` 12 · 1.0 | 5 · 45 | нет | `/` 20 · 1.0; `/plumber-carrollton-tx/` 13 · 78.6 |
| Lewisville | 1 · 19 | нет | `/plumber-plano-tx/` 19 · 1.0 | 11 · 1,583 | нет | `/plumber-lewisville-tx/` 1,550 · 80.6 |

Итог: страница видна только с Frisco и Plano, на местах 25 до 60. С восемью другими городами её нет или почти нет: там стоят городские страницы, на McKinney `/drain-services/`. В карте ключей строка поста про Little Elm прямо отдаёт "little elm drain cleaning" странице Little Elm. Больше всего показов после Frisco и Plano у The Colony (4,504 за 16 мес), там эта страница 19 показов на месте 82.4.

### 2.7. Слова, которые на страницу не идут

| Что отложено | Запросы | Показы 3 мес | 16 мес |
|---|---|---|---|
| near me (на странице один раз, анкор "plumber near me" в конце) | clogged drain near me; clogged drain service near me; clogged drain plumber near me; drain cleaning near me; clogged drain cleaning service near me; main drain cleaning near me; clogged sink drain near me; bathtub drain clogged near me; unclog drain near me | 74 | 338 |
| hydro jetting (как услугу не называем) | hydro jetting frisco; hydrojetting plano; hydro jetting plano; plano hydro jetting; hydro jetting little elm | 0 | 43 |
| чужие места | drain cleaning silverthorne (9); clogged drain removal lily lake (5); blocked drains chifley (1); clogged drain addison (1) | 3 | 16 |
| бренд и служебный | fpp plumbing; site:fppplumbing.com | 14 | 19 |
| оценочное слово | clogged toilet cost plano tx ("cost") | 0 | 1 |

Опечаток нет. Не отложено, но на странице отсутствует: "blocked" (55 показов за 3 мес, 433 за 16) и "unblocking" (1). "replacement", "repair", "cleanout", "cast iron" это слова темы `/drain-services/`.
