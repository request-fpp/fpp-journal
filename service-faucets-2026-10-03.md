# Faucet and shower valve repair: живая страница и Search Console (3 октября 2026)

Страница: https://fppplumbing.com/fixture-installation-repair/ . Сейчас не переписывается, текста страницы здесь нет.

Источники: обход живого сайта 30 сентября 2026 (`source/crawl/`), новый сайт `site/src/content/pages/fixture-installation-repair.md` и сборка `site/dist/` (3 октября), правки `site/src/data/launch-changes.csv` (строки 205 до 212), Word `source/FPP-Faucet-Shower-Valve-Page.docx`, `reviews/`, `photos/captions-en.csv`, `source/dictation/`, Search Console `source/gsc/` (выгрузка 30 сентября), `seo/`, `docs/pages-plan.md`.

Длинные таблицы в `docs/briefs/services/faucets/`: `faucets-gsc-table-3m.md` и `faucets-gsc-table-16m.md` (все запросы), `faucets-gsc-top30-and-phrases.md`, `faucets-gsc-headings.md`, `faucets-gsc-other-pages-3m.md` и `-16m.md` (запросы про услугу на всех страницах), `faucets-gsc-cities.md`, `faucets-links-and-reverse.md` (ссылки на страницу, главные строки чужих страниц, чужие запросы этой страницы).

Числа через точку: показы · место · клики (или запросов · показы · место, это сказано у таблицы).

## Коротко

1. Кормит мало и без кликов: за 3 месяца 0 кликов, 1,296 показов, место 35.6; за 16 месяцев 0 кликов, 9,104 показа, место 39.0 (итоги Google). В `docs/pages-plan.md` она 17-я из 20 в группе 3 (там порядок по показам без кликов).
2. Почти всё держат четыре запроса про Frisco: "faucet repair frisco", "frisco faucet repair", "faucet repair frisco tx", "frisco tx faucet repair": за 3 месяца 1,212 показов из 1,214 известных (места 28.7 до 64.5), за 16 месяцев 5,710 из 8,420. Запросы с другими городами, про душ и раковины за последние 3 месяца её не показывают.
3. Нельзя потерять: "Faucet" и "Frisco" в title, "Faucets" и "Frisco & Plano" в H1, "Leaky Faucet" и "Shower Valve" в title. Но слова "repair" нет ни в title, ни в H1: все слова главных запросов вместе стоят только в meta description. Ни один H2 и ни один вопрос FAQ запросы про краны не держит.
4. Против правил: унитазы в H1 и трёх разделах (страница toilet, правило 9), "Shower drains" (drain cleaning), "Reroute supply lines if needed" (на новом сайте убрано), цена "$5 part" (стоит), "We show up fast" (убрано), "Fast" в title и H1 (стоит), "same-day service guaranteed" в схеме живой страницы, пять тире (убраны), ответы FAQ в тегах H2, лозунги, непроверенные "dozens" и "hundreds".
5. Не хватает по правилу 8: своего текста 687 слов против 2,500; содержательных H2 шесть (нужно 10 до 16), ни один не держит запрос про услугу; нет списка «симптом, ссылка»; нет раздела «если это происходит сейчас» (на новом сайте есть боковой блок шаблона); FAQ 3 (нужно 5 до 7); нет ссылки на главную "plumber near me"; ноль ссылок на десять городов; из связанных страниц только emergency; нет внешнего источника.
6. Другие страницы забирают услугу. За 3 месяца по запросам про краны, душ и раковины на всём сайте 5,298 показов, у этой страницы 1,213 (23%). Страница Frisco стоит выше этой по всем четырём главным запросам (места 11.1 до 19.8 против 28.7 до 64.5). Городские страницы берут «faucet repair плюс свой город» (у Lewisville "Faucet Repair" в title, хотя карта это запрещает). Hose bib за 16 месяцев взяла 4,101 показ по 20 запросам этой темы (без слов outdoor, outside, hose, bib, spigot), из них 4,069 по 17 запросам «faucet repair» с названием города (её title "Hose Bib & Outdoor Faucet Repair in Frisco & Plano").
7. Вторичный ключ "shower valve repair" у страницы не показывается ни разу (его показы у главной и Frisco). Кран под раковиной держит гайд angle stop (по запросам этой темы у него 2,688 показов и 12 кликов за 16 месяцев; всего у гайда 23,802 показа и 129 кликов, `performance-16m/Pages.csv`), узкие темы душа два поста (Moen и 3 handle, по запросам этих тем 10 кликов за 16 месяцев).
8. Отзывов на живой странице нет; на новом сайте два (Jimmy R, Derek Gordon), тексты совпадают с архивом. Одобренный текст Word есть, но на новом сайте стоит старый текст с точечными правками.

## 1. Живая страница

### 1.1. Title, описание, H1, заголовки, объём

