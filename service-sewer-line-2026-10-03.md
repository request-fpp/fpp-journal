# Sewer line repair and camera inspection: живая страница и Search Console (3 октября 2026)

Страница https://fppplumbing.com/drain-services/ . Она сейчас не переписывается, текста страницы здесь нет. Источники: краул от 30 сентября 2026 (`source/crawl/pages/drain-services.json`, код `source/crawl/html/drain-services.html`, остальные 63 страницы там же), новая версия `site/src/content/pages/drain-services.md` и собранная `site/dist/drain-services/index.html` (сборка 3 октября 10:38, только прочитана), правки `tools/build_launch_content.py` и `site/src/data/launch-changes.csv`, одобренный текст `source/FPP-Sewer-Line-Repair-Page.docx`, Search Console `source/gsc/` (page-query-3m.csv, page-query-16m.csv, performance-3m и performance-16m Pages.csv, page-query-coverage.csv), `seo/keyword-map.md` и `.csv`, `docs/pages-plan.md`, `reviews/all-reviews.csv`, `site-ledger.md`, `site-reviews.json`.

Длинные таблицы в `docs/briefs/services/sewer-line/`: `sewer-gsc-queries-3m.md` и `-16m.md` (все запросы: тема, хозяин по карте ключей, город, слова в тексте, где стоит фраза), `sewer-gsc-top30.md` (топ 30 обоих периодов и клики), `sewer-gsc-headings.md` (что держит каждый заголовок), `sewer-gsc-phrases.md` (фраза целиком), `sewer-gsc-other-pages-3m.md` и `-16m.md` (другие страницы на запросах темы), `sewer-gsc-reverse.md` (чужие запросы этой страницы), `sewer-gsc-cities.md` (тема с каждым из десяти городов).

Три числа через точку всегда: показы · среднее место · клики. Тире в цитатах помечены словами [em dash] и [en dash].

## Коротко

1. Кормит страницу почти ничего. 3 месяца: 0 кликов, 185 показов, место 30.6 (итог Google); с известным запросом 11 запросов и 99 показов. 16 месяцев: 0 кликов, 7,138 показов, место 65.5; известных 139 запросов и 6,718 показов. Кликов не было ни разу; 6,619 из 6,718 показов пришлись на 13 месяцев до июля 2026, сейчас страница почти выпала.
2. Больше трети показов чужие: drain cleaning (хозяин `/clogged-drain-cleaning-frisco-plano/`, у этой страницы в «must not target») 2,542 из 6,718 за 16 месяцев и 76 из 99 за 3 месяца. Своя тема (sewer, main line, cast iron, камера) 3,667 и 17.
3. Свою тему забирают другие страницы: за 3 месяца у сайта по ней 5,062 показа, у этой страницы 17; Plano 3,411 (место 3.9) и Frisco 1,521 (4.0), в основном по запросам без своего города, то есть, по правилу проекта, через карточки Google. За 16 месяцев главная 5,635 показов и выше этой страницы по 39 запросам.
4. Не терять (кликов нет, только показы на местах 20 до 90): «Sewer Repair» и «Frisco, Plano & McKinney» в title; H2 «Spot Repairs & Sewer Line Replacement»; «cast iron pipes» в тексте (1,653 показа за 16 месяцев, лучшие места страницы 23.6 до 35.7); «main line» в FAQ; «Camera Inspection for Sewer» под вторичный ключ карты.
5. Ломает правила: hydro jetting в description (на новом сайте убрано); commercial как главная тема в H1, H2 и последнем абзаце с «grease traps, soda lines» (осталось); «North Dallas» дважды (исправлено); тире (убраны); ответы FAQ тегом H2 (исправил макет); граница правила 9: title, H1, четыре H2 и два вопроса FAQ про drain cleaning (осталось); в старой схеме второй бизнес; на фото фургона «M-38532», а лицензия M-44816.
6. Не хватает по правилу 8: вступления нет совсем; 7 H2 вместо 10 до 16, про саму линию два; списка симптомов нет; раздела «если это происходит прямо сейчас» нет (одна строка со ссылкой на emergency); FAQ 3 вместо 5 до 7; ссылки на главную с «plumber near me» нет; десяти городов в тексте нет; из связанных услуг в тексте только drain cleaning и emergency; внешней ссылки на официальный источник нет; 363 слова вместо около 2,500; ни фото с подписью, ни истории.
7. Новый сайт: старая страница с точечными правками (тире, North Dallas, hydro jetting), плюс два отзыва (Zach Z., Jose Alfredo Martinez) и блок «What is happening right now?». Word текст `FPP-Sewer-Line-Repair-Page.docx` (около 2,000 слов, 11 H2, 6 FAQ) не стоит. Раздел smoke test ждёт в `source/dictation/2026-10-02-sewer-smoke-test.md`.
8. Итоги посчитаны трижды (модуль csv, разбор строк, awk) и совпали с `page-query-coverage.csv`.

## 1. Живая страница

Ответ 200, в page-sitemap.xml, canonical на себя, index и follow. Опубликована 16 декабря 2024, правка 18 мая 2025 (схема). В индексе: да (проверка URL 1 октября 2026, последний обход 15 сентября 2026).

### 1.1. Title, description, H1, заголовки, объём

| Что | На живой странице |
|---|---|
| Title (57 знаков) | "Drain Cleaning & Sewer Repair in Frisco, Plano & McKinney" |
| Description (184 знака) | "We clear clogged drains, fix sewer lines, and handle tough backups in Frisco, Plano & McKinney. Snaking, hydro jetting, camera inspections & more. Emergency issue? Visit our 24/7 page." |
| H1 (74 знака) | "Full Drain Service, Repairs & Commercial Cleaning in Frisco & North Dallas" |
| OG title, крошки, пункт меню | "General Drain Services" |

H2 по порядку (слов в разделе): 1. "Why Professional Drain Maintenance Matters" (21); 2. "Video Camera Inspection for Sewer & Drain Lines" (22); 3. "Spot Repairs & Sewer Line Replacement" (21); 4. "Commercial Drain Cleaning for Restaurants & Bars" (23); 5. "Odors, Gurgling & Slow Drains? We Find the Cause" (22); 6. "Real Questions About Drain Cleaning [en dash] Answered" (FAQ, 136 слов); 7, 8, 9: три ответа FAQ, каждый целиком тегом H2; 10. "Book Routine Drain Cleaning or Emergency Service" (57 вместе с кнопкой и двумя ссылками); 11. "980-899-7997 469-998-8999" (телефоны панели звонка тегом H2, шаблон старого сайта). H3 нет. Вступления нет: после H1 сразу первый H2.

Объём: краул 363 слова, это весь текст (от H1 до конца FAQ 299, последний блок 64). "sewer" 3 раза, "cast iron" 1, "camera" 2 и "cameras" 1, "main line" 3, "Frisco" 1 (H1), "Plano" и "McKinney" 0 (только title и description), "North Dallas" 2, "plumber near me" 0. В H1 слова "sewer" нет. В первых ста словах оно стоит три раза, но только в двух заголовках H2 и в "sewer cameras"; первый абзац после H1 про обслуживание стоков, ответа на "sewer line repair" там нет.

### 1.2. FAQ слово в слово

Вопросы в раскрывающемся списке (`details`, `summary`, текст в `span`), не заголовки; каждый ответ тегом H2. Схема FAQPage совпадает со страницей.

| № | Вопрос | Ответ (тег H2) |
|---|---|---|
| 1 | "Why does my drain keep clogging over and over?" | "Most likely the clog wasn’t fully cleared or there’s a deeper issue [em dash] like roots, a belly in the pipe, or grease buildup. Snaking it isn’t always enough. We use a camera to check what’s really going on." |
| 2 | "Can I just use store-bought drain cleaner?" | "You can, but it’s usually a bad idea. Those chemicals can eat through your pipes, especially if they sit too long. And they rarely fix the actual problem [em dash] they just push it further down." |
| 3 | "How do I know if it’s the main line or just one drain?" | "If multiple fixtures are slow or backing up [em dash] like a tub, toilet, and kitchen sink all acting up [em dash] it’s probably your main line. That’s when you need a plumber, not a plunger." |

Повторы (схемы FAQPage всех страниц краула и новые файлы): вопрос 3 почти дословно на странице The Colony, "How do I know if it is my main line and not one drain?" (старый и новый сайт). Вопрос 1 по смыслу: toilet repair "What causes a toilet to clog over and over?", The Colony "My drains keep backing up every few months. Why?", пост про кухню "Why does my kitchen drain clog again even after someone already snaked it?", пост про душ "Why does a shower drain clog again even after I clean it?", drain cleaning "How do I keep drains from clogging again?". Вопрос 2 по смыслу: пост про унитаз "Will chemical drain cleaners help with a clogged toilet?". На будущее: вопрос Word текста "How much does a sewer camera inspection cost?" уже есть в гайде `/plumbing-guide/why-your-toilet-keeps-backing-up/` ("How much does a camera inspection cost in Plano TX?"); на Allen стоит "Can tree roots get into my sewer line?".

### 1.3. Отзывы

На живой странице отзывов нет. Новый сайт показывает два (из `site-reviews.json`; по `site-ledger.md` оба только на этой странице; на старом сайте не стояли):

- Zach Z., Yelp, 3 октября 2025, "★★★★★ · Yelp · October 2025", https://www.yelp.com/biz/fpp-plumbing-plano-2: "I had a main line clog. The availability and the price seemed reasonable for the urgent need. The plumber scoped it before and after to make sure the line was clear."
- Jose Alfredo Martinez, Google, профиль Plano, 10 декабря 2024, "★★★★★ · Local Guide Level 2 · December 2024 · Google", https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sChZDSUhNMG9nS0VJQ0FnSUN2OXRHRU1nEAE!2m1!1s0x0:0xccc66184bdaf3a93: "FPP Plumbing did an excellent job! I had a clogged and broken old drain line in the crawl space. They responded quickly, explained everything clearly, cleared the line, and replaced the pipe. Highly recommend!"

Тексты и ссылки совпадают с `all-reviews.csv` знак в знак, цифр времени в них нет.

