# Видимость в ИИ-поисковиках: точка отсчёта (6 октября 2026)

Чтобы рост можно было мерить, а не обещать. Заполняется раз в месяц, первая проверка в начале ноября 2026.

## 1. Переходы на сайт из ИИ-сервисов (GA4, последние 90 дней)

Источники: chatgpt.com, perplexity.ai, gemini.google.com, copilot.microsoft.com, claude.ai.

Цифр пока нет: у сервисного аккаунта проекта (gsc-reader@fpp-site.iam.gserviceaccount.com) нет доступа к GA4, и в облачном проекте fpp-site не включён API аналитики. Что нужно от Дениса, два шага, около пяти минут:
1. https://console.cloud.google.com/apis/library/analyticsdata.googleapis.com?project=fpp-site → Enable (и то же для analyticsadmin.googleapis.com).
2. В GA4 (analytics.google.com), Admin, Property access management, Add users: адрес gsc-reader@fpp-site.iam.gserviceaccount.com с ролью Viewer.
После этого Claude Code снимает переходы по источникам скриптом и вписывает сюда таблицу за 90 дней до переезда (точка отсчёта) и дальше раз в месяц.

## 2. Роботы ИИ на сайте

Первая картина: docs/ai-crawlers-2026-10-06.md (15 запросов за сутки, все пропущены: Claude-User 5, ChatGPT-User 4, Googlebot 4, ClaudeBot 2). Следующий снимок через месяц со страницы AI Crawl Control, Metrics, окно 30 дней.

## 3. Bing

Страниц в индексе Bing: не известно, Bing Webmaster Tools ещё не подключён (нужен вход Дениса; шаги в docs/journal.md, запись 6 октября). После подключения сюда вписывается число страниц из отчёта Site Explorer и дата. IndexNow подключён 6 октября: все 63 адреса отправлены, ответ API 202.

## 4. Вопросы для ежемесячной проверки

Задать в ChatGPT (с поиском), Gemini, Perplexity и Claude; записать: назван ли FPP Plumbing, есть ли ссылка на fppplumbing.com, верны ли факты (телефон, адрес, $49, лицензия, города). Результаты вносят чат и Денис.

| # | Вопрос | ChatGPT | Gemini | Perplexity | Claude |
|---|---|---|---|---|---|
| 1 | emergency plumber in Frisco TX open now | | | | |
| 2 | best plumber in Plano TX | | | | |
| 3 | who repairs slab leaks in Plano TX | | | | |
| 4 | water leak detection Frisco TX | | | | |
| 5 | 24 hour plumber near McKinney TX | | | | |
| 6 | water heater leaking in the attic who to call in Frisco | | | | |
| 7 | plumber in Little Elm TX | | | | |
| 8 | main drain line backing up plumber Plano | | | | |
| 9 | PRV replacement Frisco TX | | | | |
| 10 | how much does an emergency plumber cost in Frisco TX | | | | |
| 11 | how to shut off the main water valve in a Texas house | | | | |
| 12 | FPP Plumbing reviews | | | | |

Запись в ячейке: «назван, ссылка, факты верны» или что не так. Первая проверка: после того как Bing и Google переиндексируют новый сайт (ориентир две недели после 6 октября).
