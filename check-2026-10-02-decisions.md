# 2 октября 2026, поздний вечер: сводный блок решений Дениса по отчёту check-2026-10-02-1959

Сделано по сводному блоку (он заменил прежние блоки) и по трём замечаниям Дениса, пришедшим по ходу: «hits a 45» это 22.5, клипы нельзя открывать, на телефоне фото картриджа стояло под пунктом про измельчители. Тестовый сайт обновлён: https://fppplumbing-preview.pages.dev (за входом и с noindex). Коммит 341dd03, журнал и правила в отдельном коммите ниже.

## Коротко

- Шапка на всех 64 страницах: липкая, 56 px на телефоне и 72 px на компьютере, логотип, кнопка Call (на страницах Frisco и Plano звонит в свой офис, на остальных открывает окно с двумя офисами) и кнопка Menu. Меню со всеми услугами, городами, гайдами, офисами и часами стоит в HTML каждой страницы, скрипт 2,6 КБ без библиотек. Проверено на пяти ширинах: открытие и закрытие кнопкой, Esc, фоном, крестиком и ссылкой, фокус внутри панели и назад на кнопку, 35 ссылок, ни одной битой.
- Кнопки первого экрана до 1100 px стоят одна под другой по центру, не шире 360 px, зазор 12 px; от 1100 в ряд. Под картой главной ряд из десяти городов.
- Frisco, версия 2 (source/frisco-text-v2.md): строка автора под H1, лента доверия, отзывы перед списком вызовов, Quan Nguyen вместо Jan Shangle, Westridge Blvd, все правки D1 до D13 слово в слово, «Frisco» на странице 54 (было 94), backflow без слова о нашем тесте, 3,554 слова текста.
- Клипы только крутятся: ни кнопки, ни окна, ни полного видео, ни перемотки. Нажатие ничего не делает.
- Фото и клипы на сайте получили говорящие имена файлов: /img/sink-drain-ac-condensate-line-tied-in-frisco-201-720.webp, в srcset больше нет 1600 px, появился 1200.
- Проверки: 28 из 28, валидатор schema.org ноль ошибок и ноль предупреждений на обеих страницах, скрипт вёрстки чистый на шести ширинах, Lighthouse: главная телефон 99 и 100 (было 96 и 98), Frisco 99 и 100, компьютер 100 и 100 у обеих, LCP на телефоне в бюджете.
- Аудиты второго круга: таблица в конце.

## Что уже было сделано к приходу блока (отмечено, пропущено)

- B10: видео счётчика уже стояло в ячейке 3:4.
- B11, часть: строка лицензии в разметке уже была «Responsible Master Plumber, License M-44816»; сегодня добавлены identifier и recognizedBy как Organization по образцу из блока. Узла Person для Christopher Snell в проекте никогда не было; в узле Дениса номера нет.
- C1: отзыв Paul J. с «in 20 minutes» стоял и стоит на главной слово в слово, на том же месте; его никто не заменял.
- E: строка «Texas master plumber license M-44816 from the Texas State Board of Plumbing Examiners» стоит в блоке о компании («Local Plumber Near Me: A Licensed Plumbing Company With Two Offices»), во фразе «We work under…», не в личном блоке Дениса. По правилу блока не тронута. Снимок не нужен: место не менялось.
- F: ничего из этого раздела не делалось.

## 0. Правила, добавленные в CLAUDE.md

Все семь: лицензия и её формулировка (номер только в hasCredential организации и в строке подвала, никогда рядом с именем Дениса, в его блоке и в его узле); имена команды (Nick и Christopher только по имени, мельком, как сантехники на вызовах; в блоке Денис сказал «плотники», это описка голосового набора, в D3 они сантехники); backflow (меняем узел, тест и ремонт делает лицензированный тестировщик TCEQ, никогда не пишем, что тестируем, и не называем тестировщика); обещания времени только о наших словах, отзывы не трогаем; оплата (Zelle и чек без комиссии, карта с комиссией, размер не называем, отзывы с претензией к комиссии не берём); рейтинги ленты доверия сверять раз в месяц и перед переездом; навигация (шапка с Call и Menu, меню в HTML каждой страницы, кнопки первого экрана до 1100 px по центру). Старая запись о backflow в списке услуг исправлена. Правило о клипах переписано словами Дениса: никакого окна, кнопки и управления.

## A. Отклонения из отчёта

Все пять вписаны в design/layout-rules.md как часть правила, с датой принятия. Туда же вписана граница 1100 px и порядок на телефоне: фото стоит под своим абзацем, а следующие абзацы ниже (замечание Дениса про картридж под измельчителем). Разметка блока теперь: первый абзац, медиа, остальные абзацы; на компьютере остальные абзацы уходят в текстовую колонку под первый абзац, на телефоне идут после фото.

