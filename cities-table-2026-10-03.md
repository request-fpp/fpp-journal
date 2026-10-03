# Общая таблица страниц городов (части 9.1 и 9.2)

Ночь на 3 октября 2026. Девять страниц городов без Frisco. На сайте ничего не менялось, это справка для брифов.

## Откуда цифры

- Search Console: запросы из `source/gsc/page-query-3m.csv` (1 июля по 28 сентября 2026) и `page-query-16m.csv` (31 мая 2025 по 28 сентября 2026); итог страницы вместе со скрытыми запросами из `source/gsc/performance-3m/Pages.csv` и `performance-16m/Pages.csv`. Позиция везде средняя.
- Celina: в Search Console два адреса, нынешний `/plumber-celina-tx/` и старый `/plumber-the-celina-tx/` (с него переадресация). Они сложены, общая позиция посчитана с весом по показам.
- Title, H1, слова: `source/crawl/pages/plumber-<город>-tx.json` (обход 30 сентября 2026). Фото и клипы: `docs/briefs/_shared/photos-by-city-after-recount.json`; "свободно" значит, что кадр не стоит ни на одной собранной странице.
- Отзывы: `reviews/all-reviews.csv` (407 строк, 396 с пятью звездами). Занятые: двенадцать главной, три резерва, `reviews/site-reviews.json` и `reviews/site-ledger.md` (прочитаны в 02:25: 40 авторов на 14 страницах).
- Приложения в `docs/briefs/_shared/`: `cities-gsc-top-queries-2026-10-03.md` (по 50 запросов за 3 и 16 месяцев), `cities-gsc-other-page-above-2026-10-03.csv` (все запросы, где выше другая страница), `cities-free-photos-2026-10-03.md` (номера свободных кадров), `cities-table-notes-2026-10-03.md` (какие места искал в отзывах и откуда названия, старые страницы, замечания), `cities-official-place-names-2026-10-03.json` (списки районов, индексы).

## Сводная таблица

Итоги со скрытыми запросами. Фото и клипы: всего / свободно. Последний столбец: свободные пятизвездочные отзывы, где назван город.

| Город | Клики 3м | Показы 3м | Поз. 3м | Клики 16м | Показы 16м | Поз. 16м | Слов | Фото | Клипы | Отзывы |
|---|---|---|---|---|---|---|---|---|---|---|
| Plano | 98 | 56 197 | 6,8 | 103 | 108 268 | 30,5 | 2228 | 22 / 18 | 13 / 13 | 6 |
| Little Elm | 0 | 8 852 | 21,1 | 4 | 62 924 | 35,1 | 1637 | 11 / 10 | 1 / 0 | 0 |
| The Colony | 1 | 8 682 | 15,6 | 3 | 65 244 | 31,2 | 1804 | 2 / 1 | 0 / 0 | 0 |
| Prosper | 0 | 4 853 | 11,7 | 5 | 15 394 | 17,1 | 1353 | 4 / 3 | 0 / 0 | 1 |
| Lewisville | 2 | 3 531 | 25,7 | 2 | 63 896 | 50,9 | 1458 | 0 / 0 | 0 / 0 | 0 |
| Celina | 0 | 3 757 | 16,7 | 1 | 13 793 | 21,0 | 1355 | 2 / 2 | 0 / 0 | 0 |
| Carrollton | 2 | 2 631 | 21,3 | 2 | 45 336 | 52,5 | 1624 | 10 / 8 | 0 / 0 | 2 |
| Allen | 1 | 1 134 | 22,7 | 2 | 39 801 | 36,5 | 1594 | 12 / 11 | 1 / 1 | 0 |
| McKinney | 0 | 472 | 27,2 | 1 | 20 833 | 61,3 | 1891 | 14 / 12 | 9 / 9 | 1 |
| Все девять | 104 | 90 109 | | 123 | 435 489 | | | | | 10 |

