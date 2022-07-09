
# Postgres

### List of Commands
***
## **Pullout version**
```
SELECT version();
```
## **Print date**
```
SELECT now();
```
## **Creating the database in POSTGRES SQL**
```
CREATE DATABASE favouritefruit
WITH 
OWNER =postgres
ENCODING = 'UTF8'
CONNECTION LIMIT = -1;

```
## **List all the database in the POSTGRES SQL**
```
\l
```
## **Switching the database** 
```
\c databaseName
```
## **Create a table** 
```
create table colors(colorId int,colorName char(20));
```
To create a Table fruit and assign owner postgres and schema as public
```
CREATE TABLE public.fruit
(
"FruitId" integer,
);
ALTER TABLE public.fruit
OWNER to postgres;
```
## **Inserting values**
```

insert into colors values (1,'red'), (2,'blue'),(3,'green');
```
## **Selecting values**
```
SELECT * FROM COLORS;
```
## ** To reset the password
```
C:\Program Files\PostgreSQL\14\data\pg_hba.conf
```
..