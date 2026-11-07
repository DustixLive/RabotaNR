# RabotaNR — лендинг «Шабашка Новороссия»

Статический сайт для GitHub Pages.

## Страницы

- `index.html` — лендинг: описание, фичи, тарифы, кнопки ботов, каналы
- `privacy.html` — политика конфиденциальности
- `styles.css` — стили (адаптив mobile/desktop)

## GitHub Pages

1. Repo **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: `main`, folder: `/ (root)`
4. Сохраните. Сайт будет на `https://dustixlive.github.io/RabotaNR/`

(Имя пользователя в URL зависит от вашего GitHub username.)

## Ссылки, которые нужно подставить

В `index.html` сейчас:

| Элемент | Статус |
|--------|--------|
| Telegram-бот | `https://t.me/RabotaNR_bot` |
| MAX бот | заглушка `#` — вставьте URL |
| VK бот / сообщество | заглушка `#` |
| Каналы TG / MAX / VK | заглушки `#` |

## Локальный просмотр

Откройте `index.html` в браузере или:

```bash
python -m http.server 8080
```
