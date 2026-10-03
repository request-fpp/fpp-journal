# Water heater repair and replacement: живая страница и Search Console (3 октября 2026)

Страница: https://fppplumbing.com/water-heaters/ . Сейчас не переписывается, текста страницы здесь нет. Откуда данные: краул живого сайта от 30 сентября 2026 (`source/crawl/pages/water-heaters.json`, код `source/crawl/html/water-heaters.html`, остальные 63 страницы там же), новая версия `site/src/content/pages/water-heaters.md` и точечные правки в `tools/build_launch_content.py` и `site/src/data/launch-changes.csv`, Search Console `source/gsc/page-query-3m.csv`, `page-query-16m.csv`, `performance-3m/Pages.csv`, `performance-16m/Pages.csv`, `page-query-coverage.csv`, карта ключей `seo/keyword-map.md` и `keyword-map.csv`, `seo/cannibalization-findings.md`, план `docs/pages-plan.md`, отзывы `reviews/`. Одобренного текста этой страницы в `source/` нет.

Длинные таблицы лежат в `docs/briefs/services/water-heaters/`: `water-heaters-gsc-table-3m.md` и `-16m.md` (все запросы), `water-heaters-gsc-top30.md`, `water-heaters-gsc-headings.md`, `water-heaters-gsc-phrases.md`, `water-heaters-gsc-other-pages.md`, `water-heaters-gsc-cities.md`, `water-heaters-gsc-set-aside.md`, `water-heaters-links-in.md` (ссылки на страницу с остальных 63 страниц). Скрипты, которыми посчитано: `gsc_wh_lib.py`, `gsc_wh.py`, `links.py` в папке scratchpad `services/water-heaters/` (сделаны из `docs/briefs/_shared/gsc_plano_*.py`, оригиналы не тронуты).

Где порядок чисел через точку не подписан, он такой: показы · место · клики.

## Коротко

1. Кормит сейчас (итог Google): 3 месяца 2 клика, 5,582 показа, место 16.5; 16 месяцев 5 кликов, 42,842 показа, место 33.7. Все известные клики: "water heater repair frisco" (1 за 3 мес, 1 за 16) и "water heater replacement frisco" (1 и 2).
2. Место выросло (16.3 за 3 месяца против 36.4 за 13 месяцев до июля), показов стало меньше. Почти половина показов теперь "near me" (29 запросов, 2,555 из 5,151, 0 кликов), а "near me" на странице нет.
3. Нельзя потерять title "Water Heater Repair & Replacement in Plano & Frisco": 40 запросов, 17,338 показов, все 3 клика с известными запросами за 16 месяцев (итог Google 5). "water heater replacement frisco" держит только title (в H1 "Replace", не "Replacement"); "water heater repair frisco" держат title и H1.
4. Точной фразы "water heater repair frisco" на странице нет нигде.
5. Против правил на живой: tankless 3 места в тексте и 2 в схеме (описание узла Service и ответ FAQ в FAQPage), "North Dallas" 1, тире 4, FAQ тегом H3. На новом сайте исправлено.
6. На новом сайте осталось: "same day", "fast", "no waiting" в своих словах; "permit and inspection included" в описании (оттуда и в схеме Service); "gas/electric shutoff" и "earthquake strapping"; expansion tank и T&P valve (тема `/water-heater-repair-frisco-mckinney/`); вопросы FAQ о сроке службы и о хлопках (темы двух гидов); "6-Year, 9-Year & 12-Year" и "warranty level"; случай "One client..." без источника; лозунги.
7. Правило 8: 618 слов против примерно 2,500; H2 в содержимом шесть (седьмой H2 это панель телефонов шаблона), из них два служебные, заголовок FAQ и призыв к срочному звонку (нужно 10 до 16); список симптомов есть (8 пунктов) без ссылок; раздела "если это происходит сейчас" в тексте нет (на новом сайте шаблон даёт боковой блок со ссылками на аварийную страницу и гид по перекрытию воды).
8. Правило 8, дальше: FAQ 3 вместо 5 до 7; ссылки на главную с анкором "plumber near me" нет; ссылок на десять городов в тексте 0; из связанных услуг одна ссылка (`/water-heater-repair-frisco-mckinney/`); внешних авторитетных ссылок нет.
9. Запросы с восемью городами без офиса берут городские страницы и `/water-heater-repair-frisco-mckinney/`; Plano за 3 месяца берёт страница Plano (557 показов, место 1.6, похоже на карточку). Главная за 16 месяцев взяла 6 кликов на запросах о водонагревателе, эта страница 3.
10. Карта ключей отдаёт "water heater repair mckinney" странице `/water-heater-repair-frisco-mckinney/` вторичным ключом. По expansion tank эта страница за 16 месяцев взяла 4,756 показов чужой темы.

## 1. Живая страница

### 1.1. Title, описание, H1, заголовки, объём

| Что | На живой странице |
|---|---|
| Title (62 знака) | "Water Heater Repair & Replacement in Plano & Frisco \| Same Day" |
| Meta description (147 знаков) | "No hot water this morning? Rust in the first draw? Puddle at the base? Licensed plumbers repair or replace same day, permit and inspection included" |
| H1 | "Water Heater Not Working? We Repair & Replace Fast in Frisco" |
| OG title | "Water Heater Repair & Replacement" (не совпадает с title, по техническим правилам должен совпадать) |
| Даты в схеме | опубликована 18 декабря 2024, изменена 30 августа 2026 |

