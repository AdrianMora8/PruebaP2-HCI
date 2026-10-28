# Decisiones de diseño

## Fidelidad y herramienta
- Wireframes: baja fidelidad (cajas grises, texto de relleno) en SVG, para centrar la revisión en estructura y jerarquía y no en estilo.
- Prototipo: media fidelidad en HTML, CSS y JavaScript sin librerías. Se eligió código porque la tarea exige teclado, foco, estados reales y validaciones que una maqueta estática no puede demostrar.
- Dos prototipos, uno por producto: `prototipo/v1/cafeu/` y `prototipo/v1/dashboard/`.

## Estados implementados
| Estado | CaféU | Dashboard |
|---|---|---|
| Normal | Menú, detalle y Mi pedido | Procedimiento, checklist y registro |
| Procesando | «Confirmando…» con botón deshabilitado y estado Pendiente | Guardado automático con indicador «Sin guardar» y «Guardado» |
| Error | «No confirmado» con opción de reintentar sin perder el pedido | Mensaje que indica qué falta, sin perder marcas |
| Éxito | «Pedido recibido» con código, resumen y total | «Sesión cerrada» con datos registrados |

## Teclado y foco
- Todos los controles se operan con Tab, Enter y Escape; el foco es visible (contorno de 3 px).
- Al cambiar de pantalla el foco pasa al encabezado de la pantalla.
- Al quitar un producto se pide confirmación en un diálogo y el foco regresa al elemento siguiente.
- Los cambios de estado se anuncian con regiones `aria-live`.
- Dashboard: el paso actual se indica con texto, forma y `aria-current="step"`, no solo con color.

## Privacidad
- CaféU no solicita ni guarda datos personales; el pedido vive en memoria.
- Dashboard usa códigos de participante con formato P-NN y no admite nombres reales.

## Cambios v1 a v2
Se completa tras la prueba cognitiva en `pruebas/sesion.md`.
