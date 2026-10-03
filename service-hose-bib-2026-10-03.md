# Hose bib repair: живая страница и Search Console (3 октября 2026)

Страница: https://fppplumbing.com/hose-bib-repair-frisco-plano/ . Сейчас не переписывается, текста страницы здесь нет.

Откуда данные: обход живого сайта от 30 сентября 2026 (`source/crawl/`); новый сайт `site/src/content/pages/hose-bib-repair-frisco-plano.md` и сборка `site/dist/` (3 октября); правки `tools/build_launch_content.py`, `site/src/data/launch-changes.csv`; `source/FPP-Hose-Bib-Page.docx`, `source/approved-text-edits.md`; `reviews/`; `photos/captions-en.csv`; Search Console `source/gsc/` (выгрузка 30 сентября 2026); `seo/keyword-map.md`, `docs/pages-plan.md`; `source/dictation/2026-10-02-frisco-additions.md`, `source/frisco-text-v4.md`.

Длинные таблицы в `docs/briefs/services/hose-bib/`: `hb-gsc-table-3m.md` и `hb-gsc-table-16m.md` (все запросы), `hb-gsc-top30-and-clicks.md`, `hb-gsc-headings.md` (что держит каждый заголовок), `hb-gsc-other-pages.md` (другие страницы и обратная сторона), `hb-links.md` (все ссылки).

Числа через точку: показы · место · клики. Тире живой страницы показаны пометкой [короткое тире] или [длинное тире].

## Коротко

1. Кормит мало. Итог Google: за 3 месяца 2 клика (оба по скрытым запросам), 1,575 показов, место 21.26; за 16 месяцев 13 кликов, 7,833 показа, место 37.48. Известный запрос с кликом один: "who fixes outdoor spigots" (16 мес: 5 · 7.2 · 1). В `docs/pages-plan.md` 14-я в группе 3.
2. Главное: большую часть известных показов страница берёт чужим ключом. Запросы про кран без уличных слов, почти все «faucet repair плюс город» (frisco faucet repair, faucet repair frisco, plano faucet repair…), дают 4,101 показ из 5,507 за 16 месяцев (20 запросов, из них 17 с repair и городом: 4,069 показов) и 361 из 594 за 3 месяца (4 запроса), кликов 0. По `seo/keyword-map.md` это ключ `/fixture-installation-repair/`, этой странице он запрещён. Ловит их title словами "Outdoor Faucet Repair in Frisco & Plano"; по двум самым большим страница кранов стоит выше (24.9 и 28.1 против 38.7 и 42.5).
3. По своей теме (hose bib, spigot, outdoor faucet) за 16 месяцев 145 запросов, 1,376 показов, место 39.2, 1 клик; за 3 месяца 32 · 223 · 30.1 (до июля место было 41.0). Главный ключ по карте "hose bib repair": 1 показ за 16 месяцев на месте 56.
4. Нельзя потерять: "Hose Bib" в title и H1; H2 "What Makes a Hose Bib Installation “Right”?" (точная фраза "hose bib installation", 129 показов за 16 месяцев, 36 за 3, только здесь); "Outdoor Faucet Repair" в title (точная фраза "outdoor faucet repair"). Лучший по месту большой запрос "hose bibb repair allen" (307 · 10.7) не держит ни один заголовок: "bibb" на странице нет.
5. Спор правил: правка Дениса от 30 сентября велит убрать "faucet repair" из title и H1; этими словами title держит 3,848 показов чужого ключа (кликов 0), своей темы 154.
6. Против правил: цены "$300" и "$5,000" (на новом сайте стоят); три тире и дважды "North Dallas" (на новом исправлено); ответы FAQ тегом H2 (на новом нет); семь разорванных фраз (стоят); H1 и четыре H2 с вопросами и лозунгами; числа без подтверждения ("hundreds", "dozens", "every week"); "full wall rebuilds"; в схеме второй узел Plumber и снятая формулировка лицензии.
7. Не хватает по правилу 8: своего текста 844 слова против 2,500; разделов с содержанием 6 (нужно 10 до 16); FAQ 3 (нужно 5 до 7); нет раздела «если это происходит сейчас» и гайда по главному крану (на новом сайте их частично даёт шаблонный блок "What is happening right now?" после текста, пункт 1.8); нет ссылки "plumber near me" на главную; ссылок на десять городов в тексте 0 (Celina и Lewisville не названы); из соседних услуг в тексте только leak detection; нет внешней ссылки на источник; отзывов на живой нет.
8. Одобренный `source/FPP-Hose-Bib-Page.docx` (1,773 слова, 9 разделов, 6 FAQ, главная и десять городов анкорами) не стоит ни на живом, ни на новом сайте; его title снова с "Faucet Repair", в тексте "Denton County".
9. Тему на сайте кормит пост `/blog/burst-outside-spigot/` (за 3 месяца 16 кликов, 1,721 показ, место 9.3; 95% скрыто). Allen выше этой страницы по "hose bibb repair allen" за 3 месяца (5.7 против 14.1), и её title говорит "Hose Bibs" (по карте нельзя). Frisco, Plano и главная выше по "outdoor faucet repair dfw".
10. Город плюс уличный кран: запросы есть только с Allen и Lewisville. Отложить: 29 запросов с чужими местами (362 показа за 16 месяцев, Richardson 165), 11 без предмета, 2 site:.

## 1. Живая страница

### 1.1. Title, описание, H1, заголовки, объём

