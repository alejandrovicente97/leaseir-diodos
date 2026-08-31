# Control de Diodos — Leaseir

Repositorio **privado**: contiene el parque nominal (clientes, números de serie,
facturas e importes). No hacerlo público sin querer hacerlo público.

- `index.html` — el panel completo. Lleva los datos dentro: se abre solo.
- `datos.json` — la base de datos: parque, diodos, cambios y descuadres.

## Publicar como página

Settings › Pages › Source: `main` / raíz. En repo privado, Pages requiere plan Pro.

## Regenerar

El motor que produce estos dos ficheros está en `motor-diodos.zip`, en la carpeta
*herramienta diodos*. Cinco pasos de Python sobre los ficheros de origen.
