# Control de Diodos — Leaseir

Repositorio **público**. Por eso lo que hay aquí es solo el agregado: cuadre,
añadas y calidad del dato. **Sin nombres de cliente, sin números de serie, sin
facturas ni importes.** La tabla "parque por cliente" va anonimizada (Cliente 1…12).

- `index.html` — el panel público. Lleva los datos dentro: se abre solo.

El panel completo —el parque equipo a equipo, con cliente, serie de diodo,
disparos, garantía y factura— vive en `Control de Diodos.html`, en la carpeta
*herramienta diodos*. Ese no se sube aquí.

## Ver la página

Settings › Pages › Source: `main` / raíz. Al ser público, no hace falta plan Pro.
Queda en `https://alejandrovicente97.github.io/leaseir-diodos/`.

## Regenerar

El motor que produce estos ficheros está en `motor-diodos.zip`, en la carpeta
*herramienta diodos*. Cinco pasos de Python sobre los ficheros de origen.
