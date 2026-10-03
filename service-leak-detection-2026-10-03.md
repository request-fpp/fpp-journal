# Water leak detection: живая страница и Search Console (3 октября 2026)

Страница https://fppplumbing.com/water-leak-detection-frisco-plano/ сейчас не переписывается, текста страницы здесь нет. Источники: обход живого сайта от 30 сентября 2026 (`source/crawl/`), текст `source/FPP-Leak-Detection-Page-v2.docx`, новая страница в `site/src/content/pages/`, правки `tools/build_launch_content.py` и `site/src/data/launch-changes.csv`, `reviews/`, `source/gsc/`, `seo/keyword-map.*`, `docs/pages-plan.md`.

Длинные таблицы в `docs/briefs/services/leak-detection/`: `leak-gsc-table-3m.md` и `leak-gsc-table-16m.md` (все 92 и 183 запроса страницы: группа, хозяин запроса по карте ключей, слова в живом тексте, где стоит точная фраза), `leak-gsc-headings.md` (что держит каждый заголовок, запрос за запросом), `leak-gsc-other-pages.md` (запросы про поиск течи по всему сайту и какая страница их берёт).

В ячейках «473 · 19.6 · 0» порядок всегда такой: показы · среднее место · клики.

## Коротко

1. Кормит сейчас: кликов нет. За 3 месяца 0 кликов, 3,813 показов, место 33.9; за 16 месяцев 1 клик (по скрытому запросу), 24,163 показа, место 48.1. Почти все показы дают запросы про поиск течи (20,721 из 22,779 с известным запросом за 16 месяцев), больше всего с Plano (13,483) и Frisco (7,461).
2. Нельзя потерять title «Leak Detection in Plano, Frisco & McKinney | Water Leak Detection» и H1 «Water Leak Detection in Plano, Frisco and McKinney: Finding Hidden Leaks Under Slabs, Inside Walls and in the Yard»: они держат все главные запросы («frisco leak detection» 2,086 показов за 16 мес, «leak detection frisco» 1,699, «plano leak detection» 984, «frisco tx leak detection» 953, «leak detection plano» 751). Только H1 держит «slab leak detection frisco» (474) словом «Slabs».
3. Слова «underground» на странице нет, а запросы с ним дали 1,758 показов за 16 мес, и «underground leak detection plano» это вторичный ключ страницы по карте. Нет и specialist (764), detector (736), residential (608), waterline (356), infrared (113).
4. Свой сайт отбирает запросы: slab leak получил 15,942 показа по запросам про поиск течи за 16 мес (эта страница 20,763) и стоит выше по 26 запросам; McKinney большей частью уходит на slab leak (4,722 из 6,127 показов), Carrollton, Lewisville, Little Elm и The Colony на свои городские страницы. «slab leak detection plano» в карте отдан гайду про slab leak в Plano.
5. Нарушения: вопросы FAQ тегом H3, ответ 3 тегом H2, телефоны в H2 (шаблон); две FAQPage, один @id организации с двумя типами, в схеме Yoast «Texas Master Plumber License M-44816» и «North Dallas communities». В тексте: раздел про flapper и высокий счёт (toilet repair и гайд про счёт), туннель в FAQ 3 (slab leak), дренаж кондиционера без ссылки (drain cleaning), «the repair starts the same day» (срок начала ремонта, не время приезда, см. 1.6), тройка в последнем абзаце, риторические вопросы.
6. Чистое: чужих городов, цен кроме $49, сроков гарантии, тире, слова Owner, телефонов в тексте, обещаний времени приезда нет.
7. Против правила 8 не хватает: ссылок у списка признаков, ссылок на water heaters, water heater repair, drain cleaning, hose bib и на официальный источник, отзывов, фото (одно). Есть: вступление, 14 H2 и FAQ, раздел «прямо сейчас», 6 вопросов, «plumber near me» на главную, десять городов текстом, 3,311 слов.
8. Новый сайт: текст слово в слово как живой, точечных правок нет; раскладка сделала вопросы жирными, убрала H2 с ответом и телефонами, добавила два отзыва и фото 79. Ошибка переноса: восемь признаков склеены в один пункт списка. Ждёт материал Дениса: гвоздь в стене клозета (`source/dictation/2026-10-02-frisco-reserve-for-service-pages.md`), видео 188, 189 (Plano), 195 и фото 196 (McKinney), видео 200.

## 1. Живая страница

### 1.1. Title, описание, заголовки, объём

| Что | На живой странице |
|---|---|
| Title, 65 знаков | "Leak Detection in Plano, Frisco & McKinney \| Water Leak Detection" |
| Meta description, 169 знаков | "Water bill up and nothing looks wet? Meter turning with everything off? We isolate the line, pressure test it, and pinpoint the leak with acoustic and thermal equipment." |
| H1 | "Water Leak Detection in Plano, Frisco and McKinney: Finding Hidden Leaks Under Slabs, Inside Walls and in the Yard" |
| OG title | "Water Leak Detection" (не как title) |
| Даты | опубликована 6 мая 2025, последняя правка 27 сентября 2026; Google 30 сентября: «Submitted and indexed» (`source/gsc/inspection-2026-10-01.csv`) |

H2 по порядку (слов в разделе): 1 "Signs of a Hidden Water Leak" (211); 2 "The Water Meter Test You Can Run Tonight" (182); 3 "How Water Leak Detection Works: Isolation, Pressure Test, Acoustic, Thermal" (492); 4 "Why the Water Shows Up Far From the Leak" (169); 5 "Leaks Under the Slab" (120); 6 "Leaks Inside Walls and Ceilings" (218); 7 "Leaks in the Yard and at the Foundation" (122); 8 "Leaks That Are Not Supply Lines at All" (131); 9 "Drain Line Leaks: Hydrostatic Testing" (179); 10 "Silent Toilet Leaks and the High Water Bill" (119); 11 "What Happens After We Find the Leak" (120); 12 "What Leak Detection Costs" (151); 13 "Leak Detection Across Plano, Frisco, McKinney and the North Dallas Suburbs" (123); 14 "Water Coming Through a Ceiling Right Now?" (60); 15 "FAQ Water Leak Detection" (575, потом закрывающий абзац 34).

Ещё два тега H2 не разделы: ответ на вопрос 3 FAQ ("Yes. A pressure test on the isolated line ...") и "980-899-7997 469-998-8999" в нижней панели звонка. H3 шесть, все это вопросы FAQ.

Объём: обход 3,313 слов; свой текст от H1 до закрывающего абзаца 3,311 (без кнопки «Request Service»), вступление 182 слова в трёх абзацах. Frisco 10 раз, Plano 7, McKinney 7, «leak detection» 8 (из них «water leak detection» 4), «plumber near me» 1 (ссылка на главную).

### 1.2. Вопросы FAQ

Все шесть стоят тегом H3 в раскрывающемся списке Elementor (по правилу 8 нужен жирный текст), ответ 3 к тому же тегом H2. Ответы есть в коде обычным текстом. FAQPage в схеме два раза (свой граф и Elementor), обе совпадают со страницей слово в слово.

| № | Вопрос (H3) | Похожий вопрос на других страницах |
|---|---|---|
| 1 | "How do plumbers find a hidden water leak?" | Carrollton "How do I know if I have a hidden water leak?"; Celina "How do you find a hidden leak without opening the whole wall?" |
| 2 | "My water meter is moving with everything off. Is that always a leak?" | Lewisville "My water bill jumped but I cannot find anything wet. What now?" |
| 3 | "Can you find a leak under a concrete slab without breaking it?" | McKinney "Do you locate a slab leak before opening the floor?"; Lewisville "Can a slab leak be repaired without tearing up my floors?" |
| 4 | "What is a hydrostatic test and when do I need one?" | нет |
| 5 | "How long does leak detection take?" | нет |
| 6 | "Do you repair the leak after you find it?" | нет |

Слово в слово ни один вопрос не повторяется ни на живом сайте, ни на новом (проверены все вопросы с leak, meter, detect, hydrostatic, bill).

### 1.3. Отзывы

На живой странице отзывов нет (ни «★», ни блока, ни подписи Local Guide в коде). Текст v2 просил блок из двух отзывов Google со словами leak, water bill, hidden или detection; на живую страницу он не встал.

На новом сайте после текста стоят два отзыва из `reviews/site-reviews.json`. Оба совпадают с `reviews/all-reviews.csv` знак в знак, ссылки те же, в `reviews/site-ledger.md` оба автора только на этой странице, в колонке `on_old_site` у обоих пусто:
- **Oksana Toporina**, "★★★★★ · Local Guide Level 3 · January 2025 · Google" (2025-01-09): диагностика slab leak в январе 2024, потом течь под холодильником, заменена линия. Начало: "Great experience with FPP plumbing!" Ссылка: https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sChdDSUhNMG9nS0VJQ0FnSURmallDamtnRRAB!2m1!1s0x0:0xccc66184bdaf3a93
- **Liane W.**, "★★★★★ · Yelp · February 2025" (2025-02-24), https://www.yelp.com/biz/fpp-plumbing-plano-2 (ссылки на отдельный отзыв у Yelp нет, текст вставил Денис): поиск течи в стене клозета, гвоздь пробил пластиковую трубу и проржавел за четыре года. Начало: "TL;DR: Five-stars all around. Would absolutely hire again. Denys was methodical with his diagnosis/leak detection and was absolutely correct as to how the leak occurred." В тексте сумма "$700" и время "he was at my house by 2:15p": слова клиента; сумму Денис разрешил взять дословно (`docs/journal.md`), время в отзывах по его решению не трогаем. Проверка правил отметит оба места. Тот же текст в `reviews/all-reviews.csv` есть ещё раз как отзыв Google «L W» от 24 февраля 2025 со своей ссылкой на Maps; в `reviews/site-ledger.md` его нет.

Полные тексты: `reviews/site-reviews.json`, ключ `/water-leak-detection-frisco-plano/`.

### 1.4. Фото

| Файл | Alt | Что это |
|---|---|---|
| `/wp-content/uploads/2025/05/water-leak-detection-inspection-frisco-576x1024.jpg` (полный 720 на 1280, он же OG картинка) | "Plumber using advanced leak detection equipment to find hidden water leak inside home in Frisco" | настоящее фото с вызова: сантехник в тёмно-синей форме, в наушниках и бахилах, ведёт щуп по плитке на кухне; город по снимку не определить |
| логотип (2 раза), знак BBB | "FPP Plumbing Logo", "FPP Plumbing, LLC BBB Business Review" | шаблон |

Фото работы одно, видео нет. Файла нет в `photos/index.csv`; город Frisco в alt файлами не подтверждён, а v2 просил alt "FPP Plumbing plumber using a ground microphone to locate a water leak under a tile floor in Plano". За страницей в `photos/captions-en.csv` (колонки pages и hero_for) записаны 20 номеров. Фото: 79 (счётчик, The Colony; на новом сайте главное фото), 161 (Денис с детектором, Frisco), 65 (сушка после slab leak, Frisco), 17 (локатор на линии, Plano), 89 (тепловизор на потолке, Plano), 20 (автоматический кран YoLink, без города), 134 (перепаянный коллектор, без города), 192, 193, 194 (гвоздь в стене гаража, Frisco; 192 и 193 стоят на странице Frisco), 196 (вздувшийся пол, McKinney). Видео: 63 и 64 (коллектор PEX на чердаке, McKinney), 72 (счётчик крутится, Plano), 133 (коллектор капал годами, без города), 136 (свищ на меди в стене, Plano), 188 и 189 (Plano), 195 (McKinney), 200 (кейс с оборудованием, без города).

### 1.5. Ссылки

Со страницы в тексте 25 внутренних ссылок, внешних нет (в шаблоне соцсети, телефоны, знак BBB, «Found us»).

| Раздел | Анкор: куда |
|---|---|
| вступление, последний абзац | "plumber near me": главная |
| Signs | "why your water bill is suddenly high": гайд про счёт |
| Meter Test | "yard leak guide": гайд про течь во дворе |
| Under the Slab | "slab leak repair": slab leak |
| Walls and Ceilings | "water leak from the ceiling": гайд про течь после ремонта ванной |
| Yard and Foundation | "water line repair": water lines |
| Drain Line Leaks | "sewer line repair": `/drain-services/` |
| Silent Toilet Leaks | "toilet repair": toilet repair |
| What Happens After | "slab leak repair", "water line repair", "shower valve repair" (faucet), "toilet repair", "PRV replacement" |
| Leak Detection Across | "plumber in Plano", "... McKinney", "... Frisco", "... Allen", "... Prosper", "... Celina", "... Little Elm", "... The Colony", "... Carrollton", "... Lewisville" |
| Right Now | "shut-off guide": гайд про главный кран; "emergency plumbing": emergency |

- Главная: анкор ровно "plumber near me", последний абзац вступления: "If what brought you here is simpler than all that, and you just need a plumber near me for a faucet that will not stop dripping, the same trucks handle that call."
- Десять городов: все, анкоры по правилу 7, в одном абзаце текстом.
- Услуги со ссылкой: slab leak, water lines, sewer line, toilet, faucet, PRV, emergency. Без ссылки: water heaters и water heater repair (на странице есть течь по горячей стороне и T&P клапан), drain cleaning (дренаж кондиционера), hose bib, garbage disposal, top emergency calls.
- Лишняя запятая после ссылки: "read our water leak from the ceiling , guide first" (в v2: "read our water leak after a bathroom remodel guide first"); на новом сайте та же запятая.

Ссылки на страницу с других 62 живых страниц: меню три раза на каждой; в тексте 27 ссылок на 23 страницах. Главная: плитка (картинка и заголовок "Water Leak Detection"). Allen, Little Elm, McKinney, Prosper, The Colony: "leak detection" в строке списка; Carrollton, Celina, Lewisville: "leak detection" дважды. Slab leak, water lines: "leak detection". Hose bib: весь абзац ссылкой ("... go to Leak Detection."). Семь гайдов (slab leak Plano, yard leak, автоматический кран, главный кран, падение давления, высокий счёт, течь после ремонта): "leak detection", "water leak detection", "hidden leaks", "Active leaks", "water leak" (2), "Water Leak". Четыре поста: "water leak detection" (burst spigot, slab leak two leaks), "plumbing diagnostic" (тротуар в Plano), "plumbing inspection" (toilet fill valve). Без ссылки в тексте: Frisco, Plano и все услуги, кроме slab leak, water lines и hose bib. На новом сайте 25 ссылок в файлах страниц (те же места без главной), плюс Frisco версии 4 ("Water leak detection", "Leak detection") и главная ("leak detection", `tools/export_home_text.py`).

### 1.6. Сверка с CLAUDE.md