| Что | Живая страница |
|---|---|
| Title (71 знак) | "Hose Bib & Outdoor Faucet Repair in Frisco & Plano \| Spigot Replacement" |
| Meta description (178 знаков, длиннее того, что Google обычно показывает) | "Leaky outdoor faucet or broken hose bib? We repair and replace spigots, frost-free hydrants, and outdoor valves in Frisco, Plano & McKinney. Clean, licensed work. Need fast help?" |
| H1 | "Hose Bib Leaking? Outdoor Spigot Busted? We Replace Them Right" |
| OG title | "Outdoor Faucet (Hose Bib) Repair" (не совпадает с title) |
| OG картинка | `/wp-content/uploads/2025/05/new-hose-bib-spigot-installation-frisco-768x1024.jpg` |
| Даты в схеме | опубликована 6 мая 2025, изменена 16 августа 2026 |

H2 по порядку (в скобках слов текста в разделе, по тексту обхода):
1. "Emergency Outdoor Faucet or Hose Bib Issues? We’re On Call 24/7 in Frisco & Plano" (96; это и есть вступление: между H1 и первым H2 текста нет)
2. "Why Outdoor Faucets (Spigots / Hose Bibs) Fail Even “Frost-Proof” Ones" (137)
3. "What Makes a Hose Bib Installation “Right”?" (103)
4. "Signs Your Outdoor Faucet Might Be Leaking Inside the Wall [короткое тире] Plumber Tips" (90)
5. "Outdoor Faucet Leaking, Hose Bib Dripping or Loose? We’re On Call 24/7 in Frisco & Plano" (78)
6. "Serving Frisco, Plano, Allen, McKinney & North Dallas" (30, только список мест)
7. "Outdoor Faucet Questions From Homeowners" (FAQ, 126 слов вопросов и ответов)
8. Три ответа FAQ, каждый тегом H2 (пункт 1.2)
9. "Outdoor Spigot Problem? Call a Licensed Plumber, Not Just Anyone" (56 слов, потом кнопка "Request Service" и две строки со ссылками, 36 слов)
10. "980-899-7997 469-998-8999" (не раздел: два телефона нижней панели звонка свёрстаны тегом H2, шаблон всего старого сайта)

H3 нет ни одного.

Объём. Обход: 859 слов по пробелам, слов с буквами или цифрами 844. От H1 до конца FAQ 740 (H1 10, заголовки шести разделов 65, их текст 534, FAQ 131), последний раздел 104. До 2,500 не хватает около 1,650.

Ключи в title, описании, alt фото и тексте вместе: "hose bib" 14 раз, "outdoor faucet" 10, "spigot" 15, "hose bib repair" подряд 0, "near me" 0. Города там же: Frisco 7, Plano 6, McKinney 3, Allen 2 (H2 "Serving…" и список), Little Elm, Prosper, The Colony, Carrollton по разу в списке; Celina и Lewisville нет. В одном тексте страницы (`body_text` обхода, без title, описания и alt): "hose bib" 11, "outdoor faucet" 8, "spigot" 12, Frisco 4, Plano 4, McKinney 2.

### 1.2. FAQ: три вопроса слово в слово

| № | Вопрос | Ответ |
|---|---|---|
| 1 | "Why is my outdoor faucet leaking even when it’s off?" | "It usually means the faucet is worn out inside. The rubber washer or internal stem is damaged, or it’s packed with rust and calcium. If it keeps dripping, it’s time to replace it." |
| 2 | "Can I just change the handle if it broke?" | "If the handle snapped off but the valve still works, sure [длинное тире] we can swap the handle. But if it won’t shut off water, the whole unit needs to be replaced." |
| 3 | "Do I need to cover my hose bib in winter?" | "Yes, especially if it’s not a frost-proof model. One freeze can split the pipe inside your wall. We install frost-proof hose bibs and show you how to protect them before the next cold snap." |

- Вопросы стоят в `summary` раскрывающегося списка Elementor, это не тег заголовка; зато все три ОТВЕТА свёрстаны тегом H2. По правилу 8 вопрос жирным текстом, ответ обычным.
- Схема FAQPage совпадает со страницей слово в слово (с длинным тире). Вопросов 3, нужно 5 до 7.
- Слово в слово больше нигде на сайте не стоят. Близкие по смыслу: Allen "My outdoor faucet drips. Is that urgent?" (к вопросу 1); новая Frisco "What should I do before a freeze in Frisco?" и раздел поста `/blog/burst-outside-spigot/` "Winterizing Your Outside Spigots Before the Next Freeze" (к вопросу 3).

### 1.3. Отзывы

На живой странице отзывов нет (в коде нет звёзд и ссылок на Google Maps); в `reviews/all-reviews.csv` ни один из 407 не записан за ней. На новом сайте (`reviews/site-reviews.json`, `site-ledger.md`) два автора, оба больше нигде не стоят:
- Bharathi Hariharan, Google, профиль Plano, 7 июля 2026, подпись "★★★★★ · Local Guide Level 3 · July 2026 · Google". Текст и ссылка совпадают с архивом знак в знак, уровень 3 в архиве есть. Про замену уличного hose bib, вскрытие и подтверждённую цену; в тексте клиента два длинных тире и "peace of mind" (не правится), исполнитель "Dennis". Города в отзыве и в подписи нет: верно по правилу 11.
- David Cuevas, Google, профиль Plano, 14 августа 2026, "★★★★★ · Local Guide Level 4 · August 2026 · Google": "On time and did a great job replacing our outdoor spigot." Совпадает с архивом, уровень 4 в архиве есть.

