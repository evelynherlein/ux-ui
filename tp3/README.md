# TP HTML/CSS - Diseño UX-UI 2026

Resolución de los 20 ejercicios del trabajo práctico, organizados en carpetas individuales (`ejercicio01` a `ejercicio20`).

## Cómo ver cada ejercicio
Abrí el archivo `index.html` de la carpeta correspondiente con doble clic, o con la extensión Live Server de VS Code.

## Ejercicios resueltos
- 01-04: Estructura HTML básica, listas y enlaces, tabla de datos, formulario simple.
- 05-07: Primeros estilos CSS, selectores CSS, modelo de caja (Box Model).
- 08-10: Flexbox (barra de navegación y galería de tarjetas), CSS Grid (layout de página).
- 11-14: Pseudo-clases/pseudo-elementos, posicionamiento (fixed/absolute), formulario estilizado, variables CSS y modo oscuro simple.
- 15-17: Media queries (desktop first), animaciones con @keyframes, menú hamburguesa solo con CSS (checkbox hack).
- 18-19: Grid avanzado tipo mosaico (auto-fill + dense), formulario multi-step con radio buttons y validación :invalid/:valid.
- 20: Landing page integradora combinando Flexbox, Grid, variables CSS, media queries, animación y HTML semántico.

## Decisiones de diseño
- Se usó una paleta simple y consistente (violeta `#432c4a` como color primario, lila `#f76fd9` como secundario)
- En el Ejercicio 15, se optó por un enfoque **desktop first** ya que se parte de un layout ya construido pensado para escritorio (Ejercicio 10), y se lo adapta progresivamente hacia pantallas chicas con `max-width`.
- El menú tipo hamburgesa (Ejercicio 17) y el formulario multi-step (Ejercicio 19) se resolvieron sin JavaScript, usando el truco del checkbox/radio oculto combinado con el selector `~`.