| Город | Title живой страницы | H1 живой страницы |
|---|---|---|
| Plano | Plumber Plano, TX \| Fast Plumbing - Clogged Drains & Emergencies | Plumber Plano, TX - Same-Day Help for Clogs, Leaks & More |
| Little Elm | Plumber Little Elm, TX \| Water Line & Water Heater Repair & PRV | Plumber in Little Elm, TX - Water Lines, Water Heaters & Everyday Repairs |
| The Colony | Plumber The Colony, TX \| Slab Leak & Drain Cleaning Services | Plumber in The Colony, TX - Slab Leaks, Drains & Everyday Repairs |
| Prosper | Plumber Prosper, TX \| Plumbing for New Homes, Clogs & Emergencies | Plumber in Prosper, TX - Close By, Licensed, and Actually Available |
| Lewisville | Plumber Lewisville, TX \| Water Leaks, Slab Leaks & Faucet Repair | Plumber in Lewisville, TX - Finding Leaks Before They Find Your Floors |
| Celina | Plumber in Celina, TX \| Water Heater Repair & Replacement - FPP | Plumber in Celina, TX - Water Heaters and the Problems New Houses Hide |
| Carrollton | Plumber Carrollton, TX \| Leak Detection, Slab Leak & PRV Repair | Plumber in Carrollton, TX - We Find the Leak Before Anyone Digs |
| Allen | Plumber in Allen, TX \| Hose Bibs, Water Heaters & Drains - FPP | Plumber in Allen, TX - Licensed Plumbing Repair for the Whole House |
| McKinney | Plumber in McKinney, TX \| Slab Leak & Garbage Disposal Repair | Plumbing Repair in McKinney, TX - Slab Leaks, Water Heaters, Drains and Disposals |

Известные запросы. "Выше другая": запросы с городом, где другая страница сайта стоит выше страницы города (в скобках: у другой страницы десять и более показов). "Нет страницы": по запросу с городом показывается только другая страница.

| Город | Известные, 3м: кл. / пок. / запросов / поз. | Известные, 16м | С городом у страницы, 3м: запросов / пок. | Выше другая, 3м | Выше другая, 16м | Нет страницы, 3м / 16м |
|---|---|---|---|---|---|---|
| Plano | 48 / 49 302 / 1320 / 7,1 | 51 / 99 441 / 1569 / 32,0 | 351 / 18 096 | 54 (29) | 321 | 70 / 271 |
| Little Elm | 0 / 7 738 / 136 / 21,7 | 1 / 60 930 / 205 / 35,3 | 118 / 7 460 | 14 (7) | 35 | 3 / 3 |
| The Colony | 1 / 7 903 / 196 / 15,7 | 1 / 63 252 / 299 / 31,4 | 113 / 5 605 | 59 (21) | 111 | 12 / 11 |
| Prosper | 0 / 3 799 / 87 / 11,3 | 4 / 12 877 / 131 / 16,8 | 46 / 2 959 | 22 (10) | 26 | 2 / 6 |
| Lewisville | 0 / 3 244 / 118 / 25,9 | 0 / 61 559 / 258 / 51,1 | 97 / 2 867 | 10 (2) | 28 | 4 / 9 |
| Celina | 0 / 1 705 / 86 / 19,1 | 0 / 10 448 / 172 / 22,3 | 38 / 768 | 9 (3) | 16 | 1 / 1 |
| Carrollton | 2 / 2 450 / 98 / 21,2 | 2 / 43 821 / 189 / 52,8 | 76 / 2 178 | 15 (5) | 38 | 9 / 11 |
| Allen | 1 / 553 / 67 / 22,1 | 2 / 37 563 / 251 / 36,7 | 51 / 457 | 0 (0) | 13 | 2 / 16 |
| McKinney | 0 / 319 / 40 / 30,8 | 0 / 19 500 / 171 / 62,3 | 23 / 108 | 6 (3) | 61 | 34 / 111 |

## Проверка сумм вторым счетом

Итоги страниц из `Pages.csv` совпали с `source/gsc/page-query-coverage.csv` по всем адресам за оба периода. Суммы по известным запросам посчитаны дважды, скриптом на Python и запросом в SQLite: клики, показы, число запросов и позиция совпали по каждому адресу.

## Что видно сразу