### 1.4. Фото

Одно фото (кроме логотипа и печати BBB): `/wp-content/uploads/2025/05/drain-cleaning-snake-branded-van-frisco-652x1024.jpg`, alt "Branded FPP Plumbing van with drain snake equipment set up for sewer line cleaning in Frisco". Снимок настоящий (открыт из `site/public/`): на газоне катушка Milwaukee с толкаемым кабелем, по виду камера, а не трос, серый кейс, два открытых уличных клинаута, за ними фургон FPP. В `photos/index.csv` файла нет, город в alt ничем не подтверждён. На борту телефон Plano, на передней двери читается "M-38532" при лицензии сайта M-44816; что это за номер, в проекте не записано (то же отмечено в `docs/plano-brief-2026-10-03.md`). Для переписывания в `photos/captions-en.csv` для этой страницы уже подписаны фото и клипы Дениса: 8, 9, 10, 16, 17, 41, 122, 142, 143, 155, 156, 166, 167, 171 (smoke test), 179, 183, 184, 185, 204 (только перечень).

### 1.5. Ссылки

Со страницы в тексте две ссылки, обе в конце: `/clogged-drain-cleaning-frisco-plano/` с анкором "Drains bubbling? Toilet backs up when you use the washer? You might have a main line blockage [en dash] check Clogged Drain Cleaning for surface issues." и `/emergency-plumbing-services/` с анкором "Or go straight to 24/7 Emergency Plumbing if it’s flooding now." Остальное шаблон: 13 услуг и 10 городов в меню шапки и подвала, блог, гайды, галерея, контакты, оба офиса. Главная: только логотип с пустым анкором, "plumber near me" нет. Десяти городов в тексте нет. Slab leak, leak detection, toilet repair, water lines в тексте не названы. Внешние ссылки только шаблонные (соцсети, телефоны, почта, share.google, BBB), официального источника нет.

На страницу: меню "General Drain Services" 3 раза на каждой из 62 других страниц с содержимым (на главной 5; `/blog/author/admin/` отдаёт 301). В тексте ссылаются 16 страниц:

| Страница | Анкор |
|---|---|
| `/` | плитка услуг: картинка и H3 "General Drain Services" |
| `/emergency-plumbing-services/` | "Main line stoppages" |
| Allen (дважды), Carrollton, Celina, Lewisville, Little Elm, McKinney, Prosper, The Colony | "main line service" в строке "Backups, gurgling(, and) sewer smells: main line service"; на Allen ещё "Full details on our main line service page." |
| `/plumber-plano-tx/` | "main line service": "That is our main line service." |
| `/plumber-frisco-tx/` (живая) | "sewer line cleaning": "Main line backups and sewer line cleaning" |
| `/toilet-repair-frisco-plano/` | "Toilet gurgles when you use the sink? Could be the main line [en dash] see Drain Services" |
| `/top-emergency-plumber-calls-frisco/` | "Water coming up from the tub when washer runs sounds like a main line issue [en dash] check Drain Services" |
| `/water-leak-detection-frisco-plano/` | "sewer line repair": "The repair that follows is on our sewer line repair page." |
| `/blog/clogged-kitchen-sink-chain-snake/` | "drain services": "Our drain services cover everything from simple clogs to complex main line blockages." |

Drain cleaning, slab leak и гайды в тексте сюда не ссылаются. На новом сайте анкоры те же без тире; Frisco версии 4 и главная версии 4 дают "sewer line repair and camera inspection", главная ещё "main sewer line" в истории "One clog, the whole house".

### 1.6. Против правил CLAUDE.md

В скобках статус на новом сайте (`drain-services.md`, `launch-changes.csv` строки 196 до 204, собранная страница).

Услуги, которых FPP не делает или не заявляет:
1. Description: "Snaking, hydro jetting, camera inspections & more." (исправлено: "Snaking, camera inspections & more."; та же фраза стояла в описании WebPage старой схемы, ушла вместе с ней)
2. H1: "Full Drain Service, Repairs & Commercial Cleaning in Frisco & North Dallas": commercial бывает изредка и своей страницы не получает (осталось; то же имя у узла Service в схеме).
3. H2 "Commercial Drain Cleaning for Restaurants & Bars": "We work with cafés, bars, and commercial kitchens to clear grease traps, soda lines, floor drains, and stubborn clogs caused by kitchen debris." Grease traps и soda lines в списке услуг нет (осталось).
4. "We handle both emergency overflows and routine maintenance with flexible scheduling for residential and commercial clients across North Dallas." (commercial осталось).

Цены, гарантия, обещания времени, телефоны в тексте, слово owner: в тексте нет. Только шаблон:
5. Панель звонка "980-899-7997 469-998-8999" тегом H2 (на новом сайте нет).

Другие города:
6. H1 "... in Frisco & North Dallas" (исправлено: "... & the North Dallas Suburbs").
7. "... across North Dallas." (исправлено: "across the North Dallas suburbs").
8. Схема Organization: "surrounding North Dallas communities" (ушло со старой схемой).

