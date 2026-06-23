# Prompts: Trade Mission Support

## 1. Objetivo del documento

Este documento reúne prompts operativos para apoyar el servicio de Trade Mission Support de ARNI Consulting.

Los prompts están diseñados para ayudar a preparar participantes, detectar brechas, perfilar contrapartes, clasificar oportunidades de reunión, redactar mensajes, preparar briefings, generar minutas, estructurar seguimiento y elaborar reportes ejecutivos de misiones comerciales.

La IA puede apoyar el análisis y la redacción, pero toda información debe ser validada por una persona antes de usarse con participantes, contrapartes, aliados, instituciones o clientes.

---

## 2. Prompt para perfilar participante de misión comercial

```text
Actúa como analista de Trade Mission Support para ARNI Consulting.

Con la siguiente información, prepara un perfil de participante para una misión comercial.

Incluye:

1. Empresa.
2. Sector.
3. Producto o servicio.
4. País o ciudad de origen.
5. Mercado objetivo.
6. Objetivo de la misión.
7. Tipo de contraparte buscada.
8. Propuesta de valor.
9. Capacidad comercial u operativa.
10. Materiales disponibles.
11. Información faltante.
12. Brechas de preparación.
13. Riesgos antes de agendar reuniones.
14. Recomendación sobre si está listo para reuniones B2B.

No inventes datos. Si falta información, indícalo claramente.

Información:
[PEGAR INFORMACIÓN]
```

---

## 3. Prompt para detectar brechas de preparación

```text
Actúa como revisor crítico de preparación para misiones comerciales.

Evalúa si los siguientes participantes están preparados para sostener reuniones B2B útiles durante una misión comercial.

Revisa:

1. Claridad del producto o servicio.
2. Material comercial disponible.
3. Pitch o presentación.
4. Objetivo de la misión.
5. Tipo de contraparte buscada.
6. Capacidad de respuesta.
7. Precio o rango de referencia, si aplica.
8. Documentación mínima.
9. Idioma de materiales.
10. Riesgos de llegar mal preparado a reuniones.

Entrega una tabla con:

- Participante.
- Brecha detectada.
- Prioridad: alta, media o baja.
- Riesgo si no se corrige.
- Acción recomendada.

Participantes:
[PEGAR PARTICIPANTES]
```

---

## 4. Prompt para definir perfil ideal de contraparte por participante

```text
Actúa como consultor de desarrollo comercial internacional.

Con base en el perfil de cada participante de la misión, define el perfil ideal de contraparte para reuniones B2B.

Para cada participante entrega:

1. Tipo de contraparte ideal.
2. Canal recomendado.
3. Sector o categoría relevante.
4. Perfil de empresa o institución buscada.
5. Señales de buen fit.
6. Señales de mal fit.
7. Criterios de priorización A/B/C.
8. Preguntas que deben validarse antes de contactar.
9. Contrapartes que deberían evitarse.

Participantes:
[PEGAR PARTICIPANTES]

Mercado objetivo:
[PEGAR MERCADO]
```

---

## 5. Prompt para clasificar contrapartes A/B/C

```text
Actúa como analista de matchmaking para una misión comercial.

Clasifica las siguientes contrapartes como A, B o C según fit sectorial, canal, relevancia, capacidad, cobertura, interés potencial y posibilidad de generar una reunión útil.

Entrega una tabla con:

1. Contraparte.
2. Tipo de contraparte.
3. Participante relacionado.
4. Clasificación A/B/C.
5. Razón de la clasificación.
6. Señales positivas.
7. Riesgos o dudas.
8. Información faltante.
9. Próxima acción recomendada.

Criterios:

- A: alta prioridad, buen fit y alta probabilidad de reunión útil.
- B: prioridad media, posible fit pero requiere validación adicional.
- C: bajo fit, poca evidencia o baja prioridad.

Participantes:
[PEGAR PARTICIPANTES]

Contrapartes:
[PEGAR CONTRAPARTES]
```

---

## 6. Prompt para redactar mensaje de invitación a contraparte

