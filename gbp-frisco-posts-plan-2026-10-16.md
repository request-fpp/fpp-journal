# Посты для профиля Google во Frisco: план и первые восемь текстов

16 октября 2026. Ответ на вопрос Дениса: что писать, что лучше для Google, делить ли по районам. Сравнение с Plano: страница журнала gbp-posts-compare. Ни один пост не опубликован: каждый уходит только после «да».

## Что посты дают профилю, и что из этого следует

- Посты в профиле Google сами по себе место в карте почти не двигают. Что они делают: в выдаче карт Google подставляет под карточку строку «Their post mentions: ...», когда слова поста совпадают с запросом. Значит, первая строка поста это название услуги и город так, как их ищут: «Water heater replacement in Frisco, TX», «Sewer line repair in Frisco», «PRV replacement». Первые 100 знаков видны в карточке без раскрытия.
- Второе: свежие фото реальных работ с подписью. Профиль с живыми фото раз в неделю получает больше звонков, чем профиль с фургоном трёхлетней давности. Каждый пост это ещё и фото в профиле.
- Третье: пост живёт в карусели около полугода, потом уходит вниз. Поэтому важен ритм, а не разовая серия: два или три поста в неделю, как Plano делает с июля.
- Четвёртое: профиль Frisco ведёт на страницу /plumber-frisco-tx/, и темы постов должны совпадать с тем, о чём страница: давление и PRV, коробки с кранами в земле, водонагреватели на чердаке, гвозди в трубах, мороз, backflow, стоки с линией AC, унитазы, уличные краны.

## Делить ли по районам

Нет, не делить. Районы Frisco (Starwood, Richwoods, Phillips Creek Ranch, Panther Creek, Fields, The Grove) по отдельности почти никто не ищет: ищут «plumber Frisco TX» и услугу. Район в посте полезен как деталь правды, не как рубрика: «a house in Starwood» делает пост живым и даёт Google ещё одну привязку к месту. Правило: район пишем только когда Денис его назвал для этой работы; никогда не придумываем. Основная привязка каждого поста: «Frisco, TX» в первой строке и в последней, «City of Frisco permit and inspection» там, где они были.

## Как построен каждый пост

Одна настоящая работа во Frisco, по порядку: что было у хозяина, что показал тест или камера, что нашли, что сделали, одна деталь, которую знает только сантехник, один совет. Месяц и год работы, никогда «recently». 1,000 до 1,400 знаков. Без цен, без времени приезда, без телефонов, без тире, без восклицательных знаков и смайликов, без «North Dallas» без слова suburbs. Последняя строка: услуга и город, «Call FPP Plumbing.» Кнопка Call на большинстве, каждый третий с кнопкой Learn more на страницу сайта. Одно фото этой работы. Тексты проверены по правилам голоса Дениса (voice/denys-voice.md) и по списку запрещённых слов; инструмент gbp_post.py сам не пропустит телефон, тире и текст длиннее 1,500 знаков.

## Фото

Google берёт фото только по публичному адресу, JPG или PNG. Копии нужных фото без метаданных (по тем же веб-версиям, что на сайте, и по кадрам клипов) лежат на адресе журнала: https://fpp-journal.pages.dev/gbp/ (проект сайта не тронут). Google скачивает фото при создании поста и дальше держит свою копию.

## Порядок первых восьми

| | Пост | Фото | Кнопка | Страница |
|---|---|---|---|---|
| 1 | Водонагреватель на чердаке лопнул ночью | 173 (кадр клипа) | Call | |
| 2 | Expansion tank, полный воды, висит на PEX | 175 (кадр клипа) | Call | |
| 3 | 100 PSI на уличном кране, совет мерить раз в год | 228 | Learn more | /prv-replacement-frisco-plano/ |
| 4 | Главная линия разошлась у фундамента, корни, раскоп | 166 | Call | |
| 5 | Душ не выключается ночью, картридж | 174 (кадр клипа) | Call | |
| 6 | Кран менял не сантехник, два часа воды в стене гаража | 305 (кадр клипа) | Learn more | /hose-bib-repair-frisco-plano/ |
| 7 | Гвоздь в стене гаража, два-три капли в минуту год | 193 | Call | |
| 8 | Уличный кран не закрывается, и что сделать до первого мороза | 176 (кадр клипа) | Learn more | /plumbing-guide/how-to-shut-off-main-water-valve-texas/ |

