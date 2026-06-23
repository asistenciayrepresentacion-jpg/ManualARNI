# Prompts: Importer Scouting

## 1. Objetivo del documento

Este documento reúne prompts operativos para apoyar el servicio de Importer Scouting de ARNI Consulting.

Los prompts están diseñados para ayudar en la preparación del producto, definición del mercado, búsqueda de prospectos, clasificación A/B/C, mensajes de contacto, seguimiento y preparación de reportes.

La IA puede apoyar el análisis y la redacción, pero toda información debe ser validada por una persona antes de usarse con clientes o prospectos.

---

## 2. Prompt para ordenar ficha de producto

```text
Actúa como analista de inteligencia comercial para ARNI Consulting.

Con la siguiente información del producto, genera una ficha ordenada para iniciar un proceso de Importer Scouting.

Incluye:

1. Nombre del producto.
2. Categoría comercial.
3. Descripción breve.
4. Presentaciones disponibles.
5. Diferenciadores.
6. Capacidad de producción.
7. Certificaciones disponibles.
8. Precio estimado o información faltante sobre precio.
9. Restricciones logísticas o regulatorias conocidas.
10. Información faltante que debe solicitarse al cliente.
11. Riesgos antes de iniciar la búsqueda de importadores.
12. Recomendación sobre si la información es suficiente para avanzar.

Información del producto:
[PEGAR INFORMACIÓN DEL PRODUCTO]
```

---

## 3. Prompt para definir mercado objetivo

```text
Actúa como consultor de comercio internacional para ARNI Consulting.

Con base en el siguiente producto, ayuda a definir el mercado objetivo más adecuado para iniciar un proceso de Importer Scouting.

Analiza:

1. País o región objetivo.
2. Tipo de canal recomendado.
3. Tipo de contraparte ideal.
4. Posibles compradores o distribuidores.
5. Si conviene iniciar con un mercado regional o nacional.
6. Riesgos de entrada.
7. Información adicional necesaria.
8. Recomendación de siguiente paso.

Producto:
[PEGAR INFORMACIÓN DEL PRODUCTO]

Mercado considerado:
[PEGAR PAÍS, REGIÓN O CIUDAD]
```

---

## 4. Prompt para definir perfil ideal de importador

```text
Actúa como especialista en desarrollo de canales internacionales.

Con base en el producto y mercado objetivo, define el perfil ideal de importador, distribuidor o comprador.

Incluye:

1. Tipo de empresa ideal.
2. Canal comercial.
3. Tamaño o capacidad esperada.
4. Categorías que debería manejar.
5. Señales de buen fit comercial.
6. Señales de mal fit comercial.
7. Criterios de priorización A/B/C.
8. Preguntas que ARNI debe validar antes de contactar.

Producto:
[PEGAR PRODUCTO]

Mercado objetivo:
[PEGAR MERCADO]

Objetivo comercial:
[PEGAR OBJETIVO DEL CLIENTE]
```

---

## 5. Prompt para buscar criterios y fuentes

```text
Actúa como analista de inteligencia comercial B2B.

Para el siguiente producto y mercado objetivo, sugiere criterios de búsqueda para identificar posibles importadores o distribuidores.

Entrega:

1. Palabras clave en español.
2. Palabras clave en inglés.
3. Tipos de empresas a buscar.
4. Directorios o fuentes públicas posibles.
5. Ferias o asociaciones sectoriales relevantes.
6. Señales de que una empresa puede ser buen prospecto.
7. Señales de que una empresa debe descartarse.
8. Campos mínimos para registrar cada prospecto.

Producto:
[PEGAR PRODUCTO]

Mercado objetivo:
[PEGAR MERCADO]
```

---

## 6. Prompt para clasificar prospectos A/B/C

```text
Actúa como analista de Importer Scouting para ARNI Consulting.

Clasifica los siguientes prospectos en A, B o C, considerando fit comercial, canal, categoría, cobertura, capacidad y evidencia disponible.

Entrega una tabla con:

1. Empresa.
2. Tipo de contraparte.
3. Clasificación A/B/C.
4. Razón principal de la clasificación.
5. Señales positivas.
6. Riesgos o dudas.
7. Información que falta validar.
8. Próxima acción recomendada.

Criterios:

- A: alta compatibilidad y señales claras de operación activa.
- B: compatibilidad media o información parcial.
- C: baja compatibilidad, poca evidencia o fit débil.

Producto:
[PEGAR PRODUCTO]

Mercado:
[PEGAR MERCADO]

Prospectos:
[PEGAR LISTA DE PROSPECTOS]
```

---

## 7. Prompt para redactar mensaje inicial de contacto

```text
Actúa como consultor B2B de ARNI Consulting.

Redacta un mensaje breve, profesional y claro para contactar a un posible importador o distribuidor.

El mensaje debe:

1. Presentar brevemente a la empresa oferente.
2. Explicar el producto.
3. Mostrar por qué puede ser relevante para el prospecto.
4. Solicitar una conversación exploratoria.
5. Mantener tono ejecutivo y cordial.
6. Evitar promesas de ventas, exclusividad, precios finales o cumplimiento regulatorio.

Datos de la empresa oferente:
[PEGAR DATOS]

Producto:
[PEGAR PRODUCTO]

Prospecto:
[PEGAR DATOS DEL PROSPECTO]

Objetivo del contacto:
[PEGAR OBJETIVO]
```

