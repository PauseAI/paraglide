---
title: Por qué podríamos tener superinteligencia antes de lo que la mayoría piensa
description: Estamos subestimando el progreso de la inteligencia artificial, y hay una pequeña pero realista posibilidad de que estemos muy cerca de una superinteligencia.
date: '2023-05-04'
---
Los modelos de inteligencia artificial actuales [State-of-the-Art](/sota) ya son superhumanos en muchos dominios, pero afortunadamente no en todos.
Si alcanzamos la superinteligencia antes de resolver el problema de la alineación, [enfrentamos un riesgo de extinción](/xrisk).
Por lo tanto, tener una estimación de cuándo podríamos tener superinteligencia es esencial para asegurarnos de que no nos sorprendan.
Si nuestras predicciones están demasiado lejos, es posible que no podamos prepararnos a tiempo.

Pero, ¿cuánto tiempo nos queda?
¿Cuándo tendremos superinteligencia?
Podría ser antes de lo que la mayoría piensa.

## Crecimiento exponencial compuesto {#compounding-exponential-growth}

Los modelos de inteligencia artificial requieren algoritmos, datos y chips.
Cada uno de estos componentes está mejorando rápidamente debido a las enormes inversiones en inteligencia artificial.
Las mejoras en cada uno de estos componentes se combinan, lo que lleva a un crecimiento exponencial en las capacidades de la inteligencia artificial.

