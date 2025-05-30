---
title: Test der Link-Lokalisierung
description: Testseite zur Überprüfung des Lokalisierungsverhaltens von Links
---

Diese Seite testet verschiedene Link-Muster, um sicherzustellen, dass die Lokalisierung korrekt funktioniert.

## Reguläre interne Links (sollten lokalisiert werden) {#regular-internal-links-should-be-localized}

- [Vorschlag](/proposal)
- [Lernen](/learn)
- [Häufig gestellte Fragen](/faq)
- [Aktion](/action)
- [Startseite](/)

## Startseiten für verschiedene Sprachen (sollten NICHT lokalisiert werden) {#locale-homepages-should-not-be-localized}

- [Englische Startseite](/en)
- [Deutsche Startseite](/de)
- [Niederländische Startseite](/nl)

## Bereits lokalisierte Links (sollten NICHT lokalisiert werden) {#already-localized-links-should-not-be-localized}

- [Englische FAQ](/en/faq)
- [Deutsche Aktion](/de/action)
- [Niederländischer Vorschlag](/nl/proposal)
- [Englisch mit nachfolgendem Schrägstrich](/en/)

## Andere Link-Typen (sollten NICHT lokalisiert werden) {#other-link-types-should-not-be-localized}

- [Externer Link](https://example.com)
- [Extern: PauseAI](https://pauseai.info/proposal)
- [Protokollrelativer Link](//example.com)
- [Relativer Link](./other-page)
- [Übergeordneter relativer Link](../parent-page)
- [Anker](#section) <!-- Ziel nicht übersetzen, nur Label -->
- [E-Mail](mailto:test@example.com)

## Grenzfälle {#edge-cases}

- [Leerer href]()
- [Nur Schrägstrich](/)
- [Doppelter Schrägstrich am Anfang](//not-a-locale)

## Testabschnitt für Anker {#section} {#test-section-for-anchors-section}

Dies ist das Ziel für den Anker-Link oben.