В запасе (`reviews/ledger-decisions.csv`): Quan Nguyen (Google, профиль Frisco, март 2026, "My busted outdoor spigot was inspected and replaced carefully and fast."), снят с Frisco при версии 3 и оставлен сюда, на новом сайте не стоит ни на одной странице. На живом сайте этот отзыв стоит на странице Little Elm (`reviews/ledger.md`; в `all-reviews.csv` on_old_site `/plumber-little-elm-tx/`).

### 1.4. Фото

Одно настоящее фото с работы, сразу под H1, оно же OG картинка: `/wp-content/uploads/2025/05/new-hose-bib-spigot-installation-frisco-768x1024.jpg`, alt "New outdoor hose bib (spigot) installed after replacing leaking faucet in Frisco backyard". Новый frost free кран с чёрной ручкой в кирпиче у белого камня, внизу гравий. Грузится «лениво», хотя стоит на первом экране. Остальное шаблон (логотип, знак BBB). В `photos/index.csv` такого файла нет; по виду это фото 52 архива (сравнил на глаз по `photos/thumbs/052.jpg`), а у 52 город по месту съёмки Celina. Значит "in Frisco backyard" в alt не подтверждается. На новом сайте это фото с тем же alt стоит ниже, в начале текста, и грузится лениво; первым экраном (грузится сразу) стоит фото 30 архива: `/img/frost-free-outside-faucet-replaced-frisco-30-720.webp`, alt "New frost free outside faucet on a brick wall, hose bib replacement, Frisco" (в `photos/captions-en.csv` у 30 hero_for эта страница, city_final Frisco).

Для этой страницы в `photos/captions-en.csv` записаны ещё: 29 и 30 (новый frost free, два ракурса одного крана; у 30 city_final Frisco, у 29 город пустой; по пометке файла 29 снято вне десяти городов, 30 у границы Frisco), 100 и 101 (до и после, Frisco), 121 (лопнувший и новый рядом, Celina), 172 (течёт и не закрывается, city_final Plano, по пометке место у границы Plano и Frisco, ближе к Plano), видео 176 и фото 178 (оба Frisco, стоят на новой Frisco). Видео на живой странице нет.

### 1.5. Ссылки

Полный список с предложениями: `docs/briefs/services/hose-bib/hb-links.md`. Поправка к его разделу 2: на новом сайте ссылка на гайд по главному крану есть, в шаблонном блоке "What is happening right now?" после текста (пункт 1.8); в самом тексте её нет.

Со страницы: внутренних ссылок 105, в тексте 2 (последние две строки целиком: на `/water-leak-detection-frisco-plano/` и `/emergency-plumbing-services/`). Нет: "plumber near me" на главную, ссылок на города (города голым списком), соседних услуг в тексте, гайда по главному крану, поста про лопнувший кран, внешних ссылок.

На страницу: шаблонное "Outdoor Faucet (Hose Bib) Repair" 189 раз на 62 страницах. В тексте: главная (плитка), Allen ("hose bib repair" дважды), Frisco ("hose bib repair"), Plano ("Outdoor faucet repair"), emergency ("Outdoor faucets"), пост про лопнувший кран ("outside spigot replacement"), пост `/blog/outside-spigot-replacement-plumber-in-frisco/` (голый адрес вместо анкора), гайд PRV ("outdoor hose"), гайд `/plumbing-guide/water-leak-yard-tips-2026/` ("outside spigot"). Из десяти городов в тексте ведут три. На новом сайте то же плюс новая Frisco ("Both kinds are on the hose bib repair page") и главная (плитка "Hose bib repair", точка "Outdoor faucet" на трубе).

### 1.6. Что идёт против CLAUDE.md, дословно

«Новый сайт»: стоит ли это в файле новой страницы после точечных правок.

**Услуги, которых FPP не делает или не заявляет.** Tankless, reroute, hydro jetting, газа нет. Под вопросом:
- "…from clean installs to full wall rebuilds." Перестройки стен в списке услуг нет (стены открываем, восстанавливает партнёр). Новый сайт: стоит.
- "Insulating the wall cavity if needed to prevent freeze bursts". Денис говорил об изоляции трубы после разрыва, про утепление полости стены при установке крана в его словах нет. Новый сайт: стоит.

**Цены** (разрешена только $49 за выезд в будни; $49 на странице нет вовсе):
- "What starts as a $300 spigot swap can easily turn into a $5,000 mold remediation and drywall rebuild." Новый сайт: стоит (в журнале правок «flag not changed»).

**Сроки гарантии.** Нет. Рядом с обещанием: "install a new frost-proof hose bib that won’t quit after the next Texas freeze" (новый сайт: стоит).

**Время в своих словах.** Часов и минут нет. Намёки на скорость: meta "Need fast help?", "It’s usually a fast fix, unless damage was already done." (про работу); на новом сайте стоят. В схеме живой, во втором узле Plumber (`#schema`), ещё "Fast help from licensed plumbers"; на новом сайте этого узла нет. "We’re On Call 24/7" это факт, не обещание приезда.

**Другие города и регион.** "As a plumber in North Dallas, I’ve replaced more of these than I can count." и H2 "Serving Frisco, Plano, Allen, McKinney & North Dallas": на новом сайте исправлено на "North Dallas suburbs" (в H2 с заглавной: "Serving Frisco, Plano, Allen, McKinney & the North Dallas Suburbs"). Highland Park и University Park в списке без ссылок, это разрешено; "and nearby cities" без названий; запрещённых городов в тексте нет. Схема живой: в узле Organization "surrounding North Dallas communities" и "Texas Master Plumber License M-44816" (обе формулировки сняты), второй узел Plumber (`#schema`) с именем страницы и только адресом Plano. Новый сайт: один Plumber, Service, FAQPage, десять городов и Park Cities.