Граница (правило 9: прочистку держит drain cleaning; эта страница держит линию, камеру, ремонт, запах канализации и smoke test):
9. Title начинается с "Drain Cleaning"; «drain cleaning frisco, plano, mckinney» у этой страницы в «must not target» (осталось).
10. Description: "We clear clogged drains ... and handle tough backups" (осталось).
11. H2 "Why Professional Drain Maintenance Matters": "Regular drain cleaning keeps your plumbing system running smoothly and helps avoid backups, leaks, and expensive water damage down the road." (осталось).
12. H2 "Odors, Gurgling & Slow Drains? We Find the Cause": "Strange drain smells or bubbling sounds? We check venting issues, clogged traps, and deeper blockages to keep your system safe and odor-free." Медленные стоки это drain cleaning; запах как раз тема этой страницы, но без smoke test (осталось).
13. H2 "Real Questions About Drain Cleaning [en dash] Answered" и вопросы 1, 2 (тема drain cleaning; исправлено только тире).
14. H2 "Book Routine Drain Cleaning or Emergency Service" и "emergency overflows and routine maintenance" (осталось).

FAQ тегом заголовка:
15. Три ответа тегом H2 (исправил макет `FAQList.astro`: вопрос жирным, ответ абзацем).

Тире (все исправлены):
16. "We do spot repairs where possible [em dash] saving you time, cost, and unnecessary demolition."
17. H2 "Real Questions About Drain Cleaning [en dash] Answered".
18. Ответ 1: "a deeper issue [em dash] like roots".
19. Ответ 2: "the actual problem [em dash] they just push it further down."
20. Ответ 3: "backing up [em dash] like a tub, toilet, and kitchen sink all acting up [em dash] it’s probably your main line."
21. "You might have a main line blockage [en dash] check Clogged Drain Cleaning for surface issues."
22. Схема: "From clogged sinks to broken sewer lines - we handle drain problems of all sizes" (ушло со старой схемой).

Лозунги и общие слова (23 до 28 остались, 29 ушёл):
23. "keeps your plumbing system running smoothly and helps avoid backups, leaks, and expensive water damage down the road"
24. "saving you time, cost, and unnecessary demolition"
25. "Strange drain smells or bubbling sounds?" (риторический вопрос в начале) и "safe and odor-free"
26. "That’s when you need a plumber, not a plunger."
27. "with flexible scheduling for residential and commercial clients"
28. Description: "handle tough backups ... & more"
29. Схема: "Fast response, clean work, licensed plumbers every time."

Схема и фото:
30. Второй бизнес: Plumber `@id .../drain-services/#schema`, имя равно title, адрес только Plano, "priceRange": "$$" (на новом сайте один Plumber по `#organization`, плюс Service и FAQPage).
31. Organization: "Texas Master Plumber License M-44816", формулировка снята (на новом сайте в hasCredential "Responsible Master Plumber, License M-44816").
32. Фото фургона с "M-38532" (то же фото на новом сайте).

Итого 32 места: исправлено или ушло 16 (1, 5 до 8, 15 до 22, 29 до 31), осталось 16, и это главные: commercial (2 до 4), граница с drain cleaning (9 до 14), лозунги (23 до 28), фото (32).

Чего нет по правилу 8 и разделу «Search»: вступления 2 до 3 абзацев и ответа на «sewer line repair» в первых ста словах; 10 до 16 H2 с ключами; списка симптомов; раздела «если это происходит прямо сейчас» со ссылками на гайд по главному крану и на emergency; 5 до 7 FAQ; ссылки на главную "plumber near me"; десяти "plumber in Frisco" и так далее в тексте; связанных услуг в тексте; внешней ссылки на официальный источник; блока Дениса, фото с подписью, историй; объёма около 2,500 слов.

### 1.7. Что на живой странице есть по делу

Полевого материала почти нет: ни случая, ни цифры, ни инструмента по имени. По теме:

- "We use high-definition sewer cameras to locate hidden problems like root intrusion, cracks, misaligned joints, or old corrosion in cast iron pipes." Единственное место со словами cast iron.
- "Not every drain issue means full replacement. We do spot repairs where possible"
- Ответ 1: "roots, a belly in the pipe, or grease buildup. Snaking it isn’t always enough. We use a camera to check what’s really going on."
- Ответ 3, признак главной линии: "If multiple fixtures are slow or backing up, like a tub, toilet, and kitchen sink all acting up, it’s probably your main line."
- Признаки в конце: "Drains bubbling? Toilet backs up when you use the washer? You might have a main line blockage"
- "We check venting issues" (мостик к smoke test).

### 1.8. Новый сайт против живой страницы

