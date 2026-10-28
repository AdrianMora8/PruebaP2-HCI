# Requisitos, tarjeta IHC-A-06

| ID | Requisito | Criterio de aceptación |
|---|---|---|
| R1 | El menú muestra los productos agrupados por categoría. | Con 360 px de ancho, cada categoría tiene encabezado y no hay productos sueltos. |
| R2 | Cada acción sobre el pedido (agregar, cambiar cantidad, quitar) da feedback visible. | Tras cada acción aparece un mensaje de estado en menos de 1 segundo. |
| R3 | La pantalla Mi pedido siempre muestra el desglose y el total. | El total coincide con la suma de los subtotales en todo momento. |
| R4 | La confirmación tiene tres estados distintos: pendiente, confirmado y no confirmado. | Cada estado tiene texto, ícono y color propio, y rol semántico distinto. |
| R5 | Mientras está pendiente no se muestra éxito. | En estado pendiente el mensaje es 'Confirmando…' y no aparece 'Pedido recibido'. |
| R6 | Una segunda pulsación no genera una confirmación duplicada. | Tras la primera pulsación el botón se deshabilita; dos clics rápidos generan un único pedido. |
