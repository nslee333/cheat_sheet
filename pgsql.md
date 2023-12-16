“/etc/init.d/postgresql restart" => restart postgresql server.

psql -> pgsql command line

service postgresql status -> see if the database is running 

psql <database> -> psql mode for database, be careful.

createdb <database name> -> create database.

localhost is also known as 127.0.0.1, which helped me connect pgAdmin4 to my Postgres DB.

location of pg_hba.conf -> /etc/postgresql/16/main/pg_hba.conf, also note, make sure to check read priviledges in linux, you might need to sudo to read it.

in psql mode:

\q OR ctrl + d -> quit to postgres

\h -> help for sql commands

\i [filename] to run sql scripts

\du -> display users + permisions

\d [table name] display details of table