Дальше по той же схеме: течь магистрали у счётчика (233), счётчик крутится при закрытых кранах (232), второй гвоздь строителя в PEX (224, 225), старый expansion tank на ржавой меди (285), губка от ёршика из линии унитаза (169), Roman tub faucet (три фото), 30 PSI на манометре (153), и в ноябре советы к праздникам и к морозу заново для Frisco. Плюс каждая новая работа во Frisco, которую Денис снимает: она идёт первой, свежее важнее архива.

## Тексты

Ниже восемь текстов как они уйдут в Google (английский). Файлы: ~/Projects/fpp-data/gbp/posts/2026-10-frisco-01 ... 08.

### 01. Water Heater Burst in a Frisco Attic at Night: What the Pan Did Not Save

![](https://fpp-journal.pages.dev/gbp/attic-water-heater-burst-at-night-frisco-173.jpg)

June 2025, a night call in Frisco. A water heater in the attic let go, and water ran from it in a stream, over the top of the tank and down through the ceiling. There was a drain pan under it. A pan is for a slow leak: a drip at a fitting, a weep at the bottom of the tank. When the tank itself opens up, the pan is full in a minute and the rest goes into the house. That is what happened here.

If it happens to you, the water comes first: the valve on the cold line above the heater, or the main shut-off valve if that one will not turn. Then the heater gets replaced. When the new one went in here, the vent pipe turned out to be set very low and the flue gases were backdrafting instead of going up and out. That went right with the new heater, because the City of Frisco inspector looks at the vent and the draft hood, at the T&P line and at the sediment trap on the gas before the job is closed.

A water heater in an attic past ten years deserves a look before summer: rust on the fittings, water in the pan, a rumble when it heats. A pan and a drain line are the minimum. Where the pan cannot be piped to a drain, the code asks for an automatic shut-off valve that closes the water by itself.

Water heater replacement in Frisco, TX, with the permit and the city inspection. Call FPP Plumbing.

*1375 characters, file 2026-10-frisco-01-attic-water-heater.txt, photo attic-water-heater-burst-at-night-frisco-173.jpg*

### 02. Expansion Tank Full of Water, Hanging on a PEX Line: A Frisco Water Heater Call

![](https://fpp-journal.pages.dev/gbp/expansion-tank-full-of-water-on-pex-line-frisco-175.jpg)

July 2026, Frisco. The call was a supply line dripping at the water heater. What we found next to it was the expansion tank, hanging on the PEX pipe and bending it down. Nobody had secured it. By code an expansion tank is supported or strapped; this one just hung there.

An expansion tank is a small steel tank with a rubber bladder inside, charged with air to about 5 PSI above your house water pressure. A house with a pressure reducing valve is a closed system: when the water heater heats the water, the water expands and has nowhere to go, so the tank takes that extra pressure on itself. New, it weighs almost nothing, and the PEX held it fine. The bladder lasts three to five years. When it fails, water gets in, and this 2 gallon tank had 2 gallons of water in it. The pipe carried that weight for a while, bent, and was on its way to splitting and flooding the attic.

We replaced the tank and secured it the way the code says. If your water heater has a PRV in front of it, there is an expansion tank near it. Past five years, have it checked when the heater gets looked at.

Expansion tank replacement in Frisco, TX. Call FPP Plumbing.

*1228 characters, file 2026-10-frisco-02-expansion-tank.txt, photo expansion-tank-full-of-water-on-pex-line-frisco-175.jpg*

### 03. 100 PSI on an Outside Spigot in Frisco: What a Gauge Tells You in One Minute

![](https://fpp-journal.pages.dev/gbp/100-psi-gauge-outside-spigot-frisco-228.jpg)

This gauge sits on a hose bib in Frisco, September 2025, and it reads 100 PSI. The city sends water at whatever pressure the main carries; the pressure reducing valve in the box at the front of your house is what brings it down for your pipes. Above 80 PSI the whole system is under stress. Faucet cartridges start to drip, toilet fill valves run, the supply lines under the sinks weep, and the water heater takes it hardest.

We put a gauge on the hose bib at a lot of Frisco houses. Over 80 is common, 90 is not rare, and a few have read 105. The PRV is there, it has just drifted high with age and hard water. The same valve can fail the other way: it scales up inside until almost nothing gets through and the gauge shows 30. Too high or too low, it is usually the same part.

A new PRV goes in with a new shut-off valve next to it, and we set it to about 70 PSI. A gauge from any hardware store screws onto the spigot. Check your pressure once a year: thirty seconds at the hose bib, and you know whether the valve in the ground is still doing its job.

Pressure reducing valve replacement in Frisco, TX. Call FPP Plumbing.

*1206 characters, file 2026-10-frisco-03-100-psi.txt, photo 100-psi-gauge-outside-spigot-frisco-228.jpg*

### 04. Main Sewer Line Separated at the Foundation in Frisco: Roots, a Camera, and a Dig

![](https://fpp-journal.pages.dev/gbp/dig-at-foundation-broken-sewer-line-frisco-166.jpg)

This one started in January, in the freeze. A Frisco family's sewer backed up with snow on the ground. Under the snow we could not find the cleanouts, so we pulled a toilet and ran the chain snake and the camera through the flange. The camera showed a line packed with roots, and the pipe at that spot was cracked, separated and shifted. The snake took the roots out, a pile of them, and the house drained again.

They kept our camera report, so they knew the pipe was broken and not just clogged. They set a budget and called us back in June for the repair. The separation was right where the line leaves the house: the pipe comes out of the slab, hits a 22.5 degree fitting and drops steeply, and that joint had opened. We dug five to seven feet down next to the foundation, replaced the separated section, put the line back together and ran water through it on camera to prove it drains. The photo is the dig. The video from the hole showed water running out of the old joint with roots wrapped around it.

Roots come back where a joint is open. Clearing buys time. A repaired joint stays closed.

Sewer line repair and camera inspection in Frisco, TX. Call FPP Plumbing.

*1257 characters, file 2026-10-frisco-04-sewer-line-roots.txt, photo dig-at-foundation-broken-sewer-line-frisco-166.jpg*

### 05. Shower Will Not Shut Off at Night in Frisco: A Cartridge, Not the Water Heater

![](https://fpp-journal.pages.dev/gbp/shower-handle-turns-water-keeps-running-frisco-174.jpg)

May 2025, a night call in Frisco. A man finished his shower, turned the handle to off, and the water kept running. The handle turned, the cartridge inside the valve turned with it, and nothing closed. Most showers have no small shut-off of their own that you can reach, so the only way to stop it is the main shut-off valve for the whole house. Then the house has no water, and that is why it is a night call and not a morning one.

Hard water does this. Calcium builds up inside the cartridge and breaks down the rubber, and one day the parts stick or the cartridge turns without sealing. The warning comes earlier: a handle that gets stiff, a drip that will not stop after you close it, the temperature wandering while you stand there. We pulled the broken cartridge, set a new one, and the shower shut off tight.

If the handle is getting hard to turn, that is the cartridge talking. Do not force it. A cartridge that snaps inside the valve body turns a cartridge swap into a valve replacement with the wall open.

Shower valve and faucet repair in Frisco, TX. Call FPP Plumbing.

*1162 characters, file 2026-10-frisco-05-shower-cartridge.txt, photo shower-handle-turns-water-keeps-running-frisco-174.jpg*

### 06. Outside Spigot Changed by a Handyman: Two Hours of Water Inside a Frisco Garage Wall

![](https://fpp-journal.pages.dev/gbp/spigot-changed-by-handyman-line-broken-in-wall-frisco-305.jpg)

October 2024, nine in the evening, and a family in Frisco has no water in the house. That day a handyman, recommended by a friend, had come to change the outside spigot. He did it for half our price. He unscrewed the old spigot, and the pipe inside the wall broke behind it. He screwed the new spigot on and left. Water ran inside the wall for about two hours. Half an hour in, it was standing on the garage floor. By the time the main was closed, the insulation and the whole outside wall were wet.

A spigot is screwed into an elbow inside the wall, and a plumber who has changed a thousand of them feels whether that elbow is fastened before he puts a wrench on it. That feel is the part a half price job skips.

The homeowner paid again: an emergency call, the wall opened, the pipes inside it rebuilt, about three times what the spigot would have cost with a plumber on it from the start, and after us the restoration company, so the wall did not grow mold. We are not criticizing anybody. But plumbing in Texas is licensed work, changing a spigot is plumbing, and a handyman's policy does not cover it.

Hose bib and outdoor faucet replacement in Frisco, TX. Call FPP Plumbing.

*1269 characters, file 2026-10-frisco-06-handyman-spigot.txt, photo spigot-changed-by-handyman-line-broken-in-wall-frisco-305.jpg*

### 07. Two or Three Drops a Minute for a Year: The Nail in a Frisco Garage Wall

![](https://fpp-journal.pages.dev/gbp/cut-pipe-with-nail-hole-frisco-193.jpg)

November 2024, Frisco. A closet had a baseboard going moldy and a wet floor, and for half a year nobody could tell where the water came from. No drip, no spray, no sound. The closet backs onto the garage, and the leak was in the garage wall: a shelf nail driven through the water line behind the drywall.

This is the hidden leak we keep finding in newer Frisco homes. A nail goes through the line, most often PEX, and plugs its own hole. No leak for a year or two. Then the nail rusts through, and the pipe starts to seep around it, two or three drops a minute. That is the hardest kind of leak to find, because there is almost no water.

We found it from the garage side, opened the drywall, cut out the piece with the hole and put in new pipe. The photo is the piece we cut out, with the hole the nail left.

A wet baseboard, a musty closet, a water bill that crept up: water leak detection in Frisco, TX. Call FPP Plumbing.

*1001 characters, file 2026-10-frisco-07-nail-in-garage-wall.txt, photo cut-pipe-with-nail-hole-frisco-193.jpg*

### 08. Outside Spigot Will Not Shut Off in Frisco, and What to Do With It Before the First Freeze

![](https://fpp-journal.pages.dev/gbp/outside-spigot-will-not-shut-off-frisco-176.jpg)

May 2026, Frisco. The handle on this outside spigot turns all the way and the water keeps coming. Nothing burst, it just will not shut off. That is one of the two ways a spigot ends. The other is the crack inside the wall after a freeze, which shows nothing until the first time you turn the hose on in spring, and then the water runs into the wall instead of out of it.

The spigot on your wall is a frost free one. Put in right, it should not freeze. It still needs a cover before the first freeze, and that is the whole list for November: covers on the outside spigots, the faucets inside the house left dripping on the cold nights, and the main shut-off valve found before you need it. After the freeze, run every outside spigot once with the hose on and watch the wall.

A spigot that will not shut off, or one that runs inside the wall, gets replaced with a new frost free unit on new copper.

Hose bib repair in Frisco, TX. Call FPP Plumbing.

*1041 characters, file 2026-10-frisco-08-spigot-before-freeze.txt, photo outside-spigot-will-not-shut-off-frisco-176.jpg*
