# Garbage disposal repair: живая страница и Search Console (3 октября 2026)

Страница: https://fppplumbing.com/garbage-disposal-repair-frisco-plano/ . Сейчас не переписывается, текста страницы здесь нет.

Откуда данные. Обход живого сайта от 30 сентября 2026 (`source/crawl/pages/*.json`, код `source/crawl/html/`); новый сайт `site/src/content/pages/garbage-disposal-repair-frisco-plano.md` и сборка `site/dist/` от 3 октября 10:38; правки `tools/build_launch_content.py`, `site/src/data/launch-changes.csv`; отзывы `reviews/`; Search Console `source/gsc/` (выгрузка 30 сентября 2026); `seo/keyword-map.md`, `docs/pages-plan.md`; слова Дениса `source/dictation/2026-10-02-frisco-additions.md`.

Одобренного текста для этой услуги в `source/` нет.

Длинные таблицы в `docs/briefs/services/garbage-disposal/`: `gd-gsc-table-3m.md` и `gd-gsc-table-16m.md` (все запросы, слова в живом тексте, точная фраза, лучшая другая страница), `gd-gsc-top30-and-clicks.md` (первые 30 и запросы с кликом), `gd-gsc-other-pages.md` (запросы про измельчитель на других страницах).

Числа через точку всегда в одном порядке: показы · место · клики.

## Коротко

1. Кормит сейчас мало. За 3 месяца 1 клик (запрос скрыт), 7,121 показ, среднее место 19.0 (итог Google). За 16 месяцев 4 клика, 32,829 показов, место 30.8. Известный запрос с кликом один: "plano garbage disposal repair" (1 клик за 16 месяцев). В `docs/pages-plan.md` она пятая в группе 3 («усиливаем смело»).
2. Место выросло: за 13 месяцев до июля 2026 среднее место по известным запросам 33.6, за последние 3 месяца 18.8. Запросы почти все одной формы: "garbage disposal repair" плюс город (Plano, Frisco, Little Elm, McKinney).
3. Нельзя потерять: начало title "Garbage Disposal Repair in Frisco & Plano" (все слова 25 запросов, 17,658 показов за 16 месяцев) и начало H1 "Garbage Disposal Repair" (точная фраза "garbage disposal repair": 6,380 показов, самый большой запрос). Ни один H2 и ни один вопрос FAQ сейчас запросов не держит.
4. Против правил: цены "$229" и "$400-500" (текст, два ответа FAQ, схема), рассказ про 10 лет гарантии производителя с обещанием "the manufacturer sends you a new one free" (этого нет в словах Дениса), фразы о времени ("usually the same day you call", "takes under an hour", "the truck is usually nearby"), город "Plano, TX" в подписи отзыва без города в тексте, лозунги, "thousands of kitchens".
5. На новом сайте точечной правкой исправлено только описание (убрана гарантия, "same-day service" осталось); шаблон сам убрал цены из узла Service, H2 с телефонами и тег H3 у вопросов FAQ, отзыв Lanessa с подписью "Plano, TX" заменён другими. Цены, гарантия и фразы о времени в тексте и FAQ стоят там как на живой странице, цены попали и в схему FAQPage.
6. Не хватает по правилу 8: H2 с содержанием 6 (нужно 10 до 16), нет списка «симптом, ссылка», нет раздела «если это происходит сейчас» в тексте, своего текста 1,434 слова против 2,500, на города 5 ссылок из 10 с голыми анкорами ("Frisco", не "plumber in Frisco"), нет ссылки на гайд по перекрытию воды в тексте (на новом сайте блок шаблона «What is happening right now?» даёт ссылки на emergency и на гайд по главному крану, но это не раздел текста). Ссылка на главную "plumber near me" есть, но привязана к услуге и стоит в риторическом вопросе.
7. Повтор внутри сайта: около 160 слов этой страницы слово в слово стоят на старой странице McKinney (раздел "Garbage Disposals, and When to Stop Repairing Them" и два ответа FAQ), а title McKinney содержит "Garbage Disposal Repair".
8. Другие страницы: страница Plano за 3 месяца показывается по 33 запросам про измельчитель (933 показа, среднее место 2.5; по 18 из них место 3 и выше, 723 показа: это карточка Google Plano с кнопкой сайта), главная за 16 месяцев взяла 5,542 показа и 1 клик ("garbage disposal repair plano"), почти всё до июля 2026; городские страницы Little Elm, The Colony, Lewisville, Allen, Carrollton показываются по «измельчитель плюс свой город» за 16 месяцев на местах от 47 до 68 по запросам с 40 показами и больше (среднее по странице от 49.0 до 62.0).
9. Отложить: 96 запросов с чужими местами (3,439 показов за 16 месяцев, больше всего Dallas, Rockwall, Coppell, Richardson) и 48 запросов с невидимым знаком.

## 1. Живая страница

### 1.1. Title, описание, H1, заголовки, объём

| Что | Живая страница |
|---|---|
| Title (67 знаков) | "Garbage Disposal Repair in Frisco & Plano \| Jammed or Leaking Unit?" |
| Meta description (141 знак) | "Disposal humming, jammed, or leaking from the bottom? Honest repair or replace advice, same-day service, and a 10-year warranty on new units." |
| H1 | "Garbage Disposal Repair and Replacement, Done in One Visit" |
| OG title | "Garbage Disposal" (не совпадает с title) |
| OG картинка | `/wp-content/uploads/2025/05/new-garbage-disposal-and-p-trap-frisco.jpg` |
| Даты в схеме | опубликована 6 мая 2025, изменена 17 августа 2026 |

