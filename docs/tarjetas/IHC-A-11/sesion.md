# Sesión de prueba cognitiva, tarjeta IHC-A-11

## Datos de la sesión
- Participante: P-11
- Perfil: Evaluadora con monitor pequeño, 360 px
- Versión probada: v1 (`prototipo/v1/dashboard/`)
- Condiciones: viewport de 360 × 740 px, sin ayuda del equipo durante la tarea.
- Tarea: Registrar etapa, errores y observaciones.

## Resultados observados
| Medida | Valor |
|---|---|
| Tiempo en la tarea | 3 min 9 s (189 s) |
| Errores | 1 |
| Pausas (más de 5 s) | 3 |
| Resultado | Completó la tarea sin superposiciones |

**Cita textual:** «No hay cosas encimadas, pero el botón de seguir queda abajo del todo.»

## Observaciones
1. No encontró elementos superpuestos ni campos ocultos.
2. Mantuvo claro el orden: Stepper arriba y tarjetas debajo.
3. Se desplazó hasta el final de la pantalla para encontrar Siguiente.

## Hallazgo corregido
En pantalla de 360 px, el botón «Siguiente» queda fuera de la zona visible cuando hay varios elementos en pantalla, y la persona debe desplazarse para encontrarlo.

Medición en el prototipo: con 5 productos en el pedido, el botón «Siguiente» está a 762 px del borde superior, y la pantalla visible mide 740 px.

Issue relacionado: ver Issue de acción principal fuera de pantalla (cierre con commit de v2).

## Cambio en v2 (`prototipo/v2/dashboard/`)
Se fijó una barra de acción en la parte inferior de la pantalla, con los botones Anterior y Siguiente siempre visibles.

## Mejora demostrada y mejora estimada
- **Demostrada (medida en el prototipo):** el botón «Siguiente» pasa de 762 px a 685 px, dentro de los 740 px visibles, sin desplazarse. Capturas: `evidencias/antes-despues/dashboard-v1-antes.png` y `evidencias/antes-despues/dashboard-v2-despues.png`.
- **Estimada (por confirmar con otra sesión):** menor tiempo en la tarea, menos pausas y menos errores de toque por buscar el botón.
