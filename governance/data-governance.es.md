---
schema: foundry-doc-v1
title: "Gobernanza de Datos"
slug: data-governance
aliases:
  - topic-data-governance
short_description: "El marco de custodia de datos de cada vehículo de Tenencia Directa: quién posee qué datos, dónde y bajo qué obligaciones, coherente con el Mandato Fiduciario de Datos y los requisitos de PIPEDA."
category: governance
index_group: data-custody
type: reference
content_type: topic
quality: complete
status: active
audience: public
bcsc_class: public-disclosure-safe
language_protocol: TRANSLATE-ES
last_edited: 2026-07-31
editor: pointsav-engineering
paired_with: data-governance.md
cites: []
---

El propio órgano de gobierno de cada vehículo de Tenencia Directa — en Canadá, el socio general, Woodfine Professional Centres Inc. — es el custodio legal de todos los datos del registro de propiedades, los registros de inversores y los datos operativos generados en relación con sus activos gestionados. PointSav Digital Systems procesa los datos como proveedor de servicios tecnológicos contratado en virtud del [[topic-technology-services|acuerdo de servicios tecnológicos]]; PointSav no ostenta derechos independientes sobre esos datos. El acuerdo de custodia implementa el [[topic-fiduciary-data-mandate|Mandato Fiduciario de Datos]] dentro del [[topic-vendor-customer-model|modelo proveedor-cliente]] más amplio.

## Puntos clave

- El órgano de gobierno de cada vehículo es el custodio legal de todos los registros del libro de propiedades, los datos de identidad de los inversores y el historial de transacciones; PointSav actúa como procesador de datos conforme a las instrucciones del órgano de gobierno y no ostenta derechos independientes sobre los datos.
- Los datos operativos están segregados a nivel de activo — un inversor en un activo de [[topic-direct-hold-framework|Tenencia Directa]] no puede acceder a los registros de un activo diferente, y ninguna anulación administrativa puede conceder acceso cruzado entre activos sin un cambio estructural en el registro.
- El órgano de gobierno puede solicitar una exportación completa de datos en cualquier momento en virtud de la obligación de portabilidad, preservando su capacidad de cambiar de proveedor de tecnología sin perder el historial operativo.

## Custodio de datos

El custodio legal de un conjunto de datos es la entidad con el derecho y la responsabilidad de determinar cómo se almacena, utiliza y, en última instancia, destruye. El propio órgano de gobierno de cada vehículo es el custodio legal de todos los registros del libro de propiedades, los datos de identidad de los inversores, el historial de transacciones y los registros operativos generados por sus activos gestionados.

PointSav procesa estos datos en virtud del acuerdo de servicios tecnológicos, actuando como procesador de datos en lugar de responsable del tratamiento, en el sentido de que las instrucciones del órgano de gobierno rigen el tratamiento de los datos. PointSav no utiliza, comparte ni retiene esos datos más allá del alcance del acuerdo de servicios. MCorp puede gestionar la elaboración de informes y comunicaciones de cara al inversor a partir de estos datos como tarea delegada por el órgano de gobierno, pero no ostenta por sí misma derechos de custodia sobre ellos.

## Información personal

Los datos de identidad de los inversores y la información de contacto se recogen en virtud de la Ley de Protección de la Información Personal y los Documentos Electrónicos (PIPEDA). El aviso de privacidad de cada órgano de gobierno rige la recopilación, el uso y la conservación de la información personal de su vehículo. Los datos personales no se venden ni se transfieren a terceros salvo cuando exista una obligación legal —como el reporte contra el blanqueo de capitales en virtud de la Ley sobre el Producto del Crimen (Blanqueo de Dinero) y la Financiación del Terrorismo (PCMLTFA).

Los registros de identidad de los inversores se conservan durante el período exigido por la legislación de valores aplicable y la normativa contra el blanqueo de capitales. Transcurrido el período de conservación requerido, los registros se destruyen conforme al calendario de conservación de datos del órgano de gobierno.

## Segregación de datos operativos

Los datos operativos a nivel de activo —eventos financieros, registros de ocupación, historial de mantenimiento— están segregados por activo. Un inversor en un activo de [[topic-direct-hold-framework|Tenencia Directa]] no puede acceder a los datos operativos ni a los registros de posición de un activo diferente. Esta segregación es una propiedad de la arquitectura del registro: los controles de acceso se aplican a nivel de activo, no a nivel de cartera. Ninguna excepción de política ni anulación administrativa puede conceder acceso cruzado entre activos sin un cambio estructural en el registro.

## Portabilidad de datos

El marco de gobernanza de datos de cada órgano de gobierno requiere que todos los datos del registro sean exportables en formatos estándar. El requisito de portabilidad se impone a PointSav en virtud del acuerdo de servicios tecnológicos. El órgano de gobierno puede solicitar una exportación completa de datos en cualquier momento; PointSav está obligado a entregar la exportación en un formato que el órgano de gobierno pueda leer y operar de forma independiente de la plataforma de software de PointSav.

La portabilidad es el mecanismo por el cual cada órgano de gobierno conserva la opción de cambiar de proveedor de tecnología sin perder el historial operativo ni el registro de capital de ningún activo.

## Conservación

Los registros del libro de propiedades se conservan durante la vida operativa del activo más el período exigido por la legislación de valores aplicable. Los registros de eventos financieros son de solo adición durante la vida operativa del activo; ningún registro anterior se sobrescribe ni elimina. Al final del período de conservación requerido tras la disposición del activo, los registros se destruyen conforme al calendario de conservación de datos del órgano de gobierno y los estándares de destrucción aplicables.

## La conclusión

El marco de gobernanza de datos de cada vehículo de Tenencia Directa asigna claramente las responsabilidades de custodia y las hace cumplir tanto mediante obligación legal como mediante la arquitectura del registro. El órgano de gobierno posee los datos; PointSav los procesa; MCorp puede gestionar la elaboración de informes de cara al inversor como tarea delegada. La información personal se recopila y conserva únicamente en la medida exigida por PIPEDA y la legislación aplicable contra el blanqueo de capitales. La segregación de datos a nivel de activo es una propiedad estructural del registro — no una política que pueda dispensarse. El requisito de portabilidad garantiza que la capacidad de cada órgano de gobierno para atender a los inversores nunca dependa de la cooperación continuada de su proveedor de tecnología actual.

## Véase también

- [[topic-fiduciary-data-mandate|Mandato Fiduciario de Datos]] — las obligaciones de gobernanza que cada órgano de gobierno ostenta como custodio del registro de propiedades
- Tecnología del Registro de Propiedades — la infraestructura técnica en la que se almacenan y mantienen los datos del registro
- [[topic-vendor-customer-model|Modelo Proveedor-Cliente]] — la relación de servicios que rige el rol de PointSav como procesador de datos
