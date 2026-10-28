# Requisitos, tarjeta IHC-A-04

| ID | Requisito | Criterio de aceptación |
|---|---|---|
| R1 | El menú muestra los productos agrupados por categoría. | Con 360 px de ancho, cada categoría tiene encabezado y no hay productos sueltos. |
| R2 | Cada acción sobre el pedido (agregar, cambiar cantidad, quitar) da feedback visible. | Tras cada acción aparece un mensaje de estado en menos de 1 segundo. |
| R3 | La pantalla Mi pedido siempre muestra el desglose y el total. | El total coincide con la suma de los subtotales en todo momento. |
| R4 | Los alérgenos de cada producto se muestran en el detalle con texto e ícono. | El detalle lista los alérgenos y no depende solo del color. |
| R5 | Antes de confirmar se muestra un aviso accesible de alérgenos que el usuario debe reconocer. | Confirmar queda bloqueado hasta marcar que leyó el aviso, que se anuncia con role=alert. |
| R6 | Desde el aviso se puede volver a editar sin perder el pedido. | El botón 'Corregir pedido' regresa a Mi pedido con todos los productos y cantidades. |
