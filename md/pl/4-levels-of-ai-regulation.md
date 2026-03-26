---
title: 4 Poziomy Regulacji Bezpieczeństwa Sztucznej Inteligencji
description: Ramy myślowe dotyczące sposobów łagodzenia ryzyka związanego z potężnymi systemami sztucznej inteligencji
image: /4levels.png
---
Podczas gdy zdolności sztucznej inteligencji rosną, rosną również [ryzyka](/risks), które te systemy stanowią dla ludzkości.
Wielu naukowców już ostrzegało przed [ryzykiem wymarcia ludzkości](/xrisk).

W tym artykule przyjrzymy się naszemu 4-poziomowemu modelowi regulacji bezpieczeństwa sztucznej inteligencji.

## Potok tworzenia sztucznej inteligencji jako ramy dla zarządzania bezpieczeństwem {#ai-pipeline-as-a-framework-for-safety-governance}

Potok tworzenia sztucznej inteligencji składa się z kilku etapów, z których każdy może być regulowany w różny sposób.
Potok ten składa się z:

- **Sprzętu i algorytmów**, które są wykorzystywane do szkolenia modeli sztucznej inteligencji
- **Procesów szkolenia**, podczas których sprzęt i algorytmy są wykorzystywane do utworzenia modelu
- **Wdrożenia**, podczas którego wytrenowany model jest udostępniany publicznie
- **Użycia**, podczas którego wdrożony model jest wykorzystywany przez osoby i firmy

Im później w potoku regulujemy, tym wyższe ryzyko ponosimy.
Jeśli chcemy wysokiego poziomu bezpieczeństwa, musimy regulować wcześniej w potoku.
Dlatego też, gdy wspinamy się po 4 poziomach regulacji sztucznej inteligencji, cofamy się w potoku tworzenia sztucznej inteligencji.

## Poziom 1: Regulacja użycia {#level-1-regulate-usage}

Przykłady:

- **Zakaz uruchamiania autonomicznych agentów** (jak AutoGPT)
- **Zakaz wydawania niebezpiecznych poleceń**

Te środki mają na celu zapobieganie użytkownikom podejmowania niebezpiecznych lub szkodliwych działań z modelami sztucznej inteligencji.
Na tym poziomie odpowiedzialność spoczywa na użytkownikach modeli, a nie na twórcach.
Zależymy od wszystkich (potencjalnie milionów) użytkowników, którzy przestrzegają przepisów.
To daje nam bardzo niski poziom ochrony przed niebezpieczeństwami sztucznej inteligencji.

## Poziom 2: Regulacja wdrożenia {#level-2-regulate-deployment}

Przykłady:

- **Wymagania dotyczące testowania przez zespół czerwony**. Oznacza to, że przed wdrożeniem modelu sztucznej inteligencji jest on testowany przez zespół czerwony, aby sprawdzić, czy może być zhakowany (ujęty) lub wykorzystany w sposób niebezpieczny.
- **Zakaz wdrożenia i udostępniania** modeli z [niebezpiecznymi możliwościami](/dangerous-capabilities).

Regulując wdrożenia, zapobiegamy udostępnianiu niebezpiecznych modeli.
To oznacza, że odpowiedzialność spoczywa na twórcach modeli.
To jest bezpieczniejsza sytuacja niż poziom 1, ponieważ zależymy teraz od mniejszej grupy osób, które muszą postępować odpowiedzialnie.

Jednak nadal zezwalamy na niebezpieczne procesy szkolenia, więc wypadki w laboratoriach sztucznej inteligencji (w tym wycieki niebezpiecznych modeli sztucznej inteligencji lub tworzenie sztucznej inteligencji, która wymyka się spod kontroli) mogą nadal wystąpić.

## Poziom 3: Regulacja procesów szkolenia {#level-3-regulate-training-runs}

Przykłady:

- **Wymaganie dowodu bezpieczeństwa** przed udzieleniem pozwolenia na szkolenie określonego modelu. Może to obejmować formalny dowód wyrównania. [Ten post szczegółowo opisuje niektóre z obecnych problemów związanych z bezpieczeństwem](https://www.lesswrong.com/posts/mnoc3cKY3gXMrTybs/a-list-of-core-ai-safety-problems-and-how-i-hope-to-solve).
- Ustawienie **limitu skali** dla szkolenia nowych modeli (np. maksymalnej liczby operacji zmiennoprzecinkowych). Może to również obejmować proces dokształcania.
- **Wymaganie licencji** na szkolenie modeli sztucznej inteligencji (powyżej określonego rozmiaru / z określonymi możliwościami).
- **Zakaz szkolenia na niebezpiecznych typach danych**. Niektóre typy danych szkoleniowych mogą prowadzić do [niebezpiecznych możliwości](/dangerous-capabilities), takich jak hakowanie lub tworzenie broni biologicznych. Moglibyśmy zabronić szkolenia na danych, które zawierają tego typu wiedzę.
- **Zakaz szkolenia na danych objętych prawem autorskim**. To nie dotyka bezpośrednio niebezpiecznych danych, ale ogranicza ilość danych, które można wykorzystać, co oznacza, że daje nam czas na znalezienie sposobu na budowanie bezpiecznych modeli sztucznej inteligencji.

Regulując procesy szkolenia, zapobiegamy tworzeniu niebezpiecznych modeli od samego początku.
To zapobiegnie wypadkom w laboratoriach sztucznej inteligencji, które przestrzegają przepisów.

Jednak nadal zezwalamy na dystrybucję sprzętu i algorytmów, które mogą być wykorzystywane do szkolenia niebezpiecznych modeli, więc nadal zależymy od twórców tych modeli, aby postępowali odpowiedzialnie.

## Poziom 4: Regulacja sprzętu i algorytmów {#level-4-regulate-hardware--algorithms}

Przykłady:

- **Ograniczenie dystrybucji sprzętu szkoleniowego**. Specjalistyczny sprzęt do szkolenia modeli sztucznej inteligencji staje się coraz bardziej istotnym produktem producentów chipów. Łańcuch dostaw tego sprzętu jest bardzo scentralizowany, a sprzęt jest bardzo drogi. To oznacza, że jest [relatywnie łatwo regulować](https://arxiv.org/abs/2303.11341) dystrybucję tego sprzętu.
- **Zakaz publikacji nowych architektur szkoleniowych**. Nowe architektury szkoleniowe sztucznej inteligencji mogą prowadzić do dramatycznych wzrostów możliwości. Model Transformer, na przykład, umożliwił prawie wszystkie niedawne postępy w sztucznej inteligencji. Moglibyśmy ograniczyć publikację takich architektur, aby zapobiec nagłym skokom możliwości.

Regulując również sprzęt i algorytmy, robimy to nie tylko nielegalnym, ale także bardzo trudnym do szkolenia niebezpiecznych modeli.
To daje nam najlepszą ochronę przed ryzykiem związanym z sztuczną inteligencją.

## Ograniczenia {#limitations}

Należy zauważyć, że ten model nie jest idealny, a nie wszystkie możliwe typy regulacji sztucznej inteligencji mieszczą się ładnie w jednym z wymienionych poziomów.
Na przykład, odpowiedzialność prawna twórców modeli może być sklasyfikowana jako poziom 1 "użycie" typu regulacji, ponieważ jest egzekwowana po wdrożeniu, ale mogłaby być również sklasyfikowana jako poziom 2 lub 3 typu regulacji, ponieważ może pomóc twórcom rozważyć, czy dany model powinien być wdrożony lub szkoleniowy w pierwszej kolejności.

## Podsumowanie {#conclusions}

W tym artykule przyjrzymy się naszemu 4-poziomowemu modelowi regulacji bezpieczeństwa sztucznej inteligencji.
Wykorzystując ten model, możemy łatwiej rozważyć skuteczność regulacji sztucznej inteligencji na różnych etapach potoku tworzenia sztucznej inteligencji.
Możemy również zobaczyć, że dwa pierwsze poziomy nie oferują zbyt dużej ochrony przed (egzystencjalnymi) ryzykami związanymi z sztuczną inteligencją.
Zapobieganie niebezpiecznym procesom szkolenia i regulacja sprzętu i algorytmów są o wiele bardziej niezawodnymi sposobami zapewnienia bezpieczeństwa.