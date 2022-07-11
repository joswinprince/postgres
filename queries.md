### Create table for Departments
```
CREATE TABLE public."Departments"
(
    deparment_id serial,
    department_name character varying NOT NULL,
    building character varying NOT NULL,
    PRIMARY KEY (deparment_id)
);

ALTER TABLE IF EXISTS public."Departments"
    OWNER to "joswin.prince";
    ```