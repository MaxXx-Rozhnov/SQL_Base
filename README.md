# SQL_Base

## Урок 1.

\? команда help чтобы увидить все команды

\! chcp 1251 перевести крокозябры на русский язык


CREATE DATABASE name; создать базу данных и имя бд

\l посмотреть базы данных

\c name подключиться к созданной бд

\conninfo ифнормация о бд

DROP DATABASE avecoder; удаление бд

CREATE TABLE table_name (
    Column name + data type + constraints (if any)
) создать таблицу (имя колонки, тип данных и замечания если есть)

Вы подключены к базе данных "makson" как пользователь "postgres".
makson=# CREATE TABLE employee (
makson(# id BIGSERIAL,
makson(# first_name VARCHAR(50),
makson(# last_name VARCHAR(50),
makson(# gender VARCHAR(50),
makson(# email VARCHAR(150),
makson(# date_of_birth DATE
makson(# );

создали бд.

\d посмотреть список отношений

\d employee посмотреть таблицу

makson=# INSERT INTO employee (
makson(# first_name, last_name, gender, email, date_of_birth)
makson-# VALUES('John', 'Doe', 'MALE', 'Jd@mail.ru','2000-01-01');

ввели значения таблицы



