# Бриф страницы Celina (3 октября 2026)

Страница: /plumber-celina-tx/ . Собрано днём 3 октября 2026 из файлов разделов в папке `docs/briefs/celina/`. Страница не переписывалась: текст напишет другой чат из этого брифа и из диктовки Дениса. В проекте ничего не менялось, кроме этого нового файла.

Как устроен файл. Части 1, 2, 3, 5, 6 и 8 это файлы разделов, вставленные целиком скриптом, слово в слово (заголовки внутри опущены на уровень ниже, в части 6 на два уровня, потому что там четыре файла). Части «Коротко», 4, 7, 9 и 10 написаны при сборке. Читать стоит «Коротко», потом части 9 и 10, остальное открывать по делу.

Ответ Дениса от 3 октября, который касается и Celina (записан в `docs/morning-report-2026-10-03.md` в 10:25): компания зарегистрирована во всех городах, где работает; вопрос закрыт, в списках города больше не ищем. Поэтому всё, что во вставленных файлах сказано про отсутствие FPP в опубликованном списке сантехников Celina (строка city-a7, вопрос 1 файла фактов города, вторая половина вопроса 6 части 3), для страницы не используется и Денису не задаётся. На странице можно писать, что FPP зарегистрирована в Celina как подрядчик.

Оговорки к вставленным файлам:

- Слова «рядом» и «файл таблиц» во вставленных текстах значат папку `docs/briefs/celina/`. Длинные таблицы в бриф не вставлены: их имена названы в начале каждой части.
- Номера разделов внутри вставленных файлов («раздел 6.8», «пункт 7») относятся к самому файлу, не к частям брифа.
- Часть 6. Файлы фактов писались первыми, перепроверка шла после них. Где они расходятся, верить спискам 6.0 и таблицам проверки (6.3 и 6.4). Расхождения: city-b2, city-b11, city-c4 и city-h4 в файле фактов записаны неточно (исправленные слова города стоят в 6.3); главное из них city-h4: город всё же пишет про давление, "City Water Pressure: Varies; if more than 80 psi, a pressure reducing valve shall be installed" (пакет на полив). В файле индексов погрешность старого жилья около ±560, а не ±540, и доля жилья 2000 года и позже 82.3%, а не 82.4%; официальная карта индексов у города есть (2018), а форма почты USPS "Cities by ZIP Code" так и не открылась.
- Часть 1 записывает фразу "Celina is almost entirely new construction" в неподтверждённые. Данные Census из части 6 её поддерживают с оговоркой: около 4 из 5 единиц жилья построены с 2000 года, около 7% старше 1980 года.
- В общем файле фото `docs/briefs/_shared/photos-by-city-after-recount.json` у фото 52 и 121 город после пересчёта Celina, но подпись и план страниц там старые (Prosper). В `photos/captions-en.csv` уже стоят Celina и `/plumber-celina-tx/`. По CLAUDE.md подпись и имя файла берут город из `photos/captions-en.csv` (city_final); перенос 52 и 121 из Prosper в Celina вместе с планом страниц сделал пересчёт по границе города (`photos/city-changes.md`, tools/photo_city_apply.py), а не отдельное правило CLAUDE.md (уточнено при проверке брифа). Подробно в части 4.
- Файл нового сайта `site/src/content/pages/plumber-celina-tx.md` изменён в 10:24, после чтения в разделе 1 (10:10): title теперь "Plumber in Celina, TX | Water Heater Repair & Replacement | FPP", как и записано в разделе 1, пункт 8. Повтор ответа FAQ 2 в нём остался (проверено при сборке).
- Пересечения кандидатов в отзывы проверены разделом 5 только с Plano, Little Elm, The Colony и Lewisville (на 10:29). При проверке брифа (около 11:00) добавлены Prosper и Carrollton и предложенные четвёрки всех шести: дополнение в части 5, «Пересечения с другими городами». У Allen и McKinney файла отзывов ещё нет.
- Рабочие папки `work-6a` и `work-6b` лежат в `docs/briefs/celina/`. Скрипты Search Console и выписки проверок лежат во временной папке сессии (scratchpad/night/celina), не в проекте.
- Из вставленных файлов ничего не убрано и ничего в них не переписано. При проверке брифа (около 11:00) во вставленные части добавлены только пометки в квадратных скобках или с подписью «пометка проверки», «пояснение проверки», «дополнение проверки»: там, где перепроверка или новые файлы поправили вставленный текст. В части 6 списки «что можно брать», «только для справки» и «чего нельзя» из двух проверок переставлены в начало (6.0). Координат, адресов клиентов и телефонов клиентов во вставленных файлах нет (проверено поиском при сборке). Адрес мэрии и почтового отделения в части 6 это открытые адреса города и почты. Телефон в H1 конкурента в части 3 это телефон компании. Номера 980-899-7997 и 469-998-8999 это номера FPP.

## Проверка брифа (3 октября 2026, около 11:00)

Бриф прочитан целиком и сверен с заданием по десяти пунктам. Все десять есть и полные: 1 живая страница (title, описание, H1, все H2, семь вопросов FAQ, объём, три отзыва с текстом, датой, ссылкой и статусом на новом сайте, фото, ссылки с анкорами в части 1 и в `1-live-page-tables.md`, Т2 и Т3, нарушения дословно, районы с их предложением); 2 Search Console (3 и 16 месяцев; файлы `celina-gsc-table-3m.md`, `celina-gsc-table-16m.md`, `celina-gsc-headings.md`, `celina-gsc-extra.md` на месте); 3 десять страниц конкурентов (`source/competitors/2026-10-03-celina/00.txt` до `09.txt` на месте, число слов всей страницы совпало с таблицей); 4 фото; 5 десять кандидатов в отзывы; 6 официальные факты со ссылками и двумя проверками; 7 офис; 8 посты и гайды; 9 четыре отличия от Frisco и Plano; 10 вопросы и список кадров.

Сверено с источниками заново (всё совпало):

1. Запросы: «water heater repair celina» 65 показов, место 19.3 за 3 месяца; 487, место 23.5 за 16, из них 444 на старом адресе; «plumber celina» 130 и 389; «burst pipe repair celina texas» 53, место 3.7; итог 86 запросов и 1,705 показов за 3 месяца, 172 и 10,448 за 16 (`source/gsc/page-query-3m.csv`, `page-query-16m.csv`).
2. Итоги страниц: Celina 3,125 показов, место 16.12; старый адрес 632 и 19.36, за 16 месяцев 10,668, 22.47, 1 клик; Frisco 42 клика, 44,080, 15.2; Plano 98, 56,197, 6.77; за 16 месяцев Frisco 110 и 128,850, Plano 103 и 108,268 (`Pages.csv`).
3. Живая страница: title, описание, H1, девять H2, og:title, 1,355 слов, даты 16 мая 2025 и 17 августа 2026, четырнадцать цитат нарушений и местной сути (`source/crawl/pages/plumber-celina-tx.json`).
4. Отзывы: тексты и ссылки всех десяти кандидатов и трёх отзывов живой страницы слово в слово как в `reviews/all-reviews.csv`; 407 отзывов, 396 пятизвёздочных, Celina нет ни в одном.
5. Census, запрос повторён: B25035 Celina city 2015 (±2); B25034: 11,152 единицы, с 2010 года 65.6%, с 2000 года 82.3%, до 1980 года 833 (7.5%), с 2020 года 32.4% (data.census.gov, ACSDT5Y2024).
6. Census, пресс-релиз CB26-80 от 14 мая 2026 открыт заново: "1 Celina city Texas 24.6 64,427", "fastest-growing city in 2023".
7. Город, открыто заново: /1884 "to and through the water meter" и "any leak between the water meter and your home is the property owner's responsibility to repair"; /1920 "Cover outdoor faucets and exposed plumbing." и "Allow indoor faucets to drip during prolonged freezing temperatures."; /1985 "All contractors performing work within the City are required to complete registration before applying for permits."; /1342 "accessible only to authorized City personnel"; пакет на полив (Doc 12345) "City Water Pressure: Varies; if more than 80 psi, a pressure reducing valve shall be installed".
8. Фото: 52 и 121 в `photos/captions-en.csv` стоят с Celina и планом `/plumber-celina-tx/`, в общем файле старые подписи Prosper; 95 и 81 Frisco по границе, 165 Little Elm словом Дениса, 192 и 193 на странице Frisco, без города 37 файлов (22 фото, 15 клипов). Конкуренты: цитаты "call before ten in the morning", "typically arrive within hours", "at least 1 year", "only 7,000 people" есть в сохранённых текстах.

Что поправлено при проверке:

- Правило про фото по границе города было приписано CLAUDE.md; на деле перенос 52 и 121 из Prosper в Celina сделал пересчёт по границе (`photos/city-changes.md`). Исправлено в оговорках и в части 4.1.
- Пересечения отзывов были сверены только с четырьмя городами на 10:29; добавлены Prosper и Carrollton и предложенные четвёрки всех шести (часть 5 и «Коротко», пункт 12). Запасные Javeed N. и Dr. Jalal Jalali стоят в четвёрках Lewisville и Plano; свободная замена: Sathya P., Ryan E., Laura B.
- Часть 8: у «plumber celina» там только живой адрес (73), рядом поставлены цифры двух адресов; 1,419 показов водонагревателя включают "heating" и "pool heater" (не наши услуги), чистая цифра 1,338, как в части 2.
- Часть 6: в таблице 6.1 и в тексте 6.2 у строк, которые перепроверка поправила (city-a7, b2, b11, c4, h4; ±560 вместо ±540; 82.3% вместо 82.4%; карта индексов у города есть), стоят пометки прямо в строке; закрытые словом Дениса вопросы о регистрации помечены «не задавать» (часть 3, вопрос 6; часть 6.1, вопрос 1).
- Часть 8, раздел 3.5: добавлены три адреса официальной ссылки из 6a.

Проверено и чисто: длинных и коротких тире нет, координат нет, адресов и телефонов клиентов нет (адреса и телефоны в брифе только FPP, мэрии, почты и телефон компании конкурента в его H1), никто из предложенных авторов отзывов не стоит на новом сайте.

Что осталось открытым: уровни Local Guide и живая сверка отзывов на площадках (Yelp только со входа Дениса); у Allen и McKinney файлов отзывов ещё нет, пересечения с ними не проверены; 61% показов живого адреса Google скрывает; форма USPS "Cities by ZIP Code" и свод законов ecode360 не открыты; кто выдаёт разрешения в Light Farms (ETJ), неизвестно; город десяти фото галереи и фото 52 и 121, офис для Celina, "M-38532" на фургоне, диктовка Дениса и кадры с работ в Celina: всё это вопросы к Денису из части 10.

## Коротко

1. **Что кормит страницу.** Кликов по известным запросам нет ни за 3, ни за 16 месяцев. Итог Google по двум адресам страницы: за 3 месяца (1 июля до 28 сентября 2026) 0 кликов, 3,757 показов, место 16.67; за 16 месяцев 1 клик (на старом адресе, запрос скрыт) и 13,793 показа. Живой адрес /plumber-celina-tx/ есть в выгрузке только за последние 3 месяца (3,125 показов, место 16.12); почти вся история лежит на старом /plumber-the-celina-tx/ (с него 301, 10,668 показов за 16 месяцев). Источник: `source/gsc/performance-3m|16m/Pages.csv`, часть 2.
2. **По каким запросам.** За 3 месяца 86 известных запросов, 1,705 показов, место 19.1. Первые: «plumber near me» 152 показа на месте 15.5, «plumber celina» 130 на 24.5, «plumbing near me» 85, «water heater replacement near me» 84, «water heater repair near me» 78, «celina plumber» 69 на 32.6, «water heater repair celina» 65 на 19.3, «water heater replacement celina» 62 на 19.6. За 16 месяцев первые два: «water heater repair celina» 487 на 23.5 и «water heater replacement celina» 443 на 25.0. В первой десятке Google нет ни одного запроса с celina за 3 месяца; за 16 был один, «burst pipe repair celina texas» (53 показа, место 3.7).
3. **Половина показов не про город.** 55% известных показов за 3 месяца дают запросы без города (933 показа, место 13.7): это ключи главной и страниц услуг. После смены адреса показов по запросам с celina стало меньше: около 386 в месяц до июля, около 256 после.
4. **Что нельзя потерять.** "Plumber in Celina, TX" в начале title и H1 (держит семейство «plumber celina»); "Water Heater Repair & Replacement" в title (только эти слова держат запросы water heater с celina, 1,132 показа за 16 месяцев, но карта ключей отдаёт эту тему страницам водонагревателей: решает Денис); H2 "Our Plumbing Services in Celina" (только он держит «plumbing service celina», 47 показов за 3 месяца) и "Celina Plumbing FAQ"; слово plumbing в H2; "Licensed Celina plumbers" в описании; вопрос FAQ "How much does a plumber cost in Celina, TX?"; одно предложение с «plumber near me» и ссылкой на главную; фраза про emergency plumbing; "FPP Plumbing" в заголовке отзывов.
5. **Каких слов не хватает.** company (268 показов с celina за 16 месяцев), residential (140), install (110), contractor (72), burst (53), 24 (52), faucet (51). Пять H2 из восьми и шесть вопросов FAQ из семи не держат ни одного запроса с celina.
6. **Frisco стоит выше Celina по её же запросам.** «plumber celina»: страница Frisco 16 показов на месте 1.6, Celina 130 на 24.5. Оба клика сайта по запросам с celina ушли на Frisco и Plano. Похоже на карточки Google офисов, но выгрузка их не отделяет (часть 2, раздел 6).
7. **Что на живой странице против правил.** Ответ FAQ 2 это копия ответа 1, и повтор уже перенесён на новый сайт. В схеме второй бизнес "FPP Plumbing - Plumber in Celina, TX" с адресом и телефоном офиса Frisco, в areaServed Aubrey (не из десяти) и соседи Prosper, Frisco, McKinney, "North Dallas" без "suburbs", "Texas Master Plumber License M-44816", priceRange "$$". Близко к обещанию приезда: "most jobs are done the day you call", "getting to you is rarely the hard part", "we’ll show up", "same-day service" в описании, og:title "Clean, Fast Plumbing". H2 про шуруп за гипсокартоном это история Дениса про гвоздь со страницы Frisco и тема leak detection; целый H2 про slab leak стоит третьим разделом (правило: редкая для города беда одним абзацем со ссылкой, не в начале). Ещё "we photograph everything", риторические вопросы и тройки, нет ссылок на hose bib и expansion tank и ни одной официальной ссылки. Двенадцать утверждений страницы никто не подтвердил (часть 1, раздел 9). Новый шаблон сам убирает второй бизнес, Aubrey и priceRange; текст пока старый.
8. **Объём и местное.** Своего текста 1,192 слова, до отметки 2,500 не хватает около 1,300; H3 нет. Районы: Mustang Lakes, Sutton Fields, Glen Crossing по карте города внутри границ; Light Farms с почтовым адресом Celina, но по карте города вне полных границ (ETJ, около 3% площади под limited purpose annexation). Работал ли FPP в этих районах, по файлам не подтверждено.
9. **Конкуренты.** Десять страниц (порядок по Semrush по шести близким вариантам, сверка веб-поиском, 3 октября 2026). Основной текст от 275 до 1,212 слов, середина около 620: наша нынешняя страница (1,355 слов) уже длиннее всех. FAQ только у двух (Roto-Rooter 5 вопросов, Genzel 2). Цену вызова не называет никто, срок гарантии одна страница; купоны, tankless (7 из 10), бесплатные оценки и рассрочка есть у них и нельзя нам. Офис в самой Celina у двух местных компаний (CTX, Celina Plumbing Company); у нас его нет, и придумывать нельзя.
10. **Чего нет ни у одного конкурента.** PSI и манометр, счётчик и граница ответственности, разрешения и инспектор, ссылка на сайт города, материалы труб, способ ремонта под плитой, полив и backflow, бак на чердаке, мороз, сток кондиционера, источник воды, настоящие вызовы. Уже занято: глина, жёсткая вода словами, корни, «дома новые», три названия районов (у Genzel).
11. **Фото и клипы.** За Celina после пересчёта два фото и ни одного клипа: 52 и 121 от 24 февраля 2025 (уличный кран, лопнувший в мороз, и новый frost free в стене). Город только по границе, Денис его не называл; оба нигде не стоят. Фото 121 записано ещё и в пост про лопнувший уличный кран, где написано "A Plano homeowner". Фото 2 и 4 (фургон у офиса Frisco) Денис 1 октября разрешил ставить на Celina вместо фото с работы, с alt без слова Frisco. Кадра с работы в Celina или фургона в городе нет.
12. **Отзывы.** Celina не называет ни один из 407 отзывов архива. Свободных пятизвёздочных с текстом 330, по всем правилам проходят 146, работу называют 27. С живой страницы правила проходит только David Faidley; P M и J L называют Дениса по имени. Предложены четыре: alex p (горячая вода), Kevin N. (течь в доме), Rob C. (фильтрация в новом доме, Yelp), David Faidley. Проверка около 11:00 по файлам шести городов (часть 5, «Пересечения»): alex p и Kevin N. уже в предложенной четвёрке Little Elm, Kevin N. ещё и Lewisville; запасные Javeed N. и Dr. Jalal Jalali стоят в четвёрках Lewisville и Plano. Ни в одной чужой четвёрке нет Rob C., David Faidley, Sathya P., Ryan E., Laura B. Делить надо сразу.
13. **Официальные факты, подтверждённые двумя проходами (3 октября 2026).** Подрядчик регистрируется в городе до разрешения (FPP зарегистрирована, слово Дениса). Сантехника идёт с разрешением и инспекцией; у города своя "Water Heater Replacement Inspection", в ней расширительный бак "installed and braced"; поправка 604.8.3: при PRV, который делает систему закрытой, нужен бак. Город пишет, что давление разное и выше 80 psi ставится PRV. Город отвечает за воду до счётчика и через него, от счётчика до дома отвечает хозяин; кран у счётчика только для города, у дома нужен свой. Пересчёт счёта после течи раз в год, со счётом лицензированного мастера и фото ремонта; зимнее среднее задаёт плату за канализацию на год. Вода покупная поверхностная от UTRWD, официальной цифры жёсткости нет. Кодексы IPC и IRC 2024 действуют с 1 февраля 2026. Советы города на мороз совпадают с правилом Дениса.
14. **Индексы и возраст домов.** У почты Celina один индекс, 75009; черта города лежит в пяти индексах, ни один не целиком в Celina, и сам 75009 только на 26.7% в городе (граница 2020 года). Медианный год постройки жилья 2015 (±2); с 2010 года построено 65.6% жилья, с 2000 года 82.3%, до 1980 около 7.5% с большой погрешностью (ACS 2020-2024). Census, Vintage 2025: Celina самый быстрорастущий город США среди городов от 20,000 жителей, +24.6% за год до 1 июля 2025, 64,427 жителей. Если индекс на странице, то только 75009.
15. **Посты, гайды, ссылки.** Ни один пост и ни один гайд не рассказывает о работе в Celina и не получил ни одного показа по запросу с celina; Celina названа только общей подсказкой в замороженном гайде про главный кран. Страница ссылается на 11 услуг из 13 (нет hose bib и expansion tank); якоря "main line service" и "shower valve repair" можно поменять на имена услуг (по ним запросов нет); фразу со ссылкой на главную нужно написать заново; нужна одна официальная ссылка (кандидаты: регистрация подрядчиков, FAQ про счётчик, страница про мороз). На страницу Celina ссылаются шесть файлов сайта, восемь страниц услуг ещё нет.
16. **Офис.** Офиса в Celina нет, и CLAUDE.md не говорит, какой из двух офисов её обслуживает. В схеме живой страницы стоит офис Frisco, на фургоне главного фото телефон Plano. Новый сайт сегодня даёт на этой странице две кнопки звонка без цифр (Frisco office, Plano office), без блока офиса и без карты. Вопрос к Денису.
17. **Чего не хватает для сильной страницы.** Диктовки Дениса про Celina (в `source/dictation/` её нет); одной или двух настоящих работ из Celina с фото; его слова про фото 52 и 121, про Light Farms, про slab leak в новом доме, про title с водонагревателями и про офис; кадра с работы или фургона в Celina; выбора отзывов.

## 1. Живая страница

Файл раздела: `docs/briefs/celina/1-live-page.md`, вставлен целиком. Заголовок файла: «1. Живая страница Celina: что стоит на fppplumbing.com сейчас».

Полные таблицы в бриф не вставлены, они лежат рядом: `1-live-page-tables.md` (17 КБ): ответы FAQ слово в слово (Т1), ссылки со страницы (Т2) и на страницу (Т3), серия фото фургона на десяти городских страницах (Т4), проверка четырёх районов по карте города (Т5), схема (Т6).
Откуда данные: краул от 30 сентября 2026 (`source/crawl/pages/plumber-celina-tx.json`, `source/crawl/html/plumber-celina-tx.html`, остальные 63 в `source/crawl/pages/`). 3 октября в 10:12 по Техасу живая страница скачана ещё раз: код совпал с краулом байт в байт. Отзывы: `reviews/all-reviews.csv`, `site-ledger.md`, `site-reviews.json` (прочитаны в 10:09). Правки: `tools/build_launch_content.py`, `site/src/data/launch-changes.csv` (около 10:10; их меняют этой ночью). Длинные таблицы: `docs/briefs/celina/1-live-page-tables.md` (Т1 до Т6).

Страница https://fppplumbing.com/plumber-celina-tx/ : ответ 200, есть в page-sitemap.xml, canonical на себя, index и follow. Опубликована 16 мая 2025, последняя правка 17 августа 2026 (из схемы). Старый адрес `/plumber-the-celina-tx/` уже уводит сюда (301 в `site/public/_redirects`).

План (`docs/pages-plan.md`, группа 3, номер 11): 3,125 показов, место 16.1, 0 кликов за 1 июля до 28 сентября 2026, пометка «Старый текст». Карта ключей (`seo/keyword-map.md`): главный ключ "plumber celina tx", странице запрещены "water heater repair (water heater pages)" и "plumber near me".

### 1. Title, описание, H1, заголовки, объём

| Что | На живой странице |
|---|---|
| Title (63 знака) | "Plumber in Celina, TX \| Water Heater Repair & Replacement - FPP" |
| Meta description (134) | "No hot water? Rust in the tank? Damp spot on a wall in a nearly new house? Licensed Celina plumbers, same-day service, honest pricing." |
| H1 | "Plumber in Celina, TX - Water Heaters and the Problems New Houses Hide" |
| OG title (66) | "Plumber Celina, TX \| Clean, Fast Plumbing for New & Old Properties" (не совпадает с title; это старое название, оно же в хлебных крошках схемы и в меню главной) |
| OG картинка | фургон, `/wp-content/uploads/2025/05/photo_2025-05-15_20-41-50.jpg` |

В title и в H1 дефис с пробелами, не тире.

H2 по порядку (в скобках слова раздела вместе с заголовком, по тексту краула, значки «•» не считаны):

1. "Water Heater Repair and Replacement" (157)
2. "The Screw Behind the Drywall" (151)
3. "Yes, New Homes Get Slab Leaks" (123)
4. "Our Plumbing Services in Celina" (89, список из десяти строк)
5. "The Rest of the Week" (105)
6. "When It Cannot Wait" (83)
7. "Celina Plumbing FAQ" (349, из них 45 слов это повтор ответа, пункт 2)
8. "What Celina Homeowners Say About FPP Plumbing" (блок отзывов, 132 слова с подписями)
9. "980-899-7997 469-998-8999" (не раздел: нижняя панель звонка свёрстана тегом H2, шаблон всего старого сайта)

H3 нет ни одного.

Объём. Краул считает 1,355 слов (вместе с десятью значками «•»). Свой текст от H1 до конца FAQ: 1,192 слова, вступление 122 слова в двух абзацах. Отзывы 132 слова, последняя строка 20. До отметки 2,500 своему тексту не хватает около 1,300 слов.

Ключи, свой текст до отзывов: "Celina" 9 раз (на всей странице 11). "plumber in Celina" 2 раза: H1 и последняя строка "Need a plumber in Celina?". Во вступлении, в первом разделе и в H2 этой фразы нет; "Celina plumbers" только в описании. "plumber near me" 1 раз (ссылка на главную). "same-day" только в описании.

### 2. Семь вопросов FAQ

Вопросы НЕ тегом заголовка: `<span>` внутри `<summary>` списка Elementor, ответ `<p>`. На новом сайте вопрос жирный `<summary><strong>` (`FAQList.astro`). Ответы целиком: Т1.

| № | Вопрос, слово в слово | Шаблон или свой |
|---|---|---|
| 1 | "Should I repair my water heater or replace it?" | Свой для городов, но тема страницы водонагревателей; почти тот же вопрос в посте `/blog/plumber-frisco-water-heater-replacement/` |
| 2 | "My house is only a few years old. Why is water leaking behind a wall?" | Свой (у Prosper близкий: "My house is almost new. Why does it already need plumbing work?") |
| 3 | "Can a new home really get a slab leak?" | Свой |
| 4 | "How do you find a hidden leak without opening the whole wall?" | Свой, но это метод поиска, тема leak detection (правило 9) |
| 5 | "How much does a plumber cost in Celina, TX?" | ШАБЛОН: на всех девяти остальных городских страницах с другим городом; ответ McKinney почти слово в слово тот же |
| 6 | "Will you document what you find for a builder warranty claim?" | Свой, на сайте больше нигде |
| 7 | "Do you charge extra after hours?" | ШАБЛОН: ещё на Allen, Carrollton, Lewisville, Little Elm, McKinney, Prosper, The Colony; у McKinney ответ слово в слово |

Ошибка: на странице ответ на вопрос 2 это копия ответа 1 ("Depends on what failed and how old the tank is..."). В коде две разметки FAQPage: в первой тот же повтор, во второй настоящий ответ: "One common cause is a screw driven into a water line during shelving or trim work. It seals the hole at first, then corrodes over a couple of years and starts leaking. On newer homes it is one of the most frequent hidden leaks we find." На новом сайте повтор перенесён как есть (`site/src/content/pages/plumber-celina-tx.md`).

### 3. Три отзыва на живой странице

Подпись блока: "Real Google reviews from local homeowners." Три карточки, в каждой три ссылки на один адрес Google. Все три есть в `reviews/all-reviews.csv`: Google, 5 звёзд, `on_old_site` = `/plumber-celina-tx/`. Ни в одном отзыве и ни в одной подписи нет города.

#### 3.1. David Faidley

- Текст: "They arrived when they said, explained what was needed and why, did the work and cleanup. Reasonable price and professional service all the way. I’ll use them again."
- Подпись: "★★★★★ · Local Guide Level 6 · July 2026 · Google"
- Ссылка на странице: https://maps.app.goo.gl/oDf5DnoQX4pdWZUY6?g_st=ic
- Архив: профиль Plano, 2026-07-07, https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sCi9DQUlRQUNvZENodHljRjlvT2tGSWNuUnRkVXgyU0ZndFIwNUVhV0ZNY1RKVWNIYxAB!2m1!1s0x0:0xccc66184bdaf3a93
- Сверка: текст знак в знак, месяц совпадает. Работа не названа (ответ компании в архиве говорит "your water heater installation", это слова FPP). Говорит о компании, без имени Дениса.

#### 3.2. P M

- Текст: "Denis is honest and hardworking and I feel his work is reliable and I trust him to make the best decisions for my plumbing needs."
- Подпись: "★★★★★ · Local Guide Level 3 · May 2026 · Google"
- Ссылка на странице: https://maps.app.goo.gl/VfU7p2BQnc4uPFqr5?g_st=ic
- Архив: профиль Plano, 2026-05-30, https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sCi9DQUlRQUNvZENodHljRjlvT2tsRlNFUjFWbTFOTjNWb1JVWmZSRFpST1VObVVuYxAB!2m1!1s0x0:0xccc66184bdaf3a93
- Сверка: текст знак в знак (на странице перед ним лишний пробел), месяц совпадает. В архиве есть копия на Thumbtack: "P M.", 2026-05-29, пометка "copy of a Google review shown on Thumbtack, use the Google row": это тот же человек. Отзыв о Денисе по имени.

#### 3.3. J L

- Текст: "Denys did an excellent job replacing our ice maker water valve. He was professional, efficient, and made sure everything was working perfectly before he left. Highly recommend his service!"
- Подпись: "Local Guide Level 1 · March 2026 · Google" (звёзд нет, у двух других есть)
- Ссылка на странице: https://maps.app.goo.gl/Q3emgXbbotcXno9L8?g_st=ic
- Архив: профиль Frisco, 2026-03-03, https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sCi9DQUlRQUNvZENodHljRjlvT2xwelEyNVdVWEkyTkhjd1YzUmFXRXQ2V0VvMGFWRRAB!2m1!1s0x0:0xe28e4c9b59df630f
- Сверка: текст знак в знак, месяц совпадает. Работа названа (клапан ледогенератора). Отзыв о Денисе по имени.

#### 3.4. Общее

- На новом сайте ни один из трёх не стоит (нет в `site-ledger.md`, в `site-reviews.json`, на главной и в её резерве; копии "P M." тоже нет). Все три свободны.
- `reviews/proposed-placement.md`: «a rewritten city page keeps the reviewers it had on the old site». По этому правилу три отзыва остаются за Celina.
- По правилу городских страниц (город, услуга, plumber, имя компании; о компании, не о Денисе по имени) подходит только David Faidley, и то без города и услуги.
- Заголовок "What Celina Homeowners Say" и строка "from local homeowners" обещают жителей Celina, а по файлам ни один отзыв к Celina не привязан: два из профиля Plano, один из профиля Frisco.
- Уровни Local Guide (6, 3, 1) стоят только на старой странице; в архиве колонка пустая, проверить нельзя.
- На новом сайте на месте отзывов метка `<!-- reviews -->`, данных для Celina нет, строка "Real Google reviews from local homeowners." перенесена в `reviews_intro`.

### 4. Фото на живой странице

| Файл | Alt | Что это |
|---|---|---|
| `/wp-content/uploads/2024/12/fpp-logo-1-1024x563.png` (2 раза) | "FPP Plumbing Logo" | Логотип в шапке и в подвале |
| `/wp-content/uploads/2025/05/photo_2025-05-15_20-41-50.jpg` (1280 на 720) | "FPP Plumbing service van parked outside a home in Celina, TX" | Главное фото под H1, оно же OG картинка. Не фото работы |
| `/wp-content/uploads/2026/08/David-Faidley-verified-Google-reviewer.jpg` (289 на 283) | "David Faidley, verified Google reviewer of FPP Plumbing" | Аватар автора отзыва (вложение WordPress "screenshot-34"); файл не открывал |
| `/wp-content/plugins/elementor/assets/images/placeholder.png` (2 раза) | пустой | Заглушки вместо аватаров P M и J L |
| `https://seal-dallas.bbb.org/seals/blue-seal-200-65-bbb-91348602.png` | "FPP Plumbing, LLC BBB Business Review" | Знак BBB в подвале |

