# Water line repair: живая страница и Search Console (3 октября 2026)

Справка перед переписыванием https://fppplumbing.com/water-lines/ . Текст страницы не пишется, в проекте ничего не менялось. Источники: краул от 30 сентября 2026 (`source/crawl/`), новый сайт `site/src/content/pages/water-lines.md` и `site/dist/water-lines/index.html` (только чтение), `site/src/data/launch-changes.csv`, `reviews/`, `photos/captions-en.csv`, `source/gsc/`, `seo/keyword-map.md`, `docs/pages-plan.md`. Одобренного текста этой страницы в `source/` нет. Расчёты: копии `docs/briefs/_shared/gsc_plano_lib.py` и `gsc_plano_live.py`, переделанные под страницу (`wl_lib.py`, `wl_gsc.py`, `wl_extra.py` в scratchpad сессии). Длинные таблицы: `docs/briefs/services/water-lines/` (список в конце).

## Коротко

- Кормят страницу два запроса: "water line repair" (16 мес: 20,416 показов, место 16.4; 3 мес: 2,253, место 14.1) и "main water line repair" (4,840, место 37.1). У страницы 8 кликов за 16 мес и 3 за 3 мес (данные Google), все со скрытых запросов; у запросов с известным текстом кликов 0.
- Показы падают: последние 3 месяца в среднем 2,766 в месяц, 13 месяцев до них 5,349 в месяц (мой расчёт из `Pages.csv`). Страница правилась в WordPress 30 августа 2026, прежний текст по файлам не виден.
- Нельзя потерять: title "Main Water Line Repair & Replacement | Plano & Frisco, TX | FPP" (46 запросов, 41,042 показа за 16 мес; 21 запрос, почти все с Frisco или Plano, не держит больше ни один заголовок); H1 "Main Water Line Repair, Found Before It Gets Dug Up" (держит "water line repair" и "main water line repair" целиком); H2 "Water Line Repair vs Full Replacement" ("water line repair", "water line replacement"). Остальные H2 и семь из девяти вопросов FAQ не держат почти ничего.
- Против правил, и на живой странице, и на новом сайте: цена "three to six thousand dollars"; reroute как вариант (три места, на старом сайте ещё и в схеме); 9 вопросов FAQ при норме 5 до 7, тегом H3 на живой странице; два вопроса FAQ дословно стоят на странице Little Elm.
- Не хватает по правилу 8: 7 смысловых H2 вместо 10 до 16; нет списка «симптом и ссылка»; нет своего раздела «если это происходит сейчас» (кусками в двух разделах, на новом сайте частично его заменяет боковой блок шаблона); 2,133 слова своего текста при ориентире около 2,500; из десяти городов в тексте связаны пять (нет Frisco, Allen, Little Elm, The Colony, Lewisville); ни одной внешней ссылки на официальный источник.
- Ссылка на главную с анкором "plumber near me" стоит по правилу 6. Смежные услуги: связаны leak detection, slab leak, PRV, emergency и гайд по крану; не связаны hose bib, пост про тротуар в Plano (19 кликов за 16 мес), гайды про утечку во дворе и про счёт за воду.
- Запросы услуги с городом в последние 3 месяца чаще берут страницы городов: "water line repair plano" у Plano 319 показов, место 14.1, у /water-lines/ 10; "frisco tx water line repair" у Frisco 195, место 16.2, у /water-lines/ 221, место 30.9.
- Чужие показы: Dallas и Rockwall 5,499 за 16 мес, gas line 989, trenchless 1,352 ("trenchless water line replacement frisco": 951 показ, место 4.2), а ещё faucet, slab leak, leak detection.
- На новом сайте при переносе пропал пробел: "plumber in Prosperor a plumber in Celina".

## 1. Живая страница

### 1.1. Title, описание, H1, заголовки, объём

Ответ 200, в page-sitemap.xml, canonical на себя, index и follow. Опубликована 18 декабря 2024, правка 30 августа 2026 (схема страницы).

| Что | На живой странице |
|---|---|
| Title (63 знака) | "Main Water Line Repair & Replacement \| Plano & Frisco, TX \| FPP" |
| Meta description (156 знаков) | "Soggy patch that never dries? One strip of grass greener than the rest? Pressure gone across the house? Licensed plumbers locate the line before anyone digs" |
| H1 | "Main Water Line Repair, Found Before It Gets Dug Up" |
| OG title | "Water line repair and replacement" (не как title) |

H2 по порядку (в скобках слов под заголовком, мой счёт): 1. "Signs of a Main Water Line Leak" (207); 2. "Water Line Responsibility: Yours or the City's" (106); 3. "Locating an Underground Water Line Leak" (148); 4. "Water Line Leak at the Foundation: Copper Set in Concrete" (444); 5. "Water Line Repair vs Full Replacement" (189); 6. "Tree Roots and the Water Line" (198); 7. "What Else It Might Be" (158); 8. "Water Line FAQ"; 9. "980-899-7997 469-998-8999" (не раздел: нижняя панель звонка шаблона старого сайта свёрстана тегом H2). H3: девять, все это вопросы FAQ.

Объём: краул считает 2,135 слов. Свой текст от H1 до конца FAQ 2,133 слова: вступление 118, семь разделов 1,450, FAQ 505 (ответы 420). Отзывов и блока офиса нет.