**Граница с другими страницами (правило 9).**
- Раздел "Signs Your Outdoor Faucet Might Be Leaking Inside the Wall…" перечисляет признаки скрытой течи ("Weird drop in water pressure", "Dripping or hissing sounds inside the wall", "Musty smell or soft drywall weeks later"); поиск течи это `/water-leak-detection-frisco-plano/`, ссылка туда только в последней строке. Методов поиска раздел не описывает.
- Мороз: тема "frost free spigot leaking" по карте у поста `/blog/burst-outside-spigot/`; раздел "Why Outdoor Faucets … Fail Even “Frost-Proof” Ones" и вопрос FAQ 3 идут по ней без ссылки на пост.
- Title ловит «faucet repair плюс город», ключ `/fixture-installation-repair/` (пункт 2.5).
- С другой стороны: страница Allen, title "Plumber in Allen, TX | Hose Bibs, Water Heaters & Drains" (на новом тот же), раздел "Outdoor Faucets and Hose Bibs", вопрос "My outdoor faucet drips. Is that urgent?"; по карте Allen не должна целиться в "hose bib repair".

**Телефоны в тексте.** Нет. Только шаблон: нижняя панель звонка тегом H2 "980-899-7997 469-998-8999" (на новом сайте нет).

**Owner.** Нет.

**FAQ тегом заголовка.** Вопросы не заголовки, но ответы тегом H2 (пункт 1.2). Новый сайт: вопрос жирным в `summary`, ответ абзацем.

**Тире.** Три места: H2 "…Inside the Wall [короткое тире] Plumber Tips", ответ FAQ 2 "sure [длинное тире] we can swap the handle" (и в схеме), строка "If it’s already flooding or urgent [короткое тире] hit our 24/7 Emergency Plumbing page." Новый сайт: все три заменены двоеточием.

**Разорванные фразы** (похоже, выпал знак; в коде WordPress они уже такие; на новом сайте стоят): "The faucet won’t fully shut off keeps dripping"; "push-fits, SharkBites, no bracing invisible leaks that ruin homes slowly"; "Proper mounting to the siding or brick no wiggly faucets"; "Sometimes we can do a clean install outside other times, drywall needs to be opened up."; "pouring water into the wall every spring you’re not alone."; "hundreds of outdoor faucets , from" (пробел перед запятой); "…after the next Texas freeze" (без точки).

**Лозунги, вопросы, вода, тройки.** H1 "Hose Bib Leaking? Outdoor Spigot Busted? We Replace Them Right" (два вопроса и лозунг; правило 4). Четыре H2 с вопросом ("Emergency Outdoor Faucet or Hose Bib Issues? …", "What Makes a Hose Bib Installation “Right”?", "Outdoor Faucet Leaking, Hose Bib Dripping or Loose? …", "Outdoor Spigot Problem? Call a Licensed Plumber, Not Just Anyone"), хвост "We’re On Call 24/7 in Frisco & Plano" повторён в двух. "And years later?", "Sound familiar? We fix this stuff the right way.", "Texas weather’s crazy.", "It’s not just about stopping the drip. It’s about doing it right .", "Don’t wait for the damage to show, call a plumber before it gets worse.", meta "Clean, licensed work. Need fast help?". Тройки: "a water leak, a drywall problem, or a surprise indoor flood"; "ruins sheetrock, cabinets, insulation"; "soaking studs, insulation, and subflooring". Новый сайт: всё стоит.

**Без подтверждения** (правило 13): "We deal with this every week."; "I’ve replaced more of these than I can count."; "We’ve redone dozens of outdoor spigot jobs…"; "we’ve replaced hundreds of outdoor faucets"; "We’ve opened walls to find leaks that ran for years"; "We’ve seen that flood walls, garages, even slab edges.". Частично подтверждает одобренный текст Frisco (`source/frisco-text-v4.md`): "every spring and half the summer we replace outdoor spigots that cracked inside the wall during the freeze".

**Совет про мороз.** С поправкой Дениса (frost free кран при правильной установке не лопается, ему нужен чехол, капать его не оставляют) совпадает; нарушения нет.

### 1.7. Что на живой странице стоит сохранить по сути

Подтверждено словами Дениса (диктовка 2 октября и Frisco v4: трещина в стене видна, только когда включают шланг; кран, который не закрывается; трубы в плохо утеплённых стенах лопаются): "When spring comes, the pipe behind the wall starts leaking as soon as you open it"; "Sometimes the spigot looks totally fine, until you turn it on for the first time after winter"; "The faucet won’t fully shut off keeps dripping" (фото 100, 172, видео 176); "even “frost-proof” spigots burst if they’re installed wrong, or if there’s not enough insulation inside the wall".

Только из старого текста, в диктовках нет: "The spigot leaks from the vacuum breaker (air gap on top)" (про это запросы «leaking from top», пункт 2.7); "Old threads inside the wall get micro-cracks and they only leak after replacement"; "Builders didn’t secure the pipe inside the wall so when you try to unscrew it, the pipe snaps"; список установки ("Checking that the pipe inside the wall is braced and secure", "Using thread sealant properly (not ten pounds of Teflon)", "Making sure there’s no old corrosion inside the fitting", крепление к сайдингу или кирпичу); ошибки прежних мастеров ("Used indoor hose bibs instead of frost-free models", "Jammed on a SharkBite and hoped for the best", "Installed it too shallow, so it froze and burst next winter"); "If we find issues inside the wall (bad pipe, weak fitting, poor bracing), we’ll walk you through options." (сходится с отзывом Bharathi Hariharan); FAQ 1 и 2 по сути.

### 1.8. Новый сайт против живой страницы

- Стоит старый текст с точечными правками, одобренного текста нет. Title, описание, H1, восемь H2, три вопроса FAQ те же; OG title равен title.
- Правки (`launch-changes.csv`, строки 235 до 239): "North Dallas" дважды на "North Dallas suburbs", три тире на двоеточие. Строка 240: "$300" и "$5,000" «flag not changed», стоят.
- Добавлены отзывы Bharathi Hariharan и David Cuevas.
- От шаблона: первым экраном фото 30 (пункт 1.4); FAQ жирным вопросом; блок "What is happening right now?" дважды: под первым экраном четыре ссылки на разделы emergency (`#p-floor`, `#p-hot`, `#p-sewer`, `#p-pressure`), после текста те же четыре, ссылка на гайд по главному крану "Close the main shut-off valve: how to find it and shut off the water" и кнопки звонка в два офиса (это шаблон, в самом тексте страницы гайда нет); один Plumber; Service (имя узла это H1, описание это meta с "Need fast help?"); FAQPage; `noindex`.
- Своего текста около 846 слов.

Одобренный текст `source/FPP-Hose-Bib-Page.docx` (на сайты не ставился): title "Hose Bib & Outdoor Faucet Repair in Frisco & Plano, TX", H1 "Outdoor Faucet and Hose Bib Repair: Fixed Before It Floods the Wall", 9 разделов (признаки, причины, замена frost free, течь в стене после мороза, ручки и вакуумные клапаны, перед морозом, цена с $49, десять городов анкорами "plumber in …", «вода идёт в стену прямо сейчас»), 6 FAQ жирным, 1,773 слова, ссылки на главную "plumber near me", leak detection, пост про лопнувший кран, гайд по главному крану, emergency. Против нынешних правил: title с "Faucet Repair" (правка от 30 сентября); "On the Denton County side…" (Denton запрещён); вопрос "Can a frost-free hose bib still freeze and burst?" почти повторяет вопрос поста "Can a frost-free spigot still freeze and break?"; "We see it every March." без подтверждения; пометка про LXD Properties устарела. Фразы "hose bib installation" в нём нет.

## 2. Search Console

### 2.1. Итоги

| Период | Запросов | Клики | Показы | Место по показам | Итог Google со скрытыми | Доля известных: клики, показы |
|---|---|---|---|---|---|---|
| 3 месяца (1 июля до 28 сентября 2026) | 44 | 0 | 594 | 33.5 | 2 клика, 1,575 показов, место 21.26 | 0%, 38% |
| 16 месяцев (31 мая 2025 до 28 сентября 2026) | 186 | 1 | 5,507 | 45.3 | 13 кликов, 7,833 показа, место 37.48 | 8%, 70% |

Скрыто: за 3 месяца 981 показ и оба клика, за 16 месяцев 2,326 показов и 12 кликов из 13. 13 месяцев до июля 2026 (вычитанием; все 44 запроса 3 месяцев есть в 16): 4,913 показов, место 46.7, 1 клик.

По группам:

| Группа | 3 мес: запросов · показы · место | 16 мес: запросов · показы · место · клики |
|---|---|---|
| город из десяти | 6 · 389 · 34.6 | 27 · 4,425 · 44.7 · 0 |
| без города | 27 · 89 · 24.4 | 117 · 703 · 54.8 · 1 |
| другое место | 6 · 111 · 38.3 | 29 · 362 · 35.8 · 0 |
| без предмета | 4 · 4 · 4.0 | 11 · 11 · 12.0 · 0 |
| служебный site: | 1 · 1 · 29.0 | 2 · 6 · 24.7 · 0 |

По теме:

| Тема | 3 мес | 16 мес | 13 мес до июля |
|---|---|---|---|
| кран вообще ("faucet" без уличных слов: ключ страницы кранов) | 4 · 361 · 35.9 | 20 · 4,101 · 47.5 · 0 | 3,740 · 48.6 |
| уличный кран (тема этой страницы) | 32 · 223 · 30.1 | 145 · 1,376 · 39.2 · 1 | 1,156 · 41.0 |
| другое (водопровод, гипсокартон, outdoor kitchen) | 3 · 5 · 42.6 | 8 · 13 · 57.2 · 0 | |
| без предмета и site: | 5 · 5 · 9.0 | 13 · 17 · 16.5 · 0 | |

По месту (запросов, показы): 3 мес: 1 до 10: 14, 27; 10 до 20: 16, 45; 20 до 50: 12, 514; ниже 50: 2, 8. 16 мес: 37, 72 (и клик); 19, 396; 50, 3,302; 80, 1,737.

### 2.2. Первые 30 запросов и запросы с кликом

Полные таблицы: `hb-gsc-top30-and-clicks.md`. За 3 месяца первые 30 дают 580 показов из 594, за 16 месяцев 5,096 из 5,507; кликов в первых тридцати нет.

Первые 10 за 3 месяца (показы · место; в скобках 16 месяцев): frisco faucet repair 350 · 35.6 (1,414 · 38.7); hose bib replacement richardson tx 47 · 39.1 (91 · 41.4); hose bib repair richardson tx 43 · 39.0 (74 · 39.5); hose bib installation 36 · 39.6 (129 · 39.1); hose bibb repair allen 26 · 14.1 (307 · 10.7); water spigot texas 11 · 29.2 (22 · 26.7); who to call to fix outdoor spigot 11 · 8.0 (17 · 7.8); leaking outside faucet in cypress tx 10 · 47.0; outdoor faucet repair dfw 8 · 20.8 (17 · 21.5); faucet repair plano 7 · 50.4 (268 · 57.0).

