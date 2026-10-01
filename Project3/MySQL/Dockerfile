FROM mysql:8.0

ENV MY_SQL_ROOT_PASSWORD = demopassword

ENV MY_SQL_DATABASE = demodb

COPY init.sql /docker-entrypoint-initdb.d/

EXPOSE 3307