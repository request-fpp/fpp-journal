# DNS домена fppplumbing.com до переезда

Снято 6 октября 2026 около 02:00 по Далласу прямо с nameserver HOSTiQ (dns1.hostiq.ua), сырые ответы в `exports/dns/fppplumbing.com-2026-10-06.txt`, список для копирования в `exports/dns/records-expected.json`. Ничего не менялось: это снимок.

Слова: запись A говорит, на каком сервере сайт; CNAME это псевдоним на другое имя; MX говорит, какой сервер принимает почту; TXT это текстовые записи (SPF и DKIM защищают почту от подделки, DMARC говорит получателям, что делать с подделкой, google-site-verification подтверждает Search Console). TTL это сколько секунд интернет помнит ответ. «Без прокси» значит, что Cloudflare только отвечает на запрос DNS и не пропускает трафик через себя (в панели это серое облако).

## Кто что держит

- Nameservers: dns1.hostiq.ua и dns2.hostiq.ua (HOSTiQ). Меняются в панели HOSTiQ, в день переезда, только Денисом.
- Регистратор домена: Registrar.eu (Hosting Concepts B.V.), через HOSTiQ. Домен создан 24 декабря 2024, продлевается 24 декабря 2026. Статус clientTransferProhibited: домен заперт от переноса, это нормально.
- Сайт: A запись ведёт на 162.247.155.224, общий сервер HOSTiQ (LiteSpeed, WordPress). www отвечает 301 на fppplumbing.com; http отвечает 301 на https; сайт отдаёт HSTS на год с includeSubDomains.
- Почта request@fppplumbing.com: Google Workspace (MX smtp.google.com). К хостингу HOSTiQ она не привязана: переезд сайта почту не трогает, если записи MX, SPF, DKIM и DMARC скопированы один к одному.
- Записей AAAA (IPv6) и CAA нет. Подстановочной записи (*) нет. Имён autodiscover, autoconfig, google._domainkey нет.

## Все записи, как они отвечают сейчас

| Имя | Тип | Значение | TTL | Для чего и как копировать |
|---|---|---|---|---|
| fppplumbing.com | A | `162.247.155.224` | 1200 | the WordPress site at HOSTiQ; DNS only until the last step of the switch day, then the Pages domain |
| fppplumbing.com | MX | `1 smtp.google.com` | 1200 | mail of request@ at Google Workspace; never proxied |
| fppplumbing.com | TXT | `v=spf1 +a +mx +ip4:162.247.152.67 ~all` | 1200 | SPF, as it is (the ip4 is the HOSTiQ outgoing mail server) |
| fppplumbing.com | TXT | `google-site-verification=ZRf3Q97paZA9xWU2KhBEFiawW-wE5Hh03JgHOgoiCvc` | 1200 | Search Console verification, as it is |
| fppplumbing.com | TXT | `google-site-verification=IPE6G2RnGA1na1_wxBUA7iV1IPz5oC9vT9FHsE7HvGM` | 1200 | Search Console verification, as it is |
| www.fppplumbing.com | CNAME | `fppplumbing.com` | 1200 | www; DNS only until the last step, then the Pages domain |
| mail.fppplumbing.com | CNAME | `fppplumbing.com` | 1200 | cPanel name, kept for the 30 days of rollback |
| webmail.fppplumbing.com | A | `162.247.155.224` | 1200 | cPanel service name at HOSTiQ, kept for the 30 days of rollback |
| ftp.fppplumbing.com | A | `162.247.155.224` | 1200 | cPanel service name at HOSTiQ, kept for the 30 days of rollback |
| cpanel.fppplumbing.com | A | `162.247.155.224` | 1200 | cPanel service name at HOSTiQ, kept for the 30 days of rollback |
| webdisk.fppplumbing.com | A | `162.247.155.224` | 1200 | cPanel service name at HOSTiQ, kept for the 30 days of rollback |
| cpcalendars.fppplumbing.com | A | `162.247.155.224` | 1200 | cPanel service name at HOSTiQ, kept for the 30 days of rollback |
| cpcontacts.fppplumbing.com | A | `162.247.155.224` | 1200 | cPanel service name at HOSTiQ, kept for the 30 days of rollback |
| _dmarc.fppplumbing.com | TXT | `v=DMARC1; p=none;` | 1200 | DMARC, as it is |
| default._domainkey.fppplumbing.com | TXT | `v=DKIM1; k=rsa; p=MIIB… (ключ целиком в exports/dns/records-expected.json)` | 1200 | DKIM key of the HOSTiQ server (cPanel selector default), as it is |

