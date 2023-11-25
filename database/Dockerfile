
# Dockerfile for MySQL
FROM mysql:5.7

ENV MYSQL_HOST=mysql 
ENV MYSQL_DB=mydb
ENV MYSQL_USER=root
ENV MYSQL_PASSWORD=admin

COPY init.sql /docker-entrypoint-initdb.d/