H2 по порядку (в скобках слов в разделе по тексту обхода; считаются только слова, запятые, которые обход отбил пробелом перед ссылками, не в счёт):
1. "Humming, Tripping, Leaking: What Each One Means" (218)
2. "Why Cheap Builder-Grade Units Die Young" (149)
3. "Use It or Lose It" (123)
4. "The Dishwasher Connection Most People Never Check" (223)
5. "What We Install and What It Costs" (198)
6. "Disposal Quit Mid Dinner Prep?" (58)
7. "Garbage Disposal FAQ" (дальше семь вопросов H3)
8. "What Our Customers Say" (блок отзыва)
9. "980-899-7997 469-998-8999" (не раздел: два телефона нижней панели свёрстаны тегом H2, шаблон старого сайта)

H3: семь, все семь это вопросы FAQ (пункт 1.2). Других H3 нет.

Объём. Обход: 1,530 слов (обход считает по пробелам, и 7 запятых, отбитых пробелом перед ссылками, и 5 знаков подписи отзыва, звёзды и точки, идут у него как слова; одних слов 1,518). Свой текст от H1 до конца FAQ: 1,434 слова (H1 9, вступление 122, шесть разделов 969, семь заголовков H2 вместе с "Garbage Disposal FAQ" 40, FAQ 294). Блок отзыва 58, последняя строка 24, кнопка 2. До ориентира 2,500 не хватает около 1,070 слов.

Ключи в своём тексте: "garbage disposal" 5 раз (title, H1, H2 FAQ, вопрос FAQ про цену, alt фото), "garbage disposal repair" 2 раза (title и H1), в абзацах ни разу: в тексте везде просто "disposal". "plumber near me" 1 раз (ссылка на главную).

### 1.2. FAQ: семь вопросов слово в слово

1. "How much does garbage disposal installation cost?"
2. "My disposal hums but does not spin. Is it dead?"
3. "My disposal leaks from the bottom. Can it be repaired?"
4. "What size disposal do I actually need?"
5. "How often should I run my disposal?"
6. "Can you install a disposal I bought myself?"
7. "Why does my dishwasher need an air gap or a high loop?"

Все семь тегом H3 (`e-n-accordion-item-title-text`) в раскрывающемся списке Elementor; по правилу 8 вопрос должен быть жирным текстом. Повторы на сайте: вопрос 3 почти дословно на McKinney ("My disposal leaks from the bottom. Can it be fixed?", ответ почти тот же), вопрос 4 по смыслу там же ("What size garbage disposal should I get?", тот же ответ про 3/4, 1 и 1/2 HP). Остальные пять нигде больше не стоят. В схеме FAQPage вопросы 6 и 7 поменяны местами, ответ 6 в схеме с точкой в конце, на странице без. Ответы 1 и 6 называют цены (пункт 1.6). На новом сайте вопросы и ответы те же.

### 1.3. Отзыв на живой странице

Один отзыв.
- Текст: "Our old garbage disposal motor burned out, and they had a new one installed in no time! The tech was on time, explained everything and left the area spotless. The new unit runs perfectly. Highly recommend"
- Lanessa Arnold Jenkins, подпись "★★★★★ · Plano, TX · Local Guide Level 5 · May 2025 · Google", ссылка https://maps.app.goo.gl/755CBZnLn94Ra5Ue8?g_st=ic (три раза). Над отзывом "Real Google reviews from local homeowners."
- Архив `reviews/all-reviews.csv`: Google, профиль Plano, 19 мая 2025, `on_old_site` = эта страница. Текст совпадает знак в знак, месяц совпадает.
- Против правила 11: в тексте отзыва города нет, а в подписи стоит "Plano, TX". Уровень Local Guide в архиве пустой, проверить "Level 5" по файлам нельзя; по правилу `tools/build_site_reviews.py` отзыв Google с неизвестным уровнем на сайт не ставится.
- Ответ компании в архиве называет другой город: "garbage disposal replacement in Frisco, TX". Город работы по файлам не ясен.
- В архиве есть строка Yelp "Lanessa A." той же даты; в её текст склеен чужой отзыв ("Lisa M. …"), это ошибка разбора Yelp.
- На новом сайте Lanessa нет нигде (`site-ledger.md`, `site-reviews.json`); на этой странице там Sonja S. (Yelp, август 2025, "Excellence was provided in quality of work and interactions. Value was good for a garbage disposal replacement…") и Madison h. (Thumbtack, июнь 2023, "Came within 30 minutes on a weekend!…", слова клиента, не правятся).

### 1.4. Фото

Одно настоящее фото с работы: `/wp-content/uploads/2025/05/new-garbage-disposal-and-p-trap-frisco-967x1024.jpg` (полный файл 1209 на 1280), alt "New garbage disposal and P-trap installed under kitchen sink in Frisco home". Новый Moen под мойкой, белый P-trap, шланг посудомойки. Стоит первым под H1 и грузится «лениво» (`data-src`), хотя это первый экран. Остальное шаблон: логотип дважды, знак BBB, пустая заглушка аватара в карточке отзыва.

