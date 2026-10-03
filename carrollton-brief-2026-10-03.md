# Бриф страницы Carrollton (3 октября 2026)

Страница: /plumber-carrollton-tx/ . Собрано 3 октября 2026 из файлов разделов в папке `docs/briefs/carrollton/`. Страница этой ночью не переписывалась: текст напишет другой чат из этого брифа и из диктовки Дениса. В проекте ничего не менялось, кроме этого нового файла.

Как устроен файл. Части 1, 2, 3, 5, 6 и 8 это файлы разделов, вставленные целиком скриптом, слово в слово: первая строка файла (его заголовок) названа в начале части, остальные заголовки опущены на уровень ниже, в части 6 на два уровня, потому что там четыре файла. Части «Коротко», 4, 7, 9 и 10 написаны при сборке. Читать стоит «Коротко», потом части 9 и 10, остальное открывать по делу.

Оговорки к вставленным файлам:

- Слова «рядом» и «файл таблиц» во вставленных текстах значат папку `docs/briefs/carrollton/`. Длинные таблицы в бриф не вставлены: их имена названы в начале каждой части.
- Номера разделов внутри вставленных файлов («раздел 5», «пункт 7», «вопрос 3») относятся к самому файлу, не к частям брифа.
- Часть 6. Файлы фактов писались первыми, перепроверка шла после них. Где они расходятся, верить спискам 6.0 и таблицам проверки (6.3 и 6.4). Списки «что можно брать» и «чего нельзя» из двух файлов проверки переставлены в начало (6.0), остальное из этих файлов стоит в 6.3 и 6.4; ни одна строка не убрана. В трёх местах файлов фактов при сборке дописана пометка «[Сборка: ...]»: у строк city-b5 и city-g2 и в абзаце про поддон (6.1), у цифры 59,6% (6.2).
- Координаты. В файле `6b-zip-and-age.md` одна строка называла центры почтовых участков цифрами широты и долготы; в брифе эти цифры заменены пометкой «[Сборка: ...]». Точку офиса Plano из старой схемы страницы бриф тоже не повторяет. Больше координат во вставленных файлах нет (проверено поиском при сборке).
- Адреса и телефоны. Адресов и телефонов клиентов в брифе нет (проверено поиском). Адреса в тексте это офисы FPP, почтовые отделения USPS и офисы конкурентов на Halsey Way, все открытые. Телефоны в тексте только номера FPP: 980-899-7997 (Plano) и 469-998-8999 (Frisco).
- Отзывы в частях 1 и 5 даны дословно, с опечатками авторов; цифры приезда в них это слова клиентов, по решению Дениса их не трогаем.
- Сайт cityofcarrollton.com на все запросы помощников отвечал 403 (защита Akamai), защиту никто не обходил. Поэтому почти все страницы города прочитаны по копиям Internet Archive (март до августа 2026, у каждого пункта своя дата), а часть 1 (раздел 7) опирается на выдачу поиска. Такие пункты утром сверить с живым сайтом в обычном браузере.
- Новый сайт этой ночью пересобирает другой процесс. Всё, что сказано о новом сайте (части 1, 4, 7, 8), верно на 3 октября около 10:40 до 11:50.

## Проверка критика (3 октября 2026, около 12:00)

Бриф прочитан целиком и сверен с источниками. Правки внесены в текст и помечены «[Критик: ...]»; в «Коротко», пункт 4, и в части 10, вопрос 2, цифры поправлены прямо.

По пунктам задания:

| № | Что | Есть и полно? |
|---|---|---|
| 1 | Живая страница: title, описание, H1, все H2, вопросы FAQ, объём, два отзыва целиком с датой и ссылкой и где они на новом сайте, фото, ссылки со страницы и на неё с якорями, нарушения дословно, места | Да (часть 1 и `1-live-page-tables.md`). Поправка: фраза города "up to the back of the meter loop" в копиях страниц города не найдена, помечено |
| 2 | Search Console 3 и 16 месяцев: таблицы, файлы, главная, что держат заголовки, где выше другая страница, услуги и хозяева, чужие места | Да (часть 2). Четыре полных файла таблиц существуют (98 и 189 строк). Поправлены цифры «faucet» и «broken pipe» в «Коротко»; к Hebron добавлено, что связывает его с Carrollton по данным |
| 3 | Десять страниц конкурентов в `source/competitors/2026-10-03-carrollton/`, таблица, местные факты, которых нет ни у кого | Да. Файлы `00.txt` до `09.txt` на месте, адреса и число слов «вся страница» совпали с таблицей |
| 4 | Фото и клипы после пересчёта, где стоят, кандидаты, что просить | Да (часть 4). Десять фото, клипов 0, места на сайте перепроверены по `site/src` около 12:00: без изменений |
| 5 | Десять кандидатов с полным текстом, без чужого города, не занятые | Да. Ни один из десяти и из запаса не стоит в `reviews/site-reviews.json` (перечитан около 12:00, 14 страниц, 40 авторов). Поправлено пересечение с четвёрками других городов (Michael V. теперь в четвёрке Allen) |
| 6 | Официальные факты со ссылкой и датой, проверенные списки | Да (часть 6, списки 6.0). Неподтверждённое помечено как архив или «нельзя» |
| 7 | Офис | Да (часть 7) |
| 8 | Посты и гайды с работой в городе | Да (часть 8: таких нет). Поправлено место Carrollton в очереди городов |
| 9 | Три до пяти отличий от Frisco и Plano с опорой на данные | Да, пять (часть 9). К пункту 5 добавлено уточнение про IRC R105.2 в обоих городах |
| 10 | Вопросы Денису и список кадров | Да (часть 10) |

Что сверено с источником (всё совпало, кроме отмеченного):

1. Запросы: «carrollton tx leak detection» 398 показов, место 19.9; «carrollton leak detection» 366, 25.02; «slab leak repair carrollton tx» 231, 12.9 (3 месяца); «plumber carrollton» 2,124, 47.43, 1 клик (16 месяцев); итоги 98 запросов, 2,450 показов и 189, 43,821 (`source/gsc/page-query-3m.csv`, `-16m.csv`). У главной 40 запросов с carrollton, 1,515 показов за 16 месяцев.
2. Итоги страниц в `Pages.csv`: Carrollton 2 / 2,631 / 21.32, Frisco 42 / 44,080 / 15.2, Plano 98 / 56,197 / 6.77; за 16 месяцев 2, 110, 103. Доля течей 85.4%, 9.8%, 9.8% пересчитана. Plano по carrollton: 24 запроса, 461 показ; «plumber carrollton tx» 232, 13.22.
3. Живая страница по `source/crawl/pages/plumber-carrollton-tx.json`: title (63 знака), описание (138), H1, девять H2, восемь вопросов FAQ, даты схемы (16 мая 2025, 17 августа 2026), areaServed с Addison и Farmers Branch, все цитаты нарушений из части 1, "honest" три раза.
4. Тексты десяти кандидатов по `reviews/all-reviews.csv`: знак в знак, даты и ссылки те же.
5. Census, запрос повторён на data.census.gov: B25035 для Carrollton city 1988, погрешность 2; B25034 для 75006: 8,409 из 19,640 построено до 1980 года, 42.8%.
6. Город, копии Internet Archive (живой сайт снова 403): "Plumbing Work" от 11 июня 2026, слова "erected, installed, enlarged, altered, repaired, removed, converted, or replaced" и "plumber must provide a letter of excavation and backfill" на месте; "Fees" от 11 июня 2026, "there is no charge for that permit" на месте; "Leak Adjustments" от 12 апреля 2026, копия разрешения в течение 90 дней на месте. Не найдено: "up to the back of the meter loop" (было только в выдаче поиска).
7. Отчёт поставщика воды за 2025 год (живой PDF): источники "The Elm Fork of the Trinity River and lakes ..." на месте, слова hardness нет, оценка "Superior" у поставщика.
8. Фото фургона открыто: на крыле "M-38532", на борту "980.899.7997", номерного знака и номеров домов не видно. Фото по `docs/briefs/_shared/photos-by-city-after-recount.json`: десять записей Carrollton совпали с таблицей 4.1.

Чистота: тире и короткого тире нет; координат нет; телефоны только FPP; адреса только офисов FPP, почты USPS и конкурентов; занятых авторов среди предложенных нет.

## Коротко

1. Что кормит страницу. За 3 месяца (1 июля до 28 сентября 2026) 2 клика, 2,631 показ, среднее место 21.32; за 16 месяцев те же 2 клика, 45,336 показов, место 52.52 (`source/gsc`, Pages.csv). Оба клика с запросов «plumber carrollton» (36 показов, место 25.2) и «plumber carrollton tx» (9, место 29.3). В десятке Google ни одного запроса с carrollton.
2. По каким запросам. До июля страницу показывали в основном по общим запросам (18,427 из 40,251 показа с carrollton за 13 месяцев, место 54.6). За последние 3 месяца 83% показов с городом (1,821 из 2,188) это leak detection и slab leak: «carrollton tx leak detection» 398 показов на месте 19.9, «carrollton leak detection» 366 на 25.0, «slab leak repair carrollton» 280 на 16.1, «slab leak repair carrollton tx» 231 на 12.9.
3. Что нельзя потерять: начало title "Plumber Carrollton, TX" и начало H1 "Plumber in Carrollton, TX" (оба клика); "Leak Detection" в title и H2 "Water Leak Detection in Carrollton"; "Slab Leak" в title (только он держит 939 показов за 3 месяца и 4,967 за 16), но карта ключей отдаёт «slab leak repair carrollton» странице slab leak, которая по этим запросам не показывается: решает Денис. Ещё H2 "Our Plumbing Services in Carrollton" (только он держит 1,124 показа за 16 месяцев), H2 "Carrollton Plumbing FAQ", "Carrollton plumbers" в описании, вопрос о цене (переписать: 8 слов подряд совпадают с конкурентом). "PRV Repair" в title не держит ничего.
4. Дыры в тексте: "plumber in Carrollton" стоит только в H1; нет слов «emergency plumber» с городом (семейство emergency, 24 hour, same day: 5,471 показ до июля), слова faucet (запросы со словом faucet: 3,348 показов за 16 месяцев, из них 3,326 до июля; вместе с shower 3,434), water line repair (2,592 до июля), слов pipe break (1,549 за 16 месяцев, все до июля). [Критик: при сборке здесь стояли «faucet (3,434)» и «broken pipe (2,035)»; это итоги семейств из части 2, а в семейство «leak repair, pipe break» входят и «leak repair carrollton (tx)», чьи слова на странице есть. Пересчитано по `source/gsc/page-query-16m.csv` и `-3m.csv` 3 октября 2026.] Страница Plano стоит выше страницы Carrollton по 15 запросам с городом (424 показа за 3 месяца), в том числе «plumber carrollton tx»: Plano 232 показа на месте 13.2, Carrollton 9 на 29.3.
5. Что на живой странице против правил (на новом сайте почти всё ещё стоит): обещания времени своими словами "we’ll handle it today" и "a morning call typically means hot water by evening"; "keep the owner out of the middle of it"; "Details and pricing on our PRV replacement page."; регулировка PRV (в CLAUDE.md только замена); восемь вопросов FAQ тегом H3, пять из них шаблоны других городов; в схеме второй бизнес с адресом и телефоном офиса Plano, в areaServed Addison, Farmers Branch, Lewisville, The Colony, "Texas Master Plumber License M-44816", "North Dallas communities", priceRange "$$"; нет ссылки на официальный источник; ссылка на главную не во вступлении; нет ссылок на hose bib и expansion tank; трижды "honest".
6. Чего на живой странице нет: улиц, районов, фото с работ, историй с вызовов, блока Дениса. Своего текста 1,374 слова (весь краул 1,624), до отметки 2,500 не хватает около 1,100. Главное фото это фургон: на борту телефон Plano, на крыле "M-38532" (на сайте лицензия M-44816), Carrollton назван только в alt.
7. Конкуренты: десять страниц из выдачи по «plumber carrollton tx», «plumber in carrollton», «carrollton plumbing» (Semrush, 3 октября 2026). Основной текст от 891 до 2,605 слов, среднее 1,499. Три местные компании с офисом на Halsey Way, 75007; самая местная Carrollton Plumbing Service (улицы, районы, одна история, PRV). fppplumbing.com в первых 30 по Semrush нет ни по одному из трёх запросов.
8. Чего нет ни у одного из десяти: PSI, счётчика и ящика с краном, поставщика воды, разрешений и инспектора города, ремонта под плитой (тоннель, пайка, type L), спринклеров, бака на чердаке с поддоном и расширительным баком, слива кондиционера, округов города, человека с лицом, ссылки на официальный источник по делу. Что у них есть, а нам нельзя: tankless у 9 из 10, hydro jetting у шести, газ у девяти, бесплатная оценка у шести, вилки цен, срок гарантии, время приезда.
9. Фото: после пересчёта за Carrollton 10 фото, все по границе города, слова Дениса о городе нет; клипов 0. Свободны 27 (PRV), 57 и 58 (слив раковины до и после), 144 до 148 (душевой клапан через плитку, полная серия). Фото 42 (перепаянный стык slab leak) главное на странице slab leak, фото 6 (Bradford White) на главной и на emergency. Фото фургона или работы в Carrollton для первого экрана нет.
10. Отзывы: из 407 Carrollton называют только двое, Tyler Sommers (Google, июнь 2026, замена водонагревателя) и Paula Thompson (Google, январь 2026, прокладка в ванне и унитаз); оба с живой страницы, оба свободны и проходят правила, у обоих цифры времени в словах клиента. Свободных пятизвёздочных 330, все правила проходят 145, работу называют 27. Чистого свободного отзыва про slab leak, PRV, линию во дворе, главную линию и сдаваемые дома нет.
11. Официальные факты, подтверждённые двумя проходами (в основном по копиям Internet Archive, утром сверить вживую): регистрация сантехника в городе через портал CityServe, бесплатно, на год, с лицензией и страховкой на сайте TSBPE; разрешение, когда систему "erected, installed, enlarged, altered, repaired, removed, converted, or replaced"; разрешение на любой водонагреватель; на одну замену PRV разрешение без платы; ремонт под плитой: разрешение и "letter of excavation and backfill"; боковая канализация за хозяином, но дефект в городской полосе город чинит бесплатно по видео камеры от сантехника; пересчёт счёта после течи с копией разрешения в течение 90 дней; кодексы IPC и IRC 2024 с 1 сентября 2025; поправка M1411.9: конденсат кондиционера в канализацию через сифон; вода покупная поверхностная, официальной цифры жёсткости нет. Неверным оказался один пункт, city-g2. Лучший адрес для одной официальной ссылки: https://www.cityofcarrollton.com/departments/departments-a-f/building-inspection/my-trades/plumbing-work (разрешения и письмо при ремонте под плитой; роботам сайт отвечает 403, проверка ссылок может назвать её битой).
12. Индексы и возраст: у города три индекса с доставкой, 75006, 75007, 75010 (75011 только абонентские ящики); в них 95.3% земли и 99.96% жилья города. Медианный год постройки жилья 1988 (±2); юг 75006 1982, середина 75007 1987, север 75010 2005; до 1980 года построено 26.0%. Город лежит в трёх округах: жильё Denton 60.5%, Dallas 38.5%, Collin 0.9%.
13. Посты и ссылки: на сайте нет ни одного поста или гайда с работой в Carrollton; город назван только в замороженном гайде про главный кран, в одной фразе вместе с Richardson. Страница ссылается на 11 услуг из 13. На неё в тексте ссылаются 6 файлов нового сайта, 8 страниц услуг из 13 не ссылаются.
14. Офис: офиса в Carrollton нет, и CLAUDE.md не говорит, из какого офиса его обслуживают. Живая страница офис в тексте не называет, но в её схеме адрес и телефон офиса Plano. Новый сайт на этой странице: две кнопки звонка (Frisco office, Plano office), блока офиса и карты нет, в схеме один бизнес и узел Service с areaServed Carrollton. Вопрос к Денису.
15. Чего не хватает для сильной страницы: диктовки Дениса про Carrollton (в `source/dictation` её нет); его рассказов о работах с фото 42, 27, 57 и 58, 144 до 148 и 6; ответов про офис и про слова услуг в title; кадра фургона или работы в Carrollton; отзыва про течь или slab leak; выбора отзывов.

## 1. Живая страница

Файл раздела: `docs/briefs/carrollton/1-live-page.md`, вставлен целиком. Заголовок файла: «1. Живая страница Carrollton: что стоит на fppplumbing.com сейчас».

Таблицы рядом, в бриф не вставлены: `1-live-page-tables.md` (A: восемь вопросов FAQ с ответами слово в слово и где вопросы повторяются; B: ссылки со страницы; C: ссылки на страницу с остальных 63 страниц краула; D: схема страницы).

Оговорки сборки: раздел 7 этого файла опирается на выдачу поиска по сайту города (сами страницы отвечали 403); проверенные факты города стоят в части 6. Про округ (раздел 5 файла, «Denton County side»): по переписи 2020 года жильё Carrollton лежит в округах Denton (60.5%), Dallas (38.5%) и Collin (0.9%), часть 6.0.

Откуда данные. Краул старого сайта от 30 сентября 2026: `source/crawl/pages/plumber-carrollton-tx.json` и код `source/crawl/html/plumber-carrollton-tx.html`, остальные 63 страницы там же. Отзывы: `reviews/all-reviews.csv`, `reviews/site-ledger.md` и `reviews/site-reviews.json` (прочитаны 3 октября около 10:40, их перестраивает другой процесс), `reviews/ledger.md`, `reviews/proposed-placement.md`. Правки: `tools/build_launch_content.py`, `site/src/data/launch-changes.csv`, новый файл `site/src/content/pages/plumber-carrollton-tx.md` (прочитаны около 10:45). 3 октября живая страница открыта ещё раз одним запросом: код совпал с краулом байт в байт (282,658 байт), всё ниже верно и на сегодня.

Длинные таблицы: `docs/briefs/carrollton/1-live-page-tables.md` (A: FAQ с ответами и где вопросы повторяются; B: ссылки со страницы; C: ссылки на страницу с 63 страниц; D: схема).

Страница: https://fppplumbing.com/plumber-carrollton-tx/ , ответ 200, в page-sitemap.xml, canonical на себя, index и follow. Опубликована 16 мая 2025, правка 17 августа 2026 (из схемы).

План (`docs/pages-plan.md`, группа 3 «Показы есть, кликов почти нет: усиливаем смело», строка 12): 2,631 показ, место 21.3, 2 клика за 1 июля до 28 сентября 2026, «Старый текст». Карта ключей (`seo/keyword-map.md`): главный ключ "plumber carrollton tx", брать нельзя "slab leak repair carrollton" (страница slab leak).

### 1. Title, описание, H1, заголовки, объём

| Что | Текст на живой странице |
|---|---|
| Title (63 знака) | "Plumber Carrollton, TX \| Leak Detection, Slab Leak & PRV Repair" |
| Meta description (138 знаков) | "Wet spot in the yard? Water bill climbing? Low pressure all over the house? Licensed Carrollton plumbers find it before you pay to fix it." |
| H1 | "Plumber in Carrollton, TX - We Find the Leak Before Anyone Digs" |
| OG | title и описание те же; картинка: фургон `/wp-content/uploads/2025/05/photo_2025-05-15_20-41-51.jpg` |

В H1 дефис с пробелами на месте тире (на новом сайте заменён двоеточием).

H2 по порядку (в скобках слов в разделе с заголовком):

1. "Water Leak Detection in Carrollton" (200)
2. "Slab Leaks, Handled Honestly" (118)
3. "Water Pressure and the PRV" (150)
4. "Our Plumbing Services in Carrollton" (106, список из 10 строк)
5. "What Else We Run Into Here" (187)
6. "Water Coming In Right Now?" (89)
7. "Carrollton Plumbing FAQ" (393)
8. "What Carrollton Homeowners Say About FPP Plumbing" (233, отзывы)
9. "980-899-7997 469-998-8999" (не раздел: телефоны нижней панели тегом H2, шаблон старого сайта)

H3: восемь, все это вопросы FAQ. Блока офиса нет, и это правильно. После отзывов одна строка призыва (пункт 6.1).

Объём. Краул: 1,624 слова на страницу (без меню и подвала). Свой текст от H1 до конца FAQ: 1,374 слова (вступление 119 слов, два абзаца). Отзывы: 233 слова с подписями (Tyler Sommers 54, Paula Thompson 135). До 2,500 своему тексту не хватает около 1,100.

Ключи: "Carrollton" 18 раз, из них 12 до отзывов. "plumber in Carrollton" только в H1 (в тексте и в H2 ноль). "Carrollton plumbers" только в описании. "plumber near me" 1 раз (ссылка на главную). По правилам городской страницы фраза "plumber in Carrollton" должна стоять во вступлении, в первом блоке, в заключении и в части H2.

### 2. Восемь вопросов FAQ

Все восемь стоят тегом H3 в раскрывающемся списке Elementor (`details`, `summary`, класс `e-n-accordion-item-title-text`), ответы в коде обычным текстом. По правилу 8 нужен жирный текст. Ответы слово в слово: таблица A.

| № | Вопрос (H3) | Шаблон? |
|---|---|---|
| 1 | "How much does a plumber cost in Carrollton, TX?" | Шаблон: с заменой города на всех 9 других городских страницах старого сайта, на новом сайте на 8 |
| 2 | "What are the first signs of a slab leak?" | Слово в слово на The Colony |
| 3 | "Can you replace a water heater the same day in Carrollton?" | Только здесь |
| 4 | "My whole house lost water pressure. Is that the PRV?" | Слово в слово на Little Elm |
| 5 | "How do I know if I have a hidden water leak?" | Только здесь (похожий на leak detection) |
| 6 | "Do you charge extra after hours?" | Шаблон: слово в слово на Allen, Celina, Lewisville, Little Elm, McKinney, Prosper, The Colony |
| 7 | "Do you work in both old and new homes?" | Только здесь |
| 8 | "Do you work with property managers and rental homes?" | Слово в слово на The Colony |

Свои только 3, 5 и 7. Схема FAQPage расходится со страницей в ответе 6. Страница: "Yes, nights and weekends carry an emergency fee that depends on the hour, and you’ll know the number before we head your way." Схема: "Yes, nights and weekends carry an emergency fee that depends on the hour. You will know the exact number before we head your way."

### 3. Два отзыва, полностью

Заголовок H2, строка "Google reviews from local homeowners.", две карточки. В карточке три ссылки на один короткий адрес Google (картинка, имя, подпись). Оба есть в `reviews/all-reviews.csv` (Google, профиль Plano, 5 звёзд, `on_old_site` = `/plumber-carrollton-tx/`) и в `reviews/ledger.md` за этой страницей.

#### 3.1. Tyler Sommers

- Текст: "Great price and response time for water heater replacement. Our water heater decided to explode and the team showed up within an hour to get everything situated and prevent further leaks. They were able to come the very next day to replace our water heaters. Clear pricing and excellent response time in Carrollton, TX."
- Подпись: "★★★★★ · Local Guide Level 4 · Carrollton, TX · June 2026 · Google"
- Ссылка на странице: https://maps.app.goo.gl/uM3XbnK3iR2ey3mS7?g_st=ic
- Архив: 2026-06-17, https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sCi9DQUlRQUNvZENodHljRjlvT2tsS2JUVjJlSFpCWmxGbVMwdzJha2xuVFhScWIzYxAB!2m1!1s0x0:0xccc66184bdaf3a93
- Сверка: текст знак в знак, месяц совпадает. Город назван в отзыве. "showed up within an hour", "the very next day": слова клиента, по решению Дениса от 2 октября остаются.

#### 3.2. Paula Thompson

- Текст: "BIG 5 STARS for FPP they came through above and beyond the call! I called them around 3:30pm and they answered the phone and I described my dilemma, gasket blow out in shower tub. I mean it was full on in the tub! FPP called me back in about 20 minutes and said their man would be there in 40 minutes. He arrived on time! He was very descript and concise on conveying the possible outcomes and pricing on rectifying the problem. he showed me the failed part and left to go and get the new replacement part. Once back he had me repaired within 25 minutes! He also made an adjustment on my toilet and stopped a small leak! Yes I would recommend FPP to my friends! Larry R. & Paul T. Carrollton, Tx."
- Подпись: "★★★★★ · Local Guide Level 2 · Carrollton, TX · January 2026 · Google"
- Ссылка на странице: https://maps.app.goo.gl/hpof5QYZdm6kXbvL9?g_st=ic
- Архив: 2026-01-08, https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sCi9DQUlRQUNvZENodHljRjlvT25jMFVWcHZObTFxVHpaRWRVdFdSelF3UmtkUFQxRRAB!2m1!1s0x0:0xccc66184bdaf3a93
- Сверка: все слова совпадают; в архиве три переноса строки и двойной пробел в "Yes I  would", на странице одной строкой. Месяц совпадает. Город назван в отзыве. Аккаунт Paula Thompson, а подписан текст "Larry R. & Paul T.". Цифры времени (20, 40, 25 минут) это слова клиента. Дениса по имени не называет, говорит о "FPP".

#### 3.3. Общее

- Уровни Local Guide (4 и 2) только на странице, в архиве колонка пустая: не проверить. Порядок в подписи не по правилу 11 (город должен идти до Local Guide).
- На новом сайте ни один не стоит: нет в `site-ledger.md` (40 авторов, 14 страниц), нет в `site-reviews.json` (ключа `/plumber-carrollton-tx/` нет), нет среди двенадцати и трёх запасных главной, нет в `proposed-placement.md` и в `site/src`. Копий на Thumbtack нет; строка Thumbtack "Tyler S." 2022-06-29 это другой текст ("I didn't end up going with Denys..."). Оба свободны.
- Во всём архиве (407 строк) Carrollton в тексте отзыва только у этих двоих, так что по правилу «отзыв с городом стоит на странице города» оба для Carrollton. Лучше подходит Tyler Sommers (город, water heater replacement, "the team"); Paula Thompson тоже годится.
- Картинки карточек это копии аватаров авторов на WordPress (`IMG_5684.jpg`, буква "T"; `Paula-Thompson-Google-Review.png`, собака).
- В новом файле метка `<!-- reviews -->` и заголовок блока есть, отзывов для страницы в `site-reviews.json` нет.

### 4. Фото на живой странице

| Файл | Alt | Фото с работы? |
|---|---|---|
| `/wp-content/uploads/2024/12/fpp-logo-1-1024x563.png` (2 раза) | "FPP Plumbing Logo" | Нет, логотип |
| `/wp-content/uploads/2025/05/photo_2025-05-15_20-41-51.jpg` (1280 на 720) | "Plumbing van outside a home in Carrollton, TX" | Нет, фургон; главное фото, OG и картинка схемы |
| `/wp-content/uploads/2026/08/IMG_5684.jpg` | "Tyler Sommers Google Review" | Нет, аватар |
| `/wp-content/uploads/2026/08/Paula-Thompson-Google-Review.png` | "Google review from Paula Thompson for FPP Plumbing" | Нет, аватар |
| знак BBB `seal-dallas.bbb.org/...91348602.png` | "FPP Plumbing, LLC BBB Business Review" | Нет |

Фото фургона я открыл (копия в `site/public/wp-content/uploads/2025/05/`): белый фургон сбоку на улице с кирпичными домами, на борту "EMERGENCY SERVICE 24/7", "FULLY LICENSED & INSURED", "980.899.7997", на крыле "M-38532" (как на фургоне страницы Plano, с M-44816 не совпадает, в проекте не объяснено). Номерного знака и номеров домов не видно. Город подтверждает только alt. В `photos/index.csv` файла нет, стоит только на этой странице, грузится «лениво», хотя на первом экране.

Фото с работ и видео нет. Для справки: в `photos/captions-en.csv` 10 фото с городом Carrollton (6, 27, 42, 57, 58, 144 до 148), у восьми записана эта страница: водонагреватель Bradford White, PRV в стене, перепаянный стык slab leak (42), слив раковины до и после, смеситель душа.

### 5. Ссылки

Со страницы в тексте 15 внутренних, внешних 0 (таблица B.1): "leak detection" (2 раза), "plumber near me" на главную, "PRV replacement" (2 раза), "slab leak repair", "water line repair", "drain cleaning", "main line service" (`/drain-services/`), "water heater repair" (`/water-heaters/`), "toilet repair", "shower valve repair" (`/fixture-installation-repair/`), "garbage disposal repair", "shut-off guide", "emergency plumbing". Из 13 услуг SERVICE_ORDER нет в тексте hose bib и expansion tank (`/water-heater-repair-frisco-mckinney/`). Внешней ссылки на официальный источник нет (правило городской страницы). На другие города ссылок нет (правильно). Шаблон: 103 внутренних (меню три раза, кнопки, подвал), 25 внешних (соцсети, `tel:`, шесть ссылок на отзывы, "Found us", почта, BBB); Yelp, Thumbtack, Nextdoor, профилей Google нет (таблица B.2).

На страницу с 63 других (таблица C): шаблон "Carrollton" 3 раза в меню на 62 страницах, на главной 4 плюс пункт с полным названием. Из подвала ссылки нет (офиса нет). Анкоры: "Carrollton" 188, "plumber in Carrollton" 4, "Carrollton, TX" 1, полное название 1. В тексте ссылаются 6 страниц: emergency, slab leak, leak detection, water lines ("plumber in Carrollton"), contact ("Carrollton, TX" в списке), water heater repair ("Carrollton" в списке); на новом сайте эти шесть стоят. 8 из 13 страниц услуг в тексте не ссылаются. Постов и гайдов про Carrollton нет. Без ссылки город назван на старой главной, на hose bib и в замороженном гайде: "If you’re in an older part of Plano, Carrollton, or Richardson, this buried-box setup is what you’ve got".

Для страницы slab leak: там Carrollton "on the Denton County side", а город лежит в трёх округах (пункт 7).

### 6. Что идёт против CLAUDE.md, дословно

#### 6.1. Обещания времени в своих словах

- Последняя строка: "Plumbing problem in Carrollton? Don’t wait. Call or text us and we’ll handle it today." Обещание «сегодня», на новом сайте стоит.
- FAQ 3: "Usually yes. Standard units stay stocked, so a morning call typically means hot water by evening, with permit and inspection handled when the city requires them." Срок «к вечеру».
- Не нарушение: "Our emergency plumbing line is answered by a person at any hour, and an active leak or a backing up main goes to the top of the schedule, because in Carrollton the damage bill grows faster than the plumbing bill." (совпадает с фактами); "two minutes there beats an hour of guessing" (про чтение гайда).
- Цифры времени в отзывах: слова клиентов, остаются.

#### 6.2. Цены

- $49 по правилу: "Weekdays it’s a $49 service call, and it rolls into the job if you move forward. You hear the full price before any work starts, and the quoted price is the final price."
- "Details and pricing on our PRV replacement page." Обещает цены на другой странице.
- FAQ 2: "...or a bill that crept up thirty dollars without anyone changing habits." Не наша цена, но цифру никто не подтверждал.
- FAQ 6: "Yes, nights and weekends carry an emergency fee that depends on the hour, and you’ll know the number before we head your way." Нет праздников и слов «по телефону до выезда».
- Схема: `priceRange` "$$".

#### 6.3. Tankless, reroute, hydro jetting, гарантия, Owner

Tankless, reroute, hydro jetting, warranty, guarantee: ноль. Слово owner, FAQ 8: "We take the tenant call directly, keep the owner out of the middle of it, and send photos with the invoice so nobody has to take anyone’s word for what happened inside the house." Это хозяин сдаваемого дома, но слово "owner" на сайте не используется.

#### 6.4. Другие города и офис

