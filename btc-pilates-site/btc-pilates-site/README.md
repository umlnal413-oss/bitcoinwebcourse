# BTC Pilates — сайт курса

Статический сайт: `index.html` + папка `assets/` с картинками. Сборка не нужна.

## Как выложить на GitHub Pages
1. Создайте аккаунт на github.com и нажмите **New repository** (например, `btc-pilates`), тип **Public**.
2. На странице репозитория нажмите **uploading an existing file** и перетащите **содержимое** этой папки: `index.html`, `.nojekyll`, папку `assets` (файл `README.md` по желанию). Нажмите **Commit changes**.
3. Откройте **Settings → Pages**. В **Source** выберите **Deploy from a branch**, ветку **main** и папку **/ (root)**, нажмите **Save**.
4. Через 1–2 минуты сайт будет по адресу `https://ВАШ-ЛОГИН.github.io/btc-pilates/`.

## Заметки
- Падающие монеты используют библиотеку three.js с cdnjs.cloudflare.com, нужен интернет.
- Курс BTC и график на странице статические (данные на 17.10.2026). Чтобы обновить, правьте число и массив точек `P` в `index.html`.
- Адрес кошелька и цены ищите в `index.html` по `bc1q` и `$20` / `$30`.