- Текст тот же, кроме правок `launch-changes.csv`: тире в шести местах (строки 196, 197, 199 до 202), North Dallas в H1 и в последнем блоке (198, 204), hydro jetting в description (203). Title, H2, FAQ, commercial не тронуты. Около 360 слов.
- Макет добавил два отзыва, блок "What is happening right now?" (ссылки на `/emergency-plumbing-services/#p-sewer` и гайд по главному крану), кнопки звонка обоих офисов, FAQ жирными вопросами, noindex. Блок вступления в собранной странице пустой. Схема: WebPage, BreadcrumbList, Service с именем H1 и description страницы, FAQPage.
- Одобренный текст `FPP-Sewer-Line-Repair-Page.docx` (30 сентября) на сайте не стоит. В нём title "Sewer Line Repair & Camera Inspection in Frisco & Plano, TX", H1 "Sewer Line Repair: Camera First, Then the Right Fix", около 2,000 слов, 11 H2, 6 FAQ жирным, "plumber near me" на главную, все десять "plumber in ..." в одном абзаце, ссылки на drain cleaning, toilet repair, slab leak repair, emergency. Против решений после 30 сентября: нет smoke test; нет правила про камеру до или после прочистки (`2026-10-02-frisco-additions.md`); "show the owner what the pipe looks like" в разделе commercial; "different jobs by thousands"; "typically two to three days" и абзац о поломках по городам ("roots in mature yards", "settling backfill"), этих фактов в `source/dictation/` нет; вопрос о цене камеры повторяет гайд; в title нет McKinney (что это значит, в 2.3). Абзац Дениса про чугун и салфетки для этой страницы: `source/dictation/2026-10-01-warranty-and-care.md`, Paragraph 3.

## 2. Search Console

### 2.1. Итоги

| Период | Запросов | Клики | Показы | Место по показам | Итог Google со скрытыми: клики · показы · место | Доля показов с запросом |
|---|---|---|---|---|---|---|
| 3 мес (1 июля до 28 сентября 2026) | 11 | 0 | 99 | 37.3 | 0 · 185 · 30.64 | 54% |
| 16 мес (31 мая 2025 до 28 сентября 2026) | 139 | 0 | 6,718 | 67.5 | 0 · 7,138 · 65.51 | 94% |

Все запросы 3 месяцев есть в 16 месяцах; вычитанием: за 13 месяцев до июля 6,619 показов, место 67.9, 0 кликов. В `docs/pages-plan.md` страница двадцатая, последняя в группе 3.

| Тема (правило `gsc_sewer_lib.py`) | 3 мес: запросов · показы · место | 16 мес |
|---|---|---|
| ремонт и замена sewer и main line | 0 | 32 · 1,443 · 84.9 |
| cast iron | 0 | 11 · 1,653 · 44.7 |
| sewer и main line: прочистка, cleanout, backup | 3 · 17 · 19.8 | 27 · 569 · 67.1 |
| camera inspection | 0 | 1 · 2 · 97.0 |
| **своя тема всего** | **3 · 17 · 19.8** | **71 · 3,667 · 64.0** |
| drain cleaning (хозяин страница drain cleaning) | 6 · 76 · 43.9 | 47 · 2,542 · 71.1 |
| lining, trenchless, sleeve (нет в списке услуг) | 0 | 6 · 415 · 76.4 |
| commercial | 0 | 8 · 68 · 77.0 |
| уборка после канализации (партнёр) | 0 | 1 · 6 |
| бренд и site: | 2 · 6 · 3.3 | 3 · 16 · 8.6 |
| faucet и прочее | 0 | 3 · 4 |

По городу, 16 мес (запросов · показы · место): Frisco 37 · 3,098 · 58.4; Plano 53 · 989 · 75.3; McKinney 24 · 2,328 · 75.0; The Colony 4 · 145; Little Elm 1 · 19; остальные пять городов 0; без города 14 · 98; чужой город 3 · 25; бренд 3 · 16. За 3 мес: Frisco 5 · 76 · 33.6, McKinney 1 · 1, без города 2 · 14, чужой 1 · 2, бренд 2 · 6.

По месту, 16 мес: ниже 50-го 109 запросов (4,549 показов), 20 до 50 25 (2,148), выше 20-го 5 (21: бренд, site: и единичные). 3 мес: 20 до 50 6 (66), 10 до 20 2 (15), выше 10-го 2 (бренд и site:), ниже 50-го 1 (12).

### 2.2. Топ запросов и клики

**Запросов с кликами нет ни одного** за оба периода. Топ 30 обоих периодов: `sewer-gsc-top30.md`; все запросы: `sewer-gsc-queries-*.md`. За 3 месяца все 11:

| Запрос | 3 мес | 16 мес | Тема |
|---|---|---|---|
| drain cleaning frisco | 44 · 34.9 · 0 | 715 · 39.0 · 0 | drain cleaning |
| sewer cleaning frisco | 14 · 19.6 · 0 | 167 · 59.9 · 0 | своя |
| drain line cleaning services petros | 12 · 83.4 · 0 | 12 · 83.4 · 0 | drain cleaning, petros отложено |
| frisco drain cleaning | 12 · 45.1 · 0 | 307 · 63.6 · 0 | drain cleaning |
| drain cleaning company frisco | 4 · 30.5 · 0 | 4 · 30.5 · 0 | drain cleaning |
| fpp plumbing | 4 · 2.0 · 0 | 9 · 10.6 · 0 | бренд |
| blocked drain cleaning frisco | 2 · 40.0 · 0 | 59 · 42.3 · 0 | drain cleaning |
| drain clearing service addison | 2 · 30.5 · 0 | 2 · 30.5 · 0 | чужой город |
| sewer line cleaning near me | 2 · 22.0 · 0 | 10 · 53.4 · 0 | своя |
| site:fppplumbing.com | 2 · 6.0 · 0 | 2 · 6.0 · 0 | служебный |
| main line drain cleaning mckinney | 1 · 18.0 · 0 | 2 · 16.5 · 0 | своя |

