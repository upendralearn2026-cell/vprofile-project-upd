FROM mysql:8.0.33
LABEL maintainer="UPD"


ENV MYSQL_DATABASE=accounts
ENV MYSQL_PASSWORD="vprodpass"

# To execute any SQL scripts on container startup we need to keep them in this directory
ADD db_backup.sql /docker-entrypoint-initdb.d/db_backup.sql