Слова в тексте (H1, H2 и FAQ включены, title нет): "water line" 16 раз; "water line repair" 3, все три в заголовках, в обычном тексте 0; "main water line" 3; "Frisco" 0 (только title и alt фото); "Plano", "McKinney", "Carrollton", "Prosper", "Celina" по 1 (анкоры); "Allen", "Little Elm", "The Colony", "Lewisville" 0; "plumber near me" 1; "pipe break", "burst", "broken" 0.

### 1.2. Девять вопросов FAQ

Все девять тегом H3 в раскрывающемся списке Elementor (`e-n-accordion-item-title-text`). Схема FAQPage совпадает со страницей слово в слово по всем девяти (проверено).

1. "How do I know if my main water line is leaking?": дословно вопрос FAQ (H3) на /plumber-little-elm-tx/ и в тексте поста /blog/main-water-line-leak-under-sidewalk-plano-tx/ (на новом сайте там вопрос FAQ).
2. "Am I responsible for the water line, or is the city?": дословно вопрос FAQ (H3) на /plumber-little-elm-tx/; ответ там написан другими словами, общая с этой страницей мысль и фраза "We verify which side the problem is on".
3. "Do you have to dig up my whole yard?"
4. "Should I repair the section or replace the line?"
5. "Can tree roots damage a water line?"
6. "Why did my water pressure drop everywhere at once?" (близкий вопрос на /plumber-little-elm-tx/ и /plumber-carrollton-tx/: "My whole house lost water pressure. Is that the PRV?")
7. "The city sent me a notice about high water usage. What now?"
8. "Why did my line fail right at the foundation?"
9. "How long does a water line repair take?"

Вопросы 3 до 9 больше нигде на сайте дословно не стоят. Новый сайт: те же девять, жирным текстом в `<summary><strong>` (шаблон `FAQList.astro`), не заголовком.

### 1.3. Отзывы

На живой странице отзывов нет (блока нет, слово review только в меню и в знаке BBB). В `reviews/all-reviews.csv` (407 строк) ни у одного отзыва нет `on_old_site` = `/water-lines/`.

На новом сайте за страницей два отзыва (`reviews/site-reviews.json`, `reviews/site-ledger.md`), оба стоят на собранной странице, оба совпадают с архивом знак в знак (текст и ссылка), город в подписи не стоит (в текстах города нет):
- william mckinney, Google, профиль Plano, 13 сентября 2026, Level 6, про main water line ("they were there to repair the leak on the main water line at 9:10 AM on Sunday morning!"). Ссылка: https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sCi9DQUlRQUNvZENodHljRjlvT25nd01taHNhVFJ6UlRCM1FUSkxUR1pIVjB3eFRuYxAB!2m1!1s0x0:0xccc66184bdaf3a93
- Kathryn Kim, Google, профиль Plano, 4 сентября 2025, Level 3, про main water line leak во дворе после рабочего дня ("If you need a reliable emergency plumber, FPP Plumbing is a great company."). Ссылка: https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sCi9DQUlRQUNvZENodHljRjlvT2taWlkwMXpNVlU0ZDFwb1ZHOVhSeTFhZUdWMlIxRRAB!2m1!1s0x0:0xccc66184bdaf3a93

Время в отзывах ("9:10 AM", "the same night") это слова клиентов, их не трогают; сбор Kathryn Kim называет честным, это не жалоба. У неё в архиве есть второй отзыв (профиль Frisco, 13 февраля 2026, тоже main water line leak); по правилу «один автор на одной странице» он больше нигде стоять не может. Отзыв John Wilson (Google, Plano, 29 мая 2025, "a difficult repair on my service line in the front yard") на новом сайте не стоит нигде (на старом был на /plumber-lewisville-tx/).

### 1.4. Фото

| Файл | Alt | Что это |
|---|---|---|
| `/wp-content/uploads/2024/12/fpp-logo-1-1024x563.png` (2 раза) | "FPP Plumbing Logo" | логотип |
| `/wp-content/uploads/2025/05/prv-main-shutoff-valve-copper-water-line-repair-768x1024.jpg` (полный 960 на 1280) | "Underground copper water line with PRV valve and main shut-off valve during emergency repair in Frisco" | единственное фото в тексте, оно же OG картинка |
| `https://seal-dallas.bbb.org/seals/blue-seal-200-65-bbb-91348602.png` | "FPP Plumbing, LLC BBB Business Review" | знак BBB |

Фото открыто (копия в `site/public/wp-content/uploads/2025/05/`): настоящий снимок с работы, яма с мульчей, медная линия с фитингами и два крана с зелёными ручками. PRV по снимку не опознать; город Frisco только из alt. В `photos/captions-en.csv` файла нет. Его копия 150 на 150 стоит на старой главной.

В `photos/captions-en.csv` за /water-lines/ уже записаны снимки Дениса: 5, 24, 54 (клип), 55 (помечено главным фото страницы), 56, 65, 158 ("Pulling a new PEX water line under the sidewalk, McKinney"), 159 (клип), 168, 186 и 187 (клип).

### 1.5. Ссылки

Со страницы в тексте 11 внутренних, внешних нет:

| Раздел | Анкор | Куда |
|---|---|---|
| вступление, последний абзац | "plumber near me" | / (правило 6 выполнено) |
| Signs of a Main Water Line Leak | "shut-off guide" | /plumbing-guide/how-to-shut-off-main-water-valve-texas/ |
| Locating an Underground Water Line Leak | "leak detection" | /water-leak-detection-frisco-plano/ |
| Water Line Leak at the Foundation | "slab leak repair" | /slab-leak-repair-frisco-plano-mckinney/ |
| Tree Roots and the Water Line (два абзаца) | "plumber in McKinney", "plumber in Plano", "plumber in Carrollton", "plumber in Prosper", "plumber in Celina" | пять страниц городов |
| What Else It Might Be | "PRV"; "emergency plumbing" | /prv-replacement-frisco-plano/; /emergency-plumbing-services/ |

