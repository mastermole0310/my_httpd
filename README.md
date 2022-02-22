Status of Last Build:<br>
<img src="https://github.com/mastermole0310/my_httpd/workflows/Publish Docker image/badge.svg?branch-main"><br>


## ==Что вы увидите на экране после запуска==
![Безымянный](https://user-images.githubusercontent.com/95876810/155151091-0c58233f-b4aa-4ae2-b8f8-aff028f9a73e.jpg)

**Мой HTTP-сервер —  безопасный сервер, предоставляющий службы HTTP.

## ==ТРЕБОВАНИЯ==
- OC Linux, Windows, MacOS (тестировалась на ОС Linux)
- установленный докер version 20.10.7+ (более ранние версии не тестировались, но должны работать)
## ==УСТАНОВКА И ЗАПУСК==
- выполните следующую команду
**docker run -d -p 8080:80 mastermole/my_httpd:main**, где 
- run - команда для запуска
- d - запуск контейнера в фоновом режиме
- p 8080:80 - сопоставить порт 8080 хоста с портом 80 в контейнере (порт №1 может быть любым)
- mastermole/my_httpd:main - изображение для использования
## ==ФУНКЦИИ==
- поддержка http-протокола
- использование БД для проверки подлинности пользователей
## ==РАЗРАБОТЧИК==
- Smirnov Alexey
## ==ПРИМЕЧАНИЕ==
- отдельное спасибо **Apache Software Foundation**
