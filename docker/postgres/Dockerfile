FROM postgres
ENV POSTGRES_DB individual2
ENV POSTGRES_USER fagne
ENV POSTGRES_PASSWORD 333

COPY create.sql /docker-entrypoint-initdb.d/
COPY insert.sql /docker-entrypoint-initdb.d/