Нет ссылок в тексте на Frisco, Allen, Little Elm, The Colony, Lewisville (все десять есть только в меню и подвале). Смежные страницы без ссылки: /hose-bib-repair-frisco-plano/, /blog/main-water-line-leak-under-sidewalk-plano-tx/, /plumbing-guide/water-leak-yard-tips-2026/, /plumbing-guide/why-is-my-water-bill-so-high-frisco-tx/, /plumbing-guide/water-pressure-dropping-tips-2026/, /plumbing-guide/automatic-water-shut-off-valve-install-north-texas/.

На страницу: меню на всех 62 других живых страницах (64-й файл краула, /blog/author/admin/, это редирект 301), по 3 раза (на главной 6), анкор "Water line repair and replacement". В тексте 16 страниц: главная (плитка услуги); Plano ("main water line repair": "Our main water line repair page covers how we locate it and what each option costs.") и McKinney (тот же анкор, почти та же фраза); Little Elm ("water line replacement", "water line repair"); Carrollton, Celina, Lewisville, Prosper, The Colony, McKinney ("water line repair" в списке «симптом: услуга»); emergency ("Water lines broken"); slab leak и leak detection ("water line repair", случай с медью в бетоне); гайды slab leak Plano, PRV, automatic shut-off ("water line", "main water line"); пост про тротуар ("water line"). Frisco и Allen в тексте не ссылаются. На новом сайте те же, плюс Frisco версии 4 ("Water line repair is the page for that leak.") и главная v4 ("water line repair").

### 1.6. Что идёт против CLAUDE.md, дословно

Reroute как вариант (правило: «never mention reroute as an option»):
- "That section came out and got replaced on a different route." (Tree Roots). Новый сайт: стоит, проверка правок это предложение не ловит.
- "Rerouting costs more once and ends it." (Tree Roots). Новый сайт: стоит (`launch-changes.csv` строка 619, "flag not changed", «reroute mention (not above the slab)»).
- FAQ: "When a tree is the cause, rerouting usually makes more sense than putting the same pipe back beside the same tree." Новый сайт: стоит (строка 620, так же), и раз FAQ повторяется в схеме слово в слово, эта фраза стоит и в схеме FAQPage собранной страницы.
- Схема старой страницы, Service: "Water service line leak location, repair, replacement and rerouting". Новый сайт: нет (Service строится в `site/src/lib/schema.ts` без serviceType).

Протяжка без траншеи: "Where the route allows it, a new line can be pulled without trenching the entire run, which keeps the yard mostly intact." и в FAQ "where the route allows it a new line can be pulled without trenching the full run." В списке «не делаем» стоит «pulling new lines through existing sleeves», здесь протяжка во дворе, не через гильзу, и есть подпись Дениса к фото 158 "Pulling a new PEX water line under the sidewalk, McKinney". Прямым нарушением по файлам не выходит. Новый сайт: стоит.

Цены (кроме $49 никаких цен и вилок): "Work of that kind runs roughly three to six thousand dollars, and the spread depends on how deep the line sits, how far the tunnel has to run, and what is sitting on top of it." Новый сайт: стоит (проверка правок ищет знак $, сумму прописью не видит). Не наша цена, но сумма: "Two companies quoting the same leak can be thousands apart purely because one of them located it and the other one is pricing in the risk of not knowing." и "The bill climbs first, usually twenty or thirty dollars". Новый сайт: стоят. Слово "estimate" (раздел про замену и ответ FAQ про двор: "you see that in the estimate") бесплатную оценку не обещает; по правилам цена называется фиксированная, до начала работ.

Гарантия: сроков нет ("the next call comes anywhere from six months to two years later" про новую течь, не гарантия).

Время приезда: обещаний нет. Цифры времени не про приезд: "A gauge reading tells us which one in a few minutes." и "Most spot repairs finish in a day." Про сбор: "you hear the after hours fee before the truck moves" соответствует правилу о цене.

Другие города: в тексте нет. В общем узле Organization старого сайта: "surrounding North Dallas communities" и "Texas Master Plumber License M-44816"; новый сайт строит свою схему.

Границы (правило 9):
- "Locating an Underground Water Line Leak" описывает метод поиска, а метод принадлежит /water-leak-detection-frisco-plano/; раздел короткий (148 слов), страница сама отсылает туда ссылкой.
- "Water Line Leak at the Foundation" (444 слова): линия, залитая в фундамент, тема этой страницы, но дальше туннель "roughly five to six feet under the foundation", пайка и новая линия под фундаментом, а ремонт под фундаментом принадлежит /slab-leak-repair-frisco-plano-mckinney/. Страница называет это ("turned into what is effectively a slab leak repair") и ставит ссылку. Похожий случай стоит первым в "From the Job" на главной ("Water coming out of the foundation", клип 165, Little Elm, 27 августа 2026), диктовка `source/dictation/2026-10-02-slab-leak-water-from-foundation.md` отложена для страницы slab leak. Факты расходятся: здесь "we found the copper below the slab in good condition", на главной "The pipe past it was in bad shape too". Один это случай или два, по файлам не видно.
- Вопрос про давление и абзац про PRV касаются /prv-replacement-frisco-plano/: одна фраза со ссылкой, это по правилу.

