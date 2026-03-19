---
title: Prueba de localización de enlaces
description: Página de prueba para verificar el comportamiento de localización de enlaces
---
 <!-- end of frontmatter metadata, dashes above need to stay -->

<!-- eslint-disable -->

Esta página prueba varios patrones de enlaces para asegurarse de que se comporten correctamente con la localización.

## Enlaces internos regulares (deben ser localizados) {#regular-internal-links-should-be-localized}

- [Propuesta](/proposal)
- [Aprender más](/learn)
- [Preguntas frecuentes](/faq)
- [Tomar acción](/action)
- [Página de inicio](/)

## Páginas de inicio de idioma (no deben ser localizadas) {#locale-homepages-should-not-be-localized}

- [Página de inicio en inglés](/en)
- [Página de inicio en alemán](/de)
- [Página de inicio en neerlandés](/nl)

## Enlaces ya localizados (no deben ser localizados) {#already-localized-links-should-not-be-localized}

- [Preguntas frecuentes en inglés](/en/faq)
- [Acción en alemán](/de/action)
- [Propuesta en neerlandés](/nl/proposal)
- [Inglés con barra al final](/en/)

## Enlaces de exclusión (no deben ser localizados) {#opt-out-links-should-not-be-localized}

- [Forzar inglés](/en/proposal#no-localize)
- [Forzar alemán](/de/learn#no-localize)
- [Enlace regular con exclusión de localización](/action#no-localize)

## Otros tipos de enlaces (no deben ser localizados) {#other-link-types-should-not-be-localized}

- [Enlace externo](https://example.com)
- [PauseAI externo](https://pauseai.info/proposal)
- [Enlace relativo al protocolo](//example.com)
- [Enlace relativo](./other-page)
- [Enlace relativo a la página padre](../parent-page)
- [Ancla](#section) <!-- no localizar destino, solo etiqueta -->
- [Correo electrónico](mailto:test@example.com)

## Casos límite {#edge-cases}

- [Enlace vacío]()
- [Solo barra](/)
- [Doble barra al inicio](//not-a-locale)