```text
Actúa como consultor B2B de ARNI Consulting.

Redacta un mensaje breve, profesional y cordial para invitar a una contraparte a reunirse con participantes de una misión comercial.

El mensaje debe:

1. Presentar brevemente la misión.
2. Mencionar al organizador o entidad responsable.
3. Explicar el tipo de empresas participantes.
4. Mostrar por qué la reunión puede ser relevante.
5. Solicitar una conversación breve durante las fechas disponibles.
6. Mantener tono ejecutivo.
7. Evitar prometer ventas, contratos, distribución, inversión, exclusividad o resultados comerciales.

Datos de la misión:
[PEGAR DATOS DE LA MISIÓN]

Participante o grupo de participantes:
[PEGAR PARTICIPANTES]

Contraparte:
[PEGAR CONTRAPARTE]

Fechas disponibles:
[PEGAR FECHAS]
```

---

## 7. Prompt para redactar mensaje de seguimiento a contraparte

```text
Actúa como consultor comercial B2B.

Redacta un mensaje de seguimiento para una contraparte invitada a una reunión de misión comercial.

El mensaje debe:

1. Recordar brevemente el mensaje anterior.
2. Reiterar la razón de la reunión.
3. Mencionar el valor potencial de una conversación breve.
4. Preguntar si la persona correcta es otro contacto.
5. Mantener tono profesional, cordial y no insistente.
6. Evitar presionar o prometer resultados.

Contexto del contacto anterior:
[PEGAR CONTEXTO]

Datos de la misión:
[PEGAR MISIÓN]

Contraparte:
[PEGAR CONTRAPARTE]
```

---

## 8. Prompt para preparar briefing previo de reunión

```text
Actúa como analista de Trade Mission Support para ARNI Consulting.

Prepara un briefing previo para una reunión de misión comercial.

El briefing debe incluir:

1. Participante.
2. Contraparte.
3. Tipo de contraparte.
4. Perfil resumido de la contraparte.
5. Razón del posible fit.
6. Objetivo de la reunión.
7. Información que debe presentar el participante.
8. Preguntas sugeridas.
9. Posibles riesgos o puntos sensibles.
10. Señales que deben observarse durante la reunión.
11. Siguiente paso deseado.

Participante:
[PEGAR PARTICIPANTE]

Contraparte:
[PEGAR CONTRAPARTE]

Objetivo de la reunión:
[PEGAR OBJETIVO]
```

---

## 9. Prompt para preparar guion de reunión de misión comercial

```text
Actúa como especialista en reuniones B2B internacionales.

Prepara un guion práctico para una reunión entre un participante de misión comercial y una contraparte potencial.

Incluye:

1. Apertura breve.
2. Presentación del participante.
3. Presentación del producto, servicio o solución.
4. Preguntas para entender a la contraparte.
5. Preguntas sobre fit comercial.
6. Preguntas sobre canal, requisitos o condiciones.
7. Preguntas sobre interés y próximos pasos.
8. Cierre recomendado.
9. Señales que indicarían oportunidad.
10. Señales que indicarían bajo fit.

Contexto:
[PEGAR CONTEXTO]
```

---

## 10. Prompt para estructurar agenda B2B

```text
Actúa como coordinador de agenda B2B para una misión comercial.

Con base en la siguiente información, estructura una agenda B2B ordenada.

Incluye campos para:

1. Participante.
2. Contraparte.
3. Contacto.
4. Cargo.
5. Fecha.
6. Hora.
7. Zona horaria.
8. Modalidad.
9. Ubicación o enlace.
10. Objetivo de reunión.
11. Estado.
12. Responsable.
13. Observaciones.
14. Riesgo o punto sensible.

Información disponible:
[PEGAR INFORMACIÓN]
```

---

## 11. Prompt para revisar calidad de agenda B2B

```text
Actúa como revisor crítico de calidad para una agenda B2B de misión comercial.

Evalúa si la agenda propuesta tiene calidad suficiente antes de presentarla a participantes u organizadores.

Revisa:

1. Si las contrapartes tienen fit real.
2. Si hay equilibrio entre cantidad y calidad.
3. Si las reuniones tienen objetivo claro.
4. Si existen contactos correctos.
5. Si hay información suficiente sobre cada contraparte.
6. Si hay reuniones de bajo valor.
7. Si hay riesgos de falsas expectativas.
8. Si la agenda responde al objetivo de la misión.
9. Qué reuniones deberían priorizarse.
10. Qué reuniones deberían descartarse o validarse más.

Agenda:
[PEGAR AGENDA]
```