H2 по порядку (в скобках слов в разделе по тексту краула; отдельно стоящие точка и знак тире словами не считаются):

1. "Common Signs Your Water Heater Is Failing" (135)
2. "Water Heater Replacement: 6-Year, 9-Year & 12-Year Options" (73)
3. "Why Water Heaters Leak And Why You Shouldn’t Wait" (98)
4. "We Don’t Just Swap Tanks We Do It Right" (46)
5. "Water Heater Problems [en dash] Common Questions We Hear" (сам раздел пустой, дальше три вопроса тегом H3; на месте пометки в оригинале короткое тире)
6. "Need Emergency Water Heater Help in Frisco, Plano, or McKinney?" (50, вместе с кнопкой "Request Service" и строкой-ссылкой)
7. "980-899-7997 469-998-8999": это не раздел, а панель звонка шаблона, свёрстанная тегом H2 на всех страницах старого сайта

H3: три, все три вопросы FAQ (пункт 1.2).

Объём. Краул считает 618 слов. Это весь текст содержимого от H1 до конца, с заголовками, кнопкой и строкой-ссылкой; меню и подвал в счёт не входят. Вступление под H1 53 слова, FAQ, вопросы вместе с ответами, 98 слов (краул, который делит по пробелам и считает два знака тире, дал бы 100). До отметки 2,500 не хватает около 1,880 слов.

### 1.2. FAQ: три вопроса, слово в слово

Все три стоят тегом H3 внутри раскрывающегося списка Elementor (`summary` с классом `e-n-accordion-item-title`). Ответы есть в коде страницы обычным текстом. Схема FAQPage на живой странице совпадает с текстом слово в слово, тире включительно.

| № | Вопрос (H3) | Ответ на живой странице | Где ещё на сайте |
|---|---|---|---|
| 1 | "Why is my water heater making loud popping sounds?" | "That’s usually sediment buildup inside the tank. It traps water, which then boils and makes noise. A flush might help [em dash] or it could be time to replace." | Слово в слово нигде. Тема принадлежит гиду `/plumbing-guide/water-heater-making-noise-tips-2026/` (title "Why Is My Water Heater Making Noise?..."; ключ по карте "water heater making noise") |
| 2 | "Do I need to replace my water heater if it’s leaking?" | "If the tank itself is leaking, yes [em dash] it can’t be repaired. But if it’s just a fitting or valve, we might be able to fix it." | Слово в слово нигде. Близкие: "Should I repair a leaking water heater or just replace it?" (пост `/blog/plumber-frisco-water-heater-replacement/`), "Should I repair my water heater or replace it?" (`/plumber-celina-tx/`), "Is it better to repair or replace an old water heater?" (гид о сроке службы), "Is it cheaper to repair or replace a water heater?" (гид о стоимости) |
| 3 | "How long do water heaters last?" | "Most standard water heaters last 6[en dash]12 years, depending on the model, installation, and maintenance. Tankless units can last longer." | Это title и H1 гида `/plumbing-guide/how-long-do-water-heaters-last-guide/` (ключ по карте "how long do water heaters last"); тот же заголовок в ленте `/plumbing-guides-tips/` и в навигации двух гидов. Близкие: "How long does a water heater usually last in Texas?" (пост Frisco), "How long do water heaters usually last in North Texas?" (сам гид) |

На месте пометок в оригинале длинное и короткое тире. Ещё близкое: на `/water-heater-repair-frisco-mckinney/` стоит вопрос "What’s the difference between 6-year and 12-year water heaters?", та же тема, что H2 номер 2 этой страницы.

### 1.3. Отзывы

На живой странице отзывов нет: ни блока, ни карточек, ни имён (проверены текст краула и сохранённый код страницы). Сверять с `reviews/all-reviews.csv` нечего.

Для справки о новой версии: шаблон ставит блок отзывов из `reviews/site-reviews.json`, за `/water-heaters/` там двое, оба в `reviews/site-ledger.md` только на этой странице, тексты совпадают с архивом знак в знак. Biswa Senapati (Google, профиль Plano, 27 декабря 2024, "★★★★★ · Local Guide Level 2 · December 2024 · Google": замена водонагревателей, городские разрешения, "FFP Plumbing" с опечаткой) и Igor B. (Yelp, 24 марта 2025, "★★★★★ · Yelp · March 2025": "I had a leaking boiler, and Denys did a fantastic job replacing it."; в `reviews/proposed-placement.md` записано, что вид работы, обычный бак или нет, не подтверждён; boiler в запросах этот отчёт откладывает как не нашу услугу, раздел 2.7). Отзыв Steve Fredrickson (Google, Plano, 8 ноября 2024, на старом сайте стоит на главной) по CLAUDE.md и `docs/pages-plan.md` подходит этой странице; на новом сайте его нет ни на одной странице.

### 1.4. Фото