- Клики почти все у Plano: 98 из 104 за 3 месяца. У Little Elm, Prosper, Celina и McKinney за 3 месяца ноль.
- Страница Plano показывается по общим запросам без города (plumber, plumber near me, emergency plumber) и по запросам с чужими городами, и стоит по ним выше страниц этих городов. Вероятная причина (мой вывод, не факт из файла): карточка Google в Plano ведет на `/plumber-plano-tx/` (`reviews/live-check-2026-10-03.md`), и показы карточки идут в счет этой страницы. Так же ведет себя `/plumber-frisco-tx/`.
- McKinney: по запросам с городом чаще показываются страницы услуг с McKinney в адресе (slab leak, water heater repair), чем страница города: 34 запроса без нее против 23 с ней за 3 месяца.
- За 3 месяца позиции у всех девяти лучше, чем в среднем за 16 месяцев.
- Пять городов не названы ни в одном отзыве архива: Little Elm, The Colony, Lewisville, Celina, Allen.
- У Lewisville нет ни одного фото, у Celina и The Colony по два, у Prosper четыре.

## Части по городам

В каждой части: двадцать главных запросов за 3 месяца по показам (звездочка: в запросе назван другой город из десяти), известные запросы с кликами (в скобках клики; клики по скрытым запросам есть только в сводной таблице) и запросы с городом, где другая страница стоит выше (первые три по показам другой страницы). Отзывы по городам собраны в разделе "Раскладка отзывов", номера свободных кадров в `cities-free-photos-2026-10-03.md`.

### Plano

| Запрос | Пок. | Кл. | Поз. |
|---|---|---|---|
| plumber plano tx | 2197 | 1 | 4,5 |
| plumber | 2026 | 1 | 2,9 |
| plumber near me | 1957 | 2 | 4,9 |
| sewer line replacement the colony tx* | 1816 | 0 | 5,2 |
| emergency plumber | 1774 | 0 | 2,3 |
| slab leak repair the colony tx* | 1709 | 0 | 6,1 |
| plumber frisco tx* | 1448 | 1 | 9,2 |
| slab leak repair frisco tx* | 1414 | 0 | 9,0 |
| plumber frisco* | 1403 | 0 | 1,0 |
| plumber plano | 793 | 1 | 13,6 |
| emergency plumber near me | 778 | 0 | 1,0 |
| drain cleaning | 761 | 0 | 1,5 |
| plano plumbing | 585 | 0 | 22,0 |
| sewer line replacement | 541 | 0 | 3,7 |
| water heater repair | 510 | 0 | 2,3 |
| water line repair | 501 | 0 | 1,2 |
| plano plumbing service | 500 | 0 | 18,6 |
| plano plumber | 498 | 1 | 12,6 |
| emergency plumber plano | 469 | 0 | 7,4 |
| slab leak repair | 430 | 0 | 4,9 |

Клики, 3 мес.: fpp plumbing (21), plumbers near me (3), plumber near me (2), plumbers plano (2), plumber plano tx (1) и еще 19. 16 мес.: fpp plumbing (21), plumber plano tx (3), plumbers near me (3), plumber near me (2), plumbers plano (2) и еще 20.

Выше стоят (запросов, показов): `/` (40, 3 010); `/emergency-plumbing-services/` (10, 311); `/garbage-disposal-repair-frisco-plano/` (1, 228).

| Запрос с городом | Город: поз. / пок. | Выше стоит | Поз. / пок. |
|---|---|---|---|
| emergency plumber plano | 7,4 / 469 | `/` | 6,8 / 700 |
| plumbing plano tx | 31,5 / 184 | `/` | 26,3 / 333 |
| plumbing plano | 39,5 / 353 | `/` | 12,7 / 312 |

### Little Elm