## B. Техника

**B1.** Две колонки с 1100 px, ниже один столбец. check_layout.py прогнан на 390, 768, 1024, 1100, 1280 и 1440 (шесть ширин, две страницы): ноль пересечений, ноль выходов за экран, боковой прокрутки нет. Снимки в exports/layout-shots.

**B2.** Подписи точек домика («Roof», «Kitchen» и остальные) и четыре «Call the office closest to you» переведены из H3 в p с теми же классами в генераторах (design/wow_pipe.py, design/build_mockups_f.py), вид не менялся. Первый заголовок после H1 на главной теперь H2 («What is happening right now?»). Lighthouse снял замечание heading-order: доступность главной 98 → 100.

**B3.** Постер первого экрана главной: картинка в `picture` с источником только для экранов от 821 px, без lazy, с fetchpriority high и preload в head (с тем же media). На телефоне постер не грузится вовсе (там видео и постер скрыты по дизайну), поэтому телефон ничего не потерял. Lighthouse компьютер: LCP 0,6 → 0,5 с. Телефон: 2,4 → 2,0 с (первый замер после сборки показал 4,2 с и Speed Index 22 с, но он шёл одновременно с другими проверками и съёмкой скриншотов; два повторных замера в одиночку дали 2,0 с и 99 баллов). Оценка tools/perf_budget.py: главная 1,36 с, Frisco 1,53 с при пределе 1,6.

**B4.** Из srcset всех фото на обеих страницах убран 1600 px, добавлен 1200 (tools/optimize_photos.py сделал 1200 для 31 фото, у фото уже 1200 и меньше шириной размера нет). sizes: фото в тексте 92vw до 1099 px и 240 px выше, пары 46vw и 180 px, плитки 46vw и 290 px, большая плитка 92vw и 600 px. Постер первого экрана не трогал.

**B5.** Имена файлов: `<slug>-<город>-<номер>-<ширина>.webp`, город только когда место съёмки его подтверждает (photos/slugs.csv из tools/photo_slugs.py, 52 имени написаны вручную, остальные из подписи). Архив в design/img остался под номерами, на сайт файлы копируются под новыми именами (design/build_mockups.py web_base и source_file). Обновлены srcset, штампы кеша (tools/stamp_assets.py теперь штампует и imagesrcset), подписи, thumbnailUrl и contentUrl у VideoObject, og:image обеих страниц, фото в блоке автора и в узле Person. Проверка «картинка существует» прошла на всех 64 страницах; на главной и Frisco ни одного файла с номером вместо имени (было 21 из 24 и 15 из 16).

**B6.** Координаты в отчёт не пишу: в проекте правило не записывать координаты снимков нигде (это дома клиентов, журнал открыт). Город определён по методу проекта, ближайший центр города из tools/photo_city_guess.py.

| Фото | Место по снимку | Дата съёмки | Решение |
|---|---|---|---|
| 53 | координат в файле нет | 2024-06-27 | на Frisco не используется; в пункте про корни стоит фото 96 (chain snake в уличном клинауте, Frisco по снимку) |
| 168 | Plano, 5,9 км от центра | 2026-03-20 | на Frisco не стоит, как и было |
| 172 | между Plano (9,0 км) и Frisco (10,1 км), ближе Plano | 2025-07-11 | на Frisco не стоит, ждёт страницу hose bib |
| 178 | The Colony 3,7 км, Frisco 5,6 км | 2024-01-17 | снято со страницы Frisco; подходящего подтверждённого фото мороза в архиве нет, раздел «What a Freeze Breaks» стоит без фото, фраза «One of those Frisco garages is in the photo» заменена на «In one of those garages the line to the spigot had burst…» |

Замечание: метод «ближайший центр» не знает границ городов. У западного края Frisco центр The Colony ближе центра Frisco, и по этому же методу фото 192, 193 и клипы 179, 122, 167, 175, 174 (все названы Денисом как работы во Frisco) попадают к The Colony или Little Elm. Они остались на странице, потому что работы назвал Денис, но у них в подписях, alt и именах файлов города нет. Если Денис скажет, что 178 тоже Frisco, фото вернётся одной строкой в конфигурации.

**B7.** og:image главной: фото 112, обрезка 1200 на 630 по лицу и струе (tools/optimize_photos.py, OG_FOCUS), og:image:width, height и alt стоят. Фургона на фото 112 нет и не было: это Денис у стены с бьющей водой; лицо в кадре целиком.