- В тексте других городов нет. "North Texas clay" это регион.
- Схема, `areaServed`: "Carrollton", "Addison", "Farmers Branch", "Lewisville", "The Colony". Addison и Farmers Branch вне десяти городов (оба в FORBIDDEN_CITIES), Lewisville и The Colony соседи.
- Схема, описание организации: "surrounding North Dallas communities" и "Texas Master Plumber License M-44816" (снятая формулировка).
- Офис: текст офиса в Carrollton не обещает, но в схеме отдельный бизнес LocalBusiness плюс Plumber, `@id` `/plumber-carrollton-tx/#business`, имя "FPP Plumbing - Plumber in Carrollton, TX", с адресом, точкой карты и телефоном офиса Plano. По правилу бизнес один (`#organization`), страница без офиса называет город в areaServed. Подробно: таблица D.
- Alt фото "Plumbing van outside a home in Carrollton, TX": город не подтверждён.

#### 6.5. Телефоны, FAQ, заголовки

- Телефонов в абзацах и ответах FAQ нет (шапка, подвал, нижняя панель как H2).
- FAQ тегом H3: все восемь.
- "Water Leak Detection in Carrollton": услуга плюс город, раздел описывает метод поиска (тест счётчика, отсечение, давление, влажность), а метод принадлежит странице leak detection (правило 9). "Slab Leaks, Handled Honestly" и "Water Pressure and the PRV": целые разделы объяснений услуг, на городской странице это короткий абзац со ссылкой.
- Title с тремя ключами услуг, а карта ключей запрещает "slab leak repair carrollton". Менять после сверки с Search Console (раздел 2). H2 с "plumber in Carrollton" нет ни одного. Запрет «услуга плюс город» записан для главной, для города это список на сверку.

#### 6.6. Остальное

- Тире: только дефис с пробелами в H1.
- Ссылка на главную: анкор "plumber near me" верный, но в третьем абзаце первого раздела, не в последнем абзаце вступления, и привязан к течи (правило 6): "If you searched for a plumber near me because the bill jumped and nothing looks wrong, this is the part most companies skip."
- Вопросы вместо ответа: три в описании, H2 "Water Coming In Right Now?", "Plumbing problem in Carrollton? Don’t wait."
- "honest" три раза: "Slab Leaks, Handled Honestly", "One honest note that saves people money", "it is the honest answer instead of pretending there is a shortcut"; и "this is the part most companies skip".
- Утверждения о компании без опоры в CLAUDE.md ("working Carrollton constantly", "calls like these fill our week", "A large share of our Carrollton schedule is rental property.", "send photos with the invoice", "Standard units stay stocked") и регулировка PRV ("If it responds to adjustment and holds steady, we adjust it."; в CLAUDE.md только замена): список вопросов в пункте 9.
- Нет блока Дениса, строки лицензии в тексте, фото с работ, историй. Подвал: "all rights reserved © 2024-2026 License M - 44816".
- Схема: два Organization с одним `@id`, часы 00:00 до 23:59 без часов офиса, `legalName` "FPP Plumbing, LLC", sameAs без Google, Yelp, Thumbtack, Nextdoor, крошки "Main"; узлов Person, Review, Service нет.

### 7. Улицы, районы, ориентиры

Улиц, районов и ориентиров на странице нет (проверено поиском: Trinity Mills, Josey, Belt Line, Frankford, Keller Springs, Hebron, Rosemeade, Old Denton, Castle Hills, Indian Creek, Square, Road, Parkway, Highway, County: ноль). Мест два, общими словами.

Сайт города cityofcarrollton.com на мои запросы отвечал 403 (главная, история, перерасчёт за течь): could_not_open. Ниже то, что видно 3 октября 2026 в выдаче поиска по этому сайту; сами страницы не открыты.

| Предложение | Слово | Что это | Вывод |
|---|---|---|---|
| "We are FPP Plumbing, licensed plumbers working Carrollton constantly, from the older streets near downtown to the newer sections up north." | downtown | На сайте города раздел Downtown Carrollton ("Historic Downtown Carrollton Parking", "Sounds on the Square", "The History of the Downtown Carrollton Square"); по выдержке площадь ограничена улицами Broadway, 4th, Elm и West Main, рядом район Carrollton Heights (дома 1910 до 1960, страница "Historical Designations") | Настоящее место в Carrollton. Какая там сантехника, знает только Денис |
| то же | up north | По выдержке город лежит в северо-западной части округа Dallas, юго-восточной части Denton и юго-западной части Collin | Север есть; что он «новее», в официальной выдаче не сказано. Спросить Дениса |
| "Carrollton sits on the same North Texas clay as everyone else, and clay moves." | North Texas | Регион | Можно оставить |

Для раздела 6a: в выдаче по сайту города (страницы "Water Leak Adjustment Policy" и "FAQs - Water Billing") сказано, что ответственность города идёт до задней стороны узла счётчика ("up to the back of the meter loop"), дальше частная собственность. Это совпадает со словами страницы "the line from the meter to your house is yours, and the line before the meter belongs to the city". Там же: на ремонт течи может понадобиться разрешение, для перерасчёта нужна форма Certification of Water Leak Repair с копией разрешения в течение 90 дней. Перед переносом на страницу эти страницы надо открыть и процитировать.

[Критик, 3 октября 2026: копии Internet Archive обеих страниц открыты (Leak Adjustments от 12 апреля 2026, FAQs - Water Billing от 14 мая 2026, по одному запросу). Слов "meter loop" и "back of the meter" там нет. Есть: "faulty plumbing lines and/or fixtures on private property", "Permits may be required for repairs performed", "a copy of the permit must be submitted within 90 days" и совет смотреть "flow indicator" на счётчике. Значит, фраза "up to the back of the meter loop" осталась только в выдаче поиска и не подтверждена; граница по воде дана в части 6 как вывод (city-d1, страница о свинце), прямой фразы города о ней нет. Таблица выше (downtown, улицы площади, Carrollton Heights, округа) тоже из выдачи поиска: в проверенные списки 6.0 не входит, на страницу без сверки не ставить.]

### 8. Точечные правки, которые уже стоят на новом сайте

- POINT_FIXES в `tools/build_launch_content.py` для `/plumber-carrollton-tx/`: ни одной. Carrollton в файле только в списке десяти городов и в правке для замороженного гайда (убрать Richardson); гайд в FROZEN, и на новом сайте "Plano, Carrollton, or Richardson" стоит.
- `site/src/data/launch-changes.csv`, две строки: H1 "Plumber in Carrollton, TX - We Find the Leak Before Anyone Digs" стал "Plumber in Carrollton, TX: We Find the Leak Before Anyone Digs"; виджеты отзывов заменены меткой `<!-- reviews -->`. Строк «flag not changed» нет.
- Новый файл: title и описание как на живой; FAQ в шапке файла (ответ 6 в словах страницы); список услуг обычным списком; фото фургона в тексте и как OG.
- Ещё НЕ исправлено: "we’ll handle it today", "a morning call typically means hot water by evening", "keep the owner out of the middle of it", "Details and pricing on our PRV replacement page.", место ссылки на главную, alt фургона "in Carrollton, TX", нет официальной ссылки, нет отзывов, шаблонные вопросы FAQ.

### 9. Что стоит сохранить как местную суть

Местного на странице мало: почти весь текст (счётчик, slab leak, PRV) общий и подошёл бы любому городу. Связано с Carrollton (всё это старый текст, Денис не подтверждал):

- "We are FPP Plumbing, licensed plumbers working Carrollton constantly, from the older streets near downtown to the newer sections up north."
- "Carrollton has houses from very different decades, and the work follows the house. In the newer sections the plumbing is young and the failures are early ones: builder grade cartridges, fill valves, disposals that were never going to last. In some of the older sections the drain lines are cast iron, and cast iron ages from the inside out."
- "Roots work into a joint until a slow drain turns into a full stoppage over a season or two."
- "Some older houses here do not have a usable one, and in that case we pull a toilet and run equipment through the flange to reach the main, then reset it properly with a new wax ring."
- "the line from the meter to your house is yours, and the line before the meter belongs to the city. If the wet spot sits on their side, we will tell you to call them instead of billing you for their problem." (совпадает с выдержкой с сайта города) [Критик: выдержка в копиях страниц города не нашлась, см. конец раздела 7; опора только city-d1 в части 6, как вывод]
- "A large share of our Carrollton schedule is rental property. We take the tenant call directly, keep the owner out of the middle of it, and send photos with the invoice..." (без слова owner)
- "with permit and inspection handled when the city requires them" (что требует город, раздел 6a)
- "anything above 80 PSI quietly chews through supply lines, cartridges, and water heaters from the inside" (совет Дениса)
- Из отзывов: замена водонагревателя в Carrollton (Tyler Sommers), прокладка смесителя ванны и унитаз (Paula Thompson). Из архива фото: настоящие работы в Carrollton, в том числе slab leak (42).

Метод поиска, slab leak и PRV принадлежат своим страницам (правило 9). Дословно ничего не переносить: текст пишется заново и проверяется на повторы.

Никто не подтверждал (спросить Дениса): что в Carrollton неделя занята течами и работаем там «постоянно»; что фото идут с каждым счётом (в CLAUDE.md фото больших работ и по просьбе); старые дома у даунтауна и новые на севере, чугун в старых, дешёвые детали застройщика в новых; дома без рабочего клинаута и чистка через снятый унитаз; доля сдаваемых домов среди вызовов; регулировка PRV; запас водонагревателей и замена в тот же день; как часты slab leak в Carrollton (цифры Дениса в CLAUDE.md есть только по Frisco); "thirty dollars" и "twenty seconds"; снят ли фургон в Carrollton; уровни Local Guide.

### 10. Что не удалось проверить

- Сайт города отвечает 403: официальные факты пункта 7 взяты из выдачи поиска, страницы не открыты.
- Уровни Local Guide по архиву не проверить; что значит "M-38532" на фургоне, в проекте не записано; город фото фургона по снимку не определить.

## 2. Search Console

Файл раздела: `docs/briefs/carrollton/2-gsc.md`, вставлен целиком. Заголовок файла: «2. Search Console: страница Carrollton (/plumber-carrollton-tx/)».

Полные таблицы рядом, в бриф не вставлены: `carrollton-gsc-table-3m.md` (все запросы страницы за 3 месяца, 1 июля до 28 сентября 2026), `carrollton-gsc-table-16m.md` (все запросы за 16 месяцев, 31 мая 2025 до 28 сентября 2026), `carrollton-gsc-headings.md` (что держит title, description, H1, каждый H2 и каждый вопрос FAQ, по запросам), `carrollton-gsc-extra.md` (таблицы A до I, на которые ссылается текст: семейства запросов, запросы без точной фразы, главная, другие страницы сайта, услуги и хозяева по карте ключей, запросы без города, другие места, слова запросов, отложенные слова). Скрипты подсчёта лежат во временной папке помощника, в проект не входят.

Собрано 3 октября 2026. Источники: source/gsc/ (page-query-3m.csv и -16m.csv от 30 сентября 2026, Pages.csv, Chart.csv, page-query-coverage.csv), seo/keyword-map.md и .csv, seo/cannibalization-findings.md; живой текст: source/crawl/pages/plumber-carrollton-tx.json (обход 30 сентября, правка страницы 17 августа 2026). В ячейках: показы · место · клики (клики, где есть).

Метод брифа Plano, скрипты скопированы под Carrollton (`gsc_carrollton_lib.py`, `gsc_carrollton_live.py` в scratchpad/night/carrollton/gsc). Отличия: двадцатки вместо 40 и 30; «carlton» считается Carrollton с ошибкой; leak detection проверяется раньше slab leak (правило 9); мягкая проверка смотрит и description. Рядом: `carrollton-gsc-table-3m.md`, `carrollton-gsc-table-16m.md` (все запросы), `carrollton-gsc-headings.md`, `carrollton-gsc-extra.md` (таблицы A до I). В одном запросе о чужой компании улица и дом скрыты.

### Главное коротко

1. За 16 месяцев 2 клика, оба за последние 3 месяца, оба с известным запросом: «plumber carrollton» и «plumber carrollton tx» (за 3 месяца 36 · 25.2 · 1 и 9 · 29.3 · 1).
2. Страницу показывают по другим запросам, чем раньше. До июля (13 месяцев) запросы с carrollton: 40,251 показ, место 54.6, почти половина общие (18,427). Последние 3 месяца: 2,188 показов, место 21.4, и 83% из них (1,821) это leak detection и slab leak. Общие упали до 131 показа, но оба клика с них.
3. Leak и slab держит title ("Leak Detection, Slab Leak") и H2 "Water Leak Detection in Carrollton". Карта ключей запрещает странице «slab leak repair carrollton», а страница slab leak по этим запросам за 3 месяца не показывалась. Решает Денис.
4. "Plumber Carrollton, TX" в начале title и "Plumber in Carrollton, TX" в начале H1 держат общие запросы и оба клика.
5. Plano выше по 15 запросам с carrollton (424 показа за 3 месяца): 162 показа по правилу проекта карточка офиса, 262 обычная выдача, из них 232 «plumber carrollton tx» (Plano 13.2, Carrollton 29.3). Главная мешала до июля.
6. Слово в слово запросы с городом стоят только в title, H1, description и H2 "Carrollton Plumbing FAQ"; «slab leak repair carrollton», «emergency plumber carrollton», «faucet repair carrollton» нет нигде. Чужие места (Hebron 342 показа за 16 месяцев, Denton, Rollingwood, Prosper) в тексте не названы.

### Как считали

Правило tools/gsc_page_table.py (инструмент не запускался): запрос покрыт, когда каждое значимое слово стоит в своём тексте страницы (заголовки, текст, FAQ, строка над отзывами, закрывающая строка; отзывы отдельно); in, tx, near, me не в счёт, множественное как единственное; чужие места, не наши услуги, оценочные слова, опечатки и голосовые слова отложены. Правило «карта» (место 3 и выше без своего города) касается только страниц Frisco и Plano, у Carrollton карточки нет.

**Второй счёт.** Модуль csv, разбор строк без него в скрипте (с остановкой при расхождении), awk и разбор строки с конца дали одно: 3 месяца 98 запросов, 2 клика, 2,450 показов, место 21.24; 16 месяцев 189, 2, 43,821, 52.78; совпадает с page-query-coverage.csv. Восемь строк сверены с файлом руками (например «plumber carrollton tx» 9 · 29.33 · 1, «plumber hebron tx» 142 · 30.47): совпало. Семейства раздела 1 в сумме дают 2,188 и 40,251.

### 1. Итоги за 3 и 16 месяцев

| Период | Запросов | Клики | Показы | Место | Итог Google со скрытыми |
|---|---|---|---|---|---|
| 3 месяца (1 июля до 28 сентября 2026) | 98 | 2 | 2,450 | 21.2 | 2 клика, 2,631 показ, место 21.32 |
| 16 месяцев (31 мая 2025 до 28 сентября 2026) | 189 | 2 | 43,821 | 52.8 | 2 клика, 45,336 показов, место 52.52 |

Известен запрос у 100% кликов, у 93% и 97% показов. 13 месяцев до июля (вычитанием): известные 41,371 показ, место 54.7; итог Google 42,705; кликов 0.

| Группа | 3 мес: запросов · показы · место | 16 мес |
|---|---|---|
| carrollton | 77 · 2,188 · 21.4, 2 клика | 153 · 42,439 · 52.9, 2 клика |
| без города | 18 · 250 · 20.4 | 23 · 996 · 54.1 |
| другой город | 1 · 3 · 16.3 | 11 · 365 · 34.5 |
| бренд (fpp) | 2 · 9 · 3.4 | 2 · 21 · 10.3 |

Запросы с carrollton по месту, 3 месяца: от 10 до 20 стоят 17 (1,172 показа), от 20 до 50 стоят 53 (1,001, оба клика), ниже 50 стоят 7 (15); в десятке ни одного. За 16 месяцев 101 запрос (27,105 показов) стоял ниже 50. В месяц до июля около 3,096 показов с carrollton, после около 729. У всего сайта показы тоже упали: 201,829 в апреле 2026 и 81,307 в сентябре по 28-е (Chart.csv).

| Семейство с carrollton (таблица A) | 3 мес: запросов · показы · место | 13 мес до июля |
|---|---|---|
| leak detection | 8 · 990 · 23.1 | 1,275 · 63.6 |
| slab leak (и опечатка sab) | 7 · 831 · 15.6 | 4,366 · 51.4 |
| общие (plumber carrollton и варианты) | 22 · 131 · 37.9, 2 клика | 18,427 · 54.2 |
| leak repair, pipe break | 3 · 112 · 23.9 | 2,035 · 60.0 |
| emergency, 24 hour, same day | 6 · 34 · 21.8 | 5,471 · 54.0 |
| faucet, shower | 4 · 22 · 22.6 | 3,434 · 51.0 |
| water line, water heater, остальные услуги, не наше | 27 · 68 | 5,243 |

### 2. Первые 20 запросов каждого периода и запросы с кликом

34 запроса, первые 20 строк это двадцатка за 16 месяцев; двадцатки дают 2,161 показ из 2,450 и 22,461 из 43,821. Звёздочка: запрос без города. Последняя колонка это раздел 5: «точно» слово в слово, «мягко» без in и tx и без разницы в числе, «перест.» те же слова в другом порядке.

| Запрос | № 3м | № 16м | 3 мес | 16 мес | Слова | Фраза целиком |
|---|---|---|---|---|---|---|
| plumber carrollton | 16 | 1 | 36 · 25.2 · 1 | 2,124 · 47.4 · 1 | да | точно: title |
| slab leak repair carrollton | 3 | 2 | 280 · 16.1 | 1,512 · 46.7 | да | нет |
| emergency plumber carrollton |  | 3 | 6 · 18.3 | 1,425 · 54.7 | да | нет |
| plumber in carrollton tx |  | 4 | 2 · 35.0 | 1,272 · 47.0 | да | точно: H1 |
| carrollton plumber |  | 5 | 3 · 29.0 | 1,244 · 56.3 | да | мягко: description |
| plumber in carrollton |  | 6 | 9 · 49.6 | 1,243 · 57.1 | да | точно: H1 |
| slab leak repair carrollton tx | 4 | 7 | 231 · 12.9 | 1,214 · 47.9 | да | нет |
| plumber carrollton tx |  | 8 | 9 · 29.3 · 1 | 1,187 · 44.0 · 1 | да | точно: title |
| faucet repair carrollton |  | 9 | 2 · 16.5 | 1,103 · 56.5 | нет faucet | нет |
| carrollton plumbers |  | 10 |  | 1,102 · 61.0 | да | точно: description |
| carrollton tx leak detection | 1 | 11 | 398 · 19.9 | 1,014 · 49.0 | да | точно: title (через "\|") |
| carrollton slab leak repair | 5 | 12 | 162 · 14.4 | 987 · 42.8 | да | нет |
| carrollton plumbing service |  | 13 | 2 · 44.0 | 970 · 52.2 | да | перест.: H2 |
| plumber carrollton texas |  | 14 | 2 · 49.5 | 943 · 55.5 | да | мягко: title, H1 |
| carrollton tx sab leak repair | 9 | 15 | 65 · 18.6 | 933 · 48.0 | опечатка | нет |
| carrollton tx faucet repair |  | 16 | 16 · 23.8 | 879 · 44.7 | нет faucet | нет |
| emergency plumber carrollton tx |  | 17 | 6 · 24.8 | 839 · 48.8 | да | нет |
| plumbers in carrollton tx |  | 18 | 5 · 47.8 | 831 · 50.9 | да | мягко: title, H1 |
| water line repair carrollton |  | 19 | 2 · 32.5 | 823 · 57.0 | да | нет |
| carrollton tx emergency plumbing |  | 20 | 17 · 21.6 | 816 · 51.2 | да | нет |
| carrollton leak detection | 2 |  | 366 · 25.0 | 596 · 41.8 | да | мягко: title |
| slab leak plumber carrollton | 6 |  | 85 · 20.3 | 543 · 39.6 | да | нет |
| slab leak detection carrollton | 7 |  | 74 · 22.3 | 228 · 42.3 | да | перест.: title |
| foundation leak detection carrollton | 8 |  | 70 · 30.5 | 76 · 31.9 | нет foundation | нет |
| leak repair carrollton | 10 |  | 57 · 23.0 | 121 · 21.4 | да | нет |
| leak detection services carrollton | 11 |  | 53 · 25.2 | 62 · 27.2 | да | нет |
| leak repair carrollton tx | 12 |  | 45 · 23.5 | 356 · 42.9 | да | нет |
| google find me a plumber * | 13 |  | 44 · 38.2 | 737 · 66.1 | голосовой | нет |
| alexa find me a plumber * | 14 |  | 39 · 35.1 | 82 · 32.7 | голосовой | нет |
| slab leak repair near me * | 15 |  | 38 · 9.9 | то же | да | мягко: текст |
| slab leak detection near me * | 17 |  | 36 · 10.8 | то же | да | перест.: title |
| carrollton tx pluming | 18 |  | 29 · 43.9 | 205 · 55.5 | опечатка | нет |
| water leak repair near me * | 19 |  | 27 · 7.0 | то же | да | нет |
| water leak detection near me * | 20 |  | 26 · 8.2 | то же | да | мягко: H2 |

**С кликом** только «plumber carrollton» и «plumber carrollton tx», по одному клику, оба за последние 3 месяца.

Запросы с carrollton за 3 месяца: все слова стоят у 58 (2,051 показ из 2,188), частично у 8 (97), не наша услуга у 11 (40). Нет слов (3 месяца, в скобках 16): foundation 73 (79), faucet 22 (3,348), break 0 (1,549), 24 0 (227), contractor 1 (201), bathroom 0 (133). Таблица H.

### 3. Главная по запросам с carrollton

За 3 месяца у главной 2 запроса с carrollton, 10 показов, место 1.0, оба emergency (раздел 6). За 16 месяцев 40 запросов, 1,515 показов, место 38.0, кликов нет, из них 1,505 до июля. Из 35 общих запросов главная выше по 29 (у неё 1,355 показов, у Carrollton по всем 35 запросам 16,666). Только у главной 5 запросов, 93 показа (крупнейший «website for plumbers carrollton» 55, не услуга). Крупнейшие строки главной: emergency с carrollton (раздел 6) и «carrollton tx garbage disposal repair» 170 · 33.8 (Carrollton 215 · 62.1). Все строки: таблица C.

### 4. Что держат title, H1, H2 и вопросы FAQ

Заголовок «держит» запрос, когда в нём стоят все значимые слова запроса; «фраза целиком» значит подряд, без in и tx. Только запросы с carrollton, запросов · показы. По запросам: `carrollton-gsc-headings.md`.

| Заголовок | Все слова, 3 мес | 16 мес | Фраза целиком, 3 мес | 16 мес | Только он, 3 мес | 16 мес |
|---|---|---|---|---|---|---|
| title "Plumber Carrollton, TX \| Leak Detection, Slab Leak & PRV Repair" | 22 · 1,799 | 31 · 19,958 | 12 · 843 | 15 · 12,230 | 8 · 939 | 9 · 4,967 |
| description "... Licensed Carrollton plumbers find it ..." | 11 · 82 | 17 · 13,349 | 1 · 3 | 5 · 2,731 | 0 | 0 |
| H1 "Plumber in Carrollton, TX - We Find the Leak Before Anyone Digs" | 11 · 82 | 17 · 13,349 | 10 · 79 | 12 · 10,618 | 0 | 0 |
| H2 "Water Leak Detection in Carrollton" | 4 · 785 | 6 · 1,833 | 2 · 21 | 3 · 221 | 1 · 7 | 1 · 191 |
| H2 "Our Plumbing Services in Carrollton" | 5 · 11 | 13 · 2,693 | 0 | 4 · 91 | 1 · 2 | 7 · 1,124 |
| H2 "Carrollton Plumbing FAQ" | 4 · 9 | 6 · 1,569 | 2 · 3 | 2 · 230 | 0 | 0 |
| H2 "What Carrollton Homeowners Say About FPP Plumbing" | 4 · 9 | 6 · 1,569 | 0 | 0 | 0 | 0 |
| вопрос "How much does a plumber cost in Carrollton, TX?" | 11 · 82 | 17 · 13,349 | 0 | 0 | 0 | 0 |

Ничего с carrollton не держат H2 "Slab Leaks, Handled Honestly", "Water Pressure and the PRV", "What Else We Run Into Here", "Water Coming In Right Now?" и семь вопросов FAQ из восьми ("Can you replace a water heater the same day in Carrollton?" без слова repair). Без заголовка 49 запросов с carrollton за 3 месяца (371 показ) и 108 за 16 (19,597): emergency, faucet, water line, pipe break, water heater, sewer.

**Что нельзя потерять** (3 месяца, в скобках 16):

1. "Plumber Carrollton, TX" в title и "Plumber in Carrollton, TX" в H1: оба клика и общие запросы (раздел 5). В тексте (не в заголовках) этих фраз нет.
2. "Leak Detection" в title и H2 "Water Leak Detection in Carrollton": «carrollton tx leak detection» 398 (1,014), «carrollton leak detection» 366 (596); только H2 держит «water leak detection carrollton» 7 (191). Страница leak detection по carrollton почти не показывается (3 показа за 16 месяцев).
3. "Slab Leak" в title, только он (939 и 4,967): «slab leak repair carrollton» 280 (1,512), «slab leak repair carrollton tx» 231 (1,214), «carrollton slab leak repair» 162 (987), «slab leak plumber carrollton» 85 (543), «slab leak detection carrollton» 74 (228), «leak repair carrollton» и «... tx» 57 и 45. Против запрета карты: вопрос к Денису.
4. H2 "Our Plumbing Services in Carrollton", только он: «carrollton plumbing service» 2 (970) и ещё 6 вариантов plumbing service(s), всего 1,124 за 16 месяцев.
5. H2 "Carrollton Plumbing FAQ": точно «carrollton plumbing» 2 (183), «carrollton tx plumbing» (47). Description "Licensed Carrollton plumbers": точно «carrollton plumbers» (1,102). Вопрос "How much does a plumber cost in Carrollton, TX?" единственный держит общие запросы (на новом сайте жирный текст).
6. Предложение с "plumber near me" и ссылкой на главную (near me: 13 запросов, 162 показа, место 10.2), одно по правилу 6. "FPP Plumbing" в H2 отзывов и вступлении: «fpp plumbing» 8 · 1.9 (20).

"PRV Repair" в title не держит ничего: запросов про PRV с carrollton нет.

### 5. Фраза целиком

Из 34 запросов раздела 2: точно 6, только мягко 6, только перестановка 3, нигде 19 (у 28 запросов с carrollton 6, 4, 2, 16).

- Слово в слово стоят 10 запросов с carrollton и бренд: «plumber carrollton», «plumber carrollton tx», «plumber carrollton, tx» (title), «plumber in carrollton», «plumber in carrollton tx» (H1), «carrollton plumbers» (description), «carrollton plumbing» (H2 FAQ), «carrollton tx leak detection» и «carrollton+tx+leak+detection» (title, только через знак "\|"), «fpp plumbing». На них 464 показа и 2 клика за 3 месяца, 8,178 показов за 16.
- Без точной фразы 71 запрос с carrollton за 3 месяца (1,732 показа) и 144 за 16 (34,281). Крупнейшие: семейство «slab leak repair carrollton» (в title "Slab Leak & PRV Repair", слова не подряд; "slab leak repair" без города только в списке услуг), «emergency plumber carrollton» (в тексте "emergency plumbing line"), «water line repair carrollton» (без города в списке услуг), «faucet repair carrollton». 30 крупнейших: таблица B.

### 6. Запросы с carrollton, где другая страница стоит выше или забирает показы

На сайте за 3 месяца 86 запросов с carrollton, 2,661 показ, из них у Carrollton 2,188; оба клика у Carrollton. За 16 месяцев 164 запроса, 45,480, у Carrollton 42,439. Все строки и итоги по страницам: таблица D.

| Запрос | Другая страница | Она, 3 мес | Carrollton, 3 мес | Она, 16 мес | Carrollton, 16 мес |
|---|---|---|---|---|---|
| plumber carrollton tx | /plumber-plano-tx/ | 232 · 13.2 | 9 · 29.3 · 1 | то же | 1,187 · 44.0 · 1 |
| emergency plumber carrollton | /plumber-plano-tx/; / | 98 · 1.3; 9 · 1.0 | 6 · 18.3 | 98 · 1.3; 509 · 48.3 | 1,425 · 54.7 |
| carrollton tx emergency plumbing | /plumber-plano-tx/; / | 42 · 1.6; 1 · 1.0 | 17 · 21.6 | 42 · 1.6; 149 · 2.0 | 816 · 51.2 |
| emergency plumber carrollton tx | /plumber-plano-tx/; / | 14 · 2.8 | 6 · 24.8 | 14 · 2.8; 225 · 32.1 | 839 · 48.8 |
| emergency drain cleaning carrollton | /plumber-plano-tx/; / | 12 · 1.0 | нет | 12 · 1.0; 20 · 1.0 | нет |

- Plano: 24 запроса, 461 показ, место 8.2, почти всё за 3 месяца; выше Carrollton по 15 (424 показа: 162 в строках на месте 3 и выше, по правилу проекта карточка, и 262 в обычной выдаче), без Carrollton по 8 (36, например «which plumbers in carrollton, tx offer weekend emergency plumbing service?» 13 · 1.8). Живой текст Plano Carrollton не называет.
- Страницы услуг почти не мешают: slab leak 5 запросов, 344 показа, место 79.0, ни разу не выше; garbage disposal («carrollton garbage disposal repair» 124 · 56.2 против 46 · 62.0), water heater repair («expansion tanks repair carrollton» 87 · 49.9 против 5 · 51.0), water heaters, emergency и гайд о сроке службы водонагревателя выше по одному запросу каждая (за 16 месяцев). The Colony: «same day service plumbing carrollton» 95 · 66.9 (Carrollton 46 · 58.1).

### 7. Запросы услуг с carrollton и их хозяин по карте ключей

У Carrollton в keyword-map.csv: главный ключ plumber carrollton tx; вторичные plumber carrollton, carrollton plumber, plumber in carrollton; must not target slab leak repair carrollton (slab leak page). У страниц услуг ключей с carrollton нет, хозяин по их главному ключу; у emergency must not target plumber + city, так что emergency с carrollton ничей. Таблица E.

| Услуга с carrollton | Хозяин | Carrollton, 3 мес | Carrollton, 16 мес | Хозяин, 16 мес |
|---|---|---|---|---|
| общие | Carrollton | 22 · 131 · 37.9, 2 клика | 50 · 18,558 · 54.1 |  |
| leak detection | water-leak-detection | 8 · 990 · 23.1 | 14 · 2,265 · 45.9 | 1 · 3 · 63.3 |
| slab leak | slab-leak-repair | 7 · 831 · 15.6 | 7 · 5,197 · 45.7 | 3 · 324 · 79.4 |
| leak repair, pipe break | ключа нет, ближе water-lines | 3 · 112 · 23.9 | 8 · 2,147 · 58.1 | нет |
| emergency, 24 hour, same day | ничей | 6 · 34 · 21.8 | 15 · 5,505 · 53.8 | 8 · 94 · 76.9 |
| faucet, shower | fixture-installation-repair | 4 · 22 · 22.6 | 6 · 3,456 · 50.8 | нет |
| water line | water-lines | 4 · 6 · 39.8 | 4 · 2,598 · 55.2 | 1 · 9 · 66.1 |
| water heater | water-heaters | 7 · 17 · 23.4 | 14 · 1,564 · 60.2 | нет |
| toilet; sewer line | toilet-repair; drain-services | 1 · 1; нет | 3 · 296; 5 · 290 | нет |
| garbage disposal | garbage-disposal-repair | 1 · 1 | 4 · 263 · 62.0 | 5 · 311 · 57.3 |
| sink, bathroom plumbing | ключа нет | нет | 4 · 188 · 57.7 | нет |
| expansion tank; drain cleaning | water-heater-repair; clogged-drain-cleaning | 2 · 2; 1 · 1 | 2 · 22; 5 · 20 | 1 · 87 · 49.9; нет |

