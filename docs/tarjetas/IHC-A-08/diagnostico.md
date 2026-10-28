# Diagnóstico, tarjeta IHC-A-08 (Dashboard UX)

**Persona usuaria:** Docente evaluador que prepara sesión contrarreloj

**Tarea crítica:** Completar datos de prueba y checklist

**Restricción:** El procedimiento debe quedar claro antes de iniciar

**Fallo identificado:** Las casillas parecen guardadas pero se pierden al cambiar de paso

## Touchpoints

| # | Touchpoint | Emoción (1 a 5) | Nota | Tipo |
|---|---|---|---|---|
| 1 | Abrir el panel de la prueba | 3 | Primera vista del Dashboard | Estimado |
| 2 | Leer el procedimiento antes de iniciar | 3 | Instrucciones previas | Estimado |
| 3 | Configurar el checklist | 3 | Casillas en cuadrícula | Estimado |
| 4 | Avanzar de etapa con el Stepper | 2 | Riesgo de saltar pasos | Estimado |
| 5 | Registrar datos y observaciones | 2 | Formularios largos | Estimado |
| 6 | Revisar el progreso | 3 | Resumen por etapa | Estimado |
| 7 | Cerrar la sesión | 2 | Momento de verdad 2 | Estimado |

## Momentos de verdad

- **Avanzar a la siguiente etapa.** La persona confía en que el sistema valida que la etapa anterior está completa.
- **Cerrar la sesión de prueba.** La persona necesita comprobar que todo quedó registrado antes de terminar.

## Fallos priorizados

| # | Fallo | Principio | Severidad |
|---|---|---|---|
| 1 | Las casillas parecen guardadas pero se pierden al cambiar de paso | Nielsen 1, visibilidad del estado; consistencia | Alta |
| 2 | Sin indicador global de progreso | Nielsen 1, visibilidad del estado | Media |
| 3 | Checklist en cuadrícula sin agrupar por etapa | Gestalt, proximidad y carga cognitiva | Baja |

## Observado y estimado

Lo registrado antes de la prueba con participante es estimación basada en la revisión de la interfaz de referencia y en el perfil de la persona usuaria. Lo observado se completa en `pruebas/sesion.md`.

## Curva emocional inicial

Se construye con las emociones de la tabla de touchpoints (eje X: touchpoints; eje Y: 1 a 5). Ver `evidencias/curva-antes`.
