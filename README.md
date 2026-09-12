# Gestión de Donaciones de Sangre con JDBC

Aplicación Java desarrollada para gestionar donaciones y traspasos de sangre
entre hospitales utilizando **JDBC** y una base de datos **Oracle**.

El proyecto aplica acceso directo a base de datos mediante SQL, control
transaccional y validación de reglas de negocio.

## Funcionalidades

Entre las operaciones implementadas se encuentran:

- Registro de nuevas donaciones.
- Validación de la existencia de donantes.
- Validación de hospitales y reservas de sangre.
- Control de la cantidad máxima permitida por donación.
- Comprobación de donaciones realizadas recientemente.
- Actualización automática de las reservas hospitalarias.
- Anulación de traspasos de sangre.
- Restauración de las reservas de los hospitales implicados.
- Consulta de traspasos por tipo de sangre.

## Modelo de datos

La base de datos incluye entidades relacionadas con:

- Donantes.
- Tipos de sangre.
- Hospitales.
- Reservas hospitalarias.
- Donaciones.
- Traspasos.

Las tablas, restricciones, claves foráneas y datos de prueba se encuentran en:

```text
sql/gestion_donaciones_sangre.sql
````
## Autores

Héctor Sánchez García, Mohamed Amin El Amrani El Khottouli, Pablo Cela Duran
