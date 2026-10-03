# Бриф страницы McKinney (3 октября 2026)

Страница: /plumber-mckinney-tx/ . Собрано 3 октября 2026 из файлов разделов в папке `docs/briefs/mckinney/`. Страница этой ночью не переписывалась: текст напишет другой чат из этого брифа и из диктовки Дениса. В проекте ничего не менялось, кроме этого нового файла.

Как устроен файл. Части 1, 2, 3, 5, 6 и 8 это файлы разделов, вставленные целиком скриптом, слово в слово: первая строка файла (его заголовок) названа в начале части, остальные заголовки опущены на уровень ниже, в части 6 на два уровня, потому что там четыре файла. Части «Коротко», 4, 7, 9 и 10 написаны при сборке. Читать стоит «Коротко», потом части 9 и 10, остальное открывать по делу.

Оговорки к вставленным файлам:

- Слова «рядом» и «файл таблиц» во вставленных текстах значат папку `docs/briefs/mckinney/`. Длинные таблицы в бриф не вставлены: их имена названы в начале каждой части.
- Номера разделов внутри вставленных файлов («раздел 6a», «пункт 6», «вопрос 3», «Т7») относятся к самому файлу или к его приложению, не к частям брифа.
- Часть 6. Файлы фактов писались первыми, перепроверка шла после них. Где они расходятся, верить спискам 6.0 и таблицам проверки (6.3 и 6.4). Расхождения перечислены в начале части 6.
- После того как файлы разделов были написаны, в CLAUDE.md стоят решения Дениса от 3 октября 2026. Они главнее вставленного текста. Первое: регистрация. Компания зарегистрирована во всех городах, где работает, вопрос закрыт, списки подрядчиков не проверяются (раздел 6a их и не проверял). Второе: город фото определяется по черте города, а не по ближайшему центру; кадр в черте другого обслуживаемого города берёт этот город, город, который назвал Денис, проверка не меняет. Поэтому спор, который части 1 и 8 видят у клипов 180, 190 и 191 (в `docs/pages-plan.md`, файл от 04:53, записано «по месту съёмки Prosper» и «Allen»), решён в пользу McKinney: эти записи плана сделаны старым способом, а `photos/captions-en.csv` (10:23) уже пишет McKinney. Денис эти работы не называл, но спрашивать его нужно, только если он помнит город (часть 10). Третье: отзыв Google, скопированный на Thumbtack, берётся из строки Google.
- Часть 1, раздел 7, говорит, что граница «from the meter to the house is yours» официальной страницей не проверена. Её проверил раздел 6a (city-d1, d2, подтверждено): фраза живой страницы с городом совпадает.
- Часть 1, раздел 4: «В архиве 21 номер с городом McKinney». Это строки `photos/captions-en.csv`; в общем файле пересчёта их 23, ещё два клипа (13 и 14) без подписи. Подробно в части 4.
- Часть 8, раздел 2, просит раздел 6a проверить слова гида про счёт за воду («McKinney ... automatically send alerts»). Раздел 6a этого не делал. При сборке найдено в сохранённом тексте страницы города (`docs/briefs/mckinney/work-6a/meters-leaks-pipes.txt`, https://www.mckinneytexas.org/2284/Meters-Leaks-Pipes , прочитана 3 октября 2026): "My Water Advisor® 2.0 ... Get text and email alerts to identify leaks and high water usage." и "Opt-in to receive alert notifications". То есть оповещения есть, но по подписке клиента, не «автоматически». Вторую проверку эта находка не проходила.
- Координат, адресов клиентов и телефонов клиентов во вставленных файлах нет (проверено поиском при сборке). Адреса почтовых отделений в части 6 (550 N Central Expy, 7210 Virginia Pkwy Ste 100, а в таблице индексов и 1919 E Melissa Rd, отделение чужого индекса 75454; это название на сайте не пишется) и адреса здания города (401 E. Virginia Street, старый 221 N. Tennessee) это открытые адреса почты и города. Телефоны в части 6.1 (469-617-4800, 972-547-7360) это телефоны города; номера 980-899-7997 и 469-998-8999 это номера FPP. На страницу ни один номер в текст не ставится (правило 10).
- Отзывы в частях 1 и 5 даны дословно, с опечатками авторов; цифры приезда в них это слова клиентов, по решению Дениса их не трогаем.
- Несколько файлов разделов чуть больше 25 КБ (1, 2, 3, 5 и четыре файла части 6 от 25.5 до 27.5 КБ, 8 около 35 КБ): так их написали помощники, длинные таблицы они вынесли в отдельные файлы.

Проверка критиком (3 октября 2026, около 12:00). Бриф пройден по десяти пунктам задания: все десять частей на месте. Сверено с источниками заново:

- Search Console (`source/gsc/page-query-3m.csv`, `page-query-16m.csv`, `performance-*/Pages.csv`): итоги McKinney 472 · 27.19 · 0 и 20,833 · 61.33 · 1; Frisco 42 клика и 44,080 показов, Plano 98 и 56,197 за 3 месяца; 40 и 171 запрос (319 и 19,500 показов); «low water pressure plumber mckinney» 580 · 33.75; «garbage disposal repair near me» 46 · 5.74; «plumber mckinney tx» у Frisco 98 · 17.93, у Plano 75 · 17.29, у McKinney 2 · 59; главная по mckinney 99 запросов, 9,417 показов. Всё совпало.
- Краул: title, описание, H1, все H2, шесть вопросов FAQ, 1,891 слово, даты 16 мая 2025 и 17 августа 2026, схема (Fairview, Melissa, Allen, Prosper, "North Dallas", второй бизнес с адресом Frisco). Совпало. Все цитаты частей 1 и 6.2 о живой странице стоят и в крауле, и в `site/src/content/pages/plumber-mckinney-tx.md`.
- Отзывы: тексты десяти кандидатов и трёх отзывов живой страницы совпали с `reviews/all-reviews.csv`; ни одного из десяти нет в `reviews/site-reviews.json` (10:04) и ни у одного нет старой страницы; ни один не называет город; Thumbtack кандидатов это настоящие заказы, не копии Google.
- Census заново (data.census.gov, ACSDT5Y2024): McKinney city B25035 2007 (±1); B25034: до 1980 года 6,092 из 77,617 (7.8%), 1939 и раньше 1,128 (±356), 2000 и позже 72.8%. Совпало.
- Город заново, по одному запросу: https://www.mckinneytexas.org/2284/Meters-Leaks-Pipes (кредит "as a courtesy", "$150.00", "12-month period", "60 days", "faucet insulator", "Get text and email alerts...", "Opt-in to receive alert notifications"), https://www.mckinneytexas.org/257/Contractor-Registration ("No registration fee", "follows the individual no matter what company they work for"), https://www.mckinneytexas.org/350/Historic-Preservation-Resources (цитата про два исторических района). Всё на месте, ответ 200.
- Конкуренты: десять файлов в `source/competitors/2026-10-03-mckinney/`, первая строка каждого адрес из таблицы; title JMP, его вопрос FAQ, "$86", "14 to 16 grains per gallon", у Legacy "67 percent being built after 2000", "more than 14,000 copper water service lines", "200,000-plus residents" стоят в сохранённых текстах.
- Фото: 21 строка McKinney в `photos/captions-en.csv` плюс клипы 13 и 14, всего 23; страницы из колонки pages совпали; 99 и 141 стоят на главной и на своих страницах услуг. Факты Plano в части 9 совпали с `docs/plano-brief-2026-10-03.md`.
- Исправлено: в части 8 (раздел 2) слова "working with me to satisfy permit requirements for city of mckinney" были приписаны LXD Properties, это отзыв Ezzy Zhoo. В частях 1, 6.1, 6.2 и 8 у устаревших мест, которые поправила проверка или сборка, стоят пометки в квадратных скобках прямо в тексте. В часть 1 добавлены 16 ссылок текста с якорями и главные цитаты Т9.
- Длинных и коротких тире, координат, адресов и телефонов клиентов в брифе нет; адреса и телефоны в нём это офисы FPP, почта и город.

## Коротко

1. Что кормит страницу. Почти ничего. За 3 месяца (1 июля до 28 сентября 2026) 0 кликов, 472 показа, среднее место 27.19; за 16 месяцев 1 клик (запрос скрыт), 20,833 показа, место 61.33 (`source/gsc`, Pages.csv). Показы почти пропали: 20,361 за 13 месяцев до июля против 472 за последние 3; так же упали все запросы с mckinney на сайте (61,658 за 16 месяцев, 910 за 3). Почему, по выгрузке не видно. По показам за 3 месяца это последняя из десяти городских страниц.
2. По каким запросам. За 3 месяца первые: «garbage disposal repair near me» 46 показов на месте 5.7, «slab leak plumber near me» 45 на 7.7, «slab leak plumber mckinney» 26 на 14.8, «fpp plumbing» 20 на 1.9, «plumber mckinney» 14 на 49.1. За 16 месяцев: «plumber in mckinney» 1,431 на 59.1, «plumber mckinney» 1,343 на 45.7, «slab leak repair mckinney» 711 на 62.1, «low water pressure plumber mckinney» 580 на 33.8 (лучший большой запрос страницы, а слова low на ней нет). 96 процентов показов за 16 месяцев идут по запросам с mckinney, но на местах 1 до 3 нет ни одного.
3. Что нельзя потерять (часть 2, раздел 4): начало title "Plumber in McKinney, TX" (только там стоят точные «plumber in mckinney» и «plumber in mckinney tx»); "Licensed McKinney plumbers" в описании; H1 "Plumbing Repair in McKinney, TX"; H2 "Our Plumbing Services in McKinney"; H2 "Main Water Line Repair in Older McKinney Homes" (один держит четыре запроса water line repair с mckinney, 1,416 показов за 16 месяцев); H2 "McKinney Plumbing FAQ"; имя "FPP Plumbing"; "Garbage Disposal Repair" в title (лучшие места страницы за 3 месяца). Фразы «plumber in McKinney» в H1, описании, тексте и H2 нет: по правилу городских страниц её надо поставить во вступление, первый блок, последний абзац и в часть H2.
4. Кто ещё берёт показы. За 3 месяца по главному ключу «plumber mckinney tx» выше стоят страницы Frisco (98 показов, место 17.9) и Plano (75, место 17.3), сама McKinney 2 показа на месте 59. Slab leak с mckinney держит страница slab leak (10,363 показа на 32.4 против 2,382 на 61.1 за 16 месяцев), emergency с mckinney держит главная (6,744 на 48.7). По water line, faucet, toilet и low water pressure с mckinney страница McKinney сильнее страниц-хозяев по карте ключей. Запросов с чужими городами нет.
5. Что на живой странице против правил: title, H1, первый H2 "Slab Leak Repair in McKinney" и вопросы FAQ 1 и 5 целятся в «slab leak repair mckinney», который карта ключей этой странице запрещает; раздел про измельчители и FAQ 2 и 3 это глубина страницы disposal (138 общих слов); фразы "has the full pricing" и "what the options cost" ведут к ценам вне правил ($229, $400-500, «three to six thousand dollars»); "tired of four hour windows" и "a licensed plumber who arrives inside it"; шесть вопросов FAQ тегом H3, вопросы 4 и 6 шаблон, вопрос 4 слово в слово как у конкурента JMP; ссылка на главную во втором абзаце, начало фразы как на четырёх других городах; нет ссылок на hose bib и expansion tank; нет официальной ссылки; пропущен пробел "guidecovers". В схеме Fairview и Melissa, соседи Allen и Prosper, "North Dallas communities", "Texas Master Plumber License M-44816", второй бизнес с адресом и телефоном офиса Frisco, priceRange "$$". Новый сайт поправил только тире в H1 и поставил метку отзывов; второго бизнеса и чужих городов в его схеме этой страницы нет (так строит шаблон, `site/src/lib/schema.ts`), весь текст старый.
6. Объём и содержание. Своего текста 1,561 слово, до отметки 2,500 не хватает около 940. Ни одного фото с работы, нет блока Дениса и заключения; единственный случай с вызова (дерево вросло в медную линию) ничем не подтверждён и почти теми же словами стоит на /water-lines/. Главное фото это фургон из общей серии снимков, город не подтверждён, на крыле "M-38532", на борту телефон Plano.
7. Конкуренты: десять страниц по «plumber mckinney tx», «plumber in mckinney», «mckinney plumbing» (Semrush, 3 октября 2026): Baker Brothers, Bewley, Milestone, Cr Plumbing, Roto-Rooter, JMP, Legacy, Hackler, Jimmy Cash's, Genzel. Шесть из десяти это главные страницы местных фирм, офис в McKinney у восьми. Основной текст от 449 до 3,121 слова, середина около 1,100; FAQ у трёх; срок гарантии не называет никто; цены в цифрах только у JMP; на mckinneytexas.org ссылается только Legacy. Нашего сайта в первых 30 по этим трём запросам нет.
8. Чего нет ни у одного из десяти: PSI и манометра, ящика счётчика, пайки и type L под плитой, чердака, поддона и расширительного бака, того, что смотрит инспектор McKinney, замены обратного клапана на поливе с разрешением, мороза, слива кондиционера в раковину, cleanout и дымового теста, настоящей истории с вызова в McKinney. Что у них есть, а нам нельзя: tankless у семи, газ у пяти, repipe у четырёх, hydro jetting у трёх, купоны и клубные карты, бесплатные сметы, телефоны в тексте у всех десяти.
9. Фото и клипы: после пересчёта за McKinney числятся 23 файла (14 фото, 9 клипов). По слову Дениса только 195 и 196: кран в laundry box посреди дома, пинхол в латунном кране, месяцами капало в стену, вздулся пол и плинтусы (история надиктована 2 октября, записана для этой страницы и для leak detection). Остальные по черте города. На собранном сайте стоят только 99 (две ручки на одну, Moen) и 141 (бачок с новыми fill и flush valve): на главной и на своих страницах услуг. Свободны 21; по темам страницы: 7 и 51 (заменённый PRV), 103 (Moen 3/4 HP, пол шкафа испорчен долгой течью), 98 (старый смеситель на две ручки), 139 (сломанные fill и flush valve), 33 (ржавый фланец), 158 (PEX под тротуаром), 71 и 73 (outlet box стиральной машины), клипы 190 (toilet auger), 180 (дивертер), 63 и 64 (пинхол на PEX у манифолда). Фургона или работы в McKinney, город которой назвал Денис, кроме 195 и 196, нет.
10. Отзывы: на весь архив McKinney называет один отзыв, Ezzy Zhoo (Google, март 2025, "permit requirements for city of mckinney"), но в нём дважды имя Дениса, "rerouting of vents and water lines" и "gas line": без слова Дениса не проходит. Свободных и чистых отзывов с McKinney 0. Три отзыва живой страницы оставить нельзя: LXD Properties стоит на Frisco, Ezzy Zhoo и Victoria Nwanegbo называют Дениса. Предложение части 5 (к McKinney не привязаны): Rangsan L. (измельчитель и смесители), Javeed N. (течь, которую трудно найти), alex p (нет горячей воды), Phillip Potter (срочная работа в воскресенье). Строку вида "Reviews from McKinney homeowners" писать нельзя.
11. Официальные факты, подтверждённые вторым проходом (3 октября 2026): подрядчик регистрируется в городе до разрешения, через портал CSS, без платы; на водонагреватель нужно разрешение; в пакете для строителей, действующем с 1 октября 2025: трубка T&P не ниже 6 дюймов от пола, расширительный бак при тепловом расширении, поддон со сливом; вода: от магистрали до ящика счётчика отвечает город, от счётчика до дома хозяин; кран города у счётчика трогают только работники города, у хозяина свой кран; канализация: от cleanout до дома часть хозяина (Public Works, 2025); пересчёт счёта после течи (расход в 3 раза выше, счёт больше $150.00, раз в 12 месяцев, бланк за 60 дней, с чеком и именем подрядчика); город сам меняет медные вводы 1997 до 2011 годов на своей части ("aggressive soil in the region"); кодексы 2024 года с 1 октября 2025; вода NTMWD, жёсткость 200 и 144 ppm по станциям (2025, цифры NTMWD, не города); мороз: струйка из кранов на открытых трубах, утеплитель на наружный кран. Про PRV и давление в доме у города ни слова. Официальная ссылка для страницы: https://www.mckinneytexas.org/257/Contractor-Registration (как на Frisco) или https://www.mckinneytexas.org/2284/Meters-Leaks-Pipes .
12. Индексы и возраст (USPS, Census, ГИС города, проверено): индексы McKinney 75069, 75070, 75071, 75072; медианный год постройки жилья 2007 (±1); до 1980 года построено 7.8% жилья; старое жильё стоит в 75069, к востоку от US 75, вокруг площади (там до 1980 года 26.1%); жилья 1939 года и раньше около 1,128 (±356). Под 75071 тысячи домов вне черты города (ETJ, 6,834 жилых адреса округа в слое адресов города): к ним слова о разрешении и инспекции McKinney не относятся.
13. Ссылки: на сайте нет ни одного поста или гида целиком из McKinney. В гиде про утечку во дворе есть случай из McKinney в три предложения (счётчик крутился, утечка главной линии в шести футах под землёй), гид на страницу McKinney не ссылается. Семь страниц услуг не ссылаются на McKinney; якорь "plumber in McKinney" стоит на сайте 6 раз.
14. Офис: офиса в McKinney нет, и CLAUDE.md не говорит, из какого офиса его обслуживают. Живая страница в тексте офис не называет, но в схеме у неё второй бизнес с адресом и телефоном офиса Frisco, а на фургоне главного фото телефон Plano. В выгрузке Google (30 сентября 2026) McKinney стоит в зоне обслуживания карточки Plano, у карточки Frisco зона пустая. Новый сайт показывает две кнопки (Frisco office, Plano office), блока офиса и карты нет. Вопрос к Денису.
15. Чего не хватает для сильной страницы: диктовки Дениса про McKinney (в `source/dictation` есть только laundry box), его слов о самых частых вызовах, давлении, старых домах у центра и инспекторе; решения по title и по slab leak; подтверждения истории с деревом; ответа про офис; кадра фургона или работы в McKinney; выбора отзывов.

## 1. Живая страница

Файл раздела: `docs/briefs/mckinney/1-live-page.md`, вставлен целиком. Заголовок файла: «1. Живая страница McKinney: что стоит на fppplumbing.com сейчас».

Полные таблицы в бриф не вставлены, они лежат рядом: `1-live-page-tables.md` (28 КБ): Т1 FAQ с ответами и повторами, Т2 ссылки со страницы, Т3 ссылки на страницу, Т4 страницы с McKinney без ссылки, Т5 общий текст с другими страницами, Т6 схема, Т7 фото McKinney в архиве, Т8 места без названия, Т9 голос и мелочи.

Откуда данные: краул от 30 сентября 2026 (`source/crawl/pages/plumber-mckinney-tx.json`, `source/crawl/html/plumber-mckinney-tx.html`, остальные 63 страницы рядом); `reviews/all-reviews.csv`, `reviews/site-ledger.md` и `reviews/site-reviews.json` (прочитаны 3 октября в 11:01), `reviews/ledger.md`, `reviews/ledger-decisions.csv`; `tools/build_launch_content.py`, `site/src/data/launch-changes.csv`, `site/src/content/pages/plumber-mckinney-tx.md` (все три от 10:23 и 10:24). 3 октября в 11:01 по Техасу живая страница скачана ещё раз одним запросом: код совпал с краулом байт в байт.

Длинные таблицы: `docs/briefs/mckinney/1-live-page-tables.md` (Т1 FAQ с ответами и повторами, Т2 ссылки со страницы, Т3 ссылки на страницу, Т4 страницы с McKinney без ссылки, Т5 общий текст с другими страницами, Т6 схема, Т7 фото McKinney в архиве, Т8 места без названия, Т9 голос и мелочи).

Страница https://fppplumbing.com/plumber-mckinney-tx/ : ответ 200, в page-sitemap.xml, canonical на себя, index и follow. Опубликована 16 мая 2025, правка 17 августа 2026 (схема). `docs/pages-plan.md` (Search Console, 1 июля до 28 сентября 2026): 472 показа, место 27.2, 0 кликов, «Старый текст», в очереди городов последняя. `seo/keyword-map.md`: главный ключ "plumber mckinney tx", не целиться в "slab leak repair mckinney (slab leak page)", на запуск "carry as is".

### 1. Title, описание, H1, заголовки, объём

| Что | Текст на живой странице |
|---|---|
| Title (61 знак) | "Plumber in McKinney, TX \| Slab Leak & Garbage Disposal Repair" |
| Meta description (145) | "Warm spot on the floor? Disposal humming or leaking underneath? Water heater cold? Licensed McKinney plumbers, upfront pricing, same-day service." |
| H1 (81) | "Plumbing Repair in McKinney, TX - Slab Leaks, Water Heaters, Drains and Disposals" |
| OG title, OG картинка | тот же, что title; фургон `/wp-content/uploads/2025/05/photo_2025-05-15_20-41-45.jpg` |

В H1 дефис с пробелами, не тире; слова "plumber" в H1 нет.

H2 по порядку (слов в разделе): 1. "Slab Leak Repair in McKinney" (169); 2. "Main Water Line Repair in Older McKinney Homes" (266); 3. "Garbage Disposals, and When to Stop Repairing Them" (249); 4. "Our Plumbing Services in McKinney" (93, десять строк со ссылками, абзацы со знаком "•"); 5. "Water Heaters and the Tank Nobody Mentions" (125); 6. "Older McKinney, Newer McKinney" (105); 7. "When It Cannot Wait" (64); 8. "McKinney Plumbing FAQ" (263); 9. "What McKinney Homeowners Say About FPP Plumbing" (отзывы); 10. "980-899-7997 469-998-8999" (не раздел: телефоны нижней панели тегом H2, шаблон сайта).

H3: шесть, все это вопросы FAQ. Блока офиса нет (верно). Нет заключения и блока Дениса.

Объём: краул считает 1,891 слово. Свой текст от H1 до конца FAQ 1,561 с заголовками (вступление 170 слов, три абзаца). Отзывы 328 с заголовком, строкой и подписями (тексты трёх отзывов 270). До 2,500 своему тексту не хватает около 940 слов.

Ключи: "McKinney" 15 раз, из них 12 до отзывов (H1, шесть раз в пяти H2, четыре в тексте, вопрос FAQ 4). "plumber in McKinney" только в title; в H1, описании и тексте 0. "McKinney plumbers" только в описании. "plumber near me" 1 (ссылка на главную). "same-day" только в описании и в alt фото.

### 2. Шесть вопросов FAQ

Все шесть тегом H3 в раскрывающемся списке Elementor (`details`, `summary`), ответы в коде обычным текстом, FAQPage совпадает со страницей слово в слово. Ответы и повторы: Т1.

| № | Вопрос (H3), слово в слово | Шаблон? |
|---|---|---|
| 1 | "What does a slab leak feel like before you can see it?" | Нет. Тема slab leak и leak detection |
| 2 | "My disposal leaks from the bottom. Can it be fixed?" | Почти повтор "…Can it be repaired?" со страницы disposal, ответ из тех же слов |
| 3 | "What size garbage disposal should I get?" | Вопрос только здесь, ответ почти слово в слово на странице disposal |
| 4 | "How much does a plumber cost in McKinney, TX?" | ШАБЛОН: тот же с другим городом на всех девяти остальных городских страницах |
| 5 | "Do you locate a slab leak before opening the floor?" | Нет. Тема leak detection |
| 6 | "Do you charge extra after hours?" | ШАБЛОН слово в слово: Allen, Carrollton, Celina, Lewisville, Little Elm, Prosper, The Colony (на Celina и ответ тот же) |

По правилу 8 вопросы 4 и 6 повторять нельзя, 2 повторяет страницу disposal. Вопросы 2 и 3 принадлежат странице disposal, 1 и 5 страницам slab leak и leak detection (правило 9).

### 3. Три отзыва на живой странице

Над отзывами строка "Real Google reviews from local homeowners." Три карточки, в каждой три ссылки на один короткий адрес Google. Все три есть в `reviews/all-reviews.csv` (Google, 5 звёзд, `on_old_site` = `/plumber-mckinney-tx/`) и в журнале старого сайта `reviews/ledger.md`.

#### 3.1. LXD Properties

- Текст: "I hired FPP Plumbing to do some plumbing inspections on a couple of homes and immediately I felt a high level of trust with them that I ended up doing all of my plumbing repair work for those homes through FPP as well. They helped me with everything from faucet/drain repairs, main water line replacements, spigot replacements, water heater installation, toilet reinstallation and several other things and I’m super happy with the work, the feedback and information and the value I felt I was getting for all of that. I find them very fair with pricing and they are now my go-to for all plumbing inspections and needs. 5 out of 5 for sure."
- Подпись: "★★★★★ · McKinney, TX · Local Guide Level 2 · January 2026 · Google"
- Ссылка на странице: https://maps.app.goo.gl/8Cvqx4Yo4avXtrut6?g_st=ic
- Архив: профиль Frisco, 2026-01-17, https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sCi9DQUlRQUNvZENodHljRjlvT2pZNFQwSmhaM3A0Unpaa2VtcHlTRmRTVm5Sb05uYxAB!2m1!1s0x0:0xe28e4c9b59df630f
- Сверка: слова совпадают все (в архиве перед "5 out of 5" два пробела). Месяц совпадает. Города в отзыве нет, а в подписи стоит (правило 11). Уровень 2 неверен: в архиве "none", и `reviews/ledger-decisions.csv` пишет, что 2 октября отзыв сверен на Google и значка Local Guide нет.
- На новом сайте: ЗАНЯТ, стоит на `/plumber-frisco-tx/` (`site-ledger.md`, `site-reviews.json`), взят туда вместо Quan Nguyen ночью 2 октября. На McKinney нельзя.

#### 3.2. Ezzy Zhoo

- Текст: "Denys of FPP is a wonderful and trustworthy plumber. He is very responsive and hardworking. I hired Denys to do the rough plumbing for my batbroom remodeling which included a new shower drain being put in, rerouting of vents and water lines, and gas line. He did a great job, working with me to satisfy permit requirements for city of mckinney. He is legit and i will be hiring him for future projects!"
- Подпись: "★★★★★ · McKinney, TX · Local Guide Level 5 · March 2025 · Google"
- Ссылка на странице: https://maps.app.goo.gl/YWbDRWSNAdB2dtm2A?g_st=ic
- Архив: профиль Plano, 2025-03-12, https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sChZDSUhNMG9nS0VJQ0FnTURReGN2dEZBEAE!2m1!1s0x0:0xccc66184bdaf3a93
- Сверка: текст знак в знак (с "batbroom" и строчными "city of mckinney"), месяц совпадает, город в отзыве есть, подпись с McKinney верна. Уровень 5 в архиве не записан.
- На новом сайте: нигде, свободен. Но "rerouting of vents and water lines, and gas line": перенос линий FPP не предлагает, газ только с подтверждения Дениса (6.4). Говорит о Денисе по имени.

#### 3.3. Victoria Nwanegbo

- Текст: "I have worked with Denys on multiple projects. I manage a rental property. The best thing about them is, I’ve never had to call them back for anything. I’ve had multiple plumbers do various jobs for me, and there’s always a leak, a loose clamp or something or another installed incorrectly. It’s exhausting. All that is old news now. I call FPP Plumbing and get on the schedule. Whatever they work on, is done and perfect. I can’t begin to explain the relief."
- Подпись: "★★★★★ · Local Guide Level 4 · September 2024 · Google"
- Ссылка на странице: https://maps.app.goo.gl/uJDLx5jXvY5g33SeA?g_st=ic
- Архив: профиль Plano, 2024-09-30, https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sChZDSUhNMG9nS0VJQ0FnSUNueTRYcUVBEAE!2m1!1s0x0:0xccc66184bdaf3a93
- Сверка: слова совпадают все (в архиве два абзаца, на странице слиты, в начале лишний пробел). Месяц совпадает. Города нет ни в отзыве, ни в подписи (верно). Уровень 4 в архиве не записан.
- На новом сайте: нигде, свободна. В архиве есть Thumbtack "Victoria N." (2022-11-20, другой текст, без пометки о копии): тот ли это человек, по файлам не понять.

#### 3.4. Общее

- Никто из трёх не входит в двенадцать главной и в запас главной; копий на Thumbtack с пометкой нет.
- На новом сайте у McKinney отзывов нет: ключа `/plumber-mckinney-tx/` в `site-reviews.json` нет, в файле страницы метка `<!-- reviews -->`.
- По правилу городских страниц (город, услуга, plumber, имя компании, речь о компании): у Ezzy Zhoo город и разрешение города, но речь о Денисе и перенос линий с газом; Victoria без города и услуги, с Денисом по имени.

### 4. Фото на живой странице

7 тегов картинок, фото одно: два логотипа (`fpp-logo-1-1024x563.png`, alt "FPP Plumbing Logo"), три пустые заглушки аватаров в отзывах (`placeholder.png`, alt пустой), знак BBB в подвале и главное фото:

- `/wp-content/uploads/2025/05/photo_2025-05-15_20-41-45-1024x576.jpg` (полный 1280 на 720), alt "FPP Plumbing truck in McKinney during same-day plumbing service". Под H1, оно же OG картинка, грузится «лениво», хотя на первом экране.
- Я его открыл: белый фургон Ram у бордюра на улице с кирпичными домами, пасмурно; на борту "EMERGENCY SERVICE 24/7", "FULLY LICENSED & INSURED", "980.899.7997", "EXPERT PLUMBING SOLUTIONS", на крыле "M-38532" (не совпадает с M-44816, в проекте не объяснено). Номерного знака и номеров домов не видно. Не фото с работы.
- Город не подтверждён: снимок из той же серии (`20-41-45` до `20-41-54`), что фургоны на других городских страницах, у каждого свой город в alt.
- Фото с работ и видео нет. В `photos/index.csv` такого файла нет. Новый файл страницы оставил фото, alt и OG картинку.
- В архиве 21 номер с городом McKinney (Т7); по слову Дениса только 195 и 196 (laundry box), остальные по месту съёмки. [С клипами 13 и 14 без подписи их 23, часть 4.]

### 5. Ссылки

Со страницы в тексте 16 внутренних, внешних 0 (Т2): "plumber near me" на `/` во втором абзаце вступления из трёх, по одной ссылке в конце первых трёх разделов, десять строк списка, "shut-off guide" и "emergency plumbing". Из 13 услуг в тексте 11: нет Hose bib repair и Expansion tank replacement (хотя про бак есть предложение). "water heater repair" ведёт на `/water-heaters/`. Официальной ссылки на город нет.

Все 16 ссылок текста с якорями (сверено критиком с `internal_links` краула): вступление "plumber near me" на `/`; раздел slab "slab leak repair" на `/slab-leak-repair-frisco-plano-mckinney/`; раздел water line "main water line repair" на `/water-lines/`; раздел disposal "garbage disposal repair" на `/garbage-disposal-repair-frisco-plano/`; список "Our Plumbing Services in McKinney": "slab leak repair" (slab leak), "garbage disposal repair" (disposal), "water heater repair" (`/water-heaters/`), "leak detection" (`/water-leak-detection-frisco-plano/`), "drain cleaning" (`/clogged-drain-cleaning-frisco-plano/`), "main line service" (`/drain-services/`), "toilet repair" (`/toilet-repair-frisco-plano/`), "shower valve repair" (`/fixture-installation-repair/`), "PRV replacement" (`/prv-replacement-frisco-plano/`), "water line repair" (`/water-lines/`); раздел "When It Cannot Wait": "shut-off guide" (`/plumbing-guide/how-to-shut-off-main-water-valve-texas/`) и "emergency plumbing" (`/emergency-plumbing-services/`). Ссылки на страницу с якорями: живой сайт в Т3, новый сайт в части 8, раздел 4 (те же 11 ссылок на 10 страницах, сверено критиком по `site/src/content/pages`).

На страницу с 63 страниц: 200 ссылок, из них "McKinney" 191 (почти всё меню), "plumber in McKinney" 7, "McKinney, TX" 1, полное название в меню главной 1. В тексте 12 мест на 11 страницах (Т3). Не ссылаются в тексте семь сервисных страниц: drain services, drain cleaning, water heaters, faucet and shower valve, hose bib, toilet, PRV. Шесть гайдов и постов называют McKinney без ссылки (Т4).

### 6. Что идёт против CLAUDE.md, дословно

#### 6.1. Другие города и "North Dallas"

- В видимом тексте других городов нет (меню с десятью городами разрешено).
- Схема, `areaServed`: McKinney, Fairview, Allen, Prosper, Melissa. Fairview и Melissa запрещены, Allen и Prosper соседи.
- Схема, описание организации: "…serving Frisco, Plano, McKinney, and surrounding North Dallas communities."

#### 6.2. Сроки приезда в своих словах

- "If you searched for a plumber near me and are tired of four hour windows and vague estimates, that is the whole difference." Цифра часов в своём тексте (про чужие окна).
- "Our own people answer the phone, book you a window you can plan around, and send a licensed plumber who arrives inside it with parts already on board." Цифры нет, но обещание приехать внутри окна.
- Не нарушение: "Our emergency plumbing line reaches a person at any hour, and anything actively running goes to the front of the schedule." "same-day" в описании и в alt без часов. Цифры "ten calm minutes", "year three", "fifteen years" не о приезде. В отзывах цифр времени нет.

#### 6.3. Цены

- $49 по правилу: "A $49 service call on weekdays, credited toward the repair if you go ahead. Everything beyond that is priced before work starts, and that number is what lands on the invoice."
- Доплата по правилу: "Evenings, weekends, and holidays carry an emergency fee tied to how late the call comes in. You hear the exact figure while we are still on the phone, before anyone is dispatched."
- Против правила: "Our garbage disposal repair page has the full pricing." Страница disposal (живая и новая) несёт "$229" и "$400-500": фраза ведёт к ценам вне правила (сами цены на чужой странице, показать Денису).
- Пустое обещание: "Our main water line repair page covers how we locate it and what the options cost." На странице water lines цен нет.
- Схема: `priceRange` "$$".

#### 6.4. Tankless, reroute, hydro jetting, газ

- В своём тексте нет. "…what each route means for your flooring" это путь к трубе, не перенос линии (двусмысленно, Т9). "gas valves do get repaired" это клапан водонагревателя.
- Отзыв Ezzy Zhoo: "…which included a new shower drain being put in, rerouting of vents and water lines, and gas line." Слова клиента, править нельзя; ставить ли, решает Денис.

#### 6.5. Офис или адрес в McKinney

В тексте нет, это верно. В схеме второй бизнес "FPP Plumbing - Plumber in McKinney, TX" (`/plumber-mckinney-tx/#business`) с адресом, телефоном и точкой на карте офиса Frisco, часы круглые сутки. По правилу бизнес один, `#organization`, McKinney в areaServed (Т6).

#### 6.6. Телефоны, Owner, гарантия, FAQ

Телефонов в тексте и ответах нет (шапка, подвал, панель тегом H2). Owner нет (только "Homeowners"). Сроков гарантии нет. FAQ: все шесть тегом H3.

#### 6.7. Заголовки и ключи

- Против карты ключей: карта запрещает "slab leak repair mckinney", а title ("Slab Leak & Garbage Disposal Repair"), H1 ("Slab Leaks"), первый H2 "Slab Leak Repair in McKinney" и FAQ 1 и 5 целятся туда. Страница slab leak несёт McKinney в адресе и в H1 ("Slab Leak Repair in Plano, McKinney and Frisco"). Что держит показы: раздел 2.
- "Garbage Disposals, and When to Stop Repairing Them" (249 слов) и FAQ 2, 3: глубина страницы disposal (правило 9), 138 общих слов с ней (Т5).
- "Main Water Line Repair in Older McKinney Homes" (266): глубина страницы water lines, история с деревом стоит и там.
- H2 вида «услуга плюс город»: "Slab Leak Repair in McKinney", "Main Water Line Repair in Older McKinney Homes", "Our Plumbing Services in McKinney" (и "McKinney Plumbing FAQ"). Запрет на такие H2 записан для главной; для города правило другое (фраза с городом в части H2), но первые два спорят с картой ключей и правилом 9.
- "plumber in McKinney" нет в H1, описании, вступлении, первом блоке, H2; заключения нет. Правило городов требует фразу во всех этих местах.
- Ссылка на главную: анкор верный, но во втором абзаце вступления, не в последнем, и "If you searched for a plumber near me" повторяет Carrollton, Lewisville, Prosper, The Colony и старый Frisco (правило 6).

#### 6.8. Остальное

- Тройки, лозунги, итоги разделов, описание из трёх риторических вопросов, пропущенный пробел "shut-off guidecovers": дословно в Т9. Главное оттуда: "One is a slab leak, quiet, expensive, and easy to ignore until the floor tells on it."; "The other is a garbage disposal, loud, annoying, and usually cheaper to replace than to keep nursing."; "No overseas call center, no script."; "Here is the honest version most companies will not tell you: disposals mostly do not get repaired."; "Undersized units grind slowly, clog often, and rust through from the inside."; итог раздела "Caught early, this is contained work. Left alone through a season, the plumbing becomes the cheap part and the flooring becomes the expensive one."; описание "Warm spot on the floor? Disposal humming or leaking underneath? Water heater cold?"; "…what each route means for your flooring" (читается как перенос линии).
- Схема: два узла Organization с одним @id, "Texas Master Plumber License M-44816", `legalName` "FPP Plumbing, LLC", нет Service, Person, Review (Т6). Подвал: "License M - 44816".
- Нет блока Дениса, фото с работ, историй, заключения.

### 7. Улицы, районы, ориентиры

Названий улиц, районов, комплексов и ориентиров на странице нет (проверены все слова с заглавной буквы; в `docs/briefs/_shared/cities-official-place-names-2026-10-03.json` у McKinney тоже пусто). Места без названия целиком: Т8. Главное:

- "Around the historic center and the older established streets, the failures come from age: …" Исторический центр McKinney настоящий: страница города https://www.mckinneytexas.org/350/Historic-Preservation-Resources (открыта 3 октября 2026): "During the 1980s, the City Council of McKinney passed ordinances establishing two historic districts and the regulations that oversee them." Какие улицы старые и что там в трубах, на странице не сказано и Денисом не подтверждено.
- "Worth knowing before you call anyone: everything from the meter to the house is yours, everything from the meter to the street is the city’s." Город McKinney; граница ответственности официальной страницей здесь не проверена (раздел 6a). [Проверена в части 6: city-d1 и city-d2 подтверждены, https://www.mckinneytexas.org/765/Galvanized-Service-Lines и https://www.mckinneytexas.org/2284/Meters-Leaks-Pipes ; фраза живой страницы с городом совпадает.]
- Отзыв Ezzy Zhoo: "…satisfy permit requirements for city of mckinney." Внутри McKinney.
- Схема: адрес офиса Frisco (6.5).

### 8. Точечные правки на новом сайте

В `tools/build_launch_content.py` правок для `/plumber-mckinney-tx/` нет: "mckinney" там только в списке десяти городов (строка 46) и в адресах других страниц (строки 894, 897, 902, 903, 966). Общие правила, `launch-changes.csv`, строки 263 и 264:

- H1: "Plumbing Repair in McKinney, TX: Slab Leaks, Water Heaters, Drains and Disposals" (дефис заменён двоеточием);
- карточки отзывов заменены меткой `<!-- reviews -->`.

Остальное в файле новой страницы слово в слово, включая фото фургона с alt, "four hour windows", "has the full pricing", "what the options cost" и пропущенный пробел. Отзывов для McKinney в `site-reviews.json` нет. Схему новой страницы не проверял (`site/dist` пересобирается).

### 9. Местная суть и непроверенные факты

Что можно сохранить как суть, если Денис подтвердит:

1. "McKinney sends us two calls more than any others, and they could not be more different. One is a slab leak, … The other is a garbage disposal, …" и "We do both weekly here, along with everything in between." Главная мысль страницы, нигде не подтверждена. Если slab leaks в McKinney редкие, по правилу городских страниц этот блок не может открывать страницу.
2. "Once a McKinney house passes the twenty year mark, the plumbing outside the walls starts dealing with two forces…" (грунт, который набухает и сохнет, и корни старых деревьев).
3. "We handled a job in McKinney recently where a large tree in the yard had grown into the service line and damaged the copper outright." Единственный случай с работы на странице. В диктовках Дениса его нет; та же история на странице water lines.
4. Граница "from the meter to the house is yours" (если подтвердит официальная страница, раздел 6a). [Подтверждена: часть 6, city-d1, city-d2.]
5. "Most of the failed units we pull out of McKinney kitchens share a story: a builder grade 1/3 or 1/2 HP unit…" На город идёт одним предложением со ссылкой.
6. Старый центр и новые районы (пункт 7).
7. "When it is replacement, the common sizes are on the truck and the permit and inspection are ours to handle." Разрешения и инспекции в правилах есть, "common sizes are on the truck" не подтверждено.
8. Отзыв Ezzy Zhoo: работа по разрешению города McKinney (с оговоркой 6.4).

Материал Дениса, которого на живой странице нет: McKinney, кран в laundry box посреди дома, пинхол в латунном клапане, месяцами капало в стену, вздулись пол и плинтусы (видео 195, фото 196; `source/dictation/2026-10-02-frisco-additions.md`; `docs/pages-plan.md`: «страница McKinney и leak detection»).

Ещё не подтверждено: "fill valves quit in year three"; "3/4 HP is the sweet spot…"; "run it every day or two with cold water"; "Plenty of older homes here have copper out there"; alt "in McKinney during same-day plumbing service"; город работ LXD Properties и Victoria Nwanegbo.

### 10. Что не удалось проверить

Уровни Local Guide двух свободных авторов; тот ли человек Thumbtack "Victoria N."; что значит "M-38532"; граница ответственности за водяную линию (раздел 6a) [закрыто в части 6: подтверждена]; схема новой страницы на тестовом сайте [описана по шаблону в части 7.3]; какие слова держат показы (раздел 2) [закрыто в части 2].

## 2. Search Console

Файл раздела: `docs/briefs/mckinney/2-gsc.md`, вставлен целиком. Заголовок файла: «2. Search Console: страница McKinney (/plumber-mckinney-tx/)».

Длинные таблицы в бриф не вставлены, они лежат рядом в `docs/briefs/mckinney/`: `mckinney-gsc-section-tables.md` (38 КБ, все таблицы раздела со всеми колонками), `mckinney-gsc-table-3m.md` (7 КБ, все 40 запросов за 3 месяца), `mckinney-gsc-table-16m.md` (20 КБ, все 171 запрос за 16 месяцев), `mckinney-gsc-home-mckinney.md` (9 КБ, главная по запросам с mckinney, 99 строк), `mckinney-gsc-headings.md` (32 КБ, что держит каждый заголовок), `mckinney-gsc-other-pages.md` (51 КБ, другие страницы сайта по запросам с mckinney: 49 строк за 3 месяца, 271 за 16). Там же скрипты счёта `gsc_mckinney_live.py` и `gsc_mckinney_lib.py` (копии скриптов Plano, переделанные под McKinney).

Собрано 3 октября 2026, страница сейчас не переписывается. Источники: source/gsc/page-query-3m.csv и page-query-16m.csv (выгрузка Search Console API от 30 сентября 2026), performance-3m и performance-16m/Pages.csv, page-query-coverage.csv, seo/keyword-map.md и .csv, seo/cannibalization-findings.md. Живая страница: source/crawl/pages/plumber-mckinney-tx.json (обход 30 сентября 2026, страница менялась 17 августа 2026). Файл нового сайта site/src/content/pages/plumber-mckinney-tx.md пока несёт тот же старый текст.

Три числа через точку: показы · место · клики. Четыре: запросов · показы · место · клики.

Рядом: `mckinney-gsc-section-tables.md` (все таблицы раздела со всеми колонками), `mckinney-gsc-table-3m.md` (40 запросов), `mckinney-gsc-table-16m.md` (171), `mckinney-gsc-home-mckinney.md` (главная, 99 строк), `mckinney-gsc-headings.md` (каждый заголовок по запросам), `mckinney-gsc-other-pages.md` (другие страницы: 49 строк за 3 мес, 271 за 16), скрипты `gsc_mckinney_live.py` и `gsc_mckinney_lib.py` (копии скриптов Plano из docs/briefs/_shared, переделанные под McKinney).

### Главное коротко

1. Кликов нет: 1 за 16 месяцев (запрос скрыт), 0 за 3; с известным запросом 0. На всём сайте по запросам с mckinney за 16 месяцев один клик, у страницы Frisco.
2. Показы почти исчезли: 20,833 за 16 месяцев, из них 472 за последние 3. Это последняя из десяти городских страниц за 3 месяца (Allen 1,134). Так же упали все запросы с mckinney на сайте: 61,658 за 16 месяцев, 910 за 3. Когда и почему, по выгрузке не видно.
3. 96 процентов показов дают запросы с mckinney, но на месте около 62; на местах 1 до 3 ни одного. Фраза «plumber in McKinney» стоит только в title.
4. За 3 месяца по «plumber mckinney tx» выше McKinney (2 · 59.0) стоят страницы Frisco (98 · 17.9) и Plano (75 · 17.3).
5. Title и H2 "Slab Leak Repair in McKinney" бьют в ключ страницы slab leak (у McKinney он в must not target); slab leak сильнее: 10,363 · 32.4 против 2,382 · 61.1 за 16 месяцев.
6. По water line, faucet и toilet с mckinney страница McKinney сильнее хозяев по карте (1,416 против 32, 876 против 31, 232 против 3). По «low water pressure plumber mckinney» (580 · 33.8) она лучшая на сайте.
7. Запросов с чужими городами нет совсем.

### Как считали

- Метод Plano без изменений: запрос покрыт словами, когда каждое значимое слово стоит в тексте FPP (title, description, H1, H2, вопросы FAQ, текст, ответы FAQ); in, tx, near, me не считаются; множественное число приводится к единственному; отзывы клиентов отдельно. Блока офиса у McKinney нет. Пометки «карта» нет: по правилу tools/cannibalization_report.py она только у страниц карточек Google (Frisco, Plano).
- Отличия от Plano: первые 20 запросов (так в задании), отложенные слова из запросов McKinney, индексы McKinney из docs/briefs/_shared/cities-official-place-names-2026-10-03.json.
- Второй счёт: модуль csv, разбор строк без csv (в скрипте, с остановкой при расхождении) и awk дали одно и то же: 3 мес 40 запросов, 0 кликов, 319 показов, место 30.80; 16 мес 171, 0, 19,500, 62.26. Совпадает с page-query-coverage.csv; пять запросов сверены руками по всем страницам.

### 1. Итоги за 3 и 16 месяцев

| Период | Запросов | Клики | Показы | Среднее место (по показам) |
|---|---|---|---|---|
| 3 месяца (1 июля до 28 сентября 2026) | 40 | 0 | 319 | 30.8 |
| 16 месяцев (31 мая 2025 до 28 сентября 2026) | 171 | 0 | 19,500 | 62.3 |

Итог Google со скрытыми запросами: 3 мес 0 кликов, 472 показа, место 27.19; 16 мес 1 клик, 20,833 показа, место 61.33. С известным запросом 68 процентов показов за 3 месяца, 94 за 16.

| Группа запросов | 3 мес: запросов | клики | показы | место | 16 мес: запросов | клики | показы | место |
|---|---|---|---|---|---|---|---|---|
| mckinney | 23 | 0 | 108 | 28.1 | 142 | 0 | 18,779 | 62.4 |
| без города | 15 | 0 | 190 | 35.4 | 27 | 0 | 678 | 62.7 |
| другой город | 0 | 0 | 0 | 0.0 | 0 | 0 | 0 | 0.0 |
| бренд | 2 | 0 | 21 | 2.8 | 2 | 0 | 43 | 7.3 |

- Все запросы трёх месяцев есть в шестнадцатимесячной выгрузке, 13 месяцев до июля 2026 получаются вычитанием: 19,181 показ, 0 кликов, место 62.8. Место за 3 месяца (30.8) «лучше» только потому, что исчезли дальние показы.
- Места запросов с mckinney за 16 мес: 1 до 3 ни одного, 3 до 10 один (12 показов), 20 до 50 семнадцать (2,520), ниже 50 сто двадцать четыре (16,247).
- За 3 месяца без города больше показов, чем с mckinney (190 против 108), и лучшие места: «garbage disposal repair near me» 46 · 5.7, «slab leak plumber near me» 45 · 7.7.

### 2. Запросы страницы

Первые 20 за 3 месяца: 1. garbage disposal repair near me 46 · 5.7; 2. google find me a plumber 45 · 79.6; 3. slab leak plumber near me 45 · 7.7; 4. slab leak plumber mckinney 26 · 14.8; 5. alexa find me a plumber 22 · 77.8; 6. fpp plumbing 20 · 1.9; 7. plumber mckinney 14 · 49.1; 8. garbage disposal repair mckinney 12 · 9.9; 9. garbage disposal installation near me 10 · 13.2; 10. leak detection plumber mckinney 9 · 21.7; 11. repiping mckinney 7 · 33.3; 12. 24 hour plumber mckinney texas 6 · 45.3; 13. repiping near me 6 · 19.7; 14. same day service plumbing mckinney 6 · 15.5; 15. 24/7 plumber mckinney 5 · 29.2; 16. plumber in mckinney 5 · 49.4; 17. repiping services near me 4 · 24.2; 18. dpp plumbing 3 · 65.0; 19. low water pressure plumber mckinney 3 · 13.0; 20. plumber mckinney tx 2 · 59.0.

Первые 20 за 16 месяцев: 1. plumber in mckinney 1,431 · 59.1; 2. plumber mckinney 1,343 · 45.7; 3. slab leak repair mckinney 711 · 62.1; 4. plumber mckinney texas 696 · 60.0; 5. plumber in mckinney tx 631 · 53.4; 6. low water pressure plumber mckinney 580 · 33.8; 7. slab leak repair mckinney tx 515 · 56.9; 8. plumbers mckinney tx 489 · 63.8; 9. google find me a plumber 455 · 81.3; 10. mckinney tx plumber service 439 · 63.6; 11. plumbing mckinney tx 432 · 72.0; 12. mckinney tx water line repair 404 · 57.8; 13. mckinney plumber service 382 · 81.0; 14. mckinney water line repair 375 · 67.2; 15. plumber mckinney tx 367 · 50.9; 16. water line repair mckinney tx 365 · 57.4; 17. emergency plumber mckinney tx 345 · 75.1; 18. emergency plumber mckinney 340 · 65.6; 19. mckinney slab leak repair 328 · 68.0; 20. mckinney tx sab leak repair 323 · 62.7. Из этих 20 за последние 3 месяца не показывались 11.

Кликов 0 у всех. Запросов с кликом нет ни за 3, ни за 16 месяцев; единственный клик сайта по mckinney это «plumbers in mckinney texas» у страницы Frisco (5 · 53 · 1).

### 3. Главная по запросам со словом mckinney

За 3 мес у главной 7 запросов с mckinney, 12 показов, место 31.2; главная выше McKinney по одному (1 показ). За 16 мес 99 запросов, 9,417 показов, место 52.7, 0 кликов; общих с McKinney 69, главная выше по 24 (7,028 её показов), только у главной 30 (908). Быстрых ссылок главной по mckinney нет.

| Запрос | Главная 16 мес | McKinney 16 мес | Главная 3 мес | McKinney 3 мес |
|---|---|---|---|---|
| emergency plumber mckinney | 1,800 · 44.4 · 0 | 340 · 65.6 · 0 | 5 · 23.0 · 0 | |
| emergency plumber mckinney tx | 858 · 55.6 · 0 | 345 · 75.1 · 0 | | 1 · 16.0 · 0 |
| same day service plumbing mckinney | 371 · 19.4 · 0 | 23 · 30.6 · 0 | 1 · 18.0 · 0 | 6 · 15.5 · 0 |
| low water pressure plumber mckinney | 309 · 61.8 · 0 | 580 · 33.8 · 0 | | 3 · 13.0 · 0 |
| plumber in mckinney | 65 · 84.7 · 0 | 1,431 · 59.1 · 0 | | 5 · 49.4 · 0 |

Главная берёт emergency, same day и near me (19 запросов emergency с mckinney: 6,744 · 48.7 против 1,848 · 75.2 у McKinney). Общие запросы города у главной слабее.

### 4. Что держат title, H1, каждый H2 и вопросы FAQ

Дословно. Title: "Plumber in McKinney, TX | Slab Leak & Garbage Disposal Repair". Description: "Warm spot on the floor? Disposal humming or leaking underneath? Water heater cold? Licensed McKinney plumbers, upfront pricing, same-day service." H1: "Plumbing Repair in McKinney, TX - Slab Leaks, Water Heaters, Drains and Disposals". H2: "Slab Leak Repair in McKinney", "Main Water Line Repair in Older McKinney Homes", "Garbage Disposals, and When to Stop Repairing Them", "Our Plumbing Services in McKinney", "Water Heaters and the Tank Nobody Mentions", "Older McKinney, Newer McKinney", "When It Cannot Wait", "McKinney Plumbing FAQ", "What McKinney Homeowners Say About FPP Plumbing". Вопросы FAQ (H3): "What does a slab leak feel like before you can see it?", "My disposal leaks from the bottom. Can it be fixed?", "What size garbage disposal should I get?", "How much does a plumber cost in McKinney, TX?", "Do you locate a slab leak before opening the floor?", "Do you charge extra after hours?"

Заголовок держит запрос, когда все значимые слова запроса стоят в нём. За 16 мес (запросов · показы): title 30 · 8,203 (фразой целиком 13 · 5,354); description 24 · 7,123; H1 22 · 2,775; H2 slab 6 · 1,655; H2 water line 5 · 1,416; H2 services 12 · 1,137; H2 FAQ и H2 отзывов по 7 · 703; вопрос про цену 19 · 6,130. Ничего не держат: H2 "Garbage Disposals, and When to Stop Repairing Them", "Water Heaters and the Tank Nobody Mentions", "Older McKinney, Newer McKinney", "When It Cannot Wait" и пять вопросов FAQ из шести. Ни один заголовок не держит 86 запросов с mckinney (7,606 показов): faucet repair, emergency plumber, toilet repair, drain cleaning, sewer line, low water pressure.

#### Что нельзя потерять

1. **Начало title "Plumber in McKinney, TX".** Точные «plumber in mckinney» (1,431 · 59.1) и «plumber in mckinney tx» (631 · 53.4) стоят только здесь. Мягко title держит ещё «plumber mckinney» (1,343), «plumber mckinney texas» (696), «plumbers mckinney tx» (489), «plumber mckinney tx» (367, главный ключ по карте). В H1 и тексте этой фразы нет.
2. **Description "Licensed McKinney plumbers ... service".** Единственное место точной «mckinney plumbers» (31); только description держит «mckinney tx plumber service» (439) и «mckinney plumber service» (382).
3. **H1 "Plumbing Repair in McKinney, TX".** Один держит «plumbing repair mckinney» фразой целиком (205 · 72.0) и «mckinney water heater repair» (84). Слова plumber в H1 нет.
4. **H2 "Our Plumbing Services in McKinney".** Один держит «plumbing service mckinney» (177) и «plumbing services mckinney» (96) фразой целиком, «mckinney plumbing service(s)» (89 и 71).
5. **H2 "Main Water Line Repair in Older McKinney Homes".** Один держит четыре запроса water line repair с mckinney (404, 375, 365, 261). За 3 месяца по ним показов нет. Хозяин по карте /water-lines/ (32 показа).
6. **H2 "McKinney Plumbing FAQ".** Единственное место точных «mckinney tx plumbing» (12) и «mckinney plumbing» (1).
7. **"FPP Plumbing" в H2 отзывов и во вступлении:** «fpp plumbing» 20 · 1.9 за 3 мес.
8. **"Garbage Disposal Repair" в title:** «garbage disposal repair near me» (46 · 5.7) и «garbage disposal repair mckinney» (12 · 9.9), лучшие места страницы за 3 месяца; ключ с mckinney карта отдаёт странице disposal.
9. **H2 "Slab Leak Repair in McKinney":** 1,290 показов фразой целиком за 16 мес, но это ключ страницы slab leak (вопрос 1).

Слов нет в тексте FPP: low (580 показов за 16 мес), faucet (869; только в отзыве LXD Properties "faucet/drain repairs"), 24 («24/7 plumber mckinney» и подобные; «24/7» есть только в схеме), bathroom (99), contractor (71), pipe и break (70). Emergency есть в тексте, в заголовках нет.

### 5. Фраза целиком

Кликов нет, поэтому проверено 35 запросов: первые 20 за каждый период (5 общих). Точная фраза стоит у 3, только по мягкой проверке у 7, только с перестановкой слов у 3, нигде у 22; из 26 запросов с mckinney 2, 6, 3, 15.

- Точно: «plumber in mckinney», «plumber in mckinney tx» (title); «fpp plumbing» (H2 отзывов, вступление, alt).
- Только мягко: «plumber mckinney», «plumber mckinney texas», «plumbers mckinney tx», «plumber mckinney tx» (title); «slab leak repair mckinney» и «... tx» (H2); «garbage disposal repair near me» (title, текст).
- Перестановка: «plumbing mckinney tx» (H2), «mckinney slab leak repair» (H1, H2), «slab leak plumber mckinney» (title).
- Нигде: low water pressure, оба plumber service, три water line repair, два emergency plumber, «garbage disposal repair mckinney», «same day service plumbing mckinney», 24 hour и 24/7, голосовые, repiping, опечатки и другие.

Во всём списке запросов с mckinney и бренда точная фраза в словах FPP стоит всего у 6 (2,140 показов за 16 мес): три варианта «plumber in mckinney» (title), «fpp plumbing», «mckinney plumbers» (description), «mckinney plumbing» (H2 FAQ).

### 6. Где другая страница выше или забирает показы

На сайте за 3 мес 57 запросов с mckinney (910 показов), McKinney по 23 (108). За 16 мес 253 (61,658), McKinney по 142 (18,779).

| Страница (ещё /water-heaters/ 1,201 и leak detection 877 показов за 16 мес) | 16 мес: запросов · показы · место | Выше McKinney: запросов · показы | 3 мес: запросов · показы · место |
|---|---|---|---|
| /slab-leak-repair-frisco-plano-mckinney/ | 49 · 15,926 · 44.7 | 17 · 13,206 | 6 · 127 · 17.4 |
| / | 99 · 9,417 · 52.7 | 24 · 7,028 | 7 · 12 · 31.2 |
| /water-heater-repair-frisco-mckinney/ | 47 · 7,148 · 55.7 | 6 · 3,757 | 4 · 50 · 20.1 |
| /garbage-disposal-repair-frisco-plano/ | 8 · 2,669 · 33.6 | 1 · 648 | 6 · 318 · 25.9 |
| /emergency-plumbing-services/ | 25 · 2,447 · 68.4 | 5 · 260 | нет |
| /drain-services/ | 24 · 2,328 · 75.0 | 1 · 10 | нет |
| /plumber-frisco-tx/ | 37 · 320 · 23.6, 1 клик | 26 · 243 | 18 · 190 · 15.4 |
| /plumber-plano-tx/ | 10 · 88 · 18.9 | 8 · 85 | 10 · 88 · 18.9 |

Главные пары:

- «slab leak repair mckinney»: slab leak 2,806 · 26.8 против McKinney 711 · 62.1 (16 мес); за 3 мес 85 · 16.1, у McKinney показов нет.
- «emergency plumber mckinney»: главная 1,800 · 44.4, emergency 788 · 65.9, McKinney 340 · 65.6; за 3 мес Frisco 21 · 1.6 (по правилу проекта показ карточки Frisco).
- «water heater repair mckinney» 2,005 · 53.3 у /water-heater-repair-frisco-mckinney/, «garbage disposal repair mckinney» 1,654 · 28.3 у disposal, «leak detection mckinney» 786 · 61.4 у slab leak; у McKinney 63 · 77.4, 12 · 9.9, 107 · 90.2.
- Общие запросы города за 3 мес: Frisco 104 · 19.1, Plano 84 · 19.2, McKinney 28 · 49.9 (за 16 мес McKinney ещё впереди: 9,381 · 60.8). В живом тексте Frisco McKinney назван в ответе FAQ ("We also cover Plano, McKinney, Prosper, Little Elm, and The Colony"), в тексте Plano нет.

### 7. Запросы услуг с mckinney и хозяева по карте ключей

Услуга по словам запроса; хозяин из seo/keyword-map.md и .csv и seo/cannibalization-findings.md. За 16 мес: запросов · показы · место.

| Услуга | McKinney | Хозяин по карте | Хозяин по тем же запросам |
|---|---|---|---|
| slab leak | 10 · 2,382 · 61.1 | slab leak (slab leak repair mckinney) | 14 · 10,363 · 32.4 |
| water line | 5 · 1,416 · 62.0 | /water-lines/ (water line repair) | 5 · 32 · 74.1 |
| faucet, shower valve | 6 · 876 · 51.3 | /fixture-installation-repair/ (faucet repair в любом городе) | 2 · 31 · 69.9 |
| drain cleaning | 10 · 743 · 72.6 | /clogged-drain-cleaning-frisco-plano/ (drain cleaning mckinney) | 2 · 6 · 74.7 |
| PRV, давление | 2 · 593 · 34.3 | /prv-replacement-frisco-plano/ по теме | нет |
| leak detection | 6 · 279 · 85.4 | /water-leak-detection-frisco-plano/ по теме | 7 · 836 · 88.8 |
| toilet | 4 · 232 · 64.3 | /toilet-repair-frisco-plano/ по теме | 1 · 3 · 57.3 |
| water heater, ремонт | 4 · 232 · 77.7 | /water-heater-repair-frisco-mckinney/ (water heater repair mckinney) | 24 · 4,162 · 59.9 |
| water heater, замена | 2 · 57 · 79.4 | /water-heaters/ (решение 5) | 10 · 396 · 75.8 |
| garbage disposal | 4 · 173 · 57.1 | disposal (garbage disposal repair mckinney) | 7 · 2,668 · 33.6 |
| sewer line | 4 · 176 · 69.7 | /drain-services/ (main sewer line replacement mckinney) | 11 · 1,145 · 58.8 |
| emergency, 24 hour | 14 · 1,848 · 75.2 | /emergency-plumbing-services/, ключа с mckinney нет | 18 · 2,392 · 67.9; главная 19 · 6,744 · 48.7 |
| общие запросы города | 63 · 9,381 · 60.8 | сама страница McKinney | главная 53 · 1,841 · 61.3 |

Ещё: pipe и leak repair 3 · 134 · 83.1 (ключа нет); repipe, hydro jet, trenchless 5 · 257 (услуги нет); hose bib, expansion tank, tankless, gas line у McKinney не показывались. Drain с mckinney фактически берёт /drain-services/ (11 · 1,180 · 90.8). Ключ «emergency plumber mckinney» в карте ни за кем, у Little Elm, Prosper и The Colony такой ключ за страницей города. Тема «low water pressure in house» в карте у гайда /plumbing-guide/water-pressure-dropping-tips-2026/, по запросу с mckinney он не показывается.

### 8. Запросы с чужими городами

Ни одного ни за 3, ни за 16 месяцев. «plumber 75070» и «emergency plumber 75070» (по 2 показа) это индекс McKinney. Видимый текст чужих городов не называет; называет схема: areaServed Fairview, Allen, Prosper, Melissa и описание организации ("surrounding North Dallas communities", "Texas Master Plumber License M-44816"). По правилам проекта это уходит, по Search Console ничего не стоит.

### 9. Слова, которые на страницу не ставятся

Запрос с двумя словами одного вида посчитан один раз; по словам с примерами в `mckinney-gsc-section-tables.md`.

| Что отложено | Слова (в скобках показы за 16 мес) | 3 мес: запросов · показы · клики | 16 мес: запросов · показы · клики |
|---|---|---|---|
| Голосовые слова | google (459), alexa (71) | 2 · 67 · 0 | 3 · 530 · 0 |
| Услуги и темы, которых на странице быть не должно | hydrojet (243), repiping (22), patio (3), heating (1), repipe (1), trenchless (1) | 5 · 19 · 0 | 9 · 271 · 0 |
| Название компании с ошибкой | pp (7), dpp (3), fps (1), ppx (1) | 2 · 4 · 0 | 4 · 12 · 0 |
| Чужие компании | trapp (2), fairfield (1), choice (1), faulk (1), flush (1), pop (1) | 3 · 4 · 0 | 6 · 7 · 0 |
| Оценочные слова и слова про цену | expert (2), immaculate (1), impeccable (1), affordable (1) | 4 · 4 · 0 | 5 · 5 · 0 |
| Опечатки | pluming (335), sab (323), mckiinney (2) | 1 · 1 · 0 | 4 · 660 · 0 |

- Главные: «google find me a plumber» (455 · 81.3), «hydrojet sewer plumber mckinney tx» (243 · 60.3), «mckinney tx sab leak repair» (323), «mckinney tx pluming» (315). Immaculate и impeccable могут быть и названиями компаний, не проверялось. Прочее: «yes», «local guide program», два site:fppplumbing.com. Длинных вопросов нет.
- Rerouting, gas line и bathroom remodeling стоят на живой странице только в отзыве Ezzy Zhoo (слова клиента).

### Что из цифр следует для брифа

1. Терять в кликах нечего; выигрыш возможен в общих запросах города (место сейчас 45 до 65).
2. Сохранить пункты 1 до 7 из «Что нельзя потерять». «plumber in McKinney» поставить ещё в текст: вступление, первый блок, последний абзац, часть H2 (правило городских страниц, как на Frisco).
3. Slab leak и garbage disposal в title и H2 slab противоречат карте; хозяева сильнее в 4 и 15 раз. Решает Денис (вопрос 1).
4. Каждая услуга один раз со ссылкой, но не терять water line, faucet repair (сейчас ссылка подписана "shower valve repair"), toilet repair, drain cleaning: по ним McKinney первая на сайте. Одна простая строка со ссылками, о добавке сказать Денису.
5. Одно предложение про low water pressure со ссылкой на страницу PRV (вопрос 2). Emergency: без глубокого раздела, ссылку и слова "emergency plumbing" оставить (вопрос 4).
6. «plumber near me» со ссылкой на главную уже во вступлении; на новой странице другими словами. Из схемы убрать Fairview, Melissa, Allen, Prosper, "North Dallas".

### Вопросы для Дениса

1. Title "Plumber in McKinney, TX | Slab Leak & Garbage Disposal Repair": оставить или заменить вторую половину? Карта отдаёт slab leak и disposal с McKinney страницам услуг, они сильнее; кликов по этим словам у McKinney не было.
2. Есть ли материал про давление воды в домах McKinney (манометр, PRV, как часто вызов)? «low water pressure plumber mckinney» лучший большой запрос страницы.
3. На живой странице написано, что в McKinney вы меняли медную линию от счётчика, в которую вросли корни дерева. Это реальный вызов, есть фото? Этот H2 один держит 1,416 показов.
4. Записать «emergency plumber mckinney» ключом страницы McKinney, как у Little Elm, Prosper и The Colony? Сейчас эти запросы держит главная.

### Что проверить не удалось

- Когда и почему пропали показы: по дням страницы в выгрузке не разбиты. Запрос единственного клика Google скрывает.
- Откуда места 17 и 19 у Frisco и Plano по «plumber mckinney tx»: выгрузка не отделяет карточку от выдачи.
- Сайт заново не открывался; tools/gsc_page_table.py и tools/export_page_text.py не запускались; данных Semrush по странице в keyword-map.csv нет.

## 3. Конкуренты

Файл раздела: `docs/briefs/mckinney/3-competitors.md`, вставлен целиком. Заголовок файла: «3. Конкуренты по McKinney: десять страниц из выдачи».

Рядом и в бриф не вставлены: `3-competitors-details.md` (25 КБ: выдача Semrush целиком, веб-поиск, все заголовки, местные факты дословно, небрежности конкурентов, запас, приёмы, которые нам нельзя) и папка `source/competitors/2026-10-03-mckinney/` (`00.txt` до `09.txt`, тексты десяти страниц для `tools/check_overlap.py`).

Дата: 3 октября 2026. Проект только читался. Новое: эта секция, приложение `3-competitors-details.md` (выдача Semrush целиком, веб-поиск, все заголовки, местные факты дословно, небрежности, запас, приёмы, которые нам нельзя) и папка `/Users/denyskavaler/Projects/fppplumbing-site/source/competitors/2026-10-03-mckinney/` (`00.txt` до `09.txt`). Где в цитате было длинное или среднее тире, стоит " / ".

### 1. Как выбраны десять страниц

Запросы: "plumber mckinney tx", "plumber in mckinney", "mckinney plumbing" (Semrush: 590, 480 и 260 поисков в месяц; для сравнения "plumber mckinney" 1 000, "mckinney plumber" 880). Оба источника сняты 3 октября 2026:

1. Semrush, обычная (не рекламная) выдача Google, база "us", первые 30 мест. По нему порядок. Метод тот же, что по Plano.
2. Веб-поиск (расширенный режим), те же запросы. Сверка: он не Google и к городу не привязан.

Чего нет: живой выдачи Google с точкой в McKinney и блока с картой. База Semrush общая по США, дата её обновления в ответе не указана.

Порядок: среднее место по трём запросам, нет в первых 30 считается как 31, одна компания один раз. У Bewley и Milestone среднее одно (7,3): выше Bewley, он есть во всех трёх запросах веб-поиска.

| № | Файл | Компания | URL | Места Semrush (три запроса по порядку) | Среднее | Веб-поиск (из 3) |
|---|---|---|---|---|---|---|
| 1 | 00.txt | Baker Brothers Plumbing, Air & Electric | https://bakerbrothersplumbing.com/mckinney-plumbing/ | 1 / 1 / 5 | 2,3 | 0 |
| 2 | 01.txt | Bewley Plumbing | https://www.bewleyplumbing.com/ | 8 / 7 / 7 | 7,3 | 3 |
| 3 | 02.txt | Milestone Electric, A/C & Plumbing | https://callmilestone.com/mckinney/plumbing/ | 5 / 5 / 12 | 7,3 | 2 |
| 4 | 03.txt | smithandsonplumbing.com (на экране "Cr Plumbing") | https://smithandsonplumbing.com/ | 6 / 6 / 14 | 8,7 | 0 |
| 5 | 04.txt | Roto-Rooter | https://www.rotorooter.com/mckinneytx/ | 4 / 4 / нет | 13,0 | 1 |
| 6 | 05.txt | JMP Plumbing Services | https://jmpplumbingservices.com/ | 21 / 19 / 8 | 16,0 | 3 |
| 7 | 06.txt | Legacy Plumbing & Electric | https://legacyplumbing.net/service-area/mckinney/ | 14 / 17 / 19 | 16,7 | 0 |
| 8 | 07.txt | Hackler Plumbing | https://hacklerplumbingmckinney.com/ | 9 / 11 / нет | 17,0 | 3 |
| 9 | 08.txt | Jimmy Cash's Plumbing ("The McKinney Plumber") | https://themckinneyplumber.com/ | 26 / 22 / 4 | 17,3 | 0 |
| 10 | 09.txt | Genzel Plumbing | https://www.genzelplumbing.com/ (у Semrush без www) | 12 / 13 / нет | 18,7 | 0 |

Не так, как в Plano: страниц города у сетей только четыре (Baker, Milestone, Roto-Rooter, Legacy), шесть это главные страницы местных фирм (Bewley, Cr Plumbing, JMP, Hackler, Jimmy Cash's, Genzel). Офис с адресом в McKinney у восьми из десяти; нет у Milestone и Legacy (Legacy обслуживает McKinney "from nearby Frisco").

Пропущено (приложение, разделы А и Е): каталоги, соцсети, видео (yelp.com 2 / 2 / 2, пост facebook.com, bbb.org, angi.com, mapquest.com, thumbtack.com, serviceagent.ai и другие); mckinneyplumbertx.com (10 / 8 / 13, был бы шестым): без названия компании и лицензии, "©Copyright 2016", чужие индексы 77511 и 77512, страница для сбора звонков, в папку не сохранена; mckenneys.com (1 место по "mckinney plumbing"): фирма McKenney's с созвучным именем. Запас: Everflow (19,3), Berkeys (20,3), M6 Plumbing (21,0). Только в веб-поиске: augerpros.com (3 из 3), jpstx.pro, Benjamin Franklin.

fppplumbing.com по трём запросам в первых 30 нет. По Semrush наша /plumber-mckinney-tx/ на 8 месте по "slab leak plumber mckinney" (90 в месяц), страница про измельчители на 20 и 28 местах по "garbage disposal repair mckinney" (170) и "mckinney garbage disposal repair" (70). Сверить с секцией Search Console.

Все десять отдали код 200 с первого запроса (один запрос на страницу), без обхода защиты. В файлы вошёл и текст, открываемый нажатием (карусель Roto-Rooter, окно отзывов Hackler, ответы FAQ Genzel).

### 2. Таблица по десяти страницам

"Основной текст": от H1 до подвала, с FAQ и отзывами; блоки, которые в коде стоят дважды (для телефона и для компьютера), считал один раз. "Вся страница": весь файл с меню и подвалом. Слова и "McKinney" (без учёта регистра) считал сам.

#### 2.1. Размер, "McKinney", отзывы, FAQ

| № | Компания | Слов: основной текст | Вся страница | "McKinney": основной / вся | Отзывы на странице | FAQ |
|---|---|---|---|---|---|---|
| 1 | Baker | 2 320 | 2 653 | 27 / 30 | 0 | 0 |
| 2 | Bewley | 827 | 1 023 | 18 / 21 | 1 строка ("R Ball"), без даты и ссылки | 0 |
| 3 | Milestone | 1 070 | 1 730 | 33 / 35 | 0, только "Over 33,000 5 Star Reviews!" | 0 |
| 4 | Cr Plumbing | 963 (без отзывов 787) | 1 206 | 8 / 11 | 3 коротких, имя и буква, без города, даты, ссылки | 0 |
| 5 | Roto-Rooter | 3 121 (без отзывов 1 991; FAQ 648) | 3 612 | 50 / 60 (без отзывов 22) | Карусель на 27 мест, все с подписью "McKinney, TX"; один отзыв дважды, два места не отзывы; "Rated 4.8 out of 379 reviews" | 9 |
| 6 | JMP | 1 125 (с повторами в коде 1 643; FAQ 546) | 2 323 | 29 / 106 (меню) | 0 в коде (виджет на скрипте) | 11 |
| 7 | Legacy | 1 176 | 2 201 | 22 / 24 | 0 | 0 |
| 8 | Hackler | 1 820 (без отзывов 855) | 4 978 (около 3 000 из них окно всех отзывов) | 23 / 34 | 10 отзывов Google с ответами, без города и даты; "4.6, Based on 114 reviews"; в окне 50, один отрицательный | 0 |
| 9 | Jimmy Cash's | 449 | 545 | 14 / 20 | 0 | 0 |
| 10 | Genzel | 931 (FAQ 394) | 1 128 | 6 / 9 | 0 в коде (виджет) | 8 |

Наша нынешняя страница (source/crawl/pages/plumber-mckinney-tx.json): 1 891 слово, "McKinney" 16 раз, 6 вопросов FAQ. [Без учёта регистра 16, с заглавной буквы 15, как в части 1: разница это "city of mckinney" в отзыве Ezzy Zhoo.]

#### 2.2. Title и H1 дословно

1. Baker. Title "Plumber in McKinney TX: Baker Brothers Plumbing, Air Conditioning, & Electric". H1 два: "Plumbers Mckinney TX: Baker Brothers Plumbing, Air, & Electric" и "Enjoy Hassle-Free Service with Baker Brothers Plumbing, Air & Electric in McKinney".
2. Bewley. Title "Bewley Plumbing, LLC | Plumbing Company Based in McKinney, Texas". H1 "Bewley Plumbing Serving McKinney Since 1947".
3. Milestone. Title "McKinney Plumber - Milestones' Local Plumbing Repairs!". H1 "Plumber in McKinney".
4. Cr Plumbing. Title "Trusted Plumber Mckinney, TX | Kings Plumbing and Backflow". H1 "Your McKinney Plumbing Experts".
5. Roto-Rooter. Title "McKinney Plumber - $55 Off Plumbing & Drain | Roto-Rooter". H1 "McKinney Plumbing, Drain & Water Cleanup Services".
6. JMP. Title "Plumber in McKinney, TX | Residential & Commercial | JMP Plumbing Services". H1 "Plumber in McKinney, TX".
7. Legacy. Title "Trusted Plumber in McKinney, TX | Legacy Plumbing & Electric". H1 "McKinney, TX Plumbing Services".
8. Hackler. Title "Hackler Plumbing | Best Plumber in McKinney TX | A+ Rated". H1 два: "Hackler Plumbing McKinney: Call the Best Plumber in McKinney TX" и "Best Plumber in McKinney TX".
9. Jimmy Cash's. Title "Jimmy Cash's Plumbing | The McKinney Plumber!". H1 нет.
10. Genzel. Title "Plumbers in McKinney, TX | Family-Owned Since 2001 | Genzel Plumbing". H1 "Family-Owned Plumbers in McKinney and Across Collin County".

#### 2.3. Темы H2, местные факты, цены, гарантия, приезд

Все H2 дословно и факты цитатами: приложение, разделы В и Г. Факты это слова самих страниц, мной не проверены.

| № | Компания | Темы H2 | Местные факты | Цены | Гарантия | Приезд |
|---|---|---|---|---|---|---|
| 1 | Baker | 21 H2 (6 с McKinney): услуги сети по одной (slab leak с reroute, септик, hydrojetting, сток в подвале, газ, tankless), электрика, кондиционеры | Районы: Adriatica, Craig Ranch, Eldorado, Tucker Hill, Stonebridge Ranch, Historic Downtown, Trinity Falls; State Highway 121; корни и осевшие глиняные трубы у Wilson Creek; кран у счётчика | Нет | Нет | "We show up on time", "Same-day service is available on most calls", история "installed by lunchtime" |
| 2 | Bewley | 14 H2 (8 с McKinney): семейная фирма с 1947, почему мы, акция октября, скидка новым, плитки услуг | С 1947, McKinney Chamber of Commerce, округа Collin и Denton | 10% новым (до $250), "$15 OFF Any Service Over $250", бесплатная смета на водонагреватель | "Customer Satisfaction Guaranteed", без срока | "On-the-way Courtesy Call" |
| 3 | Milestone | 1 H2, остальное H3 до H6: ремонт, установка, обслуживание, авария 24/7, канализация, прочистка, водонагреватели | Нет; офиса в McKinney нет | Нет, клубная карта | "100% satisfaction guarantee", без срока | "same day plumbing repairs", 24/7 |
| 4 | Cr Plumbing | 12 H2 (3 с McKinney): форма, услуги, "customer-first", купоны, три отзыва заголовками | С 1970, "3rd generation", "veteran owned" | "FREE Same-Day estimates", купоны | "comprehensive warranty", без срока | "Same-day services are available" |
| 5 | Roto-Rooter | 7 H2, все с McKinney: затопление и сушка, авария, отзывы, частые поломки (давление, PRV), округа, FAQ, почему мы | В FAQ: дома на плитах, глина двигается, жёсткая вода. 11 округов. PHCC | "$55 Off", ночь и выходные без доплаты, рассрочка | Нет | "a technician is sent the same day"; минуты только в отзывах |
| 6 | JMP | 16 H2 (5 с McKinney): о фирме, рядом с Downtown, почему мы, "что особенного в McKinney" (глина, корни, жёсткая вода, старые дома), услуги, города, FAQ | Самая местная. Районы: Historic Downtown, Eldorado, Stonebridge Ranch, Trinity Falls, Painted Tree. До 2000 чугун и медь, после PEX. NTMWD, "14 to 16 grains per gallon". Корни, пик slab leak летом. Какая работа требует разрешения города | "$150 to $500" за вызов, "$1,500 to $15,000+" за крупное, выезд "$86", снимается при ремонте | Нет | "Same-day dispatch is available" |
| 7 | Legacy | 7 H2, все с McKinney: фирма против одиночки, рост города, частые ремонты, газ, вода, недавние работы | 200 000+ жителей, 67% домов после 2000. Газ Atmos или CoServ. Вода NTMWD. Полив запрещён с 10 до 18, скидка на контроллер полива. Утечка от счётчика до дома на хозяине. Город меняет 14 000+ медных вводов на пластик. Ссылки на mckinneytexas.org | "free service call for new customers", скидка 5% по плану | Нет. "Best Customer Service Guarantee" | "We will show up on time." |
| 8 | Hackler | 5 H2 (3 с McKinney): знакомство, рейтинг, услуги, "fast, affordable", блог | "We live and work in McKinney"; второй адрес Pottsboro | "service call charge is perhaps the lowest in McKinney", без цифры | "warranted and guaranteed", без срока | "On Time Guarantee", "Same-day service is often available" |
| 9 | Jimmy Cash's | 6 H2: бесплатная оценка по телефону, перебьём смету на 10% | "the last 20 years" в McKinney | Бесплатная оценка, "beat any written bid by 10%" | Нет | Нет |
| 10 | Genzel | 2 H2 без McKinney, дальше H3: услуги, клубная карта, FAQ | С 2001, "25 years in Collin County" | Клубная карта "$27 a month or $282 a year", скидка 15% | "a warranty that stands behind the repair", без срока | "Track Your Plumber", членам запись "within 24 hours" |

Адреса офисов в McKinney (индексы): Baker 75070, Bewley 75069, Cr Plumbing 75070, Roto-Rooter 75070, JMP 75069, Hackler 75069, Jimmy Cash's 75071, Genzel 75071.

Сводка: цены за работу в цифрах даёт одна страница (JMP), купоны, скидки и клубные карты пять. Срок гарантии не называет никто. Минуты и часы приезда в своём тексте не обещает никто; ближе всех Genzel (запись в течение 24 часов для членов клуба) и история Baker ("by lunchtime"). "Same day" в своём тексте у шести, "on time" у четырёх. Ссылку на официальный источник ставит одна страница (Legacy: mckinneytexas.org, atmosenergy.com); на TSBPE, NTMWD, EPA никто.

### 3. Какие местные факты не называет никто

Проверено поиском слов по всем десяти сохранённым текстам (с меню, подвалом и отзывами).

1. Давление в цифрах: "PSI" ни у кого. PRV общими словами у Roto-Rooter, у Legacy строкой в списке работ. Где стоит редуктор, закопан ли он, что показывает манометр: ни слова.
2. Ящик у счётчика. "valve box", "meter box" нет ни у кого. Счётчик упоминают четыре (Baker, Roto-Rooter, Legacy, Genzel), как по счётчику найти утечку, не объясняет никто.
3. Ремонт под плитой. "post-tension", "braze", "type L" нет ни у кого, "tunnel" одной фразой у Baker. Что дома на плитах, пишут JMP и Roto-Rooter, как чинят под плитой, никто.
4. Чердак: "attic", "pan", "expansion tank" нет ни у кого; клапан сброса давления только в общих словах Roto-Rooter.
5. Инспектор города. Какая работа требует разрешения, пишет только JMP. Что проверяет инспектор McKinney на замене водонагревателя, не пишет никто; регистрацию подрядчика в городе не упоминает никто.
6. Полив и обратный клапан: backflow строкой в списке услуг у Cr Plumbing; полив только у Legacy (часы и скидка), и та поливом не занимается. Замену клапана с разрешением города не описывает никто.
7. Мороз: что ломается в мороз, не пишет никто (у Legacy только "rain and freeze sensor").
8. Сток кондиционера в сливе раковины ("condensate"): ни у кого.
9. Канализация до города: "cleanout", "property line", "city side", "smoke test" ни у кого. Корни у Baker и JMP, где кончается линия хозяина, никто.
10. Индексы списком: ни у кого. 75069, 75070, 75071 только в адресах офисов, 75072 нигде.
11. Вода: NTMWD у JMP и Legacy; Lavon Lake ни у кого; цифра жёсткости только у JMP; хлор и хлорамин ни у кого.
12. Трубы по годам: "polybutylene" ни у кого, оцинковка в общих словах у Roto-Rooter; годы и материалы только у JMP (до 2000 и после), у Legacy доля домов после 2000.
13. Настоящие вызовы в McKinney: подробного рассказа о своей работе нет ни у кого. У Baker одна история без проверяемых деталей, у Legacy шесть названий работ без текста.
14. Улицы и ориентиры: кроме адресов офисов только State Highway 121, Historic Downtown и Wilson Creek.

Уже занято, не будет только нашим: районы (Baker семь, JMP пять), глина и плиты (JMP, Roto-Rooter), жёсткая вода (JMP с цифрой, Roto-Rooter словами), NTMWD (JMP, Legacy), полив и замена вводов городом (Legacy), разрешения города (JMP).

Важно для нашей страницы:

- Правило вызова уже не только наше: JMP пишет выезд "$86", снимается при ремонте, цена до начала работ. Наше отличие: $49 в будни, засчитывается в ремонт, доплата вечером, в выходные и праздники называется по телефону до выезда.
- Человек с именем есть у четырёх (Bewley, JMP, Genzel, Hackler в ответах на отзывы). Блок с Денисом здесь не редкость; отличие должно быть в содержании: что он сам делал на вызовах.

Факты для нашей страницы: от Дениса или с официальных страниц города (секция 6a); здесь не проверены.

### 4. Структура: длина, разделы, FAQ

Длина основного текста по возрастанию: 449, 827, 931, 963, 1 070, 1 125, 1 176, 1 820, 2 320, 3 121 слово. Середина около 1 100, среднее 1 380. Без отзывов Roto-Rooter 1 991, Hackler 855. Наша нынешняя страница (1 891) длиннее восьми из десяти; с 2 500 словами своего текста будем длиннее всех, кроме Roto-Rooter с лентой отзывов.

Три типа: шаблон сети (Baker, Milestone, Roto-Rooter, Legacy: услуги абзацами, авария 24/7, "почему мы"; местный раздел у двух последних); длинная главная местной фирмы (JMP, Hackler); короткая главная (Bewley, Cr Plumbing, Jimmy Cash's, Genzel: 450 до 970 слов, год основания, купоны, форма).

Почти у всех: телефон в тексте (все десять), год основания или стаж (восемь), "family owned" (шесть), купоны, скидки или клубная карта (шесть). Tankless у семи, газ у пяти, repipe у четырёх, hydro jetting у трёх. "McKinney" в каждом H2 у Roto-Rooter и Legacy, у Genzel ни в одном.

FAQ у трёх страниц, всего 28 вопросов: у Roto-Rooter тегами H3, у JMP и Genzel обычным текстом. Дословно:

Roto-Rooter (9): "Does Roto-Rooter handle the cleanup after water damage, or just the plumbing repair?"; "What causes low water pressure throughout the whole house?"; "If a pipe bursts or a major leak starts, can I get a plumber out in the middle of the night?"; "My water heater is making a rumbling noise - is that serious?"; "My kitchen sink drains slowly even after I've tried drain cleaner - what's actually going on?"; "How bad is water damage if I don't dry it out quickly?"; "What is hydro jetting and when does a drain need it instead of a standard snake?"; "How do I know if I have a hidden water leak behind my walls?"; "What are the most common plumbing problems in McKinney?"

JMP (11): "How much does a plumber cost in McKinney, TX?"; "What is your trip fee?"; "Do you offer same-day plumbing service in McKinney?"; "Are you a licensed plumber in McKinney?"; "Do I need a permit for plumbing work in McKinney?"; "How do I know if I have a slab leak?"; "Does homeowners insurance cover slab leak repair in Texas?"; "Why do slab leaks and sewer breaks spike in North Texas summers?"; "How long does a whole-house repipe take?"; "Are you woman-owned?"; "Do you do commercial plumbing in McKinney?"

Genzel (8): "What areas does Genzel Plumbing serve?"; "Are your plumbers licensed and insured?"; "Do you offer emergency plumbing service?"; "Do you give upfront pricing and estimates?"; "Do you repair and install water heaters?"; "Can I track my plumber or get arrival updates?"; "Do you handle main sewer line clogs and tree roots?"; "What is the Genzel Guardian Plan?"

У Baker, Bewley, Milestone, Cr Plumbing, Legacy, Hackler, Jimmy Cash's FAQ нет.

Пересечения с нашими нынешними вопросами (шесть, снимок старой страницы):

- Наш "How much does a plumber cost in McKinney, TX?" слово в слово первый вопрос JMP. Это единственное совпадение 8 слов подряд нашего текста (старый снимок и site/src/content/pages/plumber-mckinney-tx.md) с десятью страницами (правила tools/check_overlap.py, своим скриптом). В новом тексте спросить иначе.
- Не начинать вопрос с "How do I know if I have a": так начинаются вопросы JMP и Roto-Rooter.
- Наш "Do you charge extra after hours?" по теме встречается с доводом Roto-Rooter "no extra charge for nights, weekends, or holidays"; ответ у нас обратный.
- Ни у кого нет вопросов про давление в PSI, обратный клапан на поливе, мороз, водонагреватель на чердаке; наши вопросы про ощущение slab leak и про измельчитель тоже уникальны.

### 5. Шаблоны title и H1

Title (дословно в 2.2):

- Ключ первым у семи: "Plumber in McKinney (,) TX" (Baker, JMP), "McKinney Plumber" (Milestone, Roto-Rooter), "Trusted Plumber (in) McKinney, TX" (Cr Plumbing, Legacy), "Plumbers in McKinney, TX" (Genzel). Имя фирмы первым у трёх (Bewley, Hackler, Jimmy Cash's).
- Хвост это оценка себя или приманка: "Trusted" (два), "Best" и "A+ Rated" (Hackler), "$55 Off" (Roto-Rooter), "Family-Owned Since 2001" (Genzel), "Residential & Commercial" (JMP), "Local Plumbing Repairs!" (Milestone без офиса в McKinney).
- Работу в title называет только Roto-Rooter ("Plumbing & Drain"). Телефона в title у десятки нет. Длина 45 до 77 знаков.

H1:

- Короткие из ключа: "Plumber in McKinney" (Milestone), "Plumber in McKinney, TX" (JMP), "McKinney, TX Plumbing Services" (Legacy), "Your McKinney Plumbing Experts" (Cr Plumbing). Остальные с именем фирмы, оценкой ("Best Plumber in McKinney TX") или годом основания.
- Два H1 у Baker и Hackler, у Jimmy Cash's H1 нет. Работы в H1 называет только Roto-Rooter.

Наши нынешние (снимок): title "Plumber in McKinney, TX | Slab Leak & Garbage Disposal Repair" (61 знак), H1 "Plumbing Repair in McKinney, TX - Slab Leaks, Water Heaters, Drains and Disposals". Начало как у JMP (это ключ), дальше только мы называем сами работы. Решает Search Console; со стороны конкурентов причин менять нет. Не брать: "Trusted", "Best", "Experts", "A+ Rated", "Family-Owned", купон, телефон.

Приёмы конкурентов, которые нам нельзя (tankless, газ, repipe, hydro jetting, reroute, бесплатные сметы, вилки цен, "financing", телефоны в тексте, соседние города, "on time", слово "Owner", PHCC, вопросы FAQ заголовками): приложение, раздел З.

### 6. Папка для проверки на совпадения

`source/competitors/2026-10-03-mckinney/`: `00.txt` до `09.txt` в порядке таблицы раздела 1, формат как у Plano (первая строка адрес, вторая весь текст страницы одной строкой: title, меню, текст, подвал, карусели и окна). `tools/check_overlap.py` я не запускал (правило ночи); чтение папки по его правилам проверено своим скриптом. Команда для будущего черновика: `python3 tools/check_overlap.py <черновик> source/competitors/2026-10-03-mckinney`.

## 4. Фото и клипы

Источник: `docs/briefs/_shared/photos-by-city-after-recount.json` (204 записи архива; снимок 02:03, прочитан 3 октября 2026). Город «после пересчёта» в этом файле поставлен по черте города (basis "city boundary"), по слову Дениса ("Denys's word") или снят, если место съёмки вне десяти городов. Слово Дениса о городе главнее проверки по карте. Координат в файле нет, и в брифе их нет. Сверено с `docs/briefs/_shared/cities-free-photos-2026-10-03.md` (строка McKinney: 14 фото, 9 клипов; свободны фото 7, 33, 34, 51, 71, 73, 98, 103, 139, 140, 158, 196 и все 9 клипов), с `photos/captions-en.csv` (файл от 10:23), с частью 1 (раздел 4 и таблица Т7 в `1-live-page-tables.md`) и с частью 8 (раздел 2 и `8-links-details.md`, часть В). Где стоят 99 и 141, проверено ещё поиском по `site/src`: их файлы есть только в плитках главной (`site/src/design/home-text.json`, `home-services.html`, `design.json`).

После пересчёта за McKinney числятся 23 файла: 14 фото и 9 клипов. По слову Дениса только два, 195 и 196 (одна работа, laundry box). Остальные 21 по черте города; у семи из них город до пересчёта был другим (51 и 103 Prosper, 71, 73, 190 и 191 Allen, 180 Prosper), у шести города не было (63, 64, 74, 158, 13 и 14; у клипов 13 и 14 нет и подписи), у восьми он и раньше был McKinney (7, 33, 34, 98, 99, 139, 140, 141). В диктовках Дениса (`source/dictation/`) про McKinney записана только работа laundry box (`2026-10-02-frisco-additions.md`, раздел "McKinney: the laundry box valve"; ещё одна строка в `2026-10-02-frisco-reserve-for-service-pages.md`: случай ждёт и страницу leak detection).

### 4.1. Все файлы, у которых город после пересчёта McKinney

Колонка «Что сказал Денис» дана как в файле, по-русски. Подпись дана как в файле, по-английски. «Где стоит» это колонка stands_on_built_pages. «Отложено для» это колонка planned_pages. Пометки (flags) даны как в файле, по-английски.

| № | Вид | Дата | Основание (город до пересчёта) | Что сказал Денис | Подпись (англ.) | Где стоит на собранном сайте | Отложено для | Пометки |
|---|---|---|---|---|---|---|---|---|
| 7 | фото | 2026-09-29 | черта города (McKinney) | Замененный PRV (pressure reducing valve) | Replaced PRV (pressure reducing valve), McKinney | нигде | /prv-replacement-frisco-plano/ /plumber-mckinney-tx/ | нет |
| 13 | клип | 2026-09-30 | черта города (без города) | Видео, Денис не помнит что это | нет | нигде | нет | нет |
| 14 | клип | 2026-09-30 | черта города (без города) | Видео, Денис не помнит что это | нет | нигде | нет | нет |
| 33 | фото | 2026-07-29 | черта города (McKinney) | Ржавый фланец унитаза, сломанное восковое кольцо, унитаз снят | Rusted toilet flange, broken wax ring, toilet pulled, McKinney | нигде | /toilet-repair-frisco-plano/ /blog/toilet-replacement-with-new-shutoff-valve-and-wax-ring/ /plumber-mckinney-tx/ | нет |
| 34 | фото | 2026-07-29 | черта города (McKinney) | Новый фланец, новое восковое кольцо, новые болты | New flange, new wax ring, new bolts, McKinney | нигде | /toilet-repair-frisco-plano/ /blog/toilet-replacement-with-new-shutoff-valve-and-wax-ring/ | нет |
| 51 | фото | 2026-09-17 | черта города (Prosper) | Замена PRV во flower bed | PRV replaced in a flower bed, Prosper | нигде | /prv-replacement-frisco-plano/ /plumber-prosper-tx/ | нет |
| 63 | клип | 2025-09-17 | черта города (без города) | Пинхол на PEX трубе у манифолда на чердаке, из-за него утечка | Pinhole on PEX at the manifold in the attic, the cause of the leak | нигде | /water-leak-detection-frisco-plano/ | Video, no slider. |
| 64 | клип | 2025-09-17 | черта города (без города) | Манифолд заменен полностью, все переподключено | Manifold replaced completely, everything reconnected | нигде | /water-leak-detection-frisco-plano/ | Video. |
| 71 | фото | 2026-04-01 | черта города (Allen) | Washing machine outlet box, клапаны не работают | Washing machine outlet box, the valves do not work, Allen | нигде | /fixture-installation-repair/ /plumber-allen-tx/ | нет |
| 73 | фото | 2026-04-01 | черта города (Allen) | Заменили washing machine outlet box с новыми клапанами | Washing machine outlet box replaced, new valves, Allen | нигде | /fixture-installation-repair/ /plumber-allen-tx/ | нет |
| 74 | клип | 2024-11-13 | черта города (без города) | Milwaukee snake: пробиваем дренажную линию душа | Milwaukee snake clearing the shower drain line | нигде | /clogged-drain-cleaning-frisco-plano/ | Video. |
| 98 | фото | 2024-12-30 | черта города (McKinney) | Сломанная душевая система в ванне, две ручки и излив, старая непонятная фирма | Broken tub and shower set, two handles and a spout, old unknown brand, McKinney | нигде | /fixture-installation-repair/ /plumber-mckinney-tx/ | нет |
| 99 | фото | 2024-12-30 | черта города (McKinney) | Вскрыли немного плитку, в стене перепаяли на Moen с одной ручкой: замена двух ручек на одну | Small tile opening, new single handle Moen soldered in: two handles to one, McKinney | / /fixture-installation-repair/ | /fixture-installation-repair/ /plumber-mckinney-tx/ | нет |
| 103 | фото | 2025-01-06 | черта города (Prosper) | Заменен garbage disposal Moen 3/4 л.с. и сливная линия под раковиной; пол шкафа поврежден, старый диспоузер долго тек | New Moen 3/4 HP disposal and drain line; a long leak damaged the cabinet floor, Prosper | нигде | /garbage-disposal-repair-frisco-plano/ /plumber-prosper-tx/ | нет |
| 139 | фото | 2024-07-01 | черта города (McKinney) | Бачок унитаза: сломаны fill и flush valve | Toilet tank: broken fill and flush valves, McKinney | нигде | /toilet-repair-frisco-plano/ /plumber-mckinney-tx/ | Wide shot versus close up: not a clean slider. |
| 140 | фото | 2024-07-01 | черта города (McKinney) | Новый flush valve, бачок снят | New flush valve, tank removed, McKinney | нигде | /toilet-repair-frisco-plano/ | нет |
| 141 | фото | 2024-07-01 | черта города (McKinney) | Бачок установлен на место, новые fill и flush valve | Tank back in place, new fill and flush valves, McKinney | / /toilet-repair-frisco-plano/ | /toilet-repair-frisco-plano/ /plumber-mckinney-tx/ | нет |
| 158 | фото | 2024-08-15 | черта города (без города) | Под тротуаром протягиваем новую водяную линию PEX | Pulling a new PEX water line under the sidewalk | нигде | /water-lines/ /plumbing-guide/water-leak-yard-tips-2026/ | нет |
| 180 | клип | 2025-11-15 | черта города (Prosper) | Про спауты (tub spout): из-за жесткой воды они тоже со временем перестают работать, нарастает кальций, резинки и пластик внутри он съедает; переключаешь на душ, а вода течет и из спаута, и из душа | The diverter is gone: switched to the shower, water runs from the tub spout and the shower head at once, Prosper | нигде | /fixture-installation-repair/ | Video, 15 s. For the faucet and shower valve page, not on the Frisco page (Prosper by its location). An arm with a watch in the frame, no face. |
| 190 | клип | 2024-11-19 | черта города (Allen) | Кейс: унитаз забит полностью, только местный унитаз. На видео огер шестифутовый, которым пробили. Просто кто-то смыл много туалетной бумаги, оно забилось. Запомни себе кейс, куда-нибудь потом | A six foot toilet auger clears a toilet packed with paper, Allen | нигде | /toilet-repair-frisco-plano/ /plumber-allen-tx/ | Video, 6 s, not placed yet (Denys: keep the case). Shoes of the plumber in the frame. |
| 191 | клип | 2024-11-19 | черта города (Allen) | то же, что у 190 | The toilet before: clogged solid with toilet paper, Allen | нигде | /toilet-repair-frisco-plano/ | Video, 6 s, not placed yet. Waste in the bowl: think before using. |
| 195 | клип | 2024-12-03 | слово Дениса (McKinney) | Кейс в McKinney: у человека пол вздулся и захлюпал, плинтусы вздулись, в зале и в спальне. Никто не мог понять, кто-то уже приезжал и не разобрался. Оказалось: посреди дома laundry, в laundry box с кранами, и на бронзовом кране появился пинхол, с него капала вода внутрь стены, очень медленно, но постоянно, месяцами, все позатапливало, пока мы не приехали и не разобрались. Фото, где капает и пол поврежден с плинтусом, и видео | The laundry box in the wall: the brass valve that dripped inside the wall for months, McKinney | нигде | /plumber-mckinney-tx/ /water-leak-detection-frisco-plano/ | Video, 9 s, not placed yet. |
| 196 | фото | 2024-12-02 | слово Дениса (McKinney) | то же, что у 195 | What showed up in the rooms: a swollen floor and baseboard, months of a slow leak, McKinney | нигде | /plumber-mckinney-tx/ /water-leak-detection-frisco-plano/ | Not placed yet. A watch on the wrist in the frame. |

| № | Подпись в `photos/captions-en.csv` (10:23) | Страницы там же (колонка pages) |
|---|---|---|
| 51 | PRV replaced in a flower bed, McKinney | /prv-replacement-frisco-plano/ /plumber-mckinney-tx/ |
| 63 | Pinhole on PEX at the manifold in the attic, the cause of the leak, McKinney | /water-leak-detection-frisco-plano/ |
| 64 | Manifold replaced completely, everything reconnected, McKinney | /water-leak-detection-frisco-plano/ |
| 71 | Washing machine outlet box, the valves do not work, McKinney | /fixture-installation-repair/ /plumber-mckinney-tx/ |
| 73 | Washing machine outlet box replaced, new valves, McKinney | /fixture-installation-repair/ /plumber-mckinney-tx/ |
| 74 | Milwaukee snake clearing the shower drain line, McKinney | /clogged-drain-cleaning-frisco-plano/ |
| 103 | New Moen 3/4 HP disposal and drain line; a long leak damaged the cabinet floor, McKinney | /garbage-disposal-repair-frisco-plano/ /plumber-mckinney-tx/ |
| 158 | Pulling a new PEX water line under the sidewalk, McKinney | /water-lines/ /plumbing-guide/water-leak-yard-tips-2026/ |
| 180 | The diverter is gone: switched to the shower, water runs from the tub spout and the shower head at once, McKinney | /fixture-installation-repair/ |
| 190 | A six foot toilet auger clears a toilet packed with paper, McKinney | /toilet-repair-frisco-plano/ /plumber-mckinney-tx/ |
| 191 | The toilet before: clogged solid with toilet paper, McKinney | /toilet-repair-frisco-plano/ |

Подписи и страницы общего файла взяты из снимка 02:03. В `photos/captions-en.csv` (10:23) у одиннадцати файлов они уже другие: город в подписи McKinney, страница другого города из плана снята. Вторая таблица выше показывает их так, как они записаны там сейчас. Пометка у 180 "(Prosper by its location)" осталась от старого способа: по CLAUDE.md с 3 октября город фото берётся по черте города.

Что видно по таблице:

- Свободны 21 файл из 23. Стоят на собранном сайте только 99 (две ручки на одну, Moen) и 141 (бачок с новыми fill и flush valve): оба плитками услуг на главной и на своих страницах услуг. Правила не запрещают одному фото стоять на нескольких страницах.
- `photos/captions-en.csv` (10:23) ставит на страницу McKinney тринадцать файлов: 7, 33, 51, 71, 73, 98, 99, 103, 139, 141, 190, 195, 196.
- 195 и 196 это единственная работа в McKinney, которую назвал Денис, и она уже надиктована: пол и плинтусы вздулись в гостиной и спальне, кто-то уже приезжал и не нашёл, прачечная посреди дома, пинхол на латунном кране в laundry box, капало внутрь стены месяцами. Оба кадра показывают проблему (кадра «после» в архиве нет), это верно по правилу «история, названная по проблеме, сначала показывает проблему». Клип 195 длится 9 секунд: по правилам режется до пяти секунд, без звука, крутится сам. На 196 видны часы на руке. Денис записал этот случай и для страницы leak detection: одна страница рассказывает его целиком, другая одной фразой со ссылкой, текст не повторяется.
- 7 и 51 (PRV, сентябрь 2026) это кадры «после». Для истории про давление нужен кадр проблемы или слова Дениса.
- 139, 140 и 141 одна работа (1 июля 2024): сломанные fill и flush valve, новый flush valve, бачок на месте. По пометке 139 и 141 сняты по-разному (общий план и крупно), чистого «до и после» в слайдере не будет. 33 и 34 одна работа (29 июля 2026): ржавый фланец и новый.
- 98 и 99 одна работа (30 декабря 2024): старый набор на две ручки и новый Moen с одной ручкой через небольшое окно в плитке.
- 71 и 73 (1 апреля 2026): outlet box стиральной машины, клапаны не работали, заменён. Это другая работа, не laundry box из 195 и 196: в одной истории их не смешивать.
- 190 и 191 (19 ноября 2024): унитаз, забитый бумагой, шестифутовый auger. По пометкам в кадре обувь сантехника, у 191 содержимое унитаза («think before using»).
- 13 и 14: Денис не помнит, что на них. Без его слова не использовать.

Ещё про фото McKinney вне этого файла:

- Главное фото живой страницы: фургон Ram у бордюра на улице с кирпичными домами, `/wp-content/uploads/2025/05/photo_2025-05-15_20-41-45-1024x576.jpg`, alt "FPP Plumbing truck in McKinney during same-day plumbing service" (часть 1, раздел 4). В архиве этого кадра нет; он из той же выгрузки, что фургоны на других городских страницах, у каждого свой город в alt. На крыле "M-38532" (на сайте лицензия M-44816), на борту телефон Plano, номерного знака и номеров домов не видно. Новый сайт ставит его главным фото страницы, alt тот же.
- Девять старых фото галереи с McKinney в подписи (часть 8, `8-links-details.md`, часть А): старый PRV и главный кран перед заменой; два газовых водонагревателя и расширительный бак в гараже; водонагреватель с баком на чердаке; замер давления на уличном кране; старая и новая ручка смыва коммерческого унитаза (два кадра); корни из линии унитаза; ванна, прочищенная Milwaukee M18; новый диспоузер Moen. Их нет в `photos/index.csv`, место съёмки никто не проверял.
- Фото фургона в архиве: 1, 2, 3, 4 у офиса Frisco (слово Дениса) и 202 у офиса Plano (сборное фото). Фото 2 и 4 Денис 1 октября разрешил ставить вместо фото с работы на страницах Celina и Lewisville ("stand in for Celina and Lewisville until job photos from there"), alt там не называет Frisco. Для McKinney такого слова нет.

### 4.2. Кандидаты по темам страницы

Темы взяты из живой страницы (часть 1), из запросов (часть 2), из того, чего нет у конкурентов (часть 3), и из официальных фактов (часть 6). Правила из CLAUDE.md: история, названная по проблеме, сначала показывает проблему, потом ремонт; клип режется примерно до пяти секунд, без звука, крутится сам, без кнопок; все картинки одного размера, 3:4; номерной знак размывается; на странице города стоят работы из этого города.

| Тема страницы | Файлы | Что с ними делать |
|---|---|---|
| Первый экран: фургон или работа в McKinney | нет | Нынешнее фото фургона городом не подтверждено, на крыле "M-38532", на борту телефон Plano. Нужен настоящий кадр (4.3). Ставить ли пока фото 2 или 4 (фургон у офиса Frisco), решает Денис |
| Скрытая течь, история с вызова (лучший живой материал страницы) | 195, 196 | Короткая история со ссылкой на `/water-leak-detection-frisco-plano/`: 196 (вздутый пол и плинтус) и пять секунд клипа 195 рядом под текстом. Город назвал Денис |
| Давление и PRV («low water pressure plumber mckinney» 580 показов за 16 месяцев, слова low на странице нет; город про PRV молчит) | 7, 51 | Строка или короткая история со ссылкой на `/prv-replacement-frisco-plano/`. Оба кадра «после»: нужен кадр проблемы и слова Дениса (что было на манометре) |
| Линия от счётчика к дому (H2 "Main Water Line Repair in Older McKinney Homes", 1,416 показов за 16 месяцев) | 158 | PEX под тротуаром (15 августа 2024). Записан для `/water-lines/` и гида про двор. С какой работы, неизвестно; для истории с деревом кадров нет |
| Унитаз («toilet repair mckinney» 218 показов за 16 месяцев) | 139, 140, 141; 33, 34; клипы 190, 191 | Одна пара «до и после» или клип 190 в строке про унитаз со ссылкой на `/toilet-repair-frisco-plano/`. 141 уже стоит на главной и на странице унитаза |
| Смеситель и клапан душа («mckinney faucet repair» 290, «faucet repair mckinney» 259 показов за 16 месяцев; слова faucet в тексте нет) | 98, 99; клип 180 | 98 и 99 пара «до и после» (99 уже на главной и на странице услуги). 180 (дивертер, 15 секунд, рука с часами) записан для страницы смесителей |
| Измельчитель (title, H2 "Garbage Disposals, and When to Stop Repairing Them") | 103 | Moen 3/4 HP и новая сливная линия, пол шкафа испорчен долгой течью. На страницу города одним предложением со ссылкой; слова про 1/3 и 1/2 HP от застройщика только со слова Дениса |
| Стиральная машина | 71, 73 | Пара «до и после». Отдельная работа, к истории laundry box не приклеивать |
| Сливы | клип 74 | Milwaukee snake в линии душа, записан для `/clogged-drain-cleaning-frisco-plano/` |
| Скрытая течь на чердаке | клипы 63, 64 | Пинхол на PEX у манифолда, манифолд заменён. Записаны для leak detection; на страницу McKinney только если Денис захочет вторую историю |
| Водонагреватель и расширительный бак (H2 "Water Heaters and the Tank Nobody Mentions"; город: T&P, бак, поддон) | нет | Ни одного кадра из McKinney в архиве. В галерее старого сайта есть подписи с McKinney (водонагреватели и бак в гараже и на чердаке): только со словом Дениса |
| Slab leak, старая медь и чугун у центра, канализация, emergency, уличный кран и мороз, обратный клапан на поливе | нет | Ни одного кадра из McKinney |
| 13, 14 | клипы | Денис не помнит, что на них: не использовать |

В архиве есть 37 файлов без города (22 фото и 15 клипов). Для страницы McKinney они не предлагаются: на странице города стоят работы из этого города.

### 4.3. Чего не хватает: какие кадры просить у Дениса

1. Настоящее фото с работы в McKinney или фургон FPP на улице в черте города. Кадр вертикальный, чтобы встал в размер 3:4; без номеров домов; номерной знак мы размоем. Это замена нынешнему главному фото.
2. Давление: манометр на уличном кране дома в McKinney с цифрой; для работ с фото 7 и 51 старый PRV до замены (кадр проблемы).
3. Линия от счётчика к дому: ящик счётчика и кран хозяина; если работа с деревом была в McKinney, яма, повреждённая медь и новый участок; для фото 158, если это работа из гида про двор, место утечки.
4. Дом у исторического центра: чугунная канализация или старая медь, экран камеры с корнями в главной линии.
5. Замена водонагревателя в McKinney, «до» и «после»: трубка T&P, поддон со сливом, расширительный бак (то, что город перечисляет для готовности к инспекции).
6. Работа laundry box (195, 196): кадр после ремонта, новый кран или коробка, если он есть.
7. Измельчитель с фото 103: старый текущий агрегат до замены.
8. Обратный клапан на поливе, заменённый в McKinney (только замена; проверка не наша).

## 5. Отзывы: кандидаты

Файл раздела: `docs/briefs/mckinney/5-review-candidates.md`, вставлен целиком. Заголовок файла: «5. Отзывы: кандидаты для страницы McKinney».

Рядом и в бриф не вставлен: `5-review-candidates-tables.md` (42 КБ: как искали McKinney и его районы, кто отсеян и почему поимённо, все 145 чистых отзывов, 23 отзыва запаса дословно, списки по видам работ, полный текст LXD Properties).

Раздел для брифа `/plumber-mckinney-tx/`. На страницы ничего не поставлено: выбирает чат, который пишет страницу, живая проверка после выбора. Длинные списки (как искали McKinney и его районы; кто отсеян и почему, поимённо; все 145 чистых; запас за десяткой дословно; отзывы по видам работ) лежат рядом: `docs/briefs/mckinney/5-review-candidates-tables.md`.

### Коротко

- **Пятизвёздочных отзывов, где назван McKinney, его улица, район или индекс: 1 на весь архив.** Это Ezzy Zhoo (Google, профиль Plano, март 2025): "permit requirements for city of mckinney". На новом сайте он свободен, но правила не проходит: имя Дениса два раза ("Denys of FPP", "I hired Denys"), кроме того "rerouting of vents and water lines" и "gas line". **Свободных и чистых отзывов с McKinney: 0.**
- Поэтому все десять кандидатов ниже из отзывов без места: **ни один не привязан к McKinney**. Те же отзывы этой ночью предлагают для своих городов другие помощники (столбец "Ещё предложен"); только Rangsan L. и Thomas S. не стоят ни в одной другой десятке.
- Свободных пятизвёздочных с текстом 330. По всем правилам для страницы города проходят 145, работу в них называют 27, ещё у двух работа названа общо.
- Живая страница McKinney: три отзыва, оставить нельзя ни один. LXD Properties со 2 октября стоит на новой странице Frisco (один автор на одну страницу). Ezzy Zhoo и Victoria Nwanegbo называют Дениса по имени.
- По главным темам McKinney чистых отзывов почти нет: измельчитель 2 (Rangsan L., Sathya P.), водонагреватель 1 (alex p, без слова замена), скрытая течь 1 (Javeed N.). Slab leak, главный водопровод, давление воды и PRV, расширительный бак, канализационная линия, пермит и инспекция города: 0.

### Откуда данные

- `reviews/all-reviews.csv` (04:53 3 октября): 407 отзывов, Google 131 (профиль Plano 105, Frisco 26), Thumbtack 249, Yelp 27.
- Занятые: `reviews/site-reviews.json` (10:04) и `reviews/site-ledger.md` (04:54), прочитаны около 11:10: 40 авторов на 14 страницах, файлы совпадают, страницы McKinney нет. Плюс двенадцать главной и три резерва из задания.
- Решения: `reviews/ledger-decisions.csv`, `reviews/ledger.md`, `reviews/proposed-placement.md`, `docs/journal.md`. Живая страница: `source/crawl/pages/plumber-mckinney-tx.json`. Запросы: раздел McKinney в `docs/briefs/_shared/cities-gsc-top-queries-2026-10-03.md` (16 месяцев: 31 мая 2025 по 28 сентября 2026).
- Места McKinney: 937 названий слоя Subdivisions города из `docs/briefs/_shared/cities-official-place-names-2026-10-03.json`, индексы 75069, 75070, 75071, 75072, известные места и улицы; 814 текстов (CSV, Takeout, сырые Thumbtack и Yelp). Подробно: файл таблиц, раздел 1.
- Google кандидатов сверены с Takeout (`source/gbp-takeout/`): слово в слово, пять звёзд, даты и номер отзыва в ссылке совпадают. Thumbtack сверен с `reviews/raw/thumbtack-reviews.json` (оттуда заявка клиента), Yelp с `reviews/raw/yelp-from-pdf.json`. Десятки других городов: `docs/briefs/*/5-review-candidates.md`, восемь городов.

### Сколько свободно

| Шаг | Сколько |
|---|---|
| Всего отзывов / из них пять звёзд | 407 / 396 |
| Минус 6 без текста и 10 копий отзывов Google на Thumbtack | 380 |
| Минус 47 строк занятых (43 человека: двенадцать главной, три резерва, 28 на других страницах нового сайта; у четверых по две строки: tony phuong, Kathryn Kim, Yuliia Novoderezhkina, Stephan S) | 333 |
| Минус 3: тот же человек под другим именем (L W это Liane W., Rani C это Rani ., Lanessa A. это Lanessa Arnold Jenkins) | **330 свободных** |
| Из них называют McKinney или место в нём | **1** (Ezzy Zhoo) |
| Из них проходят правила | **0** |

Отсеивают (строка может попасть в несколько причин): имя Дениса 156; автор на другой странице старого сайта 37; другой город или место 13; суммы, проценты, fee 10; "plumber near me" 8; придержаны для другой страницы 5 (Ann Crawford дважды, expansion tank; Steve Fredrickson и, по имени и дате, Steve F. на Yelp, water heaters; Quan Nguyen, запас hose bib). Остаётся **145 чистых** (Thumbtack 116, Google Plano 20, Yelp 7, Google Frisco 2). Большинство короткие и общие ("Great job", "Excellent work").

### Десять лучших кандидатов

Ни один не называет McKinney, **ни один не привязан к McKinney**. Порядок по темам страницы McKinney (измельчитель в title, течи и slab leak, водонагреватель, смесители, срочные вызовы, засоры, унитаз) и по силе слов о работе. Текст дословный, с опечатками автора.

| Место | Имя | Площадка | Дата | Работа | Место в тексте | Цифра приезда | Текст дословно | Ссылка | Почему | Ещё предложен |
|---|---|---|---|---|---|---|---|---|---|---|
| 1 | Rangsan L. | Thumbtack, листинг Plano | 2023-12-10 (December 2023) | Замена измельчителя и трёх смесителей | нет, не привязан к McKinney | нет | "We hired him to replace a garbage disposal and 3 new faucets. Good work. Good value. Highly recommended." | [ссылка](https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760) | Измельчитель в title и H2 живой страницы ("mckinney tx garbage disposal repair" 102 показа), смесители ("mckinney faucet repair" 290). Нет слова plumber и названия компании. | ни в одной десятке (в запасе у других) |
| 2 | Sathya P. | Thumbtack, листинг Plano | 2023-11-04 (November 2023) | Замена измельчителя, течь под раковиной | нет, не привязан к McKinney | нет | "I had to get the garbage disposal, replaced and also fix the leak under the sink. Both jobs were completed." | [ссылка](https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760) | Второй чистый про измельчитель, плюс течь под раковиной. Сухо. С Rangsan L. вместе не брать. | Celina 7, Lewisville 10, Prosper 8 |
| 3 | Javeed N. | Thumbtack, листинг Plano | 2022-11-06 (November 2022) | Течь, которую трудно найти | нет, не привязан к McKinney | нет | "Response was immediate. They were able to troubleshoot a water leak that was hard to find. Very nice and pleasant to work with." | [ссылка](https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760) | Единственный чистый про скрытую течь ("slab leak detection mckinney" 142, "leak detection mckinney" 107). Самый старый. | Carrollton 3, Celina 5, Lewisville 1, The Colony 5 |
| 4 | alex p | Google, профиль Plano | 2025-01-11 (January 2025) | Нет горячей воды в снежную бурю (ремонт или замена, не сказано) | нет, не привязан к McKinney | нет | "FPP Plumbing provided exceptional service! They quickly responded to our call, arrived promptly, and fixed the issue fast when we had no hot water in this winter snow storm. Their team was professional, efficient, and thorough. Whether it’s plumbing repairs, drain cleaning, or water heater installation, FPP Plumbing delivers top-quality solutions. Highly recommend for reliable, quick, and expert plumbing services." | [ссылка](https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sChdDSUhNMG9nS0VJQ0FnSURmel9Qamh3RRAB!2m1!1s0x0:0xccc66184bdaf3a93) | Единственный чистый про водонагреватель (H2 "Water Heaters and the Tank Nobody Mentions"). Дважды "FPP Plumbing". Конец как реклама (оговорка 4). | Allen 2, Celina 1, Lewisville 9, Little Elm 3, Plano 9, Prosper 2, The Colony 6 |
| 5 | David H. | Thumbtack, листинг Plano | 2023-01-05 (January 2023) | Течь смесителя душа, лопнувшая труба снаружи | нет, не привязан к McKinney | нет | "Was able to fit us in the same day and correctly fix the issues (leaking shower faucet and exterior broken pipe) and answer all questions. Will plan to use again for future plumbing needs" | [ссылка](https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760) | Смесители ("faucet repair mckinney" 259, "mckinney tx faucet repair" 239). Две работы. | Allen 3, Lewisville 5, Little Elm 6, The Colony 8 |
| 6 | Kevin N. | Thumbtack, листинг Plano | 2023-01-04 (January 2023) | Течь в ванной наверху: вода через светильник кухни и стены гаража | нет, не привязан к McKinney | нет | "These guys are life savers. I had a leak in an upstairs bathroom and water was coming out of my light fixture in the kitchen as well as down the walls in my garage. They came out the same day I contacted them and were able to diagnosis and fix the issue. I would and will be contacting them for any other plumbing work that I have." | [ссылка](https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760) | Самая живая картина течи среди свободных. | все восемь других |
| 7 | Phillip Potter | Google, профиль Plano | 2024-12-09 (December 2024) | Срочная работа в воскресенье (какая, не сказано) | нет, не привязан к McKinney | нет | "Awesome service! Came out and completed an emergency job on a Sunday!" | [ссылка](https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sChZDSUhNMG9nS0VJQ0FnSUN2M0llZUdBEAE!2m1!1s0x0:0xccc66184bdaf3a93) | Срочные вызовы ("emergency plumber mckinney tx" 345, "emergency plumber mckinney" 340). Google. 12 слов. | Prosper 5 |
| 8 | Thomas S. | Thumbtack, листинг Plano | 2023-02-24 (February 2023) | Раковина поздно ночью (в заявке Thumbtack засор) | нет, не привязан к McKinney | нет | "Came out late at night and fixed our sink!" | [ссылка](https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760) | Засор ночью ("clogged drain plumber mckinney" 185). 9 слов. | ни в одной десятке (в запасе у других) |
| 9 | Ryan E. | Thumbtack, листинг Plano | 2023-03-30 (March 2023) | Унитаз: нашёл причину и заменил детали | нет, не привязан к McKinney | нет | "Great job! Quickly identified the issue with my toilet, and got the necessary parts replaced. I'll be saving their number for all of my future plumbing needs. Thanks again!" | [ссылка](https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760) | Унитаз ("toilet repair mckinney" 218). Один из двух чистых про унитаз. | Celina 8, Little Elm 10, Prosper 3 |
| 10 | Dr. Jalal Jalali | Google, профиль Plano | 2025-07-08 (July 2025) | Замена крана стиральной машины | нет, не привязан к McKinney | ДА: "the same day in less than an hour" | "I called several plumber for replacement of a washer machine valve and this FPP plumbing  compony was the only  one that his price was a lot reasonable than the others. He came the same day in less than an hour. Very professional i highly recommend them and I will use them again for any pluming work." | [ссылка](https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sCi9DQUlRQUNvZENodHljRjlvT2xOTFpEQlVhbmxvY0ZoRk4wSTNhbGc0Um10WmJrRRAB!2m1!1s0x0:0xccc66184bdaf3a93) | Слова "plumber" и "FPP plumbing", цена без сумм. Опечатки автора остаются. | Allen 6, Carrollton 10, Celina 4, Little Elm 1, Plano 4, The Colony 1 |

Ссылки Google ведут на сам отзыв (из файла, вживую не открывались); у Thumbtack ссылка на общий листинг, как на других страницах сайта. Площадки: Thumbtack 7, Google 3, Yelp 0. В скобках у Thumbtack слова из заявки клиента: на странице их нет, они только помогают понять работу.

#### Оговорки

1. **Подпись без города** (правило 11): Google "★★★★★ · Local Guide Level N · Month Year · Google", Thumbtack "★★★★★ · Thumbtack · Month Year". Уровень Local Guide у alex p, Phillip Potter, Dr. Jalal Jalali в файле пуст: читать в профиле.
2. **Цифра приезда** только у Dr. Jalal Jalali: слова клиента, разрешены, аудитор отметит.
3. **Семь из десяти с Thumbtack 2022 и 2023 годов**: чистых Thumbtack с работой позже 2023 года нет. Свежие чистые с работой только у Google и Yelp: A P (август 2026), Stacie B. (июль 2026), Dr. Jalal Jalali, Rob C., alex p, Phillip Potter.
4. **alex p**: вторая половина ("Whether it’s plumbing repairs, drain cleaning, or water heater installation, FPP Plumbing delivers top-quality solutions.") как реклама. Запретного нет.
5. **Yelp в десятке нет.** Работу называют только Stacie B. (уличный кран, "within an hour") и Rob C. (фильтрация воды в новом доме, не основная услуга); оба в запасе, с ними Jaime D.
6. **Пересечение.** Kevin N. стоит во всех восьми других десятках, alex p в семи, Dr. Jalal Jalali в шести. Ближе к McKinney и меньше спорные: Rangsan L. и Thomas S. (ни в одной), Phillip Potter (только Prosper).
7. **Строка над отзывами.** Строка вида "Reviews from McKinney homeowners" (как на Frisco) была бы неправдой: кандидаты McKinney не называют, где были работы, не записано.

#### Если выбирать четыре сейчас

Предложение, выбор за чатом и Денисом (на Frisco четыре отзыва): **Rangsan L.** (измельчитель и смесители, тема title), **Javeed N.** (течь, которую трудно найти), **alex p** (нет горячей воды, Google, "FPP Plumbing"), **Phillip Potter** (срочная работа в воскресенье, Google). Google 2 и Thumbtack 2, без имени Дениса, денег и цифр приезда, четыре разные работы. Если alex p заберёт другой город (его предлагают семеро), другого чистого отзыва про водонагреватель нет: тогда David H. (смеситель душа и наружная труба). Если уйдёт Javeed N., ближе всех Kevin N. (течь сверху). Если уйдёт Phillip Potter, Thomas S. (ночной вызов).

### Три отзыва живой страницы McKinney

Все три в Takeout (пять звёзд), `on_old_site` = `/plumber-mckinney-tx/`, на странице слово в слово. Над ними строка "Real Google reviews from local homeowners.", хотя двое пишут как владельцы сдаваемых домов. Переписанная страница может оставить своих по правилам; здесь не проходит никто.

| Имя | Профиль, дата | Свободен | Имя Дениса | Деньги, жалобы | McKinney в тексте | Работа | Итог |
|---|---|---|---|---|---|---|---|
| LXD Properties | Google Frisco, 2026-01-17 | НЕТ: стоит на `/plumber-frisco-tx/` (блок чата 2 октября) | нет | нет | нет | проверки в нескольких домах, смесители, сливы, главный водопровод, уличные краны, водонагреватель, унитаз | **Занят**, остаётся на Frisco |
| Ezzy Zhoo | Google Plano, 2025-03-12 | да | ДА, два раза | нет | **ДА**: "city of mckinney" | черновая сантехника при ремонте ванной, слив душа, перенос вентиляции и водопровода, газ, пермит города | **Не проходит**: имя Дениса; ещё "rerouting" и "gas line" |
| Victoria Nwanegbo | Google Plano, 2024-09-30 | да | ДА, один раз | нет (про других сантехников, не жалоба на FPP) | нет | не названа: управляет сдаваемым домом | **Не проходит**: имя Дениса; без города и услуги |

- **Ezzy Zhoo**: "Denys of FPP is a wonderful and trustworthy plumber. He is very responsive and hardworking. I hired Denys to do the rough plumbing for my batbroom remodeling which included a new shower drain being put in, rerouting of vents and water lines, and gas line. He did a great job, working with me to satisfy permit requirements for city of mckinney. He is legit and i will be hiring him for future projects!" [ссылка](https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sChZDSUhNMG9nS0VJQ0FnTURReGN2dEZBEAE!2m1!1s0x0:0xccc66184bdaf3a93)
- **Victoria Nwanegbo**: "I have worked with Denys on multiple projects. I manage a rental property. The best thing about them is, I’ve never had to call them back for anything. I’ve had multiple plumbers do various jobs for me, and there’s always a leak, a loose clamp or something or another installed incorrectly. It’s exhausting. All that is old news now. I call FPP Plumbing and get on the schedule. Whatever they work on, is done and perfect. I can’t begin to explain the relief." [ссылка](https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sChZDSUhNMG9nS0VJQ0FnSUNueTRYcUVBEAE!2m1!1s0x0:0xccc66184bdaf3a93)
- **LXD Properties**: полный текст и ссылка в файле таблиц, раздел 6.

Подпись LXD Properties на живой странице ("McKinney, TX · Local Guide Level 2") неверна дважды: города в тексте нет, значка Local Guide нет (сверено 2 октября). Уровни 5 у Ezzy Zhoo и 4 у Victoria Nwanegbo есть только на старой странице. Ezzy Zhoo единственный на весь архив называет McKinney, разрешение города и газ: оставить его можно только словом Дениса, как исключение сразу из трёх правил. Опечатку "batbroom" не править.

### Каких работ нет

По 330 свободным, поиск по словам работы; имена в файле таблиц, раздел 5. Показы за 16 месяцев.

| Работа | Тема или запрос McKinney | Свободных | Чистых | Что мешает |
|---|---|---|---|---|
| Slab leak | H2 страницы; "slab leak repair mckinney" 711 | 0 | 0 | оба отзыва про slab leak стоят на странице slab leak |
| Главный водопровод | H2 "Main Water Line Repair in Older McKinney Homes"; "mckinney tx water line repair" 404 | 8 | 0 | шесть с именем Дениса, John Wilson (старая Lewisville), Inna Kravchenko (процент, "near me") |
| Давление воды, PRV | "low water pressure plumber mckinney" 580 | 5 | 0 | старая страница PRV, "near me", имя Дениса |
| Водонагреватель | H2 "Water Heaters and the Tank Nobody Mentions" | 11 | 1 | чистый только alex p; остальные с именем Дениса, городом, суммами, "near me", старыми страницами |
| Расширительный бак | та же H2 | 2 | 0 | Jan Shangle (комиссия, снят Денисом), funny warner f ("near me"); Ann Crawford придержана |
| Канализационная линия | "sewer line plumber mckinney" 142 | 4 | 0 | имя Дениса, "near me", старая The Colony |
| Пермит и инспекция | FPP берёт пермиты (CLAUDE.md) | 7 | 0 | Ezzy Zhoo и другие с именем Дениса, городом, "near me" |
| Газ, backflow, спринклеры | нет | 1 | 0 | один про газ: Ezzy Zhoo |
| Измельчитель | title; "mckinney tx garbage disposal repair" 102 | 4 | 2 | Rangsan L., Sathya P.; двое с именем Дениса |
| Смесители | "mckinney faucet repair" 290 | 26 | 5 | двадцать с именем Дениса |
| Засоры | "clogged drain plumber mckinney" 185 | 26 | 5 | плюс Thomas S. (засор в заявке); четырнадцать с именем Дениса |
| Унитаз | "toilet repair mckinney" 218 | 20 | 2 | Ryan E., Kayla T.; тринадцать с именем Дениса |
| Срочные, ночь, выходные | "emergency plumber mckinney tx" 345 | 48 | 9 | двадцать девять с именем Дениса |

Свободные со словами "plumber near me" закрыли бы часть пробелов (PRV, водонагреватель, расширительный бак, канализация), но Денис такие снимал 1 и 2 октября; в десятку не включены.

### Что знает только Денис

1. Ezzy Zhoo, единственный отзыв с McKinney: ставим на страницу McKinney как исключение (имя Дениса, "rerouting of vents and water lines", "gas line") или нет? Делаем ли мы черновую сантехнику при ремонте ванной и газовые линии?
2. Были ли работы кого-то из десяти кандидатов в McKinney. Отзыв без места к McKinney всё равно не привязан, но спорного кандидата можно отдать городу, где была работа.
3. Где были дома LXD Properties и работы Victoria Nwanegbo.
4. Есть ли отзыв клиента из McKinney, которого ещё нет в архиве (Google, Yelp, Thumbtack, Nextdoor), особенно про slab leak, главный водопровод или давление воды.
5. Отзывы со словами "plumber near me" для McKinney по-прежнему не берём, как на Frisco?

### После выбора

- Сверить текст на площадке слово в слово, прочитать уровень Local Guide у авторов Google.
- Записать выбранных в `reviews/proposed-placement.csv` и пересобрать журнал отзывов (делает чат, который ставит страницу). Город, взявший отзыв без места, забирает его у остальных городов.

## 6. Официальные факты

Четыре файла из `docs/briefs/mckinney/`: два файла фактов (`6a-official-city.md`, `6b-zip-and-age.md`) и две независимые перепроверки (`6a-official-city-verified.md`, `6b-zip-and-age-verified.md`). Сначала (6.0) идут проверенные списки, что можно брать и чего нельзя, вынутые из двух файлов проверки слово в слово; потом два файла фактов (6.1 и 6.2); потом оба файла проверки целиком, с таблицами сверки (6.3 и 6.4). Заголовки внутри опущены на два уровня, первая строка каждого файла (его заголовок) названа в начале его подчасти.

Рядом лежат и в бриф не вставлены: `6a-official-city-quotes.md` (28 КБ: список 30 источников S1 до S30 с адресами и дословные цитаты по каждому пункту city-a1 до city-h7), `6b-zip-and-age-tables.md` (23 КБ, таблицы 1 до 11 Census, USPS и ГИС города), папки `work-6a/` (тексты прочитанных страниц и документов), `work-6b/` (выписки и расчёты) и `work-6b-verify/` (выписки и счётчики проверки, без координат и адресов).

Важно: файлы фактов (6.1 и 6.2) писались до перепроверки. Где они расходятся со списками 6.0 и с таблицами проверки (6.3 и 6.4), верить проверке. Вот где:

- city-b3, city-b4, city-c2: пакет для строителей ("Residential Builders Packet", https://www.mckinneytexas.org/DocumentCenter/View/2670/Residential-Builder-Packet-) действует с 1 октября 2025 ("EFFECTIVE: OCTOBER 1, 2025" на видимой обложке), а не с 7 января 2020: старая дата осталась только в скрытом текстовом слое. Значит, правила пакета (T&P не ниже 6 дюймов, расширительный бак, поддон со сливом, отсечка 3:00 PM, плата 40.00 за водонагреватель) это действующий документ. Слова 6.1 «документы 2020 года» (в «Главное за минуту», пункт 6, в таблице и в «Пояснения», пункт c) неверны. Правило «после 3 PM через два рабочих дня» стоит только в памятке Public Works про инспекции полива от 9/11/2020.
- city-d5: граница по канализации у города написана. Public Works, "Right-of-Way Construction & Permitting Procedures Manual", "Effective July 1, 2025", раздел 5.6C: часть города от магистрали до счётчика (вода) или до cleanout (канализация), часть хозяина от счётчика или cleanout до дома. Слова 6.1 «простыми словами не написана» неверны.
- cmp-d1 (файл 6.2, раздел «г»): 72.8% (у Frisco 81.5%, у Plano 31.3%) это жильё, построенное в 2000 году и позже, вместе с 2020-ми, а не «2000-е и 2010-е». Только 2000-е и 2010-е: McKinney 67.9%, Frisco 74.8%, Plano 29.6%.
- zip-a9: официальный фотоальбом города прямо привязывает к площади только Virginia и Tennessee Street; Louisiana к площади подписями не привязана, Kentucky только косвенно. ГИС города (все адреса этих улиц под 75069) подтверждена полностью.
- zip-a10: сервис USPS "Cities by ZIP Code" не открылся ни у одного помощника. Какие ещё названия городов почта принимает для индексов McKinney, не проверено.
- cmp-d2: «как Frisco» по возрасту верно для 75070 и 75071; 75072 старше (медиана 2004, треть жилья из 1980-х и 1990-х).
- Вопрос о регистрации FPP в списках города закрыт словом Дениса от 3 октября 2026 (компания зарегистрирована во всех городах, где работает); раздел 6a его и не проверял.
- Найдено при сборке, второй проверки не было: страница города https://www.mckinneytexas.org/2284/Meters-Leaks-Pipes (сохранённый текст `work-6a/meters-leaks-pipes.txt`) пишет об оповещениях по подписке: "My Water Advisor® 2.0 ... Get text and email alerts to identify leaks and high water usage." Это к утверждению гида про счёт за воду в части 8.

### 6.0. Проверенные списки: что можно брать и чего нельзя

Вынуто слово в слово из двух файлов проверки: «6, часть первая, проверка. Официальные факты Мак-Кинни (McKinney), перепроверка» и «6b, проверка. Почтовые индексы и возраст домов McKinney: что подтвердилось». Полностью оба файла стоят ниже, в 6.3 и 6.4.

#### Город (из `6a-official-city-verified.md`): Можно брать в бриф (с поправками)

Все факты, кроме трёх в старой редакции, подтверждены. Поправленные версии:

- **city-b3:** "Разрешение на водонагреватель нужно (тип Water Heater в CSS). Residential Water Heater Permits $ 40.00 стоит в прейскуранте без даты (View/358) и в Residential Builders Packet, действующем с 1 октября 2025 (View/2670, стр. 7)."
- **city-b4:** "Отдельной памятки для замены водонагревателя нет. В Residential Builders Packet, действующем с 1 октября 2025 (на него отсылает страница Building Inspections для готовности к инспекции): T&P line termination no less than 6” from floor or receptor; Expansion tank installed if thermal expansion encountered and not controlled; Water heater T&P line roughed-in and pan drain installed. 2024 IPC 504.7: пластиковый поддон под газовым баком с flame spread не больше 25 и smoke-developed index не больше 450."
- **city-c2:** "Residential Builders Packet, действующий с 1 октября 2025: Any inspection properly scheduled before 3:00 PM will be scheduled for the next business workday. Правило after 3 PM: 2 business days out есть только в памятке Public Works про инспекции полива от 9/11/2020 (View/25379)."
- **city-d5:** "Город (Public Works, Right-of-Way Construction & Permitting Procedures Manual, Effective July 1, 2025, 5.6C): The city owned section of a lateral service is typically from the main pipeline to the (water) meter or (sewer) cleanout. The property owner or customer’s section of a lateral service is typically from the (water) meter or (sewer) cleanout to the serviced building/structure. В законе: Building sewer means the extension from the building drain to the sewer lateral at the property line; по 110-228 городская врезка тянет отвод от магистрали до границы участка или сервитута, прочистка у границы участка."

Остальные 43 подтверждены как есть: a1, a2, a3, a4, b1, b2, b5, b6, b7, b8, b9, b10, b11, b12, c1, c3, c4, c5, d1, d2, d3, d4, d6, d7, e1, e2, e3, e4, f1, f2, f3, f4, f5, g1, g2, g3, g4, h1, h2, h3, h4, h5, h6, h7 (с уточнениями из таблицы).

#### Город (из `6a-official-city-verified.md`): Нельзя брать

В старой редакции (ошибка):
- "Пакет для строителей от 7 января 2020" и любые выводы из этого: "оба документа с отсечкой 2020 года", "свежего документа с отсечкой нет" (city-b3, city-b4, city-c2, и тот же вывод в разделе "Пояснения", пункт c, файла 6a-official-city.md). Видимая дата пакета: 1 октября 2025.
- "Граница ответственности по канализации на страницах города не написана" (city-d5): написана в ROW Manual 2025.

На страницу как есть (правила CLAUDE.md, факты верные, но в текст страницы не переносить):
- Wylie, Leonard (станции NTMWD), названия улиц из списка замены линий на 1702: не наши десять городов или адреса. Писать "вода NTMWD, главное озеро Lavon Lake".
- Все телефоны города и подрядчиков города (правило 10).
- Платы города (40.00, 75.00, 50.00 и другие) и цифры кредита ($150.00): не наши цены, без слова Дениса не ставить.
- Регистрация тестеров BPAT и кто тестирует обратный клапан: на странице только фраза "Once the new assembly is in, it gets tested and the test report goes to the city."
- Расчёт gpg (11.68, 8.41) подавать только как пересчёт по формуле NTMWD, не как цифру города.
- Цифры числа линий с 1702 (14,500, 27,000, 37,000, 74,606): страница сама себе противоречит.
- "20 psi" из закона 110: это минимум для пожарных гидрантов, не давление в доме.
- "Rerouting of a zone" из 110-477: это про зону полива; reroute как нашу услугу не писать.

#### Индексы и возраст домов (из `6b-zip-and-age-verified.md`): Можно использовать в брифе

1. Почтовые индексы McKinney: 75069, 75070, 75071, 75072, все обычные, с доставкой (USPS ZIP Locale Detail, файл от 1 октября 2026). Индекса только для абонентских ящиков у McKinney нет.
2. Четыре индекса покрывают 98,9% суши города (2020). 75454 (почта Melissa) это 1,1% суши и 391 единица жилья McKinney (0,5%); 75407 (почта Princeton) задевает город клочком без жилья. Показывать 75454 и 75407 как индексы McKinney нельзя.
3. Жилье 2020 года по индексам: 75070 33,1%, 75072 25,8%, 75071 25,6%, 75069 14,9% жилья города. 75070 и 75072 почти целиком McKinney (100% и 98,9% жилья участка). В 75069 только 67,1% жилья участка в McKinney, в 75071 84,1%.
4. Под 75071 много домов вне черты города, в ETJ: 3 128 единиц жилья по переписи 2020 года, 6 834 жилых адреса округа в слое адресов самого города. Адрес "McKinney, TX 75071" не значит, что дом в черте города; слова про разрешение и инспекцию города McKinney к ним не относятся.
5. Старое жилье McKinney стоит в 75069, к востоку от US 75: все жилье McKinney в 75069 к востоку от US 75, а адреса улиц у площади (Tennessee, Kentucky, Chestnut, Louisiana, Virginia St) все под 75069 по ГИС города. Площадь стоит на Virginia и Tennessee, это прямо написано в подписях официального фотоальбома города.
6. Медианный год постройки жилья, ACS 2020-2024, таблица B25035: McKinney city 2007 (±1); 75069 2000, 75072 2004, 75070 2010, 75071 2011, 75454 2015. Жилье владельцев: город 2007, 75069 1999, 75072 2004, 75070 2007, 75071 2011.
7. Доли по годам, весь город (B25034): до 1980 года 7,8%, 1980-1999 19,4%, 2000-2009 33,2%, 2010 и позже 39,6%; построено до 2000 года 27,2%, в 2000 году и позже 72,8%. В 75069 до 1980 года 26,1%, в 75070, 75071, 75072 от 2,3% до 5,1%.
8. Дома на одну семью (с таунхаусами, только занятое жилье): 55 328, 74,7%; из них до 1980 года 7,9%. В 75069 таких старых 33,7%.
9. Жилья 1939 года и раньше в McKinney по оценке 1 128 (±356), в 75069 885 (±325).
10. Сравнение с Фриско (2009) и Плано (1993), домов до 1940 года больше, чем у Плано и Фриско вместе: только знание для автора, на странице McKinney другие города не называются.
11. Граница города с 2020 года выросла (суша на 2,6%), доли суши посчитаны по границе 2020 года.
12. Самая надежная одна цифра для страницы, если автор захочет ссылку на официальный источник: медианный год постройки жилья в McKinney 2007 (U.S. Census Bureau, ACS 5-year 2020-2024, таблица B25035, McKinney city, Texas).

#### Индексы и возраст домов (из `6b-zip-and-age-verified.md`): Нельзя использовать

1. Подпись "72,8% жилья это 2000-е и 2010-е" (и 81,5% у Фриско, 31,3% у Плано как "2000-е и 2010-е"): это доли жилья "2000 год и позже". Только 2000-е и 2010-е: 67,9%, 74,8%, 29,6%. Исправить в разделе "г" файла 6b.
2. Утверждение, что фотоальбом города называет Louisiana улицей площади: в подписях этого нет. Kentucky привязана к площади только косвенно. Для автора хватит Virginia и Tennessee, плюс ГИС.
3. Какие названия городов почта принимает для индексов McKinney: сервис USPS "Cities by ZIP Code" не открылся ни у первого помощника, ни у меня.
4. Слова "как Фриско" про 75072: медиана 2004 и треть жилья из 1980-1990-х, это старше Фриско. Для 75070 и 75071 сравнение верно, но и оно только для автора.
5. Оценки "75069 без Fairview" (32,9%, 7,1%, "три четверти", "две трети") на странице: это разность двух выборочных оценок, туда же попали Lowry Crossing и земля вне городов. Только как ориентир для автора.
6. Названия соседних городов из таблиц (Fairview, Lowry Crossing, Lucas, New Hope, Melissa, Anna, Princeton, Wylie, а на странице McKinney и Frisco, Celina): только для автора. Первые восемь на сайте не называются совсем, города из списка десяти нельзя называть на странице McKinney (правило CLAUDE.md).
7. Счет "1 500 клеток без расхождений": это его счет, поштучно я его не повторял (все цифры фактов при этом проверены мной).
8. Про чугун, медь, корни и возраст труб на конкретных улицах: Census этого не знает, это только знание Дениса.

### 6.1. Факты города (файл `6a-official-city.md`)

Заголовок файла: «6, часть первая. Официальные факты города Мак-Кинни (McKinney)».

Страница: /plumber-mckinney-tx/. Проверено 3 октября 2026 года. Источники только официальные: сайт города mckinneytexas.org и его документы (DocumentCenter), портал разрешений города CSS (egov.mckinneytexas.org), бланк пересчёта счёта (form.jotform.com, ссылка на него стоит на странице города), законодательная система города mckinney.legistar.com, свод законов города на Municode (на него ссылается сам город), отчёт города о качестве воды, сайт водного округа ntmwd.com (город сам называет NTMWD своим поставщиком), закон штата в издании TSBPE.

Как читать: английские слова в кавычках это слова источника слово в слово. Русский текст это мой пересказ. Длинные цитаты по каждому номеру лежат рядом в файле 6a-official-city-quotes.md, полные тексты всех прочитанных страниц в папке work-6a. Регистрацию самой FPP в списках города я не искал и не проверял (вопрос закрыт словом Дениса от 3 октября).

#### Главное за минуту

1. Регистрация: подрядчик с лицензией регистрируется в городе до выдачи разрешения, через CSS, на имя держателя лицензии RMP, без платы. На каждый объект отдельная "Signature Verification Form".
2. Водонагреватель: разрешение нужно, тип "Water Heater" в CSS.
3. Без разрешения: мелкая течь без замены труб, прочистка, замена унитаза, крана, прибора на том же месте. Линию от счётчика, канализацию во дворе, PRV, ремонт под плитой город отдельно не называет; копать глубже 6 дюймов: звонок в Building Inspections про разрешение.
4. Ремонт фундамента: письмо инженера указывает, нужен ли тест воды, канализации, газа. Это прямо про наши тесты до и после.
5. Обратный клапан на поливе: проверка лицензированным тестером при установке, ремонте, замене, переносе, отчёт в город за 10 рабочих дней.
6. Инспекции только через CSS, заказывает генподрядчик; до 3 PM на следующий рабочий день (документы 2020 года). В дождь подземную сантехнику отменяют. [Поправка проверки (6.3, city-c2): пакет для строителей действует с 1 октября 2025, не 2020; правило «после 3 PM через два рабочих дня» есть только в памятке Public Works про полив от 9/11/2020.]
7. Вода: город отвечает от магистрали до ящика счётчика, хозяин от счётчика до дома. Кран города у счётчика трогают только работники города.
8. Пересчёт счёта после течи есть: расход в 3 раза выше прошлого года, счёт больше $150.00, раз в 12 месяцев, бланк с чеком в течение 60 дней.
9. Жёсткость: в отчёте города цифры нет; NTMWD за 2025: станция Wylie 200 ppm, станция Leonard 144 ppm, город берёт воду с обеих. Вода покупная, NTMWD, главные озёра Lavon, Bois d'Arc, Texoma, Jim Chapman.
10. Кодекс: 2024 IPC и 2024 IRC с поправками NCTCOG, с 1 октября 2025. Municode не обновлён с декабря 2022.
11. Город сам меняет медные линии от магистрали до счётчика: медь 1997 - 2011 годов, "aggressive soil in the region".

#### Сводная таблица

| id | Вопрос | Что говорит город, коротко | Статус | Источник |
|---|---|---|---|---|
| city-a1 | Регистрация подрядчика | Лицензированный подрядчик регистрируется до выдачи разрешения, через CSS, учётная запись на имя держателя лицензии | found | S1 |
| city-a2 | Что требуют от сантехника | "Texas Responsible Master Plumber or Mechanical License" и документ с фото; копии по email после регистрации в CSS | found | S1, S6 |
| city-a3 | Плата и продление | "No registration fee"; продление по сроку лицензии штата. Закон штата: сантехник не платит регистрационный сбор, регистрироваться обязан | found | S1, S30 |
| city-a4 | Подписи на каждый объект | "Signature Verification Form" на каждый проект, без всех подписей разрешение не выдают | found | S1 |
| city-b1 | Общий список работ с разрешением | В списке есть "Water Heater"; для газа и счётчика тип "Residential Stand-Alone Plumbing" | found | S3 |
| city-b2 | Работы без разрешения | Три пункта по сантехнике у города, плюс список закона штата 1301.551(c) | found | S3, S30 |
| city-b3 | Замена водонагревателя | Разрешение нужно, тип "Water Heater" в CSS; 40.00 долларов по прейскуранту без даты (та же цифра в пакете 2020 года) [поправка проверки: пакет действует с 1 октября 2025] | found | S3, S4, S5 |
| city-b4 | Что смотрит инспектор на водонагревателе | Отдельной памятки для замены нет. В пакете новой стройки: трубка T&P не ниже 6 дюймов от пола или приёмника, расширительный бак при неконтролируемом расширении, поддон с дренажом; поправка 2024 года про пластиковый поддон под газовым баком [поправка проверки: пакет действует с 1 октября 2025, страница Building Inspections отсылает к нему для готовности к инспекции] | found | S5, S9 |
| city-b5 | Линия воды от счётчика до дома | Отдельно не названа. Действует общее правило списка без разрешения; копать глубже 6 дюймов: звонок в Building Inspections про разрешение | not_on_official_page | S3, S28 |
| city-b6 | Ремонт или замена канализации | Отдельно не названа; без разрешения только прочистка. В кодексе 2024 года: провод-трассер вдоль пластиковой канализации, вакуумный тест разрешён, воздухом нельзя | not_on_official_page | S3, S9 |
| city-b7 | Замена редуктора давления (PRV) | Нигде не назван: ни в списке с разрешением, ни без | not_on_official_page | S3, S4, S5 |
| city-b8 | Обратный клапан на поливе | Разрешение на установку системы и на перенос или добавление зоны; клапан проверяет тестер при установке, ремонте, замене, переносе; отчёт в город за 10 рабочих дней. Разрешение на одну замену клапана прямо не названо | found | S12, S13, S15 |
| city-b9 | Ремонт под плитой | Отдельной страницы или памятки нет | not_on_official_page | S3, S7 |
| city-b10 | Тест труб при ремонте фундамента | Письмо инженера указывает, нужен ли тест воды, канализации, газа; разрешение 75.00 | found | S7, S4 |
| city-b11 | Повторные инспекции, дождь | 50.00, 75.00, 100.00; после часов 50.00 в час, минимум 2 часа; дождь: отменить подземную сантехнику, иначе красная бирка и $50 | found | S4, S2 |
| city-b12 | Заземление на трубе | 2024 IRC P2903.6: старую металлическую трубу, на которой заземление, не убирают без другого заземления | found | S10 |
| city-c1 | Как заказать инспекцию | Только через CSS, заказывает генподрядчик | found | S2 |
| city-c2 | Отсечка | До 3 PM: следующий рабочий день; после 3 PM: через два рабочих дня. Оба документа 2020 года [поправка проверки: пакет S5 действует с 1 октября 2025 и пишет только «before 3:00 PM ... next business workday»; «после 3 PM через два дня» только в памятке про полив 2020 года] | found | S14, S5 |
| city-c3 | Отмена | Звонок до 9 a.m. технику по разрешениям, после 9 a.m. инспектору напрямую | found | S2 |
| city-c4 | Почему не прошла, почему не заказывается | Причина видна во вкладке checklist в CSS; не заказывается, если не сданы предыдущие инспекции | found | S6 |
| city-c5 | Телефон-автомат или сообщение для заказа | На страницах города такого способа нет | not_on_official_page | S2, S14 |
| city-d1 | Граница по воде | Город: от ящика счётчика до магистрали. Хозяин: от счётчика до дома | found | S19, S20 |
| city-d2 | Чья течь | До счётчика чинит город, после счётчика хозяин за свой счёт | found | S17 |
| city-d3 | Чей счётчик | Счётчик принадлежит городу, город его обслуживает; ящик у улицы или у края участка | found | S17, S12 |
| city-d4 | Можно ли хозяину закрыть воду на счётчике | Нет: кран города между счётчиком и улицей только для работников города; закон запрещает трогать кран и счётчик. У хозяина свой кран | found | S17, S12 |
| city-d5 | Граница по канализации | Простыми словами не написана. Есть определения: "building sewer" от дома до линии у границы участка; город тянет отвод от магистрали до границы участка [поправка проверки: написана, Public Works ROW Manual, Effective July 1, 2025, 5.6C: часть хозяина от cleanout до дома] | not_on_official_page | S12, S5 |
| city-d6 | Городская замена медных линий | Медь 1997 - 2011 годов, плохая медь и агрессивный грунт; город меняет свою часть на HDPE бесплатно | found | S21 |
| city-d7 | Что ставит хозяин за свой счёт | Линии от узлов города до точки использования, свои краны, обратные клапаны, прочистки | found | S12 |
| city-e1 | Пересчёт после течи вообще | Есть, "as a courtesy" | found | S17 |
| city-e2 | Условия | 3 раза выше того же периода прошлого года, счёт больше $150.00, раз в 12 месяцев, бланк и подтверждение в течение 60 дней; полив не считается; платить полностью до кредита | found | S17 |
| city-e3 | Что спрашивает бланк | Дата ремонта, описание, кто чинил (сам или подрядчик), имя подрядчика, чек | found | S18 |
| city-e4 | Точность счётчика | Погрешность по AWWA 1.5%, счётчик не может крутить быстрее | found | S17 |
| city-f1 | Жёсткость в отчёте города | Цифры нет: вторичные показатели "not required to be reported" | not_on_official_page | S23 |
| city-f2 | Жёсткость, станция Wylie (NTMWD) | 200 ppm наибольшее, 96.0 - 200, данные 2025 года, отчёт NTMWD "2025 Water Quality Report" | found | S25, S23 |
| city-f3 | Жёсткость, станция Leonard (NTMWD) | 144 ppm наибольшее, 96.0 - 144, данные 2025 года | found | S25, S23 |
| city-f4 | Grains per gallon | В отчётах нет. NTMWD: делить на 17.12, вода "moderately hard" из-за Lavon Lake. Мой расчёт: около 11.7 и 8.4 | not_on_official_page | S24 |
| city-f5 | Откуда вода | Покупная поверхностная вода NTMWD, шесть источников, главные Lavon, Bois d'Arc, Texoma, Jim Chapman | found | S23, S22 |
| city-g1 | Сантехнический кодекс | 2024 International Plumbing Code с поправками NCTCOG (март 2025), с 1 октября 2025 | found | S2, S8, S11 |
| city-g2 | Кодекс для частных домов | 2024 International Residential Code с поправками NCTCOG (март 2025) | found | S2, S11 |
| city-g3 | Местные поправки по сантехнике | Ежегодная проверка обратных клапанов; при споре с городским законом о cross connection берут более строгое | found | S11 |
| city-g4 | Текст законов на Municode | Свод не обновлён с 20 декабря 2022: там 2021 год; статьи XI о cross connection там нет | not_on_official_page | S12 |
| city-h1 | Мороз | Внутри пустить струйку толщиной с грифель, наружный кран накрыть, шланги снять, полив выключить | found | S17 |
| city-h2 | Проверка обратных клапанов | Тестеры регистрируются в городе, 100 долларов, только городские бланки, подлинник | found | S16 |
| city-h3 | Давление воды | Есть FAQ про низкое давление. Цифры давления в сети и правила про PRV на страницах нет | found | S26, S17, S5 |
| city-h4 | Где искать течь в доме | Водонагреватель: верх бака, предохранительный клапан, сливной кран, сбросная трубка; трубы в стенах, плите, земле: "may require a professional plumber" | found | S26 |
| city-h5 | Дымовой тест канализации городом | Каждый год июнь - август; дым из вентиляции на крыше это норма, из двора или у фундамента дефект | found | S29 |
| city-h6 | Аварийное закрытие воды | Через Public Works, отдел отвечает круглые сутки | found | S27, S22 |
| city-h7 | Свинец и оцинковка | Районы последних 30 лет без свинца; оцинковка в 1980-х и раньше; бесплатная проба для домов до 1988 года | found | S20, S19 |

#### Источники (S)

Полный список из 30 источников (адрес каждой страницы и документа, дата документа, имя файла с полным текстом в work-6a) стоит в начале файла 6a-official-city-quotes.md. Главные: S1 Contractor Registration, S2 Building Inspections, S3 Home Repairs & Permit Information, S17 Meters, Leaks & Pipes, S23 отчёт города о воде 2026, S25 отчёт NTMWD 2025.

#### Пояснения по разделам

**a.** Учётная запись в CSS "follows the individual no matter what company they work for": регистрация привязана к человеку с лицензией RMP, а не к компании. Других сроков, кроме срока лицензии штата, город не ставит.

**b.** Линию от счётчика, канализацию, PRV, ремонт под плитой город отдельно не называет: писать на странице "в Мак-Кинни на это нужно разрешение" можно только со слов Дениса. Платы из S4 взяты из файла без даты; в своде Municode плата вынесена в "appendix A", а свод не обновлялся с 2022 года.

**c.** [Поправка проверки (6.3): неверно, S5 действует с 1 октября 2025.] Свежего документа с отсечкой по времени нет: S14 и S5 оба 2020 года. Страница S2 свежая, на ней только CSS и порядок отмены. Помощник "Development Navigation Assistant (DNA)" работает только через JavaScript, я его не читал.

**d.** Разница с Плейно: в Мак-Кинни кран города у счётчика трогают только работники города, и закон (110-119) запрещает перекрывать воду на кране под контролем города. Советовать хозяину "закройте воду на счётчике" нельзя; правильно: свой кран у дома, а если его нет, аварийная линия города. Нынешняя страница (site/src/content/pages/plumber-mckinney-tx.md, строка 59: "everything from the meter to the house is yours, everything from the meter to the street is the city’s") с городом совпадает.

**e.** Чек и описание ремонта в бланке (S18) ложатся на наше правило "Every invoice describes the work". Условия ($150.00, 3 раза, 60 дней, 12 месяцев) это цифры города, не наши цены.

**f.** Отчёт Мак-Кинни жёсткость не приводит, но называет станции Wylie и Leonard, а NTMWD публикует жёсткость по каждой. Пересчёт в grains per gallon мой (200 / 17.12 = 11.68; 144 / 17.12 = 8.41; 96.0 / 17.12 = 5.61). Обычный текст отчёта NTMWD путает столбцы, строки с жёсткостью извлечены повторно с сохранением расположения (ntmwd-annual-wqr-2025-layout-wylie-leonard.txt). Старый ответ FAQ (S27) про источники не упоминает Bois d'Arc Lake; верная формулировка в отчёте 2026 года.

**g.** S2 пишет, что совет утвердил коды 1 октября 2025; Legistar показывает закон в повестке совета на 19 августа 2025 с вступлением в силу "beginning on October 1, 2025". В Legistar лежит проект без номера и даты подписи, "Final action" пустое. Надёжно: "2024 International Plumbing Code, в силе с 1 октября 2025"; номер закона неизвестен. Закон о cross connection (глава 110, статья XI) не нашёлся ни на Municode, ни поиском по Legistar.

**h.** Совет города про мороз совпадает с правилом Дениса: капают краны внутри, на наружный кран утеплитель ("faucet insulator"); город не пишет, что наружный кран должен капать. Дымовой тест города (S29) про городские линии; наш дымовой тест живёт на /drain-services/.

#### Что из этого нельзя переносить на страницу как есть

- Названия городов из источников: Wylie и Leonard (станции NTMWD), список городов NTMWD в отчёте округа (там Allen, Frisco, Plano, Little Elm, Prosper, а также Melissa, Fairview, Princeton и другие). Страница города не называет соседние города, а Melissa, Fairview и все города вне десяти запрещены везде. Писать "вода NTMWD с озёр Lavon и Bois d'Arc", без названий станций.
- Телефоны города (469-617-4800, 972-547-7360 и другие): по правилу 10 в тексте страницы телефонов нет. Можно писать "аварийная линия Public Works города", без номера.
- Платы города (40.00, 75.00, $100, $150.00 и другие): это не наши цены, но по правилу о ценах на странице лучше их не ставить без слова Дениса; файл платы без даты.
- Обратный клапан: мы только меняем узел. Про проверку только разрешённая фраза "Once the new assembly is in, it gets tested and the test report goes to the city." Не писать, кто тестирует, и не писать, что тестируем мы.
- Не писать, что PRV, линия от счётчика, канализация или ремонт под плитой "по закону Мак-Кинни требуют разрешения": город этого прямо не пишет.
- "Hydro jetting" и "tankless" в источниках не встречаются. Слово "rerouting" есть только в законе о поливе ("rerouting of a zone", зона полива), к водопроводу дома оно отношения не имеет: на страницу не переносить. Сроки, которые город пишет о своих работах (замена городской линии, дымовой тест), это слова города, не наши.

#### Вопросы Денису (что знает только он)

1. Замена PRV в Мак-Кинни: берёте ли разрешение и какое (город про PRV молчит)?
2. Линия от счётчика до дома и точечный ремонт канализации во дворе в Мак-Кинни: какой тип разрешения в CSS берёте (например "Residential Stand-Alone Plumbing") и что смотрит инспектор?
3. Ремонт течи под плитой в Мак-Кинни: разрешение, тест, фото для инспектора, как на деле?
4. Замена обратного клапана на поливе в Мак-Кинни: берёте ли разрешение на полив и как отчёт тестера уходит в город?
5. Ставить ли на страницу пересчёт счёта после течи (условия города слово в слово, без телефонов)?
6. Город пишет про плохую медь 1997 - 2011 годов на городской части линии. Видите ли вы то же на частной части линии от счётчика до дома в Мак-Кинни? Если да, нужна диктовка: районы не называть, только что видите в яме.
7. Жёсткость: ставить ли цифру NTMWD на страницу и что вы видите по накипи в водонагревателях и кранах в Мак-Кинни?
8. Ремонт фундамента: в Мак-Кинни инженер пишет в письме, нужен ли тест воды, канализации, газа. Делаете ли вы такие тесты именно по этому письму? Нужна диктовка.

#### Файлы рядом

- 6a-official-city-quotes.md: дословные цитаты по каждому номеру.
- work-6a/: полные тексты всех прочитанных страниц и документов (у каждого файла в первой строке адрес и дата чтения). Файл state-oc-1301-551.txt пустой по сути: сайт законов штата отдаётся только через JavaScript, текст закона взят из PDF TSBPE (S30). Файл legistar-24-1442.txt про план засухи, к этой части не относится.

### 6.2. Индексы и возраст домов (файл `6b-zip-and-age.md`)

Заголовок файла: «6, часть вторая. Почтовые индексы McKinney и возраст домов».

Проверено 3 октября 2026. Все цифры взяты из официальных файлов USPS, Census Bureau и ГИС города McKinney, адреса запросов стоят в конце раздела. Ничего не придумано: где проверить не удалось, так и написано. Полные таблицы лежат рядом, в файле 6b-zip-and-age-tables.md (таблицы 1-11), выписки и расчеты в папке work-6b.

#### Коротко, самое важное

1. У почты в McKinney четыре индекса, все обычные, с доставкой к домам: 75069, 75070, 75071, 75072. Индекса только для абонентских ящиков (PO BOX) у McKinney нет. Все четыре обслуживает главное отделение MCKINNEY (550 N Central Expy), у 75071 есть еще станция LINKSIDE PARK (7210 Virginia Pkwy Ste 100).
2. Эти четыре индекса покрывают 98,9% суши города (2020). Еще 1,1% суши и 391 единица жилья (0,5% жилья города в 2020 году) лежат в участке 75454, это индекс другого города. Индекс 75407 задевает McKinney клочком в 1 133 кв. м без единого дома.
3. Чистые индексы McKinney: 75070 (100% жилья участка в городе) и 75072 (98,9%). Общие с соседями: 75069 (в черте McKinney 67,1% жилья участка, остальное Fairview 28,1%, Lowry Crossing 3,5%, земля вне городов 1,4%) и 75071 (McKinney 84,1%, земля вне городов, то есть ETJ, 14,1%, еще New Hope, Frisco, Celina). Адрес "McKinney, TX 75071" не значит, что дом в черте города: в слое адресов самого города под 75071 стоит 6 834 жилых адреса округа (ETJ).
4. Медианный год постройки жилья, ACS 5-year 2020-2024, таблица B25035: McKinney city 2007 (±1). По индексам: 75069 2000 (±2), 75072 2004 (±1), 75070 2010 (±2), 75071 2011 (±2), 75454 2015 (±2).
5. По годам, весь McKinney (B25034): до 1980 года построено 7,8% жилья, с 1980 по 1999 год 19,4%, с 2000 по 2009 год 33,2%, в 2010 году и позже 39,6%.
6. Старое жилье McKinney стоит в 75069, к востоку от US 75, вокруг исторической площади. Там до 1980 года построено 26,1% всего жилья участка, а без части Fairview по грубой оценке 32,9%, и 7,1% построено до 1940 года.
7. Для сравнения тем же выпуском: Frisco city 2009 (±1), Plano city 1993 (±2). McKinney по медиане почти как Фриско, но старых домов в нем намного больше: домов до 1940 года в McKinney по оценке 1 128 (±356), в Плано 292 (±119), во Фриско 47 (±61).
8. Census API (api.census.gov) без ключа данные не отдает (проверено 3 октября 2026, ответ 302 на страницу missing_key). Ключ я не запрашивал: это регистрация с почтой, такое делает только Денис. Те же цифры взяты из официальных файлов Census (ACS Summary File) и сверены с data.census.gov: 1 500 клеток, 0 расхождений.

#### а. Индексы McKinney

Источник 1: USPS, файл "ZIP Locale Detail" (Zip_Locale_Detail.xlsx, на сервере файл от 1 октября 2026, 4 380 487 байт). Источник 2: Census Bureau, файл связи участков ZCTA и городов 2020 года, место "McKinney city", код 4845744. Источник 3: перепись 2020 года по кварталам (официальный файл Block Assignment 2020 и карта Census TIGERweb). Источник 4: ГИС города McKinney, слой адресов "Address Points" (город ведет адреса в своей черте, округ в ETJ).

ZCTA это "ZIP Code Tabulation Area": участок, которым Census приближенно повторяет почтовый индекс. По ним считается вся статистика ниже.

| Индекс | USPS: класс | USPS: отделение | Доля суши McKinney в участке | Доля суши участка в черте McKinney | Жилье McKinney в участке, 2020 | Доля жилья участка в McKinney | Жилые адреса в ГИС города: в черте / ETJ | С кем индекс общий (доля жилья участка, 2020) |
|---|---|---|---|---|---|---|---|---|
| 75069 | обычный | MCKINNEY, главное (550 N Central Expy) | 23,55% | 46,8% | 10 882 (14,9% жилья города), все к востоку от US 75 | 67,1% | 8 076 / 253 | Fairview town 28,1%, Lowry Crossing city 3,5%, вне городов 1,4%, Lucas city 1 единица |
| 75070 | обычный | MCKINNEY, главное | 16,84% | 99,9% | 24 151 (33,1%), все к западу от US 75 и к югу от US 380 | 100% | 17 767 / 0 | ни с кем (0,08% суши вне городов, без жилья) |
| 75071 | обычный | MCKINNEY, главное, и станция LINKSIDE PARK (7210 Virginia Pkwy Ste 100) | 40,84% | 36,9% | 18 622 (25,6%), 96,5% к западу от US 75; 61,9% к югу от US 380, 38,1% к северу | 84,1% | 28 264 / 6 834 | вне городов (ETJ) 14,1%, New Hope town 1,2%, Frisco city 0,35%, Celina city 0,2%, Melissa city 0 |
| 75072 | обычный | MCKINNEY, главное | 17,64% | 97,9% | 18 830 (25,8%), все к западу от US 75 и к югу от US 380 | 98,9% | 18 864 / 56 | Frisco city 0,9%, вне городов 0,3% |
| 75454 | обычный, индекс Melissa | MELISSA (1919 E Melissa Rd) | 1,13% | 3,5% | 391 (0,5%), к востоку от US 75 и к северу от US 380 | 7,4% | 4 / 167 | Melissa city 84,2%, вне городов 8,3%, Anna city 0 |
| 75407 | обычный, индекс Princeton | PRINCETON | 0,0007% (1 133 кв. м) | 0,0% | 0 | 0% | 0 / 32 | чужой индекс (таблица 11) |
| только PO BOX | нет | | | | | | | |

Что еще видно в источниках:

- Абонентские ящики. В файле USPS индексы "только PO BOX" помечены буквой P в поле "ZIP CLASS CODE". У всех четырех строк MCKINNEY (75069, 75070, 75071, 75072) это поле пустое. В листах файла "Unique" и "Other" строк McKinney нет. Своего индекса для ящиков у McKinney нет.
- Город сам подтверждает четыре индекса: в его слое адресов жилые адреса в черте McKinney стоят под 75071, 75072, 75070 и 75069 (числа в таблице выше), под 75454 их 4, под 75035 одна точка (по виду опечатка). Это адреса, а не квартиры: у комплекса бывает одна точка на здание (таблица 9).
- ETJ. Под 75071 в том же слое 10 362 адреса с пометкой COUNTY (вне черты города), из них 6 834 жилых; по переписи 2020 года в участке 75071 вне всяких городов 3 128 единиц жилья. По почте это McKinney (у 75071 в файле USPS одно название, MCKINNEY), но дом вне черты города, и слова про разрешение и инспекцию города McKinney к нему не относятся. Вопрос Денису ниже.
- Обратный случай: 164 единицы жилья Frisco лежат в 75072 и 78 в 75071 (2020); в слое города это 33 и 83 жилых адреса с кодом FRIS.
- Часть McKinney в участке 75454 (391 единица жилья в 2020 году) в слое адресов города почти не видна: жилых адресов McKinney с индексом 75454 всего 4. Какой индекс стоит на конвертах этих домов, не проверено.
- Историческая площадь. Улицы площади это Virginia, Louisiana, Tennessee и Kentucky Street (официальный фотоальбом города: "Virginia Street North Side of Square", "East Side of Square looking South on Tennessee"). [Поправка проверки (6.4, zip-a9): подписи альбома прямо привязывают к площади только Virginia и Tennessee; Kentucky косвенно, Louisiana ни одной подписью.] Все адреса этих улиц с приставками N, S, E, W и адреса N/S Chestnut St в ГИС города стоят под 75069.
- Граница города с 2020 года выросла: суша по файлу 2020 года 173 432 672 кв. м, по карте TIGERweb (выпуск на 1 января 2026) 177 990 541 кв. м, на 2,63% больше. Доли суши в таблице посчитаны по границе 2020 года.
- Сервис USPS "Cities by ZIP Code" на один запрос по 75069 ответил перенаправлением на служебную страницу; обходить защиту я не стал. Какие еще названия городов почта принимает для индексов McKinney, не проверено.

Для автора страницы: если индексы вообще показывать, то четыре: 75069, 75070, 75071, 75072. Индексы 75454 и 75407 не нужны. Названия Fairview, Lowry Crossing, Lucas, New Hope, Melissa, Anna, Princeton, Wylie на сайте писать нельзя совсем, а Frisco, Celina и Plano нельзя называть на странице McKinney (городская страница не называет соседей).

#### б. Медианный год постройки по индексам (таблица B25035)

Выпуск: American Community Survey, 5-year, 2020-2024 ("2024 ACS 5-year"). Это самый новый выпуск, который знает API: описание переменной B25035_001E за 2024 год отвечает ("Estimate!!Median year structure built"), за 2025 год ответ 404, папка data выпуска 2025 года на сервере Census пустая. Файлы 2024 года датированы 29 января 2026. Рядом прошлый выпуск, 2019-2023.

"Медианный год" значит: половина жилья построена раньше этого года, половина позже. "±" это погрешность опроса из того же файла (ACS это выборочный опрос, не перепись). Считается все жилье, и дома, и квартиры. Поэтому рядом медиана по жилью, где живет сам владелец (таблица B25037): это ближе к частным домам.

| Участок | Где | Медиана, все жилье, 2020-2024 (B25035_001E) | Погрешность | Выпуск 2019-2023 | Медиана, жилье владельцев (B25037_002) | Медиана, съемное (B25037_003) | Всего жилья (B25034_001) |
|---|---|---|---|---|---|---|---|
| 75069 | восток, за US 75, старый центр; плюс Fairview и Lowry Crossing (33% жилья участка) | 2000 | ±2 | 2000 (±2) | 1999 (±3) | 2001 (±2) | 17 022 |
| 75072 | запад, к югу от US 380 | 2004 | ±1 | 2004 (±1) | 2004 (±1) | 2005 (±2) | 18 648 |
| 75070 | юго-запад, к югу от US 380 | 2010 | ±2 | 2010 (±1) | 2007 (±1) | 2012 (±1) | 25 707 |
| 75071 | север и северо-запад, по обе стороны US 380; плюс ETJ (14% жилья) | 2011 | ±2 | 2010 (±2) | 2011 (±2) | 2008 (±2) | 25 276 |
| 75454 | индекс Melissa, в McKinney 7% его жилья | 2015 | ±2 | 2014 (±2) | 2015 (±2) | 2014 (±3) | 7 124 |
| McKinney city, Texas (штат 48, место 45744) | весь город | 2007 | ±1 | 2006 (±2) | 2007 (±2) | 2008 (±1) | 77 617 |
| Frisco city, Texas (48 и 27684) | для сравнения | 2009 | ±1 | 2009 (±2) | 2008 (±1) | 2011 (±1) | 80 353 |
| Plano city, Texas (48 и 58016) | для сравнения | 1993 | ±2 | 1993 (±1) | 1991 (±1) | 1997 (±1) | 117 686 |

Цифры Frisco и Plano совпадают с проверенными разделами Плано и Allen (docs/briefs/plano/6b-zip-and-age.md, docs/briefs/allen/6b-zip-and-age.md). 75407 (2012), Collin County (2003) и Texas (1992) в таблице 1 файла с таблицами. Все медианы строк McKinney и его индексов сверены с data.census.gov, совпали.

Как читать: в 75069 треть жилья не McKinney (в основном Fairview, медиана 2006 ±1), поэтому часть McKinney в 75069 старше медианы 2000: по грубой оценке без Fairview середина в 1990-х (таблица 10). В 75071 седьмая часть жилья в ETJ. 75070 и 75072 это почти только McKinney.

#### в. Доли по годам постройки (таблица B25034, все жилье)

Выпуск тот же, 2020-2024. Проценты посчитаны мной из чисел файла: "до 1980" это строки 007-011, "1980-1999" строки 005 и 006, "2000-2009" строка 004, "2010 и позже" строки 002 и 003. Названия строк сверены с официальным файлом описаний (Table Shells).

| Участок | Построено до 1980 | 1980-1999 | 2000-2009 | 2010 и позже |
|---|---|---|---|---|
| 75069 (восток, старый центр) | 26,1% | 22,9% | 25,5% | 25,5% |
| 75069 без Fairview (грубая оценка, таблица 10) | 32,9% | 25,3% | 19,1% | 22,6% |
| 75072 (запад) | 2,3% | 31,0% | 41,7% | 25,0% |
| 75070 (юго-запад) | 2,4% | 15,5% | 33,4% | 48,7% |
| 75071 (север, северо-запад) | 5,1% | 12,6% | 29,6% | 52,7% |
| 75454 (индекс Melissa) | 3,8% | 7,0% | 16,4% | 72,8% |
| McKinney city | 7,8% | 19,4% | 33,2% | 39,6% |
| Frisco city | 1,5% | 16,9% | 34,8% | 46,7% |
| Plano city | 18,4% | 50,3% | 17,6% | 13,7% |

По десятилетиям (таблица 3): в 75069 до 1960 года построено 12,4% жилья (2 108 единиц), из них до 1940 года 5,2% (885); в 75072 больше всего 2000-х (41,7%) и 1990-х (24,8%); в 75070 и 75071 больше всего 2010-х (42,5% и 43,4%), в 75071 уже 9,3% жилья с 2020 года.

Только дома на одну семью (таблица B25127, строка "1, detached or attached", владельцы и съемщики вместе; периоды там по двадцать лет):

| Участок | Домов на одну семью | Доля от занятого жилья | Дома до 1980 | Дома 1980-1999 | Дома 2000 и позже |
|---|---|---|---|---|---|
| 75069 | 9 232 | 58,7% | 33,7% | 20,8% | 45,6% |
| 75072 | 16 700 | 92,5% | 2,2% | 31,1% | 66,7% |
| 75070 | 14 916 | 61,0% | 3,4% | 19,7% | 76,9% |
| 75071 | 21 403 | 88,4% | 5,0% | 10,3% | 84,7% |
| McKinney city | 55 328 | 74,7% | 7,9% | 19,5% | 72,6% |
| Frisco city | 57 248 | 74,1% | 1,5% | 18,3% | 80,2% |
| Plano city | 72 982 | 64,9% | 24,1% | 53,3% | 22,6% |

Где стоит старое жилье McKinney (грубая оценка вычитанием, таблица 10): из 6 092 единиц жилья города, построенных до 1980 года, около двух третей (4 108) в 75069 без Fairview; из 1 128 построенных до 1940 года около трех четвертей (885). В эти остатки входят еще Lowry Crossing и земля вне городов (в 2020 году 783 единицы жилья из 11 665), поэтому доли приблизительные. Жилье владельцев по десятилетиям, погрешности клеток и прошлый выпуск в файле с таблицами (таблицы 2, 4, 5).

#### г. McKinney рядом с Фриско и Плано

- По медиане McKinney почти как Фриско: 2007 (±1) против 2009 (±1), и на 14 лет новее Плано (1993 ±2); по жилью владельцев 2007 против 2008 и 1991. Основная масса жилья McKinney это 2000-е и 2010-е (72,8%; у Фриско 81,5%, у Плано 31,3%). [Поправка проверки (6.4, cmp-d1): 72,8%, 81,5% и 31,3% это жильё 2000 года и позже, вместе с 2020-ми; только 2000-е и 2010-е: 67,9%, 74,8%, 29,6%.]
- Но у McKinney, в отличие от Фриско, есть настоящий старый центр: до 1980 года построено 7,8% жилья города (у Фриско 1,5%, у Плано 18,4%), а домов до 1940 года в McKinney по оценке 1 128, больше, чем в Плано (292) и во Фриско (47) вместе. Это 75069, к востоку от US 75, вокруг площади; запад и север города (75070, 75071, 75072, медианы 2004-2011) по возрасту как Фриско. [Поправка проверки (6.4, cmp-d2): «как Фриско» верно для 75070 и 75071; 75072 старше, медиана 2004, 31,0% жилья 1980-1999.]
- Это только для автора: на странице McKinney другие города не упоминаются, сравнение на страницу не выносить.

#### Сверка с живой страницей

На живой странице McKinney (source/crawl/pages/plumber-mckinney-tx.json) и в нынешнем тексте нового сайта (site/src/content/pages/plumber-mckinney-tx.md) стоят заголовки "Main Water Line Repair in Older McKinney Homes" и "Older McKinney, Newer McKinney", фразы "Once a McKinney house passes the twenty year mark" и "Around the historic center and the older established streets, the failures come from age: cast iron and copper that have earned their retirement". Индексов и десятилетий на странице нет.

- "Historic center" данные подтверждают: старое жилье стоит в 75069, к востоку от US 75, вокруг площади (Virginia, Louisiana, Tennessee, Kentucky St; по альбому города к площади прямо привязаны только Virginia и Tennessee, 6.4). Там до 1980 года построено 26,1% жилья участка (по грубой оценке около трети без Fairview), домов на одну семью до 1980 года 33,7%.
- "Twenty year mark": половина жилья McKinney построена до 2007 года (медиана), то есть этой половине сейчас около двадцати лет и больше. Построено до 2000 года 27,2% жилья.
- "Newer developments" тоже сходится: в 75070, 75071 и 75072 построено до 1980 года от 2,3% до 5,1% жилья.
- Про чугун, медь и корни Census ничего не знает: в ACS нет данных о трубах. Это знание Дениса с вызовов.
- Цифры Census на страницу россыпью лучше не выносить. Если нужна одна цифра со ссылкой на официальный источник: медианный год постройки жилья в McKinney 2007 (ACS 2020-2024, таблица B25035, McKinney city, Texas).

#### Вопросы Денису

1. Показывать ли на странице McKinney почтовые индексы вообще. Если да, по данным это четыре индекса: 75069, 75070, 75071, 75072.
2. Под индексом 75071 (и немного под 75069, 75072) много домов вне черты города, в ETJ: в слое адресов самого города 6 834 жилых адреса округа под 75071, по переписи 2020 года 3 128 единиц жилья. На конверте у них "McKinney, TX". Считать ли такие вызовы вызовами в McKinney, как Paloma Creek для Little Elm? В любом случае к ним не относятся слова про разрешение и инспекцию города McKinney.
3. Что он называет "historic center and the older established streets": восток за US 75 вокруг площади (75069)? Какие улицы или районы он видит на вызовах с чугунной канализацией и медными линиями?

#### Адреса запросов

Census API, как просили в задании, и что он ответил (3 октября 2026):

- https://api.census.gov/data/2024/acs/acs5?get=NAME,B25035_001E&for=zip%20code%20tabulation%20area:75069,75070,75071,75072,75454 : ответ 302, перенаправление на https://api.census.gov/data/missing_key.html
- https://api.census.gov/data/2024/acs/acs5?get=NAME,B25035_001E&for=place:45744,27684,58016&in=state:48 (McKinney, Frisco, Plano): ответ 302, то же.
- https://api.census.gov/data/2025/acs/acs5?get=NAME,B25035_001E&for=zip%20code%20tabulation%20area:75069,75070,75071,75072 : ответ 302, то же.
- https://api.census.gov/data/2024/acs/acs5/variables/B25035_001E.json : ответ 200, "Estimate!!Median year structure built". Тот же адрес для 2025 года: 404.
- Когда у Дениса будет свой ключ, те же цифры дадут запросы: https://api.census.gov/data/2024/acs/acs5?get=NAME,B25035_001E,B25035_001M&for=zip%20code%20tabulation%20area:75069,75070,75071,75072&key=КЛЮЧ и https://api.census.gov/data/2024/acs/acs5?get=NAME,B25035_001E,B25035_001M&for=place:45744,27684,58016&in=state:48&key=КЛЮЧ

Откуда цифры взяты на самом деле (официальные файлы Census, без ключа; размеры и даты локальных копий сверены с сервером 3 октября 2026, совпали). Полный список всех адресов, включая перепись 2020 года, карту TIGERweb и линии дорог, в конце файла с таблицами.

- https://www2.census.gov/programs-surveys/acs/summary_file/2024/table-based-SF/data/5YRData/acsdt5y2024-b25035.dat и acsdt5y2024-b25034.dat (там же b25036, b25037, b25127; прошлый выпуск в папке 2023). Строки: 860Z200US75069, 860Z200US75070, 860Z200US75071, 860Z200US75072, 860Z200US75454, 1600000US4845744 (McKinney city, Texas), 1600000US4827684, 1600000US4858016.
- Сверка: https://data.census.gov/api/access/data/table?id=ACSDT5Y2024.B25035&g=860XX00US75069 (и так же для остальных участков и таблиц, 1 500 клеток, все совпали). Ответ сам называет запрос API, которым он собран: https://api.census.gov/data/2024/acs/acs5?get=group(B25035)&ucgid=860Z200US75069
- https://postalpro.usps.com/mnt/glusterfs/2026-10/Zip_Locale_Detail.xlsx (индексы и классы USPS)
- https://www2.census.gov/geo/docs/maps-data/data/rel2020/zcta520/tab20_zcta520_place20_natl.txt (участки и города, код 4845744)
- https://maps.mckinneytexas.org/mckinney/rest/services/MapServices/Addressing/MapServer/0 (слой адресов города; описание слоя: "This data contains the Address Points for the City of McKinney and its ETJ.")
- https://www.mckinneytexas.org/PhotoGallery/Album/2 (официальный фотоальбом города "McKinney Historic Photos", подписи про площадь)

#### Оговорки

- ACS это выборочный опрос за пять лет (2020-2024), у каждой цифры есть погрешность. У медиан она от 1 до 3 лет. Доли посчитаны из оценок; различия в один или два процента ничего не значат, а мелкие клетки очень неточные: например, жилья до 1940 года в 75072 33 (±47).
- Участок ZCTA повторяет почтовый индекс приближенно.
- "Жилье" в B25034 и B25035 это все жилые единицы, квартиры тоже. Для домов надежнее смотреть жилье владельцев (B25036, B25037) и дома на одну семью (B25127).
- Доли жилья по участкам и стороны US 75 и US 380 посчитаны мной по кварталам переписи 2020 года, это не готовая цифра источника; итоги совпали с официальными цифрами переписи до единицы. С 2020 года город вырос (суша на 2,63%), больше всего новых адресов на севере, под 75071. Оценка "75069 без Fairview" сделана вычитанием двух оценок ACS и очень грубая.
- Названий районов (Stonebridge Ranch, Craig Ranch и т.п.) у Census нет, их привязка к индексам здесь не проверялась.
- Выписки и расчеты лежат в папке work-6b рядом с этим файлом. Координат ниже уровня ZCTA там нет.

### 6.3. Перепроверка фактов города: таблица и поправки (файл `6a-official-city-verified.md`)

Заголовок файла: «6, часть первая, проверка. Официальные факты Мак-Кинни (McKinney), перепроверка».

Страница: /plumber-mckinney-tx/. Проверено 3 октября 2026 года. Проверялся файл 6a-official-city.md (47 фактов). Каждый источник я открыл заново сам (curl, по одному запросу на страницу; PDF прочитаны текстом, спорные места отрисованы картинкой и просмотрены глазами; Municode через его интерфейс данных). Подтверждаю только то, что сам увидел на официальной странице. Census в этой части нет, поэтому запросов к Census не было.

Как читать: "да" значит слова или цифры стоят в источнике и утверждение верно. "нет, поправка" значит в утверждении есть ошибка, правильная версия дана словами источника. Для фактов со статусом not_on_official_page "да" значит, что я тоже искал и тоже не нашёл, то есть утверждение "этого нет" верно.

#### Главное из проверки

1. **Ошибка в дате пакета для строителей.** "Residential Builders Packet" (https://www.mckinneytexas.org/DocumentCenter/View/2670/Residential-Builder-Packet-) на видимой обложке датирован "EFFECTIVE: OCTOBER 1, 2025" и несёт новый адрес 401 E. Virginia Street. Строка "E F F E C T I V E : J A N U A R Y 7 , 2 0 2 0" осталась только в скрытом текстовом слое под новой обложкой (её видит извлечение текста и поиск, но не читатель). Я отрисовал страницу 1 и проверил глазами. Значит, правила из пакета (отсечка 3:00 PM, T&P, расширительный бак, плата 40.00 за водонагреватель) это действующий документ 2025 года, а не 2020. Это поправляет city-b3, city-b4, city-c2.
2. **Граница по канализации у города написана.** В "Right-of-Way Construction & Permitting Procedures Manual" отдела Public Works, "Effective July 1, 2025", раздел 5.6C, стр. 33: "The city owned section of a lateral service is typically from the main pipeline to the (water) meter or (sewer) cleanout." и "The property owner or customer’s section of a lateral service is typically from the (water) meter or (sewer) cleanout to the serviced building/structure." Это поправляет city-d5.
3. Остальные 44 факта подтверждены, у части есть уточнения (колонка "Примечание").

#### Таблица проверки

| id | Утверждение (коротко) | Источник | Подтверждено | Примечание |
|---|---|---|---|---|
| city-a1 | Регистрация до разрешения, через CSS, учётная запись на имя и email держателя лицензии, следует за человеком | 257/Contractor-Registration | да | Слово в слово: "Licensed contractors must register with the City of McKinney before a permit can be issued." и "the account follows the individual no matter what company they work for". Сказано в абзаце "Subcontractors". |
| city-a2 | Для сантехника: лицензия RMP и документ с фото; копии по email после регистрации | 257/Contractor-Registration | да | "Texas Responsible Master Plumber or Mechanical License", "State picture identification (e.g., Texas driver’s license)", "Email copies of required licenses after registering for an account in CSS". |
| city-a3 | Платы нет, продление по сроку лицензии штата; 1301.551(g),(h) | 257 и PDF TSBPE Sept 2025 | да | "No registration fee", "Licenses are renewable on the expiration date specified on the state license." (g) и (h) стоят в PDF TSBPE слово в слово. На обложке PDF TSBPE пометка "(UNOFFICIAL VERSION)", дата September 1, 2025. |
| city-a4 | Signature Verification Form на каждый проект, подписывает держатель мастер-лицензии, без подписей разрешения нет | 257/Contractor-Registration | да | Точнее: когда субподрядчик работает под генподрядчиком, форму даёт GC, и её подписывает "each master license holder". |
| city-b1 | В списке работ с разрешением есть Water Heater; газ и счётчик: Residential Stand-Alone Plumbing; фундамент отдельно | 3350/Home-Repairs-Permit-Information | да | Пункт называется "Gas / Meter Inspection": это про газ и газовый счётчик, к водяной линии его не тянуть. Фундамент: "Residential Foundation Repair". |
| city-b2 | Без разрешения: мелкая течь без замены трубы, прочистка, замена прибора на месте; 1301.551(c) | 3350 и PDF TSBPE | да | Три пункта раздела "Plumbing" слово в слово; список закона штата в (c) тоже. |
| city-b3 | Разрешение на водонагреватель нужно; 40.00 по прейскуранту без даты; та же цифра в пакете от 7 января 2020 | DocumentCenter/View/358 и View/2670 | нет, поправка | "Residential Water Heater Permits $ 40.00" стоит в обоих. Но пакет не от 2020 года: видимая обложка "EFFECTIVE: OCTOBER 1, 2025", прейскурант на стр. 7 пакета. В файле 358 даты нет; в нём же лежит старая таблица с адресом 221 N. Tennessee и "Minimum Fee $25.00". |
| city-b4 | Отдельной памятки для замены нет; в пакете новой стройки 2020 года T&P не ниже 6 дюймов, бак при расширении, поддон с дренажом; 504.7 пластиковый поддон | View/2670 и View/36289 | нет, поправка | Все слова на месте: "T&P line termination no less than 6” from floor or receptor", "Expansion tank installed if thermal expansion encountered and not controlled", "Water heater T&P line roughed-in and pan drain installed", 504.7 "maximum flame spread rating of 25 and a maximum smoke-developed index of 450". Ошибка только в годе: пакет действует с 1 октября 2025, и страница Building Inspections прямо отсылает к нему: "Use the Readiness Points section in the last half of the Residential Builders Packet to determine readiness." |
| city-b5 | Город отдельно не пишет про разрешение на линию от счётчика до дома; копать глубже 6 дюймов: звонить в Building Inspections | faq.aspx?TID=61 | да | Цитата на месте. Правила о разрешении на линию я тоже не нашёл. Дополнение (не про разрешение): в ROW Manual, 5.6C: "A licensed plumber must be obtained by the permittee for repairs to privately owned sanitary sewer or water service pipelines." Это сказано подрядчикам, которые повредили линию при работах в полосе отвода. |
| city-b6 | Отдельного правила о разрешении на канализацию нет; трассер 14 AWG, вакуумный тест можно, воздушный нельзя | View/36289 | да | "Min. 14 AWG tracer wire is now required to be buried along the entire length of plastic sewer piping"; "Vacuum testing is now an option for DWV piping"; "Air testing is still prohibited." Вакуум разрешён для DWV вообще, не только для канализации во дворе. |
| city-b7 | PRV не назван нигде | 3350, 358, 2670 | да | Я проверил те же документы, плюс General Notes 2026 (DocumentCenter/View/410) и поиск по сайту города: PRV нигде нет. |
| city-b8 | Разрешение на систему полива и на перенос или добавление зоны; тест клапана при установке, ремонте, замене, переносе; отчёт за 10 рабочих дней; разрешения на одну замену клапана нет | Municode 110-477, 110-478 | да | Слово в слово в 110-478(e) и (g); обязанность отдать отчёт городу и хозяину за "ten business days" лежит на "the irrigator". Страница 514/Irrigation о замене клапана тоже молчит. Свод Municode кодифицирован по 20 декабря 2022, статья X поправлена в 2021 году. |
| city-b9 | Отдельной страницы о ремонте под плитой нет | 3350 | да | Не нашёл. Плита упоминается только в FAQ про течи ("Pipes located in the walls, slab or underground") и в памятке по фундаменту ("slab-on-grade and pier & beam"). |
| city-b10 | Ремонт фундамента с разрешением; письмо инженера: нужен ли тест воды, канализации, газа; 75.00 | View/2102 и View/358 | да | "and if any affected plumbing systems will require testing (water, sewer, and/ or gas)." "Residential Foundation Repair Permits $ 75.00" стоит и в пакете, действующем с 1 октября 2025. |
| city-b11 | Повторные 50.00, 75.00, 100.00; вне часов 50.00 в час, минимум 2 часа; в дождь отменить подземную сантехнику, иначе красная бирка и $50 | 243/Building-Inspections и View/358 | да | Цифры есть и в пакете 2025 года. Уточнение: красная бирка выдаётся, "if the site is deemed too wet by the inspector". У всех почасовых плат сноска: или полная часовая стоимость для города, "whichever is the greatest". |
| city-b12 | P2903.6: металлическую трубу с заземлением не убирать без другого заземления | View/36290 | да | Слово в слово. |
| city-c1 | Все инспекции только через CSS; заказывает генподрядчик | 243/Building-Inspections | да | "All inspections must be scheduled through Citizen Self-Service." и "should be requested by the general contractor". |
| city-c2 | До 3 PM: следующий рабочий день; после 3 PM: через два; оба документа 2020 года | View/25379 и View/2670 | нет, поправка | Памятка 25379 ("Last Update: 9/11/2020") это памятка Public Works про инспекции полива; там "Before 3 PM: Inspection scheduled for next (1) business day" и "After 3 PM: Inspection scheduled for 2 business days out", как "normal defined global inspection rules". Пакет для строителей не 2020, а "EFFECTIVE: OCTOBER 1, 2025", и в нём только: "Any inspection properly scheduled before 3:00 PM will be scheduled for the next business workday." |
| city-c3 | Отмена до 9 a.m. через техника, после 9 a.m. инспектору напрямую | 243/Building-Inspections | да | Слово в слово. В пакете 2025 года добавлено: "Inspections cannot be canceled on CSS." |
| city-c4 | Причина отказа во вкладке checklist; не заказывается без предыдущих инспекций | Faq.aspx?TID=95 | да | "Click the checklist tab and you will see the reason."; "without completing other required inspections". |
| city-c5 | Телефона-автомата или сообщения для заказа нет | 243 | да | Не нашёл ни на 243, ни в FAQ CSS, ни в пакете. |
| city-d1 | Город: от ящика счётчика до магистрали; хозяин: от счётчика до дома | 765/Galvanized-Service-Lines | да | "The city’s responsibility is to maintain service lines from the meter box to the main." и цитата про хозяина слово в слово. |
| city-d2 | До счётчика чинит город, после счётчика хозяин за свой счёт | 2284/Meters-Leaks-Pipes | да | Слово в слово, плюс "This leak will not affect your consumption as it is not running through the meter." |
| city-d3 | Счётчик города; ящик у улицы или у края участка | 2284 | да | "generally located in a small box in the ground near the street or the edge of the property". |
| city-d4 | Кран города только для работников; 110-119 запрещает перекрывать воду на городских кранах; у хозяина свой кран; в аварии Public Works | 2284 и Municode 110-119 | да | Слово в слово. Места личного крана по городу: в подполье у ввода, в гараже у ввода (у водонагревателя или стиральной машины), снаружи у фундамента. Город: "If you have an emergency and need help shutting off your water at the meter, please call" (номер не переносить). |
| city-d5 | Простыми словами граница по канализации не написана; есть только определения в законе | Municode ст. IV | нет, поправка | Определение "Building sewer means the extension from the building drain to the sewer lateral at the property line" верно, 110-228 тоже. Но граница написана в ROW Manual (Public Works, "Effective July 1, 2025", 5.6C, стр. 33), см. "Главное", пункт 2. Там же: "Only the City of McKinney Public Works Department is authorized to repair city-owned sanitary sewer or water mains, structures, or lateral service lines." |
| city-d6 | Город меняет медь 1997-2011 на HDPE, плохая медь и агрессивный грунт, свою часть, бесплатно | 1702/Water-Service-Line-Replacement-Project | да | "From 1997 to 2011...", "high-density polyethylene (HDPE)", "deterioration of substandard copper material and aggressive soil in the region", "No. The City of McKinney covers the cost of replacing the public portion of the service line." Цифры на странице не сходятся между собой (14,500 из 27,000 и 37,000 медных из 74,606): цифры не брать. |
| city-d7 | 110-22(c): хозяин за свой счёт ставит линии, краны, обратные клапаны, прочистки | Municode 110-22 | да | "including any customer service isolation valves, backflow prevention devices, clean-outs, and other equipment as may be specified by the city". |
| city-e1 | Кредит после течи как любезность | 2284 | да | Слово в слово. |
| city-e2 | 3x к тому же периоду, больше $150.00, раз в 12 месяцев, бланк за 60 дней, полив не считается, платить до кредита | 2284 | да | Все условия слово в слово. |
| city-e3 | Бланк: дата ремонта, описание, кто чинил, имя подрядчика, чек; 3x | form.jotform.com/230534509935055 | да | Поля "Date Leak Repaired", "Description of Repairs", "Repaired by" (Self, Contractor), "Name of Contractor", "Upload Receipt"; ссылка на бланк стоит на 2284. |
| city-e4 | AWWA 1.5%, счётчик не крутит быстрее | 2284 | да | Слово в слово. |
| city-f1 | В отчёте города жёсткости нет | View/127 (отчёт 2026, данные 2025) | да | Цитата на месте, слова "hardness" в отчёте нет. |
| city-f2 | NTMWD 2025, Wylie: 200 ppm, 96.0 - 200 | ntmwd.com/Archive.aspx?ADID=611 | да | Отрисовал стр. 7 ("NTMWD Wylie Water Treatment Plants, Water Quality Data for Year 2025 (continued)"): Highest 200, Range 96.0 - 200, ppm. |
| city-f3 | NTMWD 2025, Leonard: 144 ppm, 96.0 - 144 | ADID=611 | да | Стр. 11, таблица Leonard: 144, 96.0 - 144, ppm. (На стр. 9 таблица Tawakoni, 249, к Мак-Кинни не относится.) |
| city-f4 | Grains per gallon в отчётах нет; делить на 17.12; "moderately hard"; расчёт 11.7 и 8.4 | ntmwd.com/200/Water-Quality | да | Формула и "moderately hard" слово в слово. Числа в gpg нет и в листке NTMWD "Water Hardness" (Rev. Jan. 2022). Арифметика верна: 200/17.12 = 11.68, 144/17.12 = 8.41, 96.0/17.12 = 5.61. Это расчёт брифа, не цифра источника. |
| city-f5 | Покупная поверхностная вода NTMWD, шесть источников | View/127 | да | Слово в слово, плюс "purchases treated drinking water from the water treatment plants located in Wylie and Leonard". |
| city-g1 | 2024 IPC с поправками NCTCOG (март 2025), с 1 октября 2025; номера закона нет | 243 и Legistar | да | "The City of McKinney adopted the 2024 Codes on Oct 1, 2025."; проект "ORDINANCE NO. 2025-XX-", IPC: "dated March 2025". Legistar 25-3063: "On agenda: 8/19/2025", "Final action" пустое. |
| city-g2 | 2024 IRC с поправками NCTCOG (март 2025), с 1 октября 2025 | 243 и Legistar | да | Слово в слово; IRC тоже "dated March 2025". |
| city-g3 | Ежегодная проверка обратных клапанов; при конфликте с законом о cross connection берётся более строгое | Legistar View.ashx ID=14585641 | да | 312.10.1, 312.10.2, 608.1.1 слово в слово. Это проект закона. |
| city-g4 | Municode по 20 декабря 2022, там 2021; статьи XI нет | Municode | да | Последняя редакция: "Supplement 37", "Codified through Ordinance No. 2022-12-145, enacted December 20, 2022."; в главе 122 стоит 2021; в главе 110 статьи с I по X, XI нет. Поиск по Legistar я не повторял. |
| city-h1 | Струйка толщиной с грифель, снять шланги, утеплитель на наружный кран, выключить полив, при прорыве главный кран | 2284 | да | Точнее: струйка "from any faucet served by exposed pipes or those in exterior walls". |
| city-h2 | Тестеры BPAT регистрируются, $100, только бланки города, подлинник, без электронной подписи | 513/Backflow | да | Слово в слово. |
| city-h3 | FAQ про низкое давление; цифры давления в сети и правила PRV нет; потери от течи при 60 psi | faq.aspx?TID=26 и 2284 | да | Цитата на месте; 60 psi на 2284. В законе 110 (ст. II) есть только минимум для пожарных гидрантов: "A minimum sufficient water pressure of at least 20 psi"; это не давление в доме, не переносить. |
| city-h4 | Водонагреватель: верх бака, клапан, сливной кран, сбросная трубка; трубы в стенах, плите, земле | faq.aspx?TID=26 | да | Слово в слово. |
| city-h5 | Дымовой тест города каждый год июнь - август; дым из крыши норма, из двора дефект | 1275/Smoke-Testing | да | Слово в слово. |
| city-h6 | Аварийное закрытие через Public Works, отдел отвечает круглые сутки | Faq.aspx?TID=79 | да | Цитата на 79; "Answered 24 hours" стоит в блоке Water / Wastewater на 1275 и 1702. |
| city-h7 | Районы 30 лет без свинца; оцинковка 1980-х и раньше; бесплатная проба для домов до 1988 | 407 и 765 | да | "30 years" на 407; "In the 1980s and earlier" и условия пробы ("A home built before 1988", "Galvanized private water service lines", нужны оба) на 765. |

#### Можно брать в бриф (с поправками)

Все факты, кроме трёх в старой редакции, подтверждены. Поправленные версии:

- **city-b3:** "Разрешение на водонагреватель нужно (тип Water Heater в CSS). Residential Water Heater Permits $ 40.00 стоит в прейскуранте без даты (View/358) и в Residential Builders Packet, действующем с 1 октября 2025 (View/2670, стр. 7)."
- **city-b4:** "Отдельной памятки для замены водонагревателя нет. В Residential Builders Packet, действующем с 1 октября 2025 (на него отсылает страница Building Inspections для готовности к инспекции): T&P line termination no less than 6” from floor or receptor; Expansion tank installed if thermal expansion encountered and not controlled; Water heater T&P line roughed-in and pan drain installed. 2024 IPC 504.7: пластиковый поддон под газовым баком с flame spread не больше 25 и smoke-developed index не больше 450."
- **city-c2:** "Residential Builders Packet, действующий с 1 октября 2025: Any inspection properly scheduled before 3:00 PM will be scheduled for the next business workday. Правило after 3 PM: 2 business days out есть только в памятке Public Works про инспекции полива от 9/11/2020 (View/25379)."
- **city-d5:** "Город (Public Works, Right-of-Way Construction & Permitting Procedures Manual, Effective July 1, 2025, 5.6C): The city owned section of a lateral service is typically from the main pipeline to the (water) meter or (sewer) cleanout. The property owner or customer’s section of a lateral service is typically from the (water) meter or (sewer) cleanout to the serviced building/structure. В законе: Building sewer means the extension from the building drain to the sewer lateral at the property line; по 110-228 городская врезка тянет отвод от магистрали до границы участка или сервитута, прочистка у границы участка."

Остальные 43 подтверждены как есть: a1, a2, a3, a4, b1, b2, b5, b6, b7, b8, b9, b10, b11, b12, c1, c3, c4, c5, d1, d2, d3, d4, d6, d7, e1, e2, e3, e4, f1, f2, f3, f4, f5, g1, g2, g3, g4, h1, h2, h3, h4, h5, h6, h7 (с уточнениями из таблицы).

#### Нельзя брать

В старой редакции (ошибка):
- "Пакет для строителей от 7 января 2020" и любые выводы из этого: "оба документа с отсечкой 2020 года", "свежего документа с отсечкой нет" (city-b3, city-b4, city-c2, и тот же вывод в разделе "Пояснения", пункт c, файла 6a-official-city.md). Видимая дата пакета: 1 октября 2025.
- "Граница ответственности по канализации на страницах города не написана" (city-d5): написана в ROW Manual 2025.

На страницу как есть (правила CLAUDE.md, факты верные, но в текст страницы не переносить):
- Wylie, Leonard (станции NTMWD), названия улиц из списка замены линий на 1702: не наши десять городов или адреса. Писать "вода NTMWD, главное озеро Lavon Lake".
- Все телефоны города и подрядчиков города (правило 10).
- Платы города (40.00, 75.00, 50.00 и другие) и цифры кредита ($150.00): не наши цены, без слова Дениса не ставить.
- Регистрация тестеров BPAT и кто тестирует обратный клапан: на странице только фраза "Once the new assembly is in, it gets tested and the test report goes to the city."
- Расчёт gpg (11.68, 8.41) подавать только как пересчёт по формуле NTMWD, не как цифру города.
- Цифры числа линий с 1702 (14,500, 27,000, 37,000, 74,606): страница сама себе противоречит.
- "20 psi" из закона 110: это минимум для пожарных гидрантов, не давление в доме.
- "Rerouting of a zone" из 110-477: это про зону полива; reroute как нашу услугу не писать.

### 6.4. Перепроверка индексов и возраста домов: таблица и находки (файл `6b-zip-and-age-verified.md`)

Заголовок файла: «6b, проверка. Почтовые индексы и возраст домов McKinney: что подтвердилось».

Проверено 3 октября 2026, вторым помощником, с нуля. Чужие выписки я не брал: сам заново скачал официальные файлы USPS и Census, сам сделал запросы к data.census.gov, к Census API, к карте TIGERweb и к слою адресов ГИС города McKinney. Проверяемый раздел: docs/briefs/mckinney/6b-zip-and-age.md. Мои выписки лежат рядом, в папке work-6b-verify (только итоги и счетчики, без координат и без адресов).

Главный итог: из 32 фактов подтверждены 29. Один факт (cmp-d1) верен по цифрам, но подписан неправильно: 72,8% это жилье, построенное в 2000 году и позже (вместе с 2020-ми), а не "2000-е и 2010-е"; правильные цифры ниже. Один факт (zip-a9) подтвержден наполовину: ГИС города верна полностью, а фотоальбом города прямо привязывает к площади только Virginia и Tennessee. Сервис USPS "Cities by ZIP Code" (zip-a10) у меня тоже не открылся, из него ничего брать нельзя.

#### Как я проверял

- USPS: сам скачал Zip_Locale_Detail.xlsx (ответ 200, 4 380 487 байт, last-modified 1 октября 2026, 21:23:18 GMT), разобрал все три листа. Строки в work-6b-verify/usps-zip-locale-rows.txt. Что значит пустое поле "ZIP CLASS CODE", сказано в официальном руководстве USPS "Address Information System Products Technical Guide" (апрель 2016, postalpro.usps.com/storages/2016-04/AIS_0.PDF): "Blank = Non-Unique", "P = PO Box Zip", "U = Unique Zip".
- Земля: сам скачал файл связи ZCTA и городов 2020 года (tab20_zcta520_place20_natl.txt) и пересчитал доли. Выписка: work-6b-verify/tab20-zcta-place-mckinney.txt.
- Жилье 2020 года по индексам и городам: другим путем, чем первый помощник (он клал центр квартала в контур индекса на карте). Я взял официальный файл "квартал к ZCTA" (tab20_zcta520_tabblock20_natl.txt, 1 057 697 144 байт, оставил кварталы округов Collin и Denton), принадлежность квартала городу из Block Assignment File (BlockAssign_ST48_TX.zip) и число жилья по каждому кварталу из переписи 2020 года (DECENNIALPL2020.H1 на data.census.gov, все 16 324 квартала округа Collin одним запросом). Поле HU100 карты TIGERweb совпало с этими числами во всех 16 324 кварталах. Стороны US 75 и US 380: внутренняя точка квартала из TIGERweb против линий дорог из TIGERweb Transportation (слой 2 "US Hwy 75", слой 3 "US Hwy 380"). Итоги: work-6b-verify/blocks-2020-recheck.txt.
- ACS 2020-2024: сам сделал заново запросы к data.census.gov (B25035, B25034, B25037, B25127 для 75069, 75070, 75071, 75072, 75454, McKinney, Frisco, Plano; плюс прошлый выпуск B25035 и Fairview town) и пересчитал доли. Названия строк сверил по описаниям таблиц Census API (groups). Строки официальных файлов acsdt5y2024-b25034.dat и b25035.dat (и b25035 за 2023 год) скачал сам и сравнил с data.census.gov: B25034 198 клеток, 0 расхождений; B25035 все 10 строк совпали. Выписка: work-6b-verify/acs-datacensus-recheck.txt.
- ГИС города McKinney: сам сделал запросы-счетчики к слою "Address Points" и прочел описание слоя. Чтобы проверить, что COUNTY значит "вне черты города", я проверил все 6 834 жилые точки COUNTY с индексом 75071 по границе города из TIGERweb (выпуск на 1 января 2026): 6 831 вне черты, 3 внутри. Итоги: work-6b-verify/city-gis-address-counts.txt.
- Фотоальбом города, живая страница, Census API, папки выпуска 2025, площадь города в TIGERweb: work-6b-verify/album-live-page-check.txt и api-and-files-check.txt.

#### Таблица проверки

| id | Что утверждается (коротко) | Источник | Подтверждено | Примечание |
|---|---|---|---|---|
| zip-a1 | Четыре индекса McKinney, все обычные (класс пустой): 75069, 75070, 75071, 75072; все при отделении MCKINNEY (550 N Central Expy), у 75071 еще LINKSIDE PARK (7210 Virginia Pkwy Ste 100); файл от 1 октября 2026, 4 380 487 байт | USPS Zip_Locale_Detail.xlsx | да | Строки слово в слово: "752, 75069, класс пустой, MCKINNEY, W24653, P, 550 N CENTRAL EXPY", то же для 75070, 75071, 75072; "752, 75071, класс пустой, LINKSIDE PARK, 017833, S, 7210 VIRGINIA PKWY STE 100". Пустой класс по руководству USPS: "Non-Unique", то есть обычный индекс. Слова "главное" и "станция" это прочтение букв P и S в поле LOCALE TYPE; на странице они не нужны |
| zip-a2 | Индекса только для PO BOX у McKinney нет; в листах Unique и Other строк McKinney нет | тот же файл USPS | да | У всех пяти строк McKinney класс пустой, буквы P нет. В листах Unique и Other нет ни индексов 75069-75072, ни города MCKINNEY; слово MCKINNEY там есть только в адресе почты Denton ("101 E MCKINNEY ST", индексы 76203, 76204), это улица в Denton |
| zip-a3 | Суша McKinney 2020 года 173 432 672 кв. м: 75071 40,84%, 75069 23,55%, 75072 17,64%, 75070 16,84%, 75454 1,13%, 75407 1 133 кв. м; четыре индекса 98,87% | tab20_zcta520_place20_natl.txt | да | Все цифры совпали: 70 828 729, 40 850 959, 30 590 352, 29 197 722, 1 963 777, 1 133 кв. м; сумма четырех 171 467 762 = 98,867% |
| zip-a4 | 75069: 16 229 единиц жилья (2020), McKinney 10 882 (67,05%), Fairview 4 564 (28,12%), Lowry Crossing 561 (3,46%), вне городов 221 (1,36%), Lucas 1; все жилье McKinney в 75069 к востоку от US 75 | перепись 2020 по кварталам; DECENNIALDHC2020.H1 | да | Мой пересчет другим методом дал те же числа до единицы; итог участка на data.census.gov 16 229. По моей проверке к западу от US 75 жилья McKinney в 75069 ноль (10 882 к востоку). Это расчет по кварталам, не готовая цифра Census |
| zip-a5 | 75071: 22 133 единицы, McKinney 18 622 (84,14%), вне городов 3 128 (14,13%), New Hope 258, Frisco 78, Celina 47; в ГИС города 6 834 жилых адреса COUNTY (ETJ) под 75071 против 28 264 в черте | перепись 2020 по кварталам; ГИС McKinney, Address Points | да | Все совпало. Описание слоя: "This data contains the Address Points for the City of McKinney and its ETJ." и "Address points outside the city limits but within ETJ are assigned and coordinated with Collin County GIS." Что COUNTY значит "вне черты", я проверил сам: 6 831 из 6 834 точек лежат вне границы города (TIGERweb, 1 января 2026). В 28 264 входят 14 точек с кодом MCK вместо MCKN |
| zip-a6 | 75070: 24 151 единица, 100% McKinney. 75072: 19 047, McKinney 18 830 (98,86%), Frisco 164 (0,86%), вне городов 53. Оба целиком к западу от US 75 и к югу от US 380 | перепись 2020 по кварталам; DECENNIALDHC2020.H1 | да | Совпало до единицы, итоги участков на data.census.gov 24 151 и 19 047. Стороны дорог: мой расчет дал 100% к западу и 100% к югу для обоих |
| zip-a7 | 75454 (почта MELISSA): 391 единица жилья McKinney (0,54% города, 7,41% участка, Melissa 84,24%); в ГИС города 4 жилых адреса McKinney с 75454; 75407 (PRINCETON) задевает 1 133 кв. м без жилья | файл связи 2020; перепись 2020; ГИС города | да | 391, 0,54%, 7,41%, Melissa 4 443 (84,24%) совпали; в ГИС MCKINNEY и 75454: 19 точек, из них 4 жилых. 75407: 1 133 кв. м, жилья McKinney 0 |
| zip-a8 | McKinney 72 876 единиц жилья в 2020 году (PL 94-171 H1): 75070 24 151 (33,14%), 75072 18 830 (25,84%), 75071 18 622 (25,55%), 75069 10 882 (14,93%), 75454 391 (0,54%); 83,6% к западу от US 75, 89,5% к югу от US 380 | DECENNIALPL2020.H1; расчет по кварталам | да | 72 876 на data.census.gov (H1_001N). Мой расчет сторон дорог: к западу от US 75 60 952 (83,6%), к югу от US 380 65 254 (89,5%). Это расчет по внутренним точкам кварталов и линиям дорог выпуска 2026 года, не готовая цифра Census |
| zip-a9 | Фотоальбом города называет улицы площади (Virginia, Louisiana, Tennessee, Kentucky); в ГИС города все адреса N/S Tennessee, N/S Kentucky, N/S Chestnut, E/W Louisiana и E/W Virginia St под 75069 | mckinneytexas.org/PhotoGallery/Album/2; ГИС города | нет, подтверждено наполовину | ГИС: да, все группы адресов этих улиц стоят под 75069 (Tennessee 174 и 210, Kentucky 137 и 99, Chestnut 70 и 79, Louisiana 157 и 168, Virginia St 194 и 206 точек). Virginia Pkwy это другая улица, она под 75071 и 75072. Альбом: подпись "Virginia Street North Side of Square" на месте, есть "East Side of Square looking South on Tennessee". Kentucky к площади привязана только парой подписей "Circa 1955 Ritz Theater NW Corner of Square" и "Ritz Theater NE Corner of Virginia and Kentucky". Louisiana в альбоме есть ("Circa 1928 Looking East on Louisiana Street"), но ни одна подпись не связывает ее с площадью |
| zip-a10 | Сервис USPS "Cities by ZIP Code" не открылся | tools.usps.com, cityByZip | нет | Мой один запрос по 75069 тоже ушел на anyapp_outage_apology.htm; повторять и обходить не стал. Какие еще названия городов почта принимает для этих индексов, не проверено |
| zip-a11 | Суша города 177 990 541 кв. м в TIGERweb (выпуск 1 января 2026) против 173 432 672 в 2020 году, на 2,63% больше | TIGERweb tigerWMS_Current, слой 28 | да | Слой "Incorporated Places; January 1, 2026 vintage": AREALAND 177 990 541. Разница с файлом 2020 года 2,63%. Для сведения: слой TIGERweb 2020 года дает 173 544 065 (разница 2,56%), а слой ACS2024 уже 177 990 541, то есть рост произошел до 2024 года. Это сравнение площадей, не формы границы |
| api-1 | Census API без ключа: 302 на missing_key.html (2024 и 2025); цифры взяты из официального ACS Summary File и сверены с data.census.gov (1 500 клеток, 0 расхождений) | api.census.gov | да | Все четыре запроса дали 302 на https://api.census.gov/data/missing_key.html, на странице слова "A valid key must be included with each data API request." Его счет "1 500 клеток" я поштучно не повторял; сам сравнил файл B25034 с data.census.gov (198 клеток) и все строки B25035, расхождений нет |
| api-2 | Новейший выпуск ACS 5-year 2020-2024; описание B25035_001E за 2024 отвечает 200, за 2025 404; папка data выпуска 2025 пустая; файлы 2024 от 29 января 2026 | api.census.gov; www2.census.gov | да | 2024: 200, "Estimate!!Median year structure built". 2025: 404, и /data/2025/acs/acs5.json тоже 404. В папке summary_file/2025/table-based-SF есть data (2026-09-23) и documentation (2026-09-29), обе пустые. acsdt5y2024-b25035.dat: 29 января 2026, 13:11:37 GMT |
| age-75069 | 75069: медиана 2000 (±2), владельцы 1999 (±3), съемщики 2001 (±2), 17 022 единицы; прошлый выпуск 2000 (±2); треть жилья не McKinney (в основном Fairview, медиана 2006) | data.census.gov ACSDT5Y2024 B25035, B25037, B25034; ACSDT5Y2023 B25035 | да | Все совпало. Не McKinney в 2020 году 32,95% жилья участка. Fairview town: 2006 (±1) |
| age-75070 | 75070: 2010 (±2), владельцы 2007 (±1), съемщики 2012 (±1), 25 707 | data.census.gov ACSDT5Y2024 | да | Совпало |
| age-75071 | 75071: 2011 (±2), владельцы 2011 (±2), съемщики 2008 (±2), 25 276 | data.census.gov ACSDT5Y2024 | да | Совпало |
| age-75072 | 75072: 2004 (±1), владельцы 2004 (±1), съемщики 2005 (±2), 18 648 | data.census.gov ACSDT5Y2024 | да | Совпало |
| age-75454 | 75454: 2015 (±2), 7 124 единицы; в McKinney только 7,4% его жилья 2020 года | data.census.gov ACSDT5Y2024; перепись 2020 | да | Совпало (391 из 5 274 = 7,41%) |
| age-mckinney | McKinney city: 2007 (±1), прошлый выпуск 2006 (±2), владельцы 2007 (±2), съемщики 2008 (±1), 77 617 единиц | data.census.gov ACSDT5Y2024 и 2023; строка 1600000US4845744 файла b25035 | да | Совпало, в файле "1600000US4845744, 2007, 1" |
| age-frisco | Frisco city: 2009 (±1), владельцы 2008 (±1), 80 353 единицы; как в брифах Plano и Allen | acsdt5y2024-b25035.dat; data.census.gov | да | Файл: "1600000US4827684, 2009, 1". Те же цифры в docs/briefs/plano/6b-zip-and-age-verified.md и docs/briefs/allen/6b-zip-and-age-verified.md. Только для автора |
| age-plano | Plano city: 1993 (±2), владельцы 1991 (±1), 117 686 единиц | acsdt5y2024-b25035.dat; data.census.gov | да | Файл: "1600000US4858016, 1993, 2". Только для автора |
| share-75069 | 75069: до 1980 26,1%, 1980-1999 22,9%, 2000-2009 25,5%, 2010 и позже 25,5%; до 1960 12,4% (2 108), до 1940 5,2% (885); без Fairview грубо 32,9 / 25,3 / 19,1 / 22,6, до 1940 7,1% | data.census.gov ACSDT5Y2024 B25034 (и Fairview town) | да | Все совпало. 2 108 = 927 (1950-е) + 296 (1940-е) + 885 (1939 и раньше). Оценка без Fairview: 4 108, 3 159, 2 386, 2 817 и 885 из 12 470. Вычитание честное: в 2020 году 4 564 из 4 568 единиц Fairview лежат в 75069. Но это разность двух выборочных оценок, очень грубо |
| share-75070 | 75070: 2,4 / 15,5 / 33,4 / 48,7 | data.census.gov B25034 | да | Совпало |
| share-75071 | 75071: 5,1 / 12,6 / 29,6 / 52,7, с 2020 года 9,3% | data.census.gov B25034 | да | Совпало (2 362 из 25 276 с 2020 года) |
| share-75072 | 75072: 2,3 / 31,0 / 41,7 / 25,0 | data.census.gov B25034 | да | Совпало |
| share-75454 | 75454: 3,8 / 7,0 / 16,4 / 72,8 | data.census.gov B25034 | да | Совпало |
| share-mckinney | McKinney: до 1980 7,8% (6 092), 19,4 / 33,2 / 39,6; дома на одну семью (B25127) 55 328, 74,7% занятого жилья; из них до 1980 7,9%, 1980-1999 19,5%, 2000 и позже 72,6% | data.census.gov B25034, B25127 | да | Все совпало. 55 328 это строки "1, detached or attached" среди занятого жилья (74 072); туда входят и таунхаусы. Не делить на 77 617 (там и пустующее жилье) |
| share-frisco-plano | Frisco 1,5 / 16,9 / 34,8 / 46,7; Plano 18,4 / 50,3 / 17,6 / 13,7 | acsdt5y2024-b25034.dat; data.census.gov | да | Совпало, файл и data.census.gov одинаковы. Только для автора |
| old-1 | Жилье 1939 года и раньше: McKinney 1 128 (±356), Plano 292 (±119), Frisco 47 (±61); около трех четвертей (885) и около двух третей до 1980 (4 108 из 6 092) в 75069 без Fairview | data.census.gov B25034; b25034.dat | да | Совпало: 885 из 1 128 = 78,5%, 4 108 из 6 092 = 67,4%. Оговорка: в этих остатках еще Lowry Crossing и земля вне городов (783 из 11 665 единиц в 2020 году), а у 885 своя погрешность ±325 |
| cmp-d1 | McKinney 2007 почти как Frisco 2009, на 14 лет новее Plano 1993; "72,8% жилья из 2000-х и 2010-х (Frisco 81,5%, Plano 31,3%)" | b25035.dat, b25034.dat | нет, неверная подпись | Медианы верны. Но 72,8%, 81,5% и 31,3% это доли жилья, построенного в 2000 году и позже, вместе с "Built 2020 or later". Только 2000-е и 2010-е: McKinney 67,9%, Frisco 74,8%, Plano 29,6%. Та же подпись стоит в разделе "г" файла 6b ("2000-е и 2010-е (72,8%...)") |
| cmp-d2 | У McKinney есть старый центр: до 1980 7,8% (Frisco 1,5%, Plano 18,4%); домов до 1940 больше, чем в Plano и Frisco вместе; это 75069 к востоку от US 75 у площади; запад и север (75070, 75071, 75072, медианы 2004-2011) по возрасту как Frisco | b25034.dat; data.census.gov; расчет по кварталам | да, с оговоркой | Цифры верны: 1 128 больше 292 + 47 = 339 даже с учетом погрешности. "Как Frisco" точно для 75070 и 75071 (медианы 2010 и 2011, Frisco 2009). 75072 старше: медиана 2004, а с 1980 по 1999 год там построено 31,0% жилья (у Frisco 16,9%) |
| live-1 | На живой странице и в тексте нового сайта "Around the historic center and the older established streets" и "Once a McKinney house passes the twenty year mark"; данные подтверждают старый центр (75069), половина жилья построена до 2007 года | fppplumbing.com/plumber-mckinney-tx/; site/src/content/pages/plumber-mckinney-tx.md | да | Живая страница ответила 200, обе фразы стоят слово в слово, там же заголовки "Older McKinney, Newer McKinney" и "Main Water Line Repair in Older McKinney Homes". В файле нового сайта строки 53 и 92. До 2000 года построено 27,2% жилья города. Про чугун и медь Census ничего не знает |

#### Что еще я сверил в разделе 6b сверх списка фактов

Дома на одну семью по индексам, десятилетия, доли суши участков, адреса ГИС по всем индексам, коды FRIS, стороны дорог для 75071: все совпало, расхождений нет. Подробно в work-6b-verify/extra-checks.txt.

#### Можно использовать в брифе

1. Почтовые индексы McKinney: 75069, 75070, 75071, 75072, все обычные, с доставкой (USPS ZIP Locale Detail, файл от 1 октября 2026). Индекса только для абонентских ящиков у McKinney нет.
2. Четыре индекса покрывают 98,9% суши города (2020). 75454 (почта Melissa) это 1,1% суши и 391 единица жилья McKinney (0,5%); 75407 (почта Princeton) задевает город клочком без жилья. Показывать 75454 и 75407 как индексы McKinney нельзя.
3. Жилье 2020 года по индексам: 75070 33,1%, 75072 25,8%, 75071 25,6%, 75069 14,9% жилья города. 75070 и 75072 почти целиком McKinney (100% и 98,9% жилья участка). В 75069 только 67,1% жилья участка в McKinney, в 75071 84,1%.
4. Под 75071 много домов вне черты города, в ETJ: 3 128 единиц жилья по переписи 2020 года, 6 834 жилых адреса округа в слое адресов самого города. Адрес "McKinney, TX 75071" не значит, что дом в черте города; слова про разрешение и инспекцию города McKinney к ним не относятся.
5. Старое жилье McKinney стоит в 75069, к востоку от US 75: все жилье McKinney в 75069 к востоку от US 75, а адреса улиц у площади (Tennessee, Kentucky, Chestnut, Louisiana, Virginia St) все под 75069 по ГИС города. Площадь стоит на Virginia и Tennessee, это прямо написано в подписях официального фотоальбома города.
6. Медианный год постройки жилья, ACS 2020-2024, таблица B25035: McKinney city 2007 (±1); 75069 2000, 75072 2004, 75070 2010, 75071 2011, 75454 2015. Жилье владельцев: город 2007, 75069 1999, 75072 2004, 75070 2007, 75071 2011.
7. Доли по годам, весь город (B25034): до 1980 года 7,8%, 1980-1999 19,4%, 2000-2009 33,2%, 2010 и позже 39,6%; построено до 2000 года 27,2%, в 2000 году и позже 72,8%. В 75069 до 1980 года 26,1%, в 75070, 75071, 75072 от 2,3% до 5,1%.
8. Дома на одну семью (с таунхаусами, только занятое жилье): 55 328, 74,7%; из них до 1980 года 7,9%. В 75069 таких старых 33,7%.
9. Жилья 1939 года и раньше в McKinney по оценке 1 128 (±356), в 75069 885 (±325).
10. Сравнение с Фриско (2009) и Плано (1993), домов до 1940 года больше, чем у Плано и Фриско вместе: только знание для автора, на странице McKinney другие города не называются.
11. Граница города с 2020 года выросла (суша на 2,6%), доли суши посчитаны по границе 2020 года.
12. Самая надежная одна цифра для страницы, если автор захочет ссылку на официальный источник: медианный год постройки жилья в McKinney 2007 (U.S. Census Bureau, ACS 5-year 2020-2024, таблица B25035, McKinney city, Texas).

#### Нельзя использовать

1. Подпись "72,8% жилья это 2000-е и 2010-е" (и 81,5% у Фриско, 31,3% у Плано как "2000-е и 2010-е"): это доли жилья "2000 год и позже". Только 2000-е и 2010-е: 67,9%, 74,8%, 29,6%. Исправить в разделе "г" файла 6b.
2. Утверждение, что фотоальбом города называет Louisiana улицей площади: в подписях этого нет. Kentucky привязана к площади только косвенно. Для автора хватит Virginia и Tennessee, плюс ГИС.
3. Какие названия городов почта принимает для индексов McKinney: сервис USPS "Cities by ZIP Code" не открылся ни у первого помощника, ни у меня.
4. Слова "как Фриско" про 75072: медиана 2004 и треть жилья из 1980-1990-х, это старше Фриско. Для 75070 и 75071 сравнение верно, но и оно только для автора.
5. Оценки "75069 без Fairview" (32,9%, 7,1%, "три четверти", "две трети") на странице: это разность двух выборочных оценок, туда же попали Lowry Crossing и земля вне городов. Только как ориентир для автора.
6. Названия соседних городов из таблиц (Fairview, Lowry Crossing, Lucas, New Hope, Melissa, Anna, Princeton, Wylie, а на странице McKinney и Frisco, Celina): только для автора. Первые восемь на сайте не называются совсем, города из списка десяти нельзя называть на странице McKinney (правило CLAUDE.md).
7. Счет "1 500 клеток без расхождений": это его счет, поштучно я его не повторял (все цифры фактов при этом проверены мной).
8. Про чугун, медь, корни и возраст труб на конкретных улицах: Census этого не знает, это только знание Дениса.

#### Адреса, которые я открывал 3 октября 2026

Полный список адресов с ответами сервера лежит в work-6b-verify/sources-opened.txt и work-6b-verify/api-and-files-check.txt. Главные: USPS Zip_Locale_Detail.xlsx и руководство AIS_0.PDF; файлы связи Census tab20_zcta520_place20_natl.txt и tab20_zcta520_tabblock20_natl.txt; BlockAssign_ST48_TX.zip; data.census.gov (DECENNIALPL2020.H1 по кварталам Collin, DECENNIALDHC2020.H1, ACSDT5Y2024 и ACSDT5Y2023); ACS Summary File 2024 и 2023; Census API; TIGERweb (tigerWMS_Current, ACS2024, Census2020, Transportation); слой адресов ГИС McKinney; фотоальбом города https://www.mckinneytexas.org/PhotoGallery/Album/2; живая страница https://fppplumbing.com/plumber-mckinney-tx/.

## 7. Офис

Файла раздела для этой части не было: она написана при сборке по CLAUDE.md, по краулу живой страницы (`source/crawl/pages/plumber-mckinney-tx.json` и `source/crawl/html/plumber-mckinney-tx.html`, обход 30 сентября 2026; по части 1 живая страница 3 октября в 11:01 совпала с ним байт в байт), по выгрузке Google Business Profile (`source/gbp-takeout/`, файлы data.json двух карточек от 30 сентября 2026) и по файлам нового сайта (`site/src/content/pages/plumber-mckinney-tx.md` от 10:24, `site/src/layouts/ServicePage.astro`, `site/src/components/CallButtons.astro`, `Body.astro`, `ReviewCards.astro`, `site/src/lib/site.ts`, `site/src/lib/schema.ts`, `site/src/design/design.json`, прочитаны 3 октября 2026 около 11:45). Карточки Google у McKinney нет.

### 7.1. Что говорит CLAUDE.md

- Офисы есть только во Frisco и в Plano. Страницы остальных восьми городов описывают обслуживание города из ближайшего офиса: "The other eight city pages describe service coverage of that city from the nearest office. Never invent a local office, address or phone for a city that has none."
- Офис Frisco: 12800 Westridge Blvd, Suite 116, Frisco, TX 75035, линия 469-998-8999. Офис Plano: 5700 Tennyson Pkwy, Suite 300, Plano, TX 75024, линия 980-899-7997.
- Телефоны стоят в шапке, в подвале, в кнопках звонка и в блоках офисов на страницах Frisco и Plano. В абзацах и в ответах FAQ их нет (правило 10).
- Схема: один бизнес на весь сайт (Plumber, `#organization`) с обоими офисами; страница города без офиса ссылается на организацию и называет город в `areaServed`.
- Одобренная строка про дежурство: "A licensed plumber is on duty 24/7". В каком городе сейчас дежурный сантехник, не показываем. Времени приезда своими словами не обещаем.
- Формулировка "About a twenty minute drive from our Frisco or Plano office" в CLAUDE.md дана для мест вне списка городов ("for everything else") и описывает район, а не время приезда. Для McKinney, у которого своя страница, она не предназначена.
- Страница города не называет соседние города и не ссылается на страницы других городов (правило 7).

Чего в CLAUDE.md нет: какой из двух офисов обслуживает McKinney. Не сказано и то, как называть офис на странице города без офиса: по имени ("our Plano office", "our Frisco office") или без названия города. Имя офиса это название соседнего города, и это упирается в правило 7. Оба вопроса стоят в части 10.

Что есть в проекте вместо ответа (это не слово Дениса):

- Главная (`source/home-text-v4.md`, раздел «Where We Work»): "Two offices cover the whole area. A plumber in Frisco works out of our office on Westridge Boulevard, a plumber in Plano out of Tennyson Parkway. East of the two offices the same trucks take the calls for a plumber in Allen and a plumber in McKinney." Офис для McKinney не назван.
- Страница emergency: "North and east of us the drive is short: a plumber in McKinney, a plumber in Allen, a plumber in Prosper or a plumber in Celina is inside the loop we run every day anyway." (часть 8, `8-links-details.md`, часть А).
- Схема живой страницы: отдельный бизнес с адресом, точкой на карте и телефоном офиса Frisco (ниже, 7.2). На главном фото живой страницы на борту фургона телефон Plano ("980.899.7997", часть 1, раздел 4).
- Выгрузка Google (`source/gbp-takeout/`, data.json, 30 сентября 2026): в зоне обслуживания карточки Plano (телефон (980) 899-7997, сайт /plumber-plano-tx/) среди 18 мест стоит «Мак-Кинни, Техас, США». У карточки Frisco (телефон (469) 998-8999, сайт /plumber-frisco-tx/) поле зоны обслуживания в выгрузке пустое. Вживую карточки этой ночью не открывались. Для сведения Денису, к странице McKinney не относится: в той же зоне карточки Plano стоят места, которые CLAUDE.md не разрешает называть (Irving, Addison, Coppell, Richardson, Fairview, Farmers Branch, два индекса Dallas); это работа над карточками Google, она в очереди после страниц.
- Search Console (часть 2, раздел 6): по «plumber mckinney tx» за 3 месяца выше страницы McKinney стоят страницы Frisco (98 · 17.9) и Plano (75 · 17.3); «emergency plumber mckinney» за 3 месяца страница Frisco держит на месте 1.6 (21 показ), по правилу проекта это показ карточки Frisco. Выгрузка не отделяет карточку от обычной выдачи.

### 7.2. Что показывает живая страница

- Адреса офиса в видимом тексте страницы нет. В подвале (общий шаблон старого сайта, блок "Found us") стоят оба офиса: "Frisco Office", 12800 Westridge Blvd, Suite 116, и "Plano Office", 5700 Tennyson Pkwy, Suite 300, с обоими телефонами (сверено по сохранённому HTML).
- Карты нет: в коде страницы нет ни одной встроенной карты (единственный iframe это служебный тег Google Tag Manager).
- Телефоны: оба номера ссылками `tel:` (в коде по четыре ссылки на каждый номер; по части 1 это шапка, подвал и нижняя панель). Нижняя панель свёрстана тегом H2: "980-899-7997 469-998-8999". В абзацах и в FAQ телефонов нет.
- В тексте офис не назван, слов «рядом» и «по пути» нет. О времени: "tired of four hour windows" и "a licensed plumber who arrives inside it" (часть 1, раздел 6.2).
- Схема: отдельный узел бизнеса "FPP Plumbing - Plumber in McKinney, TX" (`/plumber-mckinney-tx/#business`) с адресом, точкой на карте и телефоном офиса Frisco (+1-469-998-8999), часами круглые сутки и `areaServed`: McKinney, Fairview, Allen, Prosper, Melissa. У организации в той же схеме телефон Plano (+1-980-899-7997). Подробно: часть 1, раздел 6.5, и `1-live-page-tables.md`, Т6.

### 7.3. Что новый сайт показывает на этой странице сегодня

Файл страницы: layout "city", city "McKinney". Полей `office`, `call_office` и `office_map` в нём нет (у страницы Frisco стоят `office: "frisco"`, `call_office: true`, `office_map: true`; у Plano `office: "plano"`). В `site/src/lib/site.ts` своей страницей офиса записаны только /plumber-frisco-tx/ и /plumber-plano-tx/.

- Над H1 строка "A licensed plumber is on duty 24/7" (её получают все страницы городов и страница emergency).
- Под вступлением две кнопки звонка без цифр: "Call" и "Frisco office" (красная), "Call" и "Plano office" (с обводкой); рядом кнопка "Request Service". Одна кнопка со своим номером бывает только на странице офиса с полем `call_office`.
- Блока офиса и карты нет: шаблон ставит их только на странице, которая записана у офиса как его собственная.
- Шапка: оба номера и кнопка Call; на телефоне липкая панель звонка с обоими номерами. Подвал общий для всего сайта: оба офиса с адресами и номерами.
- Первый экран: главным фото встаёт первая картинка текста, то есть то же фото фургона со старого адреса, alt "FPP Plumbing truck in McKinney during same-day plumbing service".
- Отзывы: в тексте стоит метка `<!-- reviews -->`, но в `reviews/site-reviews.json` (файл от 10:04) ключа этой страницы нет, значит блок отзывов не выводится. Поля `reviews_heading` ("What McKinney Homeowners Say About FPP Plumbing") и `reviews_intro` ("Real Google reviews from local homeowners.") записаны в файле страницы, но шаблон их не читает.
- Схема: один бизнес с обоими офисами, как на всём сайте, и узел Service с именем "Plumber in McKinney, TX", `serviceType` "Plumbing", поставщиком организацией и `areaServed` McKinney. Отдельного бизнеса города, чужих городов в `areaServed` и `priceRange` на этой странице новый сайт не делает: это исправлено самим шаблоном.
- Что осталось от старого текста и спорит с правилами про время: "tired of four hour windows", "a licensed plumber who arrives inside it with parts already on board"; описание "same-day service" (время своими словами на городских страницах правилами не решено).

### 7.4. Что из этого следует для новой страницы

- Блока офиса, карты, адреса и своего телефона у страницы McKinney быть не должно. Кнопки остаются как есть, пока Денис не назовёт офис. Если он назовёт один офис, решить с ним, ставить ли на первый экран одну кнопку с номером этого офиса или оставить две.
- В тексте нужна одна честная фраза о том, откуда мы приезжаем в McKinney, без минут и часов. Писать её можно только после ответа Дениса (какой офис и как его назвать).
- Фразу страницы Frisco про то, кто приедет ("the plumber at your door may be Nick, Christopher or Denys"), слово в слово не повторять: она стоит в блоке офиса Frisco.
- Заголовок и строку над отзывами решать вместе с выбором отзывов (часть 5): "Real Google reviews" станет неправдой с отзывом Thumbtack, а «from McKinney homeowners» неправда, пока ни один отзыв не привязан к McKinney.

## 8. Посты и гайды

Файл раздела: `docs/briefs/mckinney/8-links.md`, вставлен целиком. Заголовок файла: «8. Истории из McKinney, которые уже есть на сайте, и ссылки для страницы McKinney».

Рядом и в бриф не вставлены: `8-links-details.md` (10 КБ: цитаты про McKinney с других страниц, 13 услуг с якорями и запросами «услуга + mckinney», фото из McKinney) и `8-links-queries-by-page.md` (15 КБ: все запросы со словом McKinney по страницам, 3 и 16 месяцев).

Собрано 3 октября 2026, около 11:00. Работа только на чтение: в проекте ничего не менялось, страница McKinney не переписывалась.

### Откуда данные

- Живой сайт: снимок 64 страниц в `source/crawl/pages/*.json` (снят 30 сентября 2026), поля title, h1, body_text, images, internal_links.
- Новый сайт: файлы страниц `site/src/content/pages/**/*.md`, прочитаны 3 октября около 11:00 (у файлов городов стоит время 10:24, их пересобирал другой процесс). Навигация: `site/src/components/Header.astro`, `Footer.astro`, главная: `site/src/design/home-text.json`, `site/src/layouts/Home.astro`.
- Search Console: `source/gsc/performance-3m/Pages.csv` и `performance-16m/Pages.csv` (итог страницы), `source/gsc/page-query-3m.csv` и `page-query-16m.csv` (строки «страница плюс запрос»). 3 месяца это 1 июля до 28 сентября 2026, 16 месяцев это 31 мая 2025 до 28 сентября 2026.
- План работ `docs/pages-plan.md`, карта ключей `seo/keyword-map.md`, находки `seo/cannibalization-findings.md`, подписи к фото `photos/captions.csv` и `photos/captions-en.csv`, диктовка `source/dictation/2026-10-02-frisco-additions.md`.
- Рядом лежат два приложения: `docs/briefs/mckinney/8-links-queries-by-page.md` (все запросы со словом McKinney по страницам, 3 и 16 месяцев) и `docs/briefs/mckinney/8-links-details.md` (цитаты про McKinney с других страниц, таблица услуг с цифрами запросов, фото из McKinney).

**Как читать цифры.** «Итог» это строка страницы в `Pages.csv`: клики / показы / место. «Сумма строк» это сумма строк страницы в `page-query`: строк / клики / показы / место (место средневзвешенное по показам). Google прячет редкие запросы, поэтому сумма строк меньше итога.

### Коротко

На сайте нет ни одного поста и ни одного гайда, где вся история случилась в McKinney. Есть один гайд, внутри которого стоит случай из McKinney в три предложения (утечка главной линии в шести футах под землёй, счётчик крутился). Второй случай из McKinney, корни дерева в медной линии от счётчика к дому, стоит сразу на двух страницах: на самой странице McKinney и на странице water lines, почти одними словами. Больше историй с McKinney на сайте нет. В диктовке Дениса есть один готовый случай для страницы McKinney (кран в laundry box, видео 195 и фото 196), он ещё нигде не стоит.

### 1. Посты и гайды, где работа была в McKinney

Целиком из McKinney: **нет ни одного** поста или гайда. Проверены все 64 страницы снимка и все файлы нового сайта. В новом сайте McKinney назван в 27 постах и гайдах; в 26 из них только в перечислении городов («Frisco, Plano, McKinney») без истории, такие в счёт не идут.

С коротким случаем из McKinney внутри: один гайд.

| № | Страница | 3 мес, итог: клики / показы / место | 16 мес, итог | 3 мес, сумма строк: строк / клики / показы / место | 16 мес, сумма строк | Режим правки |
|---|---|---|---|---|---|---|
| 1.1 | `/plumbing-guide/water-leak-yard-tips-2026/` | 0 / 157 / 16.87 | 0 / 311 / 11.88 | 4 / 0 / 37 / 37.16 | 6 / 0 / 40 / 36.73 | обычная очередь (не заморожен, не в группе 2 плана; гайды идут последними) |

Для сравнения сама страница `/plumber-mckinney-tx/`: за 3 месяца итог 0 кликов, 472 показа, место 27.19 (сумма строк: 40 / 0 / 319 / 30.80); за 16 месяцев итог 1 клик, 20,833 показа, место 61.33 (сумма строк: 171 / 0 / 19,500 / 62.26). В `docs/pages-plan.md` McKinney стоит последней в очереди городов (строка 19: 472 показа, место 27.2, 0 кликов).

#### 1.1. Гайд: как проверить утечку главной линии во дворе

- URL: `/plumbing-guide/water-leak-yard-tips-2026/`
- Title: "Water Meter Spinning? Check for a Main Water Line Leak (Plumber Guide)" (одинаково на живом и новом сайте)
- H1: "How to Check for a Main Water Line Leak in Your Yard: A Step-by-Step Guide for North Texas Homeowners"
- Опубликован 27 июня 2026 (снимок), автор Denys Kavaler, 2,621 слово на живом сайте (word_count снимка).
- История одной строкой (раздел про тест счётчиком, Step 2): клиент из McKinney был уверен, что утечки нет, потому что воды нигде не видно, но счётчик крутился; нашли утечку главной линии в шести футах под землёй, на поверхности никаких признаков. Дословно: "I had a McKinney customer who swore he didn’t have a leak because he couldn’t see water anywhere. But the meter kept spinning. We traced it to a main line leak six feet underground with no visible signs at the surface."
- Факты, особые для McKinney: кроме самого города, никаких. Улицы, возраста дома, материала трубы и способа ремонта в тексте нет. В том же гайде есть общая фраза с цифрой: "Many newer subdivisions in Frisco, Plano, and McKinney have high municipal water pressure, sometimes 80 to 100 psi or more." Источник этой цифры в проекте не записан.
- Запросы: с городом ни одного. Главный "main line water leak" 25 показов, место 20.2 (3 мес).
- На страницу McKinney гайд не ссылается. На страницу water lines тоже не ссылается (ссылки в тексте: главная, toilet repair, hose bib, гайд про главный кран, PRV, leak detection, emergency). По правилу 12 гайд, где назван город истории, ссылается на страницу этого города. В том же гайде есть и случай из Plano (это описано в брифе Plano, раздел 1.9).
- Фото: по плану `photos/captions-en.csv` (колонка pages) в этот гайд и на water lines назначено фото 158 «Pulling a new PEX water line under the sidewalk, McKinney». Город фото взят из места съёмки, Денис его не называл. Та ли это работа, что в гайде, неизвестно (вопрос 2).

### 2. Что про McKinney уже сказано на страницах услуг и на других страницах

Это опоры: на странице McKinney их нельзя повторять слово в слово (правило оригинальности), но факты уже стоят на сайте.

**Случай с корнями, стоит дважды.**
- Страница McKinney (живая и новая, раздел "Main Water Line Repair in Older McKinney Homes"): "We handled a job in McKinney recently where a large tree in the yard had grown into the service line and damaged the copper outright. That is not a repair you patch and forget, the damaged section came out and got replaced."
- Water lines (`/water-lines/`, раздел "Tree Roots and the Water Line"): "A [plumber in McKinney](/plumber-mckinney-tx/) sees this one a lot. On one job there a large tree in the front yard had grown into the service line and damaged the copper outright." Дальше: "That section came out and got replaced on a different route." и "Rerouting costs more once and ends it."
- Это один и тот же случай почти одними словами на двух страницах. Фото этой работы в архиве нет (в подписях нет дерева или корней на водяной линии).

**Slab leak repair** (`/slab-leak-repair-frisco-plano-mckinney/`, одобренный текст v3):
- "The oldest copper on our schedule is under the houses a plumber in Plano sees every week, dispatched from our office on Tennyson Parkway, followed by the established streets a [plumber in McKinney](/plumber-mckinney-tx/) works around downtown."
- В карте ключей: запрос "slab leak repair mckinney" принадлежит этой странице, а не странице McKinney. Search Console подтверждает: за 16 месяцев страница slab leak держит его на месте 26.75 (2,806 показов), страница McKinney на месте 62.1 (711 показов).

**Water leak detection** (`/water-leak-detection-frisco-plano/`, одобренный текст v2):
- "A copper water line under the foundation with a pinhole in it is the most common hidden leak in the older parts of Plano and McKinney and in the first Frisco neighborhoods"
- "...and to a [plumber in McKinney](/plumber-mckinney-tx/) working the established streets around downtown."
- "This is why foundation repair companies in Plano, Frisco and McKinney require a hydrostatic test before and after leveling a house."

**Остальные страницы** (цитаты целиком в `8-links-details.md`, часть А): emergency, garbage disposal и главная называют McKinney только как место, куда ездят те же машины, без местных фактов. Что важно для автора страницы:
- Страница expansion tank пишет "Half the homes in Frisco and McKinney keep the water heater in the attic". Источник цифры «половина» в проекте не записан: без слова Дениса не переносить.
- Гайд про счёт за воду пишет, что McKinney и другие города присылают оповещения о расходе воды. Это утверждение про городскую службу, официальной проверки нет: передать разделу 6a. [Найдено при сборке и прочитано критиком 3 октября 2026 на https://www.mckinneytexas.org/2284/Meters-Leaks-Pipes : "Get text and email alerts to identify leaks and high water usage." и "Opt-in to receive alert notifications of possible leaks". Оповещения есть, но по подписке, не «автоматически».]
- На сайте уже есть вопросы FAQ "Does a slab leak repair need a permit in Plano, McKinney or Frisco?" (slab leak) и "Is it better to hire a local plumber in McKinney or a large national company?" (гайд «plumber near me»). На странице McKinney их не повторять.
- Замороженный гайд про цену водонагревателя пишет "a contractor traveling from Dallas to McKinney ... $50 to $100": Dallas отдельно и цена, не переносить.
- Замороженный гайд про главный кран: в домах последних 10 до 15 лет в Frisco, McKinney, Prosper, Plano второй кран чаще в гараже, коробки в большинстве районов между тротуаром и улицей. Замороженный гайд про кран под раковиной: компрессионные краны "most common type in older homes around McKinney and Frisco".
- На главной в плитках услуг стоят два фото из McKinney (141, бачок с новыми fill и flush valve; 99, Moen с одной ручкой через окно в плитке), город по месту съёмки. В галерее девять фото с подписью McKinney со старого сайта; на страницу McKinney галерея не ссылается.

**Сама страница McKinney сегодня** держит утверждения, источник которых в проекте не записан: "McKinney sends us two calls more than any others" (slab leak и диспоузер); "Most of the failed units we pull out of McKinney kitchens share a story: a builder grade 1/3 or 1/2 HP unit"; раздел "Older McKinney, Newer McKinney" про "the historic center and the older established streets", где "cast iron and copper", и новые районы, где "fill valves quit in year three". Отзыв Ezzy Zhoo на странице: "working with me to satisfy permit requirements for city of mckinney" (отзывы разбирает раздел 5). [Поправка критика брифа, 3 октября 2026: во вставленном файле эти слова приписаны LXD Properties; по `reviews/all-reviews.csv` и краулу это отзыв Ezzy Zhoo, у LXD Properties слов про разрешение и город нет.]

**Материал Дениса, который ещё нигде не стоит:**
- McKinney, кран в laundry box (видео 195, фото 196; `source/dictation/2026-10-02-frisco-additions.md`, раздел "McKinney: the laundry box valve"): пол вздулся и хлюпал, плинтусы вздулись в гостиной и спальне; кто-то уже приезжал и не нашёл; прачечная в середине дома, на латунном кране в laundry box открылся пинхол, вода капала в стену месяцами. Город назван Денисом. Назначен им странице McKinney и странице leak detection (`docs/pages-plan.md`). На фото 196 видны часы на руке.
- Фото из McKinney, которые план подписей уже ставит на страницу McKinney (PRV, outlet box стиральной машины, две ручки на одну, диспоузер Moen 3/4 HP после долгой течи, бачок унитаза): список и источник города в `8-links-details.md`, часть В. Город у них по месту съёмки, не со слов Дениса.

### 3. На что должна ссылаться страница McKinney и с какими якорями

#### 3.1. Главная: одна ссылка

Правило 6: один раз, в последнем абзаце вступления, якорь ровно "plumber near me", фраза общая и не как на других страницах. Сейчас ссылка стоит во втором абзаце из трёх: "If you searched for a [plumber near me](/) and are tired of four hour windows and vague estimates, that is the whole difference." Начало "If you searched for a plumber near me" стоит ещё на Carrollton, Lewisville, Prosper и The Colony, а у The Colony и конец почти тот же ("that is the whole difference in one sentence"). Фразу переписать заново и поставить в последний абзац вступления.

#### 3.2. Все 13 услуг

Город ссылается на каждую услугу. Список и адреса из `site/src/design/design.json` (порядок меню). Сейчас на странице McKinney есть ссылки на 11 услуг из 13: **нет hose bib repair и нет expansion tank replacement**.

| № | Услуга (имя в меню) | URL | Якорь сейчас | Предлагаемый якорь | Где встаёт по смыслу |
|---|---|---|---|---|---|
| 1 | Emergency plumbing | `/emergency-plumbing-services/` | "emergency plumbing" | "emergency plumbing" | блок «если течёт прямо сейчас» |
| 2 | Slab leak repair | `/slab-leak-repair-frisco-plano-mckinney/` | "slab leak repair" (два раза) | "slab leak repair", без города | короткий блок про slab leaks |
| 3 | Water leak detection | `/water-leak-detection-frisco-plano/` | "leak detection" | "water leak detection" | случай с laundry box (195, 196) |
| 4 | Sewer line repair and camera inspection | `/drain-services/` | "main line service" | "sewer line repair and camera inspection" | старые районы: чугун, корни |
| 5 | Drain cleaning | `/clogged-drain-cleaning-frisco-plano/` | "drain cleaning" | "drain cleaning" | засоры |
| 6 | Water heater repair and replacement | `/water-heaters/` | "water heater repair" | "water heater repair and replacement" | раздел про водонагреватели |
| 7 | Expansion tank replacement | `/water-heater-repair-frisco-mckinney/` | ссылки нет | "expansion tank replacement" | фраза про расширительный бак в том же разделе |
| 8 | Faucet and shower valve repair | `/fixture-installation-repair/` | "shower valve repair" | "faucet and shower valve repair" | две ручки на одну (фото 98, 99) |
| 9 | Hose bib repair | `/hose-bib-repair-frisco-plano/` | ссылки нет | "hose bib repair" | уличный кран, мороз |
| 10 | Garbage disposal repair | `/garbage-disposal-repair-frisco-plano/` | "garbage disposal repair" (два раза) | "garbage disposal repair" | раздел про диспоузеры |
| 11 | Water line repair | `/water-lines/` | "main water line repair", "water line repair" | "water line repair" | линия от счётчика к дому, корни |
| 12 | Toilet repair | `/toilet-repair-frisco-plano/` | "toilet repair" | "toilet repair" | бачок, fill и flush valve (фото 139, 141) |
| 13 | PRV replacement | `/prv-replacement-frisco-plano/` | "PRV replacement" | "PRV replacement" | давление, PRV (фото 7, 51) |

Цифры Search Console по каждой услуге (запросы «услуга + mckinney», на какой странице и на каком месте) в `8-links-details.md`, часть Б. Коротко: запросы «услуга + mckinney» идут на страницы услуг (disposal 1,654 показа на месте 28.29, slab leak 2,806 на месте 26.75, expansion tank "expansion tanks repair mckinney" 881 на месте 25.31), а по faucet, toilet, water line и low water pressure больше показов у самой страницы McKinney, на местах от 34 до 63.

Оговорки:
- Старые якоря стоят в списке "Our Plumbing Services in McKinney". В запросах страницы McKinney нет ни одного, который держится именно за "main line service", "shower valve repair" или "main water line repair", поэтому замена на имя услуги ничего не теряет. Окончательная сверка за таблицей запросов страницы (раздел 2 брифа).
- Карта ключей: странице McKinney нельзя бороться за "slab leak repair mckinney". Сейчас на странице стоит H2 "Slab Leak Repair in McKinney" и H2 "Main Water Line Repair in Older McKinney Homes", то есть услуга плюс город. По правилам города объяснения живут на страницах услуг. Как поступить с этими заголовками, решает автор страницы вместе с разделом 2 (что ранжируется, остаётся); ссылки при этом с якорем без города.
- Две фразы рядом со ссылками обещают цены: "Our [garbage disposal repair] page has the full pricing." и "Our [main water line repair] page covers how we locate it and what the options cost." На тех страницах стоят цены, которых нет в правилах ($229 и $400-500 на диспоузере, "three to six thousand dollars" на water lines). На странице McKinney такие фразы не писать; цены на тех страницах это вопрос их очереди.
- "hydrojet sewer plumber mckinney tx" даёт странице McKinney 243 показа за 16 месяцев. Hydro jetting мы не предлагаем: этот запрос не ловить.

#### 3.3. Истории и гайды: что ставить

Сегодня страница McKinney ссылается только на один гайд (главный кран). Историй из McKinney, кроме случая в гайде про двор, на сайте нет, поэтому список короткий.

| Важность | Страница | Предлагаемый якорь | Где встаёт | Оговорка |
|---|---|---|---|---|
| А | `/plumbing-guide/how-to-shut-off-main-water-valve-texas/` | оставить как есть, "shut-off guide", или "where the main shut-off valve is" | блок «если течёт прямо сейчас» | заморожен, ссылаться можно; в новом файле после ссылки нет пробела: "...texas/)covers" |
| А | `/plumbing-guide/water-leak-yard-tips-2026/` | "a meter that kept spinning with no water in sight" | раздел про линию от счётчика к дому | единственная история из McKinney в постах и гайдах; в брифе Plano для этого гайда предложен якорь "how to check for a main water line leak in the yard", здесь нужен другой |
| Б | `/plumbing-guide/automatic-water-shut-off-valve-install-north-texas/` | "an automatic water shut-off valve" | после случая с laundry box | гайд в группе 2 плана (28 кликов за 3 мес), сам гайд не трогаем; ставить, только если Денис захочет совет про автоматический клапан рядом с этим случаем |
| В | `/plumbing-guide/water-pressure-dropping-tips-2026/` | "why water pressure drops" | пункт про PRV | по желанию; страница McKinney держит "low water pressure plumber mckinney" (580 показов) |
| В | `/plumbing-guide/water-heater-replacement-cost-2026/` | "water heater replacement cost" | раздел про водонагреватели | заморожен; только ссылка, цены, Dallas и tankless из него не переносить |

А ставить в любом случае, Б если в тексте есть абзац на эту тему, В по желанию.

#### 3.4. На что страница McKinney не ссылается

- На другие города и на посты, где в заголовке или адресе стоит другой город (пост про трубу под тротуаром Plano, пост про две утечки Plano, посты Frisco, `/top-emergency-plumber-calls-frisco/`). Правило 7 запрещает ссылку на страницу города и упоминание соседа; пост с чужим городом в заголовке тот же сосед в тексте. Пост про смеситель с трёх ручек на одну сделан в Plano (так написано в самом посте), поэтому для темы «две ручки на одну» лучше фото 98 и 99 из McKinney и ссылка на страницу услуги.
- Сегодня страница McKinney не называет и не ссылается ни на один соседний город, это правильно.
- Ссылки на города в шапке, в меню и в подвале стоят на каждой странице, это навигация, правило 7 про текст.

#### 3.5. Одна внешняя ссылка на официальный источник

По образцу Frisco. Сейчас на странице McKinney (и на живой, и на новой) внешней ссылки на город нет совсем. Нужна конкретная официальная страница города McKinney про регистрацию подрядчиков или разрешения; адрес выбирает раздел 6a. [Выбор при сборке, «Коротко» п. 11: https://www.mckinneytexas.org/257/Contractor-Registration (как на Frisco) или https://www.mckinneytexas.org/2284/Meters-Leaks-Pipes ; обе страницы ответили 200 на проверке критика 3 октября 2026.]

### 4. Кто уже ссылается на `/plumber-mckinney-tx/` на новом сайте

В файлах страниц 11 ссылок из 10 файлов (страница expansion tank ссылается дважды).

| Откуда | Якорь |
|---|---|
| `/slab-leak-repair-frisco-plano-mckinney/` | "plumber in McKinney" |
| `/water-leak-detection-frisco-plano/` | "plumber in McKinney" |
| `/water-lines/` | "plumber in McKinney" |
| `/emergency-plumbing-services/` | "plumber in McKinney" |
| `/garbage-disposal-repair-frisco-plano/` | "McKinney" |
| `/water-heater-repair-frisco-mckinney/` | "McKinney" (в тексте) и "McKinney" (в списке городов) |
| `/contact/` | "McKinney, TX" (список городов) |
| `/plumbing-guide/why-your-toilet-keeps-backing-up/` | "plumber in McKinney" |
| `/plumbing-guide/how-to-shut-off-main-water-valve-texas/` | "plumber in McKinney," (запятая внутри якоря; гайд заморожен, не правим) |
| `/plumbing-guide/water-leak-after-bathroom-remodel-frisco-tx/` | "plumber in McKinney" |

Якоря по числу: "plumber in McKinney" 6, "McKinney" 3, "plumber in McKinney," 1, "McKinney, TX" 1. Ни одного поста среди ссылающихся нет. Для сравнения: на страницу Plano в файлах 25 ссылок из 24 файлов (бриф Plano, раздел 4).

Кроме файлов страниц:
- Шаблоны на каждой странице: "McKinney" в выпадающем списке Areas в шапке, в панели Menu (раздел Cities, McKinney третий) и в подвале (Areas).
- Главная, три ссылки по решению Дениса: якорь "plumber in McKinney" в тексте «Where We Work», точка на карте (aria-label "Plumber in McKinney") и ряд городов под картой.
- Три старых адреса вложений ведут на страницу McKinney редиректом 301 (`site/src/data/redirects.csv`): `/plumber-mckinney-tx/screenshot-26/`, `/plumber-mckinney-tx/photo_2025-05-15_20-41-45/`, `/plumber-mckinney-tx/5-1/`.
- Офиса и карточки Google в McKinney нет, так что внешнего входа с карточки, как у Frisco и Plano, у страницы нет.

**Чего не хватает** (правки других страниц, делаются в их очередь, не сейчас):
- Семь страниц услуг из 13 не ссылаются на страницу McKinney в тексте, хотя услуга ссылается на все десять городов: `/water-heaters/`, `/drain-services/`, `/clogged-drain-cleaning-frisco-plano/`, `/toilet-repair-frisco-plano/`, `/hose-bib-repair-frisco-plano/` (McKinney там просто строка списка без ссылки), `/fixture-installation-repair/` (McKinney в H2 без ссылки), `/prv-replacement-frisco-plano/`.
- Гайд про двор с историей из McKinney не ссылается на страницу McKinney.
- Галерея с девятью подписями "McKinney" не ссылается на страницу McKinney.
- Search Console показывает, что Google видит страницу McKinney слабой даже по её главному запросу: за 3 месяца "plumber mckinney tx" страница Frisco показана 98 раз на месте 17.93, страница Plano 75 раз на месте 17.29, а страница McKinney 2 раза на месте 59. "emergency plumber mckinney" страница Frisco держит на месте 1.62 (21 показ). Ссылок со словами "plumber in McKinney" на сайте мало (6), это одна из причин, которую можно исправить ссылками с услуг.

### 5. Расхождения с правилами, которые всплыли по дороге

Здесь ничего не исправлено, это список для того, кто будет писать страницу и править другие страницы.

1. Случай с корнями дерева стоит на странице McKinney и на странице water lines почти одними словами ("a large tree in the yard had grown into the service line and damaged the copper outright"). Правило: текст не повторяет другую страницу сайта.
2. На water lines в том же разделе: "replaced on a different route", "Rerouting costs more once and ends it.", в FAQ "rerouting usually makes more sense". Слово reroute по правилам не звучит как вариант работы. На страницу McKinney не переносить.
3. На странице McKinney 11 услуг из 13: нет hose bib repair и expansion tank replacement.
4. Ссылка на главную стоит во втором абзаце вступления, а не в последнем; начало фразы общее с четырьмя городами, конец почти как у The Colony.
5. После ссылки на гайд про главный кран нет пробела ("[shut-off guide](...)covers").
6. Фразы со ссылками обещают «full pricing» и «what the options cost», а на тех страницах цены вне правил ($229, $400-500, три до шести тысяч долларов).
7. Две H2 с услугой и городом ("Slab Leak Repair in McKinney", "Main Water Line Repair in Older McKinney Homes") при записи в карте ключей, что "slab leak repair mckinney" принадлежит странице slab leak.
8. Утверждение «половина водонагревателей в Frisco и McKinney стоит на чердаке» (страница expansion tank) и «города, включая McKinney, присылают оповещения о расходе воды» (гайд про счёт) не имеют источника в проекте. [Про оповещения McKinney см. раздел 2 выше: есть, по подписке клиента.]
9. Подписи фото 180, 190 и 191 в `photos/captions-en.csv` и `captions.csv` дают город McKinney, а в заметках к ним и в `docs/pages-plan.md` записано «по месту съёмки Prosper» (180) и «по месту съёмки Allen» (190, 191), город Денис не назвал. Фото 190 план ставит на страницу McKinney. До слова Дениса город этих клипов не считать известным. [Решено правилом CLAUDE.md от 3 октября 2026: город фото по черте города, кадр в черте другого обслуживаемого города берёт этот город. `photos/captions-en.csv` (10:23) пишет у 180, 190 и 191 McKinney; записи плана о Prosper и Allen сделаны старым способом. Спрашивать Дениса только если он помнит город (часть 10, вопрос 9).]
10. Запрос "hydrojet sewer plumber mckinney tx" (243 показа за 16 месяцев) приходит на страницу McKinney; hydro jetting мы не делаем, этот запрос не ловить.

### 6. Вопросы к Денису (то, что знает только он)

1. Работа с деревом, которое вросло в медную линию от счётчика к дому: это было в McKinney? Что сделали: заменили участок в той же траншее или проложили линию другим путём? Есть фото? Сейчас этот случай стоит и на странице McKinney, и на странице water lines; где он остаётся, а где нужен другой?
2. Гайд про утечку во дворе: случай «клиент из McKinney, воды не видно, счётчик крутился, утечка главной линии в шести футах под землёй» был на самом деле? Можно рассказать его на странице McKinney коротко со ссылкой на гайд? Фото 158 (тянем новую PEX под тротуаром, по месту съёмки McKinney) с этой работы или с другой?
3. На странице McKinney написано, что больше всего звонков из McKinney про slab leak и про диспоузеры, и что в новых домах стоят диспоузеры на 1/3 или 1/2 л.с. Это так? Какие вызовы в McKinney самые частые сейчас?
4. Где в McKinney старая медь под плитой и чугун: только вокруг исторического центра (downtown), как написано на страницах slab leak и leak detection, или ещё где-то? Можно назвать улицы или районы?
5. Девять фото в галерее подписаны McKinney (PRV и главный кран, два газовых водонагревателя с баком в гараже, водонагреватель с баком на чердаке, замер давления на уличном кране, ручка смыва коммерческого унитаза, корни из линии унитаза, ванна и Milwaukee M18, диспоузер Moen). Это работы в McKinney? Их можно ставить на страницу McKinney?
6. Клипы 190 и 191 (унитаз, забитый бумагой, шестифутовый auger) и 180 (дивертер на изливе): в каком городе были эти работы? [По черте города это McKinney (правило 3 октября); вопрос только на случай, если Денис помнит другой город.]

## 9. Чем McKinney отличается от Frisco и Plano

Только то, что подтверждено данными Search Console из части 2 или официальной страницей из части 6. У каждого пункта назван источник. Цифры Frisco и Plano взяты из тех же выгрузок Search Console (`source/gsc/performance-3m/Pages.csv` и `performance-16m/Pages.csv`), из тех же таблиц Census (часть 6) и из брифа Plano (`docs/plano-brief-2026-10-03.md`, часть 6, факты там прошли перепроверку). По Frisco официальных фактов города в этих файлах нет, поэтому в пунктах 3 и 4 сравнение только с Plano. Это для автора: на самой странице McKinney соседние города не называются.

1. **Страница без кликов, почти без показов и без своей карточки Google.** За 3 месяца McKinney 0 кликов, 472 показа, место 27.19; Frisco 42 клика, 44,080 показов, место 15.2; Plano 98 кликов, 56,197 показов, место 6.77. За 16 месяцев McKinney 1 клик и 20,833 показа, Frisco 110 и 128,850, Plano 103 и 108,268. У Frisco и Plano есть карточки офисов, и по главному ключу McKinney «plumber mckinney tx» за 3 месяца выше самой McKinney (2 показа, место 59.0) стоят страницы Frisco (98, место 17.9) и Plano (75, место 17.3). У McKinney 96 процентов известных показов за 16 месяцев пришли по запросам со словом mckinney; у Plano 62 процента идут по запросам без слова plano, скорее всего через карточку офиса (бриф Plano, «Коротко», пункт 2). Источник: Pages.csv, часть 2, разделы 1, 6 и «Главное коротко». Для текста: «plumber in McKinney» и варианты в тексте и в части H2 здесь важнее, чем на страницах офисов, а вести на страницу должны ссылки с услуг (сейчас якорь "plumber in McKinney" стоит на сайте 6 раз, часть 8, раздел 4).
2. **Есть настоящий старый центр, при общем жилье как во Frisco.** Медианный год постройки жилья: McKinney 2007 (±1), Frisco 2009 (±1), Plano 1993 (±2). Построено до 1980 года: McKinney 7.8%, Frisco 1.5%, Plano 18.4%. Жилья 1939 года и раньше: McKinney около 1,128 (±356), больше, чем в Plano (292 ±119) и во Frisco (47 ±61) вместе. Старое жильё McKinney стоит в одном месте: индекс 75069, к востоку от US 75, вокруг площади (там до 1980 года построено 26.1% жилья участка; в 75070, 75071 и 75072 от 2.3% до 5.1%). Источник: U.S. Census Bureau, ACS 2020-2024, таблицы B25034 и B25035, перепись 2020 года по кварталам (часть 6, строки age-mckinney, age-frisco, age-plano, share-mckinney, share-frisco-plano, share-75069, old-1 таблицы проверки 6.4; оговорка cmp-d2). Для текста: слова живой страницы про "the historic center and the older established streets" данными подтверждаются; что там в трубах (чугун, медь, оцинковка), Census не знает, это только слова Дениса.
3. **Кран города у счётчика хозяину трогать нельзя.** McKinney: кран между счётчиком и улицей только для работников города, закон города (110-119) запрещает перекрывать воду на кране под контролем города; у хозяина свой кран (в подполье у ввода, в гараже у ввода, у водонагревателя или стиральной машины, снаружи у фундамента), в аварии звонят в Public Works, отдел отвечает круглые сутки (city-d4 и city-h6, подтверждено; https://www.mckinneytexas.org/2284/Meters-Leaks-Pipes ). Plano наоборот: закон разрешает хозяину открыть ящик счётчика, чтобы закрыть или открыть воду на кране города (бриф Plano, city-d4, раздел 21-17(1), подтверждено). Для текста: на странице McKinney не советовать «закройте воду на счётчике»; правильно: свой главный кран дома, а если его нет, аварийная линия Public Works города, без номера.
4. **Свои условия пересчёта счёта после течи.** McKinney: "as a courtesy", расход в 3 раза выше того же периода прошлого года, счёт больше $150.00, раз в 12 месяцев, бланк с подтверждением в течение 60 дней, полив не считается, счёт платится полностью до кредита; бланк спрашивает дату ремонта, описание, кто чинил, имя подрядчика и чек (city-e1 до city-e3, подтверждено; https://www.mckinneytexas.org/2284/Meters-Leaks-Pipes и https://form.jotform.com/230534509935055 ). Plano: "water credit as a courtesy", больше 30,000 галлонов сверх среднего на одном счёте, заявка в течение 90 дней после ремонта (бриф Plano, city-e1 и city-e2, подтверждено). Для текста: наш счёт, где описана работа, подходит к бланку города; цифры и условия города на страницу только со слова Дениса.
5. **Кодекс 2024 года введён позже.** McKinney принял 2024 International Plumbing Code и 2024 International Residential Code с поправками NCTCOG (март 2025) с 1 октября 2025 (city-g1 и city-g2, подтверждено; https://www.mckinneytexas.org/243/Building-Inspections ); номер закона неизвестен, Municode не обновлён с декабря 2022. Plano ввёл кодексы 2024 года с 1 августа 2025 (бриф Plano, city-g1). Для текста: разница небольшая; номера разделов кодекса со страницы Plano сюда не переносить, а что смотрит инспектор McKinney на водонагревателе, брать из пакета для строителей, действующего с 1 октября 2025 (city-b4 в поправленном виде).

## 10. Вопросы к Денису и нужные фото

Только то, что знает он один. Собрано из вопросов разделов (части 1, 2, 3, 5, 6 и 8) и из частей 4 и 7, без повторов.

### 10.1. Вопросы

1. **Офис.** Из какого офиса обслуживается McKinney, Frisco или Plano? Можно ли на странице назвать офис по имени (например "served from our Plano office", без ссылки, без минут), или писать без названия города? По правилу 7 страница города соседей не называет. Сейчас в схеме живой страницы адрес и телефон Frisco, на фургоне главного фото телефон Plano, а в выгрузке Google McKinney стоит в зоне обслуживания карточки Plano (у карточки Frisco зона пустая).
2. **Title и самые частые вызовы.** Живая страница открывается словами, что чаще всего McKinney звонит про slab leak и про измельчитель, а в новых домах стоят измельчители от застройщика на 1/3 или 1/2 HP. Это так? Какие вызовы в McKinney самые частые сейчас? Вторую половину title "Slab Leak & Garbage Disposal Repair" оставляем или меняем? По карте ключей slab leak и garbage disposal с McKinney отданы страницам услуг, и по показам они сильнее (в 4 и в 15 раз); кликов по этим словам у страницы McKinney не было. Если slab leaks в McKinney редкие, как во Frisco, этот блок не может открывать страницу.
3. **Дерево в медной линии.** На странице написано, что в McKinney большое дерево вросло в медную линию от счётчика к дому. Это была работа в McKinney? Участок заменили в той же траншее или линию проложили по-другому? Есть фото? Сейчас случай почти одними словами стоит и на странице McKinney, и на /water-lines/ (там со словами про reroute); на какой странице он остаётся? Раздел с ним один держит 1,416 показов за 16 месяцев.
4. **Счётчик крутился, течь в шести футах под землёй.** Случай из гида про утечку во дворе ("I had a McKinney customer...") был на самом деле? Можно рассказать его на странице McKinney коротко со ссылкой на гид? Фото 158 (новая PEX под тротуаром, по месту съёмки McKinney) с этой работы или с другой?
5. **Давление и PRV.** Что вы видите на манометре в домах McKinney, где там стоит PRV и как часто бывает вызов на низкое или высокое давление? «low water pressure plumber mckinney» дал 580 показов за 16 месяцев, а слова low на странице нет. Что было на работах с фото 7 (29 сентября 2026) и 51 (PRV в клумбе, 17 сентября 2026), и есть ли кадр старого PRV? Берёте ли в McKinney разрешение на замену PRV (город про PRV нигде не пишет)?
6. **Старые и новые дома.** Что вы находите в старых домах у исторического центра (чугун, медь, оцинковка, старые краны) и где это: восток за US 75 вокруг площади (индекс 75069) или ещё где-то? Можно ли назвать улицы или районы? Что ломается в новых районах (на странице "fill valves quit in year three")? Город пишет про плохую медь 1997 до 2011 годов на своей части линии: видите ли вы то же на частной части от счётчика до дома?
7. **Разрешения и инспектор в McKinney.** Какой тип разрешения в портале CSS вы берёте на линию от счётчика до дома, на точечный ремонт канализации во дворе, на ремонт течи под плитой и на замену обратного клапана на поливе? Что смотрит инспектор McKinney при замене водонагревателя (пакет для строителей называет трубку T&P не ниже 6 дюймов, расширительный бак и поддон со сливом)? Бывают ли там водонагреватели на чердаке? При ремонте фундамента инженер пишет в письме, нужен ли тест воды, канализации и газа: делаете ли вы тесты по этому письму?
8. **Отзывы.** Ezzy Zhoo единственный в архиве называет McKinney (черновая сантехника при ремонте ванной, разрешение города), но в нём дважды ваше имя, "rerouting of vents and water lines" и "gas line": ставим как исключение или нет? Делаем ли мы черновую сантехнику при ремонте ванной и газовые линии? Где были дома LXD Properties и дом Victoria Nwanegbo, и та же ли это Victoria N. с Thumbtack (ноябрь 2022)? Были ли в McKinney работы кого-то из кандидатов части 5 (Rangsan L., Javeed N., alex p, Phillip Potter и другие)? Отзывы со словами "plumber near me" для McKinney по-прежнему не берём, как на Frisco? Есть ли отзыв клиента из McKinney, которого ещё нет в архиве, особенно про slab leak, главную линию или давление?
9. **Город и содержание кадров.** Главное фото живой страницы (фургон на улице у кирпичных домов): где снято, что за номер "M-38532" на крыле (на сайте M-44816), убираем ли его? Можно ли пока ставить фургон у офиса Frisco (фото 2 или 4), как вы разрешили для Celina и Lewisville? Что на клипах 13 и 14 (вы не помнили)? Девять старых фото галереи с McKinney в подписи (PRV и главный кран, водонагреватели с баком в гараже и на чердаке, замер давления на уличном кране, ручка смыва коммерческого унитаза, корни из линии унитаза, ванна, диспоузер Moen): это работы в McKinney, можно ставить? Клипы 180, 190 и 191 по черте города в McKinney, а в плане работ записаны Prosper и Allen: если помните город, скажите.
10. **Индексы и дома вне города.** Показывать ли на странице почтовые индексы (по данным их четыре: 75069, 75070, 75071, 75072)? Под 75071 тысячи домов вне черты города (ETJ, на конверте "McKinney, TX"): считать ли такие вызовы вызовами в McKinney, как Paloma Creek для Little Elm? Слова о разрешении и инспекции города McKinney к ним в любом случае не относятся.
11. **Срочные вызовы и «same day».** Записать ли «emergency plumber mckinney» ключом страницы McKinney, как у Little Elm, Prosper и The Colony (сейчас эти запросы держит главная: 6,744 показа на месте 48.7 за 16 месяцев)? Можно ли на странице города писать "same day" своими словами, как в описании живой страницы ("same-day service"), или только как на главной?
12. **Мелкие факты страницы.** Это ваши слова, и они верны: размеры измельчителей (3/4 HP для семьи из трёх или четырёх, 1 HP для тех, кто много готовит, 1/2 HP для кухни, где почти не готовят) и совет гонять измельчитель каждый день или два с холодной водой; "the common sizes are on the truck" про водонагреватели? Ставить ли на страницу условия пересчёта счёта городом после течи (без телефонов) и цифру жёсткости воды NTMWD, и что вы видите по накипи в McKinney? Вопрос FAQ "How much does a plumber cost in McKinney, TX?" слово в слово совпадает с вопросом конкурента JMP: задаём его по-другому, например про $49 за будний вызов, согласны?

Закрыто раньше словом Дениса, не спрашивать снова: регистрация. 3 октября 2026 Денис сказал, что компания зарегистрирована во всех городах, где работает (CLAUDE.md); списки подрядчиков города не проверяются.

### 10.2. Какие фото просить

Подробно в части 4.3. Коротко, по порядку важности:

1. Настоящее фото с работы в McKinney или фургон FPP на улице в черте города (вертикальный кадр, без номеров домов).
2. Манометр на уличном кране дома в McKinney с цифрой давления; для работ с фото 7 и 51 старый PRV до замены.
3. Ящик счётчика и кран хозяина на участке; если работа с деревом была в McKinney, яма, повреждённая медь и новый участок.
4. Дом у исторического центра: чугунная канализация или старая медь, экран камеры с корнями в главной линии.
5. Замена водонагревателя в McKinney, «до» и «после»: трубка T&P, поддон со сливом, расширительный бак.
6. Работа laundry box (195, 196): кадр после ремонта, если он есть.
7. Измельчитель с фото 103: старый текущий агрегат до замены.
8. Обратный клапан на поливе, заменённый в McKinney (только замена).