| Что | Живая страница |
|---|---|
| Title (54 знака) | "Leaky Faucet or Shower Valve? We Fix It Fast in Frisco" |
| Meta description (188 знаков) | "Dripping faucet, stuck cartridge, or loose shower handle? We repair and install bathroom and kitchen plumbing parts in Frisco, Plano & McKinney. Need urgent help? Visit our Emergency page." |
| H1 (82 знака) | "Leaky Faucets, Rocking Toilets, Bad Valves? We Fix Fixtures Fast in Frisco & Plano" |
| OG title | "Faucets, Showers, Sinks" (не равен title; так же названы пункт меню и крошка) |
| OG картинка | `/wp-content/uploads/2025/05/kitchen-faucet-installation-frisco-827x1024.jpg` |
| Даты в схеме | опубликована 18 декабря 2024, изменена 18 мая 2025 |
| Индекс | "Submitted and indexed", последний обход Google 1 сентября 2026 (`source/gsc/inspection-2026-10-01.csv`) |

H2 по порядку (в скобках слов в разделе):
1. "If Your Fixture Leaks, Wobbles, or Just Won’t Work Our Plumber Fixes It" (62; это вступление, под H1 текста нет)
2. "Daily Fixture Repairs by Your Plumber, Toilets, Faucets, Valves & More" (81, список из девяти пунктов)
3. "Why You Need a Licensed Plumber for Fixture Repairs, Not Just a Quick Fix" (77)
4. "Shower Cartridge Leaking? Toilet Valve Failing? We Handle It Daily" (54, список из четырёх пунктов)
5. "Licensed Fixture Plumber in Frisco, Plano, McKinney, Allen & Nearby Cities" (48)
6. "Honest Plumbing. Real Work. No Nonsense." (84, список из четырёх пунктов)
7. "Faucet & Shower Questions We Hear All the Time" (заголовок FAQ)
8. Три ответа FAQ, каждый целиком в теге H2 (пункт 1.2)
9. "Need Help? FPP Plumbing Is One Call Away" (50, последний абзац)
10. "980-899-7997 469-998-8999" (телефоны нижней панели тегом H2, шаблон)

H3 нет ни одного.

Объём: обход 689 слов; свой текст 687 (H1 14, заголовки H2 82, разделы 456, вопросы FAQ 28, ответы 73, строки-ссылки 34). До 2,500 не хватает около 1,800.

Ключи: "faucet(s)" 13 раз, "shower(s)" 11, "fixture(s)" 10 (из них "fixture" 7), "toilet(s)" 9 (из них "toilet" 5), "Frisco" 3, "Plano" 3; "faucet repair", "shower valve repair", "plumber near me" ни разу.

### 1.2. FAQ: три вопроса слово в слово

1. "Why does my faucet keep dripping even after I shut it off?"
2. "Is it better to fix or replace a leaky faucet?"
3. "Why is my shower pressure weak?"

Вопросы стоят в раскрывающемся списке Elementor (тег `summary`, не заголовок), а все три ответа целиком в тегах H2. Схема FAQPage совпадает слово в слово.

Повторы: вопрос 1 по смыслу стоит на Little Elm и The Colony ("My faucet drips no matter how tight I turn it. What is that?"), на новом сайте тоже. Вопросы 2 и 3 больше нигде; тема слабого напора есть на гайде water pressure dropping и на странице PRV. Вопросов три, нужно 5 до 7.

### 1.3. Отзывы

На живой странице отзывов нет: ни блока, ни звёзд, ни ссылок на отзыв (проверено по коду страницы).

На новом сайте (`reviews/site-reviews.json`, `site-ledger.md`) два отзыва Google, оба только на этой странице:
- Jimmy R, профиль Plano, октябрь 2025, Local Guide Level 2: "FPP came on time and replaced a stuck valve in my shower. The job required extensive cutting to get the part out…" Встал 2 октября вместо Rushi Nani (отзыв называет Frisco, ушёл на Frisco).
- Derek Gordon, профиль Plano, март 2025, Level 3: "We had a shower/tub faucet that we could not stop from running late Sunday evening…" (называет Дениса по имени).

С `reviews/all-reviews.csv` совпадают знак в знак тексты, уровни, даты и ссылки. Города в текстах и подписях нет, как велит правило 11; слова о времени ("came on time", "arrived within the ETA") принадлежат клиентам.

### 1.4. Фото

Одно настоящее фото с работы: `/wp-content/uploads/2025/05/kitchen-faucet-installation-frisco-827x1024.jpg` (полный файл 1034 на 1280), alt "Licensed plumber installing a new kitchen faucet in Frisco home". На снимке рука в перчатке вытягивает лейку нового смесителя над двойной мойкой: похоже на настоящий выезд. В `photos/index.csv` такого файла нет, город "Frisco" в alt по файлам не подтверждается. Три страницы вложений этой страницы на новом сайте уходят 301 сюда (`site/public/_redirects`). Остальное шаблон: логотип, знак BBB.

На новом сайте то же одно фото.

В архиве для этой страницы больше 25 настоящих снимков и клипов (`photos/captions-en.csv`): смесители с открытием стены (98 и 99 McKinney, 99 отмечено главным фото страницы; 144 до 148 Carrollton; 113 Frisco; 150 Allen; 151 и 152 Plano, смеситель криво на SharkBite), картриджи (60 и 177, 109 и 110 Frisco; 75 и 76 Plano), Roman tub (106 до 108 Frisco), коробка стиральной машины (71, 73 McKinney), клипы 174, 180, 181, 182. У клипа 180 в файлах два города: McKinney в `city_final`, Prosper в пометке и в плане.

### 1.5. Ссылки

