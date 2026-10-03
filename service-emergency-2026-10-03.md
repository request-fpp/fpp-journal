# Emergency plumbing: живая страница и Search Console (3 октября 2026)

Страница https://fppplumbing.com/emergency-plumbing-services/ : ответ 200, в page-sitemap.xml, canonical на себя, index и follow, опубликована 18 декабря 2024, правка в WordPress 30 августа 2026. Сейчас не переписывается, текста страницы здесь нет.

Источники (прочитаны 3 октября 2026, проект только читался): краул от 30 сентября `source/crawl/pages/emergency-plumbing-services.json` и `html/`, остальные 63 страницы; `site/src/content/pages/emergency-plumbing-services.md`, `ServicePage.astro`, `schema.ts`; `tools/build_launch_content.py`, `launch-changes.csv`; `reviews/`; `source/gsc/` (page-query 3m и 16m, Pages.csv, coverage); `seo/keyword-map`; `docs/pages-plan.md`; `photos/captions-en.csv`.

Длинные таблицы в `docs/briefs/services/emergency/`: `emergency-gsc-summary-tables.md` (все сводные таблицы раздела 2, в том числе первые 30 запросов за оба периода), `emergency-gsc-table-3m.md` (206 запросов) и `emergency-gsc-table-16m.md` (915), `emergency-gsc-headings.md` (что держит каждый заголовок), `emergency-gsc-other-pages.md` (другие страницы на тех же запросах), `emergency-gsc-cities.md` (десять городов), `emergency-gsc-set-aside.md` (отложенные слова), `emergency-links-in.md` (41 ссылка на страницу из текста других страниц).

В разделе 2 три числа через точку: показы · среднее место · клики.

## Коротко

1. Кормит страницу срочность: «emergency plumbing», «emergency plumber», «24 hour plumbers», «24 7 plumber» и «emergency plumber» с Frisco и Plano. У Google за 3 месяца 2 клика, 9,978 показов, место 23.4; за 16 месяцев 7 кликов, 96,031 показ, место 32.5. Из известных запросов клики дали только бренд «fpp plumbing» (1 и 3) и «plumber emergency service» (1).
2. Слов хватает: у 96% показов за 16 месяцев (88,234 из 91,603) все слова запроса уже стоят в тексте. Беда в месте: по десяти запросам «emergency plumber» с Frisco или Plano (от 133 показов каждый) за 3 месяца страница на 23 до 44 месте, главная по тем же запросам на 7 до 12.
3. Главная забирает тему: за 16 месяцев она выше этой страницы по 233 срочным запросам (147,650 показов), за 3 месяца по 71 (20,937). По CLAUDE.md главная держит эти слова до отдельного шага после переезда.
4. Нельзя терять: «Emergency Plumber», «Frisco», «Plano», «24/7» в title и H1 (title и H1 держат по 60 тысяч показов за 16 месяцев), «McKinney» в H1, «24 Hour Plumber» в H2 («24 hour plumbers» 3,630 · 14.1, «24 7 plumber» 3,069 · 14.8) и в H2 про города, «Emergency Plumbing» в заголовке (4,164 · 18.2), «After Hours» в H2. «Emergency Plumbing Services» живой сайт держит в og:title и меню, на новом её нет, а запрос за 3 месяца на месте 10.1.
5. Против правил: «the bill follows the work, not the estimate» (текст и FAQ), «That coordination costs you nothing», ссылка на гайд цен с 19 суммами в долларах, «Outdoor faucets split» в мороз (против поправки Дениса), запах газа и «then call us», «Fast» в H1, на фото фургона «M-38532», а лицензия компании M-44816 (что это за номер, в проекте не записано). Живая схема: «same night», «North Dallas communities», «Texas Master Plumber License»; новая схема этого не несёт.
6. Границы: пять историй (картридж в душе, ремонт ванной, пинхол на чердаке, засор главной линии, дренаж кондиционера) и вопрос FAQ про воду с потолка уходят в темы других страниц без ссылки.
7. Против правила 8 не хватает: FAQ 9 вопросов вместо 5 до 7, на живой странице тегом H3, три почти повторяют главную и городские страницы; 6 из 10 H2 без ключевых слов; нет ссылок на drain cleaning, leak detection, expansion tank, PRV, garbage disposal, faucet и shower valve; нет внешней ссылки на официальный источник; нет фото с работы (в архиве под страницу помечены 12).
8. Есть и должно остаться: ссылка на главную «plumber near me» в последнем абзаце вступления, все десять городов «plumber in ...» в тексте, список симптомов со ссылками, раздел «Shut This Off First, Then Call» со ссылкой на гайд, 2,714 слов своего текста.
9. Новая версия: текст, заголовки и FAQ слово в слово как на живой, точечных правок нет, одобренного текста в source/ нет. Макет добавляет «What is happening right now?», «Close the main shut-off valve», два отзыва, строку дежурства. Список «What We Fix at Two in the Morning» склеился в один пункт.

## 1. Живая страница

### 1.1. Title, описание, H1, заголовки, объём