Фото с работ нет, видео нет. Главное фото (копию на новом сайте я открыл): белый фургон FPP сбоку у кирпичных домов с гаражами, на борту "EMERGENCY SERVICE 24/7", логотип, "980.899.7997"; на крыле "M-38532", как на фургоне Plano (в проекте не объяснён, не M-44816). Номерного знака не видно, метаданных в копии нет.

Город в alt ничем не подтверждён: у всех десяти городских страниц главное фото из одной серии файлов `photo_2025-05-15_20-41-45` до `-54`, имена отличаются секундами, и в alt у каждой свой город (Т4). Фото грузится лениво, хотя стоит на первом экране. Три страницы вложений под адресом Celina (screenshot-34, photo_2025-05-15_20-41-50, 5-2) на новом сайте уводятся 301 на страницу.

### 5. Ссылки

Со страницы в тексте 16 внутренних ссылок, внешних 0 (таблица Т2). Ссылка на главную стоит по правилу 6: анкор "plumber near me", последний абзац вступления.

- Из 13 услуг единого списка (`tools/export_design.py`, SERVICE_ORDER) в тексте 11. Нет hose bib (`/hose-bib-repair-frisco-plano/`) и expansion tank (`/water-heater-repair-frisco-mckinney/`).
- Внешней ссылки на официальный источник нет (городской странице нужна одна).
- Шаблон (меню три раза, кнопки, подвал, соцсети, `tel:`, ссылки на отзывы): Т2. Yelp, Thumbtack, Nextdoor нет.

На страницу с 63 других (предложения в Т3): "Celina" 189 раз в меню. В тексте "plumber in Celina" на четырёх страницах (slab leak, leak detection, emergency, water lines), везде в одном предложении с Prosper и другими городами. Голые списки: главная, contact, `/water-heater-repair-frisco-mckinney/`. Без ссылки Celina назван в замороженном гайде по перекрытию воды. Восемь сервисных страниц на Celina в тексте не ссылаются.

### 6. Что идёт против CLAUDE.md, дословно

#### 6.1. Другие города

В тексте ни одного (меню со всеми городами это шаблон, разрешено). В схеме: `areaServed` "Celina", "Prosper", "Frisco", "McKinney", "Aubrey" (Aubrey вне десяти городов, остальные это соседи на городской странице); описание организации "serving Frisco, Plano, McKinney, and surrounding North Dallas communities" ("North Dallas" не в форме "North Dallas suburbs"); описание WebSite "24/7 Emergency Plumbing in Frisco, Plano &amp; McKinney, TX.".

#### 6.2. Время приезда в своих словах

Минут и часов нет. Близко к обещанию:

- "When you call, our own team picks up and books you a window you can plan around. A licensed plumber arrives inside it with the parts already loaded, and the price is agreed before anything is opened."
- "Standard sizes ride on the truck, so most jobs are done the day you call, and when a permit and inspection are required we pull the permit and book the inspector ourselves."
- "We run Light Farms, Mustang Lakes, Sutton Fields, Glen Crossing, and the streets still going up around them, so getting to you is rarely the hard part."
- Последняя строка: "Need a plumber in Celina? Call or text us [en dash] we’ll show up, fix it, and leave it clean." (в оригинале короткое тире; "we show up" этой ночью сняли из описания Little Elm)
- Описание: "same-day service"; OG title: "Clean, Fast Plumbing".
- В отзыве: "They arrived when they said" (слова клиента, остаются).

#### 6.3. Цены

Только $49, и по правилу: "A $49 service call during the week, credited toward the repair if you go ahead. Anything beyond that is priced before work begins, and that number is what lands on the invoice." Доплата: "Evenings, weekends, and holidays carry an emergency fee tied to how late the call comes in. You hear the exact figure while we are still on the phone, before anyone is dispatched." (по правилу). В схеме `makesOffer` 49 USD и `priceRange` "$$".

#### 6.4. Tankless, reroute, hydro jetting

Нет ни в тексте, ни в схеме. (Запросы tankless на страницу приходят, см. файл 8.)

#### 6.5. Офис или адрес в Celina

В тексте офиса в Celina нет. В схеме второй бизнес: узел `["LocalBusiness", "Plumber"]`, `@id` `/plumber-celina-tx/#business`, имя "FPP Plumbing - Plumber in Celina, TX", с адресом, координатами и телефоном офиса Frisco. По правилу бизнес на весь сайт один, `#organization`.

#### 6.6. Телефоны, Owner, гарантия, FAQ заголовками

- Телефонов в абзацах и в ответах FAQ нет (они в шапке, в панели H2, в подвале).
- Слова Owner нет (только "homeowners").
- Сроков гарантии FPP нет. "warranty conversation" и "builder warranty claim" это гарантия застройщика: "And we photograph everything, because on a house this young that documentation is what you want if the repair turns into a warranty conversation."
- FAQ не заголовками (пункт 2).

#### 6.7. Заголовки и ключи

- H2 «услуга плюс город» нет. Но title "Water Heater Repair & Replacement" и H2 "Water Heater Repair and Replacement" берут ключ, который карта ключей отдаёт страницам водонагревателей; у `/water-heaters/` title "Water Heater Repair & Replacement in Plano & Frisco \| Same Day", то есть общая фраза в title. При этом страница Celina собирает эти запросы: "water heater repair celina" 487 показов, место 23.5, "water heater replacement celina" 443 показа, место 25.0 за 16 месяцев (`docs/briefs/celina/8-links-gsc-celina-queries.md`, раздел Б). Решать по правилу «что ранжируется, остаётся».
- "plumber in Celina" нет во вступлении, в первом разделе, в H2 (правило городских страниц).

#### 6.8. Границы с сервисными страницами (правило 9 и правила городов)

- Весь H2 "The Screw Behind the Drywall": та же история у Дениса своими словами стоит на странице Frisco (`source/frisco-text-v4.md`, H2 "The Nail in the Wall: The Leak Nobody Can Find") и отложена для leak detection (`source/dictation/2026-10-02-frisco-reserve-for-service-pages.md`). У Дениса тонкий гвоздь от полки, чаще PEX, год или два; на странице шуруп, "the metal corrodes", "Two or three years later".
- Целый H2 "Yes, New Homes Get Slab Leaks" третьим разделом. На Frisco редкий slab leak стоит коротким абзацем вторым в разделе про valve box; правило: редкая для города проблема это один абзац со ссылкой, не в начале.
- FAQ 1 (ремонт или замена) это тема страницы водонагревателей, FAQ 4 (как ищем) тема leak detection.

#### 6.9. Остальное

- Тире: короткое тире в последней строке; дефис с пробелами в title и H1.
- Риторические вопросы: три в описании, "Searched for a plumber near me and ended up here?", "Need a plumber in Celina?".
- Тройки и лозунги: "Both are normal, both are fixable, and both are what we drive out here for every week."; "these are parts, not projects"; "so you choose with facts instead of fear"; "and that is the entire point"; "you are holding evidence instead of a story"; "we’ll show up, fix it, and leave it clean".
- "And we photograph everything": в CLAUDE.md фотографируют большие работы, фото и видео по просьбе.
- "Celina is almost entirely new construction": обобщение; на портале ГИС города есть история-карта "Step Into History: 150 Years of Stories & Memories".
- Схема (Т6): два Organization с одним `@id`; "Texas Master Plumber License M-44816" (формулировка снята); legalName "FPP Plumbing, LLC"; в sameAs нет Google, Yelp, Thumbtack, Nextdoor; две FAQPage с разным ответом 2; крошки "Main" и старое название.
- Подвал (шаблон): "all rights reserved © 2024-2026 License M - 44816", не строка "Responsible Master Plumber, License M-44816".
- Нет блока Дениса, фото с работ, историй.

### 7. Улицы, районы, ориентиры

Названия мест стоят в одном предложении: "We run Light Farms, Mustang Lakes, Sutton Fields, Glen Crossing, and the streets still going up around them, so getting to you is rarely the hard part." Улиц, шоссе и ориентиров на странице нет (проверено по тексту).

Проверка по открытым данным ГИС города Celina (слои Celina Neighborhoods, Subdivisions, City Limits от 8 до 17 сентября 2026; адреса и метод в Т5):

| Название | Что показывает карта города | Вывод |
|---|---|---|
| Light Farms | Есть в слоях районов и застройки. В полных границах города 0%, около 3% площади под limited purpose annexation (постановление 23-34), остальное в ETJ. В Planned Developments нет. Почтовый адрес Celina 75009 (OpenStreetMap) | Настоящий район с адресом Celina, но по карте вне границ города. Спросить Дениса |
| Mustang Lakes | MUSTANG LAKES и MUSTANG LAKES EXPANSION, 100% в границах; есть в Planned Developments | Внутри Celina |
| Sutton Fields | SUTTON FIELDS и SUTTON FIELDS EAST, 100% в границах; часть города в Denton County | Внутри Celina |
| Glen Crossing | GLEN CROSSING и GLEN CROSSING WEST, 100% в границах | Внутри Celina |

Работает ли FPP в этих районах, по файлам не подтверждено.

### 8. Точечные правки на новом сайте

В `tools/build_launch_content.py` для `/plumber-celina-tx/` точечных правок (POINT_FIXES) нет: слово Celina стоит в файле только в списке TEN_CITIES (строка 46). В `site/src/data/launch-changes.csv` четыре изменения по общим правилам:

1. Последняя строка: "Call or text us [en dash] we’ll show up..." стало "Call or text us: we’ll show up, fix it, and leave it clean."
2. Title: "...Replacement - FPP" стало "...Replacement \| FPP".
3. H1: "Plumber in Celina, TX - Water Heaters..." стало "Plumber in Celina, TX: Water Heaters and the Problems New Houses Hide".
4. Виджет отзывов заменён меткой `<!-- reviews -->`.

Пометок без правки нет. Не исправлено (`site/src/content/pages/plumber-celina-tx.md`, 10:10): повтор ответа FAQ 2, "same-day service" в описании, "most jobs are done the day you call", "getting to you is rarely the hard part", "we photograph everything", alt фургона с Celina, нет ссылок на hose bib и expansion tank, нет официальной ссылки, нет отзывов для страницы.

### 9. Что стоит сохранить как местную суть

- Новые дома ломаются деталями: "Young plumbing does not mean trouble free plumbing, it means the failures come from parts rather than from age. Fill valves that give up in year three. Disposals chosen to meet a budget instead of a family. Shower cartridges that stick early. Drains that block because of what went down them rather than because of anything wrong with the pipe."
- Гарантия застройщика: вопрос FAQ 6 и ответ "We photograph the failure and write up plainly what we found and why..." (единственный такой на сайте).
- Признаки водонагревателя: "popping and rumbling from sediment, rust colored water in the first draw of the morning, a puddle ring at the base, or hot water that quits partway through the second shower."
- Разрешение и инспекция: "when a permit and inspection are required we pull the permit and book the inspector ourselves" (совпадает с CLAUDE.md).
- Кран перекрытия: "finding it on a calm evening is worth far more than finding it at midnight."
- Районы: Mustang Lakes, Sutton Fields, Glen Crossing по карте внутри города; Light Farms с оговоркой (пункт 7).

Факты, которые никто не подтвердил (в CLAUDE.md, диктовках и журналах их нет):

1. "Celina is almost entirely new construction".
2. "a water heater starts rumbling in year four"; "Fill valves that give up in year three."
3. "what we drive out here for every week".
4. "This is what Celina calls us about more than everything else combined."
5. "Standard sizes ride on the truck, so most jobs are done the day you call".
6. Шуруп за гипсокартоном в Celina, "Two or three years later", "explains a lot of the mystery leaks we find" (у Дениса гвоздь и Frisco).
7. Slab leak в почти новом доме в Celina: "We have repaired one right here in Celina where the ground shifted just enough to crack a line under a foundation that was still practically new." и FAQ 3.
8. "Most Celina visits open and close in one appointment".
9. "We run Light Farms, Mustang Lakes, Sutton Fields, Glen Crossing".
10. "And we photograph everything".
11. Ответ из схемы: "On newer homes it is one of the most frequent hidden leaks we find."
12. Что фото фургона снято в Celina.

### 10. Что не удалось проверить

- Уровни Local Guide трёх авторов (в архиве пусто).
- Город работ во всех трёх отзывах.
- Аватар David Faidley я не открывал.
- Что значит "M-38532" на фургоне.
- Кто выдаёт разрешение на работы в Light Farms, если он вне границ города: в файлах проекта этого нет.

## 2. Search Console

Файл раздела: `docs/briefs/celina/2-gsc.md`, вставлен целиком. Заголовок файла: «2. Search Console: страница Celina (/plumber-celina-tx/)».

Длинные таблицы в бриф не вставлены, они лежат рядом: `celina-gsc-table-3m.md` (14 КБ, все 86 запросов страницы за 3 месяца, по каждому адресу и вместе); `celina-gsc-table-16m.md` (26 КБ, все 172 запроса страницы за 16 месяцев, по каждому адресу и вместе); `celina-gsc-headings.md` (32 КБ, что держит каждый заголовок и вопрос FAQ живой страницы, по запросам); `celina-gsc-extra.md` (26 КБ, таблицы A до F: запросы без точной фразы, другие страницы выше Celina, услуги, главная, отложенные слова, слова запросов на странице). Запросы со словом celina по всем остальным страницам сайта стоят в части 8 (`8-links-gsc-celina-queries.md`).
Собрано 3 октября 2026, страница сейчас не переписывается. Источники: source/gsc/ (page-query-3m.csv и page-query-16m.csv от 30 сентября 2026, Pages.csv, page-query-coverage.csv, old-urls-with-impressions-16m.csv, inspection-2026-10-01.csv), seo/keyword-map.csv; живой текст из source/crawl/pages/plumber-celina-tx.json (обход 30 сентября 2026, правка страницы 17 августа 2026). В ячейках: показы · место · клики; где кликов нет совсем, показы · место.

Метод брифа Plano, его скрипты скопированы под Celina (`gsc_celina_lib.py`, `gsc_celina_live.py` в scratchpad/night/celina/gsc). Отличия: у страницы два адреса, живой `/plumber-celina-tx/` (в выгрузке только последние 3 месяца) и старый `/plumber-the-celina-tx/` (301, почти вся история); строки сложены по запросу, место средним по показам. Вопросы FAQ взяты из разметки FAQPage. Рядом: `celina-gsc-table-3m.md`, `celina-gsc-table-16m.md` (все запросы, каждый адрес и отдельно), `celina-gsc-headings.md`, `celina-gsc-extra.md` (таблицы A до F).

### Главное коротко

1. Кликов по известным запросам нет. Итог Google по двум адресам: 0 кликов, 3,757 показов за 3 месяца; 1 клик, 13,793 показа за 16 (клик на старом адресе до июля 2026, запрос скрыт).
2. Из 38 запросов с celina за 3 месяца в первой десятке ни одного. За 16 месяцев был один: «burst pipe repair celina texas» (53 показа, место 3.7).
3. После смены адреса запросов с celina стало меньше: около 386 показов в месяц до июля, около 256 после, место то же (26.2 и 25.7). Итог Google в месяц вырос (около 772 и 1,252), но на живом адресе запрос известен у 39% показов.
4. «Plumber in Celina, TX» в начале title и H1 держит семейство «plumber celina». Слова Water Heater Repair & Replacement в title одни держат запросы water heater с celina (1,132 показа за 16 месяцев), а карта ключей запрещает странице water heater repair. Решает Денис.
5. 55% показов за 3 месяца дают запросы без города, место 13.7. Офиса и карточки в Celina нет («карта» 4 показа). Эти запросы принадлежат главной и страницам услуг.
6. Главная почти не мешает (84 показа с celina за 16 месяцев, за 3 ни одного). Frisco выше по 9 запросам с celina, но это 58 показов, похоже, через карточку офиса; оба клика сайта по celina пришли на Frisco и Plano.
7. Точных фраз с городом на странице две, «plumber in celina» и «celina plumbing», плюс бренд «fpp plumbing». Нет слов company, residential, contractor, install, burst, 24, faucet.

### 1. Итоги за 3 и 16 месяцев

| Период | Запросов | Клики | Показы | Место | Итог Google со скрытыми, два адреса |
|---|---|---|---|---|---|
| 3 месяца (1 июля до 28 сентября 2026) | 86 | 0 | 1,705 | 19.1 | 0 кликов, 3,757 показов, место 16.67 |
| 16 месяцев (31 мая 2025 до 28 сентября 2026) | 172 | 0 | 10,448 | 22.3 | 1 клик, 13,793 показа, место 21.03 |

| Адрес | 3 мес: известные (запросов · показы · место) | 3 мес: Google | 16 мес: известные | 16 мес: Google | Доля известных показов |
|---|---|---|---|---|---|
| /plumber-celina-tx/ | 80 · 1,223 · 18.76 | 3,125 · 16.12 | то же | то же | 39% |
| /plumber-the-celina-tx/ (301) | 51 · 482 · 19.89 | 632 · 19.36 | 144 · 9,225 · 22.79 | 10,668 · 22.47, 1 клик | 76% и 86% |

На обоих адресах сразу 45 запросов за 3 месяца и 52 за 16. Старый `/plumber-celina-tex-water-heater-repair-replacement/` дал 1 показ (сейчас 404).

**Второй счёт.** Модуль csv, разбор строк без него в скрипте (по каждому адресу, с остановкой при расхождении), разбор строк с конца и awk дали одно: 3 месяца 131 строка (80 и 51), 86 запросов, 0 кликов, 1,705 показов, место 19.08; 16 месяцев 224 строки (80 и 144), 172 запроса, 10,448, место 22.32. По адресам совпадает с page-query-coverage.csv; пять запросов сверены руками.

| Группа | 3 мес: запросов · показы · место | 16 мес |
|---|---|---|
| celina | 38 · 768 · 25.7 | 79 · 5,780 · 26.2 |
| без города | 46 · 933 · 13.7 | 83 · 4,635 · 17.5 |
| другое место | 0 | 7 · 12 · 54.8 |
| бренд (fpp) | 2 · 4 · 5.8 | 3 · 21 · 13.9 |
| «карта»: без celina, место 3 или выше | 3 · 4 · 1.8 | 5 · 5 · 1.6 |

Запросы с celina по месту: за 3 месяца от 10 до 20 стоят 10 (225 показов), от 20 до 50 стоят 27 (542), ниже 50 один; за 16 месяцев от 3 до 10 один (53), от 10 до 20 стоят 24 (897), от 20 до 50 стоят 46 (4,595), ниже 50 стоят 8 (235). За 13 месяцев до июля (вычитанием): известные 8,743 показа, место 23.0, из них с celina 5,012 · 26.2; итог Google 10,036 показов, 1 клик.

Из 5,780 показов с celina за 16 месяцев 5,229 были на старом адресе: «plumbing celina tx» 348 из 349, «celina tx plumber» 344 из 346, «plumbers celina, tx» 131 из 131; на живом они почти не показываются. Title старого адреса неизвестен; на живой странице остался og:title "Plumber Celina, TX | Clean, Fast Plumbing for New & Old Properties" (по разделу 1 старое название) с точной фразой «plumber celina». Это догадка.

### 2. Первые 20 запросов каждого периода и запросы с кликом

Обе двадцатки одной таблицей, 25 запросов; первые 20 строк это двадцатка за 16 месяцев. Запросы без слова celina это группа «без города» (бренда и чужих мест в двадцатках нет). Двадцатки дают 1,202 показа из 1,705 и 6,069 из 10,448. Последняя колонка: раздел 5.

| Запрос | № 3 мес | № 16 мес | 3 мес | 16 мес | Из 16 мес на старом адресе | Фраза целиком |
|---|---|---|---|---|---|---|
| water heater repair celina | 7 | 1 | 65 · 19.3 | 487 · 23.5 | 444 | перестановка: title |
| water heater replacement celina | 8 | 2 | 62 · 19.6 | 443 · 25.0 | 404 | нет |
| plumber near me | 1 | 3 | 152 · 15.5 | 408 · 17.8 | 299 | точно: вступление |
| plumbing repair | 11 | 4 | 50 · 14.3 | 393 · 13.7 | 357 | нет |
| plumber celina | 2 | 5 | 130 · 24.5 | 389 · 21.5 | 316 | мягко: title, H1, текст |
| plumbers celina tx | 18 | 6 | 29 · 25.5 | 367 · 27.9 | 347 | мягко: title, H1, текст |
| plumbing celina tx |  | 7 | 2 · 28.0 | 349 · 27.5 | 348 | перестановка: H2 |
| celina tx plumber |  | 8 | 5 · 24.2 | 346 · 28.5 | 344 | перестановка: title, H1, текст |
| emergency plumber | 17 | 9 | 31 · 11.9 | 330 · 10.5 | 311 | нет |
| plumbing company | 19 | 10 | 29 · 18.8 | 310 · 16.3 | 292 | нет |
| emergency plumbing near me | 10 | 11 | 51 · 9.5 | 292 · 15.6 | 257 | мягко: текст |
| emergency plumbing | 13 | 12 | 45 · 10.8 | 288 · 11.4 | 258 | точно: текст |
| plumber | 14 | 13 | 45 · 10.4 | 258 · 13.6 | 215 | точно: title, H1, FAQ, текст |
| emergency plumbing services near me |  | 14 | 13 · 13.5 | 255 · 11.0 | 248 | нет |
| celina plumber | 6 | 15 | 69 · 32.6 | 231 · 21.1 | 187 | перестановка: title, H1, текст |
| plumbing services near me |  | 16 | 1 · 15.0 | 203 · 22.0 | 202 | мягко: H2 |
| plumbing near me | 3 | 17 | 85 · 17.2 | 191 · 17.9 | 127 | мягко: H2, текст |
| plumber celina tx | 16 | 18 | 34 · 24.2 | 190 · 24.0 | 170 | мягко: title, H1, текст |
| emergency plumber near me | 9 | 19 | 56 · 9.3 | 170 · 11.5 | 134 | нет |
| plumbing company near me |  | 20 | 25 · 16.7 | 169 · 19.6 | 153 | нет |
| water heater replacement near me | 4 |  | 84 · 13.3 | 134 · 14.6 | 72 | нет |
| water heater repair near me | 5 |  | 78 · 9.6 | 156 · 20.6 | 84 | мягко: title, H2, текст |
| plumbing service celina | 12 |  | 47 · 19.6 | 151 · 18.2 | 115 | мягко: H2 |
| plumbing company celina tx | 15 |  | 35 · 29.5 | 152 · 23.7 | 126 | нет |
| 24 hour plumbers near me | 20 |  | 25 · 15.1 | 76 · 26.0 | 60 | нет |

**Запросов с кликом нет** ни за 3, ни за 16 месяцев.

Слова в живом тексте (отзывы не в счёт), запросы с celina за 3 месяца: стоят полностью у 26 (607 показов из 768), частично у 10 (151), не наша услуга у 2 (10). Нет слов (показы с celina за 3 месяца, в скобках за 16): company 59 (268), residential 47 (140), contractor 34 (72), install 5 (110), maintenance 8, bathroom 6, kitchen 6; за 16 месяцев ещё burst 53, 24 52, faucet 51.

### 3. Главная по запросам с celina

За 3 месяца у главной нет ни одного запроса с celina. За 16 месяцев 12 запросов: 84 показа, место 46.7, кликов нет, все до июля 2026; все 12 есть у Celina (у неё по ним 2,060 показов). Главная выше по 6 (26 показов): «emergency plumber celina texas» 21 · 1.0 (Celina 64 · 11.4) и пять запросов по 1 показу. Больше всего показов у главной: «plumbing repair celina, tx» 28 · 66.3 (Celina 141 · 27.9). Только у главной ничего нет. Все строки: `celina-gsc-extra.md`, таблица D.

### 4. Что держат title, H1, H2 и вопросы FAQ

Заголовок «держит» запрос, когда в нём стоят все значимые слова запроса (in, tx, near, me не в счёт, множественное как единственное); «фраза целиком» здесь как в tools/gsc_page_table.py: подряд, без in и tx. Только запросы с celina, запросов · показы. Списки: `celina-gsc-headings.md`.

| Заголовок живой страницы | Все слова, 3 мес | 16 мес | Фраза целиком, 3 мес | 16 мес | Держит только он, 3 мес | 16 мес |
|---|---|---|---|---|---|---|
| title: "Plumber in Celina, TX \| Water Heater Repair & Replacement - FPP" | 8 · 396 | 15 · 2,989 | 4 · 195 | 6 · 1,134 | 2 · 127 | 5 · 1,132 |
| meta description | 6 · 269 | 9 · 1,760 | 2 · 74 | 2 · 577 | 0 | 1 · 49 |
| H1: "Plumber in Celina, TX - Water Heaters and the Problems New Houses Hide" | 6 · 269 | 10 · 1,857 | 4 · 195 | 6 · 1,134 | 0 | 0 |
| H2: "Our Plumbing Services in Celina" | 5 · 88 | 8 · 802 | 3 · 83 | 4 · 283 | 3 · 83 | 4 · 283 |
| H2: "Celina Plumbing FAQ" | 2 · 5 | 4 · 519 | 1 · 3 | 1 · 3 | 0 | 0 |
| H2: "What Celina Homeowners Say About FPP Plumbing" | 2 · 5 | 4 · 519 | 0 | 0 | 0 | 0 |
| FAQ: "How much does a plumber cost in Celina, TX?" | 6 · 269 | 8 · 1,711 | 0 | 0 | 0 | 0 |

Ничего не держат H2 "Water Heater Repair and Replacement", "The Screw Behind the Drywall", "Yes, New Homes Get Slab Leaks", "The Rest of the Week", "When It Cannot Wait" и шесть вопросов FAQ из семи. Без заголовка 25 запросов с celina за 3 месяца (284 показа) и 56 за 16 (1,989), больше всего plumbing company 152, plumbing repair 141, slab leak repair 112, drain cleaning 97, emergency plumber 64 (16 мес).

**Что нельзя потерять** (показы за 3 месяца, в скобках за 16):

1. "Plumber in Celina, TX" в начале title и H1: «plumber celina» 130 (389), «plumbers celina tx» 29 (367), «plumber celina tx» 34 (190), «plumbers celina, tx» (131), «plumber celina texas» (55); перестановкой «celina plumber» 69 (231), «celina tx plumber» 5 (346). Точная «plumber in celina» стоит в title, H1 и закрывающей строке.
2. "Water Heater Repair & Replacement" в title, только они: «water heater repair celina» 65 (487), «water heater replacement celina» 62 (443), «heater repair celina» (101), с texas (51 и 50); «water heaters celina, tx» (123) держат title и H1. Карта ключей тему не даёт: вопрос к Денису.
3. H2 "Our Plumbing Services in Celina", только он: «plumbing service celina» 47 (151), «plumbing services celina tx» 20 (47), «plumbing service celina tx» 16 (41), «plumbing service celina texas» (44).
4. Слово plumbing стоит только в трёх H2: «plumbing celina tx» 2 (349), «plumbing celina, tx» (110), «plumbing celina texas» (57). Точная «celina plumbing» 3 только в "Celina Plumbing FAQ".
5. "Licensed Celina plumbers" в description, только оно: «licensed plumber celina texas» (49).
6. Вопрос FAQ "How much does a plumber cost in Celina, TX?": единственный с городом (жирный текст на новом сайте).
7. "Searched for a plumber near me and ended up here?" со ссылкой на главную: «plumber near me» 152 (408). Карта ключей его странице не даёт: одно предложение со ссылкой (правило 6), не больше.
8. "Our emergency plumbing line reaches a person at any hour": «emergency plumbing» 45 (288); одно предложение со ссылкой на emergency.
9. "FPP Plumbing" в H2 отзывов и alt фото: «fpp plumbing» 2 (14).

### 5. Фраза целиком

Проверены 25 запросов раздела 2 (с кликом нет ни одного). «Точно»: слово в слово; «мягко»: без in и tx, множественное не в счёт; «перестановка»: те же слова рядом в другом порядке.

- Точно 3, все без города: «plumber near me», «emergency plumbing», «plumber».
- Только мягко 8: «plumber celina», «plumbers celina tx», «plumber celina tx», «plumbing service celina» и 4 без города.
- Только перестановка 4: «water heater repair celina» (title: "Celina, TX | Water Heater Repair"), «plumbing celina tx» (H2), «celina tx plumber», «celina plumber».
- Нигде 10; с celina два: «water heater replacement celina» (Repair & Replacement не подряд с water heater) и «plumbing company celina tx» (нет company).

По всем запросам с celina и бренду точная фраза стоит у трёх («plumber in celina», «celina plumbing», «fpp plumbing»: 7 показов за 3 месяца, 19 за 16). Нет у 36 запросов с celina (763; за 16 месяцев 77 и 5,775): мягко стоят 11 (350 и 1,992), перестановкой 7 (67 и 1,226), нигде 59 (346 и 2,557). Список: таблица A.

### 6. Запросы с celina, где другая страница стоит выше или забирает показы

На сайте за 3 месяца 39 запросов с celina, 893 показа, из них 768 у Celina; 2 клика, оба не у неё. За 16 месяцев 81 запрос, 6,080 показов, из них 5,781 у Celina. Другая страница выше Celina по 9 запросам за 3 месяца (у Celina по ним 366 показов) и по 16 за 16 (2,283). Все 23 строки и итоги по страницам: таблица B.

| Запрос | Другая страница | Она, 3 мес | Celina, 3 мес | Она, 16 мес | Celina, 16 мес |
|---|---|---|---|---|---|
| plumber celina | /plumber-frisco-tx/ | 16 · 1.6 · 0 | 130 · 24.5 · 0 | то же | 389 · 21.5 · 0 |
| plumber celina tx | /plumber-frisco-tx/; /plumber-plano-tx/ | 11 · 3.9 · 1; 1 · 1.0 · 1 | 34 · 24.2 · 0 | 12 · 3.7 · 1; 1 · 1.0 · 1 | 190 · 24.0 · 0 |
| water heater repair celina | /plumber-frisco-tx/ | 10 · 1.0 · 0 | 65 · 19.3 · 0 | то же | 487 · 23.5 · 0 |
| 24/7 plumbing repair near celina tx | /plumber-plano-tx/; /plumber-frisco-tx/ | 12 · 23.3; 6 · 1.8 | нет | то же | нет |
| emergency plumbing service near celina tx | /plumber-frisco-tx/ | 6 · 1.2 · 0 | 4 · 17.5 · 0 | то же | то же |
| emergency plumber celina texas | /; /plumber-frisco-tx/ |  |  | 21 · 1.0; 6 · 1.0 | 64 · 11.4 · 0 |
| slab leak repair celina, tx | /slab-leak-repair-frisco-plano-mckinney/ |  |  | 68 · 37.4 · 0 | 112 · 15.4 · 0 |

