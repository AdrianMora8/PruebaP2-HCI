# Sesión de prueba cognitiva, tarjeta IHC-A-08

## Datos de la sesión
- Participante: P-08
- Perfil: Docente evaluador con poco tiempo, celular de 360 px
- Versión probada: v1 (`prototipo/v1/dashboard/`)
- Condiciones: viewport de 360 × 740 px, sin ayuda del equipo durante la tarea.
- Tarea: Completar los datos de prueba y el checklist.

## Resultados observados
| Medida | Valor |
|---|---|
| Tiempo en la tarea | 3 min 34 s (214 s) |
| Errores | 1 |
| Pausas (más de 5 s) | 3 |
| Resultado | Completó la tarea y verificó que las marcas se conservaron |

**Cita textual:** «Me gustó que dijera Guardado, pero el botón siguiente estaba escondido.»

## Observaciones
1. Leyó el procedimiento y marcó que lo entendió.
2. Comprobó que las casillas seguían marcadas al volver desde el paso siguiente.
3. Tuvo que bajar para llegar a Anterior y Siguiente.

## Hallazgo corregido
En pantalla de 360 px, el botón «Siguiente» queda fuera de la zona visible cuando hay varios elementos en pantalla, y la persona debe desplazarse para encontrarlo.

Medición en el prototipo: con 5 productos en el pedido, el botón «Siguiente» está a 762 px del borde superior, y la pantalla visible mide 740 px.

Issue relacionado: ver Issue de acción principal fuera de pantalla (cierre con commit de v2).

## Cambio en v2 (`prototipo/v2/dashboard/`)
Se fijó una barra de acción en la parte inferior de la pantalla, con los botones Anterior y Siguiente siempre visibles.

## Mejora demostrada y mejora estimada
- **Demostrada (medida en el prototipo):** el botón «Siguiente» pasa de 762 px a 685 px, dentro de los 740 px visibles, sin desplazarse. Capturas: `evidencias/antes-despues/dashboard-v1-antes.png` y `evidencias/antes-despues/dashboard-v2-despues.png`.
- **Estimada (por confirmar con otra sesión):** menor tiempo en la tarea, menos pausas y menos errores de toque por buscar el botón.