| Что | Текст |
|---|---|
| Title (63 знака) | "Emergency Plumber in Frisco & Plano, TX \| 24/7 Plumbing Service" |
| Description (149) | "Burst pipe? Overflowing toilet? No hot water? Call FPP Plumbing for 24/7 emergency service in Frisco, Plano & McKinney. nights and weekends included." ("nights" с маленькой после точки) |
| H1 (113) | "Got a Plumbing Emergency? Call Your 24/7 Emergency Plumber in Frisco, Plano & McKinney: Licensed, Fast, and Local" |
| og:title | "Emergency Plumbing Services" (не равен title) |
| og:image | фургон `/wp-content/uploads/2025/05/fpp-plumber-emergency-truck-frisco.png` |

H2 по порядку (слов в разделе по тексту краула): 1 "Shut This Off First, Then Call" (258); 2 "What Actually Counts as an Emergency" (193); 3 "What a 24 Hour Plumber Costs After Hours" (156); 4 "A 24 Hour Plumber Who Actually Picks Up" (162); 5 "What We Fix at Two in the Morning" (97, девять пунктов, шесть со ссылками); 6 "What These Calls Actually Look Like" (550, семь историй, первые фразы жирным, не заголовки); 7 "The One Thing All of Them Share" (307); 8 "Frozen Pipes and Burst Lines After a Hard Freeze" (136); 9 "24 Hour Plumber Service Area: Frisco, Plano and the Cities Around Them" (120); 10 "Emergency Plumbing FAQ" (482 вместе с вопросами). Ещё H2 "980-899-7997 469-998-8999": два телефона нижней панели, шаблон старого сайта. H3: девять, все это вопросы FAQ.

Объём: краул 2,716 слов, из них свой текст от H1 до конца FAQ 2,714 (H1 18, вступление 162, заголовки H2 73, разделы 1,979, FAQ 482), остальное кнопка "Request Service". Отметка правила 3 достигнута.

### 1.2. FAQ

Девять вопросов, все тегом H3 в раскрывающемся списке Elementor (`details`, `summary`, класс `e-n-accordion-item-title-text`), ответы в коде страницы. Схема FAQPage совпадает со страницей слово в слово.

1. "Do you really answer the phone at night?"
2. "Do I pay the after hours fee if the repair turns out to be small?"
3. "Is my problem actually an emergency?"
4. "What should I do before you arrive?"
5. "The valve behind my toilet will not stop the water. What do I do?"
6. "Water is coming through my ceiling. Where is it coming from?"
7. "My shut-off valve will not turn. What now?"
8. "How fast can you get here?"
9. "Do you charge extra on holidays?"

Слово в слово ни один не стоит на других 63 страницах и в других файлах `site/src/content/pages`. Близко по смыслу: 1 и вопрос главной (source/home-text-v4.md) "Are you open 24/7? Do you really answer at night?"; 8 и "How quickly can a plumber arrive?" на главной, "How fast can you get to The Colony?" (так же Lewisville; у Prosper "How quickly can you get to Prosper?"); 9 и "Do you charge extra after hours?" на восьми городских страницах (Allen, Carrollton, Celina, Lewisville, Little Elm, McKinney, Prosper, The Colony); 7 и "The shutoff valve under my sink will not turn. Is that a problem?" (Lewisville).

### 1.3. Отзывы

На живой странице отзывов нет ни одного (нет звёзд, "Local Guide", ссылок на Google, Yelp, Thumbtack).

На новом сайте за страницей стоят два отзыва Google из профиля Plano (`reviews/site-reviews.json`, `site-ledger.md`): Gerardo, 6 мая 2025 ("Sunday night the faucet in my bathroom broke and there was water everywhere...", подпись "★★★★★ · Local Guide Level 2 · May 2025 · Google") и Mark Y, 14 июля 2025 ("FPP Plumbing came to our rescue! We had a shower that we could not turn off at 4AM...", подпись "★★★★★ · Local Guide Level 2 · July 2025 · Google"). Сверка с `reviews/all-reviews.csv`: тексты и ссылки совпадают знак в знак, Local Guide 2 и месяцы совпадают; на старом сайте оба нигде не стояли, на других страницах нового сайта их нет; города в текстах и подписях нет. "super fast", "promptly", "quickly" это слова клиентов, они остаются по решению Дениса от 2 октября.

### 1.4. Фото

На странице три картинки: логотип (дважды, "FPP Plumbing Logo"), знак BBB в подвале и одно фото `/wp-content/uploads/2025/05/fpp-plumber-emergency-truck-frisco-1024x673.png`, alt "FPP Plumbing emergency plumber truck parked in Frisco", под H1, оно же og:image. Видео нет.

Фото я открыл (копия в `site/public/wp-content/uploads/2025/05/`). Это не фото с работы: белый фургон сбоку у кирпичного дома, на борту "EMERGENCY SERVICE 24/7" и "980.899.7997", на крыле "M-38532" (не лицензия компании M-44816, в проекте не объяснён), у окна кабины курсор мыши, номерного знака не видно. Что это Frisco, файлы не подтверждают; в `photos/index.csv` файла нет.

В `photos/captions-en.csv` за этой страницей помечены 12 фото и клипов: 4, 90, 112 (помечен первым фото страницы), 114 и 120 (до и после), 119, 136, 164, 173, 174, 178, 183.

### 1.5. Ссылки

Со страницы в тексте 20 внутренних, внешних нет ни одной:

