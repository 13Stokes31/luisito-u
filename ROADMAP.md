# ROADMAP — luisito-u

Lo que está por hacer o por decidir. Lo ya hecho pero sin comprobar está en
`TESTING.md`.

## Pendiente

### Publicar la 0.1.0 en Universe
Estado: **PR abierto, falta el merge**. PR typst/packages#6141 enviado el
2026-10-17 con los tres checks en verde; etiqueta `v0.1.0` en el repo. Si los
revisores piden cambios, corregir, mover la etiqueta (`git tag -f` + push --force)
y copiar los ficheros a la rama `luisito-u-0.1.0` del fork.

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
