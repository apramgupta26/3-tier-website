FROM mysql:8.0

ENV MYSQL_DATABASE=appdb

COPY init.sql /docker-entrypoint-initdb.d/init.sql

EXPOSE 3306