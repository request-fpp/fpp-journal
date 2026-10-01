# Проверка индексации в Search Console (1 октября 2026)

Проверено через Search Console API (URL Inspection, только чтение) 81 адрес: все 64 страницы старого сайта и все старые адреса, у которых были показы за 16 месяцев. Полные данные: source/gsc/inspection-2026-10-01.csv.

## Адреса с ошибками: Денис прав, все сделано
| Старый адрес | Что видит Google | Правильный адрес | Что видит Google |
|---|---|---|---|
| /plumbing-guide/emergency-plumbing-repair-cost-guid-2026/ | Page with redirect (последний обход 2026-08-06), Google сам выбрал правильный адрес | /plumbing-guide/emergency-plumbing-repair-cost-guide-2026/ | Submitted and indexed (последний обход 2026-09-25) |
| /plumber-the-celina-tx/ | Redirect error (последний обход 2026-07-27) | /plumber-celina-tx/ | Submitted and indexed (последний обход 2026-08-30) |
| /news и /news/ | Google их не знает (выпали из индекса) | /blog/ | Submitted and indexed (последний обход 2026-09-04) |

Про /plumber-the-celina-tx/: «Redirect error» это отметка с обхода 27 июля. Сейчас адрес отдает одну чистую переадресацию 301 на /plumber-celina-tx/ (проверено сегодня с http, https, www и без слеша), а правильная страница в индексе. Делать ничего не нужно, Google снимет отметку при следующем обходе. В новой сборке эта переадресация сохранена.

Остальные старые адреса (/blog/post/, hello-world, адреса гайдов с опечатками и т.п.) Google больше не знает: из индекса выпали.

## Все 64 страницы
- В индексе: 55.
- «Crawled, currently not indexed» (Google обошел, но в индекс не взял): 8: /blog/clogged-main-drain-line-daycare-plano/, /blog/clogged-shower-drain-little-elm-case/, /blog/clogged-toilet-auger-fix-blog/, /blog/outside-spigot-replacement-plumber-in-frisco/, /blog/plumber-frisco-water-heater-replacement/, /blog/shower-valve-bathtub-faucet-replacement-in-frisco-from-fpp-plumbing/, /blog/toilet-replacement-with-new-shutoff-valve-and-wax-ring/, /plumbing-guide/water-heater-making-noise-tips-2026/. Это короткие посты и один гайд; при переезде переходят как есть, потом их углубляем по диктовке Дениса.
- /blog/author/admin/ Google не знает (на старом сайте это переадресация на главную).
- www.fppplumbing.com: переадресация на главный адрес, все правильно.