| Запрос | Пок. | Кл. | Поз. |
|---|---|---|---|
| plumber little elm | 321 | 0 | 20,2 |
| emergency plumber little elm tx | 270 | 0 | 19,2 |
| plumber little elm tx | 259 | 0 | 21,1 |
| water heater repair little elm | 252 | 0 | 18,8 |
| little elm tx emergency plumbing | 235 | 0 | 16,7 |
| little elm plumber | 189 | 0 | 19,9 |
| emergency plumber little elm | 184 | 0 | 19,3 |
| plumbing little elm tx | 183 | 0 | 28,4 |
| little elm plumbers | 173 | 0 | 24,1 |
| expansion tanks repair little elm tx | 171 | 0 | 10,8 |
| little elm tx emergency plumber | 164 | 0 | 21,8 |
| little elm tx emergency plumbers | 132 | 0 | 20,4 |
| bathroom plumbing little elm | 129 | 0 | 25,6 |
| little elm tx well repair | 129 | 0 | 23,6 |
| little elm water line repair | 129 | 0 | 13,0 |
| little elm tx leak detection | 124 | 0 | 23,4 |
| little elm tx pluming service | 120 | 0 | 29,4 |
| little elm tx faucet repair | 119 | 0 | 13,9 |
| plumbers little elm tx | 119 | 0 | 24,6 |
| little elm slab leak repair | 115 | 0 | 11,0 |

Клики, 3 мес.: нет. 16 мес.: emergency plumber little elm (1).

Выше стоят (запросов, показов): `/garbage-disposal-repair-frisco-plano/` (2, 347); `/plumber-frisco-tx/` (10, 76); `/plumber-plano-tx/` (6, 41).

| Запрос с городом | Город: поз. / пок. | Выше стоит | Поз. / пок. |
|---|---|---|---|
| garbage disposal repair little elm tx | 25,0 / 1 | `/garbage-disposal-repair-frisco-plano/` | 20,4 / 184 |
| garbage disposal repair little elm | 16,0 / 1 | `/garbage-disposal-repair-frisco-plano/` | 13,7 / 163 |
| emergency plumber little elm | 19,3 / 184 | `/plumber-frisco-tx/` | 12,1 / 18 |

Фото: из 11 кадров придержано 8 (№ 16, 38, 39, 40, 41, 102, 126, 204): сняты за чертой города, почтовый адрес Little Elm, ждут слова Дениса; № 204 из них уже стоит на главной. Без оговорок свободны три фото в черте города (№ 69, 123, 124). Клип № 165 записан за Little Elm по слову Дениса и стоит на главной.

### The Colony

| Запрос | Пок. | Кл. | Поз. |
|---|---|---|---|
| plumber the colony tx | 257 | 0 | 19,9 |
| plumber near me | 215 | 0 | 12,2 |
| plumber the colony | 214 | 0 | 19,0 |
| the colony plumber | 200 | 0 | 20,7 |
| fpp plumbing | 176 | 0 | 1,8 |
| emergency plumber the colony tx | 167 | 0 | 13,6 |
| plumbers the colony tx | 167 | 0 | 19,7 |
| plumber in the colony | 158 | 0 | 20,9 |
| slab leak repair the colony tx | 156 | 0 | 7,4 |
| the colony tx emergency plumber | 151 | 0 | 14,6 |
| emergency plumber the colony | 150 | 0 | 12,6 |
| plumbing company | 142 | 0 | 13,8 |
| the colony tx drain cleaning | 138 | 0 | 10,9 |
| faucet repair the colony tx | 131 | 0 | 14,7 |
| plumbers in the colony | 131 | 0 | 22,9 |
| plumber service | 118 | 0 | 12,0 |
| the colony sump pump repair | 115 | 0 | 23,7 |
| drain cleaning the colony tx | 114 | 0 | 10,4 |
| the colony plumber service | 114 | 0 | 19,8 |
| plumbers the colony | 112 | 0 | 19,4 |

Клики, 3 мес.: plumbers in the colony tx (1). 16 мес.: plumbers in the colony tx (1).

Выше стоят (запросов, показов): `/plumber-plano-tx/` (59, 4 867); `/plumber-frisco-tx/` (6, 324); `/` (8, 14).

| Запрос с городом | Город: поз. / пок. | Выше стоит | Поз. / пок. |
|---|---|---|---|
| sewer line replacement the colony tx | 15,5 / 4 | `/plumber-plano-tx/` | 5,2 / 1816 |
| slab leak repair the colony tx | 7,4 / 156 | `/plumber-plano-tx/` | 6,1 / 1709 |
| plumber the colony tx | 19,9 / 257 | `/plumber-plano-tx/` | 4,8 / 360 |