- Вступление, последний абзац: "plumber near me" на `/` ("The trucks that answer after hours are the ones people in Frisco and Plano already call as their plumber near me on a Tuesday afternoon"). Правило 6 соблюдено.
- "shut-off guide" на гайд перекрытия воды; "emergency plumbing repair cost guide" на гайд цен.
- Список симптомов: "Water heaters leaking" (`/water-heaters/`), "Main line stoppages" (`/drain-services/`), "Slab leaks", "Toilets overflowing", "Shut-off valves that snapped" (гайд angle stop), "Water lines broken" (`/water-lines/`); в разделе мороза "Outdoor faucets" (`/hose-bib-repair-frisco-plano/`).
- Раздел про город: все десять "plumber in Frisco", "plumber in Plano", "plumber in McKinney", "plumber in Allen", "plumber in Prosper", "plumber in Celina", "plumber in Little Elm", "plumber in The Colony", "plumber in Carrollton", "plumber in Lewisville", в одном абзаце текста. Правило 7 соблюдено.

Услуг в тексте 6 из 12 остальных единого списка. Нет: `/clogged-drain-cleaning-frisco-plano/`, `/water-leak-detection-frisco-plano/`, `/water-heater-repair-frisco-mckinney/` (expansion tank), `/prv-replacement-frisco-plano/`, `/garbage-disposal-repair-frisco-plano/`, `/fixture-installation-repair/`. Соседняя `/top-emergency-plumber-calls-frisco/` только в меню. Внешние ссылки только шаблонные: соцсети, `tel:`, "Found us" (share.google), почта, BBB.

На страницу с остальных 63: меню "Emergency Plumbing Services" 189 раз на 62 страницах (по три на 61, на главной шесть; 64-я запись краула, `/blog/author/admin/`, это переадресация 301 на главную). В тексте 41 ссылка с 41 страницы: главная, 11 услуг, все 10 городов, 9 гайдов, 10 постов; анкоры "emergency plumbing" 19 раз, "emergency plumber" 5, остальные по одному или два (`emergency-links-in.md`). Без ссылки в тексте: `/water-heaters/`, `/water-heater-repair-frisco-mckinney/`, служебные страницы, оба хаба, 7 постов, 7 гайдов. На новом сайте эти 41 остаются, и боковой блок каждой страницы услуги и города даёт четыре ссылки сюда (`#p-floor`, `#p-hot`, `#p-sewer`, `#p-pressure`, `NowAside.astro`).

### 1.6. Что идёт против CLAUDE.md, дословно

В конце пункта: остаётся ли это на новой версии (файл страницы и `site/src/lib/schema.ts`). Всего 27 мест.

Услуги. Tankless, reroute, hydro jetting, гильз на странице нет.

1. "Any smell of gas near a water heater, and that one means leave the house first, call the gas utility, then call us." Газ не заявляем, пока Денис не подтвердит, а "then call us" читается как выезд по запаху газа. Остаётся.

Цены. По правилам: "There is an after hours fee and it scales with the hour", "You get the number spoken on the phone before dispatch", "The repair itself is quoted separately, before work begins". $49 не назван.

2. "And if the fix turns out smaller than it looked at two in the morning, the bill follows the work, not the estimate." Правило: цена фиксированная до работы, одобренная цена равна цене в счёте, оценок нет. Остаётся.
3. То же в ответе FAQ 2: "...and if the fix is smaller than it looked at two in the morning, the bill follows the work, not the estimate." Остаётся, и в схеме FAQPage.
4. "That coordination costs you nothing and it saves the part of the repair nobody thinks about until later." Обещание "бесплатно" вне правил цен. Остаётся.
5. "If you want a sense of what night repairs typically run before you call anyone, our emergency plumbing repair cost guide walks through it." Гайд несёт 19 сумм в долларах, от $150 до $5,000 (`site/src/content/pages/plumbing-guide/emergency-plumbing-repair-cost-guide-2026.md`). Остаётся.

Гарантия: сроков нет.

Время приезда. Текст аккуратный ("How fast we reach you comes down to one thing: where the on-call plumber is at the moment you call."), ответ FAQ 8 без цифр.

6. H1 "Licensed, Fast, and Local": цифры нет, но "Fast" в заголовке. Остаётся.
7. Живая схема Service: "a licensed plumber drives out the same night for burst lines, sewage backups, leaking water heaters, main line stoppages and slab leaks." Новая схема строится заново (name = H1, description = meta), фразы нет.

Города и лицензия. В тексте чужих городов нет, Park Cities не названы.

8. Живая схема Organization: "serving Frisco, Plano, McKinney, and surrounding North Dallas communities". "North Dallas" отдельно нельзя. На новом сайте нет.
9. Там же "Texas Master Plumber License M-44816." Нужно "Responsible Master Plumber, License M-44816". На новом сайте нет (hasCredential правильный).

Против фактов Дениса.

10. "A hard freeze changes the whole picture for a few days. Outdoor faucets split, exposed pipe in an attic or a garage lets go". По поправке Дениса уличный кран frost free и при правильной установке не мёрзнет и не лопается, ему нужен чехол; капать оставляют краны в доме (этого на странице нет). Остаётся (в файле нового сайта та же фраза, ссылка стоит на словах "Outdoor faucets").

Границы (правило 9: история в чужую тему говорит об этом одной фразой со ссылкой). У историй про fill valve и бак во втором этаже ссылки есть только в списке выше.

