# Issues, tarjeta IHC-A-12

## Issue 1: El estado final aparece sin comprobar checklist obligatorio
- Severidad: Alta
- Responsable: Matías Morales (@MatiusJBG)
- Reproducción: seguir la tarea «Recuperar checklist y cerrar sesión» en el prototipo v1 y observar este comportamiento.
- Principio: Nielsen 5, prevención de errores; Nielsen 1, visibilidad del estado
- Decisión de cierre: Resuelto en el prototipo v3: el cierre revisa todos los pasos, lista lo pendiente y permite completarlo sin borrar datos (`prototipo/v3/dashboard/`).

## Issue 2: Sin indicador global de progreso
- Severidad: Media
- Responsable: Matías Morales (@MatiusJBG)
- Reproducción: completar la tarea y observar que no hay feedback del estado.
- Principio: Nielsen 1, visibilidad del estado
- Decisión de cierre: Resuelto en el prototipo v1: barra de progreso con porcentaje (PR #2, `prototipo/v1/dashboard/`).

## Issue 3: Checklist en cuadrícula sin agrupar por etapa
- Severidad: Baja
- Responsable: Matías Morales (@MatiusJBG)
- Reproducción: revisar la pantalla principal de la tarea.
- Principio: Gestalt, proximidad y carga cognitiva
- Decisión de cierre: Resuelto en el prototipo v1: el checklist marca los ítems obligatorios y su estado de guardado (PR #2).

## Issue 4: Acción principal fuera de pantalla en 360 px (hallazgo de la prueba)
- Severidad: Media
- Responsable: Cristian Ango (@CristianDDGA)
- Reproducción: abrir `prototipo/v1/dashboard/` a 360 × 740 px, completar la tarea con varios elementos y buscar «Siguiente».
- Principio: Nielsen 7, eficiencia de uso; carga cognitiva
- Decisión de cierre: Resuelto en el prototipo v2: barra de acción fija con Anterior y Siguiente (PR #3, `prototipo/v2/dashboard/`).