### Prosper

| Запрос | Пок. | Кл. | Поз. |
|---|---|---|---|
| prosper plumber | 499 | 0 | 9,0 |
| plumber prosper tx | 488 | 0 | 10,2 |
| plumber prosper | 452 | 0 | 8,3 |
| plumber near me | 297 | 0 | 9,3 |
| plumbing company prosper tx | 175 | 0 | 10,4 |
| plumbing services prosper tx | 123 | 0 | 11,1 |
| plumbers prosper tx | 108 | 0 | 9,7 |
| plumber in prosper | 95 | 0 | 9,1 |
| emergency plumber prosper | 87 | 0 | 8,3 |
| plumber | 86 | 0 | 13,4 |
| water heater repair prosper | 86 | 0 | 10,8 |
| water heater replacement prosper | 71 | 0 | 16,9 |
| the prosper plumber | 66 | 0 | 11,2 |
| toilet repair prosper | 65 | 0 | 13,5 |
| plumbing repair near me | 59 | 0 | 15,7 |
| emergency plumbing prosper | 56 | 0 | 14,8 |
| water heater replacement near me | 50 | 0 | 10,4 |
| water heater repair near me | 46 | 0 | 11,8 |
| toilet repair near me | 44 | 0 | 10,1 |
| plumbing near me | 42 | 0 | 20,0 |

Клики, 3 мес.: нет. 16 мес.: plumber prosper (3), prosper plumber (1).

Выше стоят (запросов, показов): `/plumber-frisco-tx/` (21, 258); `/plumber-plano-tx/` (5, 30).

| Запрос с городом | Город: поз. / пок. | Выше стоит | Поз. / пок. |
|---|---|---|---|
| plumber prosper tx | 10,2 / 488 | `/plumber-frisco-tx/` | 2,6 / 28 |
| emergency plumber prosper | 8,3 / 87 | `/plumber-frisco-tx/` | 1,0 / 26 |
| sewer line repair prosper | 37,0 / 1 | `/plumber-frisco-tx/` | 1,0 / 25 |

### Lewisville

| Запрос | Пок. | Кл. | Поз. |
|---|---|---|---|
| slab leak repair lewisville | 200 | 0 | 9,6 |
| plumber lewisville tx | 152 | 0 | 33,4 |
| slab leak repair lewisville tx | 152 | 0 | 9,5 |
| lewisville tx leak detection | 134 | 0 | 19,9 |
| plumber lewisville | 113 | 0 | 34,3 |
| lewisville tx sab leak repair | 106 | 0 | 11,8 |
| lewisville slab leak repair | 105 | 0 | 9,0 |
| lewisville tx slab leak repair | 98 | 0 | 12,9 |
| lewisville plumbing | 94 | 0 | 35,0 |
| plumbers lewisville tx | 94 | 0 | 38,4 |
| plumbers in lewisville tx | 92 | 0 | 42,2 |
| plumbing lewisville tx | 89 | 0 | 40,3 |
| lewisville plumber | 79 | 0 | 37,9 |
| plumber in lewisville tx | 78 | 0 | 36,5 |
| google find me a plumber | 66 | 0 | 35,0 |
| plumbers lewisville texas | 66 | 0 | 38,6 |
| lewisville plumber service | 65 | 0 | 35,9 |
| lewisville plumbing service | 63 | 0 | 33,0 |
| lewisville leak detection | 62 | 0 | 19,1 |
| plumbers in lewisville texas | 53 | 0 | 40,8 |

Клики, 3 мес.: нет. 16 мес.: нет.

Выше стоят (запросов, показов): `/plumber-plano-tx/` (10, 135).

| Запрос с городом | Город: поз. / пок. | Выше стоит | Поз. / пок. |
|---|---|---|---|
| plumber lewisville tx | 33,4 / 152 | `/plumber-plano-tx/` | 16,9 / 76 |
| leak detection plumber lewisville | 17,3 / 26 | `/plumber-plano-tx/` | 1,4 / 40 |