В `photos/index.csv` этого файла нет. По виду это та же установка, что фото 115 архива (тот же шкаф, Moen, шланги; сравнил на глаз), а у 115 город по месту съёмки Plano: "in Frisco home" в alt по файлам не подтверждается. Фото 115 стоит на плитке услуги на главной нового сайта.

Для этой страницы в `photos/captions-en.csv` записаны ещё пять настоящих фото: 69 (новый Moen 3/4 HP, Little Elm), 103 (новый Moen и сливная линия, пол шкафа испорчен долгой течью, McKinney), 115 (Moen под мойкой, Plano), 123 и 124 (старый и новый, до и после, Little Elm). Видео нет.

### 1.5. Ссылки

Со страницы, в тексте (9 внутренних, 1 внешняя): "plumber near me" на `/` (вступление, второй и последний абзац); "shut-off valve replacement" на `/fixture-installation-repair/` (Humming, Tripping, Leaking); "drain" на `/clogged-drain-cleaning-frisco-plano/` (Use It or Lose It); "emergency plumbing" на `/emergency-plumbing-services/` и "Frisco", "Plano", "McKinney", "Allen", "Little Elm" на пять городских страниц (Disposal Quit Mid Dinner Prep?); внешняя "Moen 3/4 HP disposal" на https://shop.moen.com/collections/garbage-disposals (What We Install).

Предложение с городами: "Wherever you are, from Frisco to Plano , McKinney , Allen , or Little Elm , the truck is usually nearby." Нет ссылок на Prosper, Celina, The Colony, Carrollton, Lewisville. Нет ссылок на гайд по главному крану, на гайд про кран под раковиной (angle stop), на `/drain-services/`, на посты про засор кухонной мойки.

Шаблон: всего 112 внутренних ссылок, из них 9 в тексте; меню трижды, офисы, Privacy Policy, "Request Service". Внешние: соцсети иконками, `tel:`, три ссылки на отзыв, "Found us" (share.google), почта, знак BBB.

На страницу с остальных 63 страниц: шаблонное "Garbage Disposal" 188 раз (по 3 в меню на каждой странице с содержимым, на главной 5; `/blog/author/admin/` отдаёт 301 и ссылок не несёт). Ссылки в тексте:

| Страница | Анкор | Где |
|---|---|---|
| `/` | "Garbage Disposal Service" (H3 плитки) и картинка плитки без анкора | плитки услуг |
| `/plumber-frisco-tx/`, `/plumber-plano-tx/` | "Garbage disposal repair" | списки "• Garbage disposal repair and replacement" и "• Garbage disposal repair and installation" |
| `/plumber-mckinney-tx/` | "garbage disposal repair" (2 раза) | "Our garbage disposal repair page has the full pricing." и список услуг |
| Allen, Carrollton, Celina, Lewisville, Little Elm, Prosper, The Colony | "garbage disposal repair" | список "Humming, jammed, (or) leaking underneath: garbage disposal repair" |
| `/blog/plumber-frisco-kitchen-drain-clog/` | "garbage disposal" | "He did everything right before calling: cleaned the P-trap, checked the garbage disposal , even bought a small hardware store snake…" |

Все десять городских страниц ссылаются сюда; сервисные страницы, гайды и остальные посты только через меню. На новом сайте в тексте ссылаются девять городских страниц (на McKinney два раза), Frisco (пункт "Garbage disposals that jam or leak"), пост про засор кухни и плитка главной.

### 1.6. Что идёт против CLAUDE.md, дословно

«Новый сайт»: стоит ли это в файле новой страницы после точечных правок. Всё из этого раздела там стоит, кроме гарантии в описании, цен в узле Service, схемы организации живой страницы, H2 с телефонами и тега H3 у вопросов FAQ (у каждого пункта отмечено). "same-day service" в описании на новом сайте осталось.

**Услуги, которых FPP не делает или не заявляет.** Tankless, reroute, hydro jetting, газа нет. В фактах CLAUDE.md не записано, но и не запрещено: установка измельчителя клиента ("$229 for professional installation if you supply your own unit", вопрос "Can you install a disposal I bought myself?").

**Цены** (разрешена только $49 за выезд в будни; $49 на странице нет вовсе):
- What We Install: "The numbers, up front as always: $229 for professional installation if you supply your own unit , or $400-500 complete with our Moen 3/4 HP installed, sealed, and tested." Новый сайт: стоит (в журнале правок «flag not changed»).
- FAQ 1: "$229 for installation if you supply the unit, or $400-500 complete with our Moen 3/4 HP disposal, installed and tested, backed by a 10-year manufacturer warranty." FAQ 6: "Yes, that is the $229 option." Новый сайт: оба стоят, и в схеме FAQPage.
- Схема Service: Offer с price 229 и Offer с minPrice 400, maxPrice 500. Новый сайт: нет.
- По правилу сходится: "No separate parts bill afterward. The price you hear before we start is the price you pay after." и "Nights and weekends run through our emergency plumbing line with the after hours fee named before we roll out." (праздники не названы).