**B8.** Лента доверия под первым экраном Frisco: «Google 5.0 · Yelp 5.0 · BBB A+ · Thumbtack Top Pro · 4,500+ happy customers», текстом, по центру, перенос только целыми пунктами. Сверка вживую: профиль Google Frisco показывает 5.0 (26 отзывов). Yelp браузер заблокировал («You have been blocked»), обходить не стал; цифра 5.0 осталась как подтверждённая Денисом 1 октября, в архиве reviews/all-reviews.csv все 27 отзывов Yelp по пять звёзд.

**B9.** «Westridge Blvd» везде на Frisco: H1, meta, вступление, FAQ, блок офиса, закрытие, alt и подпись фото фургона (photos/captions-en.csv). «Boulevard» на странице больше не встречается.

**B10.** Видео счётчика 3:4, без изменений.

**B11.** hasCredential организации ровно по образцу из блока (credentialCategory, name, identifier, recognizedBy как Organization). Узел Person Дениса: name, jobTitle, url, image, worksFor, sameAs; номера лицензии в нём нет. Узла для Christopher Snell нет и не было. В разметке обеих страниц номер стоит только в hasCredential.

## C. Отзывы

**C1.** Paul J. (Yelp, «in 20 minutes») на главной как есть.

**C2.** Jan Shangle снята с Frisco (в тексте комиссия 2.99% как претензия). Замена: Quan Nguyen, Google, профиль Frisco, март 2026, пять звёзд, текст: «Appointment was scheduled easily and on time and reasonably priced. My busted outdoor spigot was inspected and replaced carefully and fast. Great company!» Сумм и претензий нет, города нет, Дениса по имени нет, автор больше нигде на сайте не стоит (reviews/site-ledger.md). Текст сверен с живым отзывом на Google Maps в этот же вечер, совпадает слово в слово; значка Local Guide у автора нет, подпись «★★★★★ · March 2026 · Google». Другие кандидаты из профиля Frisco: LXD Properties (114 слов, управляющий домами, «very fair with pricing»), Marina Sexton (44 слова, общий текст, «affordable»); David Harbour не подошёл (четыре звезды), Bo Wang (время приезда и имя Дениса), David Zhang и J L (о Денисе по имени), Nivas chowdary (называет Plano).

**C3.** Блок отзывов стоит сразу перед «The Plumbing Calls We Get Most in Frisco», блок офиса на своём месте в конце.

**C4.** reviews/site-ledger.md обновлён: 32 рецензента, повторов 0. В reviews/ledger-decisions.csv две записи (Jan Shangle заменена, Quan Nguyen поставлен), в reviews/proposed-placement.csv строка Frisco заменена.

## D. Текст Frisco

**D1.** Под H1: «By Denys Kavaler, Managing Partner and Licensed Plumber», имя ссылкой на /blog/author/admin/; у Person в схеме url тот же адрес; у WebPage author на @id Дениса. Даты на странице нет, dateModified в схеме.

**D2.** Было: «If the City of Frisco requires a permit for the job, we pull it and go through the inspection.» Стало: «When the job needs a permit, we file it with the City of Frisco ourselves and set up the inspection, so you never have to call the building department.»

**D3.** Блок офиса заканчивается: «Every job out of this office is done under our Responsible Master Plumber license, M-44816. Depending on who is on call that night, the plumber at your door may be Nick, Christopher or Denys.» Перед ними стоит фраза с ZIP кодами (D8).

**D4.** «hits a 45, and drops steeply» → «hits a 22.5-degree fitting, and drops steeply» (Денис поправил: 22.5, не 45).

**D5.** «The second most common call.» → «Another call we get all the time.»

**D6.** Было: «Yes. A lot of our Frisco work is in houses under ten years old: builder grade PRVs, cartridges, expansion tanks, and water heaters installed with the bare minimum.» Стало: «Yes. In the newest neighborhoods, where houses are under ten years old, a lot of our work is builder grade PRVs, cartridges, expansion tanks, and water heaters installed with the bare minimum.»

**D7.** Было одно предложение: «When a tank is due is in our guide on how long water heaters last, one Frisco job from start to finish is here: a water heater that burst and was replaced, and when the pan under the heater cannot be piped to a drain, the code calls for an automatic shut-off valve.» Стало три: «When a tank is due is in our guide on how long water heaters last. One Frisco job from start to finish is here: a water heater that burst and was replaced. And when the pan under the heater cannot be piped to a drain, the code calls for an automatic shut-off valve.» Анкоры те же.

**D8.** Word файл есть (source/FPP-Frisco-City-Page.docx), фразы взяты дословно, проверка по шесть слов против всех 64 страниц, старого сайта и конкурентов совпадений не дала:
- в блоке офиса (раздел о зоне работы): «All of Frisco, all four ZIP codes, 75033, 75034, 75035 and 75036.»
- в абзаце о плите (раздел «Newer Streets, Older Streets, Different Calls»): «The older Frisco neighborhoods near downtown and along Preston Road have copper under the slab, and twenty plus years of clay soil moving under a foundation is how a pinhole starts.»
Замечание: абзацем выше уже стоит «Closer to downtown and along Preston Road, where homes went up before 2005…», так что «downtown and Preston Road» теперь звучит дважды подряд. Это вопрос к Денису (в конце).

**D9.** Заголовок «Sprinkler Backflow Preventers in Frisco: Replace, Test, Report to the City» → «Backflow Preventers on Sprinkler Systems». Раздел до: два абзаца, второй кончался «This is a plumber's job. We pull the city permit, put in the new backflow, test that it works the right way, send the test report to the city and pass the city inspection.» Раздел после: первый абзац без «in Frisco» («We replace backflow preventers on sprinkler systems often. Most of them simply rust. …»), второй: «An old backflow with rusted valves also cannot be tested, and very often it has to be replaced after that. This is a plumber's job. We pull the city permit, put in the new backflow and pass the city inspection. Once the new assembly is in, it gets tested and the test report goes to the city.» Фраза из блока стоит один раз, тестировщик не назван, слова «so no report can go to the city» из первого предложения убраны, чтобы о тесте и отчёте говорила только разрешённая фраза.

**D10.** «Frisco» в тексте страницы: было 66 в копии (title, meta, H1, разделы, FAQ, закрытие) и 94 на странице, стало 34 в копии и 54 на странице (с подписями фото, крошками, кнопками и блоком офиса). Осталось в title (1), meta (2), H1 (1), вступлении (3), блоке офиса (3, с ZIP), фразах D2 и D8, трёх H2: «The Plumbing Calls We Get Most in Frisco», «Frisco Plumbing Questions», «Our Plumbing Office in Frisco, TX», в вопросах FAQ (у них своя уникальность на сайте) и в 13 подписях к фото, у которых место съёмки подтверждает город. Отзывы не тронуты. Изменённые заголовки: «Frisco Homes: Newer Streets…» → «Newer Streets, Older Streets, Different Calls»; «Water Pressure in Frisco Homes: What the Gauge Shows» → «Water Pressure: What the Gauge Shows»; «Where Newer Frisco Houses Leak First: The Valve Box» → «Where Newer Houses Leak First: The Valve Box»; «Permits and the City Inspection in Frisco» → «Permits and the City Inspection»; «The Nail in the Wall: The Frisco Leak Nobody Can Find» → «…The Leak Nobody Can Find»; «What a Freeze Breaks in Frisco Homes» → «What a Freeze Breaks»; «From the Job in Frisco» → «From the Job: Four Calls Out of This Office»; «Night Calls in Frisco: When It Is an Emergency» → «Night Calls: When It Is an Emergency»; «How a Call Works From the Frisco Office» → «How a Call Works From This Office»; «What Frisco Homeowners Say About FPP Plumbing» → «What Homeowners Say, Word for Word». Изменённые фразы (до → после): «Frisco is one of the newest areas…» → «It is one of the newest areas…»; «…what fills a Frisco week» → «…what fills our week here»; «This is the top call in Frisco right now, like everywhere else we work» → «This is the top call right now, here like everywhere else we work»; «In Frisco we replace them all the time» → «We replace them all the time»; «The clip here is a Frisco PRV leaking» → «The clip here is a PRV leaking»; «One we pulled in Frisco came out» → «One we pulled came out»; «In the newer Frisco homes the builder puts in» → «In the newer homes the builder puts in»; «at a lot of Frisco houses» → «at a lot of houses here»; «In the newer Frisco homes, when the main water line leaks» → «In the newer homes here, when…»; «That is the main trend we see in Frisco right now» → «…we see here right now»; «The Frisco inspectors are strict» → «The inspectors here are strict»; «In the newer Frisco homes we keep finding» → «In the newer homes we keep finding»; «One of those Frisco garages is in the photo: the line…» → «In one of those garages the line…»; «We replace backflow preventers on sprinkler systems in Frisco often» → «…systems often»; «A Frisco homeowner called about a water bill» → «A homeowner called about a water bill»; «A Frisco family's sewer backed up» → «A family's sewer backed up»; «A Frisco homeowner called about a drip» → «A homeowner called about a drip»; «Eleven at night in Frisco: a man» → «Eleven at night: a man»; «Another night, also in Frisco: a man» → «Another night: a man»; «A water heater in a Frisco attic burst» → «A water heater in an attic here burst»; FAQ про новые дома (D6); «If you need a plumber in Frisco today or tonight» → «If you need a plumber today or tonight». В подписях 192, 193, 166 и клипов 179, 122, 167, 175, 174 города нет (B6).

**D11.** «right now» оставлено, строки «Updated» нет.

