# php-crud-pgsql-example
Simple CRUD using PHP and PostgreSQL  


# Credits
Fork from: https://phpforever.com/postgresql/crud-example-using-php-object-oriented-and-postgresql/   
All credits to PHP Forever (just forked to github to make it easier to access)  


# Configuration
Edit file `connection.inc.php` and add your database configuration. A sample database script is provided on `sql/database.sql`.   

```
CREATE TABLE public."user"
(
    id serial NOT NULL,
    name character varying(250),
    email character varying(250),
    mobile_no bigint,
    address text,
    PRIMARY KEY (id)
)
```

To create new user/schema/privs and everything else on postgres refer to its documentation (https://www.postgresql.org/docs/13/index.html)   


# References

1. https://phpforever.com/postgresql/crud-example-using-php-object-oriented-and-postgresql/   
2. https://chartio.com/learn/postgresql/create-a-user-with-psql/