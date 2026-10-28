# Issues, tarjeta IHC-A-12

## Issue 1: El estado final aparece sin comprobar checklist obligatorio
- Severidad: Alta
- Responsable: _asignar_
- Reproducción: seguir la tarea «Recuperar checklist y cerrar sesión» en el prototipo v1 y observar este comportamiento.
- Principio: Nielsen 5, prevención de errores; Nielsen 1, visibilidad del estado
- Decisión de cierre: _completar al cerrar (commit/PR)_

## Issue 2: Sin indicador global de progreso
- Severidad: Media
- Responsable: _asignar_
- Reproducción: completar la tarea y observar que no hay feedback del estado.
- Principio: Nielsen 1, visibilidad del estado
- Decisión de cierre: _completar al cerrar (commit/PR)_

## Issue 3: Checklist en cuadrícula sin agrupar por etapa
- Severidad: Baja
- Responsable: _asignar_
- Reproducción: revisar la pantalla principal de la tarea.
- Principio: Gestalt, proximidad y carga cognitiva
- Decisión de cierre: _completar al cerrar (commit/PR)_

## Issue 4: Acción principal fuera de pantalla en 360 px (hallazgo de la prueba)
- Severidad: Media
- Responsable: _asignar_
- Reproducción: abrir `prototipo/v1/dashboard/` a 360 × 740 px, completar la tarea con varios elementos y buscar «Siguiente».
- Principio: Nielsen 7, eficiencia de uso; carga cognitiva
- Decisión de cierre: barra de acción fija en v2 (`prototipo/v2/dashboard/`); enlazar el commit o PR al cerrar.