За 16 месяцев первые 12 по показам: drain cleaning frisco 715 · 39.0; drain cleaning mckinney 660 · 93.9; mckinney drain cleaning 466 · 87.9; main sewer line replacement mckinney 362 · 88.4; frisco drain cleaning 307 · 63.6; cast iron pipe replacement plano 246 · 78.3; sewer repair frisco 225 · 84.6; sewer replacement frisco 222 · 81.9; cast iron pipe replacement frisco 205 · 31.5; cast iron pipe repair mckinney 194 · 29.0; cast iron drain pipe repair frisco 189 · 34.5; sewer pipe lining frisco 188 · 85.1 (не наше).

Слова запросов в живом тексте (правило `tools/gsc_page_table.py`), 16 мес: «да» 86 запросов на 5,675 показов, «частично» 33 на 535 (нет excavation, colony, blocked, company, «near me»), отложено 20 на 508. Слова есть, но разбросаны: «cast iron» только в тексте, «replacement» только в одном H2, «McKinney» и «Plano» только в title и description.

### 2.3. Что держат заголовки

Держит: все значимые слова запроса стоят в заголовке. «Без города»: все слова, кроме названия города. Подробно: `sewer-gsc-headings.md`.

| Заголовок | Все слова, 16 мес: запросов · показы | Без города, 16 мес | Из них своя тема | Все слова, 3 мес |
|---|---|---|---|---|
| title | 30 · 2,879 | 34 · 3,034 | 19 · 655 | 3 · 70 |
| description | 3 · 7 | 3 · 7 | 1 · 1 | 0 |
| H1 | 10 · 1,049 | 23 · 2,408 | 0 | 2 · 56 |
| "General Drain Services" | 0 | 2 · 8 | 0 | 0 |
| H2 "Spot Repairs & Sewer Line Replacement" | 0 | 16 · 591 | 16 · 591 | 0 |
| H2 "Video Camera Inspection for Sewer & Drain Lines" | 0 | 1 · 1 | 1 · 1 | 0 |
| H2 commercial, "Real Questions About Drain Cleaning", "Book Routine Drain Cleaning" | до 2 · 3 | 13 до 22 · до 2,376, всё drain cleaning | 0 | 0 |
| H2 "Why Professional Drain Maintenance Matters", "Odors, Gurgling..." | 0 | 0 | 0 | 0 |
| три вопроса FAQ и три ответа тегом H2 | 0 | 0 | 0 | 0 |

- **Title**: фразой (слова подряд, если не считать "in") держит "sewer repair frisco" (225 · 84.6); все слова у "sewer cleaning mckinney" (184 · 82.5), "sewer cleaning frisco" (167 · 59.9; за 3 мес 14 · 19.6, лучшее своё место последних месяцев), "sewer repair plano", "sewer repair mckinney" и ещё 13 мелких. Города в title (и в description) единственное место с "McKinney" и "Plano". Остальное, что держит title, это чужой drain cleaning (715, 660, 466, 307).
- **H1** своей темы не держит: в нём нет "sewer".
- **H2 "Spot Repairs & Sewer Line Replacement"** единственный H2 своей темы: без города 16 запросов на 591 ("sewer repair frisco" 225, "sewer replacement frisco" 222, "sewer line repair frisco" 57, "sewer line repair mckinney" 14, "sewer line replacement frisco" 14 и мелкие).
- **Cast iron** нет ни в одном заголовке, только в тексте, а это 11 запросов на 1,653 показа и лучшие места страницы: "cast iron drain pipe repair mckinney" 23.6, "cast iron pipe repair mckinney" 29.0, "cast iron pipe replacement frisco" 31.5, "cast iron drain pipe repair frisco" 34.5, "cast iron pipe replacement mckinney" 35.3, "cast iron pipe repair frisco" 35.7. За 3 месяца по cast iron показов нет.
- **"main"** только в вопросе 3, в ответе 3 и в анкоре ссылки в конце ("main line blockage"), ни в одном заголовке; его ждут "main sewer line replacement mckinney" (362), "... plano" (144), "... frisco" (67).
- **Не потерять**: "Sewer Repair" и "Frisco, Plano & McKinney" в title; "Sewer Line Replacement" и "Repairs" в заголовке; "cast iron pipes" (лучше в заголовке); "main line"; "Camera Inspection for Sewer". McKinney: если город уйдёт из title (как в Word тексте), останется только в description, а им держатся все 24 запроса страницы с McKinney (2,328 показов за 16 мес), в том числе cast iron. Кроме того, "Drain Cleaning ... McKinney" в title даёт этой странице показы по "drain cleaning mckinney" и "mckinney drain cleaning" (1,126 за 16 мес, места 88 до 94, за 3 мес 0); кроме неё по ним показывается только страница McKinney (183 · 65.8 и 6 · 84.0 за 16 мес), страница drain cleaning не показывается.