Первые 10 за 16 месяцев, кроме уже названных: faucet repair frisco 1,322 · 42.5; plano faucet repair 460 · 67.9; faucet repair frisco tx 238 · 56.7; little elm faucet repair 134 · 55.8; frisco tx faucet repair 133 · 61.3.

Запрос с кликом один: "who fixes outdoor spigots", за 16 месяцев 5 · 7.2 · 1, за 3 месяца 2 · 10.5 · 0.

### 2.3. Что держат title, H1, H2 и вопросы FAQ

Заголовок «держит» запрос, когда все значимые слова запроса стоят в нём (in, tx и подобные не считаются, множественное число и формы на -ing приводятся к одной, город считается, «near me» считается одним словом и на странице не стоит). Все запросы по каждому заголовку: `hb-gsc-headings.md`.

| Заголовок | 3 мес: запросов · показы | 16 мес: запросов · показы · клики | Из них «кран вообще», 16 мес | Держит только он, 16 мес |
|---|---|---|---|---|
| title "Hose Bib & Outdoor Faucet Repair in Frisco & Plano \| Spigot Replacement" | 6 · 363 | 20 · 4,002 · 0 | 7 · 3,848 | 20 · 4,002 |
| meta description | 11 · 368 | 42 · 4,070 · 0 | 10 · 3,868 | 15 · 45 |
| H1 "Hose Bib Leaking? Outdoor Spigot Busted? We Replace Them Right" | 1 · 1 | 6 · 20 · 0 | 0 | 4 · 8 |
| H2 "What Makes a Hose Bib Installation “Right”?" | 1 · 36 | 1 · 129 · 0 | 0 | 0 (держит и ответ FAQ 3, свёрстанный H2) |
| H2 "Outdoor Faucet Leaking, Hose Bib Dripping or Loose? …" | 1 · 1 | 5 · 17 · 0 | 0 | 3 · 5 |
| H2 "Signs Your Outdoor Faucet Might Be Leaking Inside the Wall…" | 1 · 1 | 1 · 2 · 0 | 0 | 1 · 2 |
| H2 "Outdoor Spigot Problem? Call a Licensed Plumber, Not Just Anyone" | 0 | 1 · 1 · 0 | 0 | 1 · 1 |
| остальные четыре H2 | 0 | 0 | 0 | 0 |
| три вопроса FAQ | 0 | 0 | 0 | 0 |

Что нельзя потерять:
- "Hose Bib" в title и H1: на них стоят все запросы с hose bib ("hose bib repairs", "hose bib faucet repair" держит title, "replace hose bib", "replacing hose bibs" держит H1).
- H2 "What Makes a Hose Bib Installation “Right”?": точная фраза "hose bib installation" (129 · 39.1 за 16 месяцев, 36 · 39.6 за 3) только здесь; в Word тексте её нет.
- "Outdoor Faucet Repair" в title: точная фраза "outdoor faucet repair" (5 · 19.0) только там; у "outdoor faucet repair allen" (29 · 19.2) три слова в title, Allen в H2 "Serving…".
- "Spigot" в title, H1 и H2: запросы со spigot стоят на местах до 10 (who to call to fix outdoor spigot 17 · 7.8, plumber to replace outdoor spigot 3 · 6.0, outdoor spigot replacement near me 6 · 9.3).
- Запрос с кликом "who fixes outdoor spigots" и "hose bibb repair allen" (307 · 10.7) не держит ни один заголовок.
- Вопросы FAQ, первые два H2, H2 "Serving…" и заголовок FAQ запросов не держат: по Search Console их можно менять.

Без единого заголовка (кроме description): 141 запрос, 1,331 показ и единственный клик за 16 месяцев; 29 и 187 за 3 месяца.

### 2.4. Фраза целиком: 20 первых за каждый период и запрос с кликом

Список из 32 запросов (20 первых за 16 месяцев, 20 первых за 3 месяца, запрос с кликом). Точная фраза (подряд, слово в слово, регистр и знаки не в счёт) стоит на живой странице только у двух:
- "hose bib installation": H2 "What Makes a Hose Bib Installation “Right”?";
- "outdoor faucet repair": title.

По правилу проектного инструмента (без in и tx) title содержит ещё "faucet repair frisco" и "faucet repair frisco tx", а "frisco faucet repair" и "frisco tx faucet repair" как перестановку; это всё чужой ключ. "hose bib repairs" инструмент находит в описании только через знак вопроса ("broken hose bib? We repair").

Точной фразы нет нигде (ни в заголовках, ни в тексте, ни в FAQ) у остальных 30, в том числе: запрос с кликом "who fixes outdoor spigots"; "hose bibb repair allen"; "who to call to fix outdoor spigot"; "plumber to replace outdoor spigot"; "outdoor faucet repair allen"; "bib faucet repair"; четыре запроса с "near me"; "plano faucet repair", "faucet repair plano", "little elm faucet repair" (Plano не стоит рядом со словами faucet repair, Little Elm только в списке).

### 2.5. Другие страницы сайта

Все строки: `hb-gsc-other-pages.md`. «Выше»: лучшее место по тому же запросу за тот же период.

**Запросы про уличный кран на всём сайте.** За 16 месяцев таких запросов 190, эта страница стоит в 145 (1,376 показов, место 39.2); за 3 месяца 74 и 32 (223 показа, место 30.1).

