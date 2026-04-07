---
title: 4 Niveles de Regulación de Seguridad de la Inteligencia Artificial
description: Un marco para pensar en cómo mitigar los riesgos de los sistemas de inteligencia artificial potentes
image: /4levels.png
showImage: false
---

A medida que aumentan las capacidades de la inteligencia artificial, también aumentan los riesgos que estos sistemas plantean a la humanidad.
Muchos científicos ya han advertido sobre el riesgo de extinción humana.

En este artículo, exploraremos nuestro marco de 4 niveles para pensar en cómo regular la seguridad de la inteligencia artificial.

<div style="max-width: 500px">

![4 Niveles de regulación de seguridad de la inteligencia artificial](/4levels-cropped.png)

</div>

## Canalización de la inteligencia artificial como marco para la gobernanza de la seguridad {#ai-pipeline-as-a-framework-for-safety-governance}

La canalización de creación de la inteligencia artificial consiste en varias etapas, cada una de las cuales se puede regular de diferentes maneras.
Esta canalización consiste en:

- **Hardware y algoritmos**, que se utilizan para entrenar modelos de inteligencia artificial
- **Ejecuciones de entrenamiento**, donde se utilizan el hardware y los algoritmos para crear un modelo
- **Despliegue**, donde se comparte el modelo entrenado con el público
- **Uso**, donde se utiliza el modelo desplegado por individuos y empresas

Cuanto más tarde se regule en la canalización, mayores son los riesgos que enfrentamos.
Si queremos un alto nivel de seguridad, debemos regular más temprano en la canalización.
Por eso, cuando ascendemos por los 4 niveles de regulación de la inteligencia artificial, retrocedemos en la canalización de creación de la inteligencia artificial.

## Nivel 1: Regular el uso {#level-1-regulate-usage}

Ejemplos:

- **Prohibir el uso de entornos de ejecución de agentes autónomos** (como AutoGPT)
- **Prohibir instrucciones peligrosas**

Estas medidas están destinadas a prevenir que los usuarios realicen acciones peligrosas o dañinas con los modelos de inteligencia artificial.
En este nivel, la responsabilidad recae en los usuarios de los modelos, no en los creadores.
Dependemos de que todos los usuarios (potencialmente millones) cumplan con las regulaciones.
Esto solo ofrece un nivel de protección muy bajo contra los peligros de la inteligencia artificial.

## Nivel 2: Regular el despliegue {#level-2-regulate-deployment}

Ejemplos:

- **Requisitos de prueba de penetración**. Esto significa que antes de desplegar un modelo de inteligencia artificial, se prueba con un equipo de prueba para ver si se puede piratear o abusar.
- **Prohibir el despliegue y la publicación de modelos** con capacidades peligrosas.

Al regular los despliegues, prevenimos que los modelos peligrosos estén disponibles.
Esto significa que la responsabilidad recae en los creadores de los modelos.
Esta es una situación más segura que el nivel 1, porque ahora dependemos de un grupo mucho más pequeño de personas para que actúen de manera responsable.

Sin embargo, todavía permitimos que ocurran ejecuciones de entrenamiento peligrosas, por lo que pueden ocurrir accidentes en los laboratorios de inteligencia artificial (incluyendo fugas de modelos de inteligencia artificial peligrosos o la creación de inteligencia artificial descontrolada).

## Nivel 3: Regular las ejecuciones de entrenamiento {#level-3-regulate-training-runs}

Ejemplos:

- **Requerir prueba de seguridad** antes de otorgar permiso para entrenar un modelo determinado. Esto puede incluir una prueba formal de alineación. [Este artículo detalla algunos de los problemas de seguridad actuales](https://www.lesswrong.com/posts/mnoc3cKY3gXMrTybs/a-list-of-core-ai-safety-problems-and-how-i-hope-to-solve).
- Establecer un **límite de escala para el entrenamiento de nuevos modelos** (por ejemplo, un máximo de operaciones de punto flotante utilizadas). Esto también puede incluir el proceso de ajuste fino.
- **Requerir una licencia** para entrenar modelos de inteligencia artificial (por encima de un cierto tamaño / con ciertas capacidades).
- **Prohibir el entrenamiento con tipos de datos peligrosos**. Algunos tipos de datos de entrenamiento pueden llevar a capacidades peligrosas, como el pirateo o la creación de armas biológicas. Podríamos prohibir el entrenamiento con datos que contengan este tipo de conocimiento.
- **Prohibir el entrenamiento con datos con derechos de autor**. Esto no apunta directamente a los datos inseguros, pero sí limita la cantidad de datos que se pueden utilizar, lo que significa que nos da tiempo para averiguar cómo construir modelos de inteligencia artificial seguros.

Al regular las ejecuciones de entrenamiento, prevenimos que se creen modelos peligrosos en primer lugar.
Esto prevenirá accidentes en los laboratorios de inteligencia artificial que cumplan con las regulaciones.

Sin embargo, todavía permitimos la distribución de hardware y algoritmos que se pueden utilizar para entrenar modelos peligrosos, por lo que todavía dependemos de que los creadores de estos modelos actúen de manera responsable.

## Nivel 4: Regular el hardware y los algoritmos {#level-4-regulate-hardware--algorithms}

Ejemplos:

- **Limitar la distribución de hardware de entrenamiento**. El hardware especializado para entrenar modelos de inteligencia artificial se está convirtiendo rápidamente en el producto más importante de los fabricantes de chips. La cadena de suministro de este hardware es muy centralizada y el hardware es muy costoso. Esto significa que es [relativamente fácil regular](https://arxiv.org/abs/2303.11341) la distribución de este hardware.
- **Prohibir la publicación de arquitecturas de entrenamiento novedosas**. Las nuevas arquitecturas de entrenamiento de inteligencia artificial pueden llevar a aumentos dramáticos en las capacidades. El modelo Transformer, por ejemplo, permitió virtualmente todos los progresos recientes en inteligencia artificial. Podríamos limitar la publicación de tales arquitecturas para prevenir saltos repentinos en las capacidades.

Al regular también el hardware y los algoritmos, no solo hacemos que sea ilegal, sino también muy difícil entrenar modelos peligrosos.
Esto nos brinda la mejor protección contra los riesgos de la inteligencia artificial.

## Limitaciones {#limitations}

Tenga en cuenta que este marco no es perfecto y no todos los tipos posibles de regulación de la inteligencia artificial encajan perfectamente en uno de los niveles mencionados.
Por ejemplo, la responsabilidad legal para los creadores de modelos se puede clasificar como una regulación de "uso" de nivel 1, ya que se aplica después del despliegue, pero también se puede clasificar como una regulación de nivel 2 o 3, ya que puede ayudar a los creadores a reconsiderar si un modelo determinado debe ser desplegado o entrenado en primer lugar.

## Conclusión {#conclusions}

En este artículo, hemos explorado nuestro marco de 4 niveles para pensar en cómo regular la seguridad de la inteligencia artificial.
Utilizando este modelo, podemos razonar más fácilmente sobre la efectividad de la regulación de la inteligencia artificial en las diferentes etapas de la canalización de creación de la inteligencia artificial.
También podemos ver que los dos primeros niveles no ofrecen mucha protección contra los riesgos (existenciales) de la inteligencia artificial.
Prevenir las ejecuciones de entrenamiento peligrosas y regular el hardware y los algoritmos son formas mucho más confiables de garantizar la seguridad.