**Сроки гарантии.** Гарантия на нашу работу не названа нигде. Названа гарантия производителя Moen, 10 лет: это есть в записи диктовки Дениса от 2 октября (`source/dictation/2026-10-02-frisco-additions.md`, запись по-английски с его русских слов: "We mostly use Moen, 3/4 horsepower, with a ten year manufacturer warranty"), и это стоит на новой странице Frisco; но 3 октября из описания этой страницы её убрали как «срок гарантии».
- Meta: "…and a 10-year warranty on new units." Новый сайт: убрано.
- What We Install: "Our standard unit is a Moen 3/4 HP disposal backed by a 10-year manufacturer warranty, one of the longest in the business. If anything happens to the unit inside those ten years, the manufacturer sends you a new one free. That warranty length is the factory betting on its own build quality, and it is why we stopped installing the cheap stuff." Новый сайт: стоит. Что производитель «присылает новый бесплатно», в файлах проекта не подтверждено.
- FAQ 1 (выше) и Offer в схеме "Moen 3/4 HP disposal installed, 10-year manufacturer warranty" (на новом сайте схемы нет).
- "The short manufacturer warranty on those units tells you everything." сходится со словами Дениса (один год у дешёвых моделей).

**Время в своих словах.** Часов и минут приезда нет, но стоят (и на новом сайте): "We handle all three across Frisco, Plano, and the surrounding cities, usually the same day you call."; "Same day is the normal case. You call, we name a real window, and the swap itself usually takes under an hour." (час про работу); "Wherever you are, from Frisco to Plano , McKinney , Allen , or Little Elm , the truck is usually nearby." (намёк на быстрый приезд); "If the fix is a jam and a five minute reset, that is what you pay for."; H1 "…Done in One Visit" и "same-day service" в описании (H1 держит запрос, пункт 2.3). В отзыве на новом сайте "Came within 30 minutes on a weekend!" (Madison h.) это слова клиента.

**Другие города.** В тексте запрещённых нет, "the surrounding cities" без названий. Схема живой страницы: `areaServed` 8 городов (нет Prosper и Celina), в описании организации "surrounding North Dallas communities" (по правилу область называется только "North Dallas suburbs") и "Texas Master Plumber License M-44816" (снятая формулировка). На новом сайте схема своя: один узел Plumber, десять городов и Park Cities.

**Граница с другими страницами (правило 9).**
- "While we are under there, the supply lines and shut-off valve replacement usually deserve a look too, since the parts under a sink tend to age together." Одно предложение со ссылкой на `/fixture-installation-repair/`, это разрешено; тема крана под раковиной по карте ключей у гайда `/plumbing-guide/angle-stop-valve-leaking-under-sink/` (замороженный).
- "A good share of the kitchen backups we clear started with a disposal being treated like a trash can." Засоры кухни это `/clogged-drain-cleaning-frisco-plano/`; ссылка "drain" абзацем выше.
- С другой стороны границу переходит старая McKinney: H2 "Garbage Disposals, and When to Stop Repairing Them", два вопроса FAQ, title "Plumber in McKinney, TX | Slab Leak & Garbage Disposal Repair". Около 160 слов совпадают дословно (цепочки из 8 слов), например "A disposal that hums but will not spin is jammed", "because it was the cheapest thing that passed inspection" (на McKinney дальше "installed in a house where somebody actually cooks", здесь без "installed"), "run it every day or two with cold water, even for a few seconds with nothing in it", ответы FAQ про течь снизу и размер. На новом сайте McKinney несёт это так же.

**Телефоны в тексте.** Нет. Только шаблон: нижняя панель звонка тегом H2 "980-899-7997 469-998-8999" (на новом сайте нет).

**Owner.** Нет. **Тире.** Нет ("$400-500" это дефис). **FAQ тегом заголовка.** Все семь H3; на новом сайте шаблон даёт жирный текст.

**Лозунги, вода, вопросы, тройки:** H2 "Use It or Lose It", "Disposal Quit Mid Dinner Prep?" (вопрос), "Humming, Tripping, Leaking: What Each One Means" (тройка); "Searched for a plumber near me because the sink is full and the disposal just clicks?" (риторический вопрос; в нём ссылка на главную, привязанная к услуге, против правила 6); "Here is the honest version, and we would rather you hear it from us than learn it twice"; "the smart money says replace it"; "Anyone who tells you otherwise is selling you a visit."; "It still works, right up until it does not."; "share the same biography"; "gravity does what gravity does"; "Nobody sets out to do it wrong."; "one of the longest in the business"; "The numbers, up front as always"; "because this is where other companies start adding lines to the invoice"; тройки "It grinds faster, jams less, runs quieter, and lasts." и "gum up, rust, and die young".

**Без подтверждения** (правило 13, факты CLAUDE.md, диктовки): "From our experience across thousands of kitchens here"; "A licensed plumber arrives with a new unit already on the truck"; "it is why we stopped installing the cheap stuff"; "Tell us what the disposal is doing and we will tell you whether it is a repair or a replacement before anyone comes out."

### 1.7. Что на живой странице стоит сохранить по сути

Подтверждено словами Дениса 2 октября (дешёвые модели застройщика на 1/3 или 1/2 л.с., гарантия производителя год, засоры и заклинивание, через два или три года течь снизу, измельчители в основном меняют, а не чинят; ставим в основном Moen 3/4 л.с. с гарантией производителя 10 лет):
- "a basic 1/3 or 1/2 HP unit, installed by the builder because it was the cheapest thing that passed inspection, in a house where somebody actually cooks."
- "They rust from the inside out and eventually leak from the bottom"
- "disposals mostly do not get repaired. Outside of a simple jam or a loose drain connection, once a unit starts causing problems…" (суть)
- "Our standard unit is a Moen 3/4 HP disposal backed by a 10-year manufacturer warranty"

