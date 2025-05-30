---
title: Test Link Lokalisatie
description: Testpagina voor het verifiëren van lokalisatiegedrag van links
---

Deze pagina test verschillende linkpatronen om ervoor te zorgen dat het lokalisatiegedrag correct is.

## Gewone interne links (moeten worden gelokaliseerd) {#regular-internal-links-should-be-localized}

- [Voorstel](/proposal)
- [Leer meer](/learn)
- [Veelgestelde vragen](/faq)
- [Actie ondernemen](/action)
- [Startpagina](/)

## Lokale startpagina's (moeten NIET worden gelokaliseerd) {#locale-homepages-should-not-be-localized}

- [Engelse startpagina](/en)
- [Duitse startpagina](/de)
- [Nederlandse startpagina](/nl)

## Reeds gelokaliseerde links (moeten NIET worden gelokaliseerd) {#already-localized-links-should-not-be-localized}

- [Engelse Veelgestelde vragen](/en/faq)
- [Duitse Actie](/de/action)
- [Nederlands Voorstel](/nl/proposal)
- [Engels met afsluitende schuine streep](/en/)

## Andere linktypes (moeten NIET worden gelokaliseerd) {#other-link-types-should-not-be-localized}

- [Externe link](https://example.com)
- [Externe link PauseAI](https://pauseai.info/proposal)
- [Protocolrelatief](//example.com)
- [Relatief](./other-page)
- [Ouderrelatief](../parent-page)
- [Anker](#section) <!-- vertaal alleen het label -->
- [E-mail](mailto:test@example.com)

## Uitzonderlijke gevallen {#edge-cases}

- [Lege href]()
- [Alleen schuine streep](/)
- [Dubbele schuine streep aan het begin](//geen-lokale)

## Testsectie voor ankers {#section} {#test-section-for-anchors-section}

Dit is het doelwit voor de ankerlink hierboven.