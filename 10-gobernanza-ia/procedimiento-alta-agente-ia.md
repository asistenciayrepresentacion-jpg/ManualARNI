# Procedimiento de Alta de un Agente IA

Este documento define el proceso que ARNI Consulting debe seguir antes de crear, probar o activar un nuevo agente IA.

## Objetivo

Evitar que los agentes IA se creen sin propósito claro, sin límites, sin responsable humano o sin reglas de control.

Todo agente debe tener una justificación operativa, permisos definidos, revisión humana y pruebas antes de usarse en procesos reales.

## 1. Cuándo usar este procedimiento

Este procedimiento aplica cuando ARNI quiera crear un agente para:

- Clasificar oportunidades.
- Preparar minutas.
- Generar propuestas.
- Dar seguimiento B2B.
- Evaluar market readiness.
- Analizar importadores o distribuidores.
- Revisar documentos.
- Automatizar procesos.
- Actualizar bases de datos.
- Apoyar tareas comerciales, analíticas u operativas.

## 2. Paso 1: Definir el problema

Antes de crear un agente, ARNI debe responder:

- ¿Qué problema operativo resuelve?
- ¿Qué proceso mejora?
- ¿Qué tarea repetitiva apoya?
- ¿Qué riesgo reduce?
- ¿Qué decisión ayuda a preparar?
- ¿Por qué no basta con una plantilla o prompt simple?

## 3. Paso 2: Definir el objetivo del agente

El objetivo debe ser claro y concreto.

Formato sugerido:

> El agente [nombre] tiene como objetivo apoyar a ARNI en [proceso], mediante [acciones permitidas], para generar [resultado esperado], bajo revisión humana.

Ejemplo:

> El Agente de Seguimiento B2B tiene como objetivo apoyar a ARNI en la clasificación de reuniones y generación de próximos pasos, mediante análisis de minutas, para mejorar la trazabilidad comercial, bajo revisión humana.

## 4. Paso 3: Definir entradas de información

Se debe documentar qué información usará el agente.

Ejemplos:

- Minutas.
- Formularios.
- Registros de Airtable.
- CRM.
- Notas de reunión.
- Fichas de producto.
- Bases de prospectos.
- Playbooks.
- Prompts.
- Documentos internos.

## 5. Paso 4: Definir salidas esperadas

El agente debe tener salidas claras.

Ejemplos:

- Resumen ejecutivo.
- Clasificación A/B/C.
- Próximo paso recomendado.
- Riesgos identificados.
- Información faltante.
- Borrador de correo.
- Borrador de minuta.
- Borrador de propuesta.
- Registro sugerido.
- Acción recomendada.

## 6. Paso 5: Definir permisos

Antes de activarlo, se debe asignar un nivel de permiso.

| Nivel | Descripción |
|---|---|
| Nivel 0 | Solo lectura |
| Nivel 1 | Sugerencias y análisis |
| Nivel 2 | Borradores internos |
| Nivel 3 | Acciones con aprobación humana |
| Nivel 4 | Acción restringida o no permitida |

Todo agente nuevo debe iniciar preferentemente en Nivel 0, 1 o 2.

## 7. Paso 6: Definir acciones prohibidas

Cada agente debe tener límites explícitos.

Ejemplos:

- No enviar correos sin autorización.
- No modificar datos críticos sin aprobación.
- No eliminar registros.
- No prometer resultados.
- No confirmar precios finales.
- No aprobar propuestas.
- No presentar supuestos como hechos.
- No compartir información confidencial.

## 8. Paso 7: Definir responsable humano

Cada agente debe tener un responsable.

El responsable debe revisar:

- Objetivo.
- Permisos.
- Pruebas.
- Errores.
- Cambios.
- Uso operativo.
- Riesgos.

Sin responsable humano, el agente no debe operar.

## 9. Paso 8: Prueba inicial

Antes de usar datos reales, el agente debe probarse con casos simulados o información no sensible.

La prueba debe validar:

- Si entiende instrucciones.
- Si respeta permisos.
- Si diferencia hechos de supuestos.
- Si entrega el formato esperado.
- Si señala riesgos.
- Si pide autorización cuando corresponde.
- Si evita acciones prohibidas.

## 10. Paso 9: Prueba controlada con datos reales

Después de la prueba inicial, puede probarse con datos reales de bajo riesgo.

Condiciones:

- Supervisión humana.
- Sin envío externo automático.
- Sin modificación de datos críticos.
- Registro de errores.
- Revisión de salidas.
- Ajuste de instrucciones.

## 11. Paso 10: Registro en inventario

Todo agente aprobado debe registrarse en:

[Inventario de Agentes IA ARNI](inventario-agentes-ia.md)

Debe incluir:

- Nombre.
- Objetivo.
- Proceso relacionado.
- Herramientas conectadas.
- Nivel de permiso.
- Responsable humano.
- Riesgos principales.
- Estado.

## 12. Paso 11: Activación operativa

Un agente puede activarse solo cuando:

- Tiene objetivo documentado.
- Tiene permisos definidos.
- Tiene responsable humano.
- Fue probado.
- Tiene reglas claras.
- Está registrado en el inventario.
- Tiene protocolo de revisión.
- Tiene bitácora de errores asociada.

## 13. Checklist de alta

| Requisito | Sí / No |
|---|---|
| Problema definido |  |
| Objetivo claro |  |
| Entradas identificadas |  |
| Salidas esperadas definidas |  |
| Permisos asignados |  |
| Acciones prohibidas documentadas |  |
| Responsable humano asignado |  |
| Prueba inicial realizada |  |
| Prueba controlada realizada |  |
| Registrado en inventario |  |
| Reglas de revisión definidas |  |
| Bitácora de errores disponible |  |

## 14. Principio del procedimiento

Un agente IA no debe crearse porque la tecnología lo permite. Debe crearse porque resuelve un problema concreto, bajo reglas claras, con control humano y trazabilidad.