В архиве нет ни одного фото и ни одного клипа из Lewisville.

### Celina

| Запрос | Пок. | Кл. | Поз. |
|---|---|---|---|
| plumber near me | 152 | 0 | 15,5 |
| plumber celina | 130 | 0 | 24,5 |
| plumbing near me | 85 | 0 | 17,2 |
| water heater replacement near me | 84 | 0 | 13,3 |
| water heater repair near me | 78 | 0 | 9,6 |
| celina plumber | 69 | 0 | 32,6 |
| water heater repair celina | 65 | 0 | 19,3 |
| water heater replacement celina | 62 | 0 | 19,6 |
| emergency plumber near me | 56 | 0 | 9,3 |
| emergency plumbing near me | 51 | 0 | 9,5 |
| plumbing repair | 50 | 0 | 14,3 |
| plumbing service celina | 47 | 0 | 19,6 |
| emergency plumbing | 45 | 0 | 10,8 |
| plumber | 45 | 0 | 10,4 |
| plumbing company celina tx | 35 | 0 | 29,5 |
| plumber celina tx | 34 | 0 | 24,2 |
| emergency plumber | 31 | 0 | 11,9 |
| plumbers celina tx | 29 | 0 | 25,5 |
| plumbing company | 29 | 0 | 18,8 |
| 24 hour plumbers near me | 25 | 0 | 15,1 |

Клики, 3 мес.: нет. 16 мес.: нет.

Выше стоят (запросов, показов): `/plumber-frisco-tx/` (9, 58).

| Запрос с городом | Город: поз. / пок. | Выше стоит | Поз. / пок. |
|---|---|---|---|
| plumber celina | 24,5 / 130 | `/plumber-frisco-tx/` | 1,6 / 16 |
| plumber celina tx | 24,2 / 34 | `/plumber-frisco-tx/` | 3,9 / 11 |
| water heater repair celina | 19,3 / 65 | `/plumber-frisco-tx/` | 1,0 / 10 |

### Carrollton

| Запрос | Пок. | Кл. | Поз. |
|---|---|---|---|
| carrollton tx leak detection | 398 | 0 | 19,9 |
| carrollton leak detection | 366 | 0 | 25,0 |
| slab leak repair carrollton | 280 | 0 | 16,1 |
| slab leak repair carrollton tx | 231 | 0 | 12,9 |
| carrollton slab leak repair | 162 | 0 | 14,4 |
| slab leak plumber carrollton | 85 | 0 | 20,3 |
| slab leak detection carrollton | 74 | 0 | 22,3 |
| foundation leak detection carrollton | 70 | 0 | 30,5 |
| carrollton tx sab leak repair | 65 | 0 | 18,6 |
| leak repair carrollton | 57 | 0 | 23,0 |
| leak detection services carrollton | 53 | 0 | 25,2 |
| leak repair carrollton tx | 45 | 0 | 23,5 |
| google find me a plumber | 44 | 0 | 38,2 |
| alexa find me a plumber | 39 | 0 | 35,1 |
| slab leak repair near me | 38 | 0 | 9,9 |
| plumber carrollton | 36 | 1 | 25,2 |
| slab leak detection near me | 36 | 0 | 10,8 |
| carrollton tx pluming | 29 | 0 | 43,9 |
| water leak repair near me | 27 | 0 | 7,0 |
| water leak detection near me | 26 | 0 | 8,2 |

Клики, 3 мес.: plumber carrollton (1), plumber carrollton tx (1). 16 мес.: plumber carrollton (1), plumber carrollton tx (1).

Выше стоят (запросов, показов): `/plumber-plano-tx/` (15, 424); `/` (2, 10).

| Запрос с городом | Город: поз. / пок. | Выше стоит | Поз. / пок. |
|---|---|---|---|
| plumber carrollton tx | 29,3 / 9 | `/plumber-plano-tx/` | 13,2 / 232 |
| emergency plumber carrollton | 18,3 / 6 | `/plumber-plano-tx/` | 1,3 / 98 |
| carrollton tx emergency plumbing | 21,6 / 17 | `/plumber-plano-tx/` | 1,6 / 42 |