Телефоны в тексте: нет (H2 с номерами это панель шаблона, на новом сайте её нет). Owner: нет, в историях "the homeowner". FAQ тегом H3: да, все девять (новый сайт исправил шаблоном). Тире: нет ни на живой странице, ни в файле нового сайта.

Лозунги и пустые слова: H1 "..., Found Before It Gets Dug Up" (правило 4: H1 с ключами, не броский); описание из трёх риторических вопросов подряд (голосовой файл запрещает риторические вопросы в начале); "that link is the front door"; "knowing it in advance is worth more than any tool in your garage" (целиком та же фраза на /plumber-lewisville-tx/, на /plumber-plano-tx/ её конец "is worth more than any tool in your garage"); "This one saves people real money". Слов из запретного списка `voice/denys-voice.md` нет.

Повторы с другими страницами (7 слов подряд): /plumber-mckinney-tx/ 18 отрезков (в том числе "yard had grown into the service line and damaged the copper outright"), /plumber-little-elm-tx/ 15 (вопросы и ответы FAQ), "a plumber in Prosper or a plumber in Celina" ещё на трёх страницах услуг, отдельные фразы на Plano, Carrollton, slab leak, leak detection.

Ошибка переноса на новый сайт: в `site/src/content/pages/water-lines.md` "[plumber in Prosper](/plumber-prosper-tx/)or a [plumber in Celina]"; на собранной странице читается "plumber in Prosperor a plumber in Celina". На живой странице пробел есть.

### 1.7. Полевая суть, которую стоит сохранить

Стоит на живой странице; в `source/dictation/` этих цифр и случаев нет.

- "with every tap in the house closed, a leak indicator that keeps moving means water is leaving the system somewhere."
- "it drops everywhere at once, not at one fixture. That is what separates a line problem from a cartridge or an aerator."
- "Everything from the meter to your house is yours. Everything from the meter out to the street is the city’s"
- "isolate the yard from the house so we know the water is going into the ground and not into a wall, then trace the run with pressure readings and acoustic equipment"
- "Done properly it passes through a sleeve, so the copper never touches concrete and has room to move. Done in a hurry, the pipe is simply set into the pour. Concrete is alkaline and it works on copper slowly."
- Цифры случая: "a meter reading a steady 0.2 gallons per minute with everything in the house shut off"; "fifty PSI of air and walked it with an acoustic locator"; "about three feet from the secondary shut-off valve sitting in its box in the ground"; "a three quarter inch branch and a half inch branch, and both ran directly into the concrete with no sleeve"; "ran the replacement line underneath the foundation instead of through it."
- Замена вместо ремонта: "old galvanized, aging copper that is failing from age rather than from an event, or a line that has already been repaired once and is now leaking somewhere else."
- McKinney: "a large tree in the front yard had grown into the service line and damaged the copper outright" (без слов о reroute).
- "If pressure is the only symptom and nothing anywhere is wet, check the PRV before assuming the worst" и "if the soft ground sits right next to a sprinkler head, start with the irrigation."

Материал Дениса по теме уже лежит: `source/dictation/2026-10-02-frisco-reserve-for-service-pages.md` (раздел "For the water lines page": коробка клапанов в грязи, коррозия, pinholes) и `2026-10-02-frisco-additions.md` (течи у PRV и secondary shut-off valve; Plano: тройник на уличный кран, 186 и 187).

### 1.8. Новый сайт против живой страницы

- Title, описание, H1, весь текст и девять вопросов FAQ перенесены без изменений. Точечных правок, которые что-то поменяли, нет: в `launch-changes.csv` две строки, обе "flag not changed" (reroute); в `tools/build_launch_content.py` правил с путём /water-lines/ нет.
- Шаблон добавил: FAQ жирным текстом, два отзыва, боковой блок "What is happening right now?" (ссылки на emergency и гайд по крану, кнопки звонка обоих офисов), noindex. Схема: без serviceType с rerouting, areaServed десять городов и Park Cities.
- Ошибка переноса: пробел после ссылки "plumber in Prosper".
- Одобренного текста в `source/` нет. `docs/pages-plan.md`: группа 3, номер 4, "Water lines | 8,299 | 26.9 | 3 | Старый текст". Карта ключей (`seo/keyword-map.md`, второстепенные ключи в `seo/keyword-map.csv`): "carry as is", главный ключ "water line repair", второстепенные "main water line repair; water line repair frisco; water line repair plano", не трогать "slab leak repair; leak detection; gas line repair".

## 2. Search Console

### 2.1. Итоги

| Период | Запросов с известным текстом | Клики | Показы | Среднее место (взвешено по показам) | Google, вся страница: клики | показы | место | Доля показов с известным запросом |
|---|---|---|---|---|---|---|---|---|
| 3 месяца (1 июля до 28 сентября 2026) | 138 | 0 | 7,349 | 27.6 | 3 | 8,299 | 26.9 | 89% |
| 16 месяцев (31 мая 2025 до 28 сентября 2026) | 555 | 0 | 74,128 | 35.4 | 8 | 77,831 | 34.9 | 95% |

Вторая проверка: файлы прочитаны второй раз без модуля csv, число запросов, клики, показы и место совпали между собой и с `page-query-coverage.csv`. Все клики (3 и 8) со скрытых запросов; скрытых показов 950 за 3 мес и 3,703 за 16 мес. 13 месяцев до последних трёх: 69,532 показа, 5 кликов, место 35.9 (мой расчёт из `Pages.csv`).

