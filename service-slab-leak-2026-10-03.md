# Slab leak repair: живая страница и Search Console (3 октября 2026)

Страница `/slab-leak-repair-frisco-plano-mckinney/`. Справка перед переписыванием, текста страницы здесь нет. Источники: обход живого сайта source/crawl/pages/slab-leak-repair-frisco-plano-mckinney.json и source/crawl/html/ (на WordPress страница последний раз менялась 27 сентября 2026); новый сайт site/src/content/pages/slab-leak-repair-frisco-plano-mckinney.md и уже собранная копия site/dist/ (сборка 3 октября, 10:38, я ничего не собирал); одобренный текст source/FPP-Slab-Leak-Repair-Page-v3.docx; Search Console source/gsc/page-query-3m.csv, page-query-16m.csv, performance-*/Pages.csv, page-query-coverage.csv; карта ключей seo/keyword-map.md.

В ячейках Search Console числа идут так: показы · среднее место · клики. Тире в живом заголовке FAQ записано как [тире].

Длинные таблицы в docs/briefs/services/slab-leak/: gsc-queries-3m.md, gsc-queries-16m.md (все запросы), gsc-top30.md, gsc-headings.md, gsc-phrases.md, gsc-other-pages.md, gsc-not-this-page.md, gsc-set-aside.md, links-to-page.md.

## Коротко

1. Кликов нет: 0 за 3 и 0 за 16 месяцев, и в итогах Google со скрытыми запросами тоже 0. Показы 4,509 за 3 месяца (место 27.6) и 62,525 за 16 месяцев (место 47.1). За 13 месяцев до июля было 55,837 показов с известным запросом на месте 48.5, за последние 3 месяца 4,173 на месте 27.1.
2. Кормят страницу запросы «slab leak repair» с Plano, McKinney, Frisco. Title и H1 держат 74 и 83 запроса, 36,818 и 39,166 показов из 60,010 за 16 месяцев. Начало title «Slab Leak Repair in Plano, McKinney & Frisco» (это пример из правила 4) и начало H1 терять нельзя; точная фраза «slab leak repair in plano» стоит только в них.
3. Страница показывается по 87 запросам страницы leak detection (11,770 показов за 16 месяцев на месте 63.5, без кликов). Из них 21 запрос (7,794 показа, место 61.8; за 3 месяца 8 и 98) держат слова «Leak Detection» с городами в title и H1 («leak detection frisco», «mckinney leak detection»), остальные («water leak detection plano», «underground leak detection mckinney») ни один заголовок не держит.
4. Внутри сайта страницу обгоняют: по slab leak с Frisco за 3 месяца страница Frisco 1,997 показов на месте 8.1 против 979 на месте 19.9; «slab leak repair» без города берёт гайд по Plano (485 показов против 62); с Carrollton, Lewisville, Little Elm, The Colony, Allen почти всё у страниц городов.
5. Против правил на живой странице, на новом сайте уже исправлено: вопросы FAQ как H3, тире в заголовке FAQ, телефоны как H2 шаблона, FAQPage в разметке дважды, «Texas Master Plumber License M-44816» и «North Dallas communities» в разметке организации.
6. Против правил и на живой странице, и на новом сайте: три повторённых или старых абзаца (221 слово), старый абзац «We’ve seen it all ... through the roof», метод поиска утечки подробно (по правилу 9 тема leak detection), фраза о том, что slab leak во Frisco обычная работа (по Денису там около десяти за всё время).
7. Правило 8: вступление 3 абзаца, 15 разделов H2, список признаков, раздел «прямо сейчас» со ссылками на shut-off гайд и emergency, 6 вопросов FAQ, ссылка на главную «plumber near me», все десять городов в тексте: есть. Нет: ссылок в списке признаков, ссылки на water heaters, внешней ссылки на официальный источник, отзывов (на новом сайте два). На новом сайте девять признаков слиплись в один пункт списка.

## 1. Живая страница

### 1.1. Title, description, H1, H2, H3, объём

- Title: «Slab Leak Repair in Plano, McKinney & Frisco | Hidden Leak Detection»
- Description: «Slab leak under the foundation? We find the pinhole, tunnel under the slab, cut out the corroded copper, braze in new pipe and pressure test it.» (в Word v3 длиннее: «... We find the pinhole or the torn line, ... Plano, McKinney, Frisco.»; живая страница и новый сайт несут короткое)
- OG title: «Slab Leak Repair» (не равен title)
- H1: «Slab Leak Repair in Plano, McKinney and Frisco: Hidden Leak Detection and Tunneling Under the Foundation»

H2 по порядку: 1) What a Slab Leak Actually Is; 2) Signs of a Slab Leak in Plano, McKinney and Frisco Homes; 3) Why Copper Pinholes Under the Slab; 4) The Soil Moves, the Foundation Moves, the Pipe Tears; 5) Slab Leak Detection: Finding the Pinhole Under the Slab; 6) Slab Leak Repair by Tunneling Under the Foundation; 7) Slab Leak Repair Through the Floor; 8) When One Pinhole Is Not the Only One; 9) Slab Leaks and Foundation Damage; 10) What Slab Leak Repair Costs; 11) A Plano Slab Leak, Start to Finish; 12) Insurance, Documentation and Drying; 13) Slab Leak Repair Across Plano, McKinney, Frisco and the North Dallas Suburbs; 14) Water Coming Up Through the Floor Right Now?; 15) Slab Leak Repair [тире] Real Questions from Texas Homeowners (в v3 «Slab Leak Repair FAQ»); 16) «980-899-7997 469-998-8999», это H2 шаблона WordPress, он стоит на 63 из 64 страниц. H3: только шесть вопросов FAQ.

