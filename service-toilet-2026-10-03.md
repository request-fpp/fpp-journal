# Toilet repair: живая страница и Search Console (3 октября 2026)

Страница: https://fppplumbing.com/toilet-repair-frisco-plano/ . Сейчас не переписывается, текста страницы здесь нет.

Откуда данные: обход живого сайта (`source/crawl/pages/*.json`, `source/crawl/html/`); новый сайт `site/src/content/pages/toilet-repair-frisco-plano.md` и сборка `site/dist/` от 3 октября 10:38; `tools/build_launch_content.py`, `site/src/data/launch-changes.csv`; `reviews/`; `photos/captions-en.csv`, `photos/captions.csv`; Search Console `source/gsc/` (выгрузка 30 сентября 2026); `seo/keyword-map.md`, `seo/cannibalization-findings.md`, `docs/pages-plan.md`; `source/dictation/`. Одобренного текста для этой услуги в `source/` нет.

Длинные таблицы в `docs/briefs/services/toilet/`: `toilet-gsc-table-3m.md`, `toilet-gsc-table-16m.md` (все запросы: слова в живом тексте, точная фраза, лучшая другая страница), `toilet-gsc-top30-and-clicks.md`, `toilet-gsc-headings.md` (что держит каждый заголовок, со списками), `toilet-gsc-other-pages.md` (запросы про унитаз на других страницах и обратная сторона).

Числа через точку всегда в одном порядке: показы · место · клики. Тире в цитатах заменены пометкой [короткое тире].

## Коротко

1. Кормит мало. Итог Google за 3 месяца: 2 клика, 1,422 показа, место 20.2; оба клика известны ("toilet unclog near me", "plumber for running toilet"). За 16 месяцев 7 кликов (известны те же 2), 12,572 показа, место 32.0. Место растёт: 34.2 за 13 месяцев до июля, 17.8 за последние 3. В `docs/pages-plan.md` строка 16 группы 3.
2. Большие запросы за 16 месяцев: "toilet frisco" 682 · 16.2, "toilet repair frisco tx" 537 · 13.2, "toilet repair plano" 471 · 34.2, "emergency toilet replacement" 468 · 43.2, "toilet repair plano tx" 467 · 42.2; за 3 месяца первые "toilet repair plano" 131 · 24.9 и "toilet repair near me" 120 · 5.5.
3. Нельзя потерять: "Toilet Repair & Replacement in Frisco" и "Same-Day ... Service" в title (только title держит 16 запросов, 973 показа за 16 мес); H2 "Same-Day Toilet Repair in Frisco, Plano & ...", единственный заголовок с "toilet repair" и Plano (5 запросов, 1,028 показов); H2 "Toilet Repair Near Me ..." (1,079); "Plumbers" рядом с "Toilet Repair" в H2 (509). Пять других H2, вопросы и ответы FAQ не держат ничего.
4. Против правил: телефон в тексте, "North Dallas" в двух H2, два коротких тире, "$500/month", неподтверждённые числа ("99%", "thousands", "hundreds", "10+ years", "over 20 years"), лозунги и абзац со списком поисковых фраз, ответы FAQ тегом H2, второй узел Plumber в схеме. H2 "...Keeps Backing Up?" заходит на ключ гайда `/plumbing-guide/why-your-toilet-keeps-backing-up/`, запрещённый этой странице картой ключей.
5. Новый сайт: старый текст с пятью точечными правками (телефон, два "North Dallas", два тире), "$500/month" помечено и оставлено; шаблон добавил фото 141, отзывы KD и Brandon Klapholz, блок "What is happening right now?", одну схему.
6. Не хватает по правилу 8: вступления нет (после H1 сразу H2), содержательных H2 семь (нужно 10 до 16), FAQ три (нужно 5 до 7), раздела «если это происходит сейчас» в тексте нет, ссылки на главную "plumber near me" нет, ссылок на десять городов в тексте ноль, связанных услуг три (списком внизу). Своего текста 919 слов при ориентире 2,500.
7. Другие страницы: карточки Google Frisco и Plano стоят на 1.4 и 1.0 по "toilet repair" (548 и 163 показа за 16 мес; эта страница 220 · 14.8) и берут "toilet installation" (Frisco 266 · 2.4, этой страницы нет); главная за 16 месяцев показывалась по 111 запросам про унитаз (2,115 показов, из них 89 за последние 3 месяца); городские страницы берут «унитаз плюс свой город».
8. Материал Дениса для страницы есть и не стоит: абзацы 1, 3, 4, 6 из `source/dictation/2026-10-01-warranty-and-care.md` (без сроков гарантии), история "A week with the plunger" (на Frisco), видео 190 и 191, около двадцати фото унитазов в архиве.
9. Отложить: 35 запросов с чужими местами (698 показов за 16 мес, Dallas 471), септики, переносные туалеты, продажа унитазов, TOTO, оценочные слова.

## 1. Живая страница

### 1.1. Title, описание, H1, заголовки, объём

| Что | Живая страница |
|---|---|
| Title (65 знаков) | "Toilet Repair & Replacement in Frisco \| Same-Day Plumbing Service" |
| Meta description (172 знака) | "Toilet leaking, running, or won’t flush? We repair and replace toilets in Frisco, Plano & McKinney. Licensed plumber near you. Overflow or backup? Visit our Emergency page." |
| H1 (78 знаков) | "Toilet Leaking, Running or Clogged? We Fix & Replace Toilets in Frisco & Plano" |
| OG title | "Toilet Overflow & Repairs" (как пункт меню; с title не совпадает) |
| OG картинка | `toilet-overflow-emergency-frisco-576x1024.jpg` (не 1200 на 630) |
| Даты в схеме | опубликована 6 мая 2025, изменена 18 мая 2025 |

