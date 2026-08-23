---
schema: foundry-doc-v1
title: "Metodología de Valoración de la Empresa Matriz"
slug: holding-company-valuation-methodology
aliases:
  - topic-holding-company-valuation-methodology
short_description: "El marco de tres métodos — precio/utilidad, rendimiento de utilidades y valor en libros — utilizado para modelar una estimación compuesta del valor razonable por acción de la empresa matriz, distinta de la valoración a nivel de activo o de vehículo."
category: financial-model
index_group: valuation-and-forecasting-methodology
type: reference
content_type: topic
quality: complete
status: active
audience: public
bcsc_class: public-disclosure-safe
language_protocol: TRANSLATE-ES
last_edited: 2026-07-15
editor: pointsav-engineering
paired_with: holding-company-valuation-methodology.md
cites: []
---

La **Metodología de Valoración de la Empresa Matriz** es el marco de tres métodos que Woodfine Capital Projects Inc. (WCP) aplica, en su modelización financiera, para derivar una estimación ilustrativa del valor razonable por acción a nivel de la empresa matriz. Esto es distinto de los métodos de valoración a nivel de activo y de vehículo — [[cre-financial-metrics|ingreso operativo neto, tasa de capitalización, valor de activo neto]] — aplicados dentro de cada vehículo individual de [[direct-hold-framework|Tenencia Directa]]. La metodología combina un método de precio/utilidad, un método de rendimiento de utilidades y un método de valor en libros en una sola cifra compuesta a lo largo de un horizonte de proyección modelado de diez años. Cada cifra que sigue — el múltiplo de 10,72x, el rendimiento del 4,5%, la participación de beneficio económico del 10% y la tasa impositiva estatutaria del 27% — es un parámetro modelado e ilustrativo utilizado en un ejercicio de proyección; ninguna es una métrica actual divulgada, una proyección de resultados reales, ni una garantía de ningún tipo.

## El método de precio/utilidad (P/E)

Bajo el método de precio/utilidad, las utilidades anuales proyectadas de WCP para un año determinado de la proyección se multiplican por un múltiplo fijo de precio/utilidad — 10,72x en este modelo — para derivar un valor de capital implícito por acción para ese año. El múltiplo se mantiene constante a lo largo de la proyección de diez años, de modo que el movimiento del valor implícito de un período a otro proviene enteramente de la línea de utilidades y no de una revaloración del múltiplo en sí. El método refleja una convención estándar del mercado accionario: el valor de una empresa matriz se trata como una función de su flujo de utilidades, capitalizado al múltiplo que el modelo supone que el mercado estaría dispuesto a pagar por él.

## El método de rendimiento de utilidades

El método de rendimiento de utilidades invierte la misma línea de utilidades frente a una tasa objetivo fija — 4,5% en este modelo — dividiendo las utilidades anuales proyectadas entre esa tasa para producir un segundo valor implícito por acción, independiente del primero. Aplicado junto con el método de precio/utilidad, y no en su lugar, el cálculo del rendimiento de utilidades funciona como una verificación cruzada: dado que un múltiplo de precio/utilidad y un rendimiento de utilidades son expresiones recíprocas de la misma relación, cualquier divergencia significativa entre los dos valores implícitos en un año determinado de la proyección señala que el múltiplo modelado y el rendimiento modelado no son internamente consistentes entre sí para ese período.

## El método de valor en libros y la construcción del VAN de beneficio económico

El método de valor en libros construye un valor por acción a partir del balance general y no del estado de resultados. El valor en libros se construye como el flujo de caja libre acumulado — ingresos de financiamiento más utilidades retenidas, acumulados a lo largo de la proyección — más la participación proporcional de beneficio económico de WCP en el valor de activo neto (VAN) proyectado de cada vehículo afiliado de Tenencia Directa en la cartera. Esa participación de beneficio económico está fija en 10% en este modelo. La construcción del VAN aplica la misma cifra del 10% al VAN proyectado individual de cada vehículo afiliado, y luego agrega las participaciones resultantes a través de toda la cartera de vehículos antes de sumar el total al flujo de caja libre acumulado de WCP. La cifra combinada se divide entre las acciones en circulación para producir un resultado de valor en libros por acción.