Объём: обход считает 4,015 слов (основной блок от H1 до кнопки «Request Service», без меню и подвала). Из них 221 слово повторено или осталось от старой версии (1.6), FAQ 557 слов, последний абзац 45, ещё 2 слова это кнопка «Request Service». Своего текста без повторов и без кнопки около 3,792 слов. Текст Word v3 от H1 до конца: 3,774 слова (мой подсчёт). Файл нового сайта: около 3,440 слов текста (от 3,426 до 3,445, смотря как считать подпись к фото и значки списка), 557 FAQ, 16 H1, всего около 4,010, то есть тот же текст, что живой.

### 1.2. FAQ

На живой странице каждый вопрос стоит тегом H3 (правило: жирный текст, не заголовок). Ответы слово в слово продублированы в FAQPage, и сам FAQPage выведен дважды.

1. How does water from a slab leak get into the house?
2. Why do copper pipes get pinholes under the slab?
3. Do you braze or solder the repair under the foundation?
4. Should I call a foundation company or a plumber first?
5. Is tunneling or cutting the slab better for a slab leak?
6. Does a slab leak repair need a permit in Plano, McKinney or Frisco?

Ни один вопрос не стоит слово в слово на других 63 страницах и в файлах нового сайта. Близкие: к вопросу 5 пост two leaks «Why do you repair slab leaks through a tunnel instead of cutting the floor?» и Lewisville «Can a slab leak be repaired without tearing up my floors?»; к разделу 9 гайд Plano «Can a slab leak cause foundation damage?»; про разрешения Frisco и Prosper; признаки slab leak спрашивают Carrollton и The Colony одним вопросом «What are the first signs of a slab leak?», а также McKinney, Plano, пост two leaks и гайд про счёт за воду. На новом сайте вопросы жирным текстом в раскрывающемся блоке (FAQList.astro), заголовок «Slab Leak Repair: Real Questions from Texas Homeowners».

### 1.3. Отзывы

На живой странице отзывов нет (ни в тексте, ни в HTML; в reviews/ledger.md страницы нет). На новом сайте за страницей два отзыва (reviews/site-reviews.json, site-ledger.md), оба автора стоят только здесь, тексты и ссылки на Google совпадают с reviews/all-reviews.csv слово в слово (ссылки в site-ledger.md):
- Steven Cossettini, Google, профиль Plano, 10 сентября 2026, Local Guide Level 3: копали и тоннелировали весь день, «The leak was likely due to some foundation movement», цена разумная, ещё промывка нагревателя.
- Saman Attar, Google, профиль Plano, 11 февраля 2026, Local Guide Level 3: Денис нашёл slab leak, тоннель на следующий день, работа до вечера. Его копия на Thumbtack (Saman A.) помечена взятой.

В отзыве Saman Attar есть время («the next day», «till 9:30pm») и слова «tunneling crew»: это слова клиента, по правилу отзыв не правится. В Word v3 для страницы были назначены Carolanne Roberto и Alex Gilles; их на новом сайте нет, и про слэб они не пишут.

### 1.4. Фото

Живая страница: логотип шаблона (два раза), печать BBB и одно фото в тексте: /wp-content/uploads/2025/05/slab-leak-detection-and-repair-frisco-706x1024.jpg, alt «Slab leak detection with professional equipment before repair in Frisco home». Это реальное фото с работы, номер 161 в архиве: Денис с детектором утечек на плиточном полу, Frisco (photos/index.csv, photos/captions.csv). Оно же og:image и primaryImageOfPage. Alt в v3 описывал брейзинг в туннеле в Plano, то есть другое фото.

Новый сайт: первым экраном фото 42 (перепаянное соединение, Carrollton), рисунок «под слэбом», клип со счётчиком (Plano) под разделом поиска, пара фото 163 (брейзинг в туннеле, Plano) и 45 под разделом туннеля, ниже старое фото 161 (файл лежит в site/public по старому адресу).

### 1.5. Ссылки

Из текста: главная с анкором «plumber near me» в последнем абзаце вступления («If you ended up here needing a plumber near me for something that has nothing to do with your foundation, the same people answer that call.»), правило 6 выполнено; все десять городов одним абзацем раздела «Slab Leak Repair Across ...» с анкорами «plumber in Plano» ... «plumber in Lewisville», правило 7 выполнено; услуги «PRV replacement», «leak detection», «water line repair», «emergency plumbing»; гайды «slab leak repair guide» (Plano) и «shut-off guide». Без ссылки, хотя тема рядом: /water-heaters/ (горячая линия, нагреватель, который включается чаще), /drain-services/ (тест канализации после подъёма фундамента), пост /blog/slab-leak-two-leaks-one-line-plano/. Внешние: только соцсети, tel:, mailto:, печать BBB, ссылка Google «Found us»; ссылки на официальный источник нет.

На страницу (links-to-page.md): меню и подвал со всех 62 открывающихся страниц, анкор «Slab Leak Repair» (63-й адрес, /blog/author/admin/, ведёт 301 на главную); из текста 29 ссылок: главная, все десять страниц городов (у Frisco «Slab leak detection and pipe reroutes», у Plano «Slab leak detection and reroutes», reroute на новом сайте снят), leak detection (две), water lines, PRV, emergency, пост two leaks, пять гайдов, top emergency calls.

### 1.6. Места против правил CLAUDE.md

По каждому месту сказано, что на новом сайте.

Услуги. Tankless, reroute, hydro jetting, газ: нет. Тесты до и после подъёма фундамента разрешены. Сушка «we bring in a water damage restoration company we work with regularly» не нарушение, но утверждённые слова «a restoration partner we trust». Новый сайт: так же.

Цены. Только $49 в будни в счёт работы и плата за вечер, выходные и праздники, названная по телефону. В разметке Service живой страницы, в узле Plumber внутри него, «priceRange: "$$"». Новый сайт: текст тот же, в разметке priceRange нет (dist).

Гарантия и время приезда. Сроков гарантии нет («it has to outlast the house» про шов). Обещаний приезда нет: «goes to the front of the schedule» и «usually a one to two day job» (длительность работы) приезд не обещают. Новый сайт: так же.

Другие города. Чужих нет. «on the Denton County side»: округ, сборка пометила и оставила (launch-changes.csv), на новом сайте стоит. В разметке организации живой страницы «surrounding North Dallas communities» (без suburbs); на новом сайте этой разметки нет.

Факт против записанного. «slab leaks in Plano, McKinney and Frisco are our regular work», «This is how most slab leaks in Plano, McKinney and Frisco get fixed» и в разделе городов «A plumber in Frisco rolls out of our Westridge Boulevard office for both the older neighborhoods near Preston Road and the post-tension slabs of the newer ones.» По CLAUDE.md (Денис, 2 октября 2026) slab leak во Frisco редкость, около десяти за всё время. Новый сайт: так же.

Граница с другими страницами (правило 9). Метод поиска, тема leak detection, описан подробно в разделе «Slab Leak Detection: Finding the Pinhole Under the Slab»: от «So the order never changes. First the meter, ...» до «A thermal camera confirms a hot line’s path.»; ссылка на leak detection стоит («The general method, and the tests you can run yourself tonight, are on our leak detection page.»). Линия, вмурованная в фундамент, передана water lines одним предложением со ссылкой, давление передано PRV одним предложением: правило выполнено. Новый сайт: так же.

Телефоны: в тексте и ответах FAQ нет, только H2 шаблона (на новом сайте его нет). Owner: нет. FAQ в заголовках: живая шесть H3, новый сайт жирный текст. Тире: одно, в H2 FAQ, на новом сайте двоеточие.

Повторы и старый текст (на новом сайте остались, launch-changes.csv: «duplicate block on the old page, kept as is (Denys decides after launch)»): абзац про гильзу дважды, второй раз старой версией с концом «That edge is one of the most common places we find the pinhole.» (82 слова); абзац «The leak itself begins as a weep. ...» дважды слово в слово (91 слово); старый абзац, которого нет в v3, «We’ve seen it all: copper pipes that rusted through, poorly soldered joints that finally gave out, or homes where soil movement snapped the line clean in half. These leaks can wash away soil from under your home, damage the foundation, and send your water bill through the roof.» (48 слов: шаблонные выражения, тройка, «rusted» про медь).

Шаблонность. Слов из запретного списка voice/denys-voice.md нет, кроме двух в старом абзаце; последний абзац собран перечислением («We find the pinhole, we reach it without wrecking your house, we braze the copper and we test it ...»).

Разметка живой страницы: Organization и Plumber с одним @id и разными описаниями, «Texas Master Plumber License M-44816» (формулировка снята), FAQPage дважды. Новый сайт (dist): один Plumber с лицензией «Responsible Master Plumber, License M-44816» в hasCredential, WebSite, WebPage, BreadcrumbList, Service, один FAQPage, noindex.

### 1.7. Полевое содержание, которое стоит сохранить

Текст v3 и есть стандарт глубины сайта (правило 3). Самое сильное:
- «a hole smaller than a pin in a pipe carrying sixty to ninety pounds of pressure, twenty four hours a day, into the ground under your kitchen»;
- гильза: «The sleeve holds the pipe rigid at that one point while the rest of the line lies free in the soil.»; рост утечки: «a pinhole that lost a few gallons a day in March can be dumping hundreds by August»;
- признаки: белая корка на бетоне и затирке, нагреватель включается чаще («a hot side leak is pulling heated water into the ground around the clock»), «Two of them together, in a house with copper under the slab, is a slab leak until a pressure test says otherwise.»;
- причины: медь на бетоне, в глине, у тросов post-tension; замер давления на каждом вызове («a brazed repair under a house running at 100 PSI will not be the last leak in that line»); «We have opened lines in houses less than ten years old and found all of it.»;
- порядок поиска с холодным входом нагревателя и проверка post-tension («You do not cut into a post-tension slab without locating the cables first»);
- туннель: «The dirt comes out in buckets.», чистая медь, type L, брейзинг, тест с открытым туннелем, засыпка слоями; вторая дыра на той же линии в Plano; фундамент: вымывание против набухания («A leak that ran all summer can do both.»), сантехник раньше фундаментной компании;
- цена: четыре вещи, от которых она зависит, «A price built on a marked leak is the one that holds.»; случай в Plano с камнем в траншее; что получает страховой оценщик;
- «прямо сейчас»: закрыть главный кран; этот абзац одобрен и для блока «What is happening right now?» (source/approved-text-edits.md).

Ждёт эту страницу (docs/pages-plan.md): история «Water coming out of the foundation» (Little Elm, 27 августа 2026) с клипом 165 (source/dictation/2026-10-02-slab-leak-water-from-foundation.md) и фразы Дениса про глину и пинхолы (source/dictation/2026-10-02-frisco-reserve-for-service-pages.md). Срок гарантии на slab leak записан в source/dictation/2026-10-01-warranty-and-care.md только для сведения, публиковать нельзя.

### 1.8. Новый сайт против живой страницы

- Текст живой страницы, не чистый v3: те же 15 разделов, повторы и старый абзац, короткое описание. Title, description, H1 те же.
- В tools/build_launch_content.py своих точечных правок у страницы нет; две строки с её адресом правят Frisco и Plano (снят reroute рядом со ссылкой сюда). Общие правила заменили тире в заголовке FAQ; пометки без правки: повтор блока и «Denton County».
- Вёрстка: FAQ жирным вместо H3, H2 с телефонами ушёл. Ошибка переноса: в .md список признаков начинается одним «-», дальше признаки идут через «•», и в собранной странице это один пункт списка с восемью «•».
- Добавлено: фото 42, рисунок «под слэбом», клип со счётчиком, фото 163 и 45, отзывы Steven Cossettini и Saman Attar, боковой блок «прямо сейчас», разметка одним графом.

## 2. Search Console

### 2.1. Итоги

Запросы, которые Google называет, и итог Google со скрытыми запросами:

| Период | Запросов | Клики | Показы | Среднее место (по показам) | Итог Google со скрытыми: клики · показы · место | Доля показов с известным запросом |
|---|---|---|---|---|---|---|
| 3 месяца (1 июля до 28 сентября 2026) | 90 | 0 | 4,173 | 27.1 | 0 · 4,509 · 27.6 | 93% |
| 16 месяцев (31 мая 2025 до 28 сентября 2026) | 355 | 0 | 60,010 | 47.0 | 0 · 62,525 · 47.09 | 96% |

Все 90 трёхмесячных запросов есть в шестнадцатимесячной выгрузке, поэтому 13 месяцев до июля считаются вычитанием: 55,837 показов на месте 48.5.

По группам запросов (город из десяти: в запросе одно из десяти названий; Park Cities: University Park или Highland Park; бренд: fpp):

| Группа | 3 мес: запросов · показы · место | 16 мес: запросов · показы · место |
|---|---|---|
| город из десяти | 46 · 2,364 · 29.0 | 274 · 56,785 · 47.5 |
| без города | 19 · 994 · 13.6 | 28 · 1,969 · 31.3 |
| другой город | 23 · 771 · 40.0 | 50 · 1,195 · 50.6 |
| Park Cities | нет | 1 · 14 · 66.2 |
| бренд | 2 · 44 · 2.7 | 2 · 47 · 6.2 |

По месту страницы: за 3 месяца на местах 1 до 10 стоят 5 запросов (174 показа), 10 до 20: 21 (1,539), 20 до 50: 52 (2,338), ниже 50: 12 (122). За 16 месяцев: 7 (285), 17 (785), 82 (33,497), 249 (25,443).

Чьи это запросы по seo/keyword-map.md и правилу 9 (полный список в gsc-not-this-page.md):

| Чей запрос | 3 мес: запросов · показы · место | 16 мес: запросов · показы · место |
|---|---|---|
| эта страница (с чужими городами) | 60 · 3,574 · 26.6 | 150 · 38,443 · 40.2 |
| leak detection (leak detection без slab, foundation leak detection и подобные) | 10 · 156 · 51.8 | 87 · 11,770 · 63.5 |
| спорные: «slab leak detection» (карта не записала никому, метод по правилу 9 у leak detection) | 9 · 297 · 18.8 | 23 · 2,743 · 35.1 |
| гайд slab leak Plano («slab leak plano», «slab leak detection plano») | 4 · 43 · 35.2 | 5 · 1,672 · 43.1 |
| пост two leaks («under slab leak plano») | 1 · 41 · 31.3 | 1 · 222 · 36.1 |
| water lines | нет | 9 · 937 · 79.5 |
| faucet page (fixture-installation-repair) | нет | 5 · 413 · 67.4 |
| PRV, drain services | нет | 2 · 12 |
| ничьи по карте («leak repair» с городом, «pipe break repair», «water leak repair») | 2 · 15 · 82.7 | 41 · 3,163 · 66.2 |
| не наши (крыша, бетонные плиты, сушка, spa, repipe, газ и другие) | 2 · 3 | 30 · 588 |
| бренд | 2 · 44 · 2.7 | 2 · 47 · 6.2 |

Запросы об этой услуге по всему сайту (в запросе slab или опечатки sab, slabe, slap вместе со словом leak, или foundation leak repair, leak under the foundation или floor, under slab, tunnel): за 3 месяца 14,010 показов, из них у этой страницы 3,955 (28%); за 16 месяцев 84,901, у этой страницы 43,081 (51%).

