# PRV replacement: живая страница и Search Console (3 октября 2026)

Справка перед переписыванием https://fppplumbing.com/prv-replacement-frisco-plano/ . Текст страницы не пишется, в проекте ничего не менялось. Источники: краул от 30 сентября 2026 (`source/crawl/`), новый сайт `site/src/content/pages/prv-replacement-frisco-plano.md` и `site/dist/prv-replacement-frisco-plano/index.html` (только чтение), правки `tools/build_launch_content.py` и `site/src/data/launch-changes.csv`, `reviews/`, `photos/captions-en.csv`, `source/gsc/`, `seo/keyword-map.md` и `.csv`, `docs/pages-plan.md`. Одобренного текста этой страницы в `source/` нет. Расчёты: копии `docs/briefs/_shared/gsc_plano_lib.py` и `gsc_plano_live.py`, переделанные под страницу (`prv_lib.py`, `prv_gsc.py`, `prv_extra.py`, `links_in.py` в scratchpad сессии).

Длинные таблицы в `docs/briefs/services/prv/`: `prv-gsc-table-3m.md` и `prv-gsc-table-16m.md` (все запросы), `prv-gsc-top30.md`, `prv-gsc-headings.md` (что держит каждый заголовок), `prv-gsc-other-pages.md` (запросы про PRV и давление на всём сайте), `prv-links-in.md` (ссылки на страницу).

## Коротко

- Кормят страницу скрытые запросы: по данным Google 19 кликов, 1,390 показов, место 8.6 за 3 месяца; 35, 2,443, 9.8 за 16 месяцев. Запросы с текстом дают 81 показ (6%) и 187 (8%) и 0 кликов. Показов в месяц стало 463 против 81 за 13 месяцев до того.
- Видимые запросы: "plumbing pressure test near me" (30 показов, место 2.6), семья "how to adjust a prv" (18 показов, место 1.0, только за 16 месяцев), семья "how long does a prv last" (15, места 2 до 13), "prv water pressure" (7, место 1.0), "shut-off valve replacement near me" (11, место 18.6).
- Нельзя потерять: "PRV / Water Pressure Regulator" в title, H1, слово adjust (описание, H2 и вопрос FAQ про регулировку), H2 и вопрос FAQ про срок службы, "water pressure test" (вступление и последний H2), "plumber near me" со ссылкой.
- Против правил и на живой, и на новой: цены $499 и $799 (раздел, ответ FAQ, FAQPage); 9 FAQ; "the owners had no idea"; манометр "120 PSI", по виду не снимок с работы, и "100 to 120 PSI" при максимуме Дениса 105; "North Texas" трижды; ссылка на главную в первом абзаце; два города из десяти.
- Исправлено только на новом: "4,000 jobs" и "North Dallas", телефоны в тексте, "Real cost ranges" в описании, FAQ не заголовки, схема (лицензия, десять городов, без цен в Service), OG title.
- Не хватает по правилу 8: восьми городов с анкором "plumber in ...", списка «симптом и ссылка», своего раздела «если это происходит сейчас» (на новом сайте частично боковой блок шаблона); шесть из девяти FAQ повторяют свои H2. Не связаны: расширительный бак (ссылка ведёт на `/water-heaters/`), water lines, leak detection, toilet repair, гайд PRV.
- Чужие страницы на запросах услуги: Frisco 2.8 по "pressure reducing valve replacement", главная и Frisco 1.0 по "prv installation", гайд PRV по "prv replacement" и "pressure reducing valve replacement" (места около 30), Plano по "prv plumbing". Три ключа страницы по карте не дают ни одного видимого показа никому.
- Отзывы: на живой Megan E и Kseniia, тексты совпадают с архивом; на новой странице отзывов нет, в архиве у обоих нет уровня Local Guide. Фото: два, оба вне архива; в архиве для страницы помечено 17 фото и клипов.

## 1. Живая страница

### 1.1. Title, описание, H1, заголовки, объём

Ответ 200, в page-sitemap.xml, canonical на себя, index и follow. В схеме опубликована 6 мая 2025, правка 17 августа 2026.

| Что | На живой странице |
|---|---|
| Title (59 знаков) | "PRV / Water Pressure Regulator Replacement \| Frisco & Plano" |
| Meta description | "Water pressure too high or dropping after 20 seconds? We test first, then adjust or replace the PRV. Real cost ranges for Frisco and Plano." |
| H1 | "Pressure Reducing Valve (PRV) Replacement for Low or High Water Pressure in Frisco & Plano" (в крауле в конце невидимый знак zero width space) |
| OG title | "Pressure Reducing Valve (PRV)" (не как title) |
| Хлебные крошки в схеме | "Main" > "Pressure Reducing Valve (PRV)" |

H2 по порядку (в скобках слов под заголовком, мой счёт, маркеры списков не считаются):
1. "What a Pressure Reducing Valve Does" (150)
2. "Signs a Pressure Reducing Valve Is Failing" (184, вместе с подписью фото)
3. "How High Water Pressure Damages Plumbing" (161)
4. "Can a Bad PRV Cause Low Water Pressure?" (163)
5. "How Long Does a Pressure Reducing Valve Last?" (202)
6. "Where the PRV Is Located in Frisco and Plano Homes" (332, с двумя H3: "Outdoor PRVs in Front Flower Beds", "PRVs Inside Garage Access Panels")
7. "Can a PRV Be Adjusted, or Does It Need Replacement?" (170)
8. "PRV Replacement Cost in Frisco & Plano" (146)
9. "How FPP Plumbing Replaces a PRV" (206)
10. "PRV Replacement in Frisco and Plano, TX" (114)
11. "Pressure Valve Questions We Get All the Time" (заголовок FAQ, под ним 9 вопросов H3)
12. "What North Dallas Homeowners Say About Our PRV Work." (отзывы)
13. "Schedule a Water Pressure Test or PRV Replacement" (заключение)
14. "980-899-7997 469-998-8999" (не раздел: нижняя панель звонка шаблона старого сайта свёрстана тегом H2)

