
# Postgres

### List of Commands
***
>**Pullout version**
```
SELECT version();
```
>**Print date**
```
SELECT now();
```
>**Creating the database in POSTGRES SQL**
```
CREATE DATABASE favouritefruit
WITH 
OWNER =postgres
ENCODING = 'UTF8'
CONNECTION LIMIT = -1;

```
>**List all the database in the POSTGRES SQL**
```
\l
```
>**Switching the database** 
```
\c databaseName
```
>**Create a table** 
```
create table colors(colorId int,colorName char(20));
```
>**Inserting values**
```

insert into colors values (1,'red'), (2,'blue'),(3,'green');
```
>**Selecting values**
```
SELECT * FROM COLORS;
```
