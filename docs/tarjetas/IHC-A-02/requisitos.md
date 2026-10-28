# Requisitos, tarjeta IHC-A-02

| ID | Requisito | Criterio de aceptación |
|---|---|---|
| R1 | El menú muestra los productos agrupados por categoría. | Con 360 px de ancho, cada categoría tiene encabezado y no hay productos sueltos. |
| R2 | Cada acción sobre el pedido (agregar, cambiar cantidad, quitar) da feedback visible. | Tras cada acción aparece un mensaje de estado en menos de 1 segundo. |
| R3 | La pantalla Mi pedido siempre muestra el desglose y el total. | El total coincide con la suma de los subtotales en todo momento. |
| R4 | Todo el recorrido se completa solo con Tab, Enter y Escape, con foco visible. | Un participante edita y finaliza el pedido sin usar el ratón, con indicador de foco en cada paso. |
| R5 | Cada control Quitar tiene nombre accesible con el producto y pide confirmación. | El lector de pantalla anuncia 'Quitar café' y aparece un diálogo de confirmación cerrable con Escape. |
| R6 | Tras quitar un producto, el foco pasa a un elemento lógico. | Después de confirmar, el foco queda en el siguiente producto o en el encabezado del pedido. |
| R7 | Al quitar un producto con teclado se anuncia qué se eliminó, el foco pasa a un control lógico y se ofrece Deshacer. | Tras confirmar Quitar, un mensaje con aria-live dice «X quitado. Puedes deshacer», el foco va al siguiente Quitar y Deshacer restaura el producto en su posición. |
