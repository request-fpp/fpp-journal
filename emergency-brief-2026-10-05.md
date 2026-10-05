# Бриф страницы emergency plumbing (5 октября 2026)

Страница: /emergency-plumbing-services/. Следующая по очереди по решению Дениса от 5 октября 2026: emergency наша главная услуга. Бриф собран по блоку чата от 5 октября, вечер, в том же виде, что брифы городов. Основа: docs/service-emergency-2026-10-03.md (живая страница, Search Console). Добавлены конкуренты, темы, которых у нас нет, указатель материала Дениса с номерами файлов, кандидаты в отзывы и вопросы FAQ, которых нет ни на одной странице сайта. Вопросов к Денису в брифе нет: их задаёт чат, один раз. Что всплыло при сравнении с конкурентами и из материала, записано в конце, в части «Для чата».

Пять частей написали пять помощников Claude Code по файлам проекта и по страницам конкурентов, каждый свою; что они не смогли проверить, стоит в части «Сомнения помощников».

## Коротко

- Страница на тестовом сайте стоит со старым текстом и точечными правками. С 5 октября на её первом экране клип 253 (Plano, потолок, отвалившийся от пинхола), кран в блоке «Close the main shut-off valve» поворачивается нажатием, старое фото фургона снято со страницы и с картинки для соцсетей. Текст, title, H1 и H2 не тронуты.
- Что нельзя потерять: в title и H1 Emergency Plumber, Frisco, Plano, 24/7 и McKinney; в H2 24 Hour Plumber, Emergency Plumbing и After Hours; фраза «emergency plumbing services» должна вернуться на страницу. Запросы emergency у главной не трогаем: передача этой странице отдельный шаг после переезда. Подробно в части 8.
- По запросам с городом первые места у страниц городов и главных страниц конкурентов, а не у их срочных страниц; то же у нас: главная выше срочной. Ни у одного из десяти конкурентов нет фото или видео с настоящей работы на срочной странице; пятеро называют время приезда цифрой, чего мы не делаем никогда. Подробно в части 3.
- Материал Дениса для этой страницы: главный кейс с потолком в Plano (253 до 257, первый экран показывает его, история идёт в текст), вечерний вызов с гвоздём от плинтуса во Frisco (297 до 300), манифолд из push-fit фитингов, который затопил дом (295), прорывы в мороз (275 до 279), гвоздь в гардеробе (280), главная линия под дорожкой (274) и другие; что уже рассказано на главной, Frisco и Plano, здесь только одной фразой со ссылкой. Подробно в части 4.
- Текст пишет чат после диктовки Дениса и кладёт в source/emergency-text-v1.md. Claude Code сверяет его с девятью страницами конкурентов (source/competitors/2026-10-05-emergency/) и со всем сайтом.

## 1. Живая страница

Источники: краул от 30 сентября (`source/crawl/pages/emergency-plumbing-services.json`), заметка `docs/service-emergency-2026-10-03.md` (дальше «заметка»), тестовый сайт (`site/dist/emergency-plumbing-services/index.html`). Ответ 200, canonical на себя, правка в WordPress 30 августа 2026. Одобренного текста в `source/` нет. Карта ключей: главный ключ "emergency plumber", вторичные "emergency plumbing; 24 hour plumber; emergency plumber frisco; emergency plumber plano", нельзя: "plumber near me; plumber + city" (`seo/keyword-map.csv`).

### 1.1. Title, description, H1, H2

| Что | Дословно |
|---|---|
| Title | "Emergency Plumber in Frisco & Plano, TX \| 24/7 Plumbing Service" |
| Description | "Burst pipe? Overflowing toilet? No hot water? Call FPP Plumbing for 24/7 emergency service in Frisco, Plano & McKinney. nights and weekends included." |
| H1 | "Got a Plumbing Emergency? Call Your 24/7 Emergency Plumber in Frisco, Plano & McKinney: Licensed, Fast, and Local" |
| og:title, хлебные крошки, меню | "Emergency Plumbing Services" |

H2 по порядку: "Shut This Off First, Then Call"; "What Actually Counts as an Emergency"; "What a 24 Hour Plumber Costs After Hours"; "A 24 Hour Plumber Who Actually Picks Up"; "What We Fix at Two in the Morning" (девять пунктов, шесть со ссылками); "What These Calls Actually Look Like" (семь историй, первые фразы жирным); "The One Thing All of Them Share"; "Frozen Pipes and Burst Lines After a Hard Freeze"; "24 Hour Plumber Service Area: Frisco, Plano and the Cities Around Them"; "Emergency Plumbing FAQ". Ещё H2 из шаблона: два телефона нижней панели.

Объём: своего текста 2,714 слов от H1 до конца FAQ (заметка, 1.1). Слов "same day" и "weekend" в тексте нет; "weekends" стоит только в description.

### 1.2. FAQ, девять вопросов (тегом H3)

"Do you really answer the phone at night?"; "Do I pay the after hours fee if the repair turns out to be small?"; "Is my problem actually an emergency?"; "What should I do before you arrive?"; "The valve behind my toilet will not stop the water. What do I do?"; "Water is coming through my ceiling. Where is it coming from?"; "My shut-off valve will not turn. What now?"; "How fast can you get here?"; "Do you charge extra on holidays?"

Вопросы 1, 8 и 9 близки к вопросам главной и восьми городских страниц (заметка, 1.2); по правилу 8 вопросов 5 до 7.

### 1.3. Фото

Одно фото под H1, оно же og:image: `/wp-content/uploads/2025/05/fpp-plumber-emergency-truck-frisco-1024x673.png`, alt "FPP Plumbing emergency plumber truck parked in Frisco". Не фото с работы: фургон сбоку у кирпичного дома, на борту "EMERGENCY SERVICE 24/7" и телефон Plano, на крыле "M-38532", а лицензия компании M-44816 (что за номер, в проекте не записано). По заданию этого брифа фото снимается со страницы 5 октября 2026 решением Дениса. На тестовом сайте сегодня оно ещё стоит: первая картинка текста и og:image (`site/src/content/pages/emergency-plumbing-services.md`, строки 7, 34, 40).

### 1.4. Ссылки

- Со страницы 20 внутренних в тексте, внешних нет. "plumber near me" на главную в последнем абзаце вступления (правило 6), все десять "plumber in <город>" в разделе про города (правило 7). Нет ссылок на drain cleaning, leak detection, expansion tank, PRV, garbage disposal, faucet и shower valve.
- На страницу на живом сайте: меню на 62 страницах; в тексте 41 ссылка с 41 страницы, анкор "emergency plumbing" 19 раз, "emergency plumber" 5 (`docs/briefs/services/emergency/emergency-links-in.md`).

### 1.5. Что идёт против CLAUDE.md (дословно, по заметке 1.6)

- Цена: "the bill follows the work, not the estimate" (текст и ответ FAQ 2); "That coordination costs you nothing"; ссылка на гайд цен, где 19 сумм в долларах.
- Мороз: "Outdoor faucets split", против поправки Дениса (уличный кран frost free, ему нужен чехол).
- Газ: "...call the gas utility, then call us."
- H1: слово "Fast" (правило о времени приезда); открывается риторическим вопросом "Got a Plumbing Emergency?".
- Пять историй и ответ FAQ про воду с потолка уходят в темы других страниц без ссылки (правило 9).
- Старая схема: "same night", "North Dallas communities", "Texas Master Plumber License"; на новой этого нет.

### 1.6. Тестовый сайт сегодня

Текст, заголовки и FAQ как на живой. Макет добавил H2 "What is happening right now?" и "Close the main shut-off valve", два отзыва Google. og:title равен title, меню пишет "Emergency plumbing": фразы "emergency plumbing services" в HTML страницы нет ни разу (проверил). Список "What We Fix at Two in the Morning" теперь девять пунктов (в заметке был склеен).

## 2. Search Console

Источник: `source/gsc/page-query-3m.csv` (1 июля до 28 сентября 2026) и `page-query-16m.csv` (31 мая 2025 до 28 сентября 2026). Числа: показы · место, в скобках клики, если они есть.

### 2.1. Итоги

| Период | Google всего | С известным запросом |
|---|---|---|
| 3 месяца | 9,978 · 23.4 (2) | 206 запросов, 8,947 · 24.0 (1) |
| 16 месяцев | 96,031 · 32.5 (7) | 915 запросов, 91,603 · 32.9 (4) |

Клики с известным запросом: только "fpp plumbing" (1 и 3) и "plumber emergency service" (1 за 16 месяцев).

### 2.2. Группы запросов: страница и главная рядом

Мой подсчёт. Каждый запрос в одной группе, по первому признаку: burst, water heater, drain, after hours, same day, 24 hour, потом emergency с городом или без. Итоги страницы сходятся с заметкой; с её таблицей городов (2.6) числа не совпадают, группы другие.

| Группа | Страница 3 мес | Главная 3 мес | Страница 16 мес | Главная 16 мес |
|---|---|---|---|---|
| emergency без города | 1,998 · 18.3 | 7,143 · 11.5 | 12,720 · 20.2 (1) | 52,765 · 13.6 (20) |
| emergency + near me | 246 · 40.9 | 3,445 · 13.1 | 1,778 · 28.8 | 38,887 · 20.8 (2) |
| emergency + Frisco | 1,577 · 34.7 | 2,948 · 10.1 | 17,387 · 38.1 | 26,325 · 10.7 (10) |
| emergency + Plano | 1,252 · 29.7 | 3,242 · 7.9 | 16,379 · 40.5 | 23,161 · 14.0 (9) |
| emergency + McKinney | 0 | 8 · 29.0 | 2,010 · 73.0 | 6,079 · 50.6 |
| emergency + другие 7 городов | 43 · 54.6 | 197 · 39.5 | 1,988 · 63.3 | 9,416 · 33.6 |
| 24 hour, 24/7 | 2,268 · 17.0 | 3,515 · 14.1 | 17,053 · 28.6 | 24,331 · 18.5 (3) |
| same day | 199 · 22.0 | 1,378 · 9.8 | 2,410 · 21.4 | 32,622 · 23.8 |
| after hours, night, weekend, holiday | 11 · 18.9 | 105 · 23.4 | 200 · 53.3 | 581 · 33.1 (1) |
| burst pipe, pipe break | 119 · 27.9 | 18 · 52.4 | 1,686 · 56.3 | 1,771 · 58.4 |
| emergency drain, sewer, toilet | 77 · 8.9 | 133 · 9.4 | 958 · 26.0 | 2,027 · 14.7 |
| emergency water heater | 0 | 1 · 1.0 | 89 · 65.2 | 400 · 37.7 (1) |
| Все срочные | 7,790 · 24.1 | 22,133 · 11.7 | 74,658 · 34.6 (1) | 218,365 · 19.0 (46) |

По emergency + Plano за 3 месяца лучшее место у страницы Plano: 2,103 · 4.6 (та же цифра в карте ключей). По emergency + Frisco страница Frisco 1,971 · 24.7, главная выше.

### 2.3. Главные запросы: кто где стоит