### 2.2. Топ 30 и клики

Полные таблицы: gsc-top30.md и gsc-queries-3m.md, gsc-queries-16m.md. Запросов с кликом нет ни в одном периоде, таблицы кликов поэтому нет. Топ 30 дают 3,638 показов из 4,173 за 3 месяца (87%) и 35,927 из 60,010 за 16 месяцев (60%).

Первые шесть за 3 месяца: «slab leak repair frisco» 342 · 16.8; «slab leak repair near me» 290 · 14.8; «slab leak repair frisco tx» 285 · 22.2; «slab leak repair plano» 245 · 30.4; «slab leak specialist near me» 241 · 11.7; «slab leak repair plano tx» 220 · 32.7.

Первые шесть за 16 месяцев: «slab leak repair plano» 3,080 · 34.8; «slab leak repair mckinney» 2,806 · 26.8; «slab leak repair frisco» 2,730 · 27.8; «slab leak repair plano tx» 2,050 · 50.5; «plano slab leak repair» 1,958 · 40.1; «mckinney slab leak repair» 1,933 · 27.1.

За 3 месяца лучше всего стоят запросы без города: «slab leak repair» 62 · 5.3, «under slab leak repair near me» 60 · 9.1, «slab leak specialist near me» 241 · 11.7 (слова specialist на странице нет), «slab leak detection near me» 148 · 12.9. С городом страница в топ 30 на местах от 15.9 до 48.3. В топ 30 за 3 месяца 7 запросов с чужими городами (Coppell, Lake City, Rockwall), в топ 30 за 16 месяцев 6 запросов «leak detection» с городом без slab и 3 с опечаткой «sab».

### 2.3. Что держат title, H1, каждый H2 и каждый вопрос FAQ

Заголовок держит запрос, когда все значимые слова запроса стоят в нём (in, tx, near, me не считаются, множественное число сводится к единственному по списку слов скрипта, slabs в этом списке нет, город считается, опечатки и оценочные слова не считаются, чужие города не берутся). Запрос за запросом: gsc-headings.md.

| Заголовок | Держит запросов: 3 мес (показы) | 16 мес (показы) | Фраза целиком, 16 мес | Только этот заголовок, 16 мес |
|---|---|---|---|---|
| title | 35 (2,080) | 74 (36,818) | 13 (6,295) | 0 (0) |
| H1 | 37 (2,123) | 83 (39,166) | 13 (6,295) | 9 (2,348) |
| H2: «Signs of a Slab Leak in Plano, McKinney and Frisco Homes» | 6 (42) | 15 (1,193) | 5 (595) | 0 (0) |
| H2: «Slab Leak Repair by Tunneling Under the Foundation» | 1 (62) | 2 (74) | 2 (74) | 0 (0) |
| H2: «Slab Leak Repair Through the Floor» | 1 (62) | 2 (74) | 2 (74) | 0 (0) |
| H2: «What Slab Leak Repair Costs» | 1 (62) | 2 (74) | 2 (74) | 0 (0) |
| H2: «A Plano Slab Leak, Start to Finish» | 3 (19) | 8 (749) | 1 (20) | 0 (0) |
| H2: «Slab Leak Repair Across Plano, McKinney, Frisco and the North Dallas Suburbs» | 21 (1,828) | 46 (26,385) | 2 (74) | 0 (0) |
| H2: «Slab Leak Repair [тире] Real Questions from Texas Homeowners» | 1 (62) | 2 (74) | 2 (74) | 0 (0) |
| вопрос FAQ (H3): «Does a slab leak repair need a permit in Plano, McKinney or Frisco?» | 21 (1,828) | 46 (26,385) | 2 (74) | 0 (0) |

Не держат ни одного запроса: description (в нём нет городов), H2 1, 3, 4, 5, 8, 9, 12, 14 (номера из 1.1) и вопросы FAQ 1 до 5.

Что нельзя потерять:
- Title и H1: «Slab Leak Repair» и три города. Фраза целиком у 13 запросов (6,295 показов за 16 месяцев), например «slab leak repair plano» (3,080 · 34.8), «slab leak repair plano tx» (2,050 · 50.5), «slab leak repair in plano» (468 · 33.4). «slab leak repair frisco» (2,730 · 27.8) и «slab leak repair mckinney» (2,806 · 26.8) держатся словами, не фразой: сразу за «Repair in» стоит Plano.
- Только H1 держит 9 запросов (2,348 показов за 16 месяцев) словами «Under the Foundation»: «foundation leak repair mckinney» (496 · 63.6), «foundation leak repair frisco» (343 · 46.0), «foundation leak repair plano» (189 · 56.0), «under slab leak plano» (222 · 36.1, ключ поста по карте) и «foundation leak detection frisco», «... plano», «... mckinney» (363, 360, 341 показ, это запросы страницы leak detection).
- H2 13 (города) и вопрос FAQ 6 (разрешение) держат одно и то же, 46 запросов и 26,385 показов за 16 месяцев: только в них «slab leak repair» стоит рядом с тремя городами.
- H2 2 (признаки) держит «slab leak plano» (251 · 37.7), «slab leaks frisco tx» и похожие (15 запросов, 1,193 показа); H2 11 (случай в Plano) 8 запросов (749) и точную фразу «plano slab leak»; H2 6, 7, 10, 15 держат «slab leak repair» (73 · 7.8 за 16 мес, 62 · 5.3 за 3 мес).
- «Hidden Leak Detection» в title и H1 держит с городами 21 запрос страницы leak detection (7,794 показа за 16 месяцев из 11,770 у всех 87 её запросов на этой странице; по gsc-headings.md): «leak detection frisco» (1,048 · 40.7), «mckinney leak detection» (1,040 · 68.5), «leak detection mckinney» (786 · 61.4), «leak detection plano» (679 · 65.8) и другие; кликов нет.
- Ни один заголовок не держит 222 запроса (19,649 показов за 16 месяцев; за 3 месяца 30 и 1,279): «slab leak repair little elm» (1,005 · 53.3), «slab leak repair near me» (855 · 42.0; 290 · 14.8 за 3 мес), «the colony slab leak repair» (531 · 50.3), «slab leak plumber mckinney» (503 · 22.4), «slab leak plumber frisco» (489 · 30.7), «slab leak repair lewisville» (432 · 77.9). Семь городов кроме трёх названы только в абзаце городов, слово plumber только в тексте.

