# Requisitos, tarjeta IHC-A-07

| ID | Requisito | Criterio de aceptación |
|---|---|---|
| R1 | En todo momento se identifica el paso actual del Stepper. | El paso activo tiene texto, ícono y foco visible, no solo color. |
| R2 | El checklist indica qué casillas están guardadas y cuáles no. | Cada casilla muestra su estado de guardado y el progreso total en porcentaje. |
| R3 | El procedimiento se lee antes de iniciar la prueba. | No se puede abrir el primer paso sin haber visto el procedimiento. |
| R4 | El paso actual se identifica siempre con texto, ícono y foco visible. | El Stepper muestra 'Paso 2 de 4: Configurar checklist' con aria-current=step. |
| R5 | No se puede avanzar sin completar los requisitos de la etapa y se explica el motivo. | Al pulsar Siguiente con campos pendientes aparece un mensaje que indica qué falta. |
| R6 | Se puede volver a una etapa anterior sin perder las marcas. | Retroceder y avanzar conserva todas las casillas marcadas. |
