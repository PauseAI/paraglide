---
title: Construyendo el Botón de Pausa
description: ¿Cómo sería un botón de pausa para la IA? ¿Cómo podemos evitar realmente la creación de una superinteligencia?
---
 <!-- end of frontmatter metadata, dashes above need to stay -->

Si permitimos la creación de una IA superinteligente, estamos [poniendo en peligro todas las vidas en la Tierra](/xrisk).
Cuando hablamos de un botón de pausa, nos referimos a [implementar una prohibición internacional para la creación de una IA superinteligente](/proposal).
Algunos argumentan que es demasiado pronto para activar el botón de pausa (no [estamos de acuerdo](/urgency)), pero la mayoría de los expertos parecen estar de acuerdo en que puede ser beneficioso pausar si los avances son demasiado rápidos.
Pero por ahora, _no tenemos un botón de pausa_.
Así que debemos empezar a pensar en cómo funcionaría y cómo podemos implementarlo.
Afortunadamente, crear una IA superinteligente es difícil y requiere muchos recursos.

_Esta página es un trabajo en progreso gestionado por el equipo de Construyendo el Botón de Pausa en PauseAI, como parte del AI Safety Camp 2025._

## Contenido {#contents}

## La Carrera: por qué necesitamos cooperación internacional {#the-race-why-we-need-international-cooperation}

No esperamos que ningún país pueda implementar un botón de pausa por sí solo.
Los incentivos económicos son demasiado fuertes, y frenar el desarrollo de la IA pondría a un país en desventaja económica y geopolítica.
Los costos de subinvertir en seguridad se distribuyen globalmente, mientras que los beneficios de acelerar son locales.
Este problema de teoría de juegos a veces se conoce como "Moloch" o "Carrera hacia el Abismo".

La única salida es tener un _acuerdo internacional_.
Es por eso que estamos tan enfocados en las [cumbres](/summit): estos son los eventos en los que los líderes mundiales se reúnen y trabajan en una solución global.
O al menos, eso es lo que queremos que hagan.
Hasta ahora, todas las cumbres de seguridad de la IA no han llevado a una regulación significativa.
Depende de ti y de mí [convencerlos](/action).

## Gobernanza de la Computación {#compute-governance}

Para entrenar un modelo de lenguaje grande como GPT-4, se necesita mucho hardware especializado y costoso.
GPT-4 se entrenó con 25.000 GPU Nvidia A100, que cuestan $10.000 cada una.
Aunque hay innovaciones que permiten un entrenamiento más eficiente, la tendencia es que los modelos de IA están creciendo cada vez más.

