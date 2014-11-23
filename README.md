prettyforms-laravel-app
=======================

Пример веб-приложения на Laravel, PrettyForms и Backbone.js
К статье на Хабрахабре [Динамичное веб-приложение на основе Laravel, PrettyForms и Backbone.js](http://habrahabr.ru/post/243925/)

####Установка

- Склонировать проект на локальную машину, войти в папку проекта
```bash
git clone git@github.com:believer-ufa/prettyforms-laravel-app.git
cd prettyforms-laravel-app/
```
- Установить все зависимости приложения через [Composer](https://getcomposer.org/)
```bash
composer install
```
- Настроить подключение к MySQL базе данных в файле **app/config/database.php**
- Создать базу данных приложения, выполнив SQL-запрос в MySQL
```sql
```
- Запустить скрипт генерации таблиц БД
```bash
php artisan migrate
```
- Запустить веб-сервер
```bash
php artisan serve
```
- Открыть страницу в браузере: [http://localhost:8000/](http://localhost:8000/)
