# Bitácora de Errores e Incidentes IA

Este documento define cómo ARNI Consulting debe registrar, analizar y corregir errores relacionados con inteligencia artificial, agentes, automatizaciones o flujos asistidos por IA.

## Objetivo

Mantener trazabilidad sobre errores, incidentes, respuestas dudosas o acciones incorrectas generadas por IA.

La bitácora permite aprender de los errores, reducir riesgos y mejorar las reglas de operación de agentes y automatizaciones.

## 1. Cuándo registrar un error

Debe registrarse un evento cuando la IA:

- Invente información.
- Confunda clientes, empresas o proyectos.
- Clasifique mal una oportunidad.
- Sugiera una acción incorrecta.
- Modifique información equivocada.
- Genere una propuesta con alcance excesivo.
- Omita exclusiones importantes.
- Use información desactualizada.
- Presente supuestos como hechos.
- Genere un mensaje externo con riesgo comercial.
- Produzca una respuesta que requiera corrección humana relevante.

## 2. Tipos de incidentes

| Tipo de incidente | Descripción |
|---|---|
| Error de información | La IA generó información incorrecta o no confirmada |
| Error de clasificación | La IA asignó prioridad, estado o categoría equivocada |
| Error de alcance | La IA propuso actividades o entregables fuera de alcance |
| Error de cliente | La IA mezcló información de clientes o proyectos |
| Error de modificación | La IA intentó cambiar un dato incorrecto |
| Error de comunicación | La IA generó un mensaje externo inadecuado |
| Error de fuente | La IA usó información no confiable o desactualizada |
| Error de permisos | La IA intentó hacer algo sin autorización |

## 3. Formato de registro

| Campo | Descripción |
|---|---|
| Fecha | Día del incidente |
| Herramienta o agente | Nombre del agente, flujo o herramienta |
| Proceso afectado | Propuesta, seguimiento, scouting, CRM, Airtable, etc. |
| Tipo de incidente | Categoría del error |
| Descripción del error | Qué ocurrió |
| Información afectada | Cliente, oportunidad, archivo o dato involucrado |
| Riesgo generado | Bajo / Medio / Alto |
| Acción correctiva | Qué se hizo para corregir |
| Responsable de revisión | Persona que revisó |
| Estado | Abierto / Corregido / En observación / Cerrado |
| Lección aprendida | Qué debe cambiarse para evitar repetición |

## 4. Niveles de riesgo

### Riesgo bajo

Error menor sin impacto externo.

Ejemplos:

- Redacción poco clara.
- Formato incorrecto.
- Clasificación preliminar discutible.
- Falta de detalle.

### Riesgo medio

Error que puede afectar seguimiento, análisis o decisión interna.

Ejemplos:

- Prioridad mal asignada.
- Información incompleta.
- Supuesto presentado con demasiada certeza.
- Próximo paso incorrecto.

### Riesgo alto

Error que puede afectar cliente, reputación, datos sensibles o decisión comercial.

Ejemplos:

- Información confidencial mal usada.
- Propuesta con promesas indebidas.
- Modificación de datos críticos sin autorización.
- Mezcla de información entre clientes.
- Envío externo sin revisión.

## 5. Acciones correctivas posibles

Según el caso, ARNI puede:

- Corregir la información.
- Revertir el cambio.
- Actualizar reglas del agente.
- Ajustar el prompt.
- Agregar validación humana.
- Restringir permisos.
- Documentar una nueva regla.
- Capacitar al equipo.
- Cerrar el flujo temporalmente.
- Revisar la fuente de información.

## 6. Ejemplo de registro

| Campo | Ejemplo |
|---|---|
| Fecha | 2026-06-22 |
| Herramienta o agente | Agente Comercial ARNI |
| Proceso afectado | Seguimiento B2B |
| Tipo de incidente | Error de clasificación |
| Descripción del error | Clasificó una oportunidad como A sin decisor identificado |
| Información afectada | Empresa prospecto X |
| Riesgo generado | Medio |
| Acción correctiva | Se ajustó regla: no clasificar como A sin siguiente paso claro |
| Responsable de revisión | [Nombre] |
| Estado | Corregido |
| Lección aprendida | La prioridad A requiere decisor o acción concreta |

## 7. Reglas de uso

- Todo error relevante debe registrarse.
- No se debe ocultar un error operativo.
- La bitácora debe enfocarse en mejora, no en culpa.
- Los errores repetidos deben convertirse en nuevas reglas.
- Los errores de alto riesgo deben revisarse con responsable directivo.
- Toda modificación a agentes debe documentarse.

## 8. Relación con otros documentos

Esta bitácora se relaciona con:

- Reglas de Uso de IA en ARNI Consulting.
- Matriz de Permisos para Agentes IA.
- Playbook Automatización e IA Aplicada.
- Agente Comercial ARNI.
- Prompts Base ARNI Consulting.

## 9. Principio de la bitácora

Un error registrado mejora el sistema. Un error no registrado se puede repetir. La gobernanza IA requiere trazabilidad, corrección y aprendizaje continuo.
