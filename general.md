## POSTGRES
create a schema in POSTGRES
```
CREATE SCHEMA IF NOT EXISTS Inventory AUTHORIZATION postgres;
```
## User creation  
create a user with password
```
create user raju with encrypted password 'Postgres123';
```
Granting schema access to the user (role)
```
GRANT USAGE ON SCHEMA your_schema_name TO your_role_name;

```
Creating database
```
create database db_name
```
switching database in psql command line
```
\c your_database_name
```


GRANT USAGE ON SCHEMA schema_name TO role_name;
```
Display all the database in the postgres sql database 
```
\l
```
Display all the schemas in the postgres sql database 
```
\dn
```
change the schema from one owner to another
```
ALTER SCHEMA schema_name OWNER TO new_owner;
```
set createdb access to username 
```
ALTER USER new_username CREATEDB;
```
