## Узел-API

Узел-API - это стандартная прослойка на Node JS, которая предназначена для выполнения следующих функций:

- Получение данных из БД
- Получение данных из API 1С
- Отправка данных по API 1С
- Компиляция данных
- Отправка данных на клиент
- Прием данных от клиента

Все данные, которые приходят на Узел-API, должны быть в формате JSON. Все данные, которые отправляются на клиент, должны быть в формате JSON. Все данные, которые отправляются на сервер 1С, должны быть в формате JSON.

Приложение реализовано на Node. Для маршрутизации используется Express, для работы с SQL - Sequelize, для работы с API 1С используются типовые возможности языка JS.

Всё ¯\\\_(ツ)\_/¯