H3: 11 (два подраздела про место PRV и 9 вопросов FAQ).

Объём: краул считает 2,902 слова (всё от H1 до кнопки Request Service, с маркерами списков и отзывами). Свой текст 2,652 слова: H1 14, вступление 116, заголовки H2 82, десять разделов 1,828, вопросы FAQ 75, ответы FAQ 401, заключение с его H2 136. Блок отзывов 201 слово. Своё вступление: три абзаца, третий из одной фразы.

Слова в своём тексте: "PRV" 51 раз (вместе с "PRVs"; 52 с H2 отзывов), "pressure reducing valve" 9, "water pressure" 13, "PSI" 12, "Frisco" 17, "Plano" 10, "plumber near me" 1, "North Texas" 3; McKinney, Allen, Prosper, Celina, Little Elm, The Colony, Carrollton, Lewisville в тексте 0 (Lewisville только в alt фото).

### 1.2. Девять вопросов FAQ

Все девять тегом H3 в раскрывающемся списке Elementor (`e-n-accordion-item-title-text`). Схема FAQPage совпадает со страницей слово в слово по всем девяти (проверено).

1. "What is normal water pressure for a house?"
2. "How much does PRV replacement cost in Frisco?"
3. "How do I know if my pressure reducing valve is bad?"
4. "Can a bad PRV cause low water pressure throughout the house?"
5. "Where is the PRV located?"
6. "How long does a residential PRV last?"
7. "Can a plumber adjust the PRV instead of replacing it?"
8. "Does PRV replacement require a permit?"
9. "Does a PRV affect the water heater expansion tank?"

Дословно ни один не стоит на других 63 живых страницах и на других страницах нового сайта. Близкие: у гайда `/plumbing-guide/water-pressure-dropping-tips-2026/` вопрос "How do I know if my pressure reducing valve is failing?" (отличие в одном слове от вопроса 3) и "Can I replace a pressure reducing valve myself?"; у Carrollton и Little Elm вопрос "My whole house lost water pressure. Is that the PRV?" (близко к вопросу 4); у `/water-lines/` "Why did my water pressure drop everywhere at once?"; у Plano "My PRV is buried in a box in the ground. Is that a problem?"; у гайда PRV "Do I need a PRV?" и "Can I replace a PRV myself?". На живой странице Frisco стоит "Why do PRVs fail so often in Frisco homes?", на новом Frisco его нет, он отложен для страницы PRV (`source/dictation/2026-10-02-frisco-reserve-for-service-pages.md`).

Внутри страницы шесть вопросов из девяти повторяют темы своих H2: вопрос 2 и H2 цены, 3 и H2 признаков, 4 и H2 про низкое давление, 5 и H2 про место, 6 и H2 про срок службы, 7 и H2 про регулировку.

Новый сайт: те же девять, жирным текстом в `<summary><strong>`, не заголовком; FAQPage в схеме те же девять.

### 1.3. Отзывы

На живой странице два отзыва Google в карусели Elementor, у обоих аватар картинкой (`IMG_5505.jpg` без alt и `google-review-avatar-kseniia.jpeg`).

1. Megan E. Подпись на странице: "★★★★★ · Local Guide Level 2 · April 2025 · Google", ссылка https://maps.app.goo.gl/gdDMm12ngNdDV6Uc7?g_st=ic . Текст: "I was having crazy water pressure problems for weeks. Sometimes the water would slow down to almost nothing, especially when I was in the middle of a shower!!! Then it would come back like nothing was wrong. It was driving me crazy and no one could figure it out!!! Denys and his guy from FPP Plumbing stopped by , found the problem fast, and explained everything in a way that made sense. The PRV valve was packed with calcium buildup and wasn’t working right. He replaced it quickly, and the water pressure has been perfect ever since! Now Denys from FPP Plumbing is my go-to plumber !!!"
   Архив: Google, профиль Plano, 2025-04-26, `on_old_site` = эта страница; текст совпадает знак в знак (краул только склеил абзацы); ссылка длинная (google.com/maps/reviews/...), `local_guide_level` пустой.
2. Kseniia. Подпись: "★★★★★ · Plano, TX · Local Guide Level 5 · June 2026 · Google", ссылка https://maps.app.goo.gl/dWbSpWeCDsYtFfQ38?g_st=ic . Текст: "PRV replacement in Plano made a huge difference for us. Our water pressure dropped to about 30 PSI, and taking a shower was getting really annoying. I called the city first, and they told me it was probably a bad PRV. FPP Plumbing came out, replaced the PRV and the shutoff valve, and now we’re right around 60 PSI. Finally feels like a normal shower again. Good guys, solid work."
   Архив: "Ксенія" (кириллицей), Google, профиль Plano, 2026-06-27, `on_old_site` = эта страница, текст совпадает знак в знак, `local_guide_level` пустой; латинского имени в `DISPLAY` (`tools/build_site_reviews.py`) нет.

Новый сайт: в `reviews/site-reviews.json` ключа этой страницы нет, на собранной странице нет ни отзывов, ни их заголовка (метка `<!-- reviews -->` стоит). Ни Megan E, ни Ксенія не стоят ни на одной странице нового сайта (`reviews/site-ledger.md`, 40 авторов). Пустой уровень Local Guide значит «неизвестно», и `tools/build_site_reviews.py` останавливает сборку на таком отзыве. Ксенія называет Plano; вопрос о её переносе на Plano уже стоит в `docs/briefs/plano/5-review-candidates.md`.

Ещё отзывы про PRV в архиве, нигде на новом сайте не стоят: Inna Kravchenko (Google, Plano, 2026-01-11, PRV во flower bed, "plumber near me", "showed up fast"; тот же текст, только без апострофов, на Thumbtack от Inna K., 2026-01-10), Elnard KA (Google, Plano, 2025-07-07, PRV и главный кран, имя Дениса, "North Dallas"), Viktoriia Stekhina (в архиве "Виктория Стехина", Google, Frisco, 2026-02-03, PRV и кран; стоит только на живой странице Frisco, в `reviews/site-reviews.json` и `reviews/site-ledger.md` её нет).

### 1.4. Фото

| Файл | Alt | Что это |
|---|---|---|
| `/wp-content/uploads/2024/12/photo_2024-12-24_18-56-20-e1786397582748-894x1024.jpg` | "Newly installed PRV valve set in ground near water meter during outdoor plumbing in Lewisville, TX" | Новый PRV в коробе на гравии, по виду настоящий снимок с работы. Тот же кадр в старой галерее `/gallery/`, он же og:image и главная картинка в схеме. В `photos/index.csv` его нет; город держится только на старом alt (так же отмечено в брифе Lewisville). |
| `/wp-content/uploads/elementor/thumbs/high-water-pressure-120-psi-plano-tx-...jpg` | "Water pressure gauge showing extremely high 120 PSI water pressure in Plano, TX"; подпись "Water pressure gauge reading 120 PSI at a home in Plano, Texas." | По виду не снимок с работы: шкала идёт 0, 20, 40, 60, 80, 100, 120, 160, 140, 160, 280, 200, над манометром нарисован красный восклицательный знак. В архиве такого кадра нет. В схеме Service живой страницы это `image`. |
| `IMG_5505.jpg`, `google-review-avatar-kseniia.jpeg` | пустой и "google-review-avatar-kseniia" | аватары в отзывах |
| логотип дважды, знак BBB | | шаблон |

Новый сайт: те же две картинки с теми же alt и подписью. В архиве `photos/captions-en.csv` для этой страницы помечено 17 номеров: Frisco 44, 46, 47 (47 записан главным фото страницы), 48, 80 (клип), 81, 82 (клип), 83, 97 (клип), 153, 197, 198, 199 (клипы); McKinney 7, 51; Carrollton 27; Prosper 36.

### 1.5. Ссылки

Из текста страницы (меню, шапка и подвал не в счёт), живой и новый сайт одинаково:

| Анкор | Куда |
|---|---|
| "plumber near me" | `/` (первый абзац вступления: "If you are searching for a plumber near me because the water blasts out of every faucet...") |
| "slab leak" | `/slab-leak-repair-frisco-plano-mckinney/` |
| "other causes of whole-house water pressure dropping" | `/plumbing-guide/water-pressure-dropping-tips-2026/` |
| "faucet and shower valve repairs" | `/fixture-installation-repair/` |
| "find and operate the main water shutoff" | `/plumbing-guide/how-to-shut-off-main-water-valve-texas/` |
| "water heater repair and replacement" | `/water-heaters/` |
| "Frisco plumbing team" | `/plumber-frisco-tx/` |
| "Plano plumbing team" | `/plumber-plano-tx/` |
| "Contact FPP Plumbing" | `/contact/` |
| "emergency plumbing service" | `/emergency-plumbing-services/` |

