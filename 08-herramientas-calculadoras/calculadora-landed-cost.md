# Calculadora de Landed Cost Preliminar

Esta herramienta permite estimar el costo total preliminar de un producto puesto en mercado destino.

## Objetivo

Ayudar a ARNI Consulting a evaluar si un producto tiene viabilidad preliminar de precio antes de avanzar a importer scouting, negociación comercial, piloto o propuesta formal.

El landed cost preliminar no sustituye una cotización logística, aduanal o fiscal formal. Su función es ordenar variables, estimar rangos y detectar riesgos de precio.

## Cuándo usar esta herramienta

Debe usarse cuando una empresa quiere:

- Exportar un producto.
- Validar precio viable.
- Comparar precio contra competidores.
- Estimar margen de importador o distribuidor.
- Preparar una conversación con compradores.
- Evaluar si el producto puede competir en mercado destino.
- Definir si conviene avanzar a piloto comercial.

## 1. Variables principales

| Variable | Descripción |
|---|---|
| Precio base | Precio del producto en origen, ex works, FOB u otra referencia |
| Flete internacional | Costo estimado de transporte internacional |
| Seguro | Costo estimado de seguro de carga |
| Arancel | Impuesto de importación aplicable |
| Gastos aduanales | Costos de despacho, manejo o documentación |
| Transporte interno | Costo de mover el producto dentro del mercado destino |
| Margen importador | Margen esperado del importador |
| Margen distribuidor | Margen esperado del distribuidor |
| Margen retail | Margen esperado del punto de venta |
| Impuestos | Impuestos aplicables al consumidor o canal |
| Otros costos | Costos adicionales relevantes |

## 2. Fórmula base

El landed cost preliminar puede estimarse así:

Precio base  
+ Flete internacional  
+ Seguro  
+ Arancel  
+ Gastos aduanales  
+ Transporte interno  
+ Otros costos  
= Costo puesto en destino

Después se agregan márgenes comerciales según el canal.

## 3. Formato de captura

| Campo | Valor |
|---|---:|
| Producto | [Nombre del producto] |
| País de origen | [País] |
| Mercado destino | [País o región] |
| Incoterm base | [EXW / FOB / CIF / DDP / Otro] |
| Precio base por unidad | [Monto] |
| Flete internacional por unidad | [Monto] |
| Seguro por unidad | [Monto] |
| Arancel por unidad | [Monto] |
| Gastos aduanales por unidad | [Monto] |
| Transporte interno por unidad | [Monto] |
| Otros costos por unidad | [Monto] |
| Costo puesto en destino | [Monto] |

## 4. Márgenes comerciales

Después del costo puesto en destino, se deben estimar márgenes por canal.

| Canal | Margen estimado | Precio resultante |
|---|---:|---:|
| Importador | [%] | [Monto] |
| Distribuidor | [%] | [Monto] |
| Retail | [%] | [Monto] |
| Precio final estimado | [% acumulado] | [Monto] |

## 5. Ejemplo simplificado

| Concepto | Costo por unidad |
|---|---:|
| Precio base | 10.00 |
| Flete internacional | 1.20 |
| Seguro | 0.10 |
| Arancel | 0.80 |
| Gastos aduanales | 0.40 |
| Transporte interno | 0.50 |
| Otros costos | 0.00 |
| **Costo puesto en destino** | **13.00** |

Si el importador agrega 25%:

13.00 × 1.25 = 16.25

Si el distribuidor agrega 20%:

16.25 × 1.20 = 19.50

Si retail agrega 35%:

19.50 × 1.35 = 26.33

Precio final estimado:

**26.33**

## 6. Interpretación del resultado

### Precio viable

El precio final estimado se mantiene dentro de un rango competitivo frente a productos comparables.

### Precio presionado

El precio final estimado queda cerca del límite competitivo y requiere revisar márgenes, logística, presentación o canal.

### Precio no viable preliminarmente

El precio final estimado queda muy por encima del benchmark y requiere replantear estrategia antes de avanzar.

## 7. Riesgos a considerar

ARNI debe señalar cuando existan riesgos como:

- Flete demasiado alto por bajo volumen.
- Arancel no confirmado.
- Márgenes de canal no validados.
- Presentación no comparable con competidores.
- Precio base poco competitivo.
- Costos aduanales estimados sin validación.
- Tipo de cambio no considerado.
- Impuestos no confirmados.
- Incoterm mal definido.
- Volumen insuficiente para cotización realista.

## 8. Información mínima requerida

Para usar esta herramienta se necesita:

- Producto.
- Presentación.
- Peso o volumen.
- Precio base.
- País de origen.
- Mercado destino.
- Incoterm de referencia.
- Canal objetivo.
- Competidores comparables.
- Supuestos de margen.

## 9. Uso futuro

Esta calculadora puede convertirse después en:

- Excel.
- Airtable.
- Calculadora web.
- Dashboard de precio viable.
- Herramienta de benchmark.
- Agente IA de análisis preliminar de precio.

## 10. Principio de la herramienta

El landed cost preliminar no busca dar una respuesta definitiva. Busca identificar si el precio tiene sentido antes de invertir más tiempo en compradores, muestras, viajes o negociación comercial.
