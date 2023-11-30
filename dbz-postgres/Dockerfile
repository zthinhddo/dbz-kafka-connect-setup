FROM --platform=linux/amd64 debezium/postgres:13

LABEL maintainer="Sheng"

COPY postgresql.conf.sample /usr/share/postgresql/postgresql.conf

COPY start-up.sql /docker-entrypoint-initdb.d