Со страницы в тексте только две строки в конце: "Shower dripping or faucet won’t shut off? We fix shower cartridges and faucets clean and fast." (ссылка на саму эту страницу) и "And if hot water dies halfway through your shower, that’s Emergency Plumbing. Call us before it gets worse." (на `/emergency-plumbing-services/`).
- Ссылки на главную "plumber near me" нет. Ссылок на десять городов нет: города названы без ссылок ("Whether you’re in Frisco, Little Elm, Prosper, Plano, or Allen").
- Нет ссылок на toilet, garbage disposal, hose bib, PRV, leak detection, на гайды по главному крану и по крану под раковиной, на посты про душ. Внешних ссылок в тексте нет (только шаблон: соцсети, `tel:`, почта, BBB, ссылка "Found us" на Google).

На страницу с остальных 63: пункт меню "Faucets, Showers, Sinks" 189 раз с 62 страниц (на главной ещё H3 плитки и картинка). В тексте 20 ссылок с 19 страниц (таблица с предложениями: `faucets-links-and-reverse.md`): десять городских страниц (Allen, Carrollton, Celina, Little Elm, McKinney, Prosper, The Colony списком "…: shower valve repair"; The Colony ещё "shower cartridge replacement" в абзаце; Lewisville "faucet and shower valve repair"; Frisco "faucets, cartridges, shut-off valves"; Plano "shower cartridges replacement"), три сервисные (garbage disposal "shut-off valve replacement", PRV "faucet and shower valve repairs", leak detection "shower valve repair"), три гайда (angle stop "shut-off valves", water pressure "faucet", water bill "Shut-off valves") и три поста про душ (Moen "shower cartridge replacement in Frisco", 3 handle "shower valve", shower valve and tub faucet "shower valve").

Пост `/blog/frisco-shower-valve-leak-turned-into-a-costly-lesson/` сюда в тексте не ссылается; toilet, hose bib, water heaters, drain, slab leak, water lines, emergency тоже только через меню. На новом сайте те же ссылки, Frisco версии 4 даёт "Faucet and shower valve repair" в абзаце про жёсткую воду, главная версии 4 плитку с тем же именем и три точки трубы ("Kitchen faucet", "Bathroom sink and faucet", "Shower valve").

### 1.6. Что идёт против CLAUDE.md, дословно

«Новый сайт»: стоит ли это на новой странице после точечных правок.

**Услуги, которых FPP не делает или не заявляет.**
- "We can also: … Reroute supply lines if needed" (H2 "Shower Cartridge Leaking? Toilet Valve Failing? We Handle It Daily"). Reroute не предлагаем. Новый сайт: убрано.
- "We’ve helped homeowners, landlords, builders, and property managers who were tired of chasing flaky plumbers or getting half-baked work from big franchises." Строителей и управляющих компаний в фактах нет. Новый сайт: стоит.
- Tankless, hydro jetting, газа нет. Замена мойки и коробки стиральной машины в списке услуг CLAUDE.md не названы, но есть в одобренном тексте Word.

**Цены** (разрешена только $49 за выезд в будни; $49 на странице нет):
- "We’re not here to oversell. Sometimes it’s a $5 part. Sometimes the whole setup’s wrong." Новый сайт: стоит (в журнале правок «flag not changed»).

**Сроки гарантии.** Нет.

**Время в своих словах** (часов и минут нет):
- "We’re local. We show up fast. You call , we don’t ghost." Новый сайт: "We show up fast." убрано.
- title "…We Fix It Fast in Frisco" и H1 "…We Fix Fixtures Fast in Frisco & Plano". Новый сайт: стоят.
- "we’ll show up and fix it"; "We’ll respond."; "We don’t reschedule five times."; "We fix shower cartridges and faucets clean and fast." Новый сайт: стоят.
- Схема живой страницы, узел Plumber: "Quick repairs and full installations - clean, same-day service guaranteed." Новый сайт: схема своя, фразы нет.

**Другие города.** В тексте запрещённых нет. В схеме живой страницы "surrounding North Dallas communities" (разрешено только "North Dallas suburbs"), снятая формулировка "Texas Master Plumber License M-44816" (в узле Organization) и отдельный второй узел компании, Plumber с адресом Plano. Новый сайт: один узел Plumber, десять городов и Park Cities.

**Граница с другими страницами (правило 9).**
- Унитазы, страница `/toilet-repair-frisco-plano/`: H1 "Leaky Faucets, Rocking Toilets, Bad Valves?"; "Toilet rocking like a chair?"; список "Running or clogged toilets", "Toilet flange or wax ring issues"; H2 "Shower Cartridge Leaking? Toilet Valve Failing? We Handle It Daily" и "Daily Fixture Repairs by Your Plumber, Toilets, Faucets, Valves & More"; "Help you choose high-efficiency or ADA-compliant toilets"; "toilet seals"; "a toilet that won’t flush". Отсюда показы по "toilet repair frisco" (92 · 53.2; у страницы toilet 323 · 14.3). Новый сайт: всё стоит. Текст Word унитазы убирает.
- Засоры, страница `/clogged-drain-cleaning-frisco-plano/`: "Shower drains and tub spouts that never drained right", "clogged toilets", в ответе FAQ "clogged cartridges, or a bigger issue like restricted pipes". Новый сайт: стоит.
- Кран под раковиной: "Shut-off valves under sinks (if yours is stuck or leaking, it’s time)". Ключ "shut off valve under sink leaking" по карте у гайда `/plumbing-guide/angle-stop-valve-leaking-under-sink/`, ссылки на гайд нет.