### 2.4. Фраза целиком: топ 20 за каждый период и запросы с кликами

Таблица по 29 запросам (топ 20 за 16 месяцев и топ 20 за 3 месяца без повторов; запросов с кликами нет): gsc-phrases.md. Точная фраза: слово в слово и в том же порядке, без регистра и знаков. Мягко: те же слова подряд без in и tx, множественное число и опечатки не в счёт.

- Точная фраза стоит у 2: «slab leak repair in plano» (91 · 33.6 за 3 мес; 468 · 33.4 за 16) в title и H1; «slab leak repair» (62 · 5.3; 73 · 7.8) в title, H1, пяти H2, вопросе FAQ 6 и тексте двух разделов.
- Только мягко у 4: «slab leak repair plano» и «slab leak repair plano tx» (title и H1, потому что «in» не считается), «slab leak repair near me» (title, H1, H2, текст; «near me» на странице есть только в «plumber near me»), «slab leak detection near me» (H2 «Slab Leak Detection: ...»).
- Только с перестановкой у 2: «plano slab leak repair» (1,958 · 40.1), «plano tx sab leak repair» (921 · 60.1).
- Нигде у 21, из них 5 с чужим городом. Среди них самые большие: «slab leak repair mckinney» (2,806 · 26.8), «slab leak repair frisco» (2,730 · 27.8), «mckinney slab leak repair» (1,933), «slab leak repair frisco tx» (1,862), «slab leak repair mckinney tx» (1,861), «frisco slab leak repair» (1,575), «leak detection frisco» (1,048), «mckinney leak detection» (1,040), «slab leak repair little elm» (1,005), «slab leak detection plano» (905), «slab leak detection mckinney» (755), «slab leak specialist near me» (241 · 11.7 за 3 мес).

Из всех 355 запросов страницы (90 трёхмесячных входят в их число) точная фраза стоит только у шести: «slab leak repair in plano», «leak repair in plano» (title и H1), «slab leak repair», «leak repair», «fpp plumbing» (текст «We are FPP Plumbing», «call or text FPP Plumbing»), «plano slab leak» (H2 «A Plano Slab Leak, Start to Finish»). На них 715 показов за 16 месяцев и 201 за 3. Эти формулировки сохранить.

### 2.5. Другие страницы сайта на запросах этой услуги, и наоборот

Запрос «об этой услуге» как в 2.1. Старые адреса с 301 сложены с новыми. «Выше»: лучшее место по тому же запросу; «больше показов»: по тому же запросу; «только она»: эта страница по запросу не показывалась. Строка за строкой: gsc-other-pages.md. Страницы меньше чем с 20 показами (пост two leaks и ещё семь) не показаны.

| Страница | 3 мес: запросов · показы | выше этой страницы · больше показов · только она | 16 мес: запросов · показы | выше · больше показов · только она |
|---|---|---|---|---|
| /plumber-plano-tx/ | 30 · 3,867 | 18 · 4 · 12 (1,800) | 56 · 7,364 | 16 · 3 · 9 (75) |
| /plumber-frisco-tx/ | 22 · 2,800 | 8 · 5 · 7 (253) | 35 · 5,628 | 12 · 3 · 8 (46) |
| /plumber-carrollton-tx/ | 10 · 979 | 2 · 0 · 8 (905) | 12 · 5,501 | 6 · 4 · 6 (2,157) |
| /plumber-lewisville-tx/ | 12 · 861 | 3 · 1 · 9 (718) | 14 · 5,253 | 10 · 8 · 3 (317) |
| /plumber-little-elm-tx/ | 5 · 295 | 4 · 3 · 1 (27) | 6 · 3,924 | 5 · 4 · 1 (4) |
| / | 6 · 54 | 1 · 0 · 0 | 48 · 2,915 | 21 · 0 · 10 (289) |
| /plumber-the-colony-tx/ | 7 · 378 | 1 · 1 · 6 (303) | 8 · 2,655 | 5 · 5 · 3 (12) |
| /plumber-mckinney-tx/ | 5 · 75 | 2 · 1 · 2 (27) | 11 · 2,421 | 3 · 0 · 0 |
| /water-lines/ | нет |  | 12 · 1,817 | 1 · 0 · 0 |
| /plumbing-guide/slab-leak-repair-plano-tips-2026/ | 22 · 681 | 9 · 4 · 8 (107) | 46 · 1,689 | 22 · 2 · 16 (283) |
| /plumber-allen-tx/ | нет |  | 8 · 1,255 | 7 · 7 · 0 |
| /water-leak-detection-frisco-plano/ | 6 · 37 | 0 · 0 · 0 | 19 · 1,031 | 1 · 0 · 0 |
| /plumber-prosper-tx/ | 1 · 8 | 1 · 1 · 0 | 3 · 126 | 3 · 2 · 0 |
| /plumber-celina-tx/ | 1 · 1 | 1 · 0 · 0 | 4 · 117 | 2 · 1 · 0 |
| /emergency-plumbing-services/ | нет |  | 9 · 44 | 3 · 0 · 1 (1) |
| /contact/ | нет |  | 5 · 25 | 0 · 0 · 0 |

