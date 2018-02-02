# Websky-темы
## Сетап для сотворения тем websky

Название темы нужно изменить в *package.json* в объекте *devConfig* поле theme (тема websky стоит дефолтно).

Файлы SASS добавляем в папку с название темы в *src/sass* (например: *src/sass/our_theme*). Основной файл компиляции custom.scss. Готовый стиль будет скомпилирован в папке *build/css/название_темы*.

Файлы Javascript добавляем в папку с название темы в *src/js* (например: *src/js/our_theme*). Основной файл компиляции custom.js. Готовый скрипт будет скомпилирован в папке *build/js/название_темы*.

Запуск осуществляется командой **gulp**. Browser sync открывает тестовую площадку с websky. Адрес площадки можно поменять в *devConfig* в поле *host*