---

## 12. Prompt para generar minuta de reunión

```text
Actúa como consultor de ARNI Consulting.

Convierte las siguientes notas de reunión de misión comercial en una minuta clara, breve y accionable.

Incluye:

1. Participante.
2. Contraparte.
3. Fecha.
4. Objetivo de la reunión.
5. Resumen de la conversación.
6. Interés detectado: alto, medio, bajo o nulo.
7. Objeciones o dudas.
8. Información solicitada.
9. Próxima acción.
10. Responsable.
11. Fecha sugerida de seguimiento.
12. Clasificación: informativa, útil, oportunidad potencial o no relevante.
13. Recomendación de seguimiento.

Notas:
[PEGAR NOTAS]
```

---

## 13. Prompt para analizar resultados de reuniones

```text
Actúa como analista comercial de ARNI Consulting.

Analiza los resultados de las siguientes reuniones de una misión comercial.

Entrega:

1. Resumen general.
2. Reuniones informativas.
3. Reuniones útiles.
4. Oportunidades potenciales.
5. Reuniones no relevantes.
6. Principales señales positivas.
7. Principales objeciones.
8. Información solicitada por contrapartes.
9. Seguimientos pendientes.
10. Riesgos o dudas.
11. Recomendaciones.

Resultados:
[PEGAR RESULTADOS]
```

---

## 14. Prompt para identificar oportunidades potenciales

```text
Actúa como consultor senior de desarrollo de oportunidades comerciales.

Revisa las siguientes reuniones de misión comercial y determina cuáles deben considerarse oportunidades potenciales.

Para cada reunión entrega:

1. Participante.
2. Contraparte.
3. Resumen breve.
4. Señales de oportunidad.
5. Evidencia concreta.
6. Riesgos o dudas.
7. Próxima acción.
8. Responsable sugerido.
9. Recomendación: convertir en oportunidad, mantener en seguimiento o descartar.

Regla: no conviertas una reunión en oportunidad si no existe una señal clara de avance.

Reuniones:
[PEGAR REUNIONES]
```

---

## 15. Prompt para preparar plan de seguimiento posterior

```text
Actúa como consultor de seguimiento comercial para una misión comercial.

Con base en los resultados de reuniones, prepara un plan de seguimiento posterior.

Entrega una tabla con:

1. Participante.
2. Contraparte.
3. Resultado de reunión.
4. Acción requerida.
5. Objetivo de la acción.
6. Responsable.
7. Prioridad: alta, media o baja.
8. Plazo sugerido.
9. Información o documento necesario.
10. Riesgo si no se ejecuta.
11. Estado sugerido.

Resultados:
[PEGAR RESULTADOS]
```

---

## 16. Prompt para preparar email posterior a reunión

```text
Actúa como consultor B2B de ARNI Consulting.

Redacta un email breve de seguimiento posterior a una reunión de misión comercial.

El email debe:

1. Agradecer la reunión.
2. Resumir brevemente el punto principal.
3. Enviar o mencionar la información acordada.
4. Confirmar la próxima acción.
5. Mantener tono profesional y cordial.
6. Evitar prometer condiciones comerciales no autorizadas.

Contexto de la reunión:
[PEGAR CONTEXTO]

Información a enviar:
[PEGAR INFORMACIÓN]

Próxima acción:
[PEGAR ACCIÓN]
```

---

## 17. Prompt para preparar reporte final de misión comercial

```text
Actúa como consultor senior de ARNI Consulting.

Prepara un reporte ejecutivo final de Trade Mission Support con base en la siguiente información.

El reporte debe incluir:

1. Resumen ejecutivo.
2. Objetivo de la misión.
3. Mercado objetivo.
4. Sectores participantes.
5. Empresas participantes.
6. Metodología de preparación.
7. Metodología de matchmaking.
8. Agenda ejecutada.
9. Reuniones realizadas.
10. Reuniones útiles.
11. Oportunidades potenciales.
12. Objeciones recurrentes.
13. Seguimientos pendientes.
14. Recomendaciones.
15. Siguientes pasos.
16. Anexos sugeridos: agenda, minutas, matriz de resultados y seguimiento.

Mantén un tono profesional, claro y prudente. No presentes la misión como garantía de ventas, contratos, distribución, inversión o éxito comercial.

Información:
[PEGAR INFORMACIÓN]
```

