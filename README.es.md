<div align="center">

# Woodfine — Wiki de Gobernanza Corporativa
### *Arquitectura Financiera y Marco Fiduciario*

<br/>

**[→ woodfinegroup.com](https://woodfinegroup.com)** &nbsp;·&nbsp; **[→ Wiki de Proyectos](https://projects.woodfinegroup.com)** &nbsp;·&nbsp; **[→ Despliegue de Flota](https://github.com/woodfine/woodfine-fleet-deployment)** &nbsp;·&nbsp; **[→ Ingeniería PointSav](https://github.com/pointsav/pointsav-monorepo)**

</div>

---

## Sobre este repositorio

Esta es la biblioteca pública de gobernanza y arquitectura financiera del grupo Woodfine. Documenta la lógica estructural del marco de inversión de Tenencia Directa — el modelo financiero que Woodfine utiliza para desarrollar, gestionar y mantener bienes raíces comerciales con certificación ambiental en América del Norte y Europa.

El lector objetivo es un banquero de inversión, gestor de activos o auditor que desea comprender la estructura del vehículo de inversión, los controles de gobernanza y la arquitectura financiera antes de una primera conversación.

Este repositorio no contiene cuentas financieras activas, registros de personal ni datos corporativos no redactados.

---

## El Marco de Tenencia Directa

Woodfine no opera fondos de inversión. Opera Soluciones de Tenencia Directa — entidades de reporte regulado que poseen los activos inmobiliarios directamente, estructuradas para eliminar los costos estructurales redundantes de los vehículos de fondos en capas. Los inversores mantienen unidades directamente en la empresa que posee los inmuebles.

**Corrección (2026-08-04):** la caracterización de "Libre Transferencia" que aparece a
continuación (y en varios artículos relacionados) describe el diseño estructural de las
Soluciones de Tenencia Directa como clase, sin diferenciar el estado actual por vehículo.
Solo el vehículo de Canadá (Woodfine Professional Centres Limited Partnership) está
actualmente constituido; se encuentra sujeto a una orden de suspensión de negociación
(cease-trade order) activa de la BCSC, en virtud de la cual las unidades no son
actualmente de libre transferencia. Los vehículos de Estados Unidos, España y México
están planificados, aún no constituidos. **Señalado, no reescrito silenciosamente** —
esta corrección se aplica en todo el corpus a cada artículo que hace la afirmación no
matizada de "libre transferencia"/"oferta activa"; véase la corrección correspondiente
en cada artículo relacionado.

`topic-DIRECT-HOLD-FRAMEWORK.md` — El argumento estructural completo para las Soluciones de Tenencia Directa frente a los REIT tradicionales y los vehículos de fondos. Las cuatro implementaciones jurisdiccionales: LP de Canadá, LP de Estados Unidos, SOCIMI de España, FIBRA de México.

`topic-EQUITY-TRANSFER-MODEL.md` — Cómo las Unidades de Inversión se transfieren directamente entre inversores sin colas de redención. Por qué el estado de Libre Transferencia distingue las Soluciones de Tenencia Directa tanto de los REIT públicos como de los fondos privados.

`topic-REDEMPTION-ELIMINATION.md` — Capital Perpetuo: por qué la eliminación de los mecanismos de redención es una elección estructural deliberada que alinea los intereses de los inversores y la empresa a largo plazo.

`topic-INTEREST-COVERAGE-RATIO.md` — El ratio mínimo estricto de cobertura de intereses de 1.2x, el diseño de Desapalancamiento Orgánico y el Modelo de Financiamiento Cíclico (estabilizar → emitir deuda → construir el siguiente activo).

`topic-FIDUCIARY-DATA-MANDATE.md` — Por qué el control custodial de los registros corporativos es una obligación fiduciaria, no una elección tecnológica.

---

## Estructura de gobernanza

Woodfine Capital Projects Inc. ("Woodfine") es la matriz, promotora y desarrolladora. Cada Solución de Tenencia Directa está gobernada por el órgano que exige su forma legal: Woodfine Professional Centres Inc. (subsidiaria de Woodfine) como socio general en Canadá; un socio general de Delaware, un Consejo de Administración español y un Administrador mexicano con Comité Técnico para los tres vehículos planificados. Woodfine Management Corp. (MCorp) es una subsidiaria separada de Woodfine que contrata consultores externos y realiza tareas delegadas por otras subsidiarias; no es socio general, administrador ni órgano de gobierno de ningún vehículo.

Los vehículos jurisdiccionales establecidos y planificados:

| Entidad | Jurisdicción | Estado | Designación |
|:---|:---|:---|:---|
| Woodfine Professional Centres Limited Partnership | Canadá | Establecido | Emisor Regulado bajo BCSC |
| Woodfine Professional Centres 2 Limited Partnership | Estados Unidos | Planificado | Entidad de Reporte Regulada |
| Woodfine Professional Centres 3 SOCIMI | España | Planificado | Sociedad Cotizada |
| Woodfine Professional Centres 4 FIBRA | México | Planificado | Fideicomiso de flujo directo |

---

*© 2026 Woodfine Capital Projects Inc. Todos los derechos reservados.*

*→ English version: [README.md](./README.md)*
