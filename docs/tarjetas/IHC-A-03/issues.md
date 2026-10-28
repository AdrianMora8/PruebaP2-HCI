# Issues, tarjeta IHC-A-03

## Issue 1: La pantalla dice «Listo» pero no muestra número ni resumen
- Severidad: Alta
- Responsable: _asignar_
- Reproducción: seguir la tarea «Confirmar pedido y comprobar que se recibió» en el prototipo v1 y observar este comportamiento.
- Principio: Nielsen 1, visibilidad del estado
- Decisión de cierre: _completar al cerrar (commit/PR)_

## Issue 2: Sin estado de procesamiento al confirmar
- Severidad: Media
- Responsable: _asignar_
- Reproducción: completar la tarea y observar que no hay feedback del estado.
- Principio: Nielsen 1, visibilidad del estado
- Decisión de cierre: _completar al cerrar (commit/PR)_

## Issue 3: Productos del menú sin agrupación por categoría
- Severidad: Baja
- Responsable: _asignar_
- Reproducción: revisar la pantalla principal de la tarea.
- Principio: Gestalt, proximidad y similitud
- Decisión de cierre: _completar al cerrar (commit/PR)_

## Issue 4: Acción principal fuera de pantalla en 360 px (hallazgo de la prueba)
- Severidad: Media
- Responsable: _asignar_
- Reproducción: abrir `prototipo/v1/cafeu/` a 360 × 740 px, completar la tarea con varios elementos y buscar «Confirmar pedido».
- Principio: Nielsen 7, eficiencia de uso; carga cognitiva
- Decisión de cierre: barra de acción fija en v2 (`prototipo/v2/cafeu/`); enlazar el commit o PR al cerrar.
