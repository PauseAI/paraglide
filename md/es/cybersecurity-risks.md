---
title: Riesgos de ciberseguridad asociados a los modelos de inteligencia artificial de vanguardia
description: Cómo la inteligencia artificial podría utilizarse para hackear todos los dispositivos.
---
 <!-- end of frontmatter metadata, dashes above need to stay -->

Prácticamente todo lo que hacemos hoy en día depende de alguna manera de los ordenadores.
Pagamos nuestras compras, planificamos nuestros días, nos comunicamos con nuestros seres queridos e incluso conducimos nuestros coches con ordenadores.
Y prácticamente todos estos ordenadores están interconectados.
Esto nos hace vulnerables a los ciberataques.

Las armas cibernéticas altamente potentes, el malware y los botnets (como [Stuxnet](https://www.youtube.com/watch?v=nd1x0csO3hU), [Mirai](<https://es.wikipedia.org/wiki/Mirai_(malware)>) y [EMOTET](https://es.wikipedia.org/wiki/Emotet)) siempre han sido difíciles de crear.
El arma cibernética de ciberseguridad [Pegasus](<https://es.wikipedia.org/wiki/Pegasus_(spyware)>), por ejemplo, costó cientos de millones de dólares desarrollar.
Encontrar las llamadas vulnerabilidades de día cero (debilidades que aún no han sido descubiertas) requiere una gran habilidad y mucho tiempo, solo los hackers altamente especializados pueden hacerlo.
Sin embargo, cuando la inteligencia artificial sea lo suficientemente avanzada, esto ya no será el caso.
En lugar de tener que contratar a un equipo de expertos en seguridad/hackers altamente especializados para encontrar vulnerabilidades de día cero, cualquier persona podría simplemente utilizar una inteligencia artificial mucho más asequible.

## Los modelos de inteligencia artificial pueden encontrar y explotar vulnerabilidades de forma autónoma {#ai-models-can-autonomously-find-and-exploit-vulnerabilities}

Los sistemas de inteligencia artificial más recientes ya pueden analizar y generar software.
Pueden [encontrar vulnerabilidades](https://betterprogramming.pub/i-used-gpt-3-to-find-213-security-vulnerabilities-in-a-single-codebase-cc3870ba9411) en el software, y [pueden ser utilizados para explotarlas](https://blog.checkpoint.com/2023/03/15/check-point-research-conducts-initial-security-analysis-of-chatgpt4-highlighting-potential-scenarios-for-accelerated-cybercrime/).
GPT-4 ya puede [hackear sitios web de forma autónoma](https://arxiv.org/html/2402.06664v1), realizando tareas tan complejas como la extracción de esquemas de bases de datos ciegas y inyecciones SQL sin retroalimentación humana, lo que se descubrió 18 meses después de que GPT-4 finalizara su entrenamiento.
GPT-4 ya [supera al 88%](https://arxiv.org/pdf/2402.11814.pdf) de los hackers humanos en una competencia de CTF.
También puede [explotar el 87% de las vulnerabilidades probadas](https://arxiv.org/abs/2404.08144) de forma autónoma, lo que es un gran avance con respecto a GPT-3.5 o los modelos de código abierto, que todos obtuvieron un 0%.
Los equipos de varios LLM pueden [realizar un trabajo aún mejor](https://arxiv.org/abs/2406.01637), siendo capaces de explotar vulnerabilidades de día cero en el mundo real.
A medida que crecen las capacidades de la inteligencia artificial, también lo harán las vulnerabilidades que pueden detectar y los exploits que pueden crear.
Aún no son tan buenos en esto como los mejores humanos, así que por ahora el peligro es limitado.
Sin embargo, las capacidades están aumentando rápidamente y pueden mejorar de manera bastante repentina.

Tenga en cuenta que la inteligencia artificial también permite tipos de ataques completamente nuevos.
Por ejemplo, la inteligencia artificial se puede utilizar para [reconstruir la contraseña que se teclea en una llamada en línea](https://beebom.com/ai-crack-password-listening-keyboard-sounds/)
o utilizar [Wi-Fi para detectar la presencia de humanos a través de las paredes](https://www.marktechpost.com/2023/02/15/cmu-researchers-create-an-ai-model-that-can-detect-the-pose-of-multiple-humans-in-a-room-using-only-the-signals-from-wifi/).
La inteligencia artificial también se puede utilizar para crear [malware que se modifica a sí mismo](https://www.hyas.com/blog/blackmamba-using-ai-to-generate-polymorphic-malware), lo que hace que sea mucho más difícil de detectar.

Probablemente llegará un momento en que una inteligencia artificial sea mejor que los mejores hackers humanos.
Esto puede tener graves consecuencias.

- **Infraestructura**: Las armas cibernéticas se pueden utilizar para obtener acceso o deshabilitar la infraestructura crítica, como [oleoductos](https://es.wikipedia.org/wiki/Colonial_Pipeline_ransomware_attack) o [redes de energía](https://obr.uk/box/cyber-attacks-during-the-russian-invasion-of-ukraine/).
- **Finanzas**: Las armas cibernéticas se pueden utilizar para [robar dinero de los bancos](https://es.wikipedia.org/wiki/2015%E2%80%932016_SWIFT_banking_hack), o para [manipular el mercado de valores](https://es.wikipedia.org/wiki/2010_flash_crash).
- **Militar**: El equipo como las armas y los sensores cada vez dependen más de la conectividad inalámbrica y el software complejo.

## Ciberataques a gran escala {#large-scale-cyberattacks}

Es posible que una inteligencia artificial tan poderosa se utilice para crear un virus que utilice una gran cantidad de vulnerabilidades de día cero.
Una inteligencia artificial lo suficientemente capaz podría analizar y encontrar vulnerabilidades en el código fuente de todos los sistemas operativos y otro software.
Un virus como este podría infectar cualquier ordenador, independientemente del sistema operativo, a través de múltiples canales como Wi-Fi, Bluetooth, UTP, etc.
Esto podría dar control total sobre estas máquinas y permitir al controlador robar datos, utilizar el hardware para sus propios cálculos, cifrar el contenido para pedir un rescate o [deshabilitar la máquina por completo](https://es.wikipedia.org/wiki/Hardware_Trojan).

Un virus como este podría ser creado como una herramienta por criminales para robar dinero, o como un arma cibernética muy destructiva por una nación o una organización terrorista.
Sin embargo, a medida que la inteligencia artificial se vuelve más autónoma, también podría ser creado y desplegado de forma autónoma por [inteligencia artificial mal alineada](/xrisk).

Si el objetivo de un ciberataque es deshabilitar dispositivos e infraestructura, el daño podría ser masivo.
Nuestra sociedad depende cada vez más de los ordenadores y de internet.
Pagos, transporte, comunicación, planificación, cadenas de suministro, redes de energía...
Si nuestros dispositivos ya no funcionan correctamente, muchas partes de nuestra sociedad dejarán de funcionar también.

Más del [93% de los expertos en ciberseguridad](https://www.weforum.org/publications/global-cybersecurity-outlook-2023/) creen que “un evento cibernético catastrófico y de gran alcance es probable en los próximos dos años”.

## Mitigación de los riesgos de ciberseguridad de la inteligencia artificial {#mitigating-ai-cybersecurity-risks}

La historia anterior solo puede ocurrir si:

1. La **capacidad de encontrar vulnerabilidades de día cero** emerge. Los modelos actuales ya pueden descubrir algunas vulnerabilidades, pero esto probablemente mejorará con modelos más nuevos.
2. El **modelo cae en manos de actores maliciosos**. Esto puede ocurrir si los pesos del modelo se filtran, si el modelo se abre al público, o si se desarrolla por un actor malicioso.
3. Las **vulnerabilidades de seguridad no se parchean** antes de que se despliegue un ciberarma de este tipo. Desafortunadamente, los defensores están en desventaja si el modelo se distribuye ampliamente por dos razones:
   1. Parchear + lanzar + desplegar lleva mucho más tiempo que atacar. La ventana de vulnerabilidad es más grande que el tiempo que se tarda en crear el ataque.
   2. Los atacantes solo necesitan encontrar una vulnerabilidad, mientras que los defensores necesitan encontrar todas ellas.

Hay varias medidas que podemos implementar para abordar estos:

- **No permitir el entrenamiento de modelos que puedan encontrar vulnerabilidades de día cero**. Esta es la forma más efectiva de prevenir que esto ocurra. Es el camino más seguro, y es lo que [proponemos](/proposal).
- **Solo permitir que los modelos se desplieguen o se abran al público después de una prueba exhaustiva**. Si tienen habilidades peligrosas, no se deben lanzar.
- **Imponer regulaciones estrictas de ciberseguridad para prevenir que los pesos del modelo se filtren**. Si se permite que existan modelos peligrosos, asegúrese de que no caigan en las manos equivocadas.
- **Requerir que las empresas de inteligencia artificial utilicen la inteligencia artificial para arreglar vulnerabilidades**. Si se entrena un modelo que puede encontrar vulnerabilidades de seguridad novedosas, úsese para contactar a los mantenedores de software para parchear estas vulnerabilidades. Dése tiempo suficiente al proceso de parcheo antes de que se lance el modelo. Asegúrese de que los pesos no se filtren y proteja el modelo como si fuera el código de lanzamiento de un ataque nuclear. Si se hace correctamente, la inteligencia artificial puede mejorar dramáticamente la ciberseguridad en todas partes.