**D12.** Список вызовов не переписывался. Пункты по порядку, первая фраза и слов:
1. A sink that won't drain, with the AC line tied in. «This is the top call right now, here like everywhere else we work.» 135 слов.
2. The pressure reducing valve. «The PRV sits in a box at the front of the house, between the meter and the house.» 152.
3. Water heaters, garage or attic. «Another call we get all the time.» 110.
4. Outside spigots. «The spigot on your wall is a frost free one.» 152.
5. Main sewer lines with roots. «The soil here moves.» 114.
6. Faucets, cartridges and tub spouts. «Hard water, same as the rest of Texas.» 103.
7. Garbage disposals. «In the newer homes the builder puts in the most basic unit there is: a third or half a horsepower, with a one year warranty from the manufacturer.» 85.

**D13.** На Frisco нет ответа FAQ про способы оплаты (аудит ссылался на ответ главной). Фразы добавлены в конец ответа «Who answers the Frisco line after hours?», единственного ответа Frisco, где речь о деньгах (после-часовой сбор): «…The emergency plumbing page says what to do while you wait. You can pay by Zelle or check at no extra charge. Card payments carry a processing fee, and we tell you about it up front.» FAQPage в схеме совпадает слово в слово. Ответы FAQ про оплату и цены на других страницах (фразу туда не копировал): главная «What payment methods do you accept?» (единственный про способы оплаты); про стоимость и сборы: /emergency-plumbing-services/ «Do I pay the after hours fee if the repair turns out to be small?», /plumber-allen-tx/ «What happens if the problem turns out smaller than expected?», /prv-replacement-frisco-plano/ «How much does PRV replacement cost in Frisco?».

## E. Главная: строка лицензии

Стоит в блоке о компании, в абзаце «We have four to five plumbers… We work under Texas master plumber license M-44816 from the Texas State Board of Plumbing Examiners». Это ряд данных компании, не блок Дениса. Не тронута. В личном блоке Дениса номера нет.

## H. Шапка и меню

Сделано в site/src/components/Header.astro, стили в site.css. Шапка липкая, высота фиксированная (56 и 72 px, сдвига вёрстки нет), логотип оригинальный на белом. На компьютере остались ссылки F2 (Services и Areas со списками, Guides, Blog, Contact), номера офисов и кнопка Request Service, к ним добавлены Call и Menu; до 1100 px номера и Request Service уходят в меню и в Call. Call: на Frisco и Plano tel: ссылка на свой офис; на остальных страницах окно с «Call Frisco office» и «Call Plano office». Номера сверены с подвалом: Frisco 469-998-8999, Plano 980-899-7997, совпадают. Меню: на телефоне на весь экран, на компьютере панель справа 420 px; закрывается крестиком, Esc, фоном и ссылкой; страница под ним не прокручивается; фокус ходит внутри и возвращается на кнопку; aria-expanded и aria-controls у кнопки, nav aria-label="Site menu". Содержимое: две кнопки звонка и Request service; Services в заданном порядке (emergency, slab leak, leak detection, sewer line, drain cleaning, water heaters, expansion tank and T&P valve, faucets and shower valves, hose bib, garbage disposal, water line, toilet, PRV); Cities в две колонки в заданном порядке; Guides (три замороженных и «All guides» на /plumbing-guides-tips/, хаб гайдов); About FPP и Reviews (на главную); Contact: оба офиса с адресами, телефонами, часами и почтой словами подвала. Заголовки групп в меню это p, не h2, чтобы не ломать порядок заголовков страницы. Ряд городов под картой главной: десять ссылок в том же порядке, текст раздела не менялся.

Проверка (три страницы: главная, Frisco, water-heaters; ширины 390, 768, 1100, 1280, 1440): шапка 56 px до 820 и 72 px выше, sticky; кнопки Call 71 на 44 и Menu 83 на 44 на телефоне, 76 на 44 и 89 на 44 на компьютере, обе внутри экрана; меню открывается (hidden снят, aria-expanded true, overflow страницы hidden, фокус на крестике), 35 ссылок, Tab 60 раз не выходит из панели, Esc закрывает и возвращает фокус на кнопку Menu, фон закрывает, крестик закрывает, ссылка закрывает; Call на Frisco это tel:+14699988999, на главной и water-heaters окно с двумя tel: ссылками. Все 35 ссылок меню ведут на существующие страницы. Боковой прокрутки нет. Снимки открытого меню: [главная 390](img/menu-home-390.jpg), [главная 1440](img/menu-home-1440.jpg), [Frisco 390](img/menu-frisco-390.jpg), [Frisco 1440](img/menu-frisco-1440.jpg).

## I. Кнопки первого экрана