По группам (суммы групп сверены с итогом):

| Группа запросов | 3 мес: запросов | клики | показы | место | 16 мес: запросов | клики | показы | место |
|---|---|---|---|---|---|---|---|---|
| город из десяти | 37 | 0 | 1,399 | 29.6 | 209 | 0 | 38,321 | 41.9 |
| Park Cities | 0 | 0 | 0 | 0.0 | 3 | 0 | 6 | 52.3 |
| без города | 73 | 0 | 5,560 | 25.8 | 228 | 0 | 29,234 | 22.0 |
| другое место | 26 | 0 | 367 | 48.9 | 112 | 0 | 6,082 | 62.1 |
| бренд | 2 | 0 | 23 | 2.1 | 3 | 0 | 485 | 2.3 |

По месту: за 16 мес на местах 1 до 10 стоят 85 запросов с 1,768 показами, на местах 10 до 20: 61 запрос и 30,343 показа, ниже 20: 409 запросов и 42,017 показов. За 3 мес: места 1 до 10: 18 запросов, 45 показов; 10 до 20: 36 и 3,024; ниже 20: 84 и 4,280.

По теме запроса за 16 мес (за 3 мес в скобках), показы: водяная линия 54,455 (6,603), место 31.2; pipe break, burst pipe, leak repair 9,013 (615), место 40.2; trenchless, lining, repipe 1,841 (12); leak detection 1,821 (10); slab leak 1,817 (0); faucet 1,742 (0); gas line 989 (35); sewer 859 (7); остальное по мелочи. Полностью: `gsc-phrases-and-reverse.md`.

### 2.2. Первые 30 запросов по показам и запросы с кликами

Запросов с кликом нет ни за 3, ни за 16 месяцев. Все запросы: `gsc-all-queries-3m.md` (138) и `gsc-all-queries-16m.md` (555), там же слова в тексте и место точной фразы. Группы (город, чужое место) видны в полных таблицах. Первые 30 дают 6,916 из 7,349 показов (94.1%) за 3 мес и 57,957 из 74,128 (78.2%) за 16 мес.

3 месяца:

| № | Запрос | Показы | Место | 16 мес: показы · место |
|---|---|---|---|---|
| 1 | main water line repair | 2,491 | 35.1 | 4,840 · 37.1 |
| 2 | water line repair | 2,253 | 14.1 | 20,416 · 16.4 |
| 3 | frisco tx water line repair | 221 | 30.9 | 3,450 · 18.1 |
| 4 | water line repair frisco tx | 220 | 26.8 | 2,809 · 18.9 |
| 5 | water line plumber | 216 | 48.7 | 216 · 48.7 |
| 6 | frisco water line repair | 157 | 19.2 | 2,597 · 20.1 |
| 7 | water line repair frisco | 143 | 18.8 | 2,679 · 20.0 |
| 8 | water leak repair | 115 | 22.2 | 253 · 19.8 |
| 9 | plano tx water line repair | 106 | 54.6 | 1,088 · 69.8 |
| 10 | frisco pipe break repair | 100 | 15.7 | 1,224 · 25.2 |
| 11 | frisco tx pipe break repair | 95 | 27.0 | 1,374 · 23.5 |
| 12 | water line leak repair | 85 | 17.5 | 288 · 21.9 |
| 13 | water line replacement | 75 | 18.1 | 344 · 21.1 |
| 14 | plano water line repair | 63 | 30.8 | 699 · 58.2 |
| 15 | water line repair rockwall | 46 | 44.9 | 229 · 64.0 |
| 16 | rockwall tx water line repair | 45 | 66.9 | 246 · 76.5 |
| 17 | pipe break repair | 44 | 32.6 | 81 · 24.9 |
| 18 | dallas tx water line repair | 43 | 44.4 | 1,035 · 59.4 |
| 19 | rockwall water line repair | 42 | 54.1 | 398 · 71.9 |
| 20 | water leak repair near me | 41 | 19.5 | 126 · 18.7 |
| 21 | water line repair little elm | 39 | 43.1 | 823 · 40.5 |
| 22 | little elm water line repair | 38 | 59.5 | 898 · 45.8 |
| 23 | water line repair dallas tx | 38 | 35.0 | 723 · 50.5 |
| 24 | water line repair dallas | 35 | 30.7 | 1,380 · 54.6 |
| 25 | pipe breaks frisco | 33 | 18.9 | 1,363 · 37.0 |
| 26 | pipe breaks frisco tx | 29 | 18.8 | 1,612 · 52.0 |
| 27 | pipe leak repair near me | 27 | 14.6 | 51 · 12.2 |
| 28 | water line repair rockwall tx | 26 | 45.1 | 131 · 62.5 |
| 29 | coppell water line repair | 25 | 63.2 | 69 · 66.3 |
| 30 | plumbing leak repair | 25 | 32.1 | 25 · 32.1 |

16 месяцев:

| № | Запрос | Показы | Место | 3 мес: показы · место |
|---|---|---|---|---|
| 1 | water line repair | 20,416 | 16.4 | 2,253 · 14.1 |
| 2 | main water line repair | 4,840 | 37.1 | 2,491 · 35.1 |
| 3 | frisco tx water line repair | 3,450 | 18.1 | 221 · 30.9 |
| 4 | water line repair frisco tx | 2,809 | 18.9 | 220 · 26.8 |
| 5 | water line repair frisco | 2,679 | 20.0 | 143 · 18.8 |
| 6 | frisco water line repair | 2,597 | 20.1 | 157 · 19.2 |
| 7 | pipe breaks frisco tx | 1,612 | 52.0 | 29 · 18.8 |
| 8 | water line repair dallas | 1,380 | 54.6 | 35 · 30.7 |
| 9 | frisco tx pipe break repair | 1,374 | 23.5 | 95 · 27.0 |
| 10 | pipe breaks frisco | 1,363 | 37.0 | 33 · 18.9 |
| 11 | frisco pipe break repair | 1,224 | 25.2 | 100 · 15.7 |
| 12 | plano tx water line repair | 1,088 | 69.8 | 106 · 54.6 |
| 13 | dallas tx water line repair | 1,035 | 59.4 | 43 · 44.4 |
| 14 | frisco tx faucet repair | 1,028 | 49.0 | нет |
| 15 | trenchless water line replacement frisco | 951 | 4.2 | 3 · 9.7 |
| 16 | little elm water line repair | 898 | 45.8 | 38 · 59.5 |
| 17 | water line repair plano | 841 | 48.0 | 10 · 17.7 |
| 18 | water line repair little elm | 823 | 40.5 | 39 · 43.1 |
| 19 | dallas water line repair | 750 | 74.9 | нет |
| 20 | frisco gas line repair | 726 | 64.3 | 9 · 34.8 |
| 21 | water line repair dallas tx | 723 | 50.5 | 38 · 35.0 |
| 22 | plano water line repair | 699 | 58.2 | 63 · 30.8 |
| 23 | the colony water line repair | 674 | 47.0 | нет |
| 24 | water line repair the colony | 618 | 55.7 | нет |
| 25 | water line repair little elm tx | 613 | 49.1 | 19 · 48.6 |
| 26 | faucet repair frisco tx | 602 | 59.7 | нет |
| 27 | slab leak repair frisco | 590 | 73.7 | нет |
| 28 | frisco slab leak repair | 539 | 68.7 | нет |
| 29 | little elm pipe break repair | 536 | 50.3 | нет |
| 30 | frisco tx leak detection | 479 | 60.8 | 5 · 81.2 |

### 2.3. Что держат title, H1, каждый H2 и каждый вопрос FAQ

Заголовок держит запрос, когда все значимые слова запроса стоят в нём. Подробно, запрос за запросом: `gsc-headings.md`.

| Заголовок | 3 мес: запросов · показы | 16 мес: запросов · показы | Фраза целиком, 16 мес | Держит только он, 16 мес |
|---|---|---|---|---|
| title | 23 · 5,786 | 46 · 41,042 | 14 · 25,510 | 21 · 15,139 |
| meta description | 0 · 0 | 0 · 0 | 0 · 0 | 0 · 0 |
| H1 | 8 · 4,766 | 20 · 25,543 | 11 · 25,496 | 0 · 0 |
| H2 «Signs of a Main Water Line Leak» | 4 · 8 | 7 · 14 | 3 · 5 | 0 · 0 |
| H2 «Water Line Responsibility: Yours or the City's» | 0 · 0 | 1 · 1 | 1 · 1 | 0 · 0 |
| H2 «Locating an Underground Water Line Leak» | 1 · 1 | 4 · 4 | 2 · 2 | 0 · 0 |
| H2 «Water Line Leak at the Foundation: Copper Set in Concrete» | 1 · 1 | 4 · 4 | 2 · 2 | 0 · 0 |
| H2 «Water Line Repair vs Full Replacement» | 5 · 2,342 | 15 · 21,026 | 9 · 20,647 | 0 · 0 |
| H2 «Tree Roots and the Water Line» | 0 · 0 | 1 · 1 | 1 · 1 | 0 · 0 |
| H2 «What Else It Might Be» | 0 · 0 | 0 · 0 | 0 · 0 | 0 · 0 |
| H2 «Water Line FAQ» | 0 · 0 | 1 · 1 | 1 · 1 | 0 · 0 |
| вопрос FAQ «How do I know if my main water line is leaking?» | 4 · 8 | 7 · 14 | 3 · 5 | 0 · 0 |
| вопрос FAQ «Am I responsible for the water line, or is the city?» | 0 · 0 | 1 · 1 | 1 · 1 | 0 · 0 |
| вопрос FAQ «Do you have to dig up my whole yard?» | 0 · 0 | 0 · 0 | 0 · 0 | 0 · 0 |
| вопрос FAQ «Should I repair the section or replace the line?» | 0 · 0 | 0 · 0 | 0 · 0 | 0 · 0 |
| вопрос FAQ «Can tree roots damage a water line?» | 0 · 0 | 1 · 1 | 1 · 1 | 0 · 0 |
| вопрос FAQ «Why did my water pressure drop everywhere at once?» | 0 · 0 | 0 · 0 | 0 · 0 | 0 · 0 |
| вопрос FAQ «The city sent me a notice about high water usage. What now?» | 0 · 0 | 0 · 0 | 0 · 0 | 0 · 0 |
| вопрос FAQ «Why did my line fail right at the foundation?» | 0 · 0 | 0 · 0 | 0 · 0 | 0 · 0 |
| вопрос FAQ «How long does a water line repair take?» | 3 · 2,266 | 10 · 20,666 | 8 · 20,646 | 0 · 0 |

