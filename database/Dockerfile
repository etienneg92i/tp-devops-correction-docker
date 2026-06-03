FROM postgres:14.1-alpine

<<<<<<< HEAD
COPY 01-CreateScheme.sql /docker-entrypoint-initdb.d/
COPY 02-InsertData.sql /docker-entrypoint-initdb.d/
=======
COPY sql docker-entrypoint-initdb.d

ENV POSTGRES_DB=db \
   POSTGRES_USER=usr
>>>>>>> c493ee4e9c4a7157077b56d3a36b9c991f19b8f1
