# SQL basic SELECT
SQL introduction

~~
CREATE TABLE series{
  ...
}
~~

show all collumns from the TABLE:  SELECT * series.

# SELECT DISTINCT

The SELECT DISTINCT statement is used to return only distinct (different) values.
Inside a table, a column often contains many duplicate values; and sometimes you only want to list the different (distinct) values.

Muestra 1 vez la columna que queremos de la tabla. Ya que muchas veces los datos de la columna pueden estar repetidos.

~~
SELECT DISTINCT columna FROM tabla
~~