Что нельзя потерять:
- Title. Из заголовков только в нём Frisco и Plano, поэтому 21 запрос (15,139 показов за 16 мес) не держит больше ни один заголовок. Крупнейшие: "frisco tx water line repair" (3,450), "water line repair frisco tx" (2,809), "water line repair frisco" (2,679), "frisco water line repair" (2,597), "plano tx water line repair" (1,088), "water line repair plano" (841), "plano water line repair" (699), "water line repair plano tx" (442), "water line replacement plano tx" (274), "main water line replacement" (185, место 6.2).
- "water line repair" целиком стоит в title, H1, H2 "Water Line Repair vs Full Replacement" и вопросе "How long does a water line repair take?", в обычном тексте ни разу. "main water line repair" целиком в title и H1. Эти два запроса: 25,256 показов за 16 мес, 4,744 за 3 мес.
- "water line replacement" (344, место 21.1) держат H2 "Water Line Repair vs Full Replacement" и title (слова не подряд).
- Описание не держит ни одного запроса (в нём нет слов water и repair). Остальные H2 и семь вопросов FAQ держат от 0 до 14 показов. Запросы, которые не держит ни один заголовок (кроме описания): 506 и 33,083 показа за 16 мес, 114 и 1,562 за 3 мес.

### 2.4. Фраза целиком

Проверены первые 20 по показам за 16 мес и за 3 мес (вместе 30 разных; запросов с кликами нет). Таблица: `gsc-phrases-and-reverse.md`. Точная фраза стоит на странице у двух: "water line repair" (title, H1, H2 "Water Line Repair vs Full Replacement", вопрос FAQ "How long does a water line repair take?") и "main water line repair" (title, H1). У остальных 28 нет ни точной фразы, ни фразы без in и tx: городских форм вида "water line repair frisco", "frisco tx water line repair", "water line repair plano" на странице нет; "pipe breaks frisco tx" (1,612 за 16 мес), "frisco tx pipe break repair" (1,374), "pipe breaks frisco" (1,363), "frisco pipe break repair" (1,224): слова "break" на странице нет вообще; нет "water line replacement" подряд, "water line leak repair", "water leak repair", "water line plumber".

### 2.5. Где другая страница сайта стоит выше или берёт показы

Только запросы услуги (водяная линия и pipe break), без чужих мест. Полностью по всем запросам: `gsc-other-pages-3m.md`, `gsc-other-pages-16m.md`; по услуге и городам: `gsc-service-other-pages-cities.md`.

За 3 мес выше или с большим числом показов по тем же запросам: /plumber-plano-tx/ (27 запросов, 1,762 показа против 6,190 у /water-lines/), /plumber-frisco-tx/ (22, 1,166 против 5,660), /plumber-little-elm-tx/ (5, 388 против 103), главная (8, 64 против 5,147), остальные меньше 60 показов. За 16 мес: /plumber-little-elm-tx/ (9, 4,593 против 3,335), /plumber-the-colony-tx/ (9, 4,536 против 2,101), /plumber-plano-tx/ (44, 4,379 против 44,814), главная (43, 2,909 против 29,621), /plumber-allen-tx/ (6, 1,819 против 796), /slab-leak-repair-frisco-plano-mckinney/ (9, 1,497 против 415), /plumber-frisco-tx/ (28, 1,484 против 29,994); ещё шесть страниц от 833 до 1,416 показов.

| Запрос | Другая страница: показы · место | /water-lines/: показы · место | Период |
|---|---|---|---|
| water line repair | главная: 1,744 · 1.7 | 20,416 · 16.4 | 16 мес |
| water line repair | /plumber-frisco-tx/: 642 · 1.7 (за 3 мес 373 · 1.45) | 20,416 · 16.4 | 16 мес |
| water line repair | /plumber-plano-tx/: 501 · 1.2 (столько же за 16 мес) | 2,253 · 14.1 | 3 мес |
| water line repair plano | /plumber-plano-tx/: 319 · 14.1 | 10 · 17.7 | 3 мес |
| frisco tx water line repair | /plumber-frisco-tx/: 195 · 16.2 | 221 · 30.9 | 3 мес |
| frisco tx pipe break repair | /plumber-frisco-tx/: 112 · 13.7 | 95 · 27.0 | 3 мес |
| water line repair the colony | /plumber-the-colony-tx/: 867 · 30.4 | 618 · 55.7 | 16 мес |
| water line repair carrollton | /plumber-carrollton-tx/: 823 · 57.0 | 9 · 66.1 | 16 мес |
| pipe breaks plano | /emergency-plumbing-services/: 646 · 59.3 | 107 · 94.6 | 16 мес |
| water line repair mckinney | /slab-leak-repair-frisco-plano-mckinney/: 412 · 76.1 | 12 · 72.2 | 16 мес |

Места 1.2 до 1.7 у страниц Plano и Frisco по запросу без своего города это по правилу проекта (`tools/cannibalization_report.py`: страница офиса, место 3 или выше, в запросе нет её города) показы из карточки на карте, не обычная выдача. Откуда место 1.7 у главной по "water line repair", файлы не говорят.

Запросы о водяной линии, где /water-lines/ нет вовсе, а другие страницы есть (16 мес): /plumber-carrollton-tx/ 4 запроса, 1,827 показов; /plumber-lewisville-tx/ 4, 1,087; гайд по главному крану 114, 586 показов, 2 клика; главная 19, 239; остальные меньше 120.

