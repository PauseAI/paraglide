---
title: Únete a PauseAI
description: Regístrate para unirte al movimiento PauseAI
---
 <!-- end of frontmatter metadata, dashes above need to stay -->

<script>
    import TallyEmbed from '$lib/components/TallyEmbed.svelte'
    import NewsletterSignup from '$lib/components/NewsletterSignup.svelte'
    import CollagenSignup from '$lib/components/CollagenSignup.svelte'

    let newsletterEmail = ''
    let userHasUid = false
    let subscribeEmail = ''
</script>

<CollagenSignup bind:newsletterEmail bind:userHasUid bind:subscribeEmail />

Este es un momento crucial.
El rápido avance de la inteligencia artificial representa uno de los cambios tecnológicos más significativos y peligrosos de la historia.
Exigimos que los políticos y las empresas suspendan el desarrollo de la inteligencia artificial general (AGI) hasta que se establezcan acuerdos internacionales de seguridad.
Únete a nuestra red global que defiende el control democrático de la inteligencia artificial.

PauseAI Global reúne a ciudadanos preocupados —científicos, padres, estudiantes, trabajadores y líderes comunitarios— que creen que las tecnologías transformadoras requieren una participación pública antes de avanzar más allá del control humano.
Puedes contribuir dedicando 5 minutos (compartiendo publicaciones), una hora (distribuyendo folletos, escribiendo cartas), 5 horas (participando en protestas, reuniones con políticos) o 5 días a la semana (desarrollando estrategias); tu voz es importante.
Después de registrarte, únete a nuestra sesión de incorporación en línea o presencial para aprender sobre las acciones actuales.

<TallyEmbed formId="wbGvKe" />

## Después de registrarte {#after-signing-up}

Únete a una de nuestras reuniones de bienvenida de la comunidad de miembros o a un evento social local para conocer más sobre la comunidad de PauseAI: [Eventos](/communities#events).
Si deseas empezar a actuar de inmediato, consulta nuestra [lista de acciones](/action).

## Mantente informado {#stay-updated}

<NewsletterSignup bind:email={newsletterEmail} />

{#if userHasUid && subscribeEmail}

<p><em>Considera convertirte en un miembro activo de PauseAI utilizando el formulario de arriba.</em></p>
{/if}