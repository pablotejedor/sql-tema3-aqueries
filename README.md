# sql-tema3-queries

## Ejercicio 1:


SELECT nombre, apellido, fecha_nacimiento FROM PROFESOR ORDER BY fecha_nacimiento ASC;


## Ejercicio 2:


SELECT * FROM PROFESOR WHERE salario >= 65000;


## Ejercicio 3:


SELECT * from PROFESOR WHERE fecha_nacimiento BETWEEN "1980-01-01" AND "1989-12-31";


## Ejercicio 4:


SELECT * FROM PROFESOR LIMIT 5


## Ejercicio 5:


SELECT * FROM PROFESOR WHERE apellido LIKE ‘P%’;



## Ejercicio 6:


SELECT * FROM PROFESOR WHERE fecha_nacimiento BETWEEN "1980-01-01" AND "1989-12-31" AND salario > 80000;
