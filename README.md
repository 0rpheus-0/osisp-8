# Лабораторная работа №8

Сервер и клиент. Погулять По ФС сервера при помощи клиента
___

### Для компиляции:
> *$* make

### Для сервера:
> *$* ./server

### Для клиента:
> *$* ./client

### Для Docker:
> *$* docker compose up
___

### Руководство пользователя

Запустить сервер

Запустить клиента 

Запросить информацию о сервере "*INFO*"

Отправить сообщение на сервер и вернуть его обратно "*ECHO*"

Изменить каталог сервера "*CD*"

Прочитать каталог сервера "*LIST*"

Выйти "*QUIT*"

Для считывания команд из файла **@"название файла"** (файл в корне проекта)

Выключить сервер *"Ctrl + C"*
___

### Интерестные факты

- Неплохо бы присылать каталог каждый раз с сервера. Но я додумался слишком поздно 

- В Docker запустить можно. Но вот как передавать в stdin я не знаю. Одним словом, бесполезно. Возможно нужно будет поменять IP в клиенте 