**Телефоны в тексте.** Нет (только H2 шаблона с телефонами; на новом сайте его нет). **Owner.** Нет.

**FAQ тегом заголовка.** Вопросы не заголовки, но три ответа в тегах H2. Новый сайт: вопрос жирным, ответ абзацем.

**Тире.** "Shower systems [длинное тире] cartridges, valves, diverters, trim kits"; "Washing machine outlet boxes [длинное тире] especially when old ones crack or leak"; "or Allen [короткое тире] we’ve got you"; "Based on real experience [короткое тире] not YouTube guesses"; ответ FAQ 1 "[длинное тире] and saves you"; в схеме "full installations - clean" (дефис с пробелами как тире). Новый сайт: все пять в тексте исправлены.

**Лозунги, вода, тройки, вопросы:** H2 "Honest Plumbing. Real Work. No Nonsense."; "That’s our zone."; "we’ll tell it like it is"; "That’s a fact."; "You call , we don’t ghost."; "flaky plumbers", "half-baked work from big franchises"; "Clean, tight, and built to last"; "We’re not here to pitch. We’re here to fix."; "Call us. Text us. Message us."; "We’re not a franchise."; "We’re licensed, local, and we actually give a damn" (грубое слово); "faster than you think"; вопросы в начале текста, в title, H1 и двух H2. Новый сайт: всё стоит.

**Без подтверждения** (правило 13, факты CLAUDE.md, диктовки): "We’ve redone dozens of these jobs."; "We’ve replaced hundreds of valves, shower cartridges, faucet bodies, toilet seals, and shut-off lines"; "landlords, builders, and property managers". Новый сайт: стоят.

**Мелкое:** "replacements :kitchen", "Either way,we’ll", "fix the leak we have to"; описание 188 знаков. Слова "drywall" (три раза), "granite", "ADA", "handyman" приводят запросы не про сантехнику (пункт 2.7).

### 1.7. Что на живой странице стоит сохранить по сути

Подтверждается словами Дениса и архивом:
- Плохая чужая работа: "handyman installs a faucet, slaps on a SharkBite, uses teflon like it’s toothpaste, and says “all done.”" и "Three days later you see water in the cabinet, pressure’s off, or fittings are dripping behind drywall." и "Sometimes we don’t just fix the leak we have to cut drywall, rebuild connections, and reset fixtures from scratch." К этому фото 151 и 152 (Plano, SharkBite) и отзыв Jimmy R.
- Картриджи: "Shower systems: cartridges, valves, diverters, trim kits" и ответ FAQ 1 "It’s usually a worn-out cartridge, washer, or valve seat." Денис 2 октября (`source/dictation/2026-10-02-frisco-additions.md`): кальций от жёсткой воды съедает резину и пластик картриджа; дивертер в спауте перестаёт переключать, вода идёт и из спаута, и из лейки; картридж Delta тёк сам ("rare, but it happens too"); сломанный картридж, душ не выключался.
- Краны под раковиной: "Shut-off valves under sinks (if yours is stuck or leaking, it’s time)". Денис: ночной выезд, картридж заклинило открытым, старые краны под раковиной не закрылись (`2026-10-02-from-the-job.md`).
- "Replace outdated valves with pressure-balanced or thermostatic ones" (фото 98 и 99: две ручки на одну Moen).
- Ответ FAQ 3 ("mineral buildup in the showerhead, clogged cartridges") сходится с его словами о жёсткой воде; давление выше 80 PSI ломает картриджи (`2026-10-01-warranty-and-care.md`, абзац 7).

Только из старого текста: "Kitchen sink replacement, especially on undermount granite setups", "Washing machine outlet boxes, especially when old ones crack or leak" (фото 71 и 73), "That drip ruins cabinets, drywall, and flooring".

Абзац 6 в `2026-10-01-warranty-and-care.md` (жёсткая вода и картриджи) помечен для этой страницы; в файле сказано, что это текст Claude по русским фактам Дениса.

### 1.8. Новый сайт против живой страницы

- Старый текст с точечными правками. Title, описание, H1, восемь H2 и три вопроса FAQ те же; одобренного текста Word на странице нет.
- Точечные правки (`site/src/data/launch-changes.csv`, строки 205 до 212): убран пункт "Reroute supply lines if needed" (правило о reroute), убрано "We show up fast." (обещание приезда), пять тире заменены двоеточием или запятой. Цена "$5 part" помечена и оставлена.
- От шаблона: FAQ жирным текстом; og:title равен title; боковой блок «What is happening right now?» (ссылки на emergency и гайд по главному крану); схема: один Plumber, Service с именем по H1, FAQPage; `noindex`; два отзыва. Своего текста около 680 слов.
- Одобренный текст `source/FPP-Faucet-Shower-Valve-Page.docx` (ещё не углублён до 2,500 слов): title "Faucet Repair & Shower Valve Repair in Frisco & Plano, TX", H1 "Faucet Repair and Shower Valve Repair: Right Part, One Visit", 11 H2 (вместе с заголовком FAQ), 6 вопросов FAQ жирным текстом, ссылка на главную "plumber near me", ссылки на десять городов анкорами "plumber in Frisco" и так далее, ссылка на EPA WaterSense, унитазы убраны. По правилу заголовков (пункт 2.3) его title держит четыре главных запроса Frisco целиком (1,212 показов за 3 месяца) и два запроса Plano. Проверить в нём по нынешним правилам: гарантии производителя ("a real warranty", Moen "lifetime warranty"); вопрос "Why does my faucet drip after I turn it off?" близок к вопросу Little Elm и The Colony; "What brand of faucet do you recommend?" близок к вопросу поста 3 handle.

## 2. Search Console

### 2.1. Итоги

| Период | Запросов | Клики | Показы | Место по показам | Итог Google со скрытыми | Доля известных показов |
|---|---|---|---|---|---|---|
| 3 месяца (1 июля до 28 сентября 2026) | 6 | 0 | 1,214 | 35.8 | 0 кликов, 1,296 показов, место 35.62 | 94% |
| 16 месяцев (31 мая 2025 до 28 сентября 2026) | 65 | 0 | 8,420 | 39.8 | 0 кликов, 9,104 показа, место 39.02 | 92% |

13 месяцев до июля 2026 (вычитанием): 7,206 показов, место 40.5, 0 кликов.

| Группа | 3 мес: запросов · показы · место | 16 мес: запросов · показы · место |
|---|---|---|
| город из десяти | 5 · 1,213 · 35.8 | 51 · 8,178 · 40.4 |
| бренд ("fpp plumbing") | 0 | 1 · 163 · 3.1 |
| без города | 0 | 9 · 71 · 64.1 |
| другое место | 0 | 2 · 2 · 97.5 |
| служебный запрос site: | 1 · 1 · 14.0 | 2 · 6 · 12.3 |

По теме (16 мес): краны 26 запросов · 7,170 · 38.3; душ и смесители 6 · 247 · 62.0; «fixture» и "bathroom plumbing" 3 · 172 · 53.9; раковины 1 · 93 · 42.9; не про услугу 29 · 738 · 43.6. За 3 месяца все 1,213 показов про краны.

По месту: за 3 месяца выше 20 только site:, от 20 до 50 четыре запроса (1,121), ниже 50 один (92). За 16 месяцев в первой десятке только бренд, от 20 до 50 тринадцать запросов (4,927), ниже 50 сорок восемь (3,321).

Главные запросы, 3 месяца против 13 месяцев до них: "frisco faucet repair" 492 · 31.9 против 1,499 · 22.6 (хуже); "faucet repair frisco" 435 · 28.7 против 2,300 · 28.0 (так же); "faucet repair frisco tx" 193 · 48.2 против 450 · 65.7 (лучше); "frisco tx faucet repair" 92 · 64.5 против 249 · 68.3.

### 2.2. Первые 30 запросов и запросы с кликом

Таблицы: `faucets-gsc-top30-and-phrases.md`. За 16 месяцев первые 30 дают 8,319 показов из 8,420.

За 3 месяца: frisco faucet repair 492 · 31.9; faucet repair frisco 435 · 28.7; faucet repair frisco tx 193 · 48.2; frisco tx faucet repair 92 · 64.5; faucet replacement frisco tx 1 · 32.0; site:fppplumbing.com 1 · 14.0.

Первые 15 за 16 месяцев: faucet repair frisco 2,735 · 28.1; frisco faucet repair 1,991 · 24.9; faucet repair frisco tx 643 · 60.5; faucet repair plano 538 · 64.4; frisco tx faucet repair 341 · 67.2; faucet repair little elm 298 · 55.7; little elm faucet repair 229 · 50.9; bathroom plumbing frisco 167 · 53.8; fpp plumbing 163 · 3.1; plano faucet repair 152 · 62.7; frisco plumbing 132 · 54.9; faucet installation little elm 120 · 54.3; shower installation frisco 103 · 65.2; drywall repair frisco 96 · 56.7; bathroom sink installation frisco 93 · 42.9.

Запросов с кликом нет: 0 кликов за оба периода, и в итоге Google со скрытыми тоже 0.

### 2.3. Что держат title, H1, H2 и вопросы FAQ

Заголовок «держит» запрос, когда все значимые слова запроса стоят в нём (in, tx не считаются, множественное приводится к единственному, город считается). По запросам: `faucets-gsc-headings.md`.

| Заголовок | 3 мес: запросов · показы | 16 мес: запросов · показы | Что это за запросы |
|---|---|---|---|
| title "Leaky Faucet or Shower Valve? We Fix It Fast in Frisco" | 0 | 1 · 12 | "frisco shower" |
| meta description | 4 · 1,212 | 16 · 6,881 | все четыре Frisco, "faucet repair plano", "plano faucet repair", "bathroom plumbing frisco", "shower installation frisco", всего 16; 15 не держит никто другой |
| H1 "Leaky Faucets, Rocking Toilets, Bad Valves? We Fix Fixtures Fast in Frisco & Plano" | 0 | 1 · 1 | "toilet frisco" |
| H2 "Licensed Fixture Plumber in Frisco, Plano, McKinney, Allen & Nearby Cities" | 0 | 6 · 39 | "plumber frisco", "frisco plumber", "licensed plumber frisco", "plumber in frisco" и ещё два: запросы страницы Frisco |
| H2 "Need Help? FPP Plumbing Is One Call Away" | 0 | 1 · 163 | "fpp plumbing" (бренд, место 3.1; у главной 1,863 · 1.5 · 212 кликов) |
| остальные шесть H2, три вопроса FAQ, три ответа в H2, og:title | 0 | 0 | ни одного |

Title и H1 почти ничего не держат, потому что в них нет "repair". Будь это слово в них, title держал бы четыре главных запроса Frisco (1,212 показов за 3 месяца, 5,710 за 16), H1 ещё два Plano (690) и, через "Toilets", "toilet repair frisco" (92). "repair" стоит только в meta, в H2 "Daily Fixture Repairs…", в ответах FAQ и в тексте; "little elm" только в тексте; "install", "bathroom", "sink" только в meta и тексте.

Что нельзя потерять:
- "Faucet" и "Frisco" в title, "Faucets" и "Frisco & Plano" в H1: на них все запросы с показами за последние 3 месяца.
- "Leaky Faucet" и "Shower Valve" в title ("leaky faucet repair mckinney" 25, "leaky faucet repair plano" 3; "shower valve repair" вторичный ключ по карте).
- "repair", "install", "bathroom" держит только meta description: при замене описания их не терять.
- H2 и вопросы FAQ запросов про услугу не держат, их можно менять. H2 "Licensed Fixture Plumber in Frisco…" держит только запросы страницы Frisco (39 показов), их потерять правильно.

### 2.4. Фраза целиком: 20 первых запросов за каждый период (запросов с кликом нет)

22 запроса: 20 первых за 16 месяцев и все 6 за 3 месяца. Точная фраза (подряд, слово в слово) стоит у одного: "fpp plumbing" (H2 "Need Help? FPP Plumbing Is One Call Away"). У остальных 21 нет нигде, мягкая проверка проектного инструмента (без in, tx, в любом порядке) тоже ничего не находит.

Части фраз: "faucet repair", "shower valve repair", "shower installation", "bathroom plumbing", "sink installation" нигде; "faucet installation" только в пункте списка "Bathroom & kitchen faucets (installation and leak repair)" (между словами скобка); "shower valve" в title и вступлении, "leaky faucet" в title и вопросе FAQ 2, "kitchen faucet" в alt и в том же пункте списка.

### 2.5. Другие страницы сайта по запросам про эту услугу

Тема: краны в доме, душевые смесители и картриджи, спауты, раковины, "fixture", "bathroom plumbing"; без уличных кранов, засоров, крана под раковиной и вопросов постов Moen и 3 handle. «Выше»: место лучше этой страницы по тому же запросу за тот же период; «без этой»: эта страница по запросу не показывается. Все строки: `faucets-gsc-other-pages-3m.md` и `-16m.md`.

Весь сайт по теме: за 3 месяца 5,298 показов, у этой страницы 1,213 (23%), место 35.8; за 16 месяцев 51,603, у этой 7,682 (15%), место 39.5. Единственный клик по теме за 16 месяцев у главной ("kitchen faucet replacement", 1 · 3.0 · 1).

| Страница | 3 мес: запросов · показы · место | выше этой | без этой | 16 мес: запросов · показы · место | выше этой | ниже этой | без этой |
|---|---|---|---|---|---|---|---|
| `/plumber-frisco-tx/` | 31 · 1,428 · 18.0 | 5 · 889 | 26 · 539 | 46 · 3,455 · 38.4 | 9 · 2,424 | 2 · 438 | 35 · 593 |
| `/plumber-plano-tx/` | 45 · 693 · 6.9 | 4 · 32 | 41 · 661 | 63 · 6,543 · 43.8 | 10 · 2,304 | 3 · 17 | 50 · 4,222 |
| `/plumber-little-elm-tx/` | 8 · 658 · 18.1 | 0 | 8 · 658 | 9 · 6,437 · 24.6 | 3 · 2,364 | 0 | 6 · 4,073 |
| `/plumber-the-colony-tx/` | 6 · 436 · 15.0 | 0 | 6 · 436 | 6 · 4,598 · 32.9 | 1 · 701 | 0 | 5 · 3,897 |
| `/hose-bib-repair-frisco-plano/` | 4 · 361 · 35.9 | 0 | 2 · 9 | 20 · 4,101 · 47.5 | 5 · 658 | 7 · 3,362 | 8 · 81 |
| `/` (главная) | 17 · 209 · 35.9 | 2 · 23 | 15 · 186 | 128 · 4,843 · 30.6 · 1 клик | 11 · 1,984 | 4 · 287 | 113 · 2,572 |
| `/plumber-lewisville-tx/` | 4 · 94 · 27.6 | 0 | 4 · 94 | 12 · 4,139 · 53.7 | 3 · 921 | 0 | 9 · 3,218 |
| `/plumber-carrollton-tx/` | 5 · 23 · 22.2 | 0 | 5 · 23 | 11 · 3,645 · 51.1 | 1 · 1 | 0 | 10 · 3,644 |
| `/water-lines/` | 0 | | | 9 · 1,743 · 53.8 | 3 · 1,631 | 3 · 107 | 3 · 5 |
| `/plumber-allen-tx/` | 3 · 141 · 12.6 | 0 | 3 · 141 | 7 · 1,537 · 41.0 | 0 | 0 | 7 · 1,537 |
| `/plumber-mckinney-tx/` | 2 · 2 · 43.5 | 0 | 2 · 2 | 8 · 975 · 51.8 | 1 · 259 | 0 | 7 · 716 |
| `/toilet-repair-frisco-plano/` | 1 · 2 · 30.5 | 0 | 1 · 2 | 8 · 930 · 57.7 | 0 | 2 · 550 | 6 · 380 |
| `/slab-leak-repair-frisco-plano-mckinney/` | 0 | | | 5 · 413 · 67.4 | 1 · 71 | 2 · 168 | 2 · 174 |
| ещё 21 страница (contact, emergency, посты про душ, gallery, Celina, Prosper, гайды и другие) | от 1 до 15 показов каждая | | | от 1 до 161 показа каждая | | | |