| Файл | Alt | Что это |
|---|---|---|
| `/wp-content/uploads/2025/05/water-heater-replacement-frisco-466x1024.jpg` (полный файл 582 на 1280) | "Replacement gas water heater in Plano" | Единственное фото страницы и OG картинка. Я его открыл: новый газовый бак A. O. Smith Signature 100 на подставке в нише, сверху расширительный бак на холодной линии, вытяжная труба, жёлтая гибкая газовая подводка с биркой, слив T&P пластиковой трубой, поддон под баком, инструкция в пакете на баке. Похоже на настоящую работу. На баке читается наклейка EnergyGuide "$330" (это оценка годовой стоимости энергии, не наша цена). |
| `/wp-content/uploads/2024/12/fpp-logo-1-1024x563.png` (2 раза) | "FPP Plumbing Logo" | Логотип в шапке и в подвале |
| знак BBB с seal-dallas.bbb.org | "FPP Plumbing, LLC BBB Business Review" | Подвал |

Что видно по фото:

- Имя файла говорит Frisco, alt говорит Plano. В `photos/index.csv` и `photos/captions-en.csv` этого файла нет, город по файлам проекта не подтвердить (то же записано в `docs/plano-brief-2026-10-03.md`).
- Фото грузится лениво (`data-src`), хотя стоит у начала страницы.
- Других фото с работ и видео нет.

### 1.5. Ссылки

