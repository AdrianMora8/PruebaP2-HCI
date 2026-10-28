# Requisitos, tarjeta IHC-A-10

| ID | Requisito | Criterio de aceptación |
|---|---|---|
| R1 | En todo momento se identifica el paso actual del Stepper. | El paso activo tiene texto, ícono y foco visible, no solo color. |
| R2 | El checklist indica qué casillas están guardadas y cuáles no. | Cada casilla muestra su estado de guardado y el progreso total en porcentaje. |
| R3 | El procedimiento se lee antes de iniciar la prueba. | No se puede abrir el primer paso sin haber visto el procedimiento. |
| R4 | El paso activo se indica con texto y estado accesible, no solo con color. | El paso activo tiene aria-current=step y la etiqueta 'Paso actual'. |
| R5 | Cada acción y su resultado se anuncian con una región aria-live. | Marcar una casilla o avanzar anuncia el resultado sin mover el foco. |
| R6 | El foco visible sigue un orden lógico por todo el recorrido. | Tab recorre Stepper, checklist y botones en orden con indicador de foco visible. |
