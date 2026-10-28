# Incidencia sorpresa, tarjeta IHC-A-12: Finalización prematura

## Evento imprevisto
El sistema marca finalizada una sesión aunque falta un requisito del checklist.

## Cambio obligatorio
Impedir la finalización falsa, explicar el elemento pendiente y permitir completarlo sin borrar datos.

## Issue
- Título: Finalización prematura (incidencia sorpresa)
- Severidad: Alta
- Responsable: Matías Morales (@MatiusJBG)
- Issue en GitHub: #6
- Reproducción: abrir `prototipo/v2/dashboard/index.html` y reproducir el evento; el comportamiento corregido está en `prototipo/v3/dashboard/index.html`.
- Decisión de cierre: cambio implementado en `prototipo/v3/dashboard/`; el Issue se cierra con el PR que sube esa carpeta.

## Requisito nuevo (R7)
No se finaliza la sesión si falta un requisito: se lista lo pendiente, se permite completarlo sin borrar datos y el éxito solo aparece al cumplirse todo.

Criterio de aceptación: Con «Cronómetro a cero» sin marcar, Cerrar sesión se bloquea y lo indica; «Completar» lleva al checklist con el código, el tiempo y los errores conservados.

## Flujo y trazabilidad
En la rama de error, el diamante «¿Checklist obligatorio OK?» ahora revisa todos los pasos al cerrar. Si falta algo, se muestra la lista y «Completar» regresa a esa etapa sin borrar datos; el éxito solo aparece con todo completo.

La fila R7 se agregó a `trazabilidad.md` y a `requisitos.md` de esta tarjeta.

## Prueba antes y después
- **Antes:** v2: con «Cronómetro a cero» sin marcar, Cerrar sesión muestra «Sesión cerrada. Todos los datos quedaron registrados» (éxito falso). Captura: `evidencias/incidencias/12-antes.png`.
- **Después:** v3: Cerrar sesión se bloquea con «No se puede cerrar: faltan 1 elemento(s): Checklist: Cronómetro a cero» y la revisión lista lo pendiente con el botón «Completar»; al usarlo se vuelve al checklist con código P-07, tiempo 80 y errores 1 conservados, y al completar el ítem se cierra con éxito. Capturas: `evidencias/incidencias/12-despues.png`. Probado en el navegador.

## Defensa
El momento de verdad es el Cierre: se muestra un resumen con lo completado y la lista de pendientes. El estado final se comprueba porque el sistema revisa procedimiento, checklist y registro, y el éxito solo aparece si no falta nada.
