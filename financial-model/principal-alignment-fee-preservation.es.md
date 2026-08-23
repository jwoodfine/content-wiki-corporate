---
schema: foundry-doc-v1
title: "Alineación de Principales y Preservación de Tarifas"
slug: principal-alignment-fee-preservation
category: financial-model
index_group: compensation-and-alignment
type: topic
content_type: topic
quality: complete
short_description: "Modelo de compensación que reemplaza el 2/20: beneficio del desarrollador en capital en fideicomiso hasta devolver el capital del inversor, más una contribución fija anual."
status: stable
bcsc_class: current-fact
last_edited: 2026-07-01
editor: pointsav-engineering
language_protocol: TRANSLATE-ES
source_refs:
  - "23f39b3b44859cad2483d47bf7d003a4183e40ef99c01fc6c58aa189d26b637e"
paired_with: principal-alignment-fee-preservation.md
cites: []
---

El modelo de **Alineación de Principales y Preservación de Tarifas** describe cómo se estructura la compensación en las [[direct-hold-solutions-structural-comparison|Direct-Hold Solutions]] para hacer cumplir una alineación directa entre el interés económico del desarrollador y los rendimientos de inversión de los inversores que atiende. La estructura convencional de inversión alternativa de tarifas — el 2/20 de una comisión de gestión anual del 2% e interés acumulado del 20% — se reestructura de dos maneras: el beneficio del desarrollador se toma como capital en lugar de efectivo, y la tarifa variable de gestión se reemplaza por una contribución fija anual a los gastos generales que no crece con el tiempo ni con la ejecución de transacciones.

## El problema con el modelo convencional 2/20

En la estructura convencional de fondos inmobiliarios 2/20, el gestor recibe dos flujos de compensación que están estructuralmente desacoplados de los resultados de los inversores. La comisión de gestión anual se gana independientemente del rendimiento de la inversión. El interés acumulado se gana solo en resultados rentables, pero se liquida en efectivo a medida que se generan los rendimientos, lo que significa que el gestor extrae efectivo del vehículo mientras se generan los rendimientos.

### Ingresos del gestor desacoplados de los resultados del inversor

El resultado es una estructura de tarifas en la que los ingresos del gestor son parcialmente independientes de los rendimientos de los inversores (el componente de comisión de gestión) y parcialmente correlacionados con ellos (el componente de interés acumulado), pero en la que el capital propio del desarrollador no está en riesgo en el vehículo de la misma manera que el capital del inversor.

## Compensación basada en capital

En las Direct-Hold Solutions, Woodfine no recibe comisiones de gestión en efectivo basadas en activos bajo gestión. La compensación del desarrollador se toma como Compensación Basada en Capital: Unidades de Inversión en el vehículo, recibidas en lugar de interés acumulado en efectivo. Estas unidades se mantienen en fideicomiso hasta que el capital inicial de los inversores haya sido devuelto en su totalidad.

La consecuencia de esta estructura es una alineación 1:1 entre el desarrollador y los inversores a nivel del capital del vehículo. El beneficio económico del desarrollador no es una extracción de efectivo del flujo de ingresos del vehículo — es una participación de titularidad en el mismo activo que tienen los inversores, sujeta a las mismas condiciones de mercado, rendimiento de ingresos y calendario de distribución.

### Capital Retenido como reserva estructural

La posición de capital del desarrollador, una vez ganada a través del período de tenencia y el retorno del capital del inversor, se convierte en Capital Retenido en el balance del vehículo. El Capital Retenido actúa como una reserva estructural: es capital permanente que no requiere distribución, reduciendo la necesidad futura del vehículo de obtener capital externo para nuevas fases de construcción.

## Reembolso inicial de costos de oferta

Aparte de la contribución continua a los gastos generales, WCP paga todos los costos y gastos de cada oferta de participaciones. En el vehículo de Canadá ya constituido, la sociedad reembolsa a WCP el 1% de los ingresos brutos de la venta de participaciones en esa oferta, como pago parcial de dichos costos, conforme a su acuerdo rector. Se trata de un reembolso único ligado a una oferta específica, no de una comisión de gestión recurrente.

## La contribución fija anual a gastos generales

Las tarifas variables de gestión son reemplazadas por una única contribución fija anual a los gastos generales calculada sobre el Valor Financiado Bruto de cada Direct-Hold Solution. Esta estructura elimina varias características de la comisión de gestión convencional que crean desalineación: la tarifa no crece con la apreciación de los activos, es predecible en el momento de la inversión, y no está sujeta a manipulación a través de la valoración de activos, ya que se calcula sobre el Valor Financiado Bruto en lugar de un valor neto de activos marcado al mercado. En el vehículo de Canadá ya constituido, su acuerdo rector prohíbe pagar a cualquier persona una tarifa calculada por referencia al valor neto de los activos.

## Preservación de tarifas para gestores de activos independientes

La estructura de tarifas de las Direct-Hold Solutions está diseñada para que la única contribución fija a los gastos generales permanezca completamente disponible para compensar a los Gestores de Activos independientes que orquestan los Vehículos de Propósito Especial externos a través de los cuales los inversores internacionales acceden a la plataforma. El término "tarifas preservadas" se refiere a la contribución a los gastos generales que está disponible para los Gestores de Activos independientes después de que se satisface el costo fijo de los gastos generales del desarrollador. Dado que la compensación del desarrollador se toma como capital en lugar de tarifas de efectivo adicionales, la contribución a los gastos generales representa una extracción de tarifas total menor del flujo de ingresos del vehículo que la que representaría una comisión de gestión convencional.

## Consulte también

- [[narrow-bank-financial-model]] — el modelo financiero dentro del cual opera la estructura de tarifas
- [[investment-units]] — la mecánica de unidades detrás de la base de tarifas sobre el Valor Financiado Bruto
- [[tripartite-management-structure]] — la estructura de gestión cuya pata de Gestores de Activos independientes compensa el fondo de tarifas preservadas