Что из этого следует, только факты:
- Frisco и Plano. Кнопки сайта в карточках Google Business Profile ведут на эти две страницы (seo/cannibalization-findings.md, Денис, 30 сентября 2026); по правилу проекта картой считается место 3 и выше по запросу без своего города. По slab leak таких строк (без своего города) за 3 месяца у Frisco 4 (23 показа), у Plano 9 (61); вместе со строками со своим городом на местах 1 до 3 стоят 5 строк Frisco (31 показ) и 12 строк Plano (97). Почти всё остальное (у Frisco 2,615 из 2,800 показов, у Plano 3,645 из 3,867) на местах ниже 3 и до 12: «slab leak repair frisco tx» у Frisco 1,860 · 7.4, у Plano 1,414 · 9.0, у этой страницы 285 · 22.2; «slab leak repair the colony tx» у Plano 1,709 · 6.1, все за последние 3 месяца. Выгрузка карточку и выдачу не разделяет.
- Гайд по Plano. «slab leak repair» без города: за 3 месяца у гайда 485 · 28.9, у этой страницы 62 · 5.3; за 16 месяцев 956 · 20.8 и единственный клик против 73 · 7.8 (то же в seo/cannibalization-findings.md, пункт 3). Гайд выше и по «slab leak repair plano» (66 · 22.9 против 3,080 · 34.8), «slab leak detection plano» (53 · 26.6 против 905 · 38.5).
- Главная: за 16 месяцев выше этой страницы по 21 запросу, например «slab leak plumber frisco» (449 · 17.8 против 489 · 30.7), «slab leak repair plano tx» (256 · 3.1 против 2,050 · 50.5); за 3 месяца только 54 показа.
- Страницы остальных городов забирают свои запросы (2.6), хотя по карте ключей Carrollton, Little Elm, McKinney и Plano не должны целиться в slab leak repair (колонка «Must not target»).

Наоборот (таблица «Чей запрос» в 2.1, полностью gsc-not-this-page.md): 87 запросов страницы leak detection (11,770 показов за 16 месяцев, место 63.5; за 3 месяца 10 и 156), ключи гайда («slab leak detection plano» 905 · 38.5, «slab leak plano» 251 · 37.7, всего 1,672), ключ поста «under slab leak plano» (222 · 36.1), water lines («water line repair mckinney» 412 · 76.1, всего 937), faucet page (413).

### 2.6. Услуга с каждым из десяти городов

Запросы услуги (как в 2.1) с названием города, место взвешено по показам. «Впереди за 3 мес»: страница с наибольшими показами. Лучшее место за 16 месяцев у страниц с 20+ показами: Frisco у страницы Plano (9.1, 1,435 показов), Plano у главной (6.1, 362), The Colony у главной (1.7, 45), McKinney и Little Elm у страницы Frisco (21.8 при 25 показах, 24.3 при 49), остальные у страниц своих городов.

| Город | Всего показов сайта: 3 мес · 16 мес | Эта страница, 3 мес: показы · место (запросов) | Эта страница, 16 мес | Больше всех показов, 16 мес | Впереди за 3 мес |
|---|---|---|---|---|---|
| Frisco | 4,422 · 19,923 | 979 · 19.9 (9) | 9,196 · 27.6 (18) | эта страница, 9,196 · 27.6 | /plumber-frisco-tx/, 1,997 · 8.1 |
| Plano | 1,153 · 18,506 | 874 · 32.7 (14) | 13,783 · 44.4 (38) | эта страница, 13,783 · 44.4 | эта страница, 874 · 32.7 |
| McKinney | 163 · 12,562 | 127 · 17.4 (6) | 10,124 · 32.0 (14) | эта страница, 10,124 · 32.0 | эта страница, 127 · 17.4 |
| Allen | 1 · 1,740 | нет | 458 · 61.0 (10) | /plumber-allen-tx/, 1,255 · 52.4 | /plumber-plano-tx/, 1 · 1.0 |
| Prosper | 16 · 253 | 7 · 13.0 (1) | 126 · 43.6 (4) | /plumber-prosper-tx/, 126 · 43.3 (поровну с этой страницей) | /plumber-prosper-tx/, 8 · 12.1 |
| Celina | 0 · 180 | нет | 68 · 37.4 (1) | /plumber-celina-tx/, 112 · 15.4 | запросов нет |
| Little Elm | 533 · 7,163 | 206 · 43.4 (4) | 3,049 · 53.6 (5) | /plumber-little-elm-tx/, 3,924 · 38.5 | /plumber-little-elm-tx/, 295 · 15.0 |
| The Colony | 2,379 · 6,368 | 2 · 30.5 (1) | 1,667 · 58.2 (6) | /plumber-the-colony-tx/, 2,654 · 25.1 | /plumber-plano-tx/, 1,767 · 5.9 |
| Carrollton | 905 · 5,771 | нет | 338 · 79.2 (4) | /plumber-carrollton-tx/, 5,426 · 45.6 | /plumber-carrollton-tx/, 905 · 16.1 |
| Lewisville | 723 · 6,238 | нет | 1,105 · 77.9 (8) | /plumber-lewisville-tx/, 5,103 · 37.8 | /plumber-lewisville-tx/, 718 · 10.5 |