H2 по порядку (в скобках слов текста под ним):
1. "Toilet Won’t Flush or Keeps Backing Up? It Could Be the Main Drain Line" (96)
2. "Water Around the Toilet Base? It’s Not Always the Wax Ring" (160)
3. "Toilet Running or Leaking Slowly? You Might Be Losing Hundreds Without Noticing" (90)
4. "Toilet Shutoff Valve Leaking, Stuck, or Broken? Avoid a Major Plumbing Problem" (77)
5. "Replacing a Toilet? Don’t Just Buy the Cheapest One" (75)
6. "Toilet Repair by Licensed Plumbers You Can Trust Serving Frisco & North Dallas" (61)
7. "Same-Day Toilet Repair in Frisco, Plano & North Dallas" (62)
8. "Toilet Repair [короткое тире] Common Questions We Get" (три вопроса FAQ)
9. до 11. три ответа FAQ тегом H2 (пункт 1.2)
12. "Toilet Repair Near Me Call FPP Plumbing Today" (57 и три ссылки внизу, 39)
13. "980-899-7997 469-998-8999" (телефоны нижней панели тегом H2, шаблон)

H3 нет. Пять первых H2 построены как вопрос с припиской.

Объём: обход 921 слово, свой текст 919 (H1 14; семь разделов 701; FAQ 100; последний раздел 65; три ссылки 39). В тексте: "toilet repair" 5 раз, "Frisco" 4, "Plano" 2, McKinney только в description, "plumber near me" 0, "near me" 2, "emergency" 3, "install" 3, "unclog" 0.

### 1.2. FAQ: три вопроса слово в слово

1. "Why does my toilet keep running after flushing?" Ответ: "Usually it’s a faulty flapper or fill valve. These parts wear out over time and are easy to replace."
2. "What causes a toilet to clog over and over?" Ответ: "It could be a weak flush, something stuck in the trap, or a bigger issue in the main drain line. We’ll find the real cause."
3. "Do I need a new toilet or just a repair?" Ответ: "If the porcelain is cracked or it’s over 20 years old, it might be time to replace. Otherwise, most problems are fixable."

Вопросы стоят текстом (`span` в `summary` Elementor), не тегом заголовка; зато все три ответа тегом H2. Схема FAQPage совпадает со страницей слово в слово. Вопросов три, нужно 5 до 7.

Повторы по смыслу (дословных нет): вопрос 1 почти тот же на Allen ("Why does my toilet keep running after it fills?", ответ тоже про flapper и fill valve) и близок к вопросу поста про fill valve ("If my toilet is running, can I fix it myself?"); вопрос 2 как в гайде `why-your-toilet-keeps-backing-up` ("Why does my toilet keep clogging in the same spot?"); вопрос 3 как в посте про замену унитаза ("How do I know it’s time to replace my toilet?"), и ответы расходятся: здесь "over 20 years old", там "more than 10 years old". На новом сайте те же вопросы, жирным текстом, ответы абзацем.

### 1.3. Отзывы

На живой странице отзывов нет.

На новом сайте шаблон ставит два (`reviews/site-reviews.json`; в `reviews/site-ledger.md` оба только здесь). Оба из профиля Google Plano; текст в `reviews/all-reviews.csv` совпадает знак в знак, уровень Local Guide тот же, на старом сайте не стояли. Города в тексте нет, в подписи тоже (правило 11).

KD, Google, 19 августа 2026, подпись "★★★★★ · Local Guide Level 2 · August 2026 · Google", ссылка https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sCi9DQUlRQUNvZENodHljRjlvT2s4NVpVMUZVbVJNVFVGcU15MUNWMVpZVkdSeVVsRRAB!2m1!1s0x0:0xccc66184bdaf3a93

> I used FPP recently to clear a main log clog that flooded part of my home and to replace the toilet flange/wax ring where the water had backed into the house. Denys was my plumber and he was fantastic. He was patient, careful, explained everything thoroughly, and cleaned everything up nicely afterwards. He discovered that the original builder flange install was not done properly and spent the extra time to fix the flooring so that everything would balance correctly. All price quotes were done up front and were extremely fair and reasonable, and the company responded to all inquiries almost instantly. Highly recommend these folks!

Brandon Klapholz, Google, 12 августа 2026, подпись "★★★★★ · Local Guide Level 4 · August 2026 · Google", ссылка https://www.google.com/maps/reviews/data=!4m6!14m5!1m4!2m3!1sCi9DQUlRQUNvZENodHljRjlvT2pORGFHODRVV2h2UlhKek1VbFFlSGxuWm1wUlZFRRAB!2m1!1s0x0:0xccc66184bdaf3a93