Страницы названы по началу адреса. Главная за 16 месяцев: emergency 14 · 1,140 · 38.6, garbage disposal 4 · 231 · 30.6, общие 16 · 107 · 59.6. PRV и hose bib с carrollton запросов нет. По услугам с carrollton Google ставит только страницу города; по правилам она называет каждую услугу один раз со ссылкой.

### 8. Запросы с другими местами

За 3 месяца один: «plumber hebron tx» 3 · 16.3 (у Plano он же 33 · 1.1, по правилу карточка). За 16 месяцев 11 запросов, 365 показов, место 34.5, кликов нет. Таблица G.

- Hebron, 7 запросов, 342 показа: «plumber hebron, tx» 167 · 37.9, «plumber hebron tx» 142 · 30.5, «plumbing hebron, tx» 14, «emergency plumber hebron, tx» 11 · 15.2 и три мелких. Слова Hebron на странице нет (ни в тексте, ни в схеме, ни в меню), причина не видна; в списке разрешённых мест его нет. [Критик: что связывает Hebron с Carrollton по данным брифа, без вывода о причине показов: город Hebron делит с Carrollton почтовые участки 75010 (в Hebron лежит 2.6% земли участка) и 75007 (0.1%) по файлу Census 2020 (часть 6.2, таблица а); у конкурента Carrollton Plumbing Service "Hebron Pkwy" и "Hebron Corridor" названы местами Carrollton (часть 3, таблица 2.2). Hebron на сайте не называем совсем (часть 6.0).]
- Denton: «prv replacement denton tx» 17 · 29.5, «slab leak plumber denton» 1 · 56.0. Совпадает часть про услугу: PRV и Slab Leak в title. Denton CLAUDE.md называть запрещает; на странице его нет.
- Rollingwood: «plumber rollingwood» 4 · 19.0; на странице нет, причину назвать нельзя.
- Prosper: «plumber in prosper» 1 · 74.0; Prosper только в меню сайта Service Areas.

Других городов из десяти, Park Cities, Dallas и чужих индексов нет (75010 в запросе о чужой компании это индекс Carrollton, таблица Census в docs/briefs/_shared/cities-table-notes-2026-10-03.md). Свой текст страницы чужих мест не называет, убирать нечего.

### 9. Слова, которые на страницу не ставятся

3 месяца: запросов · показы, в скобках 16 месяцев; кликов нет. По словам: таблица I.

- Не наши услуги 14 · 57 (15 · 87): repiping и repipe (34 и 3 за 16 мес), sump pump (17), pool leak repair (13), tankless (9), basement pumping (5), roof leak repair (3), well repair (3). Reroute, hydro jetting и gas не встретились.
- Чужие места (раздел 8). Опечатки: «sab leak» 65 (933), «pluming» 32 (640), «carlton» 10 (112). Голосовые: «google find me a plumber» 44 (737), «alexa ...» 39 (82). FPP с ошибкой (pp, dpp, ppx) 2 · 3 (5 · 8); чужие компании (trapp, fleming brothers, pro fix) 1 · 2 (3 · 7); «site:fppplumbing.com» 1; «best plumbers carrollton» (26); «city of carrollton water» (1).
- Время: «same day service plumbing carrollton» (46) обещанием в наших словах не отвечается. «24-hour plumber carrollton» (155) и «24 hour plumber carrollton tx» (72) только строкой "A licensed plumber is on duty 24/7" и ссылкой на emergency.
- near me: 13 · 162, место 10.2; ключ главной, одно предложение со ссылкой.

### Что из цифр следует для брифа

1. Начало title "Plumber Carrollton, TX" и H1 "Plumber in Carrollton, TX" сохранить.
2. "Leak Detection, Slab Leak" в title и H2 "Water Leak Detection in Carrollton" (83% нынешних показов) против карты ключей: оставить, заменить один к одному или отдать страницам услуг, решает Денис.
3. "plumber in Carrollton", "Carrollton plumber", "plumbers in Carrollton", "Carrollton plumbing" во вступление, первый блок, закрывающий абзац и часть H2. Два H2 с Carrollton, вопрос о цене и "Carrollton plumbers" в description сохранить или заменить один к одному.
4. По одной строке со ссылкой: faucet repair (3,434 до июля), emergency plumber in Carrollton со строкой "A licensed plumber is on duty 24/7" (5,471), water line repair (2,592), broken pipe (2,035), water heater repair (1,547), toilet, sewer line, garbage disposal (295, 290 и 262). [Критик, 3 октября 2026: 3,434, 5,471 и 2,035 это итоги семейств таблицы раздела 1 (faucet вместе с shower; emergency вместе с 24 hour и same day; leak repair вместе с pipe break). Запросы, где на странице нет самого слова: faucet 3,348 показов за 16 месяцев, pipe break 1,549 за 16 месяцев, все до июля (пересчёт по `source/gsc/page-query-16m.csv`).]
5. Одно предложение с «plumber near me» и ссылкой на главную. Места раздела 8 и слова раздела 9 не ставить.

### Что проверить не удалось

- Почему показы ушли от общих запросов к leak и slab: по дням выгрузка не делит, страница правилась 17 августа 2026, прежнего title в прочитанных файлах нет.
- 7% показов за 3 месяца (181 из 2,631) Google скрывает.
- Карточка или обычная выдача у Plano: выгрузка не отделяет, деление по правилу проекта. Почему Plano выше по «plumber carrollton tx», по тексту не видно. Причина показов по Hebron и Rollingwood не видна; сайт заново не открывался.

## 3. Конкуренты

Файл раздела: `docs/briefs/carrollton/3-competitors.md`, вставлен целиком. Заголовок файла: «3. Конкуренты по Carrollton: десять страниц из выдачи».

Рядом, в бриф не вставлены: `3-competitors-details.md` (по каждой из десяти страниц все H2, description, местные факты, цены, гарантия, приезд; список из 104 районов у Barbosa; страница, которая не открылась; небрежности конкурентов) и `3-competitors-serp.md` (первые 30 мест по каждому из трёх запросов с отметкой, что взято и почему пропущено; сверка веб-поиском). Тексты десяти страниц для проверки черновика на совпадения: `source/competitors/2026-10-03-carrollton/00.txt` до `09.txt`.

Дата: 3 октября 2026. Проект только читался. Новое: эта секция, два файла рядом и папка с текстами конкурентов `/Users/denyskavaler/Projects/fppplumbing-site/source/competitors/2026-10-03-carrollton/` (файлы `00.txt` до `09.txt`).

Файлы рядом:
- `3-competitors-details.md`: по каждой странице все H2 дословно, description, местные факты, цены, гарантия, приезд; список из 104 районов у Barbosa; небрежности конкурентов; страница, которая не открылась.
- `3-competitors-serp.md`: первые 30 мест по каждому запросу с отметкой, что взято и почему пропущено; ответы веб-поиска; подробный список пропущенного.

### 1. Как выбраны десять страниц

Запросы: "plumber carrollton tx", "plumber in carrollton", "carrollton plumbing". Способ тот же, что у раздела Plano.

1. Semrush (инструменты ответили): обычная, не рекламная выдача Google, база "us", последнее обновление базы, первые 30 мест. По нему порядок.
2. Веб-поиск (расширенный режим), те же запросы. Это сверка: поиск не Google и к Carrollton не привязан.

Живой выдачи Google с точкой в Carrollton и блока с картой здесь нет. Дату обновления базы Semrush не сообщает.

Порядок: среднее место по трём запросам, отсутствие в первых 30 считается как 31. Одна компания один раз, берётся её лучшее место.

| № | Файл | Компания | URL | Semrush: "plumber carrollton tx" / "plumber in carrollton" / "carrollton plumbing" | Среднее | Веб-поиск (из 3) |
|---|---|---|---|---|---|---|
| 1 | 00.txt | Baker Brothers Plumbing, Air & Electric | https://bakerbrothersplumbing.com/carrollton-plumbing/ | 1 / 2 / 3 | 2,0 | 0 |
| 2 | 01.txt | Roto-Rooter | https://www.rotorooter.com/carrolltontx/ | 4 / 1 / 2 | 2,3 | 2 |
| 3 | 02.txt | Cathedral Plumbing | https://www.cathedralplumbingtx.com/ | 5 / 5 / 9 | 6,3 | 2 |
| 4 | 03.txt | Berkeys Plumbing | https://www.berkeys.com/carrollton-plumbing/ | 9 / 4 / 13 | 8,7 | 0 |
| 5 | 04.txt | Plumbing Dynamics | https://www.plumbingdynamicsdallas.com/ | 6 / 14 / 14 | 11,3 | 1 |
| 6 | 05.txt | AugerPros Plumbing and Drain | https://augerpros.com/carrollton-texas-plumbing-company/ | 7 / 7 / нет | 15,0 | 1 |
| 7 | 06.txt | Barbosa Plumbing & Air Conditioning | https://www.barbosamechanical.com/service-area/carrollton/plumber | 14 / 24 / 15 | 17,7 | 2 |
| 8 | 07.txt | Milestone Electric, A/C & Plumbing | https://callmilestone.com/carrollton/plumbing/ | 18 / 16 / 23 | 19,0 | 0 |
| 9 | 08.txt | Carrollton Plumbing Service, Inc. | https://www.carrolltonplumbingservice.com/ | нет / нет / 1 | 21,0 | 3 |
| 10 | 09.txt | CR Plumbing, Air & Electric | https://www.crplumbingdfw.com/service-areas/carrollton-tx/ | нет / нет / 10 | 24,0 | 0 |

Тип страниц: семь страниц города у компаний из других городов и три главные страницы местных компаний (Cathedral, Plumbing Dynamics, Carrollton Plumbing Service). У всех троих адрес на одной улице: Halsey Way, 75007. У остальных семи офиса в Carrollton нет.

Пропущено (подробно в `3-competitors-serp.md`):
- каталоги, форум и соцсети: Yelp, Reddit (r/CarrolltonTX на 3 месте), BBB, Nextdoor, Angi, HomeAdvisor, Facebook, Thumbtack, MapQuest;
- Carrollton в штате Georgia: запросы без "tx" дают Cox Plumbing (места 6 и 6), Thompson West, Lee Plumbing, статью addisonsmith.net;
- сборщики звонков: профиль about.me и plumbingcarrollton.com (без названия компании и лицензии, "© 2017");
- leflr.com: второй сайт Carrollton Plumbing Service, компания уже в десятке;
- Signature Plumbing Company (19 / 18 / 17, была бы восьмой): could_not_open, защищённое соединение обрывается, по http Cloudflare отвечает "error code: 1001"; повторно не пробовал, взял следующую (CR);
- реже встречаются: Jim's Plumbing Now 24,7; Legacy 25,0; Harmony 26,3; DNA 26,3; Trident 27,0 (в веб-поиске 3 из 3); My Local Plumber 27,3; Mother 27,7 и другие.

fppplumbing.com по Semrush нет в первых 30 ни по одному из трёх запросов. Это не Search Console: сверить с разделом 2.

Все десять страниц отдали код 200 с первого запроса, обходить защиту не пришлось. CR перенаправил со старого адреса (/service-areas/carrollton-plumbing-and-hvac-company/) на новый, в файле новый.

### 2. Таблица по десяти страницам

"Основной текст": от H1 до подвала, без меню, с FAQ и отзывами в теле страницы. "Вся страница": всё видимое, как в файле.

#### 2.1. Размер, слово Carrollton, отзывы, FAQ

| № | Компания | Слов: основной / вся | "Carrollton": основной / вся | H2 с Carrollton | Отзывов на странице | FAQ |
|---|---|---|---|---|---|---|
| 1 | Baker Brothers | 1 685 / 2 054 | 10 / 12 | 2 из 15 | 0 | 0 |
| 2 | Roto-Rooter | 1 305 (без повтора FAQ около 911) / 1 626 | 33 / 39 | 5 из 6 | 0 ("Rated 4.8 on Google") | 5, напечатаны дважды |
| 3 | Cathedral | 891 / 1 063 | 3 / 6 | 1 из 5 | 6 | 3 |
| 4 | Berkeys | 1 265 / 1 587 | 14 / 17 | 1 из 1 | 0 | 0 |
| 5 | Plumbing Dynamics | 2 271 (без отзывов 1 822) / 2 736 | 14 / 20 | 3 из 15 | 9 (Google через Trustindex) | 0 |
| 6 | AugerPros | 1 377 / 1 729 | 18 / 19 | 4 из 6 | 0 (в разметке 5.0 и 1 578) | 0 |
| 7 | Barbosa | 1 522 (без списка районов 1 285) / 1 840 | 39 / 41 | 6 из 8 | 0 (в разметке 4.8 и 190) | 5 |
| 8 | Milestone | 977 / 1 621 | 6 / 7 | 1 из 1 | 1 короткая цитата | 0 |
| 9 | Carrollton Plumbing Service | 2 605 / 2 882 | 50 / 59 | 10 из 20 | 5 (один дважды) | 6 |
| 10 | CR Plumbing | 1 091 / 2 645 | 13 / 15 | 2 из 5 | 0 ("+ 1200 Reviews") | 8 |

Наша нынешняя /plumber-carrollton-tx/ (снимок `source/crawl/pages/plumber-carrollton-tx.json`, от H1 до конца отзывов): 1 624 слова, Carrollton 18 раз, 8 вопросов FAQ.

#### 2.2. Темы H2, местные факты, цены, гарантия, приезд

| № | Компания | Темы H2 | Местные факты на странице | Цены | Гарантия | Приезд |
|---|---|---|---|---|---|---|
| 1 | Baker Brothers | По H2 на услугу: авария, кухня, slab leak, фильтры, септик, газ, канализация, унитазы, водонагреватели, насос, душ, hydrojetting | Нет. Офисы в Dallas, Arlington, McKinney. В тексте остался "Double Oak" | Нет | "100% Satisfaction Guarantee", без срока | "24/7", без времени |
| 2 | Roto-Rooter | Почему мы, услуги, авария, FAQ, 11 округов, почему нам верят | Глина двигает плиту и трубы; жара и грозы; корни live oaks и pecan trees; вода "high in mineral content". Общими словами. Адреса офиса нет | Купон "$55 Off", без доплаты в выходные | "clear warranties", без срока | "typically arrive within hours", "Same-day service" |
| 3 | Cathedral | Кто мы, 12 услуг одними заголовками, отзывы, почему мы, FAQ | Офис 1451 Halsey Way, 75007; округа Dallas, Collin, Tarrant | "Free Estimate" | "100% Guarantee", без срока | "be there fast"; в FAQ "same day" по будням 7:00 до 17:30 |
| 4 | Berkeys | Один H2; H3: водонагреватели и tankless, ремонт 24 часа, осмотр по клубу, repiping, прочистка, hydro jetting, канализация, бренды | Индексы 75006, 75007, 75010; "35 years ... in Carrollton"; общая фраза про разрешения. Текст на 98% как их страница Plano | Нет, скидка по клубу | По сантехнике нет | "24 hours a day" |
| 5 | Plumbing Dynamics | Семейная компания против фондов, без процентов с продаж, услуги, "North Dallas", отзывы | Офис 1448 Halsey Way Ste 114, с 2005. Общими словами: глина и "bellies", "cast-iron systems", жёсткая вода и осадок, корни | "Free Estimates No Service or Trip Fee", рассрочка | "parts & labor warranty", без срока | "fast, local response times" |
| 6 | AugerPros | Мы рядом, списки и плитки услуг, призыв, список городов | О городе ничего; офис в Allen; "Carrollton" трижды ссылкой на cityofcarrollton.com; строками "Smoke testing", "Cleanout installation", "Backflow Protection" | "free phone consultations" | Нет | "punctual" |
| 7 | Barbosa | Кухня и ванная, почему мы, услуги, обслуживание, районы, заключение, FAQ (под заголовком про HVAC) | Historic Downtown Carrollton, Elm Fork Nature Preserve (ссылка на страницу города), Green Trail; 104 района; офис в Dallas | Прочистка "$100 and $300", водонагреватель "$1,000 or more" | "Satisfaction Guaranteed" | "same-day" только в description |
| 8 | Milestone | Один H2 и общие абзацы, список услуг | Нет; 9 офисов, ни одного в Carrollton | "price matching" | "100 percent satisfaction guaranteed" | "same-day appointment availability" |
| 9 | Carrollton Plumbing Service | 20 H2: почему мы, Halloween, по H2 на услугу (в том числе PRV и сдвиг фундамента), "We Know Carrollton", сезоны, города, отзывы, FAQ | Самая местная. Офис 1448 Halsey Way #100, лицензия M-15249, с 2007. George Bush Turnpike, Rosemeade Pkwy, Josey Lane, Hebron Pkwy; Indian Creek, Josey Ranch, Hebron Corridor, Old Town; трубы у Old Town "since the 80s"; рассказ о скрытой утечке под плитой; заморозки; глина; "hard and heavily chlorinated" вода; "old clay pipes" | "$150-$450" за обычный ремонт, "No service-call fee" | "1-year workmanship warranty" (единственный срок) | "Same-day", "within 1-2 days", водонагреватель "within 24 hours" |
| 10 | CR Plumbing | Услуги (сантехника, HVAC, газ, электрика), газ, водонагреватели, FAQ, как работаем | Пять районов строкой: Indian Creek, Castle Hills, Austin Waters, Josey Ranch, Trinity Mills; офисы не в Carrollton | "Free consultations" | "warranties" по почте, без срока | "arrive promptly" |

Сводка: цены в цифрах у двух (Barbosa, Carrollton Plumbing Service), купон у одного (Roto-Rooter); наше правило ($49 в будни, засчитывается в ремонт, цена до начала работ) так не объясняет никто, а двое пишут "no service-call fee". Срок гарантии назван один раз (1 год, Carrollton Plumbing Service). Время в своём тексте: "within hours" (Roto-Rooter), "within 1-2 days" и "within 24 hours" (Carrollton Plumbing Service); "same day" у четырёх. На официальный источник по делу (разрешения, TSBPE, поставщик воды, EPA) не ссылается никто: только AugerPros на главную сайта города и Barbosa на страницу заповедника.

### 3. Какие местные факты не называет никто

Проверено поиском слов по всем десяти текстам.

1. Давление в цифрах: "PSI" нет ни у кого. PRV только у Carrollton Plumbing Service, общими словами, без цифр и без того, где стоит клапан. Наша нынешняя страница держит H2 "Water Pressure and the PRV": угол занят наполовину, цифры и манометр за нами.
2. Счётчик: "meter" в тексте нет ни у кого, "valve box" и "meter box" нет совсем. Проверку утечки по счётчику и границу "до счётчика городское, после ваше" не объясняет никто. На нашей нынешней странице это есть: оставить.
3. Откуда вода: поставщика, озеро или реку не называет никто. Жёсткость словами у трёх, цифр (ppm, grains) ни у кого, "chloramine" ни у кого. Факт должен прийти с официальной страницы (раздел 6a).
4. Разрешения и инспекция в Carrollton: общая фраза у Berkeys, "proper permits" про газ у Carrollton Plumbing Service. На какую работу нужно разрешение города, что смотрит инспектор, регистрация подрядчика: ни у кого. "inspector" и "registration" нет. Ссылки на страницу разрешений города нет.
5. Ремонт под плитой: "post-tension", "tunnel", "braze", "type L" нет; медь как труба не названа ни разу. Slab leak упомянут у восьми страниц, везде общими словами.
6. Трубы по годам: только "since the 80s" у Carrollton Plumbing Service; чугун одной фразой у Plumbing Dynamics. "PEX", "polybutylene", "galvanized" нет. Возраст домов по частям города (раздел 6b: медиана 1988, юг 75006 около 1982, север 75010 около 2005) не даёт никто.
7. Округа: в каких округах лежит сам город, не пишет никто (раздел 6b: Denton, Dallas, Collin).
8. Канализация до города: "property line", "city side" нет. "Cleanout installation" и "Smoke testing" только строками в списке у AugerPros. Запах канализации не объясняет никто (есть в отзыве у Cathedral).
9. Полив: "sprinkler", "irrigation" нет. "Backflow Protection" строкой у AugerPros.
10. Водонагреватель на чердаке: "attic" только в меню (утепление); "pan", "expansion tank", "T&P" нет ни у кого.
11. Мороз: только Carrollton Plumbing Service, общими словами. Наружный кран в тексте не описан (упомянут в отзыве у Cathedral и пунктом меню у Plumbing Dynamics).
12. Сток кондиционера в сливе раковины: "condensate" нет ни у кого.
13. Дороги: I-35E, Belt Line, Sam Rayburn Tollway, Old Denton Rd в тексте нет ни у кого.
14. Настоящие вызовы: один рассказ на десять страниц (Carrollton Plumbing Service, утечка под плитой в Hebron Corridor). Фото с подписью о работе в Carrollton нет ни у кого.
15. Человек: лица и рассказа о себе нет ни у кого; имена мастеров только в отзывах, держатели лицензий строкой в подвале. Блок с Денисом будет единственным.

Уже занято: районы (Barbosa 104, Carrollton Plumbing Service 5, CR 5), Old Town и исторический центр, глина, жёсткая вода, корни, индексы (Berkeys, те же три, что в 6b), заморозки и PRV (Carrollton Plumbing Service), местный офис (три компании на Halsey Way). Офиса в Carrollton у нас нет и придумывать его нельзя: страница описывает выезд из ближайшего нашего офиса.

Список выше говорит только о том, чего нет у конкурентов. Факты для нашей страницы приходят от Дениса или с официальных страниц. Районы Barbosa и CR я с границами города не сверял (Castle Hills проверить отдельно, прежде чем называть).

### 4. Структура: длина, разделы, FAQ

Длина основного текста: 891, 977, 1 091, 1 265, 1 305, 1 377, 1 522, 1 685, 2 271, 2 605 слов; середина около 1 340, среднее 1 499. Наша нынешняя (1 624) длиннее семи из десяти. Цель около 2 500 слов ставит нас рядом с самой длинной (Carrollton Plumbing Service, 2 605).

Три типа: шаблон "список услуг" (Baker, Berkeys, AugerPros, Milestone; Berkeys на 98% совпадает со своей страницей Plano, AugerPros на 86% со своей The Colony); страница с местным слоем (Roto-Rooter, Barbosa, Carrollton Plumbing Service: глина, вода, корни, районы, FAQ с городом в вопросе); главная местной компании (Cathedral, Plumbing Dynamics). Почти у всех: значки доверия наверху, "почему мы", список соседних городов (все десять), рассрочка, бесплатная оценка (шесть). Tankless у 9 из 10, hydro jetting у шести, газ у девяти. Карта Google у пяти.

FAQ на пяти страницах, 27 вопросов. У Roto-Rooter и Barbosa вопросы стоят тегами H3. Дословно:

Roto-Rooter (5): "Why are slab leaks so common in Carrollton, TX?" / "Can tree roots really damage my plumbing in Carrollton?" / "How does hard water affect plumbing in Carrollton?" / "What should I do if a storm causes a drain backup or water damage in my Carrollton home?" / "Is Roto-Rooter available for plumbing emergencies in Carrollton on weekends?"

Cathedral (3): "I need help now, how long will it take you to get here?" / "Do you service my neighborhood?" / "What is the screening process for technicians?"

Barbosa (5): "How much will a Carrollton plumbing repair cost?" / "What types of plumbing systems do you service?" / "How often should I schedule plumbing maintenance in Carrollton?" / "Are your Carrollton plumbers licensed and insured?" / "How long does a Carrollton plumbing repair take?"

Carrollton Plumbing Service (6): "Who is the best plumber in Carrollton, TX?" / "How fast can you get to my home for a plumbing emergency in Carrollton?" / "How much does a plumber cost in Carrollton?" / "Do you repair and install water heaters in Carrollton?" / "Are you licensed and insured?" / "What neighborhoods and cities do you serve?"

CR Plumbing (8): "What services do you provide in Carrollton?" / "Do you serve areas outside Carrollton?" / "Can one team handle plumbing, electrical, HVAC, and gas services?" / "How do you approach service pricing?" / "Do you work with both homes and businesses?" / "What plumbing and electrical issues do you commonly address?" / "Can you help improve energy efficiency?" / "Why choose a local plumbing, electrical, and HVAC company?"

У Baker, Berkeys, Plumbing Dynamics, AugerPros и Milestone FAQ нет.

Наши нынешние вопросы (8, из `site/src/content/pages/plumber-carrollton-tx.md`) против десятки:
- "How much does a plumber cost in Carrollton, TX?" совпадает с вопросом Carrollton Plumbing Service восемью словами подряд ("how much does a plumber cost in carrollton"); по смыслу тот же вопрос у Barbosa. Это единственное совпадение нашей нынешней страницы с десяткой (проверено правилом tools/check_overlap.py отдельным скриптом). В новом тексте вопрос о цене задать по-своему.
- "Can you replace a water heater the same day in Carrollton?" близок по теме к вопросу Carrollton Plumbing Service о водонагревателях; слов не совпадает.
- Наших вопросов про PRV, скрытую утечку и счётчик, доплату вечером и в выходные, старые и новые дома, сдаваемые дома нет ни у кого.

### 5. Шаблоны title и H1

Title (все дословно в `3-competitors-details.md`):
- Город в первых четырёх словах у всех десяти. "Plumber in Carrollton" у двух (Plumbing Dynamics: "Plumber in Carrollton, Texas - Plumbing Dynamics"; Carrollton Plumbing Service: "Plumber in Carrollton TX | Carrollton Plumbing Service, Inc."). "Plumber Carrollton" у двух (Cathedral: "Plumber Carrollton, TX | Plumbing Experts | Cathedral"; Barbosa: "Best Plumber Carrollton TX | ..."). "Carrollton Plumber(s)" у трёх (Roto-Rooter: "Carrollton Plumbers Near You | Roto-Rooter"; Berkeys; Milestone). Остальные: "Plumber Services Carrollton TX" (Baker), "Carrollton Texas Plumbing Services" (AugerPros), "Carrollton Plumbing, Electrical, and HVAC Company" (CR).
- Хвост: телефон (Baker, Berkeys), "Near You" (Roto-Rooter, Milestone), "Best" (Barbosa, Milestone), "Experts", "24-Hour", имя компании.
- Работу или проблему в title не называет никто. Длина 42 до 84 знаков.

H1: "Carrollton TX Plumbing Service" (Baker); "Carrollton's Go-To Plumbing Experts for Every Job, Big or Small" (Roto-Rooter); "A Whole New Level Of Service" дважды и "Why Choose Cathedral Plumbing" (Cathedral, три H1 без города); "Carrollton Plumber" (Berkeys); "Plumber in Carrollton, TX" (Plumbing Dynamics и Milestone, одинаково); "Your Carrollton Neighborhood Plumbing and Drain Cleaning Professionals" (AugerPros); "The Best Plumber in Carrollton, Texas" (Barbosa); "Trusted Plumber in Carrollton, TX" (Carrollton Plumbing Service); "Carrollton Plumbing, Electrical, and HVAC Company" (CR). Короткие, ключ плюс слово оценки; проблему не называет никто.

Наши нынешние: title "Plumber Carrollton, TX | Leak Detection, Slab Leak & PRV Repair" (63 знака), H1 "Plumber in Carrollton, TX: We Find the Leak Before Anyone Digs". Наш title единственный из одиннадцати называет работу. Начало H1 совпадает со всем H1 у Plumbing Dynamics и Milestone, дальше своё. Менять или нет, решает Search Console (раздел 2); со стороны конкурентов причин менять нет. Не брать в title и H1: "Best", "Trusted", "Go-To", "Near You", "Experts", "24-Hour", телефон, купон.

### 6. Что у конкурентов нельзя нам

Tankless, hydro jetting как услуга, repiping; бесплатная оценка и "no service-call fee"; вилки цен и купоны; срок гарантии; время приезда ("within hours", "within 24 hours", "within 1-2 days", "arrive promptly"); телефон в тексте и в ответах FAQ (семь страниц); списки соседних городов (все десять) и города, которые нам называть нельзя (Addison, Farmers Branch, Coppell, Irving, Richardson и другие); вопросы FAQ тегами заголовков; "financing"; PHCC (Roto-Rooter).

### 7. Папка для проверки на совпадения

`/Users/denyskavaler/Projects/fppplumbing-site/source/competitors/2026-10-03-carrollton/`, файлы `00.txt` до `09.txt` в порядке таблицы раздела 1. Формат как в `2026-10-03-plano/`: первая строка адрес, вторая весь видимый текст одной строкой (title, меню, текст, подвал). Чтение по правилам `tools/check_overlap.py` проверено отдельным скриптом (сам инструмент не запускал): все десять читаются. Папка `source/competitors/` в .gitignore. Команда для черновика: `python3 tools/check_overlap.py <черновик> source/competitors/2026-10-03-carrollton`.

## 4. Фото и клипы

Файла раздела для этой части не было: она написана при сборке. Источник: `docs/briefs/_shared/photos-by-city-after-recount.json` (204 записи архива: 143 фото и 61 видео; прочитан 3 октября 2026). Город «после пересчёта» в этом файле поставлен по границе города (basis "city boundary", 115 записей), по слову Дениса ("Denys's word", 43), оставлен как был ("as before", 19), снят, если место съёмки вне десяти городов (19), или придержан для Little Elm (8). Слово Дениса о городе работы главнее проверки по карте. Координат в этом файле нет, и в брифе их нет.

Сверено с `docs/briefs/_shared/cities-free-photos-2026-10-03.md` (строка Carrollton: 10 фото, свободны 27, 57, 58, 144, 145, 146, 147, 148; клипов 0), с `photos/captions.csv` и `photos/captions-en.csv` (те же десять номеров, в `city_final` Carrollton, источник "city boundary (Census TIGER/Line 2025)"), с частью 1 (раздел 4) и с частью 8 (разделы 1.2 и 2.3). Где стоят фото 6 и 42, проверено ещё и по файлам `site/src` (3 октября 2026, около 11:50): совпало с полем stands_on_built_pages. Фото 42 есть и в заготовке блока фото главной (`site/src/design/home-marked.html`), но шаблон главной меняет его на фото 163, так что на главной оно не стоит.

После пересчёта за Carrollton числятся 10 файлов, все фото, все по границе города; слова Дениса о городе нет ни у одного. Клипов (видео) за Carrollton нет ни одного. У всех десяти город до пересчёта тоже был Carrollton; только у фото 6 первая колонка `photos/captions.csv` пишет Plano, а `city_final` Carrollton, и по правилу город берётся из `city_final`.

### 4.1. Все файлы, у которых город после пересчёта Carrollton

Колонка «Что сказал Денис» дана как в файле, по-русски. Подпись дана как в файле, по-английски. «Отложено для» это колонка planned_pages. «Пометки» это колонка flags, слово в слово; пары «до» и «после» взяты из колонки pair файла `photos/captions.csv`.