До 1100 px кнопки одна под другой, по центру, 360 px (на 390 вся ширина колонки 340 до 358 px), зазор 12 px (верх 301 и 369 на главной: 56 px кнопки плюс 12), порядок звонок, потом форма; от 1100 в ряд по левому краю текста, как в F2. Снимки первого экрана: Frisco [390](img/first-frisco-390.jpg), [768](img/first-frisco-768.jpg), [1100](img/first-frisco-1100.jpg), [1440](img/first-frisco-1440.jpg); главная [390](img/first-home-390.jpg), [768](img/first-home-768.jpg), [1100](img/first-home-1100.jpg), [1440](img/first-home-1440.jpg).

## G. Проверки

- Слов на Frisco: 3,554 в тексте (title, meta, H1, разделы, FAQ, закрытие), 4,161 в main страницы.
- Валидатор schema.org: главная 0 ошибок, 0 предупреждений; Frisco 0 и 0. hasCredential у организации с identifier, FAQPage Frisco 7 вопросов слово в слово с D13.
- check_layout.py: чисто на шести ширинах, обе страницы. check_site.py: 28 из 28.
- Скорость на телефоне (tools/perf_budget.py): главная 1,36 с, Frisco 1,53 с, предел 1,6. Lighthouse до → после: главная телефон 96/98 → 99/100 (LCP 2,4 → 2,0 с), главная компьютер 100/98 → 100/100 (LCP 0,6 → 0,5 с), Frisco телефон 99/100 → 99/100 (LCP 2,1 → 2,1 с), Frisco компьютер 100/100 → 100/100 (производительность/доступность).
- Тире (U+2014, U+2013) во всём выводе обеих страниц, с меню: Frisco 0; главная 1, в дословном отзыве Adam Lis, оставлено по решению.
- «minute», «hour», «within» в тексте, каждое проверено: главная 15 совпадений, все про часы работы, «any hour», «24 hours a day», сбор «by the hour», «twenty minute drive» (описание района), «within a day» про автомат водонагревателя; одно «in 20 minutes» в отзыве Paul J.: отзыв, оставлено по решению. Frisco 12: «in a minute» и «takes minutes» про манометр, «drops a minute» про течь, «in minutes instead of a dig», «at any hour», «after hours», часы офиса. Обещаний времени от FPP нет.
- «Frisco» на странице Frisco: 54 (в main), цель 45 до 55.
- Backflow по всем 64 страницам, llms.txt, llms-full.txt и схеме: на Frisco только D9; в FAQ поста /blog/main-water-line-leak-under-sidewalk-plano-tx/ две правки точечными фиксами: «…has to be tested and inspected by the city before the job is closed out» → «…has to be tested, and the city inspects it before the job is closed out» (тестировщиком назывался город) и «Trench, bore, new line, new backflow, test, done» → «Trench, bore, new line, new backflow, done»; гайд /plumbing-guide/why-is-my-water-bill-so-high-frisco-tx/ «Isolate irrigation and backflow systems» это поиск утечки, не тест узла, оставлено; в схеме слово backflow только в имени старого файла фото этого поста; услуг или offers про backflow testing в схеме нет.
- Имена: Nick и Christopher стоят только в D3; ещё «Nick with FPP Plumbing showed up» внутри дословного отзыва на Frisco, отзыв не правится. В схеме имён нет. M-44816 рядом с именем Дениса нигде, кроме двух соседних предложений D3 в блоке офиса (текст Дениса, оставлено как дано).
- Клипы: 8, все без controls, muted, loop, playsinline, pointer-events none, кнопок и окон 0; клип в зоне видимости играет; нажатие ничего не открывает.
- llms-full.txt: тело Frisco отдавалось с HTML тегами блоков «текст плюс медиа», теперь текстом (подписи курсивом). Техническая мелочь, починена попутно.

## Аудиты второго круга

Два помощника, только чтение, по копиям собранных страниц (сборка 21:14). Методы те же, что в первом круге сегодня (superseo page-audit, семь частей по 10; claude-seo seo-page, пять областей из 100), поэтому цифры сравнимы.

**claude-seo seo-page**

| Область | Главная, 1 круг | Главная, сейчас | Frisco, 1 круг | Frisco, сейчас |
|---|---|---|---|---|
| On-page | 80 | 86 | 90 | 91 |
| Контент и E-E-A-T | 85 | 85 | 90 | 93 |
| Технические мета | 82 | 90 | 88 | 91 |
| Схема | 85 | 88 | 88 | 89 |
| Картинки | 76 | 85 | 76 | 86 |
| **Итого** | **82** | **87** | **86** | **90** |