- **Más chips**. ChatGPT se entrenó con [10.000](https://www.fierceelectronics.com/sensors/chatgpt-runs-10k-nvidia-training-gpus-potential-thousands-more) chips especializados. Meta ha [anunciado](https://www.datacenterdynamics.com/en/news/meta-to-operate-600000-gpus-by-year-end/) que tendrá 600.000 chips de próxima generación para entrenar sus próximos modelos de inteligencia artificial este año.
- **Chips más rápidos**. Cada año, los chips se vuelven más rápidos debido a nuevas arquitecturas y innovaciones en litografía. Los chips que Meta está utilizando son 10 veces más rápidos que los chips utilizados para ChatGPT. También estamos viendo hardware altamente especializado como los chips Groq, que son [13 veces más rápidos](https://mezha.media/en/2024/02/22/groq-s-new-ai-chip-offers-to-increase-chatgpt-speed-by-13-times/) que la competencia. En un plazo más largo, [arquitecturas ternarias](https://arxiv.org/pdf/2402.17764.pdf) o [chips fotónicos](https://www.nature.com/articles/s41566-024-01394-2) podrían hacer que los chips sean aún más rápidos.
- **Más datos**. GPT3 se entrenó con [45TB](https://community.openai.com/t/what-is-the-size-of-the-training-set-for-gpt-3/360896) de texto, GPT4 utilizó aproximadamente 20 veces más. Las empresas de inteligencia artificial también están utilizando [grandes cantidades de datos de video](https://www.404media.co/nvidia-ai-scraping-foundational-model-cosmos-project/), datos de audio y incluso [generando datos sintéticos para entrenar estos modelos](https://arxiv.org/pdf/2401.10020). Anteriormente, la idea de utilizar datos sintéticos para el entrenamiento se consideraba imposible debido al colapso del modelo, pero [los avances recientes](https://arxiv.org/abs/2406.07515) están mostrando que es posible prevenir el colapso del modelo.
- **Mejores datos**. El artículo "Los libros de texto son todo lo que necesitas" [mostró](https://arxiv.org/abs/2306.11644) que utilizar datos sintéticos de alta calidad puede mejorar drásticamente el rendimiento del modelo, incluso si se utiliza menos datos y cómputo.
- **Mejores algoritmos**. La arquitectura Transformer permitió la revolución actual de los modelos de lenguaje grande. Nuevas arquitecturas pueden permitir saltos similares en capacidad. El modelo Mamba, por ejemplo, está [mostrando](https://arxiv.org/abs/2312.00752) un rendimiento 5 veces más rápido.
- **Mejores tiempos de ejecución**. Los tiempos de ejecución de Agentic, la generación de recuperación o incluso simplemente la configuración inteligente (a través de [Graph of Thought](https://arxiv.org/abs/2305.16582), por ejemplo) pueden tener un impacto significativo en las capacidades de estos modelos.

Es completamente posible que _simplemente escalar_ nos lleve a [capacidades peligrosas](/dangerous-capabilities) en un año o dos, pero con todos estos factores compuestos, podría ser aún más pronto.

## Hemos alcanzado el rendimiento humano en muchos dominios en 2023 {#we-reached-human-level-performance-in-many-domains-in-2023}

En 2022, los investigadores de inteligencia artificial pensaban que tomaría [17 años](https://aiimpacts.org/2022-expert-survey-on-progress-in-ai/) hasta que la inteligencia artificial pudiera escribir un bestseller del New York Times.
Un año después, un profesor chino [ganó un concurso de escritura](https://www.scmp.com/news/china/science/article/3245725/chinese-professor-used-ai-write-science-fiction-novel-then-it-won-national-award) con un libro escrito por inteligencia artificial.

En Metaculus, [la predicción comunitaria para (inteligencia artificial general débil)](https://www.metaculus.com/questions/3479/date-weakly-general-ai-is-publicly-known/) era 2057 hace solo unos años, y ahora es 2027.

Ahora, analicemos la definición de inteligencia artificial general utilizada en esa encuesta:

- Puntuación >90% en el desafío de Winograd Schema
- Puntuación >75% en puntuaciones SAT
- Aprobar una prueba de Turing
- Terminar Montezuma's Revenge

GPT-4 obtiene [94,4% en el desafío de Winograd Schema](https://d-kz.medium.com/evaluating-gpt-3-and-gpt-4-on-the-winograd-schema-challenge-reasoning-test-e4de030d190d), y [93% en el examen de lectura SAT, 89% en el examen de matemáticas SAT](https://www.cnbc.com/2023/03/14/openai-announces-gpt-4-says-beats-90percent-of-humans-on-sat.html).
No ha aprobado la prueba de Turing, pero probablemente no debido a una falta de capacidades.
Es porque GPT-4 se ha ajustado para no engañar a las personas. No es bueno para el negocio que su inteligencia artificial le diga a la gente que es una persona de verdad.
Solo queda Montezuma's Revenge.
No es impensable que pueda ser terminado por una configuración inteligente de GPT-4, utilizando algo como AutoGPT para analizar la pantalla y generar las entradas correctas.
En mayo de 2023, [GPT-4 pudo escribir código para obtener equipo de diamante en Minecraft](https://the-decoder.com/minecraft-bot-voyager-programs-itself-using-gpt-4/).
En resumen: GPT-4 obtuvo 2/4 criterios con certeza, con los otros dos a su alcance.

**Estamos allí, amigos.
Ya tenemos (inteligencia artificial general débil).**
No nos tomó 35 años, nos tomó tres.
Estábamos equivocados por un factor de 10.

## Por qué la mayoría subestima el progreso de la inteligencia artificial {#why-most-underestimate-the-progress-of-ai}

Hay muchas razones por las que la gente subestima el progreso de la inteligencia artificial.

- **Es difícil mantenerse al día**. Casi a diario vemos nuevos avances en inteligencia artificial. Es casi imposible mantenerse al día con el ritmo del progreso. No estás solo si te sientes como si estuvieras quedando atrás.
- **Seguimos moviendo el objetivo**. En la década de 1990, la gente pensaba que el Santo Grial de la inteligencia artificial era algo que pudiera jugar al ajedrez. Cuando la inteligencia artificial derrotó a Kasparov, su próximo desafío fue Go. Ahora, tenemos máquinas que puntúan en el [99,9 percentil en pruebas de inteligencia](https://bgr.com/tech/chatgpt-took-an-iq-test-and-its-score-was-sky-high/), pueden [traducir 26 idiomas](https://bgr.com/tech/chatgpt-took-an-iq-test-and-its-score-was-sky-high/) y [ganar concursos de fotografía](https://www.scientificamerican.com/article/how-my-ai-image-won-a-major-photography-competition/), pero todavía estamos haciendo preguntas como "¿Cuándo alcanzará la inteligencia artificial el nivel humano?". Ya supera nuestras capacidades en muchas áreas, pero siempre nos enfocamos en el número cada vez menor de cosas que podemos hacer mejor.
- **Nos gusta pensar que somos especiales**. A los humanos nos gusta sentir que somos especiales. Si una inteligencia artificial puede hacer lo que podemos hacer, ya no somos especiales. Esto es una píldora difícil de tragar, y el [cerebro tiene muchos mecanismos de defensa para evitar esto](psychology-of-x-risk).
- **Somos muy malos para el crecimiento exponencial**. Tendemos a subestimar estructural y predeciblemente cómo el crecimiento exponencial se acumula con el tiempo. Esto se ha demostrado en [estudios científicos](https://www.researchgate.net/figure/Underestimation-of-exponential-growth-a-shows-the-participants-prediction-of-the_fig4_351171143).

Afortunadamente, todavía hay algunas cosas que una inteligencia artificial no puede hacer.
No puede [hackear mejor que los mejores hackers](/cybersecurity-risks), y no puede hacer investigación de inteligencia artificial tan bien como los mejores investigadores de inteligencia artificial.
**Cuando alcancemos cualquiera de estos umbrales, estaremos en un nuevo régimen de mayor riesgo**.

Así que, ¿cuándo alcanzaremos el punto en el que una inteligencia artificial pueda hacer todas estas cosas a un nivel superhumano?
¿Cuándo tendremos una _superinteligencia_?

## El umbral de Ilya {#the-ilya-threshold}

Creo que el punto crucial que debemos considerar es **el punto en el que una inteligencia artificial es más capaz de hacer investigación de inteligencia artificial que alguien como Ilya Sutskever** (ex científico jefe en OpenAI).
Una inteligencia artificial que pueda hacer contribuciones significativas a los algoritmos y arquitecturas de inteligencia artificial es probable que pueda mejorarla a sí misma.
Llamemos a este punto de posible auto-mejora el _umbral de Ilya_.
Cuando lo alcance, una inteligencia artificial podría mejorarla a sí misma porque se le dio la instrucción explícita de hacerlo, o porque ser más inteligente es un sub-objetivo útil para otros objetivos (las inteligencias artificiales ya están [creando sus propios sub-objetivos](https://github.com/Significant-Gravitas/Auto-GPT)).
Estas iteraciones podrían tomar semanas (entrenar GPT-3 tomó 34 días), pero también es posible que se implemente algún tipo de mejora en tiempo de ejecución que haga progresos significativos en cuestión de minutos: una [explosión de inteligencia](https://www.youtube.com/watch?v=5qfIgCiYlfY).

Así que, ¿cuánto tiempo nos queda para alcanzar el umbral de Ilya?
Es fundamentalmente difícil predecir [cuándo surgen ciertas capacidades](https://arxiv.org/abs/2206.07682) a medida que los modelos de lenguaje grande escalan, pero hasta ahora hemos visto muchas capacidades surgir que se pensaban que estaban muy lejos.
Los [últimos modelos de inteligencia artificial](/sota) ya superan a la mayoría de los programadores humanos, así que no es impensable que los modelos futuros, los chips mejores, más datos y mejores algoritmos contribuirán a alcanzar el umbral de Ilya.
No tenemos idea de cómo alinear una inteligencia artificial así (incluso [OpenAI admite esto](https://youtu.be/L_Guz73e6fw?t=1477)), y las consecuencias de tener una superinteligencia mal alineada probablemente serán [catastróficas](/xrisk).

## Actuar {#act}



Nadie sabe con certeza cuándo alcanzaremos el umbral de Ilya.
Pero las [apuestas son demasiado altas](/xrisk) como para asumir que tenemos mucho tiempo.
Necesitamos actuar sobre la pequeña posibilidad de que podamos estar a solo unos meses de distancia.
Necesitamos [pausar el desarrollo de inteligencia artificial de frontera](/proposal) ahora mismo.
Depende de cada uno de nosotros [tomar medidas](/action) y asegurarnos de que no nos sorprendan.