| Группа | На живой странице, дословно | Новый сайт |
|---|---|---|
| Услуги, которых нет | tankless, reroute, hydro jetting, газа нет. На грани: "A roof or window flashing leak ... We test for all of it before we call it a pipe, because a plumbing repair does not fix a roof." (выходит, что проверяем крышу) | так же |
| Цены | только "$49 service call that rolls into the work" и "After hours there is an emergency fee that depends on the time of night, stated on the phone before we roll." (правило: вечер, выходные, праздники) | так же |
| Гарантия | сроков нет | так же |
| Время | приезда не обещают. Не о приезде: "In most cases the repair starts the same day" (FAQ 6), "Most houses take one to three hours to isolate and locate." (FAQ 5), "it just happens faster"; числа "ten minutes", "cuts an hour off the visit", "two minutes" есть в v2, в `source/dictation/` нет | так же |
| Чужие города | в тексте нет, "North Dallas Suburbs" в разрешённой форме; в схеме Yoast "surrounding North Dallas communities" | схема новая, этих слов нет |
| Тема другой страницы (правило 9) | раздел "Silent Toilet Leaks and the High Water Bill" (flapper: toilet repair; «why is my water bill so high»: гайд); FAQ 3 "the repair itself usually reaches the pipe by tunneling under the foundation from outside rather than through your floor" (slab leak, без ссылки); "An air conditioner condensate line draining behind a wall, or into a bathroom sink line that is too narrow to take it, which shows up every July." (drain cleaning, без ссылки); "A water heater T&P valve discharging into a pan with no drain line." (water heater repair, без ссылки); ceiling в H2 и разделе рядом с ключом гайда «leak in ceiling under bathroom». В допустимой форме (фраза и ссылка): ремонт под плитой, труба в бетоне, PRV | так же |
| Чужие страницы на этой теме | slab leak пересказывает порядок поиска ("First the meter ... Then we shut the cold inlet on the water heater ... pressure tested with a gauge"), Carrollton и Lewisville описывают метод | так же |
| Телефоны | в тексте нет; H2 "980-899-7997 469-998-8999" в панели шаблона | нет |
| Owner | нет, "the homeowner" 2 раза | так же |
| FAQ заголовками | шесть H3, ответ 3 тегом H2 | жирный текст в `details` |
| Тире | нет | нет |
| Вода и голос | тройка "We isolate it, we test it, we mark it, ..."; итоговые фразы "This is the single most expensive misunderstanding in leak repair.", "Finding it first is the cheap part of this job."; риторический вопрос "Not sure whether the bill is a leak, a rate change or a teenager’s showers?", ещё два в разделе о методе и два в meta; "advanced" в alt. Слов из `voice/denys-voice.md` нет | так же |
| Схема | Yoast: WebPage, Organization (@id #organization), BreadcrumbList; свой граф: Service, provider типа Plumber с тем же @id, priceRange "$$", FAQPage; ещё FAQPage от Elementor. В Organization "Texas Master Plumber License M-44816" | один Service, provider по @id |

Случаи, которых нет в `source/dictation/`, но есть в v2 и частью на других страницах: счёт во Frisco вдвое (тест с краской и в гайде про счёт), медь, протёртая о камень (slab leak v3), три течи после ремонта во Frisco (гайд про ремонт ванной), flange унитаза и чёрная от плесени гипсокартонная панель. Не повторять за другими страницами.

### 1.7. Настоящее, что стоит сохранить

- Счётчик: "look for the small leak indicator on the dial, a little triangle, star or wheel"; закрыть кран дома: "If the indicator stops, the leak is inside or under the house."
- Разделение: "Shut the cold inlet on the water heater and the meter stops? The leak is on the hot side"; "you have a sprinkler leak, and that is a different repair".
- Давление и воздух: "A line that holds pressure is not leaking"; "how fast it bleeds tells us how big the hole is"; "a pinhole that is silent under water pressure hisses under air".
- Приборы: "On a slab we work the floor in a grid with a ground microphone"; "Inside a wall we use a listening rod"; "That map is what your insurance adjuster and your restoration company work from."; "A transmitter clipped to the copper puts a signal on the pipe".
- Путь воды: "runs inside the sleeve where the pipe comes up through the concrete, spreads through the gravel bed"; "In an attic, insulation holds gallons before a drop reaches the ceiling".
- Гвоздь в PEX: "A nail shot through a PEX line ... it sealed itself for months, then the nail rusted" (как в диктовке Дениса про полки и в отзыве Liane W.).
- Ввод в дом: "copper set straight into the concrete of the foundation with no sleeve" (тот же факт в видео 165 Дениса).
- Гидростатика: "plugged at the cleanout with a test ball, the drain system is filled with water to slab level ... isolated section by section with more test balls ... then confirmed with a camera"; тест до и после выравнивания фундамента.
- Не трубы: поддон душа ("plugging the drain, filling the pan and watching the ceiling below"), ледогенератор, T&P клапан в поддон без слива.
- "A lot of the leaks we find were caused by pressure sitting above 80 PSI" (совет Дениса); "the same plumber prices the repair right there".

### 1.8. Новый сайт против живой страницы

- Живая страница это текст v2 из Word со своими отличиями: в meta отрезан хвост "Plano, Frisco, McKinney."; H2 FAQ "FAQ Water Leak Detection" (в v2 "Leak Detection FAQ"); анкор "water leak from the ceiling" с лишней запятой; другой alt; FAQ тегом H3 (v2 просил жирный); нет блока отзывов.
- Новый файл: title, description, H1, все H2, текст, шесть вопросов и ответов совпадают с живой страницей слово в слово. Точечных правок нет: в `launch-changes.csv` ни одной строки для адреса (ни правки, ни пометки), в `build_launch_content.py` нет P() для него, в FROZEN страницы нет.
- Раскладка: вопросы жирным; ответ 3 и телефоны не H2; сверху фото 79 (`site/src/design/design.json`), старое фото первым в тексте; два отзыва; один Service в схеме.
- Ошибка переноса: восемь признаков раздела "Signs of a Hidden Water Leak" стоят одним пунктом списка через «•» (на живой странице это восемь строк со знаком «•», не настоящий список).

## 2. Search Console

Как считали: `gsc_leak_live.py` и `gsc_leak_lib.py` в scratchpad, переделанные копии `docs/briefs/_shared/gsc_plano_lib.py` и `gsc_plano_live.py` (оригиналы не тронуты, `tools/gsc_page_table.py` не запускался). Запрос покрыт, если каждое значимое слово стоит в живом тексте; in, tx, near, me не считаются; множественное число как единственное. Все десять городов свои. Запрос «про поиск течи», если в нём есть detect, detection, detector, locate, locator, finder, find, hydrostatic, infrared, thermal, acoustic, pressure test, leak test или leak inspection вместе со словом leak.

### 2.1. Итоги

| Период | Запросов | Клики | Показы | Место |
|---|---|---|---|---|
| 3 месяца (1 июля до 28 сентября 2026) | 92 | 0 | 3,455 | 34.7 |
| 16 месяцев (31 мая 2025 до 28 сентября 2026) | 183 | 0 | 22,779 | 48.8 |

Итог Google со скрытыми запросами (`performance-3m/Pages.csv`, `performance-16m/Pages.csv`): 3 месяца 0 кликов, 3,813 показов, место 33.93; 16 месяцев 1 клик, 24,163 показа, место 48.09. Известный запрос у 91% и 94% показов (`page-query-coverage.csv`). Единственный клик пришёл по скрытому запросу.

Второй счёт: модуль csv, разбор строк без него и awk дали одно и то же (92 запроса, 0, 3,455, 34.72; 183, 0, 22,779, 48.78); те же числа в `page-query-coverage.csv`.

| Группа | 3 мес: запросов · показы · место | 16 мес |
|---|---|---|
| Plano | 53 · 2,100 · 42.2 | 91 · 13,483 · 53.5 |
| Frisco | 12 · 894 · 26.8 | 32 · 7,461 · 37.3 |
| McKinney | нет | 10 · 877 · 88.5 |
| The Colony, Little Elm, Lewisville, Allen, Prosper, Carrollton | нет | 16 запросов, 361 показ (180, 148, 15, 12, 3, 3) |
| без города | 23 · 431 · 14.8 | 29 · 566 · 14.4 |
| чужой город (Coppell, Grape Creek, North Dallas) | 2 · 28 · 33.2 | 3 · 29 · 34.5 |
| бренд и служебный | 2 · 2 · 13.5 | 2 · 2 · 13.5 |
| из всех: про поиск течи | 77 · 3,406 · 34.7 | 131 · 20,721 · 48.5 |
| из всех: не про поиск | 15 · 49 · 37.8 | 52 · 2,058 · 52.0 |

- Все запросы трёхмесячной выгрузки есть в шестнадцатимесячной и показов там не меньше, поэтому старый период получается вычитанием: за 13 месяцев до июля 2026 было 19,324 показа, 0 кликов, место 51.3. Сейчас показов в месяц меньше (около 1,150 против 1,490), место лучше (34.7 против 51.3).
- По месту за 3 месяца: 1 до 10: 4 запроса (17 показов); 10 до 20: 17 (974); 20 до 50: 59 (2,257); ниже 50: 12 (207). За 16 месяцев: 6 (19), 18 (896), 59 (10,856), 100 (11,008).
- С какого дня стоит текст v2, по выгрузке не узнать (последняя правка в WordPress 27 сентября 2026).

### 2.2. Первые 30 запросов и клики

Запросов с кликом нет ни за 3, ни за 16 месяцев. Первые 30 дают 2,770 из 3,455 показов за 3 месяца и 15,621 из 22,779 за 16. Полные списки: `leak-gsc-table-3m.md`, `leak-gsc-table-16m.md`.

3 месяца:

| № | Запрос | 3 мес: показы · место | 16 мес | Слова в живом тексте |
|---|---|---|---|---|
| 1 | frisco leak detection | 473 · 19.6 | 2,086 · 37.8 | да |
| 2 | frisco tx leak detection | 197 · 42.7 | 953 · 68.8 | да |
| 3 | leak detection frisco | 127 · 19.9 | 1,699 · 22.8 | да |
| 4 | water leak detection in plano | 110 · 33.2 | 462 · 35.9 | да |
| 5 | water leak detection company in plano | 101 · 38.3 | 433 · 42.6 | да |
| 6 | water leak detection near me | 100 · 13.7 | 104 · 13.8 | да |
| 7 | water leak detection company plano | 99 · 38.0 | 388 · 43.3 | да |
| 8 | water leak detection services in plano | 91 · 37.8 | 402 · 42.0 | да |
| 9 | leak detection near me | 89 · 15.4 | 123 · 14.9 | да |
| 10 | water leak detection plano | 88 · 34.0 | 619 · 48.5 | да |
| 11 | commercial leak detection in plano | 85 · 49.7 | 98 · 52.5 | не наше: commercial |
| 12 | water leak detection services plano | 84 · 39.5 | 390 · 42.6 | да |
| 13 | leak detection specialist in plano | 78 · 44.9 | 216 · 55.5 | частично, нет: specialist |
| 14 | leak detection services | 77 · 10.3 | 77 · 10.3 | да |
| 15 | plano tx leak detection | 73 · 43.0 | 76 · 45.1 | да |
| 16 | leak detection company in plano | 68 · 45.3 | 261 · 55.4 | да |
| 17 | leak detectors plano | 68 · 36.3 | 177 · 58.4 | частично, нет: detector |
| 18 | plano water leak detection | 67 · 37.6 | 319 · 49.3 | да |
| 19 | plano underground leak detection | 66 · 37.8 | 319 · 31.2 | частично, нет: underground |
| 20 | leak detection services in plano | 65 · 43.1 | 293 · 52.9 | да |
| 21 | leak detectors in plano | 64 · 39.2 | 171 · 50.5 | частично, нет: detector |
| 22 | underground leak detection in plano | 62 · 58.2 | 367 · 33.6 | частично, нет: underground |
| 23 | leak detection services near me | 59 · 15.2 | 66 · 15.4 | да |
| 24 | leak detection frisco tx | 58 · 40.0 | 89 · 47.8 | да |
| 25 | plano commercial leak detection | 56 · 39.8 | 64 · 45.0 | не наше: commercial |
| 26 | plano water leak detection services | 55 · 46.0 | 403 · 50.8 | да |
| 27 | leak detection specialists in plano | 54 · 48.3 | 278 · 61.1 | частично, нет: specialist |
| 28 | plano water leak detection company | 53 · 45.5 | 320 · 54.1 | да |
| 29 | water leak detection plano tx | 53 · 38.4 | 56 · 39.8 | да |
| 30 | commercial leak detection plano | 50 · 45.0 | 53 · 47.6 | не наше: commercial |

16 месяцев: 17 из первых 30 уже стоят в таблице выше (там же их числа за 16 мес; это места 1, 2, 4, 6, 9, 10, 11, 12, 14, 15, 17, 19, 20, 21, 25, 26, 29 шестнадцатимесячного списка). Остальные 13:

| № | Запрос | 16 мес: показы · место | 3 мес | Слова в живом тексте |
|---|---|---|---|---|
| 3 | plano leak detection | 984 · 67.2 | 16 · 35.2 | да |
| 5 | leak detection plano | 751 · 64.5 | 14 · 33.4 | да |
| 7 | underground leak detection plano | 554 · 35.5 | 24 · 40.9 | частично, нет: underground |
| 8 | slab leak detection frisco | 474 · 45.0 | 8 · 38.0 | да |
| 13 | underground leak detection frisco | 398 · 11.9 | нет | частично, нет: underground |
| 16 | water leak detection frisco | 386 · 24.1 | 11 · 15.1 | да |
| 18 | foundation leak detection frisco | 364 · 32.3 | нет | да |
| 22 | leak detection mckinney | 318 · 94.7 | нет | да |
| 23 | leak detection service in plano | 317 · 50.7 | 43 · 45.6 | да |
| 24 | foundation leak detection plano | 293 · 78.7 | нет | да |
| 27 | plano residential leak detection services | 271 · 56.0 | 37 · 50.7 | частично, нет: residential |
| 28 | water leak frisco | 263 · 23.8 | 2 · 24.5 | да |
| 30 | residential leak detection services in plano | 256 · 55.9 | 41 · 49.2 | частично, нет: residential |

### 2.3. Что держат заголовки

Заголовок держит запрос, если все значимые слова запроса стоят в нём (город считается, «near me» одним словом, оценочные слова не считаются). «Фраза целиком»: подряд и в том же порядке, in, tx, near не в счёт. Числа: запросов · показы. Подробно: `leak-gsc-headings.md`.

| Заголовок | 3 мес | 16 мес | Фраза целиком, 16 мес | Держит только он, 16 мес |
|---|---|---|---|---|
| title | 19 · 1,340 | 25 · 10,157 | 6 · 966 | 0 |
| meta description | 0 | 1 · 31 | 0 | 0 |
| H1 | 22 · 1,357 | 36 · 10,864 | 9 · 2,103 | 11 · 707 |
| H2 "Leak Detection Across Plano, Frisco, McKinney and the North Dallas Suburbs" | 12 · 1,004 | 15 · 7,555 | 1 · 6 | 0 |
| H2 "How Water Leak Detection Works ..." и H2 "FAQ Water Leak Detection" (каждый) | 1 · 6 | 2 · 37 | 2 · 37 | 0 |
| H2 "What Leak Detection Costs" и вопрос "How long does leak detection take?" (каждый) | 1 · 6 | 1 · 6 | 1 · 6 | 0 |
| H2 "Signs of a Hidden Water Leak" и вопрос "How do plumbers find a hidden water leak?" (каждый) | 0 | 1 · 31 | 1 · 31 | 0 |
| H2 "Why the Water Shows Up ...", H2 "Silent Toilet Leaks ...", вопрос "My water meter is moving ..." (каждый) | 0 | 1 · 31 | 0 | 0 |
| остальные 8 H2 и 3 вопроса | 0 | 0 | 0 | 0 |

Что нельзя потерять:
- **title и H1** держат все запросы «leak detection» с Plano, Frisco и McKinney; фразы целиком у запросов с Plano дают связки «Water Leak Detection in Plano» (H1) и «Leak Detection in Plano» (title).
- **Только H1** держит 11 запросов (707 показов), все со slab или wall: «slab leak detection frisco» 474, «slab leak detection plano» 89, «slab water leak detection in plano» 55, «slab leak detection in plano» 41, «wall leak detection plano» 15. Слова «Slabs» и «Walls» в H1 оставить.
- **H2 с городами** единственный подзаголовок с городами (15 запросов, 7,555 показов). Остальные держат только «leak detection» (6) и «water leak» (31).
- Ни один заголовок (кроме meta) не держит 147 запросов, 11,915 показов за 16 мес: в основном с company, services, underground, specialist, residential, foundation («underground leak detection plano» 554, «water leak detection company in plano» 433, «underground leak detection frisco» 398, «foundation leak detection frisco» 364).

### 2.4. Фраза целиком: первые 20 каждого периода

Запросов с кликом нет; проверены первые 20 по показам за 3 и за 16 месяцев (вместе 30). Точная фраза слово в слово и в том же порядке стоит на живой странице у одного: «water leak detection in plano» (H1). «frisco leak detection» и «leak detection frisco» целиком нигде: в title и H1 Frisco стоит после Plano через запятую. Из всех 183 запросов точная фраза есть у пяти: «water leak detection in plano», «leak detection in plano» (title, H1), «water leak», «leak detection», «fpp plumbing».

Проверенные 30: «frisco leak detection», «frisco tx leak detection», «leak detection frisco», «water leak detection in plano», «water leak detection company in plano», «water leak detection near me», «water leak detection company plano», «water leak detection services in plano», «leak detection near me», «water leak detection plano», «commercial leak detection in plano», «water leak detection services plano», «leak detection specialist in plano», «leak detection services», «plano tx leak detection», «leak detection company in plano», «leak detectors plano», «plano water leak detection», «plano underground leak detection», «leak detection services in plano», «plano leak detection», «leak detection plano», «underground leak detection plano», «slab leak detection frisco», «plano water leak detection services», «underground leak detection frisco», «water leak detection frisco», «underground leak detection in plano», «foundation leak detection frisco», «plano water leak detection company».

### 2.5. Другие страницы на запросах про поиск течи

Все страницы обеих выгрузок, старые адреса сложены с новыми. Полностью: `leak-gsc-other-pages.md`. На сайте таких запросов за 3 месяца 144 (7,274 показа), у этой страницы 80 и 3,414 (47%); за 16 месяцев 242 (49,617), у неё 133 и 20,763 (42%). (80 и 133 больше, чем 77 и 131 в 2.1: сюда входят gas, spa и roof leak detection.)

| Страница | 3 мес: запросов · показы · место | 16 мес | Выше этой страницы за 16 мес: запросов · её показы |
|---|---|---|---|
| slab leak | 21 · 488 · 30.5 | 118 · 15,942 · 57.0 | 26 · 7,568 |
| Lewisville | 16 · 485 · 16.0 | 18 · 2,380 · 57.5 | 7 · 747 |
| Carrollton | 14 · 1,063 · 22.2 | 20 · 2,338 · 44.8 | 5 · 119 |
| water lines | 4 · 10 · 72.8 | 39 · 1,820 · 58.5 | 5 · 512 |
| Frisco | 27 · 853 · 23.9 | 32 · 1,416 · 35.0 | 10 · 588 |
| Little Elm | 3 · 156 · 22.9 | 3 · 1,261 · 47.6 | 2 · 439 |
| The Colony | 7 · 128 · 15.3 | 13 · 1,140 · 50.9 | 1 · 279 |
| главная | 12 · 74 · 65.1 | 71 · 842 · 42.7 | 23 · 364 |
| Plano | 31 · 374 · 5.8 | 59 · 663 · 32.5 | 24 · 290 |
| McKinney | 2 · 11 · 19.8 | 10 · 503 · 79.8 | 4 · 280 |
| гайд slab leak Plano | 18 · 174 · 24.2 | 22 · 307 · 24.3 | 15 · 138 |
| PRV | 2 · 31 · 3.9 | 2 · 31 · 3.9 | 1 · 30 |

Крупнее всего за 16 мес (другая страница против этой): «mckinney leak detection» slab leak 1,040 · 68.5 против 181 · 94.3; «slab leak detection plano» slab leak 905 · 38.5 против 89 · 93.4; «leak detection mckinney» slab leak 786 · 61.4 против 318 · 94.7; «slab leak detection frisco» slab leak 581 · 24.7 против 474 · 45.0; «frisco tx leak detection» slab leak 492 · 68.2, water lines 479 · 60.8, Frisco 434 · 61.7 против 953 · 68.8; «water leak detection lewisville» Lewisville 340 · 62.3 против 2 · 83.0.

За 3 месяца: «slab leak detection near me» slab leak 148 · 12.9 против 7 · 29.3; «frisco tx leak detection» Frisco 111 · 28.4 против 197 · 42.7; «water leak detection near me» Lewisville 48 · 7.9 против 100 · 13.7; «plumbing pressure test near me» PRV 30 · 2.6 против 12 · 8.2.

Эта страница не показывалась вовсе по 109 запросам за 16 мес, которые получили другие: «carrollton tx leak detection» (Carrollton 1,014 · 49.0), «little elm tx leak detection» (Little Elm 822 · 44.8), «the colony tx leak detection» (The Colony 744 · 52.2), «lewisville tx leak detection» (Lewisville 691 · 59.5), «mckinney tx leak detection» (slab leak 431 · 84.9), «water leak detection» без города (Frisco 276 · 1.1, место 1: по правилу проекта карточка Google офиса Frisco).

Карта ключей: у slab leak «must not target: leak detection (leak detection page)», у Frisco «leak detection frisco»; «slab leak detection plano» записан вторичным ключом гайда `/plumbing-guide/slab-leak-repair-plano-tips-2026/`.

Обратно, запросы этой страницы, чужие по карте ключей или не наши:

| Чей запрос | 16 мес: запросов · показы | 3 мес | Примеры (показы за 16 мес) |
|---|---|---|---|
| общий про течь, хозяина в карте нет | 10 · 924 | 3 · 9 | water leak frisco 263, water leak plano 251, leaks frisco 233 |
| ремонт течи без места, хозяина в карте нет | 15 · 545 | 4 · 15 | plano water leak repair 108, plano leak repair 94, water leak repair plano 89 |
| ущерб от воды, сушка, плесень (партнёр) | 10 · 352 | нет | plano wet wall damage 72, frisco slab leak water damage 64 |
| slab leak | 7 · 145 | 3 · 15 | foundation leak repair frisco 76 (у slab leak 343 · 46.0), slab leak repair frisco 32 (у slab leak 2,730 · 27.8) |
| toilet repair | 1 · 36 | нет | plano toilet overflow damage |
| water lines | 3 · 10 | нет | frisco water line repair 6 (у water lines 2,597 · 20.1) |
| газ, спа, крыша | 3 · 43 | 3 · 8 | gas leak detection frisco 22, spa leak detection frisco 16, roof leak detection services in plano tx 5 |
| главная | 1 · 1 | нет | north dallas plumber |

### 2.6. Поиск течи с каждым из десяти городов

Запросы про поиск течи с городом, все страницы сайта. Числа: запросов · показы · место.

| Город | Leak detection: 3 мес (запросов · показы · место) | 16 мес | Страница города: 3 мес | 16 мес | Slab leak: 16 мес | Больше всех показов, 16 мес | Лучшее место за 16 мес (от 10 показов) |
|---|---|---|---|---|---|---|---|
| Frisco | 8 · 878 · 26.5 | 17 · 6,630 · 36.3 | 8 · 468 · 37.2 | 9 · 909 · 50.3 | 18 · 3,322 · 42.5 | эта страница (6,630) | Plano (4.4) |
| Plano | 50 · 2,092 · 42.2 | 70 · 12,373 · 53.1 | 11 · 56 · 6.3 | 39 · 345 · 57.1 | 65 · 7,540 · 63.9 | эта страница (12,373) | гайд slab leak Plano (24.8) |
| McKinney | нет | 9 · 870 · 88.8 | 1 · 9 · 21.7 | 9 · 501 · 80.1 | 15 · 4,722 · 57.3 | slab leak (4,722) | Frisco (21.0) |
| Allen | нет | 3 · 12 · 63.0 | 1 · 3 · 38.7 | 3 · 130 · 59.4 | 3 · 27 · 71.9 | Allen (130) | Allen (59.4) |
| Prosper | нет | нет | нет | 1 · 2 · 38.0 | нет | Prosper (2) | нет |
| Celina | нет | нет | нет | 1 · 59 · 19.5 | нет | Celina (59) | Celina (19.5) |
| Little Elm | нет | 3 · 134 · 63.8 | 3 · 156 · 22.9 | 3 · 1,261 · 47.6 | 1 · 1 · 74.0 | Little Elm (1,261) | Little Elm (47.6) |
| The Colony | нет | 1 · 180 · 71.5 | 7 · 128 · 15.3 | 13 · 1,140 · 50.9 | 1 · 38 · 75.2 | The Colony (1,140) | главная (1.0) |
| Carrollton | нет | 1 · 3 · 63.3 | 8 · 990 · 23.1 | 14 · 2,265 · 45.9 | 2 · 20 · 72.1 | Carrollton (2,265) | Carrollton (45.9) |
| Lewisville | нет | 4 · 15 · 79.8 | 12 · 381 · 18.4 | 13 · 2,269 · 59.8 | 3 · 34 · 67.1 | Lewisville (2,269) | Plano (1.4) |

- Frisco и Plano: больше всех показов у этой страницы, но место плохое (Plano 53.1 за 16 мес). Страница Plano стоит выше всех по запросам Frisco (23 показа, место 4.4) и The Colony (за 3 месяца 171 показ, место 6.8).
- McKinney: запросы уходят на slab leak (4,722 из 6,127 показов всех страниц), у этой страницы 870 на месте 88.8, хотя McKinney стоит в title и H1; за 3 месяца по McKinney у неё нет показов.
- Остальные семь городов: эта страница почти не показывается (за 3 месяца ни разу), запросы берут страницы городов.

### 2.7. Что отложено

| Что | 3 мес: запросов · показы | 16 мес | Запросы |
|---|---|---|---|
| ущерб от воды, сушка, плесень: делает партнёр | нет | 11 · 388 | plano wet wall damage, mold remediation prosper |
| commercial: своей страницы нет | 3 · 191 | 3 · 215 | commercial leak detection in plano и ещё 2 |
| чужие места | 2 · 28 | 3 · 29 | coppell leak detection, grape creek water leak detection, north dallas plumber (North Dallas отдельно не пишем) |
| газ | 1 · 3 | 1 · 22 | gas leak detection frisco |
| спа | 1 · 1 | 1 · 16 | spa leak detection frisco |
| крыша | 1 · 4 | 1 · 5 | roof leak detection services in plano tx |
| оценочные слова | 1 · 1 | 2 · 3 | leak detection cost plano tx, plano plumbing and leak detection reviews |
| бренд и служебный | 2 · 2 | 2 · 2 | fpp plumbing, site:fppplumbing.com |

Опечаток и голосовых запросов нет. Свои слова запросов, которых нет в живом тексте (16 мес, запросов · показы): underground 8 · 1,758; specialist 9 · 764; detector 6 · 736; residential 4 · 608; waterline 4 · 356; infrared 2 · 113 (на странице стоит thermal); city 2 · 21. За 3 месяца: specialist 8 · 197, underground 4 · 153, detector 4 · 140, residential 4 · 87. Слова company и services на странице есть только в других смыслах ("restoration company", "service call").