11. "The shower cartridge. Cartridge failed and the water would not stop running." Хозяин `/fixture-installation-repair/`, на странице на неё ссылки нет совсем. Похожие случаи стоят на новой странице Frisco (душ, видео 174) и на главной (кран, "A night call that could have been a morning call"). Остаётся.
12. "The remodel that came apart ... both supply lines to the shower valve had been forced into place crooked and under tension. A compression ring had simply slipped and the pipe had cracked." Хозяин `/fixture-installation-repair/`, ссылки нет. Остаётся.
13. "The pinhole in the attic. A copper supply line feeding a water heater in the attic developed a pinhole." Поиск утечки принадлежит `/water-leak-detection-frisco-plano/`, ссылки нет. Остаётся.
14. "The main line, at the worst possible moment ... We cleared the line that night". Срочная прочистка у `/clogged-drain-cleaning-frisco-plano/`, ссылки на неё нет (список ведёт на `/drain-services/`). Остаётся.
15. "The air conditioning drain ... The AC condensate line runs into the kitchen sink drain, the sink is partly clogged". По CLAUDE.md этот случай принадлежит drain cleaning, он же стоит на главной и на новой Frisco. Ссылки нет. Остаётся.
16. Ответ FAQ 6: "Attic supply lines, a water heater in an upstairs closet, or an air conditioning condensate line backing up will all send water along framing before it drops. Shut the main off first, then let us trace it". Метод поиска у leak detection, ссылки нет. Остаётся.

Телефонов в тексте нет (только шаблонная панель). "Owner" нет ("homeowner" дважды, верно). Тире нет нигде: ни в title, description, H1, тексте, ни в схеме.

FAQ.

17. Девять вопросов тегом H3. На новом сайте жирный текст в `details` (`site/src/components/FAQList.astro`), исправлено макетом.
18. Девять вопросов при норме 5 до 7. Остаётся.
19. Вопросы 1, 8, 9 почти повторяют главную и городские страницы (1.2). Остаётся.

Слоганы и вода.

20. H1 открывается риторическим вопросом "Got a Plumbing Emergency?" Остаётся.
21. Description: три вопроса подряд "Burst pipe? Overflowing toilet? No hot water?" и "nights" с маленькой. Остаётся.
22. Тройки: "Something is leaking, flooding, or backing up"; "Not a machine, not a dispatcher three time zones away ..., not a form promising a callback within one business day"; "a flooring, drywall and cabinet bill"; "Licensed, Fast, and Local". Остаётся.
23. Фразы-итоги: "That is the whole reason this page exists."; "Attic plumbing does not warn you politely."; "That is the whole story."; "None of it would have happened at three in the afternoon." Остаётся.
24. "Nobody has ever been surprised by that line on our paperwork, and nobody is going to be." Остаётся.
25. "and honestly, ten minutes with it on a quiet evening is worth more than anything else on this page"; "That is the honest reason and we are not going to dress it up." Остаётся.

Прочее.

26. og:title "Emergency Plumbing Services" не равен title. На новом сайте og:title берётся из title (`site/src/layouts/Base.astro`), исправлено.
27. Фото фургона с "M-38532" и курсором мыши. На новом сайте то же фото первой картинкой текста и og:image. Остаётся.

### 1.7. Настоящее, из поля

Как материал (текст по правилу 3 пишется заново):

- "Under a sink that is the small oval or football shaped handle on the wall, usually two of them, hot and cold. Behind a toilet it is the same valve on the left side near the floor. Turn it clockwise until it stops."
- "If it is the water heater, there is a valve on the cold inlet at the top of the tank. Close that and the tank stops refilling."
- "do not force it with a wrench, because a snapped gate valve turns one emergency into two"; в FAQ: "Old gate valves that have not moved in years are the most common version of this."
- "if water is anywhere near outlets, a panel, or a ceiling fixture, kill the breaker to that area"
- Списки "Call tonight" и "This can wait until morning" ("A water heater that quit but is not leaking, unless there is a baby or someone elderly in the house"); "Plenty of these calls end with us booking you a normal weekday slot at a normal rate".
- Истории: "builder grade plastic pop-in stop", который давно не работал; бак во втором этаже со сломанным краном: "put in a bypass so the rest of the house could work, and drained the tank down"; посудомойка и стирка в забитую главную линию, сушка через партнёра; ремонт ванной без лицензии, "A compression ring had simply slipped".
- "A stop valve that has never been turned is not a working valve, it is an assumption."
- "We work with a restoration partner and bring them in the same night when a job calls for it" (совпадает с CLAUDE.md).
- Мороз: "the failure usually shows up not during the freeze but on the thaw, when the ice plug melts"; "open a faucet at the lowest point in the house to drain the pressure".
- FAQ 6: "In two story homes it is often not from the room directly above."

Откуда истории, в проекте не записано. В `source/dictation/` есть похожие случаи: картридж в душе (2026-10-02-frisco-additions.md, видео 174), линия кондиционера в раковине (home-text-v4.md, frisco-text-v4.md), бак на чердаке (видео 173). Fill valve, пинхол на чердаке, бак во втором этаже, посудомойка с главной линией и ремонт ванной в диктовках не найдены.

### 1.8. Новая версия против живой

