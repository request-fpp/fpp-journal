# Бриф страницы The Colony (3 октября 2026)

Страница: /plumber-the-colony-tx/ . Собрано 3 октября 2026 из файлов разделов в папке `docs/briefs/the-colony/`. Страница этой ночью не переписывалась: текст напишет другой чат из этого брифа и из диктовки Дениса. В проекте ничего не менялось, кроме этого нового файла.

Как устроен файл. Части 1, 2, 3, 5, 6 и 8 это файлы разделов, вставленные целиком скриптом, слово в слово: первая строка файла (его заголовок) названа в начале части, остальные заголовки опущены на уровень ниже, в части 6 на два уровня, потому что там четыре файла. Части «Коротко», 4, 7, 9 и 10 написаны при сборке. Читать стоит «Коротко», потом части 9 и 10, остальное открывать по делу.

Оговорки к вставленным файлам:

- Слова «рядом» и «файл таблиц» во вставленных текстах значат папку `docs/briefs/the-colony/`. Длинные таблицы в бриф не вставлены: их имена названы в начале каждой части.
- Номера разделов внутри вставленных файлов («раздел 5», «пункт 6», «вопрос 3») относятся к самому файлу, не к частям брифа.
- Часть 6. Файлы фактов писались первыми, перепроверка шла после них. Где они расходятся, верить спискам 6.0 и таблицам проверки (6.3 и 6.4). В части 6 списки «что можно брать» и «чего нельзя» из двух файлов проверки переставлены в начало (6.0), остальное из этих файлов стоит в 6.3 и 6.4; ни одна строка не убрана.
- Координат, адресов клиентов и телефонов клиентов во вставленных файлах нет (проверено поиском при сборке). Адрес мэрии ("6053 Main Street") и адреса почтовых отделений в части 6 это открытые адреса города и почты. Телефон в title конкурента в части 3 это телефон компании. Номера 980-899-7997 и 469-998-8999 это номера FPP.
- Отзывы в части 1 и 5 даны дословно, с опечатками авторов; цифры приезда в них это слова клиентов, по решению Дениса их не трогаем.

Проверка брифа (3 октября 2026, около 10:50, отдельный проверяющий). Все десять пунктов задания на месте: живая страница (часть 1), Search Console за 3 и 16 месяцев (часть 2, полные таблицы в названных файлах рядом, все файлы есть), десять конкурентов и таблица (часть 3, тексты `00.txt` до `09.txt` в папке есть), фото и клипы (часть 4), десять кандидатов в отзывы (часть 5), официальные факты и проверенные списки (часть 6), офис (часть 7), посты и гайды (часть 8), отличия от Frisco и Plano (часть 9), вопросы и список кадров (часть 10). Сверено с источниками заново, всё совпало:

- Title, описание, H1, все H2, восемь вопросов FAQ и 1,804 слова: `source/crawl/pages/plumber-the-colony-tx.json`; дата публикации 16 мая 2025 стоит в схеме этой страницы (datePublished).
- Запросы: «plumber the colony tx» 257 · 19.89 и 2,639 · 31.19, «slab leak repair the colony tx» 156 · 7.43 и 713 · 23.0, «plumbers in the colony tx» 1 клик, 110 · 21.37 (`source/gsc/page-query-3m.csv`, `page-query-16m.csv`); итоги страниц The Colony, Frisco, Plano (`Pages.csv`); главная и Plano по запросам с the colony.
- Тексты 13 отзывов (десять кандидатов и трое живой страницы): `reviews/all-reviews.csv`, знак в знак. Никто из них и из запаса не стоит в `reviews/site-reviews.json` (перечитан в 10:47, файл от 10:04, 40 авторов на 14 страницах) и в `reviews/site-ledger.md`. Ни текст, ни ответ компании ни у одного не называют город.
- Census заново (data.census.gov, 3 октября 2026): B25035 "The Colony city, Texas" 2001, погрешность 2; B25034: до 1980 года 4,120 из 19,388 (21.3%), 2010 и позже 5,682 (29.3%).
- Официальные цитаты, каждая страница открыта один раз: "All contractors working in the City of The Colony must be registered." (https://www.thecolonytx.gov/293/Contractor-Registration); "Any plumbing repairs under the slab must be permitted and repaired by a licensed plumber." (https://www.thecolonytx.gov/DocumentCenter/View/13584/Foundation-Repair-Requirements); пункт 9 памятки "Do I need a Permit?", "REV 05/26" (https://www.thecolonytx.gov/DocumentCenter/View/14462/Do-I-Need-a-Permit).
- Фото 9, 79, 81, 95: `docs/briefs/_shared/photos-by-city-after-recount.json`; ссылки на страницу The Colony с новых страниц: пять, как в части 8.

Что поправлено при проверке (пометки «[Проверка: ...]» в тексте): в части 6.1 у строк city-d6, city-e6, city-h1, city-h5, в пункте про прейскурант и в вопросе о регистрации стоят ошибки первого прогона, которые нашла перепроверка; теперь это видно прямо в строке, а не только в начале части 6. В части 6.2 помечены вывод «старого жилья больше, чем в Плано» и доли площади по сегодняшней границе. В части 8 объяснено, почему её числа по Plano и The Colony на одну строку больше, чем в части 2 (Iowa Colony). В части 9, пункт 5, уточнено про Plano по поправке 1 брифа Plano. В части 10, вопрос 4, Austin Ranch и The Tribute больше не названы «новыми частями»: их возраст данными не проверен. Длинных тире, координат, адресов и телефонов клиентов в брифе нет (проверено поиском); телефоны в тексте это номера FPP и одной компании-конкурента в её title, адреса это офисы FPP, мэрия и почта.

## Коротко

1. Что кормит страницу. За 3 месяца (1 июля до 28 сентября 2026) 1 клик, 8,682 показа, среднее место 15.6; за 16 месяцев 3 клика, 65,244 показа, место 31.2 (`source/gsc`, Pages.csv). Единственный клик с известным запросом дал «plumbers in the colony tx». Место выросло (33.7 за 13 месяцев до июля, 15.7 за последние 3), показов в месяц стало меньше (около 4,260 против 2,630). На местах 1 до 3 страница не стоит ни по одному запросу с the colony.
2. По каким запросам. 71 процент показов с известным запросом идут по запросам со словами the colony (5,597 из 7,903 за 3 месяца, 112 запросов). Первые: «plumber the colony tx» 257 показов на месте 19.9, «plumber the colony» 214 на 19.0, «the colony plumber» 200 на 20.7, «emergency plumber the colony tx» 167 на 13.6. Лучшие места у slab leak: «slab leak repair the colony tx» 156 показов на месте 7.4.
3. Что нельзя потерять в title, H1 и описании: начало title "Plumber The Colony, TX" и начало H1 "Plumber in The Colony, TX" (только там стоят точные фразы главного ключа); слова "Drain Cleaning Services" в title (только они держат 10 запросов, 539 показов за 3 месяца, но карта ключей запрещает этой странице drain cleaning: вопрос Денису); "Licensed plumbers in The Colony" в описании.
4. Что нельзя потерять в заголовках: H2 "Slab Leak Repair in The Colony" (лучшие места страницы), "Our Plumbing Services in The Colony", "The Colony Plumbing FAQ", "Plumbing Repairs in Older and Newer The Colony Homes", имя FPP Plumbing в заголовке отзывов и слово emergency из H2 "Plumbing Emergency in The Colony?" (это единственный заголовок с emergency; вопросом по правилам не ставим, заменить один к одному).
5. Самая большая дыра: второго ключа страницы «emergency plumber the colony» в тексте нет совсем, а запросы про emergency с the colony дали 738 показов за 3 месяца и 7,687 за 16. Фраз «plumber in The Colony» и «plumbers in The Colony» в абзацах тоже нет (только в H1 и в описании).
6. Кто забирает показы: страница Plano стоит по запросам The Colony на месте 5.0 (69 запросов, 4,950 показов за 3 месяца, выше страницы The Colony по 59 из них), почти всё это новое. Главная с этих запросов почти ушла: 8,600 показов за 16 месяцев, 37 за последние 3.
7. Что на живой странице против правил: время и расстояние своими словами ("minutes from our Plano office", "usually within a couple of hours", "we are already close", "a morning call usually means hot water by evening"; на новом сайте точечно поправлено описание, две фразы убраны, ответ FAQ укорочен, остальное стоит); Plano назван пять раз (сосед, правило 7); в схеме второй бизнес "FPP Plumbing - Plumber in The Colony, TX" с адресом офиса Plano, соседи в areaServed, "Texas Master Plumber License M-44816", "North Dallas communities", priceRange "$$"; восемь вопросов FAQ тегом H3; H2 вопросом; "a bill that climbed by fifty dollars"; камера только после чистки; нет ссылки на официальный источник; в ссылках нет hose bib и expansion tank.
8. Чего на живой странице нет: улиц, районов, ориентиров, фото с работы, историй с вызовов, блока Дениса. Своего текста 1,573 слова, до отметки 2,500 не хватает около 930. Главное фото это фургон на жилой улице: на крыле "M-38532" (на сайте лицензия M-44816), на борту телефон Plano, The Colony названа только в alt.
9. Конкуренты: десять страниц из выдачи по «plumber the colony tx», «plumber in the colony», «the colony plumbing» (Semrush, 3 октября 2026). Основной текст от 632 до 1,981 слова, середина около 1,180; наша страница длиннее девяти из десяти. Самая местная Jennings: семь районов, вода, глина, возраст домов, 11 вопросов FAQ.
10. Чего нет ни у одного из десяти: PSI и места PRV, счётчика и ящика с краном, инспекции города, тоннеля и пайки под плитой, cleanout и границы участка, спринклеров, бака на чердаке, слива кондиционера в раковину, правила $49 со списанием в ремонт, ссылки на официальный источник, блока мастера. Что у них есть, а нам нельзя: tankless у всех десяти, hydro jetting у семи, repiping у пяти, financing у пяти, бесплатная оценка у четырёх.
11. Фото и клипы: после пересчёта за The Colony числятся два фото, оба по границе города, слова Дениса о городе нет. 79 (крутится счётчик) стоит главным фото на странице leak detection; 9 (новый наружный two way cleanout) нигде не стоит и свободен, но кадр 10 той же работы записан во Frisco. Работы на границе с Frisco (122, 166, 167, 178, 179, 192 до 194) это Frisco словом Дениса; 81 и 95 ушли во Frisco по границе. Фото фургона или работы в The Colony нет.
12. Отзывы: The Colony не называет ни один из 407 отзывов архива. Свободных пятизвёздочных с текстом 330, все правила проходят 145, работу называют 27. Три отзыва живой страницы (Maksym Basovskyi, Angelo Toborg, Sun Sun) свободны и проходят; Maksym остаётся на этой странице словом Дениса от 30 сентября. Свободного отзыва про slab leak нет. На новом сайте блок отзывов этой страницы пуст.
13. Официальные факты, подтверждённые двумя проходами (3 октября 2026): все подрядчики регистрируются в городе, без регистрации и лицензии разрешений не дают; разрешение нужно на водонагреватели, линии воды и канализации, душ, mixing valves, сифоны, умягчитель; без разрешения только унитаз или раковина на то же место; "Any plumbing repairs under the slab must be permitted and repaired by a licensed plumber." и письмо инженера о засыпке на финале; счётчик, curb cock и ящик принадлежат городу, после счётчика подключает только лицензированный сантехник; пересчёт счёта после течи (больше 15,000 галлонов, раз в 12 месяцев, со счётом сантехника); кодексы IPC и IRC 2024; вода из пяти своих скважин плюс покупная. Про PRV город не пишет нигде; цифры жёсткости в отчёте города противоречат друг другу (132.0 и 12.0 ppm). Адрес для одной официальной ссылки: https://www.thecolonytx.gov/293/Contractor-Registration (или памятка "Do I need a Permit?").
14. Индексы и возраст домов: у города один индекс, 75056 (99.9% жилья). Медианный год постройки жилья 2001 (±2), до 1980 года построено 21.3%, в 2010 и позже 29.3% (Census, ACS 2020-2024). Мысль живой страницы про «две эпохи» данными подтверждается; старое ядро 1970-х лежит у Paige Rd, Strickland Ave, Colony Blvd и Main St.
15. Ссылки: на сайте нет ни одной истории из The Colony (17 постов, 16 гайдов). Страница ссылается на 11 услуг из 13 (нет hose bib и expansion tank), девять страниц услуг на неё в тексте не ссылаются. Начало фразы со ссылкой на главную ("If you searched for a plumber near me") занято на других городских страницах.
16. Офис: офиса в The Colony нет, и CLAUDE.md не говорит, из какого офиса её обслуживают. Живая страница пишет "our Plano office", в её схеме адрес и телефон Plano; на новом сайте описание "served from our Plano office", на первом экране две кнопки звонка (Frisco office, Plano office), блока офиса и карты нет. Вопрос к Денису.
17. Чего не хватает для сильной страницы: диктовки Дениса про The Colony (в `source/dictation` её нет), одной или двух настоящих работ из города с фото, его слова о городе фото 9, 10, 79, 81, 95 и девяти фото галереи, ответа про офис и про "Drain Cleaning" в title, кадра фургона или работы в городе, отзыва про slab leak, выбора отзывов.

## 1. Живая страница

Файл раздела: `docs/briefs/the-colony/1-live-page.md`, вставлен целиком. Заголовок файла: «1. Живая страница The Colony: что стоит на fppplumbing.com сейчас».

Полные таблицы в бриф не вставлены, они лежат рядом: `1-live-page-tables.md` (20 КБ): ответы FAQ слово в слово (A), ссылки со страницы (B) и на страницу (C), упоминания города без ссылки (D), схема (E), повторы с другими страницами старого сайта (F), ссылки отзывов в архиве (G), два предложения про старые и новые части города (H), цитаты официальной страницы города (I).
Откуда данные. Краул старого сайта от 30 сентября 2026 (`source/crawl/pages/plumber-the-colony-tx.json` и ещё 63 страницы там же). Отзывы: файлы в `reviews/` (ведомости нового сайта перечитаны 3 октября в 10:08). Правки нового сайта: `tools/build_launch_content.py`, `site/src/data/launch-changes.csv`, `site/src/content/pages/plumber-the-colony-tx.md` (перечитан 3 октября в 10:08). 3 октября около 02:21 живая страница запрошена один раз: текст от H1 до конца отзывов совпал с краулом слово в слово.

Таблицы рядом, в `1-live-page-tables.md` (дописаны 3 октября утром, в первом прогоне файла не было): ответы FAQ (A), ссылки со страницы (B), на страницу (C), упоминания без ссылки (D), схема (E), повторы с другими городами (F), ссылки отзывов в архиве (G), два предложения про части города (H), цитаты официальной страницы города (I).

Страница https://fppplumbing.com/plumber-the-colony-tx/ : ответ 200, в page-sitemap.xml, canonical на себя, index и follow. Опубликована 16 мая 2025, правлена 17 августа 2026. По `docs/pages-plan.md` (группа 3, № 3): 8,682 показа, место 15.6, 1 клик, «Старый текст». В `seo/keyword-map.md`: ключ "plumber the colony tx", не целиться в "drain cleaning".

### 1. Title, описание, H1, заголовки, объём

- Title (60 знаков): "Plumber The Colony, TX | Slab Leak & Drain Cleaning Services"
- Описание (133 знака): "Warm spot on the floor? Drains backing up? Faucet dripping all night? Licensed plumbers in The Colony, minutes from our Plano office."
- H1: "Plumber in The Colony, TX - Slab Leaks, Drains & Everyday Repairs" (дефис на месте тире)

H2 по порядку (в скобках слов в разделе с заголовком):

1. "Slab Leak Repair in The Colony" (196)
2. "Drain Cleaning and Main Lines" (190)
3. "Faucets, Cartridges, and Shower Valves" (161)
4. "Our Plumbing Services in The Colony" (106, десять строк со ссылками)
5. "Water Heaters and the Expansion Tank Nobody Mentions" (137)
6. "Plumbing Repairs in Older and Newer The Colony Homes" (120)
7. "Plumbing Emergency in The Colony?" (104)
8. "The Colony Plumbing FAQ" (405)
9. "What The Colony Homeowners Say About FPP Plumbing" (212, отзывы)
10. "980-899-7997 469-998-8999" (не раздел: телефоны нижней панели тегом H2, шаблон)

H3: восемь, все это вопросы FAQ.

Объём: краул считает 1,804 слова (точки списка услуг он считает словами, без них 1,794). Свой текст от H1 до конца FAQ 1,573 слова (вступление 142), отзывы 212 (сами тексты 159), призыв с кнопкой 19. До 2,500 не хватает около 930 слов. Блока офиса и карты нет (правильно: офиса в городе нет).

Ключи в своём тексте: "The Colony" 11 раз; "plumber in The Colony" 1 раз, только в H1. В абзацах нет ни этой фразы, ни "The Colony plumber", ни "plumbers in The Colony" ("Licensed plumbers in The Colony" только в описании). "plumber near me" 1, "slab leak" 7, "drain cleaning" 3. По правилу городских страниц фраза с городом стоит и в тексте, и в части H2: сейчас в H2 есть город, но нет слова plumber.

### 2. Восемь вопросов FAQ

Все восемь стоят тегом H3 в раскрывающемся списке Elementor (против правила 8: вопрос это жирный текст). Ответы есть в коде обычным текстом, полностью в таблице A. Схема FAQPage совпадает со страницей слово в слово.

| № | Вопрос (H3) | Повтор на старом сайте |
|---|---|---|
| 1 | "How much does a plumber cost in The Colony, TX?" | Шаблон: на всех девяти городских с другим городом. Ответ слово в слово как на Little Elm, Prosper, Lewisville |
| 2 | "What are the first signs of a slab leak?" | Тот же на Carrollton |
| 3 | "How do I know if it is my main line and not one drain?" | Близнец на `/drain-services/`: "How do I know if it’s the main line or just one drain?" |
| 4 | "My drains keep backing up every few months. Why?" | Нет |
| 5 | "My faucet drips no matter how tight I turn it. What is that?" | Тот же на Little Elm |
| 6 | "Do you charge extra after hours?" | Шаблон: ещё на семи городских. Ответ слово в слово как на Little Elm, на Carrollton почти так же |
| 7 | "How fast can you get to The Colony?" | Шаблон: "How fast can you get to Lewisville?" |
| 8 | "Do you work with property managers and rental homes?" | Тот же на Carrollton |

Без повторов только вопрос 4. Вопросы 2 по 5 это темы сервисных страниц; про город только 1 и 7, оба шаблонные.

### 3. Три отзыва, полностью

Над ними строка "Real Google reviews from local homeowners." Все три есть в `reviews/all-reviews.csv`: Google, профиль Plano, 5 звёзд, `on_old_site` = `/plumber-the-colony-tx/`. Длинные ссылки архива в таблице G.

**Angelo Toborg.** "Came over quickly and cleared a blockage, found a cracked pipe. He came over a couple of days later and repaired the crack quickly. Highly recommend, friendly and easy to work with."
Подпись: "★★★★★ · Local Guide Level 4 · July 2026 · Google". Ссылка: https://maps.app.goo.gl/E1moWmuDEksYnS8q8?g_st=ic . Архив: 2026-07-18. Текст совпадает знак в знак, месяц совпадает.

**Maksym Basovskyi.** "I own a rental property, and a few nights ago, my tenants called me in a panic because the main drain line got clogged, and water started flooding the house. I wasn’t sure what to do at first, but I found FPP Plumbing and gave them a call. I honestly wasn’t expecting much in the middle of the night, but they showed up in about 25 minutes! They got everything under control quickly and did a great job. The price for an emergency visit at that hour was really fair. I’m definitely keeping their number for any future issues!!!"
Подпись: "★★★★★ · Local Guide Level 3 · October 2024 · Google". Ссылка: https://maps.app.goo.gl/UNpuEGvXD1GD8yvx6?g_st=ic . Архив: 2024-10-23. Текст совпадает знак в знак, месяц совпадает. "about 25 minutes" это слова клиента, по решению Дениса от 2 октября не трогаем.

**Sun Sun.** "They are really professional,every repair order they will tell you allthe details not playing game,no hide fee,I will use them for my all properties in the future,highly recommend"
Подпись: "★★★★★ · Local Guide Level 3 · November 2024 · Google". Ссылка: https://maps.app.goo.gl/Khuh6qUTNp2nZDG38?g_st=ic . Архив: 2024-11-05. Текст совпадает знак в знак (с опечатками автора), месяц совпадает.

Общее:

- На новом сайте никто из троих не стоит: в `site-ledger.md` (40 авторов) и в `site-reviews.json` (14 страниц, из городских только Frisco) этих имён нет (перечитано в 10:08), в `reviews/proposed-placement.md` тоже. Копий на Thumbtack и Yelp в архиве нет. Все трое свободны.
- Решение Дениса в `reviews/ledger-decisions.csv`: "Maksym Basovskyi,/,status,removed,Stays on /plumber-the-colony-tx/ only,Denys 2026-09-30". То есть Maksym снят с главной и оставлен за этой страницей. В шапке `proposed-placement.md` правило: "a rewritten city page keeps the reviewers it had on the old site".
- Ни один из трёх не называет The Colony; во всём архиве из 407 отзывов слова "Colony" нет ни в тексте, ни в ответе компании. "The Colony Homeowners" и "local homeowners" файлами не подтверждены. Двое из троих пишут как хозяева домов под аренду.
- Подписи без города (правило 11). Уровни Local Guide (4, 3, 3) только на старой странице, в архиве колонка пустая.
- По правилу городских страниц ближе всех Maksym Basovskyi ("FPP Plumbing", "main drain line", ночной вызов); у Angelo Toborg нет имени компании, у Sun Sun общие слова.
- В файле новой страницы метка `<!-- reviews -->`, записи для неё в `site-reviews.json` нет.

### 4. Фото

Семь тегов картинок, настоящее фото одно, и оно не с работы.

- `/wp-content/uploads/2025/05/photo_2025-05-15_20-41-47-1024x576.jpg`, alt "FPP Plumbing van outside a home in The Colony, TX": главное фото под H1 и OG картинка. Не работа.
- `/wp-content/uploads/2026/08/Maksym-Basovskyi-Google-Review.jpg` (270 на 272), alt "Google review from Maksym Basovskyi for FPP Plumbing": аватар автора отзыва.
- Остальное шаблон: логотип 2 раза (alt "FPP Plumbing Logo"), заглушка Elementor 2 раза (пустой alt, на месте аватаров), знак BBB в подвале.

Главное фото я открыл: белый фургон FPP на жилой улице, за ним кирпичные дома. На борту "EMERGENCY SERVICE 24/7", "980.899.7997", на крыле "M-38532" (не совпадает с M-44816, в проекте не объяснено). Номерного знака не видно. На доме сзади мелкая табличка с номером дома.

Что это The Colony, говорит только alt. У всех десяти городских страниц главное фото из одной пачки `photo_2025-05-15_20-41-45` ... `20-41-54` (по файлу на город, имя это время сохранения, не место). Фото с работ, видео и карты нет. На новой странице это же фото стоит главным и OG с тем же alt (копия в `site/public/wp-content/uploads/2025/05/`).

Для справки: в `photos/captions-en.csv` (city_final) за The Colony сейчас два кадра: 9 (наружный two way cleanout; помечен "ask Denys which city", кадр 10 той же работы записан во Frisco) и 79 (крутится счётчик; стоит на собранной странице leak detection). Кадры 81 и 95 после пересчёта по границам (`docs/briefs/_shared/photos-by-city-after-recount.json`) ушли во Frisco. Кадры 178 и 192 сняты на границе The Colony и Frisco, записаны во Frisco словом Дениса.

### 5. Ссылки

Со страницы (таблица B): в тексте 16 внутренних ссылок, внешних в тексте нет. "plumber near me" на `/` в последнем абзаце вступления (по правилу 6); в разделах "slab leak repair", "drain cleaning", "shower cartridge replacement", "shut-off guide", "emergency plumbing"; в списке услуг десять ссылок с названием услуги ("main line service" ведёт на `/drain-services/`). Из 13 услуг единого списка нет hose bib и "Expansion tank replacement" (`/water-heater-repair-frisco-mckinney/`; раздел про expansion tank есть, ссылки нет). На другие города ссылок нет (правильно); внешней ссылки на официальный источник тоже нет, а городской странице она нужна. Шаблон: всего 119 внутренних и 28 внешних записей.

На страницу с остальных 63 страниц (таблицы C и D). Анкоры: "The Colony" 189, "plumber in The Colony" 3, "The Colony, TX" 1, полное название страницы 1.

- Меню: "The Colony" 3 раза на каждой из 62 страниц (`/blog/author/admin/` отдаёт 301). В подвале ссылки нет.
- В тексте только на шести страницах: slab leak, leak detection, emergency (анкор "plumber in The Colony" в общем предложении с Little Elm, Carrollton и Lewisville) и списки городов на главной, `/contact/` и `/water-heater-repair-frisco-mckinney/`.
- Девять сервисных страниц в тексте на The Colony не ссылаются (список в таблице C). По правилу нужны все, анкор "plumber in The Colony". Ни один пост и ни один гид на страницу не ссылается, случая из The Colony на старом сайте нет.
- На leak detection: "across the lake to a plumber in Little Elm , a plumber in The Colony". Официальная страница города (ссылка в пункте 7): "The Colony is located in southern Denton County on the eastern edge of Lewisville Lake." Восточный берег это сторона офисов, "across the lake" к The Colony не подходит (по карте не сверял). "on the Denton County side" на slab leak с цитатой сходится.

### 6. Что идёт против CLAUDE.md, дословно

Время приезда и расстояние в своих словах:

- "The Colony sits minutes from our Plano office, which changes what same-day actually means here."
- "Not before sunset if you are lucky, but usually within a couple of hours."
- "The truck crosses this stretch constantly, so when a main line quits or a floor turns warm in the wrong spot, we are already close." (говорит, где машина)
- "Our Plano office is close enough that dispatch here is measured in minutes, not days."
- "You describe the problem to someone local, we hold a slot for you, and a licensed plumber arrives with the common parts already loaded."
- "First we clear it, because you need your house back today."
- "We keep standard units stocked, so a morning call usually means hot water by evening, with the permit and inspection handled when the city wants them."
- "Being minutes from Plano means our nights and weekends are not a promise on a website, they are a truck that actually turns around and comes back."
- FAQ 7: "How fast can you get to The Colony?" и "Faster than most, our Plano office is minutes away. Same day is the norm and it is often a couple of hours. Active flooding jumps the line." То же в схеме.
- Описание: "Licensed plumbers in The Colony, minutes from our Plano office."
- В отзывах "showed up in about 25 minutes" и "Came over quickly": слова клиентов, остаются.

Соседний город. Plano назван 4 раза в тексте и раз в описании (фразы выше), без ссылки; в схеме `areaServed` ещё Frisco, Lewisville, Carrollton. Правило 7: городская страница соседей не называет. Другое правило: страница без офиса описывает обслуживание из ближайшего офиса. Как совместить, решает Денис.

Цены и цифры:

- Цена одна и по правилу: "Weekdays it is a $49 service call, and it rolls into the job if you move forward. You hear the full price before any work starts, and the quoted price is the final price."
- "Or a bill that climbed by fifty dollars and nobody in the house did anything differently." Сумма, которую никто не давал.
- "Yes, nights and weekends carry an emergency fee that depends on the hour. You will know the exact number before we head your way." В правиле ещё праздники. В схеме `priceRange` "$$".
- Цифры без источника: "the same 10 to 15 years", "have not been turned in fifteen years", "fill valves that quit in year three", "a fifteen minute job", "a dozen versions".

Заголовки (список для сверки с Search Console, не на удаление):

- "Slab Leak Repair in The Colony": услуга плюс город. 196 слов про признаки и поиск течи это темы slab leak и leak detection (правило 9); редкая для города беда это короткий абзац со ссылкой, не в начале.
- "Drain Cleaning and Main Lines" и "Drain Cleaning Services" в title против записи в `seo/keyword-map.md`.
- "Faucets, Cartridges, and Shower Valves", "Water Heaters and the Expansion Tank Nobody Mentions" (заголовок «цепляющий»): разделы про услугу без города.
- "Plumbing Emergency in The Colony?": заголовок вопросом. Восемь вопросов FAQ тегом H3.

Остальное:

- Порядок камеры: "First we clear it... Then, if the line has a history, the camera goes down". По Денису (2 октября) камера идёт до чистки, когда линия ещё пропускает, и после, когда забита.
- Короткое тире: "Need plumbing help in The Colony? Don’t wait [en dash] text or call now. We’ll get it fixed." (в оригинале на месте пометки тире).
- Три вопроса подряд в описании. "The quiet workhorse of our Colony schedule.": город без "The".
- Слова о компании, которых нет в фактах: "We keep standard units stocked"; "Tenant coordination happens on our end, the job closes on the first visit whenever the parts allow it, and photos come back with the invoice." (в фактах: фото и видео по запросу); "we have almost certainly done your exact repair a few streets over, and the part is probably already on the truck" (слово в слово и на McKinney).
- Упрёк строителям без фактов: "the parts were chosen to pass inspection rather than to last".
- "If you searched for a plumber near me" теми же словами открывает фразу на Carrollton, Frisco, Prosper, Lewisville, McKinney (по правилу 6 фраза везде своя). Девять из десяти строк списка услуг общие с другими городами; у McKinney близнец H2 "Water Heaters and the Tank Nobody Mentions" (таблица F).
- Схема (таблица E): второй бизнес-узел "FPP Plumbing - Plumber in The Colony, TX" с адресом офиса Plano; "Texas Master Plumber License M-44816"; "North Dallas communities".
- Подвал: "all rights reserved © 2024-2026 License M - 44816".

Чего на странице нет (поиск по тексту): tankless 0, reroute 0, hydro jetting 0, гарантийных сроков 0, слова Owner 0 ("I own a rental property" это отзыв), телефонов в абзацах и FAQ 0, запрещённых городов 0, выдуманного офиса или адреса в The Colony нет.

### 7. Улицы, районы, ориентиры

Их на странице нет: ни улицы, ни района, ни ориентира, ни озера, ни шоссе, ни года постройки. Проверено поиском и чтением; в `docs/briefs/_shared/cities-official-place-names-2026-10-03.json` для The Colony `live_page_names` тоже пустой. Сверять с картой нечего.

Места названы без имён: "our Plano office" (другой город), "this stretch", "one block here", "a few streets over", "In the older sections..." и "In the newer sections..." (оба предложения целиком в таблице H). Какие части города старые и какие новые, страница не говорит. Официальная страница города https://www.thecolonytx.gov/611/Welcome-Message (3 октября 2026, сырой HTML, цитаты в таблице I): город с 1977 года, около 42,000 жителей, на восточном берегу Lewisville Lake, через город идёт Sam Rayburn Tollway (SH 121); названы Grandscape, The Cascades at The Colony, Austin Ranch, The Tribute. Осторожно: школьные округа там названы по соседним городам ("Lewisville and Little Elm ISDs"), на странице The Colony их не называть.

### 8. Точечные правки на новом сайте

В `tools/build_launch_content.py` для страницы четыре правки:

1. Описание: "minutes from our Plano office." стало "served from our Plano office."
2. Убрано: " Not before sunset if you are lucky, but usually within a couple of hours."
3. Убрано: "Our Plano office is close enough that dispatch here is measured in minutes, not days. "
4. FAQ: "Same day is the norm and it is often a couple of hours." стало "Same day is the norm."

По `launch-changes.csv` ещё три общих: H1 с двоеточием вместо дефиса ("Plumber in The Colony, TX: Slab Leaks, Drains & Everyday Repairs"); "Don’t wait: text or call now."; виджет отзывов заменён меткой. Title не менялся.

Ещё НЕ исправлено в файле новой страницы: всё из пункта 6, кроме трёх убранных фраз (ответ FAQ 7 теперь "Faster than most, our Plano office is minutes away. Same day is the norm. Active flooding jumps the line."); строка "Real Google reviews from local homeowners." стоит при пустом блоке отзывов.

### 9. Что сохранить и что не подтверждено

Вывод: местной сути на странице почти нет. Текст подойдёт любому городу, если заменить название: ни улицы, ни района, ни случая с вызова. Сохранять стоит темы, не абзацы, и после слова Дениса. Title, H1 и H2 с городом не снимаются без сверки с Search Console.

Темы:

- Близость офиса Plano: 3.0% земли The Colony лежит в индексе 75024, индексе офиса Plano (`docs/briefs/_shared/cities-official-place-names-2026-10-03.json`). Без минут и часов.
- Две эпохи домов: "Drive one block here and you can pass two different plumbing eras." Названий и годов на странице нет.
- Главная линия: "That is not four problems, it is one blocked line announcing itself through every opening it can find." Тема `/drain-services/`.
- Expansion tank: "A lot of past swaps skipped it, and without one every heating cycle quietly spikes the pressure in the whole house and wears down cartridges and fill valves." Сходится с диктовкой Дениса в CLAUDE.md.
- Аренда: вопрос FAQ про property managers и два отзыва от хозяев домов под аренду.

Не подтверждено никем:

1. Что slab leak частый вызов в The Colony (стоит первым в title, H1 и тексте), и "the other call we get constantly from The Colony" про засоры.
2. "hard water here wears them out faster than people expect" (нужен отчёт города о воде).
3. "A tank water heater in The Colony lives the same 10 to 15 years", "We keep standard units stocked", "hot water by evening".
4. Нужен ли в The Colony permit на замену водонагревателя ("when the city wants them").
5. Старые и новые части города и всё сказанное о них.
6. "Tenant coordination happens on our end", "photos come back with the invoice".
7. Что три автора отзывов из The Colony; их уровни Local Guide; что главное фото снято в The Colony.

### 10. Расхождения и вопросы Денису

- В плане страница «Старый текст», а общая правка тире уже поменяла H1 (то же в брифе Plano).
- `seo/keyword-map.md` против "Drain Cleaning Services" в title: решается по Search Console.
- Аватар из отзыва один раз скачан с живого сайта, в проект не добавлен. Цитаты с сайта города сверены по сырому HTML (curl, один запрос, 3 октября утром).

Вопросы:

1. Можно ли на странице The Colony назвать офис Plano ("served from our Plano office"), без ссылки и минут?
2. Какие вызовы в The Colony на самом деле самые частые? Часты ли там slab leaks?
3. Angelo Toborg, Maksym Basovskyi, Sun Sun: это клиенты из The Colony?
4. Где снято главное фото с фургоном? Что значит "M-38532" на нём?
5. Фото 9 (наружный cleanout): The Colony или Frisco, как у фото 10 той же работы?
6. Много ли в The Colony вызовов от хозяев домов под аренду? Правда ли фото приходят с каждым счётом?

## 2. Search Console

Файл раздела: `docs/briefs/the-colony/2-gsc.md`, вставлен целиком. Заголовок файла: «2. Search Console: страница The Colony (/plumber-the-colony-tx/)».

Длинные таблицы в бриф не вставлены, они лежат рядом: `the-colony-gsc-table-3m.md` (23 КБ, все запросы страницы за 3 месяца); `the-colony-gsc-table-16m.md` (38 КБ, все запросы страницы за 16 месяцев); `the-colony-gsc-section-tables.md` (16 КБ, длинные таблицы к разделам 2 до 7 (группы, слова в тексте, услуги)); `the-colony-gsc-headings.md` (44 КБ, что держит каждый заголовок, по запросам); `the-colony-gsc-home.md` (14 КБ, главная по запросам с the colony); `the-colony-gsc-other-pages.md` (30 КБ, другие страницы сайта по запросам с the colony); `the-colony-gsc-set-aside.md` (8 КБ, отложенные слова: чужие услуги, опечатки, чужие города). Таблица запросов с the colony по всем остальным страницам сайта стоит в части 8 (`8-links-gsc-colony-queries.md`).
Собрано 3 октября 2026. Источники (только чтение): source/gsc/page-query-3m.csv (1 июля до 28 сентября 2026) и page-query-16m.csv (31 мая 2025 до 28 сентября 2026), выгрузка API от 30 сентября; performance-3m и performance-16m/Pages.csv; page-query-coverage.csv; seo/keyword-map; seo/cannibalization-findings.md. Живая страница: source/crawl/pages/plumber-the-colony-tx.json (обход 30 сентября, правка страницы 17 августа 2026).

Три числа через точку всегда: показы · среднее место · клики (иначе сказано в шапке).

Рядом: `the-colony-gsc-table-3m.md` и `-16m.md` (все запросы), `the-colony-gsc-section-tables.md` (длинные таблицы к разделам 2 до 7), `the-colony-gsc-headings.md`, `the-colony-gsc-home.md`, `the-colony-gsc-other-pages.md`, `the-colony-gsc-set-aside.md`.

### Главное коротко

1. Кликов почти нет: со скрытыми запросами 1 клик, 8,682 показа, место 15.6 за 3 месяца; 3 клика, 65,244, место 31.2 за 16. Клик с известным запросом один: «plumbers in the colony tx».
2. Место стало лучше, показов меньше. 13 месяцев до июля 2026: 55,349 показов, место 33.7, около 4,260 в месяц. Последние 3 месяца: 7,903, место 15.7, около 2,630 в месяц. На местах 1 до 3 страница не стоит ни по одному запросу с the colony; лучшие места (6.7 до 7.4) у slab leak.
3. Главный ключ «plumber the colony tx» это запрос номер один (257 · 19.9 · 0; за 16 мес 2,639 · 31.2 · 0), точная фраза только в title. Начала "Plumber The Colony, TX" (title) и "Plumber in The Colony, TX" (H1) трогать нельзя.
4. Второго ключа «emergency plumber the colony» на странице нет совсем, а запросы про emergency с the colony это 738 показов за 3 месяца и 7,687 за 16.
5. Страница Plano забирает запросы The Colony: за 3 месяца 69 запросов, 4,950 показов, место 5.0, выше страницы The Colony по 59 из них. Почти всё это новое (4,950 из 4,987 за 16 мес). Страница The Colony получила половину всех показов сайта по запросам с the colony (5,597 из 11,166).
6. Главная с этих запросов почти ушла: 8,600 показов и 2 клика за 16 месяцев, из них 37 показов за последние 3.
7. "Drain Cleaning Services" в title одни держат 10 запросов (539 показов за 3 мес), а карта ключей запрещает странице drain cleaning. Вопрос Денису.
8. Чужие города почти не дают показов (8 за 3 месяца). Пять предложений страницы называют Plano, запросов с plano нет ни одного.

### Как считали

- Копия скриптов docs/briefs/_shared/gsc_plano_lib.py и gsc_plano_live.py под The Colony (scratchpad/night/the-colony; оригиналы и tools/gsc_page_table.py не трогались). Метод как у Plano: запрос покрыт, если каждое значимое слово стоит в живом тексте (отзывы не в счёт); in, the, tx, near, me не считаются; множественное число как единственное; чужой город, чужая услуга, оценочные слова, опечатки, голосовые слова отложены.
- Отличия: «Iowa Colony» (другой город в Техасе) считается чужим; вместо блока офиса в текст входят строка над отзывами и призыв в конце; место «the t's» внутри 27 запросов вынимается.
- Пометка «карта» (без города, место 3 и выше) у этой страницы ничего не значит: по файлам проекта карточек Google на неё нет; 176 из 178 таких показов это «fpp plumbing».
- Второй счёт: модуль csv, разбор строк без него (скрипт останавливается при расхождении) и отдельная команда Python. Совпало: 196 · 1 · 7,903 · 15.73 и 299 · 1 · 63,252 · 31.44 (запросов · клики · показы · место), как в page-query-coverage.csv. Awk дал 7,902 и 61,864, потому что режет запросы с запятой внутри ("plumber the colony, tx"): 1 строка (1 показ) и 39 строк (1,388), с ними сходится. Шесть запросов сверены руками с файлом: совпало.

### 1. Итоги за 3 и 16 месяцев

| | 3 мес | 16 мес |
|---|---|---|
| Известные запросы: запросов · клики · показы · место | 196 · 1 · 7,903 · 15.7 | 299 · 1 · 63,252 · 31.4 |
| Итог Google со скрытыми (Pages.csv): клики · показы · место | 1 · 8,682 · 15.62 | 3 · 65,244 · 31.18 |
| Доля показов с известным запросом | 91% | 97% |
| colony: запросов · клики · показы · место | 112 · 1 · 5,597 · 17.1 | 189 · 1 · 55,421 · 33.4 |
| без города | 81 · 0 · 2,121 · 13.3 | 98 · 0 · 7,169 · 18.0 |
| другой город | 1 · 0 · 8 · 27.0 | 9 · 0 · 121 · 62.2 |
| бренд (fpp) | 2 · 0 · 177 · 1.9 | 3 · 0 · 541 · 2.3 |

Запросы с the colony по месту (запросов · показы · клики), 3 мес и 16 мес: места 1 до 3: 0 и 0; 3 до 10: 11 · 556 · 0 и 2 · 13 · 0; 10 до 20: 55 · 3,473 · 0 и 35 · 3,712 · 0; 20 до 50: 46 · 1,568 · 1 и 119 · 46,568 · 1; ниже 50: 0 и 33 · 5,128 · 0.

- 13 месяцев до июля (вычитание, все запросы 3 мес есть в 16 мес): 55,349 · 33.7 · 0; с the colony 49,824, место 35.2.
- Места 3 до 10 за 3 месяца: шесть запросов slab leak (377 показов), «the colony emergency plumber» 58 · 9.2, два drain cleaning (103), два expansion tank (18).
- «near me»: 47 запросов, 919 показов за 3 мес (54 и 2,909 за 16), кликов нет; по карте это ключ главной.

### 2. Запросы страницы

Первые 20 по показам за 3 месяца (3,126 показов из 7,903, кликов нет). Группа и слова в тексте: `the-colony-gsc-section-tables.md`.

| № | Запрос | 3 мес | 16 мес |
|---|---|---|---|
| 1 | plumber the colony tx | 257 · 19.9 · 0 | 2,639 · 31.2 · 0 |
| 2 | plumber near me | 215 · 12.2 · 0 | 1,056 · 23.4 · 0 |
| 3 | plumber the colony | 214 · 19.0 · 0 | 1,944 · 25.3 · 0 |
| 4 | the colony plumber | 200 · 20.7 · 0 | 1,482 · 31.5 · 0 |
| 5 | fpp plumbing | 176 · 1.8 · 0 | 535 · 2.1 · 0 |
| 6 | emergency plumber the colony tx | 167 · 13.6 · 0 | 1,144 · 19.6 · 0 |
| 7 | plumbers the colony tx | 167 · 19.7 · 0 | 1,617 · 34.2 · 0 |
| 8 | plumber in the colony | 158 · 20.9 · 0 | 1,160 · 31.4 · 0 |
| 9 | slab leak repair the colony tx | 156 · 7.4 · 0 | 713 · 23.0 · 0 |
| 10 | the colony tx emergency plumber | 151 · 14.6 · 0 | 1,049 · 22.5 · 0 |
| 11 | emergency plumber the colony | 150 · 12.6 · 0 | 1,696 · 18.6 · 0 |
| 12 | plumbing company | 142 · 13.8 · 0 | 184 · 14.4 · 0 |
| 13 | the colony tx drain cleaning | 138 · 10.9 · 0 | 1,049 · 26.4 · 0 |
| 14 | faucet repair the colony tx | 131 · 14.7 · 0 | 1,084 · 26.7 · 0 |
| 15 | plumbers in the colony | 131 · 22.9 · 0 | 1,261 · 34.3 · 0 |
| 16 | plumber service | 118 · 12.0 · 0 | 524 · 15.0 · 0 |
| 17 | the colony sump pump repair | 115 · 23.7 · 0 | 370 · 33.8 · 0 |
| 18 | drain cleaning the colony tx | 114 · 10.4 · 0 | 874 · 30.5 · 0 |
| 19 | the colony plumber service | 114 · 19.8 · 0 | 1,052 · 30.3 · 0 |
| 20 | plumbers the colony | 112 · 19.4 · 0 | 1,122 · 31.4 · 0 |

Первые 20 за 16 месяцев (26,186 показов из 63,252, 1 клик): 14 из них стоят выше, ещё шесть: «plumbers in the colony tx» 1,498 · 31.2 · 1, «plumbers in the colony texas» 1,098 · 38.9 · 0, «the colony tx emergency plumbing» 1,072 · 22.4 · 0, «plumbing the colony» 1,069 · 34.1 · 0, «the colony tx emergency plumbers» 1,061 · 24.7 · 0, «plumber in the colony tx» 1,033 · 38.9 · 0.

Запросы с кликом: один и тот же за оба периода, «plumbers in the colony tx», 1 клик (110 · 21.4 за 3 мес).

### 3. Главная по запросам со словами the colony

Главная: 10 запросов, 37 показов, место 38.6, 0 кликов за 3 месяца; 125 запросов, 8,600 показов, место 25.1, 2 клика за 16. Общих запросов со страницей The Colony за 16 месяцев 116, главная выше по 95 (6,296 её показов). Её клики: «drain cleaning the colony tx» (324 · 1.1 · 1 за 16 мес) и «plumber in the colony tx» (51 · 51.8 · 1). Крупнее всего у главной за 16 месяцев «emergency plumber the colony» 965 · 17.2 (The Colony 1,696 · 18.6), «emergency plumber the colony tx» 850 · 17.4 (1,144 · 19.6), «the colony tx emergency plumbers» 716 · 10.0 (1,061 · 24.7); за 3 месяца по ним у главной 5, 2 и 8 показов.

Главная держала эти запросы раньше, теперь у неё единицы показов; по карте ключей она не целится в «город + plumber».

### 4. Что держит title, H1, каждый H2 и каждый вопрос FAQ

Таблица по всем заголовкам: `the-colony-gsc-section-tables.md`; по запросам: `the-colony-gsc-headings.md`. На живой странице вопросы FAQ размечены H3, на новой они жирный текст.

#### Что нельзя потерять (3 месяца, в скобках 16)

1. **"Plumber The Colony, TX" в начале title.** Только здесь точные «plumber the colony tx» 257 · 19.9 (2,639) и «plumber the colony» 214 · 19.0 (1,944): главный и вторичный ключи.
2. **"Plumber in The Colony, TX" в начале H1.** Только здесь точные «plumber in the colony» 158 · 20.9 (1,160) и «plumber in the colony tx» 98 · 22.3 (1,033).
3. **"Drain Cleaning Services" в title.** Только title держит 10 запросов, 539 показов (5,227): «the colony tx drain cleaning» 138 · 10.9, «drain cleaning the colony tx» 114 · 10.4, «drain cleaning the colony» 98 · 9.8, «the colony plumber service» 114 · 19.8, «the colony tx plumber service» 67 · 22.8. H2 "Drain Cleaning and Main Lines" без города ничего не держит. Противоречит карте ключей, вопрос 1.
4. **"Licensed plumbers in The Colony" в description.** Единственное место точной «plumbers in the colony» 131 · 22.9 (1,261).
5. **H2 "Plumbing Emergency in The Colony?".** Единственный заголовок со словом emergency; только он держит «the colony tx emergency plumbing» 73 · 11.1 (1,072) и «emergency plumbing the colony» 57 · 12.9 (469). Фразы «emergency plumber» на странице нет, хотя «emergency plumber the colony» вторичный ключ: 150 · 12.6 (1,696), «emergency plumber the colony tx» 167 · 13.6 (1,144), «the colony tx emergency plumber» 151 · 14.6 (1,049). Это дыра, которую надо закрыть.
6. **H2 "Slab Leak Repair in The Colony"**: «slab leak repair the colony tx» 156 · 7.4 (713), «slab leak repair the colony» 75 · 7.2 (591), лучшие места страницы; услуга по карте у страницы slab leak (вопрос 2).
7. **H2 "Our Plumbing Services in The Colony"**: только он держит «the colony plumbing service» 32 · 19.0 (627) и ещё 5 запросов, всего 50 показов (894).
8. **H2 "The Colony Plumbing FAQ"**: единственная точная «the colony plumbing» 7 · 16.6 (564).
9. **H2 "Plumbing Repairs in Older and Newer The Colony Homes"**: только он держит «plumbing repair the colony tx» и ещё 3, 15 показов (186).
10. **"FPP Plumbing" в H2 отзывов**: «fpp plumbing» 176 · 1.8 (535); в title имени нет.
11. **"plumber near me" во вступлении**: 215 · 12.2 (1,056), ключ главной; на новой странице это ссылка на главную (правило 6).

Ничего не держат: H2 "Drain Cleaning and Main Lines", "Faucets, Cartridges, and Shower Valves", "Water Heaters and the Expansion Tank Nobody Mentions" и семь вопросов FAQ из восьми; вопрос про цену держит те же слова, что title и H1.

### 5. Фраза целиком: первые 20 запросов и запросы с кликами

Проверены 26 запросов (первые 20 за 3 мес, первые 20 за 16 мес, запрос с кликом); таблица в `the-colony-gsc-section-tables.md`. Точная фраза стоит у 7: «plumber the colony tx» и «plumber the colony» (title), «plumber in the colony» и «plumber in the colony tx» (H1), «plumbers in the colony» (description), «plumber near me» (вступление), «fpp plumbing» (H2 отзывов). Без точной, но подряд без in и tx: 5 («plumbers the colony tx», «plumbers in the colony tx», «plumbers the colony», «plumbers in the colony texas» в title и H1; «slab leak repair the colony tx» в H2). Только с перестановкой слов: 3 («the colony plumber», «the colony tx emergency plumbing», «plumbing the colony»). Нигде: 11, среди них все четыре запроса «emergency plumber(s)» с the colony, «faucet repair the colony tx», оба «drain cleaning» с the colony и «the colony plumber service».

По всем запросам с the colony и бренду точная фраза в своих словах страницы стоит у 8 (1,041 показ за 3 мес, 9,341 за 16, кликов нет). У 106 запросов с the colony (4,732 показа, 1 клик) точной фразы нет. Крупные из них, кроме названных: «bathroom plumbing the colony» 86 · 16.9 (877), «water line repair the colony» 71 · 15.6 (867), «the colony tx pipe break repair» 99 · 13.6 (756).

### 6. Где другая страница сайта выше или забирает показы

За 3 месяца (запросов · показы · место; «выше» и «больше показов»: запросов · показы другой страницы):

| Страница | Всего | Выше The Colony | Больше показов | The Colony нет |
|---|---|---|---|---|
| /plumber-plano-tx/ | 69 · 4,950 · 5.0 | 59 · 4,867 | 11 · 4,296 | 10 · 83 |
| /plumber-frisco-tx/ | 8 · 552 · 11.6 | 6 · 324 | 4 · 434 | 1 · 1 |
| / (главная) | 10 · 37 · 38.6 | 8 · 14 | 0 | 0 |

Главные строки (другая страница, потом The Colony): «sewer line replacement the colony tx» Plano 1,816 · 5.2, The Colony 4 · 15.5; «slab leak repair the colony tx» Plano 1,709 · 6.1, Frisco 227 · 10.7, The Colony 156 · 7.4; «plumber the colony tx» Plano 360 · 4.8, Frisco 108 · 13.1, The Colony 257 · 19.9; «emergency plumber the colony tx» Plano 144 · 1.1, The Colony 167 · 13.6. Кликов у других страниц нет.

За 16 месяцев: главная 8,600 показов (выше по 95 запросам), Plano 4,987, /water-lines/ 1,931, slab leak 1,705, garbage disposal 1,191 (выше The Colony по 4 запросам), остальные меньше 1,000.

Откуда показы Plano. Карточка Google офиса Plano ведёт на /plumber-plano-tx/ (seo/cannibalization-findings.md, Денис, 30 сентября 2026). По правилу проекта карточкой считаются 41 запрос и 778 показов (место 3 и выше). Ещё 4,160 показов на местах 3 до 10, в том числе две крупнейшие строки; карточка это или обычная выдача, выгрузка не различает.

### 7. Запросы услуг с the colony и хозяева по карте ключей

Таблица по 17 группам услуг: `the-colony-gsc-section-tables.md`. Ни у одной страницы услуг в карте нет ключа с the colony; у страницы The Colony ключи «plumber the colony tx», «plumber the colony», «emergency plumber the colony» и запрет «drain cleaning (drain cleaning page)».

Страница The Colony за 3 месяца (запросов · показы · место): общие 41 · 2,743 · 20.3 (1 клик) и emergency 8 · 738 · 13.2, хозяин она сама; drain cleaning 10 · 399 · 10.9 (хозяин /clogged-drain-cleaning-frisco-plano/); slab leak 7 · 378 · 7.5 (страница slab leak); water line 4 · 311 · 15.4 (/water-lines/); faucet и shower valve 4 · 278 · 14.2 (/fixture-installation-repair/); pipe break и leak repair 3 · 225 · 14.1 (ключа нет ни у кого, ближе /water-lines/); leak detection 127, water heater 97, expansion tank 18, sewer line 17 показов. Garbage disposal и toilet только за 16 мес (1,053 и 219), hose bib и PRV запросов нет. Не наши: tankless, gas line, sump pump и прочее (266 показов за 3 мес).

Хозяева стоят ниже (за 16 мес места 27.5 до 83), поэтому запросы с городом идут на страницу города. По правилам: услуга одной строкой со ссылкой, разбор на странице услуги; название услуги с городом может стоять в H3 пункта списка частых вызовов.

### 8. Запросы с другими городами

| Город | 3 мес | 16 мес | Запросы |
|---|---|---|---|
| Iowa Colony (Техас, другой город) | 8 · 27.0 · 0 | 14 · 28.7 · 0 | plumber iowa colony tx |
| Carrollton | нет | 95 · 66.9 · 0 | same day service plumbing carrollton |
| Little Elm | нет | 8 показов, места 50 до 94 | burst pipe repair little elm; emergency plumber little elm и ещё два |
| Lewisville | нет | 2 · 32.5 · 0 | prv replacement lewisville tx |
| Allen | нет | 1 · 71.0 · 0 | same day service plumbing allen |
| Memorial City | нет | 1 · 62.0 · 0 | slab leak repair memorial city |

Причины: Iowa Colony из-за слова colony; Carrollton, Allen, Little Elm, Lewisville стоят только в меню сайта, не в тексте страницы; Memorial City на странице нет, причину не установить.

Пять предложений живой страницы называют Plano, и все про время в пути; запросов с plano у страницы нет:
- description: "Licensed plumbers in The Colony, minutes from our Plano office."
- вступление: "The Colony sits minutes from our Plano office, which changes what same-day actually means here."
- вступление: "Our Plano office is close enough that dispatch here is measured in minutes, not days."
- раздел про emergency: "Being minutes from Plano means our nights and weekends are not a promise on a website, they are a truck that actually turns around and comes back."
- ответ FAQ: "Faster than most, our Plano office is minutes away."

На новом сайте после точечных правок (site/src/content/pages/plumber-the-colony-tx.md на 3 октября) description говорит "served from our Plano office", третьего предложения нет, остальные три стоят.

### 9. Слова, которые на страницу не ставятся

Ячейки: запросов · показы · клики. Полностью: `the-colony-gsc-set-aside.md`.

| Что | Слова (показы за 16 мес) | 3 мес | 16 мес |
|---|---|---|---|
| Услуги не из списка FPP или запрещённые | sump (478), tankless (411), gas (165), commercial (83), remodeling (24), cleanup (9), septic (5), furnace (4), plomeros (3), well (2) | 17 · 274 · 0 | 27 · 1,184 · 0 |
| Опечатки | pluming (1,531), sab (585) и ещё 8 по 1 до 3 показов | 7 · 230 · 0 | 11 · 2,127 · 0 |
| Голосовые | google (231), alexa (75) | 2 · 67 · 0 | 2 · 306 · 0 |
| Оценочные и про цену | professional (33), affordable (12), free, estimate, cheap и другие | 14 · 42 · 0 | 19 · 64 · 0 |
| Чужие города | Carrollton, Iowa Colony, Little Elm, Lewisville, Allen, Memorial City | 1 · 8 · 0 | 9 · 121 · 0 |
| Чужие компании | trapp, freedom, full send | 1 · 3 · 0 | 3 · 5 · 0 |
| Служебные | site: | 1 · 1 · 0 | 2 · 6 · 0 |
| Место внутри запроса | the t's (242) | 0 | 27 · 242 · 0 |

Tankless никогда; газ только если Денис подтвердит; sump pump, septic, well, remodeling в списке услуг FPP нет (вопрос 3); commercial без своей страницы; cleanup это партнёр по сушке; других языков нет; цен кроме $49 нет.

### Что из цифр следует для брифа

1. Начала title и H1 оставить; «plumber in The Colony» и «plumbers in The Colony» поставить в текст.
2. Поставить «emergency plumber» с The Colony в заголовок и текст: второй ключ, самый крупный пропуск.
3. H2 с plumbing services и The Colony, H2 "The Colony Plumbing FAQ" и заголовок про emergency plumbing сохранить или заменить один к одному.
4. Услуги с городом (drain cleaning, faucet, water line, pipe break, slab leak): одной строкой со ссылкой, можно в H3 списка частых вызовов. Предложения с Plano и временем в пути убрать.

### Вопросы Денису

1. В title стоит "Drain Cleaning Services", а карта ключей запрещает странице The Colony drain cleaning. Только title держит 10 запросов (539 показов за 3 месяца, место около 10, кликов нет). Оставить или заменить другой услугой?
2. Как часто вы чините slab leaks именно в The Colony? Лучшие места страницы (6.7 до 7.4) у slab leak, а редкая для города проблема по правилу идёт одним коротким абзацем со ссылкой.
3. Делаете ли вы sump pump? «the colony sump pump repair» дал 115 показов за 3 месяца; без вашего ответа слова на странице не будет.
4. Указана ли The Colony в зоне обслуживания карточки Google офиса в Plano? Страница Plano стоит на местах 1 до 6 по запросам The Colony.

### Что проверить не удалось

- Отделить показы карточки Google от обычной выдачи: выгрузка не различает, правило «место 3 и выше без своего города» это договорённость проекта.
- Когда начался сдвиг (место страницы, приход Plano): разбивки страницы по дням нет.
- Что такое «the t's» в 27 запросах.
- Точные даты итогов Pages.csv («последние 3 и 16 месяцев» в интерфейсе) в Filters.csv не записаны и могут на день или два отличаться от дат API.

## 3. Конкуренты

Файл раздела: `docs/briefs/the-colony/3-competitors.md`, вставлен целиком. Заголовок файла: «3. Конкуренты по The Colony: десять страниц из выдачи».

Рядом лежат и в бриф не вставлены: `3-competitors-serp.md` (5 КБ, полная выдача, первые 30 мест по трём запросам, и сверка веб-поиском) и `3-competitors-table.md` (9 КБ, темы H2, местные факты, цены, гарантия и слова о приезде по каждой странице, с цитатами). Тексты страниц: `source/competitors/2026-10-03-the-colony/` (`00.txt` до `09.txt` это десятка, `10.txt`, `11.txt`, `12.txt` лишние, объяснено ниже; `tools/check_overlap.py` сверяет со всеми).
Дата: 3 октября 2026. Проект только читался. Новое: эта секция, полная выдача в `3-competitors-serp.md` рядом, тексты страниц в `/Users/denyskavaler/Projects/fppplumbing-site/source/competitors/2026-10-03-the-colony/`.

Про прошлый прогон. Он успел скачать страницы и сохранить 13 файлов (`00.txt` до `12.txt`), но порядок и секцию не записал. Я снял выдачу заново: порядок совпал с его файлами. Десятка это `00.txt` до `09.txt`. Файлы `10.txt`, `11.txt`, `12.txt` в десятку не входят (ниже сказано, что это), я их не удалял (удалять файлы правило не разрешает), а `tools/check_overlap.py` читает все `*.txt` папки, лишние тексты только добавляют сверку. В `09.txt` (Dean's) я дописал пять ответов FAQ и десять отзывов (правка недоделанного файла прошлого прогона): в нём были только вопросы. Прежняя версия лежит в рабочей папке: `/private/tmp/claude-501/-Users-denyskavaler-Projects-fppplumbing-site/d2b78dea-4d58-4222-812f-a40bb43eb5d1/scratchpad/night/the-colony/comp3/09.before.txt`.

### 1. Как выбраны десять страниц

Запросы: "plumber the colony tx", "plumber in the colony", "the colony plumbing".

Источники (оба сняты 3 октября 2026):

1. Semrush, обычная (не рекламная) выдача Google, база "us", последнее обновление базы, первые 30 мест по каждому запросу. По нему порядок. Дата обновления базы в ответе не указана.
2. Веб-поиск (расширенный режим), те же три запроса. Это сверка: этот поиск не Google и к городу не привязан.

Чего нет: живой выдачи Google из точки в The Colony я не снимал; блок с картой в базу Semrush не входит.

Порядок: среднее место по трём запросам, нет в первых 30 считается местом 31. Одна компания считается один раз, берётся лучшее место любой её страницы.

| № | Файл | Компания | URL | Места по Semrush: "plumber the colony tx" / "plumber in the colony" / "the colony plumbing" | Среднее | В веб-поиске (из 3) |
|---|---|---|---|---|---|---|
| 1 | 00.txt | CPR Plumbing Services | https://www.cprplumbingservices.com/ | 3 / 3 / 2 | 2,7 | 3 |
| 2 | 01.txt | Berkeys Plumbing | https://www.berkeys.com/the-colony-plumbing/ | 1 / 1 / 13 | 5,0 | 0 |
| 3 | 02.txt | Herndon McFarland Plumbing | https://www.hmcplumbing.com/about-us/areas-served/the-colony/ | 6 / 4 / 6 | 5,3 | 3 |
| 4 | 03.txt | Legacy Plumbing | https://legacyplumbing.net/service-area/the-colony/ | 5 / 5 / 9 | 6,3 | 1 |
| 5 | 04.txt | ENCO Plumbing | https://encoplumbing.com/ | 15 / 11 / 10 | 12,0 | 0 |
| 6 | 05.txt | Roto-Rooter | https://www.rotorooter.com/thecolonytx/ | 8 / 7 / нет | 15,3 | 3 |
| 7 | 06.txt | Jennings Plumbing Services | https://www.jpstx.pro/plumbing-services-the-colony-tx/ | 14 / 13 / нет | 19,3 | 3 |
| 8 | 07.txt | Reeves Family Plumbing | https://www.reevesfamilyplumbing.com/the-colony-plumber/ | 13 / 16 / нет | 20,0 | 1 |
| 9 | 08.txt | Jar-Dab Plumbing | https://www.jardabplumbing.com/ | 17 / 15 (другая страница) / нет | 21,0 | 3 |
| 10 | 09.txt | Dean's Plumbing | https://www.deansplumbingtx.com/the-colony-plumbers/ | 20 / 12 / нет | 21,0 | 1 |

Тип страниц: семь страниц города (Berkeys, Herndon McFarland, Legacy, Roto-Rooter, Jennings, Reeves, Dean's) и три главные (CPR, ENCO, Jar-Dab); у всех трёх главных город стоит в title. Jar-Dab и Dean's делят 9 и 10 место.

Лишние файлы в папке (не в десятке):
- `10.txt`: вторая страница Jar-Dab, https://www.jardabplumbing.com/near-me/the-colony-plumber (15 место по второму запросу). Одна компания считается один раз, в десятке её главная.
- `11.txt`: Cathedral Plumbing, https://www.cathedralplumbingtx.com/service-areas/the-colony-plumbing/ (4 / нет / нет, среднее 22,0, одиннадцатая).
- `12.txt`: Auger Pros, https://augerpros.com/plumbing-services-the-colony/ (11 / 25 другая страница / нет, среднее 22,3, двенадцатая; в веб-поиске 2 из 3).

Что пропущено и почему (полный список мест в `3-competitors-serp.md`):

- Каталоги, сборники, соцсети: yelp.com (места 2, 2, 7), thumbtack.com, angi.com, facebook.com (страницы CPR и Colony Heating), bbb.org, todayshomeowner.com, homeguide.com, bestplumbers.com, linkedin.com, x.com, mapquest.com.
- fppplumbing.com: /plumber-the-colony-tx/ на 22 и 23 месте, по третьему запросу в первых 30 нет. Это Semrush, не Search Console.
- http://www.thecolonyplumbing.com/ (12 / 8 / 1, среднее 7,0, была бы пятой): нет названия компании, адреса и номера лицензии; страница для сбора звонков, как plano-plumbing.com у Plano. Прошлый прогон открыл её один раз, я прочёл его копию. Не сохранена.
- Совпадение по слову Colony, другое место: colonyplumbingct.com (Connecticut), emetsplumbing.com/iowa-colony, colonyhomeservices.com (страница Round Rock), mapquest и Trane (Iowa), Yelp из Tiffin. colonyheating.com (31 / 31 / 5) я не открывал: рядом в выдаче его же Facebook, LinkedIn и X, похоже на фирму с Colony в названии; по среднему 22,3 в десятку не проходит в любом случае.
- Реже встречаются: Thorough Plumbing, 448 Plumbing, Imperial, BillyGO, Milestone, CW Service Pros, My Local Plumber, Blue Star и другие (средние от 22,3 до 30). Только в веб-поиске: calltoptech.com (1 из 3).

Запросы к страницам. Прошлый прогон: по одному запросу curl на страницу (около 02:23). Восемь страниц отдались полностью. Herndon McFarland и Dean's ответили защитой Cloudflare (403 и "Attention Required"), их текст прошлый прогон взял через WebFetch. Я сделал ещё по одному запросу WebFetch к этим двум страницам, чтобы снять заголовки, ответы FAQ и отзывы. Защиту не обходил, никакую проверку не проходил. Оговорка: WebFetch отдаёт текст через маленькую модель, мелкие расхождения со страницей возможны; меню и подвал этих двух страниц в файлы не попали.

### 2. Таблица по десяти страницам

"Основной текст": от H1 до подвала, без меню, подвала и формы, с FAQ и отзывами, если они стоят на странице. "Весь файл": весь сохранённый видимый текст. Подсчёт скриптом по файлам папки, "The Colony" без учёта регистра.

#### 2.1. Размер, слово The Colony, отзывы, FAQ

| № | Компания | Слов в основном тексте | Слов во всём файле | "The Colony" в основном / во всём | Отзывов на странице | FAQ |
|---|---|---|---|---|---|---|
| 1 | CPR | 632 | 828 | 8 / 10 | 0 | 0 |
| 2 | Berkeys | 1 276 | 1 600 | 14 / 17 | 0 | 0 |
| 3 | Herndon McFarland | 761 (без отзывов 552) | 779 (без меню и подвала) | 4 / 5 | 3, подписи "Addison" и дважды "Happy Customer", без города | 0 |
| 4 | Legacy | 968 (без отзывов 809) | 1 993 | 11 / 13 | 3, без города | 0 |
| 5 | ENCO | 1 116 (FAQ 137) | 1 692 | 8 / 13 | 0 текстов; три значка "5.0": Google, Facebook, Yelp | 3 |
| 6 | Roto-Rooter | 1 629 (без отзывов 1 304) | 1 958 | 21 / 25 (8 из 21 в блоке отзывов) | 7, каждый подписан "The Colony, TX"; в разметке даты 2012, 2022, 2023; "Rated 4.8 on Google" | 0 |
| 7 | Jennings | 1 981 (FAQ 483) | 2 214 | 42 / 45 (12 в FAQ) | 0 текстов; значок "Excellent 4.8" и "310 reviews" | 11 |
| 8 | Reeves | 1 010 | 1 293 | 7 / 9 | 0 в тексте (виджет; 3 отзыва есть только в разметке) | 0 |
| 9 | Jar-Dab | 1 443 (FAQ 460) | 1 660 | 4 / 7 | 0 | 4 |
| 10 | Dean's | 1 249 (без отзывов 773) | 1 257 (без меню и подвала) | 9 / 10 | 10, без города | 5 |

Для сравнения, наша страница /plumber-the-colony-tx/ (по `1-live-page.md`): свой текст 1 573 слова плюс отзывы 212, "The Colony" 11 раз, 8 вопросов FAQ.

#### 2.2. Title и H1 дословно

1. CPR. Title: "The Colony Plumbing Services | CPR Plumbing Services". H1 два: "Home" (хлебная крошка) и "Plumbing Services in The Colony".
2. Berkeys. Title: "The Colony Plumber 972-464-2460 Berkeys Plumbing The Colony 24-Hour Plumbing Company". H1: "The Colony Plumber".
3. Herndon McFarland. Title: "Plumber in The Colony, TX" (по выдаче веб-поиска; сам тег не снят). H1: "Plumber in The Colony, TX".
4. Legacy. Title: "Plumbing Repair Experts in The Colony, TX | Schedule Now". H1 два: "Experienced Plumbers in Colony, Texas" и "Local Plumbing Experts in The Colony, TX".
5. ENCO. Title: "Trusted Home Services in The Colony, TX". H1 два: "Full-Service Residential & Commercial Plumbing" и "Service Across North Texas".
6. Roto-Rooter. Title: "Plumber in The Colony, TX - 24/7 Plumbing Services | Roto-Rooter". H1: "The Colony Plumbing, Drain & Water Cleanup Services".
7. Jennings. Title: "Plumber in The Colony, TX | Jennings Plumbing Services". H1: "Trusted Plumbing Services in The Colony, TX".
8. Reeves. Title: "The Colony Plumber - Reeves Family Plumbing". H1: "Safe, Reliable Plumbing & Drain Cleaning in The Colony".
9. Jar-Dab. Title: "The Colony Plumber | Plumbing Services The Colony, TX". H1: "Fast, Quality Solutions for All Your Plumbing Needs in the Colony and Surrounding Areas".
10. Dean's. Title: "Plumbers in The Colony, TX - Dean's Plumbing". H1: "Plumbers in The Colony, TX".

#### 2.3. Темы H2, местные факты, цены, гарантия, приезд

Полная таблица по каждой странице (темы H2, местные факты, цены, гарантия, приезд, всё с цитатами): `3-competitors-table.md` рядом. Коротко, какие местные факты страница действительно даёт:

1. CPR: адрес офиса в самом городе (Bradford Place, 75056), единственный из десяти; строка "Air Conditioner Condensation Drain Cleaning" в списке услуг. Больше ничего.
2. Berkeys: индекс 75056 один раз, "over 35 years ... in The Colony", общая фраза про разрешения. Текст на 97% совпадает с их страницей Plano (сверка восьмисловными кусками после замены названия города).
3. Herndon McFarland: ничего местного; офис в Addison.
4. Legacy: районы Austin Ranch, Stewart Peninsula, Ridgepointe, Castle Hills; "older houses and modern residences"; шесть названий недавних работ без подробностей.
5. ENCO: только общие слова про плиты, грунт, городскую воду и "permit scheduling"; адреса нет.
6. Roto-Rooter: 11 округов и подписи "The Colony, TX" под отзывами; своих фактов нет.
7. Jennings: самая местная. Семь районов (The Tribute, Austin Ranch, Stewart Peninsula, Legends, Old Colony, Eastvale, Sunset Pointe), Grandscape, Nebraska Furniture Mart, SH 121, FM 423, Lewisville Lake, вода "Dallas Water Utilities" (их слова), глина Denton County, первые дома конца 1970-х, медь и чугун "40 to 45 years old", PEX в новых, полив у фундамента.
8. Reeves: мороз, срок водонагревателя "up to 10 years"; относит город к "Dallas County" (у Jennings Denton County; сверить в разделе 6a).
9. Jar-Dab: о городе ничего; адрес компании в Forestburg.
10. Dean's: "City by the Lake", берег Lewisville Lake, первые кварталы 1970-х и 80-х, "master planned"; что ломается в старых домах (закисшие краны, свищи, засоры); один рассказ о работе у The Tribute.

Сводка:

- Свои цены в цифрах даёт одна страница (ENCO). Купоны и скидки ещё у трёх (Legacy, Roto-Rooter, Jar-Dab) и клубная скидка у Berkeys.
- Срок гарантии называют двое: Herndon McFarland (год на работу по установкам) и ENCO (три года на работу по акции водонагревателя). У Plano не называл никто.
- Время приезда в минутах или часах своими словами не обещает никто; ближе всех Jennings ("just minutes away"). "Same day" своими словами у Jennings и Dean's.
- Ссылок на официальные источники (сайт города, TSBPE, EPA, водоканал) нет ни на одной из восьми страниц, где я видел код; у Herndon McFarland и Dean's код не снят.
- Что пишут конкуренты и чего нельзя нам: tankless у всех десяти; hydro jetting у семи в меню или тексте (CPR, Berkeys, ENCO, Roto-Rooter, Jennings, Reeves, Dean's); repiping у пяти в меню или тексте (Berkeys, Herndon McFarland, Legacy, Reeves, Dean's); бесплатная оценка у четырёх (Jennings, Reeves, Jar-Dab, ENCO); бесплатное второе мнение у Legacy и ENCO; проверку и ремонт обратного клапана предлагает Jennings ("We test, certify, and repair backflow assemblies"), у нас про это только одно разрешённое предложение.

### 3. Какие местные факты не называет никто

Проверено поиском слов по десяти сохранённым текстам (`00.txt` до `09.txt`). Если факт есть в лишних файлах, это сказано.

1. Давление воды в цифрах. "PSI" нет ни у кого. Редуктор давления только пунктом меню у Legacy. Где он стоит в домах The Colony, сколько показывает манометр, не пишет никто.
2. Счётчик и ящик с краном. "valve box", "water meter", "meter box" нет ни у кого ("meter" только как влагомер у Roto-Rooter и "meter testing" у ENCO). Где главный кран и как по счётчику понять утечку, никто не объясняет.
3. Разрешение и инспекция. Только общие фразы у Berkeys и ENCO. "inspector", "city inspection", фразы "City of The Colony" нет ни у кого; ссылки на сайт города нет ни у кого. Наша страница с одной ссылкой на официальный источник будет единственной.
4. Ремонт под плитой. "tunnel", "braze", "post-tension" нет ни у кого из десяти. Slab leak у всех общими словами (признаки, глина). Подкоп под дом и справку инженера описывает только Auger Pros в лишнем `12.txt`.
5. Канализация до города. "property line", "city side", "cleanout" нет ни у кого (у ENCO "clean out" только в условии купона). "smoke test" нет ни у кого из десяти; у Auger Pros (`12.txt`) он стоит строкой в списке услуг.
6. Полив. "sprinkler" нет ни у кого. "irrigation" только у Jennings (полив у фундамента, проверка обратных клапанов). Про замену узла с разрешением и проверкой города не пишет никто.
7. Водонагреватель на чердаке, поддон, слив из поддона. "attic" только в меню Berkeys (утепление). Поддон одной фразой у Dean's ("with proper pans").
8. Расширительный бак. Одна строка у Legacy и упоминание у Jennings; зачем он и сколько служит, никто не объясняет.
9. Мороз. Общими словами у Jennings, Reeves, Herndon McFarland, Dean's. Что именно лопается в домах The Colony и что уличный кран зимой только закрывают чехлом, не пишет никто.
10. Сток кондиционера, врезанный в слив раковины. "condensate" нет ни у кого; у CPR одна строка в списке услуг без объяснения.
11. Хлор и резиновые детали. "chlorine", "chloramine" нет ни у кого.
12. Жёсткость воды в цифрах. "ppm", "gpg", "grains" нет ни у кого; Jennings пишет "hard" без цифры.
13. Настоящие вызовы в городе. Один рассказ у Dean's (The Tribute, угловые краны), у Legacy только шесть названий работ. Больше нет ни у кого.
14. Правило оплаты вызова. Никто не объясняет, сколько стоит вызов и что сумма засчитывается в ремонт. Наше правило ($49 в будни, засчитывается в ремонт, цена до начала работ) в такой форме не стоит ни у кого.
15. Главный кран дома. "main shut-off" нет ни у кого; Dean's пишет только о кранах под раковиной и унитазом.
16. Человек с лицом. Ни на одной из десяти страниц (по сохранённым текстам) нет блока о мастере; в подвалах номер лицензии, иногда имя держателя (у Jennings одна строка о владельце).

Что уже занято и нашим не будет: названия районов (Jennings семь, Legacy четыре), Lewisville Lake и "City by the Lake" (Jennings, Dean's; у Auger Pros в `12.txt` тоже), источник воды (Jennings; нам слово Dallas отдельно писать нельзя, как писать про воду, сказано в `6a-official-city.md`), глина (Jennings, у ENCO общими словами), возраст первых кварталов и материалы по годам (Jennings, Dean's), Grandscape и Nebraska Furniture Mart (Jennings; NFM ещё у Auger Pros), рассказ о работе у The Tribute (Dean's).

Важно: всё выше говорит только о том, чего нет у конкурентов. Факты для нашей страницы должны прийти от Дениса или с официальных страниц; здесь я их не проверял и не утверждаю.

### 4. Структура: длина, разделы, FAQ

Длина основного текста по возрастанию: 632, 761, 968, 1 010, 1 116, 1 249, 1 276, 1 443, 1 629, 1 981 слово. Середина около 1 180, среднее 1 207. Наша нынешняя страница (около 1 785 со своими отзывами) длиннее девяти из десяти, длиннее только Jennings. Цель в 2 500 слов ставит нас выше всех.

Три типа страниц:

- Шаблон "список услуг" (Berkeys, Herndon McFarland, Legacy, Reeves, Jar-Dab, CPR): H1, вступление, по абзацу на услугу, призыв позвонить, список городов. Местных фактов нет или одна фраза.
- Местная страница (Jennings, Dean's): блок "проблемы города" с глиной, водой и возрастом домов, районы, FAQ про город. Самые сильные по содержанию.
- Сетевая страница (Roto-Rooter, ENCO): много общих разделов (затопление, акции), город вставлен в заголовки.

Что почти у всех: значки доверия в первом экране (licensed, insured, 24/7), "почему мы", список соседних городов, акции или рассрочка (financing у пяти: Berkeys, Legacy, ENCO, Roto-Rooter, Reeves).

FAQ есть на четырёх страницах, всего 23 вопроса. У Jennings и Jar-Dab вопросы стоят тегами H3, у ENCO и Dean's не заголовками. У Jennings разметка FAQPage несёт 4 вопроса, два из них на странице не стоят. Вопросы дословно:

ENCO (3):
- "What general plumbing services does Enco Plumbing provide?"
- "When should I call a professional plumber?"
- "Can regular plumbing maintenance help prevent repairs?"

Jennings (11):
- "What plumbing services do you offer in The Colony?"
- "Do you offer water heater repair near me in The Colony?"
- "Do you work on lakefront homes in The Tribute?"
- "How do I know if I have a slab leak?"
- "Is The Colony's water hard?"
- "Do you offer emergency plumbing in The Colony?"
- "Why do older Colony homes have frequent plumbing problems?"
- "How often should I have my drains cleaned?"
- "Do you service my The Colony neighborhood?"
- "Can I text you photos of my plumbing problem?"
- "Are your plumbers licensed and insured?"

Jar-Dab (4):
- "What Type Of Water Heater Is Best For My Property?"
- "Why Is Drain Cleaning From a Plumber Better Than Store-Bought Chemicals?"
- "How Quickly Do I Need To Schedule Service If I Find A Leak?"
- "What Are The Common Reasons For Sewer Clogs?"

Dean's (5):
- "My home in The Colony was built in the early 80s. What usually fails first?"
- "Can you replace seized shutoff valves under sinks and toilets?"
- "Do you serve the newer lakeside communities too?"
- "Do you offer emergency plumbing in The Colony?"
- "Should I replace my original water heater before it fails?"

Вопрос "Do you offer emergency plumbing in The Colony?" стоит слово в слово у двух (Jennings, Dean's): нам его не брать. "How do I know if I have a slab leak?" у Jennings близок к нашему "What are the first signs of a slab leak?". Для сведения: в лишнем `12.txt` у Auger Pros пять вопросов, четыре из них про COVID.

### 5. Шаблоны title и H1

Title (дословно в 2.2):

- Город стоит во всех десяти, ", TX" в семи (нет у CPR, Berkeys, Reeves).
- Три начала повторяются: "Plumber in The Colony, TX" (Herndon McFarland, Roto-Rooter, Jennings), "The Colony Plumber" (Berkeys, Reeves, Jar-Dab), "Plumbers in The Colony, TX" (Dean's). Слово plumber или plumbers в семи title; только "Plumbing" у CPR и Legacy, "Home Services" у ENCO.
- Телефон в title только у Berkeys. Обещаний в title почти нет: "24/7" у Roto-Rooter, "24-Hour" у Berkeys, "Schedule Now" у Legacy.
- Наш нынешний title "Plumber The Colony, TX | Slab Leak & Drain Cleaning Services" единственный, где названы конкретные услуги; у остальных только общее "Plumbing Services" или ничего.

H1:

- Город в H1 у девяти (нет у ENCO; у Jar-Dab "the Colony" с маленькой буквы, у Legacy в одном H1 "Colony, Texas" без The).
- Слово plumber или plumbers в H1 только у четырёх (Berkeys, Herndon McFarland, Legacy, Dean's); остальные строят H1 на "Plumbing Services", "Plumbing Experts", "Drain Cleaning".
- Два H1 на странице у трёх (CPR, Legacy, ENCO).
- Город в H2: у Jennings в 7 из 15, у Roto-Rooter в 5 из 6 (не считая H2 с адресом в шапке), у Legacy и Dean's по 3, у CPR 1, у Berkeys в единственной H2 (повтор названия); у Herndon McFarland, ENCO, Reeves и Jar-Dab ни в одной.

Вывод для брифа: формула "Plumber in The Colony, TX" в title и H1 стоит у сильнейших страниц (Herndon McFarland, Roto-Rooter, Jennings), и наш H1 "Plumber in The Colony, TX - Slab Leaks, Drains & Everyday Repairs" с ней совпадает. Отличаться нужно не заголовком, а тем, чего нет ни у кого из пункта 3.

## 4. Фото и клипы

Источник: `docs/briefs/_shared/photos-by-city-after-recount.json` (204 записи архива: 143 фото и 61 видео; прочитан 3 октября 2026). Город «после пересчёта» в этом файле поставлен по границе города (basis "city boundary"), по слову Дениса (basis "Denys's word"), оставлен как был ("as before") или снят, если место съёмки вне десяти городов. Слово Дениса о городе работы главнее проверки по карте. Координат в файле нет, и в брифе их нет. Сверено с `docs/briefs/_shared/cities-free-photos-2026-10-03.md` (строка The Colony: 2 файла, свободен 9) и с частью 8 (раздел 1).

После пересчёта за The Colony числятся 2 файла, оба фото, оба по границе города; слова Дениса о городе нет ни у одного. Видео за The Colony нет.

### 4.1. Все файлы, у которых город после пересчёта The Colony

Колонка «Что сказал Денис» дана как в файле, по-русски. Подпись дана как в файле, по-английски. «Отложено для» это колонка planned_pages. «Пометки» это колонка flags, слово в слово. У обоих город до пересчёта тоже был The Colony.

| № | Вид | Дата | Основание города | Что сказал Денис | Подпись (англ.) | Где стоит на собранном сайте | Отложено для | Пометки |
|---|---|---|---|---|---|---|---|---|
| 9 | фото | 2026-04-15 | city boundary | Замена наружного two way cleanout на дренажной линии | New outside two way cleanout on the drain line, The Colony | нигде | /drain-services/ /plumber-the-colony-tx/ | Same job as 10 but city_final differs (9 The Colony, 10 Frisco, both near a border): ask Denys which city. |
| 79 | фото | 2026-04-08 | city boundary | Крутящийся счетчик: где-то утечка | Spinning meter: a leak somewhere, The Colony | /water-leak-detection-frisco-plano/ (главное фото страницы, alt "Water meter with the leak indicator turning, leak detection, The Colony", по части 8) | /water-leak-detection-frisco-plano/ /plumber-the-colony-tx/ /plumbing-guide/why-is-my-water-bill-so-high-frisco-tx/ | Meter maker's phone number on the dial; fine. |

Что видно по таблице:

- Свободен для страницы The Colony один кадр, 9. Фото 79 уже стоит главным на странице leak detection; правила не запрещают одному фото стоять на двух страницах (фото 95 стоит на главной и на странице expansion tank), но город у него только по границе.
- Фото 9 и 10 одна работа: 9 новый наружный cleanout (15 апреля 2026), 10 старый, сломанный, уже вынутый ("The same cleanout, broken, already pulled out, Frisco", 16 апреля 2026, город Frisco по границе). В столбце `city` файла `photos/captions.csv` у фото 9 стоит Plano (в `city_final` The Colony, по границе). Три разных города у одной работы: решает Денис. Если работа в The Colony, история «сломанный cleanout» по правилу CLAUDE.md сначала показывает проблему (10), потом ремонт (9).
- Фото 79 записано и в план гайда `/plumbing-guide/why-is-my-water-bill-so-high-frisco-tx/`, где история из Frisco (течёт унитаз): подпись не должна выдавать фото за ту работу (часть 8, раздел 1.1). Что нашли на этом вызове, в архиве не записано.
- Не для The Colony, хотя связаны с ней по месту съёмки или по прежней записи:
  - работы на границе The Colony и Frisco, город Frisco словом Дениса (2 октября 2026): видео 122, фото 166, видео 167, видео 179 (корни в дренажной линии, главная линия у фундамента), фото 178 (линия к уличному крану лопнула в мороз в стене гаража), фото 192, 193, 194 (гвоздь от полки в трубе). 122, 166, 167, 178, 179, 192, 193 стоят на странице Frisco, 194 нигде;
  - фото 81 ("PRV and secondary shutoff valve replaced", 12 апреля 2026) и 95 ("T&P valve replaced on a water heater", 19 декабря 2024): раньше записаны за The Colony, после пересчёта по границе Frisco; слова Дениса нет. 81 нигде не стоит, 95 стоит на главной и на странице expansion tank (`/water-heater-repair-frisco-mckinney/`). В подписях обоих в файле до сих пор стоит "The Colony".
- Вне этого файла: главное фото живой страницы (фургон на жилой улице, `/wp-content/uploads/2025/05/photo_2025-05-15_20-41-47-1024x576.jpg`, alt "FPP Plumbing van outside a home in The Colony, TX"). В архиве этого кадра нет; город подтверждает только alt. И девять старых фото галереи с "The Colony, TX" в alt (`/wp-content/uploads/2024/12/photo_2024-12-24_18-50-31.jpg` и дальше, список в части 8, раздел 1.2): их нет в `photos/index.csv`, место съёмки никто не проверял.
- Фото фургона в архиве: 1, 2, 3, 4 у офиса Frisco (слово Дениса) и 202 у офиса Plano (сборное фото). По пометкам файла фото 2 и 4 Денис 1 октября разрешил ставить вместо фото с работы на страницах Celina и Lewisville ("stand in for Celina and Lewisville until job photos from there"). Для The Colony такого слова нет.

### 4.2. Кандидаты по темам страницы

Темы взяты из живой страницы (часть 1), из запросов (часть 2) и из того, чего нет у конкурентов (часть 3). Правила из CLAUDE.md: история, названная по проблеме, сначала показывает проблему, потом ремонт; клип режется до пяти секунд, без звука, крутится сам; все картинки одного размера, 3:4; номер дома и номерной знак в кадре закрываются; фото, снятое в другом месте, на страницу города не идёт, пока Денис не назовёт работу.

| Тема страницы | Файлы | Что с ними делать |
|---|---|---|
| Первый экран: фургон или работа в The Colony | нет | Нынешнее фото фургона городом не подтверждено, на крыле "M-38532", на борту телефон Plano. Нужен настоящий кадр (4.3). Ставить ли пока фото 2 или 4 (фургон у офиса Frisco), как для Celina и Lewisville, решает Денис |
| Slab leak (первое в title, H1 и первом H2; лучшие места страницы, 378 показов за 3 месяца) | нет | Ни одного кадра из The Colony. Клип 165 (вода из-под фундамента) это Little Elm словом Дениса, сюда не идёт. На странице города slab leak одним коротким абзацем со ссылкой, если Денис скажет, что это редкость |
| Главная линия, засоры, cleanout (слова Drain Cleaning в title, H2 "Drain Cleaning and Main Lines") | 9 (и 10, если Денис назовёт город) | Пара «сломанный cleanout, потом новый» для короткой истории или для строки про sewer line со ссылкой на `/drain-services/`. Только после слова Дениса о городе |
| Скрытая течь, высокий счёт, счётчик (вопрос FAQ про признаки slab leak, строка "Hidden leaks and climbing bills") | 79 | Кадр уже стоит на странице leak detection. На странице The Colony только с подтверждением города и с тем, что нашли в итоге (вопрос в части 10) |
| Смесители, картриджи, клапан душа (H2 "Faucets, Cartridges, and Shower Valves"; запрос «faucet repair the colony tx» 131 показ) | нет | Ни одного кадра из The Colony |
| Водонагреватель и расширительный бак (H2 про expansion tank; памятка города про водонагреватель) | нет | Фото 95 (T&P клапан) по границе Frisco, на странице The Colony только если Денис назовёт город |
| Давление и PRV (строка "Pressure too high or too low"; город про PRV не пишет) | нет | Фото 81 (PRV и второй запорный кран) по границе Frisco, то же условие |
| Emergency, ночные вызовы (второй ключ страницы, 738 показов за 3 месяца) | нет | Ни одного кадра из The Colony |
| Старые и новые дома (H2 "Plumbing Repairs in Older and Newer The Colony Homes") | нет | Ни одного кадра из The Colony |
| Дома под аренду (вопрос FAQ про property managers) | нет | Ни одного кадра |
| Девять фото галереи с The Colony в alt (кран холодильника на ProPress, течь в стене, линия к backflow preventer, кухонная раковина, линия в гараже, ручка смыва коммерческого унитаза, фланец унитаза) | вне архива | Только после слова Дениса, что это The Colony. На фото с backflow preventer чинили линию к узлу, не узел (часть 8, раздел 1.2) |

В архиве есть 37 файлов без города (22 фото и 15 клипов; сняты вне десяти городов или город не определён), среди них по темам этой страницы есть кадры (картридж Moen 25, водонагреватель Bradford White 28, пайка под фундаментом 45 и 162). Как кандидаты для страницы The Colony они не предлагаются: на странице города стоят работы из этого города (на странице Frisco все фото Frisco), а у этих файлов города нет.

### 4.3. Чего не хватает: какие кадры просить у Дениса

1. Настоящее фото с работы в The Colony или фургон FPP на улице в черте города. Кадр вертикальный, чтобы встал в размер 3:4; без номеров домов; номерной знак мы размоем. Это замена нынешнему главному фото.
2. Если работа с cleanout (9 и 10) была в The Colony: ещё кадр той же работы пошире (яма, линия, новый cleanout на месте) или кадр с экрана камеры.
3. Что нашли на вызове с крутящимся счётчиком (79), если это The Colony: место течи, вскрытый участок или прибор на полу.
4. Работа slab leak в The Colony, если такая была: яма доступа или тоннель, пинхол на меди, спаянное место. Без своего кадра эта тема на странице только строкой со ссылкой.
5. Водонагреватель в гараже или на чердаке в The Colony, «до» и «после»: поддон, слив поддона и T&P наружу или аварийный клапан отсечки воды, кран на холодной воде, расширительный бак. Это ровно то, что перечисляет памятка города (часть 6, city-b3).
6. Манометр на уличном кране дома в The Colony с цифрой давления и PRV там, где он стоит в этих домах.
7. Ящик счётчика: кран города у счётчика и отдельный кран хозяина на участке. Закон города говорит, что кран у счётчика не заменяет кран хозяина (часть 6, city-d4).
8. Картридж или клапан душа с работы в The Colony, «до» и «после».
9. Работа в доме 1970-х годов в старой части города (Paige Rd, Strickland Ave, Colony Blvd, Main St), если такая была: старые краны, чугун, медь.

## 5. Отзывы: кандидаты

Файл раздела: `docs/briefs/the-colony/5-review-candidates.md`, вставлен целиком. Заголовок файла: «5. Отзывы: кандидаты для страницы The Colony».

Длинные списки в бриф не вставлены, они лежат рядом: `5-review-candidates-tables.md` (14 КБ, части А до Е: запас, работы, кого отсеяли и почему, полные тексты трёх отзывов живой страницы).
Раздел для брифа страницы `/plumber-the-colony-tx/`. На страницы ничего не поставлено, ни один файл проекта не изменён. Журналы отзывов нового сайта этой ночью пересобирают: `reviews/site-reviews.json` прочитан 3 октября 2026 в 10:11 (файл от 10:04), `reviews/site-ledger.md` тогда же (файл от 04:54). Перед выбором их нужно прочитать ещё раз. Длинные списки лежат рядом, в `5-review-candidates-tables.md`.

### Коротко

- Отзывов, которые называют The Colony, её улицу, район или индекс: **0** (ни свободных, ни занятых, ни в ответах компании).
- Поэтому все десять кандидатов без места и **не привязаны к этому городу**: их могут предложить и другим городам, а стоять отзыв может только на одной странице.
- Свободных пятизвёздочных отзывов с текстом: **330**. Все правила проходят **145**, что именно делали, называют **27** из них.
- Три отзыва живой страницы (Angelo Toborg, Maksym Basovskyi, Sun Sun) свободны и правила проходят все трое, с пометками. Про Maksym Basovskyi уже есть слово Дениса от 30 сентября: «Stays on /plumber-the-colony-tx/ only» (`reviews/ledger-decisions.csv`).
- Первый раздел живой страницы, slab leak, отзывом не закрыть: свободных отзывов про течь под фундаментом нет ни одного. Про главную канализационную линию чистый отзыв в архиве один, и это Maksym Basovskyi с этой же страницы.

### Откуда данные

- `reviews/all-reviews.csv`: 407 отзывов (Google 131: профиль Plano 105, профиль Frisco 26; Thumbtack 249; Yelp 27). Кто занят: `reviews/site-reviews.json` и `reviews/site-ledger.md` (40 авторов на 14 страницах, страницы The Colony нет), три резерва главной из задания. Старый сайт и решения: `reviews/ledger.md`, `reviews/ledger-decisions.csv`, `reviews/proposed-placement.csv`, `docs/state.md`, `docs/reviews-proposal.md`.
- Живая страница: `source/crawl/pages/plumber-the-colony-tx.json` и раздел 3 файла `1-live-page.md`. Новая: `site/src/content/pages/plumber-the-colony-tx.md` (метка `<!-- reviews -->`, отзывов нет).
- Тексты кандидатов Google и трёх отзывов живой страницы сверены с Google Takeout (`source/gbp-takeout/`): знак в знак, пять звёзд, даты те же. Thumbtack и Yelp сверены с `reviews/raw/`. Вживую ни один отзыв не открывался.

### The Colony в отзывах: ноль

Искал "Colony", четыре названия с официальной страницы города (Austin Ranch, The Cascades at The Colony, The Tribute, Grandscape), индексы 75056 и 75036 и несколько своих ориентиров во всех 407 строках архива, в `reviews/raw/` и в отзывах Google Takeout (список слов: файл таблиц, часть Д). Совпадений нет. Это сходится с `docs/cities-table-2026-10-03.md`: The Colony не названа ни в одном отзыве архива.

Вывод: заголовок новой страницы "What The Colony Homeowners Say About FPP Plumbing" и строка "Real Google reviews from local homeowners." файлами не подтверждаются. Был ли кто-то из авторов из The Colony, знает только Денис.

### Сколько свободно и сколько чистых

| Шаг | Сколько |
|---|---|
| Всего отзывов в архиве | 407 |
| Из них пять звёзд | 396 |
| Минус 6 без текста и 10 копий отзывов Google, показанных на Thumbtack (копия и оригинал один человек, кандидат только оригинал) | 380 |
| Минус 47 строк занятых авторов (43 человека: 40 на новом сайте, у Kathryn Kim, Stephan S, Yuliia Novoderezhkina и tony phuong по две строки Google; плюс три резерва главной) | 333 |
| Минус 3 строки: тот же человек под другим именем (L W это Liane W.; Rani C это Rani .; Lanessa A. на Yelp это Lanessa Arnold Jenkins) | **330 свободных** |

Из 330: Thumbtack 227, Google профиль Plano 69, Yelp 19, Google профиль Frisco 15. The Colony не называет ни один.

Трое из 330 это авторы живой страницы The Colony, их судят отдельно (ниже). Из остальных 327 правила кандидата отсеивают 182 строки (одна строка может попасть в несколько причин):

- имя Дениса в тексте (Denys, Dennis, Denis, Denyes, Deny, Denny, Dany, Danny, Dennys, Dnys, Denise): 156;
- автор стоит на городской или служебной странице старого сайта, которая оставляет своих: 26 (Plano 5, Celina 3, Prosper 3, Lewisville 3, PRV 2, Carrollton 2, Allen 2, Little Elm 2, McKinney 2, water heater repair 1, Frisco 1);
- ответ компании под отзывом называет другой город: 22 (только по этой причине трое: Marina Sexton, Shashi, Abhishek Pooja);
- суммы денег, слово fee или charge: 20;
- назван другой город или место в нём (Plano, "Shops at Legacy", Frisco, "Frisco Lakes", Prosper, Carrollton, McKinney, "North Dallas"): 14;
- слова "plumber near me" (Денис снимал такие 1 и 2 октября): 8;
- придержаны для другой страницы: 5 (Ann Crawford, две строки, expansion tank; Steve Fredrickson, water heaters, и его же Steve F. на Yelp; Quan Nguyen, запас hose bib и живая страница Little Elm).

Подробности, а также трое свободных со старой главной и старой Frisco (Eric Wickstrom, Kathryn Michelle, Vic Jones) и двое возвращённых в чистые (Dale Q. и Camrin C.: слово charged без суммы): файл таблиц, часть Г.

Остаётся **145 чистых**: Thumbtack 116, Google профиль Plano 21, Yelp 7, Google профиль Frisco 1. Большинство короткие и общие ("Great job"). Что делали, называют 27: файл таблиц, часть Б.

### Десять лучших кандидатов

Места не называет ни один, поэтому порядок: сила слов о работе и о компании (plumber, FPP Plumbing, названная работа), потом близость к разделам живой страницы (скрытые течи, засоры, смесители и картриджи душа, водонагреватель, срочные вызовы, FAQ "the quoted price is the final price"), потом разные работы в наборе. **Все десять не привязаны к The Colony.** Текст дословный, с опечатками автора.

| # | Имя | Площадка, профиль | Дата | Работа | Текст дословно | Ссылка | Почему |
|---|---|---|---|---|---|---|---|
| 1 | Dr. Jalal Jalali | Google, Plano | 2025-07-08 (July 2025) | замена крана стиральной машины | "I called several plumber for replacement of a washer machine valve and this FPP plumbing  compony was the only  one that his price was a lot reasonable than the others. He came the same day in less than an hour. Very professional i highly recommend them and I will use them again for any pluming work." | [отзыв](https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sCi9DQUlRQUNvZENodHljRjlvT2xOTFpEQlVhbmxvY0ZoRk4wSTNhbGc0Um10WmJrRRAB!2m1!1s0x0:0xccc66184bdaf3a93) | "plumber" и "FPP plumbing", работа названа, цена без сумм. Цифра приезда: "in less than an hour". |
| 2 | Kevin N. | Thumbtack, Plano | 2023-01-04 (January 2023) | течь из ванной наверху, вода через светильник на кухне и стены гаража | "These guys are life savers. I had a leak in an upstairs bathroom and water was coming out of my light fixture in the kitchen as well as down the walls in my garage. They came out the same day I contacted them and were able to diagnosis and fix the issue. I would and will be contacting them for any other plumbing work that I have." | [листинг](https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760) | Живая картина скрытой течи, нашли и починили. Без цифр и денег. Старый. |
| 3 | Eric H. | Thumbtack, Plano | 2023-02-25 (February 2023) | сломанный shower valve заменён | "Quick and easy! Fixed my broken shower valve - able to get the replacement from the local HD and then they were done!" | [листинг](https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760) | Ровно тема раздела "Faucets, Cartridges, and Shower Valves". Короткий, нет слова plumber. |
| 4 | Dale Q. | Thumbtack, Plano | 2024-09-17 (September 2024) | в тексте нет; в заявке Thumbtack "Leaking pipes • Toilet • House" | "On time, cared about fixing the issue. Charged exactly what he had said it would cost up front...." | [листинг](https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760) | Слова клиента подтверждают правило: цена до работы и не меняется. Среди чистых Thumbtack 2024 и 2025 почти все из общих слов, здесь есть конкретика. |
| 5 | Javeed N. | Thumbtack, Plano | 2022-11-06 (November 2022) | течь, которую трудно найти (заявка: "Leaking pipes • House") | "Response was immediate. They were able to troubleshoot a water leak that was hard to find. Very nice and pleasant to work with." | [листинг](https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760) | Ближе всех к разделу slab leak. Был в первом предложении для leak detection, заменён на Oksana Toporina. Старый. |
| 6 | alex p | Google, Plano | 2025-01-11 (January 2025) | нет горячей воды в снежную бурю | "FPP Plumbing provided exceptional service! They quickly responded to our call, arrived promptly, and fixed the issue fast when we had no hot water in this winter snow storm. Their team was professional, efficient, and thorough. Whether it’s plumbing repairs, drain cleaning, or water heater installation, FPP Plumbing delivers top-quality solutions. Highly recommend for reliable, quick, and expert plumbing services." | [отзыв](https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sChdDSUhNMG9nS0VJQ0FnSURmel9Qamh3RRAB!2m1!1s0x0:0xccc66184bdaf3a93) | Единственный чистый про горячую воду, дважды "FPP Plumbing". Вторая половина звучит как реклама. |
| 7 | Margo W. | Thumbtack, Plano | 2023-08-29 (August 2023) | большой засор (заявка: "Clogged toilet or drain • Flooding • Bathroom") | "I received same day service for a major plumbing clog at a very fair price. I was very happy with the service and the work that was done. Highly recommend!!" | [листинг](https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760) | Тема раздела про засоры. "same day" без цифры, цена без суммы. Старый. |
| 8 | David H. | Thumbtack, Plano | 2023-01-05 (January 2023) | течь смесителя душа, лопнувшая труба снаружи | "Was able to fit us in the same day and correctly fix the issues (leaking shower faucet and exterior broken pipe) and answer all questions. Will plan to use again for future plumbing needs" | [листинг](https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760) | Две работы, одна из раздела про смесители. Без цифр и денег. Старый. |
| 9 | Jaime D. | Yelp, Plano | 2023-11-21 (November 2023) | вечерний вызов в праздничную неделю, работа не названа | "We had a plumbing issue later in the evening and FPP was not only very quick to respond, but they also arrived within an hour during a holiday week. They were able to fully resolve our issue in an efficient and thorough manner. They were very professional, let us know what the problem was and there were no surprises from what was quoted. I hope we don't have any more problems, but if we do I would not hesitate to call them again. Highly recommend" | [листинг](https://www.yelp.com/biz/fpp-plumbing-plano-2) | "no surprises from what was quoted" под FAQ про цену; вечер и праздник под раздел срочных вызовов. Цифра приезда: "within an hour". |
| 10 | Lily Chaskelmann | Google, Plano | 2024-11-14 (November 2024) | течь (общо), обращались дважды | "Excellent plumber. We've used FPP Plumbing twice already. Fixed everything we needed fixed and at reasonable prices. Explained everything really well before repairing. Most recently we had a leak and he showed up within 30 minutes!" | [отзыв](https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sChZDSUhNMG9nS0VJQ0FnSUQzbHJIRmRBEAE!2m1!1s0x0:0xccc66184bdaf3a93) | "Excellent plumber" и "FPP Plumbing", объяснили до ремонта. Цифра приезда: "within 30 minutes". |

Ссылки Google ведут на сам отзыв (из архива, вживую не открывались); у Yelp и Thumbtack отдельной ссылки нет, ведут на листинг. Заявка Thumbtack (поле details в `reviews/raw/thumbtack-reviews.json`) это анкета клиента, не текст отзыва: её не цитируют, она только помогает понять работу.

#### Оговорки

1. **Пересечение с другими городами** (брифы Plano, Little Elm и Lewisville, прочитаны 3 октября в 10:20). Dr. Jalal Jalali: Plano 4 и четвёрка Plano, Little Elm 1. Kevin N.: десятки всех трёх, четвёрка Little Elm и Lewisville. alex p и Lily Chaskelmann: десятки всех трёх, четвёрка Little Elm. Javeed N.: Lewisville 1 и четвёрка Lewisville, запас Plano и Little Elm. David H.: Little Elm 6, Lewisville 5, запас Plano. Eric H.: Lewisville 6, запас Little Elm. Jaime D.: Plano 10, Little Elm 9. Margo W.: запас Plano и Little Elm. Нигде нет только Dale Q. Распределять нужно по всем брифам сразу.
2. **Цифра приезда** есть у трёх: Dr. Jalal Jalali, Jaime D., Lily Chaskelmann (и у Maksym Basovskyi с живой страницы). Это слова клиентов, они разрешены, но аудитор их отметит.
3. **Local Guide** у кандидатов Google в архиве не записан; читают в профиле при живой проверке. Подпись по правилу 11 без города.
4. **Thumbtack.** Шесть из десяти; все, кроме Dale Q., 2022 и 2023 годов.
5. **David H.** В архиве есть David Harbour (Google, 4 звезды, июль 2026): совпадают имя и первая буква фамилии, отмечено на случай, если это один человек.
6. **Строка над отзывами** в файле новой страницы: "Real Google reviews from local homeowners." С отзывом Thumbtack или Yelp слова "Google reviews" станут неправдой; "local homeowners" не подтверждено ни для кого.

#### Если выбирать сейчас

Предложение, выбор за другим чатом и за Денисом: оставить Maksym Basovskyi (главная линия ночью, дом под аренду; слово Дениса 30 сентября) и Angelo Toborg (засор, треснувшая труба) с живой страницы; добавить Dale Q. (цена как договорились; его нет ни в одном другом брифе) или Eric H. (shower valve; его нет ни в одной предложенной четвёрке); Sun Sun оставить, если Денис держит все три старых отзыва (вопрос FAQ про дома под аренду). Четыре разные работы. С Eric H. или Dale Q. строку "Real Google reviews" придётся поменять.

### Запас за десяткой

Чистые, но короче или слабее (тексты и ссылки: файл таблиц, часть А; все без места): Michael V., Stacie B., Phillip Potter, Gorden C., Matt M., Ryan E., Sathya P., Rangsan L., A P, Kevin C., Alecia K., Laura B.

### Три отзыва живой страницы

Все три есть в выгрузке Google (профиль Plano, пять звёзд), тексты на старом сайте совпадают с Google знак в знак (сверено в `1-live-page.md`, раздел 3, и здесь ещё раз с Takeout). Города нет ни в текстах, ни в ответах компании. На новом сайте ни один не стоит, в резерве главной их нет.

| Имя | Дата в Google | Свободен | Имя Дениса | Деньги, жалобы, комиссия | Работа | Цифра приезда | Итог по правилам |
|---|---|---|---|---|---|---|---|
| [Maksym Basovskyi](https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sChdDSUhNMG9nS0VJQ0FnSURYMEotUWl3RRAB!2m1!1s0x0:0xccc66184bdaf3a93) | 2024-10-23 (October 2024) | да | нет | суммы нет; "The price for an emergency visit at that hour was really fair" (похвала) | засор главной линии ночью, вода в доме, дом под аренду | ДА: "in about 25 minutes" | **Проходит.** Слово Дениса 30 сентября: остаётся на The Colony. Единственный чистый отзыв архива про главную линию. |
| [Angelo Toborg](https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sCi9DQUlRQUNvZENodHljRjlvT25ScmJXZG9TblpRY1RWdWNrbGpaRWw1VVhFeGEwRRAB!2m1!1s0x0:0xccc66184bdaf3a93) | 2026-07-18 (July 2026) | да | нет ("He came over", имени нет) | нет | засор прочищен, найдена треснувшая труба, починена через пару дней | нет ("Came over quickly") | **Проходит.** Нет слова plumber и названия компании. |
| [Sun Sun](https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sChdDSUhNMG9nS0VJQ0FnSUMzcnVMMHZRRRAB!2m1!1s0x0:0xccc66184bdaf3a93) | 2024-11-05 (November 2024) | да | нет | "no hide fee": это похвала за отсутствие скрытых платежей, не комиссия за карту и не жалоба | не названа; автор держит несколько домов ("my all properties") | нет | **Проходит с пометкой**: слово fee стоит в тексте. Общие слова, опечатки автора. |

Полные тексты с прямыми ссылками: файл таблиц, часть Е (и `1-live-page.md`, раздел 3).

Что ещё видно по этим трём:

- Старый сайт ставил короткие ссылки maps.app.goo.gl; в архиве есть прямые (в именах выше). Ставить прямые.
- Подписи по правилу 11 без города. Уровни Local Guide на живой странице (Angelo Toborg 4, Maksym Basovskyi 3, Sun Sun 3) в архиве не записаны: перед постановкой их читают в профиле.
- Двое из трёх (Maksym Basovskyi, Sun Sun) пишут как хозяева домов под аренду. Других чистых свободных отзывов от таких хозяев в архиве нет (часть В). Для вопроса FAQ "Do you work with property managers and rental homes?" эти два единственные.

### Каких работ среди кандидатов нет

Поиск слов по всем 330 свободным отзывам. Имена и причины в файле таблиц, часть В.

| Работа (раздел живой страницы) | Свободных | Чистых |
|---|---|---|
| Slab leak, течь под фундаментом (первый раздел) | 0 | 0; ближе всех Javeed N. ("a water leak that was hard to find") |
| Главная линия, камера, корни (второй раздел) | 4 | 0, кроме Maksym Basovskyi с этой страницы |
| Водонагреватель | 11 | 1 (alex p, без замены) |
| Расширительный бак | 2 | 0 |
| PRV, давление воды | 5 | 0 |
| Водопровод во дворе, счётчик | 10 | 0 |
| Хозяева домов под аренду (вопрос FAQ) | 3 | 0, кроме Maksym Basovskyi и Sun Sun с этой страницы |
| Газ, backflow, спринклеры | 1 (газ) | 0 |

Мешают имя Дениса, другой город, "near me" и места на других старых страницах; оба отзыва про slab leak стоят на странице slab leak. Кто именно: файл таблиц, часть В.

Среди чистых есть: смесители и душ (Eric H., David H., Mohit D., Marcus K., Rangsan L.), засоры и сливы (Margo W., Gorden C., Lauren M., Shirley S., Laura B.), унитаз (Ryan E.), измельчитель (Sathya P., Rangsan L.), уличные краны и труба снаружи (Stacie B., Michael V., David H.), вызовы ночью, вечером и в выходные (9). Почти всё это Thumbtack 2022 и 2023 годов.

Отзывы со словами "plumber near me" закрыли бы часть пробелов (Mohaimen Kadhim: водонагреватель на чердаке и инспекция; funny warner f: расширительный бак; Inna Kravchenko: PRV и течь во дворе; Сергей Кравченко: главная линия и камера), но Денис такие снимал 1 и 2 октября. В десятку они не включены.

### После выбора

- Заново прочитать `reviews/site-reviews.json` и `reviews/site-ledger.md`: автора мог занять другой город.
- Сверить каждый текст на площадке слово в слово (Google по прямой ссылке, Yelp со входа Дениса, Thumbtack на листинге), прочитать уровень Local Guide.
- Записать выбранных в `reviews/proposed-placement.csv` и пересобрать журнал (чат, который ставит страницу); поправить `reviews_intro`, если будет не Google.

### Вопросы Денису

1. Ни один отзыв не называет The Colony. Помните ли вы, у кого из авторов работа была в The Colony (из трёх с живой страницы или из десятки)?
2. Заголовок "What The Colony Homeowners Say About FPP Plumbing" и строка "Real Google reviews from local homeowners.": оставляем или ставим нейтральные? Двое из трёх нынешних авторов хозяева домов под аренду, а не жильцы.
3. Три отзыва живой страницы: оставляем все три? У Sun Sun в тексте "no hide fee" (похвала, не комиссия за карту), это можно?
4. Отзывы со словами "plumber near me" для The Colony по-прежнему не берём, как на Frisco? Только они закрывают водонагреватель, расширительный бак и PRV.
5. Про slab leak, главный раздел страницы, свободного отзыва нет совсем. Есть ли клиент с такой работой, которого можно попросить оставить отзыв?

## 6. Официальные факты

Четыре файла из `docs/briefs/the-colony/`: два файла фактов (`6a-official-city.md`, `6b-zip-and-age.md`) и две независимые перепроверки (`6a-official-city-verified.md`, `6b-zip-and-age-verified.md`). Все четыре вставлены целиком, заголовки внутри опущены на два уровня. Порядок: сначала списки «что можно брать» и «чего нельзя» из двух проверок (6.0), потом два файла фактов (6.1 и 6.2), потом остальное из проверок: таблицы сверки и новые источники (6.3 и 6.4).

Рядом лежат и в бриф не вставлены: `6a-official-city-quotes.md` (26 КБ, полные цитаты по каждому пункту), `6b-zip-and-age-tables.md` (19 КБ, таблицы Census и USPS T1 до T9 и полный список источников), папки `work-6a/` (тексты источников S01 до S27 и картинка таблицы жёсткости) и `work-6b/` (выписки и расчёты).

Важно: файлы фактов (6.1 и 6.2) писались до перепроверки. Где они расходятся со списками 6.0 и с таблицами проверки (6.3 и 6.4), верить проверке. Не подтверждено шесть строк, и вот где правильно:

- city-b15: цифры платы за разрешение верные, но новый прейскурант на сайте города уже есть: "FY 2027 Master Fee Schedule", "October 01, 2026 - September 30, 2027", с теми же цифрами. Слова файла фактов «нового нет» (и в его разделе «Что нельзя переносить», пункт 2) неверны.
- city-d6: реестр линий воды пересчитан: 14,726 линий, хозяйская часть "After 2014" 2,369, материал "Non-Lead" 8,334 (в файле фактов 14,724, 2,367 и 8,332). Округлённо: около 14,700 линий, все без свинца, примерно у 6,800 хозяйская часть проложена до 1989 года.
- city-e6: постоянного правила о пересчёте канализации после течи нет, но был разовый случай: рассылка города от 19 февраля 2021 года после зимних бурь (февраль не брали в усреднение, платы за разрешения на ремонт порывов сняли).
- city-h1: город пишет "drip each faucet one drip per second", слова «внутренние» у города нет; добровольцы не городские ("Next Steps The Colony"). Совет про краны в доме идёт словами Дениса.
- city-h5: страницы про PRV у города нет, но давление в сети город описывал: план водоснабжения 2010 года, "typically between 50 and 80 psi". Только с годом и только рядом с советом Дениса мерить давление раз в год.
- zip-a9: форма почты USPS "Cities by ZIP Code" не открылась ни у первого помощника, ни у проверки; какие названия города почта принимает для 75056 и 75036, не известно.

Ещё: доли площади по сегодняшней границе города (84,2%, 13,1% и другие в 6.2) проверка не пересчитывала. Вопрос раздела 6a о регистрации FPP в The Colony закрыт словом Дениса от 3 октября (часть 10).

### 6.0. Проверенные списки: что можно брать и чего нельзя

#### Город (из `6a-official-city-verified.md`): Можно брать в бриф (подтверждено, правила сайта не нарушает)

Ссылаться на город, официальный источник с датой проверки 3 октября 2026.

- city-a1, a2, a4, a5, a6, a7: регистрация подрядчиков, разрешения не дают без регистрации и лицензии. Для страницы: "we are registered with the City of The Colony" (это совпадает с правилом CLAUDE.md, что FPP зарегистрирован в каждом городе). Ссылка для внешнего источника: thecolonytx.gov/293/Contractor-Registration.
- city-a3: с сантехников годовой платы за регистрацию нет (знание для автора).
- city-b1, b2, b4, b5, b8, b10, b12, b13: на что нужен permit. Самое сильное для страницы: "Any plumbing repairs under the slab must be permitted and repaired by a licensed plumber." и "replacing a toilet or a sink going right back in the same location does not require a permit".
- city-b3: что смотрит инспектор у водонагревателя (18 дюймов, поддон с точной формулировкой, слив и T&P наружу на 6 до 24 дюймов или "emergency water shut off device", полнопроходной кран на холодной). Аварийный клапан отсечки воды FPP ставит, это хорошая связка со страницей водонагревателей.
- city-b6, b9, b11: отсутствие (для автора: про PRV и тест при ремонте фундамента ничего городского не цитировать).
- city-c1, c2, c3, c4, c5, c7, c8: как идёт инспекция. Для страницы годится одной фразой без часов и обещаний срока.
- city-d1, d2, d3, d4, d5: кто за что отвечает. Для страницы: город не обслуживает линии к дому, счётчик и ящик принадлежат городу, после счётчика работает только лицензированный сантехник. Своих слов "до счётчика город, дальше вы" городу не приписывать.
- city-e1, e2 (с точной формулировкой про 90 дней), e3, e4, e5: пересчёт счёта после течи и зимнее усреднение канализации. e3 хорошо ложится на правило "every invoice describes the work".
- city-f3, f6 (без имён соседних городов и озёр), f7.
- city-g1, g2, g3: кодексы 2024 года и местные поправки (обе даты вступления называть нельзя как одну; лучше "the 2024 codes the city adopted in 2025").
- city-h2, h4, h8.

#### Город (из `6a-official-city-verified.md`): Можно только с оговоркой

- city-b7, city-h3 (обратный клапан на поливе): знание для автора. На странице только одна разрешённая фраза из CLAUDE.md: "Once the new assembly is in, it gets tested and the test report goes to the city." Не писать, что мы тестируем, не называть тестера и компанию для отчётов, не называть $53 и $75.
- city-b15, city-c6, city-e4 (суммы города): цифры верные и в FY 2027 те же, но это платы города, а не наши цены. На странице лучше без сумм, чтобы читатель не принял их за цену FPP (правило: никаких цен, кроме $49).
- city-f1, city-f2, city-f4 (жёсткость): цифры в отчёте есть, но противоречат друг другу (132.0 против 12.0 у той же воды). Писать "вода в The Colony жёсткая" или "мягкая" по этим цифрам нельзя без слова Дениса. В f4 нельзя называть город-поставщика: можно только "a small part of Austin Ranch gets purchased water".
- city-h5 в исправленном виде: "50 to 80 psi" есть только в документе 2010 года. Если брать, то с годом ("the city's 2010 water master plan"), и только вместе с советом Дениса мерить давление раз в год.
- city-h6: факт про аварийную линию города годится, номера города на нашу страницу не ставить.
- city-h7: фаза засухи меняется, только с датой.
- city-e6 в исправленном виде: история 2021 года, не правило; писать только как прошлый случай с датой.

#### Город (из `6a-official-city-verified.md`): Нельзя брать

- city-d6 в цифрах первого помощника (14,724, 2,367, 8,332): брать мои цифры из таблицы выше, а лучше округлённо ("about 14,700 service lines, all listed as non-lead; on about 6,800 of them the homeowner's side was put in before 1989").
- city-b15, часть "нового прейскуранта на сайте нет": неверно, FY 2027 уже висит.
- city-e6 в формулировке "город не пишет": есть рассылка 2021 года.
- city-h1 в формулировке "город советует капать внутренние краны" и "добровольцы города": город так не пишет. Совет Дениса про внутренние краны идёт его словами, не как слова города.
- city-h5 в формулировке "город не называет давление в сети": есть документ 2010 года.
- city-b14 (газ) на странице: FPP газом не занимается без слова Дениса.
- Имена из отчёта о воде (Dallas Water Utilities, соседний город-поставщик, озёра Lewisville, Grapevine и другие) и телефоны города: на нашей странице запрещены правилами CLAUDE.md.

#### Индексы и возраст домов (из `6b-zip-and-age-verified.md`): Можно использовать в брифе

Все с источником и датой проверки 3 октября 2026.

1. Почтовый индекс The Colony один: 75056. Так пишет свой адрес сам город ("6053 Main Street The Colony, Texas 75056", https://www.thecolonytx.gov/), и это единственный индекс отделения THE COLONY в файле USPS (https://postalpro.usps.com/ZIP_Locale_Detail, файл от 10/01/2026). Индекса только для абонентских ящиков у The Colony нет.
2. По переписи 2020 года 18 800 из 18 814 единиц жилья города (99,9%) стоят в индексе 75056 (Census, файлы 2020 года, расчет по кварталам; итог 18 814 совпадает с таблицей переписи DECENNIALPL2020.H1).
3. Медианный год постройки жилья в The Colony: 2001, погрешность ±2 (U.S. Census Bureau, ACS 2020-2024, таблица B25035, "The Colony city, Texas"; ссылка для читателя https://data.census.gov/table/ACSDT5Y2024.B25035?g=160XX00US4872530 ). Это единственная цифра возраста, которую можно ставить на страницу как "возраст домов The Colony".
4. До 1980 года построено 21,3% жилья города, в 2010 году и позже 29,3%; до 2000 года 46,9%, с 2000 года 53,1% (B25034, тот же выпуск). Это подтверждает мысль живой страницы о старых и новых частях города.
5. Домов на одну семью (вместе с таунхаусами) в городе 13 774 из 18 591 занятых единиц; из них 3 713 (27,0%) построены до 1980 года (B25127). Больше половины из них, 2 103, в двух участках переписи 215.20 и 215.21.
6. Для ориентира автору, не как цифра на страницу: старые участки 215.20 и 215.21 (медианы 1976 и 1977) лежат у Paige Rd, Strickland Ave, N и S Colony Blvd, Main St (FM 423); новая застройка 2010-х в основном квартиры у State Hwy 121, Plano Pkwy (216.55, 216.47). Улицы определены по карте Census, это расчет, а не готовый текст источника.
7. Для автора: индекс 75056 общий с соседними землями, в черте города только 66,9% его жилья (перепись 2020). Поэтому медиана по индексу 75056 (2006) не годится как возраст домов The Colony.

#### Индексы и возраст домов (из `6b-zip-and-age-verified.md`): Нельзя использовать

1. Какие названия города почта принимает для 75056 и 75036 (zip-a9): форма USPS не открылась ни у первого помощника, ни у меня. Факта нет.
2. Медианы и доли по индексам 75036, 75024, 75034, 75093 как "возраст домов The Colony": это земля Frisco и Plano, жилья The Colony там 14 единиц из 18 814. Медиана индекса 75056 (2006) тоже не про город целиком.
3. Медиану участка 215.34 (2014) как цифру про The Colony: четверть его жилья вне черты города.
4. Любые сравнения с Frisco и Plano на странице The Colony и любые названия соседей из таблиц (Lewisville, Hebron, Carrollton, Frisco, Plano, Hackberry, Little Elm, Dallas): правило CLAUDE.md, страница города соседей не называет. Цифры сравнения верны, но только для сведения автора.
5. Утверждение "больше старого жилья, чем в Плано" как твердый вывод: разница почти в пределах погрешности опроса.
6. Слова "one block" из живой страницы как проверенный факт: статистика этого не проверяет, решает Денис по своему опыту.
7. Цифры площади и положение кусков по сегодняшней границе города (84,2%, 13,1% и другие из файла 6b): я их не проверял, это расчет первого помощника.

### 6.1. Факты города (файл `6a-official-city.md`)

Заголовок файла: «6a, часть первая. Официальные факты города Зе Колони (The Colony)».

Проверено 3 октября 2026 года. Источники только официальные: сайт города thecolonytx.gov и его хранилище документов (DocumentCenter), форма города в FormCenter, портал инспекций tcol-trk.aspgov.com (на него ссылается город), свод законов города на library.municode.com/tx/the_colony (на него ссылается страница города "Adopted Codes & Ordinances"). Сайт поставщика воды не открывал: город сам пишет, откуда вода (пункт f).

Как читать: английский текст в кавычках, это слова города слово в слово. Русский текст, это мой пересказ. Если город чего-то не пишет, так и сказано: not_on_official_page. Ничего не придумано.

Рядом лежат:
- `6a-official-city-quotes.md`: длинные цитаты по каждому пункту, полностью.
- `work-6a/`: тексты всех прочитанных документов (файлы S01 ... S27, номер файла равен номеру источника), чтобы автор страницы мог сверить любую цитату. Картинка `S20-...-secondary-table.png`: таблица жёсткости из отчёта о воде, снята с самого PDF.

#### Сводная таблица

| id | Вопрос | Что говорит город, коротко | Статус | Источник |
|---|---|---|---|---|
| city-a1 | Нужна ли регистрация | Все подрядчики, работающие в городе, регистрируются; бланк, права, лицензия | found | S1 |
| city-a2 | Что требуют от сантехника | Plumbing Contractor отмечен звёздочкой: копия лицензии штата и прав, список людей, кто берёт разрешения | found | S2 |
| city-a3 | Плата | $75 в год только для General Contractor; с тех, кому нужна лицензия штата (сантехники), годовой платы нет | found | S2, S27 |
| city-a4 | Срок и продление | Расходятся: страница "один год с даты оплаты", бланк "на срок лицензии", закон "истекает ежегодно" | found | S1, S2, S4 |
| city-a5 | Закон о регистрации | Без регистрации работать незаконно; штраф равен плате; ответ города за 10 рабочих дней | found | S4 |
| city-a6 | Без регистрации или лицензии | Разрешения не выдают | found | S2 |
| city-a7 | Хозяин дома сам | Может сам делать сантехнику только в своём доме с homestead, разрешение всё равно нужно | found | S1, S5 |
| city-b1 | Общее правило | Разрешение нужно и на ремонт сантехнических систем | found | S3 |
| city-b2 | Замена водонагревателя | Разрешение нужно, подрядчик зарегистрирован в городе | found | S5, S6 |
| city-b3 | Что смотрит инспектор у водонагревателя | Памятка: 18 дюймов в гараже, поддон, слив поддона и T&P или аварийный клапан отсечки воды, кран на холодной воде | found | S6 |
| city-b4 | Линия воды от счётчика до дома | Разрешение нужно ("water and sewer line repairs"), отдельно "от счётчика до дома" город не пишет | found | S5 |
| city-b5 | Канализационная линия | Разрешение нужно; про точечный ремонт отдельных слов нет | found | S5 |
| city-b6 | Замена редуктора давления (PRV) | PRV не назван ни в одном документе города | not_on_official_page | S5, S27 |
| city-b7 | Обратный клапан на поливе | Разрешение "Backflow Repair / Replacement Permit"; тест после установки, переноса, ремонта, тестером штата | found | S5, S27, S17, S13 |
| city-b8 | Ремонт под плитой | "Any plumbing repairs under the slab must be permitted and repaired by a licensed plumber." | found | S7 |
| city-b9 | Тест труб до и после ремонта фундамента | Ремонт фундамента с разрешением с 1 октября 2025, про тест сантехники ни слова | not_on_official_page | S3, S7 |
| city-b10 | Список работ без разрешения | Одна фраза: унитаз или раковина на то же место без разрешения | found | S5 |
| city-b11 | Список без разрешения в законе | Поправка к R105.2 перечисляет только два строительных пункта, сантехники там нет | found | S15 |
| city-b12 | Душ, смеситель, сифон | Душ, mixing valves, p-traps, поддоны душа, переделка ванны: разрешение нужно | found | S5 |
| city-b13 | Умягчитель воды | Установка и ремонт: сантехническое разрешение | found | S5 |
| city-b14 | Газ | Любая работа с газом: сантехническое разрешение | found | S5 |
| city-b15 | Плата за разрешение | $10 на каждую $1,000 стоимости, минимум $100; без разрешения плата вдвое | found | S27, S3 |
| city-c1 | Как назначить инспекцию | eTRAKiT, телефон, почта | found | S3 |
| city-c2 | Отсечка | Заявка до 4 p.m., инспекция на следующий рабочий день | found | S6, S8 |
| city-c3 | Отмена | Два правила: звонок с 7:00 до 8:00 утра, или в портале до 4:00 PM накануне | found | S8, S9 |
| city-c4 | Портал | Заявка до 14 дней вперёд, у каждого вида инспекций дневной лимит, это только "REQUEST" | found | S9 |
| city-c5 | Часы инспекций | Monday - Friday, 7 a.m. - 4 p.m. | found | S3 |
| city-c6 | Срочные и повторные | Тот же день $50 в час, после часов $100, праздник $200 (до 2 часов), повторная $75 | found | S27 |
| city-c7 | Время приезда инспектора | Можно попросить ETA в заявке, инспектор постарается | found | S6 |
| city-c8 | Закрывать до инспекции | Нельзя закрывать работу до одобрения | found | S8 |
| city-d1 | Чья линия | Город не отвечает за обслуживание линий воды и канализации к дому, это хозяин | found | S16 |
| city-d2 | Чей счётчик | Счётчик, curb cock, задвижки, ящик счётчика: собственность города | found | S16 |
| city-d3 | Кто подключает после счётчика | Только сантехник с лицензией штата; кран у счётчика вернуть как был | found | S16 |
| city-d4 | Граница простыми словами | Фразы "город до счётчика, дальше хозяин" нет; в реестре линий есть "System-Owned" и "Customer-Owned Portion" | not_on_official_page | S16, S28 |
| city-d5 | Граница по канализации | Простыми словами нет; есть только "City provided 4” SDR clean-out" для новых домов | not_on_official_page | S8 |
| city-d6 | Реестр линий воды | 14,724 линий, все "Non-Lead"; у 6,785 часть хозяина проложена "Before 1989" [Проверка: в файле 14,726 линий; 6,785 верно; см. 6.3] | found | S28 |
| city-e1 | Пересчёт счёта после течи | Да, форма "Leak Adjustment Request" для жилых занятых домов | found | S25 |
| city-e2 | Условия | 90 дней, раз в 12 месяцев, больше 15,000 галлонов, сверх этого по нижнему тарифу | found | S25 |
| city-e3 | Что прикладывают | Счёт с названием компании, адресом и телефоном; проверка счётчика городом | found | S25 |
| city-e4 | Проверка на течь от города | 3 бесплатные за 6 месяцев, дальше $25 | found | S19 |
| city-e5 | Канализация по зиме | Плата за канализацию на год считается по счетам декабрь - март | found | S21 |
| city-e6 | Пересчёт канализации после течи | Город об этом не пишет [Проверка: постоянного правила нет, но был разовый случай, рассылка города от 19 февраля 2021 года; см. 6.3] | not_on_official_page | S25, S21 |
| city-f1 | Жёсткость, цифра 1 | "Hardness, Calcium/Magnesium": среднее 132.0, разброс 0 - 132.0, ppm, проба 2025 | found | S20 |
| city-f2 | Жёсткость, цифра 2 | "Total Hardness as CaCO3 (ppm)": 12.0, проба 2024. С цифрой 1 не сходится | found | S20 |
| city-f3 | Остальная таблица | Calcium 25.24, Magnesium 2.491, Sodium 96.4, TDS 915.0, Alkalinity 319.0, pH 8.6 | found | S20 |
| city-f4 | Вода из Плейно (часть Austin Ranch) | Total Hardness до 200, разброс 96.0 - 200; у закупки из DWU: "Information was not provided" | found | S20 |
| city-f5 | grains per gallon | В отчёте такой единицы нет | not_on_official_page | S20 |
| city-f6 | Откуда вода | 5 своих скважин (Trinity Sands и Paluxy) плюс покупная очищенная вода двух поставщиков | found | S20 |
| city-f7 | Потери воды в сети | 7% за 2025 год | found | S20 |
| city-g1 | Сантехнический кодекс | 2024 International Plumbing Code с поправками, Ord. No. 2025-2607 от 17 июня 2025; дата вступления на двух страницах разная | found | S14, S10, S3 |
| city-g2 | Кодекс для домов | 2024 International Residential Code с поправками | found | S15, S10 |
| city-g3 | Поправки, полезные сантехнику | Канализация не мельче 12 дюймов, вентиляция над крышей не меньше 6 дюймов, засыпка пластиковых труб | found | S14, S15 |
| city-h1 | Мороз | Открыть шкафчики, внутренние краны капают по капле в секунду, полив выключить, наружные краны накрыть [Проверка: город пишет "drip each faucet one drip per second", слова «внутренние» нет; наружные краны накрывают добровольцы "Next Steps The Colony", не город; см. 6.3] | found | S24 |
| city-h2 | Наружные краны в новых домах | "Frost -proof hose bibs with integral vacuum breakers must be installed." | found | S8 |
| city-h3 | Проверка обратных клапанов | Отчёты в BSI онлайн; $53 в год за прибор; для частных домов закон требует тест только после установки, переноса, ремонта | found | S12, S27, S17 |
| city-h4 | Замкнутая система | Тепловое расширение после обратного клапана: забота хозяина; падение давления из-за клапана: не забота города | found | S17 |
| city-h5 | Давление в сети | Цифры давления от города нет, страницы про PRV нет; есть таблица потерь "at 40 Lbs. Pressure" [Проверка: страницы про PRV нет, но в плане водоснабжения 2010 года "typically between 50 and 80 psi"; только с годом; см. 6.0 и 6.3] | not_on_official_page | S23 |
| city-h6 | Аварийная линия города | После часов работы, "$50 after-hours fee may apply"; номера на двух страницах разные | found | S21, S22 |
| city-h7 | Засуха | Город сейчас в Phase 1 Drought Contingency Plan | found | S21 |
| city-h8 | Проверка унитаза | Капля пищевого красителя в бачок | found | S23 |

#### Источники (S)

- S1. "Contractor Registration": https://www.thecolonytx.gov/293/Contractor-Registration
- S2. "Contractor Registration Form (PDF)", "Revised 01/2026": https://www.thecolonytx.gov/DocumentCenter/View/613/Contractor-Registration-Form-PDF
- S3. "Building Inspections/Permits": https://www.thecolonytx.gov/283/Building-InspectionsPermits
- S4. Свод законов, Chapter 6, Article II "Registration of Contractors" (Ord. No. 2010-1871): https://library.municode.com/tx/the_colony/codes/code_of_ordinances?nodeId=PTIICOOR_CH6BUCOHESA_ARTIIRECO (свод "Codified through Ordinance No. 2026-2645, enacted April 21, 2026. (Supp. No. 75)")
- S5. "Do I need a Permit?", "REV 05/26": https://www.thecolonytx.gov/DocumentCenter/View/14462/Do-I-Need-a-Permit
- S6. "Residential Replacement Water Heater Requirements", файл от 20 марта 2026: https://www.thecolonytx.gov/DocumentCenter/View/650/Replacement-Water-Heater-Requirements-PDF
- S7. "Foundation Repair Requirements", файл от 6 марта 2026: https://www.thecolonytx.gov/DocumentCenter/View/13584/Foundation-Repair-Requirements
- S8. "Residential Construction Information Packet", "REV 03/26": https://www.thecolonytx.gov/DocumentCenter/View/651/Residential-Construction-Information-Packet-PDF
- S9. "eTRAKiT Guide for Scheduling Inspections": https://www.thecolonytx.gov/DocumentCenter/View/10326/How-To-Schedule-Inspections , портал https://tcol-trk.aspgov.com/etrakit/
- S10. "Adopted Codes & Ordinances": https://www.thecolonytx.gov/1366/Adopted-Codes-Ordinances
- S11. "Irrigation System Requirements": https://www.thecolonytx.gov/DocumentCenter/View/643/Irrigation-System-Requirements-PDF
- S12. "Backflow Device Test Report", "Revised 10/12": https://www.thecolonytx.gov/DocumentCenter/View/620/Backflow-Device-Test-Report-PDF
- S13. Свод законов, Chapter 12, Article XI "Irrigation Systems": https://library.municode.com/tx/the_colony/codes/code_of_ordinances?nodeId=PTIICOOR_CH12MUUTSE_ARTXIIRSY
- S14. Sec. 6-5, International Plumbing Code: https://library.municode.com/tx/the_colony/codes/code_of_ordinances?nodeId=PTIICOOR_CH6BUCOHESA_ARTIINGE_S6-5INPLCOAD
- S15. Sec. 6-1, International Residential Code: https://library.municode.com/tx/the_colony/codes/code_of_ordinances?nodeId=PTIICOOR_CH6BUCOHESA_ARTIINGE_S6-1INRECOAD
- S16. Chapter 12, Article VI "Water and Sewer Code" (Sec. 12-103, 12-103A, 12-117): https://library.municode.com/tx/the_colony/codes/code_of_ordinances?nodeId=PTIICOOR_CH12MUUTSE_ARTVIWASECO
- S17. Chapter 12, Article IX "Cross Connection Control and Prevention": https://library.municode.com/tx/the_colony/codes/code_of_ordinances?nodeId=PTIICOOR_CH12MUUTSE_ARTIXCRCOCOPR
- S18. "Utility Billing Information", "Revised 06/2026": https://www.thecolonytx.gov/DocumentCenter/View/1062
- S19. "2025-2026 Water and Sewer Rates" (Utility Fee Schedule): https://www.thecolonytx.gov/DocumentCenter/View/910
- S20. Отчёт о воде, "The analysis covers January 1 through December 31, 2025", файл изменён 25 июня 2026, ссылка "2025 Water Quality Report" стоит на S22: https://www.thecolonytx.gov/DocumentCenter/View/11377/2025-Water-Quality-Report
- S21. "Utility Billing Customer Service": https://www.thecolonytx.gov/399/Utility-Billing
- S22. "Water Distribution & Water Production": https://www.thecolonytx.gov/256/Water-Distribution-Water-Production
- S23. "Water Tips and Information": https://www.thecolonytx.gov/DocumentCenter/View/11652/water-tips-and-information
- S24. Новость "Winter Weather Updates", "Posted on January 20, 2026", сейчас в архиве: https://www.thecolonytx.gov/CivicAlerts.aspx?AID=2166&ARC=5297
- S25. Форма "Residential Water Account Leak Adjustment Request": https://www.thecolonytx.gov/FormCenter/Customer-Services-6/Residential-Water-Account-Leak-Adjustmen-163
- S26. "The Colony 1 & 2 Family Home Inspections", файл 2019 года, для новых домов: https://www.thecolonytx.gov/DocumentCenter/View/4385/The-Colony-Residential-Inspections
- S27. "Master Fee Schedule October 01, 2025 - September 30, 2026": https://www.thecolonytx.gov/DocumentCenter/View/13587/FY-2026-Master-Fee-Schedule
- S28. "Water Service Line Inventory" (таблица Excel, изменена 13 августа 2025): https://www.thecolonytx.gov/DocumentCenter/View/12696/Water-Service-Line-Inventory-Data

#### Главные цитаты по пунктам

Остальные цитаты, полностью: `6a-official-city-quotes.md`.

**a.** S1: "All contractors working in the City of The Colony must be registered." S2: "Specialty contractors will be registered with the City for the duration of their specialty license." и "Permits will not be issued if city registration and/or state license is not current."

**b.** S5, пункт 9: "Plumbing, including water heaters, water and sewer line repairs, removal and replacement of showers, mixing valves and p-traps, requires a permit. (replacing a toilet or a sink going right back in the same location does not require a permit)". S7: "Any plumbing repairs under the slab must be permitted and repaired by a licensed plumber. An engineer’s letter must be provided for backfilling under the slab at final."

**c.** S8: "Inspection requests for the next business must be made by 4 p.m. Cancellations must be called in between 7:00am-8:00am."

**d.** S16, Sec. 12-103A(d): "The city shall not be responsible for the maintenance of any water and wastewater service lines and such maintenance shall be the responsibility and duty of the owner of the premises serviced by any such service line." Sec. 12-117(a): "It shall be unlawful for any person other than a plumber, as licensed by the state, to connect any water service on the premises or outlet side of any meter or meter box." Слово "service line" в законе не определено.

**e.** S25: "consumption use must show over 15,000 gallons on the bill in question" и "An adjustment may occur only after all leaks have been repaired and verified with a field check of the meter by City staff."

**f.** S20: "We owns and operates five groundwater wells that produce up to 9 Million Gallons per Day (MGD) of treated water. Four wells are on the Trinity Sands Aquifer and one on the Paluxy Aquifer." и "The Colony owns and operates the water system within the city limits regardless of the supplier." Две строки жёсткости в колонках The Colony Water Utility: 132.0 и 12.0 ppm (картинка таблицы в work-6a).

**g.** S14: "The International Plumbing Code with Appendices A through F, 2024 edition, is hereby adopted and designated as the Plumbing Code for the City of The Colony, Texas." Дата вступления: S10 "Effective Sep. 1, 2025", S3 "effective July 17, 2025".

**h.** S24: "When temperatures are below freezing, open cabinets and drip each faucet one drip per second. Ensure sprinklers are turned off." S6, водонагреватель: слив поддона и T&P "or add emergency water shut off device" (это прямой повод для нашего автоматического клапана отсечки воды).

#### Что годится для одной ссылки на официальный источник

На странице Фриско эта ссылка ведёт на страницу города о регистрации подрядчиков. Для Зе Колони ближе всего:
1. S1, https://www.thecolonytx.gov/293/Contractor-Registration (так же, как на Фриско).
2. S5, "Do I need a Permit?" (PDF, 2026 год): прямо называет водонагреватели, линии воды и канализации, душ, смесители, умягчители.
3. S25, форма пересчёта счёта после течи.
Выбор за автором страницы и Денисом.

#### Что нельзя переносить на нашу страницу как есть (правила CLAUDE.md)

1. Источник воды у города назван через "Dallas Water Utilities", "City of Plano", "Lakes Lewisville, ... Grapevine". На нашей странице нельзя писать "Dallas" отдельно, нельзя называть Grapevine, и страница города не называет соседние города. Если писать про воду, то словами вроде "городские скважины плюс покупная очищенная вода", без названий.
2. Сборы города ($75, $100, $53 и так далее) это суммы города, не наши. Прейскурант S27 действовал до 30 сентября 2026, новый на сайте ещё не стоит [Проверка: неверно, "FY 2027 Master Fee Schedule" на сайте города уже есть, суммы те же; см. 6.0 и 6.3]. Лучше не печатать суммы города на странице.
3. Телефоны города на странице не нужны: правило про номера в тексте, и номера аварийной линии на двух страницах города разные (city-h6).
4. Обратный клапан: город требует тест после замены (city-b7). Это совпадает с нашей единственной разрешённой фразой "Once the new assembly is in, it gets tested and the test report goes to the city." Кто тестирует, не называем.
5. "Hard water" в старом тексте страницы: официальные цифры жёсткости противоречат друг другу (132.0 и 12.0 ppm), опираться на них нельзя без слова Дениса. В старом тексте ещё стоит "a morning call usually means hot water by evening", это обещание по времени, по правилам его быть не должно.

#### Вопросы Денису

1. Зарегистрирована ли FPP в Зе Колони сейчас и до какого числа? Город пишет по-разному: "один год", "на срок лицензии", "ежегодно". [Проверка: вопрос закрыт словом Дениса 3 октября, компания зарегистрирована во всех городах, где работает; не спрашивать, см. часть 10]
2. Замена обратного клапана на поливе в Зе Колони: вы берёте разрешение "Backflow Repair / Replacement Permit" сами? Город пишет, что поливную систему ставит лицензированный irrigator.
3. Течь под плитой в Зе Колони: просил ли город письмо инженера на засыпку под плитой на ваших работах, или только при ремонте фундамента?
4. Замена PRV в Зе Колони: берёте ли разрешение? У города про PRV ни слова.
5. Что вы видите по воде в Зе Колони: накипь, картриджи, водонагреватели? Официальные цифры не сходятся.
6. Есть ли у вас случаи в Зе Колони, где клиент получил пересчёт счёта после течи по нашему счёту?

#### Что не сделано и что надо знать

1. Большая часть документов скачана ночью 3 октября первым, остановленным прогоном этой задачи; я перечитал их и сверил цитаты. Заново открыл: S24, S26, S28, поиск по сайту города (результаты грузятся скриптом, текста нет), страницы 255 и 257 про готовность к непогоде (про трубы ничего).
2. В таблице S28 есть адреса и координаты: ничего не переносил, только итоги по колонкам.
3. Регистрацию FPP в городе не проверял: поиск подрядчика в eTRAKiT это отправка формы.
4. Жёсткость прочитана с картинки таблицы (текстовый слой PDF перемешан). Файл 12674 с названием "2024" сейчас отдаёт тот же отчёт за 2025 год, прошлого года для сравнения нет.
5. S26 (2019 год, новые дома) в списке памяток города уже не стоит, опираться осторожно.

### 6.2. Индексы и возраст домов (файл `6b-zip-and-age.md`)

Заголовок файла: «6, часть вторая. Почтовые индексы The Colony и возраст домов».

Проверено 3 октября 2026. Все цифры взяты из официальных файлов USPS и Census Bureau и с официального сайта города, адреса запросов стоят в конце. Ничего не придумано: где проверить не удалось, так и написано. Полные таблицы лежат рядом, в файле 6b-zip-and-age-tables.md, рабочие выписки и расчеты в папке work-6b.

#### Коротко, самое важное

1. The Colony по сути город одного индекса: 75056. По файлу почты USPS это единственный индекс почтового отделения THE COLONY. Отдельного индекса "только абонентские ящики" (PO BOX) у The Colony нет. Сам город пишет свой адрес так: "6053 Main Street The Colony, Texas 75056".
2. Черта города по файлу Census задевает пять участков индексов: 75056 (87,6% земли города), 75036 (9,2%), 75024 (3,0%), 75034 (0,1%) и 75093 (0,03%). Но жилье почти все в одном: по переписи 2020 года в 75056 стояли 18 800 из 18 814 жилых единиц города (99,9%). В куске 75036 было 14 жилых единиц, в кусках 75024, 75034 и 75093 ни одной.
3. Индекс 75056 общий с соседями. В черте The Colony только 51,9% его земли и 66,9% его жилья (перепись 2020). Остальное жилье индекса: земля вне городов 17,5%, Lewisville city 14,7%, Hebron town 0,8%, Carrollton city 0,1%.
4. Медианный год постройки жилья: The Colony city 2001 (±2). Участок 75056 дает 2006 (±1), он новее города, потому что треть его жилья стоит за чертой города. Для страницы годится только цифра города.
5. The Colony город двух эпох. Построено до 1980 года 21,3% жилья (в Плано 18,4%, во Фриско 1,5%), в 2010 году и позже 29,3%. Медиана жилья владельцев 1994 (±4), съемного 2007 (±2). Домов на одну семью до 1980 года 3 713, это 27,0% всех таких домов города.
6. Старая часть города по участкам переписи: 215.20 и 215.21 (медианы 1976 и 1977), это улицы Paige Rd, Strickland Ave, N и S Colony Blvd, Main St (FM 423). Там стоят 2 103 из 3 713 домов на одну семью, построенных до 1980 года. Самые новые участки: 216.55 (2015), 215.34 (2014), 216.47 (2011, в основном квартиры).
7. Census API (api.census.gov) без ключа не отвечает (проверено 3 октября 2026, дважды); ключ это регистрация с почтой, ее делает только Денис. Те же цифры взяты из официальных файлов Census (ACS Summary File) и сверены с data.census.gov: 240 клеток плюс две проверки по участкам переписи, несовпадений ноль.

#### а. Индексы The Colony

Источники: USPS, файл Zip_Locale_Detail.xlsx ("file updated 10/01/2026"), лист ZIP_Locale; Census Bureau, файл связи участков ZCTA и городов 2020 года ("The Colony city", код 4872530); перепись 2020 года по кварталам (Т8 в файле таблиц); сайт города thecolonytx.gov.

ZCTA это "ZIP Code Tabulation Area": участок, которым Census приближенно повторяет почтовый индекс. По ним считается вся статистика ниже.

| Индекс | USPS: класс индекса | USPS: почтовое отделение | Доля земли города в участке | Доля земли участка в черте The Colony | Жилье The Colony в участке, перепись 2020 | С кем участок общий (доля земли участка) |
|---|---|---|---|---|---|---|
| 75056 | обычный, с доставкой (поле "ZIP CLASS CODE" пустое) | THE COLONY и THE COLONY CARRIER ANNEX | 87,6% | 51,9% | 18 800 (99,9%) | Lewisville city 29,4%; земля вне городов 17,5%; Hebron town 0,4%; Carrollton city 0,4%; Frisco city 0,4%; Plano city 0,02% |
| 75036 | обычный, с доставкой | FRISCO | 9,2% | 12,0% | 14 (0,1%) | Frisco city 56,8%; земля вне городов 19,5%; Hackberry town 6,3%; Little Elm city 5,4% |
| 75024 | обычный, с доставкой | NORTHWEST PLANO | 3,0% | 3,3% | 0 | Plano city 96,4%; Frisco city 0,3% |
| 75034 | обычный, с доставкой | FRISCO | 0,1% | 0,1% | 0 | Frisco city 99,9% |
| 75093 | обычный, с доставкой | COIT (город PLANO) | 0,03% | 0,03% | 0 | Plano city 98,8%; земля вне городов 0,4%; Carrollton city 0,4%; Hebron town 0,2%; Dallas city 0,1% |

Что еще видно в источниках:

- Абонентские ящики. В файле USPS индексы "только PO BOX" помечены буквой P в поле "ZIP CLASS CODE" (так помечены 75026 и 75086 в Плано и 75029 в Lewisville). У отделения THE COLONY такой строки нет: в файле две записи с индексом 75056 (THE COLONY, 5200 S Colony Blvd, и THE COLONY CARRIER ANNEX, 5201 S Colony Blvd Ste 600), обе с пустым полем класса. Значит, отдельного индекса для ящиков у The Colony нет. Других индексов с отделением THE COLONY в файле нет, на листах "Unique" и "Other" тоже.
- Файл Census сделан по границам 2020 года. По сегодняшней границе города (карта TIGERweb, мой расчет, земля вместе с водой) картина та же: 75056 84,2%, 75036 13,1%, 75024 2,6%, 75093 0,03%. [Проверка: эти доли перепроверка не пересчитывала, см. 6.0.]
- Где лежат малые куски (мой расчет по карте Census, только для ориентира). Кусок 75036 это северо-западный край города, целиком севернее State Hwy 121; на карте там улицы Hidden Cove Park, Hackberry Creek Park Rd, Lone Star Ranch Pkwy и северный конец Main St (FM 423). Кусок 75024 это юго-восточный край, почти целиком (99,6%) южнее State Hwy 121; там улицы Grandscape Blvd, Destination Dr, Plano Pkwy, Windhaven Pkwy. Жилья в куске 75024 по переписи 2020 года не было. Куски 75034 и 75093 это полоски по границе, жилья в них тоже не было.
- Официальный сайт города. На главной странице https://www.thecolonytx.gov/ (открыта 3 октября 2026) стоит адрес "6053 Main Street The Colony, Texas 75056". На 12 других страницах сайта города, сохраненных этой ночью для других частей брифа (FAQ, Public Works / Utilities, Building Inspections/Permits, Contractor Registration и другие), тоже только 75056. Страницы города со списком индексов я не нашел.
- Форму USPS "Cities by ZIP Code" (какие названия города почта принимает для индекса) открыть не удалось: без обычного браузера сайт почты уводит на страницу о сбое, а обходить защиту нельзя. Поэтому не проверено, принимает ли почта "The Colony" как название для 75036 и какие еще названия она принимает для 75056.

Для автора страницы:

- Если индекс вообще показывать, то один: 75056. Так пишет свой адрес сам город. Других индексов на странице The Colony не нужно: в них по переписи 2020 года жили 14 единиц жилья из 18 814.
- Индекс 75056 не принадлежит The Colony целиком: треть его жилья вне черты города.
- Названия из таблицы на сайте писать нельзя. Hebron, Hackberry, Dallas не входят в десять городов (а слово "Dallas" отдельно на сайте вообще запрещено). Lewisville, Carrollton, Frisco, Plano и Little Elm входят, но страница города соседей не называет и ссылок на них не ставит (правило CLAUDE.md).
- В разделе 1 этого брифа (1-live-page.md, строка про близость офиса Plano) стоит опора "3.0% земли The Colony лежит в индексе 75024, это индекс офиса Plano". Цифра верная, но по переписи 2020 года жилья в этом куске не было, поэтому про дома клиентов она ничего не говорит.

#### б. Медианный год постройки (таблица B25035)

Выпуск: American Community Survey, 5-year, 2020-2024 (в файлах Census это "2024 ACS 5-year"). Это самый новый выпуск: файл acsdt5y2024-b25035.dat на сервере датирован 29 января 2026, а папка файлов и набор API за 2025 год отвечают 404. Для сравнения рядом стоит прошлый выпуск, 2019-2023.

"Медианный год" значит: половина жилья построена раньше этого года, половина позже. "±" это погрешность опроса из того же файла (ACS это выборочный опрос). Считается все жилье, квартиры тоже. Медиана жилья владельцев (B25037) ближе к частным домам, с которыми работает сантехник.

| Участок | Медиана, все жилье, 2020-2024 (B25035_001) | Погрешность | Та же медиана, выпуск 2019-2023 | Медиана, жилье владельцев (B25037_002) | Всего жилья (B25034_001) | Насколько цифра про The Colony |
|---|---|---|---|---|---|---|
| 75056 | 2006 | ±1 | 2005 (±1) | 2004 (±2) | 29 056 | на две трети: в 2020 году 66,9% жилья участка стояло в городе |
| 75036 | 2012 | ±2 | 2013 (±1) | 2013 (±1) | 12 043 | нет: в куске города 14 единиц жилья |
| 75024 | 2002 | ±1 | 2001 (±2) | 2000 (±1) | 20 461 | нет: жилья города там нет, цифра описывает Плано |
| 75034 | 2010 | ±2 | 2010 (±1) | 2006 (±1) | 24 756 | нет: цифра описывает Фриско |
| 75093 | 1994 | ±1 | 1994 (±2) | 1993 (±1) | 21 069 | нет: цифра описывает Плано |
| The Colony city (весь город, штат 48, место 72530) | 2001 | ±2 | 2000 (±2) | 1994 (±4) | 19 388 | да, это сам город |
| Frisco city (штат 48, место 27684) | 2009 | ±1 | 2009 (±2) | 2008 (±1) | 80 353 | для сравнения |
| Plano city (штат 48, место 58016) | 1993 | ±2 | 1993 (±1) | 1991 (±1) | 117 686 | для сравнения |

Для справки из того же файла: медиана съемного жилья в The Colony 2007 (±2); Denton County 2003 (±1), штат Texas 1992 (±1).

Главная цифра для брифа это строка "The Colony city": 2001 (±2). Цифры по участкам 75036, 75024, 75034 и 75093 описывают чужую землю, брать их как "возраст домов The Colony" нельзя.

#### в. Доли по годам постройки (таблица B25034, все жилье)

Выпуск тот же, 2020-2024. Проценты посчитаны мной из чисел файла: "до 1980" это строки с 007 по 011, "1980 по 1999" строки 005 и 006, "2000 по 2009" строка 004, "2010 и позже" строки 002 и 003. Названия строк сверены с файлом Table Shells. Из-за округления сумма может дать 99,9 или 100,1.

| Участок | Построено до 1980 | С 1980 по 1999 | С 2000 по 2009 | В 2010 и позже | В том числе в 2020 и позже |
|---|---|---|---|---|---|
| 75056 | 14,3% | 20,0% | 26,1% | 39,7% | 5,4% |
| 75036 | 1,6% | 3,1% | 30,0% | 65,3% | 3,1% |
| 75024 | 3,7% | 40,6% | 27,8% | 27,8% | 3,5% |
| 75034 | 1,7% | 16,0% | 30,3% | 52,0% | 7,7% |
| 75093 | 7,1% | 71,6% | 13,4% | 7,8% | 0,5% |
| The Colony city | 21,3% | 25,6% | 23,8% | 29,3% | 3,4% |
| Frisco city | 1,5% | 16,9% | 34,8% | 46,7% | 6,7% |
| Plano city | 18,4% | 50,3% | 17,6% | 13,7% | 1,8% |

Сами числа по городу The Colony (жилых единиц): всего 19 388; 2020 и позже 665; 2010-2019 5 017; 2000-2009 4 622; 1990-1999 1 718; 1980-1989 3 246; 1970-1979 3 564; 1960-1969 382; до 1960 года 174. Погрешности и числа по каждому участку стоят в файле таблиц (Т3).

Сверх задания, коротко (подробно в файле таблиц):

- Только жилье владельцев (B25036), The Colony city: до 1980 года 24,2%, с 1980 по 1999 32,4%, с 2000 по 2009 23,2%, в 2010 и позже 20,2%. Владельцы живут в 59,8% занятого жилья города (11 113 из 18 591). Самые частые десятилетия у владельцев: 2000-е 23,2%, 1970-е 22,0%, 1980-е 21,9%.
- Только дома на одну семью (B25127), The Colony city: таких 13 774 из 18 591 занятых единиц (74,1%). Из них 27,0% построены до 1980 года (3 713 домов), 30,8% с 1980 по 1999, 42,3% в 2000 году и позже. У Плано до 1980 года 24,1%, у Фриско 1,5%.
- Новое жилье города в основном съемное: из занятого жилья, построенного в 2010-2019 годах, сдается 58,6% (2 775 из 4 735 единиц); из занятого жилья 1970-х сдается 27,8% (943 из 3 393).
- Внутри города по участкам переписи (Т7 в файле таблиц): самые старые 215.20 (медиана 1976, до 1980 года 83,6%) и 215.21 (1977, 67,6%), самые новые 216.55 (2015), 215.34 (2014) и 216.47 (2011, в основном квартиры). Улицы каждого участка для ориентира стоят там же.

#### г. Что говорят цифры: The Colony рядом с Фриско и Плано

1. По медиане The Colony ровно посередине: 2001 (±2) против 2009 (±1) у Фриско и 1993 (±2) у Плано, по восемь лет в каждую сторону. Но по жилью владельцев, то есть почти по частным домам, The Colony близок к Плано: 1994 (±4) против 1991 (±1), а Фриско моложе на 14 лет (2008).
2. [Проверка: разница с Плано почти в пределах погрешности опроса (около ±2,6 и ±0,9), твёрдо «больше» не писать; см. 6.0, «Нельзя использовать», пункт 5.] Старого жилья в The Colony даже больше, чем в Плано: до 1980 года 21,3% против 18,4% (дома на одну семью 27,0% против 24,1%), во Фриско 1,5%. При этом новой застройки 2010 года и позже в The Colony 29,3%, вдвое больше, чем в Плано (13,7%), хотя меньше, чем во Фриско (46,7%). Слой 1990-х в The Colony тонкий: 8,9% против 28,6% в Плано.
3. Итог: в The Colony есть ядро застройки 1970-х (участки 215.20 и 215.21), рядом кварталы 1980-х, 1990-х и 2000-х (215.16, 215.18, 215.31, 215.32), а самая новая застройка 2010-х стоит у State Hwy 121 и Plano Pkwy (216.55, 216.47) и у Lebanon Rd (215.34). Это сравнение только для сведения автора: на странице The Colony другие города не называются.

#### Что из этого следует для страницы

Это предложение помощника по данным, решение за Денисом: его слово про то, что он видит на вызовах, главнее статистики.

- Живая страница говорит: "Drive one block here and you can pass two different plumbing eras." и делит город на "older sections" и "newer sections" (раздел "Plumbing Repairs in Older and Newer The Colony Homes"). Данные Census это подтверждают: до 2000 года построено 46,9% жилья, в 2000 году и позже 53,1%, а участки 215.20 (медиана 1976) и 215.31 (2002) по карте Census стоят на одних и тех же улицах (Paige Rd, Strickland Ave, N и S Colony Blvd). Слова "one block" статистика проверить не может.
- Для The Colony, в отличие от Фриско, истории про дома 1970-х годов уместны: таких домов на одну семью около 3 700, больше половины из них в двух участках вокруг Paige Rd, Strickland Ave, Colony Blvd и Main St. Что именно ломается в этих домах, говорит Денис в диктовке, Census этого не знает.
- Цифры Census на страницу лучше не выносить россыпью. Если автор захочет одну цифру со ссылкой на официальный источник, самая надежная: медианный год постройки жилья в The Colony 2001 (U.S. Census Bureau, ACS 2020-2024, таблица B25035, The Colony city, Texas). Ссылка для читателя по образцу Плано: https://data.census.gov/table/ACSDT5Y2024.B25035?g=160XX00US4872530 . В браузере я ее не открывал (браузером ночью пользоваться нельзя), данные за этой страницей ответили: "The Colony city, Texas", "2001", погрешность "2".
- Если нужна цифра про старые дома: до 1980 года построено 21,3% жилья города, примерно каждая пятая единица (B25034, тот же выпуск). Формулировку пишет автор страницы, здесь только факт.

#### Вопросы Денису

1. Нужен ли на странице индекс 75056? На живой странице индексов нет.
2. Старая часть города (участки 215.20 и 215.21: Paige Rd, Strickland Ave, N и S Colony Blvd, Main St; дома в основном 1970-х): больше ли там вызовов, чем в новых частях, и чем они отличаются? Это основа для фразы про "older sections".
3. Новые части (у State Hwy 121 и Plano Pkwy, у Lebanon Rd): там много квартир и съемного жилья. Берете ли вы вызовы в многоквартирные комплексы, или только частные дома?

#### Адреса запросов

Census API, как просили в задании, и что он ответил (3 октября 2026, в 07:26 и в 15:13 по Гринвичу):

- https://api.census.gov/data/2024/acs/acs5?get=NAME,B25035_001E&for=zip%20code%20tabulation%20area:75056,75036,75024,75034,75093 : ответ 302, перенаправление на https://api.census.gov/data/missing_key.html (заголовок "X-DataWebAPI-KeyError: 1"). То же для 2023 года и для одного 75056.
- https://api.census.gov/data/2024/acs/acs5?get=NAME,B25035_001E&for=place:72530,27684,58016&in=state:48 : ответ 302, тот же отказ без ключа.
- https://api.census.gov/data/2024/acs/acs5/variables/B25035_001E.json : отвечает без ключа, подпись переменной "Estimate!!Median year structure built". https://api.census.gov/data/2025/acs/acs5/variables/B25035_001E.json : ответ 404, значит выпуск 2024 самый новый.
- Когда у Дениса будет свой ключ, те же цифры даст запрос: https://api.census.gov/data/2024/acs/acs5?get=NAME,B25035_001E,B25035_001M&for=zip%20code%20tabulation%20area:75056,75036,75024,75034,75093&key=КЛЮЧ и для городов: https://api.census.gov/data/2024/acs/acs5?get=NAME,B25035_001E,B25035_001M&for=place:72530,27684,58016&in=state:48&key=КЛЮЧ

Откуда цифры взяты на самом деле (официальные файлы Census, ключ не нужен):

- https://www2.census.gov/programs-surveys/acs/summary_file/2024/table-based-SF/data/5YRData/acsdt5y2024-b25035.dat (медиана, все жилье)
- https://www2.census.gov/programs-surveys/acs/summary_file/2024/table-based-SF/data/5YRData/acsdt5y2024-b25034.dat (по десятилетиям, все жилье)
- там же acsdt5y2024-b25037.dat (медиана, владельцы и съемщики), acsdt5y2024-b25036.dat (по десятилетиям, владельцы и съемщики), acsdt5y2024-b25127.dat (по типу здания)
- https://www2.census.gov/programs-surveys/acs/summary_file/2023/table-based-SF/data/5YRData/acsdt5y2023-b25035.dat и acsdt5y2023-b25034.dat (прошлый выпуск)
- https://www2.census.gov/programs-surveys/acs/summary_file/2024/table-based-SF/documentation/ACS20245YR_Table_Shells.txt (названия строк) и Geos20245YR.txt (названия участков)
- Строки в файлах: 860Z200US75056, 860Z200US75036, 860Z200US75024, 860Z200US75034, 860Z200US75093, 1600000US4872530 (The Colony city, Texas), 1600000US4827684 (Frisco city, Texas), 1600000US4858016 (Plano city, Texas), участки переписи 1400000US48121021516 и другие из таблицы Т7.

Сверка с сайтом data.census.gov, файлы USPS, перепись 2020 года по кварталам и карта Census: полный список адресов стоит в файле 6b-zip-and-age-tables.md, в последнем разделе "Источники".

#### Оговорки

- ACS это выборочный опрос за пять лет (2020-2024), у каждой цифры есть погрешность. У медиан города и индексов она 1 или 2 года, у медианы жилья владельцев The Colony 4 года, у участка переписи 215.30 13 лет. По мелким клеткам (десятки и сотни единиц, все жилье до 1970 года) погрешность сравнима с самой цифрой.
- Участок ZCTA повторяет почтовый индекс приближенно, границы у почты и у Census могут расходиться. Файл связи участков и городов и раскладка кварталов сделаны по границам 2020 года.
- Число жилья по индексам и по городам внутри 75056 (Т8, Т9) это перепись 2020 года, а не ACS. Что построено после 2020 года, в нем не учтено.
- Доли площади по сегодняшней границе, положение кусков города относительно State Hwy 121 и списки улиц посчитаны мной по карте Census, это не готовые цифры источника. Названий районов у Census нет: участки переписи названы номерами, улицы даны только для ориентира.
- В файле USPS стоят названия почтовых отделений, а не список названий города, которые почта принимает для индекса. Этот список есть только в форме на tools.usps.com, которую ночью открыть не удалось.

### 6.3. Перепроверка фактов города: таблица сверки и новые источники (файл `6a-official-city-verified.md`)

Заголовок файла: «6a, проверка. Официальные факты города Зе Колони (The Colony), сверка с источниками». Списки «Можно брать», «Можно только с оговоркой» и «Нельзя брать» из этого файла стоят в 6.0.

Проверено 3 октября 2026 года, второй помощник, независимо от первого. Каждый документ скачан заново один раз (curl, без браузера), текст снят с PDF и HTML, таблица воды проверена ещё и по картинке страницы 4 отчёта. Свод законов взят через api.municode.com, выпуск Supplement 75 (codified through Ord. No. 2026-2645, enacted April 21, 2026). Файл проверяемого раздела: `6a-official-city.md` (первый помощник), его тексты источников лежат в `work-6a/`.

Как читать: "да" значит, я сам увидел эти слова или цифры на официальной странице. "нет" значит, на странице другое, или в утверждении есть то, чего на странице нет; тогда в заметке стоит правильная версия словами источника. Для пунктов not_on_official_page "да" значит: я тоже искал и тоже не нашёл, отсутствие подтверждаю.

Итог: 60 пунктов, подтверждено 55, не подтверждено 5 (city-b15, city-d6, city-e6, city-h1, city-h5). У нескольких подтверждённых есть уточнения в заметке (b3, d3, e2, g3, h3). Новые находки, которых не было у первого помощника: прейскурант FY 2027 уже на сайте города, старый документ города с давлением в сети 50 до 80 psi, разовое решение 2021 года о пересчёте канализации после морозов.

#### Таблица сверки

| id | Утверждение, коротко | Источник | Подтверждено | Заметка |
|---|---|---|---|---|
| city-a1 | Все подрядчики регистрируются; бланк, права, лицензия мастера если нужна; срок один год с даты оплаты | thecolonytx.gov/293/Contractor-Registration | да | Цитата слово в слово на странице. |
| city-a2 | Бланк Revised 01/2026; Plumbing Contractor со звёздочкой; копия лицензии штата и прав; список людей, кто берёт разрешения | DocumentCenter/View/613 | да | "Persons Authorized to Pull Permits Under This Registration" стоит в бланке. |
| city-a3 | $75 в год только General Contractor; кому нужна лицензия штата, годовой платы нет | View/613, View/13587 | да | Список "commercial, residential, moving, pool, fence, sign, demolition, foundation, remodeling, etc." стоит в прейскуранте, не в бланке. В прейскуранте FY 2027 то же самое. |
| city-a4 | Срок описан по-разному: страница, бланк, Sec. 6-26 | 293, View/613, Municode Ch. 6 Art. II | да | Все три формулировки на месте. В бланке ещё: "Contractor registration is required annually for general or like contractors." |
| city-a5 | Ord. No. 2010-1871: без регистрации нельзя; не лицензия; штраф равен плате; ответ за 10 рабочих дней | Municode Sec. 6-21, 6-24, 6-25 | да | Уточнение: запрет относится к подрядчику "required to pull a permit". |
| city-a6 | Без действующей регистрации или лицензии разрешения не дают | View/613 | да | Слово в слово. |
| city-a7 | Хозяин сам только в своём доме при homestead, разрешение всё равно нужно | View/14462 (REV 05/26) | да | Слово в слово. Страница 293 добавляет: хозяин регистрируется бесплатно по отдельной форме. |
| city-b1 | Разрешения на ремонт сантехники; с 1 октября 2025 и на ремонт фундамента | 283 | да | "As of Oct. 1, 2025, the City of The Colony requires a permit for roof replacement, siding replacement and foundation repair." |
| city-b2 | Замена водонагревателя: разрешение, подрядчик зарегистрирован | View/650 | да | Слово в слово. |
| city-b3 | Памятка по водонагревателю: 18 дюймов, газ 60 дюймов, изоляция, поддон, слив и T&P 6 до 24 дюймов или аварийный клапан, кран на холодной | View/650 | да | Про поддон точнее: "A pan is required where water heaters are installed in locations where leakage of the tank or connections could cause structural damage where one existed previously." То есть не всегда, а там, где течь может повредить конструкцию, и там, где поддон уже был. |
| city-b4 | Линия воды: разрешение; "от счётчика до дома" отдельно не названо | View/14462 | да | Пункт 10 слово в слово. |
| city-b5 | Канализационная линия: разрешение; про точечный ремонт слов нет | View/14462 | да | Слово в слово. |
| city-b6 | PRV нигде не назван | View/14462 и другие | да | Отсутствие подтверждаю: искал в памятке о разрешениях, прейскурантах FY 2026 и FY 2027, поправках к IPC и IRC, в списке 22 памяток папки "Requirement Information" (DocumentCenter/Index/68), в руководстве View/4385. Слова PRV и pressure reducing нет нигде. |
| city-b7 | Backflow Repair / Replacement Permit $75; полив ставит лицензированный irrigator; тест после установки, переноса, ремонта, тестером штата | Municode Sec. 12-156, View/14462, View/13587 | да | Sec. 12-156(b) слово в слово; "$75" в FY 2026 и FY 2027. Пункт 14 памятки: "An irrigation system must be designed and installed by a State-licensed irrigator." |
| city-b8 | Ремонт под плитой: разрешение, лицензированный сантехник; письмо инженера о засыпке на финале | View/13584 | да | Слово в слово. |
| city-b9 | Про тест сантехники при ремонте фундамента город молчит | View/13584 | да | Отсутствие подтверждаю. В View/4385 есть строка про трубы под фундаментом, но это новое строительство, не ремонт фундамента. |
| city-b10 | Без разрешения только унитаз или раковина на то же место | View/14462 | да | Слово в слово, других сантехнических исключений в памятке нет. |
| city-b11 | R105.2 в версии города: только два строительных пункта | Municode Sec. 6-1 | да | 120 square feet и "Retaining walls that are not over 2 feet". Сантехники в списке нет. |
| city-b12 | Душ, mixing valves, сифоны, поддоны душа, переделка ванны: разрешение | View/14462 | да | Пункт 9 и пункт 5 ("plumbing (shower pans, tub conversions)"). Заметка для автора: mixing valve это смесительный клапан душа, а не любой кухонный смеситель. |
| city-b13 | Умягчитель: сантехническое разрешение | View/14462 | да | Пункт 20 слово в слово. |
| city-b14 | Газ: сантехническое разрешение и лицензия штата | View/14462 | да | Пункт 12. |
| city-b15 | Плата: $10 за $1,000, минимум $100; без разрешения вдвое; заявка $50; прейскурант FY 2026, нового нет | View/13587 | нет | Цифры верные, но "нового на сайте пока нет" неверно. На странице города Fee Schedule (thecolonytx.gov/822/Fee-Schedule) стоит "FY 2027 Master Fee Schedule" (DocumentCenter/View/18455, тот же файл, что View/5009), заголовок "October 01, 2026 - September 30, 2027". В нём те же цифры: "Plumbing Permit $10.00 for every $1,000 value ($100 minimum)", "Work Performed without a Permit schedule fee doubled", "Application Fee/Non-Refundable $50.00". Страница 283 пока ссылается на FY 2026. |
| city-c1 | Инспекцию назначают: eTRAKiT, автоматическая линия, почта; результаты в eTRAKiT | 283, View/651 | да | Почта building_inspections@thecolonytx.gov и ссылка tcol-trk.aspgov.com/etrakit есть на 283. Слова "automated inspection request line" стоят в пакете View/651, на 283 просто "By phone". |
| city-c2 | Заявка до 4 p.m., инспекция на следующий рабочий день; что указать | View/651, View/650 | да | "Inspection requests for the next business must be made by 4 p.m." Номер разрешения, адрес, вид инспекции, телефон: на месте. |
| city-c3 | Отмена: звонком 7:00 до 8:00, голосовую почту не принимают; в портале до 4:00 PM накануне | View/651, View/10326 | да | Оба правила слово в слово. Пакет: обложка REV12/25, страницы REV 03/26. |
| city-c4 | Портал: до 14 дней вперёд, дневной лимит, время не гарантировано, с долгом не подать | View/10326 | да | "if there are any fees dues you will not be able to schedule an inspection." |
| city-c5 | Часы инспекций Monday - Friday 7 a.m. - 4 p.m. | 283 | да | Слово в слово. |
| city-c6 | Тот же день $50/ч, после часов $100/ч, праздник $200/ч, до 2 часов; повторная $75 | View/13587 | да | Сверено по раскладке таблицы. В FY 2027 те же суммы. |
| city-c7 | Можно попросить ETA инспектора | View/650 | да | Слово в слово. |
| city-c8 | Нельзя закрывать работу до одобрения | View/651 | да | Пункт 13 слово в слово. |
| city-d1 | Город не отвечает за обслуживание линий к дому, это хозяин (Sec. 12-103A(d)) | Municode Ch. 12 Art. VI | да | Номер раздела верный. |
| city-d2 | Счётчик, curb cock, задвижки, ящик: собственность города; счётчики чинит только город | Municode Sec. 12-103(2)b, c | да | Слово в слово. |
| city-d3 | После счётчика подключает только сантехник с лицензией штата; кран вернуть как был | Municode Sec. 12-117(a), (d) | да | Это Sec. 12-117 "Plumbers", не 12-103. Пункт (d) говорит про curb cock: "turn the curb cock to the position in which he found it". |
| city-d4 | Фразы "город до счётчика, дальше хозяин" нет; service line не определён; в реестре колонки System-Owned и Customer-Owned | View/12696, Municode Sec. 12-101 | да | Отсутствие подтверждаю (искал на страницах 189, 256, в отчёте о воде, в определениях Sec. 12-101). Рядом есть полезное: Sec. 12-103(3)a, хозяин ставит свой кран "inside the property line": "The customer shall install inside the property line a "stop and wastecock" ... The curb cock at the meter shall not be used in lieu of this". |
| city-d5 | Граница канализации простыми словами не описана; городская очистка 4" SDR | View/651 | да | Отсутствие подтверждаю. Цитата на месте, рядом: "2 feet (2') of the City's green lateral line adjacent to the tie-in must be exposed". Это требования к новому дому. |
| city-d6 | Реестр: 14,724 линий; хозяйская часть Before 1989 6,785, 1989 до 2014 4,987, After 2014 2,367, Unknown 584; материал Non-Lead 8,332, Non-Lead - Copper 6,391 | View/12696 (xlsx) | нет | Мой пересчёт того же файла (байт в байт совпадает с файлом первого помощника), лист LSLI, все строки данных: 14,726 линий, все "Non-Lead" в колонке Entire Service Line. Хозяйская часть, дата: "Before 1989" 6,785, "Between 1989 and 2014" 4,987, "After 2014" 2,369, "Unknown" 584, одна строка с текстом вместо даты. Материал хозяйской части: "Non-Lead" 8,334, "Non-Lead - Copper" 6,391, "Non-Lead - Plastic" 1. Расхождение в 2 строки, четыре цифры из семи совпали точно. Адреса не переносил. |
| city-e1 | Пересчёт после течи для занятых жилых домов, форма | FormCenter 163 | да | Слово в слово. |
| city-e2 | 90 дней, раз в 12 месяцев, больше 15,000 галлонов, нижний тариф; 90 дней на поиск и ремонт; два периода; кража, вандализм, стройка не покрываются | FormCenter 163 | да | Точнее про 90 дней на ремонт: "Reasonable efforts to locate the leak and initiate repairs must take place within 90 days of the city's or the customer's initial notification of increased usage." То есть начать поиск и ремонт, а не закончить. |
| city-e3 | Счёт сантехника с названием, адресом, телефоном; проверка счётчика городом; иногда второе снятие через две недели | FormCenter 163 | да | Слово в слово ("within a minimum of two weeks"). |
| city-e4 | Проверка на течь: 3 бесплатные за 6 месяцев, дальше $25 | View/910 | да | Есть и в прейскуранте FY 2027. |
| city-e5 | Канализация на год по расходу декабрь - март | 399 | да | Слово в слово. |
| city-e6 | Пересчитывают ли канализацию после течи, город не пишет | FormCenter 163, 399 | нет | Постоянного правила действительно нет, но есть официальное разовое решение. Рассылка города от 2/19/2021 (thecolonytx.gov/list.aspx?MID=691): "we will not be taking the consumption for the month of February into consideration for this year's sewer averaging process. Also, the city will waive any permit fees associated with water-line breaks or other storm-related permit costs." Это было один раз, после зимних бурь 2021 года. |
| city-f1 | Hardness, Calcium/Magnesium: 132.0, разброс 0 - 132.0, 2025 | View/11377 | да | Сверено по картинке страницы 4: колонка The Colony. |
| city-f2 | Total Hardness as CaCO3: 12.0, 2024; с 132.0 не сходится | View/11377 | да | Сверено по картинке. Противоречие в самом отчёте. |
| city-f3 | Calcium 25.24, Magnesium 2.491, Sodium 96.4, TDS 915.0 (2024), Alkalinity 319.0 (2024), pH 8.6 (2011) | View/11377 | да | Все цифры на месте. Годы: Calcium, Magnesium, Sodium 2025. |
| city-f4 | Купленная вода (часть Austin Ranch): Total Hardness до 200, разброс 96.0 - 200; у второго поставщика данных нет | View/11377 | да | "Information was not provided by water provider." стоит в колонке второго поставщика. |
| city-f5 | Grains per gallon в отчёте нет | View/11377 | да | Отсутствие подтверждаю: слова grain нет ни на одной странице отчёта. Страница 409 отдаёт тот же PDF. |
| city-f6 | Пять своих скважин (4 Trinity Sands, 1 Paluxy, до 9 MGD), покупка до 7 MGD и до 4 MGD; систему ведёт город | View/11377 | да | Слово в слово, включая "We owns". Отчёт называет соседние города и озёра, на нашей странице их писать нельзя. |
| city-f7 | Потери воды 7% за 2025 | View/11377 | да | Слово в слово. |
| city-g1 | IPC 2024 с приложениями A - F, Ord. No. 2025-2607 от 17 июня 2025; даты Sep. 1, 2025 и July 17, 2025 | Municode Sec. 6-5, 1366, 283 | да | Страница 1366: "Effective Sep. 1, 2025"; страница 283: "effective July 17, 2025". |
| city-g2 | IRC 2024, приложения A - Q кроме L | Municode Sec. 6-1 | да | Слово в слово. |
| city-g3 | Канализация от 12 дюймов, вентиляция от 6 дюймов над крышей, пластик на 4 дюймах гранулированной подсыпки, P3111 удалён | Municode Sec. 6-5, 6-1 | да | Удаление P3111 стоит в поправках к IRC (Sec. 6-1), не к IPC. Глубина 12 дюймов есть в обоих (IPC 305.4.1, IRC P2603.5.1). Трамбовка "in 6-inch layers". |
| city-h1 | Новость 20 января 2026: шкафчики открыть, внутренние краны капают раз в секунду, полив выключить; добровольцы помогают; постоянной страницы нет | CivicAlerts AID=2166 | нет | Город пишет "drip each faucet one drip per second", слова "внутренние" нет. Добровольцы не городские: "Next Steps The Colony is providing volunteers to assist homeowners unable to physically winterize their homes outdoors (e.g. disconnecting water hoses, covering outdoor water spigots, etc.)". Что постоянной страницы про мороз нет, проверить до конца не смог: советы стоят в новостях и рассылках. |
| city-h2 | В новых домах незамерзающие наружные краны с вакуумным прерывателем | View/651 | да | Слово в слово (раздел про новое строительство). |
| city-h3 | Отчёты в BSI онлайн; $53 в год за прибор; закон для частных домов: после установки, переноса, ремонта; проверить обязан хозяин | View/620, View/13587, Sec. 12-156 | да | "$53 per device annually" это плата "Annual Backflow Inspection Report" (FY 2026 и FY 2027). Форма View/620 старая, "Revised 10/12". Закон оставляет городу право требовать чаще: "Assemblies may be required to be tested more frequently if the city or state or any agents thereof deem necessary." |
| city-h4 | Тепловое расширение при замкнутой системе убирает хозяин; падение давления не забота города | Municode Sec. 12-157, 12-158 | да | Слово в слово. |
| city-h5 | Давления в сети и страницы про PRV у города нет; есть только памятка "at 40 Lbs. Pressure" | View/11652 | нет | Страницы про PRV нет, это подтверждаю. Но давление в сети город описывал: Water Master Plan Update, September 2010 (thecolonytx.gov/DocumentCenter/View/493, ссылка стоит на странице 256): "Both pressure planes currently operate within the same pressure range, typically between 50 and 80 psi." Там же для модели: "Required minimum pressure: 35 psi", "Recommended minimum pressure: 40 psi". Документу 16 лет. |
| city-h6 | Аварийная линия после часов, "$50 after-hours fee may apply"; номера на 399 и 256 разные | 399, 256 | да | Слово в слово; номера на двух страницах действительно разные. Цифры сюда не переношу. |
| city-h7 | Сейчас первая фаза плана на засуху | 399 | да | "The Colony is currently under Phase 1 Drought Contingency Plan" на 3 октября 2026. |
| city-h8 | Проверка бачка красителем, обход участка при работающем поливе | View/11652 | да | Слово в слово, плюс "Wait for at least 30 minutes to an hour." |

#### Новые источники, найденные при проверке

- Fee Schedule: https://www.thecolonytx.gov/822/Fee-Schedule (ссылки на FY 2024 до FY 2027).
- FY 2027 Master Fee Schedule: https://www.thecolonytx.gov/DocumentCenter/View/18455 (тот же файл: https://thecolonytx.gov/DocumentCenter/View/5009/Development-Services-Fee-Schedule-PDF), "October 01, 2026 - September 30, 2027".
- Water Master Plan Update, September 2010: https://thecolonytx.gov/DocumentCenter/View/493 (раздел 4.1 и 4.3).
- Рассылка 2/19/2021 "Sewer re-averaging adjusted; storm-related permit fees waived": https://www.thecolonytx.gov/list.aspx?MID=691
- 1 & 2 Family Home Inspections: https://www.thecolonytx.gov/DocumentCenter/View/4385/The-Colony-Residential-Inspections (новое строительство; вода под давлением 50 psi на тесте, канализация водой 5 футов или воздухом 5 фунтов). Для страницы о ремонте не основной источник.

### 6.4. Перепроверка индексов и возраста домов: таблица (файл `6b-zip-and-age-verified.md`)

Заголовок файла: «6b, проверка: индексы The Colony и возраст домов». Списки «Можно использовать» и «Нельзя использовать» из этого файла стоят в 6.0.

Проверка фактов из файла 6b-zip-and-age.md. Проверял второй помощник, 3 октября 2026, примерно с 15:20 до 15:45 по Гринвичу. Каждую цифру я открыл или скачал сам, с официального сервера, и сверил по цифрам. Правило проверки: "да" ставится только тогда, когда цифра или слова стоят в источнике и я их видел сам.

Как проверял, коротко:

- USPS: сам скачал файл https://postalpro.usps.com/mnt/glusterfs/2026-10/Zip_Locale_Detail.xlsx (страница https://postalpro.usps.com/ZIP_Locale_Detail пишет "file updated 10/01/2026"), прочитал все три листа: ZIP_Locale, Unique, Other.
- Census, земля: сам скачал файл связи индексов и городов 2020 года tab20_zcta520_place20_natl.txt.
- Census, жилье по переписи 2020 года: взял другой путь, чем первый помощник, чтобы проверка была независимой. Первый помощник относил квартал к индексу по точке внутри квартала. Я взял официальный файл связи индексов и кварталов https://www2.census.gov/geo/docs/maps-data/data/rel2020/zcta520/tab20_zcta520_tabblock20_natl.txt (в нем каждый квартал наших пяти индексов лежит целиком в одном индексе, деленных нет), город по файлу https://www2.census.gov/geo/docs/maps-data/data/baf2020/BlockAssign_ST48_TX.zip, число жилья и жителей по кварталам из карты Census (TIGERweb, слой 10, поля HU100 и POP100). Итоги сверил с готовыми таблицами переписи на data.census.gov (DECENNIALPL2020.H1 и P1 для города, DECENNIALDHC2020.H1 для 75056).
- Census, возраст жилья (ACS 2020-2024): сам запросил data.census.gov по каждому участку отдельно (таблицы B25035, B25034, B25037, B25036, B25127 и прошлый выпуск B25035), потом сам скачал официальные файлы ACS Summary File (acsdt5y2024-b25035.dat, b25034.dat, b25127.dat) и сверил строки наших участков с ответами data.census.gov: 1 980 клеток, несовпадений 0. Подписи строк таблиц взял с api.census.gov (groups/B25034.json и другие, ключ для них не нужен).
- Census API без ключа: запросил еще раз в 15:25 по Гринвичу, оба адреса ответили 302 на https://api.census.gov/data/missing_key.html с заголовком "X-DataWebAPI-KeyError: 1".
- Живая страница https://fppplumbing.com/plumber-the-colony-tx/ и главная страница города https://www.thecolonytx.gov/ открыты сам, по одному запросу.

Рабочие файлы проверки лежат вне проекта, в папке помощника: scratchpad/night/the-colony/verify6b.

#### Таблица проверки

| id | Что утверждается (коротко) | Источник | Подтверждено | Примечание |
|---|---|---|---|---|
| zip-a1 | У отделения THE COLONY один индекс, 75056: две записи, THE COLONY (5200 S Colony Blvd) и THE COLONY CARRIER ANNEX (5201 S Colony Blvd Ste 600), поле ZIP CLASS CODE пустое, как у обычных индексов | USPS Zip_Locale_Detail.xlsx | да | Обе строки стоят в файле слово в слово, поле класса пустое. На листе ZIP_Locale пустое поле у 33 637 строк, "P" у 8 645. |
| zip-a2 | Индекса "только ящики" у The Colony нет; P стоит у 75026 и 75086 (Plano) и 75029 (Lewisville); других индексов у отделения THE COLONY нет ни на одном листе | USPS Zip_Locale_Detail.xlsx, страница ZIP_Locale_Detail | да | 75026 (COIT, PLANO), 75086 (три отделения PLANO) и 75029 (LEWISVILLE) с "P". Слово COLONY в Техасе на всех трех листах встречается еще только у TENNESSEE COLONY и FIRST COLONY, это другие места. Дата файла "file updated 10/01/2026" на странице есть. |
| zip-a3 | Город пишет адрес с 75056; на 12 других страницах города тоже только 75056; страницы со списком индексов нет | https://www.thecolonytx.gov/ | да | На главной стоит "6053 Main Street The Colony, Texas 75056", других индексов нет. В 21 сохраненной этой ночью копии страниц города тоже только 75056. Что страницы со списком индексов нет, до конца проверить нельзя: поиск сайта города выдает результаты скриптом, без браузера их не видно. |
| zip-a4 | Земля города в пяти участках: 75056 87,6%, 75036 9,2%, 75024 3,0%, 75034 0,1%, 75093 0,03%; сумма 36 283 966 кв. м | tab20_zcta520_place20_natl.txt | да | Цифры в файле точно такие: 31 775 991, 3 355 555, 1 096 450, 44 049, 11 921, в сумме 36 283 966, это и есть вся земля города в файле. |
| zip-a5 | Перепись 2020: 18 800 из 18 814 единиц жилья (99,9%) и 44 498 из 44 534 жителей в 75056; 14 единиц в 75036; в остальных ноль | TIGERweb блоки, BAF 2020 | да | Мой путь другой (официальный файл индекс-квартал), итог тот же до единицы. 656 кварталов города подтверждены. Итоги города 18 814 жилья и 44 534 жителя совпадают с таблицами переписи на data.census.gov. |
| zip-a6 | 75056 общий с соседями: в черте города 51,9% земли и 66,9% жилья; земля: Lewisville 29,4%, вне городов 17,5%, Hebron 0,4%, Carrollton 0,4%, Frisco 0,4%, Plano 0,02%; жилье (28 095): вне городов 17,5%, Lewisville 14,7%, Hebron 0,8%, Carrollton 0,1% | rel-файл и BAF 2020 | да | Все доли сошлись. 28 095 единиц жилья в 75056 совпадает с таблицей переписи DHC на data.census.gov. Названия соседей на страницу нельзя, это верно сказано в самом утверждении. |
| zip-a7 | 75036 (отделение FRISCO): Frisco 56,8%, вне городов 19,5%, The Colony 12,0%, Hackberry 6,3%, Little Elm 5,4% земли; кусок города севернее State Hwy 121, улицы Hidden Cove Park, Hackberry Creek Park Rd, Lone Star Ranch Pkwy; 14 единиц жилья | rel-файл, USPS, карта Census | да, с уточнением | Доли и 14 единиц сошлись. Все 18 кварталов куска лежат севернее State Hwy 121 (по точкам кварталов и линии дороги на карте Census). Названные улицы проходят по этим кварталам (еще Main St, она же FM 423). Уточнение: "северо-западный край" верно для основной части, около 81% площади куска; остальное мелкие полоски по северному краю ближе к Lone Star Ranch Pkwy. Положение и улицы это расчет по карте, не готовая цифра источника. |
| zip-a8 | 75024 (NORTHWEST PLANO): Plano 96,4%, The Colony 3,3%, Frisco 0,3%; кусок города южнее State Hwy 121 у Grandscape Blvd, Destination Dr, Plano Pkwy, жилья в 2020 нет; 75034 (Frisco 99,9%) и 75093 (Plano 98,8%) только полоски без жилья; строка про 3,0% в 1-live-page.md верна | rel-файл, USPS | да | Все сошлось. Строка 168 в 1-live-page.md стоит как описано. Оговорка: перепись 2020 года не знает жилья, построенного после 2020 года. |
| zip-a9 | Форма USPS "Cities by ZIP Code" не открылась, какие названия города почта принимает, не проверено | tools.usps.com | нет | Открыть не удалось и у меня: один запрос, ответ 302 на страницу о сбое (anyapp_outage_apology.htm). Факта нет, использовать нечего. Обходить защиту не стал. |
| age-api | Census API без ключа отвечает 302 на missing_key.html; цифры взяты из Summary File и сверены с data.census.gov | api.census.gov | да | Повторил оба запроса в 15:25 по Гринвичу: 302, "X-DataWebAPI-KeyError: 1". Сверка файлов с data.census.gov у меня: 1 980 клеток, 0 несовпадений. |
| age-release | Самый новый выпуск ACS 5-year 2020-2024; файл b25035 от 29 января 2026; за 2025 год 404; подпись "Estimate!!Median year structure built" | www2.census.gov, api.census.gov | да, с уточнением | Дата файла "Thu, 29 Jan 2026" верна, подпись переменной верна, набор API 2025 acs5 и переменная за 2025 год отвечают 404. Уточнение: папка summary_file/2025/ уже есть (ответ 200), но папка data в ней пустая, а 5YRData отвечает 404. |
| age-75056 | 75056: медиана 2006 (±1), прошлый выпуск 2005 (±1), владельцы 2004 (±2), 29 056 единиц; до 1980 14,3%, 1980-1999 20,0%, 2000-2009 26,1%, 2010+ 39,7% (2020+ 5,4%) | data.census.gov, Summary File | да | Все цифры сошлись. |
| age-75036 | 75036: 2012 (±2), прошлый 2013 (±1), владельцы 2013 (±1), 12 043; 1,6 / 3,1 / 30,0 / 65,3% | то же | да | Все цифры сошлись. Описывает в основном землю Frisco. |
| age-75024 | 75024: 2002 (±1), прошлый 2001 (±2), владельцы 2000 (±1), 20 461; 3,7 / 40,6 / 27,8 / 27,8% | то же | да | Все цифры сошлись. |
| age-75034 | 75034: 2010 (±2), прошлый 2010 (±1), владельцы 2006 (±1), 24 756; 1,7 / 16,0 / 30,3 / 52,0% | то же | да | Все цифры сошлись. |
| age-75093 | 75093: 1994 (±1), прошлый 1994 (±2), владельцы 1993 (±1), 21 069; 7,1 / 71,6 / 13,4 / 7,8% | то же | да | Все цифры сошлись. |
| age-place-the-colony | The Colony city: медиана 2001 (±2), прошлый 2000 (±2), владельцы 1994 (±4), съемщики 2007 (±2), 19 388 единиц; до 1980 21,3%, 1980-1999 25,6%, 2000-2009 23,8%, 2010+ 29,3% (2020+ 3,4%) | data.census.gov, Summary File | да | Ответ data.census.gov: "The Colony city, Texas", "2001", погрешность "2". Числа по десятилетиям тоже сошлись (19 388; 665; 5 017; 4 622; 1 718; 3 246; 3 564; 382; 94; 80; 0). |
| age-place-frisco | Frisco city: 2009 (±1), владельцы 2008 (±1); 1,5 / 16,9 / 34,8 / 46,7% | то же | да | Все цифры сошлись. |
| age-place-plano | Plano city: 1993 (±2), владельцы 1991 (±1); 18,4 / 50,3 / 17,6 / 13,7% | то же | да | Все цифры сошлись. |
| age-sf-the-colony | B25127: 13 774 из 18 591 занятых единиц на одну семью (74,1%); из них до 1980 27,0% (3 713), 1980-1999 30,8%, 2000+ 42,3%; Plano 24,1%, Frisco 1,5%; B25036: владельцы 59,8%, из жилья 2010-2019 сдается 58,6% | data.census.gov, b25127.dat | да, с уточнением | Все цифры сошлись (сдается 2 775 из 4 735). Уточнение к словам: в таблице B25127 это строка "1, detached or attached", то есть дома на одну семью вместе с таунхаусами, а не только отдельные дома. |
| age-tracts | Самые старые участки 215.20 (1976, до 1980 83,6%) и 215.21 (1977, 67,6%), улицы Paige Rd, Strickland Ave, N и S Colony Blvd, Main St (FM 423); в них 2 103 из 3 713 домов до 1980; самые новые 216.55 (2015), 215.34 (2014), 216.47 (2011, в основном квартиры) | data.census.gov, карта Census | да, с уточнением | Медианы, доли и 2 103 (1 064 плюс 1 039) сошлись. Участок 215.20 целиком в городе, у 215.21 все жилье в городе. Среди 11 участков с жильем города это действительно самые старые и самые новые. В 216.47 в домах на 5 и больше квартир 74,1% занятого жилья. Улицы названы верно: по карте Census они проходят по этим участкам или по их границе. Уточнение: у участка 215.34 в черте города только 73,4% жилья 2020 года (остальное Frisco и земля вне городов), его медиана 2014 описывает не только The Colony. Участок 216.55 тоже в основном квартиры (67,0%). |
| age-compare | По медиане The Colony на 8 лет новее Plano и на 8 лет старше Frisco; по жилью владельцев близко к Plano (1994 и 1991), старше Frisco на 14 лет; до 1980 больше, чем в Plano (21,3% и 18,4%), 2010+ вдвое больше (29,3% и 13,7%) | b25034.dat, B25035, B25037 | да, с уточнением | Арифметика верна. Уточнение: разница по жилью до 1980 года небольшая на фоне погрешности опроса: The Colony 21,3% (около ±2,6, мой расчет по формуле Census для долей), Plano 18,4% (около ±0,9). Сказать "больше" можно, но почти на границе. Медиана владельцев The Colony 1994 с погрешностью ±4. |
| age-live-check | Строка живой страницы про "two plumbing eras" совпадает с данными: до 2000 года 46,9%, с 2000 года 53,1%; участки 215.20 (1976) и 215.31 (2002) на одних улицах; "one block" статистикой не проверить | живая страница, Census | да | Строка "Drive one block here and you can pass two different plumbing eras." стоит на живой странице под заголовком "Plumbing Repairs in Older and Newer The Colony Homes". 46,9% и 53,1% сошлись. 215.31: медиана 2002 (±2); Paige Rd, Strickland Ave, N и S Colony Blvd проходят и по 215.20, и по 215.31 (по самому участку или по границе). |

## 7. Офис

Файла раздела для этой части не было: она написана при сборке по CLAUDE.md, по краулу живой страницы (`source/crawl/pages/plumber-the-colony-tx.json` и `source/crawl/html/plumber-the-colony-tx.html`, обход 30 сентября 2026) и по файлам нового сайта (`site/src/content/pages/plumber-the-colony-tx.md`, `site/src/layouts/ServicePage.astro`, `site/src/components/CallButtons.astro`, `Header.astro`, `Footer.astro`, `Callbar.astro`, `ReviewCards.astro`, `site/src/lib/schema.ts`, прочитаны 3 октября 2026). Карточки Google у The Colony нет, проверять вживую было нечего.

### 7.1. Что говорит CLAUDE.md

- Офисы есть только во Frisco и в Plano. Страницы остальных восьми городов описывают обслуживание города из ближайшего офиса: "The other eight city pages describe service coverage of that city from the nearest office. Never invent a local office, address or phone for a city that has none."
- Офис Frisco: 12800 Westridge Blvd, Suite 116, Frisco, TX 75035, линия 469-998-8999. Офис Plano: 5700 Tennyson Pkwy, Suite 300, Plano, TX 75024, линия 980-899-7997.
- Телефоны стоят в шапке, в подвале, в кнопках звонка и в блоках офисов на страницах Frisco и Plano. В абзацах и в ответах FAQ их нет.
- Схема: один бизнес на весь сайт с обоими офисами; страница города без офиса ссылается на организацию и называет город в `areaServed`.
- Одобренная строка про дежурство: "A licensed plumber is on duty 24/7". В каком городе сейчас дежурный сантехник, не показываем. Времени приезда в своих словах не обещаем.
- Про расстояние разрешена одна формулировка, и она описывает район, а не время приезда: "About a twenty minute drive from our Frisco or Plano office".
- Страница города не называет соседние города и не ссылается на страницы других городов (правило 7).

Чего в CLAUDE.md нет: какой из двух офисов обслуживает The Colony. Не сказано и то, как называть офис на странице города без офиса: по имени ("our Plano office") или без названия города. Первое упирается в правило 7, потому что Plano для The Colony сосед. Оба вопроса стоят в части 10.

Что есть в проекте вместо ответа (это не слово Дениса):

- Живая страница называет офис Plano в описании и четыре раза в тексте ("The Colony sits minutes from our Plano office" и другие, часть 1, раздел 6); в её схеме адрес и телефон офиса Plano.
- На новом сайте точечная правка в `tools/build_launch_content.py` поменяла описание на "served from our Plano office."; во вступлении, в разделе об аварии и в ответе FAQ слова про Plano и минуты остались.
- На главном фото живой страницы на борту фургона телефон Plano ("980.899.7997").
- Текст главной (`source/home-text-v4.md`) называет The Colony без офиса: "On the Denton County side, to the west, we send a plumber in Lewisville, a plumber in Carrollton, a plumber in The Colony and a plumber in Little Elm."
- Search Console: страница Plano показывается по запросам The Colony на месте 5.0 (часть 2, раздел 6). Карточка Google офиса Plano ведёт на /plumber-plano-tx/ (`seo/cannibalization-findings.md`). Указана ли The Colony в зоне обслуживания этой карточки, в файлах проекта не записано.
- География (часть 6, Census): 3.0% земли The Colony лежит в индексе 75024, где стоит офис Plano, но по переписи 2020 года жилья в этом куске не было; кусок в 75036 (почта Frisco) это 14 единиц жилья. Это география, а не решение о том, откуда едет фургон.

### 7.2. Что показывает живая страница

- Адреса офисов в видимом тексте страницы нет. В подвале (общий шаблон старого сайта) стоят оба офиса: "Frisco Office" (ссылка на /plumber-frisco-tx/), 12800 Westridge Blvd, Suite 116, Frisco, TX 75035, 469-998-8999, и "Plano Office" (ссылка на /plumber-plano-tx/), 5700 Tennyson Pkwy, Suite 300, Plano, TX 75024, 980-899-7997 (сверено по сохранённому HTML).
- Карты нет: в коде страницы нет ни одной встроенной карты (единственный iframe это служебный тег Google Tag Manager).
- Телефоны: оба номера ссылками `tel:` в шапке и в нижней панели, порядок 980-899-7997, потом 469-998-8999. Нижняя панель свёрстана тегом H2: "980-899-7997 469-998-8999" (шаблон старого сайта). В абзацах и в FAQ телефонов нет.
- В тексте страница говорит о близости офиса Plano и о времени ("minutes from our Plano office", "we are already close", "Being minutes from Plano"), полный список в части 1, раздел 6.
- Схема: отдельный узел LocalBusiness плюс Plumber с именем "FPP Plumbing - Plumber in The Colony, TX", адресом и точкой на карте офиса Plano, телефоном Plano, `priceRange` "$$", часами 00:00 до 23:59 все семь дней и `areaServed`: The Colony, Plano, Frisco, Lewisville, Carrollton. Подробно: часть 1 и `1-live-page-tables.md`, часть E.

### 7.3. Что новый сайт показывает на этой странице сегодня

Файл страницы: layout "city", city "The Colony". Полей `office`, `call_office` и `office_map` в нём нет (у страницы Frisco стоят `office: "frisco"` и `call_office: true`).

- Над H1 строка "A licensed plumber is on duty 24/7" (её получают все страницы городов и страница emergency).
- Под вступлением две кнопки звонка без цифр: "Call" и "Frisco office" (красная), "Call" и "Plano office" (с обводкой); рядом кнопка "Request Service". Одна кнопка со своим номером бывает только на странице офиса с полем `call_office`.
- Блока офиса и карты нет: шаблон ставит их только на странице, которая записана у офиса как его собственная (/plumber-frisco-tx/ и /plumber-plano-tx/).
- Шапка: оба номера (Frisco, потом Plano) и кнопка Call, которая открывает выбор офиса (без скрипта набирает Frisco). На телефоне липкая панель звонка с обоими номерами. Подвал общий для всего сайта: оба офиса с адресами, номерами и ссылками на отзывы Google.
- Первый экран: главным фото встаёт первая картинка текста, то есть то же фото фургона со старого адреса и с тем же alt "FPP Plumbing van outside a home in The Colony, TX".
- Отзывы: в тексте стоит метка `<!-- reviews -->`, но в `reviews/site-reviews.json` ключа этой страницы нет, значит блок отзывов не выводится. Поля `reviews_heading` ("What The Colony Homeowners Say About FPP Plumbing") и `reviews_intro` ("Real Google reviews from local homeowners.") записаны в файле страницы, но шаблоны в `site/src` их не читают (поиск 3 октября 2026).
- Схема: один бизнес (Plumber) с обоими офисами, как на всём сайте, и узел Service с именем "Plumber in The Colony, TX", `serviceType` "Plumbing", поставщиком организацией и `areaServed` The Colony. Отдельного бизнеса для города, чужих городов в `areaServed` и `priceRange` на этой странице новый сайт не делает: это уже исправлено самим шаблоном.
- Что осталось от старого текста и спорит с правилами про офис: "The Colony sits minutes from our Plano office, which changes what same-day actually means here.", "The truck crosses this stretch constantly, so when a main line quits or a floor turns warm in the wrong spot, we are already close.", "Being minutes from Plano means our nights and weekends are not a promise on a website, they are a truck that actually turns around and comes back." и ответ FAQ "Faster than most, our Plano office is minutes away. Same day is the norm. Active flooding jumps the line."

### 7.4. Что из этого следует для новой страницы

- Блока офиса, карты, адреса и своего телефона у страницы The Colony быть не должно. Кнопки остаются как есть, пока Денис не назовёт офис. Если он назовёт один офис, решить с ним, ставить ли на первый экран одну кнопку с номером этого офиса или оставить две.
- В тексте нужна одна честная фраза о том, откуда мы приезжаем в The Colony, без минут и часов. Писать её можно только после ответа Дениса (какой офис и как его назвать). Слова "minutes", "already close" и "Faster than most" уходят.
- Фразу страницы Frisco про то, кто приедет ("the plumber at your door may be Nick, Christopher or Denys"), слово в слово не повторять: она стоит в блоке офиса Frisco.
- Заголовок и строку над отзывами решать вместе с выбором отзывов (часть 5): "Google reviews" станет неправдой с отзывом Thumbtack или Yelp, а "local homeowners" файлами не подтверждено.

## 8. Посты и гайды

Файл раздела: `docs/briefs/the-colony/8-links.md`, вставлен целиком. Заголовок файла: «8. Истории из The Colony, которые уже есть на сайте, и ссылки для страницы The Colony».

Рядом лежит и в бриф не вставлена таблица `8-links-gsc-colony-queries.md` (13 КБ): все запросы Search Console со словами the colony по всем страницам сайта, кроме самой The Colony, главной и Plano.
Собрано 3 октября 2026, ночью. Работа только на чтение: в проекте ничего не менялось, страница The Colony не переписывалась. Рядом лежит полная таблица запросов со словами "the colony" по всем страницам, кроме самой The Colony, главной и Plano: `8-links-gsc-colony-queries.md`.

### Откуда данные

- Живой сайт: снимок 64 страниц `source/crawl/pages/*.json` (снят 30 сентября 2026). Слово "colony" искал в тексте, title, H1, H2, H3, alt картинок и схеме всех 64 страниц. Отдельно искал места внутри The Colony (Austin Ranch, Stewart Peninsula, Grandscape, Lewisville Lake, Hawaiian Falls, Wynnwood, индекс 75056 и другие): совпадений нет ни на живом сайте, ни на новом, ни в диктовках.
- Новый сайт: `site/src/content/pages/**/*.md` (17 постов, 16 гайдов и остальные страницы), `site/src/design/home-text.json`, шаблоны `Header.astro`, `Footer.astro`, `Home.astro`; `site/dist/index.html` только ради ссылки с карты (папку ночью может пересобирать другой процесс).
- Search Console (сервис Google, где видно запросы, показы и клики): `source/gsc/performance-3m/Pages.csv` и `performance-16m/Pages.csv` (итог страницы), `source/gsc/page-query-3m.csv` и `page-query-16m.csv` (строки «страница плюс запрос»). 3 месяца это 1 июля до 28 сентября 2026, 16 месяцев это 31 мая 2025 до 28 сентября 2026.
- Фото: `photos/captions-en.csv`, `photos/captions.csv`, `photos/city-changes.md`, `docs/briefs/_shared/photos-by-city-after-recount.json`. Диктовки: `source/dictation/`. План: `docs/pages-plan.md`. Карта ключей: `seo/keyword-map.md`. Список услуг: `site/src/design/design.json`.

**Как читать цифры.** «Итог страницы» это строка в `Pages.csv`. «Сумма строк» это сумма строк страницы в `page-query`; Google прячет редкие запросы, поэтому она меньше итога. Место в сумме строк посчитано как среднее с весом по показам. Формат: клики / показы / место.

### 1. Посты и гайды, где работа была в The Colony

**Таких нет.** Ни один из 17 постов и 16 гайдов не рассказывает о работе в The Colony и не называет The Colony местом истории, ни на живом сайте, ни на новом. Поэтому таблицы «URL, title, H1, клики, режим правки» для этого города нет: ни замороженной страницы, ни страницы «править осторожно» среди историй The Colony нет.

Где The Colony всё же стоит в постах и гайдах:
- Лента блога `/blog/`, первый абзац, перечень городов, не история: "Every week we deal with real plumbing emergencies across Frisco, Plano, McKinney, Allen, The Colony, Little Elm, Prosper, and nearby areas."
- Схема (areaServed) двух страниц живого сайта (пост про картридж Moen, гайд про утечку во дворе): только список городов.
- Search Console: за 16 месяцев посты и гайды поймали по запросу с "the colony" ровно по одному показу: `/plumbing-guide/slab-leak-repair-plano-tips-2026/` ("the colony slab leak repair", 1 показ, место 68) и `/blog` ("plumber the colony tx", 1 показ, место 1). За 3 месяца ни одного.

Для сравнения сама страница `/plumber-the-colony-tx/`: за 3 месяца итог 1 / 8,682 / 15.62 (сумма строк: 196 строк, 1 / 7,903 / 15.73); за 16 месяцев итог 3 / 65,244 / 31.18 (сумма строк: 299 строк, 1 / 63,252 / 31.44). В `docs/pages-plan.md` это группа 3, строка 3: «Старый текст», показы есть, кликов почти нет, усиливать смело.

#### 1.1. Что есть вместо историй: фото с работ в The Colony

Ни одно из этих фото не рассказано как история. Это материал, из которого история может получиться, если Денис её расскажет.

| Фото | Что на нём (слова Дениса из `photos/captions.csv`) | Почему The Colony | Где стоит сейчас | Куда записано в планах |
|---|---|---|---|---|
| 79, снято 8 апреля 2026 | «Крутящийся счетчик: где-то утечка» | по границе города (`city_final`), Денис город не называл | главное фото страницы leak detection на новом сайте, alt "Water meter with the leak indicator turning, leak detection, The Colony" | leak detection, The Colony, гайд про высокий счёт за воду |
| 9, снято 15 апреля 2026 | «Замена наружного two way cleanout на дренажной линии» | по границе города; в столбце `city` стоит Plano; фото 10 той же работы по границе Frisco | нигде | sewer line (`/drain-services/`), The Colony |

Цифры страниц, где эти фото стоят или должны встать: leak detection за 3 месяца 0 / 3,813 / 33.93, за 16 месяцев 1 / 24,163 / 48.09; `/drain-services/` за 3 месяца 0 / 185 / 30.64.

Оговорки: фото 79 записано и в план гайда `/plumbing-guide/why-is-my-water-bill-so-high-frisco-tx/`, а там история из Frisco (течёт унитаз), подпись не должна выдавать фото за ту работу. Фото 9 и 10 одна работа, а города в разных столбцах разные (Plano, The Colony, Frisco); в `captions-en.csv` записано: спросить Дениса.

#### 1.2. Девять старых фото в галерее с подписью The Colony

На `/gallery/` (живой и новый сайт) девять фото из одной пачки, файлы `photo_2024-12-24_18-50-31.jpg` ... `18-56-12.jpg` в `/wp-content/uploads/2024/12/`. The Colony названа только в alt, alt дословно:
- "Refrigerator water line outlet replaced using RIDGID ProPress tool in The Colony, TX"
- "Wall leak repaired using RIDGID press tool during emergency plumbing call in The Colony, TX"
- "Leaking water line to backflow preventer valve repaired during outdoor service in The Colony, TX"
- "Final view of newly reinstalled kitchen sink during plumbing project in The Colony, TX"
- "Leaking water line replaced in garage: plumbing repair in The Colony, TX." (на живом сайте вместо двоеточия дефис)
- "Broken flush handle on commercial toilet before repair in The Colony, TX"
- "Toilet reinstalled after flange and wax ring replacement in The Colony, TX"
- "Toilet flange and wax ring replaced before reinstalling toilet in The Colony, TX"
- "Kitchen sink reinstalled with updated drain and supply lines in The Colony, TX"

Файлов нет в `photos/index.csv`, откуда город, в проекте не сказано; имя файла это время сохранения. Брать на страницу The Colony только после слова Дениса (вопрос 3). На фото с backflow preventer чинили линию к узлу, не узел (тест узла не наш); "commercial toilet" это коммерческий вызов, в фото и историях он допустим. Галерея в Search Console: за 3 месяца 1 / 1,293 / 10.13, за 16 месяцев 1 / 9,588 / 14.16; запрос с городом один: "expansion tanks repair the colony tx", 59 показов, место 53.42 (16 месяцев).

#### 1.3. Работы на границе Frisco и The Colony: это Frisco, на страницу The Colony не брать

- Работы, которые по месту съёмки на границе The Colony и Frisco, а Денис 2 октября назвал Frisco: корни в дренажной линии зимой (видео 122, фото 166, видео 167, видео 179), линия к уличному крану, лопнувшая в мороз в стене гаража (фото 178), гвоздь от полки в трубе (фото 192, 193, 194). Две последние уже стоят на странице Frisco.
- Фото 81 (заменили PRV и второй запорный кран) и 95 (замена T&P клапана) раньше были записаны за The Colony, после пересчёта по границам ушли во Frisco (`photos/city-changes.md`); слова Дениса о городе у них нет. Фото 95 сейчас стоит на главной и на странице expansion tank.

### 2. Что про The Colony сказано на страницах услуг и других страницах

Ни случая, ни числа про The Colony на сайте нет. Везде это одна строка в общем предложении или пункт в списке городов. Дословно (новый сайт):

- **Emergency** (`/emergency-plumbing-services/`): "West and south it is the same story for a plumber in Little Elm, a plumber in The Colony, a plumber in Carrollton or a plumber in Lewisville: same line, same fee structure, and the time you hear on the phone is the real one."
- **Slab leak** (`/slab-leak-repair-frisco-plano-mckinney/`): "...and on the Denton County side a plumber in Little Elm, a plumber in The Colony, a plumber in Carrollton or a plumber in Lewisville with a warm spot on the floor."
- **Leak detection** (`/water-leak-detection-frisco-plano/`): "...and across the lake to a plumber in Little Elm, a plumber in The Colony, a plumber in Carrollton or a plumber in Lewisville with a bill that makes no sense." Слова "across the lake" раздел 1 брифа уже поставил под вопрос: по официальной странице города The Colony стоит на восточном берегу Lewisville Lake, то есть со стороны офисов.
- **Главная** (`home-text.json`, «Where We Work»): "On the Denton County side, to the west, we send a plumber in Lewisville, a plumber in Carrollton, a plumber in The Colony and a plumber in Little Elm." В FAQ главной The Colony в перечне городов.
- **Списки городов**: `/contact/` ("The Colony, TX", со ссылкой), `/water-heater-repair-frisco-mckinney/` ("The Colony", со ссылкой), `/hose-bib-repair-frisco-plano/` ("The Colony" без ссылки, в конце "and nearby cities").
- На живом сайте ещё FAQ страницы Frisco: "We also cover Plano, McKinney, Prosper, Little Elm, and The Colony." На новом сайте этой фразы нет (текст Frisco v4).

Единственное, что годится как факт для страницы The Colony: формула "Denton County side" (совпадает с официальной страницей города, проверено разделом 1).

**Что показывает Search Console.** Запросы «услуга плюс the colony» Google уже отдаёт страницам услуг, но далеко, кликов ноль (таблица в `8-links-gsc-colony-queries.md`). За 16 месяцев больше всего показов у water line repair (1,931, место 54.69), slab leak (1,705, место 58.60), garbage disposal (1,191, место 27.52) и expansion tank (929, место 38.94); у PRV ни одной строки.

Важнее другое: по словам "the colony" выше стоят чужие городские страницы. За 3 месяца Plano: 70 строк, 4,951 показ, место 4.96 ("sewer line replacement the colony tx" 1,816 показов, место 5.2; "plumber the colony tx" 360, место 4.79); Frisco: 8 строк, 552 показа, место 11.64; сама The Colony: 113 строк, 5,605 показов, место 17.09. [Проверка: в этих числах учтены запросы с Iowa Colony, другим городом Техаса (у Plano 1 строка, 1 показ; у The Colony 1 строка, 8 показов). Без них 69 строк и 4,950 показов у Plano и 112 и 5,597 у The Colony, как в части 2.] Городские страницы друг на друга не ссылаются, поэтому ссылками странице The Colony помогают только услуги (якорь "plumber in The Colony") и главная. Разбор запросов дело раздела про Search Console.

### 3. На что должна ссылаться страница The Colony и с какими якорями

#### 3.1. Главная: одна ссылка

Правило 6: один раз, в последнем абзаце вступления, якорь ровно "plumber near me", общая фраза не про услугу, своими словами. Сейчас: "If you searched for a plumber near me and landed on this page, that is the whole difference in one sentence." Место и якорь правильные, а начало фразы занято: "If you searched for a plumber near me..." стоит на Carrollton, Lewisville, McKinney, Prosper и в FAQ главной; "Searched for a plumber near me..." на Allen, Celina и garbage disposal; у Frisco "If you typed plumber near me into your phone somewhere in Frisco". Новой странице нужна новая формулировка.

#### 3.2. Все 13 услуг

Город ссылается на каждую услугу. Сейчас на странице 11 из 13: нет hose bib и нет expansion tank (раздел про expansion tank на странице есть, ссылки нет). Якорь по образцу Frisco это простое имя услуги. Карта ключей запрещает странице The Colony бороться за "drain cleaning" (его страница drain cleaning), значит про засоры коротко и со ссылкой.

| № | Услуга (имя в меню) | URL | Якорь сейчас | Предлагаемый якорь | Где встаёт |
|---|---|---|---|---|---|
| 1 | Emergency plumbing | `/emergency-plumbing-services/` | "emergency plumbing" | "emergency plumbing" | блок «если течёт прямо сейчас», рядом с гайдом про главный кран |
| 2 | Slab leak repair | `/slab-leak-repair-frisco-plano-mckinney/` | "slab leak repair" (2 раза) | "slab leak repair" | один короткий абзац, по правилу городских страниц |
| 3 | Water leak detection | `/water-leak-detection-frisco-plano/` | "leak detection" | "water leak detection" | высокий счёт, крутящийся счётчик (фото 79, если Денис подтвердит город) |
| 4 | Sewer line repair and camera inspection | `/drain-services/` | "main line service" | "sewer line repair and camera inspection" | главная канализационная линия, камера; фото 9, если город подтвердится |
| 5 | Drain cleaning | `/clogged-drain-cleaning-frisco-plano/` | "drain cleaning" (2 раза) | "drain cleaning" | засоры раковин, ванн, душа |
| 6 | Water heater repair and replacement | `/water-heaters/` | "water heater repair" | "water heater repair and replacement" | водонагреватели |
| 7 | Expansion tank replacement | `/water-heater-repair-frisco-mckinney/` | ссылки нет | "expansion tank replacement" | раздел "Water Heaters and the Expansion Tank Nobody Mentions" |
| 8 | Faucet and shower valve repair | `/fixture-installation-repair/` | "shower cartridge replacement", "shower valve repair" | "faucet and shower valve repair" | картриджи и жёсткая вода |
| 9 | Hose bib repair | `/hose-bib-repair-frisco-plano/` | ссылки нет | "hose bib repair" | уличный кран; про мороз по правилу Дениса: капают краны в доме, уличному нужен чехол |
| 10 | Garbage disposal repair | `/garbage-disposal-repair-frisco-plano/` | "garbage disposal repair" | "garbage disposal repair" | строка в списке услуг |
| 11 | Water line repair | `/water-lines/` | "water line repair" | "water line repair" | мокрое место у счётчика |
| 12 | Toilet repair | `/toilet-repair-frisco-plano/` | "toilet repair" | "toilet repair" | строка в списке услуг |
| 13 | PRV replacement | `/prv-replacement-frisco-plano/` | "PRV replacement" | "PRV replacement" | давление в доме, совет Дениса про 80 PSI |

Оговорка «что ранжируется, остаётся»: старые якоря стоят в списке "Our Plumbing Services in The Colony". Прежде чем менять слово, сверить с таблицей запросов страницы (раздел про Search Console). Если старое слово держит показы, оно остаётся, а якорь с именем услуги ставится в другом месте текста.

#### 3.3. Посты и гайды

Своих историй у The Colony нет, ставить нечего. Остаётся одна ссылка, которая уже стоит:
- `/plumbing-guide/how-to-shut-off-main-water-valve-texas/`, якорь сейчас "shut-off guide", в блоке «если течёт прямо сейчас». Гайд заморожен (текст не трогаем), ссылаться на него можно. За 3 месяца у гайда 104 / 9,953 / 7.64. Якорь можно оставить или сделать "main shut-off valve guide"; не называть главный кран "quarter turn valve".

По желанию, только после слова Дениса о городе фото: `/gallery/` с якорем вроде "photos from our jobs", если девять фото с подписью The Colony подтвердятся.

#### 3.4. На что страница The Colony не ссылается

- На другие города и их страницы (правило 7). Ссылки на Plano на странице нет, правильно; но Plano назван в описании ("served from our Plano office"), во вступлении ("The Colony sits minutes from our Plano office"), в разделе об аварии ("Being minutes from Plano") и в FAQ ("our Plano office is minutes away"). Это вопрос 1 раздела 1 брифа, здесь не повторяю.
- На посты и гайды с историей из Frisco или Plano и городом в заголовке: прямого запрета нет, но это против смысла правила 7; без слова Дениса не ставить.
- На `/top-emergency-plumber-calls-frisco/`: Frisco в адресе, это не услуга из списка.
- Ссылки на города в шапке, панели Menu и подвале это навигация на каждой странице, правило 7 про текст страницы.

#### 3.5. Одна внешняя ссылка на официальный источник

Городская страница несёт одну (у Frisco это страница города про регистрацию подрядчиков). Сейчас её нет. Раздел 1 цитирует https://www.thecolonytx.gov/611/Welcome-Message (открыл её 3 октября 2026, я не открывал). Какую страницу города ставить, решает раздел про официальные источники.

### 4. Кто уже ссылается на `/plumber-the-colony-tx/` на новом сайте

В файлах страниц 5 ссылок из 5 файлов:

| Откуда | Якорь | Как стоит |
|---|---|---|
| `/emergency-plumbing-services/` | "plumber in The Colony" | в тексте, вместе с Little Elm, Carrollton, Lewisville |
| `/slab-leak-repair-frisco-plano-mckinney/` | "plumber in The Colony" | в тексте, так же |
| `/water-leak-detection-frisco-plano/` | "plumber in The Colony" | в тексте, так же |
| `/water-heater-repair-frisco-mckinney/` | "The Colony" | голый список городов |
| `/contact/` | "The Colony, TX" | список городов |

Кроме файлов страниц:
- Главная, текст «Where We Work» (`home-text.json`): "plumber in The Colony". На готовой главной ещё карта (ссылка с aria-label "Plumber in The Colony") и ряд городов под картой ("The Colony"): три ссылки по решению Дениса.
- Шаблоны на каждой странице: Areas в шапке, Menu (Cities), подвал (Areas), якорь "The Colony".
- Три старых адреса вложений под `/plumber-the-colony-tx/` уводятся на страницу редиректом 301 (`site/src/data/redirects.csv`).

**Чего не хватает** (правки других страниц, в их очередь, не сейчас):
- Девять страниц услуг не ссылаются на The Colony в тексте, хотя по правилу услуга ссылается на все десять городов: `/water-heaters/`, `/drain-services/`, `/clogged-drain-cleaning-frisco-plano/`, `/fixture-installation-repair/`, `/hose-bib-repair-frisco-plano/` (город есть, ссылки нет), `/garbage-disposal-repair-frisco-plano/`, `/water-lines/`, `/toilet-repair-frisco-plano/`, `/prv-replacement-frisco-plano/`.
- `/water-heater-repair-frisco-mckinney/` ссылается голым списком с якорем "The Colony"; правило 7 просит "plumber in The Colony" внутри предложения.
- Ни один пост и гайд не ссылается на The Colony: так и должно быть, историй отсюда нет. Ни одна другая городская страница не ссылается: тоже правильно.

### 5. Расхождения с правилами, которые всплыли по дороге

Ничего не исправлено. Подробности выше, здесь только список.

1. Leak detection: "across the lake" про The Colony (раздел 2).
2. Expansion tank ссылается голым списком; hose bib называет The Colony без ссылки и пишет "and nearby cities"; девять услуг без ссылки (раздел 4).
3. Фото 79 (The Colony) записано в план гайда с историей из Frisco; у фото 9 три разных города; у девяти фото галереи город только в alt (раздел 1).
4. По запросам с "the colony" страница Plano стоит выше самой The Colony (раздел 2).
5. Среди запросов страницы water heaters есть "tankless water heater repair the colony" (4 показа, 16 месяцев). Это только запрос; tankless на странице The Colony не упоминать.

### 6. Вопросы к Денису (то, что знает только он)

1. На сайте нет ни одной истории из The Colony. Помните работу там, которую можно рассказать (что случилось, что нашли, что сделали), лучше с фото?
2. Фото 9, новый наружный cleanout (и фото 10, старый вынутый): это The Colony, Frisco или Plano?
3. Девять фото в галерее подписаны The Colony (кран для холодильника на ProPress, течь в стене, линия к backflow preventer, кухонная раковина, линия в гараже, ручка смыва на коммерческом унитазе, фланец унитаза). Это правда The Colony? Какие можно поставить на страницу The Colony?
4. Фото 79, крутящийся счётчик: это The Colony? Что там в итоге нашли? Из этого может выйти короткая история для страницы.
5. Фото 81 (PRV и второй запорный кран) и 95 (T&P клапан): раньше были записаны за The Colony, по границе ушли во Frisco. Какой город на самом деле?

## 9. Чем The Colony отличается от Frisco и Plano

Только то, что подтверждено данными Search Console из части 2 или официальной страницей из части 6. У каждого пункта назван источник. Цифры Frisco и Plano взяты из тех же выгрузок и из брифа Plano (`docs/plano-brief-2026-10-03.md`, часть 6, факты прошли там перепроверку). Это для автора: на самой странице The Colony соседние города не называются.

1. **Страница почти без кликов, на второй странице Google.** The Colony за 3 месяца: 1 клик, 8,682 показа, место 15.62. Frisco: 42 клика, 44,080 показов, место 15.2. Plano: 98 кликов, 56,197 показов, место 6.77. За 16 месяцев: The Colony 3 клика, Frisco 110, Plano 103. Из запросов с the colony на местах 1 до 3 нет ни одного. Терять тут почти нечего, задача страницы подняться; правило «что держит показы, остаётся» всё равно действует (начала title и H1, H2 со словами plumbing services и FAQ, "Drain Cleaning" в title до слова Дениса). Источник: `source/gsc/performance-3m/Pages.csv` и `performance-16m/Pages.csv` (та же выгрузка, что в части 2), часть 2, разделы 1 и 4.
2. **Нет офиса и карточки Google, а по запросам города её обходит страница Plano.** 71 процент показов с известным запросом идут по запросам со словами the colony (5,597 из 7,903 за 3 месяца), без города 2,121, бренд 177. У страницы Plano наоборот: 62 процента показов с известным запросом идут по запросам без слова plano (бриф Plano, «Коротко», пункт 2), скорее всего через карточку Google офиса. По запросам The Colony страница Plano стоит на месте 5.0 (69 запросов, 4,950 показов за 3 месяца, выше страницы The Colony по 59), а сама The Colony на 17.1. Для текста это значит: название города и варианты «plumber in The Colony», «plumbers in The Colony», «emergency plumber» с городом в тексте и в части H2 здесь важнее, чем на страницах офисов. Источник: часть 2, разделы 1 и 6.
3. **Дома старше, чем во Frisco, и разного возраста.** Медианный год постройки жилья: The Colony 2001 (±2), Frisco 2009 (±1), Plano 1993 (±2). Жильё владельцев: The Colony 1994 (±4), Plano 1991 (±1), Frisco 2008 (±1). Построено до 1980 года: The Colony 21.3%, Plano 18.4%, Frisco 1.5%; в 2010 году и позже: 29.3%, 13.7% и 46.7%. Разница со Plano по старому жилью почти в пределах погрешности опроса, твёрдо говорить «старше Plano» нельзя; с Frisco разница большая. Старое ядро 1970-х (участки переписи 215.20 и 215.21) лежит у Paige Rd, Strickland Ave, Colony Blvd и Main St (FM 423). Истории про дома 1970-х годов здесь уместны, во Frisco нет; что в них ломается, говорит Денис. Источник: U.S. Census Bureau, ACS 2020-2024, таблицы B25035, B25037, B25034 (часть 6, строки age-place-the-colony, age-place-frisco, age-place-plano, age-compare, age-tracts таблицы проверки 6.4).
4. **Своя вода из скважин.** The Colony берёт воду из пяти своих скважин ("Four wells are on the Trinity Sands Aquifer and one on the Paluxy Aquifer") плюс покупает очищенную воду у двух поставщиков; "The Colony owns and operates the water system within the city limits regardless of the supplier." Plano покупает поверхностную воду водного округа NTMWD (озёра Lavon и Bois d'Arc), жёсткость по отчёту за 2025 год до 200 ppm (бриф Plano, city-f1, city-f4). Цифры жёсткости The Colony в её же отчёте противоречат друг другу (132.0 и 12.0 ppm), а "жёсткая вода" на живой странице ничем не подтверждена: слово за Денисом. По Frisco данных о воде в этих файлах нет. Источник: отчёт о воде The Colony за 2025 год, https://www.thecolonytx.gov/DocumentCenter/View/11377/2025-Water-Quality-Report (часть 6, city-f1, city-f2, city-f6). Поставщиков и озёра по имени на странице не называть (правила CLAUDE.md).
5. **Свои правила города, из-за которых текст с других страниц сюда не переносится.** Три вещи. Первая, ремонт под плитой: в The Colony "Any plumbing repairs under the slab must be permitted and repaired by a licensed plumber. An engineer’s letter must be provided for backfilling under the slab at final." (Foundation Repair Requirements, https://www.thecolonytx.gov/DocumentCenter/View/13584/Foundation-Repair-Requirements , city-b8); Plano при замене линий под плитой просит фото работ и письмо от Responsible Master Plumber с номером лицензии, а слов о разрешении на любой ремонт одной течи на страницах Plano нет (бриф Plano, city-b8, city-b9); есть только текст принятого Plano кодекса 2024 года на сайте его издателя: остановить течь можно без разрешения, а вырезать и заменить скрытую трубу считается новой работой с разрешением и инспекцией (бриф Plano, поправка 1 к city-b9). Разница в том, что The Colony пишет это своими словами про ремонт под плитой и добавляет письмо инженера о засыпке. Вторая, кран у счётчика: закон The Colony велит хозяину поставить свой кран на участке, "The curb cock at the meter shall not be used in lieu of this", а счётчик, curb cock и ящик принадлежат городу (Sec. 12-103, часть 6, city-d2, city-d4); Plano, наоборот, публикует памятку, как закрыть воду краном в ящике счётчика (бриф Plano, city-h2). Третья, давление: The Colony про PRV не пишет нигде (city-b6), давление в сети "typically between 50 and 80 psi" есть только в плане водоснабжения 2010 года (city-h5 в исправленном виде, https://thecolonytx.gov/DocumentCenter/View/493); у Plano есть возврат денег за PRV и порог 80 psi (бриф Plano, city-h4). Здесь нельзя писать «город требует PRV» или «город советует», только слова Дениса про 80 PSI.

## 10. Вопросы к Денису и нужные фото

Только то, что знает он один. Собрано из вопросов разделов (части 1, 2, 3, 5, 6, 8), без повторов.

### 10.1. Вопросы

1. **Офис.** Из какого офиса обслуживается The Colony, Frisco или Plano? Можно ли на странице назвать офис по имени ("served from our Plano office", без ссылки, без минут и часов), или писать без названия города? По правилам страница города соседей не называет. Указана ли The Colony в зоне обслуживания карточки Google офиса Plano? (Страница Plano стоит по запросам The Colony на местах 1 до 6.)
2. **"Drain Cleaning" в title.** В title стоит "Drain Cleaning Services", а карта ключей запрещает этой странице drain cleaning. Только title держит 10 запросов (539 показов за 3 месяца, место около 10, кликов нет). Оставить или заменить другой услугой (например словом Emergency: «emergency plumber the colony» второй ключ страницы, а этих слов на ней нет)?
3. **Самые частые вызовы и slab leaks.** Какие вызовы в The Colony на самом деле самые частые? Как часто вы чините там slab leaks? Title, H1 и первый раздел живой страницы начинаются со slab leak, и лучшие места страницы у запросов slab leak; если для города это редкость, по правилу это один короткий абзац со ссылкой, не в начале.
4. **Старые и новые части города.** Что вы находите в домах 1970-х годов в старой части (Paige Rd, Strickland Ave, N и S Colony Blvd, Main St): медь под плитой, чугунная канализация, пинхолы, старые краны? Что в новых частях (по Census новая застройка 2010-х в основном у State Hwy 121 и Plano Pkwy и у Lebanon Rd, много квартир; Austin Ranch и The Tribute названы на странице города, но их возраст данными не проверен): PEX, что ломается первым? Верна ли по вашему опыту фраза живой страницы "Drive one block here and you can pass two different plumbing eras"?
5. **Истории.** На сайте нет ни одной истории из The Colony. Помните одну или две работы там (что случилось, что нашли, что сделали), лучше с фото? В каких районах города вы работали?
6. **Город у фото.** Фото 9 (новый наружный cleanout) и 10 (старый, сломанный): одна работа, а записаны три города (The Colony, Frisco, Plano). Где это было? Фото 79 (крутится счётчик): это The Colony, и что нашли в итоге? Фото 81 (PRV и второй запорный кран) и 95 (T&P клапан): раньше записаны за The Colony, по границе ушли во Frisco; какой город на самом деле? Девять старых фото галереи с "The Colony, TX" в alt (кран холодильника на ProPress, течь в стене, линия к backflow preventer, кухонная раковина, линия в гараже, ручка смыва коммерческого унитаза, фланец унитаза): это правда The Colony, и какие можно поставить на страницу?
7. **Главное фото живой страницы.** Где снят фургон на жилой улице? Что за номер "M-38532" на крыле (на сайте лицензия M-44816)? Убираем это фото? Можно ли пока ставить фургон у офиса Frisco (фото 2 или 4), как вы разрешили для Celina и Lewisville?
8. **Разрешения и инспектор в The Colony.** На что смотрит инспектор при замене водонагревателя (памятка города: 18 дюймов, поддон, слив поддона и T&P наружу или аварийный клапан отсечки воды, кран на холодной воде)? Берёте ли разрешение на замену PRV (город про PRV не пишет ничего)? Замена обратного клапана на поливе: разрешение "Backflow Repair / Replacement Permit" берёте вы сами (город пишет, что поливную систему ставит лицензированный irrigator)? На ваших работах slab leak город просил письмо инженера о засыпке под плитой?
9. **Давление и вода.** Какое давление вы видите на манометре в домах The Colony и где там обычно стоит PRV? Что вы видите по воде: накипь, картриджи, водонагреватели? Официальные цифры жёсткости в отчёте города противоречат друг другу (132.0 и 12.0 ppm), а живая страница пишет "hard water here".
10. **Дома под аренду и квартиры.** Много ли в The Colony вызовов от хозяев домов под аренду и управляющих? Правда ли, что фото приходят с каждым счётом, как пишет старый FAQ ("photos come back with the invoice"; в фактах проекта фото и видео по запросу)? Берёте ли вызовы в многоквартирные комплексы (новые части города в основном квартиры)? Были ли случаи, когда клиент в The Colony получил пересчёт счёта за воду после течи по нашему счёту?
11. **Отзывы.** Ни один из 407 отзывов не называет The Colony. Помните ли, кто из авторов был оттуда (Maksym Basovskyi, Angelo Toborg, Sun Sun с живой страницы или кто-то из десятки части 5)? Оставляем все три старых отзыва (Maksym остаётся по вашему слову от 30 сентября; у Sun Sun "no hide fee", это похвала, не комиссия за карту: так можно)? Заголовок "What The Colony Homeowners Say About FPP Plumbing" и строку "Real Google reviews from local homeowners." оставляем или ставим нейтральные? Отзывы со словами "plumber near me" для The Colony по-прежнему не берём, как на Frisco? Есть ли клиент со slab leak, которого можно попросить оставить отзыв (свободного такого отзыва нет)?
12. **Услуги и индекс.** Делаете ли вы sump pump («the colony sump pump repair» дал 115 показов за 3 месяца; без вашего ответа слова на странице не будет)? Нужен ли на странице индекс 75056 (на живой странице индексов нет)?

Закрыто раньше словом Дениса, не спрашивать снова: регистрация. 3 октября 2026 Денис сказал, что компания зарегистрирована во всех городах, где работает (бриф Little Elm, «Ответы Дениса», пункт 1); в CLAUDE.md то же. Раздел 6 спрашивал, до какого числа действует регистрация в The Colony: для текста страницы это не нужно.

### 10.2. Какие фото просить

Подробно в части 4.3. Коротко, по порядку важности:

1. Настоящее фото с работы в The Colony или фургон FPP на улице в черте города (вертикальный кадр, без номеров домов).
2. Если cleanout (9 и 10) был в The Colony: кадр той же работы пошире или кадр с экрана камеры.
3. Что нашли на вызове с крутящимся счётчиком (79), если это The Colony.
4. Работа slab leak в The Colony, если была: яма или тоннель, пинхол, спаянное место.
5. Водонагреватель в The Colony «до» и «после»: поддон, слив поддона и T&P наружу или аварийный клапан, кран на холодной, расширительный бак.
6. Манометр на уличном кране с цифрой давления и PRV.
7. Ящик счётчика: кран города и отдельный кран хозяина на участке.
8. Картридж или клапан душа, «до» и «после».
9. Работа в доме 1970-х годов в старой части города.