## El compuesto de valor razonable

El compuesto de valor razonable promedia los tres resultados por acción — precio/utilidad, rendimiento de utilidades y valor en libros — en una sola estimación combinada del valor razonable por acción para cada año de la proyección de diez años. Promediar tres métodos con determinantes subyacentes distintos — un múltiplo de mercado, un rendimiento objetivo y una construcción de balance general que incorpora una participación de VAN a nivel de toda la cartera — busca reducir la sensibilidad del modelo a los supuestos de un solo método. El compuesto no afirma que un único método por sí solo sea la medida correcta del valor; es un ejercicio de triangulación aplicado a cifras modeladas y prospectivas.

## Modelización de ingresos y del estado de resultados

La cifra de utilidades que alimenta los tres métodos de valoración es, a su vez, producida por un estado de resultados modelado de la empresa matriz a diez años. Los ingresos se construyen a partir de tres líneas: ingresos por honorarios de asesoría obtenidos en toda la cartera de vehículos afiliados de Tenencia Directa, distribuciones recibidas de esos vehículos, y el reembolso de costos de oferta. La línea de honorarios de asesoría se modela por vehículo — el flujo de honorarios de cada vehículo se escala mediante un factor relativo de tamaño y se incorpora gradualmente a partir del año de lanzamiento propio de ese vehículo — y luego se agrega en una sola cifra consolidada de ingresos por honorarios a nivel de la empresa matriz.

Frente a esos ingresos, el modelo compensa los gastos operativos, incluidos los costos generales y administrativos multijurisdiccionales y un acuerdo de compensación para un promotor o consultor afiliado. Este artículo no especifica ni cuantifica dicho acuerdo. Luego se aplica una tasa impositiva estatutaria fija — 27% en este modelo — a la cifra resultante antes de impuestos para llegar a las utilidades netas modeladas, que a su vez determinan las métricas por acción utilizadas en cada uno de los tres métodos de valoración anteriores.

## Véase también

- [[narrow-bank-financial-model|Modelo Financiero Narrow Bank]] — la disciplina de financiamiento que rige los vehículos afiliados de Tenencia Directa cuyo VAN alimenta el método de valor en libros
- [[cre-financial-metrics|Métricas Financieras de Bienes Raíces Comerciales]] — las métricas de valoración a nivel de activo y de vehículo (VAN, tasa de capitalización) sobre las que se construye esta metodología a nivel de empresa matriz, sin reemplazarlas
- [[non-ifrs-measures-explained|Medidas No-NIIF Explicadas]] — el tratamiento de divulgación aplicable a las medidas financieras complementarias no-NIIF
- [[direct-hold-framework|Marco de Tenencia Directa]] — la estructura de propiedad a nivel de vehículo cuya participación de beneficio económico se agrega en el método de valor en libros

## En resumen

La valoración de la empresa matriz en WCP se modela a través de tres métodos independientes — precio/utilidad, rendimiento de utilidades y valor en libros con su construcción de VAN de beneficio económico — promediados en un solo compuesto de valor razonable a lo largo de un horizonte de diez años. Los tres métodos se basan en la misma cifra de utilidades subyacente, construida a su vez a partir de una línea de ingresos por honorarios de asesoría modelada en toda la cartera de vehículos afiliados, neta de gastos operativos y de una tasa impositiva estatutaria fija. Cada insumo — el múltiplo de 10,72x, el rendimiento del 4,5%, la participación de beneficio económico del 10% y la tasa impositiva del 27% — es un parámetro modelado e ilustrativo, no una métrica divulgada ni una proyección de resultados reales.