- Текст: title, description, H1, десять H2, весь текст и девять FAQ совпадают с живой страницей слово в слово (разница только в пробелах перед знаками).
- Точечных правок для адреса нет: из 608 строк `site/src/data/launch-changes.csv` ни одной с `url` этой страницы, в `tools/build_launch_content.py` правил для неё нет. Четыре строки с этим адресом внутри относятся к ссылкам на неё с hose bib, top 5 и двух постов (сняты тире).
- Одобренного текста в `source/` нет. Карта ключей: "carry as is, Point fixes only (no approved rewrite yet)". План, группа 3, номер 1: "Делит запросы с главной, нужен сильный текст".
- Макет добавляет: "A licensed plumber is on duty 24/7" над H1; H2 "What is happening right now?" (четыре одобренных ответа из `source/approved-text-edits.md`, фото 47, 6, 96, 48, кнопки обоих офисов, ссылки на slab leak, water heaters, drain cleaning, sewer line, PRV, гайд); H2 "Close the main shut-off valve" (рисунок крана); два отзыва; FAQ жирным. Фото в шапке нет (нет записи в `heroes` файла `design.json`), фургон идёт первой картинкой текста.
- Схема новая: Service (name = H1, description = meta, areaServed десять городов и Park Cities), FAQPage с теми же девятью, WebPage, BreadcrumbList, Organization с правильной лицензией. Пункты 7, 8, 9 не повторяются; hoursAvailable 24/7 в узле Service больше нет.
- Ошибка переноса: список "What We Fix at Two in the Morning" в Markdown одна строка "- Burst supply lines ... • Sewage backing up ... • [Water heaters leaking](/water-heaters/) ...", девять пунктов выглядят одним.
- Меню нового сайта называет страницу "Emergency plumbing" (живое "Emergency Plumbing Services"), og:title равен title: фраза "emergency plumbing services" уходит со страницы совсем (2.3).

## 2. Search Console

Скрипт `gsc_emergency_live.py` и `gsc_emergency_lib.py` в scratchpad `services/emergency`: копии `docs/briefs/_shared/gsc_plano_*.py`, переделанные под страницу услуги (оригиналы не тронуты, `tools/gsc_page_table.py` не запускался). Запрос покрыт, когда каждое значимое слово стоит в тексте; in, tx, near, me не считаются; 24/7 и 24 hour дают 24. Группы: один из десяти городов (с индексами Frisco и Plano), без города, чужое место, чужая компания, бренд. «Срочность»: emergency, 24 hour, 24/7, same day, after hours, night, weekend, urgent, burst, frozen и подобные.

### 2.1. Итоги

| Период | Запросов | Клики | Показы | Место |
|---|---|---|---|---|
| 3 месяца (1 июля до 28 сентября 2026) | 206 | 1 | 8,947 | 24.0 |
| 16 месяцев (31 мая 2025 до 28 сентября 2026) | 915 | 4 | 91,603 | 32.9 |

Итог Google со скрытыми запросами: 3 месяца 2 клика, 9,978 показов, место 23.44; 16 месяцев 7 кликов, 96,031, место 32.5. Доля с известным запросом: 50% кликов и 90% показов за 3 месяца, 57% и 95% за 16.

| Группа | 3 мес: запросов · клики · показы · место | 16 мес |
|---|---|---|
| один из 10 городов | 95 · 0 · 3,671 · 30.2 | 333 · 0 · 57,287 · 37.2 |
| без города | 82 · 0 · 4,570 · 18.3 | 411 · 1 · 31,094 · 24.6 |
| чужое место | 25 · 0 · 328 · 59.0 | 153 · 0 · 1,823 · 65.7 |
| чужая компания | 2 · 0 · 3 · 13.0 | 15 · 0 · 33 · 52.0 |
| бренд | 2 · 1 · 375 · 1.8 | 3 · 3 · 1,366 · 1.9 |
| из всех: срочность | 136 · 0 · 8,184 · 25.5 | 647 · 1 · 77,333 · 35.4 |
| из всех: без срочности | 70 · 1 · 763 · 7.5 | 268 · 3 · 14,270 · 19.8 |

- Каждый запрос трёх месяцев есть в шестнадцати, ни у одного за 3 месяца показов не больше, старый период получен вычитанием: за 13 месяцев до июля 82,656 показов, 3 клика, место 33.9 (с десятью городами 53,616, место 37.7). В месяц это около 6,360 показов тогда и около 2,980 за последние 3 месяца: показов вдвое меньше, место лучше.
- По месту за 16 месяцев: 1,424 показа на местах 1 до 3 (почти все бренд), 1,043 на 3 до 10, 29,305 на 10 до 20, 49,027 на 20 до 50, 10,804 ниже 50.
- Слова: у 577 запросов из 915 (88,234 показа) все слова в тексте, частично 129 (1,068); не хватает чаще всего cleaning (282 показа), sewer (253), urgent (106).

### 2.2. Первые запросы и клики

Первые 30 за каждый период с колонкой главной: `emergency-gsc-summary-tables.md`, разделы 2 и 3; все запросы: `emergency-gsc-table-3m.md`, `-16m.md`. На первые 30 приходится 7,482 показа из 8,947 за 3 месяца и 62,031 из 91,603 за 16. Первые 10 (в скобках главная по тому же запросу):

