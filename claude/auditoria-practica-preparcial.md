# Auditoría · Práctica preparcial 2.º parcial (index.html)

Versión auditada: la subida a `main` el 19/10/2026, que agrega puntaje, fotos, informe PDF con resoluciones paso a paso y una pregunta nueva en E4 b). Las correcciones de la auditoría anterior no estaban en esa versión y se volvieron a aplicar.

## Cómo se auditó
- Verificación a mano de las 20 claves y de las 20 resoluciones paso a paso que van al PDF (cada primitiva, derivándola).
- Resolución programática en Chromium a 390 px: nombre y grupo, una respuesta incorrecta y después la oficial en cada ejercicio.
- Puntaje: todo resuelto en el 2.º intento debe dar 60 de 100 (subtotales de 15 de 25 en cada tanda).
- Persistencia: recarga de la página y control de ejercicios cerrados, puntaje, nombre y grupo.
- Fotos y PDF: una foto por tanda, descarga real del PDF con jsPDF y html2canvas, y revisión página por página.
- Fracciones en línea y LaTeX crudo en todo el texto, en las pistas ocultas y en los dos bloques codificados (devoluciones y resoluciones).
- Desborde horizontal a 1280, 1024, 820, 414, 390, 360 y 320 px en las cinco pestañas, y capturas a 390 y 320 px.
- Durante las pruebas se interceptaron los envíos a la planilla de Google, así que no llegó ninguno.

## Resultado
- Claves: 20/20 correctas. Resoluciones del PDF: 20/20 correctas.
- E4 b) nuevo: "¿Dónde tiene h su máximo relativo?" → (√2 ; 2). Es correcto, y las devoluciones de cada distractor también.
- Puntaje: 60 de 100 en el escenario de prueba, como se esperaba. El grupo 1 suma la Parte A; en la Tanda 4 suman la mejor integral por partes, la mejor por sustitución y "Encontrá el error".
- Después de recargar se conservan los 20 ejercicios cerrados, el puntaje, el nombre y el grupo.
- El PDF tiene 25 páginas: resumen, 4 fotos y 20 resoluciones. Sin errores de JavaScript y sin desborde en ningún ancho.

## Correcciones aplicadas
1. **Exponente ½ con llaves crudas** en E6 b) y E6 d): se veía `t^{1}{2}` en la pista 3 y en dos devoluciones de cada uno. Ahora es una fracción apilada.
2. **Pestañas en el celular.** Con la pestaña nueva (Informe) son cinco, y en el celular sólo se veían dos y media. Ahora van en una sola fila ("Tanda 1 … Entrega"), y el nombre de cada tanda sigue en su título.
3. **E2: lista de puntos.** `x₁` quedaba en un renglón y `= −1` en otro. Ahora la lista baja entera.
4. **Cortes dentro de fórmulas en línea**, como `sen(x) | dx`, `∫ | v du` o `(x − | x₀)`. Ahora sólo se corta junto a los operadores.
5. **Ficha del alumno en el celular.** "Grupo" quedaba a la derecha del nombre y el selector en el renglón de abajo. Ahora el nombre ocupa todo el ancho y debajo van "Grupo" y el selector.
6. **Tabla de puntaje a 320 px.** La columna Puntos se cortaba. Ahora usa letra y márgenes más chicos en pantallas angostas.
7. **Resolución de E1 (PDF), redacción.** Decía "1/x, que sólo se anula el denominador en x = 0"; ahora dice "1/x, cuyo denominador sólo se anula en x = 0".

## Observaciones a criterio del docente
- **Puntaje e intentos.** El texto dice "100 % en el 1.er intento, 60 % en el 2.º y 30 % en el 3.º", pero los ejercicios de opción (E1, E4 C, E4 b, E6 y "Encontrá el error") tienen sólo 2 intentos. El 30 % se aplica únicamente a los de respuesta numérica, a E2 y a E4 A. Es coherente, pero algún alumno puede preguntarlo.
- **E3 a)** pide escribir la fracción como "1/2". Es una instrucción de tipeo en un campo, no una fracción mostrada.
- **PDF.** Cada resolución mide entre 11 y 13 cm, así que casi siempre ocupa una hoja propia. El PDF completo pesa unos 2 MB con 4 fotos.

## Pasada final
- Fecha: 2026-10-19 · md5 de index.html: `d2d0a91336ad76fe296b171cd124e9c0`
- Claves 20/20 · resoluciones 20/20 · puntaje 60/60 esperado · persistencia OK · PDF OK (25 págs.) · fracciones en línea 0 · LaTeX crudo 0 · errores JS 0 · desborde 0 (320 a 1280 px).