Со страницы в тексте одна внутренняя ссылка: "Need help after hours? Visit our Emergency Water Heater Repair page." на `/water-heater-repair-frisco-mckinney/`, и кнопка "Request Service". Ссылки на главную с анкором "plumber near me" нет (на главную ведёт только логотип). Десять городов только в меню, три раза, плюс "Frisco Office" и "Plano Office" в подвале; в тексте ни одного. Связанные услуги (PRV, expansion tank, leak detection, slab leak), аварийная страница и гид по перекрытию воды из текста не связаны. Внешних ссылок в тексте нет; в шаблоне соцсети, `tel:`, "Found us" (https://share.google/uosRA41P1LGbG7orc), почта, знак BBB.

На страницу (таблица в `water-heaters-links-in.md`): меню на каждой странице, анкор "Water Heater Repair & Replacement". В тексте 30 ссылок с 23 страниц: все десять городских (почти везде "water heater repair"), главная (плитка услуги и "Get help here: Water Heater Repair"), `/water-heater-repair-frisco-mckinney/`, `/prv-replacement-frisco-plano/`, `/emergency-plumbing-services/`, пост `/blog/plumber-frisco-water-heater-replacement/` (голый адрес), хаб гидов и семь гидов. Остальные сервисные страницы в тексте на неё не ссылаются.

### 1.6. Что идёт против CLAUDE.md, дословно

"Новый сайт" значит файл `site/src/content/pages/water-heaters.md` после точечных правок.

**Услуги, которые FPP не делает или не заявляет**

- Вступление: "Whether it’s gas or electric, tank or tankless we fix it fast." Новый сайт: исправлено на "Whether it’s gas or electric, we fix it fast."
- Список "We install:": "Tankless systems". Новый сайт: убрано.
- Ответ FAQ 3: "Tankless units can last longer." Новый сайт: убрано.
- Схема Service: "Tank and tankless systems. Same-day service and expert installation." Новый сайт: схема своя (`site/src/lib/schema.ts`), tankless нет.
- H2 номер 2: "we always install to code with a new pan, gas/electric shutoff, expansion tank (if needed), and earthquake strapping where required." Новый сайт: стоит. Газовый кран: газовые работы не заявляются без слова Дениса; "earthquake strapping" общий текст, не из диктовок.

**Цены.** Долларов в своём тексте нет. В описании "permit and inspection included": обещание о составе цены, а правила говорят о цене только $49 и "цена до начала работ". Новый сайт: стоит и попадает в описание узла Service в схеме.

**Сроки гарантии.** H2 "Water Heater Replacement: 6-Year, 9-Year & 12-Year Options" и "We’ll help you pick the right size and warranty level...". Это классы заводской гарантии бака, не наша гарантия на работу, но цифры гарантийных сроков стоят; правило проекта: ни один срок гарантии не публикуется, пока Денис не решит по странице. Новый сайт: стоит.

**Скорость и время в своих словах** (часов и минут нет). Title "... | Same Day"; описание "Licensed plumbers repair or replace same day, permit and inspection included"; H1 "We Repair & Replace Fast in Frisco"; вступление "Whether it’s gas or electric, we fix it fast." (так после правки) и "Licensed, local, and available same-day even on weekends."; закрывающий блок "We’ll get your info fast and send a licensed plumber without the usual games, no call centers, no waiting." ("no waiting" читается как обещание). Новый сайт: всё стоит.

**Другие города, "North Dallas", схема**

- Вступление: "At FPP Plumbing, we help homeowners across Frisco, Plano, McKinney, and North Dallas with urgent water heater repairs and full replacements." Новый сайт: "the North Dallas suburbs".
- Схема Service: areaServed "Frisco", "Plano", "McKinney", "Allen", "Little Elm", "Prosper", "Lewisville", "Highland Park", "University Park", "Fairview"; адрес "4848 Grand Gate Way", Frisco, 75034 (старый адрес компании, не адрес офисов Frisco и Plano; так он описан в `docs/seo-baseline-live-2026-10-01.md`); url "https://fppplumbing.com/water-heater-repair-replacement/". Схема Organization: "Texas Master Plumber License M-44816". Новый сайт: схема своя, десять городов и Park Cities, provider на `#organization`, Fairview и старого адреса на Grand Gate Way нет.

**Граница с темами других страниц** (правило 9, `seo/keyword-map.md`). Новый сайт: всё стоит.

- "Expansion tank replacements" (список "We install:"), "Add or replace expansion tank if required", "Test pressure/temperature relief valve": expansion tank и T&P valve принадлежат `/water-heater-repair-frisco-mckinney/` (решение 30 сентября 2026).
- Вопрос FAQ "Why is my water heater making loud popping sounds?": тема гида `/plumbing-guide/water-heater-making-noise-tips-2026/`.
- Вопрос FAQ "How long do water heaters last?": главный ключ гида `/plumbing-guide/how-long-do-water-heaters-last-guide/`.
- H2 "Need Emergency Water Heater Help in Frisco, Plano, or McKinney?" и "No hot water? Tank leaking bad? We’re ready 24/7 even nights and weekends.": title соседней страницы "Emergency Water Heater Repair in Frisco & McKinney | 24/7 Help" (по карте её заголовки после запуска перенацеливаются).
- "Even if your attic unit has a drain pan and line, we’ve seen them overflow or clog, and that water ends up pouring through ceilings and walls.": перекликается с разделом "Attic Water Heaters and Texas Summer..." той же соседней страницы.

**Телефоны в тексте**: нет; номера только в панели звонка шаблона, свёрстанной тегом H2. **Owner**: слова нет. **FAQ тегом заголовка**: три вопроса H3; на новом сайте `FAQList.astro` ставит вопрос жирным в `summary`.

**Тире.** H2 "Water Heater Problems [en dash] Common Questions We Hear" (новый сайт: двоеточие); "A flush might help [em dash] or it could be time to replace." (запятая); "If the tank itself is leaking, yes [em dash] it can’t be repaired." (двоеточие); "6[en dash]12 years" ("6 to 12"). На новом сайте остались диапазоны через дефис "40-50 gallon" и "8-10+ years old" и места, где тире когда-то убрали без замены и предложение склеилось: "...from licensed plumbing supply houses not big box stores.", "Leaks usually start slow a small drip here, puddle there.", "We Don’t Just Swap Tanks We Do It Right", "available same-day even on weekends", "We’re ready 24/7 even nights and weekends."

**Лозунги, наполнитель, случай без источника** (новый сайт: всё стоит)

- "We Don’t Just Swap Tanks We Do It Right"; "Clean, safe, code-compliant install, no shortcuts."; "without the usual games, no call centers, no waiting"; "Not all water heaters are built the same."; "Don’t wait until it ruins your drywall or insulation. Let us swap it out before it becomes a flood."
- Тройки: "Licensed, local, and available...", "leaking, smelling weird, or making popping noises", "Clean, safe, code-compliant". Риторические вопросы в начале: "Hot water gone?", "No hot water? Tank leaking bad?".
- "One client had a slow leak for weeks before noticing the ceiling sagged.": такого случая нет ни в диктовках, ни в других файлах Дениса (правило 3).
- "the anode rod ... it’s supposed to catch calcium and extend the life of your tank": по сути неточно, анод защищает бак от коррозии.
- Цифры "40+ gallons", "8-10+ years old", "6 to 12 years" не из файлов Дениса.

### 1.7. Что на живой странице стоит сохранить как суть

Настоящей полевой глубины на странице мало, но есть живые места:

- Список симптомов (8 пунктов): "Leaking from the tank or underneath", "Rust-colored or smelly water", "Popping, banging, or rumbling noises", "Hot water running out too fast", "Pilot won’t stay lit (on gas units)", "Higher electric or gas bills for no reason", "Visible corrosion around fittings or valves", "Sulfur smell or “rotten egg” smell near the heater". Основа под список "симптом и ссылка" по правилу 8.
- Чердак: "Even if your attic unit has a drain pan and line, we’ve seen them overflow or clog, and that water ends up pouring through ceilings and walls." Перекликается с диктовкой Дениса о баке на чердаке во Frisco, который лопнул ночью (видео 173, `source/dictation/2026-10-02-frisco-additions.md`).
- Что входит в замену: "Install new flex lines and shutoffs", "Replace pan and drain line if needed", "Secure the tank with proper strapping", "Haul away your old unit", "Check for city code compliance". Под это есть диктовка о том, на что смотрит инспектор Frisco (`source/dictation/2026-10-02-frisco-reserve-for-service-pages.md`, раздел для этой страницы).
- "We install professional-grade models from licensed plumbing supply houses not big box stores." Перекликается с фактом из CLAUDE.md о марках (Bradford White в первую очередь, ещё State, A. O. Smith, Rheem).
- "Units in garages, closets, attics, or outside" и "If the tank itself is leaking, yes ... But if it’s just a fitting or valve, we might be able to fix it." Простая правда о ремонте и замене.

### 1.8. Чем новая версия отличается от живой

На новом сайте стоит старый текст с точечными правками. Одобренного текста этой страницы в `source/` нет; в `docs/pages-plan.md` страница в группе 3, номер 6 ("Старый текст"). Применённые правки (`site/src/data/launch-changes.csv`, строки 611 до 618):

1. tankless убран во вступлении, в списке "We install:" и в ответе FAQ 3;
2. "North Dallas" стал "the North Dallas suburbs";
3. тире заменены: в H2 номер 5 двоеточием, в ответах FAQ 1 и 2 запятой и двоеточием, "6[en dash]12" стало "6 to 12".

Что даёт шаблон нового сайта сверх текста: FAQ жирным текстом, не заголовками; схема Service с `provider` на `#organization` и десятью городами плюс Park Cities (имя узла берётся из H1, описание из meta, то есть "same day" и "permit and inspection included" попадают в схему); блок отзывов (Biswa Senapati, Igor B.); боковой блок "что делать сейчас" со ссылками на аварийную страницу и гид по перекрытию воды; крошки, где последний пункт назван "Water Heater Repair & Replacement in Plano & Frisco" (часть title до "|"). Title, описание, H1, H2 содержимого (в H2 номер 5 только тире заменено двоеточием; панели телефонов тегом H2 нет), фото и единственная ссылка в тексте те же, что на живой странице.

## 2. Search Console

### 2.1. Итоги за 3 и 16 месяцев

| Период | Запросов | Клики | Показы | Место по показам | Итог Google с запросами, которые он скрывает: клики · показы · место | Доля известных: клики · показы |
|---|---|---|---|---|---|---|
| 3 месяца (1 июля до 28 сентября 2026) | 102 | 2 | 5,151 | 16.3 | 2 · 5,582 · 16.46 | 100% · 92% |
| 16 месяцев (31 мая 2025 до 28 сентября 2026) | 273 | 3 | 41,069 | 33.9 | 5 · 42,842 · 33.74 | 60% · 96% |

13 месяцев до июля 2026 (16 месяцев минус 3; каждый запрос трёхмесячной выгрузки есть и в шестнадцатимесячной): известные запросы 1 клик, 35,918 показов, место 36.4; по итогу Google 3 клика, 37,260 показов.

По группам запросов:

| Группа | 3 мес: запросов · клики · показы · место | 16 мес: запросов · клики · показы · место |
|---|---|---|
| Frisco | 27 · 2 · 2,182 · 19.8 | 56 · 3 · 25,823 · 28.8 |
| без города | 55 · 0 · 2,861 · 13.2 | 90 · 0 · 6,631 · 19.8 |
| Plano | 8 · 0 · 46 · 37.2 | 44 · 0 · 6,286 · 58.4 |
| другой из десяти | 1 · 0 · 1 · 99.0 | 58 · 0 · 1,938 · 69.6 |
| чужое место | 7 · 0 · 24 · 47.5 | 20 · 0 · 291 · 46.0 |
| бренд (fpp plumbing) | 1 · 0 · 33 · 1.9 | 1 · 0 · 91 · 3.4 |
| не про услугу | 3 · 0 · 4 · 7.0 | 4 · 0 · 9 · 7.0 |

За 3 месяца 50 запросов на местах выше 10 и до 20 включительно дают 3,961 показ из 5,151; за 16 месяцев 142 запроса ниже 50 места дали 12,449. Запросы с heater или hot water за 3 месяца: 88, 4,775 показов, 2 клика (вместе с "water heating repair near me" 89 и 4,778).

Второй счёт. Итоги посчитаны тремя способами: модулем csv, разбором строк без модуля csv и командой awk. Все три дали 102 запроса, 2 клика, 5,151 показ, место 16.35 и 273 запроса, 3 клика, 41,069 показов, место 33.87; те же числа стоят в `page-query-coverage.csv`. Суммы групп, оценок слов, хозяев и корзин мест сходятся с итогами. Руками сверены строки "water heater repair frisco" (16 мес: 5,089 · 15.45 · 1) и "water heater replacement frisco" (3 мес: 310 · 6.97 · 1).

### 2.2. Первые запросы и запросы с кликами

Полные таблицы первых 30: `water-heaters-gsc-top30.md`. Первые 10 каждого периода (показы · место · клики):

| № | 3 месяца | 16 месяцев |
|---|---|---|
| 1 | water heater repair near me: 858 · 13.6 · 0 | water heater repair frisco: 5,089 · 15.4 · 1 |
| 2 | water heater replacement near me: 856 · 13.8 · 0 | frisco water heater repair: 2,593 · 18.5 · 0 |
| 3 | water heater repair frisco: 457 · 13.8 · 1 | expansion tanks repair frisco: 2,510 · 22.4 · 0 |
| 4 | hot water heater repair near me: 337 · 11.3 · 0 | water heater replacement frisco: 2,206 · 11.3 · 2 |
| 5 | water heater replacement frisco: 310 · 7.0 · 1 | water heater repair near me: 2,190 · 17.7 · 0 |
| 6 | frisco water heater repair: 262 · 15.5 · 0 | water heater repair plano: 1,895 · 63.5 · 0 |
| 7 | water heater repair: 219 · 14.4 · 0 | water heater installation frisco: 1,708 · 20.2 · 0 |
| 8 | water heater repair frisco tx: 201 · 30.0 · 0 | tankless water heater repair frisco: 1,633 · 32.9 · 0 |
| 9 | hot water heater repair frisco: 188 · 12.9 · 0 | hot water heater repair frisco: 1,576 · 12.5 · 0 |
| 10 | expansion tanks repair frisco tx: 182 · 41.1 · 0 | water heater replacement near me: 1,508 · 18.3 · 0 |

Первые 30 дают 4,972 показа из 5,151 за 3 месяца и 34,245 из 41,069 за 16 месяцев.

Запросы с кликами, все: "water heater repair frisco" (3 мес 457 · 13.8 · 1; 16 мес 5,089 · 15.4 · 1) и "water heater replacement frisco" (3 мес 310 · 7.0 · 1; 16 мес 2,206 · 11.3 · 2).

Слова живого текста (правило `tools/gsc_page_table.py`, название города считается словом): за 3 месяца все слова стоят у 52 запросов (2,481 показ, 2 клика), частично у 31 (2,528 показов; из них 22 запроса "near me" с 2,452 показами), не наше 9 (114), чужое место 7 (24), не про услугу 3 (4). За 16 месяцев: да 131 (29,361, 3 клика), частично 79 (7,381), не наше 39 (4,027), чужое место 20 (291), не про услугу 4 (9). Слово "service" на странице есть только в кнопке "Request Service", "conventional" нет нигде.

### 2.3. Что держат title, H1, H2 и вопросы FAQ

Заголовок держит запрос, когда все значимые слова запроса (и город) стоят в этом заголовке. Подробно по каждому: `water-heaters-gsc-headings.md`.

| Заголовок | 3 мес: запросов (показы · клики) | 16 мес | Держит только он (без meta), 16 мес | Главные запросы, показы за 16 мес |
|---|---|---|---|---|
| title | 21 (1,621 · 2) | 40 (17,338 · 3) | 20 (6,278) | "water heater repair frisco" 5,089, "frisco water heater repair" 2,593, "water heater replacement frisco" 2,206, "water heater repair plano" 1,895, "water heater repair" 817 |
| meta description | 2 (2 · 0) | 3 (3 · 0) | 2 (2) | "hot water repair" 1, "inspection" 1, "replace it" 1 |
| H1 | 11 (1,244 · 1) | 15 (10,853 · 1) | 0 | "water heater repair frisco" 5,089, "frisco water heater repair" 2,593, "water heater repair" 817, "heater repair frisco" 727, "water heater frisco" 673 |
| H2 "Water Heater Replacement: 6-Year, 9-Year & 12-Year Options" | 4 (4 · 0) | 6 (44 · 0) | 0 | "water heater replacement" 39 |
| Остальные H2 (номера 1, 3, 4, 5) | от 0 до 2 (до 2 · 0) | от 0 до 3 (до 3 · 0) | 0 | только общие ("water heater", "who does water heaters"); H2 номер 4 не держит ничего |
| H2 "Need Emergency Water Heater Help in Frisco, Plano, or McKinney?" | 4 (36 · 0) | 10 (997 · 0) | 1 (1) | "water heater frisco" 673, "frisco water heater" 134, "water heater plano" 95, "water heaters plano" 65 |
| Три вопроса FAQ | 2 или 3 (до 3 · 0) | 3 или 4 (до 4 · 0) | 0 | только общие ("replace it" у вопроса 2) |

Что нельзя потерять:

- В title "Water Heater Repair & Replacement" вместе с "Frisco" и "Plano": на нём держатся оба запроса с кликами. Только title держит "water heater replacement frisco" (2,206 показов, 2 клика), "water heater repair plano" (1,895), "water heater replacement plano" (573), "plano water heater repair" (429), "water heater repair in plano" (409), "heater replacement frisco" (290). Слово "Replacement" в H1 нет ("Replace").
- В H1 "Repair" и "Frisco": вместе с title держат "water heater repair frisco", "frisco water heater repair", "water heater repair frisco tx".
- "Same Day" в title держит мало: "same day water heaters" 19 показов, "same day water heater" 8, "same day water heater replacement" 7, ещё три запроса по 2 до 5 показов. Все запросы со "same day" на странице за 16 месяцев: 20 запросов, 71 показ, 0 кликов.
- Ни один заголовок не держит запросы "near me" (43 запроса, 5,455 показов за 16 месяцев), "hot water heater repair frisco" (1,576), "water heater installation frisco" (1,708; слово installation есть только в ответе FAQ 3). Из запросов этой услуги (хозяин по карте ключей эта страница: 73 запроса и 4,651 показ за 3 месяца, 181 и 31,398 за 16) ни один заголовок не держит 52 запроса и 3,030 показов за 3 месяца, 140 запросов и 14,059 показов за 16 месяцев.

### 2.4. Фраза целиком: первые 20 запросов и запросы с кликами

Полная таблица на 28 запросов: `water-heaters-gsc-phrases.md`. "Точно" значит слово в слово (регистр и знаки не в счёт); "те же слова подряд" значит без in, tx, near me, в том же порядке (правило проектного инструмента).

- Точно на живой странице стоит один запрос из 28: "water heater repair" (title и строка "Need help after hours? Visit our Emergency Water Heater Repair page."). Во вступлении стоит "urgent water heater repairs".
- Оба запроса с кликами, "water heater repair frisco" и "water heater replacement frisco", не стоят на странице ни точно, ни теми же словами подряд. Title разрывает их словами "& Replacement in Plano &", H1 говорит "Repair & Replace Fast in Frisco".
- Теми же словами подряд, если убрать "near me": "water heater repair near me" (title, вступление, закрывающий блок) и "water heater replacement near me" (H2 номер 2).
- Не стоят никак: "frisco water heater repair" (2,593 · 18.5 за 16 мес), "water heater installation frisco" (1,708 · 20.2), "hot water heater repair frisco" (1,576 · 12.5), "hot water heater repair near me" (767 · 16.4), "water heater frisco" (673 · 25.3), "water heater repair plano" (1,895 · 63.5), "water heater replacement plano" (573 · 48.3), "water heater installer near me", "water heater installation near me", "water heater service near me", "hot water heater replacement near me", "frisco tx water heater repair", "water heater repair frisco tx", "water heater replacement frisco tx".
- Остальные в списке: expansion tank (3 запроса), tankless (3), "conventional water heaters frisco" и "... frisco tx", "heater repair frisco".

### 2.5. Другие страницы сайта на запросах этой услуги

Полные списки: `water-heaters-gsc-other-pages.md`. Запрос услуги: есть heater или hot water, и по карте ключей хозяин эта страница (без tankless, expansion tank, цены, срока службы, шума, McKinney repair).

Где другая страница стоит выше, берёт больше показов или показана вместо этой (строк · показы · клики · место):

| Страница | 3 месяца | 16 месяцев |
|---|---|---|
| `/` (главная) | 39 · 216 · 0 · 39.6 | 201 · 9,101 · 6 · 16.5 |
| `/plumber-frisco-tx/` | 49 · 2,180 · 1 · 3.7 | 65 · 6,786 · 1 · 26.0 |
| `/water-heater-repair-frisco-mckinney/` | 14 · 181 · 0 · 17.8 | 106 · 6,537 · 0 · 61.9 |
| `/plumber-plano-tx/` | 102 · 2,293 · 2 · 2.1 | 108 · 2,505 · 2 · 8.4 |
| `/plumber-little-elm-tx/` | 14 · 740 · 0 · 18.9 | 19 · 3,556 · 0 · 48.0 |
| `/plumber-lewisville-tx/` | 5 · 6 · 0 · 30.2 | 21 · 3,694 · 0 · 65.2 |
| The Colony, Allen, Carrollton, Celina, Prosper (городские) | от 17 до 324 показов каждая | от 911 до 2,039 каждая |
| `/plumbing-guide/water-heater-replacement-cost-2026/` | 80 · 100 · 0 · 3.8 | 171 · 275 · 0 · 5.1 |

Самые крупные строки:

- "water heater repair": здесь 219 · 14.4 (3 мес), у `/plumber-frisco-tx/` 894 · 3.2, у `/plumber-plano-tx/` 510 · 2.3; за 16 мес главная 752 · 1.1, Frisco 1,525 · 6.0, здесь 817 · 23.2.
- "water heater installation": эта страница не показана; 3 мес Frisco 490 · 1.5, Plano 162 · 1.2; 16 мес Frisco 819 · 2.2, главная 299 · 1.3. "water heater replacement": 3 мес здесь нет, Plano 283 · 3.7; 16 мес здесь 39 · 35.4, главная 217 · 2.4 и 1 клик.
- "water heater repair near me" (здесь 858 · 13.6, 3 мес): выше Frisco 157 · 4.3, Celina 72 · 8.8, Prosper 46 · 11.8. "water heater repair frisco tx" (16 мес): здесь 520 · 59.9, Frisco 1,482 · 47.7, соседняя страница 949 · 62.6.
- Plano: "plano water heater replacement" 16 мес главная 248 · 4.2, здесь 126 · 68.4; "water heater installation plano" главная 227 · 15.2 и 1 клик, здесь 507 · 68.5.

Места 1 до 3 страниц Frisco и Plano по запросам без своего города по правилу проекта (`tools/cannibalization_report.py`) считаются показами карточки Google: кнопка сайта карточки ведёт на страницу офиса. Главная стоит на 1.0 до 1.5 по общим "water heater repair", "water heater installation", "water heater service near me"; откуда эти показы, по выгрузке не проверить. Все клики сайта на запросах о водонагревателе за 16 месяцев: главная 6, гид о стоимости 3, эта страница 3, Plano 2, Frisco 1.

Обратное: эта страница показана по чужим запросам (запросов · показы, 3 и 16 мес):

- `/water-heater-repair-frisco-mckinney/`, expansion tank: 5 · 321 и 11 · 4,756. "expansion tanks repair frisco" за 16 мес здесь 2,510 · 22.4, у хозяина 2,145 · 32.6; "expansion tanks repair frisco tx" за 3 мес здесь 182 · 41.1, у хозяина 324 · 6.8.
- Та же страница, вторичный ключ "water heater repair mckinney": 0 и 4 · 452 (сам запрос здесь 229 · 73.1).
- tankless, никому: 7 · 99 и 24 · 3,704 ("tankless water heater repair frisco" 1,633 · 32.9).
- boiler, furnace, heating, pool heater, gas line, commercial, никому: 2 · 15 и 15 · 323.
- garbage disposal, water lines, городские страницы: 0 и 8 · 76. Чужие места: 7 · 24 и 19 · 254. Бренд "fpp plumbing": 1 · 33 и 1 · 91.

### 2.6. Водонагреватель с каждым из десяти городов

Запросы с heater или hot water и названием города, без tankless, expansion tank и не наших услуг. В ячейке: эта страница (показы · место · клики) / страница с наибольшими показами (показы · место). Все страницы и запросы по каждому городу: `water-heaters-gsc-cities.md`.

| Город | 3 мес: все страницы, показы | 3 мес: эта / первая | 16 мес: все страницы, показы | 16 мес: эта / первая |
|---|---|---|---|---|
| Frisco | 2,304 (2 клика) | 1,866 · 17.0 · 2 / эта | 34,114 (3 клика) | 18,860 · 25.2 · 3 / эта |
| Plano | 610 | 31 · 42.2 · 0 / `/plumber-plano-tx/` 557 · 1.6 | 9,163 (3 клика) | 5,150 · 63.6 · 0 / эта; главная 2,582 · 17.2, 3 клика |
| McKinney | 36 | нет / `/water-heater-repair-frisco-mckinney/` 33 · 22.5 | 6,908 | 917 · 73.1 / `/water-heater-repair-frisco-mckinney/` 5,683 · 62.1 |
| Allen | 29 | нет / `/plumber-allen-tx/` 29 · 15.3 | 2,138 | 9 · 49.4 / `/plumber-allen-tx/` 2,031 · 56.2 |
| Prosper | 262 | нет / `/plumber-prosper-tx/` 198 · 14.4 | 975 | 20 · 64.5 / `/plumber-prosper-tx/` 785 · 38.1 |
| Celina | 106 | нет / `/plumber-celina-tx/` 90 · 19.4 | 1,284 | 4 · 73.8 / `/plumber-celina-tx/` 1,256 · 29.1 |
| Little Elm | 740 | нет / `/plumber-little-elm-tx/` 740 · 18.9 | 4,818 | 123 · 65.3 / `/plumber-little-elm-tx/` 3,555 · 48.0 |
| The Colony | 113 | нет / `/plumber-the-colony-tx/` 97 · 22.1 | 2,683 | 252 · 74.1 / `/plumber-the-colony-tx/` 2,038 · 59.8 |
| Carrollton | 18 | нет / `/plumber-carrollton-tx/` 17 · 23.4 | 1,566 | нет / `/plumber-carrollton-tx/` 1,564 · 60.2 |
| Lewisville | 5 | нет / `/plumber-lewisville-tx/` 5 · 29.2 | 3,697 | 4 · 86.2 / `/plumber-lewisville-tx/` 3,693 · 65.2 |

Что видно:

- Frisco это почти вся страница. За 16 месяцев по Frisco рядом стоят `/water-heater-repair-frisco-mckinney/` 8,794 · 46.6, `/plumber-frisco-tx/` 4,012 · 49.8, главная 2,406 · 40.2.
- По Plano за 3 месяца почти всё у страницы Plano на месте 1.6 (похоже на карточку Google).
- По восьми городам без офиса эта страница за 3 месяца в таблице не показана ни разу (вне таблицы одна строка: "expansion tanks repair little elm tx", 1 показ, место 99). Их берут городские страницы, McKinney берёт `/water-heater-repair-frisco-mckinney/`. Страница Frisco стоит на 1.0 по запросам с Prosper (64 показа) и Celina (16): правило карточки.
- На живой странице названы только Frisco, Plano и McKinney; остальные семь городов в тексте не стоят ни разу.
- Tankless с городами в таблицу не входит; за 16 месяцев по всем страницам Frisco 4,546 показов, Lewisville 1,076, Little Elm 585, The Colony 461, Plano 257.

### 2.7. Слова запросов, которые на страницу не идут

Полная таблица: `water-heaters-gsc-set-aside.md`. Без двойного счёта отложено за 3 месяца 24 запроса, 463 показа, 0 кликов; за 16 месяцев 77 запросов, 9,104 показа, 0 кликов (вместе с expansion tank, garbage disposal и water line, у которых своя страница). Запросов · показы за 3 и за 16 месяцев:

- expansion tank (своя страница `/water-heater-repair-frisco-mckinney/`): 5 · 321 и 11 · 4,756;
- tankless: 7 · 99 и 24 · 3,704 ("tankless water heater repair frisco", "tankless water heaters frisco");
- Dallas: 2 · 2 и 12 · 147; места вне десяти Pep, Trappe, Elm City, Zwolle, Coppell, Fertile, Forest Park: 5 · 22 и 8 · 144;
- boiler 1 · 12 и 2 · 118; gas line 0 и 3 · 83; pool heater, heating, furnace, commercial 1 · 3 и 10 · 122;
- garbage disposal и water line (свои страницы): 0 и 4 · 58 (в двух запросах невидимый знак);
- оценочные слова (cheap, cheapest, best, fast, fastest, reliable): 2 · 3 и 7 · 8;
- не про услугу ("site:fppplumbing.com", чужой адрес "samedaywaterheaters.com", "修理" на другом языке): 3 · 4 и 4 · 9.

Опечаток почти нет ("sameday" посчитан как "same day"). "near me" не отложено, это не запрещённое слово, но на странице его нет: 43 запроса, 5,455 показов за 16 месяцев, 0 кликов.