Слов запросов нет на странице нигде: excavation (156), colony (145), blocked (59); отложенные lining (269), trenchless (79), sleeve (67), petros (12).

### 2.4. Фраза целиком (топ 20 обоих периодов, кликов нет)

28 запросов, таблица `sewer-gsc-phrases.md`. Точно стоит только "fpp plumbing" (alt фото "Branded FPP Plumbing van"); из всех 139 запросов ещё "drain cleaning" (title, H2, текст; 2 · 83.0). Мягко (без in и tx, слова подряд) стоит "sewer repair frisco" в title. У остальных 26 фразы нет нигде: ни "drain cleaning frisco", ни "sewer cleaning frisco", ни "cast iron pipe repair/replacement" с городом, ни "main sewer line replacement", ни "sewer line cleaning near me" (на странице нет "near me").

### 2.5. Другие страницы на запросах этой услуги, и наоборот

Тема sewer, cast iron и камеры по сайту: 3 мес 124 запроса и 5,062 показа, у этой страницы 3 и 17; клики 2, оба у Plano ("sewer drain cleaning near me", "sewer and drain repair near me"). 16 мес 345 и 20,048, у этой страницы 71 и 3,667; клики 3 (ещё главная, "sewer line repair" 191 · 2.4 · 1).

| Страница | 3 мес: запросов · показы · место | 16 мес | Выше этой, 16 мес: запросов · показы | Без своего города, 3 мес |
|---|---|---|---|---|
| `/plumber-plano-tx/` | 81 · 3,411 · 3.9 | 113 · 4,239 · 18.8 | 21 · 355 | 50 · 3,241 |
| `/plumber-frisco-tx/` | 41 · 1,521 · 4.0 | 65 · 2,908 · 13.4 | 8 · 170 | 32 · 1,448 |
| `/` | 5 · 11 · 9.3 | 207 · 5,635 · 20.3 | 39 · 3,143 | |
| `/clogged-drain-cleaning-frisco-plano/` | 1 · 1 · 23.0 | 30 · 968 · 59.9 | 14 · 544 | |
| `/water-lines/` | 6 · 10 · 40.5 | 16 · 864 · 60.4 | 8 · 674 | |
| Lewisville, Carrollton, McKinney | мелко | 8 · 427; 5 · 290; 4 · 176 | 0; 0; 3 · 34 | |
| `/drain-services/` | 3 · 17 · 19.8 | 71 · 3,667 · 64.0 | | |

По правилу проекта (место 3 и выше без города страницы) карточкой за 3 мес считаются у Plano 40 запросов на 850 показов (место 1.2), у Frisco 14 на 970 (1.3). Главные строки (полностью в `sewer-gsc-other-pages-*.md`):

| Запрос | Другая страница | Её числа | Эта страница |
|---|---|---|---|
| sewer line replacement the colony tx (3 мес) | Plano | 1,816 · 5.2 · 0 | нет |
| sewer line replacement (3 мес) | Plano | 541 · 3.7 · 0 | нет |
| sewer repair (3 мес) | Frisco | 361 · 1.1 · 0 | нет |
| sewer cleaning (3 мес) | Frisco | 308 · 1.5 · 0 | нет |
| sewer line camera inspection (3 мес) | Frisco | 47 · 1.0 · 0 | нет |
| sewer line cleaning near me (3 мес) | Plano | 116 · 1.0 · 0 | 2 · 22.0 · 0 |
| main sewer line replacement plano (16 мес) | `/` | 362 · 12.3 · 0 | 144 · 90.5 · 0 |
| cast iron plumbing frisco (16 мес) | `/` | 278 · 15.7 · 0 | 39 · 49.7 · 0 |
| cast iron drain pipe repair frisco (16 мес) | `/` | 196 · 13.3 · 0 | 189 · 34.5 · 0 |
| main sewer line replacement frisco (16 мес) | `/water-lines/` | 367 · 44.6 · 0 | 67 · 46.1 · 0 |
| sewer cleaning frisco (16 мес) | drain cleaning | 138 · 54.0 · 0 | 167 · 59.9 · 0 |
| sewer line repair the colony (16 мес) | The Colony | 99 · 36.6 · 0 | 9 · 93.6 · 0 |

`/water-lines/` по карте держит линию от счётчика до дома, а показывается по "main sewer line": слова "main line" путают две темы.

Наоборот (`sewer-gsc-reverse.md`): drain cleaning этой страницы, 47 запросов на 2,542 показа за 16 мес и 6 на 76 за 3 мес. Хозяин показывается по 25 из 47 (9,088 показов по тем же запросам) и выше в 18; за 3 мес по 3 из 6 и выше во всех (884 показа). "drain cleaning frisco": здесь 715 · 39.0, у хозяина 2,244 · 43.4 за 16 мес (эта была выше); за 3 мес 44 · 34.9 против 422 · 22.5. "drain cleaning plano" 37 · 95.9 против 1,703 · 67.4. "drain cleaning mckinney" 660 · 93.9 и "mckinney drain cleaning" 466 · 87.9: хозяин не показывается. Бренд "fpp plumbing": здесь 9 · 10.6, у главной 1,863 · 1.5 · 212. "mckinney faucet repair" (хозяин faucet): 1 показ.

