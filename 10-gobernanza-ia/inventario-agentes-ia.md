# Inventario de Agentes IA ARNI

Este documento registra los agentes IA actuales y futuros de ARNI Consulting, su función, nivel de permiso, procesos relacionados y estado de implementación.

## Objetivo

Mantener control sobre los agentes IA utilizados por ARNI Consulting para evitar duplicidad, pérdida de trazabilidad, uso incorrecto de permisos o automatizaciones sin supervisión.

## 1. Principio general

Todo agente IA debe estar documentado antes de usarse de forma operativa.

Cada agente debe tener:

- Nombre.
- Objetivo.
- Proceso que apoya.
- Herramientas conectadas.
- Nivel de permiso.
- Responsable humano.
- Riesgos principales.
- Estado de implementación.

## 2. Inventario inicial

| Agente | Objetivo | Proceso relacionado | Nivel de permiso | Estado |
|---|---|---|---|---|
| Agente Comercial ARNI | Clasificar oportunidades y sugerir próximos pasos | Seguimiento comercial | Nivel 1-2 | En diseño |
| Agente de Minutas B2B | Preparar minutas y próximos pasos | Reuniones B2B | Nivel 2 | Pendiente |
| Agente de Market Readiness | Evaluar preparación de mercado | Market readiness | Nivel 1-2 | Pendiente |
| Agente de Importer Scouting | Clasificar importadores y distribuidores | Importer scouting | Nivel 1-2 | Pendiente |
| Agente de Propuestas | Preparar borradores de propuestas | Propuesta comercial | Nivel 2 | Pendiente |
| Agente de Seguimiento | Sugerir acciones de follow-up | Seguimiento B2B | Nivel 1-2 | Pendiente |
| Agente de Documentación | Mantener playbooks, prompts y manuales | Manual operativo | Nivel 1-2 | Pendiente |

## 3. Ficha por agente

Cada agente debe documentarse con esta estructura:

### Nombre del agente

[Nombre del agente]

### Objetivo

[Qué problema resuelve o qué proceso apoya]

### Proceso relacionado

[Proceso comercial, operativo o analítico]

### Herramientas conectadas

- [Airtable]
- [n8n]
- [GitHub]
- [CRM]
- [Google Sheets]
- [Otra herramienta]

### Nivel de permiso

[Nivel 0 / Nivel 1 / Nivel 2 / Nivel 3 / Nivel 4]

### Acciones permitidas

- [Acción permitida 1]
- [Acción permitida 2]
- [Acción permitida 3]

### Acciones que requieren autorización

- [Acción restringida 1]
- [Acción restringida 2]
- [Acción restringida 3]

### Acciones prohibidas

- [Acción prohibida 1]
- [Acción prohibida 2]
- [Acción prohibida 3]

### Responsable humano

[Nombre o rol responsable]

### Riesgos principales

- [Riesgo 1]
- [Riesgo 2]
- [Riesgo 3]

### Estado

[En diseño / En prueba / Activo / Pausado / Retirado]

## 4. Niveles de permiso aplicables

| Nivel | Uso permitido |
|---|---|
| Nivel 0 | Solo lectura |
| Nivel 1 | Sugerencias y análisis |
| Nivel 2 | Borradores internos |
| Nivel 3 | Acciones con aprobación humana |
| Nivel 4 | Acción restringida o no permitida |

## 5. Reglas de actualización

El inventario debe actualizarse cuando:

- Se cree un nuevo agente.
- Se cambie el objetivo de un agente.
- Se conecte una nueva herramienta.
- Se modifiquen permisos.
- Se detecte un error relevante.
- Se pause o retire un agente.
- Se cambie el responsable humano.

## 6. Riesgos a vigilar

ARNI debe vigilar:

- Agentes duplicados.
- Agentes sin responsable.
- Agentes con permisos excesivos.
- Agentes sin revisión humana.
- Agentes conectados a datos sensibles sin control.
- Agentes que modifican información crítica.
- Agentes sin bitácora de errores.
- Agentes que generan salidas externas sin autorización.

## 7. Relación con otros documentos

Este inventario se relaciona con:

- Reglas de Uso de IA en ARNI Consulting.
- Matriz de Permisos para Agentes IA.
- Bitácora de Errores e Incidentes IA.
- Protocolo de Revisión Humana para IA.
- Agente Comercial ARNI.

## 8. Principio del inventario

Lo que no está documentado no debe operar como agente formal. Todo agente IA debe tener propósito, límites, permisos y responsable humano.
