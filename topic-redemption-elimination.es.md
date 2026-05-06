---
schema: foundry-doc-v1
title: "Eliminación de Reembolsos"
slug: topic-redemption-elimination
category: root
type: reference
quality: complete
status: active
audience: public
bcsc_class: public-disclosure-safe
language_protocol: PROSE-TOPIC
last_edited: 2026-05-06
editor: pointsav-engineering
paired_with: topic-redemption-elimination.md
cites: []
---

El principio de Eliminación de Reembolsos es la consecuencia estructural de la negativa de la arquitectura de Tenencia Directa a mancomunar el capital de los inversores. Dado que no existe un fondo mancomunado, no hay mecanismo de reembolso que eliminar — la condición que hace necesarias las colas de reembolso está ausente por diseño.

## Por qué existen las colas de reembolso

En un fondo mancomunado, una cola de reembolso gestiona la tensión entre las solicitudes de liquidez de los inversores y la naturaleza ilíquida del inmueble físico. El fondo mantiene una reserva de efectivo para honrar los reembolsos a corto plazo. Si las solicitudes de reembolso superan la reserva, la cola se activa — los inversores esperan mientras el fondo vende activos o capta nuevo capital.

La reserva de efectivo es un pasivo estructural. Rinde menos que los activos subyacentes. Debe mantenerse incluso cuando no hay reembolsos pendientes. Su tamaño es una decisión discrecional del gestor.

## Lo que elimina la arquitectura de Tenencia Directa

La arquitectura de Tenencia Directa elimina la condición que requiere una reserva de efectivo. No hay capital mancomunado. El capital de cada inversor corresponde a una propiedad específica, no a una participación en un fondo. La entidad corporativa no promete devolver capital a demanda — porque no hay fondo del que extraer.

Un inversor que quiera salir localiza un comprador dispuesto en el mercado privado. La entidad corporativa actualiza el libro contable. No se accede a ninguna reserva de efectivo. La posición de ningún otro inversor se ve afectada.

## "Corridas bancarias" artificiales

Una cola de reembolso es vulnerable a un fallo de coordinación: si los inversores anticipan que la cola será suspendida, las solicitudes tempranas de reembolso pueden desencadenar la misma suspensión que temían. La arquitectura de Tenencia Directa es inmune a este modo de fallo. No hay cola que unirse, ni suspensión que anticipar, ni ventaja de primer movimiento en coordinar una salida anticipada.

## Implicaciones para los inversores

La compensación es explícita: los inversores en activos de Tenencia Directa aceptan que la entidad corporativa no los rescatará. La liquidez depende del mercado privado para el activo específico. Este es un perfil de riesgo estructuralmente diferente al de un fondo mancomunado — y más honesto, porque la entidad corporativa no está haciendo una promesa de liquidez que no puede cumplir.

---

*Copyright © 2026 Woodfine Capital Projects Inc. Licenciado bajo [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/).*
