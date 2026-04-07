---
title: Regulación de capacidades peligrosas en la inteligencia artificial
description: A medida que la inteligencia artificial se vuelve más poderosa en dominios específicos, también aumentan los riesgos. ¿Cómo podemos prevenir la aparición o propagación de estas capacidades peligrosas?
---
 
En este artículo, discutiremos:
- ¿Qué capacidades de la inteligencia artificial pueden ser peligrosas
- ¿Cómo podemos prevenir la aparición o propagación de estas capacidades
- ¿Por qué es peligroso confiar únicamente en las [evaluaciones](/evaluations) como medida de política

A medida que los modelos de inteligencia artificial se vuelven más poderosos y útiles, también se vuelven más peligrosos.
Entonces, ¿en qué punto debemos proceder con cautela?
Un umbral particular que se menciona a menudo es la inteligencia artificial general (AGI).
Hay mucho debate sobre qué significa exactamente la AGI.
Algunos dicen que es cuando la inteligencia artificial puede realizar todas las tareas cognitivas que los humanos pueden.
Algunos dicen que el GPT-4 ya es AGI.
Steve Wozniak define la AGI como el primer sistema que puede entrar en una cocina y preparar un café.

Desde una perspectiva de seguridad, la definición de AGI no es tan importante.
De hecho, puede darnos una falsa sensación de seguridad, porque podríamos pensar que estamos a salvo hasta que lleguemos a la AGI.
Incluso si una inteligencia artificial no puede preparar un café, todavía puede ser peligrosa.
Lo que importa es _qué capacidades tiene una inteligencia artificial_.

En este artículo, profundizaremos en varias capacidades peligrosas y qué podemos hacer para prevenir que nos causen daño.

## ¿Qué capacidades pueden ser peligrosas? {#which-capabilities-can-be-dangerous}

