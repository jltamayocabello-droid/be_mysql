Práctica en MySQL parte del curso Backend Developer

# Contenido

## 1. Introducción a las bases de datos y MySQL
    - ¿Qué es una base de datos?
    - Tipos de bases de datos
    - ¿Qué es MySQL y cómo funciona?
    - Instalación y configuración de MySQL
    - Uso de MySQL Workbench y linea de comandos

## 2. Fundamentos de SQL
    - Concepto de SQL y sus tipos de comandos
        - DDL (Data Definition Language)
        - DML (Data Manipulation Language)
        - DCL (Data Control Language)
        - TCL (Transaction Control Language)
    - Creación de bases de datos en MySQL
    - Tipos de datos en MySQL

## 3. Operaciones Básicas con SQL
    - Creación de tablas (CREATE TABLE)
    - Inserción de datos (INSERT INTO)
    - Consulta de datos (SELECT)
    - Filtrado de datos con WHERE
    - Actualización de datos ('UPDATE')
    - Eliminación de datos (DELETE)

## 4. Operadores y Funciones en SQL
    - Operadores aritméticos y lógicos ( =, >, <, >=, <=, AND, OR, NOT)
    - Operadores de comparación (LIKE, BETWEEN, IN, IS NULL)
    - Funciones de agregación ( COUNT(), SUM(), AVG(), MAX(), MIN() )
    - Funciones de fecha y hora ( NOW(), CURDATE(), DATE_FORMAT() )
    - Funciones de texto (CONCAT(), SUBSTRING(), LENGTH(), UPPER(), LOWER() )

## 5. Consultas Avanzadas
    - Uso de GROUP BY y HAVING
    - Uso de ORDER BY
    - Uso de LIMIT y OFFSET
    - Subconsultas (SUBQUERY)
    - Uniones entre tablas (JOIN)
        - INNER JOIN
        - LEFT JOIN
        - RIGHT JOIN
        - FULL JOIN (No soportado en MySQL, alternativas con UNION)

## 6. Índices y Optimización de Consultas
    - Creación y uso de indices (INDEX, UNIQUE INDEX)
    - Indices compuestos
    - Explicación de EXPLAIN para optimización
    - Uso de ANALIZE TABLE
    - Estrategias de Optimización de consultas

## 7. Vistas y Procedimientos Almacenados
    - Creación y uso de vistas ( CREATE VIEW )
    - Modificación y eliminación de vistas ( ALTER VIEW, DROP VIEW )
    - Procedimientos almacenados ( CREATE PROCEDURE )
    - Uso de variables y parámetros en procedimientos
    - Llamado de procedimientos almacenados ( CALL )

## 8. Funciones y Triggers
    - Creación y uso de funciones ( CREATE FUNCTION)
    - Uso de RETURNS en funcinoes
    - Creación de triggers ( CREATE TRIGGER )
    - Tipos de triggers:
        - BEFORE INSERT
        - AFTER INSERT
        - BEFORE UPDATE
        - AFTER UPDATE
        - BEFORE DELETE
        - AFTER DELETE

## 9. Gestión de Transacciones
    - Concepto de transacción
    - Uso de STAR TRANSACTION
    - Uso de COMMIT y ROLLBACK
    - Niveles de aislamiento de transacciones
    - Manejo de bloqueos ( LOCK TABLES, UNLOCK TABLES)