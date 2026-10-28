# Sesión de prueba cognitiva, tarjeta IHC-A-05

## Datos de la sesión
- Participante: P-05
- Perfil: Estudiante con presupuesto de USD 4,25, celular de 360 px
- Versión probada: v1 (`prototipo/v1/cafeu/`)
- Condiciones: viewport de 360 × 740 px, sin ayuda del equipo durante la tarea.
- Tarea: Añadir productos, ajustar cantidades y revisar el total.

## Resultados observados
| Medida | Valor |
|---|---|
| Tiempo en la tarea | 3 min 16 s (196 s) |
| Errores | 2 |
| Pausas (más de 5 s) | 3 |
| Resultado | Completó la tarea ajustando el pedido al presupuesto |

**Cita textual:** «El aviso del presupuesto está arriba, pero el total y el botón quedan lejos.»

## Observaciones
1. Superó el presupuesto y vio el aviso con el exceso en dólares.
2. Usó Ajustar pedido y redujo cantidades sin perder el carrito.
3. Para ver el total y el botón de confirmar necesitó desplazarse hacia abajo.

## Hallazgo corregido
En pantalla de 360 px, el botón «Confirmar pedido» queda fuera de la zona visible cuando hay varios elementos en pantalla, y la persona debe desplazarse para encontrarlo.

Medición en el prototipo: con 5 productos en el pedido, el botón «Confirmar pedido» está a 972 px del borde superior, y la pantalla visible mide 740 px.

Issue relacionado: ver Issue de acción principal fuera de pantalla (cierre con commit de v2).

## Cambio en v2 (`prototipo/v2/cafeu/`)
Se fijó una barra de acción en la parte inferior de la pantalla, con el total y el botón Confirmar pedido siempre visibles. Además, si el aviso de alérgenos bloquea la confirmación, la barra explica el motivo.

## Mejora demostrada y mejora estimada
- **Demostrada (medida en el prototipo):** el botón «Confirmar pedido» pasa de 972 px a 662 px, dentro de los 740 px visibles, sin desplazarse. Capturas: `evidencias/antes-despues/cafeu-v1-antes.png` y `evidencias/antes-despues/cafeu-v2-despues.png`.
- **Estimada (por confirmar con otra sesión):** menor tiempo en la tarea, menos pausas y menos errores de toque por buscar el botón.
