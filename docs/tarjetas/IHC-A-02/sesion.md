# Sesión de prueba cognitiva, tarjeta IHC-A-02

## Datos de la sesión
- Participante: P-02
- Perfil: Estudiante que usa solo teclado, pantalla de 360 px
- Versión probada: v1 (`prototipo/v1/cafeu/`)
- Condiciones: viewport de 360 × 740 px, sin ayuda del equipo durante la tarea.
- Tarea: Editar la cantidad de un producto, quitar otro y finalizar sin ratón.

## Resultados observados
| Medida | Valor |
|---|---|
| Tiempo en la tarea | 3 min 25 s (205 s) |
| Errores | 1 |
| Pausas (más de 5 s) | 4 |
| Resultado | Completó la tarea sin ratón |

**Cita textual:** «Con el teclado tuve que pasar por muchos botones antes de llegar a Confirmar.»

## Observaciones
1. Quitó un producto con Enter y cerró el diálogo con Escape; el foco volvió al producto siguiente.
2. Necesitó 11 pulsaciones de Tab para llegar a Confirmar pedido desde el primer control.
3. Hizo una pausa larga al no ver el botón confirmar y recorrió la pantalla con Tab.

## Hallazgo corregido
En pantalla de 360 px, el botón «Confirmar pedido» queda fuera de la zona visible cuando hay varios elementos en pantalla, y la persona debe desplazarse para encontrarlo.

Medición en el prototipo: con 5 productos en el pedido, el botón «Confirmar pedido» está a 972 px del borde superior, y la pantalla visible mide 740 px.

Issue relacionado: ver Issue de acción principal fuera de pantalla (cierre con commit de v2).

## Cambio en v2 (`prototipo/v2/cafeu/`)
Se fijó una barra de acción en la parte inferior de la pantalla, con el total y el botón Confirmar pedido siempre visibles. Además, si el aviso de alérgenos bloquea la confirmación, la barra explica el motivo.

## Mejora demostrada y mejora estimada
- **Demostrada (medida en el prototipo):** el botón «Confirmar pedido» pasa de 972 px a 662 px, dentro de los 740 px visibles, sin desplazarse. Capturas: `evidencias/antes-despues/cafeu-v1-antes.png` y `evidencias/antes-despues/cafeu-v2-despues.png`.
- **Estimada (por confirmar con otra sesión):** menor tiempo en la tarea, menos pausas y menos errores de toque por buscar el botón.
