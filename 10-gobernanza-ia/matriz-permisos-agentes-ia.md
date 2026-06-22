# Matriz de Permisos para Agentes IA

Este documento define los niveles de permiso que deben tener los agentes IA utilizados por ARNI Consulting.

## Objetivo

Establecer qué acciones puede realizar un agente IA de forma autónoma, cuáles requieren confirmación humana y cuáles están prohibidas.

La matriz busca proteger la información, evitar errores operativos y mantener control humano sobre decisiones críticas.

## 1. Niveles de permiso

| Nivel | Descripción | Ejemplo |
|---|---|---|
| Nivel 0 | Solo lectura | Consultar información o resumir documentos |
| Nivel 1 | Sugerencia | Recomendar próximos pasos o clasificaciones |
| Nivel 2 | Borrador | Preparar mensajes, minutas o propuestas preliminares |
| Nivel 3 | Acción con aprobación | Crear o modificar registros solo con confirmación humana |
| Nivel 4 | Acción restringida | No permitida sin revisión directiva |

## 2. Acciones permitidas sin aprobación previa

El agente puede realizar estas acciones como apoyo interno:

- Resumir información.
- Ordenar notas.
- Preparar minutas preliminares.
- Clasificar oportunidades de forma sugerida.
- Identificar información faltante.
- Detectar riesgos.
- Sugerir próximos pasos.
- Preparar borradores internos.
- Generar listas de pendientes.
- Comparar información documentada.

## 3. Acciones que requieren confirmación humana

El agente debe pedir autorización antes de:

- Crear una oportunidad comercial.
- Actualizar una oportunidad existente.
- Cambiar prioridad de prospectos.
- Cambiar estado de seguimiento.
- Asignar responsable.
- Preparar una propuesta para envío.
- Generar un correo externo.
- Crear registros en CRM, Airtable u otra base operativa.
- Modificar información de clientes.
- Enviar información a terceros.

## 4. Acciones prohibidas

El agente no debe:

- Enviar correos sin autorización.
- Prometer resultados comerciales.
- Confirmar precios finales.
- Confirmar cumplimiento legal, fiscal, regulatorio o aduanal.
- Eliminar información crítica.
- Cambiar datos sensibles sin revisión.
- Compartir información confidencial.
- Inventar datos.
- Presentar supuestos como hechos.
- Tomar decisiones finales por ARNI.
- Aprobar propuestas.
- Cerrar oportunidades comerciales.
- Representar legalmente a ARNI o al cliente.

## 5. Matriz de permisos por acción

| Acción | Permitido | Requiere aprobación | Prohibido |
|---|---:|---:|---:|
| Resumir reunión | Sí | No | No |
| Preparar minuta preliminar | Sí | No | No |
| Sugerir prioridad A/B/C | Sí | No | No |
| Cambiar prioridad definitiva | No | Sí | No |
| Crear oportunidad | No | Sí | No |
| Modificar oportunidad | No | Sí | No |
| Enviar correo externo | No | Sí | No |
| Preparar borrador de propuesta | Sí | No | No |
| Enviar propuesta final | No | Sí | No |
| Eliminar registros | No | No | Sí |
| Confirmar precios finales | No | No | Sí |
| Prometer ventas | No | No | Sí |
| Confirmar cumplimiento regulatorio | No | No | Sí |
| Compartir información confidencial | No | No | Sí |

## 6. Reglas para modificación de datos

Cuando un agente pueda modificar información, debe respetar estas reglas:

- Buscar primero el registro existente.
- Confirmar que el registro corresponde al cliente correcto.
- Mostrar el cambio propuesto.
- Pedir autorización humana.
- Registrar el cambio.
- No modificar campos críticos si no fueron solicitados.
- No duplicar registros.
- No borrar información.

## 7. Campos críticos

Se consideran campos críticos:

- Nombre del cliente.
- Nombre de la empresa.
- Contraparte.
- Ticket estimado.
- Probabilidad de cierre.
- Estado comercial.
- Prioridad.
- Responsable.
- Fecha de seguimiento.
- Honorarios.
- Alcance.
- Entregables.
- Exclusiones.

## 8. Respuesta esperada del agente

Cuando el agente proponga una acción, debe responder con:

1. Acción sugerida.
2. Justificación.
3. Información usada.
4. Supuestos.
5. Riesgos.
6. Campos que modificaría.
7. Confirmación requerida.

## 9. Ejemplo de solicitud de autorización

Antes de actualizar una oportunidad, el agente debe decir:

> Encontré la oportunidad relacionada con [empresa]. Propongo actualizar el campo [campo] de [valor actual] a [nuevo valor].  
> Motivo: [justificación].  
> ¿Autorizas este cambio?

## 10. Principio de la matriz

Un agente IA debe aumentar velocidad y consistencia, pero no debe reducir control. Las acciones críticas deben permanecer bajo autorización humana.