| № | Вид | Дата | Что сказал Денис | Подпись (англ.) | Где стоит на собранном сайте | Отложено для | Пометки |
|---|---|---|---|---|---|---|---|
| 6 | фото | 2026-09-28 | Замененный газовый водонагреватель Bradford White | Replaced gas water heater, Bradford White, Carrollton | `/` и `/emergency-plumbing-services/` (блок "What is happening right now?", вкладка "No hot water", alt "New Bradford White gas water heater in a closet, Carrollton"; часть 8, раздел 1.2) | /water-heaters/ /plumber-carrollton-tx/ /plumbing-guide/water-heater-replacement-cost-2026/ | нет |
| 27 | фото | 2026-07-10 | Очередная замена PRV в доме | Another PRV replacement in a house, Carrollton | нигде | /prv-replacement-frisco-plano/ /plumber-carrollton-tx/ | нет |
| 42 | фото | 2026-09-02 | Slab leak: перепаяли брейзингом лопнувшее текущее соединение | Slab leak repair: rebrazed copper joint under the foundation, Carrollton | `/slab-leak-repair-frisco-plano-mckinney/` (главное фото страницы, alt "Finished brazed copper joint on a slab leak repair under the foundation, Carrollton") | /slab-leak-repair-frisco-plano-mckinney/ /plumber-carrollton-tx/ | "Captions.csv suggested after:56?; 56 is a Plano yard line fixed with ProPress, not this slab job. No slab slider." |
| 57 | фото | 2025-09-12 | Слив под раковиной: P-trap с гибкой гофрой, тек, забивался, криво | Sink drain: P-trap with a flexible corrugated pipe, leaking, clogging, crooked, Carrollton | нигде | /clogged-drain-cleaning-frisco-plano/ /plumber-carrollton-tx/ | нет (пара: «до» к 58) |
| 58 | фото | 2025-09-12 | Тот же слив переустановлен правильно, без гибкой трубы, ровно, не течет | The same drain reinstalled right: no flex pipe, straight, no leak, Carrollton | нигде | /clogged-drain-cleaning-frisco-plano/ /plumber-carrollton-tx/ | нет (пара: «после» к 57) |
| 144 | фото | 2024-07-12 | Сломанная душевая система, капал душ | Broken shower set, the shower was dripping, Carrollton | нигде | /fixture-installation-repair/ /plumber-carrollton-tx/ | нет (пара: «до» к 148) |
| 145 | фото | 2024-07-12 | Открываем плитку с этой стороны, потому что с другой стороны наружная стена, доступа нет | Opening tile on this side: the other side is an outside wall, no access, Carrollton | нигде | /fixture-installation-repair/ | нет |
| 146 | фото | 2024-07-12 | Плитка открыта, старый клапан | Tile open, the old valve, Carrollton | нигде | /fixture-installation-repair/ | нет |
| 147 | фото | 2024-07-12 | Перепаяли новый клапан внутри стены | New valve soldered in inside the wall, Carrollton | нигде | /fixture-installation-repair/ /plumber-carrollton-tx/ | нет |
| 148 | фото | 2024-07-12 | Установлен новый клапан и shower trim, отверстие закрыто | New valve and shower trim installed, the opening closed, Carrollton | нигде | /fixture-installation-repair/ /plumber-carrollton-tx/ | нет (пара: «после» к 144) |

Что видно по таблице:

- Свободны для страницы Carrollton (не стоят ни на одной собранной странице) восемь кадров: 27, 57, 58, 144, 145, 146, 147, 148. Все они отложены и для страниц услуг (PRV, прочистка, смесители и душ). Одно фото может стоять на двух страницах, но подробно работа рассказывается на странице своей услуги, а на странице города одним коротким абзацем со ссылкой (правило 9).
- Душевой клапан (144 до 148, июль 2024) единственная полная серия из Carrollton: проблема (144), вскрытие плитки (145, 146), пайка в стене (147), готово (148). Если Денис расскажет, что там было, это готовая короткая история для страницы города (144 и 148 как «до» и «после»), со ссылкой на faucet and shower valve repair.
- Пара 57 и 58 (слив раковины, сентябрь 2025) это «до» и «после» одной работы.
- Фото 27: Денис сказал только «Очередная замена PRV в доме». В `photos/captions-en.csv` alt "Pressure reducing valve being replaced in a wall access panel, Carrollton" (часть 1 пишет «PRV в стене»). Где стоял клапан и какое было давление, со слов Дениса не записано.
- Фото 42 уже главное на странице slab leak. Для истории slab leak на странице города одного кадра готового стыка мало: история, названная по проблеме, сначала показывает проблему (CLAUDE.md), а кадра течи, ямы или тоннеля из этой работы в архиве нет. Как заметили и как нашли течь, нигде не записано (часть 8, раздел 1.2).
- Фото 6 стоит на главной и на странице emergency. Отзыв Tyler Sommers (июнь 2026, замена водонагревателя в Carrollton) и фото 6 (28 сентября 2026) по датам разные; одна ли это работа, знает только Денис (часть 10).
- Вне этого файла: главное фото живой страницы, фургон (`/wp-content/uploads/2025/05/photo_2025-05-15_20-41-51.jpg`, alt "Plumbing van outside a home in Carrollton, TX"). В `photos/index.csv` его нет, город подтверждает только alt; на борту телефон 980.899.7997, на крыле "M-38532" (часть 1, раздел 4). На новом сайте это фото сейчас встаёт главным на первый экран (часть 7). И восемь старых фото галереи с Carrollton в alt (часть 8, раздел 2.3; таблица Г в `8-links-tables.md`): в архиве их нет, город не проверен.
- Фото фургона в архиве: 1, 2, 3, 4 у офиса Frisco (слово Дениса) и 202 у офиса Plano (сборное фото). Фото 2 и 4 Денис 1 октября разрешил ставить вместо фото с работы на страницах Celina и Lewisville ("stand in for Celina and Lewisville until job photos from there"); для Carrollton такого слова нет.

### 4.2. Кандидаты по темам страницы

Темы взяты из живой страницы (часть 1), из запросов (часть 2) и из того, чего нет у конкурентов (часть 3). Правила из CLAUDE.md: история, названная по проблеме, сначала показывает проблему, потом ремонт; все картинки одного размера, 3:4; клип режется до пяти секунд, без звука, крутится сам; номер дома и номерной знак в кадре закрываются; фото, снятое в другом месте, на страницу города не идёт, пока Денис не назовёт работу.

| Тема страницы | Файлы | Что с ними делать |
|---|---|---|
| Первый экран: фургон или работа в Carrollton | нет | Фургон живой страницы городом не подтверждён (на крыле "M-38532", на борту телефон Plano). Нужен настоящий кадр (4.3). Ставить ли пока фургон у офиса Frisco (2 или 4), как для Celina и Lewisville, решает Денис; на чужой странице alt не называет Frisco |
| Поиск течи, счётчик, высокий счёт (title "Leak Detection", H2 "Water Leak Detection in Carrollton"; 990 показов за 3 месяца) | нет | Ни одного кадра из Carrollton. Фото 79 (крутится счётчик) записано за The Colony и стоит на странице leak detection, сюда не идёт. Метод принадлежит странице leak detection, на странице города строка со ссылкой |
| Slab leak (title "Slab Leak"; 831 показ за 3 месяца) | 42 | Можно поставить вторым местом, если Денис расскажет работу и подтвердит Carrollton. Для истории нужен кадр проблемы (4.3); без него короткий абзац со ссылкой "slab leak repair" и это фото |
| Давление и PRV (H2 "Water Pressure and the PRV"; город: разрешение на одну замену PRV без платы, city-b8) | 27 | Свободно. К абзацу про давление и строке со ссылкой на PRV replacement, когда Денис скажет, что там было и что показал манометр |
| Водонагреватель (вопрос FAQ про замену; отзыв Tyler Sommers; памятка города про водонагреватели, city-b3 и city-b4) | 6 | Уже на главной и emergency; на странице города можно, если Денис скажет, та же ли это работа, что у Tyler, и было ли разрешение |
| Засоры и сливы (строка списка услуг "Slow sinks, tubs, and showers") | 57, 58 | Свободная пара «до и после». Подробно принадлежит странице прочистки, на странице города коротко со ссылкой |
| Смесители и душ (запросы faucet с carrollton: 3,434 показа до июля, слова faucet на странице нет) | 144, 145, 146, 147, 148 | Свободная серия. На странице города 144 и 148 с короткой историей и ссылкой на faucet and shower valve repair; 145 до 147 для страницы услуги |
| Чугун, корни, cleanout через снятый унитаз (H2 "What Else We Run Into Here") | нет | Ни одного кадра из Carrollton |
| Слив кондиционера в мойку (поправка города M1411.9, часть 6) | нет | Ни одного кадра из Carrollton. Фото 201 (линия конденсата в сливе) это Frisco словом Дениса, стоит на странице Frisco |
| Emergency, ночные вызовы (5,471 показ до июля) | нет | Ни одного кадра из Carrollton |
| Дома под аренду (вопрос FAQ про property managers) | нет | Ни одного кадра |

В архиве есть 37 файлов без города (22 фото и 15 клипов; сняты вне десяти городов или город не определён), среди них по темам этой страницы есть кадры (водонагреватель Bradford White 28, пайка под фундаментом 45 и 162, тоннель и пинхол 77 и 78). Как кандидаты для страницы Carrollton они не предлагаются: на странице города стоят работы из этого города, а у этих файлов города нет.

### 4.3. Чего не хватает: какие кадры просить у Дениса

1. Настоящее фото с работы в Carrollton или фургон FPP на улице в черте города. Кадр вертикальный, чтобы встал в размер 3:4; без номеров домов; номерной знак мы размоем. Это замена нынешнему главному фото.
2. Работа slab leak с фото 42: кадр проблемы из той же работы (яма доступа или тоннель, течь или лопнувший стык до пайки), если он есть. Без него история slab leak на странице города только строкой со ссылкой.
3. Работа PRV с фото 27: манометр с цифрой давления до и после, место клапана в доме.
4. Водонагреватель в Carrollton «до» и «после»: поддон и его слив, сброс T&P, кран на холодной воде, расширительный бак (это перечень памятки города, city-b4). Если фото 6 и отзыв Tyler Sommers одна работа, кадр «до» этой работы.
5. Ящик счётчика у дома в Carrollton: индикатор течи крутится, кран города и кран хозяина.
6. Главная линия в старом доме Carrollton: экран камеры, корни, чугун, cleanout или снятый унитаз, если чистили через фланец.
7. Слив мойки с врезанной линией конденсата кондиционера в Carrollton, если такая работа была.
8. Узел backflow на поливе, заменённый с разрешением города в Carrollton, если такая работа была (без слов о проверке узла: её делает не FPP).
9. Клип около пяти секунд с любой работы в Carrollton: из города нет ни одного клипа.

## 5. Отзывы: кандидаты

Файл раздела: `docs/briefs/carrollton/5-review-candidates.md`, вставлен целиком. Заголовок файла: «5. Отзывы: кандидаты для страницы Carrollton».

Рядом, в бриф не вставлен: `5-review-candidates-tables.md` (часть А: запас за десяткой с текстами; Б: 27 чистых отзывов, которые называют работу; В: пробелы по работам, кто есть и что мешает; Г: причины отсева подробнее; Д: что искали; Е: пересечения с брифами других городов этой ночи). Перед выбором заново прочитать `reviews/site-reviews.json` и `reviews/site-ledger.md`: этой ночью их перестраивает другой процесс.

Раздел для брифа страницы `/plumber-carrollton-tx/`. На страницы ничего не поставлено, файлы проекта не изменены. `reviews/site-reviews.json` (от 10:04) и `reviews/site-ledger.md` (от 04:54) прочитаны 3 октября 2026 дважды, без изменений; перед выбором прочитать снова. Длинные списки: `5-review-candidates-tables.md`.

### Коротко

- Пятизвёздочных отзывов, которые называют Carrollton, его улицу, район или индекс: **2**, оба свободны: **Tyler Sommers** и **Paula Thompson** (Google, профиль Plano), оба с живой страницы Carrollton. Улиц, районов и индексов нет ни в одном отзыве. По правилу о городе эти двое принадлежат только Carrollton; третьего нет.
- Оба проходят все правила. Пометки: цифры времени в словах клиента (у Tyler одна, у Paula три); отзыв Paula подписан внутри "Larry R. & Paul T.".
- Свободных пятизвёздочных с текстом: **330**; кроме этих двух, все правила проходят **145**, работу называют **27**. Места 3 до 10 без места и **не привязаны к Carrollton**.
- Про slab leak, PRV, водопровод во дворе, главную линию и дома под аренду, главные темы страницы, чистых свободных отзывов нет. Про скрытую течь только два старых Thumbtack (Javeed N., Kevin N.).

### Откуда данные

- `reviews/all-reviews.csv`: 407 отзывов (Google 131: профиль Plano 105, профиль Frisco 26; Thumbtack 249; Yelp 27).
- Кто занят: `reviews/site-reviews.json` и `reviews/site-ledger.md` (40 авторов на 14 страницах, с двенадцатью главной; страницы Carrollton нет), три резерва главной из задания. Старый сайт и решения: `reviews/ledger.md`, `reviews/ledger.csv`, `reviews/ledger-decisions.csv`; в `reviews/proposed-placement.csv` Carrollton нет.
- Живая страница: `source/crawl/pages/plumber-carrollton-tx.json`. Новая: `site/src/content/pages/plumber-carrollton-tx.md` (заголовок "What Carrollton Homeowners Say About FPP Plumbing", строка "Google reviews from local homeowners.", отзывов нет).
- Тексты кандидатов Google и двух отзывов живой страницы совпадают с Google Takeout (`source/gbp-takeout/`) знак в знак, пять звёзд, даты те же; Thumbtack и Yelp совпадают с `reviews/raw/`. Вживую ни один отзыв не открывался.
- Брифы других городов этой ночи прочитаны около 10:40 ради пересечений (файл таблиц, часть Е).

### Carrollton в отзывах: два

