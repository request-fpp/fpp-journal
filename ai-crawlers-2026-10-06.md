# Роботы ИИ и поисковиков на fppplumbing.com: первая картина (6 октября 2026, около 04:50)

Снято со страниц AI Crawl Control зоны в панели Cloudflare (Overview, Security, Metrics, Signals) и со страниц Security, через сутки после добавления зоны и через час после переключения домена. Это начало замеров: следующая картина через месяц.

## Что стоит в Cloudflare для роботов

- AI Crawl Control, Security: ни один из 33 роботов в списке не заблокирован (Amazonbot, Applebot, archive.org_bot, Baidu, BingBot, Bytespider, CCBot, ChatGPT-User, Claude-SearchBot, Claude-User, ClaudeBot, Cloudflare Crawler, DuckAssistBot, FacebookBot, Google-CloudVertexBot, Googlebot, GPTBot, Meta-ExternalAgent, Meta-ExternalFetcher, MistralAI-User, OAI-SearchBot, Perplexity-User, PerplexityBot, PetalBot, TikTok Spider и другие). Переключатели «Block Crawler» все выключены.
- Политики мастера добавления домена (Search, Agent, Training): все три «Allow (do not block)»; галочка «I monetize pages that serve ads» не стояла; Bot Preference Sync (дописывание robots.txt силами Cloudflare) выключен и остаётся выключенным, robots.txt отдаётся наш.
- Security, Settings: AI Labyrinth выключен, Bot fight mode выключен, Browser Integrity Check включён (значение по умолчанию; проверенных роботов он не трогает, при первом заблокированном роботе выключить), «Security Level» в новой панели не показывается отдельной настройкой. Email Address Obfuscation выключена (была включена по умолчанию).
- Security, Analytics за сутки: подозрительной активности 0, остановленных запросов 0.
- Signals: robots.txt домена отдаётся с кодом 200 (3 запроса за 7 дней), нарушений robots.txt нет; Content Signals в robots.txt «Not set» до выкладки этой ночи (с 04:50 строка стоит).

## Кто приходил за последние 24 часа (до 04:50)

| Робот | Компания | Запросов | Пропущено | Заблокировано |
|---|---|---|---|---|
| Claude-User | Anthropic | 5 | 5 | 0 |
| ChatGPT-User | OpenAI | 4 | 4 | 0 |
| Googlebot | Google | 4 | 4 | 0 |
| ClaudeBot | Anthropic | 2 | 2 | 0 |
| все остальные | | 0 | 0 | 0 |

Всего 15 запросов, все пропущены; 12 ответов 200, 2 ответа 301, 1 ответ 308. OpenAI забрал 162,62 КБ HTML, Anthropic 125 КБ, Google 12 КБ. Самые запрашиваемые адреса: /sitemap.xml (5), / (2), /water-heater-repair-frisco-mckinney/, /water-heaters/, /top-emergency-plumber-calls-frisco/, /llms.txt, /emergency-plumbing-services/ (по 1). Для сведения: чат читал сайт своим роботом (Claude-User) в 04:10, это часть из пяти запросов Anthropic.

## Что сделано этой ночью для роботов

- robots.txt: отдельные группы с Allow: / для OAI-SearchBot, ChatGPT-User, Claude-SearchBot, Claude-User, Perplexity-User, Applebot-Extended, Amazonbot, DuckAssistBot, meta-externalagent, CCBot (к прежним семи) и строка Content-Signal: search=yes, ai-input=yes, ai-train=yes в группе для всех.
- IndexNow: ключ в корне сайта, все 63 адреса отправлены; после каждой выкладки `python3 tools/indexnow.py --changed`.
- llms.txt: раздел Services в простых словах, список вопросов и ответов, строка о компании, профили в разделе Company.
