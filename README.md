## Доступные скрипты

Для запуска приложения требуется запустить сначала сервер, затем клиент.

Установка зависимостей

### `yarn install`

Запуск сервера

### `yarn start:server`

Запуск клиента

### `yarn start:client`

Запуск сервера с помощью команды nodemon для разработки

### `yarn dev:server`

## Об функционале приложения

1.При запуске приложения появляется окно для создания комнаты.<br>2.В комнате есть ссылка для приглашения пользователя в данную комнату, которая перебрасывает на форму с введённой комнатой.<br>3.При перезагрузке страницы, юзер переподключается в комнату если в комнате есть еще пользователи, иначе комната удаляется и приложение перебрасывает на создание новой комнаты.

Для реализации чата используется библиотека socket.io.
