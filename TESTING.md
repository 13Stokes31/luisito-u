# TESTING — luisito-u

Comprobaciones manuales: cosas ya hechas que falta verificar a mano. Se marcan al
comprobarlas. Para compilar sin publicar, ver «Desarrollo» en el README.

## 0.1.0

- [ ] **Instalación local.** `typst init @local/luisito-u:0.1.0 prueba`, cambiar el
      import del `main.typ` a `@local/luisito-u:0.1.0` y compilar: sale el PDF de
      ejemplo sin errores.
- [ ] **Portada fiel al proyecto original.** Comparar con el PDF del alumno (carpeta
      «Plantilla Universidad San Luis» en Descargas): título grande en mayúsculas,
      Autores/Tutor/Centro abajo a la izquierda, convocatoria y logo al pie.
- [ ] **Texto** con sangría de primera línea y títulos de capítulo
      en verde; páginas iniciales con el título centrado en versalitas.
- [ ] **Anexos.** «Anexo I. Tablas de medidas», «Tabla I.1», y en el Capítulo 3 las
      citas «Anexo I» y «Anexo II» enlazan a su anexo.
- [ ] **Contador de palabras.** Con `contar-palabras: true` sale «Extensión del
      trabajo: 5695 palabras» debajo del índice.
- [ ] **Intercambio con visillos-excelencia.** El `main.typ` de visillos compila con
      luisito-u cambiando solo el import, y al revés.
- [ ] **Fuentes.** Por defecto todo sale en Libertinus Serif y sin avisos. Al
      descomentar `fuente: "Times New Roman"` y `fuente-portada: "Calibri"` en el
      `main.typ`, el texto sale en Times y la portada en Calibri.
- [ ] **Proyecto real.** Pasar el proyecto original del alumno (sus capítulos y su
      `referencias.yaml`) a esta plantilla en una carpeta aparte, y comprobar que
      sale como su PDF y que el recuento de palabras es razonable.