### Allen

| Запрос | Пок. | Кл. | Поз. |
|---|---|---|---|
| allen tx faucet repair | 70 | 0 | 12,0 |
| faucet repair allen tx | 65 | 0 | 11,5 |
| expansion tanks repair allen tx | 46 | 0 | 13,9 |
| expansion tanks repair allen | 43 | 0 | 20,8 |
| fpp plumbing | 42 | 0 | 2,0 |
| plumbing company in allen | 34 | 0 | 40,5 |
| hose bibb repair allen | 33 | 0 | 5,7 |
| google find me a plumber | 18 | 0 | 63,4 |
| plumbing company allen tx | 16 | 0 | 43,4 |
| allen tx emergency plumbing | 13 | 0 | 22,9 |
| plumbing repairs allen tx | 11 | 0 | 38,9 |
| pro service plumbing | 11 | 0 | 35,0 |
| alexa find me a plumber | 9 | 0 | 48,7 |
| plumber allen tx | 9 | 0 | 49,7 |
| water heater repair allen tx | 9 | 0 | 9,6 |
| 24 hour plumber allen tx | 8 | 0 | 30,9 |
| allen tx pluming service | 6 | 0 | 32,0 |
| plumbing allen tx | 6 | 0 | 37,8 |
| plumbing fixture services allen tx | 6 | 0 | 31,5 |
| allen tx emergency plumbers | 5 | 0 | 33,4 |

Клики, 3 мес.: plumber allen (1). 16 мес.: plumber allen tx (1), plumber allen (1).

За 3 месяца нет запроса с городом, где у другой страницы выше позиция и десять и более показов.

### McKinney

| Запрос | Пок. | Кл. | Поз. |
|---|---|---|---|
| garbage disposal repair near me | 46 | 0 | 5,7 |
| google find me a plumber | 45 | 0 | 79,6 |
| slab leak plumber near me | 45 | 0 | 7,7 |
| slab leak plumber mckinney | 26 | 0 | 14,8 |
| alexa find me a plumber | 22 | 0 | 77,8 |
| fpp plumbing | 20 | 0 | 1,9 |
| plumber mckinney | 14 | 0 | 49,1 |
| garbage disposal repair mckinney | 12 | 0 | 9,9 |
| garbage disposal installation near me | 10 | 0 | 13,2 |
| leak detection plumber mckinney | 9 | 0 | 21,7 |
| repiping mckinney | 7 | 0 | 33,3 |
| 24 hour plumber mckinney texas | 6 | 0 | 45,3 |
| repiping near me | 6 | 0 | 19,7 |
| same day service plumbing mckinney | 6 | 0 | 15,5 |
| 24/7 plumber mckinney | 5 | 0 | 29,2 |
| plumber in mckinney | 5 | 0 | 49,4 |
| repiping services near me | 4 | 0 | 24,2 |
| dpp plumbing | 3 | 0 | 65,0 |
| low water pressure plumber mckinney | 3 | 0 | 13,0 |
| plumber mckinney tx | 2 | 0 | 59,0 |

Клики, 3 мес.: нет. 16 мес.: нет.

Выше стоят (запросов, показов): `/plumber-frisco-tx/` (3, 115); `/plumber-plano-tx/` (2, 77); `/emergency-plumbing-services/` (1, 13).

| Запрос с городом | Город: поз. / пок. | Выше стоит | Поз. / пок. |
|---|---|---|---|
| plumber mckinney tx | 59,0 / 2 | `/plumber-frisco-tx/` | 17,9 / 98 |
| plumber mckinney tx | 59,0 / 2 | `/plumber-plano-tx/` | 17,3 / 75 |
| emergency plumber mckinney tx | 16,0 / 1 | `/plumber-frisco-tx/` | 12,9 / 16 |

## Раскладка отзывов (часть 9.2)

Правило: отзыв, где назван город, закреплен за страницей этого города, другим городам его не предлагать. В таблице все свободные пятизвездочные отзывы, в тексте которых назван один из десяти городов или место в нем. Копии отзывов Google на Thumbtack отдельно не считаются.

