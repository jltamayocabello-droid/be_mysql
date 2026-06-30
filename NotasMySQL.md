# SQL: Structured Query Language
    - Lenguaje de programación -> gestionar y manipular bases de datos relacionales

## Tipos de comandos en SQL

    1. DDL (Data Definition Language)
        - CREATE : crear bases de datos
        - ALERT : modifica la estructura de una tabla
        - DROP : elimina bases de datos
        - TRUNCATE : borrar los datos de una tabla pero no la tabla completa
    2. DML (Data Manipulation Language)
        - INSERT TO
        - UPDATE
        - DELETE
        - SELECT
    3. DCL (Data Control Language)
        - GRANT : concede permisos a usuarios
        - REVOKE : revovca los permisos de usuarios
    4. TCL (Transaction Control Language)
        - COMMIT
        - ROLLBACK
        - SAVEPOINT

## Tipos de Datos en MySQL

- Los datos se almacenan en diferentes formatos segun su tipo: númerico, cadena, fecha y hora.

    1. Tipos de datos númericos
        - TINYINT: Entero y pequeño - 128 127
        - SMALLINT: Entero Corto -32768 23767
        - MEDIUMINT : Entero Mediano
        - INT INTEGER: Entero estandar -2,147,483,648 a 2,147,483,647
        - BIGINT: Entero grande
        - DECIMAL NUMERIC: Números decimales con precisión definida
        - FLOAT: números de punto flotante
        - DOUBLE: Números de punto flotante de mayor precisión
    2. Tipos de datos de cadena
        - CHAR: Cadena de Longitud fija 1 a 255
        - TEXT: Texto de tamaño grande
        - BLOB: Datos binarios (imagenes, archivos, etc)
    3. Tipos de datos fecha y hora
        - DATE: Solo fechas YYYY-MM-DD
        - DATETIME: fecha y hora YYYY-MM-DD HH:MM:SS
        - TIMESTAMP: Marca de tiempo - registrar eventos
        - TIME: Solo hora HH:MM:SS
        - YEAR: Solo año YYYY 1985

## Concepto de transacción

    - Una transacción es un conjunto de operaciones que se ejecutan como una unidad indivisibles.
    - Datos integros y coherentes.

    - Propiedades:
        - Atomicidad: Todas o ninguna se ejecutan.
        - Consistencia: la base de datos pasa de un estado valido a otro.
        - Isolamiento: una transacción no afecta a otra hasta que se confirma.
        - Durabilidad: los cambios permanecen.
        
    Ejemplo: Transferencia bancaria de $1000
        1. Se resta el dinero de la cuenta A: -1000
        2. Se suma el dinero en la cuenta B: + 1000
        3. Si una operación falla se revierte todo (rollback)

