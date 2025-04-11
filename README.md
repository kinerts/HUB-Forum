# Сайт-визитка для Форума Кафедры Информационной Безопасности

Простой одностраничный сайт-визитка, созданный для продвижения студенческого форума в Telegram.

## Структура файлов

*   `index.html`: Основной файл с HTML-разметкой страницы.
*   `css/`: Папка со стилями.
    *   `style.css`: Файл CSS со всеми стилями сайта.
*   `README.md`: Этот файл.

## Как использовать

1.  **Клонируйте/Скачайте репозиторий.**
2.  **Откройте `index.html`** в вашем веб-браузере, чтобы посмотреть сайт локально.
3.  **Настройте под себя:**
    *   **Замените плейсхолдеры:**
        *   В `index.html` найдите и замените `[Название вашего колледжа/ВУЗа]` на реальное название.
        *   В `index.html` замените `#telegram-link` в кнопке "Присоединиться в Telegram" на вашу актуальную ссылку-приглашение в Telegram-группу/канал форума (например, `https://t.me/your_forum_group`).
        *   В `index.html` (в футере) и `css/style.css` (в логотипе, если хотите) замените "IT Security Forum" / "IT Hub Forum" на фактическое название вашего форума.
        *   В `index.html` (в контактах) проверьте и при необходимости измените email и ссылку на Telegram-бота.
    *   **(Опционально) Фоновое изображение:**
        *   В `css/style.css`, найдите секцию `.hero`.
        *   Замените `url('placeholder-bg.jpg')` на путь к вашему фоновому изображению (например, `url('../images/background.jpg')`, если вы создадите папку `images` в корне и положите туда файл).
        *   Если у вас нет подходящего изображения, можно раскомментировать строку с градиентом `/* background: linear-gradient(135deg, var(--secondary-color), #0a3d62); */` и закомментировать строку с `url(...)`.
    *   **(Опционально) Цветовая схема:**
        *   В `css/style.css`, в самом начале в блоке `:root`, вы можете легко изменить основные цвета сайта, редактируя значения CSS-переменных (`--primary-color`, `--secondary-color`, и т.д.).
4.  **Разместите сайт:** Загрузите файлы (`index.html`, папку `css`) на любой хостинг (например, GitHub Pages, Netlify, Vercel, или хостинг вашего колледжа).

## Зависимости

*   **Font Awesome:** Используется для иконок. Подключается через CDN в `<head>` файла `index.html`. 