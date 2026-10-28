# Issues, tarjeta IHC-A-02

## Issue 1: El botón Quitar no tiene nombre accesible ni confirmación
- Severidad: Alta
- Responsable: Oscar Riofrio (@AdrianMora8)
- Reproducción: seguir la tarea «Editar un pedido y finalizar sin ratón» en el prototipo v1 y observar este comportamiento.
- Principio: Nielsen 5, prevención de errores; accesibilidad (nombre accesible)
- Decisión de cierre: Resuelto en el prototipo v1: cada botón Quitar tiene nombre accesible y pide confirmación en un diálogo (PR #1, `prototipo/v1/cafeu/`).

## Issue 2: Sin estado de procesamiento al confirmar
- Severidad: Media
- Responsable: Oscar Riofrio (@AdrianMora8)
- Reproducción: completar la tarea y observar que no hay feedback del estado.
- Principio: Nielsen 1, visibilidad del estado
- Decisión de cierre: Resuelto en el prototipo v1: el botón muestra «Confirmando…» y un estado Pendiente (PR #1).

## Issue 3: Productos del menú sin agrupación por categoría
- Severidad: Baja
- Responsable: Oscar Riofrio (@AdrianMora8)
- Reproducción: revisar la pantalla principal de la tarea.
- Principio: Gestalt, proximidad y similitud
- Decisión de cierre: Resuelto en el prototipo v1: el menú se agrupa en Bebidas y Comidas (PR #1).

## Issue 4: Acción principal fuera de pantalla en 360 px (hallazgo de la prueba)
- Severidad: Media
- Responsable: Cristian Ango (@CristianDDGA)
- Reproducción: abrir `prototipo/v1/cafeu/` a 360 × 740 px, completar la tarea con varios elementos y buscar «Confirmar pedido».
- Principio: Nielsen 7, eficiencia de uso; carga cognitiva
- Decisión de cierre: Resuelto en el prototipo v2: barra de acción fija con el total y Confirmar (PR #3, `prototipo/v2/cafeu/`).
