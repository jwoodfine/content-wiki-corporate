---
schema: foundry-doc-v1
title: "Mandato de Datos Fiduciarios"
slug: fiduciary-data-mandate
aliases:
  - topic-fiduciary-data-mandate
category: governance
type: reference
content_type: topic
quality: complete
status: active
audience: public
bcsc_class: public-disclosure-safe
language_protocol: PROSE-TOPIC
last_edited: 2026-07-31
editor: pointsav-engineering
paired_with: fiduciary-data-mandate.md
short_description: "Requisito de custodia y soberanía que exige que el órgano de gobierno de cada vehículo controle físicamente el hardware del registro y las claves criptográficas, sin custodio externo."
cites: []
---

El Mandato de Datos Fiduciarios es el requisito operativo por el cual el órgano de gobierno de cada vehículo de Tenencia Directa — en Canadá, el socio general, Woodfine Professional Centres Inc. — mantiene el control físico y criptográfico directo de todos los registros que definen las posiciones de capital de los inversores, las valoraciones de activos y la cadena de titularidad. El mandato trata la dependencia de infraestructura en la nube de terceros para los datos del libro contable de inversores como un incumplimiento fiduciario, no como una decisión de proveedor: un órgano de gobierno que no puede acceder a sus propios registros del libro contable sin la cooperación de un tercero no puede cumplir de forma independiente sus obligaciones con los inversores. El mandato sustenta el [[topic-direct-hold-framework|Marco de Tenencia Directa]], habilita el [[topic-equity-transfer-model|Modelo de Transferencia de Capital]] y se aplica junto con la disciplina del Ratio de Cobertura de Intereses a nivel de activo.

## Puntos clave

- El mandato exige que el órgano de gobierno de cada vehículo mantenga el control físico y criptográfico directo de todos los registros del libro contable de inversores — la dependencia de infraestructura en la nube de terceros para estos registros se clasifica como un incumplimiento fiduciario, no como una relación de proveedor.
- La plataforma de PointSav implementa el mandato proporcionando infraestructura de registro autoalojada en la que el órgano de gobierno posee las claves privadas y el hardware físico; ningún tercero puede acceder a los datos del registro sin el consentimiento criptográfico del órgano de gobierno.
- El alcance del mandato se limita a los datos del libro contable de inversores y a los registros de cadena de titularidad — los materiales de marketing, la gestión de inquilinos y la infraestructura de comunicaciones pueden utilizar servicios alojados. MCorp puede operar el portal de cara al inversor sobre ese registro como tarea delegada, pero no posee las claves de custodia subyacentes.

## Qué cubre el mandato

El mandato se aplica a todos los datos que registran posiciones de capital de inversores, valoraciones de activos, historial de transacciones y cadena de titularidad. Estos registros constituyen el fundamento legal de la relación con los inversores. El órgano de gobierno de un vehículo no puede ser el titular beneficiario de activos si no controla los datos que definen esos activos.

## La dependencia de la nube de terceros como riesgo fiduciario

Los vehículos de inversión inmobiliaria tradicionales dependen de plataformas de software de terceros, bases de datos alojadas y sistemas de contabilidad nativos en la nube. Esto crea una vulnerabilidad estructural: el registro legal de la propiedad de los inversores es mantenido por entidades cuyos intereses pueden divergir de los del inversor.

El Mandato de Datos Fiduciarios cierra esta vulnerabilidad al tratar la soberanía digital como equivalente a la propiedad física de activos. Un órgano de gobierno que posee un edificio pero no puede acceder al libro contable que prueba que lo posee está funcionalmente desapoderado.

## Plataforma PointSav

El cumplimiento del mandato por parte del órgano de gobierno de cada vehículo está respaldado por la plataforma de PointSav en virtud del [[topic-technology-services|acuerdo de servicios tecnológicos]]. PointSav proporciona la infraestructura operativa para la gestión del libro contable de inversores: un sistema autoalojado donde el órgano de gobierno posee las claves privadas, el hardware físico y el control operativo de la pila de software. Ningún intermediario de terceros tiene acceso a los datos del libro contable sin el consentimiento criptográfico del órgano de gobierno. El arreglo se rige por el [[topic-vendor-customer-model|modelo proveedor-cliente]] que separa la operación de la plataforma de la responsabilidad fiduciaria.

## Alcance y límites

El mandato se aplica a los datos del libro contable de inversores y a los registros de cadena de titularidad. No se extiende a materiales de marketing, sistemas de gestión de inquilinos o infraestructura de comunicaciones. La distinción: cualquier información que debería producirse en una disputa legal sobre la propiedad de los inversores está dentro del ámbito de aplicación.

Un inversor no puede ejercer derechos de gobierno sobre un activo cuyo libro contable legal no puede acceder. El mandato cierra esta brecha estructural: un órgano de gobierno que controla su propia infraestructura de libro contable puede siempre producir el registro de autoridad, independientemente de la disponibilidad de servicios de terceros. La disciplina complementa las obligaciones más amplias de [[topic-data-governance|gobernanza de datos]] y el [[about-continuous-disclosure|régimen de divulgación continua]] aplicable al emisor.

## La conclusión

El Mandato de Datos Fiduciarios es un principio de soberanía aplicado a los registros digitales. Un órgano de gobierno que posee un edificio pero no puede acceder al libro contable que prueba que lo posee está funcionalmente desapoderado — el mandato cierra esa brecha al exigir que el control físico y criptográfico permanezca en todo momento en manos del propio órgano de gobierno del vehículo. La plataforma de PointSav implementa este requisito operativamente; la estructura corporativa separa la operación de la plataforma de la responsabilidad fiduciaria. El resultado es que el órgano de gobierno — en Canadá, Woodfine Professional Centres Inc. — siempre puede producir el registro autoritativo de las posiciones de capital de los inversores y la cadena de titularidad, independientemente de la disponibilidad o la cooperación continuada de cualquier servicio de terceros.

## Véase también

- [[topic-direct-hold-framework]] — la estructura de propiedad que el mandato fiduciario protege
- [[topic-equity-transfer-model]] — cómo la integridad del libro contable sustenta la libre transferencia de capital
- Ratio de Cobertura de Intereses — la disciplina financiera aplicada en paralelo al mandato de datos

---

*Copyright © 2026 Woodfine Capital Projects Inc. Licenciado bajo [Creative Commons Atribución-SinDerivadas 4.0 Internacional](https://creativecommons.org/licenses/by-nd/4.0/).*
