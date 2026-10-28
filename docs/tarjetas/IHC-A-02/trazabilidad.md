# Trazabilidad, tarjeta IHC-A-02

| Requisito | Flujo | Pantalla | Componente | Wireframe |
|---|---|---|---|---|
| R1 | Rama principal | Menú | Tarjeta de producto | Inicio |
| R2 | Rama de editar/error | Detalle | Selector de cantidad | Acción |
| R3 | Rama principal | Mi pedido | Botón de acción | Error |
| R4 | Rama principal | Confirmación | Región de estado (aria-live) | Confirmación |
| R5 | Rama de editar/error | Confirmación | Diálogo de confirmación | Inicio |
| R6 | Rama de editar/error | Confirmación | Tarjeta de producto | Acción |
| R7 | Rama de editar/error (incidencia) | Mi pedido | Diálogo de confirmación | Acción |

**Flujo:** Inicio → Menú → Detalle → Agregar → Mi pedido → Confirmar → Confirmación. Rama de edición/error: Mi pedido → Editar o Quitar → Mi pedido; Confirmar con error → mensaje → volver a Mi pedido.


**Cambio por incidencia:** En la rama de editar, tras «Sí, quitar» se agregó el estado «Producto quitado, Deshacer disponible». Deshacer vuelve a Mi pedido con el producto restaurado.
