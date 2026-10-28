# Sesión de prueba cognitiva, tarjeta IHC-A-06

## Datos de la sesión
- Participante: P-06
- Perfil: Estudiante con red móvil inestable, celular de 360 px
- Versión probada: v1 (`prototipo/v1/cafeu/`)
- Condiciones: viewport de 360 × 740 px, sin ayuda del equipo durante la tarea.
- Tarea: Confirmar el pedido desde el teléfono.

## Resultados observados
| Medida | Valor |
|---|---|
| Tiempo en la tarea | 2 min 53 s (173 s) |
| Errores | 1 |
| Pausas (más de 5 s) | 3 |
| Resultado | Completó la tarea tras reintentar una vez |

**Cita textual:** «Vi que decía pendiente, así que esperé y no toqué dos veces.»

## Observaciones
1. Vio el estado Pendiente y luego No confirmado; reintentó sin perder el pedido.
2. El botón se deshabilitó al primer toque y no hubo confirmaciones duplicadas.
3. Buscó el botón Reintentar más abajo de lo esperado en la pantalla.

## Hallazgo corregido
En pantalla de 360 px, el botón «Confirmar pedido» queda fuera de la zona visible cuando hay varios elementos en pantalla, y la persona debe desplazarse para encontrarlo.

Medición en el prototipo: con 5 productos en el pedido, el botón «Confirmar pedido» está a 972 px del borde superior, y la pantalla visible mide 740 px.

Issue relacionado: ver Issue de acción principal fuera de pantalla (cierre con commit de v2).

## Cambio en v2 (`prototipo/v2/cafeu/`)
Se fijó una barra de acción en la parte inferior de la pantalla, con el total y el botón Confirmar pedido siempre visibles. Además, si el aviso de alérgenos bloquea la confirmación, la barra explica el motivo.

## Mejora demostrada y mejora estimada
- **Demostrada (medida en el prototipo):** el botón «Confirmar pedido» pasa de 972 px a 662 px, dentro de los 740 px visibles, sin desplazarse. Capturas: `evidencias/antes-despues/cafeu-v1-antes.png` y `evidencias/antes-despues/cafeu-v2-despues.png`.
- **Estimada (por confirmar con otra sesión):** menor tiempo en la tarea, menos pausas y menos errores de toque por buscar el botón.