Что подняло: подписи домика и панелей не H3 и первый заголовок после H1 это H2; og-картинка фото с alt; постер первого экрана сразу; hasCredential и url у Дениса, VideoObject у клипа счётчика; имена файлов по содержанию, без 1600; на Frisco подпись автора, лента доверия, ZIP коды и строка лицензии, backflow без заявлений о тесте. Что держит главную: закрытый текст (отзыв «20 minutes» по решению, расхождение со сбором за карту), главная и Frisco делят запросы Frisco.

По его находкам сделано сразу после аудита (коммит ниже): ссылки в ленте доверия на профили Google (Frisco), Yelp, BBB и Thumbtack; у WebPage главной появился reviewedBy на Дениса (его не было: главная получала узел Person по другому условию); подпись автора и Person.url переведены с /blog/author/admin/ на блок Дениса на главной (/#about), потому что по решению Дениса от 1 октября адрес автора остаётся переадресацией, он noindex и его нет в карте сайта; кнопка паузы видео первого экрана больше не ставит aria-pressed (программа чтения говорила «Play video, pressed»); alt и og:image:alt фургона уже с «Blvd» (аудит смотрел копию до этой правки); первая строка source/frisco-text-v2.md говорит «version 2».

Осталось, текст (решает Денис): отзыв Paul J.; сбор за карту: FAQ главной перечисляет карты без сбора, FAQ Frisco говорит о сборе, главная закрыта, формулировка для остальных страниц придёт отдельно; главная и Frisco делят запросы Frisco (наблюдение после переезда, раздел F); строка лицензии в блоке о компании другими словами (раздел E); «What Homeowners Say, Word for Word» и строка под ним дважды говорят «word for word»; фразы оплаты стоят в ответе про ночные звонки (моё решение, см. D13). Осталось, техника на потом: на iPhone с плотностью экрана 3 грузятся файлы 1200 px (380 до 499 КБ у фото 44 и 96), можно пережать 1200 сильнее; каждый город на главной связан трижды в блоке «Where We Work» (текст, карта, плашки по H5); нет twitter:title и twitter:description (подставляются og-теги); блок «What is happening right now?» на телефоне в конце страниц услуг и городов (находка первого круга, предложение в том отчёте); постер клипа ставит скрипт, робот без скриптов видит пустое видео (thumbnailUrl в разметке это закрывает); клипы и мигающая точка без кнопки остановки это WCAG 2.2.2, решение Дениса «ничего не нажимать» записано в CLAUDE.md.

**superseo page-audit**

| Часть | Главная, 1 окт | Главная, 1 круг | Главная, сейчас | Frisco, 1 круг | Frisco, сейчас |
|---|---|---|---|---|---|
| 1. Новая информация, которой нет у других | 5 | 7 | 7 | 9 | 9 |
| 2. Полнота темы | 5 | 7 | 7 | 8 | 9 |
| 3. E-E-A-T | 6 | 8 | 8 | 8 | 9 |
| 4. Структура и скорость ответа | 7 | 8 | 9 | 7 | 8 |
| 5. Техническое SEO на странице | 6 | 7 | 8 | 8 | 8 |
| 6. Вовлечение и вид в соцсетях | 6 | 7 | 8 | 8 | 8 |
| 7. Звонки и заявки | 8 | 8 | 9 | 7 | 9 |
| **Итого** | **43** | **52** | **56** | **55** | **60** |

Что подняло главную: ушли 11 заголовков H3 до первого H2, og-картинка стало фото, постер первого экрана сразу, лицензия как credential, липкая шапка с Call на любой ширине и окно с двумя офисами, кнопки первого экрана столбиком. Frisco: ZIP коды, лицензия и оплата в тексте, «22.5-degree fitting», подпись автора и лента рейтингов, отзывы вторым разделом, фраза с тремя ссылками разбита, Call звонит прямо во Frisco. Проверено и чисто: FAQ совпадает слово в слово (9 и 7), все 155 файлов фото и видео на месте, совпадения главной и Frisco только разрешённые (повтор фразы про пермит ушёл), Frisco ссылается на 13 услуг и на сайт города, 8 VideoObject на 8 клипов без кнопок, ни одно слово запроса из таблицы Search Console (1 068 запросов) не пропало из версии 2.

По его находкам сделано сразу: подпись автора и Person.url переведены на блок Дениса (страница автора остаётся переадресацией); ссылки в ленте доверия; у img постера первого экрана на телефоне (пустая заглушка) alt пустой, как у декоративной картинки; кнопка Call на страницах без своего офиса стала ссылкой на номер Frisco, которую скрипт перехватывает и открывает окно с двумя офисами (без скрипта набирается Frisco).

Осталось, текст (решает Денис): PRV на Frisco упоминается 20 раз, и вопрос FAQ «Why do PRVs fail so often in Frisco homes?» почти повторяет пункт списка; по карте ключей городская страница называет услугу один раз со ссылкой, страница PRV даёт клики и стоит на старом тексте, аудит видит риск, что Frisco заберёт «prv replacement frisco», и предлагает заменить вопрос другим, а страницу PRV переписать раньше; строка в блоке офиса «our Responsible Master Plumber license, M-44816» (твой текст D3) не дословно равна строке правила; сбор за карту в FAQ главной (главная закрыта); расхождение формулировки лицензии между блоком о компании и строкой правила (раздел E); умягчители воды одной фразой в ответе про жёсткую воду (Aquasana ставим изредка) и финансирование (есть у Berkeys, Baker и Roto-Rooter; есть ли у FPP, не выдумываю). Техника на потом: выпадающее меню F2 на компьютере и новое меню называют три услуги по-разному (Water leak detection и Leak detection, Water heater repair and replacement и Water heaters, Expansion tank replacement и Expansion tank and T&P valve) и в разном порядке, в новом меню нет Blog и Contact (Contact там это офисы); город трижды ссылкой в блоке «Where We Work»; фото 112 на главной дважды (плитка аварий и блок Дениса, по дизайну); блок «What to do» на телефоне в конце. В конфликтах с правилами аудит отметил кнопку «Pause video» на видео первого экрана: она оставлена, правило «ничего не нажимать» касается клипов в тексте.

## Замечания Дениса по ходу

1. «Здесь не 45, а 22.5»: исправлено (D4).
2. Клипы открывались и перематывались: окно, кнопка «Play video», полные видео и скрипт открытия убраны, клип только крутится; правило в CLAUDE.md переписано его словами; восемь полных видео остались в design/video, на сайт не копируются.
3. Фото картриджа под пунктом про измельчители на телефоне: правило вёрстки исправлено, медиа стоит под своим абзацем (проверено снимком блоков на 390, exports/layout-shots/blocks-plumber-frisco-tx-390.jpg).
4. Шапка на телефоне (после отчёта): логотип слева, справа одной группой Call, Request, Menu, с Request между ними; на компьютере тот же порядок после ссылок F2 и номеров. До 1100 px у Request короткая подпись, до 360 px у Call и Menu только значки. Проверено на 320, 390, 768, 1100 и 1440 на главной и Frisco: группа у правого края, боковой прокрутки нет. Снимок: [шапка Frisco 390](img/header-frisco-390.jpg). Коммит 6fc9d2b, правило навигации в CLAUDE.md уточнено.

## Вопросы к Денису

1. D8, глина: фраза из Word файла поставлена дословно, но абзацем выше уже сказано «Closer to downtown and along Preston Road…», и «downtown and Preston Road» звучит дважды подряд. Оставить дословно или взять запасную фразу из блока («The ground here is expansive clay…»)?
2. Фото 178 (лопнувшая линия к крану в гараже): по снимку ближе к центру The Colony, по твоему слову Frisco. По правилу B6 снято со страницы. Если работа была во Frisco, скажи, вернётся.
3. Есть ли у FPP финансирование (рассрочка через партнёра)? У Berkeys, Baker и Roto-Rooter оно есть на страницах. Если да, одна фраза на Frisco и на главной после её открытия; если нет, ничего не пишем.

## Файлы и коммиты

- Текст: source/frisco-text-v2.md. Конфигурация страницы: tools/export_page_text.py. Имена файлов: tools/photo_slugs.py, photos/slugs.csv. Шапка и меню: site/src/components/Header.astro, site/src/styles/site.css. Проверки: tools/check_layout.py (шесть ширин), tools/lighthouse_pages.py (новый), tools/site_reviews_ledger.py.
- Снимки: exports/layout-shots (вёрстка), exports/menu-shots (первый экран и меню), exports/lighthouse (отчёты до и после).
- Коммиты: 341dd03 (весь блок), 0cf92b4 (правки после аудитов: ссылки ленты доверия, подпись и Person на блок Дениса, reviewedBy главной, кнопка паузы), 9c51bd7 (пустой alt заглушки постера, кнопка Call как ссылка с запасным номером). Журнал и отчёт: следующий коммит.

## Таблица баллов

| Страница | superseo 1 окт | superseo 1 круг 2 окт | superseo сейчас | claude-seo 1 круг | claude-seo сейчас | Проверки сайта | Валидатор | Lighthouse телефон (производительность, доступность) | LCP телефон, оценка проекта |
|---|---|---|---|---|---|---|---|---|---|
| Главная | 43 из 70 | 52 | 56 | 82 из 100 | 87 | 28 из 28 | 0 и 0 | 99 и 100 (было 96 и 98) | 1,36 с |
| Frisco | нет (slab leak 49) | 55 | 60 | 86 | 90 | 28 из 28 | 0 и 0 | 99 и 100 | 1,53 с |
