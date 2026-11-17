# Сайт Егора Мусина — публикация на GitHub Pages

1. Создайте на github.com новый **публичный** репозиторий, например `egor-musin`.
2. «Add file → Upload files» → перетащите всё содержимое этой папки (вместе с папкой `img`) → «Commit changes».
3. Settings → Pages → Source: «Deploy from a branch», Branch: `main`, папка `/ (root)` → Save.
4. Через 1–2 минуты сайт откроется по адресу `https://ВАШ-ЛОГИН.github.io/egor-musin/`.

## Форма заявки
GitHub Pages не запускает PHP, поэтому заявки отправляются через бесплатный сервис Web3Forms:
1. Зайдите на https://web3forms.com, введите почту, куда должны приходить заявки, — придёт Access Key.
2. В `index.html` найдите `var WEB3FORMS_KEY = '';` и вставьте ключ между кавычками.
Пока ключа нет, форма предлагает написать в Telegram.

## После публикации
- Замените `https://example.com/` на адрес сайта в `index.html`, `robots.txt`, `sitemap.xml` (поиск-замена).
- Свой домен: Settings → Pages → Custom domain, у регистратора домена добавьте CNAME-запись на `ВАШ-ЛОГИН.github.io`. HTTPS GitHub включит сам («Enforce HTTPS»).
- Яндекс.Метрика: номер счётчика — в `var YM_ID = 0;`.