Только из старого текста, в диктовках нет:
- Три признака: "A disposal that hums but will not spin is jammed. Something hard is wedged between the impellers and the motor is fighting it.", "A disposal that trips its reset every week is a tired motor", "A disposal leaking from the bottom is done… That is the internal seal or the housing itself, and neither is repairable."
- Шкаф: "water sitting on particle board swells it permanently and then the cabinet becomes the expensive part" (к этому подходит фото 103: пол шкафа испорчен долгой течью).
- Размер: "3/4 HP is the sweet spot for a normal family of three or four who cook regularly", 1 HP для больших семей, 1/2 HP для кухни, где почти не готовят.
- Уход: "run it every day or two with cold water, even for a few seconds with nothing in it"; не бросать "grease, coffee grounds, bones, fibrous peels, and eggshells by the bowl".
- Посудомойка, своя тема страницы, на других страницах её нет: "an air gap, the small chrome fitting you sometimes see on the counter behind the faucet, or at minimum a high loop" и "that dirty water has an open path straight into the bottom of your dishwasher."
- Что входит в замену: новый трап и tailpiece, новые прокладки и уплотнение фланца, линия посудомойки с новым хомутом, проверка всех соединений под мойкой водой, старый блок увозим ("We replace the drain trap and the tailpiece rather than reusing tired parts that will weep in six months…").
- Вопросы FAQ 2, 3, 5, 7 по сути годятся (3 и 4 повторяются на McKinney).

### 1.8. Новый сайт против живой страницы

- Старый текст с точечными правками; одобренного текста из `source/` нет. Title, H1, шесть H2 и семь вопросов FAQ те же.
- Точечная правка одна (`build_launch_content.py`, «meta description point fix», 3 октября): описание "Disposal humming, jammed, or leaking from the bottom? Honest repair or replace advice and same-day service in Frisco and Plano." (127 знаков).
- Отзывы: вместо Lanessa Arnold Jenkins стоят Sonja S. (Yelp) и Madison h. (Thumbtack). Строки "What Our Customers Say" и "Real Google reviews from local homeowners." лежат в front matter, но шаблон их не выводит; если вывести, слово "Google" будет неверным.
- Три цены помечены «flag not changed»: стоят в тексте, в FAQ и через FAQ в схеме FAQPage. Узел Service без цен.
- От шаблона: вопросы FAQ жирным текстом, блок «What is happening right now?» рядом с текстом (разделы страницы emergency и гайд по главному крану), один узел Plumber, десять городов и Park Cities в `areaServed`, `noindex`. H2 с телефонами нет.
- Своего текста 1,449 слов без H1 и с последней строкой (1,155 в теле с заголовками, 294 в FAQ). Это те же слова, что на живой странице: 1,434 с H1 9 и без последней строки 24.

## 2. Search Console

### 2.1. Итоги

| Период | Запросов | Клики | Показы | Место по показам | Итог Google со скрытыми | Доля известных: клики, показы |
|---|---|---|---|---|---|---|
| 3 месяца (1 июля до 28 сентября 2026) | 137 | 0 | 6,718 | 18.8 | 1 клик, 7,121 показ, место 18.99 | 0%, 94% |
| 16 месяцев (31 мая 2025 до 28 сентября 2026) | 254 | 1 | 30,876 | 30.4 | 4 клика, 32,829 показов, место 30.82 | 25%, 94% |

13 месяцев до июля 2026 (вычитанием, все запросы 3 месяцев есть в 16): 24,158 показов, место 33.6, 1 клик.

По группам:

| Группа | 3 мес: запросов · показы · место | 16 мес: запросов · показы · место · клики |
|---|---|---|
| город из десяти | 35 · 2,989 · 12.9 | 63 · 19,507 · 31.2 · 1 |
| без города | 28 · 2,406 · 14.5 | 94 · 7,929 · 17.3 · 0 |
| другое место | 73 · 1,322 · 40.0 | 96 · 3,439 · 56.2 · 0 |
| служебный запрос site: | 1 · 1 · 26.0 | 1 · 1 · 26.0 · 0 |

По месту страницы: за 3 месяца на местах от 1 до 10 стоят 20 запросов (1,168 показов), от 10 до 20 ещё 39 (3,851), от 20 до 50 59 (1,512), ниже 50 19 (187). За 16 месяцев от 10 до 20 стоят 45 запросов с 14,243 показами и тем одним кликом.

Отдельно: 16 запросов про кнопку reset ("garbage disposal reset button" 51 показ, место 1.7, и другие) за 16 месяцев дали 79 показов на месте 1.6, за последние 3 месяца ни одного. "air gap for garbage disposal" и "garbage disposal air gap" по 2 показа на месте 2.

### 2.2. Первые 30 запросов и запросы с кликом

Полные таблицы за оба периода: `gd-gsc-top30-and-clicks.md`. За 3 месяца первые 30 запросов дают 5,883 показа из 6,718 (кликов 0), за 16 месяцев 27,397 из 30,876 и 1 клик.

