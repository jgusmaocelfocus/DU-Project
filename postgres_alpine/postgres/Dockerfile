# version image postgres 12
FROM postgres:12-alpine

RUN apk upgrade --available && sync

RUN mkdir -p /var/log/postgresql
RUN chown -R postgres:postgres /var/log/postgresql

ARG POSTGRES_DB: pg_db
ARG POSTGRES_PASSWORD: postgres_pawssord
ARG POSTGRES_USER: postgres

VOLUME ["/var/lib/postgresql/data", "/var/log/postgresql"]

USER postgres