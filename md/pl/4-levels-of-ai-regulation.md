---
title: 4 Poziomy Regulacji Bezpieczeństwa Sztucznej Inteligencji
description: Ramy myślowe dla ograniczania ryzyka związanego z potężnymi systemami sztucznej inteligencji
image: /4levels.png
showImage: false
---
 <!-- end of frontmatter metadata, dashes above need to stay -->

Wraz ze wzrostem możliwości sztucznej inteligencji, rośnie również ryzyko, jakie te systemy stanowią dla ludzkości.
Wiele naukowców już ostrzegało przed ryzykiem wymarcia ludzkości.

W tym artykule przedstawimy nasz 4-poziomowy model myślowy dotyczący regulacji bezpieczeństwa sztucznej inteligencji.

<div style="max-width: 500px">

![4 Poziomy regulacji bezpieczeństwa sztucznej inteligencji](/4levels-cropped.png)

</div>

## Potok tworzenia sztucznej inteligencji jako ramy dla zarządzania bezpieczeństwem {#ai-pipeline-as-a-framework-for-safety-governance}

Potok tworzenia sztucznej inteligencji składa się z kilku etapów, które można regulować na różne sposoby.
Potok ten obejmuje:

- **Sprzęt i algorytmy**, wykorzystywane do szkolenia modeli sztucznej inteligencji
- **Procesy szkolenia**, podczas których sprzęt i algorytmy są wykorzystywane do utworzenia modelu
- **Wdrożenie**, podczas którego wytrenowany model jest udostępniany publicznie
- **Użycie**, podczas którego wdrożony model jest wykorzystywany przez osoby i firmy

Im później w potoku wprowadzamy regulacje, tym wyższe ryzyko ponosimy.
Jeśli chcemy uzyskać wysoki poziom bezpieczeństwa, musimy regulować wcześniej w potoku.
Dlatego też, gdy wspinamy się po 4 poziomach regulacji sztucznej inteligencji, cofamy się w potoku tworzenia sztucznej inteligencji.

## Poziom 1: Regulacja użycia {#level-1-regulate-usage}

Przykłady:

- **Zakaz uruchamiania autonomicznych agentów** (jak AutoGPT)
- **Zakaz wydawania niebezpiecznych poleceń**

Te środki mają na celu zapobieganie użytkownikom podejmowania niebezpiecznych lub szkodliwych działań z modelami sztucznej inteligencji.
Na tym poziomie odpowiedzialność spoczywa na użytkownikach modeli, a nie na twórcach.
Zależymy od wszystkich (potencjalnie milionów) użytkowników, którzy muszą przestrzegać regulacji.
To daje nam bardzo niski poziom ochrony przed niebezpieczeństwami sztucznej inteligencji.

## Poziom 2: Regulacja wdrożenia {#level-2-regulate-deployment}

Przykłady:

- **Wymagania dotyczące testowania przez zespół czerwony**. Oznacza to, że przed wdrożeniem modelu sztucznej inteligencji, jest on testowany przez zespół czerwony, aby sprawdzić, czy można go zhakować lub wykorzystać.
- **Zakaz wdrożenia i udostępnienia** modeli z [niebezpiecznymi możliwościami](/dangerous-capabilities).

Regulując wdrożenia, zapobiegamy udostępnianiu niebezpiecznych modeli.
Oznacza to, że odpowiedzialność spoczywa na twórcach modeli.
To jest bezpieczniejsza sytuacja niż poziom 1, ponieważ zależymy teraz od znacznie mniejszej grupy ludzi, którzy muszą postępować odpowiedzialnie.

Jednak nadal zezwalamy na niebezpieczne procesy szkolenia, więc wypadki w laboratoriach sztucznej inteligencji (w tym wycieki niebezpiecznych modeli sztucznej inteligencji lub tworzenie sztucznej inteligencji, która wymyka się spod kontroli) mogą nadal wystąpić.

## Poziom 3: Regulacja procesów szkolenia {#level-3-regulate-training-runs}

Przykłady:

- **Wymaganie dowodu bezpieczeństwa** przed udzieleniem pozwolenia na szkolenie określonego modelu. Może to obejmować formalny dowód wyrównania. [Ten post szczegółowo opisuje niektóre z obecnych problemów związanych z bezpieczeństwem](https://www.lesswrong.com/posts/mnoc3cKY3gXMrTybs/a-list-of-core-ai-safety-problems-and-how-i-hope-to-solve).
- Ustawienie **limitu skali** dla szkolenia nowych modeli (np. maksymalnej liczby operacji zmiennoprzecinkowych). Może to również obejmować proces dokształcania.
- **Wymaganie licencji** na szkolenie modeli sztucznej inteligencji (powyżej określonego rozmiaru / z określonymi możliwościami).
- **Zakaz szkolenia na niebezpiecznych typach danych**. Niektóre typy danych szkoleniowych mogą prowadzić do [niebezpiecznych możliwości](/dangerous-capabilities), takich jak hakowanie lub tworzenie broni biologicznych. Moglibyśmy zabronić szkolenia na danych, które zawierają tego typu wiedzę.
- **Zakaz szkolenia na danych objętych prawem autorskim**. To nie dotyka bezpośrednio niebezpiecznych danych, ale ogranicza ilość danych, które można wykorzystać, co daje nam czas na opracowanie bezpiecznych modeli sztucznej inteligencji.

Regulując procesy szkolenia, zapobiegamy tworzeniu niebezpiecznych modeli od samego początku.
To uniemożliwi wypadki w laboratoriach sztucznej inteligencji, które przestrzegają regulacji.

Jednak nadal zezwalamy na dystrybucję sprzętu i algorytmów, które mogą być wykorzystywane do szkolenia niebezpiecznych modeli, więc nadal zależymy od twórców tych modeli, którzy muszą postępować odpowiedzialnie.

## Poziom 4: Regulacja sprzętu i algorytmów {#level-4-regulate-hardware--algorithms}

Przykłady:

- **Ograniczenie dystrybucji sprzętu szkoleniowego**. Specjalistyczny sprzęt do szkolenia modeli sztucznej inteligencji staje się coraz ważniejszym produktem producentów chipów. Łańcuch dostaw tego sprzętu jest bardzo scentralizowany, a sprzęt jest bardzo drogi. Oznacza to, że jest [relatywnie łatwo regulować](https://arxiv.org/abs/2303.11341) dystrybucję tego sprzętu.
- **Zakaz publikowania nowych architektur szkoleniowych**. Nowe architektury szkoleniowe sztucznej inteligencji mogą prowadzić do dramatycznych wzrostów możliwości. Model Transformer, na przykład, umożliwił prawie wszystkie niedawne postępy w sztucznej inteligencji. Moglibyśmy ograniczyć publikowanie takich architektur, aby zapobiec nagłym skokom możliwości.

Regulując również sprzęt i algorytmy, nie tylko czynimy niebezpieczne szkolenia nielegalnymi, ale także bardzo trudnymi.
To daje nam najlepszą ochronę przed ryzykiem związanym z sztuczną inteligencją.

## Ograniczenia {#limitations}

Należy zauważyć, że ten model nie jest idealny, a nie wszystkie możliwe typy regulacji sztucznej inteligencji mieszczą się ładnie w jednym z wymienionych poziomów.
Na przykład, odpowiedzialność prawna twórców modeli może być sklasyfikowana jako poziom 1 "użycie" regulacji, ponieważ jest egzekwowana po wdrożeniu, ale mogłaby również być sklasyfikowana jako poziom 2 lub 3 regulacji, ponieważ może pomóc twórcom rozważyć, czy dany model powinien być wdrożony lub szkoleniowy w pierwszej kolejności.

## Podsumowanie {#conclusions}

W tym artykule przedstawiliśmy nasz 4-poziomowy model myślowy dotyczący regulacji bezpieczeństwa sztucznej inteligencji.
Korzystając z tego modelu, możemy łatwiej rozważyć skuteczność regulacji sztucznej inteligencji na różnych etapach potoku tworzenia sztucznej inteligencji.
Możemy również zobaczyć, że dwa pierwsze poziomy nie oferują zbyt dużej ochrony przed (egzystencjalnymi) ryzykami związanymi z sztuczną inteligencją.
Zapobieganie niebezpiecznym procesom szkolenia i regulacja sprzętu oraz algorytmów są o wiele bardziej niezawodnymi sposobami zapewnienia bezpieczeństwa.