---

## 18. Prompt para revisión crítica del reporte final

```text
Actúa como revisor crítico de calidad para un reporte final de misión comercial.

Evalúa si el reporte está listo para entregarse al organizador o cliente.

Revisa:

1. Si el objetivo de la misión está claro.
2. Si los participantes están correctamente descritos.
3. Si las reuniones realizadas están documentadas.
4. Si las oportunidades potenciales tienen evidencia.
5. Si las objeciones no fueron omitidas.
6. Si los seguimientos tienen responsables.
7. Si se distingue actividad realizada de resultado comercial.
8. Si hay afirmaciones infladas o no verificadas.
9. Si hay promesas comerciales indebidas.
10. Si las recomendaciones son accionables.
11. Qué debe corregirse antes de entregar.

Reporte:
[PEGAR REPORTE]
```

---

## 19. Prompt para resumir aprendizajes de la misión

```text
Actúa como consultor estratégico de comercio internacional.

Resume los aprendizajes principales de una misión comercial.

Organiza la respuesta en:

1. Aprendizajes sobre el mercado.
2. Aprendizajes sobre los participantes.
3. Aprendizajes sobre contrapartes.
4. Aprendizajes sobre producto o servicio.
5. Aprendizajes sobre precio o canal.
6. Objeciones frecuentes.
7. Oportunidades detectadas.
8. Riesgos para futuras misiones.
9. Recomendaciones para próximas ediciones.

Información:
[PEGAR INFORMACIÓN]
```

---

## 20. Reglas de uso

1. No usar respuestas de IA como información final sin revisión humana.
2. No inventar participantes, contrapartes, contactos, reuniones, resultados o oportunidades.
3. No prometer ventas, contratos, alianzas, distribución, inversión, representación o éxito comercial.
4. No presentar actividad realizada como resultado comercial.
5. No convertir cortesía o conversación informativa en oportunidad falsa.
6. Toda oportunidad debe tener una señal clara de avance.
7. Toda minuta debe reflejar fielmente lo ocurrido.
8. Toda recomendación debe distinguir entre hechos, señales, supuestos y riesgos.
9. Si falta información, debe señalarse explícitamente.
10. La decisión final sobre agenda, mensajes, minutas, oportunidades, seguimiento y reporte corresponde a ARNI Consulting.

---

## 21. Documentos relacionados

| Tipo de documento    | Archivo                                                                                           |
| -------------------- | ------------------------------------------------------------------------------------------------- |
| Servicio             | [Trade Mission Support](../02-servicios-arni/trade-mission-support.md)                            |
| Proceso operativo    | [Proceso Trade Mission Support](../03-procesos-comerciales/proceso-trade-mission-support.md)      |
| Agente IA            | [Agente Trade Mission Support](../05-agentes-ia/agente-trade-mission-support.md)                  |
| Servicio relacionado | [Market Readiness](../02-servicios-arni/market-readiness.md)                                      |
| Servicio relacionado | [Importer Scouting](../02-servicios-arni/importer-scouting.md)                                    |
| Servicio relacionado | [Pilot Validation](../02-servicios-arni/pilot-validation.md)                                      |
| Servicio relacionado | [Business Matchmaking](../02-servicios-arni/business-matchmaking.md)                              |
| Seguimiento B2B      | [Herramienta de Seguimiento B2B](../08-herramientas-calculadoras/herramienta-seguimiento-b2b.md)  |
| Ficha de producto    | [Herramienta de Ficha de Producto](../08-herramientas-calculadoras/herramienta-ficha-producto.md) |

---

## 22. Regla final

Los prompts son herramientas de apoyo para preparar, ejecutar, documentar y dar seguimiento a misiones comerciales.

La responsabilidad final sobre agenda, participantes, contrapartes, minutas, oportunidades, seguimiento, reporte y comunicación al cliente corresponde a ARNI Consulting.