| Страница | 3 мес: запросов · показы · место (выше этой: запросов · показы) | 16 мес: запросов · показы · место (выше этой) |
|---|---|---|
| `/plumber-allen-tx/` | 2 · 34 · 5.7 (1 · 33) | 4 · 172 · 14.2 (2 · 34) |
| `/plumber-frisco-tx/` | 12 · 80 · 6.7 (3 · 70) | 18 · 90 · 8.0 (5 · 74) |
| `/plumber-plano-tx/` | 4 · 88 · 7.1 (2 · 86) | 4 · 88 · 7.1 (2 · 86) |
| `/blog/burst-outside-spigot/` | 32 · 73 · 22.1 (1 · 1) | 34 · 81 · 20.8 (3 · 5) |
| `/` (главная) | 0 | 9 · 66 · 10.9 (4 · 59) |
| `/plumber-lewisville-tx/` | 0 | 2 · 33 · 16.1 (1 · 16) |
| `/blog/outside-spigot-replacement-plumber-in-frisco/` | 0 | 1 · 1 · 3.0 (1 · 1) |

Главные строки: "hose bibb repair allen" за 3 мес Allen 33 · 5.7 против 26 · 14.1 (за 16 мес эта выше: 307 · 10.7 против 137 · 12.5); "hose bib replacement allen tx" 16 мес Allen 33 · 21.6 против 5 · 30.8; "outdoor faucet repair dfw" 3 мес Plano 85 · 7.0, Frisco 68 · 6.4 против 8 · 20.8 (за 16 мес ещё главная 55 · 11.2); "outdoor faucet repair lewisville tx" 16 мес Lewisville 16 · 14.2 против 6 · 33.7; "hose bib repair lewisville tx" только Lewisville 17 · 17.9 и главная 2 · 6.0; "frost free spigot leaking" 12 · 17.2 и "is it normal for my outdoor hose bib to leak after the winter thaw?" 16 · 36.6 только у поста.

Что из этого следует по файлам:
- Пост `/blog/burst-outside-spigot/` берёт больше этой страницы: итог Google за 3 месяца 16 кликов, 1,721 показ, место 9.3 (эта 2 · 1,575 · 21.26), за 16 месяцев 19, 2,139, 8.68. Известно только 5% его показов (39 запросов, 86 показов за 3 месяца); по 31 из 32 его известных запросов про уличный кран эта страница не показывается.
- Allen выше этой страницы по "hose bibb repair allen" за последние 3 месяца (пункт 1.6 про её title и раздел).
- Frisco, Plano и главная выше по "outdoor faucet repair dfw" (места от 6 до 11); по остальным запросам темы Frisco и Plano показываются по 1 до 2 раза.
- Пост `/blog/outside-spigot-replacement-plumber-in-frisco/`: за 16 месяцев 0 кликов, 25 показов, место 19; его ключ по карте "outside spigot replacement" совпадает с хвостом title этой страницы "Spigot Replacement".

**Обратная сторона: запросы этой страницы, которые принадлежат другим.**

«Faucet repair плюс город», ключ `/fixture-installation-repair/`. За 16 месяцев на этой странице 17 таких запросов с repair, 4,069 показов, место 47.4, кликов 0; страница кранов стоит в 11 из них. Эта выше в 10 запросах (707 показов), страница кранов выше в 7, в том числе в двух самых больших:

| Запрос (16 мес) | Эта страница | `/fixture-installation-repair/` | Ещё |
|---|---|---|---|
| frisco faucet repair | 1,414 · 38.7 | 1,991 · 24.9 | главная 44 · 6.4 |
| faucet repair frisco | 1,322 · 42.5 | 2,735 · 28.1 | Plano 15 · 15.7 |
| plano faucet repair | 460 · 67.9 | 152 · 62.7 | Plano 1,073 · 42.5; главная 228 · 50.4 |
| faucet repair plano | 268 · 57.0 | 538 · 64.4 | Plano 1,061 · 42.6; главная 178 · 30.0 |
| little elm faucet repair | 134 · 55.8 | 229 · 50.9 | Little Elm 1,111 · 18.0 |

За 3 месяца: frisco faucet repair 350 · 35.6 против 492 · 31.9 у страницы кранов (Frisco 229 · 19.8), faucet repair frisco 2 · 42.5 против 435 · 28.7. По всем запросам «faucet repair» за 16 месяцев на сайте больше всего показов у страницы кранов (18 запросов, 7,026 показов, место 37.9), потом Plano (20 · 4,901 · 39.9), Little Elm (4 · 4,440 · 18.4), эта страница (17 · 4,069 · 47.4).

Другое: "pipe breaks frisco" 2 · 88.5 (водопровод: `/water-lines/` 1,363 · 37.0), "plano wet wall damage" 2 · 74.0 (поиск течи: `/water-leak-detection-frisco-plano/` 72 · 44.3), "outdoor plumbing frisco tx" 3 · 46.0 (Frisco 25 · 5.0), "frisco drywall repair" 1 · 47.0 (не сантехника). Тема «кран вообще» это 20 запросов страницы за 16 месяцев, 4,101 показ, 0 кликов (все строки в `hb-gsc-other-pages.md`).

### 2.6. Уличный кран с каждым из десяти городов

Только запросы про уличный кран (hose bib, spigot, outdoor faucet и подобные) с названием города. Числа: запросов · показы · место.

| Город | Эта страница, 3 мес | Эта страница, 16 мес | Кто ещё, 3 мес | Кто ещё, 16 мес |
|---|---|---|---|---|
| Allen | 1 · 26 · 14.1 (hose bibb repair allen) | 3 · 341 · 11.7 | Allen 1 · 33 · 5.7 | Allen 3 · 171 · 14.3; Frisco 2 · 3 · 42.3 |
| Lewisville | 0 | 1 · 6 · 33.7 | нет | Lewisville 2 · 33 · 16.1; главная 1 · 2 · 6.0 |
| Frisco, Plano, McKinney, Prosper, Celina, Little Elm, The Colony, Carrollton | 0 | 0 | нет | нет |

