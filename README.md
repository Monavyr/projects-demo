# Projects / Проекты

[Русский](#русский) · [English](#english)

**Демо / Live demo:** [Открыть страницу / Open the page](https://monavyr.github.io/projects-demo/)

## Русский

**Учебная страница для управления проектами.** Можно искать проекты, создавать и редактировать их, а также удалять после подтверждения. Используются только вымышленные примеры.


### Возможности

- Поиск по названию и описанию с обновлением списка при вводе.
- Создание и редактирование проекта через форму с обязательными полями.
- Удаление с подтверждением и возможностью отмены.
- Сообщения для пустого списка и поиска без результатов.
- Сохранение изменений после обновления страницы с помощью `localStorage`.
- Адаптивная раскладка: на узком экране поиск и кнопка создания расположены друг под другом.

### Технологии и запуск

HTML, CSS и JavaScript без фреймворков и внешних зависимостей. Для публикации через GitHub Pages файл `index.html` находится в корне репозитория.

Для локального запуска выполните в папке проекта:

```bash
python3 -m http.server 8000
```

Откройте `http://localhost:8000`.

### Проверки и исправления

- Проверены поиск по названию и описанию, отсутствие результатов, создание, редактирование, отмена и подтверждение удаления.
- Проверены обязательные поля, пустой список и сохранение данных после повторного открытия страницы.
- Поиск и кнопка разнесены по отдельным строкам в мобильной раскладке, чтобы не перекрывать друг друга.
- Сообщение об ошибке сохранения выведено в открытую форму или окно подтверждения.
- Название и описание выводятся как текст, поэтому введённый HTML не исполняется.

### Ограничения

Данные хранятся только в браузере на текущем устройстве. Они не синхронизируются между устройствами и могут исчезнуть при очистке данных сайта. Серверной базы данных и учётных записей нет. Чтобы вернуть исходные примеры, удалите ключ `study-projects-v1` в локальном хранилище сайта.

Интерфейс страницы сейчас на русском языке; этот README представлен на русском и английском.

## English

**An educational page for managing projects.** You can search, create, and edit projects, or delete them after confirmation. All initial examples are fictional.


### Features

- Live search across project names and descriptions.
- Create and edit projects with required form fields.
- Delete projects with a confirmation step and a cancel option.
- Clear empty states for an empty list and searches with no matches.
- Keep changes after a page refresh using `localStorage`.
- Responsive layout: the search field and create button stack on narrow screens.

### Tech stack and local setup

HTML, CSS, and JavaScript with no framework or external dependencies. For GitHub Pages branch deployment, `index.html` is placed in the repository root.

Run this command in the project directory:

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000`.

### Checks and fixes

- Checked search by name and description, no-match results, creation, editing, cancellation, and confirmed deletion.
- Checked required fields, the empty list, and persistence after reopening the page.
- Stacked search and create controls on narrow screens to prevent overlap.
- Moved save errors into the open form or confirmation dialog so they remain visible.
- Rendered project names and descriptions as text so entered HTML cannot execute.

### Limitations

Data stays in the browser on the current device. It does not sync across devices and may be lost if site data is cleared. There is no server database or user account. To restore the initial examples, remove the `study-projects-v1` key from the site's local storage.

The page interface is currently in Russian; this README is available in Russian and English.
