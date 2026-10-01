# Предпросмотр нового сайта на Cloudflare: как выложить и как закрыть паролем

Предпросмотр живёт по адресу https://fppplumbing-preview.pages.dev. Домен fppplumbing.com и DNS не трогаем. На каждой странице стоит запрет для поисковиков (noindex), а вход будет только по вашей почте.

## Шаг 1. Вход в Cloudflare (уже сделан)

Вы уже вошли командой `npx --yes wrangler@latest login` (папка проекта, локальный Node). Повторять не нужно. Если когда-нибудь вход слетит: откройте Терминал, вставьте две строки и подтвердите вход в браузере.

```
cd ~/Projects/fppplumbing-site && export PATH="$PWD/.tools/node/bin:$PATH"
npx --yes wrangler@latest login
```

## Шаг 2. Выкладку делаю я

Я собираю сайт, прогоняю проверки и выкладываю одной командой из папки site:

```
npx wrangler pages deploy dist --project-name fppplumbing-preview --branch main
```

Выкладку делаю только после того, как включён шаг 3 (вход по почте).

## Шаг 3. Закрыть предпросмотр входом по почте (Cloudflare Access)

Это делаете вы в браузере, один раз, около пяти минут.

1. Откройте https://dash.cloudflare.com и войдите.
2. Слева выберите **Zero Trust**. Если Cloudflare попросит выбрать тариф, выберите **Free** (бесплатный) и придумайте имя команды, например `fpp`.
3. В Zero Trust слева: **Access** → **Applications** → кнопка **Add an application**.
4. Выберите **Self-hosted**.
5. **Application name**: `FPP preview`.
6. **Session Duration**: оставьте 24 hours.
7. **Application domain**: в поле Subdomain ничего, в поле Domain впишите `fppplumbing-preview.pages.dev`. Нажмите **Add domain** (или "+ Add public hostname") и добавьте вторую строку: `*.fppplumbing-preview.pages.dev` (это закроет и промежуточные версии).
8. Нажмите **Next**.
9. Политика (Policy): **Policy name** `Denys only`, **Action** `Allow`.
10. В разделе **Configure rules** → **Include** → выберите **Emails** и впишите вашу почту, с которой вы входите в Cloudflare.
11. Нажмите **Next**, на странице настроек входа оставьте **One-time PIN** (код на почту), нажмите **Add application** (или **Save**).
12. Проверка: откройте https://fppplumbing-preview.pages.dev в окне инкогнито. Должна появиться страница Cloudflare с полем для почты. Введите почту, придёт код, введите код, откроется сайт.

Напишите мне, когда шаг 3 готов, и я выложу сайт.

## Что важно

- Поисковики сайт не увидят: на каждой странице стоит noindex, и Cloudflare отдаёт тот же запрет в заголовке.
- Живой сайт fppplumbing.com на WordPress работает как раньше. Переключение домена будет отдельным шагом, только когда вы сами скажете.