Главные строки (20 строк: `faucets-links-and-reverse.md`): за 3 месяца страница Frisco выше по "frisco tx faucet repair" 272 · 11.1 (эта 92 · 64.5), "faucet repair frisco" 258 · 18.4 (435 · 28.7), "frisco faucet repair" 229 · 19.8 (492 · 31.9), "faucet repair frisco tx" 123 · 12.4 (193 · 48.2); Plano по "faucet repair" 203 · 3.6 (этой нет). За 16 месяцев Plano по "faucet repair plano tx" 1,193 · 38.6 (этой нет), "plano faucet repair" 1,073 · 42.5 (152 · 62.7), "faucet repair plano" 1,061 · 42.6 (538 · 64.4); Little Elm по "little elm tx faucet repair" 1,171 · 17.9 (этой нет) и "faucet repair little elm" 1,115 · 19.3 (298 · 55.7); hose bib по "frisco faucet repair" 1,414 · 38.7 и "faucet repair frisco" 1,322 · 42.5 (ниже этой, но берёт показы).

Что из этого следует:
- Frisco за 3 месяца выше по всем четырём главным запросам. Кнопка сайта карточки Google Frisco ведёт на страницу Frisco, по файлам показы карточки не отделить. Живой title Frisco кранов не называет.
- Hose bib: по `seo/cannibalization-findings.md` (пункт 4) "faucet repair" в любом городе отдан этой странице, hose bib должна убрать его из title и H1 к переезду; на новом сайте title hose bib всё ещё "Hose Bib & Outdoor Faucet Repair in Frisco & Plano | Spigot Replacement".
- Lewisville: карта запрещает ей "faucet repair", а title и на живом, и на новом сайте "Plumber Lewisville, TX | Water Leaks, Slab Leaks & Faucet Repair".
- Городские страницы берут «faucet repair» и "bathroom plumbing" со своим городом; эта страница по ним за 3 месяца не показывается. Plano выше всех по "faucet repair" без города (3.6).
- Water lines за 16 месяцев выше по двум запросам "frisco tx" (1,631 показ), slab leak по "leaky faucet repair mckinney".

Темы, которые карта отдаёт другим страницам (эта по ним не показывается):

| Тема | Хозяйка по карте | 3 мес, у хозяйки по запросам темы: запросов · показы · клики · место | 16 мес, так же |
|---|---|---|---|
| кран под раковиной течёт | `/plumbing-guide/angle-stop-valve-leaking-under-sink/` (заморожен) | 53 · 1,231 · 7 · 9.7 | 75 · 2,688 · 12 · 10.0 |
| Moen, душ не выключается | `/blog/moen-shower-cartridge-replacement-blog/` | 34 · 250 · 1 · 9.4 | 45 · 274 · 1 · 10.3 |
| три ручки в одну | `/blog/shower-system-replacement-3-handle-to-single-handle-valve/` | 28 · 316 · 7 · 8.4 | 44 · 592 · 9 · 10.9 |

Вторичный ключ "shower valve repair" у страницы не показывается: за 16 месяцев "shower valve repair" у главной 15 · 8.7, "shower valve repair near me" у главной 19 · 6.3 и у Frisco 13 · 30.2, "shower cartridge replacement" у главной 7 · 6.7.

Обратная сторона, запросы этой страницы, которые принадлежат другим (16 месяцев; за 3 месяца нет; таблица в `faucets-links-and-reverse.md`): "fpp plumbing" 163 · 3.1 (бренд, у главной 1,863 · 1.5 · 212 кликов); запросы страницы Frisco ("frisco plumbing" 132, "plumbing frisco" 47, "plumber frisco" 17, "frisco plumber" 14 и ещё шесть, вместе 227 показов, места от 39.6 до 97); унитазы ("toilet repair frisco" 92 · 53.2, у страницы toilet 323 · 14.3; ещё два по 1 показу); по одному показу "frisco garbage disposal repair", "frisco water line repair", "slab leak repair services in frisco". Вместе 487 показов. Запрещённых ей по карте "hose bib repair" и "outdoor spigot repair" нет ни разу.

### 2.6. Услуга с каждым из десяти городов

Запросы про услугу с названием города. Числа: запросов · показы · место. «Лучшее место»: среди страниц, у которых по городу не меньше 20 показов и 3% показов города. По страницам: `faucets-gsc-cities.md`.