- 3 месяца: emergency plumbing 797 · 15.4 (2,072 · 13.8); 24 hour plumbers 716 · 12.4 (92 · 19.4); emergency plumber 640 · 19.0 (3,102 · 9.0); 24 7 plumber 471 · 14.9 (755 · 9.6); emergency plumber frisco 411 · 26.6 (1,020 · 9.5); emergency plumbers 385 · 25.6 (1,421 · 13.3); fpp plumbing 374 · 1.8 · 1; emergency plumber frisco tx 315 · 31.6 (460 · 10.6); frisco emergency plumber 314 · 37.6 (349 · 10.1); emergency plumber plano tx 294 · 32.6 (696 · 8.1).
- 16 месяцев: emergency plumber 4,970 · 19.1 (24,723 · 10.1 · 18); emergency plumber plano 4,812 · 33.6 (6,378 · 12.6 · 6); emergency plumbing 4,164 · 18.2 (13,515 · 13.7); emergency plumber frisco 3,823 · 34.3 (8,061 · 11.1 · 9); 24 hour plumbers 3,630 · 14.1 (1,646 · 15.3); 24 7 plumber 3,069 · 14.8 (3,883 · 9.7); frisco emergency plumber 2,856 · 37.7; emergency plumber frisco tx 2,636 · 40.1; emergency plumber plano tx 2,508 · 43.2; plano emergency plumber 2,300 · 45.3. Ниже в списке: same day plumber 1,039 · 18.2 (главная 4,944 · 9.8), emergency plumbing services 868 · 16.4, emergency plumber mckinney 788 · 65.9.

Запросы с кликами всего два: "fpp plumbing" (1 клик за 3 мес, 3 за 16) и "plumber emergency service" (1 клик за 16 мес, 3 · 28.3). Остальные клики Google скрыл (1 за 3 мес, 3 за 16).

### 2.3. Что держат заголовки

Заголовок держит запрос, когда все значимые слова запроса стоят в нём (по запросам: `emergency-gsc-headings.md`). Числа: запросов · показы · клики.

| Заголовок | 3 мес | 16 мес | Держит только он (description не в счёт), 16 мес | Что держит |
|---|---|---|---|---|
| title | 64 · 5,628 · 0 | 130 · 60,397 · 1 | 24 · 1,687 · 1 | emergency plumber, emergency plumber plano, emergency plumbing, emergency plumber frisco, 24 7 plumber; один из заголовков держит "emergency plumbing services" (868 · 16.4), "emergency plumbing service" (202 · 19.6); слова этих двух запросов стоят и в description |
| description | 31 · 1,954 · 1 | 66 · 14,182 · 3 | 9 · 1,503 · 3 | "fpp plumbing" (все клики), "burst pipe plano" (122 · 28.8) |
| H1 | 58 · 5,424 · 0 | 135 · 60,459 · 0 | 32 · 1,985 · 0 | то же, что title; один держит McKinney: "emergency plumber mckinney" (788 · 65.9), "mckinney emergency plumber" (451 · 79.0) и ещё 30 |
| H2 "What a 24 Hour Plumber Costs After Hours" | 10 · 1,513 · 0 | 21 · 7,883 · 0 | 2 · 40 · 0 | "24 hour plumbers" (3,630 · 14.1), "24 7 plumber" (3,069 · 14.8), "24 hour plumber" (515 · 17.1); один держит "after hours plumber" (39 · 21.5) |
| H2 "A 24 Hour Plumber Who Actually Picks Up" | 9 · 1,510 · 0 | 19 · 7,843 · 0 | 0 | те же запросы "24 hour" |
| H2 "24 Hour Plumber Service Area: Frisco, Plano and the Cities Around Them" | 30 · 1,908 · 0 | 61 · 20,562 · 0 | 7 · 2,457 · 0 | один держит "24 hour plumber plano tx" (697 · 34.8), "24 hour plumber plano" (583 · 28.1), "24-hour plumber plano" (578 · 29.2), "24-hour plumber frisco" (410 · 21.8) |
| H2 "Emergency Plumbing FAQ" | 3 · 801 · 0 | 5 · 4,251 · 0 | 0 | единственный заголовок с точной фразой "emergency plumbing" (4,164 · 18.2; за 3 мес 797 · 15.4) |
| остальные шесть H2 и девять вопросов FAQ | 0 | 0 | 0 | ни одного запроса |

Не держит ни один заголовок (кроме description): 569 запросов, 20,710 показов за 16 мес (за 3 мес 102 и 1,750). Самые большие: "24/7 plumber near me" (1,805 · 64.1), "same day plumber" (1,039 · 18.2), "24 7 plumber near me" (798 · 17.4), "emergency plumbing services near me" (787 · 39.4), "pipe breaks plano" (646 · 59.3), "emergency drain service" (551 · 11.5). "near me" нет ни в одном заголовке, "same day" нет нигде на странице.

Что нельзя потерять:

- "Emergency Plumber", "Frisco", "Plano", "24/7" в title и H1, "McKinney" в H1.
- "24 Hour Plumber" хотя бы в одном H2 и в заголовке раздела про города вместе с Frisco и Plano.
- Точная фраза "Emergency Plumbing" в заголовке и "After Hours" в H2.
- "Emergency Plumbing Services": на живом сайте в og:title и меню каждой страницы, на новом её нет; запрос за 3 месяца на месте 10.1, лучшее место страницы среди больших запросов без бренда.

### 2.4. Фраза целиком