Обратное, по карте ключей хозяин другой, а показывается /water-lines/ (16 мес, за 3 мес в скобках): leak detection (хозяин /water-leak-detection-frisco-plano/) 39 запросов, 1,821 показ (10), место 58.4, крупнее всех "frisco tx leak detection" 479, "underground leak detection frisco" 271 (место 25.8), "waterline leak detection frisco" 186 (21.0); slab leak (/slab-leak-repair-frisco-plano-mckinney/) 12, 1,817 (0), место 72.2; faucet (/fixture-installation-repair/) 8, 1,742 (0), "frisco tx faucet repair" 1,028; sewer (/drain-services/) 13, 859 (7); остальные темы вместе меньше 100. Без хозяина по карте: pipe break и burst pipe 106 запросов, 9,013 (615), место 40.2. Таблица: `gsc-phrases-and-reverse.md`.

### 2.6. Услуга с каждым из десяти городов

Запрос о водяной линии с названием города, места взвешены по показам. Каждый запрос: `gsc-ten-cities.md`.

| Город | /water-lines/ 16 мес: запросов · показы · место | 3 мес | Больше всех показов, 16 мес | Другие страницы, 16 мес |
|---|---|---|---|---|
| Frisco | 11 · 12,691 · 18.1 | 8 · 761 · 24.6 | /water-lines/ | главная 4,132 · 42.1; Frisco 1,375 · 46.9; Plano 177 · 3.8 |
| Plano | 21 · 3,943 · 59.9 | 5 · 185 · 43.4 | /water-lines/ | Plano 2,335 · 41.3; slab leak 265 · 71.1; главная 190 · 41.0 |
| McKinney | 6 · 161 · 41.6 | 0 | /plumber-mckinney-tx/ 1,464 · 62.4 | slab leak 897 · 76.2; главная 289 · 81.1 |
| Allen | 6 · 820 · 57.4 | 0 | /plumber-allen-tx/ 1,838 · 43.4 | нет |
| Prosper | 0 | 0 | запросов нет ни у одной страницы | |
| Celina | 0 | 0 | запросов нет ни у одной страницы | |
| Little Elm | 4 · 2,714 · 47.4 | 4 · 102 · 53.3 | /plumber-little-elm-tx/ 2,963 · 41.9 | главная 28; /contact/ 21 |
| The Colony | 4 · 1,672 · 55.5 | 0 | /plumber-the-colony-tx/ 2,938 · 35.9 | главная 71 · 3.8 |
| Carrollton | 2 · 11 · 59.9 | 0 | /plumber-carrollton-tx/ 2,650 · 55.1 | |
| Lewisville | 3 · 41 · 79.2 | 0 | /plumber-lewisville-tx/ 2,119 · 62.8 | главная 5 · 5.4 |

Только по Frisco и Plano /water-lines/ берёт больше всех показов. По Little Elm, The Colony, Allen, McKinney, Carrollton, Lewisville больше у страниц городов. Park Cities: 3 запроса за 16 мес, 6 показов, ни один не про водяную линию.

### 2.7. Слова в запросах, которые на страницу не ставятся

Подробно: `gsc-words-set-aside.md`. Показы за 16 мес (за 3 мес в скобках):
- Чужие места: Dallas 4,493 (121), Rockwall 1,006 (159), Coppell 265 (50), Kennedale 35, Highlands 32, Duncanville 31, Reeves Park 25, Denton 20, Water Valley 15, Evergreen 13, Knickerbocker 11, Rowlett 10 и ещё 34 места меньше 10 показов каждое (среди них Lockhart, Irving, Richardson, Collin County, места в Utah с "ut"). "Dallas" отдельно правила запрещают.
- Услуги, которых нет или которые не заявляем: trenchless 1,352 (3), gas line 989 (35), pipe lining и CIPP 440, колодцы и насосы 150 (8), drainage 50, repipe 38 (6), irrigation 16, motherboard 7, reroute 3 (3), excavation 3.
- Оценочные слова: cost 105, nearby 14, fast 11, прочие 6. Опечатки и чужой язык: "sab" 42, испанские запросы 2, "imagenes", "reapir".
- Бренд и поиск по сайту: 485 (23), место 2.3. Park Cities: 6 показов, страницы нет и не будет.

Слова услуги из запросов, которых нет на странице: "break" 7,623 (315, вместе с breaks и broken), "little elm" 3,772, "colony" 1,931, "faucet" 1,756 (тема страницы faucet), "sewer" 975 (тема /drain-services/), "allen" 882, "waterline" 401, "burst" 244. "frisco" (26,634) стоит только в title и alt.

## Файлы с длинными таблицами

`docs/briefs/services/water-lines/`:
- `gsc-all-queries-3m.md`, `gsc-all-queries-16m.md`: все запросы страницы, с группой, хозяином темы, словами в тексте и местом точной фразы.
- `gsc-headings.md`: что держит каждый заголовок, запрос за запросом.
- `gsc-phrases-and-reverse.md`: проверка фразы целиком (30 запросов) и запросы с другим хозяином по карте ключей.
- `gsc-other-pages-3m.md`, `gsc-other-pages-16m.md`: все запросы страницы, где другая страница выше или с большим числом показов, и запросы о водяной линии, где /water-lines/ нет.
- `gsc-service-other-pages-cities.md`: то же только по запросам услуги, и десять городов.
- `gsc-ten-cities.md`: каждый запрос о водяной линии с каждым из десяти городов.
- `gsc-words-set-aside.md`: каждое слово запросов, где оно стоит, и что отложено.
