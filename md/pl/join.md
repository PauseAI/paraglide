---
title: Dołącz do PauseAI
description: Zapisz się, aby dołączyć do ruchu PauseAI
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

To jest nasz moment decydujący.
Gwałtowny postęp w dziedzinie sztucznej inteligencji stanowi jeden z najbardziej doniosłych i niebezpiecznych zwrotów technologicznych w historii.
Domagamy się, aby politycy i firmy wstrzymały rozwój ogólnych systemów inteligencji sztucznej (AGI) do czasu ustanowienia międzynarodowych porozumień dotyczących bezpieczeństwa.
Dołącz do naszej globalnej sieci, która opowiada się za demokratyczną kontrolą nad rozwojem sztucznej inteligencji.

PauseAI Global łączy obywateli, którzy są zaniepokojeni - naukowców, rodziców, studentów, pracowników i liderów społecznych - którzy wierzą, że technologie transformujące wymagają udziału społeczeństwa, zanim przejdą poza kontrolę ludzką.
Niezależnie od tego, czy możesz poświęcić 5 minut (udostępnianie postów), godzinę (rozprowadzanie ulotek, pisanie listów), 5 godzin (protestowanie, spotkania z politykami) czy 5 dni w tygodniu (rozwój strategii), twój głos ma znaczenie.
Po zapisaniu się, dołącz do naszej sesji onboardingu online lub lokalnej, aby dowiedzieć się o bieżących działaniach.

<TallyEmbed formId="wbGvKe" />

## Po zapisaniu się {#after-signing-up}

Dołącz do jednego z naszych spotkań powitalnych dla członków społeczności lub lokalnego wydarzenia, aby dowiedzieć się więcej o społeczności PauseAI: [Wydarzenia](/communities#events).
Jeśli chcesz od razu rozpocząć działanie, sprawdź naszą [listę działań](/action).

## Pozostań na bieżąco {#stay-updated}

<NewsletterSignup bind:email={newsletterEmail} />

{#if userHasUid && subscribeEmail}

<p><em>Rozważ możliwość zostania aktywnym członkiem PauseAI, używając formularza powyżej!</em></p>
{/if}