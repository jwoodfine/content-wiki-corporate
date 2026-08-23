---
schema: foundry-doc-v1
title: "Acceso de Inversores"
slug: investor-access
aliases:
  - topic-investor-access
short_description: "Cómo los inversores en activos de Tenencia Directa acceden a los datos de posición, informes financieros y registros del libro a través del portal de inversores operado por MCorp."
category: company
index_group: technology-and-investor-services
type: reference
content_type: topic
quality: complete
status: archived
archived: 2026-08-24
archived_reason: "Retirado — el concepto de 'portal de inversores operado por MCorp' no se remonta a ninguno de los ~32 archivos fuente reales. Cada referencia a 'portal' encontrada en el material fuente real describe un portal gubernamental de presentación regulatoria (SEDAR+, CNMV, STIV-2 de la CNBV), el concepto opuesto. Revisión de integridad Track-B, 2026-08-24."
superseded_by: none
audience: public
bcsc_class: public-disclosure-safe
language_protocol: TRANSLATE-ES
last_edited: 2026-08-24
editor: pointsav-engineering
paired_with: investor-access.md
cites: []
---

Un inversor en un activo de [[direct-hold-framework|Tenencia Directa]] posee una posición en una propiedad específica y nombrada. El acceso a los datos de posición, informes financieros y registros de transacciones se proporciona a través del portal de inversores operado por MCorp. El portal refleja la posición del inversor en el registro —porcentaje de capital, historial de eventos financieros y registros de transferencias— para cada activo en el que mantiene una posición, con el propio registro mantenido bajo la autoridad del órgano de gobierno del vehículo (en Canadá, el socio general, Woodfine Professional Centres Inc.). La posición se estructura en [[investment-units|unidades de inversión]] en el activo nombrado.

## Puntos clave

- Los datos de posición, los informes financieros y los registros de transferencias se presentan por activo — el portal no agrega varias posiciones de Tenencia Directa, porque cada activo es su propia unidad financiera y legal distinta.
- Las divulgaciones financieras que desencadenan la obligación de reportar cambios materiales en virtud del NI 51-102 se presentan en SEDAR+ además de a través del portal de inversores, cumpliendo con las obligaciones de divulgación continua.
- MCorp opera el portal de inversores y controla la habilitación y revocación del acceso como tarea delegada; PointSav mantiene la infraestructura del portal — la división de responsabilidades corresponde al modelo más amplio de proveedor-cliente. La custodia del registro y el registro de transferencias corresponden al propio órgano de gobierno del vehículo, no a MCorp.

## Datos de posición

Los datos de posición representan el capital fraccionario actual del inversor en el activo nombrado: el porcentaje mantenido, la fecha de adquisición, el coste de adquisición registrado en el libro y el historial acumulado de eventos financieros desde la adquisición. Los datos de posición son específicos del activo; no se agregan entre múltiples posiciones de Tenencia Directa. Cada activo es su propia unidad financiera y legal.

## Informes financieros

MCorp proporciona a los inversores informes financieros periódicos para cada activo en el que mantienen una posición, como tarea delegada por el órgano de gobierno del vehículo. Los informes abarcan el rendimiento financiero a nivel de activo: tasa de ocupación, ingresos por arrendamiento, servicio de deuda, distribuciones e ingreso operativo neto. Los informes no se agregan entre activos; cada informe corresponde a un único activo y a la posición de un único inversor en ese activo.

La frecuencia y el formato de los informes financieros se rigen por los estándares de comunicación con inversores de MCorp, coherentes con las [[about-continuous-disclosure|obligaciones de divulgación]] aplicables en virtud del NI 51-102. Cuando los eventos financieros desencadenan la obligación de reportar cambios materiales, esa divulgación se realiza también a través de SEDAR+ y del portal.

## Registros de transferencias

Cuando un inversor transfiere capital a una contraparte elegible en virtud del [[equity-transfer-model|Modelo de Transferencia de Capital]], el registro documenta la transacción: marca de tiempo, identidad de la parte cedente, identidad de la parte adquirente y porcentaje transferido. El inversor cedente recibe confirmación de la transacción completada. El inversor adquirente recibe un estado de posición actualizado que refleja el nuevo porcentaje de capital.

El órgano de gobierno del vehículo — en Canadá, el socio general — registra la transferencia y está obligado contractualmente a admitir a un cesionario elegible, negándose únicamente por una lista breve y enumerada de motivos (una opinión de derecho de valores, o declaraciones de elegibilidad falsas); fuera de eso no ejerce discrecionalidad de aprobación ni intermedia transferencias entre partes privadas. MCorp no tiene ningún rol en este paso.

## Transferencia extrabursátil

Ningún vehículo de Tenencia Directa opera un mercado secundario formal, un libro de órdenes cruzadas ni una facilidad de recompra — véase [[redemption-elimination|Eliminación de Redención]] para el fundamento estructural. Los inversores que buscan liquidez identifican de forma independiente una contraparte elegible. La entidad corporativa no intermedia este proceso y no hace ninguna declaración sobre la disponibilidad ni el precio de la liquidez privada para ningún activo específico.

Los canales de intermediación que operan de forma independiente de la entidad corporativa pueden ser utilizados por los inversores para facilitar transferencias; ni MCorp ni el órgano de gobierno del vehículo hacen ninguna declaración sobre la idoneidad, disponibilidad ni coste de dichos canales.

## Acceso al portal

El acceso al portal se realiza mediante credenciales. MCorp es responsable de la autenticación de los inversores y de la habilitación y revocación del acceso al portal, como tarea delegada por el órgano de gobierno del vehículo. PointSav mantiene la infraestructura del portal; MCorp controla quién recibe acceso y bajo qué condiciones. Las credenciales se emiten en el momento en que el inversor completa el proceso de incorporación para un activo específico.

## Véase también

- [[equity-transfer-model|Modelo de Transferencia de Capital]] — la mecánica de las transferencias de capital entre pares en activos de Tenencia Directa
- [[about-continuous-disclosure|Obligaciones de Divulgación Continua]] — los requisitos de reporte ante la OSC que rigen las divulgaciones financieras realizadas a través del portal
- Tecnología del Registro de Propiedades — la infraestructura técnica que mantiene los datos de posición y el historial de eventos financieros