| Город | Эта страница, 3 мес | Эта страница, 16 мес | Весь сайт, 16 мес: разных запросов · показы | Лучшее место, 3 мес | Больше всего показов, 3 мес | Больше всего показов, 16 мес |
|---|---|---|---|---|---|---|
| Frisco | 5 · 1,213 · 35.8 | 11 · 6,197 · 34.7 | 22 · 17,644 | Frisco 15 · 1,161 · 18.8 | эта страница | эта страница |
| Plano | 0 | 5 · 698 · 64.0 | 28 · 9,139 | Plano 9 · 336 · 8.6 | Plano | Plano 27 · 6,144 · 45.8 |
| McKinney | 0 | 2 · 31 · 69.9 | 9 · 1,473 | McKinney 2 · 2 · 43.5 | McKinney | McKinney 8 · 975 · 51.8 |
| Allen | 0 | 0 | 7 · 1,538 | Allen 3 · 141 · 12.6 | Allen | Allen 7 · 1,537 · 41.0 |
| Prosper | 0 | 0 | 1 · 12 | Prosper 1 · 11 · 13.0 | Prosper | Prosper 1 · 12 · 14.0 |
| Celina | 0 | 0 | 1 · 51 | нет | нет | Celina 1 · 51 · 15.7 |
| Little Elm | 0 | 3 · 647 · 53.7 | 8 · 7,466 | Little Elm 7 · 654 · 18.1 | Little Elm | Little Elm 8 · 6,429 · 24.6 |
| The Colony | 0 | 1 · 40 · 52.3 | 6 · 4,878 | Plano 4 · 26 · 4.0 | The Colony 6 · 436 · 15.0 | The Colony 6 · 4,598 · 32.9 |
| Carrollton | 0 | 0 | 11 · 3,645 | Carrollton 4 · 22 · 22.6 | Carrollton | Carrollton 10 · 3,644 · 51.1 |
| Lewisville | 0 | 4 · 16 · 71.1 | 13 · 4,210 | Lewisville 4 · 94 · 27.6 | Lewisville | Lewisville 11 · 4,134 · 53.7 |

За 16 месяцев по Frisco лучшее место у главной (7 запросов, 2,390 показов, место 29.5), за ней Frisco 17 · 3,100 · 40.9, hose bib 4 · 3,107 · 42.7, water lines 4 · 1,736 · 53.8. По Plano за 16 месяцев главная 19 · 1,459 · 39.9.

Park Cities: 5 запросов, 61 показ за 16 месяцев ("faucet replacement highland park, tx" 21, "faucet repair university park, tx" 19 и другие), почти все у contact (58 · 59.2). По CLAUDE.md их можно назвать на странице услуги, без ссылки.

На живой странице названы Frisco, Plano, McKinney, Allen, Little Elm, Prosper; The Colony, Carrollton, Lewisville, Celina нет.

### 2.7. Слова, которые на страницу не идут

Все за 16 месяцев (за 3 месяца только site:, 1 показ), вместе 277 показов:
- гипсокартон 3 · 196 ("drywall repair frisco", "frisco drywall repair", "drywall installation frisco"; на странице "drywall" три раза);
- душ ADA как переделка ванной 1 · 23 ("frisco ada shower"; на странице "ADA-compliant toilets");
- опечатки fuacet, cleanning 1 · 20; свет 1 · 13 ("lighting repair frisco"); trim 1 · 8 ("frisco trim installation", скорее плотницкая работа); site: 2 · 6;
- камень 2 · 4 ("frisco granite replacement", "frisco granite repair"; на странице "granite setups"); шкафы 1 · 2; handyman 1 · 2 (на странице "handyman installs a faucet");
- другие места 2 · 2 (Coppell, Waxahachie); оценочное "reviews" 1 · 1.

Бренд "fpp plumbing" (163) не откладывается, но это запрос главной. Tankless, reroute, hydro jetting, газа в запросах нет.

### Как считали и вторая проверка

- Скрипт `faucets_gsc.py` в scratchpad (`…/scratchpad/services/faucets/`) сделан по копиям `docs/briefs/_shared/gsc_plano_lib.py` и `gsc_plano_live.py` (оригиналы не тронуты, `tools/gsc_page_table.py` не запускался); правила слов те же, текст страницы из обхода живого сайта.
- Итоги посчитаны трижды (модуль csv, разбор строк без него, awk), все три совпали: 3 месяца 6 запросов, 0 кликов, 1,214 показов, место 35.78; 16 месяцев 65, 0, 8,420, место 39.85. Совпадают с `source/gsc/page-query-coverage.csv`; итоги Google из `performance-3m/Pages.csv` и `performance-16m/Pages.csv`.
- Группы сходятся с итогом: 5 + 1 = 6 и 1,213 + 1 = 1,214; 51 + 1 + 9 + 2 + 2 = 65 и 8,178 + 163 + 71 + 2 + 6 = 8,420. Темы за 16 месяцев: 26 + 6 + 3 + 1 + 29 = 65 и 7,170 + 247 + 172 + 93 + 738 = 8,420.
- Руками сверены строки "faucet repair frisco" (435 · 28.66 и 2,735 · 28.1), "frisco faucet repair" у этой страницы, Frisco и hose bib за 3 месяца (492 · 31.9, 229 · 19.83, 350 · 35.58).
