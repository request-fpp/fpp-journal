# Проверка переезда: все адреса на новом сайте (2026-10-06)

Что проверялось: сборка как для живого сайта (site/dist-live), поднятая локально как Cloudflare Pages. Скрипт: `python3 tools/check_migration.py`. Полная таблица адресов: `exports/migration-check.csv`.

Сборка для живого сайта (без noindex): passed 30, failed checks 0, warnings 7; report in site/check-report-dist-live.md.

## Итог

- Адресов проверено: 414 (64 живых страницы, старые адреса из обхода, таблица переадресаций, старые адреса с показами в Search Console, проиндексированные и непроиндексированные адреса из её выгрузки, старый sitemap).
- Отвечают 200: 83. Отвечают одним 301 на страницу с 200: 318. Старые 404, которые и на живом сайте были 404 и ни в одну таблицу не входят: 13.
- Собранных страниц проверено по содержимому: 63 (noindex, canonical, title, H1, описание, tel-ссылки, JSON-LD). Внутренних адресов (ссылки, картинки, клипы) проверено: 392.
- Проблем: 0.

## Проблемы

- нет

## Файлы

- sitemap.xml: 63 addresses, every one a built page
- robots.txt: 8 groups, Sitemap line present
- www.fppplumbing.com: on the live site a 301 to fppplumbing.com; on Cloudflare the Redirect Rule of the switch day plan does the same (a local check cannot see a hostname)
- _headers: X-Robots-Tag only for the *.pages.dev hostnames

## Старые адреса, которые были 404 на живом сайте и остаются 404

Это адреса с показами в Search Console, у которых на живом сайте уже стоит 404 (опечатки, удалённые черновики). Они не в таблице переадресаций и на новом сайте тоже отвечают 404, как сейчас.

- /2024/12/02/hello-world/
- /blog/double-sink-clog-and-drain-line-repair/feed/
- /blog/outside-spigot-replacement-work/
- /blog/post-2/
- /blog/post/
- /plumber-celina-tex-water-heater-repair-replacement/
- /plumbing-guide/
- /plumbing-guide/automatic-water-shut-off-installation-cost/
- /plumbing-guide/emergency-repair-cost-guide-2026/
- /plumbing-guide/how-to-shut-main-water-valve-texas/
- /plumbing-guide/how-to-shut-off-main-valve-texas/
- /plumbing-guide/your-toilet-keeps-back-up
- /wp-content/plugins/litespeed-cache/guest.vary.php

## Title, H1 и описание против живого сайта

Каждое поле каждой страницы сравнено с обходом живого сайта: «as live» значит слово в слово, «point fix on record» значит точечная правка, записанная в журнале правок, «rewritten page» значит переписанная страница (главная, Frisco, Plano, emergency), текст которой сверен с её файлом.

- as live: 134
- point fix on record: 45
- rewritten page: 10

