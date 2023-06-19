### 1. SQL-скрипт для создания таблиц:
Файл: [DDL-script](db/DDL/1_ddl.sql)

### 2. SQL-скрипт для заполения таблиц:
Файл: [DML-script](db/DML/2_dml.sql)

### 3. SQL-запросник - скрипт с решением задач:
Файл: [Queries-script](Scripts/queries.sql)

### 4. Файл Docker-compose:
Файл: [Docker-compose](docker-compose.yml)


### Для развертывания базы "Библиотека" необходимо:
1. Скачать архив из репозитория;
2. Распаковать в нужную папку;
3. В терминале перейти в папку с базой данных и выполнить команду <u>docker-compose up -d </u>.
4. Запустить DBeaver, port 5455, наименование базы данных (library), логин (postgres), пароль(password)
5. Посмотреть результаты отработанного скрипта queries.sql можно в DBeaver'е запустить каждую задачу последовательно или командой: <u>docker logs library</u>.