| Запрос | Страница 3 мес | Главная 3 мес | Страница 16 мес | Главная 16 мес |
|---|---|---|---|---|
| emergency plumber | 640 · 19.0 | 3,102 · 9.0 | 4,970 · 19.1 | 24,723 · 10.1 (18) |
| emergency plumbing | 797 · 15.4 | 2,072 · 13.8 | 4,164 · 18.2 | 13,515 · 13.7 |
| emergency plumbers | 385 · 25.6 | 1,421 · 13.3 | 2,172 · 26.5 | 8,489 · 17.5 |
| emergency plumbing services | 114 · 10.1 | 311 · 9.8 | 868 · 16.4 | 2,879 · 12.1 |
| emergency plumber near me | 49 · 17.6 | 1,783 · 13.0 | 457 · 18.0 | 26,574 · 21.2 (1) |
| emergency plumber frisco | 411 · 26.6 | 1,020 · 9.5 | 3,823 · 34.3 | 8,061 · 11.1 (9) |
| emergency plumber plano | 173 · 31.4 | 700 · 6.8 | 4,812 · 33.6 | 6,378 · 12.6 (6) |
| emergency plumber mckinney | нет | 5 · 23.0 | 788 · 65.9 | 1,800 · 44.4 |
| 24 hour plumbers | 716 · 12.4 | 92 · 19.4 | 3,630 · 14.1 | 1,646 · 15.3 |
| 24 hour plumber | 259 · 14.2 | 252 · 14.5 | 515 · 17.1 | 534 · 13.9 |
| 24 7 plumber | 471 · 14.9 | 755 · 9.6 | 3,069 · 14.8 | 3,883 · 9.7 |
| same day plumber | 143 · 17.7 | 859 · 10.0 | 1,039 · 18.2 | 4,944 · 9.8 |
| same day plumber near me | 42 · 32.1 | 489 · 9.1 | 280 · 24.7 | 25,194 · 27.7 |
| after hours plumber | 3 · 18.7 | 3 · 10.7 | 39 · 21.5 | 19 · 12.3 |
| weekend plumber near me | нет | 62 · 26.2 | 1 · 61.0 | 111 · 31.3 |
| emergency drain service | 64 · 8.4 | 71 · 10.4 | 551 · 11.5 | 986 · 11.0 |
| pipe breaks plano | 91 · 27.4 | нет | 646 · 59.3 | нет |
| burst pipe plano | нет | нет | 122 · 28.8 | 23 · 45.1 |
| emergency water heater repair plano tx | нет | нет | 30 · 58.7 | 186 · 37.2 |

"emergency plumber" за 3 месяца у страниц городов: Frisco 1,887 · 3.4, Plano 1,774 · 2.3 (по заметке это, похоже, карточки офисов).

Где страница выше главной (от 40 показов, мой подсчёт): за 3 месяца "24 hour plumbers", "24 hour plumber", "emergency drain service", "pipe breaks plano", "24/7 plumber near me" (50 · 27.6 против 345 · 38.6); за 16 месяцев ещё "24 7 plumber near me", "emergency plumber near me", "emergency plumbing near me", "same day plumber near me", "burst pipe plano" и мелкие запросы с McKinney, Allen, Little Elm и pipe break, где страница ниже 40 места. По остальным большим срочным запросам главная выше.

### 2.4. Что держат заголовки (заметка, 2.3; 16 месяцев)

Title держит 130 запросов и 60,397 показов, H1 135 и 60,459. H2 про города 61 запрос и 20,562 показа (вместе с plumber + Frisco), два других H2 с "24 Hour Plumber" около 7,900 каждый, H2 "Emergency Plumbing FAQ" 4,251. Остальные шесть H2 и девять вопросов FAQ не держат ни одного запроса. Подробно по каждому заголовку: раздел 8.

## 3. Конкуренты по запросам emergency plumber

Дата: 5 октября 2026. Проект только читался. Выдача: Semrush (обычная выдача Google, база "us", 30 мест, без привязки к месту) и веб-поиск (не Google, без города). Выдачи с точкой во Frisco или Plano и карты нет. Девять страниц скачаны и разобраны скриптом; DNA закрыта Cloudflare, прочитана инструментом, цифры примерные. Тексты в проект не записаны. Цитирую только title, заголовки и вопросы FAQ; тире в цитатах заменены дефисом.

### 3.1. Что показала выдача

| Запрос | Первые три (Semrush) | Где FPP | Срочные страницы местных компаний |
|---|---|---|---|
| emergency plumber frisco tx | Berkeys, Roto-Rooter, Baker Brothers (города) | главная 4, наш Instagram 9 | 1-800-Plumber 12, Air Repair Pros 20, Jennings 21, GPS 28 |
| emergency plumber plano tx | Roto-Rooter (город), Yelp, Berkeys (город) | главная 6 | DNA 8 и 10, Jennings 17, GO 19 |
| 24 hour plumber frisco | Roto-Rooter, Berkeys, Baker Brothers (города) | главная 7 | 1-800-Plumber 4 и 10, Air Repair Pros 15, Jennings 18, Mr. Rooter 21, TAB 25 |
| 24 hour plumber plano | Yelp, Berkeys, Roto-Rooter | срочная 25 | DNA 4, GO 18 и 21, Jennings 27 |
| emergency plumbing services frisco plano | данных нет | веб-поиск: Instagram 1, срочная 6, главная 8 | Berkeys Frisco (веб-поиск, 2) |

Без города. Веб-поиск по "emergency plumber" и "emergency plumbing services" дал компании других штатов (Atlanta, Buffalo, San Antonio, Baltimore, Baton Rouge). Semrush по "emergency plumber": 1 Roto-Rooter, 2 Baker Brothers (общая срочная страница DFW, единственная из Техаса); по "emergency plumbing services": Roto-Rooter, Reno, Home Depot. Что видит человек во Frisco, ни один источник не показывает.

Вывод: по запросам с городом первые три места у страниц города и главных. Лучшая срочная, DNA, на 4 месте в одном запросе. У нас Search Console показывает то же: главная выше срочной.

### 3.2. Как выбраны десять страниц

Срочные страницы местных компаний из обоих источников и одна сеть (Roto-Rooter) со своей страницей Plano. Офис по странице.