По правилу темы этого файла за 16 месяцев на всём сайте нет ни одного запроса «уличный кран плюс Frisco» или любой из этих восьми городов.

Для сравнения, «faucet плюс город» на этой странице (чужой ключ, 16 месяцев): Frisco 4 · 3,107 · 42.7 (страница кранов 5 · 5,711 · 33.0), Plano 5 · 757 · 63.8 (кранов 5 · 698 · 64.0), Little Elm 5 · 183 · 57.5 (кранов 3 · 647 · 53.7), McKinney 2 · 19 · 72.0, The Colony 1 · 2, Lewisville 1 · 1; Allen, Prosper, Celina, Carrollton 0.

### 2.7. Слова, которые на страницу не идут

| Что | 3 мес: запросов · показы | 16 мес: запросов · показы |
|---|---|---|
| Чужие места, всего | 6 · 111 | 29 · 362 |
| из них Richardson (запрещён CLAUDE.md) | 2 · 90 | 2 · 165 |
| Denton (запрещён) | 0 | 2 · 18 |
| Dallas (запрещён; "outside faucet pipe burst repair dallas tx", "hose fast dallas") | 0 | 2 · 7 |
| Rockwall | 1 · 2 | 1 · 18 |
| DFW и "north texas" (регион пишем только "North Dallas suburbs") | 1 · 8 | 3 · 26 |
| Хьюстон и окрестности: Cypress, Manvel, Stafford, Briar Forest, Fresno, Spring Branch, Channelview, Copperfield, Tomball, Houston | 1 · 10 | 11 · 105 |
| Allen County, Indiana (не наш Allen: "outdoor faucet replacement allen county in" и ещё три) | 0 | 4 · 10 |
| Sarasota FL, Fort Worth, Farmers Branch, USA | 1 · 1 | 4 · 13 |
| Без предмета: "picture?", "what about this?", "what is this called?", "crooked sideways" и ещё семь (места от 1 до 43; похоже на поиск по фото, по файлам не проверить) | 4 · 4 | 11 · 11 |
| Служебный site: | 1 · 1 | 2 · 6 |
| Другая тема: "outdoor kitchen plumbing in frisco tx", "garden hose repair near me", "insulation cover for outdoor faucet", "pipe breaks frisco" и ещё три | 2 · 2 | 7 · 9 |
| Не наше: "frisco drywall repair"; "replacing outside faucet with sharkbite" (способ, который страница ругает) | 0 | 2 · 2 |
| Слова про цену: "cost to repair outside faucet", "how much to replace hose bib" (цену, кроме $49, не называем) | 0 | 2 · 3 |

Отдельно, не отложено, а названо:
- Написание "bibb" с двумя b: "hose bibb repair allen" (307 показов за 16 месяцев, 26 за 3 месяца) и "outdoor hose bibbs [короткое тире] fixed / replace" (33). Это принятое второе написание слова, не опечатка; на странице его нет.
- «Сделай сам» (how to, how much, what is, what size): 17 запросов, 31 показ за 16 месяцев ("how to fix a hose bib that won't turn off", "how to secure outdoor faucet to brick", "what is a hose bib on a house" на месте 1).
- «Течёт сверху»: "outside faucet leaks from the top" 4 · 82.0, "frost free faucet leaking from top" 3 · 43.3, "frost free spigot leaking top" 3 · 82.3, "frost proof hose bib leaking from top" 1 · 29 (это вакуумный клапан, на странице "The spigot leaks from the vacuum breaker (air gap on top)").
- "near me": 9 запросов этой страницы с "near me", 76 показов за 16 месяцев (5 и 8 за 3 месяца), например "outdoor faucet replacement near me" 37 · 47.5; на странице "near me" нет.

### Как считали и вторая проверка

- Скрипты `hb_lib.py` и `hb_gsc.py` в `/private/tmp/claude-501/-Users-denyskavaler-Projects-fppplumbing-site/d2b78dea-4d58-4222-812f-a40bb43eb5d1/scratchpad/services/hose-bib/` сделаны из копий `docs/briefs/_shared/gsc_plano_lib.py` и `gsc_plano_live.py` (оригиналы не тронуты, `tools/gsc_page_table.py` не запускался). Правила слов те же; города развёрнуты на десять; «тема» делит запросы на уличный кран, кран вообще и другое; ответы FAQ, свёрстанные H2, отделены от разделов.
- Итоги посчитаны трижды (модуль csv, разбор строк без него, awk): 3 месяца 44 запроса, 0 кликов, 594 показа, место 33.54; 16 месяцев 186, 1, 5,507, место 45.31. Те же числа в `source/gsc/page-query-coverage.csv`; итоги со скрытыми из `performance-3m/Pages.csv` и `performance-16m/Pages.csv`.
- Группы сходятся с итогом: 6 + 27 + 6 + 4 + 1 = 44 и 389 + 89 + 111 + 4 + 1 = 594; 27 + 117 + 29 + 11 + 2 = 186 и 4,425 + 703 + 362 + 11 + 6 = 5,507. Темы тоже: 361 + 223 + 5 + 5 = 594; 4,101 + 1,376 + 13 + 17 = 5,507.
- Руками сверены "frisco faucet repair" (350 · 35.58 и 1,414 · 38.74), "who fixes outdoor spigots" (5 · 7.2 · 1) и "hose bibb repair allen" (307 · 10.68); в `performance-16m/Queries.csv` (весь сайт) "hose bibb repair allen" 368 показов, место 9.71.