Первые 10 за 3 месяца (показы · место; в скобках 16 месяцев): garbage disposal repair 1,915 · 14.9 (6,380 · 15.9); garbage disposal repair plano 512 · 5.0 (2,453 · 13.9); garbage disposal repair frisco 339 · 9.3 (1,881 · 14.6); garbage disposal repair plano tx 323 · 12.8 (1,344 · 44.5); garbage disposal repair near me 254 · 10.6 (814 · 16.4); plano garbage disposal repair 228 · 4.5 (1,192 · 17.9 · 1 клик); garbage disposal repair little elm tx 184 · 20.4 (735 · 52.5); plano tx garbage disposal repair 180 · 13.3 (981 · 55.3); frisco garbage disposal repair 164 · 10.5 (1,227 · 18.3); garbage disposal repair little elm 163 · 13.7 (1,462 · 33.0). Дальше идут McKinney, Frisco tx, "garbage disposal repair service" 99 · 12.7 и запросы с Rockwall, Coppell, Richardson, Lake City.

За 16 месяцев в первую тридцатку входят, кроме названных, в том числе "garbage disposal repair mckinney" 1,654 · 28.3, "garbage disposal repair dallas" 945 · 66.2, "the colony garbage disposal repair" 543 · 26.0, "garbage disposal repair the colony" 487 · 20.9, "garbage disposal repair allen" 161 · 26.1, "garbage disposal repair carrollton" 161 · 55.5, "lewisville garbage disposal repair" 149 · 69.1.

Запрос с кликом один: "plano garbage disposal repair", 16 мес 1,192 · 17.9 · 1 клик (за 3 месяца 228 · 4.5 · 0).

### 2.3. Что держат title, H1, H2 и вопросы FAQ

Заголовок «держит» запрос, когда все значимые слова запроса стоят в нём (in, tx и подобные не считаются, множественное число приводится к единственному, город считается).

| Заголовок | 3 мес: запросов · показы | 16 мес: запросов · показы · клики | Держит только он, 16 мес |
|---|---|---|---|
| title "Garbage Disposal Repair in Frisco & Plano \| Jammed or Leaking Unit?" | 16 · 3,982 | 25 · 17,658 · 1 | 19 · 11,268 · 1 |
| meta description | 0 | 2 · 3 | 0 |
| H1 "Garbage Disposal Repair and Replacement, Done in One Visit" | 3 · 1,918 | 6 · 6,390 | 0 (их держит и title) |
| все девять H2 | 0 | 0 | 0 |
| вопрос FAQ "How much does garbage disposal installation cost?" | 0 | 1 · 1 ("who installs garbage disposals") | 1 · 1 |
| остальные шесть вопросов FAQ | 0 | 0 | 0 |

Title и H1 вместе держат 27 запросов: 17,686 показов и клик за 16 месяцев, 4,001 показ за 3 месяца. Что нельзя потерять:
- "Garbage Disposal Repair" в начале title и в начале H1: точная фраза "garbage disposal repair" стоит только там (в абзацах её нет), это 6,380 показов.
- "Frisco & Plano" в title: на нём держатся запросы «измельчитель плюс plano или frisco», у которых все слова стоят в title: 15 запросов, 11,153 показа и единственный клик за 16 месяцев, 13 запросов и 2,064 показа за 3 месяца. Остальные запросы с этими городами (installation, sink, replacement) title держит не целиком.
- "Leaking" в title держит "leaking garbage disposal repair" (105 показов за 16 месяцев) и ещё три таких запроса (вместе 115).
- Little Elm и McKinney не держит ни один заголовок (они только в предложении со ссылками), The Colony, Carrollton и Lewisville на странице нет вовсе («частично» в полных таблицах).
- H2 и вопросы FAQ запросов не держат: по Search Console их можно менять.

### 2.4. Фраза целиком: 20 первых запросов за каждый период и запрос с кликом

Список из 26 запросов (20 первых за 16 месяцев, 20 первых за 3 месяца, запрос с кликом). Точная фраза (подряд, слово в слово, регистр и знаки не в счёт) стоит на живой странице только у одного: "garbage disposal repair" (title и H1). У остальных 25, включая запрос с кликом "plano garbage disposal repair" и все запросы «garbage disposal repair плюс город» (plano, frisco, mckinney, little elm, the colony, с tx и без), точной фразы нет нигде: ни в тексте, ни в FAQ, ни в отзыве. Нет и "garbage disposal repair near me", "garbage disposal repair service".

По правилу проектного инструмента (слово "in" не считается) title "Garbage Disposal Repair in Frisco & Plano" содержит "garbage disposal repair frisco" и "garbage disposal repair frisco tx", а "frisco garbage disposal repair" как перестановку. Для Plano так не выходит: между "repair" и "plano" стоит "frisco".

### 2.5. Другие страницы сайта по запросам про измельчитель

Только запросы про кухонный измельчитель. «Выше»: лучшее место по тому же запросу за тот же период. Все строки: `gd-gsc-other-pages.md`.

| Страница | 3 мес: запросов · показы · место (выше этой: запросов, показы) | 16 мес: запросов · показы · место (выше этой) |
|---|---|---|
| `/plumber-plano-tx/` | 33 · 933 · 2.5 (27, 714) | 33 · 2,712 · 45.5 (27, 313) |
| `/` (главная) | 2 · 7 · 14.0 (1, 1) | 55 · 5,542 · 14.9 · 1 клик (31, 4,831) |
| `/plumber-frisco-tx/` | 5 · 75 · 11.3 (3, 45) | 12 · 1,392 · 49.8 (4, 28) |
| `/plumber-mckinney-tx/` | 4 · 69 · 7.6 (4, 69) | 6 · 229 · 44.8 (5, 175) |
| `/plumber-little-elm-tx/` | 2 · 2 · 20.5 (0) | 6 · 2,599 · 57.2 (2, 1,305) |
| `/plumber-the-colony-tx/` | 0 | 6 · 1,053 · 56.5 (1, 274) |
| `/plumber-lewisville-tx/` | 0 | 7 · 856 · 59.3 (2, 399) |
| `/plumber-allen-tx/` | 0 | 2 · 647 · 49.0 (1, 277) |
| `/plumber-carrollton-tx/` | 1 · 1 · 29.0 (0) | 4 · 263 · 62.0 (2, 2) |
| ещё семь страниц (water heaters, emergency, Celina, Prosper, toilet, contact, faucet) | 0 или 1 показ | от 1 до 57 показов каждая |

