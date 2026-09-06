---
schema: foundry-doc-v1
title: "Servicio de Deuda y Estructura de Financiamiento"
slug: debt-service-and-financing-structure
category: financial-model
index_group: financing-discipline
type: topic
content_type: topic
quality: complete
short_description: "Convenciones generales del financiamiento hipotecario comercial — límites de relación préstamo-valor, amortización, riesgo de tasa y de refinanciamiento — y su interacción con el convenio de la RCI; no el financiamiento con obligaciones previsto para las Direct-Hold Solutions."
status: active
audience: public
bcsc_class: public-disclosure-safe
language_protocol: TRANSLATE-ES
last_edited: 2026-09-06
editor: woodfine-editorial
paired_with: debt-service-and-financing-structure.md
---

La deuda hipotecaria externa no es la forma en que se financian las Direct-Hold Solutions. Este
artículo describe las convenciones generales del financiamiento hipotecario comercial — el límite
de relación préstamo-valor que fija el prestamista, la amortización y los períodos de solo interés,
la exposición a la tasa de interés y el riesgo de refinanciamiento — y cómo cada una interactúa con
el piso de 1,20× de la [[cre-financial-metrics|Razón de Cobertura de Intereses]] (RCI), establecido
como convenio en el acuerdo rector de cada [[limited-partnership-structure|sociedad en comandita]]
de tenencia directa. Es contexto de mercado, no una descripción de la estructura de capital de los
vehículos. Para eso — construcción sin apalancamiento financiada con capital y, después,
Obligaciones con Primera Hipoteca Garantizada previstas para ser emitidas por el propio vehículo y
no tomadas de un prestamista externo — véase
[[narrow-bank-financial-model|el Modelo Financiero Narrow Bank]].

## Puntos clave

- En una hipoteca comercial convencional, la deuda está garantizada por una propiedad específica;
  el prestamista no tiene recurso sobre otros activos ni sobre el capital de una sociedad matriz,
  salvo garantías específicas.
- El tamaño de la hipoteca está restringido por el límite de relación préstamo-valor del
  prestamista. El piso de la RCI de 1,20× es una restricción separada e independiente, establecida
  como convenio en el acuerdo rector de la sociedad y no impuesta por un prestamista.
- La deuda a tasa fija reduce la volatilidad del estado de resultados durante el plazo fijo,
  pero crea exposición al refinanciamiento al vencimiento; la deuda a tasa flotante crea
  sensibilidad inmediata del resultado a los movimientos de la tasa de referencia.

## Restricción de relación préstamo-valor

Los prestamistas hipotecarios comerciales establecen un préstamo máximo como porcentaje del
valor tasado de la propiedad. Bajo un límite de RPV del 65%, por ejemplo, la hipoteca cubre
el 65% del valor tasado; el 35% restante debe financiarse con capital propio del prestatario,
cualquiera que sea el monto tasado de la propiedad. La relación préstamo-valor se evalúa en
el origen y puede volver a probarse en fechas de refinanciamiento o de revisión de convenios.

## Amortización y períodos de solo interés

Las hipotecas comerciales se estructuran con distintas combinaciones de amortización de
principal y períodos de solo interés. Un préstamo de solo interés no exige pago de principal
durante su plazo; al vencimiento, se adeuda la totalidad del principal original (un pago
"bullet"). Un préstamo amortizable exige pagos de principal programados durante el plazo, lo
que reduce el saldo pendiente con el tiempo y genera capital en la propiedad mediante la
amortización de la deuda.

Los períodos de solo interés — habituales en bienes raíces comerciales al momento de originar
la hipoteca — reducen la salida de efectivo anual durante las fases de estabilización o de
arrendamiento inicial, cuando la ocupación aún se está consolidando y el ION puede no sustentar
todavía un servicio de deuda amortizable. Cuando la propiedad alcanza la ocupación estabilizada,
los términos de la hipoteca típicamente pasan a ser amortizables; el mayor requerimiento de
efectivo queda cubierto por el ION estabilizado más alto.

El cálculo de la RCI utiliza las obligaciones totales de interés, no el servicio total de deuda
(principal más interés). Una hipoteca de solo interés con un costo de interés determinado produce
el mismo resultado en la prueba de RCI que una hipoteca amortizable con la misma tasa de interés y
un principal pendiente menor; la porción de pago de principal de una hipoteca totalmente
amortizable no se incluye en el denominador de la prueba. La distinción importa dondequiera que se
aplique el convenio, sea cual sea el instrumento evaluado.

## Riesgo de tasa de interés

La tasa de interés en una hipoteca comercial puede ser fija durante el plazo o flotante,
basada en una tasa de referencia más un diferencial de crédito. Las hipotecas a tasa fija protegen
al prestatario de aumentos en las tasas durante el plazo y fijan un costo de servicio de deuda
predecible. Al vencimiento, la hipoteca debe refinanciarse a la tasa de mercado vigente, que puede
ser materialmente más alta o más baja que la original.

Las hipotecas a tasa flotante exponen al prestatario a cambios inmediatos en el costo del servicio
de deuda a medida que se mueven las tasas de referencia. Un aumento en las tasas de referencia
incrementa el gasto de interés y reduce la RCI. Donde aplica un convenio de RCI, un aumento
suficientemente grande puede restringir la capacidad de emitir deuda garantizada adicional al
acercar la cobertura al piso de 1,20×.

## Riesgo de refinanciamiento

Al vencimiento de la hipoteca, el prestatario debe pagar el principal pendiente o refinanciar con
una nueva hipoteca. El riesgo de refinanciamiento surge cuando las condiciones crediticias, los
valores de las propiedades o el apetito de los prestamistas se han deteriorado desde el
financiamiento original: el monto hipotecario disponible puede ser menor — por compresión de la
RPV o por deterioro de la cobertura — y la tasa de interés puede ser más alta.

Cuando el producto del refinanciamiento no alcanza para pagar el principal que vence, un
prestatario financiado convencionalmente debe cubrir la diferencia con otra fuente: capital
adicional de sus patrocinadores, o la venta del activo. Esa exposición pertenece al financiamiento
hipotecario externo, no a los vehículos de tenencia directa: bajo el
[[narrow-bank-financial-model|Modelo Financiero Narrow Bank]], no puede exigirse a los tenedores de
unidades aportar capital adicional para cubrir obligaciones de deuda.

Este riesgo de refinanciamiento es una característica estructural del financiamiento
hipotecario a plazo limitado y no es específico de las estructuras de tenencia directa; se
aplica a todos los activos inmobiliarios financiados comercialmente.

## Consulte también

- [[narrow-bank-financial-model]] — el financiamiento propio en dos fases previsto para las
  Direct-Hold Solutions, que no recurre a prestamistas hipotecarios externos
- [[distribution-declaration-mechanics]] — cómo la restricción de la RCI interactúa con
  el proceso de declaración de distribuciones
- [[asset-vehicle-isolation]] — cómo los acreedores hipotecarios están limitados al activo
  de la SC en la que prestan