| Город | Автор | Площадка, дата | Что названо | Заметка |
|---|---|---|---|---|
| Frisco | Yulia B | Google, 2025-07-04 | "emergency plumber in Frisco" | профиль Plano; назван Denys; "emergency fee" без жалобы |
| Plano | Southwest Industrial | Google, 2026-08-22 | "Shops at Legacy", "Plano" | три вызова, без имен |
| Plano | Nivas chowdary | Google, 2026-07-01 | "Plano" | профиль Frisco; AC drain line |
| Plano | Jose Walle | Google, 2026-07-01 | "Plano" | старая стр. Plano; Nick и Denys |
| Plano | Ксенія (на старом сайте Kseniia) | Google, 2026-06-27 | "Plano" | старая стр. PRV; PRV, 30 и 60 PSI |
| Plano | Deborah Allen | Google, 2026-06-19 | "Plano" | старая стр. Plano; Denys и Nick |
| Plano | Dawson And Kelly M. | Thumbtack, 2022-12-20 | "our house in Plano" | назван Denys; "within 20 mins" |
| Prosper | DMarcus Jones | Google, 2026-06-22 | "our home in Prosper" | профиль Frisco; старая стр. Prosper; Denys и Nick |
| Carrollton | Tyler Sommers | Google, 2026-06-17 | "Carrollton, TX" | старая стр. Carrollton; "within an hour" |
| Carrollton | Paula Thompson | Google, 2026-01-08 | "Carrollton, Tx" | старая стр. Carrollton; "20 minutes", "40 minutes" |
| McKinney | Ezzy Zhoo | Google, 2025-03-12 | "city of mckinney" | старая стр. McKinney; назван Denys; в тексте rerouting и gas line |
| Frisco и Plano | Julian Jaramillo | Google, 2025-04-25 | "plumber in Frisco or Plano" | два города сразу; назван Denys |

- Little Elm, The Colony, Lewisville, Celina, Allen: таких отзывов нет.
- Город назван, но автор занят: Rushi Nani и tony phuong (стоят на `/plumber-frisco-tx/`); Kathryn Kim, отзыв от 2026-02-13 с "emergency plumber in Frisco" (ее другой отзыв стоит на `/water-lines/`).
- Jan Shangle (Google, 2026-07-07, "Frisco Lakes home"): закреплена за Frisco, но на сайт не идет по решению Дениса от 2 октября (жалоба на комиссию 2.99%).
- Elnard KA (Google, 2025-07-07) пишет "North Dallas": это не город из десяти.
- Искал названия городов, названия с живых страниц и официальные списки районов (Plano, Frisco, McKinney, Allen, Prosper, Celina, The Colony; у Little Elm списка нет; сайты Carrollton и Lewisville не открылись, 403). Кроме городов, в архиве названы только "Shops at Legacy" и "Frisco Lakes", улиц нет. Подробно: `cities-table-notes-2026-10-03.md`.
- Старые страницы: Amy Anderson (стояла на Little Elm) теперь на главной, LXD Properties (McKinney) на странице Frisco, Gregory Gaskin II (Prosper) в резерве главной, Quan Nguyen (Little Elm) в запасе для hose bib. Остальные авторы старых страниц городов свободны.

## Вопросы Денису

1. Ксенія (Kseniia) называет Plano, но стояла на старой странице PRV. По правилу она уходит на Plano. Так и делаем?
2. Julian Jaramillo называет сразу Frisco и Plano. За какой страницей его закрепить?
3. Ezzy Zhoo (McKinney) пишет про rerouting и gas line, этого мы не предлагаем. Ставить его на McKinney?
4. Восемь фото с почтовым адресом Little Elm сняты за чертой города. Подписывать их Little Elm?
5. У Lewisville нет фото, у Celina и The Colony по два. Есть ли кадры с работ в этих городах вне архива?
6. В пяти городах нет отзыва с названием города. Просить ли клиентов из Little Elm, The Colony, Lewisville, Celina и Allen называть город в отзыве?
