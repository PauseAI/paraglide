---
title: Testowanie lokalizacji linków
description: Strona testowa do weryfikacji zachowania lokalizacji linków
---
<!-- eslint-disable -->

Ta strona testuje różne wzorce linków, aby zapewnić poprawne zachowanie lokalizacji.

## Zwykłe linki wewnętrzne (powinny być zlokalizowane) {#regular-internal-links-should-be-localized}

- [Propozycja](/proposal)
- [Dowiedz się więcej](/learn)
- [Często zadawane pytania](/faq)
- [Działaj](/action)
- [Strona główna](/)

## Strony główne poszczególnych wersji językowych (nie powinny być zlokalizowane) {#locale-homepages-should-not-be-localized}

- [Strona główna w języku angielskim](/en)
- [Strona główna w języku niemieckim](/de)
- [Strona główna w języku niderlandzkim](/nl)

## Linki już zlokalizowane (nie powinny być zlokalizowane) {#already-localized-links-should-not-be-localized}

- [FAQ w języku angielskim](/en/faq)
- [Działaj w języku niemieckim](/de/action)
- [Propozycja w języku niderlandzkim](/nl/proposal)
- [Strona główna w języku angielskim z ukośnikiem na końcu](/en/)

## Linki z wyłączoną lokalizacją (nie powinny być zlokalizowane) {#opt-out-links-should-not-be-localized}

- [Wymuś język angielski](/en/proposal#no-localize)
- [Wymuś język niemiecki](/de/learn#no-localize)
- [Zwykły link z wyłączoną lokalizacją](/action#no-localize)

## Inne rodzaje linków (nie powinny być zlokalizowane) {#other-link-types-should-not-be-localized}

- [Link zewnętrzny](https://example.com)
- [Link zewnętrzny PauseAI](https://pauseai.info/proposal)
- [Link względny do protokołu](//example.com)
- [Link względny](./other-page)
- [Link względny do rodzica](../parent-page)
- [Kotwica](#section) <!-- nie lokalizuj celu, tylko etykietę -->
- [Adres e-mail](mailto:test@example.com)

## Przypadki graniczne {#edge-cases}

- [Pusty href]()
- [Tylko ukośnik](/)
- [Podwójny ukośnik na początku](//not-a-locale)