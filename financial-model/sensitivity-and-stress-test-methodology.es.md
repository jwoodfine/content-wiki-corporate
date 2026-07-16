---
schema: foundry-doc-v1
title: "Cómo Funciona el Análisis de Sensibilidad y Pruebas de Estrés para las Soluciones de Tenencia Directa"
slug: sensitivity-and-stress-test-methodology
aliases: []
short_description: "Cómo las Soluciones de Tenencia Directa modelan el estrés de tasa de interés, ocupación y rendimiento de desarrollo frente al convenio de cobertura de 1.20x."
category: financial-model
type: reference
content_type: guide
quality: complete
status: active
audience: public
bcsc_class: public-disclosure-safe
language_protocol: TRANSLATE-ES
last_edited: 2026-07-15
editor: pointsav-engineering
paired_with: sensitivity-and-stress-test-methodology.md
cites: []
---

Cada Solución de Tenencia Directa se modela frente a una unidad de referencia de preservación de capital de $100.00 y un convenio mínimo de cobertura de intereses de 1.20x establecido en las condiciones de financiamiento de sus debentures. Esta guía recorre la metodología de sensibilidad y pruebas de estrés aplicada a ese modelo: cómo se ajusta de forma aislada un solo impulsor de cobertura —tasa de interés, ocupación o rendimiento de desarrollo— para observar su efecto sobre la cobertura y el ritmo de desarrollo; cómo la palanca adaptativa de desarrollo del emisor está diseñada para sostener el convenio en lugar de incumplirlo; cómo un choque combinado máximo, calibrado a las recesiones históricas más severas, se absorbe mediante una disposición correctiva de último recurso; y cómo se reportan las sensibilidades resultantes bajo la NIIF 13 §93(h)(ii). El resultado de esta metodología es un conjunto de escenarios modelados e ilustrativos, no una predicción del desempeño futuro — la cobertura, el valor neto de los activos (NAV) y los resultados de distribución reales diferirán de cada uno de los supuestos aquí planteados.

## Requisitos previos

- Familiaridad con el propio convenio de cobertura de intereses. Véase [[interest-coverage-ratio|Ratio de Cobertura de Intereses]] para entender qué es el piso de 1.20x y por qué se establece en ese nivel — esta guía no vuelve a explicar el convenio; recorre cómo se somete ese convenio a pruebas de estrés.
- Familiaridad con el valor neto de los activos (NAV) y las demás medidas no-NIIF frente a las cuales reporta esta metodología. Véase [[non-ifrs-measures-explained|Medidas No-NIIF Explicadas]].
- Nada más allá de esto. No se requiere ningún software de modelado ni acceso a cuenta alguna — esta guía describe una metodología, no una herramienta.

## Pasos

1. **Partir de la unidad de referencia de $100 y el caso base.** La metodología da seguimiento a una unidad de referencia de preservación de capital de $100.00 a través de cada escenario, desde el caso base hasta el choque combinado máximo. El caso base es el pronóstico a 10 años sin estrés — la tasa de financiamiento, la ocupación y el rendimiento de desarrollo se mantienen en sus valores esperados, y la cobertura de intereses se verifica frente al convenio de 1.20x en cada punto del horizonte.

2. **Ajustar un impulsor de cobertura a la vez.** La metodología de escenarios de estrés por impulsor de cobertura mantiene todos los supuestos en su nivel base mientras ajusta un solo impulsor —tasa de interés, ocupación o rendimiento de desarrollo— para aislar el efecto de ese impulsor sobre la cobertura mínima de intereses y sobre el ritmo de desarrollo, antes de combinar los impulsores entre sí.

3. **Leer la respuesta de la palanca adaptativa de desarrollo, no una proyección estática.** A medida que los costos de financiamiento o las condiciones operativas empeoran durante la construcción, el emisor restringe la emisión de nuevos debentures y reduce el ritmo del programa de desarrollo para sostener la cobertura de intereses en el nivel del convenio en lugar de permitir su incumplimiento. Una proyección estática, sin respuesta, se considera poco realista en esta metodología, porque un incumplimiento sostenido del convenio transferiría el control del activo a los prestamistas garantizados — la respuesta adaptativa es el comportamiento modelado, no una capa optimista superpuesta.