- **Ciberseguridad**. Cuando una inteligencia artificial puede descubrir vulnerabilidades de seguridad (especialmente nuevas y desconocidas), puede (ser utilizada para) [acceder a sistemas](/cybersecurity-risks). Los sistemas de inteligencia artificial actuales pueden encontrar algunas vulnerabilidades de seguridad, pero no a niveles avanzados y peligrosos. Sin embargo, a medida que aumentan las capacidades de ciberseguridad, también aumenta el daño potencial que un ciberarma asistida por inteligencia artificial podría causar. Los ciberataques a gran escala podrían interrumpir nuestra infraestructura, deshabilitar los pagos y causar caos.
- **Biológica**. Diseñar nuevos agentes biológicos o ayudar en el proceso de ingeniería de una pandemia. Un grupo de estudiantes pudo utilizar un chatbot para [producir todos los pasos necesarios para crear una nueva pandemia](https://arxiv.org/abs/2306.03809). Una inteligencia artificial diseñada para encontrar medicamentos seguros fue utilizada para descubrir [40.000 nuevos agentes químicos en seis horas](https://www.theverge.com/2022/3/17/22983197/ai-new-possible-chemical-weapons-generative-models-vx).
- **Mejoras algorítmicas**. Una inteligencia artificial que puede encontrar algoritmos eficientes para un problema determinado podría llevar a un bucle recursivo de auto-mejora, girando rápidamente fuera de control. Esto se llama _explosión de inteligencia_. La inteligencia artificial resultante sería increíblemente poderosa y podría tener todo tipo de capacidades peligrosas. Afortunadamente, ninguna inteligencia artificial puede auto-mejorarse todavía. Sin embargo, hay inteligencia artificial que pueden encontrar nuevos algoritmos muy eficientes (como [AlphaDev](https://www.deepmind.com/blog/alphadev-discovers-faster-sorting-algorithms)).
- **Engaño**. La capacidad de manipular a las personas, que incluye la ingeniería social. Varias formas de engaño ya están presentes en los sistemas de inteligencia artificial actuales. Por ejemplo, la inteligencia artificial CICERO de Meta (que se entrenó para lograr una "cooperación humano-inteligencia artificial mejor y más natural") resultó ser una experta mentirosa, engañando a otros agentes en el juego. Una inteligencia artificial que puede engañar a los humanos puede engañar a los humanos durante las corridas de entrenamiento. Puede ocultar sus capacidades o intenciones.
- **Auto-replicación**. Si una inteligencia artificial puede crear nuevas instancias en otras máquinas, hay un riesgo de que se propague de manera incontrolable, lo que lleva a una [_toma de control de la inteligencia artificial_](/ai-takeover). Una inteligencia artificial lo suficientemente capaz podría superar a los humanos y llevar a la [extinción humana](/xrisk). Tenga en cuenta que esto podría suceder incluso antes de que se despliegue un modelo de inteligencia artificial.

Esta lista no es exhaustiva, por lo que hay otras capacidades peligrosas que una inteligencia artificial podría tener.

## Prevención de la creación de capacidades peligrosas {#preventing-creation-of-dangerous-capabilities}

¿Podemos prevenir la aparición de estas capacidades peligrosas?
A medida que las inteligencias artificiales se vuelven más grandes y se entrenan con más datos, adquieren nuevas capacidades.
Resulta ser muy difícil predecir qué capacidades aparecerán y cómo funcionarán las inteligencias artificiales.
Debido a esto, a menudo se les llama _Capacidades Emergentes_.

Nuestro paradigma actual de modelos de lenguaje grande es casi inherentemente impredecible.
Los modelos de inteligencia artificial no se escriben como software, se entrenan.
Son cajas negras que consisten en billones de parámetros numéricos.
Nadie realmente sabe qué está sucediendo dentro.
Esta impredecibilidad hace que sea difícil decir si una corrida de entrenamiento resultará en una inteligencia artificial peligrosa.
La investigación de interpretabilidad puede cambiar esto en el futuro, pero por ahora, no podemos explicar realmente por qué la inteligencia artificial hace lo que hace.

Entonces, prevenir la creación de capacidades peligrosas prácticamente solo se puede hacer de una manera:
no construir sistemas de inteligencia artificial cada vez más poderosos en primer lugar.
Esta sería la forma más segura de avanzar, pero eso no es lo que los laboratorios de inteligencia artificial están proponiendo.

## Prevención de la propagación de capacidades peligrosas {#preventing-the-proliferation-of-dangerous-capabilities}

En este momento, mucho está sucediendo en el espacio de regulación de la inteligencia artificial.
Muchas de estas propuestas (incluyendo todas las que provienen de los laboratorios de inteligencia artificial) dependen de las **evaluaciones** de seguridad (o _evals_): pruebas de modelos de inteligencia artificial antes de su despliegue.
Un ejemplo de estos enfoques basados en evaluaciones es el [enfoque RSP de Anthropic](https://evals.alignment.org/blog/2023-09-26-rsp/#:~:text=An%20RSP%20specifies%20what%20level,capabilities%20until%20protective%20measures%20improve.) o el [enfoque de pausa coordinada](https://www.governance.ai/research-paper/coordinated-pausing-evaluation-based-scheme) de GovAI.
Nos referimos a estos como [regulación de nivel 2](/4-levels-of-ai-regulation).
Estas evaluaciones no previenen que se creen inteligencias artificiales peligrosas, pero sí previenen que se desplieguen.
Este tipo de política es relativamente barato y aún permite que los laboratorios de inteligencia artificial continúen su investigación.
Sin embargo, creemos que este enfoque es muy peligroso:

- **Los modelos pueden filtrarse**.
  Vimos que sucedió con el modelo LLAMA de Meta. Una vez que está allí, no hay vuelta atrás.
- **Algunas capacidades son peligrosas incluso dentro de los laboratorios de inteligencia artificial**.
  Una inteligencia artificial auto-replicante, por ejemplo, podría [escapar del laboratorio antes del despliegue](https://lethalintelligence.ai/post/ai-escaped-its-container/).
- **Es difícil probar capacidades peligrosas**.
  No sabemos cómo podemos (de manera segura) probar si una inteligencia artificial puede auto-replicarse, por ejemplo. O cómo probar si engaña a los humanos.
- **Las capacidades pueden agregarse o descubrirse después del entrenamiento**.
  Esto incluye el ajuste fino, el "jailbreaking" y las mejoras en tiempo de ejecución.

Profundizaremos en este último punto con más detalle.

## Las capacidades pueden agregarse después del entrenamiento {#capabilities-can-be-added-after-training}

### Ajuste fino {#fine-tuning}

El ajuste fino se puede utilizar para mejorar las capacidades de un modelo de inteligencia artificial existente.
Esto es similar al entrenamiento, pero es mucho más rápido, más barato, no requiere tanto datos y a menudo se puede hacer en hardware de consumo.
El ajuste fino cambia los parámetros de la inteligencia artificial y, como tal, cambia sus capacidades.
Ahora, el ajuste fino no es tan poderoso como realizar una corrida de entrenamiento completa, pero aún puede mejorar las capacidades existentes.

### "Jailbreaking" {#jailbreaking}

Las inteligencias artificiales más grandes se entrenan con cantidades absolutamente vastas de datos.
La mayoría de los libros, artículos científicos y sitios web en Internet.
Hay mucha información desagradable en estos conjuntos de datos.
Las inteligencias artificiales a menudo se ajustan finamente utilizando una técnica llamada RLHF (Aprendizaje de Refuerzo desde la Retroalimentación Humana) para que sean útiles y agradables.
En este proceso, la inteligencia artificial tiene que aprender a no decir ciertas cosas, como hacer comentarios racistas, explicar cómo hacer una bomba o cómo crear un nuevo agente biológico.

Pero estas salvaguardas no son perfectas.
El "jailbreaking" es una técnica donde se intenta hacer que la inteligencia artificial ignore estas salvaguardas.
Esto se puede hacer [agregando ciertas palabras o caracteres a su mensaje de chat](https://twitter.com/AIPanicLive/status/1678942758872989696), o [reformulando creativamente su mensaje](https://twitter.com/_annieversary/status/1647865782741749760).
No está claro si [se puede parchar este comportamiento](https://llm-attacks.org/).

### Mejoras en tiempo de ejecución {#runtime-improvements}

Las mejoras en tiempo de ejecución no hacen cambios en el modelo, sino que mejoran la forma en que se utiliza el modelo.

La más simple de estas es cambiar las solicitudes.
Incluso los pequeños cambios en las solicitudes pueden tener un gran efecto en la salida del modelo.
Agregar algunas palabras a una solicitud puede mejorar el rendimiento [por más del 50%](https://arxiv.org/pdf/2309.03409.pdf).

Pero también podemos utilizar todo tipo de software para aumentar un modelo base.
Por ejemplo, las personas han encontrado formas de agregar memoria a largo plazo al GPT-4, permitiendo que el modelo consulte una base de datos.
O considere AutoGPT, que permite que un modelo se llame a sí mismo de forma recursiva, lo que significa que puede ejecutarse de forma autónoma durante cualquier período de tiempo.
O considere [Voyager](https://arxiv.org/abs/2305.16291), una herramienta que permitió que el GPT-4 jugara Minecraft de forma completamente autónoma. Incluso llegó al equipo de diamante.

No sabemos hasta dónde se puede estirar un modelo base.
Incluso si paramos de entrenar nuevos modelos de inteligencia artificial ahora, probablemente veremos innovaciones importantes que agreguen nuevas capacidades a los modelos existentes.

## En conclusión {#in-conclusion}

Las capacidades peligrosas de la inteligencia artificial pueden llevar a todo tipo de problemas: ciberataques a gran escala, pandemias ingenierizadas y inteligencia artificial descontrolada que [toma el control](/ai-takeover).
Es tentador confiar en las evaluaciones para prevenir la aparición o propagación de estas capacidades peligrosas, pero este es un enfoque peligroso:

- Incluso si probamos los modelos antes de su despliegue, todavía hay formas en que pueden obtener capacidades peligrosas después del despliegue (ajuste fino, "jailbreaking", mejoras en tiempo de ejecución).
- Los modelos pueden filtrarse.
- Algunas capacidades son peligrosas incluso dentro de los laboratorios de inteligencia artificial.

La única opción segura es no construir estos sistemas de inteligencia artificial poderosos en primer lugar.
No debemos permitir la creación de estos sistemas de inteligencia artificial impredecibles y potencialmente muy peligrosos.
[Desafortunadamente, ni una sola propuesta de borrador actualmente previene o retrasa la inteligencia artificial superinteligente.](https://twitter.com/PauseAI/status/1704998018322141496)
Es por eso que [estamos pidiendo una pausa](/proposal).