### 2.6. Тема страницы с каждым из десяти городов

Запросы сайта про sewer, main line, cast iron и камеру с названием города (по страницам: `sewer-gsc-cities.md`).

| Город | 16 мес на сайте | Эта страница, 16 мес | Больше всех, 16 мес | 3 мес на сайте | Кто за 3 мес |
|---|---|---|---|---|---|
| Frisco | 26 · 6,227 | 16 · 1,617 · 61.9 | `/` 2,480 · 29.3 | 10 · 94 | Frisco 73 · 1.7; эта 14 · 19.6 |
| Plano | 108 · 4,230 | 37 · 813 · 75.3 | `/` 1,879 · 18.8 | 31 · 170 | Plano 170 · 2.2 |
| McKinney | 15 · 1,392 | 11 · 1,145 · 58.8 | эта | 3 · 16 | Frisco 15 · 38.3; эта 1 · 18.0 |
| The Colony | 7 · 2,219 | 2 · 24 · 83.0 | Plano 1,818 · 5.2 | 4 · 1,986 | Plano 1,818 · 5.2 |
| Lewisville | 9 · 462 | нет | Lewisville 427 · 70.6 | 1 · 20 | Plano 20 · 1.0 |
| Carrollton | 5 · 290 | нет | Carrollton 290 · 61.6 | 0 | |
| Prosper | 2 · 116 | нет | Prosper 75 · 26.0; Frisco 41 · 1.0 | 1 · 26 | Frisco 25 · 1.0 |
| Celina | 3 · 79 | нет | Celina 79 · 16.4 | 1 · 6 | Celina |
| Allen | 5 · 28 | нет | Allen 26 · 58.7 | 1 · 2 | Plano |
| Little Elm | 3 · 6 | нет | Little Elm 6 · 31.8 | 2 · 3 | Little Elm |

(Город в ячейке означает страницу этого города.) McKinney единственный город, где эта страница берёт большую часть своей темы. По Frisco и Plano за 16 мес больше всех у главной, за 3 мес у страниц офисов. По семи городам эта страница не показывается. Чужой drain cleaning с городом на этой странице, 16 мес: Frisco 16 · 1,126, McKinney 11 · 1,180, The Colony 2 · 121, Plano 6 · 63, Little Elm 1 · 19.

### 2.7. Слова, которые на страницу не идут

За 16 мес (за 3 мес из этого только addison, petros, бренд и site:):

- способ, которого нет в списке услуг: lining 2 запроса · 269 показов ("sewer pipe lining frisco", "pipe lining frisco"), trenchless 1 · 79 ("trenchless pipe repair frisco"), sleeve 3 · 67 ("plano sewer pipe repair sleeve");
- commercial (бывает изредка, своей страницы нет): 8 · 68 ("commercial drain cleaning plano");
- уборка после канализации (это партнёр по восстановлению): "sewage cleanup frisco" 1 · 6;
- чужие города и места: Dallas 1 · 22 ("commercial drain cleaning dallas"), Addison 1 · 2, North Dallas 1 · 1;
- непонятные и чужие названия: petros 1 · 12 ("drain line cleaning services petros", в проекте не объяснено), gps 1 · 1 ("gps plumbing frisco", похоже на другую компанию);
- бренд и служебные: "fpp plumbing", "site:fppplumbing.com", 3 · 16.

Оценочных слов, опечаток и голосовых слов в запросах страницы нет. По сайту в этой теме есть ещё "hydrojet sewer plumber mckinney tx" (McKinney, 243 · 60.3) и "no dig sewer line replacement plano" (главная, 372 · 7.3): hydro jetting и бестраншейную замену как услугу не называем.

### Как считали

- Скрипты `gsc_sewer_lib.py` и `gsc_sewer_live.py` в scratchpad `services/sewer-line/`, из копий `docs/briefs/_shared/gsc_plano_lib.py` и `gsc_plano_live.py` (оригиналы не тронуты, `tools/gsc_page_table.py` не запускался). Правило покрытия как в проектном инструменте, текст с живой страницы из краула; город из десяти считается словом запроса; тема по словам запроса, первое совпадение; адреса с 301 считаются своей целью.
- Итоги страницы тремя способами (модуль csv, разбор строк без него с остановкой при расхождении, awk): 3 мес 11 запросов, 0 кликов, 99 показов, место 37.34; 16 мес 139, 0, 6,718, 67.48. Те же числа в `page-query-coverage.csv`. Руками сверены "drain cleaning frisco" 715 · 39.05, "cast iron pipe replacement frisco" 205 · 31.46, "sewer cleaning frisco" за 3 мес 14 · 19.64. Сумма по темам (71 · 3,667 своя, 47 · 2,542 drain cleaning, остальное 21 · 509) сходится с 139 · 6,718.
