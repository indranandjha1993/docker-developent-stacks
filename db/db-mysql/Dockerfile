FROM mysql:latest

COPY init.sql /docker-entrypoint-initdb.d/init.sql

ENV MYSQL_ROOT_PASSWORD=password
ENV MYSQL_DATABASE=mydatabase

EXPOSE 3306