Внешние из текста: "City of Frisco’s PRV guidance" (https://www.friscotexas.gov/DocumentCenter/View/8867/Pressure-Reducing-Valves-PRVs-PDF) и ссылки отзывов на Google. Остальное шаблон: соцсети, BBB, tel:, mailto:, "Found us" в подвале.

Десять городов в тексте: связаны Frisco и Plano, не связаны McKinney, Allen, Prosper, Celina, Little Elm, The Colony, Carrollton, Lewisville (все десять только в меню и подвале). Смежные: связаны slab leak, faucet, water heaters, emergency и два гайда; не связаны expansion tank (`/water-heater-repair-frisco-mckinney/`), water lines, leak detection, toilet repair, hose bib, гайд PRV, гайд про автоматический кран.

Ссылки на страницу (`prv-links-in.md`): на живом сайте 29 ссылок с 25 страниц, на новом 28 с 24 страниц плюс главная. Все девять других городов ставят анкор "PRV replacement" (строки "Pressure that fades or feels too strong" или "Pressure too high or too low"; у Plano ещё "PRV valve replacement"), живой Frisco "PRV and main water valve replacement", новый Frisco "PRV replacement" и "a new PRV". Три гайда ставят ссылку на слова не про PRV: "water pressure" (slab leak Plano), "water flow" (шумный водонагреватель), "water pressure dropping" (падение давления). Carrollton и Little Elm отправляют сюда за ценой: "Details and pricing on our PRV replacement page.", "Pricing and details on our PRV replacement page.". Главная нового сайта: одна ссылка в разделе "Same-Day Plumbing Services in Frisco, Plano & McKinney" ("Pressure high enough to bang the pipes, or fading in the shower: PRV replacement").

### 1.6. Против правил CLAUDE.md

«Новый» значит: стоит ли это на странице нового сайта после точечных правок.

Цены (кроме $49 никаких цен):
- Раздел цены: "Straight numbers. PRV replacement labor at FPP Plumbing starts at $499 when the valve sits in a garage access panel, and starts at $799 when it lives outside in a flower bed valve box, where digging, cleanup, and corroded fittings are part of the job." Новый: стоит ("flag not changed" в `launch-changes.csv`).
- Ответ FAQ 2: "Labor starts at $499 for a PRV in a garage access panel and at $799 for a valve buried in a flower bed box, with the valve itself priced on top." Новый: стоит, и в FAQPage схемы.
- Схема Service: два Offer с `minPrice` 499 и 799. Новый: цен в Service нет.
- Описание: "Real cost ranges for Frisco and Plano." Новый: "Flat price quoted before the work, in Frisco and Plano." (цены в тексте остались).
- Без цифры: "you pay for the pressure test and the adjustment, not for a valve you did not need." Правило о вызове за $49 на странице не названо. Новый: стоит.

Не делаем и не заявляем: tankless, reroute, hydro jetting, газ, backflow не найдены. Гарантия: сроков нет. Приезд: в своих словах обещаний нет; в отзыве Megan E "found the problem fast" и "He replaced it quickly" (слова клиента, остаются).

Регион и города:
- H2 отзывов "What North Dallas Homeowners Say About Our PRV Work." Новый: "...Homeowners in the North Dallas Suburbs..." (блок не выводится).
- "We have handled over 4,000 jobs across North Dallas, and pressure problems come up far more often than people think." Новый: "We have served 4,500+ happy customers across the North Dallas suburbs, ...".
- Схема Organization: "surrounding North Dallas communities". Новый: нет.
- "North Texas" трижды: "In our North Texas service work, about 5 to 15 years is common for a residential PRV.", то же в ответе FAQ 6, "...North Texas climate and soil conditions can cause service life to vary greatly." Прямого запрета нет, но регион по правилу называется только "North Dallas suburbs". Новый: стоит.
- Схема Service: `areaServed` восемь городов без Carrollton и Lewisville. Новый: десять и Park Cities.
- Alt первого фото называет Lewisville, город не проверен (1.4). Новый: стоит.

Границы (правило 9 и карта ключей):
- Бак и тепловое расширение: вопрос FAQ 9 и абзац "We also separate PRV pressure creep from thermal expansion... Sorting that out is part of our water heater repair and replacement work as well." со ссылкой на `/water-heaters/`; по карте "expansion tank replacement" у `/water-heater-repair-frisco-mckinney/`, ссылки на неё нет. Новый: так же.
- "...or the water meter moves with every fixture off, the source should be checked.": метод leak detection, одно предложение без ссылки. Новый: так же.
- Slab leak, низкое давление, главный кран, смесители: по предложению со ссылкой на хозяина, по правилу.

Телефоны в тексте: "● Frisco: Call or text 469-998-8999 ● Plano: Call or text 980-899-7997". Новый: "Call or text the office closest to you"; H2 шаблона с телефонами нет.

Owner: "We’ve tested homes in Frisco running at 100 to 120 PSI where the owners had no idea." Новый: стоит.

FAQ: H3 и 9 вопросов при норме 5 до 7. Новый: жирный текст, всё ещё 9.

Тире: нет нигде (текст, заголовки, описание, alt, схема).

Цифры без источника и картинка: "100 to 120 PSI" и манометр "120 PSI" (1.4); у Дениса (`source/dictation/2026-10-02-frisco-additions.md`): "On the gauge we very often see pressure above 80, 90 PSI. In some houses even 105." Для "about 5 to 15 years" и "homes built through roughly the mid-to-late 2010s" источника в диктовках нет. Новый: стоит.

Правило 6: анкор "plumber near me" верный, но в первом абзаце и привязан к услуге ("because the water blasts out of every faucet..."). Правило 7: связаны два города из десяти, анкоры "Frisco plumbing team", "Plano plumbing team". Новый: так же.

Схема, прочее: Organization вместо Plumber, "Texas Master Plumber License M-44816", `numberOfEmployees` 1 до 10, `foundingDate` 2022-09-13; OG title не равен title. Новый: Plumber с "Responsible Master Plumber, License M-44816" в `hasCredential`, OG title равен title.

Слоганы и вода: "High pressure feels great in the shower. It is also quietly destroying every seal and connection in the house."; "Sometimes it is subtle. Sometimes it ends in a flood."; "Straight numbers."; "One honest note:"; "We replace what actually failed."; "It is easier to find, easier to test, easier to adjust, and easier to replace." Новый: стоит.

### 1.7. Что на живой странице настоящее, из работы

- "One common pattern is pressure that feels normal when a faucet or shower is first opened, then drops after 20 or 30 seconds. The water sitting in the piping provides the initial pressure. Once the house needs continuous flow, the restricted valve cannot keep up." (то же описывает отзыв Megan E)
- Три замера: "Static pressure", "Pressure under flow", "Pressure stability: whether the setting holds after the water is turned off and after the system cycles."; и "a static reading by itself does not show whether the valve can maintain flow."
- "The PRV is often in the same box as, or immediately beside, the home’s secondary main shutoff valve. That shutoff is separate from the city-side valve at the water meter." и "Some boxes stay full of mud or water from rain and irrigation." (совпадает с фото 46, 47 и клипами 197 до 199)
- "Many newer homes route the main water line into the garage and place the PRV and house shutoff behind an access panel."
- "Do not force a buried, corroded, or seized valve. It can break and turn a pressure problem into a water leak."
- "A dripping water heater relief valve does not automatically mean the PRV is bad." "If only one faucet or one shower has weak flow, the PRV is less likely to be the problem." "We also separate PRV pressure creep from thermal expansion."
- "Install the correctly sized valve in the correct flow direction and leave it accessible for future service." "The secondary shutoff valve is often installed beside the PRV and may be the same age."
- Из документа города (ссылка стоит): "The City of Frisco states that replacing a PRV requires a permit, while repair or maintenance of the internal components does not." и "a house built in Frisco after 2001 is likely to have a PRV."
- Отзыв Kseniia: 30 PSI до замены, около 60 после, город сам сказал про PRV.

Материал Дениса для этой страницы, которого на ней нет (диктовки, не одобренный текст): `source/dictation/2026-10-02-frisco-additions.md` (часто выше 80 и 90 PSI, бывает 105; обычно ставим 70 PSI; из за жёсткой воды 30 PSI, когда PRV плохой; три способа отказа: забивается, перестаёт держать, течёт в коробе; работа во Frisco, клипы 197 до 199); `source/dictation/2026-10-02-frisco-reserve-for-service-pages.md` (вопрос "Why do PRVs fail so often in Frisco homes?" с ответом); `source/dictation/2026-10-01-warranty-and-care.md` (абзац 7: выше 80 PSI система под нагрузкой, мерить каждый год; сроки гарантии только для сведения); `source/approved-text-edits.md` (строка "No pressure"). `docs/pages-plan.md`: "Добавляем глубину (ваш абзац про давление 80 PSI)".

### 1.8. Новый сайт против живой страницы

Стоит текст живой страницы с точечными правками (`tools/build_launch_content.py`, `launch-changes.csv`, строки 561 до 569). Одобренного текста из `source/` нет.

Изменено: описание ("Real cost ranges for Frisco and Plano." на "Flat price quoted before the work, in Frisco and Plano."); "We have handled over 4,000 jobs across North Dallas," на "We have served 4,500+ happy customers across the North Dallas suburbs,"; телефоны в заключении на "Call or text the office closest to you"; H2 отзывов на "North Dallas Suburbs"; карусель отзывов на метку `<!-- reviews -->` (отзывов в файле нет, блок пустой); FAQ из H3 в жирный текст; невидимый знак в H1 убран; схема заменена целиком (Plumber с двумя офисами и лицензией по правилу, Service без цен и с десятью городами и Park Cities, FAQPage, BreadcrumbList "Home" > "PRV / Water Pressure Regulator Replacement"); OG title равен title; H2 с телефонами шаблона ушёл.

Оставлено с пометкой "flag not changed": цены $499 и $799 в тексте и в FAQ. Не тронуто: "owners", "North Texas", "100 to 120 PSI" и картинка манометра, ссылка на главную в первом абзаце, два города из десяти, девять FAQ.

Шаблон нового сайта добавляет боковой блок "What is happening right now?" (вода на полу, нет горячей воды, канализация, нет давления; ссылка на главный кран, звонок в офисы, Request Service) и тег noindex на тестовой копии.

## 2. Search Console

### 2.1. Итоги

| Период | Запросов с текстом | Клики | Показы | Место (по показам) | Google, вся страница: клики · показы · место |
|---|---|---|---|---|---|
| 3 месяца (1 июля до 28 сентября 2026) | 30 | 0 | 81 | 11.1 | 19 · 1,390 · 8.61 |
| 16 месяцев (31 мая 2025 до 28 сентября 2026) | 55 | 0 | 187 | 19.6 | 35 · 2,443 · 9.76 |

Скрыто Google: за 3 месяца 19 кликов и 1,309 показов (видно 5.8% показов), за 16 месяцев 35 кликов и 2,256 показов (видно 7.7%). Совпадает с `source/gsc/page-query-coverage.csv` (81 и 187 показов, 30 и 55 запросов, 6% и 8%). Тринадцать месяцев до последних трёх (16 минус 3, данные Google): 16 кликов, 1,053 показа, место 11.3, это 81 показ в месяц против 463 в месяц за последние 3 месяца. Страница правилась в WordPress 17 августа 2026; что было до правки, файлы не показывают.

По группам (запросов · показы · место):

| Группа | 3 месяца | 16 месяцев |
|---|---|---|
| без города | 15 · 59 · 9.0 | 34 · 114 · 8.2 |
| Frisco или Plano в запросе | 3 · 4 · 18.2 | 5 · 24 · 58.5 |
| место вне десяти городов | 2 · 5 · 38.0 | 4 · 29 · 37.9 |
| мусор и навигация (yes, images, site:) | 7 · 7 · 10.7 | 9 · 14 · 14.4 |
| чужая компания | 1 · 3 · 7.7 | 1 · 3 · 7.7 |
| бренд (fpp plumbing) | 1 · 2 · 2.0 | 1 · 2 · 2.0 |
| индекс Plano (75075) | 1 · 1 · 6.0 | 1 · 1 · 6.0 |

### 2.2. Топ 30 по показам и запросы с кликами

Запросов с кликами нет ни за 3, ни за 16 месяцев: все клики страницы приходятся на скрытые запросы. Обе таблицы топ 30: `prv-gsc-top30.md`; все запросы с другими страницами и хозяином по карте: `prv-gsc-table-3m.md`, `prv-gsc-table-16m.md`.

За 3 месяца запросов всего 30 (81 показ), первые по показам (показы · место): "plumbing pressure test near me" 30 · 2.6; "shut-off valve replacement near me" 11 · 18.6; "pressure reducing valve installation jonestown tx" 3 · 34.3; "pressure relief valve outside house" 3 · 11.3; "water works plumbing prv repair and replacement" 3 · 7.7; по 2 показа "fpp plumbing" (2.0), "good house pressure for frisco texas" (13.0), "low pressure" (9.5), "pressure reducing valve replacement spicewood tx" (43.5), "water pressure down in my area" (10.0), "what is prv in plumbing" (61.0); остальные 19 по одному показу, из них 7 мусорных.

За 16 месяцев топ 30 из 55 (162 показа из 187), первые: "plumbing pressure test near me" 30 · 2.6; "prv replacement denton tx" 22 · 37.9; "frisco water line repair" 18 · 63.4; "shut-off valve replacement near me" 11 · 18.6; "how to adjust a prv" 10 · 1.0; "how long does a prv last" 7 · 10.9; "prv water pressure" 7 · 1.0; "best prv valve repair near me" 5 · 4.4; "how long do prvs last" 5 · 13.0; "site:http://fppplumbing.com" 5 · 19.0; "how long does a prv valve last" 3 · 2.0; "how to adjust prv" 3 · 1.0; "pressure reducing valve" 2 · 4.5; "prv installation" 2 · 8.5.

Семьи запросов за 16 месяцев: "how to adjust" (7 запросов, 18 показов, все на месте 1.0: how to adjust a prv, how to adjust prv, adjust prv, how to adjust prv valve, how to adjust a pressure regulator, how to adjust high water pressure, how to adjust water pressure in the house); "how long ... last" (3 запроса, 15 показов, места 2.0, 10.9, 13.0). Ни одного из них нет за последние 3 месяца.

### 2.3. Что держат заголовки

Правило: все значимые слова запроса стоят в заголовке (in, tx, how, what, does и оценочные слова не считаются). Полная таблица: `prv-gsc-headings.md`. Числа: показы · место за 16 месяцев.

- **Title**: "prv water pressure" (7 · 1.0, точная фраза стоит только здесь), "prv replacement cost" (1 · 7.0), "frisco", "prv"; если PRV и pressure reducing valve считать одним словом, ещё "pressure reducing valve" (2 · 4.5).
- **Описание** ("...We test first, then adjust or replace the PRV..."): вся семья "how to adjust" (18 показов, место 1.0) и "prv water pressure". На новом сайте эта часть описания та же.
- **H1**: "prv water pressure", "low pressure" (2 · 9.5, есть и за 3 месяца), "pressure reducing valve" (точная фраза), "prv replacement cost".
- **H2 "Can a Bad PRV Cause Low Water Pressure?"** и вопрос FAQ 4: "prv water pressure", "low pressure".
- **Вопрос FAQ 6 "How long does a residential PRV last?"**: "how long does a prv last" (7 · 10.9), "how long do prvs last" (5 · 13.0), "how long does a prv valve last" (3 · 2.0). H2 "How Long Does a Pressure Reducing Valve Last?" держит их, только если PRV и pressure reducing valve одно слово. Точной фразы нет нигде (в вопросе мешает "residential").
- **Вопрос FAQ 7 "Can a plumber adjust the PRV instead of replacing it?"**: семья "how to adjust". H2 "Can a PRV Be Adjusted, or Does It Need Replacement?" по правилу не держит ("adjusted" не "adjust"), тема та же.
- **H2 "What a Pressure Reducing Valve Does"**, H2 признаков, вопрос FAQ 3: "pressure reducing valve" (2 · 4.5).
- **H2 и вопрос FAQ про место PRV**: "where is the prv located in a house" (1 · 11.0, и за 3 месяца) и "pressure reducing valve location in house" (1 · 1.0) не держат только из за слова house.
- **H2 цены и вопрос FAQ 2**: "prv replacement cost" (1 · 7.0), "price" (2 · 9.5). Здесь же стоят запрещённые цены; запросов за ними почти нет.
- **H2 "Schedule a Water Pressure Test or PRV Replacement"**: "prv water pressure". Слова "water pressure test" стоят здесь и во вступлении, но "plumbing pressure test near me" не держит ни один заголовок (нет plumbing).
- Ничего не держат: H2 "How High Water Pressure Damages Plumbing", "Pressure Valve Questions We Get All the Time", вопросы FAQ 1 (ближе всех к "good house pressure for frisco texas", 2 · 13.0), 8 и 9.
- Крупные видимые запросы без заголовка: "plumbing pressure test near me" (30 · 2.6), "shut-off valve replacement near me" (11 · 18.6), "best prv valve repair near me" (5 · 4.4), "prv installation" (2 · 8.5).

Нельзя потерять: "PRV" и "Water Pressure" рядом в title; H1 с "Pressure Reducing Valve (PRV) Replacement" и "Low or High Water Pressure"; adjust в описании и в вопросе или H2 про регулировку; вопрос или H2 "how long does a PRV last"; "water pressure test"; "plumber near me"; "secondary shutoff valve" рядом с PRV.

### 2.4. Фраза целиком

Проверен 31 запрос: топ 20 за 16 месяцев и топ 20 за 3 месяца (запросов с кликами нет). Точная фраза стоит на странице у 5: "prv water pressure" (title), "pressure reducing valve" (H1, три H2, вопрос FAQ 3, текст), "low pressure" (текст: "...or it may restrict the water and cause low pressure"; в ответе FAQ 3 только через запятую "too high or too low, pressure"), "frisco" (везде), "fpp plumbing" (H2 "How FPP Plumbing Replaces a PRV", текст). Мягко (без in, tx, how, множественное число не в счёт) стоят ещё три: "how to adjust a prv" и "how to adjust prv" (вопрос FAQ 7) и мусорный "find part". Остальные 23 не стоят ни точно, ни мягко, из них по услуге: "plumbing pressure test near me" (во вступлении "whole-house water pressure test", рядом "plumber near me"), "shut-off valve replacement near me", "how long does a prv last", "how long do prvs last", "how long does a prv valve last", "best prv valve repair near me", "what is prv in plumbing", "pressure relief valve outside house", "water pressure down in my area", "good house pressure for frisco texas", "where is the prv located in a house". Остальные чужие места, чужая компания, мусор и чужие темы (water line, hydrostatic testing, pipe breaks).

### 2.5. Другие страницы на запросах этой услуги и обратная проверка

Полный разбор по страницам и запросам: `prv-gsc-other-pages.md` (набор «PRV»: в запросе prv, pressure reducing, reducer или regulator; набор «давление»: water pressure, low pressure, pressure test и подобные).

Запросы «PRV» на всём сайте (запросов · показы · место; запрос с чужой компанией "water works plumbing prv repair and replacement", 3 показа у этой страницы, сюда не входит; в таблице главные страницы, остальные с 1 до 8 показами в полном файле):

| Страница | 3 месяца | 16 месяцев |
|---|---|---|
| `/` | нет | 8 · 110 · 8.6 |
| эта страница | 8 · 12 · 28.8 | 23 · 83 · 17.7 |
| гайд PRV `/plumbing-guide/pressure-reducing-valve-replacement-guide-2026/` | нет | 22 · 81 · 34.5 |
| `/plumber-frisco-tx/` | 2 · 4 · 8.0 | 5 · 71 · 2.8 |
| `/plumber-lewisville-tx/` | нет | 2 · 28 · 17.4 |
| `/plumber-carrollton-tx/` | нет | 1 · 17 · 29.5 |
| `/plumber-plano-tx/` | 4 · 14 · 8.3 | 4 · 14 · 8.3 |
| `/contact/` | нет | 2 · 11 · 32.6 |

За 3 месяца у Plano по запросам «PRV» показов больше, чем у самой страницы PRV (14 против 12). За 16 месяцев страница PRV есть в 23 из 56 таких запросов.

Где другая страница выше или берёт показы (16 месяцев, показы · место):
- "prv installation": главная 53 · 1.0 и Frisco 51 · 1.0 против PRV 2 · 8.5 (место 1.0 у двух страниц сразу похоже на карточку Google, выгрузка этого не доказывает).
- "pressure reducing valve replacement": Frisco 11 · 2.8, гайд PRV 5 · 30.0, страницы PRV нет.
- "prv plumbing": главная 19 · 12.4, Plano 10 · 10.6 (и за 3 месяца), Frisco 5 · 10.0; "pressure reducing valve (prv) installation": Plano 2 · 1.0; "prv near me": Plano 1 · 1.0, Frisco 1 · 2.0; "water pressure regulator repair": Plano 1 · 7.0; "water pressure regulator": главная 1 · 15.0; "pressure reducer valve": главная 2 · 11.5. Страницы PRV нет ни в одном.
- Гайд PRV: "replacing a pressure reducing valve" 15 · 27.1, "how to replace a pressure reducing valve" 12 · 27.6 (его ключ), "prv replacement" 7 · 29.1, "prv valve replacement" 7 · 31.9 (его вторичный ключ по карте), "replace pressure reducing valve" 7 · 31.1, "water pressure reducing valve replacement" 4 · 30.8, "prv installation and replacement" 3 · 17.3. Страницы PRV нет ни в одном.
- Lewisville: "prv replacement lewisville tx" у Lewisville 21 · 13.5, главной 21 · 17.7, contact, water lines, Frisco, gallery, The Colony; "pressure reducing valve lewisville tx" у Lewisville 7 · 29.3 и гайда по главному крану 5 · 17.0. Страницы PRV нет.
- "prv replacement denton tx": главная 10 · 19.6 и Carrollton 17 · 29.5 выше PRV 22 · 37.9 (Denton на сайте не называется).
- Страница PRV выше других: "plumbing pressure test near me" 30 · 2.6 (leak detection 12 · 8.2, Frisco 11 · 12.0, главная 5 · 39.6), "prv replacement cost" 1 · 7.0 (гайд по цене водонагревателя 1 · 12.0), "where is the prv located in a house" 1 · 11.0 (гайд PRV 2 · 41.5).
- Давление: самый крупный запрос сайта на эту тему "low water pressure plumber mckinney" (597 показов в `performance-16m/Queries.csv`) берут McKinney 580 · 33.8 и главная 309 · 61.8, страницы PRV нет. Гайд про падение давления берёт 67 запросов и 235 показов (его тема по карте).

Обратная проверка: запросы этой страницы, которые карта ключей отдаёт другой странице (16 месяцев, у страницы PRV; у хозяина):
- "frisco water line repair" 18 · 63.4; `/water-lines/` (ключ "water line repair") 2,597 · 20.1, Plano 71 · 3.4.
- "hydrostatic testing frisco" 1 · 43.0; leak detection (метод по CLAUDE.md), у неё запроса нет.
- "pressure relief valve outside house" 3 · 11.3; T&P valve у `/water-heater-repair-frisco-mckinney/`, у неё запроса нет (возможно, ищут PRV и путают названия).
- "low pressure", "water pressure down in my area", "water pressure low in my area", "water pressure starts strong then drops" (1 до 2 показов); тема гайда про падение давления, у него этих запросов нет.
- Семья "how to adjust" (18 показов, место 1.0): ключа в карте нет, ближе тема гайда PRV, гайд по ним не показывается.
- "shut-off valve replacement near me" 11 · 18.6: точного ключа нет, ближе гайд по главному крану, у него запроса нет.
- "licensed plumber" 1 · 6.0 (ключ гайда про мошенников; Plano 274 · 1.0, главная 127 · 1.1), "fpp plumbing" 2 · 2.0 (главная 1,863 · 1.5), "frisco" 1 · 4.0, "pipe breaks plano" 2 · 94.5.

Ключи страницы по карте ("prv replacement frisco", "pressure reducing valve replacement plano", "water pressure regulator replacement") в выгрузке не встречаются ни у одной страницы ни за 3, ни за 16 месяцев.

### 2.6. Услуга с каждым из десяти городов

Запросы про PRV и давление с названием города, все страницы сайта (показы · место):

| Город | 3 месяца | 16 месяцев | Какая страница берёт |
|---|---|---|---|
| Frisco | "good house pressure for frisco texas": PRV 2 · 13.0 | то же | только страница PRV |
| Plano | нет | "plano water pressure": Plano 2 · 55.0 | страница Plano |
| McKinney | "low water pressure plumber mckinney": McKinney 3 · 13.0, Frisco 1 · 21.0 | тот же запрос: McKinney 580 · 33.8, главная 309 · 61.8, water heater repair 8 · 63.5, Frisco 1 · 21.0; "mckinney water pressure": McKinney 13 · 56.9, slab leak 8 · 82.5 | страница McKinney, 919 показов всего |
| Lewisville | нет | "prv replacement lewisville tx" и "pressure reducing valve lewisville tx": Lewisville 28 · 17.4, главная 21 · 17.7, contact 11, water lines 8, гайд по главному крану 5, Frisco 3, gallery 3, The Colony 2 | страница Lewisville, 81 показ всего |
| Allen, Prosper, Celina, Little Elm, The Colony, Carrollton | нет | нет | ни одного запроса |

Страница PRV не показывается ни по одному запросу услуги с городом, кроме "good house pressure for frisco texas". Без города, но на страницах городов: Frisco 11 · 2.8 по "pressure reducing valve replacement" и 51 · 1.0 по "prv installation"; Plano 10 · 10.6 по "prv plumbing" и 2 · 1.0 по "pressure reducing valve (prv) installation".

### 2.7. Слова, которые на страницу не идут

| Что отложено | Запросы страницы (16 мес, показы) | Ещё на сайте |
|---|---|---|
| Места вне десяти городов | Denton ("prv replacement denton tx", 22), Jonestown (3), Spicewood (2), Collin County, округ (2) | Flower Mound (главная 3), Austin, Cypress, Kerrville (гайд про падение давления), индекс 75070 |
| Чужие компании | Water Works Plumbing (3) | Smith and Son Plumbing (water heater repair, 12) |
| Оценочные слова и цена | best (5), good (2), price (2), cost (1) | |
| Мусор и навигация | yes, images, where to buy, find part, what is this, where can i find it, nsd.prv, два запроса site: (9 запросов, 14 показов) | |
| Почтовый индекс | 75075 (Plano, 1) | |
| Темы других страниц | water line repair (18), hydrostatic testing (1), pipe breaks (2), pressure relief valve (3) | |
| Бренд | fpp plumbing (2) | |

Опечаток нет. Услуг, которых FPP не делает, в запросах страницы нет.

### 2.8. Проверка счёта

Итоги посчитаны дважды: модулем csv и вторым разбором той же строки файла вручную (страница до первой запятой, последние шесть полей с конца). Совпали запросы, клики, показы и место за оба периода (30 · 0 · 81 · 11.14 и 55 · 0 · 187 · 19.63), и совпали с `source/gsc/page-query-coverage.csv`. Страницы Google взяты из `source/gsc/performance-3m/Pages.csv` и `performance-16m/Pages.csv`. Старые адреса с 301 (например `/plumbing-guide/emergency-plumbing-repair-cost-guid-2026/`) в разборе других страниц посчитаны как их новая страница.
