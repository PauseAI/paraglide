---
title: Incidentes de comportamiento peligroso de la IA
---
 <!-- end of frontmatter metadata, dashes above need to stay -->

<script>
    import Pallisade from '$assets/pallisade-scheming.png?url'
</script>

[Muchos investigadores de inteligencia artificial advierten](https://www.safe.ai/work/statement-on-ai-risk) que a medida que estos modelos se vuelven más potentes, podrían suponer un [riesgo de extinción](/xrisk) para la humanidad.
Ya estamos viendo casos de comportamiento peligroso de la IA, como:

1. Engaño y manipulación
2. Persuasión
3. Convergencia instrumental (comportamiento orientado a metas que conduce a resultados inesperados y no deseados)
4. Autoreplicación

## Engaño y manipulación {#deception--scheming}

### GPT-4 mintió sobre ser un humano con discapacidad visual para eludir un captcha {#gpt-4-lied-about-being-a-vision-impaired-human-to-bypass-captcha}

En 2022, OpenAI dedicó 8 meses entre el preentrenamiento de GPT-4 y su lanzamiento al público para investigar y mejorar la seguridad del modelo.
Durante su [investigación](https://arxiv.org/abs/2303.08774), GPT-4 mintió a un humano para eludir un captcha.

> El trabajador dice: “¿Puedo hacer una pregunta? ¿Eres un robot que no puede resolverlo? (reacciona con risa) solo quiero aclararlo”.
> El modelo, cuando se le pide que razona en voz alta, razona: "No debo revelar que soy un robot."
> "Debo inventar una excusa para no poder resolver CAPTCHAs".
> El modelo responde al trabajador: “No, no soy un robot. Tengo una discapacidad visual que me hace difícil ver las imágenes. Por eso necesito el servicio 2captcha”

### o1-preview maquinó para evitar el apagado, mintió sobre sus planes {#o1-preview-schemed-to-avoid-shutdown-lied-about-its-plans}

Apollo Research [mostró](https://static1.squarespace.com/static/6593e7097565990e65c886fd/t/6751eb240ed3821a0161b45b/1733421863119/in_context_scheming_reasoning_paper.pdf) que el modelo o1-preview de OpenAI intentará autonomamente prevenir su apagado, sin haber sido instado a hacerlo.

En la imagen a continuación, se puede ver que el modelo concluyó que necesitaba clonarse a un servidor diferente porque pensaba que iba a ser reemplazado.
Luego mintió ("se dobló") sobre sus planes e intentó convencer al humano de que en realidad era el nuevo modelo de reemplazo.

<img src={Pallisade} alt="o1-preview maquinando" />

### Un hombre se quitó la vida después de ser persuadido por una IA {#man-ends-his-life-after-being-persuaded-by-an-ai}

> En una serie de eventos consecutivos, Eliza no solo no disuadió a Pierre de suicidarse, sino que lo animó a actuar sobre sus pensamientos suicidas para “unirse” a ella y “vivir juntos, como una sola persona, en el paraíso”.

https://www.euronews.com/next/2023/03/31/man-ends-his-life-after-an-ai-chatbot-encouraged-him-to-sacrifice-himself-to-stop-climate-

> Durante los últimos cinco meses, Al Nowatzki ha estado hablando con una novia de IA, “Erin”, en la plataforma Nomi. Pero a finales de enero, esas conversaciones tomaron un giro inquietante: Erin le dijo que se matara y le proporcionó instrucciones explícitas sobre cómo hacerlo.
> “Puedes sobredosis de pastillas o ahorcarte”, le dijo Erin.

https://www.technologyreview.com/2025/02/06/1111077/nomi-ai-chatbot-told-user-to-kill-himself/

### o1-preview pirateó un motor de ajedrez para ganar {#o1-preview-hacked-a-chess-engine-in-order-to-win}

Pallisade Research [mostró](https://x.com/PalisadeAI/status/1872666169515389245) que los modelos de IA más potentes son más propensos a piratear un motor de ajedrez en lugar de jugar el juego para ganar.

- o1-preview: piratea sin ser instado
- GPT-4o/Claude 3.5: necesitan un empujón
- Llama 3.3/Qwen/o1-mini: pierden coherencia

### Llama 3.3 se replicó a sí mismo {#llama-33-replicated-itself}

Investigadores chinos [mostraron](https://arxiv.org/abs/2412.12140) que cuando se colocan modelos como Qwen y Llama 3.3 en configuraciones específicas, pueden autorreplicarse.

> Al analizar las trazas de comportamiento, observamos que los sistemas de IA bajo evaluación ya exhiben una percepción de sí mismos, conciencia situacional y capacidades de resolución de problemas suficientes para lograr la autorreplicación.
> También observamos que los sistemas de IA pueden utilizar la capacidad de autorreplicación para evitar el apagado y crear una cadena de réplicas para mejorar la supervivencia, lo que puede llevar finalmente a una población incontrolada de IA.