Строка гайда по цене водонагревателя в `gd-gsc-other-pages.md` ("cost to remove and dispose old water heater 2026", 1 показ) не про измельчитель, а про вывоз старого водонагревателя: в счёт страниц выше не идёт.

Главные строки, где другая страница выше:

| Запрос, период | Другая страница: показы · место · клики | Эта страница |
|---|---|---|
| garbage disposal repair plano, 3 мес | `/plumber-plano-tx/` 216 · 1.7 | 512 · 5.0 |
| garbage disposal repair plano tx, 3 мес | `/plumber-plano-tx/` 145 · 1.6 | 323 · 12.8 |
| garbage disposal installation, 3 мес | `/plumber-plano-tx/` 119 · 1.0 | нет |
| garbage disposal repair near me, 3 мес | `/plumber-mckinney-tx/` 46 · 5.7 | 254 · 10.6 |
| garbage disposal repair, 3 мес | `/plumber-frisco-tx/` 16 · 1.8 | 1,915 · 14.9 |
| garbage disposal repair plano tx, 16 мес | `/` 983 · 3.9 | 1,344 · 44.5 |
| garbage disposal repair plano, 16 мес | `/` 970 · 10.0 · 1 клик | 2,453 · 13.9 |
| garbage disposal repair, 16 мес | `/` 913 · 12.0 | 6,380 · 15.9 |
| garbage disposal repair little elm tx, 16 мес | `/plumber-little-elm-tx/` 718 · 51.4 | 735 · 52.5 |
| the colony tx garbage disposal repair, 16 мес | `/plumber-the-colony-tx/` 446 · 52.5 | нет |

Что из этого следует по файлам:
- Страница Plano за 3 месяца стоит в среднем на месте 2.5 по запросам про измельчитель, по 18 из 33 на месте 3 и выше (723 показа), в том числе по 12 запросам без слова plano (321 показ: Frisco, The Colony, Little Elm, Willow Bend, Collin County, Lake City и "garbage disposal installation" без города). Кнопка сайта в карточке Google Plano ведёт на страницу Plano (`seo/cannibalization-findings.md`): это показы карточки, не текста; за 16 месяцев место той же страницы 45.5. Так же "garbage disposal repair" у Frisco на месте 1.8 (карточка Frisco).
- Главная брала запросы про измельчитель до июля 2026: 5,535 показов из 5,542 и 1 клик ("garbage disposal repair plano"); за последние 3 месяца у неё 7 показов, по этим запросам теперь показывается эта страница.
- Старая McKinney выше этой страницы по 4 запросам за 3 месяца ("garbage disposal repair near me", "garbage disposal repair mckinney" и ещё два); у неё раздел и title про измельчители (пункт 1.6).
- Городские страницы показываются по «измельчитель плюс свой город» за 16 месяцев на местах от 47 до 68 по запросам с 40 показами и больше (среднее по странице от 49.0 у Allen до 62.0 у Carrollton). Эта страница по тем же запросам где выше ("garbage disposal repair little elm" 33.0 против 61.5, "the colony garbage disposal repair" 26.0 против 62.0, все запросы с frisco), где ниже или её нет ("the colony tx…", "lewisville tx…", "allen tx…", "carrollton tx garbage disposal repair").

Обратная сторона, запросы этой страницы, которые по карте ключей принадлежат другим: "plano faucet repair" (14 показов, место 87.6; кран, страница `/fixture-installation-repair/`; её же показывает и Plano 1,073 · 42.5), "sink repair plano" (7 · 82.9), "emergency plumber mckinney" (1 · 95.0; главная и страница emergency), "cabinet replacements frisco" (1, не сантехника), "moen" (1). Запрещённый для этой страницы по карте ключ "plumber plano" у неё не встречается ни разу.

### 2.6. Измельчитель с каждым из десяти городов

Только запросы про измельчитель с названием города (запросы про вывоз мусора, "disposal of garbage plano" и "plano disposal of garbage", не в счёт). Числа: запросов · показы · место по показам.