Плюс NS (dns1.hostiq.ua, dns2.hostiq.ua) и SOA, которые в Cloudflare будут свои и не копируются. Одно отличие в копии (замечание проверки 6 октября): mail.fppplumbing.com у HOSTiQ это CNAME на сам домен, а после переезда домен ведёт на новый сайт; чтобы имя cPanel по-прежнему вело на HOSTiQ все 30 дней отката, в зоне Cloudflare оно стоит записью A 162.247.155.224 без прокси, как webmail и cpanel (exports/dns/records-expected.json). Почте это не нужно (MX у Google), это только для входа в панель HOSTiQ по этому имени.

## Две вещи про почту, которые видны из записей (не для переезда, на потом)

1. SPF `v=spf1 +a +mx +ip4:162.247.152.67 ~all` разрешает слать письма от имени домена серверу HOSTiQ (так шлёт форма WordPress) и серверу из A записи, но не Google. Письма, которые Денис шлёт из Gmail с адреса request@, проходят SPF как «мягкий отказ» (~all). Чтобы это починить, в SPF добавляется `include:_spf.google.com`. Это не делается при переезде (правило «один к одному»), это отдельное решение Дениса после.
2. DKIM для Google Workspace не настроен (нет записи google._domainkey). Настраивается в Google Admin, Gmail, Authenticate email; тоже после переезда и отдельно.

Оба пункта не мешают переезду и не меняют его шаги.

## Что нужно от Дениса, чтобы снимок был полным

Ничего обязательного. dig отвечает только на имена, которые у него спрашивают: все стандартные имена cPanel и почты проверены, ключ DKIM найден, Search Console найдена. Единственное, чего dig не увидит, это записи с нестандартным именем, если такие есть. Если Денис хочет полной уверенности: в панели HOSTiQ (cPanel) открыть Zone Editor и прислать скриншот списка записей домена; доступ в саму панель не нужен. Если не пришлёт, список выше считается полным: сайт, обход 64 страниц и письма ссылаются только на эти имена.

## Зона в Cloudflare: один шаг Дениса в панели (пункт 11 списка)

Вход Claude Code в Cloudflare (wrangler, под request@fppplumbing.com) умеет читать зоны и выкладывать сайт, но не умеет создавать зону и писать в неё записи. В аккаунте сейчас зон нет. Поэтому один раз в панели, около пяти минут, когда Денис скажет, что готовим переезд дальше:

1. Открыть https://dash.cloudflare.com, войти (тот же вход, что для Access).
2. Кнопка **Add a domain** (или **Onboard a domain**). Вписать `fppplumbing.com`. Оставить «Quick scan for DNS records», нажать **Continue**.
3. Тариф: **Free**. **Continue**.
4. Cloudflare покажет найденные записи. Ничего не править и не удалять, просто **Continue**: сверку и недостающие записи сделает Claude Code по таблице выше.
5. Страница «Change your nameservers»: Cloudflare покажет два своих адреса вида `xxx.ns.cloudflare.com`. **Ничего не менять у HOSTiQ.** Эти два адреса пригодятся в день переезда. Нажать **Continue** или просто закрыть страницу. Зона останется в состоянии Pending, это правильно.
6. Написать Claude Code: «зона добавлена».

Дальше Claude Code читает зону (`python3 tools/switch_day.py status`) и сравнивает с таблицей. Недостающие записи добавляет `zsh tools/switch_day.sh records` с токеном `fpp switch` из скрытого окна на Mac (docs/switch-day-plan.md, шаг 0: пять прав, только зона fppplumbing.com), все без прокси, ничего не удаляя. Токен нигде не записывается; после переезда Денис его удаляет в той же панели.

В зоне до самого последнего шага переезда: A fppplumbing.com и CNAME www ведут на HOSTiQ без прокси, как сейчас. Так после смены nameservers сайт продолжает работать с HOSTiQ, а переключение на новый сайт становится одним движением (и откат тоже), см. docs/switch-day-plan.md.
