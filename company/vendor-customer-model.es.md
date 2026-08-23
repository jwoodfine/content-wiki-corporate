---
schema: foundry-doc-v1
title: "Modelo Proveedor-Cliente"
slug: vendor-customer-model
aliases:
  - topic-vendor-customer-model
short_description: "Separación estructural entre PointSav Digital Systems como proveedor de tecnología y el órgano de gobierno de cada vehículo de Tenencia Directa como custodio de datos y cliente tecnológico, con MCorp gestionando la administración delegada del día a día."
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
paired_with: vendor-customer-model.md
cites: []
---

PointSav Digital Systems ocupa el rol de proveedor dentro de la [[topic-corporate-structure|estructura corporativa de Woodfine]]. PointSav suministra servicios de plataforma tecnológica —infraestructura del registro de propiedades, portal de inversores, mantenimiento de software— a cada vehículo de Tenencia Directa. El propio órgano de gobierno de cada vehículo — en Canadá, el socio general, Woodfine Professional Centres Inc. — ostenta la custodia de los datos en virtud del [[topic-fiduciary-data-mandate|Mandato Fiduciario de Datos]] y es el único responsable de las decisiones de inversión y fiduciarias que afectan a los activos de [[topic-direct-hold-framework|Tenencia Directa]]; MCorp administra los requisitos cotidianos de la plataforma y las comunicaciones con inversores como tarea delegada por el órgano de gobierno.

## Puntos clave

- El rol de PointSav termina en el límite de la plataforma: presta servicios operativos y técnicos, pero no ejerce discrecionalidad sobre los datos, no posee participaciones en los activos gestionados de ningún vehículo y no proporciona asesoramiento de inversión ni fiduciario.
- El órgano de gobierno de cada vehículo mantiene la custodia portable del registro de propiedades; si el órgano de gobierno contrata a un proveedor de tecnología diferente, los datos del registro se trasladan con él y no permanecen en poder de PointSav.
- La separación proveedor-cliente aísla estructuralmente los modos de fallo: una interrupción tecnológica en PointSav no afecta la titularidad legal de un órgano de gobierno sobre los activos, y un evento financiero en cualquier otra parte del grupo no interrumpe las obligaciones de plataforma de PointSav.

## Obligaciones del proveedor

Las obligaciones de PointSav en virtud del [[topic-technology-services|acuerdo de servicios tecnológicos]] son operativas y técnicas. El proveedor es responsable de la disponibilidad de la plataforma, la integridad del software, la seguridad informática y la consistencia de los datos del registro. PointSav no ejerce discrecionalidad sobre qué datos se almacenan, cómo se clasifican ni cómo se utilizan; esas decisiones corresponden al órgano de gobierno de cada vehículo como custodio de los datos.

PointSav no representa a ningún órgano de gobierno ante inversores ni ante organismos reguladores. PointSav no proporciona asesoramiento en materia de cumplimiento normativo, asesoramiento de inversión ni servicios fiduciarios. El ámbito del proveedor se limita al perímetro de la plataforma.

## Derechos del cliente

El órgano de gobierno de cada vehículo conserva la custodia legal plena de todos los datos procesados por la plataforma para su vehículo — véase [[topic-data-governance|Gobernanza de Datos]] para el marco completo de custodia. Si un órgano de gobierno contrata a un proveedor de tecnología diferente, los datos del registro de propiedades son portables; no permanecen en poder de PointSav. La arquitectura está diseñada para que el órgano de gobierno pueda reconstruir el control operativo completo del registro a partir de datos exportados, sin depender de ninguna implementación de software específica de PointSav.

El órgano de gobierno dirige los requisitos de la plataforma, con MCorp administrando la recopilación y coordinación cotidiana de requisitos como tarea delegada. PointSav construye y mantiene conforme a esos requisitos.

## Separación de modos de fallo

En una estructura combinada —donde un proveedor de tecnología también participa en la gestión de capital— un fallo en un ámbito se amplifica hacia el otro. Una interrupción tecnológica que afecte a un operador de plataforma que también gestiona capital genera simultáneamente riesgo operativo y financiero.

La separación proveedor-cliente impide esta amplificación. Un fallo tecnológico en PointSav no afecta la titularidad legal de ningún órgano de gobierno sobre los activos ni la validez de los registros de participaciones. Un evento financiero en cualquier otra parte del grupo no interrumpe la capacidad de PointSav para mantener la infraestructura de la plataforma. Los modos de fallo están estructuralmente aislados.

## No es una relación de marketing

PointSav no comercializa los productos de inversión de ningún vehículo, y ningún órgano de gobierno promueve la plataforma tecnológica de PointSav como parte de sus comunicaciones con inversores. La relación es un contrato de servicios, no una empresa conjunta. Ninguna de las partes posee participaciones en las operaciones comerciales principales de la otra.

## La conclusión

El modelo proveedor-cliente asigna a PointSav el rol de constructor de tecnología y al órgano de gobierno de cada vehículo el rol de custodio de datos, responsable de las decisiones de inversión y titular de la relación con los inversores — con MCorp gestionando la administración delegada del día a día de la plataforma. Las partes no poseen participaciones en las operaciones principales de la otra, no comercializan de forma cruzada los productos de la otra, y no son conjuntamente responsables de ningún resultado de inversión. La separación estructural implica que la plataforma y la función de gestión de inversiones pueden evaluarse, sustituirse o reestructurarse cada una de forma independiente.

## Véase también

- [[topic-corporate-structure|Estructura Corporativa]] — la relación de propiedad entre todas estas entidades
- [[topic-technology-services|Acuerdo de Servicios Tecnológicos]] — la estructura del contrato de servicios entre PointSav y cada vehículo
- [[topic-data-governance|Gobernanza de Datos]] — las obligaciones de custodia de datos de cada órgano de gobierno bajo el modelo proveedor-cliente

---

*Copyright © 2026 Woodfine Capital Projects Inc. Licenciado bajo [Creative Commons Atribución-SinDerivadas 4.0 Internacional](https://creativecommons.org/licenses/by-nd/4.0/).*
