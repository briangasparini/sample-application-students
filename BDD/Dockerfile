FROM postgres:11.6-alpine
ENV POSTGRES_DB=db \
POSTGRES_USER=usr

COPY ./SQL/CreateScheme.sql /docker-entrypoint-initdb.d
COPY ./SQL/InsertData.sql /docker-entrypoint-initdb.d