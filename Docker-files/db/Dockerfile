FROM mysql:8.0.33
LABEL "Project"="Amine"
LABEL "Author"="Amine"

ENV MYSQL_ROOT_PASSWORD="ysjdbpass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql