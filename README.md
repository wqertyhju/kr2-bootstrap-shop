# Bootstrap Shop

## Контрольная работа №2

Тема: «CSS-фреймворки: разработка интерфейса на Bootstrap или альтернативном CSS-фреймворке».

## Описание проекта

Проект представляет собой учебную версию сайта интернет-магазина, разработанную с использованием Bootstrap 5.

## Практическая работа 9

Выполнена главная страница на Bootstrap-сетке.

Реализовано:
- подключение Bootstrap через CDN;
- подключение css/custom.css;
- шапка страницы (navbar);
- hero-блок на сетке;
- блок преимуществ (row, col-md-4);
- сетка популярных товаров (row, col-12, col-md-6, col-lg-4);
- подвал страницы.

## Практическая работа 10

Выполнено:
- единая Bootstrap-навигация;
- страницы catalog.html, product.html, order.html;
- компоненты navbar, card, btn, badge, alert, modal, accordion;
- формы с form-control, form-select, input-group, form-check;
- обновлён css/custom.css.

## Используемые технологии

- HTML5;
- Bootstrap 5.3 (CDN);
- CSS;
- Git;
- GitHub.

## Структура проекта

kr2-bootstrap-shop/
├── index.html
├── catalog.html
├── product.html
├── order.html
├── css/
│   └── custom.css
├── images/
├── README.md
└── .gitignore

## Ссылка на опубликованный проект

GitHub Pages: https://wqertyhju.github.io/kr2-bootstrap-shop/


## Способ подключения Bootstrap

Bootstrap 5.3 подключён через CDN:
- CSS: `https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css`
- JS: `https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js`

Собственный файл `css/custom.css` подключён после Bootstrap и используется для точечных переопределений стилей.

## Реализованные Bootstrap-компоненты

- `navbar` — единая навигация на всех страницах, мобильное меню-гамбургер;
- `card` — карточки товаров в каталоге и на главной;
- `btn` — кнопки действия (`btn-primary`, `btn-outline-primary`, `btn-outline-secondary`);
- `badge` — метки товаров («Новинка», «Хит», «Скидка»);
- `alert` — информационные сообщения на страницах;
- `modal` — модальное окно быстрой заявки в каталоге;
- `form-control` — текстовые поля формы;
- `form-select` — выпадающий список темы заявки;
- `input-group` — поле телефона с префиксом `+7`;
- `form-check` — чекбокс согласия на обработку данных;
- `accordion` — блок «Дополнительно» на странице товара;
- `breadcrumb` — хлебные крошки на странице товара;
- `table` (`table-striped`, `table-bordered`, `table-responsive`) — таблица характеристик.

## Самостоятельные доработки

- добавлены мета-теги `description`, `canonical` и Open Graph (`og:*`) для SEO;
- реализовано модальное окно быстрой заявки на странице каталога;
- добавлен аккордеон с условиями доставки и гарантией на странице товара;
- добавлена таблица характеристик с адаптивной обёрткой `table-responsive`;
- использованы утилиты Bootstrap (`d-flex`, `gap-*`, `mt-*`, `mb-*`, `shadow-sm`, `h-100`);
- настроен `css/custom.css` для временного блока изображения и базовых переопределений.

## Как проверить проект

1. Открыть `index.html` — проверить navbar, hero-блок, преимущества, карточки товаров.
2. Открыть `catalog.html` — проверить карточки и работу кнопки «Заказать» (модальное окно).
3. Открыть `product.html` — проверить карточку товара, таблицу характеристик, accordion.
4. Открыть `order.html` — проверить форму (label, required, form-select, form-check, input-group).
5. Сузить окно браузера — проверить адаптивность сетки и мобильное меню.
6. Открыть DevTools → Console — убедиться в отсутствии ошибок.
## Автор

ФИО: Петренко Владимир Николаевич
Группа: ЭФБО-17-25

## Подготовка к сдаче КР №2

Проект проверен и готов к сдаче. Все обязательные страницы и Bootstrap-компоненты на месте.

