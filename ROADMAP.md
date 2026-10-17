# ROADMAP — luisito-u

Lo que está por hacer o por decidir. Lo ya hecho pero sin comprobar está en
`TESTING.md`.

## Pendiente

### Publicar en Universe
Estado: **pendiente** (instalada como `@local/luisito-u:0.1.0`).
Pasos según la receta de meshpad: crear el repo `13Stokes31/luisito-u` en GitHub,
push, etiqueta `v0.1.0` (el README enlaza la miniatura a ella), copiar `lib.typ`,
`LICENSE`, `README.md`, `typst.toml`, `thumbnail.png` y `template/` al fork
`13Stokes31/packages` y abrir el PR `luisito-u:0.1.0`.

### Mantener a la par con visillos-excelencia
Estado: **abierto**. Las dos plantillas comparten la configuración del `main.typ`
(basta con cambiar el import). Cualquier parámetro nuevo o arreglo de numeración,
anexos o contador hay que llevarlo a las dos. Las diferencias a propósito son la
portada, las fuentes, los tamaños de los títulos, la sangría y que luisito-u no
lleva cabecera con el capítulo.

### Versión mínima de Typst sin comprobar
Estado: **abierto**. `compiler = "0.13.0"`, pero solo se ha compilado con 0.15.

### ¿Capítulos sin salto de página?
Estado: **propuesta**. El proyecto original tenía `salto-de-pagina-en-capitulo:
false` para que un capítulo siguiera en la misma página que el anterior. Ahora cada
capítulo empieza en página nueva (igual que en visillos-excelencia). Si se añade,
añadirlo en las dos plantillas.
