
# Postgres

## List of Commands
***
### **Pullout version**
```
SELECT version();
```
### **Print date**
```
SELECT now();
```
### Creating the database in POSTGRES SQL
```
CREATE DATABASE favouritefruit
WITH 
OWNER =postgres
ENCODING = 'UTF8'
CONNECTION LIMIT = -1;

```
### List all the database in the POSTGRES SQL
```
\l
```
### Switching the database
```
\c databaseName
```
### Create a table 
```
create table colors(colorId int,colorName char(20));
```
### To create a Table fruit and assign owner postgres and schema as public
```
CREATE TABLE public.fruit
(
"FruitId" integer,
);
ALTER TABLE public.fruit
OWNER to postgres;
```
### **Inserting values**
```

insert into colors values (1,'red'), (2,'blue'),(3,'green');
```
### Selecting values**
```
SELECT * FROM COLORS;
```
### To reset the password
```
C:\Program Files\PostgreSQL\14\data\pg_hba.conf
```

### Previliges

| Name | Data Type | Description|
| --- | --- | --- |
| grantor | sql_identifier | Name of the user that granted the privilege |
| grantee	| sql_identifier	| Name of the user or group that the privilege was granted to |
| table_catalog |	sql_identifier |	Name of the database that contains the table (always the current database) |
| table_schema |	sql_identifier |	Name of the schema that contains the table |
| table_name |	sql_identifier |	Name of the table |
| privilege_type | 	character_data |	Type of the privilege: SELECT, DELETE, INSERT, UPDATE, REFERENCES, RULE, or TRIGGER |
| is_grantable	| character_data |	YES if the privilege is grantable, NO if not |
| with_hierarchy	| character_data |	Applies to a feature not available in PostgreSQL |

### create schemas

```
CREATE SCHEMAS schemaname AUTHORIZATION userRole;

```

### Query table in cmd
```
SELECT column1, column2, column3, column4 FROM "schema"."table";
```