- Frisco выше почти по всем своим запросам с celina: от 1 до 16 показов на запрос, в основном на местах от 1.0 до 8.4. Карточки Google офисов Frisco и Plano ведут на свои страницы (CLAUDE.md, seo/cannibalization-findings.md); похоже на показы карточек, выгрузка их не отделяет.
- Больше показов, чем у Celina, у другой страницы только по «emergency plumbing service near celina tx».
- Slab leak: Celina выше, но 68 показов из 180 ушли странице услуги (до июля).

### 7. Запросы услуг с celina и их хозяин по карте ключей

У Celina в keyword-map.csv: главный ключ plumber celina tx; вторичные plumber celina, celina plumber; must not target: water heater repair (water heater pages); plumber near me. Ключей с celina у страниц услуг нет; хозяин назван по главному ключу страницы услуги (правило 5 CLAUDE.md). У /emergency-plumbing-services/ must not target: plumber + city, emergency с городом остаётся городу. Запросов · показы · место, кликов нет. Главная за 16 месяцев: общие 9 · 60 · 62.0, emergency 1 · 21 · 1.0, water heater 1 · 2, leak detection 1 · 1; за 3 месяца ничего. Подробно: таблица C.

| Услуга с celina | Хозяин | Celina, 3 мес | Celina, 16 мес | Страница услуги, 16 мес |
|---|---|---|---|---|
| общие (plumber celina и варианты) | Celina | 29 · 607 · 26.8 | 42 · 3,433 · 26.1 |  |
| water heater | /water-heaters/ | 4 · 135 · 20.1 | 11 · 1,338 · 28.4 | 3 · 4 · 73.8; repair-frisco-mckinney 1 · 6 · 66.5 |
| drain cleaning, clogs | /clogged-drain-cleaning-frisco-plano/ | нет | 4 · 180 · 28.7 | нет |
| pipe repair, burst pipe, leak repair | ключа нет; рядом /water-lines/ | нет | 3 · 148 · 11.8 | нет |
| emergency, 24 hour | Celina | 1 · 4 · 17.5 | 4 · 122 · 13.3 | нет |
| slab leak | /slab-leak-repair-frisco-plano-mckinney/ | нет | 1 · 112 · 15.4 | 1 · 68 · 37.4 |
| toilet | /toilet-repair-frisco-plano/ | нет | 2 · 96 · 20.8 | нет |
| sewer line, sewer cleaning | /drain-services/ | 1 · 6 · 24.0 | 3 · 79 · 16.4 | нет |
| leak detection | /water-leak-detection-frisco-plano/ | нет | 1 · 59 · 19.5 | нет |
| faucet | /fixture-installation-repair/ | нет | 1 · 51 · 15.7 | нет |
| garbage disposal | /garbage-disposal-repair-frisco-plano/ | нет | 2 · 9 · 23.2 | нет |
| bathroom and kitchen plumbing | ключа нет | 1 · 6 · 44.7 | то же | нет |
| tankless, heating (не наше) | страницы нет | 2 · 10 | 5 · 148 |  |

По всем услугам с celina Google ставит страницу города, страницы услуг почти не показываются (кроме slab leak). Самая большая группа это water heater, и её держит только title. Остальные услуги за последние 3 месяца почти пропали: их показы были на старом адресе. По правилам страница города называет каждую услугу один раз со ссылкой.

### 8. Запросы с другими местами

За 3 месяца нет. За 16 месяцев 7 запросов, 12 показов, место 54.8, все на старом адресе до июля. Остальных городов из десяти, Park Cities, Dallas и индексов в запросах нет.

- Little Elm, 4 запроса, 7 показов: «little elm slab leak repair» 3 · 71.7, «slab leak repair little elm tx» 1 · 80.0, «tankless water heater repair little elm tx» 2 · 87.5, то же без tx 1 · 70.0. В тексте страницы Little Elm не назван, название стоит только в меню сайта Service Areas (на каждой странице); слова tankless нет. Убирать из текста нечего.
- Pearland, 2 запроса, 3 показа: «plumber in pearland texas celina dietzel» 1 · 23.0 и то же слитно texascelina 2 · 5.0. Совпало слово celina, в запросе оно, похоже, часть имени человека.
- Venus: «plumber venus» 2 · 42.0 (у главной 5 · 39.2). Слова Venus на странице нет, причину назвать нельзя.

Районы с живой страницы (Light Farms, Mustang Lakes, Sutton Fields, Glen Crossing) ни в одном запросе не встречаются.

### 9. Слова, которые на страницу не ставятся

Запросов · показы за 3 месяца, в скобках за 16; кликов нет. По словам: таблица E.

- Не наши услуги: 4 · 30 (13 · 197): heating 80, tankless 70, boiler 37, new construction plumbing 5, hydro jetting 3, pool heater 2 (за 16 мес).
- Оценочные (trusted, expert, best, top-rated): 4 · 25 (то же). Имя FPP с ошибкой (pp, dpp, fp): 2 · 3 (4 · 8). Чужие компании (kipp, f & s plumbing, greens): 1 · 1 (3 · 3). Опечатки (olumber, texascelina, plumer, pumbler, wmergency): 2 · 2 (5 · 7).
- Скорость: «fast plumbing» 80 показов за 16 месяцев на месте 84.9 (старый адрес); правило о времени приезда.
- near me: 28 · 691 (42 · 2,643), ключ главной. Без города с emergency, 24 hour, same day: 10 · 242 (18 · 1,609), группы пересекаются; это главная и страница emergency, «same day plumber» (55, место 8.7) по правилу 5 формулировка главной.
- Длинные вопросы для FAQ не годятся: машинные «... near celina tx» (от 5 до 8 показов) и «plumbers that work on saturday near me» (1).

### Что из цифр следует для брифа

1. "Plumber in Celina, TX" в начале title и H1 сохранить. «Celina plumber», «plumbers in Celina», «plumbing in Celina» поставить в текст и в часть H2: пять H2 из восьми сейчас ничего не держат.
2. "Water Heater Repair & Replacement" в title (1,132 показа за 16 месяцев, против карты ключей): оставить, заменить один к одному или отдать страницам водонагревателей, решает Денис.
3. H2 "Our Plumbing Services in Celina" и "Celina Plumbing FAQ", вопрос о цене в Celina и список услуг со ссылками сохранить или заменить один к одному.
4. По одной простой фразе, с отчётом Денису (как на Frisco): plumbing company (268), residential (140), licensed plumber (49), registered plumbing contractor (72, факт из CLAUDE.md), «emergency plumber in Celina» со ссылкой на emergency и "A licensed plumber is on duty 24/7" (64 и 52); услуги одной строкой со ссылкой: slab leak repair (112, место 15.4), drain cleaning (180), toilet (96), sewer line (79), leak detection (59), faucet repair (51), burst pipe (53, место 3.7), water heater installation (install 110).
5. Предложение с «plumber near me» и ссылкой на главную оставить одно.
6. Не ставить слова раздела 9 и места раздела 8.
7. 301 с `/plumber-the-celina-tx/` (10,668 показов) оставить одной ступенью; в новой сборке правило есть (site/public/_redirects, строка 304, ночь 3 октября). Для `/plumber-celina-tex-water-heater-repair-replacement/` (1 показ) правила нет.

### Что проверить не удалось

- Запросы 61% показов живого адреса (1,902 из 3,125) и единственного клика: Google их скрывает.
- Когда сменился адрес и какой title был у старого: по дням выгрузка не делит. Старый адрес обойдён 27 июля 2026 с "Redirect error" (inspection-2026-10-01.csv; по docs/seo-baseline-live-2026-10-01.md 1 октября это одна чистая 301), живой 30 августа 2026.
- Карточка или обычная выдача у Frisco и Plano; причина показа по Venus. Сайт заново не открывался.
- В keyword-map.csv у Celina колонка Semrush пустая, а показы (3,125, 39%) посчитаны только по живому адресу, без 10,668 старого.

## 3. Конкуренты

Файл раздела: `docs/briefs/celina/3-competitors.md`, вставлен целиком. Заголовок файла: «3. Конкуренты по Celina: десять страниц из выдачи».

Рядом лежит и в бриф не вставлено приложение `3-competitors-details.md` (25 КБ): полная выдача Semrush (А), сверка веб-поиском (Б), все H2 десяти страниц дословно (В), местные слова (Г), открытые, но не взятые страницы (Д), небрежности конкурентов (Е), их приёмы, которые нам нельзя (Ж), полный список пропущенного (З), наши вопросы FAQ рядом с их вопросами (И). Тексты страниц: `source/competitors/2026-10-03-celina/` (`00.txt` до `09.txt`; `tools/check_overlap.py` сверяет черновик со всеми).
Дата: 3 октября 2026. Проект только читался. Новое: эта секция, приложение `3-competitors-details.md` рядом (полная выдача Semrush, сверка веб-поиском, все H2 дословно, местные слова, запасные страницы, небрежности конкурентов, что нам нельзя, полный список пропущенного) и папка `/Users/denyskavaler/Projects/fppplumbing-site/source/competitors/2026-10-03-celina/` (`00.txt` до `09.txt`).

### 1. Как выбраны десять страниц

Запросы задания: "plumber celina tx", "plumber in celina", "celina plumbing". Метод как по Plano: порядок по Semrush, веб-поиск как сверка.

1. Semrush, обычная выдача Google, база "us", первые 30 мест. Из трёх запросов задания в базе есть только "plumber celina tx"; по "plumber in celina" и "celina plumbing" Semrush отвечает "NOTHING FOUND" (проверено при этом прогоне). Поэтому порядок считан по шести вариантам с данными: "plumber celina tx", "plumber celina", "plumbing celina tx", "celina plumber", "plumbers celina tx", "celina tx plumber" (40 до 70 запросов в месяц; у "celina plumbing" 10, у "plumber in celina" в базе нет).
2. Веб-поиск (расширенный), три запроса задания дословно. Он не Google и к городу не привязан.

Нет живой выдачи Google с точкой в Celina и блока с картой; дата обновления базы Semrush в ответе не указана.

Порядок: среднее место по шести вариантам, "нет в первых 30" как 31, одна компания один раз.

| № | Файл | Компания | URL | Semrush, среднее | Веб-поиск (из 3) | Что за страница |
|---|---|---|---|---|---|---|
| 1 | 00.txt | CTX Plumbing & Electrical | https://www.ctxpc.com/ | 1,7 | 2 (+ Facebook) | главная, компания из Celina |
| 2 | 01.txt | Legacy Plumbing & Electric | https://legacyplumbing.net/service-area/celina/ | 3,7 | 2 | страница города |
| 3 | 02.txt | Milestone | https://callmilestone.com/celina/plumbing/ | 7,3 | 0 | страница города |
| 4 | 03.txt | Trident Plumbing | https://trident-plumbing.com/service-areas/celina/ | 8,3 | 0 | страница города |
| 5 | 04.txt | Roto-Rooter | https://www.rotorooter.com/celina/ | 8,8 | 3 | страница города |
| 6 | 05.txt | Celina Plumbing Company | https://www.celinaplumbingcompany.com/ | 9,3 | 1 | главная, компания из Celina |
| 7 | 06.txt | Genzel Plumbing Company | https://genzelplumbing.com/service-areas/plumbers-celina-tx/ | 10,8 | 0 | страница города |
| 8 | 07.txt | Tortuga Plumbing | https://tortugaplumbing.com/affordable-plumbing-services-in-celina-tx-quality-solutions-without-breaking-the-bank/ | 15,7 | 0 | статья блога |
| 9 | 08.txt | Advanced Plumbing Solutions | https://celinaplumbing.com/ | 17,0 | 0 | главная, компания из Celina |
| 10 | 09.txt | Specialty Plumbing | https://www.specialtyplumbingtx.com/ | 17,8 | 0 | главная, "Prosper and Celina" |

Пять страниц города, четыре главные небольших компаний (три из них компании из Celina), одна статья блога. Specialty взята по правилу, но слабая: title про Prosper.

Пропущено (полный список в приложении, раздел З): каталоги и соцсети (Yelp на 2 до 6 месте во всех шести, Angi, BBB, Facebook, Nextdoor, HomeAdvisor, каталоги подрядчиков Delta и Bradford White); сайт города celina-tx.gov (места 19 до 26: список зарегистрированных подрядчиков по сантехнике, не открывал); Celina, Ohio (Riesen, Roto-Rooter Celina OH); наш сайт; запасные Cathedral (19,2, веб-поиск 2 из 3), Still Waters (20,0, 2 из 3), Bewley, Mr. Rooter; North Texas Custom Plumbing (в веб-поиске 3 из 3, в Semrush только 25,8).

Наш сайт по Semrush: /plumber-celina-tx/ на 12 месте только в "plumber celina"; в четырёх вариантах на 28 до 30 стоит старый адрес /plumber-the-celina-tx/; в "plumber celina tx" нас нет в первых 30. Сверить с Search Console (раздел 2).

По запросам без "TX" веб-поиск подмешивает Celina, Ohio: "TX" или "Texas" рядом с Celina в title и H1 нужно обязательно.

Страницы скачаны одним запросом каждая предыдущим прогоном этой задачи (около 02:30 3 октября); я взял сохранённый HTML и заново не запрашивал. Все десять полные (title, текст, подвал), ошибок и защиты от роботов нет; код ответа тот прогон не записал.

### 2. Таблица по десяти страницам

"Основной текст": от H1 (или первого экрана) до подвала, без меню, форм и подвала, с отзывами и FAQ. "Вся страница": весь видимый текст (то, что в файле). Считано скриптом по сохранённым текстам.

#### 2.1. Размер, слово Celina, отзывы, FAQ, лицензия, офис

| № | Компания | Слов в основном тексте | Слов на всей странице | "Celina" основной / вся | Отзывов | FAQ | Лицензия на экране | Офис |
|---|---|---|---|---|---|---|---|---|
| 1 | CTX | 275 | 774 | 2 / 8 | 0 (заголовок есть, отзывов нет) | 0 | нет | Celina, Preston Rd |
| 2 | Legacy | 468 (без отзывов 334) | 1 493 | 12 / 14 | 3, не про Celina | 0 | M-37588 | Little Elm, Frisco |
| 3 | Milestone | 756 | 1 400 | 6 / 8 | 1 обрывок | 0 | M-13684 | 9 офисов, в Celina нет |
| 4 | Trident | 635 (без отзывов 520) | 2 503 | 7 / 13 | 2, не про Celina | 0 | m-42675 с именем | Frisco |
| 5 | Roto-Rooter | 934 (на экране 1 370: FAQ дважды) | 1 691 | 23 / 39 | 0, "Rated 4.8 on Google" | 5 | M-43414 с именем | адреса нет |
| 6 | Celina Plumbing Co | 390 | 429 | 3 / 5 | 0 | 0 | M-39482 | Celina, только в разметке |
| 7 | Genzel | 601 | 802 | 13 / 15 | 0 | 2 | RMP-23766 | McKinney |
| 8 | Tortuga | 1 212 (без отзывов 1 104) | 1 388 | 13 / 14 | 3, не про Celina | 0 | M44814 с именем | п/я в Pilot Point |
| 9 | Advanced | 1 004 (без отзывов 477) | 1 182 | 4 / 10 | 10 из Google, 2 со словом Celina | 0 | нет | адреса нет |
| 10 | Specialty | 533 | 764 | 4 / 6 | 0 | 0 | нет | Frisco, в разметке |

Наша нынешняя страница (снимок `source/crawl/pages/plumber-celina-tx.json`): 1 355 слов, Celina 11 раз, 7 вопросов FAQ.

#### 2.2. Title и H1 дословно

1. CTX. Title: "Celina Plumbing | Celina Electical | Celina Plumbers | Celina Electricians | CTX Plumbing & Electrical". H1: восемь тегов из слайдера ("PROFESSIONAL QUALITY", "PLUMBING & ELECTRICAL SERVICES", "(972) 900-9959", "CURRENT PROMOTIONS" и повторы), города нет.
2. Legacy. Title: "Plumbing Services in Celina, TX | Fast & Reliable Experts". H1: "Plumbing Services in Celina, TX".
3. Milestone. Title: "Celina, TX Plumbers - Your Local & Trusted Plumbing Experts!". H1: "Plumbers in Celina, TX".
4. Trident. Title: "Plumber in Celina, TX | Trident Plumbing". H1: "Plumbers in Celina, TX".
5. Roto-Rooter. Title: "Celina Plumbers Near You | Roto-Rooter". H1: "Celina's Go-To Plumbing Experts for Every Drain, Leak, and Emergency".
6. Celina Plumbing Company. Title: "Celina Plumbing Company | Your Local Plumbing Service Experts". H1 нет.
7. Genzel. Title: "Plumbers in Celina, TX | Genzel Plumbing Company". H1: "Plumbers in Celina, TX".
8. Tortuga. Title: "Affordable Plumbing Services in Celina, TX: Quality Solutions Without Breaking the Bank - Tortuga Plumbing". H1: та же фраза без " - Tortuga Plumbing".
9. Advanced. Title: "Advanced Plumbing Solutions, LLC". H1 нет; в первом экране крупный текст "Celina’s Trusted Plumber" и через тире "Fast, Honest Service".
10. Specialty. Title: "Plumbing Services in Prosper TX | Specialty Plumbing". H1: "Reliable Plumbing for Residential & Commercial Properties".

#### 2.3. Темы H2, местные факты, цены, гарантия, приезд

H2 дословно в приложении, раздел В; местные слова подробнее в разделе Г.

| № | Компания | Темы H2 | Местные факты, которые страница даёт | Цены | Гарантия | Приезд |
|---|---|---|---|---|---|---|
| 1 | CTX | почему мы, услуги, отзывы, телефон тегом H2 | офис в Celina (75009), часы | скидки новым: $25, $50, $100 по сумме работ | нет | нет; будни 7:30 до 5 |
| 2 | Legacy | абзац о Celina, "Recent Plumbing Jobs" (два названия работ), плитки услуг | "small-town America", "only 7,000 people" (их цифра, не проверял) | купоны в меню (10%, $115, $125, бесплатное второе мнение) | "Customer Service Guarantee", без срока | "We will show up on time" |
| 3 | Milestone | один H2, общий текст, признаки поломок | нет | нет | "Milestone Guarantee", без срока | "call before ten in the morning and we will get out the same day" |
| 4 | Trident | формы, 20 карточек услуг (три про Frisco), почему мы, отзывы | севернее Frisco и Prosper, округа Collin и Denton, вставлен абзац города о себе ("Living Life Connected"); насосы для колодца, озера, полива | нет | "Satisfaction Guaranteed", без срока | "24/7"; в отзыве "within 24 hours" |
| 5 | Roto-Rooter | почему мы, услуги, аварийный вызов, FAQ, округа | глина набухает и сохнет; корни live oak и pecan; жёсткая вода без цифры и источника; штормы; 11 округов; PHCC | купон "$55 Off", без доплаты за выходные, "free estimates" в мета, рассрочка | "clear warranties", без срока | "typically arrive within hours", "Same-day", 24/7/365 |
| 6 | Celina Plumbing Co | логотип, слоган, "Our Guarantee", услуги | "Collin County", "out in the country or deep in the city" | нет; цена до работы | единственная со сроком: "at least 1 year" | нет |
| 7 | Genzel | районы, услуги, чек-лист нового дома, цены и план, вопросы | самая местная: 75009, "почти все дома после 2015" (их слова), builder-grade, очень жёсткая вода без цифры, Light Farms, Mustang Lakes, Cambridge Crossing, гарантия застройщика, редуктор давления, первая замена водонагревателей, глина | план $27 в месяц или $282 в год, 15 процентов, без платы за выезд | "Our work is guaranteed", без срока | "Emergency service available" |
| 8 | Tortuga | статья: доступная цена, частые услуги, как сэкономить, тревожные признаки | Frontier Park, Preston Road, "rapid growth", дома старые и новые | пример "$150", "free estimate", рассрочка | нет | "prompt response times" |
| 9 | Advanced | бесплатная проверка, о компании, 24/7, цены, статьи блога | нет; компанию ведёт Jeremy, ветеран, мастер | бесплатная проверка "($100 Value)" | нет | "Same-day service available", 24/7 |
| 10 | Specialty | "Prosper and Celina", качество, Prosper | нет | нет; рассрочка в меню | нет | "promptly send a skilled technician" |

Сводка:

- Суммы в долларах на шести страницах, но это скидки и купоны (CTX, Roto-Rooter, Legacy в меню), абонемент (Genzel), пример (Tortuga) и "стоимость" бесплатной проверки (Advanced). Цену вызова не называет никто.
- Срок гарантии называет одна страница (Celina Plumbing Company). Ещё пять пишут "guarantee" без срока.
- Время приезда: "within hours" у Roto-Rooter, условие "before ten in the morning" у Milestone, "Same-day" ещё у Advanced.
- Ссылки на официальный источник (celina-tx.gov, TSBPE, водоканал, EPA) нет ни у одной из десяти; TSBPE стоит текстом без ссылки у Genzel, Tortuga, Roto-Rooter. Из запасных на сайт города ссылаются Still Waters и Bewley.

### 3. Какие местные факты не называет никто

Проверено поиском слов по всем десяти текстам вместе с меню и подвалом.

1. Давление цифрами: "PSI" и "gauge" нет ни у кого. Редуктор в тексте только у Genzel (заводская настройка "уплывает"), у Legacy и Trident пункт меню. Где он стоит в домах Celina и что показывает манометр, не пишет никто.
2. Счётчик: слова "meter" нет ни на одной странице. Как по счётчику понять, что течёт, и где главный кран, не объясняет никто.
3. Разрешения и город: "permitted" один раз у Genzel (установка водонагревателя). "Inspector", "City of Celina", регистрации в городе и ссылки на celina-tx.gov нет ни у кого, хотя городской список зарегистрированных подрядчиков сам стоит в этой выдаче. Строка о регистрации FPP в Celina, разрешениях и инспекциях с одной ссылкой на страницу города будет только нашей.
4. Материалы труб: ни "PEX", ни "copper", ни "CPVC", ни "cast iron", ни "polybutylene" нет ни на одной странице.
5. Ремонт под плитой: "tunnel", "braze", "post-tension", "type L" нет. Slab leak назван шестью страницами одной строкой.
6. Канализация до города: "property line", "city side", "smoke test" нет; "clean out" только в чужом отзыве у Trident.
7. Полив и обратный клапан: "sprinkler" нет ни у кого; backflow только в меню (CTX "Backflow Testing", Roto-Rooter для бизнеса).
8. Чердак, поддон, расширительный бак, предохранительный клапан: нет (бак только в меню Legacy).
9. Мороз: что ломается в Celina в мороз, не пишет никто.
10. Сток кондиционера ("condensate") и хлор или хлорамин: нет ни у кого.
11. Источник воды и цифра жёсткости: о жёсткой воде пишут Roto-Rooter и Genzel, но ни источника, ни цифры нет ни у кого. Факт для нас должен прийти из раздела 6a с официальной ссылкой.
12. HOA, MUD, ETJ: нет ни у кого.
13. Районы: только Genzel (Light Farms, Mustang Lakes, Cambridge Crossing) и Tortuga (Frontier Park, Preston Road). Из 56 официальных названий со страницы города "Planned Developments" (`docs/briefs/_shared/cities-official-place-names-2026-10-03.json`) на десяти страницах стоят два.
14. Скрытые беды нового дома: про гарантию застройщика пишет только Genzel; про шуруп или гвоздь в трубе за гипсокартоном нет ни у кого ("screw", "nail", "drywall" нет). На нашей нынешней странице это уже есть ("The Screw Behind the Drywall"): наш угол.
15. Настоящие вызовы с подробностями: нет ни у кого (у Legacy два названия работ без текста).
16. Правило вызова ($49 в будни, засчитывается в ремонт, цена до начала работ): нет ни у кого.
17. Человек: по имени только Advanced (Jeremy). Блок с Денисом будет редкостью, но не единственным.

Уже занято, не будет "только нашим": глина, жёсткая вода словами, корни деревьев, три названия районов, "дома новые", округа, офис в самом Celina (CTX, Celina Plumbing Company; у нас офиса в Celina нет и придумывать его нельзя).

Пункты выше говорят только о том, чего нет у конкурентов; сами факты должны прийти от Дениса или с официальных страниц.

### 4. Структура: длина, разделы, FAQ

Основной текст по возрастанию: 275, 390, 468, 533, 601, 635, 756, 934, 1 004, 1 212 слов. Середина около 620, среднее около 680. Наша нынешняя страница (1 355) уже длиннее всех десяти; 2 500 слов это вдвое больше самой длинной. По длине здесь конкуренты слабее, чем по Plano (там середина около 1 300).

Три типа: страница города большой компании (Legacy, Milestone, Trident, Roto-Rooter, Genzel: H1 "Plumbers in Celina, TX" или близко, абзац о городе, услуги, "почему мы", купоны; местные факты только у Roto-Rooter и Genzel); главная небольшой компании (CTX, Celina Plumbing Company, Advanced, Specialty: 275 до 530 слов своего текста, две без H1; первое место в среднем у главной CTX); статья блога (Tortuga).

Почти у всех: "24/7" или "emergency", tankless (7 из 10), скидки или бесплатная проверка. Соседние города называют шесть (CTX, Legacy, Milestone, Trident, Genzel, Specialty). Карта Google у двух (Trident, Tortuga). Celina в H2: у Roto-Rooter 6 из 7, у Genzel 4 из 5, у CTX и Celina Plumbing Company ни одного.

FAQ на двух страницах из десяти, всего 7 вопросов. У Roto-Rooter вопросы тегами H3 в первом показе и жирным во втором; у Genzel жирным текстом, как у нас.

Roto-Rooter (5):
- "Why are slab leaks so common in Celina, TX?"
- "Can tree roots really damage my plumbing in Celina?"
- "How does Celina's hard water affect my plumbing and water heater?"
- "What should I do if a severe storm causes water damage to my home in Celina?"
- "Is Roto-Rooter licensed and insured to work in Celina, TX?"

Genzel (2):
- "Is Celina's water really that hard?"
- "Do I need a softener if I have a tankless heater?"

У остальных восьми FAQ нет (у Milestone и Trident только пункт меню). Сравнение с нашими семью вопросами в приложении, раздел И: совпадений слов нет; вопрос про жёсткую воду занят дважды; про цену вызова, давление и разрешения вопросов нет ни у кого.

Попутная находка: на нашей нынешней странице (живой сайт и файл нового сайта) ответ на второй вопрос FAQ ("My house is only a few years old. Why is water leaking behind a wall?") это копия ответа про водонагреватель из первого. При переписке ответ нужен новый.

### 5. Шаблоны title и H1

Title: город первым или вторым словом почти у всех. "Plumbers in Celina, TX" (Genzel), "Plumber in Celina, TX" (Trident; так же начинается наш title), "Plumbing Services in Celina, TX" (Legacy; у Tortuga после "Affordable"), "Celina Plumbers" (Roto-Rooter), "Celina, TX Plumbers" (Milestone), "Celina Plumbing" (CTX, Celina Plumbing Company). Без Celina: Advanced, Specialty. Хвост это похвала себе ("Fast & Reliable Experts", "Trusted", "Near You", "Affordable"). Конкретную работу или проблему не называет никто, телефона в title нет ни у кого. Длина от 32 до 106 знаков.

H1: чаще всего "Plumbers in Celina, TX" (Milestone, Trident, Genzel); ещё "Plumbing Services in Celina, TX" (Legacy). Проблемы в H1 только у Roto-Rooter ("for Every Drain, Leak, and Emergency"). Без H1 две, у CTX восемь H1, у Specialty H1 без города.

Наши нынешние (снимок старого сайта): title "Plumber in Celina, TX | Water Heater Repair & Replacement - FPP", H1 "Plumber in Celina, TX - Water Heaters and the Problems New Houses Hide". Начало title дословно как у Trident, дальше своё: названа работа и проблема. Менять или нет, решает Search Console; со стороны конкурентов причин менять нет. Не стоит брать: "Experts", "Trusted", "Near You", "Affordable", "Best", голое "Plumbers in Celina, TX".

### 6. Папка для проверки на совпадения

- `/Users/denyskavaler/Projects/fppplumbing-site/source/competitors/2026-10-03-celina/`: формат как в `2026-10-03-plano/` (первая строка адрес, вторая весь видимый текст одной строкой), порядок как в таблице раздела 1, оглавления нет.
- `tools/check_overlap.py` берёт все `*.txt`, первую строку как адрес. Чтение теми же правилами проверено отдельным скриптом (сам инструмент не запускал): все десять читаются.
- Команда: `python3 tools/check_overlap.py <черновик> source/competitors/2026-10-03-celina`.
- Запасные (Cathedral, Still Waters, Bewley, Mr. Rooter) в папку не положены, их тексты только во временной рабочей папке.

### 7. Вопросы Денису

1. Genzel пишет, что почти все дома в Celina построены после 2015 года, на "builder-grade" трубах. Так ли это на ваших вызовах? С чем в Celina звонят чаще всего?
2. Двое конкурентов строят страницу на жёсткой воде (Genzel ставит умягчитель почти к каждому ремонту крана). Видите ли вы в Celina накипь и убитые картриджи чаще, чем в других городах? Упоминать ли умягчитель (мы ставим Aquasana иногда)?
3. Меряете ли вы давление в домах Celina, что обычно показывает манометр, где там стоит редуктор?
4. Попадаются ли в Celina дома с колодцем или септиком, и берёте ли такие вызовы?
5. Есть ли вызовы из Celina для рассказов с фото, например тот slab leak в почти новом доме с нынешней страницы: год дома, как нашли, как чинили?
6. На что смотрит инспектор Celina при замене водонагревателя? Можно ли написать, что FPP есть в городском списке зарегистрированных подрядчиков? [Пометка проверки: вторая половина закрыта словом Дениса 3 октября, не задавать.]
7. Нынешняя страница обещает фото и описание поломки для претензии к застройщику. Это остаётся?

## 4. Фото и клипы

Источник: `docs/briefs/_shared/photos-by-city-after-recount.json` (204 записи архива: 143 фото и 61 видео; прочитан 3 октября 2026). Город «после пересчёта» в этом файле поставлен по границе города (basis "city boundary"), по слову Дениса (basis "Denys's word"), оставлен как был ("as before") или снят, если место съёмки вне десяти городов. Слово Дениса о городе работы главнее проверки по карте. Координат в файле нет, и в брифе их нет. Сверено с `photos/captions-en.csv` (подписи и план страниц после пересчёта), с `docs/briefs/_shared/cities-free-photos-2026-10-03.md` (строка Celina: 2 фото, свободны 52 и 121, клипов 0) и с частью 8 (раздел 1.2).

После пересчёта за Celina числятся 2 файла, оба фото, оба по границе города; слова Дениса о городе нет ни у одного. Видео за Celina нет.

