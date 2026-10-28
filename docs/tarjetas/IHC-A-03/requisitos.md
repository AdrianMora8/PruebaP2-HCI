# Requisitos, tarjeta IHC-A-03

| ID | Requisito | Criterio de aceptación |
|---|---|---|
| R1 | El menú muestra los productos agrupados por categoría. | Con 360 px de ancho, cada categoría tiene encabezado y no hay productos sueltos. |
| R2 | Cada acción sobre el pedido (agregar, cambiar cantidad, quitar) da feedback visible. | Tras cada acción aparece un mensaje de estado en menos de 1 segundo. |
| R3 | La pantalla Mi pedido siempre muestra el desglose y el total. | El total coincide con la suma de los subtotales en todo momento. |
| R4 | No se pide ni se muestra un número personal, y no se guardan datos sensibles. | La app no usa localStorage con datos personales y el formulario no tiene campo de teléfono ni cédula. |
| R5 | La confirmación muestra un identificador del pedido, el desglose y el estado. | La pantalla final contiene código de pedido, ítems, total y la palabra 'Pedido recibido'. |
| R6 | El estado de pedido recibido es inequívoco y se distingue de haber pulsado el botón. | Mientras no hay respuesta se muestra 'Enviando'; 'Pedido recibido' aparece solo tras la respuesta. |
