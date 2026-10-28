# Trazabilidad, tarjeta IHC-A-12

| Requisito | Flujo | Pantalla | Componente | Wireframe |
|---|---|---|---|---|
| R1 | Rama principal | Configurar checklist | Stepper | Inicio |
| R2 | Rama de editar/error | Registro de resultados | Casilla de checklist | Acción |
| R3 | Rama principal | Cierre y resumen | Tarjeta (Card UI) | Error |
| R4 | Rama principal | Cierre y resumen | Región de estado (aria-live) | Confirmación |
| R5 | Rama de editar/error | Cierre y resumen | Formulario | Inicio |
| R6 | Rama de editar/error | Cierre y resumen | Stepper | Acción |
| R7 | Rama de editar/error (incidencia) | Cierre y resumen | Formulario | Confirmación |

**Flujo:** Inicio → Procedimiento → Configurar checklist → Registro de resultados → Cierre y resumen. Rama de edición/error: etapa con requisitos pendientes → mensaje → volver y completar; retroceder conserva marcas.


**Cambio por incidencia:** En la rama de error, el diamante «¿Checklist obligatorio OK?» ahora revisa todos los pasos al cerrar. Si falta algo, se muestra la lista y «Completar» regresa a esa etapa sin borrar datos; el éxito solo aparece con todo completo.