Plano и McKinney за 16 месяцев в основном у этой страницы, но на местах 44.4 и 32.0. С Frisco за 3 месяца впереди страница Frisco (1,997 · 8.1 против 979 · 19.9). С Little Elm, The Colony, Carrollton, Lewisville, Allen, Prosper, Celina впереди страницы городов; с Carrollton и Lewisville эта страница за 3 месяца не показывалась, с The Colony у неё 2 показа против 1,767 · 5.9 у страницы Plano. Celina за 3 месяца не дала ни одного запроса, Allen один показ.

### 2.7. Слова, которые на страницу не идут

Полный список с примерами: gsc-set-aside.md. Показы по запросам этой страницы, в которых стоит слово (один запрос может попасть в две группы).

| Группа | Запросов | Показы 3 мес | Показы 16 мес | Главные слова (показы за 16 мес) |
|---|---|---|---|---|
| чужие города и места | 50 | 771 | 1,195 | Coppell 644 (и Copell с опечаткой 57), Rockwall 204, Lake City 156, Keller 29, Denton 20, Richardson 20, Quail Creek 12, Forney 10, ещё 15 мест по 1 до 7 показов (Fairview, Irving, Garland, Grapevine, Dallas, Hyde Park и другие) |
| опечатки и мусор | 15 | 221 | 4,229 | «sab» вместо slab 4,036 (11 запросов, например «mckinney tx sab leak repair» 1,140), «slabe» 134, «copell» 57, «slap» 1, «realslab.xyz» 1 |
| оценочные слова | 4 | 0 | 57 | doctor 27, professional 12, experts 12, reviews 6 |
| то, чего FPP не делает или что не про сантехнику | 25 | 4 | 250 | roof 145 (протечка крыши), watering 33 (полив фундамента), spa 21 и pool 4, crack 18 (трещины фундамента), overflow 10 (ущерб и сушка), repiping 10, gas 3, basement 3, no dig 2 |
| Park Cities (назвать можно, страницы нет) | 1 | 0 | 14 | «university park slab leak detection service» 14 |

Запросы про бетонные плиты без утечки («frisco slabs» 115, «plano slabs» 92, «slab foundation plano tx» 32) и про сушку и мокрый пол («mckinney wet floors» 50, «floor damage repair plano» 37, «frisco wet floor damage» 13) отнесены в gsc-not-this-page.md к не нашим. Слово cost (например «slab leak repair cost plano tx», 174 · 62.1 за 16 месяцев) не отложено: на странице есть раздел «What Slab Leak Repair Costs», цифр цены в нём нет, кроме $49.

### 2.8. Как считали и проверка

- Свой скрипт gsc_slab.py в scratchpad/services/slab-leak с правилами слов из docs/briefs/_shared/gsc_plano_lib.py (копия; оригинал не менялся, tools/gsc_page_table.py не запускался). Для страницы услуги десять городов свои, остальные места отложены; specialist и cost считаются обычными словами (cost стоит в H2 10).
- Текст живой страницы из обхода: title, description, H1, 15 H2 (H2 с телефонами шаблона не считался), вопросы и ответы FAQ, текст, последний абзац, alt.
- «Чей запрос» прочитан по seo/keyword-map.md, keyword-map.csv и правилу 9; где карта молчит, запрос назван ничьим или спорным.
- Второй счёт. Итоги страницы посчитаны модулем csv и разбором строк без модуля csv (внутри скрипта, с остановкой при расхождении), при проверке 3 октября посчитаны заново модулем csv: 3 месяца 90 запросов, 0 кликов, 4,173 показа, место 27.10; 16 месяцев 355 запросов, 0 кликов, 60,010 показов, место 47.02. Те же числа стоят в source/gsc/page-query-coverage.csv. Простая команда awk с запятой как разделителем за 16 месяцев даёт 59,488 показов: семь запросов содержат запятую внутри кавычек («slab leaks frisco, tx» и другие), поэтому для этих файлов awk без учёта кавычек не годится. Суммы по группам и по «чей запрос» сходятся с итогом. Сверены вручную: «slab leak repair frisco» (3 мес 342 · 16.75), «slab leak repair plano» (16 мес 3,080 · 34.8), «leak detection frisco» (16 мес 1,048 · 40.71), «fpp plumbing» (3 мес 43 · 2.0): совпало.
