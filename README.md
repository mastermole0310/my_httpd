Проект HTTP-сервера Apache — это попытка разработать и поддерживать HTTP-сервер с открытым исходным кодом для современных операционных систем, включая UNIX и Windows. Цель этого проекта — предоставить безопасный, эффективный и расширяемый сервер, предоставляющий службы HTTP в соответствии с текущими стандартами HTTP.
- ТРЕБОВАНИЯ:
- OC Linux
- установка докера
- запуск docker deamon
- УСТАНОВКА И ЗАПУСК:
- выполните следующую команду
- docker run -d -p 8080:80 --name любое_имя mastermole/my_httpd, где 
- run - команда для запуска
- d - запуск контейнера в фоновом режиме
- p 8080:80 - сопоставить порт 8080 хоста с портом 80 в контейнере (порт №1 может быть любым)
- --name - задать имя контейнеру
- mastermole/my_httpd - изображение для использования
- ФУНКЦИИ:
- поддержка http-протокола
- подключение внешних модулей
- обработка файлов конфигурации
- использование БД для проверки подлинности пользователей
- РАЗРАБОТЧИК:
- Smirnov Alexey
- ПРИМЕЧАНИЕ:
- руководство дается для базового использования
- отдельное спасибо Apache Software Foundation