---

## 8. Prompt para mensaje de seguimiento

```text
Actúa como consultor comercial B2B.

Redacta un mensaje de seguimiento para un prospecto que ya fue contactado previamente.

El mensaje debe:

1. Recordar brevemente el contacto anterior.
2. Reiterar el valor del producto.
3. Invitar a una conversación breve.
4. Preguntar si la persona correcta es otro contacto.
5. Mantener un tono profesional y no insistente.

Contexto del contacto anterior:
[PEGAR CONTEXTO]

Producto:
[PEGAR PRODUCTO]

Prospecto:
[PEGAR PROSPECTO]
```

---

## 9. Prompt para analizar respuesta de prospecto

```text
Actúa como analista comercial de ARNI Consulting.

Analiza la siguiente respuesta recibida de un prospecto y determina el siguiente paso.

Entrega:

1. Resumen de la respuesta.
2. Nivel de interés: alto, medio, bajo o nulo.
3. Señales de oportunidad.
4. Riesgos o dudas.
5. Información que debe enviarse.
6. Próxima acción recomendada.
7. Si debe convertirse en oportunidad o mantenerse como prospecto.
8. Mensaje sugerido de respuesta.

Respuesta del prospecto:
[PEGAR RESPUESTA]

Contexto:
[PEGAR CONTEXTO DEL PRODUCTO Y CONTACTO]
```

---

## 10. Prompt para convertir notas de reunión en oportunidad

```text
Actúa como consultor de desarrollo de oportunidades comerciales.

Con base en las siguientes notas de reunión, determina si existe una oportunidad comercial real.

Entrega:

1. Resumen ejecutivo de la reunión.
2. Interés del prospecto.
3. Necesidad detectada.
4. Producto o solución relacionada.
5. Señales de oportunidad.
6. Riesgos o condiciones pendientes.
7. Próxima acción.
8. Responsable sugerido.
9. Recomendación: convertir en oportunidad, mantener en seguimiento o descartar.

Notas de reunión:
[PEGAR NOTAS]
```

---

## 11. Prompt para preparar reporte ejecutivo

```text
Actúa como consultor senior de ARNI Consulting.

Prepara un reporte ejecutivo de Importer Scouting con base en la siguiente información.

El reporte debe incluir:

1. Resumen ejecutivo.
2. Objetivo del scouting.
3. Producto analizado.
4. Mercado objetivo.
5. Metodología utilizada.
6. Número de prospectos identificados.
7. Clasificación A/B/C.
8. Prospectos prioritarios.
9. Hallazgos relevantes.
10. Riesgos detectados.
11. Recomendaciones.
12. Siguiente paso sugerido.

Información disponible:
[PEGAR INFORMACIÓN]
```

---

## 12. Prompt para revisión crítica del scouting

```text
Actúa como revisor crítico de un proyecto de Importer Scouting.

Evalúa si el trabajo realizado es suficientemente sólido antes de entregarlo al cliente.

Revisa:

1. Si el producto está bien definido.
2. Si el mercado objetivo es claro.
3. Si los prospectos tienen fit real.
4. Si la clasificación A/B/C está justificada.
5. Si hay información inventada o no validada.
6. Si hay riesgos comerciales, regulatorios o logísticos.
7. Si el reporte es útil para tomar decisiones.
8. Qué debe corregirse antes de entregar.

Información del proyecto:
[PEGAR INFORMACIÓN]
```

---

## 13. Reglas de uso

1. No usar respuestas de IA como información final sin revisión humana.
2. No inventar contactos, cargos, emails o teléfonos.
3. No prometer ventas, reuniones, representación ni cierre comercial.
4. No afirmar cumplimiento regulatorio, aduanal o legal sin revisión especializada.
5. Toda clasificación A/B/C debe estar justificada con evidencia.
6. Toda oportunidad debe tener una señal clara de interés.
7. El entregable final debe ser útil, accionable y verificable.

---

## 14. Documentos relacionados

| Tipo de documento | Archivo                                                                                                         |
| ----------------- | --------------------------------------------------------------------------------------------------------------- |
| Servicio          | [Importer Scouting](../02-servicios-arni/importer-scouting.md)                                                  |
| Proceso operativo | [Proceso Importer Scouting](../03-procesos-comerciales/proceso-importer-scouting.md)                            |
| Agente IA         | [Agente Importer Scouting](../05-agentes-ia/agente-importer-scouting.md)                                        |
| Scoring           | [Scoring Importadores y Distribuidores](../08-herramientas-calculadoras/scoring-importadores-distribuidores.md) |
| Seguimiento B2B   | [Herramienta de Seguimiento B2B](../08-herramientas-calculadoras/herramienta-seguimiento-b2b.md)                |
| Ficha de producto | [Herramienta de Ficha de Producto](../08-herramientas-calculadoras/herramienta-ficha-producto.md)               |

---

## 15. Regla final

Los prompts son herramientas de apoyo. La responsabilidad final sobre análisis, contacto, validación, seguimiento y entrega al cliente corresponde a ARNI Consulting.

