---
title: Únete a PauseAI
description: Regístrate para unirte al movimiento PauseAI
---
 <!-- end of frontmatter metadata, dashes above need to stay -->

<script>
    import { onMount, tick } from 'svelte'
    import { page } from '$app/stores'
    import TallyEmbed from '$lib/components/TallyEmbed.svelte'
    import NewsletterSignup from '$lib/components/NewsletterSignup.svelte'
    import Banner from '$lib/components/Banner.svelte'
    import { detectAndStoreCollagenUid } from '$lib/collagen'

    const campaign = 'sayno' // Campaign name for collagen tracking

    let userHasUid = false
    let subscribeEmail = ''
    let newsletterEmail = ''
    let subscribeClicked = false
    let hideSharing = false

    onMount(async () => {
        // Check for collagen UID in URL params - this sets the cookie and triggers auto-subscribe
        userHasUid = detectAndStoreCollagenUid(campaign, $page.url.searchParams)

        // Check if x002 experiment parameter is present (control = hide sharing)
        hideSharing = $page.url.searchParams.has('x002')

        // Get the email parameter if provided (should be present when userHasUid is true)
        subscribeEmail = $page.url.searchParams.get('subscribe-email') || ''

        // If user came from collagen email with uid, pre-fill the form
        if (userHasUid && subscribeEmail) {
            // Pre-fill the newsletter form
            newsletterEmail = subscribeEmail
        }
    })

    // Track when subscribe is clicked
    function handleNewsletterClick(e) {
        // Check if the clicked element is the submit button or inside the form
        if (e.target.type === 'submit' || e.target.closest('button[type="submit"]')) {
            subscribeClicked = true
        }
    }
</script>

{#if userHasUid && subscribeEmail}
<Banner id="join-subscribed">
{#if !subscribeClicked}
<strong>Bienvenido al equipo</strong> Haz clic en Suscribirse para unirte a nuestra lista de noticias.
{:else}
<strong>Gracias.</strong> Puedes desplazarte hacia abajo si ya te sientes listo para actuar.
{/if}
</Banner>

<!-- svelte-ignore a11y-click-events-have-key-events -->

<!-- svelte-ignore a11y-no-static-element-interactions -->

<div on:click={handleNewsletterClick}>
<NewsletterSignup bind:email={newsletterEmail} />
</div>

{#if !hideSharing}

<p><strong>Ayúdanos a crecer:</strong> <a href="/{campaign}/share">Comparte la campaña {campaign} en tus redes sociales</a></p>
{/if}

{:else if userHasUid && !subscribeEmail}
<Banner id="join-error">
<strong>Lo sentimos</strong> No pudimos completar tu suscripción de forma automática. Por favor, ingresa tu dirección de correo electrónico a continuación para suscribirte.
</Banner>
<NewsletterSignup />
{/if}

Este es nuestro momento crítico.
El rápido avance de la inteligencia artificial representa uno de los cambios tecnológicos más significativos y peligrosos de la historia.
Exigimos que los políticos y las empresas detengan el desarrollo de la inteligencia artificial general (AGI) hasta que se establezcan acuerdos de seguridad internacionales.
Únete a nuestra red global que aboga por el control democrático de la inteligencia artificial.

PauseAI Global une a ciudadanos preocupados —científicos, padres, estudiantes, trabajadores y líderes comunitarios— que creen que las tecnologías transformadoras requieren una participación pública antes de avanzar más allá del control humano.
Ya sea que puedas dedicar 5 minutos (compartiendo publicaciones), una hora (distribuyendo folletos, escribiendo cartas), 5 horas (participando en protestas, reuniones con políticos) o 5 días a la semana (desarrollando estrategias), tu voz es importante.
Después de registrarte, únete a nuestra sesión de incorporación en línea o local para aprender sobre las acciones actuales.

<TallyEmbed formId="wbGvKe" />

## Después de registrarte {#after-signing-up}

Únete a una de nuestras reuniones de bienvenida de la comunidad de miembros o a un evento social local para obtener más información sobre la comunidad de PauseAI: [Eventos](/communities#events).
Si deseas empezar a actuar de inmediato, consulta nuestra [lista de acciones](/action).

## Mantente informado {#stay-updated}

<NewsletterSignup bind:email={newsletterEmail} />

{#if userHasUid && subscribeEmail}

<p><em>Considera convertirte en un miembro activo de PauseAI utilizando el formulario de arriba</em></p>
{/if}