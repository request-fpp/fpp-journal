# Бриф страницы Lewisville (3 октября 2026)

Страница: /plumber-lewisville-tx/ . Собрано 3 октября 2026, около 11:00, из файлов разделов в папке `docs/briefs/lewisville/`. Страница этой ночью не переписывалась: текст напишет другой чат из этого брифа и из диктовки Дениса. В проекте ничего не менялось, кроме этого нового файла.

Как устроен файл. Части 1, 2, 3, 5, 6 и 8 это файлы разделов, вставленные целиком скриптом, слово в слово: первая строка файла (его заголовок) названа в начале части, остальные заголовки опущены на уровень ниже, в части 6 на два уровня, потому что там четыре файла. Части «Коротко», 4, 7, 9 и 10 написаны при сборке. Читать стоит «Коротко», потом части 9 и 10, остальное открывать по делу.

Оговорки к вставленным файлам:

- Слова «рядом», «файл таблиц», «приложение» во вставленных текстах значат папку `docs/briefs/lewisville/`. Длинные таблицы в бриф не вставлены: их имена названы в начале каждой части.
- Номера разделов внутри вставленных файлов («раздел 5», «пункт 6», «вопрос 3», «часть E») относятся к самому файлу, не к частям брифа.
- Часть 6. Файлы фактов писались первыми, перепроверка шла после них, другими помощниками и своими запросами. Где они расходятся, верить спискам 6.0 и таблицам проверки (6.3 и 6.4). Списки «что можно брать» и «чего нельзя» из двух файлов проверки переставлены в начало (6.0), остальное из этих файлов стоит в 6.3 и 6.4; ни одна строка не убрана. Там, где первый файл расходится с перепроверкой, при сборке в строку добавлена пометка «[Сборка: ...]»; сам текст не менялся.
- Координаты. В файле `6b-zip-and-age.md` одна строка называла центры участков индексов цифрами широты и долготы; в брифе эти цифры заменены пометкой «[Сборка: ...]». Точку офиса Plano из старой схемы бриф тоже не повторяет. Больше координат во вставленных файлах нет (проверено поиском при сборке).
- Телефоны и адреса во вставленных файлах: 469-998-8999 и 980-899-7997 (на фургоне "980.899.7997") это номера FPP; 972-464-2460 в title конкурента в части 3 это телефон компании Berkeys; 972.219.3470 в части 6 это телефон города, названный как то, что на страницу не переносится. Адреса: офисы FPP, офис компании Imperial в части 3. Адресов и телефонов клиентов в брифе нет.
- Отзывы в частях 1 и 5 даны дословно, с опечатками авторов; цифры приезда в них это слова клиентов, по решению Дениса их не трогаем.
- Файлы отзывов (`reviews/site-reviews.json`, `reviews/site-ledger.md`) этой ночью пересобирают: перед выбором отзывов прочитать их ещё раз. При сборке (около 10:55 3 октября, файл от 10:04) в `site-reviews.json` 14 страниц, ключа страницы Lewisville нет.
- Сайт города cityoflewisville.com отвечает 403 на все запросы помощников; страницы и памятки города прочитаны в копиях Internet Archive (статус could_not_open). Законы города прочитаны напрямую в своде Municode. Пункты «архив» утром сверить в обычном браузере.

Что сверено при сборке заново (3 октября 2026): итоги страниц Lewisville, Frisco и Plano в `source/gsc/performance-3m/Pages.csv` и `performance-16m/Pages.csv`; шесть главных запросов Lewisville за 3 месяца в `source/gsc/page-query-3m.csv` (все совпали с частью 2); 204 записи архива фото в `docs/briefs/_shared/photos-by-city-after-recount.json` (за Lewisville ни одной); файл новой страницы `site/src/content/pages/plumber-lewisville-tx.md`, шаблоны `ServicePage.astro`, `CallButtons.astro`, `Header.astro`, `Callbar.astro`, `site/src/lib/schema.ts`; подвал и разметка живой страницы в `source/crawl/html/plumber-lewisville-tx.html`.

## Коротко

1. Что кормит страницу. За 3 месяца (1 июля до 28 сентября 2026) 2 клика, 3,531 показ, среднее место 25.74; за 16 месяцев те же 2 клика, 63,896 показов, место 50.88 (`source/gsc`, Pages.csv). Оба клика пришли в последние 3 месяца и оба по скрытым запросам: у запросов, которые Google называет, кликов ноль. Место выросло (52.5 за 13 месяцев до июля, 25.9 за последние 3), показов в месяц стало намного меньше (с известным запросом около 4,490 в месяц за 13 месяцев до июля, 58,315 всего, против около 1,080 в месяц за последние 3, 3,244 всего; часть 2, раздел 1).
2. По каким запросам. 88 процентов показов с известным запросом идут по запросам со словом lewisville (2,867 из 3,244 за 3 месяца, 97 запросов). Лучшие места у slab leak repair с городом: «slab leak repair lewisville» 200 показов на месте 9.6, «slab leak repair lewisville tx» 152 на 9.5, «lewisville slab leak repair» 105 на 9.0; вся группа slab leak 762 показа, место 10.7. Leak detection с городом 312 показов, место 19.6. Главные запросы города стоят на местах 33 до 42: «plumber lewisville tx» 152 на 33.4, «plumber lewisville» 113 на 34.3.
3. Что нельзя потерять: начало title "Plumber Lewisville, TX"; слова "Slab Leaks" и "Repair" в title (только title держит 10 запросов, 698 показов за 3 месяца, это лучшие места страницы); начало H1 "Plumber in Lewisville, TX"; "Licensed Lewisville plumbers" в описании; H2 "Lewisville Plumbing FAQ" и "Our Plumbing Services in Lewisville"; "FPP Plumbing" в заголовке отзывов; текст ссылок "leak detection" и "plumber near me", слово emergency в тексте. "Faucet Repair" в title держит 94 показа за 3 месяца и 3,116 за 16, а карта ключей запрещает этой странице faucet repair: решает Денис.
4. Дыры по запросам: фраз "plumber in Lewisville" и "Lewisville plumber" в абзацах нет совсем (только H1 и описание); emergency с городом (127 показов за 3 месяца, 5,635 за 16) не держит ни один заголовок; hose bib на странице не назван; пять H2 из восьми не держат ни одного запроса.
5. Что на живой странице против правил: в схеме второй бизнес "FPP Plumbing - Plumber in Lewisville, TX" с адресом и телефоном офиса Plano, в его areaServed Flower Mound и Highland Village (на сайте не называются) и соседи The Colony и Carrollton, "Texas Master Plumber License M-44816", "surrounding North Dallas communities", priceRange "$$"; вопрос FAQ "How fast can you get to Lewisville?" с ответом "Same day for most calls"; закрывающая строка "Fast, clean, and honest."; "thirty or forty dollars a month" и "fifteen years" не от Дениса; шесть вопросов FAQ тегом H3, три из них шаблонные; ссылка на главную не во вступлении; нет ссылок на hose bib и expansion tank; якорь "main line service"; камера только после чистки; обрезанный отзыв John Wilson; нет официальной ссылки. На новом сайте уже поправлены тире в H1, вопросы FAQ (шаблон выводит их жирным текстом, не заголовками) и схема (один бизнес на сайт, лицензия словами "Responsible Master Plumber, License M-44816", у узла Service страницы areaServed только Lewisville); весь остальной текст стоит как было.
6. Чего на живой странице нет: улиц, районов, ориентиров, фото с работы, историй с вызовов, блока Дениса, слова об офисе. Своего текста 1,253 слова, до отметки 2,500 не хватает около 1,250. Главное фото это фургон у кирпичного дома с телефоном Plano на борту и "M-38532" спереди, alt пустой, где снято, неизвестно.
7. Конкуренты: десять страниц из выдачи по «plumber lewisville tx», «plumber in lewisville», «lewisville plumbing» (Semrush, 3 октября 2026); нашей страницы в первых 30 по этим трём запросам нет. Основной текст от 334 до 2,714 слов, середина около 1,090; наша нынешняя страница длиннее восьми из десяти. Самые местные: Legacy (13 ссылок на сайт города, вода, Castle Hills, дома 1960 до 1980) и Mother (четыре района, 23 отзыва с подписью Lewisville).
8. Чего нет ни у одного из десяти: PSI на манометре и места PRV, ящика счётчика, что смотрит инспектор, тоннеля и пайки под плитой, глины, cleanout и smoke test, спринклеров, мороза в своём тексте, поддона под баком на чердаке, слива кондиционера в раковину, платы за вызов в цифрах, настоящих историй с вызовов, человека с лицом. Что у них есть, а нам нельзя: tankless у девяти, hydro jetting у пяти, repiping у четырёх, рассрочка или клубная карта у пяти, гарантия со сроком у Mother.
9. Фото и клипы: после пересчёта за Lewisville в архиве 0 фото и 0 клипов. Денис 1 октября разрешил ставить фото фургона у офиса Frisco (2 и 4) временной заменой, alt без слова Frisco: 2 уже главное фото страницы Frisco, 4 нигде не стоит. Девять старых фото галереи с "in Lewisville, TX" в alt лежат вне архива, город не проверен.
10. Отзывы: Lewisville не называет ни один из 407 отзывов архива. Свободных пятизвёздочных с текстом 330, все правила проходят 147, работу называют 29. С живой страницы проходят John Wilson (только полным текстом) и Allen Thong; Serge Geshka называет Дениса ("Dennis"). Свободного отзыва про slab leak нет. На новом сайте блок отзывов этой страницы пуст.
11. Официальные факты, подтверждённые двумя проходами (3 октября 2026): сантехник регистрируется в городе, без платы, без регистрации разрешений не дают; кодексы IPC и IRC 2021 года с поправками города; разрешение и "Plumbing Final" на водонагреватель, поправки города (18 дюймов в гараже, поддон, сброс T&P, доступ на чердак); от счётчика до дома отвечает хозяин; канализация: засор до врезки прочищает хозяин, ремонт хозяин до края тротуара, дальше город бесплатно после проверки камерой лицензированного сантехника (закон 16-99, 16-100); пересчёт счёта после скрытой течи (16-300); сигнал "Suspected Leak" умного счётчика; жёсткость 158.5 ppm (отчёт 2024 года, архивная копия). Неверны в первом прогоне два пункта: city-h1 и city-h4. Для одной официальной ссылки годится статья о регистрации подрядчиков в своде законов Municode.
12. Индексы и возраст домов: почтовые индексы Lewisville с доставкой 75057, 75067, 75077; 75029 только ящики; 75056 это почта The Colony, но в нём около четверти площади города (вопрос Денису). Медианный год постройки жилья 1997 (±1), старое ядро 75057 (52.8% домов на одну семью построены до 1980 года), по городу до 1980 года построен 21.0% домов на одну семью (Census, ACS 2020-2024).
13. Ссылки: ни одного поста или гайда с работой в Lewisville; на страницу в тексте ссылаются 5 страниц нового сайта, девять страниц услуг из 13 на неё не ссылаются. Начало фразы со ссылкой на главную ("If you searched for a plumber near me") занято на других городских страницах.
14. Офис: офиса в Lewisville нет, и CLAUDE.md не говорит, какой из двух офисов обслуживает город. Старая схема пишет Plano; новый сайт показывает две кнопки звонка (Frisco office, Plano office), без блока офиса и карты. Вопрос Денису.
15. Чего не хватает для сильной страницы: диктовки Дениса про Lewisville (в `source/dictation` нет ни слова), одной или двух настоящих работ из города с фото, его ответа про офис, про slab leaks и возраст домов, про "Faucet Repair" и "same day", выбора отзывов, кадра работы или фургона в городе.

## 1. Живая страница

Файл раздела: `docs/briefs/lewisville/1-live-page.md`, вставлен целиком. Заголовок файла: «1. Живая страница Lewisville: что стоит на fppplumbing.com сейчас».

Полные таблицы в бриф не вставлены, они лежат рядом: `1-live-page-tables.md` (18 КБ): ссылки со страницы (A), ссылки на неё (B), схема (C), фото с подписью Lewisville на других страницах (D), ответы FAQ слово в слово (E), ссылки отзывов и ответы компании (F).

Откуда данные. Краул от 30 сентября 2026: `source/crawl/pages/plumber-lewisville-tx.json`, код `source/crawl/html/plumber-lewisville-tx.html` (остальные 63 страницы там же). Отзывы: `reviews/all-reviews.csv`, `reviews/site-ledger.md` и `reviews/site-reviews.json` (прочитаны 3 октября в 10:09 и 10:18), `reviews/ledger.md`, `reviews/ledger-decisions.csv`. Правки: `tools/build_launch_content.py`, `site/src/data/launch-changes.csv`, `site/src/content/pages/plumber-lewisville-tx.md` (версия 10:04). 3 октября в 10:11 живая страница запрошена один раз: title, описание, H1, все H2 и H3, авторы отзывов и спорные фразы как в крауле.

Таблицы рядом, `1-live-page-tables.md`: ссылки со страницы (A), ссылки на неё (B), схема (C), фото с подписью Lewisville на других страницах (D), ответы FAQ (E), ссылки отзывов (F).

Страница: https://fppplumbing.com/plumber-lewisville-tx/ , 200, в page-sitemap.xml, canonical на себя, "index, follow". Опубликована 16 мая 2025, правлена 17 августа 2026. План (`docs/pages-plan.md`, группа 3, № 10): 3,531 показ, место 25.7, 2 клика, «Старый текст». `seo/keyword-map.md`: ключ "plumber lewisville tx", чужое "faucet repair (faucet page)".

### 1. Title, описание, H1, заголовки, объём

- Title (64 знака): "Plumber Lewisville, TX | Water Leaks, Slab Leaks & Faucet Repair"
- Description (134): "Bill jumped and nothing looks wet? Floor warm in one spot? Faucet dripping for months? Licensed Lewisville plumbers who find it first."
- H1: "Plumber in Lewisville, TX - Finding Leaks Before They Find Your Floors" (дефис с пробелами на месте тире)
- OG title как title, og:type "article", OG картинка: фургон `/wp-content/uploads/2025/05/photo_2025-05-15_20-41-52.jpg`

H2 по порядку (слов в разделе с заголовком):

1. "Water Leaks You Cannot See" (195)
2. "Slab Leaks in Older Lewisville Homes" (210)
3. "Faucets, Valves, and Parts That Have Simply Aged" (130)
4. "Our Plumbing Services in Lewisville" (102, десять строк со ссылками)
5. "Drains That Keep Coming Back" (86)
6. "When It Cannot Wait" (76)
7. "Lewisville Plumbing FAQ" (322)
8. "What Lewisville Homeowners Say About FPP Plumbing" (186, отзывы)
9. "980-899-7997 469-998-8999" (не раздел: телефоны нижней панели тегом H2, шаблон старого сайта)

H3: шесть, все это вопросы FAQ.

Объём. Краул: 1,458 слов (от H1 до кнопки "Request Service"). Свой текст от H1 до конца FAQ: 1,253 (H1 12, вступление 120). Отзывы 186 (сами тексты 129), закрывающая строка 17. До 2,500 не хватает около 1,250.

Ключи. "Lewisville" 10 раз: H1, четыре H2, два вопроса FAQ, в абзацах три раза ("Most leaks in Lewisville are discovered by a bill, not by a puddle.", "In most Lewisville homes we go under the house rather than through it.", закрывающая строка). "plumber in Lewisville" 1 (только H1). "Lewisville plumber", "plumbers in Lewisville" 0 (в описании "Lewisville plumbers"). "plumber near me" 1 (ссылка на главную). "same day" в своём тексте 1 (FAQ 6).

### 2. Шесть вопросов FAQ

Все шесть тегом H3 в раскрывающемся списке Elementor (`details`, `summary`); по правилу 8 это жирный текст. Ответы слово в слово: таблицы, часть E. Схема FAQPage совпадает со страницей.

| № | Вопрос (H3), слово в слово | Где такой вопрос ещё |
|---|---|---|
| 1 | "My water bill jumped but I cannot find anything wet. What now?" | Только здесь. Та же тема у гида `/plumbing-guide/why-is-my-water-bill-so-high-frisco-tx/` и у leak detection |
| 2 | "How much does a plumber cost in Lewisville, TX?" | ШАБЛОН: на всех девяти остальных городских страницах с их городом; ответ слово в слово тот же на Little Elm, Prosper, The Colony |
| 3 | "Can a slab leak be repaired without tearing up my floors?" | Только здесь (близкий на McKinney: "Do you locate a slab leak before opening the floor?") |
| 4 | "The shutoff valve under my sink will not turn. Is that a problem?" | Только здесь (близкий на emergency: "My shut-off valve will not turn. What now?"); тема замороженного гида angle stop |
| 5 | "Do you charge extra after hours?" | ШАБЛОН: Allen, Carrollton, Celina, Little Elm, McKinney, Prosper, The Colony (ответы другие) |
| 6 | "How fast can you get to Lewisville?" | ШАБЛОН: "How fast can you get to The Colony?"; похожие "How quickly can you get to Prosper?", "How fast can you get here?" (emergency) |

Единственные на сайте: 1, 3, 4. Вопросов про сам город нет.

### 3. Три отзыва на живой странице

Над карточками: "Real Google reviews from people who called us about a leak." Все три есть в `reviews/all-reviews.csv` (Google, 5 звёзд, `on_old_site` = эта страница). Ни один не занят: их нет среди двенадцати главной, в `site-ledger.md` (40 авторов), в `site-reviews.json`, в резерве главной. Копий на Thumbtack с пометкой "copy of a Google review" нет. Ссылки архива и ответы компании: таблицы, часть F.

**Allen Thong**

- Текст: "Washer valve box and pipe cutting/replacement - Reasonable price, great service, good attitude!"
- Подпись: "★★★★★ · Local Guide Level 2 · April 2026 · Google". Ссылка: https://maps.app.goo.gl/7MgJj5Q4WgkF2YhX9?g_st=ic (проверена 3 октября одним запросом: тот же отзыв, что в архиве).
- Архив: профиль Frisco, 2026-04-02. Текст совпадает (в архиве только перенос строки после "cutting/"). Месяц совпадает. Уровень в архиве пустой: "Level 2" не подтверждён.
- Новый сайт: нигде, свободен. Короткий, без города и без названия компании; дефис внутри это слова клиента.

**John Wilson**

- Текст на странице: "I had a non emergency leak that required a difficult repair on my service line in the front yard. The technician came out to the house that same day and assessed what work was required and gave me the quote for labor. I was told that parts were separate and would provide me with receipts for the parts required. Repairs were made the following day."
- Подпись: "★★★★★ · Local Guide Level 4 · May 2025 · Google". Ссылка: https://share.google/6UeA9a8BMDHElnvdl (по `ledger-decisions.csv` ведёт на отзыв архива).
- Архив: профиль Plano, 2025-05-29. Текст НЕ совпадает: в архиве "Repairs were made the following day with minimal outage time. The technician was very professional and friendly while answering and addressing all my questions and concerns." На странице предложение оборвано, поставлена точка, последнее предложение убрано, в самом коде. Правило 11: на новом сайте только полный текст. Уровень в архиве пустой.
- Новый сайт: нигде, свободен. На Thumbtack есть "John W." (2022-12-18) с другим текстом, копией не помечен; тот же ли человек, файлы не говорят. Тема: водяная линия во дворе; "same day" это слова клиента.

**Serge Geshka**

- Текст: "Had a great experience with FPP Plumbing. I called them for a supply line leak, and Dennis was quick to respond. He was very knowledgeable, professional, and polite throughout the process. The repair was done efficiently, and I really appreciated the quality of service. Highly recommend them for any plumbing needs!"
- Подпись: "★★★★★ · Local Guide Level 4 · March 2025 · Google". Ссылка: https://share.google/blkZEJ45doQ4PSvrt (по `ledger-decisions.csv` ведёт на отзыв архива).
- Архив: профиль Plano, 2025-03-27. Текст совпадает знак в знак, месяц совпадает. Уровень в архиве пустой.
- Новый сайт: нигде, свободен. Есть "FPP Plumbing" и "supply line leak", но и "Dennis" (Денис по имени, с ошибкой); по решению для Frisco отзыв городской страницы говорит о компании, не о Денисе.

Общее:

- Города нет ни в одном. Во всём архиве (407 строк) слова "Lewisville" и индексов 75057, 75067, 75077, 75056 нет ни в отзыве, ни в ответе, ни в пометке. Профили: один Frisco, два Plano; что работы были в Lewisville, не подтверждено. Отзыв Allen Thong не про течь, хотя строка над блоком говорит "about a leak".
- В подписях города нет: по правилу 11 верно.
- На новом сайте ключа страницы в `site-reviews.json` нет, `ReviewCards` при пустом списке ничего не выводит: блока отзывов нет, хотя в файле страницы остались `reviews_heading` и `reviews_intro`.
- По `reviews/proposed-placement.md` переписанная городская страница сохраняет своих авторов. Все трое доступны.

### 4. Фото на живой странице

Семь тегов картинок; фото с работы, видео и карты нет.

- `/wp-content/uploads/2025/05/photo_2025-05-15_20-41-52-1024x576.jpg`, alt пустой: главное фото под H1, OG и primaryImage. Не с работы. Копию я открыл (`site/public/wp-content/uploads/2025/05/photo_2025-05-15_20-41-52-w960.webp`): белый фургон FPP у бордюра, за ним кирпичный двухэтажный дом; на борту "EMERGENCY SERVICE 24/7", "FULLY LICENSED & INSURED", "980.899.7997" (линия Plano), "EXPERT PLUMBING SOLUTIONS", спереди "M-38532". Номерного знака и номера дома не видно. Где снято, неизвестно. Вопрос про "M-38532" уже есть в `docs/morning-report-2026-10-03.md`.
- Логотип 2 раза ("FPP Plumbing Logo"), заглушка Elementor 3 раза (аватары отзывов, alt пустой), знак BBB ("FPP Plumbing, LLC BBB Business Review").

Архив проекта: за Lewisville 0 фото и 0 клипов (`docs/briefs/_shared/cities-free-photos-2026-10-03.md`). В `photos/captions-en.csv` фото 2 и 4 (фургон у офиса Frisco) записаны временной заменой для Celina и Lewisville "until job photos from there (Denys, October 1, 2026)", alt без слова Frisco; на новой странице их пока нет. На других страницах старого сайта 9 подписей "in Lewisville, TX" (8 в галерее, одна ещё на PRV); этих файлов нет в `photos/index.csv`, город держится только на старом alt (таблицы, часть D).

### 5. Ссылки

Со страницы в тексте 16 внутренних, внешних нет (часть A1): "leak detection" и "plumber near me" (главная) в первом разделе, "slab leak repair" во втором, "angle stop guide" в третьем (после ссылки нет пробела: "guide</a>explains"), десять в списке услуг, "shut-off guide" и "emergency plumbing" в "When It Cannot Wait".

- Из 13 услуг в тексте 11; нет `/hose-bib-repair-frisco-plano/` и `/water-heater-repair-frisco-mckinney/` (Expansion tank replacement).
- Ссылка "plumber near me" стоит в третьем абзаце первого раздела, не в последнем абзаце вступления (правило 6).
- Официальной внешней ссылки нет.

На страницу (часть B): ссылаются 62 страницы из 63 (кроме `/blog/author/admin/`). Анкоры: "Lewisville" 189 (меню, по 3 на страницу), "plumber in Lewisville" 3, "Lewisville, TX" 1, полное название 1. В тексте: emergency, slab leak и leak detection ("plumber in Lewisville" в перечнях всех городов), старая главная, contact и `/water-heater-repair-frisco-mckinney/` (списки городов). Все шесть ссылаются из перечней или списков городов. В схеме город назван ещё на 13 страницах.

### 6. Что идёт против CLAUDE.md, дословно

Нет: "tankless", "reroute", "hydro", "jetting", "warranty", "guarantee", "Owner"; телефонов в абзацах и FAQ; других городов в тексте; "Dallas".

Офис, которого в Lewisville нет:

- Схема: отдельный `["LocalBusiness","Plumber"]` "FPP Plumbing - Plumber in Lewisville, TX" с адресом, телефоном и точкой офиса Plano ("5700 Tennyson Pkwy, Suite 300") и часами 24/7. По правилу бизнес один, город без офиса только в `areaServed`.
- Описание: "Licensed Lewisville plumbers who find it first."

Время в своих словах (часов и минут нет):

- FAQ 6: "How fast can you get to Lewisville?" и "Same day for most calls, and we schedule a real window rather than a half day guess. Anything actively leaking moves ahead of scheduled work." "same day" Денис разрешил на главной; для городов решения нет.
- Закрывающая строка: "Plumber needed in Lewisville? Call or text us and we’ll get it done. Fast, clean, and honest."
- По правилу: "You call, a real person takes the details and holds you a window..." и "anything actively running goes ahead of everything else on the board." В отзывах время это слова клиентов.

Цены и числа:

- "$49" (FAQ 2), FAQ 5 и "the after hours fee is quoted before we leave" по правилу.
- "a leak that adds thirty or forty dollars a month has been running long enough to matter, and it will not stop on its own." Сумма, которую никто не давал.
- Схема: `priceRange` "$$".

Города (только в схеме):

- `areaServed`: "Lewisville", "Flower Mound", "The Colony", "Carrollton", "Highland Village". Flower Mound и Highland Village не из десяти (в FORBIDDEN_CITIES проекта); The Colony и Carrollton соседи.
- Организация: "surrounding North Dallas communities" (не "North Dallas suburbs").

Заголовки:

- Шесть вопросов FAQ тегом H3, три шаблонные.
- H2 "Slab Leaks in Older Lewisville Homes" (услуга плюс город). Но это лучшие места страницы: за 3 месяца "slab leak repair lewisville" 200 показов, место 9.6; "slab leak repair lewisville tx" 152, 9.5; "lewisville slab leak repair" 105, 9.0 (`docs/cities-table-2026-10-03.md`). По правилу о том, что ранжируется, заголовок держат или меняют один к одному; по правилу 9 тема у страницы slab leak, редкая для города проблема стоит одним абзацем не в начале. Частая ли она в Lewisville, знает Денис.
- Title "...& Faucet Repair": по keyword-map эта страница не целится в "faucet repair". Решать после Search Console (раздел 2).
- "plumber in Lewisville" нет ни в одном H2, во вступлении и в закрывающем абзаце (правило городской страницы).

Остальное:

- H1 с дефисом вместо тире (на новом сайте исправлено). Описание: три риторических вопроса подряд; закрывающая строка: риторический вопрос и тройка (правило 3).
- Камера: "We clear it first so you have your house back, then put a camera down if the history says to..." У Дениса (2 октября) на главной линии камера до прочистки, если линия пропускает, и после, если забита.
- Что в городе главное: "That is most of what we do here.", "The other steady half of the work here is hardware that ran out of years.", FAQ 1 "That is the most common leak call we get." По CLAUDE.md частый вызов октября 2026 это раковина с дренажом кондиционера; про Lewisville данных нет.
- "In most Lewisville homes we go under the house rather than through it." и FAQ 3 "most of the time": FPP и прокапывает, и вскрывает плиту (CLAUDE.md), доля не подтверждена.
- Отзыв John Wilson обрезан; уровни Local Guide не подтверждены.
- Схема (часть C): два Organization с одним @id; "Texas Master Plumber License M-44816" (снятая формулировка); `legalName` "FPP Plumbing, LLC"; в `sameAs` нет Google, Yelp, Thumbtack, Nextdoor; нет Person и Review. Подвал: "all rights reserved © 2024-2026 License M - 44816".
- Нет блока Дениса, фото и историй с работ, слова о том, какой офис обслуживает город.

### 7. Улицы, районы, ориентиры

В тексте страницы нет ни одной улицы, района, дороги, озера или ориентира; то же в `docs/briefs/_shared/cities-official-place-names-2026-10-03.json` (`live_page_names` пустой). Только безымянное, каждое предложение целиком:

- "A lot of houses here have been standing long enough for the lines under the foundation to have earned some respect." (возраст не назван)
- "In most Lewisville homes we go under the house rather than through it."
- "If nobody has ever shown you where yours is, our shut-off guide covers the setups used in local homes with photos, and knowing it in advance is worth more than any tool in your garage."
- "In houses of a certain age the line itself has narrowed, roughened, or picked up roots at a joint, and clearing the top of it just restarts the clock."

В схеме:

- "5700 Tennyson Pkwy, Suite 300", Plano: настоящий офис FPP (CLAUDE.md), это Plano.
- "Flower Mound" и "Highland Village": отдельные города, не часть Lewisville. Проверено 3 октября 2026 по таблице U.S. Census Bureau "2020 ZCTA to Place" (https://www2.census.gov/geo/docs/maps-data/data/rel2020/zcta520/tab20_zcta520_place20_natl.txt): "Flower Mound town" и "Highland Village city", действующие (класс C1, статус A), с Lewisville делят индексы 75067 и 75077.
- "The Colony", "Carrollton": города из десяти.

На будущее: основная земля Lewisville в индексах 75057, 75067, 75056, 75077 (`zcta_by_city` в том же JSON); 75056 больше чем наполовину земля The Colony (та же таблица Census). Страница районов на сайте города ответила 403 (`cities-table-notes-2026-10-03.md`).

### 8. Точечные правки, которые уже стоят на новом сайте

В POINT_FIXES (`tools/build_launch_content.py`) для `/plumber-lewisville-tx/` правок нет ("Lewisville" там только в TEN_CITIES). Title и описание не правились. Метки FLAG_RULES ничего не нашли.

В `site/src/data/launch-changes.csv` две строки:

1. Строка 258, общее правило тире: H1 стал "Plumber in Lewisville, TX: Finding Leaks Before They Find Your Floors".
2. Строка 259: виджет отзывов заменён меткой `<!-- reviews -->` (для Lewisville отзывов в файле нет, пункт 3).

По файлу страницы ещё: FAQ ушёл в данные (не заголовки), список услуг стал списком, первая крошка "Home". Остальное из пункта 6 стоит как было: FAQ 6 с "Same day for most calls", "Fast, clean, and honest.", "thirty or forty dollars", фургон с пустым alt, "...)explains" без пробела.

### 9. Что сохранить как местную суть и что никем не подтверждено

Местного на странице нет: кроме имени города, всё подошло бы любому. Сохранить как мысль (не дословно):

- Течь находят по счёту: "Most leaks in Lewisville are discovered by a bill, not by a puddle." Совпадает с H1 и с запросом "lewisville tx leak detection" (134 показа, место 19.9 за 3 месяца, `docs/cities-table-2026-10-03.md`).
- Прокоп под фундаментом вместо вскрытия пола (раздел 2, FAQ 3): держит запросы slab leak с городом; метод есть в CLAUDE.md.
- "A shutoff valve that has not moved in fifteen years is not really a shutoff valve anymore, it is a decoration." Голос хороший, "fifteen years" никто не давал.
- "Close the main valve, then call."; FAQ 2 и 5 по правилам цены.
- Три своих автора отзывов, свободны; John Wilson только полным текстом.

Никем не подтверждено (нет в CLAUDE.md и в диктовках; диктовок про Lewisville в `source/dictation/` нет):

- что поиск течи "most of what we do here", вызов про счёт "the most common leak call", вторая половина работы это старая арматура;
- что в Lewisville много старых домов и slab leak частая работа; что "In most Lewisville homes" ремонт идёт прокопом;
- "thirty or forty dollars a month", "fifteen years", "it can run for months";
- какой офис обслуживает Lewisville (в схеме Plano, на фургоне телефон Plano);
- что работы трёх авторов были в Lewisville, их уровни Local Guide;
- где снят фургон и что значит "M-38532"; девять старых подписей "in Lewisville, TX" в галерее.

Настоящего материала по Lewisville в проекте нет: ни фото, ни клипа, ни отзыва с городом, ни диктовки, ни поста.

### 10. Что не удалось проверить

- Отзывы на Google вживую не открывал (браузер ночью запрещён): тексты сверены с архивом, ссылка Allen Thong проверена одним запросом, две ссылки share.google по записи от 30 сентября.
- Снимки галереи с подписью Lewisville не открывал.
- Файлы отзывов ночью пересобираются: занятость проверена в 10:09 и 10:18, для этих трёх без изменений.

## 2. Search Console

Файл раздела: `docs/briefs/lewisville/2-gsc.md`, вставлен целиком. Заголовок файла: «2. Search Console: страница Lewisville (/plumber-lewisville-tx/)».

Длинные таблицы в бриф не вставлены, они лежат рядом, в `docs/briefs/lewisville/`: `lewisville-gsc-table-3m.md` (все 118 запросов за 3 месяца), `lewisville-gsc-table-16m.md` (все 258 запросов за 16 месяцев), `lewisville-gsc-headings.md` (какие запросы держит каждый заголовок), `lewisville-gsc-extra.md` (таблицы A до G: главная, другие страницы выше, первые 30 запросов без фразы на странице, слова, которые не ставятся, и отличия метода). Рабочие скрипты раздела лежат в папке помощников (scratchpad night/lewisville), в проекте их нет.

Собрано 3 октября 2026. Источники: source/gsc/ (page-query-3m.csv и page-query-16m.csv от 30 сентября 2026, Pages.csv, Chart.csv, page-query-coverage.csv), seo/keyword-map.md и .csv, seo/cannibalization-findings.md; живой текст и разметка: source/crawl/pages/plumber-lewisville-tx.json (обход 30 сентября 2026, правка страницы 17 августа 2026). В ячейках: показы · место · клики (где два числа: показы · место).

Метод брифа Plano: копии docs/briefs/_shared/gsc_plano_*.py под Lewisville (scratchpad/night/lewisville), проектные tools не запускались; отличия в начале `lewisville-gsc-extra.md`.

### Главное коротко

1. Кликов с известным запросом нет. Итог Google: 2 клика за 3 месяца и те же 2 за 16, то есть оба в последние 3 месяца и оба по скрытым запросам.
2. Место лучше, показов меньше: за 13 месяцев до июля 2026 было 58,315 показов на месте 52.5, за последние 3 месяца 3,244 на месте 25.9.
3. Лучшие места у slab leak repair с городом: «slab leak repair lewisville» 200 · 9.6, «slab leak repair lewisville tx» 152 · 9.5 (вся группа slab leak 762 показа из 2,867, место 10.7). Leak detection с городом: 312 показов, место 19.6. Главные запросы города стоят на местах 33 до 42.
4. Slab leak repair держит только title; пять H2 из восьми не держат ничего. Точные фразы города стоят только в заголовках и description, в тексте нет ни "plumber in Lewisville", ни "Lewisville plumber".
5. "Faucet Repair" в title держит faucet repair с городом (94 показа за 3 месяца, 3,116 за 16), а карта ключей запрещает этой странице faucet repair. Решает Денис.
6. Главная по запросам с lewisville за 3 месяца не показывается. Страница Plano выше по 10 запросам (135 показов), 8 из них на местах 1 до 4: похоже на карточку Plano. Чужие места почти без показов, но разметка называет соседние города (раздел 8).

### 1. Итоги за 3 и 16 месяцев

| Период | Запросов | Клики | Показы | Место | Итог Google со скрытыми запросами |
|---|---|---|---|---|---|
| 3 мес (1 июля до 28 сентября 2026) | 118 | 0 | 3,244 | 25.9 | 2 клика, 3,531 показ, место 25.74 |
| 16 мес (31 мая 2025 до 28 сентября 2026) | 258 | 0 | 61,559 | 51.1 | 2 клика, 63,896 показов, место 50.88 |

Второй счёт: модуль csv, разбор строк без него и awk дали одно и то же (118 · 0 · 3,244 · 25.86 и 258 · 0 · 61,559 · 51.06), те же числа в page-query-coverage.csv. С известным запросом 92% и 96% показов, 0 из 2 кликов. Все запросы трёхмесячной выгрузки есть в шестнадцатимесячной, поэтому 13 месяцев до июля получены вычитанием: 58,315 показов (по итогу Google 60,365), 0 кликов, место 52.5.

| Группа запросов | 3 мес: запросов · показы · место | 16 мес |
|---|---|---|
| lewisville | 97 · 2,867 · 27.4 | 217 · 60,828 · 51.3 |
| без города | 18 · 370 · 14.6 | 32 · 690 · 30.3 |
| другое место | 1 · 1 · 35.0 | 6 · 18 · 56.8 |
| бренд (fpp) | 2 · 6 · 3.8 | 3 · 23 · 11.8 |

С lewisville за 3 месяца на местах 3 до 10 только 4 запроса (458 показов, все slab leak), 10 до 20 тринадцать (602), 20 до 50 семьдесят пять (1,795). Без города главное near me про утечки: 8 запросов, 257 показов, место 5.5 («slab leak plumber near me» 52 · 4.3), почти все за последние 3 месяца; здесь страница Lewisville выше страниц услуг. Правило «карта» (без названия города и место 3 или выше) задевает только бренд «fpp plumbing» 5 · 2.0: своей карточки у Lewisville нет. Почему упали показы, по файлам не видно (весь сайт по Chart.csv: 201,829 показов в апреле 2026, 88,708 в июне).

### 2. Первые 20 запросов каждого периода

Все запросы: `lewisville-gsc-table-3m.md` (118) и `lewisville-gsc-table-16m.md` (258). Ниже обе двадцатки, 28 запросов: строки 1 до 20 это двадцатка за 16 месяцев по порядку, «№ 3 мес» это номер в двадцатке за 3 месяца. Двадцатки дают 1,961 показ из 3,244 и 29,230 из 61,559. Запросов с кликом нет. Последняя колонка: раздел 5.

| Запрос | № 3 мес | 3 мес | 16 мес | Фраза целиком |
|---|---|---|---|---|
| plumber lewisville | 5 | 113 · 34.3 | 2,573 · 37.0 | точно: title |
| plumber lewisville tx | 2 | 152 · 33.4 | 2,520 · 44.1 | точно: title |
| lewisville plumbing | 9 | 94 · 35.0 | 2,245 · 42.5 | точно: H2 FAQ |
| lewisville plumber | 13 | 79 · 37.9 | 1,848 · 47.2 | мягко: description |
| plumbers in lewisville tx | 11 | 92 · 42.2 | 1,837 · 46.2 | мягко: title, H1 |
| lewisville plumbers |  | 27 · 39.9 | 1,583 · 53.6 | точно: description |
| plumbers lewisville |  | 25 · 41.8 | 1,522 · 49.7 | мягко: title, H1 |
| emergency plumber lewisville |  | 36 · 21.9 | 1,478 · 35.6 | нет |
| plumber in lewisville |  | 42 · 37.9 | 1,427 · 52.6 | точно: H1 |
| slab leak repair lewisville | 1 | 200 · 9.6 | 1,375 · 40.4 | нет |
| plumbing lewisville |  | 16 · 42.8 | 1,373 · 49.9 | перестановка: H2 |
| plumbing lewisville tx | 12 | 89 · 40.3 | 1,315 · 53.9 | перестановка: H2 |
| plumbers lewisville tx | 10 | 94 · 38.4 | 1,251 · 48.3 | мягко: title, H1 |
| plumber lewisville texas |  | 50 · 35.0 | 1,143 · 49.7 | мягко: title, H1 |
| plumber in lewisville tx | 14 | 78 · 36.5 | 989 · 46.4 | точно: H1 |
| slab leak repair lewisville tx | 3 | 152 · 9.5 | 989 · 39.6 | нет |
| plumbers in lewisville |  | 37 · 41.0 | 982 · 53.7 | мягко: title, H1 |
| lewisville plumbing service | 18 | 63 · 33.0 | 931 · 40.1 | перестановка: H2 |
| plumbers lewisville texas | 16 | 66 · 38.6 | 929 · 54.9 | мягко: title, H1 |
| emergency plumber lewisville tx |  | 2 · 21.5 | 920 · 46.7 | нет |
| lewisville tx leak detection | 4 | 134 · 19.9 | 691 · 59.5 | нет |
| lewisville tx sab leak repair (опечатка) | 6 | 106 · 11.8 | 828 · 38.4 | нет |
| lewisville slab leak repair | 7 | 105 · 9.0 | 690 · 38.0 | нет |
| lewisville tx slab leak repair | 8 | 98 · 12.9 | 308 · 16.1 | нет |
| google find me a plumber (голосовой) | 15 | 66 · 35.0 | 231 · 52.0 | нет |
| lewisville plumber service | 17 | 65 · 35.9 | 868 · 59.0 | нет |
| lewisville leak detection | 19 | 62 · 19.1 | 393 · 66.8 | нет |
| plumbers in lewisville texas | 20 | 53 · 40.8 | 895 · 52.7 | мягко: title, H1 |

Слова всех 28 запросов в живом тексте стоят. По всем запросам с lewisville за 3 месяца: полностью у 72 (2,763 показа из 2,867), частично у 11 (59), не наша услуга у 14 (45). Нет слов (3 мес, в скобках 16): break 26 (1,815), company 11 (647), expansion 6 (358), contractor 2 (219), 24 3 (164), bathroom 0 (1,018), hose bib 0 (17).

### 3. Главная по запросам с lewisville

За 3 месяца ни одного. За 16 месяцев 31 запрос: 818 показов, место 64.3, кликов нет; главная выше страницы города по 15 (136 показов), только у главной 5 (32). Быстрых ссылок главной по таким запросам нет. Все строки: `lewisville-gsc-extra.md`, таблица A.

| Запрос | Главная, 16 мес | Lewisville, 16 мес | Lewisville, 3 мес | Кто выше за 16 мес |
|---|---|---|---|---|
| emergency plumber lewisville | 398 · 80.5 · 0 | 1,478 · 35.6 · 0 | 36 · 21.9 · 0 | Lewisville |
| emergency plumber lewisville tx | 72 · 84.2 · 0 | 920 · 46.7 · 0 | 2 · 21.5 · 0 | Lewisville |
| leak detection plumber lewisville | 68 · 2.1 · 0 | 166 · 51.1 · 0 | 26 · 17.3 · 0 | главная |
| website for plumbers lewisville | 38 · 82.2 · 0 | 17 · 55.2 · 0 | 5 · 45.6 · 0 | Lewisville |

Главная не мешает: по крупным запросам emergency с городом она стояла на 74.6 до 94.1, страница города на 35.6 до 55.6; высокие места главной («leak detection plumber lewisville» 68 · 2.1) были только до июля 2026.

### 4. Что держат title, H1, H2 и вопросы FAQ

Дословно. Title: "Plumber Lewisville, TX | Water Leaks, Slab Leaks & Faucet Repair". Description: "Bill jumped and nothing looks wet? Floor warm in one spot? Faucet dripping for months? Licensed Lewisville plumbers who find it first." H1: "Plumber in Lewisville, TX - Finding Leaks Before They Find Your Floors". H2 и вопросы FAQ: в таблице и в списке под ней (девятый H2 это два телефона в подвале, не заголовок).

«Держит»: все значимые слова запроса стоят в заголовке; «фраза целиком»: подряд и в том же порядке. В ячейках: запросов с lewisville · показы. Списки: `lewisville-gsc-headings.md`.

| Заголовок живой страницы | Все слова запроса в заголовке, 3 мес | 16 мес | Фраза целиком, 3 мес | 16 мес | Держит только он, 3 мес | 16 мес |
|---|---|---|---|---|---|---|
| title | 26 · 1,610 | 33 · 26,877 | 13 · 805 | 15 · 16,283 | 10 · 698 | 14 · 7,088 |
| description | 16 · 912 | 20 · 19,804 | 3 · 107 | 4 · 3,506 | 0 · 0 | 1 · 15 |
| H1 | 16 · 912 | 19 · 19,789 | 13 · 805 | 15 · 16,283 | 0 · 0 | 0 · 0 |
| H2: «Our Plumbing Services in Lewisville» | 11 · 299 | 16 · 6,740 | 2 · 24 | 4 · 494 | 5 · 92 | 8 · 1,610 |
| H2: «Lewisville Plumbing FAQ» | 6 · 207 | 8 · 5,130 | 2 · 96 | 2 · 2,331 | 0 · 0 | 0 · 0 |
| H2: «What Lewisville Homeowners Say About FPP Plumbing» | 6 · 207 | 8 · 5,130 | 0 · 0 | 0 · 0 | 0 · 0 | 0 · 0 |
| вопрос FAQ: «How much does a plumber cost in Lewisville, TX?» | 16 · 912 | 19 · 19,789 | 0 · 0 | 0 · 0 | 0 · 0 | 0 · 0 |

Ничего не держат H2 "Water Leaks You Cannot See", "Slab Leaks in Older Lewisville Homes", "Faucets, Valves, and Parts That Have Simply Aged", "Drains That Keep Coming Back", "When It Cannot Wait" и вопросы "My water bill jumped but I cannot find anything wet. What now?", "Can a slab leak be repaired without tearing up my floors?", "The shutoff valve under my sink will not turn. Is that a problem?", "Do you charge extra after hours?", "How fast can you get to Lewisville?". Ни один заголовок не держит 60 запросов с lewisville, 958 показов (за 16 месяцев 168 и 27,211): emergency, leak detection, water heater, water line, pipe break, plumber service, опечатки.

**Что нельзя потерять** (3 месяца, в скобках показы за 16):

1. Начало title "Plumber Lewisville, TX": только здесь «plumber lewisville tx» 152 · 33.4 (2,520) и «plumber lewisville» 113 · 34.3 (2,573).
2. "Slab Leaks" и "Repair" в title: только title держит 10 запросов, 698 показов (14 и 7,088), там лучшие места страницы: «slab leak repair lewisville» 200 · 9.6, «slab leak repair lewisville tx» 152 · 9.5, «lewisville slab leak repair» 105 · 9.0, «slab leak plumber lewisville» 28 · 10.8.
3. "Faucet Repair" в title: «lewisville tx faucet repair» 41 · 30.7, «faucet repair lewisville» 26 · 24.5 (спор с картой ключей, раздел 7).
4. Начало H1 "Plumber in Lewisville, TX": только здесь «plumber in lewisville tx» 78 · 36.5 (989) и «plumber in lewisville» 42 · 37.9 (1,427).
5. "Licensed Lewisville plumbers" в description: только здесь «lewisville plumbers» 27 · 39.9 (1,583).
6. H2 "Lewisville Plumbing FAQ": только здесь «lewisville plumbing» 94 · 35.0 (2,245); слова plumbing нет ни в title, ни в H1.
7. H2 "Our Plumbing Services in Lewisville": один держит 5 запросов, 92 показа (8 и 1,610), главный «lewisville plumbing service» 63 · 33.0 (931). Список под ним единственное место большинства названий услуг.
8. Текст ссылки "leak detection" (detection нет в заголовках; leak detection с городом 312 · 19.6), "plumber near me" со ссылкой на главную (единственные слова near me; near me без города 267 · 5.9), emergency в тексте (emergency с городом 127 · 25.7; в заголовках нет), "FPP Plumbing" в H2 отзывов («fpp plumbing» 5 · 2.0).

Вопрос о цене держит те же слова, что H1. "How fast can you get to Lewisville?" не держит ничего, а ответ ("Same day for most calls...") задевает правило о времени приезда: замена без потерь.

### 5. Фраза целиком

Проверены 28 запросов раздела 2 (с кликом нет). «Точно»: слово в слово; «мягко»: без in, tx, texas, множественное число не в счёт (правило tools/gsc_page_table.py); «перестановка»: те же слова рядом в другом порядке. Места: title, H1, H2, вопросы FAQ, текст, description. Итог: точно 6, мягко 8, перестановка 3, нигде 11 (оба emergency, четыре slab leak repair, два leak detection, sab, «lewisville plumber service», «google find me a plumber»).

Точная фраза на странице есть у 9 запросов с lewisville и бренда (511 показов за 3 месяца, 11,447 за 16; в скобках показы за 16): «plumber lewisville» title, 113 · 34.3 (2,573); «plumber lewisville tx» title, 152 · 33.4 (2,520); «lewisville plumbing» H2 FAQ, 94 · 35.0 (2,245); «lewisville plumbers» description, 27 · 39.9 (1,583); «plumber in lewisville» H1, 42 · 37.9 (1,427); «plumber in lewisville tx» H1, 78 · 36.5 (989); «plumber lewisville, tx» title, нет (86); «fpp plumbing» H2 отзывов, 5 · 2.0 (17); «plumber+lewisville» title, нет (7).

Нет у 91 запроса с lewisville (2,361 показ; за 16 месяцев 209 и 49,398). Первые 30: `lewisville-gsc-extra.md`, таблица E.

### 6. Где другая страница стоит выше или забирает показы

За 3 месяца на сайте 101 запрос с lewisville, страница города есть в 97 (2,867 показов из 3,047); за 16 месяцев в 217 из 226 (60,828 из 63,668). Другие страницы за 3 месяца: Plano 13 запросов, 175 показов, место 8.3; /gallery/, Frisco и гайд по главному крану по 1 или 2 показа. Главные строки (все строки обоих периодов: `lewisville-gsc-extra.md`, таблица B):

| Запрос | Другая страница | Она: показы · место · клики | Lewisville: показы · место · клики | Что |
|---|---|---|---|---|
| plumber lewisville tx | /plumber-plano-tx/ | 76 · 16.9 · 0 | 152 · 33.4 · 0 | выше |
| leak detection plumber lewisville | /plumber-plano-tx/ | 40 · 1.4 · 0 | 26 · 17.3 · 0 | выше, больше показов |
| affordable sewer line repair lewisville | /plumber-plano-tx/ | 20 · 1.0 · 0 | нет | страницы Lewisville нет |
| affordable drain cleaning lewisville | /plumber-plano-tx/ | 19 · 1.0 · 0 | нет | страницы Lewisville нет |
| emergency plumber lewisville | /plumber-plano-tx/ | 5 · 3.2 · 0 | 36 · 21.9 · 0 | выше |
| slab leak plumber lewisville | /plumber-plano-tx/ | 4 · 1.8 · 0 | 28 · 10.8 · 0 | выше |

Почти всё это Plano на местах 1 до 4. Кнопка сайта карточки Plano ведёт на /plumber-plano-tx/ (seo/cannibalization-findings.md), так что это, скорее всего, карточка; выгрузка этого не доказывает. Исключение «plumber lewisville tx» (Plano 76 · 16.9 против 152 · 33.4). За 16 месяцев: главная выше по 15 (136 показов); страница slab leak по 10 запросам на месте 77.9, выше только по «slab leak detection lewisville» (10 · 51.7 против 260 · 58.6); garbage disposal выше по 3 (19 показов); /gallery/ по «expansion tanks repair lewisville tx» (68 · 53.5 против 164 · 58.4).

### 7. Запросы услуг с lewisville и хозяин по карте ключей

Карта: у страницы Lewisville главный ключ plumber lewisville tx, вторичные plumber lewisville, lewisville plumbing, lewisville plumber; must not target: faucet repair (faucet page). Ключей с lewisville у страниц услуг нет, хозяин это страница услуги по её главному ключу (правило 5): expansion tank у /water-heater-repair-frisco-mckinney/, у pipe repair ключа нет (ближе всех /water-lines/), у bathroom и не наших услуг страницы нет. Услуга определена по словам запроса (slab leak detection и foundation leak detection попали в slab leak, 69 показов). В ячейках: запросов · показы · место; кликов нет.

| Услуга в запросе с lewisville | Lewisville, 3 мес | Lewisville, 16 мес | Страница-хозяин, 16 мес |
|---|---|---|---|
| не наши услуги (раздел 9) | 14 · 45 · 35.4 | 30 · 1,477 · 62.1 |  |
| garbage disposal | нет | 7 · 856 · 59.3 | 5 · 231 · 69.6 |
| hose bib, outdoor faucet | нет | 2 · 33 · 16.1 | 1 · 6 · 33.7 |
| faucet, shower valve | 4 · 94 · 27.6 | 9 · 3,116 · 49.2 | 4 · 16 · 71.1 |
| toilet | нет | 3 · 39 · 59.5 | нет |
| expansion tank | 2 · 6 · 42.3 | 2 · 358 · 50.6 | 1 · 5 · 41.2 |
| water heater | 4 · 5 · 29.2 | 19 · 3,608 · 64.9 | 2 · 3 · 87.3 |
| slab leak | 10 · 762 · 10.7 | 11 · 5,148 · 37.6 | 9 · 1,117 · 77.7 |
| leak detection | 9 · 312 · 19.6 | 10 · 1,962 · 61.0 | 4 · 15 · 79.8 |
| sewer line, camera, main line | нет | 8 · 427 · 70.6 | нет |
| drain cleaning, clogs | нет | 11 · 1,567 · 80.5 | нет |
| water line | 3 · 6 · 28.2 | 5 · 2,014 · 63.3 | 2 · 39 · 81.2 |
| pipe repair, leak repair, burst pipe | 5 · 58 · 23.0 | 13 · 2,395 · 54.5 | 1 · 1 · 75.0 |
| PRV, water pressure | нет | 2 · 28 · 17.4 | нет |
| bathroom, kitchen plumbing | нет | 3 · 1,035 · 66.9 |  |
| emergency, 24 hour, after hours | 9 · 127 · 25.7 | 14 · 5,635 · 46.6 | 6 · 47 · 81.5 |
| общие (plumber lewisville и варианты) | 37 · 1,452 · 37.8 | 68 · 31,130 · 48.5 |  |

- Slab leak: самая сильная группа (место 10.7), а страница slab leak по этим запросам за 3 месяца не показывается. Страница города называет услугу и ссылается, глубина на странице услуги.
- Faucet: карта запрещает, а слова в title держат 3,116 показов за 16 месяцев (у страницы faucet 16). Формулировку, которая держит показы, сохраняют или меняют один в один; решает Денис.
- Emergency: у страницы emergency must not target plumber + city, здесь она на 81.5; ключа emergency с lewisville в карте нет.
- Water heater, water line, drain cleaning, bathroom, pipe break: показы почти все до июля 2026, места 54.5 до 80.5. Hose bib (33 показа, место 16.1) на странице не назван.

### 8. Запросы с другими местами

С другими девятью городами (кроме одного с Plano), Park Cities, Dallas и индексами запросов нет. Всего 6 запросов: 18 показов за 16 месяцев, 1 за 3, кликов нет (16 мес: показы · место). Видимый текст чужих мест не называет, разметка называет.

- Garden Ridge: «garden ridge plumbing slab leak detection» 7 · 49.9, «garden ridge water heater repair» 1 · 35.0 (единственный показ за 3 месяца). Ни в тексте, ни в разметке нет; причину назвать нельзя.
- Plano: «emergency faucet installation plano tx» 5 · 72.2. В тексте нет; Plano стоит в меню, в подвале ("Plano Office" с адресом) и в адресе узла LocalBusiness разметки.
- Highland Village: «plumber highland village tx» 2 · 82.0. В тексте нет; в разметке areaServed: Lewisville, Flower Mound, The Colony, Carrollton, Highland Village.
- Castle Hills («emergency plumber castle hills, tx» 2 · 49.0) и Forest Park («plumber forest park» 1 · 15.0): ни в тексте, ни в разметке нет.

Страница города не называет соседей, а Flower Mound и Highland Village на сайте не называются вообще: areaServed новой страницы только Lewisville. Потеря 2 показа.

### 9. Слова, которые на страницу не ставятся

Запросов · показы за 3 месяца, в скобках за 16; кликов нет. По словам: `lewisville-gsc-extra.md`, таблица G.

- Не наши услуги и темы: 15 · 50 (32 · 1,487). tankless 1,076 (за 3 месяца 0; «tankless water heater repair lewisville» 511 · 63.8), repiping и repipe 123, lining 117 (из них cipp 24), commercial 36, website 17, roof 13, trenchless 6, cleanup 4, handyman 3, additions 2, hydro jetting 2, sump 1. gas 85: один запрос «gas water heater repair lewisville» (75.7), про водонагреватель, не про газовую линию; отложен по правилу, решает Денис.
- Опечатки 3 · 205 (5 · 2,334): pluming 1,495, sab 828, emergenclewisville 10, meplumber 1. Голосовые (google, alexa find me a plumber) 2 · 93 (3 · 336). Оценочные (affordable 347, best 133) 4 · 16 (13 · 480). Имя FPP с ошибкой (psp, ppr, dpp, pp, f6) 3 · 8 (6 · 35). Чужие компании (pipoapps 157, trapp, barefoot, fusion, pomme) 1 · 2 (5 · 162).
- «plumber near me lewisville» (44 · 61.5 за 16 месяцев): near me только в одном предложении со ссылкой на главную. Длинных вопросов нет.

### Что из цифр следует для брифа

1. Остаётся всё из списка «Что нельзя потерять» (раздел 4). "Faucet Repair" в title: решает Денис.
2. "plumber in Lewisville" и варианты во вступление, первый блок, закрывающий абзац и в часть H2 (пять H2 пустые). По одной фразе: «Lewisville plumber», «plumbers in Lewisville», «plumbing in Lewisville», «plumbing services in Lewisville», «plumbing company in Lewisville»; слова pipe break или burst pipe, contractor, expansion tank, bathroom, 24/7 ("A licensed plumber is on duty 24/7"). О каждой добавке сказать Денису.
3. «plumber near me» со ссылкой на главную перенести в последний абзац вступления.
4. Slab leak: раздел со ссылкой; объём по ответу Дениса. Emergency: слово и ссылка остаются, заголовок решает Денис. Добавить ссылку на hose bib.
5. Убрать вопрос "How fast can you get to Lewisville?", чужие города из areaServed, слова раздела 9, места раздела 8.

### Что проверить не удалось

- Запросы 2 кликов: Google их скрывает. Почему показов меньше, а место лучше: по дням страница не разбита (правка 17 августа 2026).
- Откуда near me без города на местах 4 до 8 и Plano на местах 1 до 4: выгрузка не отделяет карточку от выдачи.
- Почему были Garden Ridge, Castle Hills, Forest Park.
- Сайт заново не открывался (обход 30 сентября 2026). Semrush по странице в keyword-map.csv нет.

## 3. Конкуренты

Файл раздела: `docs/briefs/lewisville/3-competitors.md`, вставлен целиком. Заголовок файла: «3. Конкуренты по Lewisville: десять страниц из выдачи».

Приложение рядом: `3-competitors-details.md` (32 КБ: выдача Semrush целиком, все заголовки десяти страниц, выписки местных фактов, пропущенные и запасные страницы, места нашей страницы в Semrush, что конкуренты делают, а нам нельзя). Видимый текст десяти страниц: `source/competitors/2026-10-03-lewisville/00.txt` до `09.txt` (первая строка адрес, дальше весь текст одной строкой).

Дата: 3 октября 2026. Проект только читался. Новое: эта секция, приложение `3-competitors-details.md` (выдача Semrush целиком, все заголовки, выписки местных фактов, пропущенные страницы, что нам нельзя) и папка `/Users/denyskavaler/Projects/fppplumbing-site/source/competitors/2026-10-03-lewisville/` (`00.txt` до `09.txt`, формат как у Plano: первая строка адрес, дальше весь видимый текст одной строкой).

### 1. Как выбраны десять страниц

Запросы: "plumber lewisville tx", "plumber in lewisville", "lewisville plumbing" (по Semrush 260, 140 и 210 поисков в месяц). Оба источника сняты 3 октября 2026:

1. Semrush, обычная (не рекламная) выдача Google, база "us", первые 30 мест. По нему порядок. Метод тот же, что по Plano.
2. Веб-поиск (расширенный режим), те же запросы. Сверка: он не Google и к городу не привязан.

Чего нет: живой выдачи Google с точкой в Lewisville. База Semrush общая по США, без блока с картой, дата обновления базы в ответе не указана.

Порядок: среднее место по трём запросам, нет в первых 30 считается как 31, одна компания один раз.

| № | Файл | Компания | URL | Места Semrush | Среднее | Веб-поиск (из 3) |
|---|---|---|---|---|---|---|
| 1 | 00.txt | Lewisville Plumbing (карточка Google "Lewisville Plumbing Service") | https://www.lewisville-plumbing.com/ | 1 / 1 / 1 | 1,0 | 3 |
| 2 | 01.txt | Berkeys Plumbing | https://www.berkeys.com/lewisville-plumbing/ | 2 / 4 / 5 | 3,7 | 2 |
| 3 | 02.txt | Milestone Electric, A/C & Plumbing | https://callmilestone.com/lewisville/plumbing/ | 3 / 3 / 16 | 7,3 | 0 |
| 4 | 03.txt | Legacy Plumbing & Electric | https://legacyplumbing.net/service-area/lewisville/ | 10 / 11 / 4 | 8,3 | 0 |
| 5 | 04.txt | Roto-Rooter | https://www.rotorooter.com/lewisvilletx/ | 7 / 5 / 21 | 11,0 | 3 |
| 6 | 05.txt | Mother Modern Plumbing | https://www.callmother.com/cities/lewisville | 8 / 7 / 24 | 13,0 | 1 |
| 7 | 06.txt | Trident Plumbing | https://trident-plumbing.com/service-areas/lewisville/ | 14 / 13 / 14 | 13,7 | 1 |
| 8 | 07.txt | All Metroplex Plumbing | https://allmetroplexplumbing.com/ | 11 / 8 / 29 | 16,0 | 0 |
| 9 | 08.txt | Tempo Air | https://tempoair.com/locations/plumbing-lewisville-tx/ | 18 / 17 / 15 | 16,7 | 1 |
| 10 | 09.txt | Imperial Plumbing | https://www.imperialtx.com/ | 22 / 22 / 12 | 18,7 | 0 |

Семь страниц это страницы города. Три это главные, у них в выдаче стоит именно главная: Lewisville Plumbing (местная, "since 1992" по её словам), All Metroplex ("local plumbing company in Lewisville") и Imperial (из Denton, второй офис в Lewisville).

Пропущено (подробно в приложении, раздел Г):

- Каталоги и соцсети: yelp.com (6 / 2 / 6), angi.com, facebook.com, reddit.com, homeadvisor.com, nextdoor.com, mapquest.com, todayshomeowner.com, bbb.org, patch.com. Магазины: ferguson.com, apexsupplyco.com.
- plumbinglewisville.com (30 / 18 / 7, по месту был бы десятым): страница для сбора звонков без названия компании и лицензии, внизу "© 2017". Вместо неё Imperial.
- lewisvilleplumbingpros.com (2 место по "lewisville plumbing"): компания из Lewisville в Северной Каролине. lewisvilleplumbingco.com: сам пишет "This site is a lead generation service".
- fppplumbing.com: по трём запросам в первых 30 нас нет (Semrush); по запросам о slab leak в Lewisville наша страница на 5 до 8 местах (приложение, раздел Д). Сверить с секцией Search Console.
- Запасные: Reeves Family Plumbing (20,7), Harmony Plumbing (21,3). Только в веб-поиске: horizonservice.net (2 из 3), gopaschal.com, plumberoflewisville.com.

Все страницы отдали код 200 с первого запроса (один запрос на страницу), защиту от роботов обходить не пришлось.

### 2. Таблица по десяти страницам

"Основной текст": от H1 до подвала, с FAQ и отзывами (у All Metroplex H1 нет, считал от первого блока). "Вся страница": весь видимый текст с меню и подвалом, как в файле. Слова считал сам.

#### 2.1. Размер, "Lewisville", отзывы, FAQ

| № | Компания | Слов: основной текст | Вся страница | "Lewisville": основной / вся | Отзывов на странице | FAQ |
|---|---|---|---|---|---|---|
| 1 | Lewisville Plumbing | 334 | 534 | 10 / 14 | 0 | 0 |
| 2 | Berkeys | 1 377 | 1 622 | 18 / 20 | 0 | 0 |
| 3 | Milestone | 1 046 | 2 081 | 22 / 54 | 0 (общие цифры, на одной странице три разные) | 0 |
| 4 | Legacy | 1 971 | 2 957 | 41 / 43 | 0 | 0 |
| 5 | Roto-Rooter | 1 389 (без отзывов 1 262) | 1 704 | 18 / 24 (без отзывов 14) | 3, подписаны "Lewisville, TX" | 0 |
| 6 | Mother | 2 714 (без отзывов 873) | 2 919 | 42 / 44 (без отзывов 17) | 30: 23 подписаны "Lewisville, TX" (12.2024 до 08.2026), 7 из других городов | 3 |
| 7 | Trident | 983 (без отзывов 852) | 2 738 | 10 / 16 | 2, без города | 0 |
| 8 | All Metroplex | 1 127 (без отзывов 461) | 1 293 | 1 / 3 | 9 (06.2022 до 02.2023), без города | 0 |
| 9 | Tempo Air | 758 | 1 255 | 11 / 12 | 0 | 5 |
| 10 | Imperial | 457 | 856 | 0 / 5 | 0 в коде (блок грузится скриптом) | 0 |

Для сравнения наша нынешняя страница (source/crawl/pages/plumber-lewisville-tx.json): 1 458 слов, "Lewisville" 10 раз, 6 вопросов FAQ.

#### 2.2. Title и H1 дословно

1. Lewisville Plumbing. Title: "Plumbing and Water Heater Services | Lewisville, TX". H1 в двух тегах: "Reliable Plumbing Services" и "in Lewisville, TX".
2. Berkeys. Title: "Lewisville Plumber 972-464-2460 Berkeys Plumbing Lewisville 24-Hour Plumbing Company". H1: "Lewisville Plumber".
3. Milestone. Title: "Lewisville, TX Plumbers - Milestone's Plumbing Service Near You!". H1: "Lewisville TX Plumbing".
4. Legacy. Title: "Plumbing Services in Lewisville, TX | Call for Expert Help". H1: "Plumbing Services in Lewisville, TX".
5. Roto-Rooter. Title: "Plumber in Lewisville, TX - 24/7 Plumbing Services | Roto-Rooter". H1: "Lewisville Plumbing, Drain & Water Cleanup Services".
6. Mother. Title: "Plumber in Lewisville with Same Day Service | Mother". H1: "Expert plumbers in Lewisville".
7. Trident. Title: "Plumber in Lewisville, TX | Trident Plumbing". H1: "Plumbers in Lewisville, TX".
8. All Metroplex. Title: "Home - METROPLEX". H1 нет.
9. Tempo Air. Title: "Plumbing in Lewisville, TX | Tempo Air". H1: "Lewisville Plumbing".
10. Imperial. Title: "Imperial Plumbing: Expert Plumbing Services". H1: "Imperial Plumbing" (ниже строка "Licensed Plumbing in Denton, TX").

#### 2.3. Темы H2, местные факты, цены, гарантия, приезд

| № | Компания | Темы H2 (коротко) | Местные факты, которые страница действительно даёт | Цены | Гарантия | Приезд |
|---|---|---|---|---|---|---|
| 1 | Lewisville Plumbing | 5 H2: отзыв (дважды), "мы здесь для вас", статьи, советы; услуги строками | "since 1992", лицензия словами без номера, адреса нет. Больше ничего | Нет. "Request Free Estimates" | Нет | "promptly respond ... within a 20-mile radius", "rapid response" |
| 2 | Berkeys | 1 H2, дальше H3: офис во Frisco, ремонт 24 часа, осмотр, repiping, прочистка, hydro jetting, канализация, бренды, города DFW | Нет. "over 35 years ... in Lewisville", обслуживают из Frisco, общая фраза про разрешения. Индексов нет (у Plano было семь) | Нет. 15% членам клуба | Только гарантия производителя tankless | "24 hours a day", "fast response times" |
| 3 | Milestone | 1 H2, остальное жирные строки: услуги, ремонт в тот же день, 24/7, канализация, прочистка, водонагреватели, как выбрать | Нет. Пишет, что сантехники прямо в Lewisville, но среди девяти офисов Lewisville нет | Нет. 15% членам клуба, "Price Match Guarantee" | "100% Satisfaction Guarantee", без срока | "same-day service", "ready to respond immediately" |
| 4 | Legacy | 11 H2: кто мы в Lewisville (с частыми проблемами), скидки города, газ, полив, засоры канализации, вода, нормы, Castle Hills, хозяева съёмного жилья, водосберегающие скидки, последние работы | Самая местная. Плиты, до середины 1960-х pier and beam; почти половина домов 1960 до 1980; чугун; высокое давление местами, особенно Castle Hills, норма 40 до 80 PSI, редуктор и расширительный бак; фундамент двигается, деревья. Скидки города, "leak adjustment", канализация по зимнему среднему. Atmos, счётчик газа в переулке. Полив два дня в неделю с 2014. Город не чистит линии жильцов с 03.2013. Вода Lake Lewisville плюс Dallas Water Utilities, "125.7 PPM". IPC, NCTCOG, разрешения. Castle Hills (абзац устарел). 58% съёмщиков. 13 ссылок на сайт города | Своих нет. Купоны в меню; Gold Plan снимает плату за вызов на 12 месяцев | Срока нет. Четыре обещания "Customer Service Guarantee" | "We will show up on time." |
| 5 | Roto-Rooter | 8 H2: город, затопление и сушка, аварийный сантехник, отзывы, частые поломки, округа, почему мы, статьи | Нет. 11 округов списком, адреса в Lewisville нет, лицензия с именем, PHCC | Нет. "$55 Off", без доплаты ночью и в выходные, рассрочка. Цена после осмотра | Нет | "24/7, 365 days a year"; в отзыве "about 10 minutes" (длительность работы) |
| 6 | Mother | H2: "Elite Service for An Evolving City", четыре района, услуги, отзывы из Lewisville, отзывы из DFW, FAQ, услуги, призыв | "over 100,000" жителей. Районы: Lakewood Hills (у Highway 423, 1980-е и 1990-е, чугун, медь со свищами, корни), Vista Ridge (у SH 121, медиана 1993, PEX), Castle Hills (с 1997, 2,900 акров, slab leaks от движения грунта), Highland Lakes (центр, медиана 1993). Жёсткая вода словами. Офиса в Lewisville нет | Нет | Да: "6-year parts and labor warranty" на водяную линию, "20 year warranty" на бестраншейный ремонт; "100% Guaranteed" | "Get Same Day Service!", "restore hot water by dinner"; в отзыве из Keller "in less than one hour" |
| 7 | Trident | Форма, "Expert Lewisville Texas Plumbers", услуги, частые проблемы (slab leak, водонагреватель, трубы, газ), почему мы, отзывы, новости, города | Одна фраза про MCL Grand Theatre. Блок "почему мы" про Frisco, опечатка "Lewis, TX". Офис во Frisco | Нет | Нет | Нет (в отзыве "within 24 hours") |
| 8 | All Metroplex | H1 нет. H2: о нас, услуги, отзывы, четыре заголовка статей блога | "local plumbing company in Lewisville", "since 2010", номер лицензии мастера, часы. Адреса нет | Нет. "upfront pricing guide", скидка на несколько работ | "satisfaction guaranteed", без срока | "same day appointments ... subject to availability"; в отзывах часы |
| 9 | Tempo Air | Шесть частых проблем (кран, давление, унитаз, засор, температура, счёт за воду), услуги, FAQ; в подвале H2 с офисом | Нет. Офис в Irving | Нет. FAQ: цена зависит от ремонта | Только гарантия производителя | Нет |
| 10 | Imperial | H2: услуги, о компании, чем отличаемся, почему доверять, отзывы | Офис 171 S Railroad St, Lewisville 75057 (только в подвале), второй в Denton. Текст под H1 про Denton, в коде всплывающее окно про Fort Worth | Нет | Нет | "Same Day Service" (окно); аварийная служба 8:00 до 20:00, а в окне "24/7" |

Сводка по трём последним столбцам:

- Своих цен в цифрах не даёт никто. Купоны и скидки: Roto-Rooter, Legacy, Berkeys, Milestone. Плату за вызов в цифрах не называет никто.
- Срок гарантии называет одна страница (Mother: 6 лет на водяную линию, 20 лет на бестраншейный ремонт). "Guarantee" без срока: Milestone, Legacy, All Metroplex.
- Время приезда в минутах или часах в своём тексте не обещает никто. "Same day" в своём тексте: Milestone, Mother, All Metroplex, Imperial. Цифры минут и часов только в отзывах клиентов (Roto-Rooter, Mother, Trident, All Metroplex).
- Ссылки на официальные страницы ставит одна страница, Legacy, зато сразу 13 на сайт города и ещё EPA, NCTCOG, municode. В Lewisville наша ссылка на страницу города не будет единственной, в отличие от Plano.

### 3. Какие местные факты не называет никто

Проверено поиском слов по всем десяти сохранённым текстам, вместе с меню и подвалом.

1. Манометр и редуктор. Норму 40 до 80 PSI и высокое давление местами (особенно Castle Hills) пишет только Legacy, одной фразой; у Mother только отзыв клиента про редуктор. Что показывает манометр в домах Lewisville, где стоит редуктор, сколько служит, не пишет никто. Слов "valve box" и "meter box" нет ни у кого.
2. Проверка утечки по счётчику. Legacy пишет про счёт и "leak adjustment", но как самому проверить счётчик, не объясняет никто.
3. Разрешения по делу. "Permit" только у Berkeys (общая фраза) и Legacy (общие правила, регистрация в городе). На какую работу в Lewisville нужно разрешение и что смотрит инспектор, не пишет никто; слов "inspector" и "water heater permit" нет.
4. Ремонт под плитой. "Tunnelling, Excavation and Backfill" одной строкой в списке у Lewisville Plumbing, и всё. Слов "braze", "type L", "post-tension", "sleeve" нет ни у кого.
5. Глина. Слова "clay" нет ни у кого (Legacy: движение фундамента и деревья; Mother: "soil movement" в Castle Hills).
6. Трубы по годам своими словами. Только Legacy (1960 до 1980, чугун) и Mother (четыре района). "Galvanized", "polybutylene", "CPVC", "Old Town" нет ни у кого.
7. Канализация до города. Legacy: город с 2013 года не чистит линии жильцов, после врезки линия городская. Где ревизия и как ищут запах дымом, не пишет никто: "cleanout" и "smoke test" нет.
8. Полив и обратный клапан. "Sprinkler" нет ни у кого; backflow только строкой у Imperial и пунктом меню у Roto-Rooter. Ограничения полива только у Legacy.
9. Мороз. В своём тексте страницы нет ни у кого: два заголовка статей в блоге All Metroplex и одна фраза в FAQ Mother.
10. Водонагреватель на чердаке, поддон, клапан T&P. "Attic" только в отзыве у Mother (клиент из Keller), "drain pan" нет. Расширительный бак одной фразой у Legacy.
11. Сток кондиционера, врезанный в слив раковины. В своём тексте нет ни у кого; один отзыв у Mother из Lewisville (май 2026) упоминает такую врезку.
12. Хлор и резина. "Chlorine" и "chloramine" нет ни у кого.
13. Настоящие вызовы. Ни одного рассказа о работе в Lewisville в своём тексте. У Legacy четыре подписи к фото без текста ("PRV Install", "Gas Water Heater Replacement", "Water Leak", "Electric Water Heater Replacement"), у Mother 23 отзыва из Lewisville.
14. Плата за вызов. В цифрах нет ни у кого. Наше правило ($49 в будни, засчитывается в ремонт, цена до начала работ) будет единственным.
15. Индексы, дороги, ориентиры. Индексов Lewisville нет ни у кого (только адрес офиса Imperial, 75057). "35E" нет. Дороги только у Mother (Highway 423, SH 121), ориентир только у Trident (MCL Grand Theatre).
16. Человек с лицом и рассказом. Нет ни у кого; имя держателя лицензии строкой в подвале у Berkeys, Roto-Rooter, Tempo Air. Блок с Денисом будет редкостью.

Уже занято, не "только наше": источник воды и жёсткость (Legacy с цифрой, Mother словами), районы (Mother четыре, Legacy Castle Hills), норма 40 до 80 PSI (Legacy), скидки города и "leak adjustment" (Legacy), газ Atmos (Legacy), годы постройки (Legacy, Mother), ссылки на сайт города (Legacy).

Важно: это список того, чего нет у конкурентов. Факты для нашей страницы приходят от Дениса или с официальных страниц. Цифры Legacy и Mother (125.7 PPM, Lake Lewisville, полив с 2014, линии с 2013, Castle Hills, население) это их слова, я их не проверял, часть устарела.

### 4. Длина, разделы, FAQ

Длина основного текста по возрастанию: 334, 457, 758, 983, 1 046, 1 127, 1 377, 1 389, 1 971, 2 714 слов. Середина около 1 090, среднее около 1 220. Без отзывов: середина около 860, среднее около 940. Наша нынешняя страница (1 458) длиннее восьми из десяти; длиннее только Legacy и Mother (у Mother две трети это отзывы). 2 500 слов своего текста сделают нашу страницу самой длинной в выдаче.

Три типа страниц:

- Шаблон "список услуг" (Berkeys, Milestone, Trident, Tempo Air): H1, вступление, по абзацу на услугу, "почему мы", города. Местного нет или одна фраза. Berkeys почти дословно повторяет свои страницы Plano и Little Elm (после замены города совпадает 91 и 95 процентов текста).
- Сильные местные (Legacy: факты о городе и ссылки на город; Mother: районы и 23 отзыва из Lewisville) и национальный шаблон с отзывами (Roto-Rooter).
- Главные небольших компаний (Lewisville Plumbing, All Metroplex, Imperial): 334 до 1 127 слов, о Lewisville почти ничего.

Почти у всех: значки "licensed, insured, 24/7", "почему мы", услуги ссылками. Tankless у девяти из десяти, hydro jetting у пяти, repiping у четырёх, рассрочка или клубная карта у пяти. Карта Google (встроенная или ссылкой) в коде у четырёх: Berkeys, Mother, Trident, All Metroplex. "Lewisville" в H2: у Legacy, Roto-Rooter и Mother по шесть, у остальных один или два, у Imperial ни одного.

FAQ есть на двух страницах из десяти, всего 8 вопросов. У Mother вопросы стоят тегами H3 (у нас только жирным текстом), у Tempo Air это раскрывающиеся строки. Разметка FAQPage только у Mother. Вопросы дословно:

Mother Modern Plumbing (3):
- "Is Mother open on weekends and holidays?"
- "What should I do in a plumbing emergency?"
- "What is trenchless sewer repair and does it work?"

Tempo Air (5):
- "How Much do Plumbing Services Cost in Lewisville, Texas?"
- "Why Do I Have Such Low Water Pressure in My Lewisville home?"
- "Why Are My Recent Lewisville Water Bills Increasing"
- "Why Is My Kitchen Sink Leaking?"
- "How Long Do Water Heaters Last?"

Ни один вопрос не про особенности Lewisville: в трёх город вставлен в общий вопрос, ответы в одну строку.

### 5. Шаблоны title и H1

Title:

- "Plumber in Lewisville, TX" в начале: Roto-Rooter, Trident; Mother "Plumber in Lewisville" без TX.
- "Plumbing (Services) in Lewisville, TX": Legacy, Tempo Air. "Lewisville (TX) Plumber(s)" в начале: Berkeys, Milestone. Lewisville Plumbing: "Plumbing and Water Heater Services | Lewisville, TX".
- Без города: All Metroplex ("Home - METROPLEX"), Imperial. Город в title у восьми из десяти.
- Хвосты: время ("24/7", "Same Day Service", "24-Hour"), телефон (Berkeys), "Near You" (Milestone), "Call for Expert Help" (Legacy). Сочетания "Plumber Lewisville TX" без "in" нет ни у кого; наш нынешний title: "Plumber Lewisville, TX | Water Leaks, Slab Leaks & Faucet Repair".

H1:

- С городом у восьми из десяти. Plumber или plumbers у трёх ("Lewisville Plumber", "Expert plumbers in Lewisville", "Plumbers in Lewisville, TX"), plumbing у пяти ("Lewisville TX Plumbing", "Plumbing Services in Lewisville, TX", "Lewisville Plumbing, Drain & Water Cleanup Services", "Lewisville Plumbing", "Reliable Plumbing Services in Lewisville, TX").
- Без города: Imperial (название компании); у All Metroplex H1 нет.
- H1 короткие, 2 до 6 слов, без услуги, проблемы или района. Наш нынешний H1 "Plumber in Lewisville, TX - Finding Leaks Before They Find Your Floors" длиннее всех и единственный говорит о деле.

## 4. Фото и клипы

Файла раздела для этой части не было: она написана при сборке. Источник: `docs/briefs/_shared/photos-by-city-after-recount.json` (204 записи архива: 143 фото и 61 видео; прочитан 3 октября 2026). Город «после пересчёта» в этом файле поставлен по границе города (basis "city boundary", 115 записей), по слову Дениса ("Denys's word", 43), оставлен как был ("as before", 19), снят, если место съёмки вне десяти городов (19), или придержан для Little Elm (8). Слово Дениса о городе работы главнее проверки по карте. Координат в файле нет, и в брифе их нет. Сверено с `docs/briefs/_shared/cities-free-photos-2026-10-03.md` (строка Lewisville: 0 фото, 0 клипов), с частью 1 (раздел 4) и с частью 8 (разделы 1 и 2.4).

### 4.1. Все файлы, у которых город после пересчёта Lewisville

**Таких файлов нет.** Ни одного фото и ни одного видео с городом Lewisville после пересчёта; до пересчёта (столбец city_before) Lewisville тоже не стоит ни у одного. Слово Lewisville в файле встречается только у двух записей, в столбцах planned_pages и flags: это фото фургона у офиса Frisco, которое Денис 1 октября 2026 разрешил ставить на страницы Celina и Lewisville, пока оттуда нет фото с работы.

| № | Вид | Дата | Город после пересчёта, основание | Что сказал Денис | Подпись (англ.) | Где стоит на собранном сайте | Отложено для | Пометки, дословно |
|---|---|---|---|---|---|---|---|---|
| 2 | фото | 2026-09-30 | Frisco, Denys's word | Фургон FPP Plumbing у офиса | FPP Plumbing van at the Frisco office | /plumber-frisco-tx/ (главное фото страницы Frisco) | / /contact/ /plumber-frisco-tx/; /plumber-celina-tx/; /plumber-lewisville-tx/ | Van plate blurred on every web version (tools/optimize_photos.py BLUR).; stand in for Celina and Lewisville until job photos from there (Denys, October 1, 2026): on those pages the alt must not name Frisco; hero of the Frisco page; taken at the Frisco office (Denys, October 2, 2026) |
| 4 | фото | 2026-09-30 | Frisco, Denys's word | Фургон FPP Plumbing у офиса | FPP Plumbing van at the Frisco office | нигде | /emergency-plumbing-services/ /; /plumber-celina-tx/; /plumber-lewisville-tx/ | stand in for Celina and Lewisville until job photos from there (Denys, October 1, 2026); taken at the Frisco office (Denys, October 2, 2026): on other city pages the alt must not name Frisco |

Что видно по таблице:

- Это не кадры из Lewisville, а временная замена по слову Дениса. Alt на странице Lewisville не должен называть Frisco (пометка в файле).
- Фото 2 уже главное фото страницы Frisco, и в `photos/captions-en.csv` его alt говорит "FPP Plumbing van with the Frisco phone number on it, parked at our Frisco office on Westridge Blvd": на борту телефон Frisco. Фото 4 нигде не стоит, его alt "FPP Plumbing 24/7 emergency plumbing van at the Frisco office, side view". Размытие номерного знака (`tools/optimize_photos.py`, BLUR) записано только для фото 2; виден ли знак на фото 4, файлы не говорят: проверить перед постановкой.
- Если Денис скажет, что Lewisville обслуживает офис Plano (часть 7), фургон с телефоном Frisco на первом экране будет спорить с этим; тогда замену лучше обсудить с ним.

Вне архива, но связано с Lewisville:

- Главное фото живой страницы и нынешней новой: фургон FPP у кирпичного двухэтажного дома, `/wp-content/uploads/2025/05/photo_2025-05-15_20-41-52-1024x576.jpg`, alt пустой. На борту телефон Plano ("980.899.7997"), спереди "M-38532" (лицензия на сайте M-44816). Город съёмки не известен; в архиве `photos/index.csv` этого кадра нет (часть 1, раздел 4). Вопрос про "M-38532" уже стоит в `docs/morning-report-2026-10-03.md`.
- Девять старых фото галереи с "in Lewisville, TX" в alt (часть 8, раздел 2.4; часть 1, таблицы, часть D): PRV в земле у счётчика (`photo_2024-12-24_18-56-20`), старый PRV с краном до замены (`18-55-45`) и новый после (`18-55-46`), газовый водонагреватель на 50 галлонов на чердаке (`18-53-33`), fill и flush valve унитаза (`18-54-10`), восковое кольцо (`18-54-52`), коробка крана стиральной машины на ProPress (`18-53-48`), disposal и слив (`18-55-22`), ProPress на линии водонагревателя (`18-54-31`). Их нет в `photos/index.csv`, город держится только на старом alt, и соседние кадры той же серии подписаны другими городами. По правилу CLAUDE.md фото, снятое в другом месте, не идёт на страницу города, пока Денис не назовёт работу.

### 4.2. Кандидаты по темам страницы

Темы взяты из живой страницы (часть 1), из запросов (часть 2) и из того, чего нет у конкурентов (часть 3). Правила из CLAUDE.md: история, названная по проблеме, сначала показывает проблему, потом ремонт; клип режется до пяти секунд, без звука, крутится сам; все картинки одного размера, 3:4; номерной знак и номер дома в кадре закрываются; фото другого города на страницу города не идёт, пока Денис не назовёт работу.

| Тема страницы | Файлы | Что с ними делать |
|---|---|---|
| Первый экран: фургон или работа в Lewisville | 4 (или 2) как временная замена | Своего кадра нет. Фото 4 свободно; 2 уже стоит главным на Frisco и несёт телефон Frisco. Нынешнее фото фургона с телефоном Plano и "M-38532" городом не подтверждено |
| Slab leak (лучшие места страницы: «slab leak repair lewisville» 200 показов, место 9.6) | нет | Ни одного кадра из Lewisville. Кадры slab leak архива сняты в других городах или без города (фото 45 стоит на главной и на странице slab leak, фото 162 на главной; клипы 77 и 78 сняты вне десяти городов). Тема на странице города: абзац со ссылкой; объём и фото по слову Дениса |
| Скрытая течь, счёт за воду, счётчик (H1, первый раздел, FAQ 1; leak detection с городом 312 показов) | нет | Ни одного кадра из Lewisville. Закон города о пересчёте счёта после скрытой течи (часть 6, city-e1) даёт повод для кадра счётчика с крутящимся индикатором, если он будет снят в Lewisville |
| Краны под раковиной, клапаны душа, смесители (H2 "Faucets, Valves, and Parts That Have Simply Aged") | нет | Ни одного кадра из Lewisville. Фото 23 и 25 (новые краны под раковиной, картридж Moen) без города, на страницу города не предлагаются |
| Водопровод во дворе (отзыв John Wilson, "service line in the front yard"; water line с городом 2,014 показов за 16 месяцев) | нет | Ни одного кадра из Lewisville |
| Засоры и главная линия (H2 "Drains That Keep Coming Back") | нет | Ни одного кадра из Lewisville. Если будет кадр с экрана камеры: закон города прямо называет проверку камерой лицензированного сантехника (часть 6, city-d3) |
| Давление и PRV (строка "Pressure that fades or feels too strong") | пара PRV из старой галереи (`18-55-45`, `18-55-46`) и `18-56-20`, вне архива | Только после слова Дениса, что работа была в Lewisville. Тогда это первая история страницы: сначала старый PRV, потом новый |
| Водонагреватель и расширительный бак | водонагреватель на чердаке и ProPress на его линии из старой галереи (`18-53-33`, `18-54-31`), вне архива | Только после слова Дениса о городе. Поправки города к установке (18 дюймов в гараже, поддон, сброс T&P, доступ на чердак, часть 6, city-b3) годятся для подписи к такому кадру |
| Унитаз, измельчитель, коробка стиральной машины | кадры старой галереи (`18-54-10`, `18-54-52`, `18-55-22`, `18-53-48`), вне архива | Только после слова Дениса. Коробка стиральной машины совпадает с работой из отзыва Allen Thong, но тот отзыв оставлен на профиле Frisco |
| Emergency, ночные вызовы | нет | Ни одного кадра из Lewisville |

В архиве 37 файлов без города (22 фото и 15 клипов: сняты вне десяти городов или город не определён). Как кандидаты для страницы Lewisville они не предлагаются: на странице города стоят работы из этого города (на странице Frisco все фото Frisco), а у этих файлов города нет; 19 из них по границе сняты вне десяти городов.

### 4.3. Чего не хватает: какие кадры просить у Дениса

1. Настоящее фото с работы в Lewisville или фургон FPP на улице в черте города. Вертикальный кадр, чтобы встал в размер 3:4; без номеров домов; номерной знак мы размоем. Это замена нынешнему главному фото и временной замене (2 или 4).
2. Если старая пара PRV из галереи снята в Lewisville: ещё кадр той же работы пошире (ящик счётчика, PRV в земле, манометр с цифрой после замены).
3. Скрытая течь в Lewisville: счётчик с крутящимся индикатором и то, что нашли (место течи, вскрытый участок, прибор на полу). Сначала проблема, потом ремонт.
4. Работа slab leak в Lewisville, если такая была: яма доступа или тоннель, пинхол на меди, спаянное место. Без своего кадра эта тема на странице только абзацем со ссылкой.
5. Манометр на уличном кране дома в Lewisville с цифрой давления и PRV там, где он стоит в этих домах (в ящике у счётчика в земле или в доме).
6. Кран под раковиной, который не поворачивается, или клапан душа, «до» и «после» (тема H2 про старую арматуру).
7. Водонагреватель в гараже или на чердаке в Lewisville, «до» и «после»: подставка 18 дюймов, поддон, сброс T&P, расширительный бак. Это ровно то, что перечисляют поправки города (часть 6, city-b3).
8. Водопровод во дворе от счётчика до дома: яма, лопнувший участок, новый участок.
9. Главная канализационная линия: кадр с экрана камеры или яма у тротуара. Если был случай, когда дефект оказался за краем тротуара и его чинил город, это готовая история под закон 16-99 и 16-100.
10. Работа в доме постарше в восточной части города, у старого центра (индекс 75057, там больше половины домов на одну семью построены до 1980 года), если такая была: старые краны, чугун, медь.

## 5. Отзывы: кандидаты

Файл раздела: `docs/briefs/lewisville/5-review-candidates.md`, вставлен целиком. Заголовок файла: «5. Отзывы: кандидаты для страницы Lewisville».

Полные списки рядом: `5-review-candidates-tables.md` (48 КБ): все 147 чистых отзывов с текстами, 183 не прошедших с причинами, запас за десяткой с текстами.

Раздел для брифа страницы `/plumber-lewisville-tx/`. На страницы ничего не поставлено, ни один файл проекта не изменён. `reviews/site-reviews.json` (файл от 10:04) и `reviews/site-ledger.md` (файл от 04:54) прочитаны 3 октября 2026 около 10:10; их этой ночью пересобирают, перед выбором прочитать ещё раз. Полные списки и запас с текстами: `5-review-candidates-tables.md` рядом.

### Коротко

- Отзывов, которые называют Lewisville, его улицу или район: **0**. Ни среди свободных, ни среди занятых, ни в ответах компании.
- Поэтому все десять кандидатов без места в тексте, каждый **не привязан к этому городу**: его могут предложить и другим городам, а стоять он может на одной странице.
- Свободных пятизвёздочных с текстом: 330. Все правила проходят 147 (вместе с двумя с живой страницы). Что чинили, называют 29, без двух с живой страницы 27.
- С живой страницы правила проходят John Wilson (водопровод во дворе) и Allen Thong (коробка крана стиральной машины). Serge Geshka называет Дениса ("Dennis").
- Живая страница обрезала текст John Wilson. На новом сайте нужен полный.
- Главные темы Lewisville в Search Console (slab leak repair и leak detection с названием города) чистыми отзывами почти не закрыты: про slab leak свободных ноль, про трудную течь один (Javeed N.).

### Откуда данные

- `reviews/all-reviews.csv`: 407 отзывов. Google 131 (профиль Plano 105, профиль Frisco 26), Thumbtack 249, Yelp 27.
- Занятые: 40 авторов на 14 страницах по `site-reviews.json` и `site-ledger.md` (двенадцать главной внутри, страницы Lewisville нет) и три резерва главной из задания.
- Старый сайт и придержанные: `reviews/ledger.md`, `reviews/ledger-decisions.csv`, `docs/state.md`, CLAUDE.md. Живая страница: `source/crawl/pages/plumber-lewisville-tx.json`.
- Тексты Google сверены с выгрузкой Google Takeout (`source/gbp-takeout/`): знак в знак, пять звёзд, даты и ссылки те же. Thumbtack сверен с `reviews/raw/thumbtack-reviews.json` (сбор 1 октября 2026), там же категория работы, которую выбрал клиент. Вживую этой ночью ни один отзыв не открывался.
- Запросы: `docs/cities-table-2026-10-03.md`, часть Lewisville (двадцать главных запросов за 3 месяца, 1 июля по 28 сентября 2026).

### Lewisville в отзывах: ноль

Искал во всех 407 строках архива (текст, ответ компании, тип работы, пометки), в `reviews/raw/` и во всех файлах отзывов выгрузки Google. Слова: "Lewisville", "Lewis"; индексы 75057, 75067, 75056, 75077 (из `docs/briefs/_shared/cities-official-place-names-2026-10-03.json`) и 75029; районы и улицы по памяти, список не официальный: Castle Hills, Vista Ridge, Old Town, Valley Ridge, Lakewood, Lake Vista, Timber Creek, Sun Valley, Wynnpage, Lakeland, Creekside, Hebron, Round Grove, Garden Ridge, Valley Pkwy, Main St, Mill St, Corporate Dr, Lake Lewisville. Официальный список районов города не открылся (по общему файлу cityoflewisville.com ответил 403; повторно не запрашивал).

Совпадений нет. Во всём архиве из мест названы только Plano, Frisco, Prosper, Carrollton, McKinney, "North Dallas", "Shops at Legacy" и "Frisco Lakes".

Вывод: заголовок живой страницы "What Lewisville Homeowners Say About FPP Plumbing" и строка "Real Google reviews from people who called us about a leak." файлами не подтверждаются.

### Сколько свободно и сколько чистых

| Шаг | Сколько |
|---|---|
| Всего отзывов | 407 |
| Пять звёзд | 396 |
| Минус 6 без текста и 10 копий Google на Thumbtack (кандидат только оригинал Google) | 380 |
| Минус 48 строк занятых: 43 человека (40 на новом сайте, три резерва главной; у четверых по два отзыва) и Lanessa A. с Yelp, она же Lanessa Arnold Jenkins | 332 |
| Минус 2 строки того же человека под другим именем: L W это Liane W. (leak detection), Rani C это Rani . (главная) | **330 свободных** |

Из 330: Thumbtack 227, Google Plano 69, Yelp 19, Google Frisco 15.

Отсеивают правила (строка может попасть в несколько причин): имя Дениса в любом написании 156; автор на другой странице старого сайта 36; другой город или место 14; "plumber near me" 8; суммы или слово fee 7; придержаны для другой страницы 5 (Ann Crawford, два отзыва, для expansion tank; Steve Fredrickson для water heaters и, судя по имени и дате, он же на Yelp как Steve F.; Quan Nguyen в запасе для hose bib).

Остаётся **147 чистых**: Thumbtack 116, Google Plano 21, Yelp 7, Google Frisco 3. Большинство короткие и общие ("Great job"). Работу называют 29: Google 6, Yelp 2, Thumbtack 21. Тексты всех 147 в файле таблиц, часть А; не прошедшие с причинами в части Б.

### Десять лучших кандидатов

Места не называет ни один. Порядок: сначала течи (главная тема живой страницы и запросов Lewisville), потом краны и смесители (на живой странице блок про angle stops и клапаны душа), потом засор, горячая вода, измельчитель. Работы не повторяются. Текст дословный, с опечатками автора. "Ещё где": место этого человека в десятке брифа Plano или Little Elm этой ночью (других готовых разделов отзывов в `docs/briefs/` на 10:10 нет).

| Место | Имя | Площадка | Профиль | Дата | Работа | Место в тексте | Цифра приезда | Текст дословно | Ссылка | Почему | Ещё где |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | Javeed N. | Thumbtack | листинг Plano | 2022-11-06 (November 2022) | Течь, которую трудно найти (Thumbtack: Leaking pipes) | нет, к городу не привязан | нет | "Response was immediate. They were able to troubleshoot a water leak that was hard to find. Very nice and pleasant to work with." | [листинг](https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760) | Единственный чистый отзыв про поиск скрытой течи, главную тему страницы. Нет слов plumber и названия компании, отзыв старый. | нет (у Plano в запасе) |
| 2 | Kevin N. | Thumbtack | листинг Plano | 2023-01-04 (January 2023) | Течь из ванной на втором этаже: вода из светильника на кухне и по стенам гаража | нет, к городу не привязан | нет ("the same day") | "These guys are life savers. I had a leak in an upstairs bathroom and water was coming out of my light fixture in the kitchen as well as down the walls in my garage. They came out the same day I contacted them and were able to diagnosis and fix the issue. I would and will be contacting them for any other plumbing work that I have." | [листинг](https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760) | Самая живая картина течи среди чистых, нашли и починили в тот же день, есть "plumbing work". | Plano 6, Little Elm 2 |
| 3 | Lily Chaskelmann | Google | профиль Plano | 2024-11-14 (November 2024) | Течь (без подробностей), обращались дважды | нет, к городу не привязан | ДА: "within 30 minutes" | "Excellent plumber. We've used FPP Plumbing twice already. Fixed everything we needed fixed and at reasonable prices. Explained everything really well before repairing. Most recently we had a leak and he showed up within 30 minutes!" | [ссылка](https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sChZDSUhNMG9nS0VJQ0FnSUQzbHJIRmRBEAE!2m1!1s0x0:0xccc66184bdaf3a93) | "Excellent plumber" и "FPP Plumbing", объясняют до ремонта, прямая ссылка. Работа названа общо. | Plano 8, Little Elm 5 |
| 4 | Alecia K. | Thumbtack | листинг Plano | 2023-01-07 (January 2023) | Лопнувшая труба в выходной (Thumbtack: Leaking pipes) | нет, к городу не привязан | нет ("same day (on a weekend)") | "We are so grateful that not did they come out same day (on a weekend) but also took care of the broken pipe and fixed the issue same day! Really appreciate their responsiveness and professionalism and would definitely use in the future if needed!" | [листинг](https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760) | Срочная течь в выходной, починено в тот же день. Опечатка "not did they" остаётся. | нет |
| 5 | David H. | Thumbtack | листинг Plano | 2023-01-05 (January 2023) | Течь смесителя душа и лопнувшая труба снаружи | нет, к городу не привязан | нет ("the same day") | "Was able to fit us in the same day and correctly fix the issues (leaking shower faucet and exterior broken pipe) and answer all questions. Will plan to use again for future plumbing needs" | [листинг](https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760) | Две работы, обе есть на живой странице, "plumbing needs". | Little Elm 6 (у Plano в запасе) |
| 6 | Eric H. | Thumbtack | листинг Plano | 2023-02-25 (February 2023) | Сломанный клапан душа (shower valve) | нет, к городу не привязан | нет | "Quick and easy! Fixed my broken shower valve - able to get the replacement from the local HD and then they were done!" | [листинг](https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760) | На живой странице "Shower valves that spin without shutting anything off": отзыв ровно про это. "HD" это Home Depot, слова клиента. Дефис обычный, не тире. | нет |
| 7 | A P | Google | профиль Plano | 2026-08-22 (August 2026) | Замена крана (какого, не сказано) | нет, к городу не привязан | нет | "Did a great job on our valve replacement, went above and beyond expectations!" | [ссылка](https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sCi9DQUlRQUNvZENodHljRjlvT25kbE1tNTJOVEp6UkZwUE0wbFZaa3R2YUVka1UzYxAB!2m1!1s0x0:0xccc66184bdaf3a93) | Свежий Google с прямой ссылкой, про краны. Всего 13 слов. | нет (у Plano в запасе) |
| 8 | Gorden C. | Thumbtack | листинг Plano | 2023-03-19 (March 2023) | Засор поздно в воскресенье (Thumbtack: Multiple drains, Clogging) | нет, к городу не привязан | нет | "Great work, reasonable and responsive. He came out late on a Sunday to clear a clogged pipe that had to get fixed. I would definitely use again." | [листинг](https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760) | Засор и вызов в нерабочее время, без сумм. На живой странице блок "Drains That Keep Coming Back". | нет |
| 9 | alex p | Google | профиль Plano | 2025-01-11 (January 2025) | Не было горячей воды в снежную бурю | нет, к городу не привязан | нет ("arrived promptly") | "FPP Plumbing provided exceptional service! They quickly responded to our call, arrived promptly, and fixed the issue fast when we had no hot water in this winter snow storm. Their team was professional, efficient, and thorough. Whether it’s plumbing repairs, drain cleaning, or water heater installation, FPP Plumbing delivers top-quality solutions. Highly recommend for reliable, quick, and expert plumbing services." | [ссылка](https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sChdDSUhNMG9nS0VJQ0FnSURmel9Qamh3RRAB!2m1!1s0x0:0xccc66184bdaf3a93) | Единственный чистый про горячую воду, дважды "FPP Plumbing". Вторая половина звучит как реклама. | Plano 9, Little Elm 3 |
| 10 | Sathya P. | Thumbtack | листинг Plano | 2023-11-04 (November 2023) | Замена измельчителя и течь под раковиной | нет, к городу не привязан | нет | "I had to get the garbage disposal, replaced and also fix the leak under the sink. Both jobs were completed." | [листинг](https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760) | Две работы под раковиной, обе на живой странице. Коротко и сухо. | нет |

Ссылки Google ведут на сам отзыв. У Thumbtack отдельной ссылки нет, ведёт на листинг, как на других страницах сайта. Подпись по правилу 11: Google "★★★★★ · Local Guide Level N · Month Year · Google" без города; Thumbtack "★★★★★ · Thumbtack · Month Year".

#### Оговорки

1. Шесть из десяти уже стоят в десятке или в запасе у Plano и Little Elm. Четверо (Alecia K., Eric H., Gorden C., Sathya P.) пока нигде не предложены.
2. Цифра приезда одна: Lily Chaskelmann, "within 30 minutes". Слова клиента, разрешены, аудитор отметит.
3. Thumbtack семь из десяти, шесть из них 2022 и 2023 годов. Чистых отзывов Thumbtack за 2024 по 2026 годы с названной работой в архиве нет. Свежие только Google: A P, alex p, Lily Chaskelmann.
4. Строка над отзывами на живой странице говорит "Real Google reviews". С отзывом Thumbtack её нужно менять. На Frisco строка: "Reviews from Frisco homeowners, word for word, with the links to the source."; для Lewisville слова "Lewisville homeowners" файлами не подтверждаются.
5. Уровень Local Guide у трёх кандидатов Google в файле пустой. Его читают в профиле автора перед постановкой.

### Запас за десяткой

Тексты в файле таблиц, часть В. Dr. Jalal Jalali (Google, кран стиральной машины, цифра "in less than an hour", повторяет работу Allen Thong); Michael V. (Thumbtack, коробка кранов в прачечной и уличный кран, тоже повтор); Marina Sexton (Google Frisco, September 2026, самый свежий, работа не названа); Mike C. (трубы под раковиной); Stacie B. (Yelp, уличный кран, цифра "within an hour"); Margo W. (большой засор); Ryan E. (унитаз); Laura B. (посудомойка); Rangsan L. (измельчитель и смесители).

### Три отзыва живой страницы Lewisville

Все трое есть в выгрузке Google, пять звёзд. На новом сайте ни один не стоит, среди двенадцати главной и резерва их нет. Переписанная страница города может оставить своих.

| Имя | Дата в Google | Профиль | Свободен | Имя Дениса | Деньги, жалобы, комиссия | Lewisville в тексте | Работа | Цифра приезда | Итог |
|---|---|---|---|---|---|---|---|---|---|
| John Wilson | 2025-05-29 (May 2025) | Plano | да | нет | сумм нет; есть "quote for labor" и "parts were separate" | нет | течь на водопроводе (service line) во дворе перед домом, ремонт на следующий день | нет ("that same day") | **Проходит**, с оговоркой про цену. Можно оставить. |
| Allen Thong | 2026-04-02 (April 2026) | Frisco | да | нет | нет ("Reasonable price" без цифры) | нет | коробка крана стиральной машины, трубы вырезаны и заменены | нет | **Проходит.** Можно оставить. Короткий, без слов plumber и названия компании. |
| Serge Geshka | 2025-03-27 (March 2025) | Plano | да | ДА: "Dennis was quick to respond" | нет | нет | течь подводки (supply line leak) | нет | Не проходит только из-за имени Дениса. |

Тексты дословно, по выгрузке Google:

- **John Wilson**: "I had a non emergency leak that required a difficult repair on my service line in the front yard. The technician came out to the house that same day and assessed what work was required and gave me the quote for labor. I was told that parts were separate and would provide me with receipts for the parts required. Repairs were made the following day with minimal outage time. The technician was very professional and friendly while answering and addressing all my questions and concerns." [ссылка](https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sCi9DQUlRQUNvZENodHljRjlvT2xKWmVGZFRhRXhZTUU5d1JURnhNMlk0ZVZkRU5WRRAB!2m1!1s0x0:0xccc66184bdaf3a93)
- **Allen Thong**: "Washer valve box and pipe cutting/ replacement - Reasonable price, great service, good attitude!" (в Google после "cutting/" перенос строки) [ссылка](https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sCi9DQUlRQUNvZENodHljRjlvT25odVRqTnpZVkpCZWpCVlRFRjZTR0ptZUd0WGQxRRAB!2m1!1s0x0:0xe28e4c9b59df630f)
- **Serge Geshka**: "Had a great experience with FPP Plumbing. I called them for a supply line leak, and Dennis was quick to respond. He was very knowledgeable, professional, and polite throughout the process. The repair was done efficiently, and I really appreciated the quality of service. Highly recommend them for any plumbing needs!" [ссылка](https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sChZDSUhNMG9nS0VJQ0FnTUR3dWUzOEZnEAE!2m1!1s0x0:0xccc66184bdaf3a93)

Что ещё видно:

- **Текст John Wilson на живой странице обрезан**: кончается словами "Repairs were made the following day." В Google дальше "with minimal outage time. The technician was very professional and friendly while answering and addressing all my questions and concerns." Отзыв не правят, на новой странице нужен полный текст.
- **John Wilson и правило о цене.** "gave me the quote for labor. I was told that parts were separate" можно прочитать как цену из двух частей, а правило сайта: цена называется до работы, и одобренная цена стоит в счёте. Денег и жалобы нет; решение за Денисом.
- **John Wilson и John W. с Thumbtack** (декабрь 2022, смеситель): один ли это человек, по файлам не понять. Если John Wilson остаётся, John W. на другие страницы лучше не ставить без проверки.
- Работа John Wilson совпадает с темой `/water-lines/`, там стоят william mckinney и Kathryn Kim. Повтора автора нет.
- **Allen Thong** оставил отзыв на профиле Frisco: ссылка откроет карточку Frisco. Уровни на живой странице: Allen Thong Local Guide Level 2, John Wilson и Serge Geshka Level 4; в архиве они не записаны, перед постановкой читают в профиле.
- **Serge Geshka** кроме имени Дениса сильный (дважды компания, "supply line leak", "plumbing needs"). Оставить можно только словом Дениса как исключение.
- Lewisville ни у кого из трёх не назван, подпись по правилу 11 без города.

### Каких работ не хватает

Проверено по всем 330 свободным, поиск по словам в тексте с ручной проверкой совпадений. Темы с живой страницы и из запросов Lewisville.

| Работа | Свободных | Чистых | Что мешает |
|---|---|---|---|
| Slab leak, течь под фундаментом | 0 | 0 | Все отзывы про slab leak (Saman Attar с копией на Thumbtack, Steven Cossettini, Oksana Toporina) стоят на slab leak и leak detection нового сайта. Главный пробел: из двадцати главных запросов Lewisville за 3 месяца шесть про slab leak repair с городом. |
| Скрытая течь, которую трудно найти | 2 | 1 (Javeed N.) | Gopi V. (течь у фланца унитаза) с именем Дениса. Про счёт за воду, главный заход живой страницы, отзывов нет совсем. |
| Водопровод во дворе, главный кран дома | 3 | 1 (John Wilson, живая страница) | Chris V. (лопнул главный кран на входе в дом) с именем Дениса; Inna Kravchenko (течь в переднем дворе) с "plumber near me". |
| Angle stop, краны под раковиной | 2 | 0 | Scott Waymack ("angle stop") и Raghu T. ("valves under sink") оба с именем Дениса. Есть только общий "valve replacement" (A P). |
| Главная канализационная линия, камера | 4 | 0 | Bo Wang с именем Дениса; Сергей Кравченко с "Best plumber near me"; Jose Walle с именем Дениса и Plano; Maksym Basovskyi на старой странице The Colony. |
| Водонагреватель | 11 | 1 (alex p, без замены) | Остальные с именем Дениса, другим городом, "plumber near me" или на старых страницах других городов. |
| PRV, давление | 5 | 0 | Ксенія и Megan E на старой странице PRV, Виктория Стехина и Inna Kravchenko с "near me", Elnard KA с именем Дениса. |
| Расширительный бак | 2 | 0 | Jan Shangle (Frisco Lakes и комиссия 2.99%), funny warner f ("plumber near me"). |
| Backflow, спринклеры | 0 | 0 | Отзывов нет. |

Что среди кандидатов есть: течи (скрытая, со второго этажа, лопнувшие трубы), смеситель и клапан душа, замена крана, засор, горячая вода, измельчитель и течь под раковиной; с живой страницы водопровод во дворе и коробка крана стиральной машины.

### Если выбирать четыре сейчас

Предложение, выбор за другим чатом и за Денисом.

- John Wilson с живой страницы, полный текст (водопровод во дворе).
- Allen Thong с живой страницы (коробка крана стиральной машины).
- Javeed N. (течь, которую трудно найти; ближе всех к теме страницы).
- Kevin N. (течь со второго этажа). Если нужен Google со словами, которые ищут, вместо него Lily Chaskelmann (одна цифра приезда). Оба стоят и в десятках Plano и Little Elm.

Три Google и один Thumbtack (или два и два), четыре разные работы.

### Вопросы Денису

1. Ни один отзыв не называет Lewisville. Были ли работы John Wilson (водопровод во дворе), Allen Thong (коробка крана стиральной машины) и Serge Geshka (течь подводки) в Lewisville? От этого зависит строка над отзывами.
2. Serge Geshka называет вас ("Dennis"). Снимаем или оставляем как исключение?
3. John Wilson пишет "gave me the quote for labor. I was told that parts were separate". Ставим полный текст как есть или ищем замену?
4. Были ли недавно работы в Lewisville, особенно slab leak или поиск течи? Если такой клиент сам оставит отзыв с названием города, он пойдёт на эту страницу.
5. Можно ли ставить на Lewisville отзыв с Thumbtack, если строка над отзывами сейчас говорит "Real Google reviews"?

## 6. Официальные факты

Четыре файла раздела вставлены целиком. Сначала (6.0) списки «что можно брать» и «чего нельзя» из двух файлов перепроверки, потом два файла фактов (6.1 и 6.2), потом остальное из файлов перепроверки (6.3 и 6.4). Заголовки файлов опущены на два уровня.

Рядом лежат: `6a-official-city-quotes.md` (полные цитаты по номерам фактов города), папка `work-6a` (28 файлов: тексты источников, у каждого в первой строке адрес и дата), `6b-zip-and-age-tables.md` (десятилетия по отдельности, жильё владельцев, раскладка земли), папки `work-6b` и `work-6b-verify` (выписки из файлов Census и USPS, расчёты площади).

Главное для автора: сайт города cityoflewisville.com отвечает 403, поэтому законы прочитаны напрямую в своде Municode, а страницы и памятки города в копиях Internet Archive; пункты «архив» утром сверить в обычном браузере. Из 45 фактов города подтверждено 43, неверны city-h1 и city-h4; все цифры Census и USPS подтвердились.

### 6.0. Проверенные списки: что можно брать и чего нельзя

#### Город (из `6a-official-city-verified.md`): Можно использовать в брифе

Всё ниже подтверждено; пункты "архив" перед публикацией сверить с живым сайтом.

- **a1, a2, a3, a4, a5, a8**: регистрация в городе, лицензия responsible master plumber, без платы, на год, без регистрации нет разрешения. Лицензия в тексте только словами правил: "our Responsible Master Plumber license, M-44816".
- **b1** только первая часть: разрешение нужно; работа до разрешения стоит лишней платы "investigation fee".
- **b2, b3, b5, b10, b12, g1, g2**: разрешение и Plumbing Final на водонагреватель, поправки к установке, канализация (12 и 4 дюйма), фундамент, пять работ штата без разрешения, кодексы 2021 года.
- **b7, b8, h2**: разрешение на backflow, защита на поливе, проверка тестером. Только по правилу: мы меняем узел, кто проверяет, не называть, одна фраза "Once the new assembly is in, it gets tested and the test report goes to the city."
- **c1**: инспекцию заказывают через портал города MGO Connect (без часов).
- **d1, d2, d3, d5, h5**: граница ответственности по воде и канализации; засор всегда за хозяином, ремонт до края тротуара, дальше город после проверки камерой.
- **d4**: только как основание совета закрывать главный кран дома; пересказ закона на странице по решению Дениса.
- **e1, e2 (исправленный), e3, e4, h3**: пересчёт счёта после скрытой течи, сигнал Suspected Leak, советы при низком давлении.
- **f1**: "158.5 ppm, average, 2024 Water Quality Report", с годом и единицей.
- **f2, f3** без запрещённых имён: своя станция на Lewisville Lake и покупная очищенная вода, в том числе от Upper Trinity Regional Water District.

#### Город (из `6a-official-city-verified.md`): Нельзя использовать (или только для внутренних заметок)

- **b1, вторая половина** "исключения для срочной работы нет": не доказано.
- **b4, b6, b9, b11**: это отсутствие строки, а не правило. На странице не писать "в Льюисвилле на это разрешение не нужно" и не писать обратное.
- **a6** суммы страховки (100,000) и **таблица платежей**: денежные цифры города на страницу не ставить; памятка только архивная.
- **a7, f2, f3** в исходных словах: запрещённые имена (окружное ведомство, водоканал и город соседа, чужие озёра).
- **c2, c3**: часы и окно приезда инспектора. Источники города спорят между собой, а время на странице легко прочитать как наше обещание по времени.
- **f4, f5, f6**: внутренние заметки, на страницу не нужны.
- **h1, новое 1 и 2**: старые страницы 2017 и 2021 годов. Не подавать как действующий совет города. Совет 2017 года про капающие краны совпадает со словами Дениса о морозе (капают краны в доме), но писать его надо его словами, без ссылки на город. Суммы платы 2021 года не ставить.
- **h4 и 20 psi**: условие чрезвычайного плана, к давлению в доме отношения не имеет; на страницу не ставить, цифр давления в сети города нет.

#### Индексы и возраст домов (из `6b-zip-and-age-verified.md`): Что можно брать в бриф

Все ниже подтверждено мной по официальным источникам 3 октября 2026.

1. Индексы с доставкой почты у отделения LEWISVILLE: 75057, 75067, 75077 (USPS, ZIP Locale Detail, file updated 10/01/2026). 75029 только абонентские ящики, класс P (USPS, тот же файл; смысл буквы P: USPS PostalPro "2727 Definitions").
2. 75056 это индекс почты THE COLONY, а не Lewisville (USPS). В слое карты города Lewisville у 75056 тоже стоит "The Colony".
3. Раскладка земли города по участкам ZCTA на 2020 год: 75057 35,37%, 75067 34,06%, 75056 18,78%, 75077 11,06%, 75010 0,37%, 75019 0,36%, 75007 почти ноль, 75065 только вода (Census, tab20_zcta520_place20_natl.txt).
4. Доли земли участков в черте Lewisville: 75057 98,2%, 75067 93,4%, 75077 29,0%, 75056 29,4% (тот же файл).
5. Земля города сегодня 105 523 422 кв. м против 95 851 124 в 2020 году (TIGERweb, слои ACS2024 и Current). Доли всей площади по участкам сегодня (33,0 / 27,1 / 23,3 / 9,5 / 6,5%) это расчет по карте Census, повторенный двумя людьми; в бриф только с пометкой "расчет".
6. Медианный год постройки жилья, ACS 2020-2024, таблица B25035: Lewisville city 1997 (±1); 75057 1995 (±3); 75067 1994 (±2); 75077 1994 (±2); 75056 2006 (±1). Жилье владельцев (B25037): Lewisville city 1996, 75057 1982 (±7). Ссылка для читателя, если нужна одна: https://data.census.gov/table/ACSDT5Y2024.B25035?g=160XX00US4842508 (через API data.census.gov я получил "1997", "1", "Lewisville city, Texas"; сам вид таблицы в браузере не открывал, браузер в эту ночь запрещен).
7. Доли по годам постройки (B25034), занятые дома на одну семью до 1980 года (B25127: Lewisville city 21,0%, 5 761 дом; 75057 52,8%) и доля съемного жилья 53,7% (B25036): все цифры из таблицы выше.
8. Для сведения автора, не для страницы Lewisville (городская страница не называет другие города): Frisco city 2009, Plano city 1993; дома на одну семью до 1980 года: Frisco 1,5%, Plano 24,1%.
9. Часть города в 75057 лежит к востоку от I-35E, в 75067 и 75077 в основном к западу: это расчет по карте Census (мой дал 100% к востоку для 75057, около 94% и 85% к западу для 75067 и 75077), подходит как подсказка для вопроса Денису, не как факт для страницы.

#### Индексы и возраст домов (из `6b-zip-and-age-verified.md`): Что нельзя брать

1. Дату аннексии Castle Hills (15 ноября 2021) и любые числа про Castle Hills: страница города не прочитана (403), есть только новости и выдержки поисковика.
2. Принимаемые почтой названия городов для 75056 и 75077: сервис USPS не прочитан.
3. Фразу о причине: "медиана Lewisville моложе Плано из-за земли, добавленной после 2020 года". Источник причин не называет. Можно писать только цифры: в Lewisville 23,1% жилья построено в 2010 году и позже (в Плано 13,7%).
4. Слой карты города "Zip Code Boundaries" как цитату "у города такие-то индексы": это копия данных Esri в аккаунте города, а не заявление города. Годится только как подтверждение файла USPS.
5. Цифры по 75077 и 75056 как описание Lewisville: большая часть земли этих участков принадлежит соседям.
6. 75010, 75019, 75007, 75065 как индексы Lewisville: город задевает их краем или только водой.

### 6.1. Факты города (файл `6a-official-city.md`)

Заголовок файла: «6, часть первая. Официальные факты города Льюисвилл (Lewisville)».

Проверено 3 октября 2026 года. Страница города: /plumber-lewisville-tx/.

#### Главная трудность: сайт города закрыт для наших инструментов

Сайт cityoflewisville.com (и все его страницы, и все его PDF) на любой запрос curl и WebFetch отвечает "Access Denied", ошибка 403 (защита Akamai). Обходить защиту нельзя, я не обходил. Поэтому:

1. **Законы города** я прочитал напрямую в официальном своде законов на library.municode.com (на него ссылаются страницы самого города). Это живой официальный текст, "codified through Ordinance No. 0854-26-ORD, July 6, 2026". Такие пункты стоят со статусом **found**.
2. **Закон штата** (TSBPE) и сайт водного округа UTRWD открылись напрямую: **found**.
3. **Страницы и памятки города** я видел только в копиях Internet Archive (web.archive.org), снятых с марта 2025 по сентябрь 2026 года. Это не живая страница, поэтому статус у них **could_not_open**, а слова из копии стоят в кавычках с пометкой "архив" и датой копии. Утром их надо сверить с живым сайтом в обычном браузере. Номер версии в адресе каждого PDF тот же, на который ссылались страницы города в 2026 году.

Тексты всего прочитанного лежат рядом, в папке work-6a (у каждого файла в первой строке адрес и дата). Полные цитаты по номерам: файл 6a-official-city-quotes.md.

#### Главное за минуту

1. Сантехническая компания регистрируется в городе (закон, раздел 4-551). С сантехников плату за регистрацию не берут, срок 1 год (раздел 4-555). Без регистрации разрешения не дают.
2. Сантехнический кодекс: International Plumbing Code **2021** года с поправками города (закон 0617-23-ORD от 6 ноября 2023). Для домов International Residential Code 2021.
3. Замена водонагревателя: разрешение и финальная инспекция "Plumbing Final" (памятка города, архив).
4. Инспекция заказывается в MGO Connect: на следующий день, если заявка до 3 p.m.; на понедельник до 10 a.m. пятницы (архив).
5. Вода: город отвечает до счётчика, от счётчика до дома отвечает хозяин (закон 16-237 и страница города, архив).
6. **Канализация, сильный местный факт:** засоры от дома до врезки в городскую трубу прочищает хозяин, где бы засор ни был. Ремонт: хозяин от дома до края тротуара (или края дороги, или края переулка), а дефект между этим краем и городской трубой город после проверки чинит бесплатно. Проверка камерой лицензированного сантехника для этого прямо названа в законе (16-99, 16-100). С 1 марта 2013 года город сам канализацию у домов не прочищает (архив).
7. Пересчёт счёта после скрытой течи есть (закон 16-300): раз в 12 месяцев, ремонт в течение 30 дней, заявка в течение 60 дней со счётами за ремонт.
8. Жёсткость: 158.5 ppm, среднее, отчёт о воде за 2024 год (архивная копия). Отчёт за 2025 год проверить не удалось.
9. Вода: своя станция на озере Lewisville Lake плюс покупная вода от UTRWD и от водоканала соседнего крупного города (имя на странице не писать, см. ниже).

#### Сводная таблица

| id | Вопрос | Что говорит официальный источник, коротко | Статус | Источник |
|---|---|---|---|---|
| city-a1 | Нужна ли регистрация | Да, для всех, чья работа требует лицензии штата, в том числе сантехников | found | S1 |
| city-a2 | Что требует закон от сантехников | Лицензия "responsible master plumber" штата у исполнителя или у ответственного лица фирмы | found | S1 |
| city-a3 | Плата и срок | Сантехники освобождены от платы; регистрация на 1 год; продление новой заявкой | found | S1 |
| city-a4 | Без регистрации | Разрешение не выдают; с просроченной регистрацией инспекции могут поставить на паузу | found | S1 |
| city-a5 | За что приостанавливают | В том числе: не заказал финальную инспекцию до истечения разрешения | found | S1 |
| city-a6 | Памятка о регистрации | Сантехник: страховой сертификат и номер лицензии, плата "-"; страховка от 100,000, держатель сертификата City of Lewisville; заявка в MGO Connect | could_not_open | S10 |
| city-a7 | Хозяин делает сам | Хозяин в своём доме (homestead) от регистрации освобождён | found | S1, S4 |
| city-a8 | Закон штата о регистрации | Регистрироваться надо; платы за регистрацию сантехник не платит | found | S4 |
| city-b1 | Общее правило | Разрешение нужно на работы, "which includes ... plumbing"; работа до разрешения: "investigation fee" в размере платы за разрешение [Сборка: подтверждено с поправкой, см. 6.3, city-b1] | could_not_open | S11, S2 |
| city-b2 | Замена водонагревателя | Разрешение нужно, инспекция "Plumbing Final" | could_not_open | S12 |
| city-b3 | Местные правила для водонагревателя | Гараж: источник огня на 18 дюймов от пола; поддон; чердак 20x30 дюймов и лестница от 300 lb; сброс T&P; не в кладовке | found | S2, S3 |
| city-b4 | Линия от счётчика до дома | Чинить обязан хозяин, по требованиям города; отдельной строки о разрешении нет | not_on_official_page | S5, S13 |
| city-b5 | Канализационная линия | Делёж ремонта по краю тротуара; отдельной строки о разрешении нет, "All city codes and ordinances must be followed" | not_on_official_page | S6, S13 |
| city-b6 | Замена PRV | Нигде не названа | not_on_official_page | S2, S3, S13 |
| city-b7 | Обратный клапан на поливе | Разрешение на любой backflow; проверка лицензированным тестером до запуска, отчёт за 10 рабочих дней | found | S7, S2 |
| city-b8 | Памятка про полив | Разрешение, клапан проверяет лицензированный тестер, инспекция "Irrigation Final" | could_not_open | S14 |
| city-b9 | Ремонт под плитой | Нигде не назван | not_on_official_page | S2, S3, S13 |
| city-b10 | Ремонт фундамента | Разрешение на "ALL foundation repair", проект инженера; о тесте труб ни слова | could_not_open | S15 |
| city-b11 | Список работ без разрешения у города | Своего списка по сантехнике нет; в FAQ только "Cosmetic projects" [Сборка: подтверждено с поправкой, см. 6.3, city-b11] | not_on_official_page | S16, S2 |
| city-b12 | Что без разрешения по закону штата | Ремонт течей, замена смесителей кухни и умывальника, "ballcocks or water control valves", измельчителя, унитаза | found | S4 |
| city-c1 | Как заказать инспекцию | Только онлайн в MGO Connect; до 3 p.m. на завтра; на понедельник до 10 a.m. пятницы | could_not_open | S17, S12, S16 |
| city-c2 | Время приезда инспектора | Звонить назначенному инспектору утром в день инспекции; на двух страницах два разных окна | could_not_open | S17, S16 |
| city-c3 | Часы инспекций | Monday-Friday: 7:00 a.m. - 3:30 p.m. | could_not_open | S17 |
| city-d1 | Граница по воде, закон | Хозяин чинит линии "from the meter loop connection into the residence" | found | S5 |
| city-d2 | Граница по воде, страница города | Город держит трубы и линию до счётчика; от счётчика до дома отвечает клиент | could_not_open | S18 |
| city-d3 | Граница по канализации | Засоры хозяина до врезки; ремонт делится по краю тротуара; город чинит свою часть бесплатно после проверки | found | S6 |
| city-d4 | Можно ли трогать ящик счётчика | Без разрешения директора открывать или закрывать крышку ящика счётчика и кран нельзя, кроме пожара | found | S5 |
| city-d5 | Свинец в линиях | "The vast majority" линий города и частных не свинцовые | could_not_open | S19 |
| city-e1 | Пересчёт счёта после течи | Есть, за скрытую течь, раз в 12 месяцев | found | S8 |
| city-e2 | Условия и бумаги | Рост больше 100 процентов по двум меркам; ремонт за 30 дней; заявка за 60 дней; счета за ремонт [Сборка: уточнено перепроверкой, см. 6.3, city-e2] | found | S8 |
| city-e3 | Страница города о пересчёте | Коротко то же самое | could_not_open | S20 |
| city-e4 | Сигнал о течи от умного счётчика | "Suspected Leak": сигнал, если вода течёт без остановки 24 часа | could_not_open | S21 |
| city-f1 | Жёсткость | 158.5 ppm, "Average Level (ppm)", отчёт "Water Quality Report 2024" | could_not_open | S22 |
| city-f2 | Откуда вода, слова отчёта | Своя станция на Lake Lewisville плюс покупная вода DWU и UTRWD | could_not_open | S22 |
| city-f3 | Откуда вода, страница станции | Lewisville Lake, больше 20 MGD; покупная вода добавляется | could_not_open | S23 |
| city-f4 | Отчёт за 2025 год | Не проверен: на архивной странице (февраль 2026) последний отчёт 2024 года | could_not_open | S24 |
| city-f5 | Жёсткость в grains per gallon | В отчёте города только ppm | not_on_official_page | S22 |
| city-f6 | Жёсткость у поставщика UTRWD | В отчёте UTRWD за 2025 год строки hardness нет | not_on_official_page | S25 |
| city-g1 | Сантехнический кодекс | 2021 International Plumbing Code с приложениями C, D, E и поправками города | found | S2, S11 |
| city-g2 | Кодекс для домов | 2021 International Residential Code с поправками | found | S3 |
| city-h1 | Страница про мороз | Не нашёл ни поиском, ни в архивном списке страниц сайта [Сборка: неверно по перепроверке, нашлись две старые страницы города, 2017 и 2021 годов; см. 6.3, city-h1] | could_not_open | S13 |
| city-h2 | Проверка обратных клапанов | Проверка при установке и раз в год, тестер с лицензией штата и регистрацией в городе | could_not_open | S26, S7 |
| city-h3 | Низкое давление | Советы города: фильтры, сетки кранов, только горячая вода, часть дома | could_not_open | S27 |
| city-h4 | Цифра давления в сети | Цифры в PSI на прочитанных страницах нет [Сборка: неверно по перепроверке, в законе 16-252 есть "20 psi" как условие чрезвычайного плана; цифры обычного давления в сети нет; см. 6.3, city-h4] | not_on_official_page | S27, S5 |
| city-h5 | Прочистка канализации городом | С 1 марта 2013 года город не прочищает линии у домов | could_not_open | S27 |

#### Источники (S)

Свод законов: https://library.municode.com/tx/lewisville/codes/code_of_ordinances (дальше "MC" плюс nodeId).

- S1. MC, глава 4, статья XV "Contractor Registration", разделы 4-551 до 4-559: ?nodeId=PTIICOOR_CH4BUBURE_ARTXVCORE . Файл work-6a/code-ch4-art15-contractor-registration.txt
- S2. MC, глава 4, статья IV, разделы 4-111, 4-112 (IPC 2021 и поправки): ?nodeId=PTIICOOR_CH4BUBURE_ARTIVPLST
- S3. MC, глава 4, статья II, разделы 4-31, 4-32 (IRC 2021 и поправки): ?nodeId=PTIICOOR_CH4BUBURE_ARTIIBUST
- S4. TSBPE, "Plumbing License Law", September 2025, разделы 1301.051 и 1301.551: https://tsbpe.texas.gov/wp-content/uploads/documents/TSBPE_PlumbingLicenseLaw(PlainView)_Sept2025.pdf
- S5. MC, глава 16, статья V, разделы 16-231, 16-236, 16-237: ?nodeId=PTIICOOR_CH16UT_ARTVWARE_DIV1GE
- S6. MC, глава 16, статья II, раздел 5, разделы 16-99, 16-100: ?nodeId=PTIICOOR_CH16UT_ARTIISASESY_DIV5PRRESESELICL
- S7. MC, глава 16, статья VII, раздел 16-355 (backflow): ?nodeId=PTIICOOR_CH16UT_ARTVIIBAPRDECRCOCO ; плюс S2, поправка 608.17.5
- S8. MC, глава 16, статья VI, раздел 16-300 "Adjustments for leaks": ?nodeId=PTIICOOR_CH16UT_ARTVIUTFECHRABIPR_DIV2RADEPR_S16-300ADLE
- S10. Архив. "Contractor Registration Requirements" (PDF от 16.09.2025): https://www.cityoflewisville.com/home/showpublisheddocument/21029/638936160795870000 (копия 07.10.2025)
- S11. Архив. "Building Services": https://www.cityoflewisville.com/for-business/building-services (копия 05.09.2026)
- S12. Архив. "Water Heater Requirements", "Updated 1/15/2025": https://www.cityoflewisville.com/home/showpublisheddocument/11301/638730765980570000 (копия 07.08.2025)
- S13. Поиск: WebSearch по сайту города и индекс Internet Archive по адресам сайта (слова winter, freez, leak, pipe, pressure). Живой сайт закрыт, поиск неполный.
- S14. Архив. "Irrigation System Requirements", "Updated 1/15/2025": https://www.cityoflewisville.com/home/showpublisheddocument/19006/638730769179700000 (копия 07.08.2025)
- S15. Архив. "Foundation Repair Requirements", "Updated 1/15/2025": https://www.cityoflewisville.com/home/showpublisheddocument/11557/638730767470870000 (копия 07.08.2025)
- S16. Архив. "FAQ for Building Services": https://www.cityoflewisville.com/for-business/building-services/faq (копия 18.06.2026)
- S17. Архив. "Building Inspections": https://www.cityoflewisville.com/for-business/building-services/building-inspections (копия 21.04.2026). Портал: https://www.mgoconnect.org/cp/portal (3 октября отвечает, содержимое грузится скриптом)
- S18. Архив. "Service Problems": https://www.cityoflewisville.com/our-services/utility-service-information/your-water-account/service-problems (копия 17.05.2026)
- S19. Архив. "Lead Service Line Inventory": https://www.cityoflewisville.com/city-hall/city-departments/public-services/lead-service-line-inventory (копия 16.05.2026)
- S20. Архив. "Customer Assistance": https://www.cityoflewisville.com/our-services/utility-service-information/your-water-account/customer-assistance (копия 17.05.2026)
- S21. Архив. "Advanced Metering Infrastructure" (My Water Advisor 2.0): https://www.cityoflewisville.com/city-hall/city-departments/public-services/meter-services/advanced-metering-infrastructure (копия 16.05.2026)
- S22. Архив. "Water Quality Report 2024" (PDF от 28.05.2025): https://www.cityoflewisville.com/home/showpublisheddocument/29464/638840391471300000 (копия 14.02.2026). Таблица жёсткости картинкой: work-6a/archive-ccr-2024-secondary-constituents.png
- S23. Архив. "Water Production": https://www.cityoflewisville.com/city-hall/city-departments/public-services/water-production (копия 11.05.2026)
- S24. Архив. "Water Quality Reports": https://www.cityoflewisville.com/city-hall/city-departments/public-services/environmental-compliance/water-quality-reports (копия 09.02.2026)
- S25. UTRWD, "Water Quality": https://utrwd.com/what-we-do/water/water-quality/ и отчёт "CCR 2025": https://upperoncloud.egnyte.com/dl/48tTbpy8gMG4
- S26. Архив. "Backflow Testing": https://www.cityoflewisville.com/city-hall/city-departments/public-services/meter-services/backflow-testing (копия 16.05.2026)
- S27. Архив. "Utility Line Maintenance": https://www.cityoflewisville.com/city-hall/city-departments/public-services/utility-line-maintenance (копия 16.05.2026)

(S9 не используется.)

#### Короткие пояснения по пунктам

**a. Регистрация.** Закон (S1): "No permit to perform any type of building, mechanical, electrical, plumbing, irrigation, water well drilling, or sign installation work shall be issued to any contractor which is not registered with the city under this article." Плата: "registrations for plumbing and electrical contractors are exempt from the registration fee. Registration under this article shall expire one year after the date of issue." Расхождение: закон для сантехников страховку не называет, а памятка города (S10, архив) просит страховой сертификат с минимумом 100,000 и City of Lewisville в графе "Certificate Holder".

**b. Разрешения.** Прямой строки "замена PRV", "ремонт под плитой", "замена линии от счётчика", "ремонт канализации" нет ни в законе, ни в архивных списках. Общая фраза страницы Building Services (S11, архив): "A building permit is required for all new construction, remodeling, changes, or additions to structures which includes signs, fences, retaining walls, swimming pools, patio covers, rewiring, electrical or mechanical work, and plumbing." В поправке к кодексу (S2, 109.3) работа до разрешения: "investigation fee ... equal to the amount of the permit fee" (в тексте города там ошибочно написано "mechanical system", так в оригинале). Исключения для срочной ночной работы в законе нет. [Сборка: перепроверка, city-b1 в 6.3: писать «исключения нет» нельзя, город принял весь кодекс 2021 года, его текст не прочитан.]

**c. Инспекция.** По странице S17 инспектору звонят "between 7:00 a.m. - 7:30 a.m.", по FAQ S16 звонят в офис "between 7:30 a.m. and 8 a.m.". Это расхождение самого города.

**d, e.** Полные слова закона 16-99, 16-100, 16-237, 16-231 и 16-300: в файле цитат.

**f.** Отчёт 2024 года сделан в Canva, почти все таблицы картинками. Строка "HARDNESS 158.5" стоит в таблице "Secondary Constituents", столбец "Average Level (ppm)". Год в таблице не указан, это отчёт "WATER QUALITY REPORT 2024". Строки с разбросом (минимум, максимум) нет.

#### Что из этого нельзя переносить на страницу

1. Источники воды в отчёте названы с запрещёнными словами: "Dallas Water Utility (DWU)", "Lakes Ray Roberts, Lewisville, Grapevine, Ray Hubbard, Tawakoni", "Denton County". По правилам проекта нельзя писать "Dallas" отдельно, нельзя Grapevine и Denton. Если автор пишет об источнике, то только "Lewisville Lake" и "Upper Trinity Regional Water District" или общими словами "purchased treated water".
2. Слова "Denton County Appraisal District" (исключение для хозяина, S1) на страницу не переносить.
3. Телефоны города (972.219.3470 и другие) в работе есть, но правило проекта: телефоны только наши и только в шапке, подвале, кнопках.
4. Суммы города ($25 за отчёт о проверке клапана, $75 залог и другие) это не наши цены, но правило про цифры строгое: ставить только с согласия Дениса.
5. Проверку обратного клапана мы не делаем. Факты города совпадают с единственной разрешённой фразой: "Once the new assembly is in, it gets tested and the test report goes to the city."
6. Чужие цифры жёсткости из интернета (5.2, 8.2, 8.5, 14.2 gpg на сайтах продавцов смягчителей и агрегаторов) не официальные и расходятся: не использовать.
7. Лучший кандидат на одну официальную ссылку: статья о регистрации подрядчиков в своде законов (S1) или страница "Building Permits" города. Сайт города закрыт для роботов, поэтому проверка ссылок может его пометить; ссылка на Municode открывается.

#### Что не сделано и вопросы

1. Живой сайт города не открыт ни одной страницей (403). Все пункты could_not_open утром надо сверить в браузере, особенно отчёт о воде за 2025 год (вышел ли и что в нём по жёсткости).
2. Зарегистрирована ли FPP в Льюисвилле в MGO Connect, я не проверял. Вопрос Денису. [Сборка: вопрос закрыт словом Дениса 3 октября 2026, компания зарегистрирована во всех городах, где работает; см. часть 10.]
3. Вопрос Денису: были ли в Льюисвилле вызовы, где дефект канализации оказался между тротуаром и городской трубой и его чинил город? Это готовая живая история под закон 16-99.
4. Вопрос Денису: требует ли инспектор Льюисвилля разрешение на замену PRV и на ремонт течи под плитой на практике? На бумаге города этих строк нет.
5. Архивная копия отчёта 2023 года обрезана (5 МБ), её я не читал.

### 6.2. Индексы и возраст домов (файл `6b-zip-and-age.md`)

Заголовок файла: «6, часть вторая. Почтовые индексы Lewisville и возраст домов».

Проверено 3 октября 2026. Все цифры взяты из официальных файлов USPS и Census Bureau, адреса запросов стоят в конце раздела. Ничего не придумано: где проверить не удалось, так и написано. Полные таблицы лежат рядом, в файле 6b-zip-and-age-tables.md, рабочие выписки и расчеты в папке work-6b.

#### Коротко, самое важное

1. У почтового отделения LEWISVILLE четыре индекса. Жилых, с доставкой почты, три: 75057, 75067, 75077. Индекс 75029 это только абонентские ящики (PO BOX), домов там нет.
2. Четвертый большой кусок города лежит в индексе 75056, а это индекс почты THE COLONY. По файлу Census 2020 года в 75056 лежало 18,8% земли Lewisville, по сегодняшней границе около 23% площади города. The Colony это отдельный город из десяти, у него своя страница: показывать 75056 на странице Lewisville или нет, решает Денис (вопрос 1 в конце).
3. Город почти целиком лежит в четырех участках: 75057 (35,4% земли города), 75067 (34,1%), 75056 (18,8%), 75077 (11,1%). Еще три чужих индекса задевают его краем, меньше половины процента каждый: 75010, 75019, 75007. В 75065 у города только вода озера.
4. Медианный год постройки жилья, ACS 2020-2024: Lewisville city 1997 (±1). По индексам: 75057 1995 (±3), 75067 1994 (±2), 75077 1994 (±2), 75056 2006 (±1).
5. Для сравнения тем же выпуском: Frisco city 2009 (±1), Plano city 1993 (±2). Lewisville по медиане на 12 лет старше Фриско и на 4 года моложе Плано.
6. Самые старые дома города стоят в 75057, к востоку от I-35E: там 52,8% домов на одну семью построены до 1980 года, медиана жилья владельцев 1982 (±7). По всему городу до 1980 года построен каждый пятый дом на одну семью (21,0%, это 5 761 дом).
7. Census API (api.census.gov) без ключа не отвечает (проверено 3 октября 2026). Ключ я не запрашивал: это регистрация с почтой, такое делает только Денис. Те же цифры взяты из официальных файлов Census (ACS Summary File, размеры файлов сверены с сервером) и сверены с сайтом data.census.gov: 120 клеток, несовпадений ноль.

#### а. Индексы Lewisville

Источник 1: USPS, файл "ZIP Locale Detail" (Zip_Locale_Detail.xlsx, на странице PostalPro стоит "file updated 10/01/2026", на сервере файл от 1 октября 2026, 4 380 487 байт). Источник 2: Census Bureau, файл связи участков ZCTA и городов 2020 года, место "Lewisville city", код 4842508. Источник 3: карта Census TIGERweb, сегодняшняя граница города.

ZCTA это "ZIP Code Tabulation Area": участок, которым Census приближенно повторяет почтовый индекс. По ним считается вся статистика ниже.

| Индекс | USPS: класс индекса | USPS: почтовое отделение | Доля земли города в участке (2020) | Доля земли участка в черте Lewisville (2020) | С кем индекс общий (доля земли участка) |
|---|---|---|---|---|---|
| 75057 | обычный, с доставкой | LEWISVILLE | 35,4% | 98,2% | Carrollton city 1,8% |
| 75067 | обычный, с доставкой | LEWISVILLE, плюс станция OLD TOWN FINANCE | 34,1% | 93,4% | Carrollton city 1,9%, Grapevine city 1,5%, Coppell city 1,5%, земля вне городов 1,5%, Flower Mound town 0,2% |
| 75077 | обычный, с доставкой | LEWISVILLE | 11,1% | 29,0% | Highland Village city 36,5%, Copper Canyon town 17,6%, Double Oak town 15,3%, Flower Mound town 1,4% |
| 75029 | P, только абонентские ящики | LEWISVILLE | нет участка | нет участка | домов нет |
| 75056 | обычный, с доставкой | THE COLONY, плюс THE COLONY CARRIER ANNEX | 18,8% | 29,4% | The Colony city 51,9%, земля вне городов 17,5% (на 2020 год), Hebron town 0,4%, Carrollton city 0,4%, Frisco city 0,4% |
| 75010 | обычный | ROSEMEADE (здание в Carrollton) | 0,37% | 2,0% | Carrollton city 95,3%, Hebron town 2,6% |
| 75019 | обычный | COPPELL | 0,36% | 0,8% | Coppell city 79,5%, Dallas city 13,2%, Carrollton city 6,0% |
| 75007 | обычный | ROSEMEADE | 1 179 кв. м, ноль | 0,0% | Carrollton city 98,5% |
| 75065 | обычный | LAKE DALLAS | только вода озера | 0% земли | Hickory Creek town 57,8%, Lake Dallas city 29,4% |

Что еще видно в источниках:

- Абонентские ящики. В файле USPS индексы "только PO BOX" помечены буквой P в поле "ZIP CLASS CODE". У отделения LEWISVILLE так помечен один индекс, 75029. Участка ZCTA у него нет, статистики по нему нет.
- Индексы 75022 и 75028 (почта FLOWER MOUND) город не задевают совсем, ни одного квадратного метра.
- Город вырос после 2020 года. Земля Lewisville по файлу 2020 года 95 851 124 кв. м, а по сегодняшней границе и по границе выпуска ACS 2024 (TIGERweb, слой Incorporated Places) 105 523 422 кв. м, на 9 672 298 кв. м больше. Почти весь прирост пришелся на 75056: часть города в этом участке выросла с 18,9 до 28,4 млн кв. м (мой расчет по карте, вместе с водой). В файле 2020 года эта земля стоит как "вне городов" (17,5% земли 75056).
- Что это за земля, официально проверить не удалось: страница города про Castle Hills (cityoflewisville.com/our-services/castle-hills-residents) ответила 403. Поиск по сайту города показывает на этой странице фразу о том, что полная аннексия Castle Hills прошла 15 ноября 2021 года, но сам текст страницы я не прочел. Использовать это на странице можно только после проверки.
- Сегодняшняя граница по участкам, вся площадь с водой (мой расчет, готовой цифры в источнике нет): 75057 33,0%, 75067 27,1%, 75056 23,3%, 75077 9,5%, 75065 6,5% (вода озера), 75010 0,3%, 75019 0,3%.
- Где что лежит (мой расчет по линиям I-35E с карты Census): часть города в 75057 и в 75056 целиком к востоку от I-35E; часть в 75067 на 94,1% к западу от I-35E, в 75077 на 86,2% к западу. Центры участков ZCTA по Census: [Сборка: цифры широты и долготы четырёх участков убраны, в брифе координат нет; они есть в файле раздела.]
- Официальной страницы города со списком индексов я не нашел: два поиска по cityoflewisville.com дали только сторонние справочники индексов, их я не использовал. Сервис USPS "Cities by ZIP Code" (какие названия городов почта принимает для индекса) на запрос ответил перенаправлением на страницу webtools-msg, обходить защиту я не стал. Поэтому список "принимаемых" названий для 75056 и 75077 не проверен.

Для автора страницы: если индексы вообще показывать, то надежно три: 75057, 75067, 75077. 75029 не нужен (ящики). 75056 только по слову Дениса. 75010, 75019, 75007, 75065 не показывать: это чужие индексы, город их задевает краем или водой. Города Highland Village, Copper Canyon, Double Oak, Flower Mound, Coppell, Grapevine, Hebron, Hickory Creek, Lake Dallas, Dallas на сайте называть нельзя совсем, а The Colony, Carrollton, Frisco, Plano нельзя называть на странице Lewisville (правило CLAUDE.md: городская страница не называет соседей).

#### б. Медианный год постройки по индексам (таблица B25035)

Выпуск: American Community Survey, 5-year, 2020-2024 (в файлах Census это "2024 ACS 5-year"). Это самый новый выпуск, который знает API: описание переменной B25035_001E за 2024 год отвечает ("Estimate!!Median year structure built"), за 2025 год ответ 404; папки данных 2025 года на сервере Census тоже нет (404). Файлы 2024 года на сервере датированы 29 января 2026. Рядом для сравнения прошлый выпуск, 2019-2023.

"Медианный год" значит: половина жилья построена раньше этого года, половина позже. "±" это погрешность опроса из того же файла. Считается все жилье, и дома, и квартиры. Поэтому рядом медиана по жилью, где живет сам владелец (таблица B25037): это ближе к частным домам.

Граница города в выпуске: по правилу Census "The ACS usually uses legal boundaries as of January 1 of the last year of the estimate period", то есть на 1 января 2024 года. Площадь Lewisville в слое ACS 2024 на карте Census совпадает с сегодняшней (105 523 422 кв. м земли), значит земля, добавленная после 2020 года, в цифрах города уже учтена.

| Участок | Где | Медиана, все жилье, 2020-2024 (B25035_001) | Погрешность | Выпуск 2019-2023 | Медиана, жилье владельцев (B25037_002) | Медиана, съемное жилье (B25037_003) | Всего жилья (B25034_001) |
|---|---|---|---|---|---|---|---|
| 75057 | восток от I-35E, 98% земли это Lewisville | 1995 | ±3 | 1994 (±3) | 1982 (±7) | 1999 (±3) | 7 361 |
| 75067 | запад от I-35E, юг города, 93% земли Lewisville | 1994 | ±2 | 1993 (±1) | 1991 (±1) | 1995 (±1) | 28 995 |
| 75077 | запад от I-35E, северо-запад, 29% земли Lewisville | 1994 | ±2 | 1993 (±1) | 1993 (±2) | 1999 (±4) | 15 559 |
| 75056 | восток от I-35E, почта The Colony, 29% земли Lewisville (2020) | 2006 | ±1 | 2005 (±1) | 2004 (±2) | 2010 (±2) | 29 056 |
| 75010 | чужой, краем | 2005 | ±1 | 2004 (±1) | 2005 (±2) | 2004 (±1) | 14 322 |
| 75019 | чужой, краем | 1995 | ±1 | 1994 (±1) | 1993 (±1) | 2000 (±3) | 17 530 |
| Lewisville city, Texas (код 48 и 42508) | весь город | 1997 | ±1 | 1996 (±1) | 1996 (±1) | 1998 (±2) | 54 237 |
| Frisco city, Texas (48 и 27684) | | 2009 | ±1 | 2009 (±2) | 2008 (±1) | 2011 (±1) | 80 353 |
| Plano city, Texas (48 и 58016) | | 1993 | ±2 | 1993 (±1) | 1991 (±1) | 1997 (±1) | 117 686 |
| Texas | | 1992 | ±1 | 1990 (±1) | 1993 (±1) | 1991 (±1) | 12 128 515 |

Цифры Frisco и Plano совпадают с уже проверенным разделом Плано (docs/briefs/plano/6b-zip-and-age.md).

Как читать по участкам: 75057 и 75067 это почти целиком Lewisville, их цифры описывают город. 75077 и 75056 в основном соседи (в 75056 это 70,6% земли по границе 2020 года и около 63% площади сегодня), их цифры про Lewisville говорят мало, для города надежнее строка "Lewisville city".

#### в. Доли по годам постройки (таблица B25034, все жилье)

Выпуск тот же, 2020-2024. Проценты посчитаны мной из чисел файла: "до 1980" это строки 007-011, "1980-1999" строки 005 и 006, "2000-2009" строка 004, "2010 и позже" строки 002 и 003. Названия строк сверены с официальным файлом описаний (Table Shells).

| Участок | Построено до 1980 | 1980-1999 | 2000-2009 | 2010 и позже |
|---|---|---|---|---|
| 75057 | 29,7% | 29,6% | 18,7% | 21,9% |
| 75067 | 15,0% | 53,1% | 18,5% | 13,4% |
| 75077 | 16,0% | 53,6% | 16,8% | 13,5% |
| 75056 | 14,3% | 20,0% | 26,1% | 39,7% |
| 75010 | 3,1% | 32,4% | 29,2% | 35,4% |
| 75019 | 6,1% | 61,3% | 12,1% | 20,5% |
| Lewisville city | 14,3% | 42,5% | 20,1% | 23,1% |
| Frisco city | 1,5% | 16,9% | 34,8% | 46,7% |
| Plano city | 18,4% | 50,3% | 17,6% | 13,7% |

Сверх задания, потому что в B25034 квартиры и дома смешаны, а в Lewisville съемного жилья больше половины (53,7% занятого жилья по B25036):

| Участок | Дома на одну семью (B25127, "1, detached or attached") | Из них до 1980 | 1980-1999 | 2000 и позже | Жилье владельцев до 1980 (B25036) |
|---|---|---|---|---|---|
| 75057 | 3 030 | 52,8% (1 601 дом) | 23,2% | 24,0% | 48,1% |
| 75067 | 12 382 | 25,6% (3 170) | 51,9% | 22,5% | 25,2% |
| 75077 | 13 185 | 17,2% (2 267) | 58,2% | 24,6% | 16,4% |
| 75056 | 19 603 | 19,1% (3 736) | 23,2% | 57,8% | 16,3% |
| Lewisville city | 27 489 | 21,0% (5 761) | 41,7% | 37,4% | 19,7% |
| Frisco city | 57 248 | 1,5% (846) | 18,3% | 80,2% | 1,2% |
| Plano city | 72 982 | 24,1% (17 608) | 53,3% | 22,6% | 23,5% |

Десятилетия по отдельности, числа и проценты, жилье владельцев по десятилетиям и раскладка земли по участкам стоят в файле 6b-zip-and-age-tables.md.

#### г. Что цифры говорят о возрасте домов Lewisville

1. Lewisville в целом средних лет: медиана 1997, это на 12 лет старше Фриско (2009) и на 4 года моложе Плано (1993). По жилью владельцев 1996 против 2008 и 1991. Основная масса жилья города построена в 1980-1999 годах (42,5% всего жилья, 41,7% домов на одну семью).
2. Возраст неровный. Старое ядро это 75057, к востоку от I-35E: больше половины домов на одну семью там построены до 1980 года, медиана жилья владельцев 1982. По всему городу до 1980 года построен каждый пятый дом на одну семью (21,0%), почти как в Плано (24,1%) и в четырнадцать раз чаще, чем во Фриско (1,5%).
3. Медиана города моложе Плано из-за нового жилья, в основном съемного: 23,1% всего жилья построено в 2010 году и позже (в Плано 13,7%), и в цифры города уже входит земля в 75056, добавленная после 2020 года, где жилье 2000-х и 2010-х. [Сборка: причина не из источника, это догадка помощника; цифры верны (6.4, age-d1).]

Связь с живой страницей. Там есть заголовок "Slab Leaks in Older Lewisville Homes" и фраза "A lot of houses here have been standing long enough for the lines under the foundation to have earned some respect." Данные это подтверждают для 75057 и части 75067, но не для города целиком: большинство домов Lewisville это 1980-е и 1990-е. Это предложение помощника по данным, решение за Денисом: его опыт на вызовах главнее статистики. Если автору нужна одна цифра со ссылкой на официальный источник, самая надежная: медианный год постройки жилья в Lewisville 1997 (ACS 2020-2024, таблица B25035, Lewisville city, Texas). Россыпь цифр Census на страницу лучше не выносить: это статистика, а не опыт Дениса. Сравнение с Фриско и Плано только для сведения: на странице Lewisville другие города не упоминаются.

#### Вопросы Денису

1. Индекс 75056 это почта The Colony, но около четверти площади Lewisville сегодня лежит в нем. Показывать его на странице Lewisville, или оставить странице The Colony? (Показ на двух страницах сразу может дать пересечение двух городских страниц.)
2. Сходится ли с вашими вызовами: самые старые дома Lewisville, 1960-е и 1970-е, к востоку от I-35E около старого центра, а к западу от I-35E в основном 80-е и 90-е?
3. Называть ли на странице Castle Hills? Это не город, а район, который по сайту города (страницу прочесть не удалось) вошел в Lewisville в 2021 году. Правило про города его не запрещает, но решение ваше.

#### Адреса запросов

Census API, как просили в задании, и что он ответил (3 октября 2026):

- https://api.census.gov/data/2024/acs/acs5?get=NAME,B25035_001E&for=zip%20code%20tabulation%20area:75010,75019,75022,75028,75056,75057,75067,75077 : ответ 302 на https://api.census.gov/data/missing_key.html , заголовок "X-DataWebAPI-KeyError: 1", на странице "A valid key must be included with each data API request." То же для /data/2025/.
- https://api.census.gov/data/2024/acs/acs5?get=NAME,B25035_001E&for=place:42508,27684,58016&in=state:48 : тот же ответ 302, нужен ключ.
- https://api.census.gov/data/2024/acs/acs5/variables/B25035_001E.json : ответ 200 без ключа, "Estimate!!Median year structure built". Для 2025 ответ 404.
- Когда у Дениса будет ключ, те же цифры даст запрос: https://api.census.gov/data/2024/acs/acs5?get=NAME,B25035_001E,B25035_001M&for=zip%20code%20tabulation%20area:75056,75057,75067,75077&key=КЛЮЧ и для городов: https://api.census.gov/data/2024/acs/acs5?get=NAME,B25035_001E,B25035_001M&for=place:42508,27684,58016&in=state:48&key=КЛЮЧ

Откуда цифры взяты на самом деле (официальные файлы Census, ключ не нужен; размеры файлов сверены с сервером, совпали байт в байт):

- https://www2.census.gov/programs-surveys/acs/summary_file/2024/table-based-SF/data/5YRData/acsdt5y2024-b25035.dat (медиана)
- https://www2.census.gov/programs-surveys/acs/summary_file/2024/table-based-SF/data/5YRData/acsdt5y2024-b25034.dat (по десятилетиям)
- https://www2.census.gov/programs-surveys/acs/summary_file/2024/table-based-SF/data/5YRData/acsdt5y2024-b25037.dat (медиана, владельцы и съемщики)
- https://www2.census.gov/programs-surveys/acs/summary_file/2024/table-based-SF/data/5YRData/acsdt5y2024-b25036.dat (по десятилетиям, владельцы и съемщики)
- https://www2.census.gov/programs-surveys/acs/summary_file/2024/table-based-SF/data/5YRData/acsdt5y2024-b25127.dat (по типу здания)
- https://www2.census.gov/programs-surveys/acs/summary_file/2023/table-based-SF/data/5YRData/acsdt5y2023-b25035.dat (прошлый выпуск)
- https://www2.census.gov/programs-surveys/acs/summary_file/2024/table-based-SF/documentation/ACS20245YR_Table_Shells.txt и Geos20245YR.txt (названия строк и участков)
- Строки в файлах: 860Z200US75057, 860Z200US75067, 860Z200US75077, 860Z200US75056, 860Z200US75010, 860Z200US75019, 1600000US4842508 (Lewisville city, Texas), 1600000US4827684 (Frisco city), 1600000US4858016 (Plano city), 0400000US48 (Texas).

Сверка на data.census.gov (таблицы B25035, B25034, B25037; все значения совпали с файлами):

- https://data.census.gov/api/access/data/table?id=ACSDT5Y2024.B25035&g=860XX00US75057 (и так же 75067, 75077)
- https://data.census.gov/api/access/data/table?id=ACSDT5Y2024.B25035&g=160XX00US4842508 (Lewisville city)
- то же с id=ACSDT5Y2024.B25034 и id=ACSDT5Y2024.B25037

Индексы, граница, дороги:

- https://postalpro.usps.com/ZIP_Locale_Detail и файл https://postalpro.usps.com/mnt/glusterfs/2026-10/Zip_Locale_Detail.xlsx
- https://www2.census.gov/geo/docs/maps-data/data/rel2020/zcta520/tab20_zcta520_place20_natl.txt (строки с "Lewisville city", код 4842508)
- https://tigerweb.geo.census.gov/arcgis/rest/services/TIGERweb/tigerWMS_Current/MapServer/28/query?where=GEOID%3D'4842508'&outFields=GEOID,NAME,AREALAND,AREAWATER&returnGeometry=true&outSR=4326&f=json (сегодняшняя граница) и слой 2 там же (участки ZCTA)
- https://tigerweb.geo.census.gov/arcgis/rest/services/TIGERweb/tigerWMS_ACS2024/MapServer/28/query?where=GEOID%3D'4842508'&outFields=GEOID,NAME,AREALAND,AREAWATER&returnGeometry=false&f=json (граница выпуска ACS 2024)
- https://tigerweb.geo.census.gov/arcgis/rest/services/TIGERweb/Transportation/MapServer/2 (линия I-35E)
- https://www.census.gov/programs-surveys/acs/geography-acs/geography-boundaries-by-year.2010.html (правило о границах в ACS)
- Не открылись: https://www.cityoflewisville.com/our-services/castle-hills-residents (403) и сервис USPS "Cities by ZIP Code" (перенаправление на webtools-msg).

#### Оговорки

- ACS это выборочный опрос за пять лет, у каждой цифры есть погрешность. У медиан она от 1 до 3 лет, у медианы владельцев в 75057 7 лет: в индексе всего 2 517 домов владельцев. Разница в один или два процента ничего не значит.
- Участок ZCTA повторяет почтовый индекс приближенно, границы у почты и у Census могут немного расходиться.
- Доли земли по участкам взяты из файла Census 2020 года; доли по сегодняшней границе и положение относительно I-35E посчитаны мной по карте Census, готовой цифры в источнике нет.
- Цифры по индексу описывают весь участок, а не только его часть в Lewisville. Отдельной статистики "часть индекса внутри города" в ACS нет.
- Сторонние справочники индексов (zip-codes.com и подобные) не использованы: только USPS и Census.

### 6.3. Перепроверка фактов города (файл `6a-official-city-verified.md`, без двух списков, переставленных в 6.0)

Заголовок файла: «6a. Проверка официальных фактов Льюисвилла (вторая пара глаз)».

Проверено 3 октября 2026 года. Проверял не тот помощник, который собирал факты: каждый источник я открыл сам, заново, своими запросами.

Как проверял:

1. **Законы города** скачал сам из официального свода законов Municode, редакция "Supplement 34 Update 2", "Codified through Ordinance No. 0854-26-ORD, July 6, 2026". Разделы: 4-551 до 4-558, 4-31, 4-32, 4-111, 4-112, 16-99, 16-100, 16-231, 16-237, 16-252, 16-300, 16-355.
2. **Сайт города** cityoflewisville.com и сегодня отвечает 403 (защита). Обходить не стал. Страницы и памятки города прочитал в копиях Internet Archive, скачал сам. Важно: копия страницы Building Permits от **25.09.2026** ссылается ровно на те же версии памяток (водонагреватель 11301, полив 19006, фундамент 11557, регистрация 21029), которые я читал. Значит, в конце сентября 2026 года это были действующие памятки.
3. **Закон штата** (TSBPE, Occupations Code 1301) скачал напрямую с tsbpe.texas.gov. **UTRWD**: страница и отчёт за 2025 год скачаны напрямую.
4. Таблицу жёсткости (картинка в PDF) прочитал глазами со страницы 3 отчёта.

Пункты "архив" утром сверить с живым сайтом в браузере.

#### Итог за минуту

- Из 45 фактов подтверждено 43. **Неверных два:** city-h1 (страницы о морозе есть, старые) и city-h4 (цифра PSI в законе есть).
- Три факта подтверждены, но формулировку надо поправить: city-b1 (про срочную работу), city-e2 (что такое "больше 100 процентов"), city-b11 (про список работ без разрешения).
- Найдено новое: в старых копиях сайта города совет "Keep faucets dripping" (2017) и отмена платы за сантехнические разрешения после бури февраля 2021 года. Это старьё, на страницу как совет города не ставить.

#### Таблица проверки

Статус источника: "закон" значит живой свод законов Municode; "архив ДД.ММ.ГГГГ" значит копия страницы города в Internet Archive (живая страница 403).

| id | Что утверждалось (коротко) | Где проверил | Подтверждено | Заметка |
|---|---|---|---|---|
| city-a1 | Регистрация обязательна для всех, кому штат требует лицензию, включая plumbing; это не лицензия | закон 4-551(a)(2), (b) | да | Слова "Any services which require, by state law, a license or registration to perform any mechanical, electrical, plumbing work" и "no manner of license is offered" стоят дословно. |
| city-a2 | Для сантехника нужна лицензия responsible master plumber у исполнителя или у ответственного лица фирмы | закон 4-552(c)(4) | да | Дословно. Страховки и залога для сантехников закон не требует (для других видов требует 100,000). |
| city-a3 | Сантехники без платы за регистрацию, срок 1 год, продление новой заявкой | закон 4-555; таблица платежей города (архив 07.08.2025, "Effective January 1, 2024") | да | В таблице платежей: "Plumbing Contractor NO FEE". |
| city-a4 | Без регистрации разрешение не дают; при просрочке инспекции могут остановить | закон 4-551(c) и 4-555 | да | Вторая половина стоит в 4-555, не в 4-551: "no permits shall be issued and inspections may be placed on hold if a required registration has expired". |
| city-a5 | Регистрацию могут приостановить, в том числе за финальную инспекцию не вовремя; жалоба за 10 рабочих дней | закон 4-556(1), 4-557(a) | да | Жалоба письменно, в contractor registration board, "within ten business days". |
| city-a6 | Памятка: сантехник подаёт страховой сертификат и номер лицензии штата, плата прочерк; страховка от 100,000; Certificate Holder City of Lewisville; заявка в MGOConnect | памятка 21029, архив 07.10.2025 (та же версия по ссылке со страницы 25.09.2026) | да (архив) | Дословно в копии. Закон страховку для сантехников не называет, памятка называет. |
| city-a7 | Хозяин в своём основном жилье с homestead exemption освобождён от регистрации | закон 4-551(d) | да | В цитате имя окружного налогового ведомства с запрещённым для сайта словом. Переносить только пересказом без имени. |
| city-a8 | Штат: сантехник не платит городу плату за регистрацию, но регистрироваться обязан | TSBPE, Occupations Code 1301.551(g), (h) | да | (g) дословно; (h): "A plumbing contractor must register, electronically or in person, with a municipality". |
| city-b1 | Разрешение нужно на работы, включая plumbing; работа до разрешения: investigation fee, равная плате за разрешение; исключения для срочной работы нет | Building Services, архив 05.09.2026; закон 4-112 (поправка 109.3 к IPC) | да, с поправкой | Цитата страницы дословна. В поправке 109.3 стоит "commences work on a **mechanical system**" (так написано городом в поправке к сантехническому кодексу). Про срочную работу: в поправке исключения нет, но город принял весь кодекс 2021 года, и его пункты о работах без разрешения и о срочном ремонте поправками не удалены; текст ICC прочитать не смог (codes.iccsafe.org работает только со скриптом). Писать "исключения нет" нельзя. |
| city-b2 | Водонагреватель: разрешение, Plumbing Final, лицензированный сантехник, зарегистрированный в городе | памятка 11301 "Updated 1/15/2025", архив 07.08.2025 (та же версия по ссылке 25.09.2026) | да (архив) | Там же: хозяин может сам на своём homestead. |
| city-b3 | Поправки к IRC: 18 дюймов в гараже (кроме FVIR и электрических), поддон, газовый нагреватель не в кладовке, сброс T&P, чердак 20 на 30 и лестница 300 lb | закон 4-32 (P2801.7, P2801.6, M2005.2, P2804.6.1 п. 5, M1305.1.2) | да | Поддон: "where water leakage from the tank will cause damage". Кладовка: "Fuel-fired water heaters shall not be installed in a room used as a storage closet". Лестница 300 lb это один из трёх вариантов доступа (постоянная лестница, складная от 300 lb, дверь с верхнего этажа). |
| city-b4 | Отдельной строки о разрешении на линию от счётчика нет; закон: чинит хозяин, по требованиям города | закон 16-237; список разрешений (архив 25.09.2026); таблица платежей | да | Цитата дословна; в списке и в таблице платежей только общая "Plumbing Miscellaneous". Рядом 16-231(6): без разрешения нельзя подключаться к "main or service pipes of the water system"; про частную линию во дворе прямо не сказано. |
| city-b5 | Отдельной строки о разрешении на канализацию нет; ремонт дело хозяина, законы соблюдать; глубина 12 дюймов, подсыпка 4 дюйма | закон 16-100(d); 4-112 (IPC 305.4.1, 306.2.4); 4-32 (P2603.5.1, P2604.2.1) | да | Цитата "All city codes and ordinances must be followed regarding repair work." дословна. 12 и 4 дюйма стоят в обоих кодексах, но не в разделе 16-100, который указан источником. |
| city-b6 | PRV не назван ни в законе, ни в списках | закон 4-112, 4-32; список разрешений; таблица платежей | да | Слов "pressure reducing" и "PRV" в поправках нет. |
| city-b7 | На любой backflow нужно plumbing permit; на поливе защита обязательна; на полив нужно разрешение; тестер проверяет до запуска, отчёт за 10 рабочих дней | закон 16-355(v), 16-355(j)(6); 4-112 (раздел о поливе) | да | Разрешение на полив, проверка "prior to being placed in service" и "within ten business days" стоят в 4-112, не в 16-355. Обязанность проверки там на irrigator. |
| city-b8 | Памятка о поливе: разрешение, клапан проверяет лицензированный тестер, Irrigation Final | памятка 19006 "Updated 1/15/2025", архив 07.08.2025 (та же версия 25.09.2026) | да (архив) | Там же: работу делает "a licensed plumber or irrigator who is registered as a contractor". |
| city-b9 | Ремонт под плитой нигде не назван | закон 4-112, 4-32; списки | да | Не нашёл ни одного упоминания труб под плитой. |
| city-b10 | Разрешение на любой ремонт фундамента, проект инженера, финальная инспекция; о сантехническом тесте ни слова | памятка 11557 "Updated 1/15/2025", архив 07.08.2025 (та же версия 25.09.2026) | да (архив) | Слов "plumb" и "test" в памятке ноль. |
| city-b11 | Своего списка сантехнических работ без разрешения у города нет; в FAQ только косметика | FAQ, архив 18.06.2026 | да, с поправкой | Цитата дословна. Оговорка как в b1: в принятых кодексах 2021 года свой список работ без разрешения есть и не удалён, текст ICC не прочитан. |
| city-b12 | Штат: без разрешения ремонт течей, смесители кухни и умывальника, ballcocks or water control valves, измельчитель, унитаз | TSBPE, Occupations Code 1301.551(c) | да | Это правило для городов: город обязан требовать разрешение на всё, кроме этих пяти работ. |
| city-c1 | Инспекция через MGO Connect: на следующий день до 3 p.m., на понедельник до 10 a.m. пятницы | страница инспекций, архив 21.04.2026; те же слова в памятках 11301 и 19006 и в FAQ 18.06.2026 | да (архив) | mgoconnect.org 3 октября отвечает 200. |
| city-c2 | Время инспектора узнают звонком утром; страница 7:00 до 7:30 a.m., FAQ 7:30 до 8 a.m. | страница инспекций, архив 21.04.2026; FAQ, архив 18.06.2026 | да (архив) | Расхождение реальное. На странице инспекций ещё "approximate two-hour window". |
| city-c3 | Инспекции с понедельника по пятницу 7:00 a.m. до 3:30 p.m. | страница инспекций, архив 21.04.2026 | да (архив) | Дословно "Inspection Hours: Monday-Friday: 7:00 a.m. - 3:30 p.m." |
| city-d1 | Линии от подключения у счётчика до дома чинит хозяин | закон 16-237 | да | Дословно. |
| city-d2 | Город держит трубы и линию до счётчика, от счётчика до дома отвечает клиент | Service Problems, архив 17.05.2026 | да (архив) | Там же про канализацию: "Trouble in the line between the tap and the house is the responsibility of the customer for clearing stoppages." |
| city-d3 | Засоры до врезки прочищает хозяин; ремонт хозяин до края тротуара (дороги, переулка), дальше город бесплатно после проверки; камера лицензированного сантехника; cleanout ищет или ставит хозяин | закон 16-99, 16-100 | да | Дословно, включая "camera inspection by a licensed plumber". |
| city-d4 | Без разрешения директора нельзя открывать крышку ящика счётчика или кран, кроме пожара | закон 16-231(1) | да | Дословно. Пункты (7) и (8) делают исключение для state-licensed plumbers только про крышку счётчика и ключ. Вывод про совет закрывать воду на счётчике это толкование, не слова закона. |
| city-d5 | Публичная часть до счётчика, частная от счётчика до дома; почти все линии не свинцовые | Lead Service Line Inventory, архив 16.05.2026 | да (архив) | Дословно. |
| city-e1 | Пересчёт после скрытой течи; определение скрытой течи | закон 16-300(a), (b) | да | Дословно. |
| city-e2 | Условия пересчёта: больше 100 процентов, заявка, 30 дней, 60 дней, раз в 12 месяцев, по среднему двух месяцев | закон 16-300(b) до (f) | да, с поправкой | Точнее: рост расхода **больше чем на 100 процентов** (то есть больше чем вдвое) против среднего двух прошлых месяцев и против того же месяца за последние три года. Можно один или два связанных подряд периода. Пересчёт только канализации зимой: не чаще раза в 6 месяцев. Остальное верно. |
| city-e3 | Customer Assistance: раз в 12 месяцев, заявка и счета за 60 дней | архив 17.05.2026 | да (архив) | Дословно "within 60 days of billing". |
| city-e4 | My Water Advisor 2.0: сигнал Suspected Leak при непрерывном расходе 24 часа | Advanced Metering Infrastructure, архив 16.05.2026 | да (архив) | Дословно. |
| city-f1 | Жёсткость 158.5 ppm, среднее, Secondary Constituents, отчёт 2024; разброса нет | отчёт 29464, архив 14.02.2026, стр. 3 (картинка, прочитал глазами) | да (архив) | Колонка "Average Level (ppm)", строка "HARDNESS 158.5". Версия та же, что по ссылке на странице отчётов (архив 09.02.2026). |
| city-f2 | Своя станция на Lake Lewisville плюс покупная вода от DWU и UTRWD | тот же отчёт, стр. 3 | да (архив) | Дословно. В списке озёр и в имени DWU запрещённые для сайта слова. |
| city-f3 | Вода из Lewisville Lake, станция больше 20 MGD, покупная вода добавляется | Water Production, архив 11.05.2026 | да (архив) | Дословно; там покупка названа "from the City of" и запрещённое слово. |
| city-f4 | Отчёт за 2025 год не найден; на странице отчётов последний 2024 | Water Quality Reports, архив 09.02.2026; поиск в интернете | да | Поиск 3 октября отчёт 2025 года тоже не нашёл. |
| city-f5 | В отчёте жёсткость только в ppm, в grains per gallon нет | отчёт 2024; страница Water Facts, архив 16.05.2026 | да | На Water Facts только история водоочистки, цифр жёсткости нет. |
| city-f6 | UTRWD тестирует жёсткость, в отчёте 2025 строки hardness нет | utrwd.com (живая); CCR 2025 по ссылке со страницы (4 стр., прочитал глазами) | да | Строки таблицы: Bromate, Arsenic, Barium, Copper, Lead, Fluoride, Nitrate, Turbidity, TOC, Beta/photon, Atrazine. |
| city-g1 | IPC 2021 с приложениями C, D, E и поправками, 0617-23-ORD от 6 ноября 2023 | закон 4-111 | да | Дословно, "0617-23-ORD, § 1, 11-6-23". Страница Building Services (архив 05.09.2026) тоже называет 2021. |
| city-g2 | IRC 2021 с приложениями AT и AW, 0612-23-ORD от 6 ноября 2023 | закон 4-31 | да | Дословно. |
| city-h1 | Страницу города о защите труб от мороза не нашёл | индекс Internet Archive по сайту города | **нет** | Нашёл две старые страницы (см. ниже "Новое"). Действующей страницы о морозе не нашёл. |
| city-h2 | Клапаны проверяют при установке и раз в год тестером с лицензией и регистрацией; отчёты через BSI Online за 10 дней; закон 16-355(l) | Backflow Testing, архив 16.05.2026; закон 16-355(l) | да | На странице "within ten (10) days of the test date" (просто дни), а в 4-112 для полива "within ten business days". Это разные правила, не путать. |
| city-h3 | Советы при низком давлении: фильтры, сетки, горячая вода, часть дома | Utility Line Maintenance, архив 16.05.2026 | да (архив) | Дословно. |
| city-h4 | Цифры давления в PSI в законе нет | закон 16-252 | **нет** | В законе есть: в плане чрезвычайных мер по воде условие ступеней 2 и 3: "failure to maintain 20 psi pressure at up to 500 service locations or up to ten fire hydrants in localized areas". Цифры обычного давления в сети нет. |
| city-h5 | С 1 марта 2013 года город не прочищает канализацию у домов; то же в законе 16-99 | Utility Line Maintenance, архив 16.05.2026; закон 16-99(a) | да | Дата только на странице; в законе слова "will not clean/clear any stoppages", поправка Ord. No. 3981-02-2013 от 4 февраля 2013. |

#### Новое, что первый помощник пропустил

1. **Мороз, 2017 год** (архив 24.01.2017, страница Emergency Management "Winter Weather", сейчас её на сайте нет): "Winterize your pipes. Keep faucets dripping when the temperature drops below freezing." Адрес: http://www.cityoflewisville.com/about-us/departments-services/emergency-management/think/winter-weather
2. **Буря февраля 2021 года** (архив 28.03.2021, страница "Winter Recovery Resources"): совет города 22 февраля 2021 года отменил плату за сантехнические и электрические разрешения на ремонт после бури: "a large number of plumbing repairs and some electrical repairs are anticipated". Адрес: https://www.cityoflewisville.com/about-us/city-services/emergency-management/winter-recovery-resources . На странице стоят суммы платы за разрешение и имя округа с запрещённым словом.
3. **20 psi в законе** (16-252), см. city-h4.
4. **Таблица платежей города** (архив 07.08.2025, "Effective January 1, 2024", по ссылке со страницы 25.09.2026): для сантехники строки "Plumbing (per sq. ft.)" и "Plumbing Miscellaneous", отдельных строк на воду, канализацию, PRV нет. Суммы на сайт не ставить (правило цен).

#### Вопросы Денису

1. Ставить ли на страницу правило про крышку счётчика (16-231) или просто советовать главный кран дома? Решение за ним.
2. Пересчитывать ли 158.5 ppm в grains per gallon на странице (город сам этого не делает)?

### 6.4. Перепроверка индексов и возраста домов (файл `6b-zip-and-age-verified.md`, без двух списков, переставленных в 6.0)

Заголовок файла: «6b, перепроверка: индексы Lewisville и возраст домов».

Проверено 3 октября 2026. Я заново открыл каждый источник и сам сверил слова и цифры с тем, что записал первый помощник в файле 6b-zip-and-age.md. Его выписки (папка work-6b) я не брал: все файлы скачал сам, мои выписки и расчеты лежат в папке work-6b-verify рядом.

#### Коротко

1. Все цифры Census и USPS подтвердились знак в знак. Таблицы B25034, B25035, B25036, B25037 и B25127 я взял двумя путями: из официальных файлов Census (ACS Summary File 2020-2024 и 2019-2023) и с сайта data.census.gov. Сверено 740 клеток (оценки и погрешности), несовпадений ноль.
2. Census API (api.census.gov) без ключа по-прежнему не отвечает: запрос уходит на страницу "Missing Key". Ключ я не запрашивал.
3. Одна находка к вопросу "есть ли у города официальный список индексов". Текстовой страницы со списком нет (сайт города для моих запросов закрыт, ответ 403). Но у City of Lewisville есть свой публичный слой карты "Zip Code Boundaries" в аккаунте ArcGIS города (организация "City of Lewisville, Texas"). В нем у трех индексов почтовое название Lewisville: 75057, 75067, 75077; у 75056 название The Colony. Это совпадает с файлом USPS. Подробности в таблице, строка zip-a8.
4. Площадь города и доли по индексам на сегодняшней границе я пересчитал своим способом по карте Census: получилось то же, что у первого помощника, до десятой доли процента. Это расчет, готовой цифры в источнике нет.
5. Одна поправка к выводу age-d1: фраза "медиана моложе Плано, потому что добавилась земля после 2020 года" это догадка, источник причин не называет. Цифры в этом выводе верны.
6. Castle Hills (15 ноября 2021) по-прежнему не проверено: страница города ответила 403, обходить защиту я не стал. Сервис USPS "Cities by ZIP Code" тоже не проверен.

#### Таблица проверки

| id | Утверждение | Источник | Подтверждено | Примечание |
|---|---|---|---|---|
| zip-a1 | У почтового отделения LEWISVILLE четыре индекса: 75057, 75067, 75077 с доставкой (класс пустой), 75029 только PO Box (класс P). 75067 обслуживает еще станция OLD TOWN FINANCE. Файл обновлен 10/01/2026 | USPS, Zip_Locale_Detail.xlsx (postalpro.usps.com/mnt/glusterfs/2026-10/) | да | Мой файл: 4 380 487 байт, last-modified 1 октября 2026. На странице PostalPro: "October 01, 2026" и "file updated 10/01/2026". Строки (DISTRICT NO, ZIP, CLASS, LOCALE): 752, 75029, P, LEWISVILLE; 752, 75057, пусто, LEWISVILLE; 752, 75067, пусто, LEWISVILLE; 752, 75067, пусто, OLD TOWN FINANCE; 752, 75077, пусто, LEWISVILLE. Смысл буквы P в самом файле не написан, он есть в документе USPS PostalPro "2727 Definitions": "A 'P' indicates the ZIP Code has PO Boxes only and a blank ZIP Class indicates both PO Box and street delivery." (https://postalpro.usps.com/storages/2016-12/2727_Definitions.pdf) |
| zip-a2 | 75056 это почта THE COLONY (и THE COLONY CARRIER ANNEX); 75010 и 75007 ROSEMEADE (Carrollton); 75019 COPPELL; 75022 и 75028 FLOWER MOUND; 75065 LAKE DALLAS | тот же файл USPS | да | Строки: 75056 THE COLONY и THE COLONY CARRIER ANNEX, город THE COLONY; 75007 и 75010 ROSEMEADE, город CARROLLTON; 75019 COPPELL; 75022 и 75028 FLOWER MOUND; 75065 LAKE DALLAS |
| zip-a3 | Lewisville city (4842508, земля 95 851 124 кв. м на 2020 год) лежит в участках 75057 (35,37% земли города), 75067 (34,06%), 75056 (18,78%), 75077 (11,06%), 75010 (0,37%), 75019 (0,36%), 75007 (1 179 кв. м); в 75065 только вода (7 743 325 кв. м). У 75029 участка нет. 75022 и 75028 город не задевают | Census, tab20_zcta520_place20_natl.txt | да | Строки AREALAND_PART: 33 906 335; 32 642 842; 18 002 888; 10 597 471; 355 000; 345 409; 1 179; 0 (вода 7 743 325). Сумма 95 851 124, ровно вся земля города. Строк 75029 в файле нет совсем. У 75022 и 75028 строки с Lewisville нет |
| zip-a4 | Доля земли участка в черте Lewisville (2020): 75057 98,2% (Carrollton 1,8); 75067 93,4% (Carrollton 1,9, Grapevine 1,5, Coppell 1,5, вне городов 1,5, Flower Mound 0,2); 75077 29,0% (Highland Village 36,5, Copper Canyon 17,6, Double Oak 15,3, Flower Mound 1,4); 75056 29,4% (The Colony 51,9, вне городов 17,5, Hebron, Carrollton, Frisco по 0,4) | тот же файл Census | да | Мой расчет из тех же строк дал те же числа. Мелочь: в 75077 еще 0,2% вне городов и крошка Bartonville, в 75056 крошка Plano (меньше 0,1%); в файле таблиц у помощника это стоит |
| zip-a5 | Земля Lewisville 105 523 422 кв. м и в сегодняшнем слое TIGERweb, и в слое выпуска ACS 2024, против 95 851 124 в 2020 году (+9 672 298). Почти весь прирост в 75056 (часть города там выросла примерно с 18,9 до 28,4 млн кв. м с водой). Доли всей площади сегодня: 75057 33,0%, 75067 27,1%, 75056 23,3%, 75077 9,5%, 75065 6,5% (вода) | TIGERweb, слой 28 Incorporated Places, ACS2024 и Current | да (площадь из источника; доли это расчет, повторен) | Оба запроса вернули "AREALAND":105523422, "AREAWATER":16268264. Слой ACS2024: "January 1, 2024 vintage"; слой Current: "January 1, 2026 vintage". Разница 9 672 298 верна. 18,9 млн это 18 002 888 земли плюс 940 474 воды из файла 2020 года. Мой расчет по строкам (8 000 строк, карта в равновеликой проекции): вся площадь 121 791 174 кв. м против официальных 121 791 686; 75057 33,0%, 75067 27,1%, 75056 23,3% (28 391 641 кв. м), 75077 9,5%, 75065 6,5%, 75010 0,3%, 75019 0,3%. Прирост в 75056 около 9,45 млн из 9,85 млн всего прироста площади, это 96% |
| zip-a6 | Полная аннексия Castle Hills 15 ноября 2021 года | cityoflewisville.com/our-services/castle-hills-residents | нет | Мой один запрос: 403 "Access Denied" (защита Akamai), страница города "Our History" тоже 403. Обходить не стал. Поиск снова показывает эту дату только в выдержках поисковика и в новостных сайтах (candysdirt.com, communityimpact.com), это не официальный источник. Не использовать, пока Денис или следующий проверяющий не прочтет страницу города |
| zip-a7 | Сервис USPS "Cities by ZIP Code" не прочитан, принимаемые названия для 75056 и 75077 не проверены | tools.usps.com | нет | Не проверял повторно: помощник получил перенаправление на webtools-msg, это защита, обходить нельзя. Принимаемые названия остаются непроверенными |
| zip-a8 | Официальной страницы города Lewisville со списком индексов нет | cityoflewisville.com | нет (нашелся официальный слой карты) | Текстовой страницы со списком я тоже не нашел, сайт города закрыт для запросов (403). Но в ArcGIS аккаунте города (организация kXGqZY4GIOcEYxoF, название "City of Lewisville, Texas", адрес lewisville.maps.arcgis.com) есть публичный слой "Zip Code Boundaries", владелец nlibassi@cityoflewisville.com_Lewisville, создан 24 апреля 2024, описание: "Zip code boundaries in Lewisville and surrounding area - source data ESRI's US ZIP Code Boundaries last updated Jan 5, 2024". В нем 11 индексов; PO_NAME "Lewisville" стоит у 75057, 75067, 75077; у 75056 "The Colony"; остальные (75007, 75010, 75019, 75028, 75036, 75065, 76051) с названиями соседей. Там же приложение города "Lewisville Zip Code Map" (владелец ITS_Lewisville, 2022). Ссылки: https://lewisville.maps.arcgis.com/home/item.html?id=fb8ac427a51c426b9c70cfcee62068ab и https://services2.arcgis.com/kXGqZY4GIOcEYxoF/arcgis/rest/services/Zip_Code_Boundaries/FeatureServer/1. Это слой с данными Esri, а не заявление города "наши индексы такие-то": как подтверждение файла USPS годится, как цитата для страницы нет |
| age-api | API без ключа отвечает 302 на missing_key.html; переменная B25035_001E есть для 2024 ("Estimate!!Median year structure built") и 404 для 2025, значит 2020-2024 самый новый выпуск. Цифры из официального Summary File (размеры совпали с сервером), сверены с data.census.gov: 120 клеток, 0 расхождений | api.census.gov | да, с уточнением | Мои запросы: 302, "X-DataWebAPI-KeyError: 1", Location https://api.census.gov/data/missing_key.html, на странице "A valid key must be included with each data API request." Переменная 2024: 200, label "Estimate!!Median year structure built"; 2025: 404; наборы /data/2025/acs/acs5 и acs1 тоже 404. Размеры файлов на сервере совпали с записью помощника (b25034 50 103 592, b25035 15 421 817 байт и т.д., от 29 января 2026). Моя сверка шире: 740 клеток, 0 расхождений. Уточнение: папка www2.census.gov/.../summary_file/2025/table-based-SF/data/ на сервере уже есть (создана 23 сентября 2026), но пустая; 5YRData в ней 404. Пятилетнего выпуска 2021-2025 нет, вывод помощника верен |
| age-75057 | 75057: медиана 1995 (±3); 2019-2023: 1994 (±3); владельцы 1982 (±7), съемное 1999 (±3); 7 361 единица. Доли: до 1980 29,7%, 1980-1999 29,6%, 2000-2009 18,7%, 2010 и позже 21,9%. Дома на одну семью до 1980: 52,8% (1 601 из 3 030). Целиком к востоку от I-35E | Summary File b25035, b25034, b25037, b25127; data.census.gov | да | Файл и сайт: 1995, 3. B25037: 1995, 3, 1982, 7, 1999, 3. Строка B25034: 7361, 170, 1441, 1380, 1287, 895, 820, 664, 402, 137, 165. B25127: 3 030 домов, до 1980 года 1 601. Уточнение: в B25127 считается только занятое жилье ("Occupied housing units"), то есть 3 030 это занятые дома на одну семью. "К востоку от I-35E" это расчет по карте, не цифра источника; мой расчет тоже дал 100% части города в 75057 к востоку |
| age-75067 | 75067: 1994 (±2); 2019-2023: 1993 (±1); владельцы 1991 (±1), съемное 1995 (±1); 28 995 единиц. 15,0 / 53,1 / 18,5 / 13,4%. Дома на одну семью до 1980: 25,6% | те же | да | Файл и сайт: 1994, 2. B25037: 1993, 2, 1991, 1, 1995, 1. Строка B25034: 28995, 439, 3432, 5375, 8123, 7263, 2989, 824, 282, 52, 216. B25127: 3 170 из 12 382 |
| age-75077 | 75077: 1994 (±2); 2019-2023: 1993 (±1); владельцы 1993 (±2), съемное 1999 (±4); 15 559 единиц. 16,0 / 53,6 / 16,8 / 13,5%. Только 29% земли это Lewisville | те же | да | Файл и сайт: 1994, 2. B25037: 1993, 2, 1993, 2, 1999, 4. Строка B25034: 15559, 768, 1336, 2620, 4776, 3562, 2125, 206, 109, 51, 6 |
| age-75056 | 75056: 2006 (±1); 2019-2023: 2005 (±1); владельцы 2004 (±2), съемное 2010 (±2); 29 056 единиц. 14,3 / 20,0 / 26,1 / 39,7%. В основном The Colony (51,9% земли в 2020) | те же | да | Файл: 2006, 1. B25037: 2006, 1, 2004, 2, 2010, 2. Строка B25034: 29056, 1568, 9956, 7592, 2238, 3559, 3574, 382, 107, 80, 0 |
| age-75010 | 75010 (2,0% земли в Lewisville): медиана 2005 (±1); 3,1 / 32,4 / 29,2 / 35,4% | те же | да | Файл: 2005, 1. Строка B25034: 14322, 524, 4545, 4177, 2618, 2020, 302, 77, 16, 25, 18 |
| age-75019 | 75019 (0,8% земли в Lewisville): 1995 (±1); 6,1 / 61,3 / 12,1 / 20,5% | те же | да | Файл: 1995, 1. Строка B25034: 17530, 320, 3266, 2119, 5782, 4965, 815, 113, 142, 8, 0 |
| age-lewisville-place | Lewisville city, Texas: 1997 (±1); 2019-2023: 1996 (±1); владельцы 1996 (±1), съемное 1998 (±2); 54 237 единиц; 14,3 / 42,5 / 20,1 / 23,1%. Дома на одну семью 27 489, из них 21,0% (5 761) до 1980. 53,7% занятого жилья снимают. ACS берет границы на 1 января последнего года, земля после 2020 года учтена | data.census.gov B25035, g=160XX00US4842508; Summary File | да | data.census.gov: "1600000US4842508", "1997", "1", "Lewisville city, Texas". B25037: 1997, 1, 1996, 1, 1998, 2. Строка B25034: 54237, 2146, 10405, 10890, 12891, 10146, 4829, 1574, 786, 189, 381. B25127: 27 489 из 51 915 занятых, до 1980 года 5 761. B25036: съемное 27 874 из 51 915, это 53,7%. Цитата на census.gov (страница "Geography Boundaries by Year"): "The ACS usually uses legal boundaries as of January 1 of the last year of the estimate period." Слой TIGERweb ACS2024 ("January 1, 2024 vintage") дает ту же землю, что сегодня. Уточнение: 27 489 это занятые дома на одну семью |
| age-frisco-place | Frisco city: 2009 (±1), владельцы 2008 (±1); до 1980 года 1,5% всего жилья, домов на одну семью до 1980 года 1,5% | Summary File b25035, b25037, b25034, b25127 | да | Файл: 2009, 1. B25037: 2009, 1, 2008, 1, 2011, 1. B25034: 1 234 из 80 353 (1,5%). B25127: 846 из 57 248 (1,5%) |
| age-plano-place | Plano city: 1993 (±2), владельцы 1991 (±1); до 1980 года 18,4%, домов на одну семью 24,1%. Совпадает с проверенным разделом Плано | те же | да | Файл: 1993, 2. B25037: 1993, 1, 1991, 1, 1997, 1. B25034: 21 662 из 117 686 (18,4%). B25127: 17 608 из 72 982 (24,1%). В docs/briefs/plano/6b-zip-and-age-verified.md те же 1993, 18,4 и 24,1 |
| age-d1 | Lewisville средних лет: медиана 1997, на 12 лет старше Фриско (2009) и на 4 года моложе Плано (1993). Старое ядро 75057 к востоку от I-35E (половина домов на одну семью до 1980). По городу каждый пятый дом на одну семью до 1980, близко к Плано, намного больше Фриско. Медиана моложе Плано из-за нового, в основном съемного жилья с 2010 года и земли, добавленной после 2020 | Summary File b25035, b25127, b25034, b25036 | нет (цифры верны, причина не из источника) | Все числа подтвердились: 1997, 2009, 1993; 52,8%; 21,0% против 24,1% и 1,5%; жилье 2010 года и позже 23,1% в Lewisville против 13,7% в Плано. "В основном съемное": из занятого жилья 2010 года и позже снимают 56,4% (6 825 из 12 103, B25036), в Плано 70,2%; слово "в основном" держится, но слабо. Причина "земля, добавленная после 2020 года" источником не подтверждается: Census причин не пишет, а выпуск 2019-2023 (граница на 1 января 2023, Castle Hills уже внутри, если дата верна) дал 1996, почти то же. Это догадка помощника |

#### Адреса, которые я открыл сам (3 октября 2026)

- https://postalpro.usps.com/ZIP_Locale_Detail и https://postalpro.usps.com/mnt/glusterfs/2026-10/Zip_Locale_Detail.xlsx
- https://postalpro.usps.com/storages/2016-12/2727_Definitions.pdf
- https://www2.census.gov/geo/docs/maps-data/data/rel2020/zcta520/tab20_zcta520_place20_natl.txt
- https://www2.census.gov/programs-surveys/acs/summary_file/2024/table-based-SF/data/5YRData/acsdt5y2024-b25034.dat, -b25035.dat, -b25036.dat, -b25037.dat, -b25127.dat
- https://www2.census.gov/programs-surveys/acs/summary_file/2023/table-based-SF/data/5YRData/acsdt5y2023-b25035.dat
- https://www2.census.gov/programs-surveys/acs/summary_file/2024/table-based-SF/documentation/ACS20245YR_Table_Shells.txt
- https://data.census.gov/api/access/data/table?id=ACSDT5Y2024.B25035&g=160XX00US4842508 (и так же для B25034, B25036, B25037, B25127 и всех десяти участков и городов)
- https://api.census.gov/data/2024/acs/acs5?get=NAME,B25035_001E&for=zip%20code%20tabulation%20area:75010,75019,75022,75028,75056,75057,75067,75077 (302, нужен ключ) и https://api.census.gov/data/2024/acs/acs5/variables/B25035_001E.json
- https://tigerweb.geo.census.gov/arcgis/rest/services/TIGERweb/tigerWMS_ACS2024/MapServer/28 и tigerWMS_Current/MapServer/28 (запрос GEOID 4842508), tigerWMS_Current/MapServer/2 (участки ZCTA), Transportation/MapServer/2 (I-35E)
- https://www.census.gov/programs-surveys/acs/geography-acs/geography-boundaries-by-year.2010.html
- https://www.arcgis.com/sharing/rest/content/items/fb8ac427a51c426b9c70cfcee62068ab и https://services2.arcgis.com/kXGqZY4GIOcEYxoF/arcgis/rest/services/Zip_Code_Boundaries/FeatureServer/1/query?where=1%3D1&outFields=*&returnGeometry=false&f=json
- Не открылись: https://www.cityoflewisville.com/our-services/castle-hills-residents (403), https://www.cityoflewisville.com/about-lewisville/our-history (403)

Мои выписки: папка work-6b-verify (строки из файлов Census по десяти участкам и городам, строки USPS и файла связи, итоги сверки и расчетов площади).

## 7. Офис

Файла раздела для этой части не было: она написана при сборке по CLAUDE.md, по краулу живой страницы (`source/crawl/pages/plumber-lewisville-tx.json` и `source/crawl/html/plumber-lewisville-tx.html`, обход 30 сентября 2026) и по файлам нового сайта (`site/src/content/pages/plumber-lewisville-tx.md`, `site/src/layouts/ServicePage.astro`, `site/src/components/CallButtons.astro`, `Header.astro`, `Callbar.astro`, `Footer.astro`, `FAQList.astro`, `site/src/lib/schema.ts`, прочитаны 3 октября 2026 около 10:50). Карточки Google у Lewisville нет, проверять вживую было нечего.

### 7.1. Что говорит CLAUDE.md

- Офисы есть только во Frisco и в Plano. Страницы остальных восьми городов описывают обслуживание города из ближайшего офиса: "The other eight city pages describe service coverage of that city from the nearest office. Never invent a local office, address or phone for a city that has none."
- Офис Frisco: 12800 Westridge Blvd, Suite 116, Frisco, TX 75035, линия 469-998-8999. Офис Plano: 5700 Tennyson Pkwy, Suite 300, Plano, TX 75024, линия 980-899-7997.
- Телефоны стоят в шапке, в подвале, в кнопках звонка и в блоках офисов на страницах Frisco и Plano. В абзацах и в ответах FAQ их нет.
- Схема: один бизнес на весь сайт с обоими офисами; страница города без офиса ссылается на организацию и называет город в `areaServed`.
- Одобренная строка про дежурство: "A licensed plumber is on duty 24/7". В каком городе сейчас дежурный сантехник, не показываем. Времени приезда в своих словах не обещаем.
- Про расстояние есть одна формулировка, и она описывает район, а не время приезда: "About a twenty minute drive from our Frisco or Plano office" (она для мест вне списка городов).
- Страница города не называет соседние города и не ссылается на страницы других городов (правило 7).

**Чего в CLAUDE.md нет: какой из двух офисов обслуживает Lewisville.** Не сказано и то, как называть офис на странице города без офиса: по имени ("our Plano office") или без названия города. Первое упирается в правило 7, потому что Plano и Frisco для Lewisville другие города. Оба вопроса стоят в части 10 (вопрос 1).

Что есть в проекте вместо ответа (это не слово Дениса):

- Старая схема страницы называет офис Plano: отдельный узел "FPP Plumbing - Plumber in Lewisville, TX" с адресом "5700 Tennyson Pkwy, Suite 300", телефоном "+1-980-899-7997" и точкой офиса Plano на карте.
- На главном фото живой страницы на борту фургона телефон Plano ("980.899.7997").
- Search Console: страница Plano стоит выше страницы Lewisville по 10 запросам с lewisville за 3 месяца (135 показов), 8 из них на местах 1 до 4 (часть 2, раздел 6). Кнопка сайта карточки Google офиса Plano ведёт на /plumber-plano-tx/ (`seo/cannibalization-findings.md`), так что это, скорее всего, карточка Plano. Указан ли Lewisville в зоне обслуживания этой карточки, в файлах проекта не записано.
- Текст главной (`source/home-text-v4.md`, блок «Where We Work») называет Lewisville без офиса: "On the Denton County side, to the west, we send a plumber in Lewisville, a plumber in Carrollton, a plumber in The Colony and a plumber in Little Elm."
- Временная замена фото с работы для Lewisville, которую Денис разрешил 1 октября, это фургон у офиса Frisco (фото 2 и 4, часть 4); на фото 2 телефон Frisco.

### 7.2. Что показывает живая страница

- Адреса офисов в видимом тексте страницы нет, слова office, Frisco, Plano в тексте от H1 до конца тоже нет. В подвале (общий шаблон старого сайта) стоят оба офиса: "Frisco Office", 12800 Westridge Blvd, Suite 116, Frisco, TX 75035, 469-998-8999, и "Plano Office", 5700 Tennyson Pkwy, Suite 300, Plano, TX 75024, 980-899-7997 (сверено по сохранённому HTML). Там же "all rights reserved © 2024-2026 License M - 44816".
- Карты нет: в коде страницы нет ни одной встроенной карты (единственный iframe это служебный тег Google Tag Manager).
- Телефоны: оба номера ссылками `tel:` в шапке и в нижней панели, по четыре раза каждый, первым идёт 980-899-7997. Нижняя панель свёрстана тегом H2: "980-899-7997 469-998-8999" (шаблон старого сайта). В абзацах и в FAQ телефонов нет.
- Описание страницы: "Licensed Lewisville plumbers who find it first." Своего офиса в городе страница прямо не обещает, но второй бизнес в схеме с именем города и адресом Plano против правила "one business entity".
- Схема: узел `["LocalBusiness","Plumber"]` с именем "FPP Plumbing - Plumber in Lewisville, TX", адресом, телефоном и точкой офиса Plano, часами 24/7, `priceRange` "$$" и `areaServed`: Lewisville, Flower Mound, The Colony, Carrollton, Highland Village. Подробно: часть 1, раздел 6, и `1-live-page-tables.md`, часть C.

### 7.3. Что новый сайт показывает на этой странице сегодня

Файл страницы: layout "city", city "Lewisville". Полей `office`, `call_office` и `office_map` в нём нет (они бывают у страниц офисов: у Frisco стоят `office: "frisco"` и `call_office: true`).

- Над H1 строка "A licensed plumber is on duty 24/7" (её получают все страницы городов и страница emergency).
- Под вступлением две кнопки звонка без цифр: "Call" и "Frisco office" (красная), "Call" и "Plano office" (с обводкой); рядом кнопка "Request Service". Одна кнопка со своим номером бывает только на странице офиса с полем `call_office`.
- Блока офиса и карты нет: шаблон ставит их только на странице, которая записана у офиса как его собственная (/plumber-frisco-tx/ и /plumber-plano-tx/).
- Шапка: оба номера (Frisco, потом Plano) и кнопка Call, которая открывает окно "Call the office closest to you" с двумя офисами (без скрипта набирает Frisco). В панели Menu оба офиса с адресами и номерами. На телефоне липкая панель звонка с обоими номерами. Подвал общий для всего сайта: оба офиса.
- Первый экран: главным фото встаёт первая картинка текста, то есть то же фото фургона со старого адреса, с пустым alt.
- Отзывы: в тексте стоит метка `<!-- reviews -->`, но в `reviews/site-reviews.json` ключа этой страницы нет, значит блок отзывов не выводится. Поля `reviews_heading` ("What Lewisville Homeowners Say About FPP Plumbing") и `reviews_intro` ("Real Google reviews from people who called us about a leak.") записаны в файле страницы, но шаблоны в `site/src` их не читают (поиск при сборке).
- FAQ выводится раскрывающимся списком, вопрос жирным текстом, не заголовком (`FAQList.astro`).
- Схема: один бизнес (Plumber) с обоими офисами и лицензией "Responsible Master Plumber, License M-44816", как на всём сайте, и узел Service с именем "Plumber in Lewisville, TX", `serviceType` "Plumbing", поставщиком организацией и `areaServed` только Lewisville. Отдельного бизнеса для города, чужих городов в `areaServed` и `priceRange` новый сайт на этой странице не делает: это исправлено самим шаблоном.
- Слов про офис в тексте новой страницы нет, как и на живой. Есть "You call, a real person takes the details and holds you a window" и ответ FAQ "Same day for most calls, and we schedule a real window rather than a half day guess." (часть 1, раздел 6).

### 7.4. Что из этого следует для новой страницы

- Блока офиса, карты, адреса и своего телефона у страницы Lewisville быть не должно. Две кнопки остаются, пока Денис не назовёт офис. Если он назовёт один, решить с ним, ставить ли на первый экран одну кнопку с номером этого офиса или оставить две.
- В тексте нужна одна честная фраза о том, откуда мы приезжаем в Lewisville, без минут и часов. Писать её можно только после ответа Дениса (какой офис и как его назвать).
- Фразу страницы Frisco про то, кто приедет ("the plumber at your door may be Nick, Christopher or Denys"), слово в слово не повторять: она стоит в блоке офиса Frisco.
- Заголовок и строку над отзывами решать вместе с выбором отзывов (часть 5): "Real Google reviews" станет неправдой с отзывом Thumbtack, а "Lewisville homeowners" и "called us about a leak" файлами не подтверждены.

## 8. Посты и гайды

Файл раздела: `docs/briefs/lewisville/8-links.md`, вставлен целиком. Заголовок файла: «8. Истории из Lewisville на сайте и ссылки для страницы Lewisville».

Таблица рядом: `8-links-gsc-other-pages.md` (все запросы со словом lewisville, которые Google показывал на других страницах сайта, за 3 и 16 месяцев).

Собрано 3 октября 2026, ночью и утром. Только чтение: в проекте ничего не менялось, страница Lewisville не переписывалась.

### Откуда данные

- Живой сайт: снимок 64 страниц `source/crawl/pages/*.json` (снят 30 сентября 2026).
- Новый сайт: `site/src/content/pages/**/*.md`, прочитаны 3 октября около 10:10; шаблоны `site/src/components/Header.astro`, `Footer.astro`, `site/src/layouts/Home.astro`, `site/src/design/design.json`, `home-text.json`.
- Search Console: `source/gsc/performance-3m/Pages.csv`, `performance-16m/Pages.csv`, `page-query-3m.csv` (1 июля до 28 сентября 2026), `page-query-16m.csv` (31 мая 2025 до 28 сентября 2026), `inspection-2026-10-01.csv`.
- Ещё искал слово Lewisville: `source/dictation/`, восемь Word файлов в `source/`, `photos/*.csv`, `reviews/all-reviews.csv`, посты Google в `source/gbp-takeout/`, `docs/`, `seo/keyword-map.md`.

**Как читать цифры.** «Итог» это строка страницы в `Pages.csv`: клики / показы / место. «Сумма строк» это сумма строк страницы в `page-query`; Google прячет редкие запросы, поэтому она меньше итога. Место в сумме строк посчитано как среднее с весом по показам.

### 1. Посты и гайды, где работа была в Lewisville

**Таких нет ни одного.** Ни на живом сайте, ни на новом нет поста или гайда, где работа была в Lewisville или где Lewisville назван местом истории.

Что проверено:
- 17 постов и 14 гайдов. На живом сайте слово Lewisville в них стоит только в меню шапки. В файлах нового сайта его нет ни в одном посте и гайде.
- Lewisville нет даже в перечислениях городов внутри постов: там стоит "Frisco, Plano, McKinney, Allen, Little Elm, Prosper". Ни один пост и ни один гайд не ссылается на страницу Lewisville.
- Диктовки Дениса (`source/dictation/`): ни одного упоминания.
- Архив фото: ни одного кадра с городом Lewisville. В `photos/captions-en.csv` Lewisville стоит только как страница, где временно стоят фото фургона 2 и 4 (сняты у офиса во Frisco; на странице Lewisville в alt нельзя писать Frisco). В журнале: «Celina и Lewisville: пока фото фургона, Денис снимет на ближайших вызовах.»
- Отзывы: за страницей Lewisville записаны три отзыва (Allen Thong, John Wilson, Serge Geshka), ни один не называет Lewisville. Отзывы разбирает раздел 5.
- Посты Google (Takeout): Lewisville один раз, в списке городов под постом от 20 декабря 2024 про чугунную трубу в подполе; город работы не назван.
- Word файлы: только перечисления городов (раздел 2.2).

Вывод: своей истории у страницы Lewisville нет, ссылаться на «свой» пост нельзя. Живой материал может дать только Денис (вопросы в конце).

Для сравнения сама страница `/plumber-lewisville-tx/`:

| Период | Итог | Сумма строк |
|---|---|---|
| 3 месяца | 2 / 3,531 / 25.74 | 118 строк, 0 / 3,244 / 25.86 |
| 16 месяцев | 2 / 63,896 / 50.88 | 258 строк, 0 / 61,559 / 51.06 |

Оба клика пришли по скрытым запросам. Статус в Google: "Submitted and indexed", последний обход 16 августа 2026. В `docs/pages-plan.md` страница в группе 3, номер 10, «Старый текст».

### 2. Что про Lewisville уже сказано на других страницах

Ни одного случая и ни одной цифры про Lewisville нет нигде. Есть перечисления городов, одна характеристика в Word текстах и фото галереи, где город взят со старого сайта.

#### 2.1. Страницы услуг на новом сайте

- Slab leak repair (`/slab-leak-repair-frisco-plano-mckinney/`): "...a plumber in Lewisville with a warm spot on the floor."
- Water leak detection (`/water-leak-detection-frisco-plano/`): "...a plumber in Lewisville with a bill that makes no sense."
- Emergency (`/emergency-plumbing-services/`): "...or a plumber in Lewisville: same line, same fee structure, and the time you hear on the phone is the real one."
- Expansion tank (`/water-heater-repair-frisco-mckinney/`): список "We provide emergency water heater repair and replacement in:", в нём "Lewisville".
- PRV replacement (`/prv-replacement-frisco-plano/`): фото со старого сайта с alt "Newly installed PRV valve set in ground near water meter during outdoor plumbing in Lewisville, TX". Ссылки на Lewisville нет. Про город этого фото смотри 2.4.

#### 2.2. Одобренные Word тексты, которых ещё нет на сайте

Единственные фразы, где про Lewisville сказано что-то кроме «едем туда»:
- `FPP-Sewer-Line-Repair-Page.docx`: "The older cast iron work leans toward the established streets a plumber in Carrollton or a plumber in Lewisville sees..."
- `FPP-Faucet-Shower-Valve-Page.docx`: "Seized shut-offs and diverters that no longer divert are more the territory of a plumber in Carrollton or a plumber in Lewisville..."
- `FPP-Hose-Bib-Page.docx`: "...or a plumber in Lewisville does the same job the same way, anchored, sealed and tested under pressure."
- `FPP-Drain-Cleaning-Page.docx`: "...or a plumber in Lewisville gets cleared the same day and gets the camera afterward."

Откуда слова про чугун и закисшие краны в Lewisville, в диктовках не записано. Это вопрос к Денису, а не факт.

#### 2.3. Главная

`source/home-text-v4.md`, блок «Where We Work»: "On the Denton County side, to the west, we send a plumber in Lewisville, a plumber in Carrollton, a plumber in The Colony and a plumber in Little Elm." В FAQ "What areas do you serve?" Lewisville в списке десяти городов.

#### 2.4. Галерея: девять фото с Lewisville в alt

На `/gallery/` девять фото (файлы `photo_2024-12-24_18-5x-xx`) с "in Lewisville, TX" в alt: PRV в земле у счётчика (`18-56-20`), старый PRV с краном до замены (`18-55-45`) и новый после (`18-55-46`), газовый водонагреватель на 50 галлонов на чердаке (`18-53-33`), fill и flush valve унитаза (`18-54-10`), восковое кольцо (`18-54-52`), коробка стиральной машины на ProPress (`18-53-48`), disposal и слив (`18-55-22`), ProPress на линии водонагревателя (`18-54-31`).

Город взят из alt старого сайта, не из места съёмки; в архиве этих файлов нет. Похоже, города раздавали по кадрам: `18-54-10` (унитаз, "Lewisville") стоит рядом с `18-54-11` "Flush valve removed from toilet tank... in Frisco" и `18-54-13` "Toilet tank lifted off to access and replace flush valve in Frisco"; кадры коммерческого унитаза `18-55-00` до `18-55-07` подписаны Plano, McKinney и The Colony. По правилу проекта фото другого города не идёт на страницу города, пока Денис не назовёт работу. Пара PRV до и после (`18-55-45`, `18-55-46`) могла бы стать первой историей Lewisville, если Денис подтвердит город.

#### 2.5. Сама страница Lewisville сегодня

Местные утверждения без записанного источника: "Most leaks in Lewisville are discovered by a bill, not by a puddle."; заголовок "Slab Leaks in Older Lewisville Homes"; "In most Lewisville homes we go under the house rather than through it."; "a leak that adds thirty or forty dollars a month". Улиц и районов Lewisville на странице нет. В диктовках подтверждения этим фразам нет.

### 3. На что ссылаться странице Lewisville и с какими якорями

#### 3.1. Главная: одна ссылка

Правило 6: один раз, в последнем абзаце вступления, якорь ровно "plumber near me", фраза общая и не повторяет другие страницы. Сейчас ссылка стоит не во вступлении, а в третьем абзаце первого раздела: "If you searched for a [plumber near me](/) after a bill you could not explain, start with the number itself...". Нужна новая фраза во вступлении.

Занятые начала: "If you searched for a plumber near me..." (Carrollton, McKinney, Prosper, The Colony, Lewisville и ответ FAQ на главной); "Searched for a plumber near me..." (Allen, Celina, garbage disposal); Frisco "If you typed plumber near me into your phone somewhere in Frisco...". У Carrollton та же тема счёта: "...because the bill jumped and nothing looks wrong".

#### 3.2. Все 13 услуг

Список из `site/src/design/design.json`. Якорь по образцу Frisco: имя услуги. Сейчас на странице Lewisville ссылки на 11 услуг из 13: нет hose bib и нет expansion tank.

Цифры «запросы Lewisville» это запросы страницы Lewisville за 16 месяцев по теме услуги: показы / место (по 3 месяцам там, где есть). Полный список запросов со словом lewisville на других страницах: `8-links-gsc-other-pages.md`.

| № | Услуга | URL | Якорь сейчас | Предлагаемый якорь | Запросы Lewisville, 16 мес | Где встаёт |
|---|---|---|---|---|---|---|
| 1 | Emergency plumbing | `/emergency-plumbing-services/` | "emergency plumbing" | "emergency plumbing" | 5,660 / 46.4 | блок «если течёт прямо сейчас» |
| 2 | Slab leak repair | `/slab-leak-repair-frisco-plano-mckinney/` | "slab leak repair" (2 раза) | "slab leak repair" | 5,298 / 36.7; за 3 мес 905 / 9.8 | короткий абзац про slab |
| 3 | Water leak detection | `/water-leak-detection-frisco-plano/` | "leak detection" (2 раза) | "water leak detection" | 2,024 / 59.4; за 3 мес 374 / 17.6 | скрытые утечки, счёт |
| 4 | Sewer line repair and camera inspection | `/drain-services/` | "main line service" | "sewer line repair and camera inspection" | 430 / 70.6 | канализация, корни |
| 5 | Drain cleaning | `/clogged-drain-cleaning-frisco-plano/` | "drain cleaning" | "drain cleaning" | 1,563 / 80.6 | засоры |
| 6 | Water heater repair and replacement | `/water-heaters/` | "water heater repair" | "water heater repair and replacement" | 4,664 / 64.7 | водонагреватели |
| 7 | Expansion tank replacement | `/water-heater-repair-frisco-mckinney/` | нет | "expansion tank replacement" | 358 / 50.6 | рядом с водонагревателем |
| 8 | Faucet and shower valve repair | `/fixture-installation-repair/` | "faucet and shower valve repair" | "faucet and shower valve repair" | 3,144 / 49.1 | краны и смесители |
| 9 | Hose bib repair | `/hose-bib-repair-frisco-plano/` | нет | "hose bib repair" | 17 / 17.9 | уличный кран, мороз |
| 10 | Garbage disposal repair | `/garbage-disposal-repair-frisco-plano/` | "garbage disposal repair" | "garbage disposal repair" | 849 / 59.1 | строка в списке |
| 11 | Water line repair | `/water-lines/` | "water line repair" | "water line repair" | 3,829 / 61.9 | линия от счётчика, "pipe break" |
| 12 | Toilet repair | `/toilet-repair-frisco-plano/` | "toilet repair" | "toilet repair" | 39 / 59.5 | строка в списке |
| 13 | PRV replacement | `/prv-replacement-frisco-plano/` | "PRV replacement" | "PRV replacement" | 28 / 17.4 | давление |

Пояснения:
- Старый якорь "main line service" не держит ни одного запроса (на странице нет запросов со словами "main line"), замена ничего не теряет. Якорь "water heater repair" остаётся частью нового "water heater repair and replacement" (запрос "water heater repair lewisville" 892 показа за 16 месяцев).
- Карта ключей запрещает странице Lewisville бороться за "faucet repair" (его держит страница смесителей). Поэтому смесителям один короткий блок со ссылкой, без разбора ремонта.
- Запросы «slab leak plus Lewisville» Google показывает на странице города намного выше, чем на странице услуги: "slab leak repair lewisville" за 3 месяца 200 показов, место 9.56 на странице города; на странице slab leak за 16 месяцев 432 показа, место 77.89. Абзац про slab с якорем "slab leak repair" держит это и не разбирает метод.
- Запросы «услуга плюс Lewisville» за 16 месяцев шли и на страницы услуг (slab leak 1,129 показов, garbage disposal 231, water lines 50), все дальше 60-го места. За 3 месяца 13 запросов со словом lewisville ушли на страницу Plano: 175 показов, место 8.28; "plumber lewisville tx" там 76 показов, место 16.92, а на самой странице Lewisville 152 показа, место 33.39. Таблица в `8-links-gsc-other-pages.md`.

#### 3.3. Посты и гайды: что подходит по теме

Своих историй нет, поэтому ниже гайды и посты без чужого города в адресе, title и H1, которые ложатся на разделы страницы. Якорь описывает тему, не услугу и не "plumber in Lewisville"; рядом со ссылкой нельзя называть город, где была работа в этом посте. Важность А: ставить в любом случае; Б: если на странице есть абзац на эту тему; В: по желанию.

| Важность | Страница | Итог 3 мес | Итог 16 мес | Режим | Предлагаемый якорь | Где встаёт |
|---|---|---|---|---|---|---|
| А | `/plumbing-guide/how-to-shut-off-main-water-valve-texas/` | 104 / 9,953 / 7.64 | 212 / 22,630 / 7.14 | ЗАМОРОЖЕН | "how to find and close your main shut-off valve" (сейчас "shut-off guide") | «если течёт прямо сейчас» |
| А | `/plumbing-guide/angle-stop-valve-leaking-under-sink/` | 66 / 12,812 / 8.07 | 129 / 23,802 / 7.94 | ЗАМОРОЖЕН | "a shut-off under the sink that weeps when you turn it" (сейчас "angle stop guide") | закисшие краны |
| А | `/plumbing-guide/water-leak-yard-tips-2026/` | 0 / 157 / 16.87 | 0 / 311 / 11.88 | обычная | "watching the water meter for a leak out in the yard" | блок «счёт вырос, мокрого нет» |
| Б | `/plumbing-guide/automatic-water-shut-off-valve-install-north-texas/` | 28 / 2,651 / 7.73 | 30 / 2,742 / 7.75 | приносит клики | "a valve that shuts the water off by itself when it senses a leak" | скрытые утечки |
| Б | `/plumbing-guide/water-pressure-dropping-tips-2026/` | 2 / 893 / 13.94 | 4 / 1,653 / 11.15 | обычная | "why the water pressure keeps dropping" | рядом с PRV |
| Б | `/blog/clogged-kitchen-sink-chain-snake/` | 2 / 691 / 13.81 | 3 / 930 / 15.54 | обычная | "a kitchen line still clogged past the trap" | «Drains That Keep Coming Back» |
| В | `/plumbing-guide/bathtub-drain-slow-draining-tips-2026/` | 3 / 1,073 / 35.96 | 3 / 1,810 / 29.05 | обычная | "a bathtub that drains slowly" | засоры |
| В | `/blog/clogged-toilet-auger-fix-blog/` | 2 / 816 / 10.39 | 4 / 1,327 / 9.76 | обычная | "what a toilet auger clears that a plunger cannot" | строка про унитазы |
| В | `/plumbing-guide/how-long-do-water-heaters-last-guide/` | 1 / 221 / 14.56 | 2 / 663 / 10.8 | обычная | "how many years a tank water heater lasts" | водонагреватели |

Оговорки: гайд про двор держит случаи из Plano, McKinney и Frisco; пост про кухонную мойку и пост про toilet auger это вызовы во Frisco (в тексте "On this Frisco call", "a homeowner in Frisco"); гайд про автоматический кран держит цены ($1,000, $2,000 до $5,000) и фразу "we reroute the line into the garage"; гайд про срок водонагревателя держит tankless и цены. На страницу Lewisville ничего из этого не переносить, только ссылка.

#### 3.4. На что страница Lewisville не ссылается

- На другие города. Сейчас в тексте страницы ссылок на города нет и названий других городов нет (Frisco, Plano, McKinney стоят только внутри адресов услуг). Так и оставить.
- На посты и гайды с другим городом в адресе, title или H1: `/plumbing-guide/why-is-my-water-bill-so-high-frisco-tx/` (тема счёта совпадает, но "A Real Frisco TX Service Call" в H1), `/plumbing-guide/water-leak-after-bathroom-remodel-frisco-tx/`, `/plumbing-guide/slab-leak-repair-plano-tips-2026/` (ещё и спорит со страницей slab leak), все посты с Frisco, Plano или Little Elm в названии, `/top-emergency-plumber-calls-frisco/`.
- На `/plumbing-guide/plumber-near-me-north-texas-guide-to-avoid-scams/` (якорь "plumber near me" принадлежит главной, внутри цены) и на гайды с ценами `/plumbing-guide/emergency-plumbing-repair-cost-guide-2026/`, `/plumbing-guide/water-heater-replacement-cost-2026/` (на странице города действует правило цен: только $49).
- Шапка, меню и подвал ссылаются на все города на каждой странице: это навигация, правило 7 про текст.

#### 3.5. Внешняя ссылка на официальный источник

Нужна одна (по образцу Frisco). Сейчас её нет ни на живой, ни на новой странице Lewisville. Адрес ищет раздел 6a.

### 4. Кто уже ссылается на `/plumber-lewisville-tx/` на новом сайте

В файлах страниц 5 ссылок из 5 файлов:

| Откуда | Якорь |
|---|---|
| `/emergency-plumbing-services/` | "plumber in Lewisville" |
| `/slab-leak-repair-frisco-plano-mckinney/` | "plumber in Lewisville" |
| `/water-leak-detection-frisco-plano/` | "plumber in Lewisville" |
| `/water-heater-repair-frisco-mckinney/` | "Lewisville" (список городов) |
| `/contact/` | "Lewisville, TX" (список городов) |

Кроме файлов страниц (это навигация, не текст):
- Главная, три ссылки по решению Дениса: "plumber in Lewisville" в тексте «Where We Work», карта (подпись "Lewisville", aria-label "Plumber in Lewisville"), ряд городов под картой ("Lewisville").
- На каждой странице: выпадающий список городов в шапке, панель Menu (раздел Cities), подвал (Areas), всё с якорем "Lewisville".
- Два старых служебных адреса ведут на страницу переадресацией 301 (`site/src/data/redirects.csv`, строки 107 и 108): `/plumber-lewisville-tx/photo_2025-05-15_20-41-52/` и `/plumber-lewisville-tx/1-2/`.

На живом сайте в тексте те же пять страниц, остальное меню.

**Чего не хватает** (правки других страниц, в их очередь):
- Девять страниц услуг из 13 не ссылаются на Lewisville, хотя услуга должна ссылаться на все десять городов: `/drain-services/`, `/clogged-drain-cleaning-frisco-plano/`, `/water-heaters/`, `/fixture-installation-repair/`, `/hose-bib-repair-frisco-plano/`, `/garbage-disposal-repair-frisco-plano/`, `/water-lines/`, `/toilet-repair-frisco-plano/`, `/prv-replacement-frisco-plano/`. Для четырёх из них готовая фраза с "plumber in Lewisville" уже есть в Word текстах (sewer line, drain cleaning, hose bib, faucet; раздел 2.2).
- Ни один пост и ни один гайд не ссылается на Lewisville. Это нормально, пока нет истории из Lewisville (правило 12: пост ссылается на город, который в нём назван).

### 5. Расхождения с правилами, найденные по дороге

Ничего не исправлено, это список для автора страницы и для очереди других страниц.

1. Страница Lewisville: ссылка на главную не во вступлении, её начало как у четырёх других городов; цифра "thirty or forty dollars a month" не от Дениса; FAQ "How fast can you get to Lewisville?" отвечает "Same day for most calls..." (обещание времени своими словами); "In most Lewisville homes we go under the house rather than through it" без источника, а по CLAUDE.md ремонт это тоннель или вскрытие плиты.
2. Страница Lewisville: нет ссылок на hose bib и expansion tank; якорь "main line service"; нет пробела: "[angle stop guide](/plumbing-guide/angle-stop-valve-leaking-under-sink/)explains"; у первого фото пустой alt.
3. Галерея и страница PRV показывают фото с городом Lewisville из alt старого сайта, город не проверен (2.4).
4. Гайд про автоматический кран (приносит клики): "On older homes with the shutoff outside, we reroute the line into the garage instead." Reroute как предложение запрещён; правка только по слову Дениса.
5. Word текст drain cleaning: "gets cleared the same day and gets the camera afterward" расходится с правилом Дениса о камере (до чистки, если линия пропускает, после, если забита) и со словами про время.
6. Пост Google от 20 декабря 2024 называет города вне списка (Dallas, Coppell, Denton, Garland, Fairview, Flower Mound).

### 6. Вопросы к Денису

1. Были ли у вас работы в Lewisville, которые можно рассказать: что сломалось, что нашли, что сделали? Есть ли фото или видео оттуда?
2. В галерее девять фото подписаны Lewisville (PRV в коробке у счётчика до и после, водонагреватель на 50 галлонов на чердаке, унитаз, восковое кольцо, коробка стиральной машины, disposal, линия к водонагревателю). Эти работы правда были в Lewisville? Если пара PRV оттуда, она может стать первой историей на странице.
3. В одобренных текстах сказано, что в Lewisville и Carrollton больше старого чугуна в канализации и закисших кранов. Это ваше наблюдение? Дома в Lewisville правда старше, чем во Frisco?
4. Slab leaks в Lewisville: часто ли, и как чините там, тоннелем или через плиту? Сейчас на странице написано «в большинстве домов Lewisville идём под дом».
5. Самый частый вызов в Lewisville это правда «счёт вырос, мокрого нигде нет», как построена страница сейчас? Если другой, то какой?

## 9. Чем Lewisville отличается от Frisco и Plano

Только то, что подтверждено данными Search Console из части 2 или официальной страницей из части 6. У каждого пункта назван источник. Цифры Frisco и Plano взяты из тех же выгрузок Search Console, из таблиц Census в части 6 и из брифа Plano (`docs/plano-brief-2026-10-03.md`, факты там прошли перепроверку). Это для автора: на самой странице Lewisville соседние города не называются.

1. **Страница почти без кликов и далеко от первой страницы Google.** Lewisville за 3 месяца: 2 клика, 3,531 показ, место 25.74. Frisco: 42 клика, 44,080 показов, место 15.2. Plano: 98 кликов, 56,197 показов, место 6.77. За 16 месяцев: Lewisville 2 клика, Frisco 110, Plano 103. Главные запросы города стоят на местах 33 до 42 («plumber lewisville tx» 33.4, «plumber lewisville» 34.3), ближе всех к верху только slab leak repair с городом (9.0 до 12.9). Терять почти нечего, задача страницы подняться; правило «что держит показы, остаётся» всё равно действует (часть 2, раздел 4). Источник: `source/gsc/performance-3m/Pages.csv` и `performance-16m/Pages.csv` (та же выгрузка, что в части 2), часть 2, разделы 1 и 2.
2. **Нет офиса и карточки Google, страница живёт запросами с именем города, а часть их забирает страница Plano.** У Lewisville 88 процентов показов с известным запросом идут по запросам со словом lewisville (2,867 из 3,244 за 3 месяца, часть 2, раздел 1). У страницы Plano наоборот: 62 процента показов с известным запросом идут по запросам без слова plano (30,710 из 49,302, бриф Plano, «Коротко», пункт 2), скорее всего через карточку офиса. У Frisco по моему подсчёту при сборке (тот же `page-query-3m.csv`, запросы, где есть слово frisco) 48 процентов (19,111 из 39,503). По запросам Lewisville страница Plano стоит выше страницы Lewisville по 10 запросам, 8 из них на местах 1 до 4 (часть 2, раздел 6). Для текста это значит: имя города и варианты «plumber in Lewisville», «Lewisville plumber», «plumbers in Lewisville» в абзацах и в части H2 здесь важнее, чем на страницах офисов, а их в абзацах сейчас нет совсем.
3. **Дома в среднем старше, чем во Frisco, немного моложе, чем в Plano, и неровные по городу.** Медианный год постройки жилья: Lewisville 1997 (±1), Frisco 2009 (±1), Plano 1993 (±2). Дома на одну семью, построенные до 1980 года: Lewisville 21.0% (5,761 дом), Plano 24.1%, Frisco 1.5%. Жильё 2010 года и позже: Lewisville 23.1%, Plano 13.7%, Frisco 46.7%. Старое ядро Lewisville лежит в индексе 75057: там 52.8% домов на одну семью построены до 1980 года, медиана жилья владельцев 1982 (±7); то, что 75057 лежит к востоку от I-35E, это расчёт помощника по карте Census, не цифра источника. Причину, почему медиана моложе Plano, источник не называет. Источник: U.S. Census Bureau, ACS 2020-2024, таблицы B25035, B25037, B25034, B25127 (часть 6, строки age-lewisville-place, age-frisco-place, age-plano-place, age-75057 таблицы проверки 6.4).
4. **Город своими законами называет границу по канализации.** В Lewisville засор от дома до врезки в городскую трубу прочищает хозяин; ремонт хозяин делает до края тротуара (или края дороги, или переулка), а дефект между этим краем и городской трубой город после проверки чинит бесплатно; проверка камерой лицензированного сантехника названа в законе прямо (свод законов Lewisville, разделы 16-99 и 16-100, https://library.municode.com/tx/lewisville/codes/code_of_ordinances?nodeId=PTIICOOR_CH16UT_ARTIISASESY_DIV5PRRESESELICL , часть 6, city-d3, подтверждено двумя проходами). С 1 марта 2013 года город сам канализацию у домов не прочищает (страница "Utility Line Maintenance", архивная копия, city-h5). Plano точку, где кончается ответственность города за канализационную линию, не называет; пишет только, что засор и перелив в доме хозяин чинит сам (бриф Plano, city-d5 с поправкой 2). По Frisco данных в этих файлах нет. Для страницы это повод для одного абзаца о том, что мы смотрим камерой и где кончается линия хозяина, словами Дениса.
5. **Вода из своего озера плюс покупная, и другая цифра жёсткости.** Lewisville берёт воду со своей станции на Lewisville Lake и докупает очищенную воду, в том числе у Upper Trinity Regional Water District; средняя жёсткость 158.5 ppm в отчёте о воде за 2024 год (отчёт 2025 года не найден; обе страницы прочитаны в архивных копиях, сайт города отвечает 403; часть 6, city-f1, city-f2, city-f3). Plano покупает поверхностную воду округа NTMWD (озёра Lavon и Bois d'Arc), в отчёте за 2025 год наибольшее значение жёсткости 200 ppm, разброс 96.0 до 200 (бриф Plano, city-f1, city-f4). Цифры разных лет и разной меры (среднее против наибольшего), прямо сравнивать их нельзя. По Frisco данных о воде в этих файлах нет. Поставщиков, кроме Lewisville Lake и Upper Trinity Regional Water District, на странице не называть: в отчёте города рядом стоят запрещённые для сайта имена.

## 10. Вопросы к Денису и нужные фото

Только то, что знает он один. Собрано из вопросов разделов (части 1, 2, 3, 5, 6, 8), без повторов.

### 10.1. Вопросы

1. **Офис.** Из какого офиса обслуживается Lewisville, Frisco или Plano? Можно ли на странице назвать офис по имени (например "from our Plano office", без ссылки, без минут и часов), или писать без названия города? По правилам страница города соседей не называет. Указан ли Lewisville в зоне обслуживания карточки Google офиса Plano? (Старая схема страницы стоит на адресе Plano, а страница Plano по запросам Lewisville стоит на местах 1 до 4.)
2. **Slab leaks и возраст домов.** Как часто вы чините slab leaks в Lewisville, и как там чаще: тоннелем под фундаментом или через плиту? Лучшие места страницы именно у «slab leak repair lewisville» (места 9 до 13), а текст пишет "Slab Leaks in Older Lewisville Homes" и "In most Lewisville homes we go under the house rather than through it": это правда по вашим вызовам? По Census самые старые дома в индексе 75057, у старого центра (больше половины домов на одну семью до 1980 года), а по городу в основном 80-е и 90-е; сходится? В одобренных Word текстах сказано, что в Lewisville и Carrollton больше старого чугуна в канализации и закисших кранов: это ваше наблюдение? От ответа зависит, большой ли раздел про slab leak и стоит ли он в начале.
3. **Самые частые вызовы.** Правда ли, что в Lewisville чаще всего звонят «счёт вырос, а мокрого нигде нет», как построена страница сейчас ("That is the most common leak call we get", "That is most of what we do here")? Если нет, какие вызовы там самые частые?
4. **Истории.** На сайте нет ни одной истории из Lewisville, в архиве ни одного кадра оттуда. Помните одну или две работы там (что сломалось, что нашли, что сделали), лучше с фото или клипом? Вызовы, где было высокое давление и PRV, сток кондиционера в сливе раковины, slab leak, лопнувший бак на чердаке: какие из них были в Lewisville?
5. **Девять старых фото галереи и главное фото.** Девять фото подписаны на старом сайте "in Lewisville, TX": PRV в земле у счётчика и пара PRV до и после, газовый водонагреватель на 50 галлонов на чердаке, fill и flush valve унитаза, восковое кольцо, коробка стиральной машины на ProPress, disposal и слив, ProPress на линии водонагревателя. Эти работы правда были в Lewisville? Пока нет своего кадра, ставим на первый экран фургон у офиса Frisco (фото 4 свободно, фото 2 уже стоит на Frisco и несёт телефон Frisco), как вы разрешили 1 октября? Где снят фургон на нынешнем главном фото (вопрос про номер "M-38532" на нём уже стоит в утреннем отчёте)?
6. **"Faucet Repair" в title.** Карта ключей запрещает странице Lewisville faucet repair (его держит страница смесителей, у неё по этим запросам 16 показов за 16 месяцев), а слова в title держат 94 показа за 3 месяца и 3,116 за 16 (место около 27). Оставить или заменить другой услугой?
7. **Emergency и "same day" на городской странице.** Можно ли поставить "emergency plumber in Lewisville" в один из H2? Emergency с городом дал 127 показов за 3 месяца и 5,635 за 16, ни один заголовок их не держит, а у страницы emergency в карте ключей стоит запрет на «plumber + city». Вопрос FAQ "How fast can you get to Lewisville?" с ответом "Same day for most calls" по правилу о времени приезда уходит: можно ли на городской странице сказать "same day" так, как на главной, или только без времени совсем?
8. **Отзывы.** Ни один из 407 отзывов не называет Lewisville. Были ли работы John Wilson (водопровод во дворе), Allen Thong (коробка крана стиральной машины) и Serge Geshka (течь подводки) в Lewisville? Serge Geshka называет вас ("Dennis"): снимаем или оставляем исключением? У John Wilson "gave me the quote for labor. I was told that parts were separate": ставим полный текст как есть или ищем замену? Можно ли ставить на Lewisville отзыв с Thumbtack (строка над отзывами сейчас "Real Google reviews"), и какую строку и заголовок ставить над отзывами, если "Lewisville homeowners" не подтверждено? Есть ли недавний клиент из Lewisville со slab leak или поиском течи, которого можно попросить оставить отзыв (свободного отзыва про slab leak нет)?
9. **Давление и вода.** Какое давление вы обычно видите на манометре в домах Lewisville, и где там стоит PRV: в ящике счётчика в земле или в доме? Видите ли вы там последствия жёсткой воды (накипь, картриджи, водонагреватели)? Город в отчёте за 2024 год пишет среднюю жёсткость 158.5 ppm; пересчитывать ли её на странице в grains per gallon (город сам этого не делает)?
10. **Правила города на деле.** Закон Lewisville запрещает без разрешения открывать крышку ящика счётчика и кран у счётчика (кроме пожара; исключение для лицензированных сантехников только про крышку и ключ): писать это на странице или просто советовать главный кран дома? Требует ли инспектор Lewisville на практике разрешение на замену PRV и на ремонт течи под плитой (в бумагах города таких строк нет)? Был ли случай, когда дефект канализации оказался между краем тротуара и городской трубой и его чинил город после вашей проверки камерой (закон 16-99 и 16-100)?
11. **Районы и индекс.** Можно ли называть на странице Castle Hills (конкуренты пишут его частью Lewisville; страницу города о его присоединении прочитать не удалось)? Показывать ли индекс 75056: это почта The Colony, но около четверти площади Lewisville сегодня в нём (надёжные индексы Lewisville 75057, 75067, 75077)?
12. **Газовый водонагреватель.** Запрос «gas water heater repair lewisville» дал 85 показов. Можно ли на сайте писать, что мы ремонтируем газовые водонагреватели (это работа с водонагревателем, не с газовой линией)?

Закрыто раньше словом Дениса, не спрашивать снова: регистрация. 3 октября 2026 Денис сказал, что компания зарегистрирована во всех городах, где работает (`docs/morning-report-2026-10-03.md`, «Ответы Дениса от 3 октября»: «в брифах других городов эту проверку не делаем»). Вопрос части 6 о регистрации FPP в Lewisville в MGO Connect поэтому сюда не перенесён.

### 10.2. Какие фото просить

Подробно в части 4.3. Коротко, по порядку важности:

1. Настоящее фото с работы в Lewisville или фургон FPP на улице в черте города (вертикальный кадр, без номеров домов).
2. Если пара PRV из старой галереи снята в Lewisville: кадр той же работы пошире, с манометром после замены.
3. Скрытая течь в Lewisville: крутящийся счётчик и то, что нашли.
4. Работа slab leak в Lewisville, если была: яма или тоннель, пинхол, спаянное место.
5. Манометр на уличном кране с цифрой давления и PRV там, где он стоит в этих домах.
6. Закисший кран под раковиной или клапан душа, «до» и «после».
7. Водонагреватель в гараже или на чердаке «до» и «после»: подставка, поддон, сброс T&P, расширительный бак.
8. Водопровод во дворе от счётчика до дома: яма, лопнувший участок, новый.
9. Главная канализационная линия: кадр с экрана камеры или яма у тротуара.
10. Работа в доме постарше у старого центра города (индекс 75057), если была.