### 4.1. Все файлы, у которых город после пересчёта Celina

Колонка «Что сказал Денис» дана как в файле, по-русски. Подпись и план даны как в общем файле, по-английски; ниже каждой строки то, что уже стоит в `photos/captions-en.csv`. «Пометки» это колонка flags, слово в слово.

| № | Вид | Дата | Основание города | Город до пересчёта | Что сказал Денис | Подпись (англ.) | Где стоит на собранном сайте | Отложено для | Пометки |
|---|---|---|---|---|---|---|---|---|---|
| 52 | фото | 2025-02-24 | city boundary | Prosper | «Наружный кран заменен на frost free, в стене» | "Outside faucet replaced with a frost free, in the wall, Prosper" (в captions-en.csv: "Outside faucet replaced with a frost free, in the wall, Celina") | нигде | /hose-bib-repair-frisco-plano/ /plumber-prosper-tx/ (в captions-en.csv: /hose-bib-repair-frisco-plano/ /plumber-celina-tx/) | пусто |
| 121 | фото | 2025-02-24 | city boundary | Prosper | «Замена наружных кранов: слева лопнувший при морозе (burst spigot), справа новый» | "Burst outside faucet after a freeze on the left, the new one on the right, Prosper" (в captions-en.csv: "..., Celina") | нигде | /blog/burst-outside-spigot/ /hose-bib-repair-frisco-plano/ /plumber-prosper-tx/ (в captions-en.csv: /blog/burst-outside-spigot/ /hose-bib-repair-frisco-plano/ /plumber-celina-tx/) | "Hose reel brand visible (Hoselink): crop." |

Что видно по таблице:

- Оба кадра сняты в один день и, по словам Дениса, это одна тема: замена уличного крана после мороза. Одна ли это работа, в архиве не записано. Если это одна история, по правилу CLAUDE.md она сначала показывает проблему (121, лопнувший кран рядом с новым), потом ремонт (52, новый frost free в стене).
- Город только по границе, Денис его не называл. Город в подписи по CLAUDE.md берётся из `photos/captions-en.csv` (city_final); пересчёт по границе (`photos/city-changes.md`: 52 и 121 "Prosper" стало "Celina", план `/plumber-prosper-tx/` стал `/plumber-celina-tx/`) убрал их из плана Prosper, а общий файл фото ещё показывает старые подпись и план. Слово Дениса о городе работы главнее границы (CLAUDE.md, фото на странице Frisco). Брифу Prosper эти фото не брать (часть 8, раздел 5, пункт 2).
- Фото 121 записано в план поста `/blog/burst-outside-spigot/`, а пост начинается словами "A Plano homeowner called us on a cold morning". Если это та же работа, город в посте или у фото неверен; если другая, подпись в посте не должна выдавать фото за ту работу. Пост приносит клики (16 кликов, 1,721 показ, место 9.3 за 3 месяца; часть 8, раздел 1.2).
- Правило Дениса про мороз: капать оставляют краны в доме; уличный frost free кран, поставленный правильно, не мёрзнет и не лопается, ему нужен только чехол. Подпись к 121 и строка на странице не должны говорить, что уличный кран надо оставлять капать. Какой кран лопнул (обычный или frost free) и почему, знает только Денис.
- На фото 121 видна марка катушки для шланга (Hoselink): кадр обрезать.

Вне городских записей, но для этой страницы:

- **Фото 2 и 4** (фургон FPP у офиса Frisco, 30 сентября 2026, город Frisco словом Дениса). В пометках обоих: "stand in for Celina and Lewisville until job photos from there (Denys, October 1, 2026)" и "on other city pages the alt must not name Frisco". Фото 2 уже главное фото страницы Frisco (номерной знак размыт, знак парковки закрашен), в `photos/captions-en.csv` его alt говорит, что на фургоне телефон Frisco. Фото 4 не стоит нигде, в плане ещё emergency и главная. Какой из двух ставить на Celina, решает тот, кто пишет страницу, с Денисом.
- **Главное фото живой страницы** (фургон у кирпичных домов, `/wp-content/uploads/2025/05/photo_2025-05-15_20-41-50.jpg`, alt "FPP Plumbing service van parked outside a home in Celina, TX"). В архиве этого кадра нет; город подтверждает только alt, а у всех десяти городских страниц главное фото из одной серии с разными городами в alt (часть 1, раздел 4). На борту телефон Plano, на крыле "M-38532". Новый сайт сегодня ставит его главным фото страницы Celina.
- **Десять старых фото галереи** с "Celina, TX" в alt (`/gallery/`, alt дословно в `8-links-tables.md`, Л1): главный кран и PRV на вводе, течь у коробки стиральной машины и вздувшийся пол, два газовых бака по 50 галлонов на чердаке и другие. Их нет в `photos/index.csv`, город не записан, а во всей пачке из 104 фото города в alt разложены почти поровну по всем десяти. Только после слова Дениса (часть 8, раздел 1.3).

### 4.2. Кандидаты по темам страницы

Темы взяты из живой страницы (часть 1), из запросов (часть 2) и из того, чего нет у конкурентов (часть 3). Правила из CLAUDE.md: история, названная по проблеме, сначала показывает проблему, потом ремонт; клип режется до пяти секунд, без звука, крутится сам; все картинки одного размера, 3:4; номерной знак в кадре не читается; фото, снятое в другом месте, на страницу города не идёт, пока Денис не назовёт работу.

| Тема страницы | Файлы | Что с ними делать |
|---|---|---|
| Первый экран: работа или фургон в Celina | нет | Настоящего кадра нет (4.3). Пока его нет, по слову Дениса от 1 октября можно фото 2 или 4 (фургон у офиса Frisco) с alt без слова Frisco. Нынешнее фото живой страницы городом не подтверждено |
| Водонагреватели (title, первый H2; самая большая группа запросов с celina, 1,338 показов за 16 месяцев) | нет | Ни одного кадра из Celina. Фото 28 (новый газовый Bradford White на 50 галлонов) без города, 95 (T&P клапан) Frisco по границе: на Celina не идут |
| Скрытая течь в стене молодого дома (H2 "The Screw Behind the Drywall") | нет | Кадры гвоздя от полки (192, 193, 194) это работа во Frisco словом Дениса, 192 и 193 стоят на странице Frisco. На Celina не идут |
| Slab leak в новом доме (H2 "Yes, New Homes Get Slab Leaks"; «slab leak repair celina, tx» 112 показов за 16 месяцев) | нет | Ни одного кадра из Celina. Клип 165 это Little Elm словом Дениса; 45 и 162 без города. На странице города slab leak одним коротким абзацем со ссылкой |
| Уличный кран и мороз (ссылка на hose bib, которой сейчас нет; советы города на мороз, часть 6, city-h1) | 121, потом 52 | Пара «лопнувший кран, потом новый frost free» для короткой истории или для строки со ссылкой на `/hose-bib-repair-frisco-plano/`. Только после слова Дениса о городе и о том, что случилось |
| Давление и PRV (город пишет про 80 psi; совет Дениса мерить давление раз в год) | нет | Ни одного кадра из Celina. Фото 81 (PRV и второй запорный кран) Frisco по границе |
| Детали нового дома: наполнительные клапаны, измельчители, картриджи душа (H2 "The Rest of the Week") | нет | Ни одного кадра из Celina |
| Засоры, главная линия, канализация | нет | Ни одного кадра из Celina |
| Emergency, ночные вызовы ("When It Cannot Wait") | нет | Ни одного кадра из Celina |
| Гарантия застройщика: фото и описание поломки (FAQ 6) | нет | Ни одного кадра |

В архиве есть 37 файлов без города (22 фото и 15 клипов; сняты вне десяти городов или город не определён). Среди них есть кадры по темам этой страницы (картридж Moen 25, водонагреватель 28, frost free кран 29, пайка под фундаментом 45 и 162). Как кандидаты для страницы Celina они не предлагаются: на странице города стоят работы из этого города (на странице Frisco все фото Frisco), а у этих файлов города нет.

### 4.3. Чего не хватает: какие кадры просить у Дениса

1. Настоящее фото с работы в Celina или фургон FPP на улице в черте города. Кадр вертикальный, чтобы встал в размер 3:4; без номеров домов; номерной знак размоем. Это замена нынешнему главному фото и подмене фургоном у офиса Frisco.
2. Если работа с уличным краном (121 и 52) была в Celina: кадр той же работы крупнее (лопнувшее место, кран в стене до замены, новый кран с чехлом).
3. Водонагреватель в доме в Celina, «до» и «после»: поддон и его слив, сброс T&P, расширительный бак, закреплённый ("installed and braced", это пункт городской инспекции, часть 6, city-b3).
4. Скрытая течь в молодом доме в Celina: вскрытый гипсокартон, место течи, если был шуруп или гвоздь, то он в трубе.
5. Манометр на уличном кране дома в Celina с цифрой давления и PRV там, где он стоит в этих домах.
6. Ящик счётчика: кран города у счётчика и отдельный кран хозяина у дома (город пишет, что кран у счётчика только для работников города, часть 6, city-d3).
7. Slab leak в почти новом доме в Celina, если такая работа была: яма или тоннель, место течи, ремонт.
8. Наполнительный клапан унитаза, измельчитель или картридж душа с работы в Celina, «до» и «после».

## 5. Отзывы: кандидаты

Файл раздела: `docs/briefs/celina/5-review-candidates.md`, вставлен целиком. Заголовок файла: «5. Отзывы: кандидаты для страницы Celina».

Длинные списки в бриф не вставлены, они лежат рядом: `5-review-candidates-tables.md` (43 КБ, часть А: 27 чистых отзывов с названной работой, часть Б: остальные чистые, часть В: свободные, но отсеянные, с причинами).
Раздел для брифа страницы `/plumber-celina-tx/`. На страницы ничего не поставлено: выбор делает чат, который пишет страницу, и Денис. Полные таблицы рядом: `5-review-candidates-tables.md` (часть А: 27 чистых отзывов с названной работой, часть Б: остальные чистые, часть В: свободные, но отсеянные, с причинами).

### Коротко

- **Ни один из 407 отзывов не называет Celina, её улицы или районы.** Свободных пятизвёздочных отзывов с Celina в тексте: **0**. Нет Celina и в ответах компании, и в выгрузке Google Takeout (131 отзыв).
- Поэтому все десять кандидатов **не привязаны к Celina**: это отзывы без места в тексте. Другие помощники этой ночи предлагают такие же отзывы своим городам (пересечения ниже).
- Свободных пятизвёздочных отзывов с текстом 330, по всем правилам проходят 146, работу называют 27.
- Порядок подобран под Celina: живая страница говорит, что город почти весь из новых домов, а главный вызов там водонагреватель. Первыми идут горячая вода (alex p), течь внутри дома (Kevin N.) и единственный отзыв со словами "new home" (Rob C.).
- Из трёх отзывов живой страницы правила проходит только David Faidley. P M и J L называют Дениса по имени.
- Чистых отзывов про замену водонагревателя, slab leak, течь в стене нового дома, гарантию застройщика, PRV, главную линию и водопровод во дворе нет.

### Откуда данные

