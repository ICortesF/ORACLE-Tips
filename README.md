# ORACLE-Tips

## Listar todas las tablas en Oracle
```[SQL]
select * from ALL_TABLES;
```
[Fuente](http://systemadmin.es/2009/10/listar-totas-las-tablas-en-oracle "Fuente")

## Ver campos de una tabla
```[SQL]
select * from all_tab_columns where table_name ='NOMBRETABLA'
```
## Equivalente al top en SQL
```[SQL]
SELECT column_name(s)
FROM table_name
WHERE condition
LIMIT number;
```
