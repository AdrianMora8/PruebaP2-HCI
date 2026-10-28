# Defensa

## Contribución por integrante
| Integrante | Primera parte | Incidencias sorpresa |
|---|---|---|
| Oscar Riofrio | Tarjetas 01 a 03, prototipo de CaféU v1 y README | Prototipo de CaféU v3 (Deshacer al quitar) |
| Julio Jacho | Tarjetas 04 a 06 y diagramas | Documentación de las incidencias 02 y 12: R7, flujo y trazabilidad |
| Matías Morales | Tarjetas 07 a 09, prototipo de Dashboard v1 y decisiones | Prototipo de Dashboard v3 (cierre con revisión de pendientes) |
| Cristian Ango | Tarjetas 10 a 12, prototipos v2 y capturas | Capturas de antes y después, y esta defensa |

## Issues y PR de las incidencias
| Issue | Responsable | Qué cierra |
|---|---|---|
| #5 Incidencia 02 | Oscar | Prototipo de CaféU v3 |
| #6 Incidencia 12 | Matías | Prototipo de Dashboard v3 |
| #7 R7 y trazabilidad | Julio | Documentos de las incidencias 02 y 12 |
| #8 Evidencia antes y después | Cristian | Capturas y esta defensa |

## Incidencia 02, Quitar con teclado (CaféU)
**Pregunta:** Demuestre edición, eliminación y confirmación sin usar el ratón.

Tab hasta Quitar, Enter, el diálogo se confirma con Enter en «Sí, quitar» (Escape cancela). El foco pasa al siguiente Quitar y se anuncia el producto eliminado. Tab hasta Deshacer, Enter, o seguir con Tab hasta Confirmar pedido y Enter.

## Incidencia 12, Finalización prematura (Dashboard UX)
**Pregunta:** ¿Cómo muestra el momento de verdad y comprueba el estado final?

El momento de verdad es el Cierre: se muestra un resumen con lo completado y la lista de pendientes. El estado final se comprueba porque el sistema revisa procedimiento, checklist y registro, y el éxito solo aparece si no falta nada.

## Qué evidencia muestra la mejora
Las capturas de `evidencias/incidencias/` muestran el mismo caso antes y después. En CaféU, quitar un producto ahora ofrece Deshacer. En el Dashboard, un cierre con un ítem pendiente deja de mostrar éxito y lista lo que falta.