4. **Confirmar el margen de cobertura posterior a la construcción.** Una vez que una Solución de Tenencia Directa se estabiliza tras la construcción, la cobertura de intereses se mantiene muy por encima del piso de 1.20x. Los escenarios de estrés de la metodología muestran que se requiere un aumento considerable en el cupón de financiamiento antes de que el umbral del convenio vuelva a acercarse.

5. **Combinar los tres impulsores en el choque combinado máximo.** El escenario de choque combinado máximo aplica movimientos adversos simultáneos a la tasa de financiamiento, la tasa de capitalización y la ocupación a la vez, en lugar de ajustar un impulsor por separado. Está calibrado a la evidencia histórica de recesiones severas —movimientos de expansión de tasas de capitalización de oficinas y de tasas de refinanciamiento a la escala de 2008-09 y 2022-23— y se utiliza para dimensionar el caso a la baja para la preservación de capital.

6. **Leer la disposición correctiva de último recurso.** Bajo el choque combinado, se vende una fracción mínima de la cartera a su valor de transacción ordenada bajo condiciones de estrés, para restablecer la cobertura de intereses al nivel del convenio. Se trata de una venta a valor de mercado diseñada para preservar el NAV por unidad mientras comprime —sin eliminar— las distribuciones.

7. **Leer la presentación de resiliencia del NAV a través de los casos base, pesimista y optimista.** La metodología de presentación da seguimiento a las trayectorias del NAV por unidad bajo un caso base, un caso pesimista (tasa de capitalización y ocupación adversas) y un caso optimista (tasa de capitalización favorable), frente a la referencia de preservación de capital de $100 a lo largo del horizonte de pronóstico a 10 años.

8. **Verificar la tabla de sensibilidad de la NIIF 13 §93(h)(ii).** Esta tabla se aplica como una sensibilidad unidireccional de ±25 puntos base a través de la tasa de capitalización, la tasa de interés, la ocupación y el rendimiento de desarrollo, medida frente al NAV por unidad, el rendimiento de ingresos y la cobertura mínima del Año 8. Es un requisito de divulgación de medición a valor razonable, distinto de los escenarios prospectivos de los pasos 1 a 7.

## Verificación

Un lector ha seguido correctamente la metodología si puede identificar, para cualquier ejemplo dado, cuál de los tres impulsores de cobertura se está ajustando y si el ejemplo corresponde a un estrés de un solo impulsor o al choque combinado máximo. Esto se confirma verificando si dos de los tres impulsores se mantienen en su nivel base (estrés de un solo impulsor) o si la tasa de financiamiento, la tasa de capitalización y la ocupación se mueven todas a la vez (choque combinado).

A continuación, se confirma el límite de divulgación: los ejemplos de respuesta de la administración y de disposición correctiva (pasos 3 a 6) son escenarios ilustrativos y prospectivos, mientras que la tabla de la NIIF 13 (paso 8) es una divulgación de sensibilidad de medición a valor razonable. Ambos se preparan conforme a normas distintas — los ejemplos prospectivos incorporan un lenguaje de advertencia coherente con el NI 51-102 y la ISAE 3400, y la tabla de la NIIF 13 sigue la propia convención de esa norma de supuestos alternativos razonablemente posibles de ±25 puntos base. Un lector que no pueda determinar de cuál de los dos proviene una cifra dada no la ha ubicado correctamente dentro de la metodología.

Todos los escenarios de estrés y de choque de esta metodología son modelados e ilustrativos. Ninguna de las cifras de cobertura, NAV o distribución que produce constituye una predicción, una garantía ni una promesa de desempeño futuro real; los resultados reales diferirán de cada uno de los supuestos utilizados para construir estos escenarios.

## Próximos pasos

Consulte [[interest-coverage-ratio|Ratio de Cobertura de Intereses]] para conocer el convenio que esta metodología somete a pruebas de estrés, y [[non-ifrs-measures-explained|Medidas No-NIIF Explicadas]] para saber cómo se definen el NAV y las demás medidas complementarias utilizadas en toda esta metodología, y cómo se concilian con las NIIF. Véase también [[forward-looking-statements-advisory|el Aviso sobre Declaraciones Prospectivas]] para el lenguaje de advertencia que rige cada escenario ilustrativo de esta guía.

---

*Copyright © 2026 Woodfine Capital Projects Inc. Licenciado bajo [Creative Commons Atribución-SinDerivadas 4.0 Internacional](https://creativecommons.org/licenses/by-nd/4.0/).*
