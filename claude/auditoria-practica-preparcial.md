# Auditoría · Práctica preparcial 2.º parcial (index.html)

## Cómo se auditó
- Verificación a mano de cada ejercicio (límites, rectas tangentes, estudio de g y h, las ocho primitivas y "Encontrá el error"), derivando cada primitiva para controlarla.
- Resolución programática con Playwright: por cada ejercicio, una respuesta incorrecta (feedback no vacío) y la oficial (feedback "ok").
- Rastreo de fracciones en línea y de LaTeX crudo en el texto visible, en las pistas ocultas y en las devoluciones codificadas.
- Desborde horizontal a 1280, 1024, 820, 414, 390, 360 y 320 px en las cuatro tandas, y capturas a 390 y 320 px.
- Los envíos a la planilla de Google se interceptaron durante las pruebas: no llegó ninguno.

## Resultado
- Respuestas: 20/20 correctas. Ninguna clave estaba mal.
- Errores de JavaScript: 0. Desborde horizontal: 0 en todos los anchos.

## Correcciones aplicadas
1. **Exponentes 1/2 sin apilar.** En E6 b) y E6 d), la pista 3 y dos devoluciones de cada uno mostraban `t^{1}{2}` (llaves crudas). Ahora son fracciones apiladas.
2. **Pestañas en el celular.** Por debajo de 640 px la Tanda 3 quedaba cortada y la Tanda 4 fuera de la pantalla. Ahora son una grilla de 2 × 2, con las cuatro a la vista.
3. **E2: lista de puntos.** En el celular `x₁` quedaba en un renglón y `= −1` en otro. Ahora la lista baja entera a su propio renglón y cada `xᵢ = valor` queda unido.
4. **Cortes de renglón dentro de las fórmulas en línea.** En las pistas, `sen(x) | dx`, `∫ | v du` y `(x − | x₀)` se partían en dos renglones. Ahora sólo se corta junto a los operadores (= + −).

## Observaciones a criterio del docente
- **E4 b)** La clave dice que x = 2 es un punto crítico pero no un extremo relativo, porque no hay un entorno de 2 contenido en el dominio. Es coherente si en el curso un extremo relativo exige un entorno de los dos lados. Si se aceptan los extremos en el borde del dominio, la opción "Sí, porque h(2) = 0 es menor que los valores cercanos" también sería defendible.
- **E3 a)** Se pide escribir la fracción como "1/2". Es una instrucción de tipeo en un campo, no una fracción mostrada.

## Pasada final
- Fecha: 2026-10-19 · md5 de index.html: `f079a51de5d8a06b7701d69027d5c539`
- Resolución 20/20 · fracciones en línea 0 · LaTeX crudo 0 · errores JS 0 · desborde 0 (de 320 a 1280 px).
