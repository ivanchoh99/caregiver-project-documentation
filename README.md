# Documentación del Proyecto

Este repositorio está dedicado a la documentación del proyecto. Por el momento, el enfoque principal será definir y detallar la **estructura de la base de datos**.

## Estructura de la Base de Datos

Para la modelacion de la base de datos se esta implementando draw.io, instalando esta aplicación de https://www.drawio.com/. con esto instalado bajar el repo y abrir el archivo .drawio

Estandarizacion base de datos.

1. Para los ids importantes utilizar UUID
2. Nombres de tablas en singular y con sneak_case
3. Nombre de columnas no redundantes, auto explicativo y que las FK son las IDs de la respectiva tabla
> Ej: Tabla User: user_id (redundante) - Tabla: User: id (simple y autodescriptivo)

> Próximamente se agregarán más detalles y diagramas sobre la estructura de la base de datos.