Искал в архиве (текст, ответ компании, job, note), в `reviews/raw/` и в 131 отзыве Google Takeout: Carrollton в трёх написаниях, индексы 75006, 75007, 75010 и 75011 (Census "2020 ZCTA to Place"), около пятидесяти улиц и районов по своей памяти (только как слова для поиска) и все слова с большой буквы в середине предложения. Перечень: файл таблиц, часть Д. Официальный список районов (https://www.cityofcarrollton.com/departments/departments-a-f/community-development/neighborhood-association-registration) ответил 403 на один запрос 3 октября 2026: could_not_open, защиту не обходил.

| Имя | Площадка | Дата | Что названо в тексте | Ответ компании | Свободен |
|---|---|---|---|---|---|
| Tyler Sommers | Google, профиль Plano | 2026-06-17 | "excellent response time in Carrollton, TX" | тоже называет Carrollton | да |
| Paula Thompson | Google, профиль Plano | 2026-01-08 | подпись в конце "Carrollton, Tx." | города нет | да |

Это сходится с `docs/cities-table-2026-10-03.md` (раскладка отзывов, часть 9.2).

### Сколько свободно и сколько чистых

| Шаг | Сколько |
|---|---|
| Всего отзывов в архиве | 407 |
| Из них пять звёзд | 396 |
| Минус 6 без текста и 10 копий отзывов Google, показанных на Thumbtack (кандидат только оригинал Google) | 380 |
| Минус 47 строк занятых авторов (43 человека: 40 на новом сайте, у четверых по две строки Google; плюс три резерва главной) | 333 |
| Минус 3 строки: тот же человек под другим именем (L W это Liane W.; Rani C это Rani .; Lanessa A. на Yelp это Lanessa Arnold Jenkins) | **330 свободных** |

Из 330: Thumbtack 227, Google профиль Plano 69, Yelp 19, Google профиль Frisco 15. Двое из них (Tyler Sommers, Paula Thompson) с живой страницы Carrollton, их судят ниже отдельно.

Из остальных 328 правила отсеивают 183 строки (строка может попасть в несколько причин): имя Дениса 156; автор стоит на другой городской или служебной странице старого сайта 27; ответ компании называет другой город 21; суммы, fee или charge 20 (Dale Q. и Camrin C. только по слову charged без суммы, возвращены в чистые); назван другой город или место 12; "plumber near me" 8; придержаны для другой страницы 5. Кто именно: файл таблиц, часть Г.

Остаётся **145 чистых** (без двух с живой страницы): Thumbtack 116, Google профиль Plano 21, Yelp 7, Google профиль Frisco 1. Большинство короткие и общие ("Great job"). Что делали, называют 27 (часть Б).

### Десять лучших кандидатов

Порядок: сначала двое, кто называет Carrollton (оба с живой страницы). Потом по близости к темам страницы Carrollton (скрытые течи, трубы, цена до работы, засоры, краны), по силе слов (plumber, FPP Plumbing, названная работа) и так, чтобы работы в наборе не повторялись. **Места 3 до 10 не называют никакого места и не привязаны к Carrollton.** Текст дословный, с опечатками автора; переносы строк внутри отзыва заменены пробелом.

| # | Имя | Площадка, профиль | Дата | Работа | Место в тексте | Текст дословно | Ссылка | Почему |
|---|---|---|---|---|---|---|---|---|
| 1 | Tyler Sommers | Google, Plano | 2026-06-17 (June 2026) | водонагреватель "decided to explode", остановили течь; замена на следующий день | Да: "in Carrollton, TX" | "Great price and response time for water heater replacement. Our water heater decided to explode and the team showed up within an hour to get everything situated and prevent further leaks. They were able to come the very next day to replace our water heaters. Clear pricing and excellent response time in Carrollton, TX." | [отзыв](https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sCi9DQUlRQUNvZENodHljRjlvT2tsS2JUVjJlSFpCWmxGbVMwdzJha2xuVFhScWIzYxAB!2m1!1s0x0:0xccc66184bdaf3a93) | Город, услуга ("water heater replacement") и цена без сумм; свежий. Живая страница. Цифра приезда: "within an hour". |
| 2 | Paula Thompson | Google, Plano | 2026-01-08 (January 2026) | "gasket blow out in shower tub"; ещё регулировка унитаза и мелкая течь | Да: подпись "Carrollton, Tx." | "BIG 5 STARS for FPP they came through above and beyond the call! I called them around 3:30pm and they answered the phone and I described my dilemma, gasket blow out in shower tub. I mean it was full on in the tub! FPP called me back in about 20 minutes and said their man would be there in 40 minutes. He arrived on time! He was very descript and concise on conveying the possible outcomes and pricing on rectifying the problem. he showed me the failed part and left to go and get the new replacement part. Once back he had me repaired within 25 minutes! He also made an adjustment on my toilet and stopped a small leak! Yes I  would recommend FPP to my friends! Larry R. & Paul T. Carrollton, Tx." | [отзыв](https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sCi9DQUlRQUNvZENodHljRjlvT25jMFVWcHZObTFxVHpaRWRVdFdSelF3UmtkUFQxRRAB!2m1!1s0x0:0xccc66184bdaf3a93) | Город, две работы, объяснил варианты и цену до работы, показал сломанную деталь. Живая страница. Цифры времени: три. |
| 3 | Javeed N. | Thumbtack, Plano | 2022-11-06 (November 2022) | течь, которую трудно найти | нет; не привязан к Carrollton | "Response was immediate. They were able to troubleshoot a water leak that was hard to find. Very nice and pleasant to work with." | [листинг](https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760) | Ближе всех к первой теме страницы и к её запросам (carrollton tx leak detection, carrollton leak detection в `docs/cities-table-2026-10-03.md`). Короткий, старый, нет слова plumber. |
| 4 | Kevin N. | Thumbtack, Plano | 2023-01-04 (January 2023) | течь из ванной наверху: вода из светильника на кухне и по стенам гаража | нет; не привязан | "These guys are life savers. I had a leak in an upstairs bathroom and water was coming out of my light fixture in the kitchen as well as down the walls in my garage. They came out the same day I contacted them and were able to diagnosis and fix the issue. I would and will be contacting them for any other plumbing work that I have." | [листинг](https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760) | Скрытая течь найдена и починена в тот же день; без цифр и денег. Старый. Предложен почти всем городам. |
| 5 | Lily Chaskelmann | Google, Plano | 2024-11-14 (November 2024) | течь (общо), обращались дважды | нет; не привязан | "Excellent plumber. We've used FPP Plumbing twice already. Fixed everything we needed fixed and at reasonable prices. Explained everything really well before repairing. Most recently we had a leak and he showed up within 30 minutes!" | [отзыв](https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sChZDSUhNMG9nS0VJQ0FnSUQzbHJIRmRBEAE!2m1!1s0x0:0xccc66184bdaf3a93) | "Excellent plumber" и "FPP Plumbing", объяснили до ремонта. Цифра приезда: "within 30 minutes". |
| 6 | Dale Q. | Thumbtack, Plano | 2024-09-17 (September 2024) | в тексте нет; в заявке Thumbtack "Leaking pipes • Toilet" | нет; не привязан | "On time, cared about fixing the issue. Charged exactly what he had said it would cost up front...." | [листинг](https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760) | Слова клиента подтверждают ответ FAQ страницы "the quoted price is the final price". Charged без суммы. |
| 7 | Alecia K. | Thumbtack, Plano | 2023-01-07 (January 2023) | лопнувшая труба, выходной, починили в тот же день | нет; не привязан | "We are so grateful that not did they come out same day (on a weekend) but also took care of the broken pipe and fixed the issue same day! Really appreciate their responsiveness and professionalism and would definitely use in the future if needed!" | [листинг](https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760) | Труба и выходной без цифр времени. Ни в одной предложенной четвёрке других городов. |
| 8 | Michael V. | Thumbtack, Plano | 2023-08-02 (August 2023) | новая коробка кранов в прачечной, течь уличного крана (sillcock), пайка горелкой | нет; не привязан | "I had a great experience with two jobs. I needed a new valve box installed in the laundry room and one outside sillcock was leaking. I was a little nervous when I saw a blowtorch but everything is water tight and working. I definitely will call them back if I need anything else done!" | [листинг](https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760) | Две названные работы, горелка; ни времени, ни денег. Ни в одной четвёрке. |
| 9 | Margo W. | Thumbtack, Plano | 2023-08-29 (August 2023) | большой засор, в тот же день | нет; не привязан | "I received same day service for a major plumbing clog at a very fair price. I was very happy with the service and the work that was done. Highly recommend!!" | [листинг](https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760) | Под строку услуг про засоры. "same day" без цифры, цена без суммы. Ни в одной четвёрке. |
| 10 | Dr. Jalal Jalali | Google, Plano | 2025-07-08 (July 2025) | замена крана стиральной машины | нет; не привязан | "I called several plumber for replacement of a washer machine valve and this FPP plumbing  compony was the only  one that his price was a lot reasonable than the others. He came the same day in less than an hour. Very professional i highly recommend them and I will use them again for any pluming work." | [отзыв](https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sCi9DQUlRQUNvZENodHljRjlvT2xOTFpEQlVhbmxvY0ZoRk4wSTNhbGc0Um10WmJrRRAB!2m1!1s0x0:0xccc66184bdaf3a93) | "plumber" и "FPP plumbing", цена сравнена с другими без сумм. Цифра приезда: "in less than an hour". В четвёрке Plano. |

Ссылки Google ведут на сам отзыв (взяты из архива, вживую не открывались); у Yelp и Thumbtack отдельной ссылки нет, ссылка ведёт на листинг. Заявка Thumbtack (поле details в `reviews/raw/thumbtack-reviews.json`) это анкета клиента, не текст отзыва: её не цитируют.

#### Оговорки

1. **Цифры времени** у четырёх: Tyler Sommers, Paula Thompson (три), Lily Chaskelmann, Dr. Jalal Jalali. Слова клиентов разрешены, но аудитор их отметит.
2. **Пересечения.** Kevin N. предложен всем шести другим городам (в четвёрках Celina, Lewisville, Little Elm); Javeed N. в четвёрке Lewisville, Lily Chaskelmann в четвёрке Little Elm, Dr. Jalal Jalali в четвёрке Plano, Dale Q. вариант The Colony. Alecia K., Michael V., Margo W. ни в одной четвёрке (часть Е). Распределять по всем брифам сразу.
3. **Строка над отзывами** "Google reviews from local homeowners." верна для Tyler и Paula. С Thumbtack слово Google станет неправдой, "local" у мест 3 до 10 не подтверждено.
4. **Local Guide** в архиве не записан; на живой странице Tyler Level 4, Paula Level 2 (`reviews/ledger.csv`), читают в профиле. Город в подписи (правило 11) только у Tyler и Paula.
5. **Thumbtack** пять из десяти, 2022 до 2024 годов.

#### Если выбирать четыре сейчас

Предложение, выбор за другим чатом и за Денисом.

- Tyler Sommers (водонагреватель, Carrollton в тексте).
- Paula Thompson (смеситель ванны и унитаз, Carrollton в подписи).
- Alecia K. (лопнувшая труба в выходной).
- Michael V. (коробка кранов в прачечной и уличный кран, горелка).

Четыре разные работы, двое последних не стоят ни в одной четвёрке других городов и без цифр времени. [Критик, 3 октября 2026, около 12:00: это было верно около 10:40. Теперь Michael V. стоит в предложенной четвёрке Allen (`docs/allen-brief-2026-10-03.md`, «Если выбирать четыре сейчас»), Alecia K. на месте 4 в десятке Lewisville (в его четвёрку не вошла), Margo W. в запасе Celina и запасной на место 6 у Prosper. Javeed N. в четвёрках Lewisville и McKinney, Kevin N. в четвёрках Celina, Little Elm и Lewisville, Lily Chaskelmann в четвёрке Little Elm, Dr. Jalal Jalali в четвёрке Plano. Ни в одной четвёрке из десятки Carrollton (кроме Tyler и Paula) остались Alecia K., Margo W. и Dale Q. (все трое в десятках или запасах других городов). Вместо Michael V. подходит Margo W. (засор) или Dale Q. (цена до работы). На новом сайте ни один из десяти не стоит: `reviews/site-reviews.json` (14 страниц, 40 авторов) перечитан около 12:00.] Тогда строку "Google reviews from local homeowners." придётся поменять. Если строку держать, вместо двух Thumbtack: A P (Google, "valve replacement", август 2026, нет ни в одной четвёрке; запас, файл таблиц, часть А) и Lily Chaskelmann, если её не берёт Little Elm. Если Lewisville отдаёт Javeed N., ему место здесь вместо Michael V.: страница Carrollton и её запросы про поиск течи.

### Запас за десяткой

Чистые, но слабее или с той же работой; все **без места, не привязаны к Carrollton**; тексты в части А: A P (Google, замена крана), alex p, John W. (ни в одной десятке других городов), David H., Eric H., Laura B., Ryan E., Jaime D., Stacie B., Rob C., Sathya P., Gorden C., Matt M., Huma Ishaque, Eugenio Garcia (ZeroHart), Barbara V., Aaron M.

### Два отзыва живой страницы

Оба есть в выгрузке Google (профиль Plano, пять звёзд). Тексты на старом сайте совпадают с Google, у Paula только переносы строк и двойной пробел слиты в один. На новом сайте ни один не стоит, в резерве главной их нет. Переписанная страница города может оставить своих.

| Имя | Дата в Google | Свободен | Имя Дениса | Деньги, жалобы, комиссия | Carrollton в тексте | Работа | Цифра времени | Итог по правилам |
|---|---|---|---|---|---|---|---|---|
| Tyler Sommers | 2026-06-17 (June 2026) | да | нет ("the team") | суммы нет: "Great price", "Clear pricing" | да | водонагреватель взорвался, течь остановили, замена на следующий день | ДА: "within an hour" | **Проходит**, с пометкой о цифре. |
| Paula Thompson | 2026-01-08 (January 2026) | да | нет ("their man", "He") | суммы нет: "pricing on rectifying the problem" | да, в подписи | прокладка в смесителе ванны, деталь заменена; регулировка унитаза | ДА: "in about 20 minutes", "in 40 minutes", "within 25 minutes" | **Проходит**, с пометками о цифрах и о подписи двумя именами. |

Тексты и прямые ссылки: десятка, места 1 и 2. Что ещё видно:

- Старый сайт ставил короткие ссылки maps.app.goo.gl; в архиве есть прямые, ставить прямые.
- Подпись живой страницы "★★★★★ · Local Guide Level 4 · Carrollton, TX · June 2026 · Google"; по правилу 11 город идёт перед Local Guide.
- Paula Thompson: имя профиля одно, внутри текста подпись "Larry R. & Paul T."; отзыв не правят. Paul J. с главной (Yelp, январь 2026) не тот же человек: другая буква фамилии и другой вызов.
- Tyler пишет про замену "the very next day", а FAQ файла новой страницы "Can you replace a water heater the same day in Carrollton?" отвечает "Usually yes" и "a morning call typically means hot water by evening": рядом читается вразнобой, и это обещание времени нашими словами. Для того, кто пишет страницу.
- Tyler S. на Thumbtack (2022, с именем Дениса) может быть тем же человеком; кандидатом он не является.

### Каких работ среди кандидатов нет

Поиск слов по всем 330 свободным отзывам. Имена и причины: файл таблиц, часть В.

| Работа (тема страницы Carrollton) | Свободных | Чистых |
|---|---|---|
| Поиск течи (первый раздел и главные запросы страницы) | 4 | 2 общих: Javeed N., Barbara V.; плюс Kevin N. (скрытая течь, нашли) |
| Slab leak, течь под фундаментом | 0 | 0 |
| PRV, давление | 5 | 0 |
| Водопровод во дворе, счётчик, главный кран | 10 | 0 |
| Главная линия, корни, чугун, cleanout | 4 | 0 (Maksym Basovskyi стоит на The Colony по слову Дениса) |
| Водонагреватель | 12 | 2: Tyler Sommers (здесь), alex p |
| Дома под аренду, property managers (вопрос FAQ страницы) | 3 | 0 (двое стоят на The Colony) |
| Backflow, спринклеры | 0 | 0 |

Мешают имя Дениса, другой город, "near me" и места на других старых страницах; оба отзыва про slab leak стоят на странице slab leak. Среди чистых есть: смесители и душ, засоры и сливы, унитаз, измельчитель, уличные краны и трубы снаружи, лопнувшая труба, фильтры воды, вызовы ночью и в выходные; почти всё Thumbtack 2022 и 2023 годов. Отзывы с "plumber near me" закрыли бы PRV и течь во дворе (Inna Kravchenko) и расширительный бак (funny warner f), но Денис такие снимал 1 и 2 октября; тексты в части В.

### После выбора

Заново прочитать `reviews/site-reviews.json` и `reviews/site-ledger.md`; сверить тексты на площадках и уровень Local Guide; записать выбранных в `reviews/proposed-placement.csv` и пересобрать журнал (чат, который ставит страницу); поправить `reviews_intro`, если будет не только Google.

### Вопросы Денису

1. Tyler Sommers и Paula Thompson оставляем на Carrollton? Это единственные отзывы, где назван Carrollton; у обоих цифры времени в словах клиента, у Paula их три.
2. Отзыв Paula Thompson подписан внутри "Larry R. & Paul T.", а имя профиля Paula Thompson. Ставим как есть?
3. Была ли у кого-то из авторов без места (Javeed N., Kevin N., Alecia K., Michael V. и других из десятки) работа в Carrollton? По файлам этого не видно.
4. Про поиск течи, slab leak, PRV, водопровод во дворе и дома под аренду, главные темы страницы, чистого свободного отзыва нет. Есть ли клиент из Carrollton с такой работой, которого можно попросить оставить отзыв в Google и назвать город?
5. Отзывы со словами "plumber near me" для Carrollton по-прежнему не берём, как на Frisco? Только они закрывают PRV и течь во дворе (Inna Kravchenko).

## 6. Официальные факты

Четыре файла из `docs/briefs/carrollton/`: два файла фактов (`6a-official-city.md`, `6b-zip-and-age.md`) и две независимые перепроверки (`6a-official-city-verified.md`, `6b-zip-and-age-verified.md`). Все четыре вставлены целиком, заголовки внутри опущены на два уровня. Порядок: сначала списки «что можно брать» и «чего нельзя» из двух проверок (6.0), потом два файла фактов (6.1 и 6.2), потом остальное из проверок: итог, таблицы сверки, исправления и новые находки (6.3 и 6.4).

Рядом лежат и в бриф не вставлены: `6a-official-city-quotes.md` (полные цитаты по каждому пункту), `6a-official-city-verified-checks.md` (журнал машинной сверки цитат и адреса копий Internet Archive), `6b-zip-and-age-tables.md` (полные таблицы Census, части 1 до 8), папки `work-6a/` (28 текстов источников S01 до S28), `work-6b/` и `work-6b-verify/` (выписки и расчёты).

Важно: файлы фактов (6.1 и 6.2) писались до перепроверки. Где они расходятся со списками 6.0 и с таблицами проверки (6.3 и 6.4), верить проверке. Что поправила проверка:

- city-g2 неверен в том виде, как записан: часть «местных поправок» на деле слова самого кодекса, а вент 6 дюймов над крышей стоит в поправке к IPC, кодексу для зданий, не для домов. Исправленная формулировка в 6.3.
- city-b5: фраза закона 4265 про слив поддона при замене водонагревателя это текст самого IRC, город её оставил, а не своя поправка.
- Подтверждены, но формулировку поправить: b12, b13 (не писать «в Carrollton на это разрешение не нужно»), h2 (штраф до $2,000 в день стоит за лёд на дороге и тротуаре, не за полив), a4 (страница 2021 года, как действующее правило не подавать).
- В файле цитат `6a-official-city-quotes.md` к city-b5 приведён пункт 2 поправки P2804.6.1 со словами "located in the same room as the water heater", а на странице закона эти слова зачёркнуты: город это требование убрал, смысл обратный.
- Новое от проверки: поправка M1411.9 (конденсат кондиционера в канализацию через сифон) и P2804.6.1 (сброс T&P "an approved location or to the outdoors").
- Индексы: доля 1970-х и 1980-х в 75007 равна 59,5%, не 59,6%. Страница города о TABC и сервис USPS "Cities by ZIP Code" не открылись ни у первого помощника, ни у проверки (zip-a7, zip-a8): из них ничего не брать.
- Почти все страницы города прочитаны по копиям Internet Archive (живой сайт отвечает 403): пункты с пометкой «архив» утром сверить с живым сайтом в браузере. Регистрацию FPP в городе никто не проверял: вопрос закрыт словом Дениса от 3 октября 2026.

### 6.0. Проверенные списки: что можно брать и чего нельзя

#### Город (из `6a-official-city-verified.md`): Можно использовать в брифе

Всё ниже подтверждено; пункты "архив" перед публикацией сверить с живым сайтом.

- **a1, a2, a3, a5, a6**: город регистрирует сантехников через CityServe, бесплатно, на год, с лицензией штата и страховкой, видимой на сайте TSBPE. На странице только словами правил о нас (регистрация в городе по слову Дениса) и "our Responsible Master Plumber license, M-44816".
- **b1, b2, b3, b7, b8, b10, b14**: разрешения: общее правило с "repaired" и "replaced", водонагреватель, property line cleanout, PRV без платы за разрешение, ремонт под плитой с письмом о раскопке и засыпке, срочный ремонт с заявкой в следующий рабочий день.
- **b4** одной строкой (расширительный бак на холодной воде и прочее); подробности для страницы водонагревателей.
- **b9** только по правилу: разрешение и инспекция города, мы меняем узел, затем одна фраза "Once the new assembly is in, it gets tested and the test report goes to the city."
- **c1**: инспекцию заказывают через портал CityServe (без часов).
- **d1** как вывод, **d2, d3, d4, d5**: граница по воде и канализации; засор и корни за хозяином; дефект в right-of-way город чинит бесплатно по видео камеры от сантехника; сантехнику копать в right-of-way нельзя.
- **e1, e3, e4**: пересчёт счёта после течи с копией разрешения, если Денис скажет ставить (вопрос 6 первого помощника).
- **f2, f3, f4** без имён: "the city buys treated surface water", при нужде только Elm Fork of the Trinity River, Lake Ray Roberts, Lake Ray Hubbard, Lake Tawakoni, Lake Fork; "superior" как оценка системы TCEQ в отчёте 2024 года.
- **g1** и **g2 в исправленном виде**; новое **M1411.9** (конденсат) и **P2804.6.1** (сброс T&P).
- **h1, h3**: советы города при морозе совпадают со словами Дениса (краны в доме капают, наружный кран накрыть); главный кран по линии от счётчика.
- **h7** (316 галлонов в день) по желанию, с указанием источника.

#### Город (из `6a-official-city-verified.md`): Нельзя использовать (или только для внутренних заметок)

- **Имена из f2, f3**: "Dallas", "Dallas Water Utilities", Grapevine (запрещённый город), Lewisville (соседний город, на странице Кэрролтона не называем, и "Lake Lewisville" тоже).
- **Телефоны города** со всех страниц.
- **Суммы города**: b15 ($4 за $1,000, $75, $50), d5 ($75 и $150), h2 ($2,000), h4 ($35, $100); проценты e2. Не наши цены, но правило о цифрах строгое: только с согласия Дениса.
- **a4** как действующее правило (страница 2021 года).
- **b5** как "поправку города" и цитату пункта 2 P2804.6.1 из файла цитат (зачёркнутые слова).
- **g2 в старом виде**: вент 6 дюймов для домов; металл и бетон как местная поправка.
- **b13** в виде "в Кэрролтоне на это разрешение не нужно".
- **b11, b12, f1, h5**: это отсутствие строки, а не правило. Не писать ни "разрешение не нужно", ни обратное; цифры жёсткости продавцов не брать.
- **c2, c3, c4**: часы инспекций и Police Dispatch. Время на странице легко прочитать как наше обещание.
- **h4**, проверочная часть **b9**: проверку обратного клапана делаем не мы, кто проверяет, не называть.
- **h6**: дымовой тест сети города; наш дымовой тест живёт на /drain-services/, на странице города максимум одна фраза со ссылкой.
- Заметка газеты 2014 года о давлении: не официальная.

#### Индексы и возраст домов (из `6b-zip-and-age-verified.md`): Можно использовать в брифе

1. Почтовые индексы Carrollton с доставкой: 75006, 75007, 75010 (USPS ZIP Locale Detail, файл от 1 октября 2026). 75011 это индекс только для абонентских ящиков (класс P, "PO Box Zip" по руководству USPS).
2. Три индекса 75006, 75007, 75010 покрывают 95,3% земли города и 99,96% его жилья по переписи 2020 года (53 060 из 53 080).
3. Жилье этих индексов почти все в черте города: 75006 100%, 75007 96,1%, 75010 99,3% (перепись 2020).
4. 75019 это индекс почты Coppell: 2,8% земли Carrollton, жилья Carrollton в нем нет. Еще семь чужих индексов задевают край города: 1,9% земли, 20 единиц жилья. Показывать их как индексы Carrollton нельзя.
5. Площадь суши города с 2020 года почти та же (на 0,12% меньше), доли выше годятся сегодня.
6. Жилье города по округам (2020): Denton 60,5%, Dallas 38,5%, Collin 0,9%.
7. Медианный год постройки жилья, ACS 2020-2024, таблица B25035: Carrollton city 1988 (±2); 75006 1982 (±2), 75007 1987 (±2), 75010 2005 (±1). Жилье владельцев: город 1986, 75006 1979, 75007 1986, 75010 2005.
8. Доли по годам, весь город: до 1980 года 26,0%, 1980-1999 44,3%, 2000-2009 14,2%, 2010 и позже 15,6%. По индексам: 75006 42,8% до 1980; 75007 57,8% с 1980 по 1999; 75010 64,6% с 2000 года.
9. 75007: 1970-е и 1980-е вместе 59,5% всего жилья (исправленная цифра).
10. Дома на одну семью (включая таунхаусы, только занятое жилье): в городе 33 785, из них 10 864 (32,2%) построены до 1980 года; в 75006 таких старых 57,7%.
11. Сравнение с Фриско (2009) и Плано (1993), 75075 (1982): только как знание для автора, не для текста страницы.
12. Самая надежная одна цифра для страницы, если автор захочет ссылку на официальный источник: медианный год постройки жилья в Carrollton 1988 (U.S. Census Bureau, ACS 5-year 2020-2024, таблица B25035).

#### Индексы и возраст домов (из `6b-zip-and-age-verified.md`): Нельзя использовать

1. Цифру 59,6% для 1970-х и 1980-х в 75007: правильно 59,5%.
2. Что-либо со страницы города о TABC (и со страницы полиции): обе не открылись, текст не прочитан. Список индексов "по данным города" не подтвержден.
3. Какие названия городов почта принимает для индексов (сервис USPS "Cities by ZIP Code" не открылся).
4. Слово "station" и название ROSEMEADE на странице: на странице это не нужно; по файлу USPS это почтовое отделение ROSEMEADE в самом Carrollton.
5. Названия соседних городов из таблиц (Farmers Branch, Addison, Dallas, Hebron, Coppell, Lewisville, Plano, Frisco): только для автора. Farmers Branch, Addison, Hebron, Coppell, Grapevine и Dallas сами по себе на сайте называть нельзя совсем, а города из списка десяти нельзя называть на странице Carrollton (правило CLAUDE.md).
6. Где лежит downtown Carrollton по индексу: официально не проверено. Слова "older streets near downtown" и про чугунные трубы это знание Дениса, Census этого не подтверждает и не опровергает.
7. Счет "108 клеток без расхождений": это его счет, я его поштучно не повторял (все цифры фактов при этом проверены мной).

### 6.1. Факты города (файл `6a-official-city.md`)

Заголовок файла: «6, часть первая. Официальные факты города Кэрролтон (Carrollton)».

Проверено 3 октября 2026 года. Страница: /plumber-carrollton-tx/.

#### Как читалось: сайт города закрыт для наших инструментов

Сайт cityofcarrollton.com (страницы и PDF) на curl и WebFetch отвечает "Access Denied", 403 (защита Akamai). Свод законов города (ecode360.com, ссылка со страницы города) и codelibrary.amlegal.com отвечают проверкой Cloudflare. Защиту я не обходил. Поэтому:

1. Живой портал города CityServe, закон штата (TSBPE) и отчёты поставщика воды открылись напрямую: статус **found**.
2. Страницы и памятки города я видел только в копиях Internet Archive, почти все сняты с марта по август 2026. Статус у них **could_not_open**, слова из копии в кавычках с датой копии. Утром сверить в обычном браузере. Тот же способ, что в брифе Льюисвилла.
3. Свод законов (регистрация, вода, канализация) не прочитан. Из законов есть только закон 4265 о кодексах (PDF со страницы города, копия архива).

Тексты прочитанного: папка work-6a (в первой строке файла адрес и дата). Полные цитаты по номерам: 6a-official-city-quotes.md.

#### Главное за минуту

1. Регистрация сантехника в городе через портал CityServe: документ с фото, копия лицензии штата, страховка должна значиться активной на сайте TSBPE. Бесплатно, продление каждый год.
2. **Общее правило: разрешение нужно, когда систему "erected, installed, enlarged, altered, repaired, removed, converted, or replaced".** Отдельная строка: **ремонт под плитой, сантехник даёт "letter of excavation and backfill"**. Сильный местный факт.
3. Водонагреватель: разрешение на любой. Город требует расширительный бак на холодной воде у всех водонагревателей, поддон, кран, сгоны (unions), заземление.
4. PRV: разрешение, но если работа только PRV, **"there is no charge for that permit"**.
5. Обратный клапан на поливе: разрешение; проверку делает зарегистрированный в городе тестер, при запуске и каждый год. Совпадает с нашим правилом.
6. Инспекцию заказывают через портал CityServe. Раз в день: заявка до 7:00 утра даёт инспекцию в тот же рабочий день, позже на следующий. В пятницу после обеда инспекций нет.
7. **Канализация:** вся боковая линия от дома до врезки принадлежит хозяину, засоры его. Но **конструктивный дефект линии в городской полосе (right-of-way) город раскапывает и чинит бесплатно, если хозяин принесёт видео камеры от своего сантехника.** Сантехникам копать в right-of-way нельзя.
8. Пересчёт счёта после течи есть: бланк, описание течи, оплата ремонта и **копия разрешения**, в течение 90 дней. Работа требовала разрешения, а его не взяли за 30 дней: отказ.
9. Кодекс: International Plumbing Code **2024** с поправками, закон 4265, с 1 сентября 2025.
10. Вода покупная, поверхностная. **Цифры жёсткости в официальных отчётах нет** (город 2024, поставщик 2024 и 2025). Отчёт города за 2025 год не видел.
11. Мороз: наружные краны накрыть, краны в доме оставить капать. Совпадает с правилом Дениса.

#### Сводная таблица

| id | Вопрос | Коротко | Статус | S |
|---|---|---|---|---|
| city-a1 | Где регистрируются | Портал CityServe: "New Contractor Registration", "Renewal of Contractor Registration" | found | 1, 5 |
| city-a2 | Что требуют | Фото документа, лицензия штата, "TSBPE website must show active COI" | could_not_open | 2 |
| city-a3 | Плата, продление | Бесплатно, каждый год; "Plumbing Contractor $0" | could_not_open | 2, 3 |
| city-a4 | Без регистрации | Разрешений нет; просрочка останавливает инспекции (страница 2021 года) | could_not_open | 4 |
| city-a5 | Кто делает работу | Хозяин в своём homestead; иначе лицензированный сантехник, зарегистрированный в городе | could_not_open | 7, 8 |
| city-a6 | Закон штата | Регистрация обязательна; платы с сантехника нет; хозяин в homestead без лицензии | found | 6 |
| city-a7 | Статья свода законов | Свод не открылся | could_not_open | 29 |
| city-b1 | Общее правило | Разрешение на установку, переделку, ремонт, замену; инспекция после работы | could_not_open | 7 |
| city-b2 | FAQ | Разрешение на замену сантехнической системы; без разрешения только отделка | could_not_open | 9 |
| city-b3 | Водонагреватель | "A permit is required for the installation of all water heaters." | could_not_open | 8 |
| city-b4 | Требования к нему | Бак, поддон 1½" со сливом ¾", кран, заземление, сгоны, сброс T&P; газ: шаровой кран, подводка до 36", датчик CO | could_not_open | 8 |
| city-b5 | Поддон при замене | Закон 4265: слив не нужен, если раньше не было (расходится с S8) [Сборка: по перепроверке эта фраза закона это слова самого IRC, город их оставил, а не своя поправка; см. 6.3] | could_not_open | 25, 8 |
| city-b6 | Линия счётчик-дом | Своей строки нет; общее правило; о замене своей части сообщить в Building Inspection | could_not_open | 7, 16 |
| city-b7 | Канализационная линия | Общее правило; разрешение на property line cleanout; в right-of-way копает только город | could_not_open | 7, 15 |
| city-b8 | Замена PRV | Разрешение без платы, если работа только PRV | could_not_open | 3 |
| city-b9 | Backflow на поливе | Разрешение на полив и на любой backflow; тест лицензированным тестером; датчик дождя и мороза обязателен | could_not_open | 10, 11, 25 |
| city-b10 | Ремонт под плитой | Разрешение; "letter of excavation and backfill"; бланк "Under Slab Backfill Letter" не прочитан | could_not_open | 7, 13 |
| city-b11 | Тест труб при ремонте фундамента | Разрешение и проект инженера; о сантехнике ни слова | not_on_official_page | 12, 2 |
| city-b12 | Список работ без разрешения у города | Нет; закон меняет только строительные пункты R105.2; FAQ: только отделка | not_on_official_page | 25, 9 |
| city-b13 | Без разрешения по закону штата | Течи, смесители кухни и умывальника, "ballcocks or water control valves", измельчитель, унитаз | found | 6 |
| city-b14 | Срочный ремонт | Заявка на разрешение в следующий рабочий день | could_not_open | 9 |
| city-b15 | Плата города | Single Trade $4 за $1,000, минимум $75; работа до разрешения: ещё одна такая же плата; повторная инспекция $50 | could_not_open | 3 |
| city-b16 | Памятки для сантехников | "Guidelines for Plumbing", "Guidelines for Water Heaters", "Under Slab Backfill Letter": копий нет | could_not_open | 13 |
| city-c1 | Как заказать | Через портал CityServe | found | 1, 9, 14 |
| city-c2 | Отсечка | Раз в день; до 7:00 a.m. в тот же рабочий день, позже на следующий | could_not_open | 14, 13 |
| city-c3 | Часы инспекций | Пн-Чт 7:00 a.m. до 4:30 p.m., Пт 7:00 a.m. до 11:00 a.m. | could_not_open | 14 |
| city-c4 | Ночью | Дежурный инспектор через диспетчера полиции | could_not_open | 14 |
| city-d1 | Граница по воде | Хозяину принадлежит часть линии от счётчика к дому; городские линии без свинца | could_not_open | 16 |
| city-d2 | Свинец | "no known lead service lines in its inventory" | could_not_open | 21 |
| city-d3 | Прорыв трубы на участке | "the homeowner's responsibility, not the City" | could_not_open | 17 |
| city-d4 | Граница по канализации | Город: магистрали в right-of-way и сервитутах; хозяин: линии от магистрали, засоры, корни | could_not_open | 15 |
| city-d5 | Дефект в right-of-way | Город чинит бесплатно по видео камеры от сантехника | could_not_open | 15 |
| city-d6 | Слова закона | Главы о воде и канализации не открылись | could_not_open | 29 |
| city-e1 | Пересчёт после течи | Есть; описание, оплата ремонта, копия разрешения, 90 дней | could_not_open | 18 |
| city-e2 | Условия | 1 раз в 12 месяцев или 2 в 5 лет; 60, 50 или 40 процентов разницы; бассейн нет | could_not_open | 18 |
| city-e3 | Связь с разрешением | Нет разрешения за 30 дней: отказ | could_not_open | 18 |
| city-e4 | Как найти течь | Краска в бачок; флажок расхода на счётчике; "hire a plumber to detect where the leak is" | could_not_open | 19 |
| city-f1 | Жёсткость | Строки hardness нет в отчётах города 2024 и поставщика 2024, 2025 | not_on_official_page | 21, 23, 20 |
| city-f2 | Откуда вода, город | Покупная поверхностная вода, семь источников | could_not_open | 21, 22 |
| city-f3 | Откуда вода, поставщик 2025 | Elm Fork of the Trinity River и шесть озёр | found | 23 |
| city-f4 | Оценка штата | "Superior" по TCEQ | could_not_open | 21 |
| city-g1 | Кодекс | 2024 IPC, закон 4265, с 09/01/25; 2024 IRC, законы 4265 и 4290 | could_not_open | 24, 25 |
| city-g2 | Местные поправки | Канализация от 12 дюймов; подсыпка 4 дюйма; медь не касается бетона, гильза; фиолетовый праймер; чердак; вент 6 дюймов над крышей [Сборка: в таком виде неверно, исправленная формулировка в 6.3; вент 6 дюймов для домов не брать] | could_not_open | 25 |
| city-h1 | Мороз | Шланги снять, наружные краны накрыть, полив выключить, краны в доме капают | could_not_open | 17 |
| city-h2 | Полив в мороз | Штраф до $2,000 в день; бесплатные датчики дождя и мороза | could_not_open | 17 |
| city-h3 | Главный кран | У дома или в гараже, по линии от счётчика; "near the front of the property by the outdoor faucet" | could_not_open | 17, 19 |
| city-h4 | Тест backflow | Тестер зарегистрирован в городе и в BSI Online; при запуске и каждый год | could_not_open | 11 |
| city-h5 | Давление в сети | Цифры PSI нет; жалобы на давление принимает отдел качества воды | not_on_official_page | 26 |
| city-h6 | Дымовой тест сети | Город проверяет свою сеть; дефекты на участке чинит хозяин | could_not_open | 27 |
| city-h7 | Расход воды | Средний дом около 316 галлонов в день | could_not_open | 28 |

#### Источники (S)

CC = https://www.cityofcarrollton.com ; BI = CC/departments/departments-a-f/building-inspection . "А." = копия Internet Archive (адрес копии в первой строке файла work-6a/Snn).

- S1. Живой портал CityServe (HTTP 200): https://cityserve.cityofcarrollton.com/CityViewPortal
- S2. А. 10.05.2026 "Submittal Requirements": BI/submittal-requirements
- S3. А. 11.06.2026 "Fees": BI/fees
- S4. А. 30.11.2021 "Contractor Registration": BI/my-development/permit-processing-issuance/contractor-registration
- S5. А. 14.08.2026 "CityServe": CC/about-us/stay-connected/cityserve-permits-inspections
- S6. TSBPE "Plumbing License Law", Sept 2025, 1301.051 и 1301.551 (напрямую): https://tsbpe.texas.gov/wp-content/uploads/documents/TSBPE_PlumbingLicenseLaw(PlainView)_Sept2025.pdf
- S7. А. 11.06.2026 "Plumbing Work": BI/my-trades/plumbing-work
- S8. А. 11.06.2026 "Water Heaters": BI/my-home/water-heaters
- S9. А. 12.05.2026 "FAQs": BI/faqs
- S10. А. 11.06.2026 "Landscape Irrigation": BI/my-home/landscape-irrigation
- S11. А. 12.05.2026 "Cross Connection Program": CC/departments/departments-g-p/public-works/cross-connection-program
- S12. А. 11.06.2026 "Foundation Repair": BI/my-home/foundation-repair
- S13. А. 11.06.2026 "Inspection Services": BI/my-development/inspection-services
- S14. А. 14.08.2026 "Building Inspection": BI
- S15. А. 10.05.2026 "Sewer Stoppage Policy": CC/departments/departments-g-p/public-works/water-and-wastewater/sewer-stoppage-policy
- S16. А. 16.03.2026 "Lead & Copper Rule Revisions": CC/departments/departments-a-f/engineering/lead-and-copper-rule
- S17. А. 14.08.2026 "Inclement Weather": CC/residents/public-safety/inclement-weather
- S18. А. 12.04.2026 "Leak Adjustments": CC/departments/departments-q-z/utility-customer-service/leak-adjustments
- S19. А. 14.05.2026 "FAQs - Water Billing": CC/departments/departments-q-z/utility-customer-service/faqs/faqs-water-billing
- S20. А. 06.06.2026 "Water Quality": CC/departments/departments-g-p/public-works/water-and-wastewater/water-quality ; отчёт 2025: CC/home/showpublisheddocument/41148/639131665146570000 (копии нет)
- S21. А. 06.06.2026 "2024 Drinking Water Quality Report" (PDF): CC/home/showpublisheddocument/39460/638822928128870000
- S22. А. 13.11.2024 "FAQ's City of Carrollton Water": CC/departments/departments-a-f/environmental-quality/water-conservation/faq-s-city-of-carrollton-water
- S23. Поставщик (напрямую, "April 2026 Update"): https://dallascityhall.com/departments/waterutilities/Pages/water_quality_reports.aspx ; 2025: https://dallascityhall.com/departments/waterutilities/Documents/2025%20WQR-ENG-FINAL.pdf ; 2024: https://dallascityhall.com/departments/waterutilities/Documents/COD25-WQR2024-Report-ENG-Final.pdf
- S24. А. 14.06.2026 "Codes & Ordinances": BI/codes-ordinances
- S25. А. 20.08.2026 ORDINANCE NO. 4265 (PDF): CC/home/showpublisheddocument/39720/639057137488300000 (в work-6a выдержка)
- S26. А. 11.06.2026 "Water And Wastewater": CC/departments/departments-g-p/public-works/water-and-wastewater
- S27. А. "Smoke Testing Program": CC/departments/departments-g-p/public-works/water-and-wastewater/smoke-testing-program
- S28. А. 17.04.2026 "Water Robbers": CC/departments/departments-a-f/environmental-quality/water-conservation/water-robbers
- S29. Свод законов: https://ecode360.com/CA6876 и https://codelibrary.amlegal.com/codes/carrolltontx/latest/overview , проверка Cloudflare, не прочитан.

#### Пояснения

**a.** Действующие требования: S2 (май 2026). Правило "Permits will not be issued until all contractors are registered" есть только на странице 2021 года (S4): использовать осторожно. Бланк регистрации в портале закрыт входом в учётную запись, я его не открывал.

**b.** Общее правило города очень широкое: "repaired" и "replaced" стоят прямо в списке (S7). Значит, почти любой ремонт трубы формально под разрешением, кроме того, что освободил штат (S6, 1301.551(c)). Прямые строки есть для водонагревателя, полива, ремонта под плитой, чистки у границы участка, PRV и фундамента; для линии счётчик-дом и замены канализации нет. Начал работу до разрешения: "investigation fee" равна плате за разрешение (S3).

Расхождение (b5): памятка S8 требует поддон со сливом у каждого водонагревателя, а закон 4265 при замене слив не требует, если его не было. Закон новее, но решает инспектор: вопрос Денису. [Сборка: по перепроверке фраза закона про слив поддона это текст самого IRC, не поправка города; расхождение с памяткой остаётся, см. 6.3.]

**c.** Отсечка 7:00 утра стоит на главной странице отдела (S14, август 2026). Телефон-автомат (IVR) упомянут только в старом тексте S13.

**d.** По воде прямой фразы "город отвечает до счётчика" нет; есть страница о свинце (S16): "the portion of the service line you own" начинается у счётчика со стороны дома. По канализации всё сказано прямо (S15), включая бесплатный ремонт дефекта в right-of-way по видео.

**e.** Для страницы главное: город просит описание течи, оплату ремонта и копию разрешения. Наш счёт с описанием работы и есть такой документ.

**f.** Жёсткости нет нигде из официального. Цифры в gpg у продавцов смягчителей и агрегаторов (6.5, 7.2, 7.8, 8.2, 8.5) не официальные и расходятся: не использовать. На S26 в услугах стоит "Monthly mineral analysis reports", самого отчёта на прочитанных страницах нет.

**g.** Закон 4290 ("Additional Amendments") в архиве не сохранён. В текстовом слое закона 4265 зачёркнутые и новые слова идут подряд: цитировать только целые фразы.

#### Чего нельзя переносить на страницу как есть

1. **Имя поставщика воды.** Город покупает воду "with the City of Dallas", поставщик "Dallas Water Utilities". Слово "Dallas" отдельно на сайте не пишем. В списке озёр Grapevine (запрещённый город) и Lewisville (соседний город, на странице Кэрролтона соседей не называем). Если писать об источнике: "purchases water", "surface water" без имён, или только Elm Fork of the Trinity River, Lake Ray Roberts, Lake Ray Hubbard, Lake Tawakoni, Lake Fork.
2. **Телефоны города** на страницу не ставить.
3. **Суммы города** ($75, $50, $35, $75 и $150 за выезд бригады, $2,000 штраф) не наши цены, но правило про цифры строгое: только с согласия Дениса.
4. **Проверку обратного клапана мы не делаем.** Только разрешённая фраза: "Once the new assembly is in, it gets tested and the test report goes to the city."
5. **Дымовой тест города** (S27) проверяет городскую сеть. Наш дымовой тест принадлежит /drain-services/: максимум одна фраза со ссылкой.
6. **"Same business day inspection"** это про инспектора, не обещание нашего приезда.
7. В цитатах "property owner"; на странице "the homeowner". Памятка о водонагревателе про tankless молчит, риска нет.

#### Одна официальная ссылка: кандидаты

Сайт города отвечает роботам 403, проверка ссылок может пометить ссылку как битую, хотя в браузере страница живая.

1. BI/my-trades/plumbing-work (разрешения, письмо при ремонте под плитой). Лучший по смыслу.
2. CC/departments/departments-g-p/public-works/water-and-wastewater/sewer-stoppage-policy (граница по канализации, видео от сантехника).
3. CC/departments/departments-q-z/utility-customer-service/leak-adjustments (пересчёт счёта, копия разрешения).
4. https://cityserve.cityofcarrollton.com/CityViewPortal (открывается и роботам, но это страница входа).

#### Что не сделано

1. Живой сайт города не открыт ни одной страницей. Утром сверить в браузере, в первую очередь: отчёт о воде за 2025 год (есть ли жёсткость), памятки "Guidelines for Plumbing", "Guidelines for Water Heaters", "Under Slab Backfill Letter", закон 4290.
2. Свод законов не прочитан.
3. Регистрацию FPP в городе не проверял: вопрос закрыт словом Дениса от 3 октября.

#### Вопросы Денису

1. Ремонт течи под плитой в Кэрролтоне: берёте разрешение на каждый? Что пишете в "letter of excavation and backfill"?
2. Были ли вызовы, где после вашей камеры город сам чинил канализацию в right-of-way? Готовая живая история под правило города.
3. При замене водонагревателя инспектор Кэрролтона требует слив поддона наружу, если его раньше не было?
4. PRV в Кэрролтоне: берёте бесплатное разрешение? Какое давление обычно на манометре?
5. Знаете жёсткость воды в Кэрролтоне по опыту или по месячному отчёту города? Официальной цифры нет.
6. Ставить ли на страницу факт о пересчёте счёта (копия разрешения, 90 дней)?

### 6.2. Индексы и возраст домов (файл `6b-zip-and-age.md`)

Заголовок файла: «6, часть вторая. Почтовые индексы Carrollton и возраст домов».

Проверено 3 октября 2026. Все цифры взяты из официальных файлов USPS и Census Bureau, адреса запросов стоят в конце раздела. Ничего не придумано: где проверить не удалось, так и написано. Полные таблицы лежат рядом, в файле 6b-zip-and-age-tables.md, рабочие выписки и расчеты в папке work-6b.

#### Коротко, самое важное

1. У почты в Carrollton четыре индекса. Жилых, с доставкой почты, три: 75006, 75007, 75010. Индекс 75011 это только абонентские ящики (PO BOX), домов там нет.
2. Эти три индекса и есть Carrollton: в них 95,3% земли города и 99,96% его жилья (перепись 2020 года: 53 060 из 53 080 единиц жилья). И наоборот, почти все жилье этих индексов лежит в черте города: 75006 100%, 75010 99,3%, 75007 96,1%.
3. Общие с соседями индексы. 75019 (почта COPPELL) содержит 2,8% земли Carrollton, но ни одного жилого дома города. Еще семь чужих индексов задевают город краем (75067, 75057, 75056, 75093, 75234, 75001, 75287): вместе 1,9% земли и 20 единиц жилья. Свои три индекса тоже чуть заходят к соседям, подробно в части а.
4. Медианный год постройки жилья, ACS 2020-2024: Carrollton city 1988 (±2). По индексам: 75006 1982 (±2), 75007 1987 (±2), 75010 2005 (±1).
5. По годам, весь город: до 1980 года построено 26,0% жилья, с 1980 по 1999 год 44,3%, с 2000 по 2009 год 14,2%, в 2010 году и позже 15,6%. Самое большое десятилетие это 1980-е (28,4%).
6. Для сравнения тем же выпуском: Frisco city 2009 (±1), Plano city 1993 (±2). Carrollton по медиане на 21 год старше Фриско и на 5 лет старше Плано.
7. Census API (api.census.gov) без ключа не отвечает (проверено 3 октября 2026). Ключ я не запрашивал: это регистрация с почтой, такое делает только Денис. Те же цифры взяты из официальных файлов Census (ACS Summary File, размеры файлов сверены с сервером) и сверены с сайтом data.census.gov: 108 клеток, несовпадений ноль.

#### а. Индексы Carrollton

Источник 1: USPS, файл "ZIP Locale Detail" (Zip_Locale_Detail.xlsx, на сервере файл от 1 октября 2026, 4 380 487 байт). Источник 2: Census Bureau, файл связи участков ZCTA и городов 2020 года, место "Carrollton city", код 4813024. Источник 3: перепись 2020 года, жилье по кварталам (Block Assignment File 2020 и карта Census TIGERweb), подробности метода в таблице 2 файла с таблицами.

ZCTA это "ZIP Code Tabulation Area": участок, которым Census приближенно повторяет почтовый индекс. По ним считается вся статистика ниже.

| Индекс | USPS: класс | USPS: почтовое отделение (адрес здания по файлу USPS) | Доля земли города в участке | Доля земли участка в черте Carrollton | Жилье Carrollton в участке, 2020 | С кем индекс общий |
|---|---|---|---|---|---|---|
| 75006 | обычный, с доставкой | CARROLLTON, главное отделение (2030 E Jackson Rd) | 45,6% | 97,8% | 19 083 (36,0% жилья города); это все жилье участка | Farmers Branch city 1,6% земли, Dallas city 0,4%, Addison town 0,2%; жилья там по переписи нет |
| 75007 | обычный, с доставкой | ROSEMEADE, станция (3755 N Josey Ln, город Carrollton) | 32,0% | 98,5% | 20 125 (37,9% жилья города); 96,1% жилья участка | Dallas city 1,2% земли, Hebron town 0,1%, земля вне городов 0,2%; 813 единиц жилья участка вне Carrollton |
| 75010 | обычный, с доставкой | ROSEMEADE, станция | 17,7% | 95,3% | 13 852 (26,1% жилья города); 99,3% жилья участка | Hebron town 2,6% земли, Lewisville city 2,0%; 101 единица жилья участка вне Carrollton |
| 75011 | P, только абонентские ящики | CARROLLTON и ROSEMEADE | нет участка | нет участка | домов нет | |
| 75019 | обычный | COPPELL (450 S Denton Tap Rd, город Coppell) | 2,8% | 6,0% | 0 | Coppell city 79,5% земли, Dallas city 13,2% |
| 75067, 75057, 75056, 75093, 75234, 75001, 75287 | обычные | почта LEWISVILLE, THE COLONY, COIT (Plano), FARMERS BRANCH, ADDISON, BENT TREE | вместе 1,9% | от 0,08% до 1,9% | вместе 20 (в 75056 и 75234) | это индексы соседних городов |

Что еще видно в источниках:

- Абонентские ящики. В файле USPS индексы "только PO BOX" помечены буквой P в поле "ZIP CLASS CODE". В Carrollton так помечен один индекс, 75011, он записан и за главным отделением, и за станцией ROSEMEADE. Участка ZCTA у него нет, статистики нет. В листах файла "Unique" и "Other" строк Carrollton TX нет.
- ROSEMEADE это название почтовой станции, а не другой город: в поле "PHYSICAL CITY" у нее стоит CARROLLTON.
- Граница города с 2020 года почти не менялась: суша по файлу 2020 года 94 939 827 кв. м, по сегодняшней карте и по границе выпуска ACS 2024 (TIGERweb, слой Incorporated Places) 94 827 763 кв. м, на 0,12% меньше. Значит доли выше годятся и сегодня.
- Где лежат участки (центры участков ZCTA по TIGERweb, округлено до тысячных): 75006 (юг города); 75007 (середина); 75010 (север). [Сборка: цифры широты и долготы трёх участков убраны, в брифе координат нет; они есть в файле раздела.] Все три стоят на одной долготе, город вытянут с юга на север.
- Город лежит в трех округах (тот же расчет по кварталам 2020 года): Denton County 60,5% жилья, Dallas County 38,5%, Collin County 0,9%.
- Официальную страницу города со списком индексов открыть не удалось. Поиск по cityofcarrollton.com нашел две страницы, где, судя по описанию поиска, перечислены индексы 75006, 75007, 75010 (и на одной 75011): страница о разрешениях TABC (/government/city-manager-s-office/city-secretary/tabc-information) и страница полиции. Обе ответили 403 и на curl, и на WebFetch; сам текст я не прочел, поэтому как источник их не использую.
- Сервис USPS "Cities by ZIP Code" (какие названия городов почта принимает для индекса) на один обычный запрос ответил перенаправлением на страницу о сбое (anyapp_outage_apology). Обходить защиту я не стал. Список "принимаемых" названий для индексов не проверен.

Для автора страницы: если индексы вообще показывать, то три: 75006, 75007, 75010. 75011 не нужен (ящики), 75019 не нужен (жилья Carrollton там нет, это индекс почты Coppell). Города Farmers Branch, Addison, Dallas, Hebron, Coppell, Grapevine на сайте называть нельзя совсем, а Lewisville, The Colony, Plano нельзя называть на странице Carrollton (правило CLAUDE.md: городская страница не называет соседей). Название станции ROSEMEADE на странице не нужно.

#### б. Медианный год постройки по индексам (таблица B25035)

Выпуск: American Community Survey, 5-year, 2020-2024 (в файлах Census это "2024 ACS 5-year"). Это самый новый выпуск, который знает API: описание переменной B25035_001E за 2024 год отвечает ("Estimate!!Median year structure built"), за 2025 год ответ 404. Папка 2025 года на сервере файлов Census уже появилась (датирована 29 сентября 2026), но папки data и documentation в ней пустые, данных 5-year 2021-2025 там нет. Файлы 2024 года на сервере датированы 29 января 2026. Рядом для сравнения прошлый выпуск, 2019-2023.

"Медианный год" значит: половина жилья построена раньше этого года, половина позже. "±" это погрешность опроса из того же файла (ACS это выборочный опрос, не перепись). Считается все жилье, и дома, и квартиры. Поэтому рядом медиана по жилью, где живет сам владелец (таблица B25037): это ближе к частным домам.

| Участок | Где | Медиана, все жилье, 2020-2024 (B25035_001E) | Погрешность | Выпуск 2019-2023 | Медиана, жилье владельцев (B25037_002) | Медиана, съемное жилье (B25037_003) | Всего жилья (B25034_001) |
|---|---|---|---|---|---|---|---|
| 75006 | юг города, 100% жилья участка в Carrollton | 1982 | ±2 | 1982 (±1) | 1979 (±2) | 1986 (±2) | 19 640 |
| 75007 | середина, 96% жилья в Carrollton | 1987 | ±2 | 1986 (±1) | 1986 (±1) | 1988 (±1) | 21 696 |
| 75010 | север, 99% жилья в Carrollton | 2005 | ±1 | 2004 (±1) | 2005 (±2) | 2004 (±1) | 14 322 |
| 75019 | почта Coppell, жилья Carrollton нет, только для сведения | 1995 | ±1 | 1994 (±1) | 1993 (±1) | 2000 (±3) | 17 530 |
| Carrollton city, Texas (штат 48, место 13024) | весь город | 1988 | ±2 | 1988 (±1) | 1986 (±1) | 1993 (±2) | 54 365 |
| Frisco city, Texas (48 и 27684) | | 2009 | ±1 | 2009 (±2) | 2008 (±1) | 2011 (±1) | 80 353 |
| Plano city, Texas (48 и 58016) | | 1993 | ±2 | 1993 (±1) | 1991 (±1) | 1997 (±1) | 117 686 |
| Texas | | 1992 | ±1 | 1990 (±1) | 1993 (±1) | 1991 (±1) | 12 128 515 |

Цифры Frisco и Plano совпадают с уже проверенным разделом Плано (docs/briefs/plano/6b-zip-and-age.md). Все медианы строк 75006, 75007, 75010, 75019 и трех городов сверены с data.census.gov, совпали.

Как читать: три индекса Carrollton почти целиком сам город, поэтому их цифры прямо описывают его части. Сумма жилья трех участков (55 658) немного больше, чем во всем городе (54 365): в участки входят края соседей (813 единиц в 75007, 101 в 75010 по переписи 2020 года), и выпуск ACS считает по выборке.

#### в. Доли по годам постройки (таблица B25034, все жилье)

Выпуск тот же, 2020-2024. Проценты посчитаны мной из чисел файла: "до 1980" это строки 007-011, "1980-1999" строки 005 и 006, "2000-2009" строка 004, "2010 и позже" строки 002 и 003. Названия строк сверены с официальным файлом описаний (Table Shells).

| Участок | Построено до 1980 | 1980-1999 | 2000-2009 | 2010 и позже |
|---|---|---|---|---|
| 75006 | 42,8% | 38,2% | 7,4% | 11,5% |
| 75007 | 25,1% | 57,8% | 10,4% | 6,7% |
| 75010 | 3,1% | 32,4% | 29,2% | 35,4% |
| 75019 (для сведения) | 6,1% | 61,3% | 12,1% | 20,5% |
| Carrollton city | 26,0% | 44,3% | 14,2% | 15,6% |
| Frisco city | 1,5% | 16,9% | 34,8% | 46,7% |
| Plano city | 18,4% | 50,3% | 17,6% | 13,7% |

Самые заметные десятилетия по индексам (все жилье): в 75006 это 1980-е (28,8%), 1970-е (24,3%) и 1960-е (12,2%), а 1950-е еще 5,4%; в 75007 это 1980-е (38,2%) и 1970-е (21,4%); в 75010 это 2010-е (31,7%) и 2000-е (29,2%).

Только дома на одну семью (таблица B25127, строка "1, detached or attached", владельцы и съемщики вместе; там периоды по двадцать лет, но они совпадают с группами "до 1980" и "1980-1999"):

| Участок | Домов на одну семью | Доля от занятого жилья | Дома до 1980 | Дома 1980-1999 | Дома 2000 и позже |
|---|---|---|---|---|---|
| 75006 | 10 570 | 56,3% | 57,7% | 36,4% | 6,0% |
| 75007 | 15 774 | 75,9% | 28,9% | 59,1% | 11,9% |
| 75010 | 7 697 | 56,9% | 3,2% | 37,1% | 59,7% |
| Carrollton city | 33 785 | 65,0% | 32,2% | 47,4% | 20,4% |
| Frisco city | 57 248 | 74,1% | 1,5% | 18,3% | 80,2% |
| Plano city | 72 982 | 64,9% | 24,1% | 53,3% | 22,6% |

В Carrollton 10 864 дома на одну семью построены до 1980 года. Из домов до 1980 года в трех индексах 55,9% стоят в 75006, 41,9% в 75007 и только 2,3% в 75010. Жилье владельцев по десятилетиям и прошлый выпуск лежат в файле с таблицами (таблицы 6 и 7).

#### г. Carrollton рядом с Фриско и Плано

- Carrollton старше обоих: медиана года постройки 1988 (±2) против 1993 (±2) у Плано и 2009 (±1) у Фриско; по жилью владельцев 1986 против 1991 и 2008. До 1980 года построено 26,0% жилья Carrollton, у Плано 18,4%, у Фриско 1,5%; среди домов на одну семью 32,2%, 24,1% и 1,5%.
- Юг Carrollton (75006, медиана 1982, жилье владельцев 1979) по возрасту такой же, как самый старый индекс Плано 75075 (медиана 1982 по разделу Плано). Север (75010, медиана 2005) ближе к Фриско, но и там треть жилья построена с 1980 по 1999 год.
- Это только для автора: на странице Carrollton другие города не упоминаются (правило CLAUDE.md), сравнение с Фриско и Плано на страницу не выносить.

#### Сверка с живой страницей

На живой странице Carrollton (source/crawl/pages/plumber-carrollton-tx.json) и в нынешнем тексте нового сайта (site/src/content/pages/plumber-carrollton-tx.md) стоит: "from the older streets near downtown to the newer sections up north". И в разделе "What Else We Run Into Here": "Carrollton has houses from very different decades".

- "Very different decades" данные подтверждают: каждое десятилетие с 1960-х по 2010-е дает от 5,0% (1960-е) до 28,4% (1980-е) жилья города.
- "Newer sections up north" сходится только для самого севера, 75010 (медиана 2005, 64,6% жилья построено в 2000 году и позже). Середина города, 75007, тоже лежит севернее юга, но там дома 1970-х и 1980-х (59,6% всего жилья [Сборка: перепроверка 6.4 даёт 59,5%]), медиана 1987.
- "Older streets near downtown": самый старый индекс это южный 75006 (медиана 1982, 57,7% домов на одну семью до 1980 года). В каком индексе лежит сам downtown, я по официальному источнику не проверял (страницы города ответили 403). Если Денис имеет в виду юг города, слова с данными сходятся.
- Слова живой страницы про чугунные (cast iron) канализационные трубы в старых частях города статистика Census проверить не может: о материалах труб в ACS ничего нет. Это знание Дениса с вызовов.
- Цифры Census на страницу лучше не выносить россыпью. Если автор захочет одну цифру со ссылкой на официальный источник, самая надежная: медианный год постройки жилья в Carrollton 1988 (ACS 2020-2024, таблица B25035, Carrollton city, Texas).

#### Вопросы Денису

1. Показывать ли на странице Carrollton почтовые индексы вообще. Если да, по данным это три индекса: 75006, 75007, 75010.
2. Что он называет "older streets near downtown" и "newer sections up north": это юг города (75006) и самый север (75010)? И что он видит в середине города (75007), где по данным больше всего домов 1970-х и 1980-х.

#### Адреса запросов

Census API, как просили в задании, и что он ответил (3 октября 2026):

- https://api.census.gov/data/2024/acs/acs5?get=NAME,B25035_001E&for=zip%20code%20tabulation%20area:75006,75007,75010,75019 : ответ 302, перенаправление на https://api.census.gov/data/missing_key.html (на ней: "A valid key must be included with each data API request.").
- https://api.census.gov/data/2024/acs/acs5?get=NAME,B25035_001E&for=place:13024,27684,58016&in=state:48 (Carrollton, Frisco, Plano): ответ 302, то же.
- https://api.census.gov/data/2025/acs/acs5?get=NAME,B25035_001E&for=zip%20code%20tabulation%20area:75006,75007,75010,75019 : ответ 302, то же.
- https://api.census.gov/data/2024/acs/acs5/variables/B25035_001E.json : ответ 200, "Estimate!!Median year structure built". Для 2025 года тот же адрес дает 404.
- Когда у Дениса будет свой ключ, те же цифры дадут запросы: https://api.census.gov/data/2024/acs/acs5?get=NAME,B25035_001E,B25035_001M&for=zip%20code%20tabulation%20area:75006,75007,75010&key=КЛЮЧ и https://api.census.gov/data/2024/acs/acs5?get=NAME,B25035_001E,B25035_001M&for=place:13024,27684,58016&in=state:48&key=КЛЮЧ

Откуда цифры взяты на самом деле (официальные файлы Census, без ключа). Файлы скачаны с www2.census.gov этой ночью соседним помощником; размеры и даты сверены с сервером, совпали (work-6b/census-head.txt):

- https://www2.census.gov/programs-surveys/acs/summary_file/2024/table-based-SF/data/5YRData/acsdt5y2024-b25035.dat (медиана, все жилье)
- https://www2.census.gov/programs-surveys/acs/summary_file/2024/table-based-SF/data/5YRData/acsdt5y2024-b25034.dat (по десятилетиям)
- https://www2.census.gov/programs-surveys/acs/summary_file/2024/table-based-SF/data/5YRData/acsdt5y2024-b25036.dat и acsdt5y2024-b25037.dat (владельцы и съемщики)
- https://www2.census.gov/programs-surveys/acs/summary_file/2024/table-based-SF/data/5YRData/acsdt5y2024-b25127.dat (по типу здания)
- https://www2.census.gov/programs-surveys/acs/summary_file/2023/table-based-SF/data/5YRData/acsdt5y2023-b25035.dat и acsdt5y2023-b25034.dat (прошлый выпуск)
- https://www2.census.gov/programs-surveys/acs/summary_file/2024/table-based-SF/documentation/ACS20245YR_Table_Shells.txt и Geos20245YR.txt (названия строк и участков)
- https://www2.census.gov/programs-surveys/acs/summary_file/2025/table-based-SF/ (папка 2025 года, data и documentation пустые)
- Строки в файлах: 860Z200US75006, 860Z200US75007, 860Z200US75010, 860Z200US75019, 1600000US4813024 (Carrollton city, Texas), 1600000US4827684, 1600000US4858016, 0400000US48.

Сверка на сайте data.census.gov (один участок на запрос, 108 клеток, все совпали с файлами, work-6b/datacensus-crosscheck.txt):

- https://data.census.gov/api/access/data/table?id=ACSDT5Y2024.B25035&g=860XX00US75006 (и так же 75007, 75010, 75019, 160XX00US4813024, 160XX00US4827684, 160XX00US4858016)
- https://data.census.gov/api/access/data/table?id=ACSDT5Y2024.B25034&g=860XX00US75006 (и так же 75007, 75010, 160XX00US4813024)
- https://data.census.gov/api/access/data/table?id=ACSDT5Y2024.B25037&g=160XX00US4813024

Индексы, перепись 2020 года и карта:

- https://postalpro.usps.com/mnt/glusterfs/2026-10/Zip_Locale_Detail.xlsx (строки Carrollton TX выписаны в work-6b/usps-zip-locale-carrollton.txt)
- https://tools.usps.com/tools/app/ziplookup/cityByZip (форма "Cities by ZIP Code", один запрос для 75006: перенаправление на страницу о сбое, не открыто)
- https://www2.census.gov/geo/docs/maps-data/data/rel2020/zcta520/tab20_zcta520_place20_natl.txt (строки с кодом 4813024 в work-6b/zcta_place_carrollton.txt)
- https://www2.census.gov/geo/docs/maps-data/data/baf2020/BlockAssign_ST48_TX.zip (кварталы города, код места 13024, 1 825 кварталов)
- https://tigerweb.geo.census.gov/arcgis/rest/services/TIGERweb/tigerWMS_Census2020/MapServer/10/query (жилье по кварталам 2020 года, запросы по номерам кварталов)
- https://tigerweb.geo.census.gov/arcgis/rest/services/TIGERweb/tigerWMS_Current/MapServer/2/query?where=ZCTA5%20IN%20('75006','75007','75010','75019')&outFields=ZCTA5,GEOID,CENTLAT,CENTLON,INTPTLAT,INTPTLON,AREALAND&returnGeometry=false&f=json (центры участков)
- https://tigerweb.geo.census.gov/arcgis/rest/services/TIGERweb/tigerWMS_ACS2024/MapServer/28/query?where=GEOID%3D'4813024'&outFields=GEOID,NAME,AREALAND,AREAWATER&returnGeometry=false&f=json (граница города в выпуске ACS 2024; так же tigerWMS_Current)
- https://data.census.gov/api/access/data/table?id=DECENNIALPL2020.H1&g=160XX00US4813024 (жилье Carrollton по переписи 2020 года: 53 080)
- https://data.census.gov/api/access/data/table?id=DECENNIALDHC2020.H1&g=860XX00US75006 (и так же 75007, 75010: 19 083, 20 938, 13 953)

#### Оговорки

- ACS это выборочный опрос за пять лет (2020-2024), у каждой цифры есть погрешность. У медиан она от 1 до 2 лет. Доли посчитаны из оценок; различия в один или два процента ничего не значат.
- Участок ZCTA повторяет почтовый индекс приближенно.
- "Жилье" в B25034 и B25035 это все жилые единицы, квартиры тоже. Для домов надежнее смотреть жилье владельцев (B25036, B25037) и дома на одну семью (B25127).
- Доли жилья по участкам посчитаны мной по кварталам переписи 2020 года (квартал отнесен к участку по его внутренней точке), это не готовая цифра из источника. Итог по городу совпал с официальной цифрой переписи (53 080), а по 75006 с официальной цифрой участка (19 083).
- Названия районов (downtown, Rosemeade как район) у Census нет, их привязка к индексам здесь не проверена.
- Выписки и расчеты лежат в папке work-6b (tables.py, make_fragments.py, blocks_by_zip.py, crosscheck.py). Координат ниже уровня ZCTA там нет.

### 6.3. Перепроверка фактов города (файл `6a-official-city-verified.md`)

Заголовок файла: «6a. Проверка официальных фактов Кэрролтона (вторая пара глаз)». Два списка этого файла («Можно использовать в брифе» и «Нельзя использовать») стоят в 6.0, остальное здесь.

Проверено 3 октября 2026 года. Проверял не тот помощник, который собирал факты: каждый источник я открыл сам, своими запросами. Проверяемый файл: 6a-official-city.md (и цитаты к нему 6a-official-city-quotes.md).

Как проверял:

1. **Живые источники** открыл сам: портал CityServe (200), закон штата TSBPE (200; страница законов TSBPE сегодня ссылается именно на эту редакцию "Sept2025"), отчёты поставщика воды за 2024 и 2025 годы (200), список вопросов FAQ на сайте поставщика (15 вопросов, через его открытый список).
2. **Сайт города** и сегодня отвечает 403 "Access Denied" (одна попытка, на отчёт о воде за 2025 год). Свод законов на ecode360 и codelibrary.amlegal.com отвечает 403 "Just a moment..." (по одной попытке). Защиту не обходил.
3. **Страницы города** проверил по копиям Internet Archive: сам запросил индекс архива по каждой странице и сам скачал самую свежую копию. Новее, чем у первого помощника, копий нет. 140 цитат сверены машиной слово в слово, спорные места прочитаны глазами. Журнал сверки и адреса копий: **6a-official-city-verified-checks.md**.
4. **Закон 4265** (PDF, архив 20.08.2026): страницы 30, 34, 35 и 82 я перевёл в картинки и прочитал глазами, потому что в тексте PDF не видно, какие слова город подчеркнул (новые) и какие зачеркнул (убрал). Это дало две ошибки и две новые находки.

Пункты "архив" утром сверить с живым сайтом в браузере.

#### Итог за минуту

- Из 50 фактов подтверждено 49, **неверный один: city-g2** (часть "местных поправок" на деле слова самого кодекса, а вент 6 дюймов стоит в кодексе для зданий, не для домов).
- Все 5 фактов "found" подтверждены на живых страницах. Все 4 "not_on_official_page" подтверждены: официальной строки нет и у меня (жёсткость, давление, проверка труб при ремонте фундамента, свой список работ без разрешения).
- Подтверждены, но формулировку поправить: **b5** (фраза про слив поддона это текст самого кодекса IRC, не новая поправка города), **b12**, **b13**, **h2**, **a4**.
- **Ошибка в файле цитат** (не в списке фактов): к city-b5 там приведён пункт 2 поправки P2804.6.1 "Discharge through an air gap located in the same room as the water heater." На странице закона слова "located in the same room as the water heater" **зачёркнуты**: город это требование убрал. Смысл обратный.
- **Новое и сильное:** поправка города M1411.9 к жилому кодексу: конденсат кондиционера идёт в канализацию через сифон. Это прямо про самый частый вызов октября (слив мойки с врезанной линией конденсата).

#### Таблица проверки

"А. дата" значит копия Internet Archive этой даты, скачанная мной; живая страница 403.

| id | Что утверждалось (коротко) | Где проверил | Подтверждено | Заметка |
|---|---|---|---|---|
| city-a1 | Регистрация через портал CityServe, три пункта; форма за входом | портал, живой | да | Три пункта дословно. Ссылка "New Contractor Registration" ведёт на страницу входа /CityViewPortal/Account/Logon. |
| city-a2 | Фото документа, лицензия штата, страховка активна на сайте TSBPE, лицензию проверяют при выдаче разрешения | А. 10.05.2026, Submittal Requirements | да (архив) | Все фразы дословно. |
| city-a3 | Бесплатно, каждый год; "Plumbing Contractor $0" | А. 10.05.2026; А. 11.06.2026, Fees | да (архив) | "$0" стоит в разделе "License/Registration". |
| city-a4 | Без регистрации разрешений нет; просрочка останавливает инспекции | А. 30.11.2021 | да (архив 2021) | Копий новее 2021 года у этой страницы нет. Как действующее правило не подавать; действующие требования в a2, a3. |
| city-a5 | Хозяин в своём homestead; иначе лицензированный сантехник, зарегистрированный в городе | А. 11.06.2026, Plumbing Work и Water Heaters | да (архив) | Дословно на обеих страницах. |
| city-a6 | Закон штата: регистрация обязательна, платы нет, хозяин в homestead без лицензии | TSBPE, живой | да | 1301.551(g), (h) и 1301.051 дословно. |
| city-a7 | Свод законов не прочитан, проверка Cloudflare | ecode360, amlegal | да | Оба 403 "Just a moment...". |
| city-b1 | Общее правило разрешения, инспекция после работы, заявка через CityServe | А. 11.06.2026, Plumbing Work | да (архив) | Дословно. |
| city-b2 | FAQ: разрешение на замену системы; без разрешения только отделка; код соблюдать; плата не возвращается | А. 12.05.2026, FAQs | да (архив) | Дословно. |
| city-b3 | Разрешение на любой водонагреватель, инспекция после работы | А. 11.06.2026, Water Heaters | да (архив) | Дословно. |
| city-b4 | Список требований к водонагревателю | А. 11.06.2026 | да (архив) | Все пункты дословно. Там же ещё: "If installed in garages and attics, water pipes must be insulated." и "If installed in garage, there must be pan drain pipes to floor or outside." |
| city-b5 | Поправка P2801.5.1: при замене слив поддона не нужен, если не было | закон 4265, стр. 34, глазами | да, с поправкой | Фраза стоит в разделе P2801.5.1 закона, но **не подчёркнута**: это слова самого IRC, город их оставил. Подчёркнуто (новое от города) только "Multiple pan drains may terminate to a single discharge piping system when approved by the building official...". Расхождение с памяткой города b4 остаётся. |
| city-b6 | Своей строки про линию счётчик-дом нет; сообщить в Building Inspection | А. 16.03.2026 | да (архив) | Дословно. |
| city-b7 | Разрешение на property line cleanout; в right-of-way копает только город | А. 10.05.2026 | да (архив) | Дословно. |
| city-b8 | Разрешение только на PRV без платы | А. 11.06.2026, Fees | да (архив) | Дословно. |
| city-b9 | Полив: разрешение, backflow, тестер, датчик дождя и мороза; кто ставит и меняет | А. 11.06.2026; А. 12.05.2026 | да (архив) | Дословно. Слово "repairs" в цитате города; про себя мы так не пишем (правило backflow). |
| city-b10 | Под плитой: разрешение и "letter of excavation and backfill"; бланк не прочитан | А. 11.06.2026 | да (архив) | Дословно; бланк в списке Inspection Services есть. |
| city-b11 | О проверке труб при ремонте фундамента город молчит | А. 11.06.2026; А. 10.05.2026 | да (отсутствие) | В памятке только "Plans shall delineate the proposed repairs, including pier design and locations." Поиск в сети официального слова не дал. |
| city-b12 | Своего списка работ без разрешения нет; закон меняет только строительные пункты R105.2 | закон 4265 | да, с поправкой | Верно. Добавить: закон говорит "Unless deleted, amended, expanded, or otherwise changed herein, all provisions of such code shall be fully applicable and binding." Значит, сантехнические пункты R105.2 самого IRC 2024 действуют; их текст я не прочитал (codes.iccsafe.org 403). "Section R105.2.2; delete" в законе относится к энергокодексу, не к IRC. |
| city-b13 | Штат: без разрешения течи, смесители, ballcocks, измельчитель, унитаз | TSBPE, живой | да, с поправкой | Дословно. Точнее: закон велит городу требовать разрешение на всё, кроме этих работ. Общее правило города (b1) называет и "repaired". Фразу "в Кэрролтоне на это разрешение не нужно" не писать. |
| city-b14 | Срочный ремонт: заявка в следующий рабочий день | А. 12.05.2026 | да (архив) | Дословно. |
| city-b15 | Платы города | А. 11.06.2026 | да (архив) | Дословно. Суммы города, на страницу не ставить. |
| city-b16 | Три памятки, копий нет | индекс архива | да | Сам запросил индекс по номерам 33192, 38321, 33190: пусто. |
| city-c1 | Инспекции через CityServe | портал, живой; А. 12.05.2026; А. 14.08.2026 | да | Живая строка "Apply for permits and planning cases, schedule inspections, submit code complaints and more using the CityServe Portal." |
| city-c2 | Раз в день; до 7:00 в тот же рабочий день | А. 14.08.2026 | да (архив) | Дословно. |
| city-c3 | Часы инспекций, в пятницу после обеда нет | А. 14.08.2026 | да (архив) | В оригинале между часами тире. |
| city-c4 | Ночью дежурный инспектор через Police Dispatch | А. 14.08.2026 | да (архив) | Дословно. |
| city-d1 | Хозяину принадлежит часть линии от счётчика к дому; городские линии без свинца | А. 16.03.2026 | да (архив), вывод | Прямой фразы о границе нет; вывод из "the portion of the service line you own" и "your service line on the side closest to your home". |
| city-d2 | Известных свинцовых линий нет | А. 06.06.2026, отчёт 2024 | да (архив) | В тексте PDF разрыв "C arrollton". |
| city-d3 | Прорыв трубы на участке за хозяином; город может закрыть счётчик | А. 14.08.2026 | да (архив) | Дословно. |
| city-d4 | Город: магистрали; хозяин: линии от магистрали, засоры, корни | А. 10.05.2026 | да (архив) | Дословно. |
| city-d5 | Дефект в right-of-way город чинит бесплатно по видео от сантехника | А. 10.05.2026 | да (архив) | Дословно. |
| city-d6 | Главы свода о воде и канализации не прочитаны | ecode360 | да | 403. |
| city-e1 | Пересчёт: бланк, описание, оплата, копия разрешения, 90 дней | А. 12.04.2026 | да (архив) | Дословно. |
| city-e2 | 1 в 12 месяцев или 2 в 5 лет; 60, 50, 40 процентов; бассейн нет; 6 периодов | А. 12.04.2026 | да (архив) | 40 процентов для течи "on an irrigation line". |
| city-e3 | Нет разрешения за 30 дней: отказ | А. 12.04.2026 | да (архив) | Дословно. |
| city-e4 | Краска в бачок, флажок на счётчике, нужен сантехник | А. 14.05.2026 | да (архив) | Дословно. |
| city-f1 | Цифры жёсткости нет | отчёты поставщика 2024, 2025 (живые); FAQ поставщика (живой); отчёты города 2024 и 2022 (архив); Water Quality (А. 06.06.2026) | да (отсутствие) | Слова hardness нет нигде. Отчёт города за 2025 год: живой 403, в архиве нет. В сети цифры только у продавцов смягчителей, не официальные. |
| city-f2 | Покупная поверхностная вода, семь источников | А. отчёт 2024; А. 13.11.2024 | да (архив) | Дословно; в списке озёр запрещённые имена. |
| city-f3 | Отчёт поставщика 2025: Elm Fork и шесть озёр | отчёт поставщика 2025, живой | да | Дословно. |
| city-f4 | Оценка "superior" от TCEQ | А. отчёт 2024 | да (архив) | Плюс живой отчёт поставщика за 2025 год: у поставщика "Superior". Про сам город за 2025 год слов нет. |
| city-g1 | 2024 IPC и IRC, законы 4265 и 4290, с 09/01/25 | А. 14.06.2026; закон 4265 | да (архив) | Дословно; текста закона 4290 нет. |
| city-g2 | Список "местных поправок" | закон 4265, стр. 30, 34, 35, 82, глазами | **нет, в таком виде** | См. исправленную формулировку ниже. |
| city-h1 | Мороз: шланги, наружные краны накрыть, полив, краны в доме капают, шкафчики открыть | А. 14.08.2026 | да (архив) | Дословно. |
| city-h2 | Полив в мороз: предупреждения, штрафы до $2,000 в день, бесплатные датчики | А. 14.08.2026 | да, с поправкой | $2,000 в день стоит за "roadway or sidewalk ice hazard"; за полив в мороз город выписывает "warnings and/or notices of violation, as well as citations". |
| city-h3 | Главный кран у дома или в гараже; у наружного крана спереди | А. 14.08.2026; А. 14.05.2026 | да (архив) | Дословно. |
| city-h4 | Регистрация узлов и тестеров, проверка при запуске и каждый год | А. 12.05.2026 | да (архив) | Дословно. Только для заметок. |
| city-h5 | Цифр давления нет; жалобы принимает отдел качества воды | А. 11.06.2026 | да (отсутствие) | В прочитанных копиях "psi" о воде в доме нет. Нашлась заметка газеты 2014 года о том, что город поднял давление в нескольких районах: не официальный источник, не использовать. |
| city-h6 | Дымовой тест сети города; дефекты на участке чинит хозяин | А. 12.05.2026 | да (архив) | Дословно. |
| city-h7 | Средний дом около 316 галлонов в день | А. 17.04.2026 | да (архив) | Дословно. |

##### Исправленная формулировка city-g2

Закон 4265, раздел поправок к жилому кодексу IRC (копия PDF 20.08.2026), что на странице подчёркнуто или вписано городом:

- P2604.1.1 (подчёркнуто, новое): пластиковая канализация под землёй, "The piping shall be bedded in 4 inches of granular fill and then backfilled compacting the side fill in 6-inch layers on each side of the piping."
- P2603.5.1: "Building sewers shall be a minimum of 12 inches (304 mm) below grade." Строка стоит в поправке, не подчёркнута.
- P2603.3: город заменил только материал гильзы: "plastic" зачёркнуто, вписано "approved". Фразы про металлическую трубу и бетон и про движение трубы в гильзе это слова самого IRC, не поправка города.
- P3003.9.2: фиолетовый праймер требует сам IRC; город дописал "[Delete Exceptions]", то есть исключений, когда праймер можно не ставить, в Кэрролтоне нет.
- Чердак: "A pull-down stair with a minimum 300-lb (136-kg) capacity." Для домов это поправка M1305.1.2 к IRC (подчёркнуто), для прочих зданий 502.3 к IPC.
- Вент "not less than 6 inches (152 mm) above the roof" стоит только в поправке 903.1.1 к IPC, кодексу для зданий. Частные дома идут по IRC, а эту часть IRC закон 4265 не менял. Для страницы о домах эту цифру не брать.

#### Новое, что первый помощник пропустил или прочитал неверно

1. **Конденсат кондиционера (M1411.9, поправка к IRC, стр. 30 закона 4265).** Город зачеркнул "an approved place of disposal" и вписал: "Condensate from all cooling coils or evaporators shall be conveyed from the drain pan outlet to a sanitary sewer through a trap, by means of a direct or indirect drain." Местное правило под самый частый вызов (линия конденсата в сливе мойки): на странице города одна фраза и ссылка на страницу прочистки; история только из диктовки Дениса.
2. **Сброс T&P (P2804.6.1, стр. 35).** Пункт 2: "Discharge through an air gap", слова "located in the same room as the water heater" зачёркнуты. Пункт 5: зачёркнуто "the floor, to the pan serving the water heater or storage tank, to a waste receptor", вписано "an approved location or to the outdoors". Файл цитат первого помощника приводит пункт 2 с зачёркнутыми словами как действующий: исправить.
3. Мелкое, для заметок: сифон островной мойки (P3112.2, подчёркнуто), "a double-check assembly" добавлен к защите полива (P2902.5.3), потери воды в сети 10.5 процента за 2024 год (отчёт 2024, архив).

#### Вопросы Денису

1. Город требует, чтобы конденсат кондиционера шёл в канализацию через сифон (M1411.9). Поэтому в Кэрролтоне линию конденсата врезают в слив мойки? Были ли там такие засоры? Готовая живая строка, если он подтвердит.
2. Город убрал требование выводить сброс T&P в той же комнате и разрешил "an approved location or to the outdoors". Что на деле требует инспектор Кэрролтона при замене водонагревателя: сброс наружу? И слив поддона, если раньше его не было (вопрос 3 первого помощника)?

### 6.4. Перепроверка индексов и возраста домов (файл `6b-zip-and-age-verified.md`)

Заголовок файла: «6b, проверка. Почтовые индексы и возраст домов Carrollton: что подтвердилось». Два списка этого файла («Можно использовать в брифе» и «Нельзя использовать») стоят в 6.0, остальное здесь.

Проверено 3 октября 2026, вторым помощником, с нуля. Я не брал чужие выписки: сам заново скачал официальные файлы USPS и Census и сам заново сделал запросы к data.census.gov. Проверяемый раздел: docs/briefs/carrollton/6b-zip-and-age.md. Мои выписки лежат рядом, в папке work-6b-verify.

Главный итог: из 19 фактов подтверждены 16. Один факт (75007) верен, кроме одной цифры: 59,6% надо заменить на 59,5%. Два факта со статусом "не удалось открыть" так и остались не открытыми, из них ничего брать нельзя.

#### Как я проверял

- USPS: сам скачал Zip_Locale_Detail.xlsx (4 380 487 байт, на сервере дата 1 октября 2026; на странице PostalPro "ZIP Codes by Area and District codes" написано "October 01, 2026"). Строки Техаса выписаны в work-6b-verify/usps-zip-locale-rows.txt. Что значит буква P в поле "ZIP CLASS CODE", в самом файле не написано; это написано в официальном руководстве USPS "Address Information System Products Technical Guide" (апрель 2016, postalpro.usps.com/storages/2016-04/AIS_0.PDF, страница 18): "Blank = Non-Unique", "M = APO/FPO/DPO Military", "P = PO Box Zip", "U = Unique Zip".
- Земля: сам скачал файл связи ZCTA и городов 2020 года (tab20_zcta520_place20_natl.txt) и пересчитал доли. Выписка: work-6b-verify/tab20-zcta-place-carrollton.txt.
- Жилье 2020 года по индексам и округам: другим путем, чем первый помощник. Он клал центр квартала в контур индекса на карте TIGERweb. Я взял официальный файл "квартал к ZCTA" (tab20_zcta520_tabblock20_natl.txt, 1 057 697 144 байт, оставил только кварталы округов Collin, Dallas, Denton) и официальные числа жилья по кварталам из переписи 2020 года (DECENNIALPL2020.H1 на data.census.gov, все кварталы 42 участков переписи, где лежит город). Кварталы города взял сам из Block Assignment File (1 825 кварталов, список совпал с его списком). Итог совпал до единицы. Выписка: work-6b-verify/blocks-2020-recheck.txt.
- ACS 2020-2024: сам сделал заново 30 запросов к data.census.gov (таблицы B25035, B25034, B25037, B25127 для 75006, 75007, 75010, 75019 и трех городов, плюс 75075 и прошлый выпуск для Carrollton) и пересчитал доли. Медианы B25035 еще раз сверил со строками официального файла acsdt5y2024-b25035.dat, который скачал сам. Выписки: work-6b-verify/acs-datacensus-recheck.txt и acsdt5y2024-b25035-rows.txt.
- Census API без ключа: тот же ответ 302 на missing_key.html, на странице слова "A valid key must be included with each data API request." Описания таблиц (groups) API отдает без ключа, по ним я сверил названия строк.

#### Таблица проверки

| id | Что утверждается (коротко) | Источник | Подтверждено | Примечание |
|---|---|---|---|---|
| zip-a1 | У Carrollton три индекса с доставкой: 75006 (CARROLLTON, 2030 E Jackson Rd), 75007 и 75010 (ROSEMEADE, 3755 N Josey Ln, PHYSICAL CITY CARROLLTON) | USPS Zip_Locale_Detail.xlsx, файл от 1 октября 2026 | да | Строка слово в слово: "752, 75006, класс пустой, CARROLLTON, W23158, P, 2030 E JACKSON RD, CARROLLTON, TX, 75006". У 75007 и 75010 поле LOCALE TYPE равно S, PHYSICAL ZIP 75007. Пустой класс по руководству USPS значит "Non-Unique", то есть обычный индекс. Слово "station" это прочтение буквы S, в руководстве 2016 года расшифровки S нет; на странице это слово не нужно. "Жилые индексы" подтверждаются переписью (zip-a3) |
| zip-a2 | 75011 только абонентские ящики, записан за CARROLLTON и за ROSEMEADE, участка ZCTA нет | тот же файл USPS | да | Две строки с классом P. По руководству USPS: "P = PO Box Zip". В файле связи ZCTA и городов, в файле кварталов трех округов и в файле ACS B25035 индекса 75011 нет. В листах Unique и Other строк Carrollton TX нет |
| zip-a3 | Индексы 75006, 75007, 75010 дают 95,3% земли города (45,57%, 32,00%, 17,71%) и 99,96% жилья 2020 года (53 060 из 53 080: 20 125, 19 083, 13 852) | tab20_zcta520_place20_natl.txt; перепись 2020 по кварталам | да | Земля: 43 264 307 + 30 383 329 + 16 817 684 = 90 465 320 из 94 939 827 кв. м, это 95,29%. Жилье: мой пересчет другим методом дал те же 20 125, 19 083, 13 852, сумма 53 060, город 53 080 (совпадает с DECENNIALPL2020.H1 и DECENNIALDHC2020.H1 для Carrollton city) |
| zip-a4 | Жилье участков в черте города: 75006 100% (19 083 из 19 083), 75007 96,1% (20 125 из 20 938), 75010 99,3% (13 852 из 13 953); по земле 75006 задевает Farmers Branch 1,6%, Dallas 0,4%, Addison 0,2%; 75007 Dallas 1,2%, Hebron 0,1%; 75010 Hebron 2,6%, Lewisville 2,0% | DECENNIALDHC2020.H1 по ZCTA; файл связи 2020 | да | Итоги участков с data.census.gov: 19 083, 20 938, 13 953. Доли земли участков: Farmers Branch 1,59%, Dallas 0,36%, Addison 0,20%; Dallas 1,16%, Hebron 0,12%; Hebron 2,64%, Lewisville 2,01%. Мелочи, которые он не назвал: в 75007 еще 0,19% земли вне городов и крошка Lewisville, в 75010 крошка Plano (840 кв. м). Названия соседей только для автора, на страницу их нельзя |
| zip-a5 | 75019 (почта COPPELL) содержит 2,83% земли города и ноль жилья города; Coppell 79,5% этого участка. Еще семь чужих индексов: вместе 1,9% земли и 20 единиц жилья | файл связи 2020; перепись 2020 по кварталам | да | 2 685 503 кв. м = 2,829%; Coppell 79,52%. Семь индексов: 1 789 004 кв. м = 1,88%; жилье 19 в 75056 и 1 в 75234, в остальных ноль. Строка USPS 75019: COPPELL, 450 S DENTON TAP RD |
| zip-a6 | Суша города с 2020 года почти не изменилась: 94 939 827 против 94 827 763 кв. м (на 0,12% меньше) | TIGERweb tigerWMS_ACS2024 слой 28 и tigerWMS_Current слой 28 | да | Оба слоя называются "Incorporated Places", оба ответили AREALAND 94827763, AREAWATER 1996209. Разница 0,118%. Это сравнение площадей, а не формы границы |
| zip-a7 | Страница города о TABC, судя по поиску, перечисляет 75006, 75007, 75010, 75011, но не открылась | cityofcarrollton.com, tabc-information | нет | Я тоже получил 403 (один запрос curl и один WebFetch). Текст не прочитан, использовать нельзя |
| zip-a8 | Сервис USPS "Cities by ZIP Code" не открылся | tools.usps.com, cityByZip | нет | Не проверял повторно (страница о сбое, повторять запросы не стал). Какие названия городов почта принимает для индексов, не проверено |
| zip-a9 | Жилье 2020 года по округам: Denton 32 130 (60,5%), Dallas 20 454 (38,5%), Collin 496 (0,9%) | BlockAssign_ST48_TX.zip; перепись 2020 по кварталам | да | Мой пересчет: 48121 Denton 32 130, 48113 Dallas 20 454, 48085 Collin 496. Кварталов 1 026, 794 и 5 |
| age-release | Новейший выпуск ACS 5-year 2020-2024; B25035_001E за 2024 отвечает, за 2025 404; папка 2025 пустая; API без ключа 302 | api.census.gov; www2.census.gov | да | 2024 variables: 200, "Estimate!!Median year structure built". 2025 variables: 404, и сам набор /data/2025/acs/acs5.json тоже 404. Папка summary_file/2025/table-based-SF: data (2026-09-23) и documentation (2026-09-29) пустые. Цитата "A valid key must be included with each data API request." на месте. Его счет "108 клеток" я не повторял поштучно, но каждую цифру из фактов ниже проверил сам |
| age-75006 | 75006: медиана 1982 (±2), владельцы 1979 (±2), съемщики 1986 (±2), 19 640 единиц; до 1980 42,8%, 1980-1999 38,2%, 2000-2009 7,4%, 2010 и позже 11,5%; дома на одну семью до 1980 57,7% | data.census.gov ACSDT5Y2024 B25035, B25037, B25034, B25127 | да | Все цифры совпали. 57,7% это 6 096 из 10 570 домов (B25127, строки "1, detached or attached", только занятое жилье; сюда входят и таунхаусы) |
| age-75007 | 75007: медиана 1987 (±2), владельцы 1986 (±1), съемщики 1988 (±1), 21 696; до 1980 25,1%, 1980-1999 57,8%, 2000-2009 10,4%, 2010 и позже 6,7%; 1970-е и 1980-е вместе 59,6% | data.census.gov ACSDT5Y2024 B25035, B25037, B25034 | нет, одна цифра неверна | Все совпало, кроме последней цифры. 1980-е 8 283 и 1970-е 4 634, вместе 12 917 из 21 696, это 59,5%, а не 59,6% (он сложил уже округленные 38,2 и 21,4). Та же 59,6% стоит в разделе "Сверка с живой страницей" файла 6b |
| age-75010 | 75010: медиана 2005 (±1), владельцы 2005 (±2), съемщики 2004 (±1), 14 322; до 1980 3,1%, 1980-1999 32,4%, 2000-2009 29,2%, 2010 и позже 35,4% | data.census.gov ACSDT5Y2024 | да | Все совпало. Построено в 2000 году и позже 64,6% (тоже совпало с текстом раздела) |
| age-75019 | 75019: медиана 1995 (±1); до 1980 6,1%, 1980-1999 61,3%, 2000-2009 12,1%, 2010 и позже 20,5% | data.census.gov ACSDT5Y2024 B25035, B25034 | да | Совпало. Только для сведения: жилья Carrollton в этом индексе нет |
| age-carrollton | Carrollton city: медиана 1988 (±2), прошлый выпуск 1988 (±1), владельцы 1986 (±1), съемщики 1993 (±2), 54 365 единиц; до 1980 26,0%, 1980-1999 44,3%, 2000-2009 14,2%, 2010 и позже 15,6%; домов на одну семью 33 785, из них 32,2% до 1980 (10 864) | data.census.gov ACSDT5Y2024 и ACSDT5Y2023 B25035; B25037, B25034, B25127 | да | Все совпало, в том числе строка 1600000US4813024 в файле acsdt5y2024-b25035.dat: "1988, 2". 33 785 это дома на одну семью среди занятого жилья (51 995), а 54 365 это все жилье, вместе с пустующим; не путать при делении |
| age-frisco | Frisco city: медиана 2009 (±1), владельцы 2008 (±1); до 1980 1,5%, 1980-1999 16,9%, 2000-2009 34,8%, 2010 и позже 46,7% | data.census.gov ACSDT5Y2024 | да | Совпало. Только для автора, на страницу Carrollton не выносить |
| age-plano | Plano city: медиана 1993 (±2), владельцы 1991 (±1); до 1980 18,4%, 1980-1999 50,3%, 2000-2009 17,6%, 2010 и позже 13,7%; совпадает с брифом Плано | data.census.gov ACSDT5Y2024; docs/briefs/plano/6b-zip-and-age.md | да | Совпало, и в брифе Плано стоит та же строка (1993, ±2, владельцы 1991). Только для автора |
| age-d1 | Carrollton старше обоих: 1988 против 1993 и 2009 (на 21 и 5 лет); до 1980 26,0% против 18,4% и 1,5%; 75006 (1982) такой же старый, как самый старый индекс Плано 75075 (1982); 75010 (2005) ближе к Фриско | acsdt5y2024-b25035.dat; data.census.gov | да | 75075 в файле: "1982, 2". Остальные индексы с названием Plano моложе: 75023 1985, 75074 1994, 75093 1994, 75025 1996, 75024 2002, 75094 2005. Сравнение только для автора, на странице другие города не называются |
| age-live1 | На живой странице стоит "from the older streets near downtown to the newer sections up north"; по данным самый старый юг (75006), самый новый только дальний север (75010), середина (75007) в основном 1970-е и 1980-е; где downtown, не проверено; чугун переписью не проверить | fppplumbing.com/plumber-carrollton-tx/ | да | Сам открыл живую страницу (ответ 200): фраза стоит слово в слово, во вступлении. Там же "Carrollton has houses from very different decades" и "In some of the older sections the drain lines are cast iron". В каком индексе лежит downtown, я тоже не нашел по официальному источнику |

#### Адреса, которые я открывал 3 октября 2026

- https://postalpro.usps.com/mnt/glusterfs/2026-10/Zip_Locale_Detail.xlsx и https://postalpro.usps.com/ZIP_Locale_Detail
- https://postalpro.usps.com/storages/2016-04/AIS_0.PDF (страница 18, расшифровка "ZIP Classification Code")
- https://www2.census.gov/geo/docs/maps-data/data/rel2020/zcta520/tab20_zcta520_place20_natl.txt
- https://www2.census.gov/geo/docs/maps-data/data/rel2020/zcta520/tab20_zcta520_tabblock20_natl.txt
- https://www2.census.gov/geo/docs/maps-data/data/baf2020/BlockAssign_ST48_TX.zip
- https://data.census.gov/api/access/data/table?id=DECENNIALPL2020.H1&g=1400000US{участок}$1000000 (42 участка переписи) и id=DECENNIALPL2020.H1 и DECENNIALDHC2020.H1 для 160XX00US4813024, 860XX00US75006, 75007, 75010, 75019
- https://data.census.gov/api/access/data/table?id=ACSDT5Y2024.{B25035, B25034, B25037, B25127}&g={860XX00US75006, 75007, 75010, 75019, 160XX00US4813024, 4827684, 4858016}, плюс B25035 для 860XX00US75075 и ACSDT5Y2023.B25035 для 160XX00US4813024
- https://www2.census.gov/programs-surveys/acs/summary_file/2024/table-based-SF/data/5YRData/acsdt5y2024-b25035.dat
- https://www2.census.gov/programs-surveys/acs/summary_file/2025/table-based-SF/ (data и documentation пустые)
- https://api.census.gov/data/2024/acs/acs5?get=NAME,B25035_001E&for=zip%20code%20tabulation%20area:75006,75007,75010,75019 (302 на missing_key.html), https://api.census.gov/data/2024/acs/acs5/variables/B25035_001E.json (200), https://api.census.gov/data/2025/acs/acs5/variables/B25035_001E.json (404), https://api.census.gov/data/2024/acs/acs5/groups/B25034.json (и B25035, B25037, B25127)
- https://tigerweb.geo.census.gov/arcgis/rest/services/TIGERweb/tigerWMS_ACS2024/MapServer/28/query?where=GEOID%3D'4813024'&outFields=GEOID,NAME,AREALAND,AREAWATER&returnGeometry=false&f=json и то же для tigerWMS_Current
- https://www.cityofcarrollton.com/government/city-manager-s-office/city-secretary/tabc-information (403)
- https://fppplumbing.com/plumber-carrollton-tx/ (200)

## 7. Офис

Файла раздела для этой части не было: она написана при сборке по CLAUDE.md, по краулу живой страницы (`source/crawl/pages/plumber-carrollton-tx.json` и `source/crawl/html/plumber-carrollton-tx.html`, обход 30 сентября 2026; часть 1 проверила, что 3 октября код страницы тот же байт в байт) и по файлам нового сайта (`site/src/content/pages/plumber-carrollton-tx.md`, `site/src/layouts/ServicePage.astro`, `site/src/components/CallButtons.astro`, `Header.astro`, `Footer.astro`, `Callbar.astro`, `Body.astro`, `ReviewCards.astro`, `site/src/lib/site.ts`, `site/src/lib/schema.ts`, прочитаны 3 октября 2026 около 11:50). Карточки Google у Carrollton нет, проверять вживую было нечего.

### 7.1. Что говорит CLAUDE.md

- Офисы есть только во Frisco и в Plano. Страницы остальных восьми городов описывают обслуживание города из ближайшего офиса: "The other eight city pages describe service coverage of that city from the nearest office. Never invent a local office, address or phone for a city that has none."
- Офис Frisco: 12800 Westridge Blvd, Suite 116, Frisco, TX 75035, линия 469-998-8999. Офис Plano: 5700 Tennyson Pkwy, Suite 300, Plano, TX 75024, линия 980-899-7997.
- Телефоны стоят в шапке, в подвале, в кнопках звонка и в блоках офисов на страницах городов с офисом (Frisco и Plano). В абзацах и в ответах FAQ их нет (правило 10). Значит, на странице Carrollton оба номера только в шапке, меню, липкой панели звонка и подвале, своего номера у страницы нет.
- Схема: один бизнес на весь сайт (Plumber, `#organization`) с обоими офисами; страница города без офиса ссылается на организацию и называет город в `areaServed`.
- Одобренная строка про дежурство: "A licensed plumber is on duty 24/7". В каком городе сейчас дежурный сантехник, не показываем. Времени приезда в своих словах не обещаем.
- Про расстояние разрешена одна формулировка, и она описывает район, а не время приезда: "About a twenty minute drive from our Frisco or Plano office" (она написана для городов вне списка).
- Страница города не называет соседние города и не ссылается на страницы других городов (правило 7).

Чего в CLAUDE.md нет: какой из двух офисов обслуживает Carrollton. Не сказано и то, как называть офис на странице города без офиса: по имени города ("our Plano office", "our Frisco office") или без него. Первое упирается в правило 7. Оба вопроса стоят в части 10.

Что есть в проекте вместо ответа (это не слово Дениса):

- Живая страница в тексте офис не называет и других городов не называет (часть 1, раздел 6.4). Но в её схеме отдельный бизнес "FPP Plumbing - Plumber in Carrollton, TX" с адресом, точкой на карте и телефоном офиса Plano; у организации в схеме тоже только телефон Plano (часть 1, раздел 6.4; `1-live-page-tables.md`, часть D).
- На главном фото живой страницы на борту фургона телефон Plano ("980.899.7997").
- Текст главной (`source/home-text-v4.md`) называет Carrollton без офиса: "On the Denton County side, to the west, we send a plumber in Lewisville, a plumber in Carrollton, a plumber in The Colony and a plumber in Little Elm."
- Search Console: страница Plano за 3 месяца показывалась по 24 запросам с carrollton (461 показ, место 8.2) и стоит выше страницы Carrollton по 15 из них (424 показа): 162 показа в строках на месте 3 и выше, по правилу проекта это карточка офиса Plano в картах, и 262 в обычной выдаче, из них 232 по «plumber carrollton tx» (часть 2, раздел 6). Указан ли Carrollton в зоне обслуживания карточки офиса Plano, в прочитанных файлах проекта не записано.
- География (часть 6.2, Census): жильё Carrollton лежит в округах Denton (60.5%), Dallas (38.5%) и Collin (0.9%); индексы офисов FPP среди индексов города не встречаются. Это география, а не решение о том, откуда едет фургон.

### 7.2. Что показывает живая страница

- Адреса офиса в видимом тексте страницы нет. В подвале (общий шаблон старого сайта) стоят оба офиса: "Frisco Office" (ссылка на /plumber-frisco-tx/), 12800 Westridge Blvd, Suite 116, Frisco, TX 75035, 469-998-8999, и "Plano Office" (ссылка на /plumber-plano-tx/), 5700 Tennyson Pkwy, Suite 300, Plano, TX 75024, 980-899-7997 (сверено по сохранённому HTML).
- Карты нет: в коде страницы нет ни одной встроенной карты Google.
- Телефоны: оба номера ссылками `tel:` в шапке и в нижней панели, порядок 980-899-7997, потом 469-998-8999. Нижняя панель свёрстана тегом H2: "980-899-7997 469-998-8999" (шаблон старого сайта). В абзацах и в FAQ телефонов нет.
- Схема: узел LocalBusiness плюс Plumber `/plumber-carrollton-tx/#business` с адресом, точкой карты и телефоном офиса Plano, `priceRange` "$$", часами 00:00 до 23:59 все семь дней и `areaServed`: Carrollton, Addison, Farmers Branch, Lewisville, The Colony. Описание организации: "surrounding North Dallas communities" и "Texas Master Plumber License M-44816". Подробно: часть 1 (раздел 6.4) и `1-live-page-tables.md`, часть D.

### 7.3. Что новый сайт показывает на этой странице сегодня

Файл страницы: layout "city", city "Carrollton". Полей `office`, `call_office` и `office_map` в нём нет.

- Над H1 строка "A licensed plumber is on duty 24/7" (её получают все страницы городов и страница emergency).
- Под вступлением две кнопки звонка без цифр: "Call" и "Frisco office" (красная), "Call" и "Plano office" (с обводкой); рядом кнопка "Request Service". Одна кнопка со своим номером бывает только на странице офиса с полем `call_office`.
- Блока офиса и карты нет: шаблон ставит их только на странице, которая записана у офиса как его собственная (/plumber-frisco-tx/ и /plumber-plano-tx/).
- Шапка: оба номера (Frisco, потом Plano) и кнопка Call, которая открывает выбор офиса (без скрипта набирает Frisco). Панель Menu: оба офиса с адресами и номерами. На телефоне липкая панель звонка с обоими номерами. Подвал общий для всего сайта: оба офиса с адресами, номерами и ссылками на отзывы Google каждого офиса.
- Первый экран: главным фото встаёт первая картинка текста, то есть фото фургона со старого адреса с alt "Plumbing van outside a home in Carrollton, TX" (часть 4).
- Отзывы: в тексте стоит метка `<!-- reviews -->`, но в `reviews/site-reviews.json` (файл от 10:04) ключа этой страницы нет, значит блок отзывов не выводится. Поля `reviews_heading` ("What Carrollton Homeowners Say About FPP Plumbing") и `reviews_intro` ("Google reviews from local homeowners.") записаны в файле страницы, но шаблоны в `site/src` их не читают (поиск 3 октября 2026). Значит, H2 отзывов живой страницы на новой странице сейчас нет совсем.
- Схема: один бизнес (Plumber) с обоими офисами, как на всём сайте, и узел Service с именем "Plumber in Carrollton, TX", `serviceType` "Plumbing", поставщиком организацией и `areaServed` Carrollton. Отдельного бизнеса для города, чужих городов в `areaServed` и `priceRange` на этой странице новый сайт не делает: это уже исправлено самим шаблоном.
- Про офис старый текст ничего не говорит, спорить нечему. С правилами спорят другие фразы старого текста, которые на новом сайте стоят (часть 1, раздел 8).

### 7.4. Что из этого следует для новой страницы

- Блока офиса, карты, адреса и своего телефона у страницы Carrollton быть не должно. Кнопки остаются как есть, пока Денис не назовёт офис. Если он назовёт один офис, решить с ним, ставить ли на первый экран одну кнопку с номером этого офиса или оставить две.
- В тексте нужна одна честная фраза о том, откуда мы приезжаем в Carrollton, без минут и часов. Писать её можно только после ответа Дениса (какой офис и как его назвать на странице, где по правилу 7 другие города не называются).
- Фразу страницы Frisco про то, кто приедет ("the plumber at your door may be Nick, Christopher or Denys"), слово в слово не повторять: она стоит в блоке офиса Frisco.
- Заголовок и строку над отзывами решать вместе с выбором отзывов (часть 5): "Google reviews from local homeowners." верна для Tyler Sommers и Paula Thompson, но станет неправдой с отзывом Thumbtack или Yelp. И сделать так, чтобы заголовок блока отзывов вообще выводился (сейчас шаблон его не читает), потому что H2 "What Carrollton Homeowners Say About FPP Plumbing" держит запросы вместе с другими заголовками (часть 2, раздел 4).

## 8. Посты и гайды

Файл раздела: `docs/briefs/carrollton/8-links.md`, вставлен целиком. Заголовок файла: «8. Истории из Carrollton на сайте и ссылки для страницы Carrollton».

Рядом, в бриф не вставлены: `8-links-tables.md` (А: все 33 поста и гайда, есть ли в них Carrollton и чужой город; Б: посты и гайды, которые подходят странице по теме, с оговорками; В: занятые фразы со ссылкой "plumber near me" на главную; Г: восемь фото старой галереи с Carrollton в alt) и `8-links-gsc-other-pages.md` (все запросы со словом carrollton по страницам сайта за 3 и 16 месяцев и запросы самой страницы по темам услуг).

Оговорка сборки: раздел 5, пункт 3 этого файла (округ «Denton County side») проверен частью 6: город лежит в трёх округах, жильё Denton 60.5%, Dallas 38.5%, Collin 0.9%.

Собрано 3 октября 2026, утром. Только чтение: в проекте ничего не менялось, страница Carrollton не переписывалась.

### Откуда данные

- Живой сайт: `source/crawl/pages/*.json` (30 сентября 2026). Новый сайт: `site/src/content/pages/**/*.md` (3 октября около 10:40) и шаблоны в `site/src/` (шапка, подвал, главная, `design.json`, `redirects.csv`).
- Search Console: `source/gsc/performance-3m|16m/Pages.csv`, `page-query-3m.csv` (1 июля до 28 сентября 2026), `page-query-16m.csv` (31 мая 2025 до 28 сентября 2026), `inspection-2026-10-01.csv`.
- Ещё искал Carrollton в диктовках, Word файлах, `photos/*.csv`, `reviews/`, постах Google, `docs/pages-plan.md`, `seo/keyword-map.md`.
- Рядом лежат два приложения: **`8-links-tables.md`** (все 33 поста и гайда с цифрами, посты для ссылок с оговорками, занятые фразы "plumber near me", фото галереи) и **`8-links-gsc-other-pages.md`** (все запросы со словом carrollton по страницам сайта и запросы страницы Carrollton по темам услуг).

**Как читать цифры.** «Итог» это строка страницы в `Pages.csv`: клики / показы / место. «Сумма строк» это сумма строк страницы в `page-query`; Google прячет редкие запросы, поэтому она меньше итога. Место в сумме строк это среднее с весом по показам.

### 1. Посты и гайды, где работа была в Carrollton

**Таких нет ни одного.** Ни на живом сайте, ни на новом нет поста или гайда, где работа была в Carrollton или где Carrollton назван местом истории.

Проверены 17 постов и 16 гайдов (таблица А в `8-links-tables.md`). Слово Carrollton стоит в тексте только одного гайда (1.1), и это одна фраза, не история. Ни один пост и гайд не ссылается на страницу Carrollton. В диктовках Дениса Carrollton нет. В постах Google Carrollton только в списках городов (20 декабря 2024 и 20 августа 2026), истории оттуда нет.

#### 1.1. Единственный гайд, где назван Carrollton (заморожен)

- URL: `/plumbing-guide/how-to-shut-off-main-water-valve-texas/`
- Title: "How to Turn Off Water to Your House | Main Shut-Off Valve Guide TX"
- H1: "How to Turn Off Water to Your House: Main Water Shut-Off Valve Guide for North Texas"
- Режим: **ЗАМОРОЖЕН**, текст не трогать (CLAUDE.md, `docs/pages-plan.md` группа 1). Ссылаться можно.

| Период | Итог | Сумма строк |
|---|---|---|
| 3 месяца | 104 / 9,953 / 7.64 | 404 строки, 4 / 1,224 / 9.85 |
| 16 месяцев | 212 / 22,630 / 7.14 | 521 строка, 6 / 2,194 / 9.68 |

- Про Carrollton, в разделе "Step 2: Find Your Secondary Shutoff Valve Near the House", подзаголовок "Where Is the Water Shut-Off Valve in Plano and Older North Texas Homes?": "If you’re in an older part of Plano, Carrollton, or Richardson, this buried-box setup is what you’ve got, and after 20-30 years these valves seize up hard." Речь о коробке в земле у дома, где рядом стоят PRV и второй запорный кран; дальше: старые gate valves ломаются в руке, закисший кран силой не крутить.
- Это не случай с выезда: дома и работы в Carrollton в гайде нет. Запросов со словом carrollton у гайда нет ни за 3, ни за 16 месяцев.
- На страницу Carrollton гайд не ссылается (только на Frisco, Plano, McKinney, Prosper). В той же фразе Richardson, город не из списка: на страницу Carrollton эту фразу не переносить, только сам факт, и только если Денис подтвердит его для Carrollton (вопрос 4).

#### 1.2. Работы из Carrollton, которые уже стоят на сайте без поста

1. **Фото 42**, hero страницы slab leak: alt "Finished brazed copper joint on a slab leak repair under the foundation, Carrollton". Снято 2 сентября 2026, город по месту съёмки (`photos/captions-en.csv`, `city_final`). Слова Дениса: «Slab leak: перепаяли брейзингом лопнувшее текущее соединение». Других кадров slab leak из Carrollton в архиве нет; как нашли и чинили, нигде не записано.
2. **Фото 6** на главной и на странице emergency, блок «What is happening right now?», вкладка "No hot water": alt "New Bradford White gas water heater in a closet, Carrollton". Снято 28 сентября 2026, город по месту съёмки; слова Дениса: «Замененный газовый водонагреватель Bradford White». В первой колонке `photos/captions.csv` стоит Plano, но по правилу город берётся из `city_final`, там Carrollton.
3. **Два отзыва** за страницей (`reviews/ledger.md`, разбирает раздел 5): Tyler Sommers (июнь 2026, замена водонагревателя; ответ компании: "your water heater replacement taken care of in Carrollton") и Paula Thompson (январь 2026, прорвало прокладку в ванне).

Сама страница `/plumber-carrollton-tx/` для сравнения:

| Период | Итог | Сумма строк |
|---|---|---|
| 3 месяца | 2 / 2,631 / 21.32 | 98 строк, 2 / 2,450 / 21.24 |
| 16 месяцев | 2 / 45,336 / 52.52 | 189 строк, 2 / 43,821 / 52.78 |

Клики за 3 месяца: "plumber carrollton" (1 клик, 36 показов, место 25.19) и "plumber carrollton tx" (1, 9, 29.33). Статус "Submitted and indexed", последний обход 12 сентября 2026. В `docs/pages-plan.md` группа 3, номер 12, «Старый текст»; в очереди городов Carrollton седьмой после Plano. [Критик: в `docs/pages-plan.md` после Plano идут Little Elm, The Colony, Prosper, Lewisville, Celina, Carrollton, Allen, McKinney: Carrollton шестой после Plano, седьмой, если считать сам Plano.]

### 2. Что про Carrollton уже сказано на других страницах

Своего случая с цифрами про Carrollton нет нигде. Есть перечисления городов, четыре характеристики без записанного источника и фото.

#### 2.1. Страницы услуг на новом сайте

- **Water line repair** (`/water-lines/`), раздел "Tree Roots and the Water Line", после случая с деревом в McKinney: "Older lots like these are where a plumber in Plano or a plumber in Carrollton spends a lot of time, because the trees went in with the houses." Самое близкое к факту про Carrollton на страницах услуг. Абзацем выше "Rerouting costs more once and ends it." (reroute не предлагается, не переносить).
- Slab leak, leak detection и emergency называют Carrollton только в перечислении четырёх западных городов: "...on the Denton County side a plumber in Little Elm, a plumber in The Colony, a plumber in Carrollton or a plumber in Lewisville with a warm spot on the floor" (slab), "...with a bill that makes no sense" (leak detection), "West and south it is the same story..." (emergency).
- Expansion tank (`/water-heater-repair-frisco-mckinney/`): ссылка "Carrollton" в списке городов. Hose bib: Carrollton в списке городов без ссылки.

#### 2.2. Одобренные Word тексты, которых ещё нет на сайте

- Sewer line: "The older cast iron work leans toward the established streets a plumber in Carrollton or a plumber in Lewisville sees..."
- Faucet and shower valve: "Seized shut-offs and diverters that no longer divert are more the territory of a plumber in Carrollton or a plumber in Lewisville..."
- Drain cleaning: "...a plumber in Carrollton or a plumber in Lewisville gets cleared the same day and gets the camera afterward." (расходится с правилом Дениса про камеру и со словами про время).
- Hose bib: "...a plumber in Carrollton or a plumber in Lewisville does the same job the same way, anchored, sealed and tested under pressure."

Откуда слова про чугун и закисшие краны в Carrollton, в диктовках не записано: это вопрос к Денису, не факт.

#### 2.3. Главная и фото

- `source/home-text-v4.md`, «Where We Work»: "On the Denton County side, to the west, we send a plumber in Lewisville, a plumber in Carrollton, a plumber in The Colony and a plumber in Little Elm." В FAQ "What areas do you serve?" Carrollton в списке. Плюс фото 6 (1.2).
- Свободные кадры из Carrollton (`docs/briefs/_shared/cities-free-photos-2026-10-03.md`, город по месту съёмки): 27 (PRV в доме, июль 2026), 57 и 58 (слив с гофрой до и ровно после, сентябрь 2025), 144 до 148 (душевой клапан через плитку, открыли с этой стороны, потому что с другой наружная стена, июль 2024). Основа для историй, если Денис их расскажет (вопрос 2). Клипов из Carrollton нет.
- Галерея: восемь фото старого сайта с Carrollton в alt (таблица Г в `8-links-tables.md`). В архиве этих файлов нет, город не проверен.

#### 2.4. Сама страница Carrollton сегодня

Местные утверждения без записанного источника: "from the older streets near downtown to the newer sections up north"; "In some of the older sections the drain lines are cast iron"; "Some older houses here do not have a usable one [cleanout]... we pull a toilet and run equipment through the flange"; FAQ "A large share of our Carrollton schedule is rental property". Других городов и ссылок на города в тексте нет.

### 3. На что ссылаться странице Carrollton и с какими якорями

#### 3.1. Главная: одна ссылка

Правило 6: один раз, в последнем абзаце вступления, якорь ровно "plumber near me", фраза общая, не про услугу страницы и не как на других страницах. Сейчас ссылка в третьем абзаце раздела "Water Leak Detection in Carrollton": "If you searched for a [plumber near me](/) because the bill jumped and nothing looks wrong, this is the part most companies skip." Привязана к теме счёта, начало как у четырёх других городов. Нужна новая фраза; занятые начала в таблице В `8-links-tables.md`.

#### 3.2. Все 13 услуг

Список из `site/src/design/design.json`, якорь по образцу Frisco: имя услуги. Сейчас ссылки на 11 услуг из 13: **нет hose bib и нет expansion tank**. «Запросы» это запросы самой страницы Carrollton по теме услуги: показы / место за 16 месяцев, в скобках за 3 месяца.

| № | Услуга | URL | Якорь сейчас | Предлагаемый якорь | Запросы | Где встаёт |
|---|---|---|---|---|---|---|
| 1 | Emergency plumbing | `/emergency-plumbing-services/` | "emergency plumbing" | "emergency plumbing" | 5,471 / 53.7 (34 / 21.8) | «течёт прямо сейчас» |
| 2 | Slab leak repair | `/slab-leak-repair-frisco-plano-mckinney/` | "slab leak repair" | "slab leak repair" | 5,577 / 44.9 (1,049 / 16.7) | абзац про slab, фото 42 |
| 3 | Water leak detection | `/water-leak-detection-frisco-plano/` | "leak detection" (2) | "water leak detection" | 2,589 / 44.7 (1,044 / 22.1) | тест счётчика |
| 4 | Sewer line repair and camera inspection | `/drain-services/` | "main line service" | "sewer line repair and camera inspection" | 290 / 61.6 (нет) | чугун, корни |
| 5 | Drain cleaning | `/clogged-drain-cleaning-frisco-plano/` | "drain cleaning" | "drain cleaning" | 20 / 72.1 (1 / 69) | засоры, фото 57, 58 |
| 6 | Water heater repair and replacement | `/water-heaters/` | "water heater repair" | "water heater repair and replacement" | 1,558 / 60.3 (16 / 23.3) | фото 6 |
| 7 | Expansion tank replacement | `/water-heater-repair-frisco-mckinney/` | нет | "expansion tank replacement" | 22 / 62.6 (2 / 19.0) | рядом с водонагревателем |
| 8 | Faucet and shower valve repair | `/fixture-installation-repair/` | "shower valve repair" | "faucet and shower valve repair" | 3,457 / 50.8 (23 / 22.2) | фото 144 до 148 |
| 9 | Hose bib repair | `/hose-bib-repair-frisco-plano/` | нет | "hose bib repair" | нет строк | мороз |
| 10 | Garbage disposal repair | `/garbage-disposal-repair-frisco-plano/` | "garbage disposal repair" | "garbage disposal repair" | 263 / 62.0 (1 / 29) | список |
| 11 | Water line repair | `/water-lines/` | "water line repair" | "water line repair" | 4,206 / 58.4 (9 / 32.8) | счётчик, деревья |
| 12 | Toilet repair | `/toilet-repair-frisco-plano/` | "toilet repair" | "toilet repair" | 296 / 52.4 (1 / 28) | cleanout через фланец |
| 13 | PRV replacement | `/prv-replacement-frisco-plano/` | "PRV replacement" (2) | "PRV replacement" | 17 / 29.5 (запрос с запрещённым городом) | давление, фото 27 |

Пояснения:
- "main line service" не держит ни одного запроса (на странице нет запросов со словами "main line"), замена ничего не теряет. "water heater repair" и "shower valve repair" остаются частью новых якорей ("water heater repair carrollton" 541 показ за 16 месяцев, "shower repair carrollton tx" 77).
- **Slab.** Карта ключей (`seo/keyword-map.md`, строка 13) отдаёт "slab leak repair carrollton" странице slab leak, но Google ставит выше страницу Carrollton: за 3 месяца 280 показов, место 16.08 ("...carrollton tx" 231, место 12.9); у страницы slab leak за 16 месяцев 266 показов, место 79.98. Правило «что ранжируется, остаётся» и карта тут расходятся, решение за Денисом. Безопасно: короткий абзац про slab со ссылкой "slab leak repair", без разбора метода.
- По смесителям запрета в карте ключей для Carrollton нет; у страницы "faucet repair carrollton" 1,103 показа, место 56.47 за 16 месяцев. Короткий блок со ссылкой и историей душевого клапана (если Денис её даст) это держит.
- Запросы «услуга плюс Carrollton» идут и на страницы услуг (16 месяцев, все дальше 49-го места): slab leak 344 показа, garbage disposal 311, expansion tank 87; галерея 102 по "expansion tanks repair carrollton tx".
- **Страница Plano за 3 месяца получила 24 запроса со словом carrollton: 461 показ, место 8.23** ("emergency plumber carrollton" 98, место 1.32; "plumber carrollton tx" 232, место 13.22). Место 3 и выше без своего города это, по `seo/cannibalization-findings.md`, карточка офиса Plano в картах Google. На текст Carrollton не влияет, но объясняет, почему у страницы Carrollton по "emergency" за 3 месяца всего 34 показа.

#### 3.3. Посты и гайды: что подходит по теме

Своих историй нет: ниже гайды и посты без другого города в адресе, title и H1. Якорь описывает тему, не услугу; рядом не называть город работы из поста. Цифры и оговорки: таблица Б в `8-links-tables.md`.

| Важность | Страница | Предлагаемый якорь |
|---|---|---|
| А | `/plumbing-guide/how-to-shut-off-main-water-valve-texas/` (заморожен) | "where the main shut-off sits and how to close it" (сейчас "shut-off guide") |
| А | `/plumbing-guide/water-leak-yard-tips-2026/` | "checking the yard for a main water line leak" |
| Б | `/plumbing-guide/water-pressure-dropping-tips-2026/` | "the usual reasons house water pressure drops" |
| Б | `/plumbing-guide/angle-stop-valve-leaking-under-sink/` (заморожен) | "a sink stop valve that starts dripping once it is turned" |
| Б | `/blog/shower-system-replacement-3-handle-to-single-handle-valve/` (приносит клики) | "an old three handle shower valve swapped for a single handle" |
| В | `/blog/toilet-replacement-with-new-shutoff-valve-and-wax-ring/` | "a toilet set back down on a new wax ring" |
| В | `/plumbing-guide/how-long-do-water-heaters-last-guide/` | "how many years a tank heater usually gives" |
| В | `/plumbing-guide/automatic-water-shut-off-valve-install-north-texas/` (приносит клики) | "a valve that closes the water on its own" |

А ставить в любом случае, Б если на странице есть абзац на эту тему, В по желанию. Из этих страниц на страницу Carrollton ничего не переносить, кроме ссылки: внутри цены, tankless, "rerouted", случаи из других городов.

#### 3.4. На что страница Carrollton не ссылается

- На другие города (правило 7). Сейчас их в тексте нет, так и оставить.
- На посты и гайды с другим городом в адресе, title или H1 (таблица А в `8-links-tables.md`), включая `/plumbing-guide/why-is-my-water-bill-so-high-frisco-tx/` (тема счёта совпадает), `/plumbing-guide/slab-leak-repair-plano-tips-2026/` (ещё и спорит со страницей slab leak), `/top-emergency-plumber-calls-frisco/`.
- На гайды с ценами (`emergency-plumbing-repair-cost-guide-2026`, `water-heater-replacement-cost-2026`) и на `plumber-near-me-north-texas-guide-to-avoid-scams` (якорь "plumber near me" принадлежит главной).
- Шапка, меню и подвал ссылаются на все города на каждой странице: это навигация, правило 7 про текст.

#### 3.5. Внешняя ссылка на официальный источник

Нужна одна (по образцу Frisco). Сейчас её нет ни на живой, ни на новой странице. Адрес ищет раздел 6a.

### 4. Кто уже ссылается на `/plumber-carrollton-tx/` на новом сайте

В файлах страниц 6 ссылок из 6 файлов:

| Откуда | Якорь |
|---|---|
| `/emergency-plumbing-services/` | "plumber in Carrollton" |
| `/slab-leak-repair-frisco-plano-mckinney/` | "plumber in Carrollton" |
| `/water-leak-detection-frisco-plano/` | "plumber in Carrollton" |
| `/water-lines/` | "plumber in Carrollton" |
| `/water-heater-repair-frisco-mckinney/` | "Carrollton" (список городов) |
| `/contact/` | "Carrollton, TX" (список городов) |

Кроме файлов страниц (навигация и шаблоны):
- Главная, три ссылки по решению Дениса: "plumber in Carrollton" в «Where We Work», карта (aria-label "Plumber in Carrollton"), ряд городов под картой ("Carrollton"). На каждой странице: шапка (Areas), панель Menu (Cities), подвал (Areas), якорь "Carrollton".
- Четыре старых служебных адреса ведут сюда переадресацией 301 (`redirects.csv`, строки 17, 18, 109, 110): `.../paula-thompson-google-review/`, `.../screenshot-31/`, `.../photo_2025-05-15_20-41-51/`, `.../6-1/`. На живом сайте в тексте те же шесть страниц плюс главная.

**Чего не хватает** (правки других страниц, в их очередь):
- Восемь страниц услуг из 13 не ссылаются на Carrollton: `/drain-services/`, `/clogged-drain-cleaning-frisco-plano/`, `/water-heaters/`, `/fixture-installation-repair/`, `/hose-bib-repair-frisco-plano/` (Carrollton в списке без ссылки), `/garbage-disposal-repair-frisco-plano/`, `/toilet-repair-frisco-plano/`, `/prv-replacement-frisco-plano/`. Для четырёх готовая фраза с "plumber in Carrollton" уже есть в Word текстах (2.2).
- Ни один пост и гайд не ссылается на Carrollton. Это нормально, пока нет истории оттуда; исключение только замороженный гайд (1.1).
- Ни одна другая страница города на Carrollton не ссылается: так и должно быть.

### 5. Расхождения с правилами, найденные по дороге

Ничего не исправлено, это список для автора страницы и для очереди других страниц.

1. Страница Carrollton: ссылка на главную не во вступлении (3.1); нет hose bib и expansion tank; якорь "main line service"; время своими словами: FAQ "a morning call typically means hot water by evening" и последняя строка "we’ll handle it today"; "A large share of our Carrollton schedule is rental property" без источника, там же "keep the owner out of the middle of it" (в историях по правилу "the homeowner").
2. Замороженный гайд про главный кран называет Richardson и не ссылается на Carrollton, хотя называет его.
3. Slab leak, leak detection, главная и Word тексты ставят Carrollton на "Denton County side". Округ здесь не проверялся: это раздел 6a.
4. Water lines: "Rerouting costs more once and ends it." рядом с фразой про Carrollton. Word drain cleaning: "cleared the same day and gets the camera afterward".
5. Галерея: восемь фото с Carrollton в alt, город со старого сайта, не проверен.

### 6. Вопросы к Денису

1. Фото 42 (страница slab leak): перепаянное брейзингом соединение, снято в Carrollton 2 сентября 2026. Расскажите эту работу: как заметили, как нашли, шли тоннелем или вскрывали плиту? Можно ли поставить её историей на страницу Carrollton?
2. Есть ещё три работы из Carrollton с фото: душевой клапан через плитку (фото 144 до 148, июль 2024), слив под раковиной с гофрой до и после (57, 58, сентябрь 2025), PRV в доме (27, июль 2026). Что там было? Какие можно рассказать?
3. Водонагреватель Bradford White в клозете (фото 6, сентябрь 2026) и отзыв Tyler Sommers (замена водонагревателя в Carrollton, июнь 2026): одна работа или две? Было ли разрешение и инспекция города?
4. В текстах сайта про Carrollton сказано: в старых районах коробка с краном и PRV в земле, краны закисают; старый чугун в канализации; закисшие краны и дивертеры; старые участки с деревьями, корни в линии воды. Что из этого вы сами видите в Carrollton?
5. На странице написано, что большая часть вызовов в Carrollton это сдаваемые дома и что фото работ уходят со счётом. Это так? Оставить?
6. В галерее восемь фото подписаны Carrollton (cleanout для двойной мойки, кран на backflow preventer, замер давления и другие). Эти работы правда были в Carrollton?

## 9. Чем Carrollton отличается от Frisco и Plano

Только то, что подтверждено данными Search Console (та же выгрузка, что в части 2) или официальной страницей из части 6. У каждого пункта назван источник. Цифры Frisco и Plano взяты из тех же выгрузок Search Console, из файла `6b-zip-and-age-verified.md` (часть 6.4) и из брифа Plano (`docs/plano-brief-2026-10-03.md`, часть 6, факты прошли там перепроверку). Это знание для автора: на самой странице Carrollton соседние города не называются.

1. **Страница почти без кликов, и показывают её в основном по течам.** Carrollton за 3 месяца: 2 клика, 2,631 показ, место 21.32. Frisco: 42 клика, 44,080 показов, место 15.2. Plano: 98 кликов, 56,197 показов, место 6.77. За 16 месяцев: Carrollton 2 клика, Frisco 110, Plano 103. У Carrollton 83% показов с названием города за 3 месяца (1,821 из 2,188) идут по leak detection и slab leak (часть 2, раздел 1). Мой счёт при сборке по той же выгрузке (`source/gsc/page-query-3m.csv`, запросы со словом leak или slab, доля от показов с известным запросом): Carrollton 85.4% (2,093 из 2,450), Frisco 9.8% (3,874 из 39,503), Plano 9.8% (4,813 из 49,302). Для страниц Frisco и Plano течи это одна тема из многих, для Carrollton почти всё; поэтому решение про слова "Leak Detection, Slab Leak" в title (часть 10, вопрос 2) здесь весит больше, чем на страницах офисов. Источник: `source/gsc/performance-3m/Pages.csv`, `performance-16m/Pages.csv`, `page-query-3m.csv`.
2. **Нет офиса и карточки Google, и по запросам города её обходит страница Plano.** У страниц Frisco и Plano есть свои карточки Google (правило «карта» в части 2 касается только их), у Carrollton нет. Страница Plano за 3 месяца стоит выше страницы Carrollton по 15 запросам с carrollton (424 показа), в том числе в обычной выдаче по «plumber carrollton tx» (Plano 232 показа на месте 13.2, Carrollton 9 на месте 29.3, 1 клик), а по «emergency plumber carrollton» Plano на месте 1.3 (98 показов) против 18.3 у Carrollton. Значит, на этой странице название города и варианты «plumber in Carrollton», «Carrollton plumbers», «emergency plumber» с городом в тексте и в части H2 важнее, чем на страницах офисов. Источник: часть 2, разделы 1 и 6.
3. **Дома старше, и город делится на старый юг и новый север.** Медианный год постройки жилья: Carrollton 1988 (±2), Plano 1993 (±2), Frisco 2009 (±1). Жильё владельцев: 1986, 1991 и 2008. Построено до 1980 года: Carrollton 26.0%, Plano 18.4%, Frisco 1.5%; среди домов на одну семью 32.2%, 24.1% и 1.5%. Внутри города: юг (75006) медиана 1982, до 1980 года 42.8% жилья; середина (75007) медиана 1987, 1970-е и 1980-е вместе 59.5%; север (75010) медиана 2005. Истории про дома 1970-х и раньше здесь уместны, во Frisco нет; что в них ломается (чугун, медь, закисшие краны), говорит только Денис. Источник: U.S. Census Bureau, ACS 5-year 2020-2024, таблицы B25035, B25037, B25034, B25127 (часть 6, строки age-carrollton, age-75006, age-75007, age-75010, age-frisco, age-plano, age-d1 таблицы проверки 6.4).
4. **Вода покупная, а официальной цифры жёсткости нет.** Carrollton покупает очищенную поверхностную воду; у поставщика в отчёте за 2025 год источники Elm Fork of the Trinity River и шесть озёр; слова hardness нет ни в отчёте города за 2024 год, ни в отчётах поставщика за 2024 и 2025 годы (часть 6, city-f1, city-f2, city-f3, обе проверки согласны). У Plano другой поставщик (водный округ NTMWD, озёра Lavon и Bois d'Arc), и в отчёте Plano за 2025 год жёсткость до 200 ppm (бриф Plano, city-f1, city-f4). По Frisco данных о воде в этих файлах нет. Значит, слова о жёсткой воде на странице Carrollton возможны только со слов Дениса, без цифры. Имя поставщика и озёра Grapevine и Lewisville на страницу не ставить (часть 6.0).
5. **Свои правила города про ремонт под плитой и про PRV.** Carrollton: общее правило разрешения называет и "repaired", а отдельной строкой ремонт под плитой: разрешение и "letter of excavation and backfill" от сантехника (часть 6, city-b1 и city-b10, копия архива страницы "Plumbing Work" от 11 июня 2026); на одну замену PRV разрешение без платы, "there is no charge for that permit" (city-b8, копия страницы "Fees" от 11 июня 2026). Plano: памятка только про замену линий под плитой, с фото работ и письмом от Responsible Master Plumber с номером лицензии, а слов, что ремонт одной течи под плитой требует разрешения, на страницах Plano нет; за PRV Plano возвращает часть денег, если давление по карте города выше 80 psi (бриф Plano, city-b8, city-b9, city-h4). Писать на странице Carrollton, что город требует разрешение и письмо при ремонте под плитой, можно со ссылкой на страницу города, после сверки с живым сайтом. Суммы города на страницу не идут. [Критик, 3 октября 2026: разница только в словах самих городов. Оба города приняли IRC 2024 и не меняли сантехническую часть R105.2 (Carrollton: часть 6.3, city-b12; Plano: бриф Plano, поправка 1 проверки), а там вырезка и замена скрытой трубы считается новой работой с разрешением. Строки Carrollton про разрешение при ремонте под плитой и про бесплатное разрешение на PRV перепроверены по копиям Internet Archive страниц "Plumbing Work" и "Fees" от 11 июня 2026: слова на месте; живой сайт города 3 октября снова ответил 403.]

## 10. Вопросы к Денису и нужные фото

Только то, что знает он один. Собрано из вопросов разделов (части 1, 2, 3, 5, 6 и 8), без повторов.

### 10.1. Вопросы

1. **Офис.** Из какого офиса обслуживается Carrollton, Frisco или Plano? Можно ли на странице назвать офис по имени (без минут и часов) или писать без названия города? По правилу 7 страница города соседей не называет. Указан ли Carrollton в зоне обслуживания карточки Google офиса Plano? (Страница Plano стоит выше страницы Carrollton по «plumber carrollton tx»: 232 показа на месте 13.2 против 9 на месте 29.3 за 3 месяца.)
2. **Слова услуг в title.** "Leak Detection, Slab Leak" в title и H2 "Water Leak Detection in Carrollton" держат 83% нынешних показов с городом (1,821 из 2,188 за 3 месяца), но карта ключей отдаёт «slab leak repair carrollton» странице slab leak, а та по этим запросам не показывается. Оставить, заменить один к одному или отдать страницам услуг? "PRV Repair" в title не держит ни одного запроса: оставить или поставить слова, которые ищут с Carrollton (emergency plumber, faucet repair, water line repair)? Ставить ли одну фразу "emergency plumber in Carrollton" со ссылкой на страницу emergency, как на Frisco (запросы emergency, 24 hour и same day с городом: 5,471 показ до июля; слов «emergency plumber» на странице нет)?
3. **Самые частые вызовы и slab leaks.** Правда ли, что в Carrollton больше всего вызовов про течи (мокрый двор, высокий счёт, слышно воду), как пишет старая страница? Сколько slab leaks вы починили в Carrollton за всё время, часто ли это там? Если редко, по правилу это короткий абзац со ссылкой, не начало страницы.
4. **Старые и новые части города.** Что значат слова старой страницы "older streets near downtown" и "newer sections up north"? По Census самый старый юг (75006, медиана 1982), середина (75007) в основном дома 1970-х и 1980-х, новый только дальний север (75010, медиана 2005). Какие трубы вы находите и где (медь, PEX, чугун, полибутилен)? Что из этого вы сами видите в Carrollton: ящик с краном и PRV в земле, где краны закисают; чугунную канализацию; корни в линиях воды на старых участках; дома без рабочего cleanout, где главную линию чистят через снятый унитаз? В каких районах вы работали и какие можно назвать (у конкурентов списки до 104 районов, мы называем только места настоящих работ)?
5. **Истории с фото.** Расскажите работы, от которых есть фото: slab leak (фото 42, 2 сентября 2026: как заметили, как нашли, шли тоннелем или вскрывали плиту, брали ли разрешение и что писали в "letter of excavation and backfill"); душевой клапан через плитку (144 до 148, июль 2024); слив раковины с гофрой (57 и 58, сентябрь 2025); PRV в доме (27, июль 2026). Какие можно поставить историей на страницу Carrollton? Помните ли другие работы в Carrollton?
6. **Водонагреватель.** Фото 6 (Bradford White в клозете, сентябрь 2026) и отзыв Tyler Sommers (замена в Carrollton, июнь 2026): одна работа или две? Было ли разрешение и инспекция? Что инспектор Carrollton требует при замене: слив поддона, если его раньше не было; сброс T&P наружу (город убрал требование «в той же комнате» и разрешил "an approved location or to the outdoors")? Держите ли водонагреватели в запасе? Старый ответ FAQ "Standard units stay stocked, so a morning call typically means hot water by evening" это обещание времени нашими словами, оно уходит.
7. **Давление и вода.** Где обычно стоит PRV в домах Carrollton (ящик в земле, гараж, стена) и какое давление вы видите на манометре? Берёте ли бесплатное разрешение города на замену PRV? Регулируете ли PRV, если он держит, или только меняете (старая страница пишет "we adjust it", в CLAUDE.md только замена)? Знаете ли по опыту, какая в Carrollton вода (накипь, картриджи)? Официальной цифры жёсткости нет.
8. **Правила города на ваших вызовах.** Город требует, чтобы конденсат кондиционера шёл в канализацию через сифон (поправка M1411.9): поэтому в Carrollton линию конденсата врезают в слив мойки, и были ли там такие засоры? Были ли вызовы, где после вашей камеры город сам чинил канализацию в своей полосе (right-of-way)? Меняли ли вы в Carrollton узел backflow на поливе с разрешением города, делали ли там дымовой тест?
9. **Сдаваемые дома и пересчёт счёта.** Большая ли доля вызовов в Carrollton это сдаваемые дома и управляющие компании, как пишет старый FAQ? Фото уходят с каждым счётом или по просьбе (в CLAUDE.md фото больших работ и по просьбе)? Ставить ли на страницу факт о пересчёте счёта за воду после течи (городу нужны описание течи, оплата ремонта и копия разрешения, в течение 90 дней)?
10. **Фото с неясным городом.** Где снят фургон с живой страницы (photo_2025-05-15_20-41-51) и что за номер "M-38532" на крыле (на сайте лицензия M-44816)? Убираем это фото? Можно ли пока ставить фургон у офиса Frisco (фото 2 или 4), как вы разрешили для Celina и Lewisville? Восемь фото галереи подписаны Carrollton (cleanout для двойной мойки, кран на backflow preventer, замер давления и другие): эти работы правда были в Carrollton?
11. **Отзывы.** Оставляем на Carrollton Tyler Sommers и Paula Thompson? Это единственные из 407 отзывов, где назван Carrollton; у обоих цифры времени в словах клиента, у Paula их три. Отзыв Paula подписан внутри "Larry R. & Paul T.", а имя профиля Paula Thompson: ставим как есть? Был ли кто-то из авторов без места (Javeed N., Kevin N., Alecia K., Michael V. и другие из десятки части 5) клиентом из Carrollton? Есть ли клиент из Carrollton с поиском течи, slab leak, PRV или линией во дворе, которого можно попросить оставить отзыв в Google с названием города? Отзывы со словами "plumber near me" для Carrollton по-прежнему не берём, как на Frisco?
12. **Индексы.** Нужны ли на странице почтовые индексы? Если да, по данным это три: 75006, 75007, 75010.

Закрыто раньше словом Дениса, не спрашивать снова: регистрация. 3 октября 2026 Денис сказал, что компания зарегистрирована как сантехнический подрядчик во всех городах, где работает; в CLAUDE.md то же. Раздел 6 описывает, что город требует от подрядчика, и FPP в списках города не искал.

### 10.2. Какие фото просить

Подробно в части 4.3. Коротко, по порядку важности:

1. Настоящее фото с работы в Carrollton или фургон FPP на улице в черте города (вертикальный кадр, без номеров домов).
2. Кадр проблемы из работы slab leak с фото 42 (яма или тоннель, течь, лопнувший стык до пайки), если есть.
3. Манометр с цифрой давления и место клапана из работы PRV с фото 27.
4. Водонагреватель в Carrollton «до» и «после»: поддон и слив, сброс T&P, кран на холодной воде, расширительный бак.
5. Ящик счётчика: крутится индикатор течи, кран города и кран хозяина.
6. Главная линия в старом доме: экран камеры, корни, чугун, cleanout или снятый унитаз.
7. Слив мойки с врезанной линией конденсата кондиционера в Carrollton, если была такая работа.
8. Узел backflow на поливе, заменённый с разрешением города в Carrollton, если была такая работа.
9. Клип около пяти секунд с любой работы в Carrollton.
