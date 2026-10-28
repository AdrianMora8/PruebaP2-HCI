# Incidencia sorpresa, tarjeta IHC-A-02: Quitar con teclado

## Evento imprevisto
La persona pulsa Quitar con teclado y el foco desaparece; no sabe qué se eliminó.

## Cambio obligatorio
Anunciar el producto eliminado, devolver el foco a un control pertinente y permitir Deshacer.

## Issue
- Título: Quitar con teclado (incidencia sorpresa)
- Severidad: Alta
- Responsable: Oscar Riofrio (@AdrianMora8)
- Issue en GitHub: #5
- Reproducción: abrir `prototipo/v2/cafeu/index.html` y reproducir el evento; el comportamiento corregido está en `prototipo/v3/cafeu/index.html`.
- Decisión de cierre: cambio implementado en `prototipo/v3/cafeu/`; el Issue se cierra con el PR que sube esa carpeta.

## Requisito nuevo (R7)
Al quitar un producto con teclado se anuncia qué se eliminó, el foco pasa a un control lógico y se ofrece Deshacer.

Criterio de aceptación: Tras confirmar Quitar, un mensaje con aria-live dice «X quitado. Puedes deshacer», el foco va al siguiente Quitar y Deshacer restaura el producto en su posición.

## Flujo y trazabilidad
En la rama de editar, tras «Sí, quitar» se agregó el estado «Producto quitado, Deshacer disponible». Deshacer vuelve a Mi pedido con el producto restaurado.

La fila R7 se agregó a `trazabilidad.md` y a `requisitos.md` de esta tarjeta.

## Prueba antes y después
- **Antes:** v2: al quitar, el foco pasa a un control vecino y se anuncia el cambio, pero no hay forma de deshacerlo. Captura: `evidencias/incidencias/02-antes.png`.
- **Después:** v3: tras quitar Capuchino aparece «Capuchino quitado. Deshacer», el foco pasa al siguiente control Quitar y se anuncia el cambio; Deshacer devuelve el producto a su posición original (café, capuchino, jugo), con total $3,75 y el foco en su botón Quitar. Capturas: `evidencias/incidencias/02-antes.png` y `02-despues.png`. Probado en el navegador.

## Defensa
Tab hasta Quitar, Enter, el diálogo se confirma con Enter en «Sí, quitar» (Escape cancela). El foco pasa al siguiente Quitar y se anuncia el producto eliminado. Tab hasta Deshacer, Enter, o seguir con Tab hasta Confirmar pedido y Enter.