Проверены первые 20 запросов за каждый период и запросы с кликами, всего 25 (таблица: `emergency-gsc-summary-tables.md`, раздел 7). Точная фраза стоит только у четырёх: "emergency plumber" (title, H1, alt фото), "emergency plumbing" (H2 "Emergency Plumbing FAQ" и анкор "emergency plumbing repair cost guide"), "24 hour plumber" (три H2 и вступление: "the whole difference between a 24 hour plumber and a company that only advertises as one"), "fpp plumbing" (description, alt).

Нет точной фразы у 21, в том числе у всех "emergency plumber" и "emergency plumbing" с Frisco и Plano, "24 hour plumbers", "24 7 plumber", "emergency plumbers", запросов с "near me" и "plumber emergency service". Без учёта "in" и множественного числа слова подряд стоят в title и H1 у "emergency plumbers", "emergency plumber frisco", "emergency plumber frisco tx" и в H2 у "24 hour plumbers". С Plano связки нет нигде ("Frisco & Plano"), а "emergency plumber plano" второй запрос страницы за 16 месяцев (4,812 · 33.6). "24 7 plumber" подряд нигде: title "24/7 Plumbing Service", H1 "24/7 Emergency Plumber".

### 2.5. Другие страницы на тех же запросах

Срочные запросы всего сайта (без чужих мест, компаний и бренда): за 16 месяцев 1,369 запросов, 427,698 показов, страница emergency показывается по 491 и берёт 75,506; за 3 месяца 515 запросов, 55,105 показов, страница по 111, 7,856.

| Страница | 16 мес: срочных запросов · показы · клики · место | Выше emergency: запросов · показы | 3 мес: показы · место; выше |
|---|---|---|---|
| `/` | 807 · 219,909 · 46 · 19.1 | 233 · 147,650 | 22,201 · 11.7; 71 · 20,937 |
| `/plumber-frisco-tx/` | 165 · 18,045 · 3 · 25.7 | 74 · 11,229 | 6,045 · 12.6; 38 · 4,883 |
| `/plumber-plano-tx/` | 208 · 12,434 · 2 · 25.1 | 86 · 10,953 | 7,400 · 4.0; 53 · 6,139 |
| `/plumber-the-colony-tx/` | 48 · 10,784 · 0 · 22.8 | 22 · 8,704 | 1,491 · 12.3; 13 · 617 |
| `/plumber-little-elm-tx/` | 20 · 8,644 · 1 · 29.3 | 8 · 6,712 | 1,356 · 19.7; 2 · 271 |
| `/plumber-allen-tx/` | 45 · 8,377 · 0 · 29.3 | 19 · 6,520 | 43 · 26.7; 1 · 1 |
| `/water-lines/` | 71 · 8,352 · 0 · 42.6 | 10 · 4,543 | 364 · 22.9; 0 |
| гайд цен emergency | 133 · 1,915 · 0 · 35.7 | 8 · 172 | 1,188 · 27.9; 3 · 6 |
| `/top-emergency-plumber-calls-frisco/` | 22 · 1,308 · 0 · 38.8 | 7 · 261 | 12 · 28.6; 1 · 2 |

Главные столкновения за 16 месяцев (числа главной по самым большим запросам в 2.2): "emergency plumber" ещё Frisco 3,820 · 9.0 и Plano 1,797 · 2.6; "emergency plumber the colony" The Colony 1,696 · 18.6, emergency 40 · 80.9; "pipe breaks frisco tx" water lines 1,612 · 52.0, emergency 169 · 89.7; "emergency plumber lewisville" Lewisville 1,478 · 35.6, emergency не показывается. За 3 месяца по "emergency plumber": главная 3,102 · 9.0, Frisco 1,887 · 3.4, Plano 1,774 · 2.3, emergency 640 · 19.0 (места 2 до 4 без названия города похожи на карточки офисов в Google). Полный список: `emergency-gsc-other-pages.md`.

Карта ключей: "emergency plumber frisco" и "emergency plumber plano" вторичные ключи этой страницы; "emergency plumber little elm", "emergency plumber prosper", "emergency plumber the colony" вторичные ключи этих городов; срочность с McKinney, Allen, Celina, Carrollton, Lewisville в карте не закреплена ни за кем.

Обратное: запросы этой страницы, которые по карте ключей или правилам принадлежат другой странице, за 16 месяцев 311 запросов и 15,939 показов (за 3 месяца 799):

- `/plumber-frisco-tx/`, 9,658 показов (must not target этой страницы: "plumber + city"): frisco plumber 1,741 · 28.1, plumber frisco tx 1,616 · 15.8, plumber frisco 1,269 · 19.3, plumbers frisco 669 · 15.0. За 3 месяца таких показов 189.
- `/`, 2,747: fpp plumbing 1,360 · 1.9, plumber near me 281 · 23.9, same day plumber near me 280 · 24.7, plumber 121 · 34.3.
- `/plumber-plano-tx/`, 1,303: plumbers plano 781 · 8.1, plumber near me plano 192 · 43.0.
- `/clogged-drain-cleaning-frisco-plano/`, 869: emergency drain service 551 · 11.5, emergency drain cleaning plano tx 143 · 66.8, emergency drain cleaning frisco 130 · 19.1.
- Little Elm 282 (emergency plumber little elm 237 · 39.4), `/drain-services/` 282, остальные 11 страниц вместе 798.
- Сверх этого ничьи по карте 1,916: pipe break и burst pipe 1,696 (pipe breaks plano 646 · 59.3, pipe breaks plano tx 283 · 43.7), прочее без срочности (last minute plumber 99 · 61.2).

