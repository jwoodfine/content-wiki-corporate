---
schema: foundry-doc-v1
title: "Tecnología del Registro de Propiedades"
slug: property-ledger-technology
aliases:
  - topic-property-ledger-technology
short_description: "Infraestructura tecnológica subyacente a cada registro de propiedades de los vehículos de Tenencia Directa: registro criptográfico de participaciones fraccionarias de capital, eventos del activo e historial de transferencias, mantenido por PointSav Digital Systems bajo la custodia del órgano de gobierno del vehículo."
category: company
type: reference
content_type: topic
quality: complete
status: active
audience: public
bcsc_class: public-disclosure-safe
language_protocol: TRANSLATE-ES
last_edited: 2026-07-31
editor: pointsav-engineering
paired_with: property-ledger-technology.md
cites: []
---

Cada activo mantenido bajo el [[topic-direct-hold-framework|Marco de Tenencia Directa]] tiene un registro de propiedades asociado. El registro es el documento autoritativo de las asignaciones fraccionarias de capital, los eventos financieros del activo y el historial de transferencias. El propio órgano de gobierno del vehículo — en Canadá, el socio general, Woodfine Professional Centres Inc. — ostenta la custodia legal del registro en virtud del [[topic-fiduciary-data-mandate|Mandato Fiduciario de Datos]]; PointSav Digital Systems mantiene la infraestructura técnica en su calidad de proveedor de servicios tecnológicos contratado bajo el [[topic-technology-services|acuerdo de servicios tecnológicos]].

## Puntos clave

- Cada activo de Tenencia Directa tiene un registro dedicado que recoge tres categorías de asientos: asignaciones fraccionarias de capital, eventos financieros del activo (de solo adición) e historial de transferencias entre pares con una cadena completa de titularidad desde la emisión inicial.
- El órgano de gobierno del vehículo ostenta la custodia legal y dirige cómo se opera la infraestructura; PointSav posee las claves privadas y el hardware de servidores como proveedor de servicios contratado — la entidad que controla las claves ejerce el control técnico efectivo sobre el registro.
- El registro es un documento criptográfico privado mantenido bajo la autoridad del órgano de gobierno, no una cadena de bloques pública — las dependencias de validadores externos y los órganos de gobernanza de protocolos quedan deliberadamente excluidos de la arquitectura.

## Qué registra el libro

El registro de propiedades recoge tres categorías de información:

**Asignaciones fraccionarias de capital.** El registro documenta quién posee qué porcentaje del activo nombrado en cada momento. La posición de cada inversor se expresa como un porcentaje de la propiedad específica —no como una participación en un fondo ni como un derecho proporcional sobre un conjunto de activos. Cada participación fraccional se constituye como una [[topic-investment-units|unidad de inversión]] en el activo nombrado.

**Eventos financieros del activo.** Las distribuciones, las transacciones de servicio de deuda, las valoraciones y otros eventos financieros que afectan al activo se registran en el libro con marcas de tiempo e importes. El registro es de solo adición para los asientos operativos; ningún registro de evento financiero anterior puede sobrescribirse.

**Historial de transferencias.** Cada transferencia de capital entre pares se registra con la marca de tiempo de la transacción y las identidades de las partes cedente y adquirente, coherente con el [[topic-equity-transfer-model|Modelo de Transferencia de Capital]]. El registro mantiene una cadena completa de titularidad desde la emisión inicial de capital del activo.

## Custodia y control

El órgano de gobierno del vehículo ostenta la custodia legal de todos los datos del registro. PointSav mantiene la infraestructura técnica —claves privadas, hardware de servidores, pila de software— como proveedor de servicios contratado en virtud del acuerdo de servicios tecnológicos. La entidad que posee las claves privadas y opera el registro es la que ejerce el control técnico efectivo sobre el documento. El órgano de gobierno, como custodio legal, dirige cómo se opera la infraestructura y puede exigir la exportación de datos o la transferencia de infraestructura en cualquier momento.

## Principio de control soberano

Un propietario de inmueble que no puede acceder al registro que acredita su titularidad sobre un activo queda funcionalmente desposeído. La arquitectura está diseñada para que el órgano de gobierno pueda recuperar el control operativo completo del registro de forma independiente de cualquier proveedor de tecnología específico. Los datos del registro se almacenan en formatos portables; el documento no está vinculado a la implementación de software específica de PointSav.

## Mecanismos de integridad

La estructura de solo adición de los registros operativos impide la modificación retroactiva del historial de eventos financieros. Los cambios en el registro de capital —transferencias, nuevas asignaciones— requieren el protocolo de confirmación F12: una acción explícita del operador que no puede activarse automáticamente. Ningún proceso automatizado puede modificar el registro de capital sin que un operador humano autorice expresamente el cambio.

## No es un libro de contabilidad distribuido público

El registro de propiedades es un registro criptográfico mantenido bajo la autoridad del órgano de gobierno del vehículo. No es una cadena de bloques pública ni un libro de contabilidad distribuido mantenido por validadores externos. El órgano de gobierno es la autoridad sobre el estado del registro. Esta es una decisión de diseño deliberada: los libros de contabilidad distribuidos públicos introducen dependencias de contrapartes —redes de validadores, órganos de gobernanza de protocolos— que la arquitectura está específicamente diseñada para evitar.

## La conclusión

El registro de propiedades es el fundamento legal de la relación con los inversores: es el documento que prueba quién posee qué en cada activo nombrado. La arquitectura se diseña en torno a dos prioridades — integridad y soberanía. La integridad se mantiene mediante registros de eventos financieros de solo adición y el protocolo de confirmación F12, que impide que cualquier proceso automatizado modifique el registro de capital. La soberanía se mantiene almacenando los datos del registro en formatos portables bajo la custodia legal del órgano de gobierno, de modo que este pueda recuperar el control operativo completo con independencia de su proveedor de tecnología actual. La elección de un registro criptográfico privado frente a un libro de contabilidad distribuido público refleja la misma lógica: las redes de validadores externos introducen dependencias que la arquitectura está diseñada para evitar.

## Véase también

- [[topic-fiduciary-data-mandate|Mandato Fiduciario de Datos]] — las obligaciones del órgano de gobierno como custodio del registro de propiedades
- [[topic-data-governance|Gobernanza de Datos]] — cómo se manejan los datos personales y operativos bajo el marco de custodia del órgano de gobierno
- [[topic-vendor-customer-model|Modelo Proveedor-Cliente]] — la relación de servicios bajo la cual PointSav mantiene la infraestructura técnica
- [Arquitectura del Registro WORM](https://documentation.pointsav.com/infrastructure/worm-ledger-architecture) — arquitectura subyacente del registro referenciada en este artículo

---

*Copyright © 2026 Woodfine Capital Projects Inc. Licenciado bajo [Creative Commons Atribución-SinDerivadas 4.0 Internacional](https://creativecommons.org/licenses/by-nd/4.0/).*
