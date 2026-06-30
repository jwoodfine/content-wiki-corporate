---
schema: foundry-doc-v1
title: "Marco de Tenencia Directa"
slug: topic-direct-hold-framework
aliases:
  - topic-direct-hold-framework
category: governance
type: reference
content_type: topic
quality: complete
status: active
audience: public
bcsc_class: public-disclosure-safe
language_protocol: PROSE-TOPIC
last_edited: 2026-05-25
editor: pointsav-engineering
paired_with: topic-direct-hold-framework.md
short_description: "Estructura legal que emite participaciones en un único vehículo de tenencia directa nombrado, sin participar en un fondo combinado, eliminando el contagio entre activos."
cites: []
---

El Marco de Tenencia Directa es una estructura jurídica de propiedad bajo la cual cada inversor posee participaciones en un único vehículo de tenencia directa nombrado, y no una reclamación proporcional sobre un fondo mancomunado. Cada estructura de tenencia directa se constituye como una unidad jurídica y financiera independiente, de modo que un evento financiero que afecta a una estructura no puede propagarse a la posición del inversor en otra. Este artículo describe la estructura jurídica del marco, el mecanismo de aislamiento, las [[topic-equity-transfer-model|condiciones de transferencia y liquidez]] entre inversores, las [[topic-fiduciary-data-mandate|obligaciones fiduciarias de datos]] que protegen la integridad del registro, y la [[topic-interest-coverage-ratio|disciplina de cobertura de intereses]] aplicada por estructura.

El marco emite capital específico por estructura: cada inversor posee participaciones en un único vehículo de tenencia directa nombrado, no una participación en un fondo mancomunado.

Cada activo es su propia unidad jurídica y financiera, aislada como un vehículo independiente. Un evento financiero que afecta a un activo no puede propagarse al capital del inversor en otro; el aislamiento es una propiedad de la arquitectura, no una promesa contractual.

## Qué reemplaza

Un fondo inmobiliario comercial tradicional opera con capital mancomunado. El fondo mantiene muchas propiedades; la participación de un inversor le otorga una reclamación proporcional sobre el grupo, no sobre un activo específico. El gestor del grupo determina las distribuciones, las ventanas de liquidez y cuándo se venden los activos; el inversor no puede aprobar ni rechazar ninguna decisión sobre un activo individual. El Marco de Tenencia Directa invierte este acuerdo: la exposición del inversor se vincula al activo específico en lugar de a un vehículo mancomunado.

El Marco de Tenencia Directa elimina el fondo. Cada propiedad es su propia unidad legal y financiera. Los inversores poseen participaciones en un vehículo constituido en torno a una propiedad específica nombrada, sin mezcla con otras propiedades ni discrecionalidad del gestor del fondo sobre su capital.

## Aislamiento legal

La separación legal estricta es estructural. Cada libro contable de activo está aislado como un vehículo independiente, de modo que un evento financiero que afecta a un activo — vacancia, litigio, refinanciación — no puede propagarse al capital del inversor en un activo diferente. El título legal de cada propiedad lo ostenta una sociedad nominada WCP Titleco independiente, de la cual es beneficiaria la sociedad de tenencia directa aplicable, lo que aisla la propiedad de las obligaciones de cualquier otra entidad de la estructura.

El aislamiento es una propiedad de la arquitectura y no de una promesa contractual. Un inversor que evalúa el riesgo de un activo no tiene que modelar el resto de una cartera.

## Transferencias y liquidez

Las transferencias de capital en el modelo de Tenencia Directa se ejecutan entre partes privadas. No existe [[topic-redemption-elimination|cola de redención]], ni ventana de liquidez gestionada por la entidad corporativa, ni reserva de efectivo mancomunada para satisfacer solicitudes de redención.

Un inversor que desee salir localiza una contraparte dispuesta directamente; la empresa no intermedia el proceso. La estructura no carga ninguna obligación de redención mancomunada, de modo que ningún activo se vende bajo presión para financiar la salida de otro inversor.

## Gobernanza

En cada vehículo de tenencia directa, el socio general ostenta la autoridad de gestión sobre el vehículo y su propiedad única nombrada. Los derechos de gobierno de los inversores — como socios comanditarios o titulares de unidades equivalentes — operan a nivel del activo y no a nivel de cartera agregada: las decisiones se refieren a la propiedad específica del vehículo y no a un conjunto de activos gestionados a nivel de fondo. El [[topic-perpetual-equity-model|modelo de capital perpetuo]] aplica estos mecanismos a [[topic-investment-units|unidades de inversión]] mantenidas sin un horizonte de redención fijo.

## Véase también

- [[topic-equity-transfer-model|Modelo de Transferencia de Capital]] — cómo cambian de manos los intereses de propiedad en activos de Tenencia Directa
- [[topic-fiduciary-data-mandate|Mandato Fiduciario de Datos]] — requisitos de gobernanza de datos para el libro contable de propiedad
- [[topic-interest-coverage-ratio|Ratio de Cobertura de Intereses]] — la restricción de deuda aplicada por activo
- [[topic-redemption-elimination|Eliminación de Redención]] — por qué no existe cola de reembolso en esta estructura

---

*Copyright © 2026 Woodfine Capital Projects Inc. Licenciado bajo [Creative Commons Atribución-SinDerivadas 4.0 Internacional](https://creativecommons.org/licenses/by-nd/4.0/).*
