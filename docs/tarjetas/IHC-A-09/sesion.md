# Sesión de prueba cognitiva, tarjeta IHC-A-09

## Datos de la sesión
- Participante: P-09
- Perfil: Investigadora con participantes anónimos, celular de 360 px
- Versión probada: v1 (`prototipo/v1/dashboard/`)
- Condiciones: viewport de 360 × 740 px, sin ayuda del equipo durante la tarea.
- Tarea: Registrar resultados con código de participante y finalizar la sesión.

## Resultados observados
| Medida | Valor |
|---|---|
| Tiempo en la tarea | 3 min 18 s (198 s) |
| Errores | 2 |
| Pausas (más de 5 s) | 3 |
| Resultado | Completó la tarea con el código P-07 |

**Cita textual:** «El código es claro, pero tuve que subir y bajar para avanzar.»

## Observaciones
1. Escribió primero un nombre en el campo y el mensaje le indicó el formato P-NN.
2. Corrigió con el código y avanzó al cierre.
3. Desplazó la pantalla para llegar al botón Siguiente en el paso de registro.

## Hallazgo corregido
En pantalla de 360 px, el botón «Siguiente» queda fuera de la zona visible cuando hay varios elementos en pantalla, y la persona debe desplazarse para encontrarlo.

Medición en el prototipo: con 5 productos en el pedido, el botón «Siguiente» está a 762 px del borde superior, y la pantalla visible mide 740 px.

Issue relacionado: ver Issue de acción principal fuera de pantalla (cierre con commit de v2).

## Cambio en v2 (`prototipo/v2/dashboard/`)
Se fijó una barra de acción en la parte inferior de la pantalla, con los botones Anterior y Siguiente siempre visibles.

## Mejora demostrada y mejora estimada
- **Demostrada (medida en el prototipo):** el botón «Siguiente» pasa de 762 px a 685 px, dentro de los 740 px visibles, sin desplazarse. Capturas: `evidencias/antes-despues/dashboard-v1-antes.png` y `evidencias/antes-despues/dashboard-v2-despues.png`.
- **Estimada (por confirmar con otra sesión):** menor tiempo en la tarea, menos pausas y menos errores de toque por buscar el botón.
