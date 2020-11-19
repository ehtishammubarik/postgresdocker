FROM postgres:13
ENV POSTGRES_USER docker
ENV POSTGRES_PASSWORD docker
ENV POSTGRES_DB docker
ADD CreateDB.sql /docker-entrypoint-initdb.d/
