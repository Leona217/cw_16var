# cw_16var
Курсовая работа 16 вариант
1. Необходимо наличие docker.desktop на запускаемой машине.
2. Открыть папку с проектом с visual studio code.
3. Открыть терминал и прописать команду docker-compose up —build (docker.desktop должен быть запущен).
4. Дождаться окончания сборки контейнеров.
5. Перейти в docker.desktop во вкладку Containers. Найти группу контейнеров с наименованием папки с проектом, открыть ее, перейти по ссылке в браузер, нажав на нее в контейнере application.
6. Произвести работу с веб приложением.
7. По окончании работы, в docker.desktop нажать кнопку остановки работы контейнеров, либо в терминале VScode набрать ctrl+c.
8. Для удаления контейнеров в терминале VScode прописать команду docker-compose down -v, либо удалить группу контейнеров из docker.desktop, нажав на значок корзины.
9. Для контроля правильности отображения данных в веб приложении, необходимо в docker.desktop перейти по ссылке контейнера pgadmin в браузер.
10. Пройти регистрацию: логин: admin@admin.com пароль: admin
11. ПКМ на Sersers, Register, Server..
12. В поле Name во вкладке General ввести любое имя
13. Во вкладке Connection заполнить следующие поля:
  Host name/addres: postgres
  Port: 5432
  Maintenance database: postgres
  Username: postgres
  Password: postgres
14. Нажать кнопку Save.
15. Контролировать наличие таблиц flights и planes во вкладке "зарегистрированное вами имя сервера" -> Databases -> coursework -> Schemas -> Tables.
