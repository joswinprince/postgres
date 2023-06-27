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