La escala de los requisitos de entrenamiento de IA moderna es enorme.
Microsoft acaba de anunciar un plan para [construir una central nuclear](https://www.theverge.com/2024/9/20/24249770/microsoft-three-mile-island-nuclear-power-plant-deal-ai-data-centers) para satisfacer las necesidades de energía de su IA.
Afortunadamente para nosotros, esto significa que las corridas de entrenamiento de IA son difíciles de ocultar, al menos en el futuro cercano.

Al controlar y monitorear la cadena de suministro de chips de IA, los gobiernos o otros organismos reguladores pueden asegurarse de que nadie inicie una corrida de entrenamiento de IA peligrosa.
Vamos a profundizar en los diferentes puntos de estrangulamiento en esta cadena de suministro.

### Puntos de estrangulamiento en la cadena de suministro de chips {#choke-points-in-the-chip-supply-chain}

Es difícil exagerar la complejidad y la interdependencia de la cadena de suministro de chips de IA.
Está compuesta por varias empresas altamente especializadas, algunas de las cuales son las únicas en el mundo que pueden producir ciertos componentes.
Esto es una gran noticia para la gobernanza.
A través del hardware, podemos regular las corridas de entrenamiento.
Vamos a profundizar en los diferentes puntos de estrangulamiento en la cadena de suministro de chips de IA.

#### Obleas de silicio: Shin-Etsu, Sumco, Siltronic {#silicon-wafers-shin-etsu-sumco-siltronic}

#### Litografía: ASML y SMEE {#lithography-asml--smee}

Todos los chips modernos se fabrican utilizando máquinas de litografía: máquinas enormes que cuestan 200 millones de dólares cada una y que proyectan luz sobre una oblea de silicio.
Este proceso de litografía es una de las partes más complejas y costosas del proceso de fabricación de chips.
Los chips de IA de alta gama se fabrican todos utilizando litografía EUV, y ASML es la única empresa que fabrica estas máquinas.
Esta empresa holandesa es uno de los puntos de estrangulamiento potencialmente más importantes para la gobernanza de la IA.
Estas máquinas son increíblemente complejas y requieren mucha experiencia para construir y mantener.
Cabe destacar que tienen [interruptores de apagado remoto](https://www.businessinsider.com/asml-tsmc-semiconductor-chip-equipment-kill-switch-china-invade-taiwan-2024-5) (principalmente en caso de que Taiwán sea invadida), así que en algunos aspectos importantes, el botón de pausa ya está construido.

El gobierno holandés ha establecido controles de exportación estrictos sobre sus máquinas de litografía EUV, que requieren permisos para exportar.
Estos controles de exportación se han establecido principalmente para frenar las ambiciones de China en el sector de los chips.
Los [EE. UU., Japón y los Países Bajos](https://apnews.com/article/technology-district-of-columbia-netherlands-china-business-6801d6c5f65b0bc1df6186e2e89a6f7d) están en un acuerdo (no público) destinado a restringir las exportaciones de chips y litografía a China.

La empresa china SMEE está tratando de ponerse al día, pero no puede fabricar sus propias máquinas EUV.
Sus máquinas DUV están [atascadas en 28nm](https://www.scmp.com/tech/big-tech/article/3278235/chinese-chip-making-shows-progress-new-euv-patent-domestic-lithography-champion), lo que está generaciones por detrás del proceso EUV de 5nm de ASML, por no hablar de las máquinas de 2nm que ASML está desarrollando.
Así que SMEE no puede producir chips de IA modernos.

En otras palabras: ASML es un punto de estrangulamiento fundamental en la cadena de suministro de chips de IA.

#### Óptica: Zeiss {#optics-zeiss}

Las máquinas EUV de ASML utilizan espejos y lentes fabricados por la empresa alemana Zeiss.
En 2016, ASML [compró](https://optics.org/news/7/11/11) una participación del 25% en Zeiss, y las dos empresas tienen una relación muy estrecha.
Es probable que ninguna otra empresa pueda producir estas ópticas.

#### Fotoresistencia {#photoresist}

La fotoresistencia es un producto químico que se utiliza para grabar los patrones en la oblea de silicio.
Las empresas japonesas son dominantes en este campo.

Las empresas más importantes en este campo son:

- JSR (Japón)
- Shin-Etsu (Japón)
- Tokyo Ohka Kogyo (Japón)
- DuPont (EE. UU.)

#### Interconexión y envasado: ASE {#interconnect--packaging-ase}

Cuando un chip sale de una fábrica, necesita ser "envasado".
ASE es probablemente la empresa de interconexión más grande para chips de IA.

#### Fabricación: TSMC, Samsung y SMIC {#fabrication-tsmc-samsung-and-smic}

Construir una "fábrica" (una fábrica de chips) es asombrosamente difícil: no tiene tolerancia para partículas de polvo, requiere el equipo de alta tecnología más caro y tiene una cadena de suministro muy compleja.
Una fábrica moderna cuesta alrededor de 10 a 20 mil millones de dólares para fabricar.

La Taiwan Semiconductor Manufacturing Company cuenta con [alrededor del 90%](https://www.fool.com/investing/2025/02/03/meet-the-monster-stock-that-continues-to-crush-the/) de los chips de IA modernos, que son todos los chips fabricados con una precisión de 7nm o mejor.
Samsung es la única otra fábrica que puede producir chips de IA modernos.

Pero la china SMIC está avanzando rápidamente - ya tiene un [proceso funcional de 7nm](https://wccftech.com/smic-to-limit-huawei-to-7nm-chips-until-2026-reducing-advancement/).
Debido a los controles de exportación de EE. UU. / NL, SMIC no puede comprar máquinas EUV de ASML, y ahora también está restringida para comprar las máquinas DUV más antiguas.
En junio de 2024, un [informe](https://evertiq.com/news/55926) mostró que SMIC puede producir chips de 5nm utilizando hardware DUV,
y ahora puede producir chips de IA de 7nm (unos tres años por detrás del proceso de 4nm que las máquinas EUV de ASML pueden producir), pero la litografía de SMIC está plagada de rendimientos bajos.

#### Fabricación de memoria: Micron, SK Hynix {#memory-fabrication-micron-sk-hynix}

Los chips de IA requieren mucha memoria de alta velocidad (HBM), que es el tipo de memoria más avanzado.
Actualmente, la competencia en el mercado de HBM de alta gama se limita a solo unos pocos jugadores clave.
La producción de las variantes más modernas y potentes (HBM3 y HBM3E, que se utilizan en aceleradores de IA, GPU y aplicaciones HPC) está dominada por:

- SK Hynix – El líder del mercado en la producción de HBM, que suministra HBM3 y HBM3E a Nvidia.
- Samsung – Un competidor fuerte que trabaja para asegurar los contratos de Nvidia y otras empresas de IA.
- Micron – El tercer jugador importante, que está aumentando la producción de HBM3E en 2024 para competir con SK Hynix y Samsung.

Estas empresas también utilizan máquinas EUV de ASML para producir sus HBMs.

#### Diseño de chips de IA: Nvidia, AMD, Intel, Google, Apple {#ai-chip-design-nvidia-amd-intel-google-apple}

Las empresas más famosas en esta página son todas diseñadoras de chips.
Y hay nuevas empresas, como Cerebras y Groq, que están diseñando chips específicamente para IA.
Cabe destacar que algunas de estas empresas utilizan procesos relativamente obsoletos para producir sus chips, como Groq, que utilizó un proceso de 14nm, lo que es un punto de estrangulamiento potencial para la gobernanza.

### Gobernanza en el chip {#on-chip-governance}

- El artículo ["Chips seguros y gobernables"](https://www.cnas.org/publications/reports/secure-governable-chips) propone un nuevo enfoque para la gobernanza de la IA.
- **[Informes de servidor](https://www.lesswrong.com/posts/uSSPuttae5GHfsNQL/ai-compute-governance-verifying-ai-chip-location)**. Los chips podrían responder a mensajes de servidores de confianza para probar que están dentro de una distancia determinada de una ubicación de confianza. Esto puede ser preciso hasta dentro de decenas de kilómetros.
- **[flexHEGs](https://yoshuabengio.org/wp-content/uploads/2024/09/FlexHEG-Interim-Report_2024.pdf)**: Un nuevo tipo de chip que se puede programar para autodestruirse cuando se cumplen ciertas condiciones. Esto aún está en la fase de investigación y podría tardar mucho en desarrollarse.
- **[Informes basados en firmware](https://arxiv.org/abs/2404.18308)**: Al instalar un firmware personalizado en las GPU, los usuarios deberían obtener una licencia para utilizar la GPU durante más de x ciclos. Esta es una solución más a corto plazo y podría implementarse "dentro de un año"

1. **[Seguimiento de GPS](https://arxiv.org/abs/2408.16074)**: Al instalar un firmware personalizado en las GPU, los usuarios deberían obtener una licencia para utilizar la GPU durante más de x ciclos. Esta es una solución más a corto plazo y podría implementarse "dentro de un año"

### Métodos de verificación - prevención de corridas de entrenamiento a gran escala {#verification-methods---preventing-large-training-runs}

Ahora que hemos identificado varios puntos de estrangulamiento en la cadena de suministro de chips, podemos empezar a pensar en cómo prevenir que se produzcan corridas de entrenamiento a gran escala.
Estos actores mencionados anteriormente pueden ser presionados (por los gobiernos) para asegurarse de que sus productos no se utilicen para corridas de entrenamiento de IA peligrosas.

Pero ¿cómo se puede verificar esto?

El documento ["Métodos de verificación para acuerdos internacionales de IA"](https://arxiv.org/abs/2408.16074) enumera varias opciones:

1. **Detección remota**: Utiliza imágenes satelitales y de infrarrojos para detectar centros de datos por firmas visuales y térmicas. Altamente factible pero limitado por el camuflaje o las instalaciones subterráneas.
2. **Denunciantes**: Confía en que los insiders informen sobre la no conformidad, incentivados por protecciones legales y financieras. Factible pero dependiente del acceso y la voluntad de los insiders de divulgar.
3. **Monitoreo de energía**: Seguimiento del uso de energía para identificar operaciones de IA a gran escala, viable si los patrones son distintos. La factibilidad varía; los datos pueden estar oscurecidos por otras actividades de alta energía.
4. **Análisis de datos aduaneros**: Monitoreo de la importación y exportación de hardware de IA para detectar anomalías. Factible, especialmente para las importaciones, aunque los países con fabricación nacional pueden evitar la detección.
5. **Inteligencia financiera**: Observación de transacciones grandes o inusuales relacionadas con la compra de hardware de IA. Factible si las leyes de privacidad financiera y bancaria lo permiten, a menudo mejor combinado con otros métodos.
6. **Inspecciones de centros de datos**: Inspecciones físicas de los sitios para verificar el cumplimiento de los límites de hardware y los protocolos de seguridad. Efectiva si el país anfitrión acepta las inspecciones; invasiva y exigente en recursos.
7. **Inspecciones de instalaciones de fabricación de semiconductores**: Verificación del cumplimiento de la producción de chips mediante la inspección de instalaciones con hardware relevante. Factible pero requiere recursos y consentimiento del país anfitrión significativos.
8. **Inspecciones de desarrolladores de IA**: Revisión de las instalaciones para verificar el código autorizado, los protocolos de seguridad y los registros de evaluación de IA. Efectiva pero muy invasiva, requiere especialización y cooperación del país.
9. **Seguimiento de la ubicación de los chips**: Seguimiento de los movimientos de los chips de IA para monitorear su despliegue. Factible con acuerdos internacionales, pero se puede evitar desactivando el seguimiento o falsificando los datos de ubicación.
10. **Informes basados en chips**: Incorporación de mecanismos de informe en los chips para alertar si se utilizan más allá de los límites autorizados. Factible pero desafiante, requiere estándares internacionales y desarrollo de hardware; se puede evitar modificando el firmware.

Cada método tiene sus fortalezas y debilidades, a menudo requiriendo enfoques complementarios o cooperación internacional para una implementación efectiva.

Una institución internacional podría establecerse para monitorear estos métodos de verificación y hacer cumplir el botón de pausa.

## Gobernanza de software {#software-governance}

Los chips físicos son nuestro enfoque principal, pero también podemos querer regular el _software_ utilizado para entrenar y ejecutar modelos de IA.
Es posible que los clusters de cómputo más grandes tengan suficiente potencia para entrenar un modelo de IA peligrosamente dañino, pero aún les falta el software.
Vamos a profundizar en los tipos de innovaciones de software que podemos distinguir.

### Innovaciones de software {#software-innovations}

En primer lugar, hay innovaciones en el _entrenamiento_.
La arquitectura Transformer, por ejemplo, permitió que los modelos de IA fueran mucho más capaces, a un costo mucho menor.
El modelo ALBERT basado en Transformer [superó](https://arxiv.org/pdf/2308.04950) al modelo BERT, aunque consistía en 18 veces menos parámetros.
En el futuro, podemos ver arquitecturas aún más eficientes.
También hay innovaciones en los datos que se alimentan a un modelo.

Además de las mejoras en el entrenamiento, hemos visto varias mejoras en el _tiempo de ejecución_.
Técnicas como el pensamiento en cadena, el pensamiento en gráfico y otras pueden dar mejoras drásticas en el rendimiento de los modelos de IA.
Herramientas como AutoGPT pueden convertir chatbots simples en agentes autónomos completamente que navegan por la web, envían correos electrónicos y realizan otras tareas.
El modelo o1 de OpenAI permite capacidades de razonamiento más grandes al permitir que el modelo piense durante más tiempo antes de proporcionar una respuesta.

### Regulación de software {#regulating-software}

El lado de software de la IA es más difícil de controlar que el lado de hardware.
El software es solo información - se puede copiar y distribuir muy fácilmente.
Sin embargo, hemos prohibido la información antes.
La pornografía infantil, por ejemplo, es ilegal de producir, ilegal de distribuir y ilegal de poseer.
Los mismos mecanismos de aplicación de la ley se podrían utilizar para regular el software de IA peligroso.

## Qué pueden hacer los gobiernos para construir el botón de pausa {#what-governments-can-do-to-build-the-pause-button}

1. **Diseñar firmware de GPU compatible con el botón de pausa**. El enfoque para esto se describe en [este documento](https://arxiv.org/abs/2404.18308).
2. **Forzar a los diseñadores de chips de IA a hacer que su firmware sea compatible**.
3. **Establecer un organismo de licencias**. Una autoridad debe ser responsable de emitir licencias a las empresas que desean utilizar chips de IA. Esta autoridad gestiona las claves criptográficas.
4. **Cartografiar dónde están los chips de IA ahora**. Enumerar todas las empresas y centros de datos que tienen chips de IA. Llamarlos y, en el futuro, hacer que actualicen sus chips a firmware compatible.
5. **Invertir en hardware a prueba de manipulaciones y técnicas de gobernanza en el chip**. flexHEGs son un enfoque prometedor aquí.

## Lectura adicional {#further-reading}

- [Mecanismos de gobernanza habilitados por hardware](https://www.rand.org/pubs/working_papers/WRA3056-1.html)
- [Métodos de verificación para acuerdos internacionales de IA](https://arxiv.org/abs/2408.16074)
- [Chips seguros y gobernables](https://www.cnas.org/publications/reports/secure-governable-chips)
- [flexHEGs](https://yoshuabengio.org/wp-content/uploads/2024/09/FlexHEG-Interim-Report_2024.pdf)
- [Informes basados en firmware](https://arxiv.org/abs/2404.18308)