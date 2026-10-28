# Requisitos, tarjeta IHC-A-01

| ID | Requisito | Criterio de aceptación |
|---|---|---|
| R1 | El menú muestra los productos agrupados por categoría. | Con 360 px de ancho, cada categoría tiene encabezado y no hay productos sueltos. |
| R2 | Cada acción sobre el pedido (agregar, cambiar cantidad, quitar) da feedback visible. | Tras cada acción aparece un mensaje de estado en menos de 1 segundo. |
| R3 | La pantalla Mi pedido siempre muestra el desglose y el total. | El total coincide con la suma de los subtotales en todo momento. |
| R4 | El diseño funciona en 360 px y el recorrido de compra se completa en 3 minutos. | Un participante completa agregar dos productos y confirmar en menos de 180 s con pantalla de 360 px. |
| R5 | El total se recalcula al instante al cambiar una cantidad y el cambio se anuncia. | Al pasar de 1 a 2 unidades, el total cambia y una región aria-live anuncia el nuevo importe. |
| R6 | No se puede confirmar con un importe desactualizado. | El botón Confirmar permanece deshabilitado mientras el total se recalcula. |