### 2.6. Срочность с каждым из десяти городов

Запросы со словом срочности и городом, весь сайт, 16 месяцев (показы · место). По всем страницам: `emergency-gsc-cities.md`.

| Город | Показы сайта | Emergency | Главная | Страница города | Больше всех | 3 мес: emergency; больше всех |
|---|---|---|---|---|---|---|
| Frisco | 85,287 | 19,075 · 37.2 | 30,631 · 12.6 (10 кл.) | 8,928 · 41.2 | главная | 1,651 · 34.4; главная 3,124 · 10.2 |
| Plano | 75,574 | 21,894 · 39.9 | 28,558 · 16.3 (10 кл.) | 7,323 · 39.6 | главная | 1,701 · 27.9; главная 3,732 · 8.2 |
| McKinney | 11,917 | 2,399 · 67.9 | 6,803 · 48.4 | 1,918 · 75.6 | главная | 15 · 36.9; Frisco 60 |
| Allen | 8,634 | 758 · 50.8 | 751 · 51.9 | 7,016 · 29.2 | Allen | 0; Allen 40 |
| Prosper | 2,130 | 118 · 48.6 | 649 · 28.0 | 1,213 · 14.6 | Prosper | 33 · 45.0; Prosper 203 |
| Celina | 227 | 0 | 21 · 1.0 | 175 · 10.4 | Celina | 0; Plano 13 |
| Little Elm | 13,113 | 874 · 55.2 | 2,044 · 50.5 | 8,626 · 29.3 | Little Elm | 1 · 79.0; Little Elm 1,355 |
| The Colony | 15,359 | 526 · 82.4 | 4,466 · 16.0 | 9,544 · 23.6 | The Colony | 9 · 87.3; The Colony 972 |
| Carrollton | 8,606 | 94 · 76.9 | 1,160 · 37.9 | 7,054 · 56.0 | Carrollton | 0; Plano 201 |
| Lewisville | 8,235 | 47 · 81.5 | 594 · 80.6 | 7,448 · 49.9 | Lewisville | 0; Lewisville 153 |

По Frisco и Plano срочность берёт главная, emergency вторая по показам, но на 35 до 40 месте; городские страницы за 3 месяца поднялись (Frisco 2,320 · 23.8, Plano 2,540 · 6.8). По Frisco заметную долю берёт ещё `/water-lines/` (5,716 · 36.2, "pipe breaks frisco"). По восьми остальным срочность берут свои городские страницы, emergency на 49 до 82 месте или не показывается.

### 2.7. Слова, которые на страницу не идут

По словам: `emergency-gsc-set-aside.md`. Запрос с двумя словами одного вида считается один раз.

| Что отложено | Примеры (показы за 16 мес) | 3 мес: запросов · показы | 16 мес |
|---|---|---|---|
| Места вне десяти городов | Rockwall 642, Coppell 343, Fife 242, Lake City 102, Galilee 63, Dallas, Denton, Murphy, Richardson, Melissa, Fairview, Сидней, всего 97 мест | 25 · 328 | 154 · 1,824 |
| Услуги и темы не наши | heating 187, government 54, septic и pumping 51, repiping 38, commercial 36, excavation 21, sump, lining, boiler, basement | 7 · 72 | 38 · 445 |
| Оценки и цена | cost 111, how much 42, best 25, cheap, reliable, recommend, free, guarantee | 4 · 9 | 56 · 200 |
| Сроки приезда | last minute plumber 99, 1 hour plumber, fastest emergency response | 1 · 1 | 6 · 104 |
| Чужие компании и марки | pf plumbing, bfp plumbing, fb plumbing pro, f&m plumbing, roy the plumber, rooter | 2 · 3 | 16 · 34 |
| Опечатки | pluming 25, plubers, emeegency, emergeny, plummers | 2 · 2 | 9 · 33 |
| Голосовые и служебные | "google find me a plumber" 26, site: 6 | 1 · 1 | 3 · 32 |
| Длинные вопросы, 8 слов и больше | "how do emergency plumbing services in plano work?" (34 · 14.1), "how quickly can an emergency plumber in frisco typically respond?" (30 · 11.6) | 5 · 17 | 36 · 124 |

Один запрос называет и Dallas, и Plano с McKinney, поэтому мест 154, а в группе "чужое место" (2.1) 153.

### 2.8. Проверка итогов

Итоги посчитаны тремя способами: модулем csv, разбором строк без него (в скрипте, с остановкой при расхождении) и awk. Все три: 3 месяца 206 запросов, 1 клик, 8,947 показов, место 23.97; 16 месяцев 915, 4, 91,603, место 32.95. Те же числа в `source/gsc/page-query-coverage.csv`. Руками сверены строки "emergency plumber" (главная 24,723 · 10.13 · 18, страница 4,970 · 19.15), "emergency plumber plano", "24 hour plumbers", "same day plumber", "plumber emergency service" за 16 месяцев и "emergency plumbing", "24 7 plumber" за 3 месяца. Группы дают итог: 95 + 82 + 25 + 2 + 2 = 206, 333 + 411 + 153 + 15 + 3 = 915.