> Super responsive (responded after hours by answering the phone with a human being and following up quickly with text messages which in and of itself is unique. Considering all of the ones I called. This was the only one where I got a human being who answered after hours too . The other nice thing is was the fact that I was able to be quoted price up front before anyone came out And the fact that when the final job was done, which it was done very well and actually included more work than what was originally discussed. The price was exactly what was quoted to me originally.
>
> Plumber showed up on time, was very thorough and professional and friendly. He replaced toilet filler, the valve stop and then went above and beyond and had to resolder the copper pipe which required some drywall work.
>
> I would definitely recommend fpp for any plumbing services.

KD называет Дениса по имени (правило «о компании, а не о Денисе» записано для городских страниц); "showed up on time" это слова клиента. Оба по темам страницы: фланец и кольцо, fill valve и кран.

### 1.4. Фото

Живая страница: одно фото `toilet-overflow-emergency-frisco-576x1024.jpg` (полный файл 720 на 1280), alt "Emergency toilet overflow repair by FPP Plumbing in Frisco, TX", первым под H1 и «лениво». Унитаз полный до края, салфетки через край, вода у основания, на бачке упаковка детских салфеток с читаемой чужой маркой. Похоже на настоящий вызов, но в архиве (`photos/index.csv`, `captions-en.csv`) файла нет: ни наша работа, ни Frisco не подтверждены; ремонта на фото нет. Остальное шаблон.

Новый сайт: сверху фото 141 (McKinney, новые fill и flush valve, `hero_for` этой страницы), старое фото ниже.

В архиве помечены для этой страницы (город из `city_final`): кран под унитазом 31 и 32 (Frisco, до и после), 137 и 138 (Plano, кран потёк, когда его закрывали; на 137 обрезать раковину хозяйки), 68 и 70 (без города); фланец и кольцо 33 и 34 (McKinney, до и после), 85, 86, 88 и видео 87 (Allen), 37 (Plano), 62 (Allen), 102 (Little Elm); бачок 61 (Plano; в `photos/captions.csv` пометка «продиктовано как 51, по порядку это 61»), 139 до 141 (McKinney, до и после); засоры 169 и видео 170 (Frisco, губка от ершика), видео 190 и 191 (шестифутовый toilet auger, унитаз забит бумагой; `city_final` McKinney по границе, а `source/dictation/2026-10-02-frisco-additions.md` и `docs/pages-plan.md` пишут «по месту съёмки Allen, город Денис не назвал»: записи расходятся), 11 (Frisco) и 26 (без города): очень грязные; у 26 в `captions-en.csv` пометка «только на пост про auger», слова Дениса в `captions.csv`: «подписать аккуратно».

### 1.5. Ссылки

Со страницы: в абзацах ни одной ссылки. Внизу список из трёх (по сути «симптом, ссылка»): "Toilet clogged or won’t flush? Might be in the line, check Clogged Drain Cleaning" (`/clogged-drain-cleaning-frisco-plano/`), "Flooding or backup at night? Visit our Emergency Plumbing" (`/emergency-plumbing-services/`), "Toilet gurgles when you use the sink? Could be the main line [короткое тире] see Drain Services" (`/drain-services/`). Нет: главной с анкором "plumber near me" (правило 6), ни одной из десяти городских страниц (правило 7), гайдов по главному крану и по крану под раковиной, leak detection, faucet, постов про унитаз. Внешних ссылок в тексте нет (Texas State Board of Plumbing Examiners назван без ссылки).

На страницу ссылаются в тексте (меню и подвал не в счёт):

| Страница | Анкор на живом сайте | Новый сайт |
|---|---|---|
| `/` | "Toilet Repairs" ("...We handle Toilet Repairs same-day in Frisco & nearby.") и картинка плитки | точка трубы "Toilet" и плитка "Toilet repair" ("Running, rocking or overflowing") |
| Allen, Celina, McKinney | "toilet repair" ("Clogs, phantom flushes, wobbly bases: toilet repair") | то же |
| Carrollton, Lewisville, Little Elm, Prosper, The Colony | "toilet repair" ("Clogs, running toilets, wobbly bases: toilet repair") | то же |
| `/plumber-plano-tx/` | "running toilet tanks" | то же |
| `/plumber-frisco-tx/` | нет | "Toilet repair" в истории "A week with the plunger" |
| `/emergency-plumbing-services/` | "Toilets overflowing" | то же |
| `/top-emergency-plumber-calls-frisco/` | "Toilet overflowing or won’t flush [короткое тире] check Toilet Repair" | то же, с двоеточием |
| `/water-leak-detection-frisco-plano/` | "toilet repair" дважды | то же |
| четыре гайда (toilet backing up, water bill, water leak yard, bathtub drain) и два поста (fill valve, замена унитаза) | "Toilet backed up", "fill valve", "running toilet", "clogged toilet", "running toilet", "toilet replacements" | то же |

Живой сайт: 19 страниц, из городов девять (без Frisco). Новый: все десять городов. Пост про auger и пост про daycare сюда не ссылаются.

### 1.6. Что идёт против CLAUDE.md, дословно

«Новый сайт»: стоит ли это в файле новой страницы после точечных правок.

**Услуги.** Tankless, reroute, hydro jetting, газа нет. Без подтверждения в фактах и диктовках: "We’ll be there with everything needed: tools, parts, wax ring, flange bolts, shutoff valves, even the new toilet if you need it." и "There’s a reason we recommend quality brands like American Standard or Kohler." (марки унитазов Денис не называл). Новый сайт: стоит.

**Цены** ($49 на странице нет):
- "We’ve had clients with water bills over $500/month because their toilet had a silent leak for years." Счёт клиента, число не подтверждено. Новый сайт: стоит («flag not changed»).
- Про деньги без чисел: H2 "...You Might Be Losing Hundreds Without Noticing", "We’ve been called to homes where the leak from a toilet flange caused thousands in repairs all because it was ignored or misdiagnosed.", "No overpriced replacements." Новый сайт: стоит.
- "That’s why we offer same-day appointments, including evenings and weekends if needed." Про сбор за вечер и выходные, названный по телефону, ни слова. Новый сайт: стоит.

**Сроки гарантии.** Нет. Срок службы без подтверждения: "get a toilet that lasts 10+ years", "over 20 years old". Новый сайт: стоит.

**Время в своих словах.** Часов и минут нет. Есть "Same-Day" в title и H2, "We know a toilet issue can’t wait. That’s why we offer same-day appointments", "show up on time", "fix toilet issues fast and properly". Обещания часа нет, а same-day держит запросы (пункт 2.3). Новый сайт: стоит. Для сравнения: на других страницах `tools/build_launch_content.py` уже снял как обещание приезда "shows up fast" и "We show up fast" (правило "arrival promise"), а блок description от 3 октября снял "we show up"; здесь "show up on time" и "fast" не тронуты.

**Другие города.** "...Serving Frisco & North Dallas" и "...in Frisco, Plano & North Dallas". Новый сайт: "the North Dallas Suburbs". В схеме живой страницы "surrounding North Dallas communities" и "Texas Master Plumber License M-44816" (снятая формулировка); на новом сайте схема своя.

**Граница с другими страницами (правило 9).**
- Раздел 1: "We get a lot of calls where the client thinks the toilet is the problem ... it turns out the main drain line is clogged, not the toilet itself." Главная линия это `/clogged-drain-cleaning-frisco-plano/` и `/drain-services/`, ссылки только внизу. H2 "Toilet Won’t Flush or Keeps Backing Up?" и вопрос "What causes a toilet to clog over and over?" заходят на "toilet keeps backing up", ключ гайда, который `seo/keyword-map.md` пишет этой странице в «must not target». Запросов с "backing up" у страницы ноль.
- Раздел 4 (кран под унитазом): тема крана под раковиной у замороженного гайда `angle-stop-valve-leaking-under-sink`; у emergency вопрос "The valve behind my toilet will not stop the water. What do I do?"; с другой стороны `/fixture-installation-repair/` заходит сюда H2 "Shower Cartridge Leaking? Toilet Valve Failing? We Handle It Daily".
- Разделы 2 и 3 пересекаются с постами про замену унитаза ("Is a leaking toilet always caused by the wax ring?") и про fill valve; хозяин темы эта страница, посты ссылаются сюда.

**Телефоны в тексте.** "Call or text FPP Plumbing now. We’ll take care of it. 980 899 7997" и H2 шаблона с двумя номерами. Новый сайт: убраны.

**Owner.** Нет. **FAQ.** Вопросы не заголовки, но ответы тегом H2; новый сайт: абзацем. **Тире.** "Toilet Repair [короткое тире] Common Questions We Get" и "Could be the main line [короткое тире] see Drain Services"; новый сайт: двоеточие. В семи предложениях между частями нет знака (похоже, здесь стояли тире): "And tightening the bolts won’t fix that it only makes things worse.", "But we’ve seen it again and again the problem isn’t the wax ring.", "We don’t guess we inspect the full setup before replacing anything", "Or just don’t move at all rusted solid", "We’ll help you pick the right model comfort height, efficient flush, good build and install it the right way.", "we do the job right not rushed, not sloppy.", "...caused thousands in repairs all because it was ignored or misdiagnosed." Новый сайт: так же.

**Схема.** Кроме Organization отдельный узел Plumber с именем, равным title, адресом Plano и "priceRange": "$$": второй узел бизнеса. Новый сайт (`site/dist/`): один Plumber, плюс WebSite, WebPage, BreadcrumbList, Service (имя = H1, описание = description, десять городов и Park Cities), FAQPage.

**Лозунги, вода, тройки, ключи напоказ.** "...You Can Trust...", "Avoid a Major Plumbing Problem", "Don’t Just Buy the Cheapest One", "No guessing. No shortcuts. No overpriced replacements.", "And we’ve fixed toilets that “other guys” gave up on", "We’ll take care of it.", тройки "cracked, rusted, or completely rotted out", "comfort height, efficient flush, good build", "insured, clean, and show up on time", H1 "Leaking, Running or Clogged". Абзац "If you’re searching for “toilet repair near me”, “replace toilet Frisco”, or “emergency plumber for leaking toilet” you’re in the right place." (но держит две точные фразы, пункт 2.4).

**Без подтверждения** (правила 3 и 13): "in 99% of those cases", "thousands in repairs", "$500/month", "for years", "hundreds of local homeowners" (цифра компании одна: 4,500+), "10+ years", "over 20 years old".

### 1.7. Что на живой странице стоит сохранить по сути

Подтверждается файлами:
- Главная линия вместо унитаза: "We get a lot of calls where the client thinks the toilet is the problem and they already went and bought a brand new one. But once we get there, it turns out the main drain line is clogged, not the toilet itself." Рядом история Дениса "One clog, the whole house" (`source/dictation/2026-10-02-from-the-job.md`) и отзыв KD.
- Фланец, а не кольцо: "the problem isn’t the wax ring. It’s the toilet flange.", "Sometimes the toilet starts rocking or moving. People assume it’s just loose bolts so they try to tighten them or replace them.", "Metal and rusted, it may have rotted through", "We always check the flange, not just the ring." К этому фото 33, 85 до 88 и слова Дениса из истории Frisco: "The bolts were already rusted, the wax ring was ruined, and under the toilet there was already water and waste on the tile."
- Бегущая вода: "A bad flapper slowly leaks water into the bowl", "A stuck fill valve keeps adding water that just drains away", "If you hear your toilet “refill” itself for no reason". К этому абзац 6 Дениса (жёсткая вода и таблетки в бачке) и фото 61, 139 до 141.
- Кран: "We’ve seen valves that: Snap off when you try to turn them / Leak as soon as you touch them / Or just don’t move at all rusted solid" и "That’s why we always check the shutoff valve when working on a toilet." К этому фото 31, 32, 137, 138 и отзыв Brandon Klapholz.
- Ответ FAQ 1 и три ссылки внизу.

Материал Дениса, которого на странице нет: `source/dictation/2026-10-01-warranty-and-care.md`, абзацы для toilet repair: 1 (не отвечаем за то, что смывают, wet wipes; первая фраза со сроками не публикуется), 3 (старый дом, чугун, салфетки), 4 (что достаём из унитазов), 6 (жёсткая вода съедает flapper и резину fill valve; синие таблетки в бачок нельзя); 4 и 6 по пометке в файле написаны Claude по русским фактам Дениса, это не его английский, 1 и 3 его английский с правкой грамматики. `source/dictation/2026-10-02-frisco-additions.md`: губка от ершика (шестифутовый auger, сняли унитаз, камера, pickup tool) и унитаз, забитый бумагой (видео 190, 191). `docs/pages-plan.md`: «Ваши абзацы про салфетки и таблетки в бачок».

### 1.8. Новый сайт против живой страницы

- Стоит старый текст. Title, description, H1, FAQ те же; H2 те же, кроме двух ("the North Dallas Suburbs") и заголовка FAQ (двоеточие).
- `launch-changes.csv`: 5 изменений и 1 пометка: номер убран (`build_launch_content.py`, строка 968, «phone in body»), два "North Dallas", два тире; "$500/month" «flag not changed». Правки description в блоке от 3 октября для этой страницы нет.
- От шаблона: фото 141 сверху, FAQ жирным текстом, блок "What is happening right now?" со ссылкой на гайд по главному крану, кнопки двух офисов, два отзыва, OG title равен title, одна схема, `noindex`.
- Своего текста 918 слов (живая 919).

## 2. Search Console

### 2.1. Итоги

| Период | Запросов | Клики | Показы | Место по показам | Итог Google со скрытыми | Доля известных: клики, показы |
|---|---|---|---|---|---|---|
| 3 месяца (1 июля до 28 сентября 2026) | 59 | 2 | 997 | 17.8 | 2 · 1,422 · место 20.18 | 100%, 70% |
| 16 месяцев (31 мая 2025 до 28 сентября 2026) | 264 | 2 | 10,893 | 32.7 | 7 · 12,572 · место 31.97 | 29%, 87% |

13 месяцев до июля (вычитанием; все 59 запросов 3 месяцев есть в 16): 9,896 показов, место 34.2, 0 кликов.

| Группа | 3 мес: запросов · показы · место · клики | 16 мес |
|---|---|---|
| город из десяти | 14 · 433 · 22.6 · 0 | 74 · 5,434 · 39.8 · 0 |
| без города | 40 · 428 · 15.1 · 2 | 152 · 4,152 · 22.3 · 2 |
| другое место | 3 · 20 · 63.9 · 0 | 35 · 698 · 65.6 · 0 |
| бренд "fpp plumbing" | 1 · 115 · 1.9 · 0 | 1 · 603 · 2.5 · 0 |
| служебный site: | 1 · 1 · 21.0 · 0 | 2 · 6 · 18.5 · 0 |

Со словом про унитаз: за 3 месяца 52 запроса, 874 показа, место 19.7, 2 клика (без него 7 и 123, из них бренд 115); за 16 месяцев 210, 8,972, место 31.2, 2 клика (без него 54 и 1,921). По месту за 3 месяца: от 1 до 3 три запроса (118 показов, оба клика), от 3 до 10 23 (206), от 10 до 20 13 (312), от 20 до 50 14 (327), ниже 50 шесть (34). За 16 месяцев от 10 до 20 стоят 57 запросов с 4,617 показами, ниже 50 91 с 3,197.

### 2.2. Первые 30 запросов и запросы с кликом

Полные таблицы: `toilet-gsc-top30-and-clicks.md`. Первые 30 дают 961 показ из 997 (3 мес) и 7,839 из 10,893 (16 мес), кликов в обеих тридцатках ноль. Оговорка для 3 месяцев: места с 28 по 37 делят десять запросов по 2 показа, среди них "toilet unclog near me" с кликом; в таблице равные стоят по алфавиту, и он остался за чертой, при другом порядке клик попал бы в тридцатку.

Первые 10 за 3 месяца (в скобках 16 месяцев): toilet repair plano 131 · 24.9 (471 · 34.2); toilet repair near me 120 · 5.5 (306 · 18.6); fpp plumbing 115 · 1.9 (603 · 2.5); toilet repair plano tx 95 · 27.8 (467 · 42.2); toilet frisco 82 · 17.5 (682 · 16.2); clogged toilet repair near me 55 · 15.0 (155 · 19.4); toilet repair 54 · 14.8 (220 · 14.8); emergency toilet replacement 42 · 33.1 (468 · 43.2); toilet installation near me 39 · 13.3 (113 · 13.8); toilet repair frisco tx 27 · 9.7 (537 · 13.2).

За 16 месяцев в тридцатке ещё: toilet repair frisco 323 · 14.3 (основной ключ по карте), toilet repair service 291 · 11.4, toilet replacement frisco 216 · 14.5, toilet replacement services 199 · 18.0, toilet repair plumber 193 · 12.1, toilet repairs near me 161 · 18.2, toilet replacement near me 152 · 10.5, toilet plumber 143 · 13.9, blocked toilet frisco 114 · 19.2, toilet flange repair near me 114 · 7.9, запросы "clogged toilet ... plano tx" на местах от 59 до 71, и чужие "bathroom plumbing frisco" 514, "bathroom plumbing frisco tx" 344, "dallas toilet repair" 159, "main sewer line replacement frisco" 101.

Запросы с кликом, оба без города: "toilet unclog near me" 2 · 3.0 · 1 (в обоих периодах) и "plumber for running toilet" 1 · 1.0 · 1 (16 мес 2 · 1.0 · 1). Слова "unclog" на странице нет; второй запрос по словам держит только description.

### 2.3. Что держат title, H1, H2 и вопросы FAQ

Заголовок «держит» запрос, когда все значимые слова запроса стоят в нём (in, tx не считаются, множественное число к единственному, город считается, "near me" одно слово; чужие места, не наши услуги, site: и "how to fix" не считаются). Списки: `toilet-gsc-headings.md`.

| Заголовок | 3 мес: запросов · показы | 16 мес: запросов · показы · клики | Держит только он: 16 мес (3 мес) |
|---|---|---|---|
| title | 10 · 229 | 26 · 2,899 · 0 | 16 · 973 (5 · 41) |
| description | 13 · 452 | 32 · 3,385 · 1 | 11 · 75 · 1 клик (2 · 2) |
| H1 | 2 · 89 | 6 · 839 · 0 | 5 · 157 (1 · 7) |
| H2 "Same-Day Toilet Repair in Frisco, Plano & North Dallas" | 9 · 442 | 12 · 2,803 · 0 | 5 · 1,028 (4 · 254) |
| H2 "Toilet Repair by Licensed Plumbers You Can Trust Serving Frisco & North Dallas" | 7 · 196 | 16 · 2,282 · 0 | 10 · 509 (3 · 10) |
| H2 "Toilet Repair Near Me Call FPP Plumbing Today" | 4 · 291 | 12 · 1,461 · 0 | 6 · 1,079 (3 · 237) |
| H2 FAQ и вопрос "Do I need a new toilet or just a repair?" | 1 · 54 | 3 · 231 · 0 | 0 |
| H2 "Toilet Won’t Flush or Keeps Backing Up? ..." | 0 | 1 · 1 ("toilet drain") | 1 · 1 |
| H2 разделов 2 до 5, вопросы FAQ 1 и 2, три ответа FAQ в теге H2 | 0 | 0 | 0 |

Ни один заголовок (description не в счёт) не держит 161 запрос и 4,485 показов за 16 месяцев (32 запроса, 236 показов и оба клика за 3): "emergency toilet replacement" 468, "clogged toilet repair near plano tx" 193, "clogged toilet repair plano tx" 168, "clogged toilet repair near me" 155, "toilet replacement near me" 152, "blocked toilet frisco" 114, "toilet flange repair near me" 114, "toilet installation near me" 113 и другие.

Что нельзя потерять:
- Title: "Toilet Repair & Replacement", "Frisco", "Same-Day", "Service". Только title держит "toilet repair service" 291 · 11.4, "toilet replacement frisco" 216, "toilet replacement services" 199, "same day service plumbing frisco" 74, "toilet repair services" 60, "toilet repair and replacement" 52 (фраза целиком). "Replacement", "Service" и "Same-Day" из заголовков есть только в title.
- "Toilet Repair" с Plano в заголовке: H2 "Same-Day Toilet Repair in Frisco, Plano & North Dallas" один держит "toilet repair plano" 471 (за 3 мес 131, первый запрос периода), "toilet repair plano tx" 467, "toilet repairs plano tx" 44, "plano toilet repair" 32, "toilet repairs plano" 14. В title Plano нет, в H1 нет слова repair. "North Dallas" отсюда уходит (на новом сайте уже "the North Dallas Suburbs").
- "Toilet Repair Near Me": H2 один держит "toilet repair near me" 306 (за 3 мес 120 · 5.5), "toilet repairs near me" 161, "toilets near me", "toilet near me" и бренд 603. "near me" стоит только здесь и в абзаце с поисковыми фразами.
- "Plumbers" рядом с "Toilet Repair": H2 "...by Licensed Plumbers..." один держит "toilet repair plumber" 193, "toilet plumber" 143, "plumber for toilet repair" 66, "toilet repair plumbers" 50, "plumbers for toilets" 45.
- H1 один держит "clogged toilet ... plano" (107, 19, 16, 14 показов, места от 56 до 79).
- По словам за 16 месяцев: "emergency" только в description и абзаце с фразами (запросы про унитаз с emergency, urgent, immediate: 15, 701 показ, место 45.7); "install" только в тексте (25 запросов, 648); "flange" только в тексте (115 показов, место 7.9); "bathroom" (878), "unclog" (165 и клик), "unclogging" (113), "blocked" (114) не стоят нигде.
- H2 разделов 1 до 5, вопросы FAQ и ответы ничего не держат: по Search Console их можно менять.

### 2.4. Фраза целиком: 20 первых за каждый период и запросы с кликом

Из 31 запроса точная фраза (подряд, слово в слово, регистр и знаки не в счёт) стоит на живой странице у четырёх:

| Запрос | 3 мес | 16 мес | Где стоит |
|---|---|---|---|
| toilet repair | 54 · 14.8 · 0 | 220 · 14.8 · 0 | title, H2 6, 7, 8 и 12, абзац с поисковыми фразами |
| toilet repair near me | 120 · 5.5 · 0 | 306 · 18.6 · 0 | H2 12 и абзац с поисковыми фразами |
| toilet frisco | 82 · 17.5 · 0 | 682 · 16.2 · 0 | только внутри цитаты "replace toilet Frisco" в том абзаце |
| fpp plumbing | 115 · 1.9 · 0 | 603 · 2.5 · 0 | H2 12, текст, alt |

Без in и tx: "toilet repair frisco tx" 537 и "toilet repair frisco" 323 стоят подряд в H2 7 ("Toilet Repair in Frisco"); "toilet repairs near me" 161 через множественное число в H2 12 и в абзаце.

Нет нигде: "toilet repair plano" и "toilet repair plano tx" (между repair и Plano стоит Frisco), "toilet repair service", "toilet replacement frisco", "toilet replacement services", "toilet repair plumber", "clogged toilet repair near me", "toilet installation near me", "toilet installation frisco", "toilet replacement near me", "emergency toilet replacement", "toilet repairs plano tx", "toilet repairs plano", "toilet replacement in frisco tx", "toilet flush repair near me", "toilet restoration near me", оба запроса с кликом, а также запросы с чужими местами и "bathroom plumbing".

### 2.5. Другие страницы сайта по запросам про унитаз

Запрос «про унитаз»: в нём toilet (или toliet, bidet, washlet, wax ring, flapper, fill valve, flush valve). Все строки: `toilet-gsc-other-pages.md`. Таких запросов на сайте за 3 месяца 101 (2,013 показов), эта страница в 52 (874, 43%); за 16 месяцев 343 (16,146), эта страница в 210 (8,972, 56%).

| Страница | 3 мес: запросов · показы · место (выше этой; этой нет) | 16 мес: то же |
|---|---|---|
| `/plumber-frisco-tx/` | 15 · 502 · 6.6 (3 · 317; 6 · 116), карточка 4 · 318 | 26 · 1,277 · 16.0 (8 · 629; 8 · 312), карточка 9 · 898 |
| `/plumber-plano-tx/` | 27 · 387 · 2.6 (4 · 231; 20 · 138), карточка 8 · 187 | 41 · 1,645 · 57.8 (9 · 572; 16 · 82) |
| `/` | 12 · 89 · 29.8 (0; 9 · 41) | 111 · 2,115 · 31.5 (41 · 966; 44 · 258) |
| `/plumber-prosper-tx/` | 3 · 110 · 12.1 (0; 1 · 65) | 3 · 120 · 12.6 (1 · 44; 1 · 75) |
| Lewisville, Carrollton, McKinney, The Colony | 2 · 2 | 15 · 1,079, места от 37 до 64 (3 · 324; 11 · 537) |
| `/plumber-little-elm-tx/` | 2 · 12 · 12.0 (0; 1 · 1) | 3 · 28 · 23.2 (1 · 11; 2 · 17) |
| `/clogged-drain-cleaning-frisco-plano/` | 1 · 9 · 22.2 (1 · 9; 0) | 9 · 185 · 28.9 (1 · 53; 0) |
| Allen, Celina | 0 | 10 · 227 (2 · 110; 8 · 117) |
| `/emergency-plumbing-services/`, `/fixture-installation-repair/` | 0 | 24 · 217 (8 · 45; 6 · 34) |
| гайд про "keeps backing up", пост про auger | 17 · 28 (только пост) | 47 · 84, этой страницы в этих запросах почти нет |

Главные строки:

| Запрос, период | Другая страница: показы · место | Эта страница |
|---|---|---|
| toilet repair, 3 мес | Frisco 287 · 1.5 (карточка); Plano 163 · 1.0 (карточка) | 54 · 14.8 |
| toilet repair plano tx, 3 мес | Plano 50 · 1.0 | 95 · 27.8 |
| toilet repair plano, 3 мес | Plano 16 · 1.0 | 131 · 24.9 |
| clogged toilet repair near me, 3 мес | Frisco 29 · 1.0 (карточка) | 55 · 15.0 |
| toilet installation, 3 мес | Frisco 82 · 5.4; Plano 4 · 3.0 | нет |
| toilet repair prosper, 3 мес | Prosper 65 · 13.5 | нет |
| toilet repair, 16 мес | Frisco 548 · 1.4 (карточка); главная 205 · 1.4; Plano 163 · 1.0 | 220 · 14.8 |
| toilet plumber near me, 16 мес | главная 403 · 60.6 | 1 · 7.0 |
| toilet installation, 16 мес | Frisco 266 · 2.4 (карточка) | нет |
| toilet repair the colony tx, 16 мес | The Colony 219 · 37.7 | 41 · 74.2 |
| toilet repair mckinney, 16 мес | McKinney 218 · 63.2 | 3 · 57.3 |
| toilet repair carrollton tx, 16 мес | Carrollton 203 · 50.9 | нет |
| clogged toilet repair near plano tx, 16 мес | главная 108 · 2.5 | 193 · 59.4 |
| toilet repair near me, 16 мес | главная 91 · 18.4 | 306 · 18.6 |
| clogged toilet plano, 16 мес | drain cleaning 53 · 24.3 | 19 · 56.3 |

По "toilet repair" без города показываются карточки Google Frisco и Plano (по `seo/cannibalization-findings.md` это кнопка сайта в карточке, а не текст). Главная брала запросы про унитаз до июля: из 2,115 показов за 16 месяцев на последние 3 приходится 89.

Обратная сторона: запросы этой страницы без слова про унитаз (16 мес 52 и 1,915 показов, плюс 2 служебных; 3 мес 6 и 122, из них бренд 115). По `seo/keyword-map.md`: бренд "fpp plumbing" 603 · 2.5 (главная); кластер Frisco 9 запросов, 902 показа ("bathroom plumbing frisco" 514 · 54.6, "bathroom plumbing frisco tx" 344 · 59.3); emergency и same day 11 · 125 ("same day service plumbing frisco" 74 · 26.3); `/drain-services/` 3 · 107 ("main sewer line replacement frisco" 101 · 55.7); `/clogged-drain-cleaning-frisco-plano/` 8 · 66; `/fixture-installation-repair/` 3 · 49; `/water-lines/` 4 · 26; `/garbage-disposal-repair-frisco-plano/` 3 · 10; `/water-heaters/` 1 · 1; ничьи 9 · 26 (септик и другое). Запрещённый этой странице "toilet keeps backing up" не встречается. Основной ключ "toilet repair frisco": 23 · 13.8 (3 мес), 323 · 14.3 (16 мес).

### 2.6. Унитаз с каждым из десяти городов

Только запросы про унитаз с городом, без чужих мест. Числа: запросов · показы · место.

| Город | Эта страница, 3 мес | 16 мес | Лучший запрос этой страницы | Кто ещё, 16 мес |
|---|---|---|---|---|
| Frisco | 6 · 166 · 16.0 | 9 · 1,957 · 15.1 | toilet repair frisco tx, 9.7 (3 мес) | Frisco 6 · 279 · 59.8; главная 6 · 237 · 42.5; drain cleaning 2 · 122 · 26.2; faucet 3 · 94 · 53.2 (за 3 мес Frisco 4 · 30 · 26.6) |
| Plano | 6 · 264 · 26.8 | 26 · 2,156 · 50.9 | toilet plumbing plano, 17.3 | Plano 20 · 1,407 · 67.0; главная 24 · 480 · 23.9; drain cleaning 7 · 63 (за 3 мес Plano 7 · 151 · 1.2) |
| McKinney | 0 | 1 · 3 · 57.3 | toilet repair mckinney | McKinney 4 · 232 · 64.3 |
| Allen | 0 | 2 · 10 · 82.1 | toilet repair allen, 67.0 | Allen 8 · 131 · 48.9 |
| Prosper | 0 | 0 | нет | Prosper 1 · 75 · 14.1 (за 3 мес 1 · 65 · 13.5) |
| Celina | 0 | 0 | нет | Celina 2 · 96 · 20.8 |
| Little Elm | 0 | 0 | нет | Plano 1 · 14 · 9.4 (длинный вопрос), Little Elm 1 · 1 |
| The Colony | 0 | 1 · 41 · 74.2 | toilet repair the colony tx | The Colony 1 · 219 · 37.7 |
| Carrollton | 0 | 0 | нет | Carrollton 3 · 296 · 52.4 |
| Lewisville | 0 | 1 · 3 · 56.0 | affordable toilet faucet services lewisville | Lewisville 6 · 327 · 51.0 |

На странице названы Frisco (title, H1, два H2) и Plano (H1, H2), McKinney только в description; остальных семи городов нет нигде.

### 2.7. Слова, которые на страницу не идут

| Что | 3 мес: запросов · показы | 16 мес |
|---|---|---|
| Чужие места, всего | 3 · 20 | 35 · 698 |
| из них Dallas | 1 · 1 | 12 · 471 |
| Sanford, Oviedo ("urgent toilet fix ...") | 0 | 3 · 108 |
| Union City, Fife, Lake County | 1 · 18 | 4 · 88 |
| Duncanville, Fate, Lago Vista, Willis, DFW, Walnut Grove, Coppell, Douglas County, Salado, Evergreen, Longmont, Thousand Oaks, Westminster, Woodstock | 1 · 1 | 16 · 31 |
| Не наша услуга или её нет в CLAUDE.md: септик, "portable toilet repair service", "toilets for sale near me", "toilet sales and installation near me", "toilet repair handyman", биде ("bidet repair near me", "toto washlet repair near me") | 1 · 2 | 9 · 27 |
| Марка TOTO | 0 | 4 · 5 |
| Чужие компании: Mega Toilet Plumbing, Passport Plumbing | 2 · 3 | 3 · 5 |
| Оценочные слова и срочность: urgent, cost, cheap, professional, immediate, affordable, fast, reliable, free | 1 · 1 | 15 · 216 |
| Не про услугу: "how do i fix this", "fix", "how to fix", "toilets open" | 1 · 1 | 4 · 4 |
| Опечатка "toliet plumber"; служебные site: | 1 · 1 | 3 · 7 |

Dallas сам по себе CLAUDE.md запрещает прямо; остальные места в десять городов и Park Cities не входят. Одна строка может попасть в две группы ("urgent toilet fix sanford"). Запросы с ценой ("clogged toilet repair cost plano tx" 55, "clogged toilet cost plano tx" 14) и "free toilet installation with purchase near me" на страницу не переносятся.

### Как считали и вторая проверка

- Скрипты `toilet_gsc.py` и `render.py` в `/private/tmp/claude-501/-Users-denyskavaler-Projects-fppplumbing-site/d2b78dea-4d58-4222-812f-a40bb43eb5d1/scratchpad/services/toilet/` сделаны из копий `docs/briefs/_shared/gsc_plano_lib.py` и `gsc_plano_live.py` (оригиналы не тронуты, `tools/gsc_page_table.py` не запускался). Правила слов из копии; десять городов свои, остальные места отложены. Живой текст из обхода: title, description, H1, H2, вопросы и ответы FAQ, разделы, последний раздел, три ссылки; alt только для точной фразы.
- Итоги посчитаны трижды (модуль csv, разбор строк без него, awk), совпали: 59 · 2 клика · 997 · 17.82 и 264 · 2 · 10,893 · 32.69. Те же числа в `source/gsc/page-query-coverage.csv`; итог Google из `performance-3m/Pages.csv` и `performance-16m/Pages.csv`.
- Группы сходятся: 14 + 40 + 3 + 1 + 1 = 59 и 433 + 428 + 20 + 115 + 1 = 997; 74 + 152 + 35 + 1 + 2 = 264 и 5,434 + 4,152 + 698 + 603 + 6 = 10,893.
- Руками сверены строки "toilet repair plano", "toilet repair" (эта страница, Frisco, Plano, главная) и "toilet installation" (Frisco) в обоих файлах.