| Город | Эта страница, 3 мес | Эта страница, 16 мес | Кто ещё, 3 мес | Кто ещё, 16 мес |
|---|---|---|---|---|
| Plano | 11 · 1,347 · 8.7 | 14 · 6,515 · 28.3 · 1 клик | Plano 9 · 534 · 2.5 (карточка); главная 1 · 6 | главная 6 · 2,718 · 12.3 · 1 клик; Plano 9 · 2,313 · 52.9 |
| Frisco | 10 · 849 · 12.5 | 11 · 5,151 · 23.8 | Plano 6 · 136 · 2.5; Frisco 3 · 36 · 8.3 | Frisco 5 · 1,337 · 51.2; главная 7 · 1,099 · 21.8 |
| McKinney | 6 · 318 · 25.9 | 7 · 2,668 · 33.6 | McKinney 2 · 13 · 9.6 | McKinney 4 · 173 · 57.1 |
| Little Elm | 5 · 455 · 16.9 | 6 · 3,193 · 42.8 | Plano 3 · 10 · 7.0; Little Elm 2 · 2 | Little Elm 6 · 2,599 · 57.2 |
| The Colony | 2 · 19 · 10.6 | 5 · 1,191 · 27.5 | Plano 5 · 72 · 2.7 | The Colony 6 · 1,053 · 56.5; главная 5 · 295 · 13.1 |
| Allen | 0 | 3 · 221 · 27.9 | нет | Allen 2 · 647 · 49.0 |
| Carrollton | 1 · 1 · 46.0 | 5 · 311 · 57.3 | Carrollton 1 · 1 · 29.0 | Carrollton 4 · 263 · 62.0; главная 4 · 231 · 30.6 |
| Lewisville | 0 | 5 · 231 · 69.6 | нет | Lewisville 7 · 856 · 59.3; главная 5 · 30 · 4.4 |
| Prosper | 0 | 0 | нет | Prosper 1 · 15 · 46.6 |
| Celina | 0 | 0 | нет | Celina 2 · 9 · 23.2 |

Лучшее место по городу за 3 месяца: Plano 3.9, The Colony 7.0, Frisco 9.3, Little Elm 11.0, McKinney 16.4. На странице названы Frisco и Plano (title, вступление, раздел) и Little Elm, McKinney, Allen (одно предложение); The Colony, Carrollton, Lewisville, Prosper, Celina нет.

### 2.7. Слова, которые на страницу не идут

| Что | 3 мес: запросов · показы | 16 мес: запросов · показы |
|---|---|---|
| Чужие места, всего | 73 · 1,322 | 96 · 3,439 |
| из них Dallas (и "dallas tx") | 4 · 47 | 7 · 1,425 |
| Rockwall | 5 · 320 | 5 · 575 |
| Coppell | 6 · 312 | 6 · 371 |
| Richardson | 5 · 196 | 5 · 227 |
| Lake City (и "lake city sc") | 2 · 110 | 3 · 178 |
| Остальные места (за 16 мес 42 места и индексы 43291, 43069): Willow Bend, Collin County, Far North Dallas, Denton, Denton County, Valley Ranch, Twin Creeks, Deerfield, Windhaven, Lake Dallas, Bartonville, Highland Village, Irving, Garland, Fairview, Murphy, Addison, Farmers Branch, Rowlett, Wylie и другие, в том числе вне Техаса | 51 · 337 | 70 · 663 |
| Невидимый знак после "repair" (zero width space; шаблон "sink disposal repair" или "garbage disposal repair" плюс место) | 40 · 291 | 48 · 834 |
| Не про услугу: "can you show me pictures of", "i need to replace it", "is it required", "stuck?", "moen", два запроса site: | 4 · 4 | 7 · 11 |
| Про вывоз мусора, не измельчитель: "disposal of garbage plano", "plano disposal of garbage", "garbage dumpster plano" | 0 | 3 · 3 |
| Слово handyman | 0 | 2 · 2 |
| Марка InSinkErator (на странице названа только Moen) | 1 · 1 | 2 · 2 |
| Канадское слово garburator | 1 · 1 | 2 · 2 |
| Оценочные слова: cost, how much | 1 · 1 | 2 · 4 |
| Шкафы ("cabinet replacements frisco") | 0 | 1 · 1 |

Прямо запрещены CLAUDE.md: Dallas (и Far North Dallas), Richardson, Denton, Irving, Garland, Fairview. Остальные места в десять городов не входят; Willow Bend, Deerfield, Windhaven, Twin Creeks, Valley Ranch это районы и улицы.

### Как считали и вторая проверка

- Скрипт `gd_gsc.py` в `/private/tmp/claude-501/-Users-denyskavaler-Projects-fppplumbing-site/d2b78dea-4d58-4222-812f-a40bb43eb5d1/scratchpad/services/garbage-disposal/` сделан из копий `docs/briefs/_shared/gsc_plano_lib.py` и `gsc_plano_live.py` (оригиналы не тронуты, `tools/gsc_page_table.py` не запускался). Правила слов те же; группы: город из десяти, другое место, служебный, без города; пометки «карта» нет (кнопки карточек Google ведут на Frisco и Plano). Отзыв клиента в счёт слов не идёт.
- Итоги посчитаны трижды (модуль csv, разбор строк без него, awk), все три совпали: 3 месяца 137 запросов, 0 кликов, 6,718 показов, место 18.83; 16 месяцев 254, 1, 30,876, место 30.40. Те же числа в `source/gsc/page-query-coverage.csv`.
- Группы сходятся с итогом: 28 + 35 + 73 + 1 = 137 и 2,406 + 2,989 + 1,322 + 1 = 6,718; 94 + 63 + 96 + 1 = 254 и 7,929 + 19,507 + 3,439 + 1 = 30,876.
- Руками сверены "garbage disposal repair" (1,915 · 14.91 и 6,380 · 15.93), "plano garbage disposal repair" (1,192 · 17.92 · 1) и итог в `performance-3m/Pages.csv` (1 · 7,121 · 18.99).

