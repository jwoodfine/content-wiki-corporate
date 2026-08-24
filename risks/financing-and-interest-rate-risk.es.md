---
schema: foundry-doc-v1
title: "Riesgo de Financiamiento y de Tasa de Interés"
slug: financing-and-interest-rate-risk
category: risks
index_group: financing-structural-and-offering-risk
type: topic
content_type: topic
quality: complete
short_description: "Disponibilidad de financiamiento y riesgo de tasa de interés en los Pagarés Hipotecarios de Primer Grado emitidos tras el arrendamiento bajo el Modelo de Banca Estrecha."
status: active
audience: public
bcsc_class: public-disclosure-safe
language_protocol: TRANSLATE-ES
last_edited: 2026-08-24
editor: pointsav-engineering
paired_with: financing-and-interest-rate-risk.md
---

El [[narrow-bank-financial-model|Modelo Financiero Narrow Bank]] financia la construcción con capital y
posterga el endeudamiento hasta que un edificio se ha estabilizado y ha completado su
arrendamiento. Esta secuencia elimina el riesgo de deuda durante el período de construcción,
pero no elimina el riesgo de financiamiento de la estructura —lo traslada al momento en que se
emiten los [[debt-service-and-financing-structure|Obligaciones con Primera Hipoteca Garantizada]]—. El riesgo de financiamiento y de tasa de
interés aplica desde ese momento en adelante, mientras exista deuda contra una propiedad.

## Disponibilidad de financiamiento en condiciones favorables

Una vez que una propiedad se ha estabilizado y se cumple el convenio del
[[cre-financial-metrics|Razón de Cobertura de Intereses]], se emiten pagarés para financiar la siguiente fase de
construcción. Las condiciones disponibles para esa emisión de deuda —la tasa de interés, la
relación préstamo-valor que el mercado respalde y el paquete de convenios que un prestamista o
comprador de pagarés acepte— dependen de las condiciones del mercado de capitales en el momento
de la emisión, no de las condiciones al momento en que el proyecto se planeó originalmente. No
existe garantía de que el financiamiento esté disponible en los términos supuestos al inicio de
un proyecto, ni en ningún término en particular. Un período de condiciones crediticias
restrictivas, menor apetito de los inversores por deuda inmobiliaria, o un deterioro en la
calidad crediticia percibida del patrocinador o de la clase de activo específica podrían
aumentar el costo de la deuda o reducir el monto disponible. Eso, a su vez, podría retrasar el
ritmo de financiamiento de las fases de construcción subsiguientes.

## Exposición a la tasa de interés tras el arrendamiento

Los pagarés emitidos bajo el modelo están expuestos a las condiciones de tasa de interés
vigentes al momento de la emisión. Si las tasas de interés suben entre el momento en que se
planea una propiedad y el momento en que se emiten sus pagarés, el costo de esa deuda será
mayor al supuesto en proyecciones anteriores, reduciendo el ingreso operativo neto disponible
para distribución después del servicio de la deuda. Debido a que el
[[cre-financial-metrics|Razón de Cobertura de Intereses]] se mide de forma agregada para todo el vehículo contra
las obligaciones de interés reales, costos de interés superiores a lo previsto acercan al
vehículo al piso de 1,20× que restringe el endeudamiento adicional, independientemente de
cualquier cambio en el desempeño operativo de una propiedad individual.

La prohibición del modelo sobre la capitalización de intereses significa que los aumentos en el
costo de interés se reflejan de inmediato en los resultados del período en curso, en lugar de
diferirse al principal del préstamo. Esto brinda transparencia sobre el costo de financiamiento,
pero también significa que un aumento en las tasas de interés vigentes tiene un efecto más
inmediato sobre el ingreso distribuible que bajo una estructura de financiamiento que permita
la capitalización.

## Riesgo de renovación y refinanciamiento

Cuando los pagarés se estructuran con un plazo menor al período de tenencia previsto, la
renovación o el refinanciamiento al vencimiento están sujetos a la misma incertidumbre de
disponibilidad y precio descrita arriba. No existe garantía de que un pagaré pueda renovarse o
refinanciarse en condiciones comparables a la emisión original, ni de que exista financiamiento
alternativo disponible si un prestamista o comprador de pagarés decide no renovar.

## Mitigantes estructurales y sus límites

El convenio de cobertura del servicio de deuda, la prohibición de capitalizar intereses y el
aislamiento de cada pagaré a la propiedad específica que financia son características
estructurales diseñadas para limitar cómo un faltante de financiamiento en un activo puede
afectar al resto del portafolio. Estas características restringen cuánta deuda puede añadirse y
confinan la consecuencia de un incumplimiento al activo específico involucrado. Sin embargo, no
garantizan que el financiamiento esté disponible en condiciones favorables, ni eliminan la
exposición subyacente de cualquier propiedad endeudada al movimiento de las tasas de interés.

## Consulte también

- [[about-risks]] — cómo se organizan las categorías de riesgo en este wiki
- [[narrow-bank-financial-model|Modelo Financiero Narrow Bank]] — la disciplina de financiamiento en dos fases referida arriba
- Índice de Cobertura de Intereses — el convenio que condiciona la emisión de nueva deuda
- [[market-and-property-risk]] — cómo las condiciones de mercado afectan el ingreso que sostiene el servicio de la deuda