Пропущено: каталоги и соцсети (Yelp, Angi, Thumbtack, Facebook, в том числе "Frisco Emergency Plumbers" неизвестного владельца, serviceagent.ai, Reddit); сети без своего текста (1-800-Plumber +Air, Mr. Rooter); сайты одного города, похожие на сбор звонков (planoplumbingemergency.com, plumbingemergencyfrisco.com, firstcallfriscoplumbing.com; вывод); главные и страницы городов (Lex's, Trident, Milestone, Crown, Thorough). Запас: Triple Crown Plumbing (Plano, тот же дом, что DNA; 4 H2, без FAQ и советов) и James Armstrong Plumbing (страница Plano, офис в Mesquite, места 26 и 29; одна называет ночную плату за выезд цифрой и до выезда).

### 3.3. Сводка по десяти

"Слов": основной текст от H1 до конца FAQ, примерно.

| № | Слов | Приезд в своём тексте | Цены | Плата за вызов | Ночь и выходные | FAQ | Фото, видео с работ |
|---|---|---|---|---|---|---|---|
| 1 Berkeys | 1 900 | 90 минут в своей истории | купоны, цены в баннерах | нет | сверхурочных доплат нет | нет | нет |
| 2 Baker | 2 000 | от одного до трёх часов (H2 и FAQ) | баннеры | нет; "Free Estimates" | цены одни днём и ночью | 6 | нет |
| 3 Jennings | 1 000 | часто в пределах часа | купоны | "trip charge" без цифры | будни 8 до 6, ночью по вызову | 3 | нет |
| 4 DNA | 2 100 | нет | нет; в отзыве $49, засчитанные в работу | нет | не сказано | 7 | нет |
| 5 Air Repair Pros | 2 650 | нет | баннер скидок | нет | о доплате ни слова | 9 | нет |
| 6 TAB | 1 100 | от 60 до 90 минут (FAQ); "25 minutes away" | нет; "Free Estimate" | нет | круглые сутки, цена до работы | 6 | нет |
| 7 GPS | 650 | нет | нет; рассрочка | нет | прямо пишет, что не круглые сутки | нет | нет |
| 8 Pure | 1 350 | нет; 45 минут в отзыве | $150 скидки от $500 | нет | вопрос о доплате без прямого ответа | 6 | нет |
| 9 GO | 1 550 | от 30 до 60 минут (FAQ) | нет; "Zero Dispatch Fees and FREE Estimates" | платы за выезд нет | 24 часа, но в шапке "закрыто по воскресеньям" | 5 | записи о работах без фото |
| 10 Roto-Rooter | 1 800 | нет | купоны, рассрочка | нет | "No Extra Charge for Evening Service" | 7 | нет |

Итог: цифру приезда называют пятеро, без доплаты ночью четверо. Правила, как у нас (доплата по часу, цифра по телефону до выезда), нет ни у кого. Фото или видео с работы нет ни на одной странице.

### 3.4. Страницы по очереди

В списках H2 пропущены призывы, телефоны и купоны.

**1. Berkeys** (Frisco, 4645 Avon Ln; DFW с 1975). https://www.berkeys.com/frisco-tx/plumber/emergency-plumbing-repair/ Title "Emergency Plumbers Frisco TX | Berkeys Plumbing". H1 "24/7 Emergency Plumbing Repair Frisco TX - Fast Response Time". H2: "Emergency Services"; "Why Frisco Homeowners Choose Berkeys for Emergency Plumbing"; "Common Plumbing Emergencies We Handle in Frisco"; "Serving Frisco Families Since 1975"; "Real Emergency Response Stories from Frisco Homeowners"; "Our Emergency Service Guarantee". До приезда: советов хозяину нет, главный кран находит техник. Чего у нас нет: истории с местом (West Frisco, Stonebriar) без фото, раздел гарантий без срока, ссылка на tdlr.texas.gov (отдаёт 404).

**2. Baker Brothers** (DFW с 1945, адреса на странице нет). https://bakerbrothersplumbing.com/mckinney-plumbing/services/emergency-plumbing-repair/ Title "Emergency Plumbing McKinney TX | 24/7 Plumber | Baker Brothers". H1 "Emergency Plumbing in McKinney, TX - 24/7 Service Available". H2: "Signs You Need Emergency Plumbing Service in McKinney"; "How Fast Emergency Plumbers Arrive in North Collin County"; "Serving the Greater Dallas / Fort Worth Metroplex Since 1945"; "Critical Plumbing Problems That Require Immediate Response"; "What Emergency Plumbing Service Includes"; "Insurance Coverage for Emergency Plumbing Repairs"; "Preventing Plumbing Emergencies in Your McKinney Home"; "What is considered a plumbing emergency in McKinney?"; "24/7 Emergency Plumbing Service in McKinney"; FAQ. FAQ: "Does emergency plumbing cost more than regular service in McKinney?"; "How quickly can an emergency plumber reach my McKinney home?"; "Will insurance cover my emergency plumbing repair in McKinney?"; "What should I do while waiting for the emergency plumber in McKinney?"; "Do you service McKinney neighborhoods like Stonebridge Ranch and Craig Ranch for emergencies?"; "What qualifies as a plumbing emergency vs. something that can wait?". До приезда: главный кран, вещи, снимки для страховой, полотенца, дальше от электричества и стоков. Чего у нас нет: страховка, кварталы, профилактика, "сначала остановить, потом постоянный ремонт", ссылка на CDC. Общая срочная страница DFW (2 место без города): ещё H2 про камеру и глину, ссылка на EPA.

**3. Jennings** (Little Elm). https://www.jpstx.pro/emergency-plumbing-frisco-tx/ Title "Emergency Plumbing Frisco TX | Fast Plumber | No Upselling". H1 "Emergency Plumbing in Frisco, TX". H2: повтор H1; "Our Plumbing Services" и 11 H2 с названиями услуг (газ, tankless, hydro jetting, проверка backflow среди них); "Common Plumbing Emergencies We Handle"; "Why Choose Jennings Plumbing Services for Emergency Service in Frisco"; "What Our Customers Say"; пять H2-лозунгов; FAQ, вопросы тегом H2: "Do you offer 24/7 emergency plumbing in Frisco?"; "How fast can you get to my home in Frisco?"; "My toilet is overflowing - can you come right away?". До приезда: пять шагов (главный кран, выключить водонагреватель, при газе уйти и звонить в газовую службу, позвонить, не пользоваться сантехникой).

**4. DNA** (Plano, 542 Haggard St). https://www.dnaplumbingservices.com/plumbing-services/emergency-plumbing/ Title и H1 (по инструменту) "Emergency Plumber Plano You Can Call Any Time". H2: "Calm, Clear Help For Stressful Plumbing Emergencies"; "What To Do Right Now If You Have A Plumbing Emergency"; "How Our Emergency Plumbing Process Works"; "Common Plumbing Emergencies We Handle"; "Why Homeowners & Businesses Trust Our Emergency Plumbing Team"; "Preventing Future Plumbing Emergencies"; FAQ; "Preventing Plumbing Emergencies". FAQ: "How Fast Can Your Team Get To My Home For An Emergency?"; "What Should I Do Before Your Plumber Arrives?"; "Will I Know The Cost Of Emergency Plumbing Before You Start?"; "Do You Really Answer The Phone 24 Hours A Day?"; "What Counts As A Plumbing Emergency?"; "Can You Help If I Am Worried About Paying For Emergency Repairs?"; "Do You Handle Emergency Plumbing For Businesses As Well As Homes?". До приезда: главный кран, дальше от мокрых розеток, убрать вещи, не пропускать запах и шипение газа. Чего у нас нет: шесть шагов вызова; мастер смотрит фото и видео хозяина во время звонка; вопросы про оплату и про бизнес.

**5. Air Repair Pros** (Frisco, 1647 Witt Rd). https://airrepairpros.com/plumbing/emergency-plumber/ Title "Emergency Plumbing in Frisco, TX | Air Repair Pros". H1 "Emergency Plumber in Frisco, TX". H2: "Air Repair Pros Responds 24/7 to Frisco Plumbing Emergencies"; "Why Homeowners in Frisco Call for an Emergency Plumber"; "What Causes Emergency Plumbing Problems in Frisco Homes"; "How Our Team Approaches Emergency Plumbing Service"; "Emergency Plumber Available in Frisco and Surrounding Areas"; "What to Expect During Your Emergency Appointment" (пять шагов); "Why Professional Emergency Plumbing Matters"; "Systems and Equipment We Service"; "Local Experience in Frisco"; "Emergency Plumbing Examples from Frisco and Nearby Communities"; "Why Homeowners Choose Air Repair Pros"; FAQ. FAQ: "How do I know if my plumbing situation is a true emergency?"; "What should I do if a pipe bursts in my home?"; "My toilet is overflowing and will not stop - what should I do right now?"; "I smell gas near a plumbing fixture - is that an emergency?"; "How quickly can Air Repair Pros respond to a plumbing emergency in Frisco?"; "What happens when I call Air Repair Pros for emergency plumbing service?"; "Will I still receive upfront pricing during an emergency call?"; "Should I try to fix a burst pipe myself while waiting for a plumber?"; "What steps can I take to reduce the risk of a plumbing emergency?". До приезда: главный кран, клапан бачка или кран за унитазом, полотенца и ведро, трубу под давлением не латать; при газе уйти и звонить снаружи. Чего у нас нет: два случая с работ текстом без фото, профилактика, рассрочка, абонемент.

**6. TAB** (Dallas 75370, похоже на почтовый ящик: вывод). https://www.tabhomeservices.net/plumber/frisco-tx Title "Emergency Plumber Frisco, TX | 24/7, 4.8-Star | TAB Home Services". H1 "Emergency Plumber in Frisco , TX". H2: "Emergency Plumber in Frisco : What You Need to Know"; "Frisco's 15-Year Plumbing Wave"; "Hard Water and Fixture Wear in Frisco Homes"; "Slab Leaks in Frisco's Construction-Era Homes"; "Neighborhoods We Serve in Frisco"; FAQ; "More services in Frisco". FAQ: "Do you offer 24/7 emergency plumbing in Frisco?"; "Why are so many Frisco homes having plumbing problems right now?"; "How do I know if I have a slab leak in my Frisco home?"; "Are you a licensed plumber in Frisco, TX?"; "What causes toilet running and fixture problems in Frisco homes?"; "How much does an emergency plumber cost in Frisco?". До приезда: ничего. Чего у нас нет: возраст домов Frisco (постройки 2005 до 2020), жёсткая вода, плиты на глине, пять кварталов, номер лицензии в первом экране, рейтинг в title, ссылка на tdlr.texas.gov.

**7. GPS** (Frisco, 3064 Kentshire Ln). https://gps-plumbing.com/services/emergency-plumbing/ Title из шести вариантов ключа подряд ("Emergency Plumbing Frisco TX | Emergency Plumber Frisco TX | ... | GPS Plumbing"). H1 "Emergency Plumbing Services". H2: "Your Comprehensive Emergency Plumber"; "Rapid Response to your Plumbing Emergencies"; "Professional and Experienced Emergency Plumbers"; "Advanced Equipment and Techniques"; "Transparent Pricing"; "Your local, skilled and trustworthy plumber". Часы: будни 8 до 6, суббота до 12, воскресенье закрыто. До приезда: ничего. Чего у нас нет: значки торговой палаты Frisco и PHCC Texas (PHCC у нас не упоминается), ссылка на TSBPE.

**8. Pure** (Richardson, 521 Sterling Dr). https://www.pureplumbingdfw.com/emergency-plumbing-plano-tx/ Title "Emergency Plumber Plano TX | Burst Pipes, Sewage Backups & 24/7 Repairs | Pure Plumbing". H1 "Emergency Plumbing in Plano, TX". H2: "What Emergency Plumbing Covers" (H3: пять услуг, газ среди них); "When to Call an Emergency Plumber in Plano"; "Why Choose Pure Plumbing for Emergency Plumbing in Plano?"; "Pure Plumbing Services in Plano TX"; FAQ. FAQ: "What counts as a plumbing emergency in Plano, TX?"; "How fast does Pure Plumbing respond to emergency calls in Plano?"; "Should I turn off the water before the plumber arrives?"; "Does Pure Plumbing charge extra for after-hours emergency calls in Plano?"; "Can you fix a burst pipe the same night in Plano?"; "What should I do if I smell gas in my Plano home?". До приезда: кран под прибором или главный у счётчика; при газе уйти и звонить снаружи. Чего у нас нет: вопрос про ремонт той же ночью, ссылка на CDC про стоки.

**9. GO Heating, Air & Plumbing** (Plano, 2901 Technology Dr). https://goairservices.com/air-conditioning-heating-plano/emergency-plumber-plano-tx/ Title "Trusted Emergency Plumber Plano, TX | Fast Local Service". H1 "Trusted Emergency Plumber in Plano, TX". H2: "Why Choose Us for Emergency Plumbing in Plano"; "Types of Emergency Plumbing Services We Offer" (в H3 и кондиционеры); "How to Minimize Damage During a Plumbing Emergency"; "Preventive Tips to Avoid Plumbing Emergencies"; "What to Expect When You Call Us"; "Hear What Our Satisfied Customers Say"; FAQ. FAQ: "How long does it take for an emergency plumber to arrive?"; "What should I do if I have a plumbing emergency late at night?"; "Is it safe to use my plumbing during a leak?"; "Can a plumber help with a flooded basement?"; "What is the cost of emergency plumbing services?". До приезда: четыре шага (перекрыть воду, не пользоваться водой, убрать ценное, позвонить). Вопрос про подвал в Plano: шаблон (вывод).

**10. Roto-Rooter** (сеть, Plano). https://www.rotorooter.com/planotx/emergency-plumber/ Title "Emergency Plumber Plano TX | Fast Response | Roto-Rooter". H1 "Emergency Plumbing in Plano, TX". H2: "When Cast Iron and Clay Soil Turn a Slow Leak Into a Slab Emergency"; "Plumbing Emergencies That Hit Plano Homes Hardest"; "Plano Neighborhoods Where Our Technicians Respond"; "Steps to Take When a Plumbing Emergency Strikes"; "What to Expect From Roto-Rooter Emergency Service"; "Same-Day Emergency Plumbing in Plano"; "Financing Available for Emergency Plumbing Repairs"; FAQ. FAQ: "Why do Plano homes experience so many pipe failures?"; "Can hard water cause plumbing emergencies?"; "Does Roto-Rooter provide commercial emergency plumbing in Plano?"; "How quickly can Roto-Rooter respond to a plumbing emergency in Plano?"; "What should I do if I suspect a slab leak in my Plano home?"; "Does Roto-Rooter handle water heater emergencies in Plano?"; "How do I know if tree roots are causing my sewer backup?". До приезда: главный кран и где он в домах Plano (их слова), у водонагревателя выключить газ или питание, открыть краны и сбросить давление, убрать вещи. Чего у нас нет: местные утверждения (чугун под плитами домов 1970-х и 1980-х, глина, жёсткость воды цифрой; слова сети, мной не проверены), кварталы с годами постройки, коммерческие вызовы.

### 3.5. Темы, которых у нас нет

Есть у двух и больше, нет на живой странице. "Сборка": `site/dist/emergency-plumbing-services/index.html`.

| Тема | У кого | Живая | Сборка | Заметка |
|---|---|---|---|---|
| Страховка, снимки повреждений для страховой | Baker (H2 и два вопроса), Berkeys (фраза) | нет | нет | только слова Дениса |
| Шаги вызова по порядку | Air Repair Pros, DNA, GO, Berkeys, Baker | фраза во вступлении | нет | есть на главной; повтор с главной разрешён только им и фразе про $49 |
| Сначала остановить воду, потом постоянный ремонт; самому трубу не латать | Air Repair Pros, Baker, Berkeys, Pure, Roto-Rooter | только история с обводом бака | нет | |
| Водонагреватель: выключить газ или питание | Jennings, Roto-Rooter | только кран холодной воды | в "No hot water" проверка запальника и автомата | |
| Где главный кран в здешних домах | Roto-Rooter, Pure | ссылка на гайд | есть | закрыто сборкой |
| Как не довести до аварии | Baker, GO, DNA, Air Repair Pros | только мысль про краны, которые никто не крутил | нет | у Дениса есть совет про 80 PSI |
| Глина, жёсткая вода, возраст домов | TAB, Roto-Rooter, Air Repair Pros, Baker, Berkeys | нет | нет | объяснения живут на страницах услуг и городов |
| Названия кварталов | Baker, TAB, Roto-Rooter, Berkeys | нет | нет | города держат свои страницы |
| Оплата частями | Berkeys, Air Repair Pros, Roto-Rooter, DNA, GPS | нет | нет | у нас "pay over time", "financing" о нас нельзя |
| Гарантия на срочную работу | Berkeys (без срока), TAB (значок) | нет | нет | срок только по решению Дениса |
| Коммерческие вызовы | DNA, Roto-Rooter | нет | нет | у FPP бывают, страницы нет |
| Запах газа: что делать | Jennings, Pure, Air Repair Pros, DNA | фраза с "then call us" | та же | газ без слова Дениса не заявляем |
| Не пользоваться водой до приезда | Jennings, GO | нет | нет | |
| Отзывы на странице | Jennings, GPS, GO, DNA, Pure | нет | два отзыва Google | закрыто сборкой |
| Ссылка на официальный источник | Baker и Pure (CDC), Berkeys и TAB (tdlr.texas.gov), GPS (TSBPE) | нет | нет | по правилам нужна |

Не берём, хотя это есть у многих: минуты и часы приезда (пятеро), "без доплаты ночью" (четверо; у нас доплата есть), купоны и цены в баннерах (шестеро), бесплатная оценка (Baker, TAB, GO; у нас её нет), газ, tankless и hydro jetting в списках услуг.

Нет ни у кого (вывод): фото и видео с настоящих срочных работ; краны под раковиной и за унитазом с запретом крутить старый кран ключом; список "подождёт до утра" (близко только вопрос Baker); ночная цена до выезда. Близко к нашему FAQ: вопрос DNA про телефон круглые сутки почти как наш первый; "что делать до приезда" есть у DNA, Baker и Pure.

## 4. Материал Дениса для этой страницы: кейсы и номера файлов

Источники: `docs/material-from-denys.md` (указатель, строка 2018), `photos/captions.csv`, `photos/captions-en.csv`, `photos/index.csv` (даты), `source/dictation/`, тексты главной, Frisco и Plano в `source/`, `docs/pages-plan.md`, `CLAUDE.md`. Город: «слово» значит, что город назвал Денис; «по месту» значит, что город взят по границе города из места съёмки; «без города» значит, что места в файле нет или съёмка вне десяти городов. Слова Дениса даны коротко.

### 4.1. Главный кейс: потолок в Plano (первый экран и история)

По заданию этого брифа: решение Дениса от 5 октября, кейс идёт на первый экран и в текст как история. Записи этого решения в файлах проекта я не нашёл: в таблицах 253 до 255 отложены под leak detection и Plano (`photos/captions-en.csv`, `docs/pages-plan.md:165`), emergency там не стоит.

| Файлы | Город | Дата | Слова Дениса | Что в кадре | Где уже стоит |
|---|---|---|---|---|---|
| 253 видео 5 с, 254 видео 15 с, 255 видео 8 с | Plano, слово (граница совпадает) | 2 октября 2026 | «Последние фотографии к кейсу в Plano, где пинхол и отвалился потолок» | 253: с потолка свисает гипсокартон; в кадре вещи хозяев и зеркало, брать окно только с потолком. 254: тонкая струя из пинхола на медной линии, мокрый гипсокартон. 255: участок заменён, новая медь на пресс-фитингах | Нигде |
| 256 видео 8 с, 257 видео 9 с | Plano, слово | 22 сентября 2026 | «У них до этого hose bib уже лопался и давно тёк... Это постоянно там, где hose bib выходит из земли» | 256: старый кран на трубе из земли, вода бьёт у земли. 257: новый кран на новой меди | Стоят на странице Plano под пунктом про уличные краны |

Вывод: история потолка нигде не рассказана, здесь её можно дать целиком. Кран 256 и 257 уже показан на Plano: здесь одна фраза, что в том же доме раньше лопнул кран на трубе из земли, со ссылкой на hose bib repair. Связи между краном и пинхолом Денис не называл, писать её нельзя. По правилу «проблема сначала» первым идёт 253 или 254, 255 в конце.

### 4.2. Аварии с его словами, на страницах пока нет

| Файлы | Город | Дата | Слова Дениса | Что в кадре | Отложено для |
|---|---|---|---|---|---|
| 297 до 300 (видео 31, 9, 10, 26 с) | Frisco, по месту | 6 февраля 2026, вечер | «Emergency, вечерний звонок... Год назад было пробито гвоздём от плинтуса... гвоздь закрывал утечку и ржавел... вечером началась активная утечка, начало всё затапливать» | Вскрытая стена у плинтуса, две медные трубы; гвоздь в бруске (298); водяная пыль в свете фонаря (300) | emergency, leak detection, Frisco |
| 114, 116 до 120, 237, 238 | без города (вне десяти) | 22 февраля 2025 | «Зимой лопнула труба за стеной и начала затапливать и в сторону дома, и в сторону улицы... в стене были PEX трубы, установленные на SharkBite, растянулось и лопнуло... установили медную линию»; «раньше её чинили кусочками» | 114 вода бьёт из стены; 118 лопнувшая труба в стене; 116, 117 вынутая PEX (одно из двух); 119 замена на медь с ProPress; 120 после; 237 вырезанный кусок с фитингом (обрезать пакет со штрихкодом и марку аккумулятора); 238 вода бежит по кирпичу снаружи (окно без двора с вещами) | emergency (114, 119, 120, 237, 238); top-emergency (114, 116, 120); gallery (117). Фото 118 стоит на /top-emergency-plumber-calls-frisco/, текст той страницы эту работу не рассказывает |
| 295 видео 17 с | Plano, по месту | 29 января 2024 | «Предыдущий сантехник сделал что-то типа манифолда в стене из SharkBite. SharkBite сломался, начал затапливать дом, вода хлещет» | Латунные push-fit фитинги во вскрытой стене, из них бьёт вода | leak detection, emergency, Plano |
| 280 видео 8 с | без города (места нет) | 10 декабря 2022 | «Из PEX линии в стене хлещет вода... handyman устанавливал полки в гардеробе и пробил PEX линию гвоздём» | Красная PEX в стене гардероба, тонкая струя | leak detection, emergency |
| 136 видео; 235 видео 8 с | Plano, слово | 8 мая 2025 | «На втором этаже, в кладовке за heater. Залил полдома. Сперва долгое время был маленьким пинхолом, потом превратился в активную утечку» | 136 струя из пинхола на меди 3/4 в стене; 235 после: стена открыта, новая медь | 136: leak detection, emergency; 235: leak detection, Plano. Это не четвёртая история Plano (188, 189) |
| 274 видео 5 с | Plano, по месту | 8 сентября 2026 | «главная водяная труба, service line на улице, лопнула. Мы начали копать: вода фонтаном хлещет прямо из-под бетонного sidewalk» | Яма у бетонной дорожки, вода бурлит | water lines, emergency. Не работа поста про тротуар (пост вышел 8 мая 2026) |
| 90 фото | без города (места нет) | 16 декабря 2024 | «Ресторан: забита главная линия, аварийный вызов, пробили chain snake» | Коммерческий объект, названия не видно, так и оставить | emergency, drain cleaning |

Марку push-fit фитинга Денис назвал, в подписях её нет (заметка к 237). Его слова, что такой фитинг нельзя ставить в закрытую стену, это его мнение, не правило кода (`CLAUDE.md:127`).

### 4.3. Мороз: «добавь, что у нас такое есть», историй нет

Первые три строки: без города (места в файлах нет), на страницах их нет. Слова: `2026-10-05-plano-photos.md:138-142`.

- 279 (23 декабря 2022) и 275 (28 января 2023), фото: медь на чердаке лопнула в мороз. «Burst pipe на чердаке. Медная, лопнула в мороз».
- 278 (24 декабря 2022), фото, и 277 (28 января 2023), видео 6 с: медь в наружной стене. «Медная, капает. От мороза взорвалась».
- 276 (28 января 2023), видео 4 с: заглушка на отводе душевого клапана к spout лопнула и капала. Отложено ещё для faucet and shower valve.
- 252 (23 января 2024), видео 6 с, Frisco по месту: пресс-фитинг в наружной стене, труба внутри лопнула. Уже стоит клипом на Plano без города. Один случай: общего правила о пресс-фитингах не писать (`CLAUDE.md:54`).

### 4.4. Уже рассказано на других страницах: здесь одна фраза со ссылкой

| Файлы | Город | Его слова коротко | Где рассказано |
|---|---|---|---|
| 173 (16 июня 2025) | Frisco, слово | «ночной emergency звонок: он ночью лопнул... drain pan уже не спасал» | Frisco, «Night Calls in Frisco», клип |
| 174 (21 мая 2025) | Frisco, слово | «человек принял душ и не смог выключить воду» | Frisco, «Night Calls in Frisco», клип |
| 178 (январь 2024) | Frisco, слово | «подающая линия воды к наружному спиготу в стене лопнула в мороз, начало затапливать весь гараж; мы срочно приехали» | Frisco, «What a Freeze Breaks» |
| 164 (день не записан) | Allen, слово | «перегрызли линию в двух местах, вода шла через потолок и стены» | Главная, From the Job, «Chewed through in the attic» |
| 183 (21 сентября 2024; 184 снят ночью с фонарём) | без города (вне десяти) | «Забитая главная линия, полный overflow: туалет, ванна, уличные клинауты» | Кадр 183 стоит на главной у истории «One clog, the whole house» (`tools/export_home_text.py:93`) |
| 197 до 199 (декабрь 2024) | Frisco, слово | PRV в коробке течёт (поправка Дениса: не лопнул); 197 снят ночью | Клип 199 у пункта PRV на Frisco |
| 271, 272 | Plano, слово | Засор через унитаз, в тексте «emergency call» | Plano, первая история |
| 112 (17 мая 2025) | Frisco, по месту | Не его слова, описание: «Денис на аварийном вызове: в стене вырвало кран, перекрывает воду» | Блок Дениса на главной, фото автора на 33 постах и гайдах. Пометка в таблице: «confirm he wants it on the site (strong emergency hero)» |

На тестовой странице стоят 6, 47, 48, 96 (блок «What is happening right now?»), в плане фургон 4: это не истории аварий.

Похожие кейсы под другие страницы (не путать с главным): Allen, потолок первого этажа течёт и отваливается, корродированный tee (245 до 247, декабрь 2024; leak detection, Allen); вода из-под фундамента «как водопад, как фонтан», Carrollton по месту (281, 282, сентябрь 2026; slab leak); гвозди застройщика в линии к водонагревателю, McKinney (289 до 294; 289 отложен и для emergency, но это поиск утечки).

### 4.5. Как идёт аварийный вызов: что Денис уже сказал

| Факт | Где записан |
|---|---|
| Многоканальные телефоны: звонок и сообщение видят все, берёт тот, кто увидел первым, днём и ночью | `source/dictation/2026-10-01-homepage.md:25`; его английский `2026-10-01-homepage-en.md:37`, правка грамматики `:40`; `CLAUDE.md:32` |
| «If it's an emergency and water is running, flooding, overflowing, you're first in line» | `2026-10-01-homepage-en.md:37, 40` |
| Свободное время есть, ждать не заставляем; подстраиваемся; настоящую аварию ставим первой, двигая расписание | `2026-10-01-homepage.md:26`; `CLAUDE.md:32` |
| Без обещаний времени: окно приезда по телефону, по месту дежурного; «20 минут» из истории про чердак не для сайта | `CLAUDE.md:46, 21`; `2026-10-02-from-the-job.md:3` |
| «Мы открыты 24 часа для emergency plumbing сервиса. Мы всё время на линии. Если emergency, мы всегда выезжаем»; офис с 8 до 5 | `2026-10-05-plano-photos.md:9`; `CLAUDE.md:42` |
| Emergency основной сервис, «первым должно быть самое основное» | `2026-10-05-plano-photos.md:95` |
| Строка «A licensed plumber is on duty 24/7»; город дежурного не показывать | `CLAUDE.md:38` |
| $49 в будни, идёт в счёт ремонта; вечер, выходные, праздники: аварийный сбор по часу, называется по телефону до выезда; бесплатных оценок нет; одобренная цена равна цене в счёте | `CLAUDE.md:45`; его слова про $49: `2026-10-01-homepage-en.md:37` |
| Два офиса, Frisco и Plano, других нет | `2026-10-01-homepage-en.md:37`; `CLAUDE.md:39, 40, 44` |
| 4 до 5 лицензированных сантехников, двое на каждой смене, диспетчер на телефонах | `CLAUDE.md:32`; `source/approved-text-edits.md:10` |
| Машины загружены по максимуму: запчасти, фитинги, труба; акустика, тепловизоры, тросы, chain snake, ProPress только над плитой | `2026-10-01-homepage.md:27`; `CLAUDE.md:32` |
| Restoration partner без имени и ссылки; на аварии можем приехать с их бригадой; сушат, mitigation против плесени, ведут страховую | `CLAUDE.md:32`; `2026-10-02-frisco-additions.md:82`; `2026-10-03-plano.md:13, 16` (запись чата, не дословно) |
| Счёт с описанием работы, фото крупных работ, очки с камерой | `CLAUDE.md:32` |
| До приезда: одобренные ответы «use as is» (горячая вода, канализация, давление, вода на полу), блок «Close the main shut-off valve», никогда «a quarter turn valve» | `source/approved-text-edits.md:28-32` |
| «If one drain backs up, stop every drain in the house, including the washer and the dishwasher, and call»; знать, где главный кран и как его закрыть | `2026-10-02-from-the-job.md:14, 11, 19` |
| Мороз: капают краны в доме; уличный кран frost free не должен мёрзнуть, ему нужен чехол; никогда не писать, что кран должен капать | `CLAUDE.md:122`; `2026-10-02-frisco-additions.md:80-82` |

Нельзя: smoke test (хозяин /drain-services/, `CLAUDE.md:54, 93`), hydro jetting и газ без слова Дениса (`:56`), о backflow больше одной разрешённой фразы (`:20`), телефоны в тексте (`:94`). Не повторять слово в слово шесть шагов вызова (`home-text-v4.md:67-76`), From the Job (`:122-132`) и «Night Calls in Frisco» (`frisco-text-v4.md:134-138`). Истории живой страницы про fill valve, пинхол на чердаке, бак во втором этаже, посудомойку с главной линией и ремонт ванной в диктовках не найдены (`docs/service-emergency-2026-10-03.md:159`).

### 4.6. Чего в материале нет

- У кейса с потолком нет ничего, кроме трёх видео и одной фразы: ни времени вызова, ни этажа, ни линии (горячая, холодная, диаметр), ни того, кто перекрыл воду, был ли поиск утечки и приезжал ли restoration partner.
- Ночной или вечерний вызов записан только у 173, 164 (ночь), 197 и 184 (сняты ночью), 297 до 300 (вечер) и у двух историй главной. У 253 до 255, 295, 280, 114, 136, 274, 90 и морозных снимков время вызова не записано.
- Своих слов Дениса про аварийный сбор нет: только правило `CLAUDE.md:45`. Заменяет ли сбор $49, идёт ли он в счёт ремонта, с какого часа начинается вечер, в файлах не сказано.
- Отдельной диктовки «что делать до приезда машины» для этой страницы нет; есть одобренные ответы блока «What is happening right now?» и правила из историй главной.
- Кто был на этих вызовах, не сказано: имён в историях нет.

## 5. Отзывы: кандидаты

Источники: `reviews/all-reviews.csv` (407 строк), `site-reviews.json`, `site-ledger.md`, `ledger.md`, `ledger-decisions.csv`, `raw/thumbtack-reviews.json`, `docs/journal.md`, `docs/reviews-proposal.md`, городские брифы от 3 октября. Отбор: пять звёзд; ночь, вечер, выходной, праздник, вода льётся. Тексты из CSV знак в знак, живьём не сверялись.

Общие ссылки: Yelp `https://www.yelp.com/biz/fpp-plumbing-plano-2` (на отдельный отзыв ссылки нет); Thumbtack `https://www.thumbtack.com/tx/plano/handyman/fpp-plumbing/service/454195206250143760`. Все Thumbtack ниже с меткой "Hired on Thumbtack": не копии с Google.

### 5.1. Что уже стоит на этой странице

На тестовом сайте за `/emergency-plumbing-services/` уже стоят два отзыва Google (профиль Plano): **Gerardo** (May 2025, Local Guide Level 2, «Sunday night the faucet in my bathroom broke and there was water everywhere…») и **Mark Y** (July 2025, Level 2, «a shower that we could not turn off at 4AM…»). Города и имени Дениса в текстах нет.

### 5.2. Лучшие свободные, по порядку

Порядок мой (вывод): ночь или выходной, вода идёт, есть итог, без повтора Gerardo и Mark Y.

**1. Jim Henderson**, Google, April 2025. Ссылка: https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sChZDSUhNMG9nS0VJQ0FnTURJanA3OFR3EAE!2m1!1s0x0:0xccc66184bdaf3a93
> A++++ recommendation!!!  FPP Plumbing (Fixing Plumbing Problems), promptly responded to my plumbing emergency.   On a Sunday evening, my home outside faucet busted and began gushing water into my yard.  I called a number of emergency rated plumbers I found online, but Denys from FFP Plumbing, was the ONLY PLUMBER AVAILABLE TO RESPOND.  He was upfront about the emergency hours charge, and showed up in a manner of minutes.  He was able to quickly resolve the issue and replace the older faucet with a quality new one.  He was very polite and professional with great communication, plus provided advice and safeguards on preventing this from happening again in the future.   I'm saving his number in my phone should I ever have another plumbing issue.

Почему: воскресный вечер, вода хлещет, плата за аварийные часы названа заранее, как в правилах цен. Стоял на старой Plano, на новой его нет. Уровень Local Guide не записан.

**2. Kevin N.**, Thumbtack, January 2023.
> These guys are life savers. I had a leak in an upstairs bathroom and water was coming out of my light fixture in the kitchen as well as down the walls in my garage. They came out the same day I contacted them and were able to diagnosis and fix the issue. I would and will be contacting them for any other plumbing work that I have.

Почему: вода через светильник и по стенам; о компании.

**3. Phillip M.**, Yelp, February 2024.
> Had to replace my shutoff valve because it was leaking. Unfortunately due me installing it badly, leaked to the lower floor and had to turn off the water to the home. Mind you, this was on a Saturday evening.   Denys from FPP was quick to respond on Sunday and was at my place within 1h! He was able to diagnose and remediate the problem within another hour. He gave me a rundown of why it leaked, showed me the misinstalled part and educated me on how to properly install it.  Did I mention his fees were incredibly competitive! Will definitely be calling him again if plumbing issues arise!

Почему: суббота вечер, вода на нижний этаж, дом перекрыт. Стоял на старой главной, сейчас свободен.

**4. Chris V.**, Thumbtack, January 2024, вид работы "Emergency Plumbing".
> Denys was great. He came out quickly (and on a Sunday!) when my main water valve leading into the house burst.
> He quickly for the problem and replaced (and really upgraded) the problem part.
> I will definitely use him again.

Почему: лопнул главный кран, воскресенье. Минус: опечатка во 2-й фразе.

**5. Kathleen C.**, Thumbtack, January 2023.
> Denys made quick work fixing burst pipe in a difficult attic location in my house. Really appreciate the quick response! The repair looks excellent, I recommend him highly!

Почему: burst pipe на чердаке, тема красной точки «Burst pipe, 24/7 emergency» в домике.

**6. Jaime D.**, Yelp, November 2023.
> We had a plumbing issue later in the evening and FPP was not only very quick to respond, but they also arrived within an hour during a holiday week. They were able to fully resolve our issue in an efficient and thorough manner. They were very professional, let us know what the problem was and there were no surprises from what was quoted. I hope we don't have any more problems, but if we do I would not hesitate to call them again. Highly recommend

Почему: вечер, праздничная неделя, «no surprises from what was quoted». Без имени Дениса.

**7. Ahmed J.**, Thumbtack, December 2022, "Emergency Plumbing".
> We had a water leak in the bathroom that happened over night. First, Denys was super quick to respond and very punctual.
> Second, work quality is excellent. Kept us updated as they fixed the problem and also came prepared with all materials.
> Thank you for responding so quickly (I reached out at 4am in the morning) and getting the issue resolved.

Почему: ночь, «came prepared with all materials». Минус: 4am, как Mark Y.

Цифры времени (1h, within an hour, 4am) это слова клиентов: по решению Дениса от 2 октября остаются.

### 5.3. Запас (полные тексты в CSV)

| Автор | Площадка, дата | О чём | Почему ниже |
|---|---|---|---|
| Frank D. | Thumbtack, Nov 2022 | душ, вода перекрыта, готово в 10:30pm | тема Mark Y, длинный |
| David L. | Thumbtack, Dec 2022 | другие «don't work weekends», труба | тема Gerardo |
| Matt M. | Yelp, Mar 2024 | авария среди ночи | две фразы |
| Larry K. | Thumbtack, Jun 2022 | дом без воды | общо |
| Mike r. | Thumbtack, Jun 2023 | уличный кран, не перекрыть | ближе к hose bib |
| Stacie B. | Yelp, Jul 2026 | выходной, 6:30am, hose bib | ближе к hose bib, "Hi" вместо "He" |
| M. Gibson | Google, Nov 2024 | второй аварийный вызов, линия | ближе к дренажу |
| Phillip Potter | Google, Dec 2024 | «emergency job on a Sunday» | одна фраза |
| Kareem B. | Thumbtack, Feb 2023 | инструкции по телефону | одна фраза |
| alex p | Google, Jan 2025 | нет горячей воды в снегопад | звучит как реклама |

Kevin N., Jaime D., Matt M., Stacie B., alex p, Phillip Potter уже предложены в городских брифах от 3 октября. Один человек на одну страницу.

### 5.4. Называют город: не сюда

- **Dawson And Kelly M.** (Thumbtack, Dec 2022): «at our house in Plano», 9pm, работа почти до 1am.
- **Yulia B** (Google, Jul 2025): «emergency plumber in Frisco», водонагреватель на чердаке. Денис 1 октября: заменить (SEO-фраза).
- **Tyler Sommers**, **Paula Thompson** (Google): Carrollton, стояли на старой Carrollton.
- **Nivas chowdary** (Plano): по CLAUDE.md не используется.

### 5.5. Не брать или с вопросом

- Уже стоят: главная: Paul J. (7pm, потолок), Sandra Williams (после 6pm в пятницу), Srikanth Siruvuri (воскресенье утром, душ). Frisco: tony phuong, Rushi Nani. Plano: Jeff Blackwell (Friday night after hours). Другие услуги: Derek Gordon, william mckinney, Kathryn Kim (оба отзыва), Saman Attar, Liane W. (она же L W в Google), Yuliia Novoderezhkina, Stephan S (оба), David Baez, KD, Brandon Klapholz, Madison h., Zach Z.
- Сергей Кравченко: Денис снял сам, не возвращается. Виктория Стехина: "best plumber near me", снята с Frisco 2 октября. Maksym Basovskyi: Денис, только The Colony. Ann Crawford: Денис, можно на expansion tank.
- Со словами "plumber near me": Vlad Ezhov, Mohaimen Kadhim, funny warner f, Michael Shephard ("best plumber near me"), Inna Kravchenko. Vlad Ezhov и funny warner f сняты 1 октября как SEO-фразы (`reviews-proposal.md`).
- Elnard KA: в тексте "North Dallas", запрещённое на сайте.
- Sean J. (Yelp): «without an emergency fee», вывод: спорит с правилом платы за вечер.
- Возможно тот же человек: Amy V. и Amy Van (старая Allen, кран холодильника у обоих), Victoria N. и Victoria Nwanegbo (старая McKinney), Chris V. и Chris Volpe (Google). По файлам не доказать.

## 6. Официальные страницы

- Город Plano, «Winter Preparedness»: https://www.plano.gov/winter-preparedness . Под заголовком «Winter Weather Water Tips» стоит «Leave indoor faucets dripping and open your sink cabinets during a freeze.» Текст страницы подгружается через несколько секунд после открытия, сначала видны два ролика. Открыта Claude Code 5 октября 2026; на странице Plano на неё уже стоит ссылка.
- Город Plano, возврат за PRV: https://www.plano.gov/water-conservation-rebates (стоит на странице Plano). На срочной странице не нужна.
- Лицензия: в разметке и в подвале сайта стоит Texas State Board of Plumbing Examiners (TSBPE). Два конкурента ссылаются на tdlr.texas.gov, у одного ссылка отдаёт 404. По сведениям Claude Code на 2026 год лицензии сантехников в Техасе по-прежнему выдаёт TSBPE (tsbpe.texas.gov); перед тем как ставить на страницу официальную ссылку о лицензии, открыть tsbpe.texas.gov и убедиться.
- Страницы города Frisco о заморозках и об аварийном отключении воды для этого брифа не открывались. Если текст сошлётся на город Frisco, страницу открыть и проверить фразу перед сборкой, как сделано с Plano.

## 7. Вопросы FAQ, которых нет ни на одной странице сайта

Откуда. Собранный сайт `site/dist` (сборка 5 октября 2026, 16:51), 63 страницы. Вопросы взяты скриптом из схемы FAQPage и из жирных вопросов блока FAQ, на всех страницах они совпали. FAQ есть на 60 страницах, всего 280 вопросов. Полный список по страницам в размер части не входит: `/private/tmp/claude-501/-Users-denyskavaler-Projects-fppplumbing-site/d2b78dea-4d58-4222-812f-a40bb43eb5d1/scratchpad/e5/faq-site-list.md`. Живая страница: краул 30 сентября 2026. Числа Search Console: показы · место за 16 месяцев (`emergency-gsc-table-16m.md`, `source/gsc/page-query-16m.csv`).

### 7.1. Что уже стоит на сайте

Повторы слово в слово уже есть: "Do you charge extra after hours?" и "How much does a plumber cost in ..., TX?" на восьми городских страницах, "How do I know if my main water line is leaking?" на трёх, ещё пять пар.

Вопросы, с которыми может столкнуться FAQ этой страницы:

- Главная (закрыта): "Are you open 24/7? Do you really answer at night?", "How quickly can a plumber arrive?", "How much do your services cost?", "Do I get photos or a report of the work?", "Do you handle the water damage too?"
- Frisco: "Who answers the Frisco line after hours?", "What should I do before a freeze in Frisco?". Plano: "How does an emergency plumbing call work at night in Plano?"
- Города со старым текстом: "Do you charge extra after hours?" (8); "How fast can you get to Lewisville?", то же The Colony, "How quickly can you get to Prosper?"; Allen: "What happens if the problem turns out smaller than expected?", "My water heater died overnight. How fast can you replace it?"; Lewisville: "The shutoff valve under my sink will not turn. Is that a problem?"; Little Elm и Carrollton: "My whole house lost water pressure. Is that the PRV?"
- `/top-emergency-plumber-calls-frisco/`: "My pipe just burst. What do I do first?", "Why do pipes burst during a freeze?", "Do you charge extra for emergency calls?"
- Гайд цен emergency: "How much does emergency plumbing cost?", "Why is emergency plumbing more expensive?", "What is considered a plumbing emergency?"
- Гайды: "How do I turn off the water to my house in an emergency?" (перекрытие воды, заморожен); "Do I need an emergency plumber for a ceiling leak?" и "Is a plumbing leak after a remodel covered by warranty or insurance?" (после ремонта ванной).
- Водонагреватели: "Is it normal for water to smell like gas from a water heater?", "My ceiling has a water stain under the attic. Is it the water heater?", "Do I need to replace my water heater if it’s leaking?"
- `/water-lines/`: "Why did my water pressure drop everywhere at once?"

Остальные вопросы сайта про отдельные узлы и ремонт.

### 7.2. Девять вопросов живой страницы

Слово в слово ни один не стоит на других страницах, на собранной странице те же девять. Правило 8 даёт 5 до 7. Вердикт мой.

| № | Вопрос | Вердикт | Почему |
|---|---|---|---|
| 1 | "Do you really answer the phone at night?" | менять | почти повтор главной и Frisco |
| 2 | "Do I pay the after hours fee if the repair turns out to be small?" | может остаться, ответ заново | рядом Allen; в ответе "the bill follows the work, not the estimate", против правил цен |
| 3 | "Is my problem actually an emergency?" | оставить или заменить кандидатом 1 | рядом гайд цен "What is considered a plumbing emergency?" |
| 4 | "What should I do before you arrive?" | может остаться | ответ повторяет H2 "Shut This Off First, Then Call" и блок "What is happening right now?" |
| 5 | "The valve behind my toilet will not stop the water. What do I do?" | может остаться | про кран, который не держит, два вопроса (5 и 7), хватит одного |
| 6 | "Water is coming through my ceiling. Where is it coming from?" | менять | рядом два вопроса про потолок; ответ про поиск течи без ссылки на leak detection |
| 7 | "My shut-off valve will not turn. What now?" | менять | почти повтор Lewisville |
| 8 | "How fast can you get here?" | убрать | у главной и трёх городов; "how quickly can an emergency plumber in frisco typically respond?": главная 57 · 7.1, эта 30 · 11.6 |
| 9 | "Do you charge extra on holidays?" | менять | рядом восемь городов и top 5 |

### 7.3. Кандидаты

Каждый сверен со списком сайта: слово в слово нет ни одного. «Рядом» значит близко по смыслу (мой вывод). «Денис: да» значит, что ответ без его фактов не написать.

1. "Can this wait until morning, or should I call tonight?" Замена вопросу 3. Основа: живой H2 "What Actually Counts as an Emergency" со списками "Call tonight" и "This can wait until morning"; "what should i do if i have a plumbing emergency at night?" (1 · 4.0). Рядом: гайд цен. Денис: да, источник списков не записан.
2. "Is the $49 weekday service call the same at night or on a Sunday?" Основа: правила цен CLAUDE.md; "how much is after hours plumbing" (17 · 89.3), "how much is an out of hours plumber" (17 · 74.2), "do plumbers charge more on weekends" (1 · 13.0). Рядом: восемь городов, главная. Из сумм только $49. Денис: да.
3. "Do you come out on Sundays and holidays?" Замена вопросу 9. Основа: CLAUDE.md "24/7 including holidays"; "do plumbers work on weekends" (2 · 9.0), "do plumbers work on sundays" (1 · 10.0). Рядом: главная. Денис: нет.
4. "The sewer backed up at night. Will you clear it tonight?" Основа: одобренный ответ "Sewer backing up" ("a sewer backup goes to the front of the schedule"); "frisco sewer line backup" (54 · 28.4), "emergency sewer backup near me" (12 · 32.7). Рядом: Plano. Что делать до приезда уже в блоке; прочистка одной фразой со ссылкой на drain cleaning. Денис: да.
5. "My water heater is leaking. Do I also turn off the gas or the breaker?" Основа: одобренный ответ "No hot water" ("close the cold valve on top of the tank"). Рядом: `/water-heaters/`, Allen. Работ по газу не заявлять. Денис: да.
6. "There is no water in the house at all. Is it the city or my plumbing?" Основа: "who do i call if i have no water in my house" (1 · 8.0). Рядом: Little Elm, Carrollton, `/water-lines/`; одобренный ответ "No pressure" в блоке почти закрывает тему. Брать, только если в ответе будет новое. Денис: да.
7. "I smell gas near the water heater. Do I call a plumber?" Основа: живая фраза "leave the house first, call the gas utility, then call us". Рядом: вопрос про запах газа у water heater repair. Газ не наш, пока Денис не подтвердит; ответ не должен читаться как выезд. Денис: да.
8. "Can you stop the leak tonight and do the full repair later?" Основа: живая история с "a bypass so the rest of the house could work", источник не записан. Рядом: ничего. Денис: да.
9. "Do you bill my insurance company for a burst pipe?" Запроса в Search Console нет. Факты CLAUDE.md: счёт описывает работу, фото и видео по просьбе, партнёр по сушке. Рядом: главная (фото, water damage). Что покрывает страховка, не писать. Денис: да.
10. "The pipes froze overnight but nothing is leaking yet. What should I do?" Основа: живой H2 про мороз ("the failure usually shows up not during the freeze but on the thaw"); поправка Дениса про мороз; "emergency frozen pipe repair service available now" (1 · 11.0). Рядом: top 5, Frisco. Денис: да.
11. "Water is dripping through the ceiling. Should I poke a hole to let it out?" Замена вопросу 6. Рядом: оба вопроса про потолок. Поиск течи одной фразой со ссылкой на leak detection. Денис: да.
12. "Can I text you at night instead of calling?" Основа: CLAUDE.md, звонок звонит у всех ("also texts"); на главной "Call or text us about it". Рядом: ничего. Номер в ответ не ставить. Денис: да.

Не брать (мой вывод): "how do emergency plumbing services in plano work?" (эта 34 · 14.1, Plano 18 · 10.8): под него уже стоит вопрос FAQ на странице Plano; цену emergency в суммах держит гайд цен (ключ "emergency plumber cost"); сроки приезда у главной.

## 8. Что нельзя потерять

Из заметки ("Коротко", пункт 4; 2.3) и решений о главной (CLAUDE.md, правило 5). Правило проекта: то, чем страница ранжируется, остаётся или заменяется один к одному.

| Слова | Где стоят сейчас, дословно | Почему |
|---|---|---|
| Emergency Plumber, Frisco, Plano, 24/7 | title "Emergency Plumber in Frisco & Plano, TX \| 24/7 Plumbing Service"; H1 "Got a Plumbing Emergency? Call Your 24/7 Emergency Plumber in Frisco, Plano & McKinney: Licensed, Fast, and Local" | title и H1 держат по 60 тысяч показов |
| McKinney | H1 | из заголовков только H1 держит запросы с McKinney: "emergency plumber mckinney" 788 · 65.9 |
| 24 Hour Plumber | H2 "What a 24 Hour Plumber Costs After Hours", "A 24 Hour Plumber Who Actually Picks Up", "24 Hour Plumber Service Area: Frisco, Plano and the Cities Around Them" | "24 hour plumbers" 3,630 · 14.1, страница выше главной; H2 про города один держит 24 hour plumber с Plano и Frisco (около 2,270 показов) |
| Emergency Plumbing | H2 "Emergency Plumbing FAQ" | единственный заголовок с фразой; "emergency plumbing" 4,164 · 18.2, первый запрос страницы за 3 месяца |
| After Hours | H2 "What a 24 Hour Plumber Costs After Hours" | единственный заголовок с after hours ("after hours plumber" 39 · 21.5) |
| Emergency Plumbing Services | на живом сайте og:title, крошки, меню; на тестовом нигде | "emergency plumbing services" 114 · 10.1 за 3 месяца, почти вровень с главной (311 · 9.8) |

- Фраза "emergency plumbing services" должна вернуться на страницу: в тексте или в заголовке.
- Срочные запросы главной сейчас не трогаем. На главной остаются раздел "24/7 Emergency Plumbing: How a Call Works" и слова "emergency plumber", "emergency plumbers", "same day plumber", "24/7 plumber", "licensed plumber near me", "closest plumber". Передать эти запросы странице emergency можно только отдельным шагом после переезда (CLAUDE.md, правило 5; карта ключей).
- Остаются по правилам 6 и 7: "plumber near me" со ссылкой на главную в последнем абзаце вступления и все десять "plumber in <город>" в тексте.
- Мой вывод: с фото фургона уходит alt "FPP Plumbing emergency plumber truck parked in Frisco", одно из трёх мест, где фраза "emergency plumber" стоит целиком (ещё title и H1, заметка 2.4). Title и H1 её держат, так что потери нет, если они остаются.
- Мой вывод: точной связки с Plano нет ни в одном заголовке ("Frisco & Plano"), а "emergency plumber plano" второй запрос страницы за 16 месяцев (4,812 · 33.6). "24 7 plumber" подряд тоже нигде не стоит (заметка, 2.4).

## Для чата

Собрано из пяти частей. Вопросы к Денису задаёт чат, один раз, сегодня.

### Из части 1 и 2 (живая страница, Search Console)

- Фото фургона снимается 5 октября (по заданию брифа). Тогда у страницы нет ни фото, ни og:image: в heroes файла design.json записи для неё нет. Фото 4 (фургон у офиса Frisco) в архиве отложено и для /emergency-plumbing-services/ (docs/handoff-for-new-chat.md, пункт 156), но alt на других страницах не должен называть Frisco. Для текста там же отложены кадры Дениса: медь, лопнувшая в мороз (275 до 279, без города), вечерний вызов с гвоздём от плинтуса (297 до 300, Frisco по месту съёмки), PEX, пробитая гвоздём (280), главная линия под тротуаром (274, Plano), манифолд из SharkBite (295, Plano), PEX на push-fit, лопнувшая в стене (114, 118 до 120, 237, 238).
- Фразу "emergency plumbing services" можно вернуть только в текст или в H2. Название в меню ("Emergency plumbing") идёт из общего списка услуг (design.services). Его правка меняет меню, панель и подвал на всех страницах, это отдельное решение.
- "emergency plumber plano" это вторичный ключ страницы (4,812 показов за 16 месяцев, место 33.6), но по срочным запросам с Plano лучшее место уже у страницы Plano (2,103 · 4.6 за 3 месяца), её H1 с 5 октября кончается словом Emergencies. Связка "Emergency Plumber in Plano" на странице emergency может отнять запросы у страницы Plano. Решать вместе с Денисом.
- "same day" на странице нет, а "same day plumber" по правилу 5 держит главная (4,944 · 9.8). Мой вывод: на запуске не ставить "same day" в заголовки страницы emergency, чтобы не спорить с главной.
- "Fast" в H1 нарушает правило о времени приезда, но H1 держит 60 тысяч показов. Слово можно убрать, не трогая остального: Emergency Plumber, 24/7, Frisco, Plano, McKinney. Если H1 меняется, это нужно сказать Денису.
- Свои сильные запросы у страницы: "24 hour plumbers" (выше главной за оба периода), "emergency drain service" (8.4), "pipe breaks plano" и "burst pipe plano", варианты с near me. Слова "near me" нет ни в одном заголовке. По карте ключей "plumber near me" для этой страницы запрещён.
- FAQ: девять вопросов при норме 5 до 7. Вопросы 1, 8 и 9 почти повторяют главную и городские страницы, ни один вопрос не держит ни одного запроса. Сокращать FAQ можно без потерь в Search Console.

### Из части 3 (конкуренты)

- Шаги вызова: у пятерых из десяти есть порядок звонок, приезд, цена, ремонт. На главной уже есть раздел "24/7 Emergency Plumbing: How a Call Works". Решить: срочная страница даёт свою версию шагов (повтор с главной разрешён правилом проверки только для шагов вызова и фразы про $49) или говорит о звонке своими словами и ссылается на главную.
- Ночная доплата: четверо пишут, что ночью без доплаты, у FPP доплата по часу, сумма по телефону до выезда. Решить, как просто объяснить, за что она, без цифры. И называть ли на этой странице $49 за вызов в будни (на живой странице он не назван).
- Страховка: у Baker целый раздел и два вопроса. По CLAUDE.md каждый счёт описывает работу, большие работы снимаются, фото и видео по просьбе. Можно ли связать это со страховкой, решает Денис; без его слов тему не ставить.
- Водонагреватель: Jennings и Roto-Rooter советуют выключить газ или питание у бака. У нас на странице только кран холодной воды. Спросить Дениса, что он велит хозяину делать с газовым и электрическим баком, пока плотник едет.
- Запах газа: четверо дают инструкции (уйти, звонить в газовую службу снаружи). У нас фраза "then call us" против правила (газ не заявляем). Решить с Денисом, какой одной фразой о безопасности обойтись, не предлагая газовые работы.
- Как не довести до аварии: у четверых есть такой раздел. У Дениса есть совет мерить давление раз в год, выше 80 PSI система под нагрузкой (CLAUDE.md). Решить, ставить ли его сюда одной фразой со ссылкой на страницу PRV или оставить страницам услуг.
- Официальная ссылка: на странице её нет. Конкуренты ссылаются на CDC (стоки, угарный газ), EPA (плесень после воды), TDLR, TSBPE. Выбрать одну из списка CLAUDE.md (TSBPE, EPA, страницы городов).
- Оплата: пятеро пишут про рассрочку. У нас правило: "pay over time" через PayPal Pay Later и Klarna, слово "financing" о нас нельзя, слова про карту на каждой странице свои. Решить, нужна ли эта строка на срочной странице.
- Коммерческие вызовы: у DNA и Roto-Rooter есть вопрос. FPP иногда выезжает (главная линия ресторана). Спросить Дениса, упоминать ли на срочной странице.
- Фото по телефону: у DNA мастер смотрит фото и видео хозяина во время звонка. У нас на живой странице есть история, где мы попросили фото и прислали гайд текстом. Спросить Дениса, можно ли писать это как обычную практику (телефоны принимают и сообщения).
- H1: у конкурентов H1 вида "Emergency Plumbing in [City], TX" (Jennings, Pure, Roto-Rooter) и "Emergency Plumber in [City], TX" (Air Repair Pros, TAB). Слово "Fast" в нашем H1 против правила о приезде (часть 1). Решать с Search Console, что держит title и H1.
- Кварталы и местные условия (глина, жёсткая вода, возраст домов): у четырёх и пяти конкурентов. По правилам объяснения живут на страницах услуг, города на своих страницах. Мой вывод: на срочную страницу не ставить, решение за чатом.
- Вопросы FAQ: наш "Do you really answer the phone at night?" почти как у DNA, "What should I do before you arrive?" близок к DNA, Baker и Pure. Сверить черновик проверкой на совпадения.
- Тексты конкурентов в проект не записаны (запуск только для чтения). Для `python3 tools/check_overlap.py` их надо положить в `source/competitors/2026-10-05-emergency/`: копии девяти страниц лежат во временной папке сессии `scratchpad/e1/*.txt` (формат как у Plano: первая строка адрес). DNA и Triple Crown скачать напрямую не удалось.
- Попутно, не для этой страницы: веб-поиск в ответе на "emergency plumber frisco tx" пересказывает про FPP обещание приехать в пределах часа. Фраза стоит на живой главной (source/crawl/pages/home.json) и уйдёт с переездом; на срочной странице её нет.

### Из части 4 (материал Дениса)

- Решения «кейс с потолком в Plano (253 до 255) идёт на первый экран emergency и в текст как история» в файлах проекта нет. В photos/captions-en.csv и docs/pages-plan.md:165 эти файлы отложены под leak detection и Plano. Его нужно записать (CLAUDE.md, колонка pages) и решить, где история рассказана целиком. На Plano и leak detection после этого остаётся одна фраза со ссылкой.
- Спросить Дениса о кейсе с потолком в Plano. Когда пришёл вызов: днём, вечером или ночью? Какой этаж, какая линия (горячая или холодная, диаметр), сколько тёк пинхол? Кто и как перекрыл воду, был ли поиск утечки и чем? Приезжал ли restoration partner? Видит ли он связь с краном на трубе из земли, который лопнул в том же доме 22 сентября, или это просто тот же дом? Пока он сам не скажет, связь не писать.
- Первый экран: клип 253 длится всего 5 секунд, в кадре вещи хозяев и зеркало. Проверить, хватит ли окна кадра только с потолком. Если нет, первым кадром взять 254 (струя из пинхола) и показать Денису оба варианта.
- Спросить, какие кейсы были ночными или вечерними: 253 до 255, 295 (push-fit манифолд, Plano), 280 (гвоздь в гардеробе), 114 и 237 (зимний прорыв в стене), 136 (второй этаж, залил полдома), 274 (service line под тротуаром), 90 (ресторан), морозные 275 до 279.
- Аварийный сбор словами Дениса для этой страницы, без сумм. Заменяет ли он вызов за $49 или идёт сверху? Засчитывается ли в ремонт? С какого часа начинается вечер, как с выходными и праздниками? Сейчас есть только правило CLAUDE.md:45.
- Что Денис говорит людям по телефону до приезда машины, его словами для этой страницы: главный кран, кран у счётчика (с ключом), сток при засоре, электричество у воды. На живой странице стоит «kill the breaker»; одобренные ответы лежат в source/approved-text-edits.md:28-32.
- Газ: на живой странице стоит «smell of gas... then call us». Газовые работы пишутся только по слову Дениса (CLAUDE.md:56). Спросить, что писать про запах газа или убрать это совсем.
- Фото 112: в таблице стоит пометка «confirm he wants it on the site (strong emergency hero)». Подпись «Денис на аварийном вызове, в стене вырвало кран» не его слова. Уточнить у него, что на фото и нужно ли оно на этой странице.
- Вечерний вызов 297 до 300 (Frisco по месту) отложен и для страницы Frisco. Если история рассказана здесь, на Frisco остаётся только ссылка. Страница Frisco в v4 закрыта и меняется только по его слову.
- 136 и 235 (Plano, второй этаж, залил полдома) это не четвёртая история Plano (188, 189). Не путать, и не рассказывать одну работу на двух страницах.
- Марку push-fit (в диктовке назван бренд) в тексте не называть без решения Дениса: в подписях её нет. Его слова, что такой фитинг нельзя в закрытую стену, это мнение, а не правило кода. Про пресс-фитинг 252 тоже никакого общего правила.
- Фото 116 и 117 подписаны одинаково: брать одно из двух. 237 обрезать (пакет со штрихкодом, марка аккумулятора), у 238 брать окно без двора с вещами. Фото 118 уже стоит на /top-emergency-plumber-calls-frisco/.
- Когда Денис подтвердит раскладку, поставить emergency в pages у 253 до 255 в photos/captions-en.csv и заново собрать docs/material-from-denys.md (python3 tools/material_list.py).

### Из части 5 (отзывы)

- Gerardo и Mark Y уже стоят на этой странице тестового сайта (site-reviews.json). Оставить их и добавить кандидатов из 5.2 или заменить, решает чат. Если оставить обоих, Ahmed J. (4am) и Frank D. (душ) повторяют тему Mark Y.
- Kevin N., Jaime D., Matt M., Stacie B., alex p, Phillip Potter предложены кандидатами в нескольких городских брифах от 3 октября (Little Elm, The Colony, Prosper, Lewisville, Celina, Carrollton, Allen, McKinney). Один человек стоит на одной странице: нужно решить, какой странице кого отдать, пока городские страницы не написаны.
- Jim Henderson стоял на старой странице Plano. На новой Plano его нет, по site-ledger.md он свободен. Правило черновика от 1 октября «никого со старого сайта» относилось к подбору тогда; нужно ли согласие Дениса, решает чат. Уровень Local Guide у него в CSV не записан (бриф Plano: на живой странице стоял Level 2), перед постановкой его читают в профиле.
- Правило «отзыв говорит о компании, а не о Денисе по имени» Денис дал для городских страниц (Frisco, 2 октября). На страницах услуг нового сайта отзывы с его именем стоят (Saman Attar, KD, Derek Gordon). Из семи кандидатов имя Дениса есть у пяти; без имени Kevin N. и Jaime D.
- Отзывы со словами "plumber near me" (Vlad Ezhov, Mohaimen Kadhim, funny warner f, Michael Shephard, Inna Kravchenko). Денис 1 октября велел заменить Yulia B как SEO-фразу, 2 октября убрал "best" и "near me" с Frisco, но разрешил Ann Crawford (с "I googled Plumber near me") для expansion tank. Для аварийной страницы общего решения нет: если чат захочет такой отзыв (у Vlad Ezhov и Mohaimen Kadhim сильные ночные истории с водонагревателем), его спрашивают у Дениса.
- Elnard KA пишет "North Dallas". CLAUDE.md запрещает эти слова в тексте и разметке сайта, а правило 11 запрещает править отзыв. Можно ли такой отзыв ставить вообще, решает Денис, если чат захочет его взять (он ближе к странице PRV).
- Возможные пары одного человека: Amy V. (Thumbtack) и Amy Van (Google, старая Allen), Victoria N. (Thumbtack) и Victoria Nwanegbo (Google, старая McKinney), Chris V. (Thumbtack, кандидат 4) и Chris Volpe (Google, ноябрь 2024, "We've used him a few times"). Если Chris V. пойдёт на страницу, стоит уточнить у Дениса, не один ли это клиент.
- Dawson And Kelly M. называет Plano: по правилу 11 место ему на странице Plano, а там уже четыре отзыва и страница закрыта. На аварийную страницу его не ставить.

### Из части 7 (FAQ)

- Выбрать для страницы 5 до 7 вопросов (правило 8) из тех, что могут остаться (живые 2, 3 или кандидат 1, 4, 5) и кандидатов 7.3. Перед записью снова прогнать проверку на повторы: города Little Elm, The Colony, Prosper, Lewisville и другие по плану переписываются раньше услуг, их FAQ поменяется. Скрипт: scratchpad/e5/faq.py, полный список сайта: scratchpad/e5/faq-site-list.md.
- Кандидат 2 и живой вопрос 2: спросить у Дениса, ночная плата идёт вместо $49 или сверху, засчитывается ли она в ремонт, берётся ли она, если ремонт оказался мелким. На главной сказано, что $49 действует "During regular business hours".
- Кандидат 1: какие случаи ждут до утра. Списки "Call tonight" и "This can wait until morning" стоят в старом тексте, их источник в проекте не записан (в старом тексте есть, например, водонагреватель, который не течёт, "unless there is a baby or someone elderly in the house").
- Кандидат 4: прочищают ли главную линию ночью, тросом или цепью, ставят ли камеру ночью. Ответ без времени приезда; про прочистку одна фраза и ссылка на /clogged-drain-cleaning-frisco-plano/.
- Кандидат 5: что Денис говорит хозяину про газовый кран у бака и автомат электрического бака, сливать ли бак. Одобренный ответ "No hot water" уже говорит закрыть холодный кран сверху.
- Кандидат 7: делает ли FPP вообще что-то по газу (CLAUDE.md: gas line work unless Denys confirms) и как он хочет ответить на запах газа. Старая фраза "then call us" читается как выезд по запаху газа. Название газовой компании ставить только по официальному источнику.
- Кандидат 8: ставят ли ночью временное решение (заглушка, обвод) и приходят ли за ремонтом днём; как тогда считается ночная плата.
- Кандидат 9: выставляет ли FPP счёт страховой напрямую, говорит ли с adjuster. Что покрывает страховка, не пишем.
- Кандидат 10: что Денис советует при замёрзшей, но целой трубе (открыть кран, закрыть главный, греть или нет). В диктовках этого нет; фраза старого текста "open a faucet at the lowest point in the house to drain the pressure" без источника.
- Кандидат 11: что Денис советует при провисшем мокром потолке. В диктовках этого нет.
- Кандидат 12: отвечают ли ночью на текст так же, как на звонок (CLAUDE.md: звонок звонит у всех, "also texts").
- Если в FAQ или в тексте пойдёт речь о кране, который не поворачивается: замороженный гайд перекрытия воды советует закрыть воду ключом в коробке счётчика, а по официальным фактам Little Elm (бриф Little Elm, пункт 13) хозяин сам на счётчике воду не закрывает. Без слова Дениса совет про ключ к счётчику не писать.
- Блок "What is happening right now?" той же страницы уже даёт ответы про воду на полу, горячую воду, засор канализации и давление (source/approved-text-edits.md). Вопросы FAQ не должны повторять эти ответы.

### От Claude Code

- Фраза блока «A quarter turn closes the valve» под рисунком крана не поставлена: главный кран никогда не называется quarter turn valve (правило Дениса от 1 октября 2026), а в старых домах это задвижка на много оборотов, и хозяин прочитал бы четверть оборота как достаточную. Стоит «Tap the handle to close the valve.». Решает Денис.
- Помощник по материалу не нашёл в файлах проекта решения о потолке на первом экране, потому что писал до записи: с вечера 5 октября оно записано в CLAUDE.md, в план, в журнал и в таблицы архива (253 до 255 отложены и для страницы emergency).
- Копии девяти страниц конкурентов лежат в source/competitors/2026-10-05-emergency/ для `python3 tools/check_overlap.py source/emergency-text-v1.md source/competitors/2026-10-05-emergency`.

## Сомнения помощников

Что каждый помощник не смог проверить или решил сам.

### Из части 1 и 2 (живая страница, Search Console)

- Решения Дениса от 5 октября снять фото фургона с этой страницы я в файлах проекта не нашёл: искал в docs/journal.md, docs/pages-plan.md, docs/new-material.md, exports/handoff и source/dictation. Его снятие со страницы Plano записано в source/plano-text-v1.md. Факт про страницу emergency я взял из задания брифа. На тестовом сайте фото пока стоит.
- Группы в 2.2 считал я сам. Каждый запрос попадает в одну группу по первому подходящему признаку, место усреднено с весом по показам. Чужие места взяты из списка заметки (emergency-gsc-set-aside.md) и моего короткого списка. Какие-то чужие места у главной могли остаться в группах, например "same day plumber cedar flat" с 34 показами. На итоги страницы это не влияет: они сходятся с заметкой (206 · 8,947 · 1 и 915 · 91,603 · 4).
- Что текст и FAQ на тестовом сайте совпадают с живыми слово в слово, взято из заметки от 3 октября. Сам я сверил только title, description, H1, список H2, og:title и отсутствие фразы "emergency plumbing services".
- Ссылки на страницу (41 в тексте, меню на 62 страницах) посчитаны в заметке по краулу живого сайта. На тестовом сайте главная, Plano и Frisco переписаны, поэтому их анкоры уже другие. Ссылки на тестовом сайте целиком я не пересчитывал.

### Из части 3 (конкуренты)

- Semrush даёт выдачу Google по США без места и без блока с картой; дата обновления базы в ответе не указана. Веб-поиск не Google. Что видит человек во Frisco или Plano, не проверено.
- DNA и Triple Crown прочитаны только инструментом пересказа (прямое скачивание закрыто Cloudflare): их title, H1, число слов и список FAQ могут быть неточны.
- Число слов примерное: скрипт считал от H1 до конца FAQ, вместе с баннерами и короткими отзывами внутри.
- Что фото с настоящих работ нет, сказано по подписям картинок и их числу, не по просмотру каждой картинки.
- Адрес TAB как почтовый ящик и сайты одного города как сбор звонков: мои выводы по виду адреса, названию и шаблону.
- Berkeys и TAB ссылаются на tdlr.texas.gov (страница Berkeys отдаёт 404), GPS на сайт TSBPE. Перешло ли лицензирование сантехников от TSBPE к TDLR, я не установил: поиск нашёл только предложение комиссии Sunset 2018 года. CLAUDE.md называет TSBPE в hasCredential; стоит проверить отдельно, прежде чем выбирать официальную ссылку.
- Местные утверждения конкурентов (жёсткость воды цифрой у Roto-Rooter, годы постройки кварталов, где стоит главный кран) не проверены и в наш текст идти не могут.

### Из части 4 (материал Дениса)

- Решение Дениса от 5 октября (потолок Plano на первый экран emergency) взято только из задания. В CLAUDE.md, docs/journal.md, docs/pages-plan.md, source/dictation/2026-10-05-plano-photos.md и exports/handoff записи я не нашёл.
- Фраза «время вызова не записано» основана на файлах проекта. В переписке Дениса с чатом это время могло прозвучать, но в файлы не попало.
- source/dictation/2026-10-03-plano.md это запись чата, а не дословные слова Дениса. Факты про restoration partner в Plano (сушат, утеплитель, страховая) идут оттуда.
- Кадр 183 стоит на главной у истории «One clog, the whole house». Что это та же работа, Денис не говорил: в tools/export_home_text.py это иллюстрация.
- 116, 117, 118, 119 и 120 сложены в одну работу с 114, 237 и 238 по заметкам («сняты подряд 22 февраля 2025»). Денис рассказал работу целиком по 237 и 238.
- Цифра «33 поста и гайда» для фото 112 посчитана мной по списку страниц в docs/material-from-denys.md:1768.
- Длина раздела около 11 990 знаков, по счёту Python вместе с разметкой Markdown.

### Из части 5 (отзывы)

- Тексты взяты из reviews/all-reviews.csv; живьём на Google, Yelp и Thumbtack они не сверялись (браузер в этом задании запрещён). Живая сверка 3 октября была только для двенадцати отзывов главной.
- Из-за лимита в 8,000 знаков полные тексты даны только для семи ранжированных отзывов; у запаса в 5.3 и у отзывов из 5.4 и 5.5 полного текста в разделе нет, он есть в all-reviews.csv. Восьмой кандидат (Frank D.) перенесён в запас ради лимита.
- Поиск шёл по словам (emergency, night, weekend, Sunday, burst, flood, ceiling, after hours и т.п.) и по виду работы Thumbtack "Emergency Plumbing". Отзыв об аварии, описанной без таких слов, мог не попасть в список.
- CLAUDE.md говорит, что 85 отзывов Thumbtack это копии Google, а в CSV помечено только 10. Для всех Thumbtack из 5.2 и 5.3 проверена метка "Hired on Thumbtack" в raw/thumbtack-reviews.json, значит это не копии; для остальных строк архива это не проверялось.
- Порядок в 5.2 и пометки «звучит как реклама», «общо», «спорит с правилом платы» это мои выводы, а не решения Дениса.
- Местные гайды Local Guide у Google-кандидатов (Jim Henderson, M. Gibson, Phillip Potter, alex p) в CSV не записаны, подпись по правилу 11 без них не собрать.

### Из части 7 (FAQ)

- Полный список 280 вопросов не уместился в размер части (5,000 до 8,000 знаков): в части только вопросы, близкие к теме emergency, весь список лежит во временной папке сессии scratchpad/e5/faq-site-list.md, а она пропадёт после сессии. Если чату нужен полный список в брифе, его надо приложить отдельным файлом.
- "Почти повтор" и "рядом" это мой вывод по смыслу, а не правило проекта; слово в слово ни один кандидат и ни один живой вопрос на других страницах не стоит.
- Сайт собран 5 октября в 16:51, а source/plano-text-v1.md правился позже (17:47). FAQ Plano в тексте и в сборке совпадают, другие правки после сборки не проверялись.
- У большинства запросов в форме вопроса очень мало показов (от 1 до 17 за 16 месяцев). Кандидаты 9 (страховка), 11 (потолок) и 12 (текст ночью) Search Console не подтверждает, они взяты из темы задания и из фактов CLAUDE.md.
- FAQ конкурентов не смотрели (по заданию их нет), поэтому о том, что кандидаты встречаются на рынке, ничего не сказано.
