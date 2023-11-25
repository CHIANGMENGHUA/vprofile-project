FROM mysql:8.0.33
LABEL "Project"="Vprofile"
LABEL "Author"="Leon"

ENV MYSQL_ROOT_PASSWORD=MY_DB_PASSWD
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql