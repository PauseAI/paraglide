---
title: Dołącz do PauseAI
description: Zapisz się, aby dołączyć do ruchu PauseAI
---
 <!-- end of frontmatter metadata, dashes above need to stay -->

<script>
    import { onMount, tick } from 'svelte'
    import { page } from '$app/stores'
    import TallyEmbed from '$lib/components/TallyEmbed.svelte'
    import NewsletterSignup from '$lib/components/NewsletterSignup.svelte'
    import Banner from '$lib/components/Banner.svelte'
    import { detectAndStoreCollagenUid } from '$lib/collagen'

    const campaign = 'sayno' // Nazwa kampanii dla śledzenia collagen

    let userHasUid = false
    let subscribeEmail = ''
    let newsletterEmail = ''
    let subscribeClicked = false
    let hideSharing = false

    onMount(async () => {
        // Sprawdź, czy UID collagen jest obecny w parametrach URL - ustawia to ciasteczko i wyzwala automatyczne subskrybowanie
        userHasUid = detectAndStoreCollagenUid(campaign, $page.url.searchParams)

        // Sprawdź, czy parametr eksperymentu x002 jest obecny (kontrola = ukryj udostępnianie)
        hideSharing = $page.url.searchParams.has('x002')

        // Pobierz parametr e-mail, jeśli jest dostępny (powinien być obecny, gdy userHasUid jest prawdziwy)
        subscribeEmail = $page.url.searchParams.get('subscribe-email') || ''

        // Jeśli użytkownik przyszedł z e-mailem collagen z UID, wypełnij formularz
        if (userHasUid && subscribeEmail) {
            // Wypełnij formularz newslettera
            newsletterEmail = subscribeEmail
        }
    })

    // Śledź, kiedy kliknięto przycisk subskrypcji
    function handleNewsletterClick(e) {
        // Sprawdź, czy kliknięty element jest przyciskiem submit lub znajduje się wewnątrz formularza
        if (e.target.type === 'submit' || e.target.closest('button[type="submit"]')) {
            subscribeClicked = true
        }
    }
</script>

{#if userHasUid && subscribeEmail}
<Banner id="join-subscribed">
{#if !subscribeClicked}
<strong>Witaj w społeczności!</strong> Kliknij przycisk Subskrybuj, aby dołączyć do newslettera.
{:else}
<strong>Dziękujemy za subskrypcję!</strong> Przewiń w dół, aby dowiedzieć się więcej o naszych działaniach.
{/if}
</Banner>

<!-- svelte-ignore a11y-click-events-have-key-events -->

<!-- svelte-ignore a11y-no-static-element-interactions -->

<div on:click={handleNewsletterClick}>
<NewsletterSignup bind:email={newsletterEmail} />
</div>

{#if !hideSharing}

<p><strong>Pomóż nam rosnąć:</strong> <a href="/{campaign}/share">Udostępnij kampanię {campaign} swoim sieciom</a></p>
{/if}

{:else if userHasUid && !subscribeEmail}
<Banner id="join-error">
<strong>Przepraszamy za błąd!</strong> Nie mogliśmy automatycznie ukończyć Twojej subskrypcji. Wpisz swój adres e-mail poniżej, aby subskrybować.
</Banner>
<NewsletterSignup />
{/if}

To nasz moment przełomowy.
Szybki postęp sztucznej inteligencji reprezentuje jeden z najbardziej znaczących i niebezpiecznych zmian technologicznych w historii.
Żądamy, aby politycy i firmy wstrzymali rozwój AGI do czasu ustanowienia międzynarodowych porozumień dotyczących bezpieczeństwa.
Dołącz do naszej globalnej sieci, która opowiada się za demokratycznym nadzorem nad sztuczną inteligencją.

PauseAI Global łączy obywateli, którzy są zaniepokojeni - naukowców, rodziców, studentów, pracowników i liderów społeczności - którzy wierzą, że technologie przekształcające wymagają publicznego wkładu, zanim przekroczą granice ludzkiej kontroli.
Niezależnie od tego, czy możesz poświęcić 5 minut (udostępnianie postów), godzinę (rozdawanie ulotek, pisanie listów), 5 godzin (protesty, spotkania z politykami) czy 5 dni w tygodniu (rozwój strategii), Twój głos ma znaczenie.
Po zapisaniu się dołącz do naszej sesji onboardingu online lub lokalnie, aby dowiedzieć się o aktualnych działaniach.

<TallyEmbed formId="wbGvKe" />

## Po zapisaniu się {#after-signing-up}

Dołącz do jednego z naszych spotkań powitalnych dla członków społeczności lub lokalnego wydarzenia społecznego, aby dowiedzieć się więcej o społeczności PauseAI: [Wydarzenia](/communities#events).
Jeśli chcesz od razu zacząć działać, sprawdź naszą [listę działań](/action).

## Wolne miejsca dla wolontariuszy {#volunteer-vacancies}

Jednym ze sposobów, aby regularnie angażować się jako wolontariusz, jest dołączenie do jednego z naszych zespołów cyfrowych - Onboarding, Communications i Software. Poniższe role obejmują niektóre z naszych podstawowych funkcji, a dzięki zaangażowaniu możesz pomóc nam zwiększyć nasz zasięg, zatrzymać naszych wolontariuszy lub zbudować narzędzia, których potrzebujemy, aby wygrać.

- Pracujemy w [zespołach](/teams)
- Współpracujemy głównie na naszym [serwerze Discord](https://discord.gg/2XXWXvErfA)
- Dowiedz się więcej o naszej [organizacji](/organization)

### Członek zespołu Onboarding {#onboarding-team-member}

- Minimalny czas trwania: 3 miesiące
- Zobowiązanie czasowe: 2-5 godzin tygodniowo
- Odpowiedzialność:
  - Organizowanie naszych powitalnych rozmów społecznościowych co dwa tygodnie.
  - Przygotowanie komunikacji wprowadzającej dla nowych członków na serwerze Discord PauseAI Global, w tym follow-up. Może to obejmować rozmowy jeden na jeden z nowymi członkami, aby omówić misję PauseAI i pomóc im dowiedzieć się więcej o tym, jak mogą się przyczynić.

- Kluczowe umiejętności:
  - Przyjazny i gościnny.
  - Rozumie misję PauseAI.
  - Dobry łącznik społeczny.

Zainteresowany? [Wyślij e-mail do Iriny](mailto:irina@pauseai.info)

### Członek zespołu Communications - Pisanie i edycja newslettera i postów na LinkedIn {#communications-team-member---writing-and-editing-newsletter-and-linkedin-posts}

- Czas trwania: 3 miesiące
- Zobowiązanie czasowe: 2-5 godzin tygodniowo
- Odpowiedzialność:
  - Tworzenie treści dla miesięcznego newslettera PauseAI Global i regularnych postów na LinkedIn; w tym wyszukiwanie odpowiednich wiadomości i przeprowadzanie wywiadów z autorami.

- Kluczowe umiejętności:
  - Silne umiejętności pisarskie, zdolność do uchwycenia tonu PauseAI i prostego przekazywania złożonych informacji.
  - Korekta.

Zainteresowany? [Wyślij e-mail do Iriny](mailto:irina@pauseai.info)

### Członek zespołu Communications - Edytor wideo {#communications-team-member---video-editor}

- Czas trwania: 3 miesiące
- Zobowiązanie czasowe: 2-5 godzin tygodniowo
- Odpowiedzialność:
  - Tworzenie treści wideo dla kanałów społecznościowych PauseAI Global

- Kluczowe umiejętności:
  - Zdolność do uchwycenia tonu PauseAI i prostego przekazywania złożonych informacji.
  - Edycja wideo

Zainteresowany? [Wyślij e-mail do Iriny](mailto:irina@pauseai.info)

### Członek zespołu Communications - Kontakt z influencerami i mediami {#communications-team-member---outreach-to-influencers-and-media}

- Czas trwania: 3 miesiące
- Zobowiązanie czasowe: 2-5 godzin tygodniowo
- Odpowiedzialność:
  - Kontaktowanie się z kluczowymi influencerami i kontaktami medialnymi jako przedstawiciel PauseAI Global w celu zabezpieczenia slotów w podcastach lub wideo dla dyrektorów generalnych i dyrektorów krajowych.

- Kluczowe umiejętności:
  - Silne umiejętności pisarskie, zdolność do uchwycenia tonu PauseAI i prostego przekonywania.
  - Charyzma i zdolność do budowania i sprzedawania idei.

Zainteresowany? [Wyślij e-mail do Iriny](mailto:irina@pauseai.info)

### Członek zespołu Software {#software-team-member}

- Czas trwania: 3 miesiące
- Zobowiązanie czasowe: 2-5 godzin tygodniowo
- Odpowiedzialność:
  - Budowanie i utrzymywanie funkcji dla strony internetowej PauseAI i innych części naszego stosu technologicznego (narzędzia itp.)
  - Doradzanie i wspieranie innych zespołów w wyborze technologii. Mamy [niezwykłe wymagania skalowania](https://tinyurl.com/pauseaitechandscaling), a w większości przypadków kupujemy, a nie budujemy.

- Kluczowe umiejętności:
  - (Każda z tych umiejętności może być nabyta: żadna z nich nie jest blokadą do zapisania się.)
  - Rozwój webowy (główna strona internetowa jest w większości statyczna, korzysta z SvelteKit z hydracją po stronie klienta, Node, Markdown, wdrożona przez Netlify).
  - Samodzielny i zdolny do pracy asynchronicznej. Skłonność do działania i pomysłów - zweryfikujemy wybory w przeglądzie. Wszystkie zwykłe wyzwania związane z rozwojem open source są wzmocnione w kontekście organizacji wolontariackiej - wcześniejsze doświadczenie w tym zakresie pomaga.

Tak, jesteśmy szczęśliwi, korzystając z modeli językowych, aby przyspieszyć nasz rozwój.

Zainteresowany? [Wyślij e-mail do Anthony'ego](mailto:mail@anthonybailey.net) (lub DM anthonybailey.net na [Discord](https://discord.gg/2XXWXvErfA). Upewnij się, że podpisałeś umowę wolontariacką!

## Bądź na bieżąco {#stay-updated}

<NewsletterSignup bind:email={newsletterEmail} />

{#if userHasUid && subscribeEmail}

<p><em>Rozważ zostanie aktywnym członkiem PauseAI, korzystając z formularza powyżej!</em></p>
{/if}