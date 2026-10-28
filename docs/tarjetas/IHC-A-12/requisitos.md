# Requisitos, tarjeta IHC-A-12

| ID | Requisito | Criterio de aceptación |
|---|---|---|
| R1 | En todo momento se identifica el paso actual del Stepper. | El paso activo tiene texto, ícono y foco visible, no solo color. |
| R2 | El checklist indica qué casillas están guardadas y cuáles no. | Cada casilla muestra su estado de guardado y el progreso total en porcentaje. |
| R3 | El procedimiento se lee antes de iniciar la prueba. | No se puede abrir el primer paso sin haber visto el procedimiento. |
| R4 | Al retomar la prueba se recuperan todos los pasos ya finalizados. | Recargar la página conserva los pasos completados y marcados. |
| R5 | Antes de cerrar se muestra una revisión con el resumen del checklist. | Una pantalla de revisión lista cada ítem obligatorio con su estado. |
| R6 | No se muestra éxito si falta un ítem obligatorio. | Con un ítem pendiente, Cerrar sesión se bloquea y el mensaje indica qué falta. |
| R7 | No se finaliza la sesión si falta un requisito: se lista lo pendiente, se permite completarlo sin borrar datos y el éxito solo aparece al cumplirse todo. | Con «Cronómetro a cero» sin marcar, Cerrar sesión se bloquea y lo indica; «Completar» lleva al checklist con el código, el tiempo y los errores conservados. |
