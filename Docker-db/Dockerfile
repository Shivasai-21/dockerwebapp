FROM mysql:8.4.11-oraclelinux9

ENV MYSQL_ROOT_PASSWORD="devopspassword"
ENV MYSQL_DATABASE="accounts"
#dont expose passwords here
COPY db_backup.sql docker-entrypoint-initdb.d/db_backup.sql
