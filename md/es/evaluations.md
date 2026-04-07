---
title: Cómo las evaluaciones y estándares de seguridad de la IA pueden ayudar en la gobernanza de la IA
description: ¿Qué son las evaluaciones de seguridad de la IA y cómo pueden contribuir a prevenir riesgos catastróficos?
---
<!-- end of frontmatter metadata, dashes above need to stay -->

## ¿Qué son las evaluaciones de seguridad de la IA {#what-are-ai-safety-evaluations}

Las "evaluaciones" son pruebas que miden el comportamiento de los modelos de IA y su creciente poder.
En el ámbito de la seguridad de la IA, estas evaluaciones suelen estar diseñadas para medir [capacidades peligrosas](/dangerous-capabilities), como las capacidades de ciberseguridad, la autorreplicación y la investigación de IA autónoma.

Es importante destacar que las evaluaciones pueden determinar si una IA es demasiado peligrosa para ser desplegada.
Hay ciertas líneas rojas que ningún modelo de IA debería cruzar, como cuando puede...

- **autorreplicarse**. (Por ejemplo, [RepliBench](https://arxiv.org/abs/2504.18565)). Una IA que se autorreplica podría escapar de un laboratorio y propagarse a otras máquinas.
- **crear modelos de IA más poderosos**. Por ejemplo, [RE-bench](https://metr.org/AI_R_D_Evaluation_Report.pdf). Una IA que se auto-mejora podría volverse rápidamente más poderosa que los humanos.

## La prevención del despliegue no es suficiente {#preventing-deployment-is-not-enough}

Las cosas pueden salir mal _incluso antes de que se produzca el despliegue_.
La autorreplicación y la auto-mejora pueden ocurrir en un laboratorio de IA, antes de que el modelo esté disponible públicamente.

Por esto, **necesitamos un [botón de pausa](/building-the-pause-button)**.
Necesitamos detener globalmente el desarrollo de modelos de IA cada vez más poderosos, antes de que estas capacidades peligrosas estén completamente desarrolladas.
Este botón de pausa debería activarse cuando las evaluaciones indiquen que estamos entrando en la zona de peligro.

## Qué están haciendo las empresas de IA {#what-ai-companies-are-doing}

La mayoría de las empresas de IA de vanguardia están realizando evaluaciones de seguridad en sus modelos antes de desplegarlos e incluyen los resultados de estas evaluaciones en las llamadas "tarjetas de sistema".
La mayoría de ellas (excepto Meta y Apple) han firmado el [Código de práctica de la IA de la UE](https://digital-strategy.ec.europa.eu/en/policies/contents-code-gpai), que menciona "evaluaciones de modelos de última generación" (Medida 3.2).

Esto también significa que algunas de estas empresas no están realizando _ninguna_ evaluación de seguridad, y las que se realizan _no son obligatorias_ y _no están estandarizadas_.
En otras palabras, **necesitamos urgentemente regulaciones que exijan evaluaciones de seguridad estandarizadas**.

## Qué están haciendo los países {#what-countries-are-doing}

Multiples gobiernos están invirtiendo ahora seriamente en evaluaciones y estándares de IA para medir capacidades peligrosas:

- El UK AISI ha desarrollado el [marco de inspección](https://github.com/UKGovernmentBEIS/inspect_ai), ha escrito [Replibench](https://arxiv.org/abs/2504.18565), y ahora está invirtiendo [15M GBP en subvenciones para investigaciones de evaluación y alineación](https://alignmentproject.aisi.gov.uk/)
- La Comisión Europea está lanzando una [convocatoria de propuestas de 10M EUR](https://ec.europa.eu/info/funding-tenders/opportunities/portal/screen/opportunities/tender-details/76f9edf2-d9e2-4db2-931e-a72c5ab356d2-CN), y una [gran subvención con el programa Horizon](https://ec.europa.eu/info/funding-tenders/opportunities/portal/screen/opportunities/topic-details/HORIZON-CL4-2025-04-DIGITAL-EMERGING-04). También han lanzado el [Código de práctica de la IA de propósito general](https://digital-strategy.ec.europa.eu/en/policies/contents-code-gpai), que incluye un requisito para realizar "evaluaciones de modelos de última generación" (Medida 3.2).
- El [Plan de acción de la IA de EE. UU.](https://www.whitehouse.gov/articles/2025/07/white-house-unveils-americas-ai-action-plan/) menciona evaluaciones y controles de hardware
- China (concordia AI + laboratorio de IA de Shanghái) acaba de [publicar un informe con muchas evaluaciones](https://substack.com/home/post/p-169741512)
- Otros gobiernos también están trabajando en evaluaciones

_El hecho de que tantos países estén trabajando en evaluaciones crea una oportunidad muy importante para nosotros_.
Si estos países e institutos **utilizaran los mismos estándares** y tuvieran algunas líneas rojas comunes, eso sería un paso importante hacia un tratado global.
Además, debemos comunicar claramente a los políticos que cuando se cruza una línea roja, es hora de [detener el desarrollo adicional](/proposal).