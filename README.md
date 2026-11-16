# ОГЭ Прокачка — GitHub Pages

Статическая сборка приложения. Ничего устанавливать и собирать не нужно.

## Публикация

1. Создайте публичный GitHub-репозиторий.
2. Добавьте `index.html` в корень репозитория и отправьте изменения в ветку `main`.
3. В настройках репозитория откройте **Settings → Pages** и выберите **GitHub Actions** как источник публикации.
4. После завершения workflow сайт будет доступен по адресу `https://<username>.github.io/<repository>/`.

Workflow `.github/workflows/pages.yml` публикует корень репозитория при каждом push в `main`.

## Хранение прогресса

Прогресс хранится в `localStorage` браузера пользователя под ключом `oge_prep_state_v2`.
Он не синхронизируется между устройствами и браузерами.

## Сторонние ресурсы

React 18, ReactDOM, Babel Standalone и KaTeX JavaScript загружаются с cdnjs.
Шрифты KaTeX встроены в HTML; Onest и IBM Plex Mono загружаются из Google Fonts.