- `reviews/all-reviews.csv`: 407 отзывов (Google 131: профиль Plano 105, профиль Frisco 26; Thumbtack 249; Yelp 27), пять звёзд у 396.
- Занятые: `reviews/site-reviews.json` (изменён 3 октября в 10:04) и `reviews/site-ledger.md` (04:54), прочитаны 3 октября 2026 в 10:29: в обоих одни и те же 40 авторов на 14 страницах, двенадцать главной совпадают со списком задания. Плюс резерв главной: R I. (Yelp), Gregory Gaskin II, Lanessa Arnold Jenkins.
- Живая страница: `source/crawl/pages/plumber-celina-tx.json` и старый журнал `reviews/ledger.md`.
- Места Celina для поиска, 78 названий: 4 района с живой страницы, 56 со страницы города Planned Developments (`docs/briefs/_shared/cities-official-place-names-2026-10-03.json`, источник https://www.celina-tx.gov/1291/Planned-Developments), сам Celina, индекс 75009, главные дороги (Preston Road, Coit Road, Ownsby, FM 455 и другие). Совпадений 0.
- Google сверен с Takeout от 1 октября 2026 (`source/gbp-takeout/`), Thumbtack и Yelp с `reviews/raw/`: тексты, звёзды и даты совпадают. Вживую на площадках не проверялись.

### Сколько пятизвёздочных отзывов свободно

| Шаг | Сколько |
|---|---|
| Пять звёзд | 396 |
| Минус 6 без текста и 10 копий отзывов Google на Thumbtack | 380 |
| Минус 47 строк занятых авторов (43 человека: 40 на страницах нового сайта, включая двенадцать главной, и три резерва) | 333 |
| Минус 3 строки: тот же человек под другим именем (L W = Liane W., Rani C = Rani ., Lanessa A. = Lanessa Arnold Jenkins) | **330 свободных** |
| Из них называют Celina или место в Celina | **0** |

Из 330: Thumbtack 227, Google Plano 69, Yelp 19, Google Frisco 15.

| Причина отсева (строка может иметь несколько) | Строк |
|---|---|
| Имя Дениса (Denys, Dennis, Denis, Denyes, Deny, Denise и т.п.) | 156 |
| Автор стоит на другой странице старого сайта | 36 |
| Другой город или место в нём (Plano, Frisco, Prosper, Carrollton, McKinney, "Shops at Legacy", "North Dallas") | 14 |
| "plumber near me" (Денис снимал такие 1 и 2 октября) | 8 |
| Суммы, процент комиссии или слово fee | 7 |
| Придержаны для другой страницы: Ann Crawford, Steve Fredrickson и, судя по имени и тексту, он же Steve F. на Yelp, Quan Nguyen | 5 |

После правил: **146 чистых** (Thumbtack 116, Google Plano 21, Yelp 7, Google Frisco 2), включая David Faidley с живой страницы. Работу называют 27, остальные короткие и общие.

### Десять лучших кандидатов

Все десять не привязаны к Celina: места в тексте нет ни у одного. Текст дословный, с опечатками и двойными пробелами автора. Ни у одного нет имени Дениса, сумм, жалоб, комиссии, другого города, "near me".

| Место | Имя | Площадка | Профиль | Дата | Работа | Место в тексте | Цифра приезда | Текст дословно | Ссылка | Почему |
|---|---|---|---|---|---|---|---|---|---|---|
| 1 | alex p | Google | Plano | 2025-01-11 (January 2025) | Нет горячей воды в снежную бурю | нет, не привязан к Celina | нет ("arrived promptly") | "FPP Plumbing provided exceptional service! They quickly responded to our call, arrived promptly, and fixed the issue fast when we had no hot water in this winter snow storm. Their team was professional, efficient, and thorough. Whether it’s plumbing repairs, drain cleaning, or water heater installation, FPP Plumbing delivers top-quality solutions. Highly recommend for reliable, quick, and expert plumbing services." | [ссылка](https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sChdDSUhNMG9nS0VJQ0FnSURmel9Qamh3RRAB!2m1!1s0x0:0xccc66184bdaf3a93) | Единственный чистый отзыв про горячую воду, а это главный вызов Celina; дважды "FPP Plumbing". Минус: вторая половина звучит как реклама. |
| 2 | Kevin N. | Thumbtack | Plano | 2023-01-04 (January 2023) | Течь из ванной наверху: вода из светильника на кухне и по стенам гаража | нет, не привязан к Celina | нет ("the same day") | "These guys are life savers. I had a leak in an upstairs bathroom and water was coming out of my light fixture in the kitchen as well as down the walls in my garage. They came out the same day I contacted them and were able to diagnosis and fix the issue. I would and will be contacting them for any other plumbing work that I have." | [листинг](https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760) | Скрытая течь в доме найдена и устранена: ближе всего к разделу живой страницы про течи в новых домах. Старый, 2023. |
| 3 | Rob C. | Yelp | Plano | 2025-02-19 (February 2025) | Установка сложной системы фильтрации воды в новом доме | нет, не привязан к Celina | нет | "Responsive, efficient and professional. Very satisfied with FPP and their installation of a complex water filtration system in a new home." | [листинг](https://www.yelp.com/biz/fpp-plumbing-plano-2) | Единственный свободный отзыв со словами "new home". Называет FPP. Ни в одной десятке других городов. Оговорка ниже. |
| 4 | Dr. Jalal Jalali | Google | Plano | 2025-07-08 (July 2025) | Замена крана стиральной машины | нет, не привязан к Celina | ДА: "the same day in less than an hour" | "I called several plumber for replacement of a washer machine valve and this FPP plumbing  compony was the only  one that his price was a lot reasonable than the others. He came the same day in less than an hour. Very professional i highly recommend them and I will use them again for any pluming work." | [ссылка](https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sCi9DQUlRQUNvZENodHljRjlvT2xOTFpEQlVhbmxvY0ZoRk4wSTNhbGc0Um10WmJrRRAB!2m1!1s0x0:0xccc66184bdaf3a93) | Конкретная работа, "plumber" и "FPP plumbing", цена сравнена без сумм. Минус: цифра приезда. |
| 5 | Javeed N. | Thumbtack | Plano | 2022-11-06 (November 2022) | Течь, которую трудно найти | нет, не привязан к Celina | нет | "Response was immediate. They were able to troubleshoot a water leak that was hard to find. Very nice and pleasant to work with." | [листинг](https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760) | Тема живой страницы про загадочные течи в молодых домах. Короткий и самый старый. 1 октября снят со страницы leak detection, сейчас свободен. |
| 6 | Eric H. | Thumbtack | Plano | 2023-02-25 (February 2023) | Сломанный кран душа, заменён | нет, не привязан к Celina | нет | "Quick and easy! Fixed my broken shower valve - able to get the replacement from the local HD and then they were done!" | [листинг](https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760) | Душевой кран: на живой странице одна из ранних поломок новых домов. "HD" у клиента, по всей видимости, Home Depot. |
| 7 | Sathya P. | Thumbtack | Plano | 2023-11-04 (November 2023) | Замена измельчителя и течь под раковиной | нет, не привязан к Celina | нет | "I had to get the garbage disposal, replaced and also fix the leak under the sink. Both jobs were completed." | [листинг](https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760) | Измельчитель: живая страница называет дешёвые измельчители частой поломкой. Две работы. |
| 8 | Ryan E. | Thumbtack | Plano | 2023-03-30 (March 2023) | Унитаз: нашли причину, заменили детали | нет, не привязан к Celina | нет | "Great job! Quickly identified the issue with my toilet, and got the necessary parts replaced. I'll be saving their number for all of my future plumbing needs. Thanks again!" | [листинг](https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760) | Унитаз и детали: на живой странице наполнительные клапаны, которые сдаются на третий год. "plumbing needs". |
| 9 | Laura B. | Thumbtack | Plano | 2023-07-06 (July 2023) | Посудомойка не сливала воду | нет, не привязан к Celina | нет ("the same day") | "Outstanding job at troubleshooting why the dishwasher would not drain. He was very efficient and quick and was able to get parts and install the same day. Highly recommend." | [листинг](https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760) | Слив и засор, нашёл причину, детали в тот же день. Единственный про посудомойку. |
| 10 | Michael V. | Thumbtack | Plano | 2023-08-02 (August 2023) | Новая коробка кранов в прачечной, течь уличного крана (sillcock) | нет, не привязан к Celina | нет | "I had a great experience with two jobs. I needed a new valve box installed in the laundry room and one outside sillcock was leaking. I was a little nervous when I saw a blowtorch but everything is water tight and working. I definitely will call them back if I need anything else done!" | [листинг](https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760) | Две названные работы и горелка (пайка), ни времени, ни денег. |

Ссылки Google ведут на сам отзыв (из файла, вживую не открывались). У Yelp и Thumbtack ссылка на общий листинг, как на других страницах сайта. Слово plano в адресах листингов это адрес карточки FPP, а не место работы. Уровень Local Guide у alex p и Dr. Jalal Jalali в файле не записан, его читают в профиле. Подпись по правилу 11 без города (города в тексте нет): "★★★★★ · January 2025 · Google" с уровнем, если он есть; "★★★★★ · Yelp · February 2025"; "★★★★★ · Thumbtack · January 2023".

#### Оговорки

1. **Ни один не из Celina по тексту.** Живая страница пишет над отзывами "What Celina Homeowners Say About FPP Plumbing" и "Real Google reviews from local homeowners". Текстом отзывов это не подтверждено; где были работы, знает только Денис (вопрос 1).
2. **Rob C.** Фильтрация воды у FPP работа нечастая, без своей страницы (в правилах проекта: умягчители Aquasana изредка, могут быть в фото и историях). Ответ компании на Yelp подтверждает работу: "the water filtration system for your new home". Текст из PDF кабинета Yelp; Yelp не пускает проверку из браузера, сверять Денису со своего входа (вопрос 3).
3. **Dr. Jalal Jalali** единственный в десятке с цифрой приезда: слова клиента разрешены, аудитор отметит.
4. **Семь из десяти с Thumbtack, все 2022 и 2023 годов.** Свежих отзывов Thumbtack с работой и без имени Дениса нет. Чистых Google с названной работой всего пять: alex p, Dr. Jalal Jalali, Lily Chaskelmann, A P, Phillip Potter.
5. **Тот же человек на другой площадке:** у десятки совпадений нет (имя и первая буква фамилии по трём площадкам). Сомнительные пары среди остальных чистых: ERIC W. (Thumbtack) и Eric Wickstrom (Google, старая главная); John W. (Thumbtack) и John Wilson (Google, старая страница Lewisville); Harish S. на Yelp и на Thumbtack (там имя Дениса); David H. (Thumbtack) и, возможно, David Harbour (Google, ниже пяти звёзд).

#### Пересечения с другими городами

По файлам `docs/briefs/<город>/5-review-candidates.md` на 10:29 (Plano, Little Elm, The Colony, Lewisville; у остальных городов файла ещё нет). В десятке у них: alex p и Kevin N. у всех четырёх; Dr. Jalal Jalali у Plano, Little Elm, The Colony; Michael V. у Plano и Little Elm; Javeed N. и Eric H. у The Colony и Lewisville; Sathya P. у Lewisville; Ryan E. у Little Elm. Rob C. и Laura B. ни у кого в десятке (только в запасах). Один автор стоит на одной странице, поэтому у Celina самый сильный довод за Rob C.: слова "new home".

**Дополнение при проверке брифа (3 октября, около 11:00).** После 10:29 появились файлы Prosper (10:34) и Carrollton (10:52), сверены все шесть (`docs/briefs/<город>/5-review-candidates.md`). Десятка Prosper: Marina Sexton, alex p, Ryan E., Kevin N., Phillip Potter, Rob C., Jaime D., Sathya P., Eric H., Laura B. Десятка Carrollton: Tyler Sommers, Paula Thompson, Javeed N., Kevin N., Lily Chaskelmann, Dale Q., Alecia K., Michael V., Margo W., Dr. Jalal Jalali. Значит, Rob C. и Laura B. теперь в десятке Prosper (не в его четвёрке). Предложенные четвёрки других городов: Plano: Southwest Industrial, Ксенія или Nivas chowdary, Dr. Jalal Jalali, Jeff Blackwell; Little Elm: Quan Nguyen, alex p, Kevin N., Lily Chaskelmann; The Colony: Maksym Basovskyi, Angelo Toborg, Dale Q. или Eric H., Sun Sun; Lewisville: John Wilson, Allen Thong, Javeed N., Kevin N. (или Lily Chaskelmann); Prosper: DMarcus Jones, Marina Sexton, Savannah Park, Phillip Potter; Carrollton: Tyler Sommers, Paula Thompson, Alecia K., Michael V. Из десятки Celina ни в одной чужой четвёрке нет Rob C., Sathya P., Ryan E., Laura B. (Eric H. запасной в четвёрке The Colony). David Faidley другие брифы считают отзывом Celina (старая страница оставляет своих). На новом сайте (`reviews/site-reviews.json`, `site-ledger.md`, `site/src`) на 11:00 никого из десятки и троих с живой страницы нет.

#### Если выбирать четыре сейчас

Предложение, выбор за другим чатом и Денисом: **alex p** (Google, горячая вода), **Kevin N.** (Thumbtack, течь в доме), **Rob C.** (Yelp, новый дом), **David Faidley** с живой страницы (Google, проходит все правила). Две ссылки Google на сам отзыв, три площадки, ни одной цифры приезда, разные работы. Если alex p или Kevin N. уйдут другому городу, их место занимают Javeed N. (скрытая течь) и Dr. Jalal Jalali (Google, с цифрой приезда).

Поправка проверки (около 11:00): alex p и Kevin N. оба в предложенной четвёрке Little Elm, Kevin N. и в четвёрке Lewisville; Javeed N. в четвёрке Lewisville, Dr. Jalal Jalali в четвёрке Plano. Если их отдадут тем городам, свободная замена из этой десятки, которой нет ни в одной чужой четвёрке: Sathya P. (измельчитель и течь под раковиной), Ryan E. (унитаз), Laura B. (посудомойка). Rob C. и David Faidley ни в одной чужой четвёрке нет.

### Запас за десяткой

Чистые, не привязаны к Celina. Тексты дословно в таблицах рядом (части А и Б).

- **Lily Chaskelmann**, Google Plano, November 2024: "Excellent plumber", "FPP Plumbing", течь; цифра приезда "within 30 minutes".
- **Aaron M.**, Thumbtack, December 2022: в заявке "Toilet is running"; говорил с компанией домашней гарантии клиента ("He even spoke to my home warranty company on the phone"). Близко к теме гарантий на новые дома, но слово warranty требует решения (вопрос 4).
- **Marina Sexton**, Google Frisco, September 2026, Local Guide 3 по файлу: самый свежий чистый Google, "plumbing company", работа не названа. 2 октября час стояла на Frisco, снова свободна (`reviews/ledger-decisions.csv`). Её оценка без текста на профиле Plano (январь 2026) это тот же человек.
- **A P**, Google Plano, August 2026: замена крана, 13 слов.
- **Margo W.**, Thumbtack, August 2023: большой засор в тот же день.
- **David H.**, Thumbtack, January 2023: смеситель душа и лопнувшая труба снаружи (см. оговорку 5).
- **Stacie B.**, Yelp, July 2026: уличный кран в выходной; цифра приезда "within an hour"; "Hi showed up" так в файле, сверить на Yelp.
- **Phillip Potter**, Google Plano, December 2024: срочная работа в воскресенье, 12 слов.

### Три отзыва живой страницы Celina

Все три есть в Google Takeout, пять звёзд, тексты на живой странице совпадают с Google слово в слово. На новом сайте никто из них не стоит, в главной и резерве их нет. Переписанная страница города может оставить своих.

| Имя | Профиль | Дата в Google | Свободен | Имя Дениса | Деньги, жалобы | Celina в тексте | Работа | Цифра приезда | Итог |
|---|---|---|---|---|---|---|---|---|---|
| David Faidley | Plano | 2026-07-07 (July 2026) | да | нет | суммы нет ("Reasonable price") | нет | не названа | нет ("arrived when they said") | **Проходит.** Можно оставить. |
| P M | Plano | 2026-05-30 (May 2026) | да | ДА: "Denis" | нет | нет | не названа | нет | Не проходит: имя Дениса, работы нет. |
| J L | Frisco | 2026-03-03 (March 2026) | да | ДА: "Denys" | нет | нет | кран ледогенератора (ice maker water valve) | нет | Не проходит из-за имени Дениса. |

- **David Faidley**: "They arrived when they said, explained what was needed and why, did the work and cleanup. Reasonable price and professional service all the way. I’ll use them again." [ссылка](https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sCi9DQUlRQUNvZENodHljRjlvT2tGSWNuUnRkVXgyU0ZndFIwNUVhV0ZNY1RKVWNIYxAB!2m1!1s0x0:0xccc66184bdaf3a93)
- **P M**: "Denis is honest and hardworking and I feel his work is reliable and I trust him to make the best decisions for my plumbing needs." [ссылка](https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sCi9DQUlRQUNvZENodHljRjlvT2tsRlNFUjFWbTFOTjNWb1JVWmZSRFpST1VObVVuYxAB!2m1!1s0x0:0xccc66184bdaf3a93)
- **J L**: "Denys did an excellent job replacing our ice maker water valve. He was professional, efficient, and made sure everything was working perfectly before he left. Highly recommend his service!" [ссылка](https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sCi9DQUlRQUNvZENodHljRjlvT2xwelEyNVdVWEkyTkhjd1YzUmFXRXQ2V0VvMGFWRRAB!2m1!1s0x0:0xe28e4c9b59df630f)

Что ещё видно: месяцы верные. У J L подпись без звёзд ("Local Guide Level 1 · March 2026 · Google"), по правилу 11 нужно "★★★★★ · Local Guide Level 1 · March 2026 · Google". Уровни Local Guide с живой страницы (6, 3, 1) в файле не записаны, их читают в профиле. Города в подписях нет, и это верно. J L стоит на профиле Frisco, двое других на Plano. J L единственный отзыв во всём файле про кран ледогенератора: оставить его можно только словом Дениса как исключение. Ставить полные ссылки из `all-reviews.csv`, а не короткие maps.app.goo.gl из `reviews/ledger.md`.

### Каких работ среди кандидатов нет

По всем 330 свободным; сначала то, о чём говорит живая страница Celina.

| Работа | Свободных | Чистых | Что мешает |
|---|---|---|---|
| Замена водонагревателя (главный вызов Celina) | 11 | 1 (alex p, без замены) | Имя Дениса и другой город (DMarcus Jones, Deborah Allen, Yulia B, Amy Van); Carrollton (Tyler Sommers); старая страница Allen (Kevin Bennett); Frisco Lakes и 2.99% (Jan Shangle); "near me" (Mohaimen Kadhim, Vlad Ezhov, funny warner f). |
| Течь в стене нового дома | 0 прямо | 2 близких | Близко только Kevin N. и Javeed N.; Faraz K. и Jzacqu Fields с именем Дениса. |
| Slab leak, в том числе в новом доме | 0 | 0 | Отзывы про slab leak стоят на страницах slab leak и leak detection. |
| Новый дом, застройщик, гарантия застройщика | 1 | 1 (Rob C.) | Про гарантию застройщика ни одного; домашняя гарантия только у Aaron M. |
| PRV, давление | 5 | 0 | Старая страница PRV (Ксенія, Megan E), "near me" (Виктория Стехина, Inna Kravchenko), имя и "North Dallas" (Elnard KA). |
| Главная линия, камера | 4 | 0 | Имя Дениса (Jose Walle, Bo Wang), "near me" (Сергей Кравченко), старая страница The Colony (Maksym Basovskyi). |
| Водопровод во дворе | 6 | 0 | Имя Дениса (четверо), "near me" (Inna Kravchenko), старая страница Lewisville (John Wilson). |
| Расширительный бак | 2 | 0 | Jan Shangle (Frisco Lakes, комиссия), funny warner f ("near me"). |
| Backflow, спринклеры | 0 | 0 | Отзывов нет. |
| Кран ледогенератора | 1 | 0 | Только J L, с именем Дениса. |

Есть: горячая вода, течи в доме, краны в прачечной, фильтрация в новом доме, душевой кран, измельчитель, унитаз, посудомойка, засоры, уличные краны, вызовы вечером и в выходные.

### После выбора

- Сверить текст каждого выбранного на площадке слово в слово (Google по ссылке, Yelp со входа Дениса, Thumbtack на листинге) и прочитать уровень Local Guide.
- Записать выбранных в `reviews/proposed-placement.csv` и пересобрать журнал: это делает чат, который ставит страницу, после сверки с выбором других городов.

### Вопросы Денису

1. Ни один отзыв не называет Celina. Были ли в Celina работы у кого-то из десятки или у David Faidley с живой страницы? Если нет, строку над отзывами "What Celina Homeowners Say" лучше сделать нейтральной.
2. P M и J L с живой страницы называют вас по имени. Снимаем обоих или J L оставляем как исключение (единственный отзыв про кран ледогенератора)?
3. Rob C. пишет про систему фильтрации воды в новом доме. Ставим такой отзыв на страницу города, раз фильтрация у вас работа нечастая и без своей страницы?
4. Aaron M. пишет, что сантехник говорил с его компанией домашней гарантии. Слово warranty в отзыве клиента допустимо, раз сроки нашей гарантии на сайте не публикуются?

## 6. Официальные факты

Четыре файла из `docs/briefs/celina/`: два файла фактов (`6a-official-city.md`, `6b-zip-and-age.md`) и две независимые перепроверки (`6a-official-city-verified.md`, `6b-zip-and-age-verified.md`). Все четыре вставлены целиком, заголовки внутри опущены на два уровня. Порядок: сначала списки «что можно брать», «только для справки» и «чего нельзя» из двух проверок (6.0), потом два файла фактов (6.1 и 6.2), потом остальное из проверок: таблицы сверки, исправленные строки, новые источники (6.3 и 6.4).

Рядом лежат и в бриф не вставлены: `6a-official-city-quotes.md` (29 КБ, цитаты города по каждому пункту), `6a-official-city-verified-details.md` (36 КБ, подробная таблица проверки с цитатами, новые находки и адреса всех источников), `6b-zip-and-age-tables.md` (12 КБ, полные таблицы USPS и Census), папки `work-6a/` (тексты прочитанных страниц и документов города, распознанные отчёты о воде) и `work-6b/` (выписки Census и расчёты).

Важно: файлы фактов (6.1 и 6.2) писались до перепроверки. Где они расходятся со списками 6.0 и с таблицами проверки (6.3 и 6.4), верить проверке. Что не подтверждено как написано и где правильно:

- city-b2: инспекция замены водонагревателя у города есть ("Water Heater Replacement Inspection", "Final Inspection"), но фразы «нагревателю нужен Plumbing Trade permit» у города нет, это вывод. Слова города стоят в 6.3, «Исправленные строки словами города».
- city-b11: кроме отделки, закон 2026-003 печатает строительный список работ без разрешения (сараи, заборы и другое); сантехнических работ без разрешения не печатает никто.
- city-c4: повторная инспекция стоит "$100 per failed inspection after 2nd failed inspection", а не просто 100 долларов. Сборы города на страницу всё равно не идут.
- city-h4: город про давление пишет: "City Water Pressure: Varies; if more than 80 psi, a pressure reducing valve shall be installed" (пакет на полив, REV 5/26) и про "two pressure zones" с регуляторами у клиентов "where needed" (план воды 2024, раздел 5.3). Цифры давления в сети и скидки за PRV нет.
- city-a7: подтверждено, но закрыто словом Дениса от 3 октября (компания зарегистрирована во всех городах, где работает): не использовать и не спрашивать. Вопрос 1 файла фактов города и первая ссылка «но см. city-a7» в разделе «Что годится для одной ссылки» этим закрыты: ссылка на регистрацию подрядчиков свободна.
- Индексы: погрешность жилья до 1980 года около ±560, а не ±540; доля жилья 2000 года и позже 82.3%, а не 82.4%; официальная карта индексов у города есть ("Celina Zip Codes Map", 2018), как и строка "Zip Codes" в "2026 Celina Fast Facts" корпорации развития города; форма USPS "Cities by ZIP Code" не открылась ни у первого помощника (302), ни у проверки (405).

### 6.0. Проверенные списки: что можно брать и чего нельзя

#### Город (из `6a-official-city-verified.md`): Можно брать в бриф и на страницу (со ссылкой)

1. Подрядчик регистрируется в городе до разрешения; без регистрации нет разрешений и инспекций (a1, a6). На странице можно писать, что FPP зарегистрирована в Celina: факт из CLAUDE.md и слово Дениса 3 октября.
2. Сантехника идёт с разрешением и инспекцией города; у города есть отдельная "Water Heater Replacement Inspection": T&P, поддон, бак "installed and braced", газ, вытяжка (b1, b2 исправленная, b3).
3. Местные поправки: бак при PRV, бак крепят, поддон 1 1/2 дюйма со сливом 3/4, сброс T&P через разрыв, металл не касается бетона, рукав даёт трубе ход, лестница 300 фунтов, фиолетовый праймер, вент у острова; кодексы 2024 с 1 февраля 2026 (b8, g1, g2, g3).
4. Давление: город сам пишет, что давление разное и выше 80 psi ставят PRV (h4 исправленная). Совпадает со словами Дениса про 80 PSI.
5. Вода: город до и через счётчик, от счётчика до дома хозяин (d1, d2); кран у счётчика только для города, свой кран у дома, нет крана, ставит лицензированный сантехник (d3, h2).
6. Канализация: город смотрит свою линию, иначе сантехник; чистки у дома, две белые трубы, держать открытыми (d4); жир и "grease log" (h7).
7. Пересчёт после течи: раз в год, до 2 месяцев, заявка за 30 дней, счёт от лицензированного и фото ремонта, расход больше двойного среднего (e1 до e4). Хорошо ложится на правило FPP: счёт описывает работу, большие работы фотографируются.
8. Зимнее среднее задаёт плату за канализацию на год, течь зимой её поднимает, правят через форму течи (e6), без названий других городов.
9. Вода покупная, поверхностная, от UTRWD (f1). Цифры жёсткости нет (f3, f5): не писать.
10. Мороз: накрыть краны снаружи, капать краны внутри, слить шланги, выключить полив (h1).
11. Бесплатная проверка полива раз в год (h6); Stage 2 только с датой (h5).
12. Большой счёт часто от унитаза (h8): одна фраза со ссылкой на страницу унитазов.

#### Город (из `6a-official-city-verified.md`): Только для справки, на страницу не ставить

- Все сборы города (a8, b1, b9, c4, d8, h3): на странице только цена 49 долларов.
- Запись на инспекции, часы инспекторов, отсечка, MGO и MyGov, срок разрешения (a2, c1, c2, c3, b13): работа подрядчика.
- Детали теста обратного клапана (b9, h3, h9): на странице только фраза "Once the new assembly is in, it gets tested and the test report goes to the city." Не писать, кто тестирует.
- Видео камерой для новых домов (b6): не писать, что FPP подписывает этот бланк, пока Денис не скажет.
- Срок счётчиков, потери 9.0%, "Superior", перечень свинцовых линий (d8, f6), памятка для новых домов (g4), правила стройки про канализационный отвод (d5): фон.
- Три озера UTRWD (f4): в них стоят чужие имена городов (Lewisville Lake, Dallas, Denton). На странице Celina писать без названий: "lakes of the Upper Trinity Regional Water District".

#### Город (из `6a-official-city-verified.md`): Нельзя брать

- city-a7: не использовать и не спрашивать Дениса, закрыто его словом 3 октября.
- city-b2, city-b11, city-c4, city-h4 в старом виде: только исправленные.
- city-f2: подземная вода и водоносные слои из FAQ Public Works.
- Любая цифра жёсткости для Celina: официальной нет, сайты продавцов умягчителей не источник.
- Определение "excusable defect" из форм других городов (e5).
- Названия других городов со страниц Celina (FAQ про зимнее среднее, отчёт UTRWD).
- Свод законов ecode360 (d7): не прочитан.
- Телефоны города: в текст не ставим.

#### Индексы и возраст домов (из `6b-zip-and-age-verified.md`): Можно использовать в брифе

Все с источником и датой проверки 3 октября 2026.

1. Почтовое отделение Celina: один индекс 75009, адрес отделения 918 W Walnut St. По определению USPS пустой класс индекса значит "both PO Box and street delivery"; отдельного индекса "только ящики" у Celina нет (USPS ZIP_Locale_Detail, файл от 10/01/2026; определение класса: USPS PostalPro "2727 Definitions").
2. Черта города лежит в пяти участках ZCTA; доли земли города по границе 2020 года: 75009 81,6%, 75078 11,2%, 76227 3,9%, 76258 2,2%, 75071 1,2% (Census, файл связи ZCTA и мест 2020). По сегодняшней границе (TIGERweb, January 1, 2026 vintage) расчет дает 83,8 / 9,7 / 4,8 / 1,0 / 0,7%: это наш расчет, не цифра Census.
3. Ни один индекс не лежит целиком в Celina: даже 75009 только на 26,7% в черте города по файлу 2020 года.
4. Земля города: 83,6 кв. км в 2020 году; 128 952 718 кв. м (49,8 кв. мили) по границе на 1 января 2026 года.
5. Медианный год постройки жилья, Celina city, Texas, ACS 5-year 2020-2024, таблица B25035: 2015 (±2). Прошлый выпуск 2019-2023: 2012 (±2). Жилье владельцев: 2015 (±2).
6. Доли жилья Celina city по годам (B25034, 2020-2024): до 1980 7,5%, 1980-1999 10,2%, 2000-2009 16,8%, 2010 и позже 65,6%, из них 2020 и позже 32,4%; 2000 и позже 82,3%. Всего 11 152 единицы (±588); в выпуске 2019-2023 было 8 879 (±574).
7. До 1980 года около 833 единиц с погрешностью около ±560: старое жилье в черте города есть, но сколько, точно сказать нельзя.
8. Дома на одну семью (B25127, занятое жилье): 83,1% построены в 2000 году и позже, 6,9% до 1980.
9. Цифры по индексам 75009, 75078, 76227, 75071, 76258 и по Frisco и Plano, как в таблице выше и в 6b-zip-and-age.md (все совпали с источником).
10. Сравнение (только для автора, на странице Celina другие города не называются): медиана Celina 2015, Frisco 2009, Plano 1993; жилья с 2010 года 65,6%, 46,7%, 13,7%.
11. Рост: Census Bureau, Vintage 2025 (релиз CB26-80, 14 мая 2026): Celina самый быстрорастущий город США среди городов от 20 000 жителей, +24,6% за год до 1 июля 2025 года, 64 427 жителей; самый быстрорастущий и в 2023 году. Данные ACS 2020-2024 отстают от сегодняшнего города.
12. Census API без ключа не отвечает (302 на missing_key.html); ACS 2020-2024 самый новый выпуск; Summary File от 29 января 2026.
13. Фраза живой страницы "Celina is almost entirely new construction": данные ее поддерживают с оговоркой, около 4 из 5 единиц жилья построены с 2000 года, около 7% старше 1980 года.
14. Официальные документы с индексами: карта города "Celina Zip Codes Map" (celina-tx.gov, дата на карте 8/29/2018) и строка "Zip Codes: 75009 (Celina), 75078 (Prosper), 76227 (Aubrey)" в "2026 Celina Fast Facts" корпорации развития города (celinaedc.com). Обе подписывают индексы названиями почтовых отделений. Только как сведение для автора.
15. Адрес мэрии: 142 N Ohio St, Celina, TX 75009 (главная celina-tx.gov).

#### Индексы и возраст домов (из `6b-zip-and-age-verified.md`): Нельзя использовать

1. Погрешность "около ±540" для жилья до 1980 года: неверно, правильно около ±560.
2. "82,4% всего жилья построено в 2000 году и позже": неверно, правильно 82,3%.
3. "Официальной страницы города со списком индексов нет": опровергнуто, см. пункт 14 выше.
4. Ответ на вопрос, какое название города почта принимает для адресов Celina в индексах 75078, 76227, 76258, 75071: не проверено (форма USPS не открыта). Не писать ничего на эту тему, пока не ответит Денис.
5. Слова источников, которые нарушают правила сайта, на страницу не переносить: в релизе Census стоит "Celina, Texas (near Dallas)" (слово "Dallas" одно на сайте запрещено); в листке корпорации и на карте города индексы подписаны "Prosper", "Aubrey", "Pilot Point", "McKinney", "Gunter" (Aubrey, Pilot Point, Gunter, Weston, Anna, Denton и прочие на сайте не называются вообще, а Prosper и McKinney нельзя называть на странице Celina как соседние города).
6. Индексы 75078, 76227, 76258, 75071 на странице Celina: это индексы чужих почтовых отделений; 75078 на 77% Prosper, у которого своя страница.
7. Доли земли нельзя выдавать за доли домов: Census не дает, сколько домов Celina стоит в каждом индексе.
8. Цифры по индексам 75078, 76227, 76258, 75071 как "возраст домов Celina": они описывают в основном соседние места, Celina в них от 0,5 до 11,5% земли участка.
9. Строка "1940-1949: 391 (±448)" как факт о старых домах Celina: погрешность больше самой цифры.

### 6.1. Факты города (файл `6a-official-city.md`)

Заголовок файла: «6.6, часть первая. Официальные факты города Селина (Celina)».

Проверено 3 октября 2026 года (страницы города прочитаны ночью около 02:30 первым запуском этой задачи и днём около 10:20 этим запуском). Источники только официальные: сайт города celina-tx.gov и его хранилище документов (DocumentCenter, FormCenter), отчёт города о воде за 2025 год (выложен самим городом на его странице через issuu), сайт поставщика воды, которого называет сам город: Upper Trinity Regional Water District (utrwd.com, его отчёт лежит по ссылке с его же страницы).

Как читать: всё, что в кавычках на английском, это слова города слово в слово. Всё, что по-русски, это мой пересказ. Если город чего-то не говорит, так и написано: "на официальной странице нет". Ничего не придумано. Если в оригинале стоит длинное тире, я его в цитату не беру или пишу "[тире]".

Цитаты по каждому пункту вынесены в `6a-official-city-quotes.md` (рядом). Полные тексты прочитанных страниц и документов лежат рядом, в папке `work-6a/` (файлы .txt, имя файла начинается с номера страницы или документа города). Отчёты о воде в файлах PDF и на issuu были картинками без текста: я их распознал (OCR), распознанный текст в `work-6a/ccr-2025-celina-ocr.txt` и `work-6a/ccr-2025-utrwd-ocr.txt`.

Свод законов города (Code of Ordinances) лежит на ecode360.com/CE6272: эта страница отвечает проверкой "Just a moment" (защита от роботов Cloudflare). Обходить не стал. Поэтому всё про ответственность за трубы взято со страниц и бланков города, а не из самого свода законов.

#### Сводная таблица

| id | Вопрос | Что говорит город, коротко | Статус | Источник |
|---|---|---|---|---|
| city-a1 | Нужна ли регистрация подрядчика | Да, до подачи на любое разрешение | found | S1 |
| city-a2 | Где регистрируются | В портале MGO Connect, пункт "Apply for Contractor Registration"; старые профили из MyGov не переносятся | found | S1, S8 |
| city-a3 | Какие документы | Лицензия мастера штата (если нужна), водительские права Texas, страховка с городом как "certificate holder", список людей, которые берут разрешения | found | S2, S3 |
| city-a4 | Плата | Сантехники с лицензией штата не платят: "No charge per state law" | found | S2, S5 |
| city-a5 | Срок и продление | Не больше 365 дней или до конца лицензии штата, что раньше; продление кнопкой Renew | found | S2, S4 |
| city-a6 | Без регистрации | Разрешений не дают, инспекций не проводят | found | S2, S11 |
| city-a7 | Есть ли FPP в списке сантехников города | Список от 5/13/2026, 140 записей: FPP Plumbing в нём нет | found; закрыто словом Дениса 3 октября, не использовать (пометка проверки) | S6 |
| city-a8 | Работа без разрешения | Двойная плата и повторная регистрация | found | S5 |
| city-b1 | Общее правило | Сантехнические работы требуют разрешения; без разрешения только отделка | found | S10, S7 |
| city-b2 | Замена водонагревателя | Разрешение (Trade Permit, Plumbing) и финальная инспекция "Water Heater Replacement" | found; перепроверка: инспекция есть, фраза про разрешение это вывод, слова города в 6.3 (пометка проверки) | S9, S11, S12 |
| city-b3 | Что смотрит инспектор на нагревателе | 7 пунктов, среди них расширительный бак "installed and braced" | found | S12, S16, S13 |
| city-b4 | Линия от счётчика до дома | Отдельной строки нет, только общее "plumbing ... require a permit" | not_on_official_page | S10 |
| city-b5 | Ремонт или замена канализации у готового дома | Отдельной строки нет | not_on_official_page | S10, S9 |
| city-b6 | Видео камерой канализации | Город требует видео для жилых канализационных линий, бланк подписывает сантехник с номером лицензии | found | S9, S14, S13 |
| city-b7 | Разрешение на замену PRV | Не сказано | not_on_official_page | S10, S16 |
| city-b8 | PRV и расширительный бак | Поправка города 604.8.3: с PRV, который делает систему закрытой, нужен бак | found | S16 |
| city-b9 | Обратный клапан на поливе | Разрешение на замену клапана нужно; проверка лицензированным тестером через SC Tracking до запуска, результаты за 10 рабочих дней | found | S17, S18, S5, S13 |
| city-b10 | Ремонт под плитой | Отдельных слов нет; в памятке по фундаменту только инспекция "Plumbing Rough (if applicable)" | not_on_official_page | S15 |
| city-b11 | Опубликованный список работ без разрешения | Только отделка: покраска, обои, плитка, ковры, шкафы, столешницы | found; перепроверка: закон 2026-003 печатает ещё строительный список R105.2, сантехники без разрешения нет нигде, 6.3 (пометка проверки) | S10, S16 |
| city-b12 | Сантехнический список работ без разрешения | Закон меняет только строительную часть, сантехнического списка на страницах нет | not_on_official_page | S16 |
| city-b13 | Срок жизни разрешения | 180 дней, истекает на 181-й без инспекций | found | S7 |
| city-c1 | Как назначить инспекцию | Жилые разрешения после 8 декабря 2025: MGO Connect; до этой даты: MyGov | found | S7 |
| city-c2 | Отсечка | 3:30 PM, инспекция на следующий рабочий день | found | S7, S19 |
| city-c3 | Часы инспекторов | Понедельник по четверг, 6:30 AM to 4:30 PM | found | S7 |
| city-c4 | Срочная и повторная | В тот же день 150 долларов (заявка до 8 утра), повтор 100 долларов | found; перепроверка: повтор "$100 per failed inspection after 2nd failed inspection", 6.3 (пометка проверки) | S5 |
| city-d1 | Где кончается ответственность города за воду | Город отвечает "to and through the water meter"; от счётчика до дома отвечает хозяин | found | S20, S21 |
| city-d2 | Вода через счётчик | "The customer is responsible for all water that flows through the meter." | found | S22 |
| city-d3 | Кран города у счётчика | Только для работников города | found | S23 |
| city-d4 | Засор канализации | Город проверяет свою линию, иначе говорит звать сантехника | found | S24 |
| city-d5 | Где кончается ответственность города за канализацию | Простыми словами не сказано | not_on_official_page | S24 |
| city-d6 | Разметка линий | На частной земле город линии не размечает | found | S25 |
| city-d7 | Свод законов города | ecode360 закрыт проверкой от роботов | could_not_open | S26 |
| city-d8 | Проверка счётчика | 150 долларов, деньги вернут, если счётчик неисправен; замена счётчиков раз в 10 до 15 лет | found | S20 |
| city-e1 | Пересчёт счёта после течи | Да, раз в год | found | S27 |
| city-e2 | Условия | Не больше 2 месяцев подряд, заявка в течение 30 дней после ремонта, расход больше двух средних | found | S27 |
| city-e3 | Что прикладывают | Счёт за ремонт от лицензированного мастера и/или чеки на детали, плюс фото ремонта | found | S27 |
| city-e4 | Как считают скидку | Разница между высокими ступенями тарифа и первой ступенью | found | S27 |
| city-e5 | Определение "excusable defect" | Бланк ссылается на "page two", на онлайн-бланке её нет | not_on_official_page | S27 |
| city-e6 | Течь зимой и канализация | Зимний средний расход (декабрь по март) задаёт плату за канализацию на 12 месяцев; после течи город правит это среднее | found | S28, S20 |
| city-f1 | Откуда вода | Покупная поверхностная вода от UTRWD | found | S29, S30 |
| city-f2 | Противоречие об источнике | Старая страница FAQ называет ещё и подземные воды | found | S31 |
| city-f3 | Жёсткость в отчёте города | Строки про жёсткость в отчёте за 2025 год нет | not_on_official_page | S29 |
| city-f4 | Источники у UTRWD | Три озера по отчёту UTRWD | found | S32, S33 |
| city-f5 | Жёсткость у UTRWD | Проверяют, но цифру не публикуют | not_on_official_page | S32, S33 |
| city-f6 | Прочее из отчёта | Рейтинг "Superior", потери воды 9.0%, перечень свинцовых линий сделан | found | S29 |
| city-g1 | Какой сантехнический кодекс | International Plumbing Code 2024 года с приложениями B, C, D и E; действует с 1 февраля 2026 | found | S16, S7, S8 |
| city-g2 | Кодекс для частных домов | International Residential Code 2024 года плюс поправки NCTCOG | found | S16, S7 |
| city-g3 | Местные поправки для сантехника | Медь не касается бетона, канализация на 12 дюймов, бак не провисает, поддон, сброс клапана, чердак | found | S16 |
| city-g4 | Памятка для новых домов | Пурпурный праймер, без AAV на острове, тест 40 до 80 PSI, морозостойкие наружные краны | found | S13 |
| city-h1 | Мороз | Внутри капать, снаружи накрыть, полив выключить | found | S34 |
| city-h2 | Аварийное перекрытие воды | Где искать свой кран, кран города только для персонала | found | S23 |
| city-h3 | Обратные клапаны | Отчёты через SC Tracking Solutions; письмо 2017 года с платами | found | S35, S36 |
| city-h4 | Давление в сети | Цифры давления города нет | not_on_official_page; перепроверка: город пишет "City Water Pressure: Varies; if more than 80 psi, a pressure reducing valve shall be installed", 6.3 (пометка проверки) | S13, S16 |
| city-h5 | Ограничения полива | Stage 2 с 2 июля 2026: полив раз в неделю, не с 10 AM до 6 PM | found | S37 |
| city-h6 | Проверка полива | Бесплатная проверка раз в 12 месяцев | found | S38 |
| city-h7 | Жир и засоры | "Stop the Block!" | found | S24 |
| city-h8 | Высокий счёт | Чаще всего течёт унитаз, тест пищевым красителем | found | S21 |
| city-h9 | Обязанности по обратным клапанам дома | Хозяин ставит, проверяет и обслуживает за свой счёт; осмотр после больших переделок | found | S22 |

#### Источники (S)

- S1. "Contractor Registration": https://www.celina-tx.gov/1985/Contractor-Registration
- S2. "Contractor Registration Form", RVSD 3/24: https://www.celina-tx.gov/DocumentCenter/View/5672/Contractor-Registration-2024
- S3. "MyGov Collaborator Guide, New Contractors", REV 11/24: https://www.celina-tx.gov/DocumentCenter/View/12333/Collaborator-Guide---New-Contractors
- S4. "MyGov Collaborator Guide, Existing Contractors", REV 11/24: https://www.celina-tx.gov/DocumentCenter/View/13232/Collaborator-Guide---Existing-Contractors
- S5. "Master Fee Chart", "UPDATED NOVEMBER 11, 2025": https://www.celina-tx.gov/DocumentCenter/View/8089/Master-Fee-Chart---November-2025
- S6. "Active Contractor List": https://www.celina-tx.gov/1771/Active-Contractor-List и список "Plumbing Contractor" (в конце файла "Total 140", "5/13/2026"): https://www.celina-tx.gov/DocumentCenter/View/12437/Plumbing-Contractor
- S7. "Building Permits and Inspections": https://www.celina-tx.gov/920/Building-Permits-and-Inspections
- S8. "Permit Applications": https://www.celina-tx.gov/921/Permit-Applications
- S9. "Residential Permits": https://www.celina-tx.gov/1982/Residential-Permits
- S10. "When is a building permit required?" (файл 2014 года, ссылка стоит на S7): https://www.celina-tx.gov/DocumentCenter/View/786/When-is-a-building-permit-required
- S11. "Building Permit Trade Application", RVSD 10/22: https://www.celina-tx.gov/DocumentCenter/View/5669/Trade-Permit-Application-2022
- S12. "Helpful Tips for Minor Project Inspections", RVSD 03/25: https://www.celina-tx.gov/DocumentCenter/View/13913/Helpful-Tips-for-Minor-Project-Inspections
- S13. "Helpful Tips" для строителей новых домов, RVSD 2/26: https://www.celina-tx.gov/DocumentCenter/View/15120/Helpful-Tips-2025-03-18
- S14. "Sewer Camera Video Performance Form": https://www.celina-tx.gov/DocumentCenter/View/12185/Sewer-Camera-Video-
- S15. "Foundation Repair Permit Packet", RVSD 12/25: https://www.celina-tx.gov/DocumentCenter/View/9888/Foundation-Repair-Packet-2022
- S16. ORDINANCE NO. 2026-003 (кодексы 2024 года с поправками), файл "updated 2-12-26": https://www.celina-tx.gov/DocumentCenter/View/14878/2024-I-Code-adotion_signed_updated_2-12-26 (подписанная версия: https://www.celina-tx.gov/DocumentCenter/View/14757/Signed_Building-and-Fire-Code-Ordinance_2024-I-Codes)
- S17. Irrigation Ordinance 2020-18: https://www.celina-tx.gov/DocumentCenter/View/7175/200414-Irrigation-Ordinance-Ordinance-2020-18
- S18. Ordinance 2021-39 (поправка к правилам полива, ссылка на странице https://www.celina-tx.gov/1204/Building-Services): https://www.celina-tx.gov/DocumentCenter/View/9044/Resolution-5_11_2021-2021-39_Amendment
- S19. "How to request an inspection from your MyGov account": https://www.celina-tx.gov/DocumentCenter/View/148/How-to-request-an-inspection-in-MyGov5
- S20. FAQ отдела счетов за воду: https://www.celina-tx.gov/1884/Frequently-Asked-Questions
- S21. FAQ Public Works: https://www.celina-tx.gov/1177/Frequently-Asked-Questions
- S22. "Utility Service Agreement" (файл 2024 года): https://www.celina-tx.gov/DocumentCenter/View/10205/Utility-Service-Agreement-
- S23. "Emergency Water Shut Off": https://www.celina-tx.gov/1342/Emergency-Water-Shut-Off
- S24. "Sewer": https://www.celina-tx.gov/1306/Sewer
- S25. "Line Locates": https://www.celina-tx.gov/1303/Line-Locates
- S26. "Code of Ordinances": https://www.celina-tx.gov/868/Code-of-Ordinances, ссылка ведёт на https://ecode360.com/CE6272
- S27. "UCS - Leak Adjustment Application": https://www.celina-tx.gov/FormCenter/Utility-Customer-Service-19/UCS-Leak-Adjustment-Application-254 (ссылка стоит на https://www.celina-tx.gov/1879/Utility-Billing-Forms)
- S28. "Winter Averaging": https://www.celina-tx.gov/1475/Winter-Averaging
- S29. "2025 Water Consumer Confidence Report", "WATER QUALITY REPORT FOR JANUARY 1 - DECEMBER 31, 2025", 12 страниц, выложен 29 июня 2026, встроен на странице https://www.celina-tx.gov/1431/Water ; сам документ: https://issuu.com/celina_texas/docs/2025_consumer_confidence_report
- S30. "Utility Operations": https://www.celina-tx.gov/1302/Utility-Operations
- S31. S21, ответ "WHERE DOES THE CITY OF CELINA'S WATER COME FROM"
- S32. UTRWD, "Water Quality": https://utrwd.com/what-we-do/water/water-quality/
- S33. UTRWD, отчёт "CCR 2025" (файл от 1 апреля 2026, ссылка "Water Quality Report" со страницы S32): https://upperoncloud.egnyte.com/dl/48tTbpy8gMG4
- S34. "Winter Weather Preparedness": https://www.celina-tx.gov/1920/Winter-Weather-Preparedness
- S35. "Backflow & Customer Service Program": https://www.celina-tx.gov/1338/Backflow-Customer-Service-Program
- S36. Письмо города от 6 декабря 2017 про SC Tracking Solutions (файл картинкой, прочитан глазами): https://www.celina-tx.gov/DocumentCenter/View/5685/SC-Tracking-Solutions-Notice---CSI-and-Backflow
- S37. "Water Conservation": https://www.celina-tx.gov/1304/Water-Conservation
- S38. "Irrigation Evaluation Program": https://www.celina-tx.gov/1543/Irrigation-Evaluation-Program

#### Главное в цитатах

Все цитаты по каждому пункту лежат в `6a-official-city-quotes.md`. Здесь только то, на чём держится страница.

- Регистрация (S1): "All contractors performing work within the City are required to complete registration before applying for permits." Плата (S5): "Mechanical, Electrical, Plumbing Contractor No charge per state law". Без регистрации (S2): "Permits will not be issued, or inspections performed to any individuals or companies who do not have a current registration with the City of Celina."
- Водонагреватель (S12), финальная инспекция "Water Heater Replacement Inspection", пункт 5: "Verify expansion tank is installed and braced."
- PRV (S16, 604.8.3): "An expansion tank or approved device shall be installed for the water heater with the addition of a pressure reducing valve or regulator creating a closed system."
- Полив (S18): "Any person installing an irrigation system, replacing a backflow prevention device and / or making additions to an existing irrigation system within the territorial limits or extraterritorial jurisdiction of the city is required to obtain a permit from the city."
- Инспекции (S7): "Inspection Cut-Off Hours at 3:30 PM Daily"; жилые разрешения после 8 декабря 2025 идут через MGO Connect.
- Граница ответственности (S20): "The City of Celina is responsible for delivering water to and through the water meter." и "any leak between the water meter and your home is the property owner's responsibility to repair."
- Кран города (S23): "This valve is located between the water meter and the street and is accessible only to authorized City personnel."
- Пересчёт после течи (S27): "may request a one-time water bill adjustment per year", "must be submitted within thirty (30) days after the leak repairs have been made", прикладывают "An invoice for repair(s), as evidence of repair done by a licensed individual and/or receipts for purchasing the repair parts along with pictures of the repair."
- Вода (S29, отчёт за 2025 год): "The City of Celina provides purchased surface water from Upper Trinity Regional Water District." Жёсткости в отчёте нет.
- Кодекс (S16, S8): "The International Plumbing Code, being in particular the 2024 edition and appendices B, C, D & E, as amended"; "Effective February 1, 2026, all permit applications and inspections will be conducted in accordance with the 2024 codes."
- Мороз (S34): "Cover outdoor faucets and exposed plumbing." и "Allow indoor faucets to drip during prolonged freezing temperatures."

#### Что годится для одной ссылки на официальный источник

На странице Фриско ссылка ведёт на регистрацию подрядчиков. Для Селины ближайшие варианты:
1. https://www.celina-tx.gov/1985/Contractor-Registration (тот же смысл, что у Фриско; но см. city-a7). [Пометка проверки: city-a7 закрыт словом Дениса 3 октября, ссылка свободна.]
2. https://www.celina-tx.gov/1884/Frequently-Asked-Questions (город сам пишет, что от счётчика до дома отвечает хозяин).
3. https://www.celina-tx.gov/1920/Winter-Weather-Preparedness (мороз, слова сходятся с советом Дениса).

Выбор за автором страницы и Денисом.

#### Вопросы Денису

1. Зарегистрирована ли FPP в Селине сейчас (портал MGO Connect)? В опубликованном списке сантехников от 13 мая 2026 FPP нет. [Пометка проверки: закрыт словом Дениса 3 октября, не задавать.]
2. По практике в Селине: берёте ли разрешение на замену PRV, на ремонт линии от счётчика, на точечный ремонт канализации, на ремонт течи под плитой? Город отдельно этого не пишет; на страницу только со слов Дениса.
3. Ставить ли на страницу цифры города (разрешение на сантехнику 100 долларов, пересчёт счёта)? Это не наши цены, но правило про цифры строгое.
4. Жёсткость воды: официальной цифры нет ни у города, ни у UTRWD. Если у Дениса есть свой замер в Селине, только тогда цифра на странице.

#### Что не сделано и что надо знать

1. Свод законов на ecode360 закрыт проверкой от роботов, не читал.
2. Отчёты о воде (город и UTRWD) были без текстового слоя: распознаны машиной, цитаты сверены по смыслу со страницей. Для точности открыть страницы 3 и 9 отчёта города глазами.
3. Письмо S36 (2017) прочитано глазами с картинки.
4. Как продлевать регистрацию и какая отсечка инспекций в новом MGO Connect, город отдельно не пишет.
5. Телефоны города в этом файле не приведены и в текст страницы не идут.

### 6.2. Индексы и возраст домов (файл `6b-zip-and-age.md`)

Заголовок файла: «6, часть вторая. Почтовые индексы Celina и возраст домов».

Проверено 3 октября 2026. Все цифры взяты из официальных файлов USPS и Census Bureau, адреса запросов стоят в конце. Ничего не придумано: где проверить не удалось, так и написано. Полные таблицы (все десятилетия, погрешности, жилье владельцев, дома на одну семью) лежат рядом в файле 6b-zip-and-age-tables.md, рабочие выписки и расчеты в папке work-6b.

#### Коротко, самое важное

1. У почтового отделения Celina один индекс: 75009, обычный, с доставкой на дом. Индекса "только абонентские ящики" (PO BOX) у Celina в файле почты нет.
2. Черта города при этом лежит в пяти участках индексов: 75009 (основная часть, 81,6% земли города по границе 2020 года, 83,8% по сегодняшней границе), 75078 (южный край, 11,2% и 9,7%; это индекс почты Prosper), 76227 (юго-западный угол, 3,9% и 4,8%; почта Aubrey), 76258 (северо-запад, 2,2% и 1,0%; почта Pilot Point), 75071 (юго-восточный угол, 1,2% и 0,7%; почта McKinney).
3. Ни один индекс не принадлежит Celina целиком. Даже 75009 по файлу 2020 года только на 26,7% лежит в городе (по сегодняшней границе 42,1%), остальное это земля округа вне городов и кусок Weston.
4. Celina самый молодой город из трех. Медианный год постройки жилья (ACS 2020-2024, таблица B25035): Celina city 2015 (±2), Frisco city 2009 (±1), Plano city 1993 (±2). По индексам: 75009 2012, 75078 2015, 76227 2014, 75071 2011, 76258 2002.
5. В самом городе 65,6% жилья построено в 2010 году и позже, 32,4% в 2020 году и позже, 16,8% в 2000-2009, 10,2% в 1980-1999 и 7,5% до 1980 года. Старое жилье в городе есть, но его мало, и эта цифра с большой погрешностью.
6. Данные Census отстают от сегодняшнего города: по оценке Census на 1 июля 2025 года в Celina 64 427 жителей, за год плюс 24,6%, это самый быстрорастущий город США среди городов от 20 000 жителей. Сегодня домов больше, и они новее, чем показывает выпуск 2020-2024.
7. Census API (api.census.gov) без ключа не отвечает (проверено 3 октября 2026). Ключ я не запрашивал: это регистрация с почтой, такое делает только Денис. Те же цифры взяты из официальных файлов Census (ACS Summary File) и сверены с сайтом data.census.gov: 192 клетки, несовпадений ноль.

#### а. Индексы Celina

Источник 1: USPS, файл "ZIP Codes by Area and District codes" (Zip_Locale_Detail.xlsx, на странице стоит "file updated 10/01/2026"). Источник 2: Census Bureau, файл связи участков ZCTA и городов 2020 года, место "Celina city", код 4813684. Источник 3: сегодняшняя граница города на карте Census (TIGERweb, слой "Incorporated Places", "January 1, 2026 vintage").

ZCTA это "ZIP Code Tabulation Area": участок, которым Census приближенно повторяет почтовый индекс. По ним считается вся статистика ниже.

| Индекс | USPS: класс | USPS: почтовое отделение | Доля земли города (граница 2020) | Доля площади города (граница на 1 января 2026, мой расчет) | Доля участка ZCTA в черте Celina (2020) | С кем индекс общий (доля земли участка, 2020) |
|---|---|---|---|---|---|---|
| 75009 | обычный, с доставкой (поле "ZIP CLASS CODE" пустое) | CELINA | 81,6% | 83,8% | 26,7% | вне городов 68,8%; Weston city 4,5%; Anna city меньше 0,1% |
| 75078 | обычный, с доставкой | PROSPER | 11,2% | 9,7% | 11,5% | Prosper town 77,1%; вне городов 11,4% |
| 76227 | обычный, с доставкой | AUBREY | 3,9% | 4,8% | 1,6% | вне городов 66,5% и еще десять городов и поселков (Cross Roads, Denton, Little Elm, Aubrey и другие, список в таблицах) |
| 76258 | обычный, с доставкой | PILOT POINT | 2,2% | 1,0% | 0,8% | вне городов 94,1%; Pilot Point city 4,8% |
| 75071 | обычный, с доставкой | MCKINNEY | 1,2% | 0,7% | 0,5% | McKinney city 36,9%; New Hope 1,9%; вне городов 60,4% |

Что еще видно в источниках:

- Абонентские ящики. В файле USPS индексы "только PO BOX" помечены буквой P в поле "ZIP CLASS CODE". У отделения CELINA, TX одна строка: 75009, поле пустое, адрес отделения 918 W WALNUT ST. Других строк с Celina в Техасе нет. Значит, отдельного индекса для ящиков у Celina нет.
- Граница выросла. В файле 2020 года земля города 83,6 кв. км (32,3 кв. мили), на карте Census с границей на 1 января 2026 года 129,0 кв. км (49,8 кв. мили). Доли по сегодняшней границе я посчитал сам (земля вместе с водой, метод в work-6b/overlap.py), готовой такой цифры у Census нет. Картина та же: почти весь город в 75009, южный край в 75078.
- Где лежат куски (мой расчет по карте Census, только направление от середины города): 75078 южный край, примерно в 6 км к югу; 76227 юго-западный угол; 75071 юго-восточный угол; 76258 северо-запад. Участок 75058 задевает рамку карты, но в черту города не входит.
- Почему кусок 76258 по сегодняшней границе меньше, чем в 2020 году (1,25 против 1,82 кв. км), по этим данным не видно. Может быть, граница там изменилась, может быть, разница в рисовке. Для страницы это не важно.
- Официальной страницы города со списком индексов я не нашел: поиск по celina-tx.gov дал только документы с адресом мэрии "142 N. Ohio Street Celina, Texas 75009". [Пометка проверки: опровергнуто, у города есть карта "Celina Zip Codes Map" (2018), см. 6.4, zip-a7.]
- Форму USPS "Cities by ZIP Code" (какие названия города почта принимает для каждого индекса, например принимает ли она "Celina" для домов Celina в индексе 75078) открыть не удалось: запрос через curl получил перенаправление (ответ 302), браузер в эту ночь запрещен. Это вопрос к Денису: какой город и индекс стоят в адресах его вызовов в южной части Celina.

Для автора страницы: если индексы вообще показывать, то только 75009. Индекс 75078 это главный индекс Prosper (77% его земли это Prosper), у Prosper своя страница; показать его на странице Celina значит залезть на чужую страницу. Индексы 76227, 76258, 75071 почта называет Aubrey, Pilot Point и McKinney; Aubrey и Pilot Point на сайте называть нельзя вообще. На живой странице индексов Celina нет: в тексте ни одного, в схеме только индекс офиса Frisco. В схеме живой страницы в areaServed стоит "Aubrey": это название почты индекса 76227, на сайте его быть не должно (это уже отмечено в разделе 1).

#### б. Медианный год постройки (таблица B25035)

Выпуск: American Community Survey, 5-year, 2020-2024 (в файлах Census это "2024 ACS 5-year"). Это самый новый выпуск: описание переменной B25035_001E за 2024 год отвечает ("Estimate!!Median year structure built"), за 2025 год ответ 404; файлы 2024 года на сервере Census датированы 29 января 2026. Рядом стоит прошлый выпуск, 2019-2023.

"Медианный год" значит: половина жилья построена раньше этого года, половина позже. "±" это погрешность из того же файла (ACS это выборочный опрос, не перепись). Считается все жилье: дома, квартиры, передвижные дома. Рядом медиана только по жилью, где живет сам владелец (таблица B25037): в Celina это 92,7% занятого жилья.

| Участок | Медиана, все жилье, 2020-2024 (B25035_001E) | Погрешность (B25035_001M) | Та же медиана, выпуск 2019-2023 | Медиана, жилье владельцев (B25037_002) | Всего жилья (B25034_001) |
|---|---|---|---|---|---|
| 75009 | 2012 | ±2 | 2011 (±2) | 2013 (±2) | 11 260 |
| 75078 | 2015 | ±1 | 2014 (±1) | 2015 (±1) | 16 512 |
| 76227 | 2014 | ±2 | 2013 (±2) | 2015 (±1) | 23 278 |
| 75071 | 2011 | ±2 | 2010 (±2) | 2011 (±2) | 25 276 |
| 76258 | 2002 | ±3 | 1999 (±6) | 2001 (±5) | 3 046 |
| Celina city (штат 48, код места 13684) | 2015 | ±2 | 2012 (±2) | 2015 (±2) | 11 152 |
| Frisco city (код 27684) | 2009 | ±1 | 2009 (±2) | 2008 (±1) | 80 353 |
| Plano city (код 58016) | 1993 | ±2 | 1993 (±1) | 1991 (±1) | 117 686 |

Для справки: штат Texas 1992 (±1).

Как читать индексы. О самой Celina говорят только строка "Celina city" и, с оговоркой, 75009. Остальные участки почти целиком лежат за чертой Celina: 75078 на три четверти это Prosper, 76227, 76258 и 75071 в Celina на 0,5-1,6%. Их цифры описывают соседей, не Celina. В 75009 входит и земля не Celina (по файлу 2020 года 73% участка: земля округа вне городов 69% и Weston 4,5%), поэтому его цифры тоже шире города.

За один год выпуска медиана Celina сдвинулась с 2012 на 2015: в выборку 2020-2024 попало много домов последних лет. Всего жилья в городе по выпуску 2019-2023 было 8 879 (±574), по выпуску 2020-2024 уже 11 152 (±588).

#### в. Доли по годам постройки (таблица B25034, все жилье)

Выпуск тот же, 2020-2024. Проценты посчитаны мной из чисел файла: "до 1980" это строки с 007 по 011, "1980-1999" строки 005 и 006, "2000-2009" строка 004, "2010 и позже" строки 002 и 003. Названия строк сверены с официальным файлом описаний (Table Shells).

| Участок | До 1980 | 1980-1999 | 2000-2009 | 2010 и позже | из них 2020 и позже |
|---|---|---|---|---|---|
| 75009 | 7,8% | 13,4% | 19,7% | 59,1% | 21,9% |
| 75078 | 1,2% | 5,3% | 16,7% | 76,8% | 21,9% |
| 76227 | 3,4% | 7,9% | 24,4% | 64,2% | 24,9% |
| 75071 | 5,1% | 12,6% | 29,6% | 52,7% | 9,3% |
| 76258 | 18,7% | 27,3% | 19,8% | 34,2% | 7,2% |
| Celina city | 7,5% | 10,2% | 16,8% | 65,6% | 32,4% |
| Frisco city | 1,5% | 16,9% | 34,8% | 46,7% | 6,7% |
| Plano city | 18,4% | 50,3% | 17,6% | 13,7% | 1,8% |

Числа для Celina city (жилых единиц, оценки): всего 11 152; 2020 и позже 3 618; 2010-2019 3 695; 2000-2009 1 870; 1990-е 528; 1980-е 608; 1970-е 179; 1960-е 123; 1950-е 0; 1940-е 391 (±448); 1939 и раньше 140 (±217). Все остальное в таблицах рядом.

Только дома на одну семью (таблица B25127, сверх задания): в Celina это 97,4% занятого жилья (Frisco 74,1%, Plano 64,9%). Из домов Celina 83,1% построены в 2000 году и позже, 10,0% в 1980-1999, 6,9% до 1980 года. Жилье владельцев (B25036): до 1980 года 7,2%, 1980-1999 9,8%, 2000-2009 16,6%, 2010 и позже 66,3%.

Про старые дома Celina: до 1980 года в городе построено около 830 жилых единиц, но погрешность этой суммы около ±540 (мой расчет из погрешностей строк) [пометка проверки: верно около ±560, см. 6.4, age-celina], а строка "1940-1949" (391 ±448) по сути шум. Census подтверждает, что старое жилье в черте города есть, но сколько его, точно сказать нельзя. Где именно оно стоит, по таблицам не видно (у участка 75009 до 1980 года 878 единиц, но в этот участок входит и земля вне города).

#### г. Сравнение с Frisco и Plano

- Дома Celina по медиане на 6 лет моложе, чем во Frisco (2015 против 2009), и на 22 года моложе, чем в Plano (1993); по жилью владельцев разница 7 и 24 года.
- Две трети жилья Celina (65,6%) построено с 2010 года и каждая третья единица (32,4%) с 2020 года; во Frisco это 46,7% и 6,7%, в Plano 13,7% и 1,8%. При этом доля жилья до 1980 года в Celina (7,5%, с большой погрешностью) выше, чем во Frisco (1,5%): в Celina немного старого жилья есть, во Frisco его почти нет.
- Это только для сведения автора: на странице Celina другие города не называются и не сравниваются.

#### Что из этого следует для страницы

Это предложение помощника по данным, решение за Денисом: его слово про то, что он видит на вызовах, главнее статистики.

- Фраза живой страницы "Celina is almost entirely new construction" по данным Census в целом верна: 82,4% [пометка проверки: верно 82,3%, см. 6.4, live-1] всего жилья и 83,1% домов на одну семью построены в 2000 году и позже. Слово "almost entirely" чуть сильнее данных: около 7% жилья старше 1980 года. В разделе 1 эта фраза стоит в списке неподтвержденных; данные ее поддерживают с этой оговоркой.
- Если автору нужна одна цифра со ссылкой на официальный источник, самые надежные две: медианный год постройки жилья в Celina 2015 (ACS 2020-2024, таблица B25035, Celina city, Texas) и рост населения 24,6% за год до 1 июля 2025 года, самый быстрый в стране среди городов от 20 000 жителей (Census Bureau, Vintage 2025, пресс-релиз 14 мая 2026). Россыпь процентов на страницу лучше не выносить: это статистика, а не опыт Дениса.
- Замороженный гайд по главному крану говорит о домах "built after 2010-2015" в Celina; данные это поддерживают: 65,6% жилья города построено с 2010 года. Гайд заморожен, это только сведение.
- Тема старых домов в Celina может быть отдельным коротким абзацем, только если Денис подтвердит, что такие вызовы были и что он там видел. Без его слов ее не писать.

#### Вопросы Денису

1. Какие индексы стоят в адресах ваших вызовов в Celina: только 75009 или бывает и 75078 (южный край города, почта Prosper), 76227 и 76258? Показывать ли на странице индекс вообще (на живой странице его нет)?
2. Бывают ли вызовы в старые дома Celina (по Census около 7% жилья в городе старше 1980 года)? Если да, в какой части города и что там в трубах и чем эти вызовы отличаются от вызовов в новые дома?
3. Оставляем ли фразу "Celina is almost entirely new construction"? По данным около 4 из 5 домов построены в 2000 году и позже, 2 из 3 с 2010 года.

#### Адреса запросов

Census API, как просили в задании, и что он ответил (3 октября 2026):

- https://api.census.gov/data/2024/acs/acs5?get=NAME,B25035_001E&for=zip%20code%20tabulation%20area:75009,75078,76227,75071,76258 : ответ 302, перенаправление на https://api.census.gov/data/missing_key.html (страница "Missing Key").
- https://api.census.gov/data/2024/acs/acs5?get=NAME,B25035_001E&for=place:13684,27684,58016&in=state:48 : тот же ответ 302 на missing_key.html. То же для 2023 и 2025.
- https://api.census.gov/data/2024/acs/acs5/variables/B25035_001E.json : отвечает без ключа, "Estimate!!Median year structure built". Для 2025 года ответ 404, значит выпуск 2024 самый новый.
- Когда у Дениса будет свой ключ, те же цифры даст запрос: https://api.census.gov/data/2024/acs/acs5?get=NAME,B25035_001E,B25035_001M&for=zip%20code%20tabulation%20area:75009,75078,76227,75071,76258&key=КЛЮЧ и для городов: https://api.census.gov/data/2024/acs/acs5?get=NAME,B25035_001E,B25035_001M&for=place:13684,27684,58016&in=state:48&key=КЛЮЧ

Откуда цифры взяты на самом деле (официальные файлы Census, ключ не нужен):

- https://www2.census.gov/programs-surveys/acs/summary_file/2024/table-based-SF/data/5YRData/acsdt5y2024-b25035.dat (медиана, все жилье)
- https://www2.census.gov/programs-surveys/acs/summary_file/2024/table-based-SF/data/5YRData/acsdt5y2024-b25034.dat (по десятилетиям, все жилье)
- там же acsdt5y2024-b25037.dat (медиана, владельцы и съемщики), acsdt5y2024-b25036.dat (по десятилетиям, владельцы и съемщики), acsdt5y2024-b25127.dat (по типу здания)
- https://www2.census.gov/programs-surveys/acs/summary_file/2023/table-based-SF/data/5YRData/acsdt5y2023-b25035.dat и acsdt5y2023-b25034.dat (прошлый выпуск)
- https://www2.census.gov/programs-surveys/acs/summary_file/2024/table-based-SF/documentation/ACS20245YR_Table_Shells.txt (названия строк) и Geos20245YR.txt (названия участков)
- Строки в файлах: 860Z200US75009, 860Z200US75078, 860Z200US76227, 860Z200US75071, 860Z200US76258, 1600000US4813684 (Celina city, Texas), 1600000US4827684 (Frisco city, Texas), 1600000US4858016 (Plano city, Texas), 0400000US48 (Texas).

Сверка на сайте data.census.gov (один участок на запрос, таблицы B25035 и B25034, 192 клетки, все совпали с файлами):

- https://data.census.gov/api/access/data/table?id=ACSDT5Y2024.B25035&g=860XX00US75009 (и так же для 75078, 76227, 75071, 76258)
- https://data.census.gov/api/access/data/table?id=ACSDT5Y2024.B25035&g=160XX00US4813684 (Celina city), g=160XX00US4827684 (Frisco city), g=160XX00US4858016 (Plano city)
- те же адреса с id=ACSDT5Y2024.B25034

Рост населения:

- https://www.census.gov/newsroom/press-releases/2026/vintage-2025-city-town-pop-estimates.html (таблица 3: "1 Celina city Texas 24.6 64,427"; в тексте: Celina "was also the nation’s fastest-growing city in 2023"; номер релиза CB26-80, "For Immediate Release: Thursday, May 14, 2026")

Индексы и карта:

- https://postalpro.usps.com/ZIP_Locale_Detail (страница USPS) и файл https://postalpro.usps.com/mnt/glusterfs/2026-10/Zip_Locale_Detail.xlsx (лист "ZIP_Locale", строки 75009, 75078, 76227, 75071, 76258)
- https://tools.usps.com/tools/app/ziplookup/cityByZip (форма "Cities by ZIP Code", запрос для 75009): ответ 302. Не открыто.
- https://www2.census.gov/geo/docs/maps-data/data/rel2020/zcta520/tab20_zcta520_place20_natl.txt (какой участок в каком городе, строки с "Celina city" и кодом 4813684)
- https://tigerweb.geo.census.gov/arcgis/rest/services/TIGERweb/tigerWMS_Current/MapServer/28/query?where=GEOID%3D'4813684'&outFields=GEOID,NAME,AREALAND,AREAWATER&returnGeometry=true&outSR=4326&f=json (сегодняшняя граница города) и слой 2 там же ("2020 Census ZIP Code Tabulation Areas", участки в рамке города)
- поиск по celina-tx.gov: списка индексов нет, в документах города адрес мэрии "142 N. Ohio Street Celina, Texas 75009"

#### Оговорки

- ACS это выборочный опрос за пять лет (2020-2024), у каждой цифры есть погрешность. У медиан она 1-3 года. По мелким клеткам (все жилье до 1990 года в Celina) погрешность сравнима с самой цифрой.
- ACS описывает период 2020-2024 целиком, а Celina растет быстрее любого города страны. Сегодняшний город больше и новее, чем в этих таблицах.
- Участок ZCTA повторяет почтовый индекс приближенно, границы у почты и у Census могут расходиться. Файл связи участков и городов сделан по границам 2020 года, участки ZCTA тоже 2020 года.
- Сколько домов Celina стоит в каждом индексе, Census не дает: есть только доли земли. Доля земли не равна доле домов.
- "Жилье" в B25034 и B25035 это все жилые единицы, квартиры и передвижные дома тоже (в Celina около 130 передвижных домов по B25127).
- Доли площади по сегодняшней границе и положение кусков города посчитаны мной по карте Census, это не готовые цифры источника.
- В файле USPS стоят названия почтовых отделений, а не список названий города, которые почта принимает для индекса. Этот список есть только в форме на tools.usps.com, которую ночью открыть не удалось.

### 6.3. Перепроверка фактов города: таблица сверки и исправленные строки (файл `6a-official-city-verified.md`)

Заголовок файла: «6a. Celina: перепроверка официальных фактов (второй проход)». Списки «Можно брать», «Только для справки» и «Нельзя брать» из этого файла стоят в 6.0.

Проверено 3 октября 2026 года, около 10:30 до 10:45 по Техасу. Каждую страницу я открыл сам, отдельным запросом. Документы PDF прочитаны программой. Отчёт города о воде 2025 (issuu) и отчёт UTRWD (Egnyte) сделаны картинками: я сам скачал картинки страниц и распознал их (OCR). Сайт свода законов ecode360 снова ответил проверкой от роботов; обходить не стал.

Правило: "да" только там, где я сам увидел нужные слова или цифры на официальной странице. Цитаты по каждой строке, адреса всех источников и мои новые находки лежат рядом: `6a-official-city-verified-details.md`.

Итог: 58 строк. Подтверждено 54. Не подтверждено как написано 4: city-b2, city-b11, city-c4, city-h4. Одна строка подтверждена, но закрыта словом Дениса и в бриф не идёт: city-a7.

#### Таблица проверки

| id | Что утверждается | Источник | Подтверждено | Заметка |
|---|---|---|---|---|
| city-a1 | Регистрация подрядчика до подачи на разрешение | /1985/Contractor-Registration | да | Слово в слово. |
| city-a2 | Регистрация в MGO Connect; профили MyGov не переносятся | /1985, /921/Permit-Applications | да | Про перенос сказано только на /921. На /1985 висит старый абзац про MyGov. |
| city-a3 | Документы для регистрации, клетка Plumbing | Doc 5672 | да | Бланк "RVSD 3/24", велит грузить в MyGov: старый. |
| city-a4 | Сантехники с лицензией штата не платят | Doc 8089, Doc 5672 | да | "No charge per state law". |
| city-a5 | До 365 дней или до конца лицензии; не передаётся | Doc 5672 | да | Слово в слово. |
| city-a6 | Без регистрации нет разрешений и инспекций | Doc 5672 | да | Слово в слово. |
| city-a7 | В списке сантехников (140, 5/13/2026) нет FPP | Doc 12437 | да, но закрыто | Сам проверил. Денис 3 октября: зарегистрированы во всех городах, вопрос закрыт, в других брифах не проверяем. Не использовать, не спрашивать. |
| city-a8 | Без разрешения: двойная плата и перерегистрация | Doc 8089 | да | Для жилых сантехнических разрешений своя строка: "Double the permit fee (2nd offense is 3x cost)". |
| city-b1 | Сантехника с разрешением; жилое сантехническое разрешение 100 долларов | Doc 786, Doc 8089 | да | Doc 786 от 2014 года. На /920 общее правило "alter, repair, improve...". |
| city-b2 | Замена нагревателя: Trade (Plumbing) permit и финальная инспекция | Doc 13913 | нет, как написано | Инспекция есть. Фразы "нагревателю нужен Plumbing Trade permit" у города нет, это вывод. Исправление ниже. |
| city-b3 | 7 пунктов инспекции нагревателя; бак крепят от провисания | Doc 13913, Doc 14878 | да | Пункты 3, 4, 5 слово в слово; поправки P2605.1 п. 6 и 604.8.3.1. |
| city-b4 | Про разрешение на линию от счётчика до дома не сказано | Doc 786 | да (статус стоит) | Искал на /920, /1982, /921, в стандартах 2024: нет. |
| city-b5 | Про разрешение на ремонт канализации не сказано | /1982 | да (статус стоит) | Не нашёл. |
| city-b6 | Видео камерой для жилых канализационных линий; бланк с лицензией; для новых домов финальный документ | /1982, Doc 12185, Doc 15120 | да | Бланк стоит среди бумаг нового строительства; про ремонт у готового дома не сказано. |
| city-b7 | Про разрешение на замену PRV не сказано | Doc 14878 | да (статус стоит) | Не нашёл. |
| city-b8 | 604.8.3: при PRV и закрытой системе нужен бак | Doc 14878 | да | Слово в слово. |
| city-b9 | Замена клапана на поливе с разрешением (75); тест через SC Tracking, результат за 10 рабочих дней; ремонт системы без разрешения | Doc 9044 | да | Тест и 10 дней стоят в законе 2020-18 (Doc 7175), не в Doc 9044. Сбор в Doc 8089. "repairs ... do not require a permit" про поливочную систему, не про клапан. |
| city-b10 | Памятки по ремонту под плитой нет; в пакете фундамента только "Plumbing Rough (if applicable)" | Doc 9888 | да (статус стоит) | Пакет RVSD 12/25 прочитан целиком. |
| city-b11 | Единственный список работ без разрешения: отделка | Doc 786 | нет, как написано | Закон 2026-003 печатает и строительный список R105.2 (сараи, заборы, подпорные стены, баки, отделка, бассейны, качели, козырьки, настилы). Сантехники нет нигде. |
| city-b12 | Закон меняет только строительную часть R105.2; сантехнического списка нет | Doc 14878 | да (статус стоит) | "Section R105.2; Work exempt from permit: Building: Delete # 1, 2. 3, 5 and 10". |
| city-b13 | Разрешение истекает на 181-й день без инспекции | /920 | да, с уточнением | Второе условие: "No progress has been demonstrated through inspections toward the completion of the project." |
| city-c1 | Жилые после 8 декабря 2025: MGO Connect, раньше MyGov | /920 | да | Слово в слово. |
| city-c2 | Отсечка 3:30 PM, инспекция на следующий рабочий день | /920, Doc 148 | да | "next business day" только в памятке MyGov 2023 года. |
| city-c3 | Инспекторы пн по чт 6:30 до 4:30; линии записи нет | /920 | да | Запись только через порталы. |
| city-c4 | Срочная 150 (до 8 утра), повтор 100, после часов 80 в час, минимум 4 часа | Doc 8089 | нет, как написано | Повтор: "$100 per failed inspection after 2nd failed inspection". Остальное верно. |
| city-d1 | Город до и через счётчик; от счётчика до дома хозяин | /1884, /1177 | да | Обе страницы говорят одно. |
| city-d2 | Вся вода через счётчик на клиенте | Doc 10205 | да | Бланк для новых подключений (подписывает строитель). |
| city-d3 | Кран у счётчика только для города; свой кран у дома | /1342 | да | Слово в слово. |
| city-d4 | При засоре город смотрит свою линию, иначе сантехник; чистки две белые трубы | /1306 | да | Слово в слово. |
| city-d5 | Простых слов о границе ответственности за канализацию нет | /1306 | да (статус стоит) | Нашёл правило стройки в стандартах 2024: публичная чистка "6 inches inside city right-of-way line", "clean-out on the owner's side". Это не правило, кто платит. |
| city-d6 | Город не ищет линии на частной земле | /1303 | да | Слово в слово. |
| city-d7 | ecode360 не открылся | ecode360 | да | В 10:38 снова 403 "Just a moment...". |
| city-d8 | Проверка счётчика 150, при неисправности бесплатно; замена раз в 10 до 15 лет | /1884 | да | Слово в слово. |
| city-e1 | Один пересчёт в год за течь от "excusable defect" | Form 254 | да | Слово в слово. |
| city-e2 | До 2 месяцев; заявка за 30 дней; раз в 12 месяцев; больше двойного среднего; выше 10,000 галлонов | Form 254 | да | Все цифры на форме. |
| city-e3 | Счёт от лицензированного и/или чеки, плюс фото ремонта | Form 254 | да | Слово в слово. |
| city-e4 | Зачёт: разница между высшими ставками и первой | Form 254 | да | Слово в слово. |
| city-e5 | Определения "page two" нет | Form 254 | да (статус стоит) | В сети определения только у других городов. |
| city-e6 | Зимнее среднее задаёт плату за канализацию на 12 месяцев; правка через форму течи; ссылка Laserfiche сломана | /1475 | да | В 10:39 снова "license has expired". Страница путается в месяцах и называет другие города. |
| city-f1 | Покупная поверхностная вода от UTRWD (отчёт 2025, выложен 29 июня 2026) | issuu CCR | да | Мой OCR, страница 3, слово в слово. В тексте "Lake Lewisville and Lake Chapman". |
| city-f2 | FAQ говорит про подземную воду; спорит с отчётом | /1177 | да | Брать слова отчёта. /1302 тоже говорит "purchases treated water from the Upper Trinity Regional Water District". |
| city-f3 | В отчёте города нет жёсткости | issuu CCR | да (статус стоит) | Мой OCR 12 страниц: нет. |
| city-f4 | UTRWD: три озера | UTRWD CCR | да | Мой OCR страницы 2, слово в слово. |
| city-f5 | UTRWD цифру жёсткости не публикует | utrwd.com, UTRWD CCR | да (статус стоит) | "Hardness" только в списке тестов. |
| city-f6 | "Superior", потери 9.0%, перечень свинцовых линий закончен | issuu CCR | да | Мой OCR, слово в слово. |
| city-g1 | Закон 2026-003 от 13 января 2026, IPC 2024 с B, C, D, E; с 1 февраля 2026 | Doc 14878, /921 | да | Дата 1 февраля стоит на /921 (на /920 "February 2026"). |
| city-g2 | IRC 2024 с поправками и NCTCOG | /920 | да | Слово в слово. |
| city-g3 | Местные поправки (металл и бетон, 12 дюймов, бак, поддон, T&P, 300 фунтов, праймер, вент острова) | Doc 14878 | да | Все разделы нашёл. |
| city-g4 | Новые дома: без AAV, медь в рукаве, тест 40 до 80 PSI, незамерзающие краны, не меньше 2 | Doc 15120 | да | Это тест при стройке, не давление в сети. |
| city-h1 | Мороз: накрыть краны снаружи, капать внутри, слить шланги, выключить полив | /1920 | да | Совпадает с правилом Дениса. |
| city-h2 | Нет своего крана: поставить через лицензированного сантехника | /1342 | да | Слово в слово. |
| city-h3 | SC Tracking для отчётов и CSI; в 2017 году 25 за отчёт плюс налог | /1338, Doc 5685 | да | Письмо распознал сам. |
| city-h4 | Город не называет давление, порога 80 PSI нет, скидки за PRV нет | Doc 15120 | нет | Есть: пакет на полив (REV 5/26) "City Water Pressure: Varies; if more than 80 psi, a pressure reducing valve shall be installed"; план воды 2024, 5.3: "two pressure zones", "customer service pressure regulators where needed". Цифры давления в сети и скидки нет. |
| city-h5 | Stage 2 с 2 июля 2026 | /1304 | да | 3 октября всё ещё "CURRENT STATUS: STAGE 2". |
| city-h6 | Бесплатная проверка полива раз в 12 месяцев | /1543 | да | Слово в слово. |
| city-h7 | Жир и "grease log" | /1306 | да | Слово в слово. |
| city-h8 | Частая причина большого счёта: унитаз; тест красителем | /1177 | да | Слово в слово. |
| city-h9 | Клиент ставит, тестирует и обслуживает клапаны за свой счёт; осмотр после больших переделок | Doc 10205 | да | Слово в слово. |

Короткие адреса: "/1985" значит https://www.celina-tx.gov/1985/..., "Doc 8089" значит https://www.celina-tx.gov/DocumentCenter/View/8089/..., "Form 254" это форма пересчёта после течи. Полные адреса в файле details.

#### Исправленные строки словами города

- city-b2: Doc 13913: "Water Heater Replacement Inspection", "Final Inspection". /1982: "Trade Permit Application" "Used for plumbing, electrical, and mechanical work on residential properties." /921, список MGO: "Plumbing Trade".
- city-b11: Doc 786 называет без разрешения только "Painting, papering, tiling, carpeting, cabinets, counter tops and similar finish work." Закон 2026-003 печатает свой строительный список R105.2; сантехнических работ без разрешения не печатает никто.
- city-c4: "Paid Same Day Inspection $150 (before 8AM)"; "Re-inspection Fee $100 per failed inspection after 2nd failed inspection"; "After Hours Inspection $80 per hour (4-hour minimum)".
- city-h4: https://www.celina-tx.gov/DocumentCenter/View/12345/Residential-Irrigation-Packet-0425 : "City Water Pressure: Varies; if more than 80 psi, a pressure reducing valve shall be installed". https://www.celina-tx.gov/DocumentCenter/View/12553/ORD-2024-24_2024-drought-contingency-and-water-conservation-plan-Final , раздел 5.3: "The City of Celina has determined a reasonable system pressure for each of the two pressure zones in its retail distribution system and has installed internal pressure control stations and customer service pressure regulators where needed."

### 6.4. Перепроверка индексов и возраста домов: таблица (файл `6b-zip-and-age-verified.md`)

Заголовок файла: «6b. Проверка фактов: индексы Celina и возраст домов». Списки «Можно использовать» и «Нельзя использовать» из этого файла стоят в 6.0.

Проверено 3 октября 2026, вторым помощником, независимо от первого. Проверялся файл 6b-zip-and-age.md и 18 фактов, которые вернул первый помощник. Каждый источник я открыл сам (curl, один запрос на страницу), цифры Census пересчитал заново из официальных файлов и сверил цифра в цифру. Браузер не использовался. Существующие файлы проекта не менялись. Рабочие выписки лежат в черновике: scratchpad/night/celina/verify6b/ (usps_hits.txt, rel.txt, scan.py, dc/, acsdt5y2024-b25035.dat, acsdt5y2024-b25034.dat, zipmap.pdf, celina-fast-facts2.pdf).

Правило проверки: "да" ставлю только там, где сам увидел эти слова или цифры в источнике. Где цифра верная по источнику, но расчет первого помощника неточен, ставлю "нет" и даю исправленную формулировку.

#### Итог одной строкой

Из 16 фактов со статусом "found" подтверждены 14, в двух исправлены производные цифры (погрешность старых домов ±560 вместо ±540; доля жилья 2000 года и позже 82,3% вместо 82,4%). Факт "у города нет официальной страницы с индексами" опровергнут: на celina-tx.gov есть карта "Celina Zip Codes Map", а у экономической корпорации города в листке "2026 Celina Fast Facts" есть строка "Zip Codes". Форма USPS "Cities by ZIP Code" так и осталась не открытой.

#### Таблица проверки

| id | Что утверждается (кратко) | Источник, который я открыл | Подтверждено | Заметка |
|---|---|---|---|---|
| zip-a1 | У почты Celina, TX один индекс 75009, поле "ZIP CLASS CODE" пустое, отделение 918 W WALNUT ST; других строк Celina, TX нет | USPS Zip_Locale_Detail.xlsx (страница: "file updated 10/01/2026") | да | Строка файла: "SOUTHERN / TEXAS 1 / 752 / 75009 / (пусто) / CELINA / W23189 / P / 918 W WALNUT ST / CELINA / TX / 75009". Других строк с CELINA в Техасе нет ни на одном из трех листов (ZIP_Locale, Unique, Other); есть только Celina в Теннесси и Огайо. Осторожно: буква P в этой строке стоит в поле "LOCALE TYPE" (тип отделения), а не в поле класса индекса. |
| zip-a2 | У Celina нет индекса "только PO BOX": такие индексы помечены P, а у 75009 класс пустой | USPS ZIP_Locale_Detail (страница и файл) плюс USPS PostalPro "2727 Definitions" | да | Сама страница и файл не объясняют, что значит P. Определение нашел в другом документе USPS на том же сайте: https://postalpro.usps.com/storages/2016-12/2727_Definitions.pdf : "A 'P' indicates the ZIP Code has PO Boxes only and a blank ZIP Class indicates both PO Box and street delivery." Значит, 75009 обслуживает и ящики, и доставку на дом. В файле 8 645 строк с классом P и 33 637 с пустым. |
| zip-a3 | Город Celina (4813684) лежит в пяти ZCTA: 75009 81,6%, 75078 11,2%, 76227 3,9%, 76258 2,2%, 75071 1,2%; земля города в 2020 году 83 564 240 кв. м | Census, tab20_zcta520_place20_natl.txt | да | Пересчитал из файла: 81,59 / 11,21 / 3,88 / 2,18 / 1,15%. Сумма пяти частей равна земле города, 83 564 240 кв. м (32,3 кв. мили). |
| zip-a4 | Ни один ZCTA не принадлежит Celina целиком (доли и почтовые отделения) | Тот же файл Census плюс файл USPS | да | 75009: Celina 26,67%, Weston 4,55%, вне городов 68,78%, Anna 0,005%. 75078: Prosper town 77,10%, Celina 11,46%, вне городов 11,44%. 76227: Celina 1,60% и еще десять мест; два из них не города, а CDP (Paloma Creek CDP, Savannah CDP). 76258: Celina 0,78%. 75071: McKinney 36,88%, Celina 0,50% (там еще Frisco 0,24%, New Hope 1,93%, Melissa 0,08%). Отделения по USPS: 75078 PROSPER, 76227 AUBREY, 76258 PILOT POINT, 75071 MCKINNEY (у 75071 есть еще станция LINKSIDE PARK). |
| zip-a5 | Сегодняшняя граница (TIGERweb, "January 1, 2026 vintage"): земля 128 952 718 кв. м (49,8 кв. мили); свой расчет долей: 75009 83,8%, 75078 9,7%, 76227 4,8%, 76258 1,0%, 75071 0,7% | TIGERweb tigerWMS_Current, слой 28 (запрос) и описание слоя; слой 2 (ZCTA 2020) | да | Описание слоя 28 дословно: "Incorporated Places; January 1, 2026 vintage". AREALAND 128952718, AREAWATER 1245112. Доли я пересчитал своим способом (свой скрипт, 1 500 горизонтальных срезов, суша вместе с водой): 83,82 / 9,70 / 4,77 / 0,96 / 0,75%. Совпадает с первым помощником. Направления тоже совпали: 75078 к югу (центр куска около 6 км южнее центра города), 76227 юго-запад, 76258 северо-запад, 75071 юго-восток. Это расчет, а не готовая цифра Census. |
| zip-a6 | Форму USPS "Cities by ZIP Code" открыть не удалось | tools.usps.com/tools/app/ziplookup/cityByZip | нет (не проверено) | Мой GET-запрос получил ответ 405 (у первого помощника 302). Это адрес, куда форма отправляет данные; отправлять форму без браузера я не стал. Вопрос, принимает ли почта "Celina" для адресов в 75078, остается открытым. |
| zip-a7 | Официальной страницы города со списком индексов нет; адрес мэрии 142 N. Ohio Street, Celina, Texas 75009 | celina-tx.gov | нет, исправлено | Адрес мэрии подтвержден на главной celina-tx.gov: "City Hall 142 N Ohio St Celina, TX 75009". Но официальные документы с индексами есть: 1) карта города "Celina Zip Codes Map", https://www.celina-tx.gov/DocumentCenter/View/3575/Zip-Codes-Map , на карте "Date: 8/29/2018", подписи участков "CELINA 75009", "PILOT POINT 76258", "AUBREY 76227", "PROSPER 75078", "MCKINNEY 75071", "GUNTER 75058", в легенде "Postal Officce: Aubrey, Celina, Prosper" (опечатка источника). 2) Celina Economic Development Corporation, "2026 Celina Fast Facts", https://celinaedc.com/assets/main/celina-fast-facts2.pdf (файл изменен 3 августа 2026): "Zip Codes: 75009 (Celina), 75078 (Prosper), 76227 (Aubrey)". Это корпорация развития города, а не сайт мэрии. |
| api-1 | Census API без ключа отвечает 302 на missing_key.html; описание переменной 2024 есть, 2025 нет (404); файлы Summary File от 29 января 2026; сверка 192 клеток без расхождений | api.census.gov, www2.census.gov, data.census.gov | да | Повторил оба запроса: 302, перенаправление на https://api.census.gov/data/missing_key.html. B25035_001E за 2024: 200, "Estimate!!Median year structure built"; за 2025: 404. В каталоге Census у acsdt5y2024-b25035.dat и -b25034.dat дата "2026-01-29 08:11". Сам скачал оба файла и сверил с data.census.gov по 8 участкам: 192 клетки, расхождений 0. |
| age-celina | Celina city: медиана 2015 (±2), выпуск 2019-2023 2012 (±2), жилье владельцев 2015 (±2); 11 152 единицы; до 1980 7,5%, 1980-1999 10,2%, 2000-2009 16,8%, 2010 и позже 65,6% (2020 и позже 32,4%); до 1980 около 833 единиц, погрешность около ±540 | data.census.gov ACSDT5Y2024.B25035, B25034, B25037; ACSDT5Y2023.B25035; Summary File 2024 | нет, исправлено | Все цифры источника совпали цифра в цифру ("1600000US4813684|2015|2"). Ошибка только в собственном расчете: погрешность суммы строк до 1980 года по формуле Census (корень из суммы квадратов погрешностей строк 007-011: 208, 143, 31, 448, 217) равна ±559, то есть около ±560, а не ±540. Подписи строк B25034 и B25037 сверены с описаниями переменных Census. |
| age-75009 | 75009: медиана 2012 (±2), прошлый выпуск 2011 (±2), владельцы 2013 (±2), 11 260 единиц, 7,8 / 13,4 / 19,7 / 59,1% | data.census.gov и Summary File | да | "860Z200US75009|2012|2". До 1980 года 878 единиц. |
| age-75078 | 75078: медиана 2015 (±1), владельцы 2015 (±1), 16 512 единиц, 1,2 / 5,3 / 16,7 / 76,8% | data.census.gov и Summary File | да | "860Z200US75078|2015|1". Прошлый выпуск 2014 (±1). |
| age-76227 | 76227: медиана 2014 (±2), владельцы 2015 (±1), 23 278 единиц, 3,4 / 7,9 / 24,4 / 64,2% | data.census.gov и Summary File | да | "860Z200US76227|2014|2". |
| age-75071 | 75071: медиана 2011 (±2), владельцы 2011 (±2), 25 276 единиц, 5,1 / 12,6 / 29,6 / 52,7% | data.census.gov и Summary File | да | "860Z200US75071|2011|2". |
| age-76258 | 76258: медиана 2002 (±3), прошлый выпуск 1999 (±6), 3 046 единиц, 18,7 / 27,3 / 19,8 / 34,2% | data.census.gov и Summary File | да | "860Z200US76258|2002|3"; владельцы 2001 (±5). |
| age-frisco | Frisco city: медиана 2009 (±1), владельцы 2008 (±1), 1,5 / 16,9 / 34,8 / 46,7% (2020 и позже 6,7%) | data.census.gov и Summary File | да | "1600000US4827684|2009|1"; 80 353 единицы. |
| age-plano | Plano city: медиана 1993 (±2), владельцы 1991 (±1), 18,4 / 50,3 / 17,6 / 13,7% (2020 и позже 1,8%) | data.census.gov и Summary File | да | "1600000US4858016|1993|2"; 117 686 единиц. |
| cmp-1 | По медиане Celina моложе Frisco на 6 лет, Plano на 22 года (по владельцам 7 и 24); 2010 и позже: 65,6 / 46,7 / 13,7%; доля до 1980 в Celina (7,5%) выше, чем во Frisco (1,5%) | Summary File acsdt5y2024-b25034.dat и b25035.dat | да | Арифметика верна: 2015-2009=6, 2015-1993=22, 2015-2008=7, 2015-1991=24. Разница до 1980 года держится и с погрешностью: у Celina нижний край около 2,5%, у Frisco 1,5%. |
| pop-1 | Vintage 2025, релиз CB26-80 от 14 мая 2026: Celina самый быстрорастущий город США среди городов от 20 000 жителей, +24,6% с 1 июля 2024 по 1 июля 2025, 64 427 жителей; самый быстрорастущий и в 2023 | census.gov, пресс-релиз | да | Дословно: "Press Release Number: CB26-80", "For Immediate Release: Thursday, May 14, 2026", таблица 3 "1 Celina city Texas 24.6 64,427", в тексте "Rapid growth is nothing new for Celina, which was also the nation’s fastest-growing city in 2023." Плюс в таблице 4: Celina 4-я в стране по приросту числом, 12 710 человек. |
| live-1 | Фраза живой страницы "Celina is almost entirely new construction" в целом верна: 82,4% всего жилья и 83,1% домов на одну семью построены в 2000 году и позже, около 7% старше 1980; в схеме areaServed стоит "Aubrey" | fppplumbing.com/plumber-celina-tx/ и ACS B25034, B25127 | нет, исправлено | На живой странице фраза есть дословно, в areaServed есть { "@type": "City", "name": "Aubrey" } (там же Prosper, Frisco, McKinney). Индексов на живой странице нет. Но доля всего жилья 2000 года и позже по числам: (1 870 + 3 695 + 3 618) / 11 152 = 82,3%, а не 82,4% (82,4 получилось сложением уже округленных 16,8 и 65,6). Дома на одну семью (B25127, только занятое жилье): 8 360 из 10 058 = 83,1%, верно. До 1980 года: 7,5% всего жилья, 6,9% домов на одну семью. |

#### Что поправить в 6b-zip-and-age.md (файл я не менял)

1. Абзац "Про старые дома Celina": "погрешность этой суммы около ±540" заменить на "около ±560".
2. Раздел "Что из этого следует для страницы", первый пункт: "82,4% всего жилья" заменить на "82,3% всего жилья".
3. Раздел "а", пункт про официальную страницу города: добавить карту "Celina Zip Codes Map" на celina-tx.gov (2018) и строку из "2026 Celina Fast Facts" (celinaedc.com), с тем же предупреждением, что названия Prosper и Aubrey на страницу не идут.
4. Раздел "а", пункт про форму USPS: у меня ответ 405, у первого помощника 302; форма в обоих случаях не открыта.
5. Для ясности в разделе "а": буква P в строке Celina стоит в поле "LOCALE TYPE", а не в поле класса индекса; класс пустой, по определению USPS это "both PO Box and street delivery".

#### Источники, которые я открыл 3 октября 2026

- https://postalpro.usps.com/ZIP_Locale_Detail и https://postalpro.usps.com/mnt/glusterfs/2026-10/Zip_Locale_Detail.xlsx
- https://postalpro.usps.com/storages/2016-12/2727_Definitions.pdf
- https://tools.usps.com/tools/app/ziplookup/cityByZip (ответ 405, не открыто)
- https://www2.census.gov/geo/docs/maps-data/data/rel2020/zcta520/tab20_zcta520_place20_natl.txt
- https://tigerweb.geo.census.gov/arcgis/rest/services/TIGERweb/tigerWMS_Current/MapServer/28 (описание слоя и запрос по GEOID 4813684) и слой 2 (ZCTA 2020, запрос по рамке города)
- https://api.census.gov/data/2024/acs/acs5?get=NAME,B25035_001E&for=zip%20code%20tabulation%20area:75009,75078,76227,75071,76258 и запрос по place:13684,27684,58016 (оба 302)
- https://api.census.gov/data/2024/acs/acs5/variables/B25035_001E.json (200), то же за 2025 (404); описания групп B25034, B25037, B25127 за 2024
- https://www2.census.gov/programs-surveys/acs/summary_file/2024/table-based-SF/data/5YRData/acsdt5y2024-b25035.dat и acsdt5y2024-b25034.dat (скачаны целиком, дата в каталоге 2026-01-29)
- https://data.census.gov/api/access/data/table?id=ACSDT5Y2024.B25035&g=... (а также B25034, B25037, ACSDT5Y2023.B25035 по 8 участкам; B25127 и ACSDT5Y2023.B25034 для Celina city)
- https://www.census.gov/newsroom/press-releases/2026/vintage-2025-city-town-pop-estimates.html
- https://fppplumbing.com/plumber-celina-tx/
- https://www.celina-tx.gov/ и https://www.celina-tx.gov/DocumentCenter/View/3575/Zip-Codes-Map
- https://celinaedc.com/ и https://celinaedc.com/assets/main/celina-fast-facts2.pdf

## 7. Офис

Файла раздела для этой части не было: она написана при сборке по CLAUDE.md, по краулу живой страницы (`source/crawl/html/plumber-celina-tx.html` и `source/crawl/pages/plumber-celina-tx.json`, обход 30 сентября 2026; раздел 1 сверил, что 3 октября код живой страницы тот же) и по файлам нового сайта (`site/src/content/pages/plumber-celina-tx.md`, `site/src/layouts/ServicePage.astro`, `site/src/components/CallButtons.astro`, `Header.astro`, `Callbar.astro`, `OfficeBlock.astro`, `Body.astro`, `ReviewCards.astro`, `site/src/lib/site.ts` и `schema.ts`, прочитаны 3 октября 2026 около 10:50). Карточки Google у Celina нет, проверять вживую было нечего.

### 7.1. Что говорит CLAUDE.md

- Офисы есть только во Frisco и в Plano. Страницы остальных восьми городов описывают обслуживание города из ближайшего офиса: "The other eight city pages describe service coverage of that city from the nearest office. Never invent a local office, address or phone for a city that has none."
- Офис Frisco: 12800 Westridge Blvd, Suite 116, Frisco, TX 75035, линия 469-998-8999. Офис Plano: 5700 Tennyson Pkwy, Suite 300, Plano, TX 75024, линия 980-899-7997.
- Телефоны стоят в шапке, в подвале, в кнопках звонка и в блоках офисов на страницах Frisco и Plano. В абзацах и в ответах FAQ их нет (правило 10).
- Схема: один бизнес на весь сайт с обоими офисами; страница города без офиса ссылается на организацию и называет город в `areaServed`.
- Одобренная строка про дежурство: "A licensed plumber is on duty 24/7". В каком городе сейчас дежурный сантехник, не показываем. Времени приезда в своих словах не обещаем.
- Про расстояние есть одна формулировка, и она описывает район, а не время приезда: "About a twenty minute drive from our Frisco or Plano office" (в CLAUDE.md она для мест вне списка городов).
- Страница города не называет соседние города и не ссылается на страницы других городов (правило 7).

Чего в CLAUDE.md нет: какой из двух офисов обслуживает Celina. Не сказано и то, как называть офис на странице города без офиса: по имени ("our Frisco office") или без названия города. Первое упирается в правило 7. Оба вопроса стоят в части 10.

Что есть в проекте вместо ответа (это не слово Дениса):

- В схеме живой страницы стоят адрес и телефон офиса Frisco.
- На главном фото живой страницы на борту фургона телефон Plano ("980.899.7997").
- Фото 2 и 4 (фургон у офиса Frisco, на фото 2 телефон Frisco) Денис 1 октября разрешил ставить на страницу Celina вместо фото с работы (часть 4). Это решение о картинке, не об офисе.
- Текст главной (`source/home-text-v4.md`) называет Celina без офиса: "Two offices cover the whole area." и дальше "To the north it's a **plumber in Prosper** and a **plumber in Celina**."
- Search Console: по запросам «plumber celina» и «plumber celina tx» выше Celina стоит страница Frisco, оба клика сайта по запросам с celina пришли на Frisco и Plano (часть 2, раздел 6). Это выдача, а не решение о том, откуда едет фургон.
- В `site/src/lib/schema.ts` страница города может получить поле `office`, но для города без своего офиса оно ничего не меняет в схеме.

### 7.2. Что показывает живая страница

- Адресов офисов в тексте страницы нет. В общем блоке старого сайта внизу страницы стоят оба офиса: "Frisco Office" (ссылка на /plumber-frisco-tx/), 12800 Westridge Blvd, Suite 116, Frisco, TX 75035, 469-998-8999, и "Plano Office" (ссылка на /plumber-plano-tx/), 5700 Tennyson Pkwy, Suite 300, Plano, TX 75024, 980-899-7997. Это шаблон всего старого сайта.
- Карты нет: в коде страницы один iframe, и это Google Tag Manager в noscript.
- Телефоны: оба номера ссылками `tel:` в шапке, в нижней панели и в блоке офисов. Нижняя панель свёрстана тегом H2: "980-899-7997 469-998-8999" (шаблон старого сайта). В абзацах и в FAQ телефонов нет.
- В тексте офиса в Celina нет. О том, что мы рядом, говорит одна фраза: "We run Light Farms, Mustang Lakes, Sutton Fields, Glen Crossing, and the streets still going up around them, so getting to you is rarely the hard part." Работал ли FPP в этих районах, по файлам не подтверждено, а Light Farms по карте города вне его полных границ (часть 1, раздел 7).
- Схема: отдельный узел LocalBusiness плюс Plumber с именем "FPP Plumbing - Plumber in Celina, TX", адресом и точкой на карте офиса Frisco, телефоном Frisco, `priceRange` "$$", часами 00:00 до 23:59 все дни и `areaServed`: Celina, Prosper, Frisco, McKinney, Aubrey. В узле Organization телефон Plano. Подробно: часть 1, раздел 6.5, и `1-live-page-tables.md`, Т6.
- Главное фото: фургон на жилой улице, на борту "980.899.7997" (телефон Plano), на крыле "M-38532".

### 7.3. Что новый сайт показывает на этой странице сегодня

Файл страницы: layout "city", city "Celina". Полей `office`, `call_office` и `office_map` в нём нет (они стоят только у страниц Frisco и Plano).

- Над H1 строка "A licensed plumber is on duty 24/7" (её получают все страницы городов и страница emergency).
- Под вступлением две кнопки звонка без цифр: "Call" и "Frisco office" (красная), "Call" и "Plano office" (с обводкой); рядом кнопка "Request Service". Одна кнопка со своим номером бывает только на странице офиса с полем `call_office`.
- Блока офиса и карты нет: шаблон ставит их только на страницу, которая записана у офиса как его собственная (/plumber-frisco-tx/ и /plumber-plano-tx/).
- Шапка: оба номера (Frisco, потом Plano) на ширине от 1200 px; кнопка Call на этой странице открывает окно "Call the office closest to you" с обоими офисами. В меню оба офиса с адресами и номерами. На телефоне липкая панель звонка с обоими номерами. Подвал общий для всего сайта.
- Первый экран: главным фото встаёт первая картинка текста, то есть то же фото фургона со старого адреса и с тем же alt "FPP Plumbing service van parked outside a home in Celina, TX".
- Отзывы: в тексте стоит метка `<!-- reviews -->`, но для этой страницы в `reviews/site-reviews.json` отзывов нет, поэтому блок отзывов не выводится. Заголовок "What Celina Homeowners Say About FPP Plumbing" и строка "Real Google reviews from local homeowners." записаны в файле страницы, но шаблон их сейчас нигде не выводит (поиск по `site/src/components`, `layouts`, `lib`, `pages` их не нашёл).
- Схема: один бизнес (Plumber) с обоими офисами, как на всём сайте, и узел Service с именем "Plumber in Celina, TX", `serviceType` "Plumbing", поставщиком организацией и `areaServed` Celina. Отдельного бизнеса для города, чужих городов в `areaServed` и `priceRange` на этой странице новый сайт не делает: это уже исправлено самим шаблоном.
- Что осталось от старого текста и спорит с правилами про офис и приезд: "getting to you is rarely the hard part", "most jobs are done the day you call", "same-day service" в описании, последняя строка "Need a plumber in Celina? Call or text us: we’ll show up, fix it, and leave it clean."

### 7.4. Что из этого следует для новой страницы

- Блока офиса, карты, адреса и своего телефона у страницы Celina быть не должно. Кнопки остаются как есть, пока Денис не назовёт офис. Если он назовёт один офис, решить с ним, ставить ли на первый экран одну кнопку с номером этого офиса, как на страницах офисов, или оставить две.
- В тексте нужна одна честная фраза о том, откуда мы приезжаем в Celina. Писать её можно только после ответа Дениса (какой офис и как его назвать).
- Районы называть только те, где Денис подтвердит работу; про Light Farms решает он (часть 10, вопрос 6).
- Фразу страницы Frisco про то, кто приедет ("the plumber at your door may be Nick, Christopher or Denys"), слово в слово не повторять: она стоит в блоке офиса Frisco.

## 8. Посты и гайды

Файл раздела: `docs/briefs/celina/8-links.md`, вставлен целиком. Заголовок файла: «8. Истории из Celina на сайте и ссылки для страницы Celina».

Рядом лежат и в бриф не вставлены: `8-links-tables.md` (9 КБ, списки Л1 до Л6: десять фото галереи с подписью Celina, Celina в одобренных текстах Word, занятые фразы со ссылкой на главную, что нельзя переносить из гайдов, якоря страницы Frisco, Celina на страницах нового сайта) и `8-links-gsc-celina-queries.md` (13 КБ, запросы Search Console со словом celina на других страницах сайта, запросы страницы Celina по темам услуг, итог двух адресов).
Собрано 3 октября 2026. Только чтение: в проекте ничего не менялось, страница Celina не переписывалась. Рядом два приложения: `8-links-gsc-celina-queries.md` (запросы Search Console со словом Celina по всем страницам и запросы страницы Celina по темам услуг; собрано в первом прогоне этой ночи, я пересчитал, цифры совпадают) и `8-links-tables.md` (длинные списки Л1 до Л6).

### Откуда данные

Живой сайт `source/crawl/pages/*.json` (снимок 30 сентября 2026); новый сайт `site/src/content/pages/**/*.md`, `site/src/design/home-text.json`, шаблоны и переадресации в `site/src/`; тексты Word `source/FPP-*.docx`; диктовки `source/dictation/`; карточки Google `source/gbp-takeout/`; фото `photos/captions.csv`, `photos/captions-en.csv`, `photos/city-changes.md`, `docs/briefs/_shared/`; Search Console `source/gsc/performance-3m|16m/Pages.csv` и `source/gsc/page-query-3m|16m.csv` (3 месяца: 1 июля до 28 сентября 2026; 16 месяцев: 31 мая 2025 до 28 сентября 2026); план `docs/pages-plan.md`; карта ключей `seo/keyword-map.md`; услуги `site/src/design/design.json`.

**Как читать цифры.** Формат: клики / показы / место. «Итог» это строка страницы в `Pages.csv`. «Сумма строк» это сумма строк страницы в `page-query` (Google прячет редкие запросы, она меньше итога); место в ней среднее с весом по показам.

Сама страница Celina для сравнения: `/plumber-celina-tx/` итог 3 мес 0 / 3,125 / 16.12 (за 16 мес то же: все показы пришлись на последние три месяца), сумма строк 80 / 0 / 1,223 / 18.76 (строк / клики / показы / место); старый адрес `/plumber-the-celina-tx/` (с него 301) итог 3 мес 0 / 632 / 19.36, 16 мес 1 / 10,668 / 22.47, сумма строк 16 мес 144 / 0 / 9,225 / 22.79. В плане это группа 3, номер 11: «Старый текст», показы есть, кликов нет, усиливать смело.

### 1. Посты и гайды, где работа была в Celina

**Таких нет.** Ни один из 17 постов и 16 гайдов не рассказывает о работе в Celina и не называет Celina местом истории, ни на живом сайте, ни на новом. Поэтому нет и ни одной замороженной или «осторожной» страницы с историей из Celina.

На чём это стоит:
- В тексте 33 постов и гайдов Celina стоит один раз, в замороженном гайде про главный кран, и это не история (1.1). На остальных страницах живого сайта Celina есть только в меню и в списках городов.
- Search Console: ни один пост и ни один гайд не получил ни одного показа по запросу со словом celina, ни за 3, ни за 16 месяцев. Такие запросы есть только у страницы Celina, главной, Frisco, Plano, slab leak и двух страниц водонагревателей (приложение, таблица А).
- В диктовках Дениса Celina нет. В карточках Google Celina есть в одной записи (20 декабря 2024, чугунная труба в crawl space), но только в перечне городов; место работы не названо.

#### 1.1. Единственный гайд, где названа Celina: главный кран (заморожен)

- URL: `/plumbing-guide/how-to-shut-off-main-water-valve-texas/`
- Title: "How to Turn Off Water to Your House | Main Shut-Off Valve Guide TX"; H1: "How to Turn Off Water to Your House: Main Water Shut-Off Valve Guide for North Texas" (живой и новый сайт одинаково).
- Search Console: итог 3 мес 104 / 9,953 / 7.64, 16 мес 212 / 22,630 / 7.14; сумма строк 3 мес 404 / 4 / 1,224 / 9.85, 16 мес 521 / 6 / 2,194 / 9.68. Запросов с Celina нет.
- Про Celina, под подзаголовком "Where Is the Water Shut-Off Valve in Frisco and Prosper Homes?": "Quick cheat sheet for newer neighborhoods: in Frisco, Prosper, and Celina homes built after 2010-2015, check the garage first". Дальше в оригинале тире и белая панель у водонагревателя или на стене к улице ("Nine times out of ten, your shutoff and PRV are right there."). Общая подсказка, не случай.
- Режим: ЗАМОРОЖЕН (группа 1 плана), текст не трогаем, ссылаться можно. Страница Celina уже ссылается на него, якорь "shut-off guide".

#### 1.2. Вместо историй: два фото одной работы, по границе города это Celina

| Фото | Снято | Слова Дениса (`photos/captions.csv`) | Город | Где стоит | План (`photos/captions-en.csv`) |
|---|---|---|---|---|---|
| 52 | 24 февраля 2025 | «Наружный кран заменен на frost free, в стене» | Celina по границе города (Census TIGER/Line 2025), Денис город не называл | нигде | hose bib, Celina |
| 121 | 24 февраля 2025 | «Замена наружных кранов: слева лопнувший при морозе (burst spigot), справа новый» | так же | нигде | пост `/blog/burst-outside-spigot/`, hose bib, Celina |

До пересчёта по границам у обоих стоял Prosper (`photos/city-changes.md`). Других кадров с Celina в архиве нет, клипов нет. Если Денис подтвердит город и расскажет, что было, это одна строка про уличный кран со ссылкой на hose bib.

Оговорка: пост `/blog/burst-outside-spigot/`, куда записано фото 121, начинается словами "A Plano homeowner called us on a cold morning". Если это та же работа, город в посте или у фото неверен; если другая, подпись в посте не должна выдавать фото за ту работу (вопрос 1). Пост приносит клики: итог 3 мес 16 / 1,721 / 9.3, 16 мес 19 / 2,139 / 8.68, группа 2 плана («Только мелкие правки и ссылки»). Hose bib: 3 мес 2 / 1,575 / 21.26, 16 мес 13 / 7,833 / 37.48.

#### 1.3. Десять старых фото в галерее с подписью Celina

На `/gallery/` (живой и новый сайт) десять фото из пачки `photo_2024-12-24_18-50-35.jpg` ... `18-56-17.jpg`, Celina названа только в alt (дословно в `8-links-tables.md`, Л1). Среди них: главный кран и PRV на вводе; вскрытый гипсокартон у коробки стиральной машины, течь у крана там же и вздувшийся пол у прачечной; два газовых бака по 50 галлонов на чердаке; коммерческий смывной кран; засор сифона; кран и подводка унитаза.

Готовой историей это не считается: файлов нет в `photos/index.csv`, откуда город, не записано, а во всей пачке из 104 фото города в alt разложены почти поровну по всем десяти (от 8 до 15 на город). Только после слова Дениса (вопрос 2). Если подтвердятся, три кадра у стиральной машины ложатся на главную тему страницы «скрытая течь в почти новом доме», а два бака на чердаке на водонагреватели. Оговорки: в одном alt "rough-in plumbing" (прокладка труб в строящемся доме), такой работы в списке услуг FPP нет; "commercial toilet" это коммерческий вызов, в фото и историях он допустим. Галерея: 3 мес 1 / 1,293 / 10.13, 16 мес 1 / 9,588 / 14.16, запросов с Celina нет.

#### 1.4. Случай, который стоит на самой странице Celina

Единственный «случай из Celina» на сайте стоит на самой странице: "We have repaired one right here in Celina where the ground shifted just enough to crack a line under a foundation that was still practically new." (и в FAQ 3). Источника в проекте нет; раздел 1 брифа это уже записал (6.8, 9.7), как и то, что "The Screw Behind the Drywall" это история Дениса про гвоздь со страницы Frisco.

### 2. Что про Celina сказано на страницах услуг и других страницах

Ни случая, ни числа про Celina нет. На новом сайте Celina стоит одной фразой в тексте четырёх страниц услуг (emergency, slab leak, leak detection, water lines), в «Where We Work» и FAQ главной и в двух списках городов (contact, страница expansion tank). Везде Celina в паре с Prosper как город новых домов: "where the leak is usually somebody else’s workmanship" (leak detection), "meets young lines with shallow trenching and connections that were rushed" (water lines). Дословно все фразы в Л6.

Одобренные тексты Word для sewer line, drain cleaning, faucet and shower valve и hose bib (ещё не на сайте) держат по одной фразе с "plumber in Celina": провисания и разошедшиеся стыки от оседающей засыпки, медленная мойка в новом доме, картриджи от застройщика, которые сдают на третий год, обычный кран там, где застройщику надо было ставить frost free (дословно в Л2). Общая линия сайта совпадает с текущей страницей ("Celina is almost entirely new construction"). Это общие фразы, не случаи: слово в слово на странице Celina их не повторять, конкретику брать только из диктовки Дениса.

**Search Console** (приложение, таблицы А и Б). Запросы «услуга плюс Celina» страницам услуг почти не достаются: за 16 месяцев slab leak 68 показов ("slab leak repair celina, tx", место 37.4), страницы водонагревателей 10 показов, остальные ни одного. Основную массу собирает сама Celina (оба адреса, 16 мес): водонагреватели 1,419 показов, drain 180, emergency 175, leak detection 117, slab leak 112, toilet 96, sewer 79, faucet 57, pipe 37, disposal 9; hose bib, PRV и expansion tank ни одного. (Пояснение проверки: темы здесь собраны шире, чем в части 2, раздел 7. В 1,419 вошли "heating replacement celina" 59, "heating maintenance celina" 20 и "pool heater repair celina tx" 2, это не наши услуги; чистая цифра запросов водонагревателя с celina 1,338, как в части 2. В emergency 175 вошёл "burst pipe repair celina texas" 53, в leak detection 117 вошёл "leak repair celina texas" 58; в части 2 они в других группах.)

По главному запросу Frisco стоит выше самой Celina. За 3 месяца "plumber celina": Frisco 16 показов, место 1.56; Celina 73 показа, место 22.82. "plumber celina tx": Frisco 1 клик, 11 показов, место 3.91; Celina 20 показов, место 23.5. (Пояснение проверки: здесь у Celina только живой адрес; с двумя адресами, как в части 2, «plumber celina» 130 показов на месте 24.5 и «plumber celina tx» 34 на месте 24.2, `source/gsc/page-query-3m.csv`.) Города друг на друга не ссылаются, поэтому ссылками Celina помогают только услуги (якорь "plumber in Celina"), главная и навигация.

### 3. На что должна ссылаться страница Celina и с какими якорями

#### 3.1. Главная: одна ссылка

Правило 6: один раз, в последнем абзаце вступления, якорь ровно "plumber near me", своя фраза у каждой страницы. Сейчас: "Searched for a [plumber near me](/) and ended up here? That is the whole promise, plus a straight answer when something can safely wait." Место и якорь верные, но так же начинаются фразы на Allen и garbage disposal, и это вопрос в начале мысли (правило голоса). Нужна новая фраза; занятые формулировки в Л3.

#### 3.2. Все 13 услуг

Сейчас в тексте 11 из 13: нет hose bib и expansion tank. Якорь по образцу Frisco это имя услуги из меню. Карта ключей запрещает странице Celina "water heater repair" и "plumber near me": водонагреватели здесь это блок с местными фактами и ссылкой, без разбора ремонта.

| № | Услуга (меню) | URL | Якорь сейчас | Предлагаемый якорь | Где встаёт | Запросы с Celina у страницы Celina, 16 мес (строк / показы) |
|---|---|---|---|---|---|---|
| 1 | Emergency plumbing | `/emergency-plumbing-services/` | "emergency plumbing" | "emergency plumbing" | «если течёт прямо сейчас» | 5 / 175 |
| 2 | Slab leak repair | `/slab-leak-repair-frisco-plano-mckinney/` | "slab leak repair" (2) | "slab leak repair" | один короткий абзац не в начале (правило городов) | 1 / 112 |
| 3 | Water leak detection | `/water-leak-detection-frisco-plano/` | "leak detection" (2) | "water leak detection" | скрытая течь в стене нового дома | 2 / 117 |
| 4 | Sewer line repair and camera inspection | `/drain-services/` | "main line service" | "sewer line repair and camera inspection" | главная канализационная линия | 3 / 79 |
| 5 | Drain cleaning | `/clogged-drain-cleaning-frisco-plano/` | "drain cleaning" | "drain cleaning" | засоры | 4 / 180 |
| 6 | Water heater repair and replacement | `/water-heaters/` | "water heater repair" (2) | "water heater repair and replacement" | водонагреватели | 16 / 1,419 (с "heating" и "pool heater"; без них 1,338) |
| 7 | Expansion tank replacement | `/water-heater-repair-frisco-mckinney/` | нет | "expansion tank replacement" | рядом с водонагревателями | нет |
| 8 | Faucet and shower valve repair | `/fixture-installation-repair/` | "shower valve repair" | "faucet and shower valve repair" | картриджи, которые сдают рано | 2 / 57 |
| 9 | Hose bib repair | `/hose-bib-repair-frisco-plano/` | нет | "hose bib repair" | уличный кран (фото 52, 121 после слова Дениса) | нет |
| 10 | Garbage disposal repair | `/garbage-disposal-repair-frisco-plano/` | "garbage disposal repair" | "garbage disposal repair" | строка про измельчители | 2 / 9 |
| 11 | Water line repair | `/water-lines/` | "water line repair" | "water line repair" | мокрый газон, крутится счётчик | 1 / 37 ("pipe repair") |
| 12 | Toilet repair | `/toilet-repair-frisco-plano/` | "toilet repair" | "toilet repair" | строка про унитазы | 2 / 96 |
| 13 | PRV replacement | `/prv-replacement-frisco-plano/` | "PRV replacement" | "PRV replacement" | давление, совет Дениса про 80 PSI | нет |

Правило «что ранжируется, остаётся»: я проверил якоря, которые предлагаю заменить. По "main line" и "shower valve" у страницы Celina нет ни одного запроса ни за 3, ни за 16 месяцев, замена безопасна. По "faucet" за 16 месяцев есть "faucet repair celina texas" (51 показ, место 15.7): довод за якорь со словом faucet. Остальные якоря и так совпадают с именем услуги.

Про мороз по правилу Дениса: капать оставляют краны в доме; уличный frost free кран при правильной установке не мёрзнет, ему нужен только чехол.

#### 3.3. Посты и гайды: что подходит по теме

Своих историй нет. Ниже гайды и посты без чужого города в адресе, title и H1, которые ложатся на темы страницы. Якорь описывает тему, не услугу и не "plumber in Celina"; якоря Frisco на те же гайды заняты (Л5). А: ставить в любом случае; Б: если на странице есть абзац на эту тему; В: по желанию или после слова Дениса.

| Важность | Страница | Итог 3 мес | Итог 16 мес | Режим | Предлагаемый якорь | Где встаёт |
|---|---|---|---|---|---|---|
| А | `/plumbing-guide/how-to-shut-off-main-water-valve-texas/` | 104 / 9,953 / 7.64 | 212 / 22,630 / 7.14 | ЗАМОРОЖЕН | "where the main shut-off sits in a newer house" (сейчас "shut-off guide", как у The Colony) | «если течёт прямо сейчас»; гайд сам называет Celina |
| А | `/plumbing-guide/automatic-water-shut-off-valve-install-north-texas/` | 28 / 2,651 / 7.73 | 30 / 2,742 / 7.75 | приносит клики | "a valve that closes the main line when it senses water" | скрытая течь; в гайде раздел "The Easy Case: Newer Homes (2010 to 2015 and Up)" |
| Б | `/plumbing-guide/water-heater-making-noise-tips-2026/` | 0 / 10 / 5.9 | 0 / 91 / 22.55 | обычная | "what the popping and rumbling in a tank means" | водонагреватели (на странице уже есть "popping and rumbling from sediment") |
| Б | `/plumbing-guide/how-long-do-water-heaters-last-guide/` | 1 / 221 / 14.56 | 2 / 663 / 10.8 | обычная | "the usual service life of a tank heater" | водонагреватели |
| Б | `/plumbing-guide/water-pressure-dropping-tips-2026/` | 2 / 893 / 13.94 | 4 / 1,653 / 11.15 | обычная | "why house water pressure drops" | рядом с PRV |
| В | `/blog/burst-outside-spigot/` | 16 / 1,721 / 9.3 | 19 / 2,139 / 8.68 | приносит клики | "a frost free spigot that split inside the wall" | уличный кран, только после ответа на вопрос 1 |
| В | `/plumbing-guide/pressure-reducing-valve-replacement-guide-2026/` | 0 / 64 / 10.69 | 4 / 1,439 / 9.93 | обычная | "how a pressure reducing valve wears out" | рядом с PRV, если нужна вторая ссылка |
| В | `/gallery/` | 1 / 1,293 / 10.13 | 1 / 9,588 / 14.16 | обычная | "photos from our jobs" | только если Денис подтвердит город десяти фото |

Из этих страниц на страницу Celina переносится только ссылка: внутри tankless, цены, reroute, ссылки на сайт компании по сушке и история из Plano (что где, в Л4).

#### 3.4. На что страница Celina не ссылается

- На другие города (правило 7). Сейчас в тексте их нет ни ссылкой, ни названием (Frisco, Plano, McKinney только внутри адресов услуг). Так и оставить.
- На посты и гайды с другим городом в адресе, title или H1 (`.../water-leak-after-bathroom-remodel-frisco-tx/`, `.../why-is-my-water-bill-so-high-frisco-tx/`, `.../slab-leak-repair-plano-tips-2026/`, посты с Frisco, Plano, Little Elm в названии, `/top-emergency-plumber-calls-frisco/`).
- На гайд `/plumbing-guide/plumber-near-me-north-texas-guide-to-avoid-scams/` (якорь "plumber near me" принадлежит главной) и на гайды с ценами (`emergency-plumbing-repair-cost-guide-2026`, `water-heater-replacement-cost-2026`): на странице города только $49.

#### 3.5. Внешняя ссылка на официальный источник

Нужна одна, по образцу Frisco (там страница города про регистрацию подрядчиков). Сейчас её нет ни на живой, ни на новой странице Celina. Адрес ищет раздел 6a. (Дополнение проверки: раздел 6a нашёл три адреса, часть 6, 6.1, «Что годится для одной ссылки»: https://www.celina-tx.gov/1985/Contractor-Registration , https://www.celina-tx.gov/1884/Frequently-Asked-Questions , https://www.celina-tx.gov/1920/Winter-Weather-Preparedness ; все три открыты заново 3 октября около 11:00, ответ 200, цитаты на месте.)

### 4. Кто уже ссылается на `/plumber-celina-tx/` на новом сайте

В файлах страниц 6 ссылок из 6 файлов (совпадает с Т3 раздела 1):

| Откуда | Якорь | Как стоит |
|---|---|---|
| `/emergency-plumbing-services/` | "plumber in Celina" | в тексте, с McKinney, Allen, Prosper |
| `/slab-leak-repair-frisco-plano-mckinney/` | "plumber in Celina" | в тексте, с Allen, Prosper |
| `/water-leak-detection-frisco-plano/` | "plumber in Celina" | в тексте, с Allen, Prosper |
| `/water-lines/` | "plumber in Celina" | в тексте, с Prosper |
| `/water-heater-repair-frisco-mckinney/` | "Celina" | голый список городов |
| `/contact/` | "Celina, TX" | список "Areas We Serve in the North Dallas Suburbs" |

Кроме файлов страниц:
- Главная: "plumber in Celina" в «Where We Work», карта (aria-label "Plumber in Celina") и ряд городов под картой: три ссылки по решению Дениса.
- Шаблоны на каждой странице: шапка (Areas), Menu (Cities), подвал (Areas), якорь "Celina".
- Переадресации 301: `/plumber-the-celina-tx/` и три адреса вложений под `/plumber-celina-tx/`.
- Посты и гайды на Celina не ссылаются; так и должно быть, пока нет истории из Celina.

**Чего не хватает** (правки других страниц, в их очередь):
- Восемь страниц услуг не ссылаются на Celina в тексте, хотя услуга ссылается на все десять городов: `/water-heaters/`, `/drain-services/`, `/clogged-drain-cleaning-frisco-plano/`, `/fixture-installation-repair/`, `/hose-bib-repair-frisco-plano/`, `/garbage-disposal-repair-frisco-plano/`, `/toilet-repair-frisco-plano/`, `/prv-replacement-frisco-plano/`. Четыре закроются сами, когда встанут одобренные тексты Word (sewer, drain cleaning, faucet, hose bib). Останутся `/water-heaters/`, garbage disposal, toilet, PRV.
- `/water-heater-repair-frisco-mckinney/` ссылается голым списком "Celina"; правило 7 просит "plumber in Celina" внутри предложения.

### 5. Расхождения с правилами, найденные по дороге

Ничего не исправлено, это список для тех, кто пишет страницу и правит другие.

1. Фото 121 записано в пост про лопнувший уличный кран, а пост называет Plano; по границе фото это Celina, слова Дениса о городе нет.
2. В `docs/briefs/_shared/photos-by-city-after-recount.json` у фото 52 и 121 город после пересчёта Celina, но подпись и план страниц там старые (Prosper, `/plumber-prosper-tx/`). Верный план в `photos/captions-en.csv`. Брифу Prosper эти фото не брать.
3. Галерея: alt с "rough-in plumbing" (такой работы в списке услуг нет); города в alt всей пачки из 104 фото не подтверждены.
4. `/water-lines/`: "Rerouting costs more once and ends it." (reroute не предлагаем, уже записано в брифе Plano) и пропущен пробел: "[plumber in Prosper](/plumber-prosper-tx/)or".
5. Замороженный гайд про главный кран: в фразе про Celina тире, в другом разделе назван Richardson. Не трогаем и не переносим.

### 6. Вопросы к Денису (то, что знает только он)

1. Фото 52 и 121, 24 февраля 2025: наружный кран заменён на frost free, рядом лопнувший при морозе. По месту съёмки это Celina. Это работа в Celina? Тот же вызов, что в посте про лопнувший уличный кран, где написано "A Plano homeowner"? Если Celina: что там было (какой кран стоял, оставили ли шланг, куда пошла вода), чтобы дать одну строку на странице Celina.
2. Десять фото в галерее с подписью Celina (главный кран и PRV на вводе, течь у коробки стиральной машины и вздувшийся пол, два газовых бака по 50 галлонов на чердаке и другие): это правда работы в Celina? И что за «rough-in plumbing» на одном из них, такую работу вы делаете?
3. Slab leak в почти новом доме в Celina, который сейчас стоит на странице: такая работа была? Две-три фразы, что случилось.
4. Своих историй из Celina на сайте нет ни одной. Вспомните одну или две работы в Celina, которые можно рассказать (водонагреватель, течь в стене нового дома, давление, уличный кран, засор). Без этого страница Celina остаётся без единого случая.

## 9. Чем Celina отличается от Frisco и Plano

Только то, что подтверждено данными Search Console из части 2 или официальной страницей из части 6. У каждого пункта назван источник. Это для автора: на самой странице Celina соседние города не называются и не сравниваются. Подтверждённых пунктов четыре: официальные правила города Celina (часть 6) в файлах этого брифа с правилами Frisco и Plano не сравнивались, поэтому отдельным пунктом здесь не стоят.

1. **Страница без кликов, и её история лежит на старом адресе.** Celina за 3 месяца: 0 кликов, 3,125 показов на месте 16.12 на живом адресе и ещё 632 показа на месте 19.36 на старом /plumber-the-celina-tx/. Frisco: 42 клика, 44,080 показов, место 15.2. Plano: 98 кликов, 56,197 показов, место 6.77. За 16 месяцев: Celina 1 клик (старый адрес) и 13,793 показа на двух адресах, Frisco 110 кликов и 128,850 показов, Plano 103 клика и 108,268 показов. Значит, здесь нет кликов, которые можно потерять: задача страницы подняться к первой странице Google, а правило «что держит показы, остаётся» всё равно действует (начала title и H1, слова водонагревателя в title, два H2). 301 со старого адреса держать одной ступенью. Источник: `source/gsc/performance-3m/Pages.csv` и `performance-16m/Pages.csv` (та же выгрузка, что в части 2), часть 2, раздел 1.
2. **По главному запросу Celina выше стоит страница Frisco.** «plumber celina»: Frisco 16 показов на месте 1.6, Celina 130 показов на месте 24.5; «plumber celina tx»: Frisco 11 показов на месте 3.9 и 1 клик, Plano 1 показ на месте 1.0 и 1 клик, Celina 34 показа на месте 24.2 и 0 кликов; «water heater repair celina»: Frisco 10 показов на месте 1.0, Celina 65 на месте 19.3 (всё за 3 месяца). Оба клика сайта по запросам с celina пришли на Frisco и Plano. Своей карточки Google у Celina нет, а карточки офисов ведут на страницы Frisco и Plano; похоже, показы Frisco идут через карточку, но выгрузка это не делит. Для текста это значит: страница Celina может подняться только текстом и ссылками (название города и «plumber in Celina» в тексте и в части H2, ссылки со страниц услуг с якорем "plumber in Celina"), города друг на друга не ссылаются. Источник: часть 2, раздел 6, и `celina-gsc-extra.md`, таблица B.
3. **Самое молодое жильё из трёх, но немного старого есть.** Медианный год постройки жилья: Celina 2015 (±2), Frisco 2009 (±1), Plano 1993 (±2). Построено в 2010 году и позже: 65.6%, 46.7% и 13.7%; в 2020 году и позже: 32.4%, 6.7% и 1.8%. При этом доля жилья старше 1980 года в Celina (7.5%, с большой погрешностью) выше, чем во Frisco (1.5%), и ниже, чем в Plano (18.4%). Истории про старые трубы для Celina не типичны, но и не исключены; что Денис видит на вызовах, главнее статистики. Источник: U.S. Census Bureau, American Community Survey 2020-2024, таблицы B25035 и B25034 (часть 6, проверка индексов, строки age-celina, age-frisco, age-plano, cmp-1).
4. **Город растёт быстрее любого города США своего размера.** По оценке Census Bureau (Vintage 2025, пресс-релиз CB26-80 от 14 мая 2026) Celina самый быстрорастущий город страны среди городов от 20,000 жителей: +24.6% за год до 1 июля 2025 года, 64,427 жителей; самым быстрорастущим он был и в 2023 году. Frisco и Plano тоже города больше 20,000 жителей, значит, они росли медленнее. Таблицы ACS 2020-2024 из пункта 3 от сегодняшнего города отстают: домов больше, и они новее. Источник: часть 6, проверка индексов, строка pop-1, https://www.census.gov/newsroom/press-releases/2026/vintage-2025-city-town-pop-estimates.html .

## 10. Вопросы к Денису и нужные фото

Только то, что знает он один. Собрано из вопросов разделов и частей 4 и 7, без повторов. Вопрос про регистрацию FPP в Celina сюда не входит: Денис закрыл его 3 октября (компания зарегистрирована во всех городах, где работает).

### 10.1. Вопросы

1. **Офис.** Из какого офиса обслуживается Celina, Frisco или Plano? Как это писать на странице: назвать офис по имени ("our Frisco office", без ссылки) или без названия города? По правилам страница города соседей не называет. И на первом экране оставить две кнопки звонка, как сейчас, или одну с номером этого офиса?
2. **С чем звонят в Celina.** Правда ли то, что пишет старая страница: водонагреватели звонят чаще всего остального вместе? Что ещё ломается в домах Celina (детали от застройщика, наполнительные клапаны, измельчители, картриджи душа)? Бывают ли вызовы в старые дома (по Census около 7% жилья города старше 1980 года), в дома с колодцем или септиком, и берёте ли такие? Оставляем ли фразу "Celina is almost entirely new construction"?
3. **Title и слова страницы.** Оставить в title "Water Heater Repair & Replacement" (эти слова одни держат 1,132 показа за 16 месяцев, а карта ключей отдаёт тему страницам водонагревателей), заменить один к одному (чем?) или отдать тему страницам водонагревателей? Можно ли поставить одно предложение с "emergency plumber in Celina" и ссылкой на страницу emergency, как на Frisco? Оставить ли в описании "same-day service"?
4. **Истории из Celina.** Был ли slab leak в почти новом доме в Celina, о котором пишет страница (грунт сдвинулся, треснула линия под фундаментом)? Если был, две или три фразы: год дома, как нашли, как чинили. Видели ли вы в Celina шуруп или гвоздь от полки в водяной линии, или это история только для Frisco и для страницы поиска утечек? Вспомните одну или две работы в Celina, которые можно рассказать с фото (водонагреватель, течь в стене нового дома, давление, уличный кран, засор): на сайте нет ни одной истории из Celina.
5. **Фото 52 и 121** (24 февраля 2025: лопнувший в мороз уличный кран и новый frost free в стене). По месту съёмки это Celina. Это работа в Celina? Тот же ли это вызов, что в посте про лопнувший уличный кран, где написано "A Plano homeowner"? Что там было: какой кран стоял, обычный или frost free, оставили ли шланг, куда пошла вода?
6. **Районы и индексы.** В каких районах Celina вы реально работали: Light Farms, Mustang Lakes, Sutton Fields, Glen Crossing, другие? Light Farms по карте города вне его полных границ (ETJ), хотя почтовый адрес там Celina: считаем его Celina, как Paloma Creek для Little Elm, и называем ли на странице? Если там нужно разрешение (например, на водонагреватель), кто его выдаёт и кто инспектирует? Какие индексы стоят в адресах ваших вызовов в Celina: только 75009 или бывают 75078, 76227, 76258? Показывать ли индекс на странице?
7. **Давление и вода.** Что обычно показывает манометр в домах Celina, и где там стоит PRV? Видите ли вы в Celina накипь и изношенные картриджи чаще, чем в других городах, и упоминать ли умягчитель (Aquasana вы ставите иногда)? Есть ли у вас свой замер жёсткости в Celina (официальной цифры нет ни у города, ни у UTRWD)?
8. **Разрешения на практике.** На что смотрит инспектор Celina при замене водонагревателя? Берёте ли в Celina разрешение на замену PRV, на ремонт линии от счётчика, на точечный ремонт канализации, на ремонт течи под плитой (город отдельно этого не пишет)? Правда ли, что водонагреватели обычных размеров едут в фургоне и ставятся в день звонка, как написано на старой странице?
9. **Гарантия застройщика и фото.** Оставляем ли обещание из FAQ: фото поломки и описание для претензии к застройщику? И фразу "we photograph everything" (по CLAUDE.md фотографируют большие работы, фото и видео по просьбе)?
10. **Отзывы.** Ни один отзыв не называет Celina. Были ли в Celina работы у кого-то из кандидатов (alex p, Kevin N., Rob C. и другие) или у David Faidley с живой страницы? Если нет, строку над отзывами "What Celina Homeowners Say" делаем нейтральной? P M и J L с живой страницы называют вас по имени: снимаем обоих или J L оставляем как исключение (единственный отзыв про кран ледогенератора)? Можно ли на странице города отзыв Rob C. про систему фильтрации в новом доме и отзыв Aaron M. со словом warranty (его домашняя гарантия, не наша)?
11. **Главное фото и фургон.** Фото фургона на живой странице снято в Celina? Что значит "M-38532" на крыле фургона (на сайте лицензия M-44816)? Пока нет кадра из Celina, ставим фото 2 или фото 4 (фургон у офиса Frisco), как вы разрешили 1 октября?
12. **Галерея.** Десять старых фото галереи с подписью Celina (главный кран и PRV на вводе, течь у коробки стиральной машины и вздувшийся пол, два газовых бака по 50 галлонов на чердаке и другие): это правда работы в Celina? И что за "rough-in plumbing" на одном из них: такую работу вы делаете?

Мелкие вопросы, которые остались в разделах и в двенадцать не вошли: ставить ли на страницу цифры города (разрешение на сантехнику, пересчёт счёта; по правилам на странице только наши $49, так что, скорее всего, нет; часть 6, файл фактов города, вопрос 3); ключ Census API для повторных запросов требует регистрации с почтой Дениса (часть 6, файл индексов), для брифа он не нужен.

### 10.2. Какие фото просить

Подробно в части 4.3. Коротко, по порядку важности:

1. Настоящее фото с работы в Celina или фургон FPP на улице в черте города (вертикальный кадр, без номеров домов).
2. Если работа с уличным краном (фото 121 и 52) была в Celina: кадр крупнее, лопнувшее место и новый кран с чехлом.
3. Водонагреватель в доме в Celina, «до» и «после»: поддон и слив, сброс T&P, закреплённый расширительный бак.
4. Скрытая течь в молодом доме в Celina: вскрытая стена, место течи.
5. Манометр на уличном кране с цифрой давления и PRV.
6. Ящик счётчика: кран города и отдельный кран хозяина у дома.
7. Slab leak в почти новом доме в Celina, если такая работа была.
8. Наполнительный клапан, измельчитель или картридж душа с работы в Celina, «до» и «после».
