# Diagnóstico, tarjeta IHC-A-02 (CaféU)

**Persona usuaria:** Estudiante que utiliza teclado por una lesión temporal

**Tarea crítica:** Editar un pedido y finalizar sin ratón

**Restricción:** Tabulación, Enter y Escape como medios de interacción

**Fallo identificado:** El botón Quitar no tiene nombre accesible ni confirmación

## Touchpoints

| # | Touchpoint | Emoción (1 a 5) | Nota | Tipo |
|---|---|---|---|---|
| 1 | Abrir CaféU desde el celular | 3 | Pantalla Inicio, sin demora visible | Estimado |
| 2 | Explorar el menú por categorías | 4 | Agrupación clara de productos | Estimado |
| 3 | Ver el detalle de un producto | 3 | Ingredientes y precio en una sola vista | Estimado |
| 4 | Agregar al pedido | 4 | Feedback inmediato al agregar | Estimado |
| 5 | Revisar Mi pedido y el total | 2 | Aquí aparece la duda sobre el importe | Estimado |
| 6 | Editar o quitar un producto | 2 | Rama de edición poco visible | Estimado |
| 7 | Confirmar el pedido | 2 | Momento de verdad 1 | Estimado |
| 8 | Ver la confirmación y retirar | 4 | Momento de verdad 2 | Estimado |

## Momentos de verdad

- **Confirmar el pedido.** El usuario decide pagar y necesita seguridad de que el importe es correcto.
- **Ver la pantalla de confirmación.** El usuario necesita saber con certeza que su pedido fue recibido.

## Fallos priorizados

| # | Fallo | Principio | Severidad |
|---|---|---|---|
| 1 | El botón Quitar no tiene nombre accesible ni confirmación | Nielsen 5, prevención de errores; accesibilidad (nombre accesible) | Alta |
| 2 | Sin estado de procesamiento al confirmar | Nielsen 1, visibilidad del estado | Media |
| 3 | Productos del menú sin agrupación por categoría | Gestalt, proximidad y similitud | Baja |

## Observado y estimado

Lo registrado antes de la prueba con participante es estimación basada en la revisión de la interfaz de referencia y en el perfil de la persona usuaria. Lo observado se completa en `pruebas/sesion.md`.

## Curva emocional inicial

Se construye con las emociones de la tabla de touchpoints (eje X: touchpoints; eje Y: 1 a 5). Ver `evidencias/curva-antes`.
