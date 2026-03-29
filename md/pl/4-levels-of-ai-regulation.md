---
title: 4 Poziomy Regulacji Bezpieczeństwa Sztucznej Inteligencji
description: Ramy myślowe dla rozważań na temat ograniczania ryzyka związanego z potężnymi systemami sztucznej inteligencji
image: /4levels.png
showImage: false
---
Wraz ze wzrostem zdolności sztucznej inteligencji rośnie również [ryzyko](/risks), jakie te systemy stanowią dla ludzkości.
Wielu naukowców już ostrzegało przed [ryzykiem wyginięcia ludzkości](/xrisk).

W tym artykule przyjrzymy się naszemu 4-poziomowemu modelowi regulacji bezpieczeństwa sztucznej inteligencji.

<div style="max-width: 500px">

![4 Poziomy regulacji bezpieczeństwa sztucznej inteligencji](/4levels-cropped.png)

</div>

## Potok tworzenia sztucznej inteligencji jako ramy dla zarządzania bezpieczeństwem {#ai-pipeline-as-a-framework-for-safety-governance}

Proces tworzenia sztucznej inteligencji składa się z kilku etapów, które można regulować na różne sposoby.
Obejmuje on:

- **Sprzęt i algorytmy**, wykorzystywane do tworzenia modeli sztucznej inteligencji
- **Uruchomienia treningowe**, podczas których sprzęt i algorytmy są wykorzystywane do stworzenia modelu
- **Wdrożenie**, podczas którego wytrenowany model jest udostępniany publicznie
- **Użycie**, podczas którego wdrożony model jest wykorzystywany przez osoby i firmy

Im później w procesie wprowadzamy regulacje, tym wyższe jest ryzyko.
Aby uzyskać wysoki poziom bezpieczeństwa, musimy regulować wcześniej.
Dlatego, gdy przechodzimy przez 4 poziomy regulacji sztucznej inteligencji, cofamy się w procesie tworzenia sztucznej inteligencji.

## Poziom 1: Regulacja użycia {#level-1-regulate-usage}

Przykłady:

- **Zakaz uruchamiania autonomicznych agentów** (jak AutoGPT)
- **Zakaz wydawania niebezpiecznych poleceń**

Te środki mają na celu zapobieganie użytkownikom podejmowania niebezpiecznych lub szkodliwych działań z modelami sztucznej inteligencji.
Na tym poziomie odpowiedzialność spoczywa na użytkownikach modeli, a nie na twórcach.
Zależymy od wszystkich (potencjalnie milionów) użytkowników, aby przestrzegali przepisów.
To daje nam tylko bardzo niski poziom ochrony przed niebezpieczeństwami sztucznej inteligencji.

## Poziom 2: Regulacja wdrożenia {#level-2-regulate-deployment}

Przykłady:

- **Wymagania dotyczące testów penetracyjnych**. Oznacza to, że przed wdrożeniem modelu sztucznej inteligencji jest on testowany przez zespół, aby sprawdzić, czy można go zhakować lub wykorzystać.
- **Zakaz wdrożenia i udostępniania** modeli o [niebezpiecznych zdolnościach](/dangerous-capabilities).

Regulując wdrożenia, zapobiegamy udostępnianiu niebezpiecznych modeli.
Odpowiedzialność spoczywa wówczas na twórcach modeli.
Jest to bezpieczniejsza sytuacja niż poziom 1, ponieważ zależymy teraz od znacznie mniejszej grupy ludzi, aby postępowali odpowiedzialnie.

Jednak nadal zezwalamy na niebezpieczne uruchomienia treningowe, więc wypadki w laboratoriach sztucznej inteligencji (w tym wycieki niebezpiecznych modeli sztucznej inteligencji lub tworzenie zbuntowanej sztucznej inteligencji) mogą nadal wystąpić.

## Poziom 3: Regulacja uruchomień treningowych {#level-3-regulate-training-runs}

Przykłady:

- **Wymaganie dowodu bezpieczeństwa** przed udzieleniem pozwolenia na trening określonego modelu. Może to obejmować formalny dowód wyrównania. [Ten post szczegółowo opisuje niektóre z obecnych problemów związanych z bezpieczeństwem](https://www.lesswrong.com/posts/mnoc3cKY3gXMrTybs/a-list-of-core-ai-safety-problems-and-how-i-hope-to-solve).
- Ustawienie **limitu skali** dla treningu nowych modeli (np. maksymalnej liczby operacji zmiennoprzecinkowych). Może to również obejmować proces dostrajania.
- **Wymaganie licencji** na trening modeli sztucznej inteligencji (powyżej określonego rozmiaru / z określonymi zdolnościami).
- **Zakaz treningu na niebezpiecznych typach danych**. Niektóre typy danych treningowych mogą prowadzić do [niebezpiecznych zdolności](/dangerous-capabilities), takich jak hakowanie lub tworzenie broni biologicznych. Moglibyśmy zabronić treningu na danych zawierających tego typu wiedzę.
- **Zakaz treningu na danych objętych prawem autorskim**. Nie dotyczy to bezpośrednio niebezpiecznych danych, ale ogranicza ilość danych, które mogą być wykorzystane, co daje nam czas na opracowanie bezpiecznych modeli sztucznej inteligencji.

Regulując uruchomienia treningowe, zapobiegamy tworzeniu niebezpiecznych modeli od samego początku.
To zapobiegnie wypadkom w laboratoriach sztucznej inteligencji, które przestrzegają przepisów.

Jednak nadal zezwalamy na dystrybucję sprzętu i algorytmów, które mogą być wykorzystywane do tworzenia niebezpiecznych modeli, więc nadal zależymy od twórców tych modeli, aby postępowali odpowiedzialnie.

## Poziom 4: Regulacja sprzętu i algorytmów {#level-4-regulate-hardware--algorithms}

Przykłady:

- **Ograniczenie dystrybucji sprzętu treningowego**. Specjalistyczny sprzęt do treningu modeli sztucznej inteligencji staje się coraz ważniejszym produktem producentów chipów. Łańcuch dostaw dla tego sprzętu jest bardzo scentralizowany, a sprzęt jest bardzo drogi. Oznacza to, że [relatywnie łatwo jest regulować](https://arxiv.org/abs/2303.11341) dystrybucję tego sprzętu.
- **Zakaz publikacji nowych architektur treningowych**. Nowe architektury treningowe sztucznej inteligencji mogą prowadzić do dramatycznych wzrostów zdolności. Model Transformer, na przykład, umożliwił prawie wszystkie ostatnie postępy w sztucznej inteligencji. Moglibyśmy ograniczyć publikację takich architektur, aby zapobiec nagłym skokom zdolności.

Regulując również sprzęt i algorytmy, nie tylko czynimy to nielegalnym, ale także bardzo trudnym do treningu niebezpiecznych modeli.
To daje nam najlepszą ochronę przed ryzykiem związanym z sztuczną inteligencją.

## Ograniczenia {#limitations}

Należy zauważyć, że ten model nie jest idealny, a nie wszystkie możliwe typy regulacji sztucznej inteligencji pasują ładnie do jednego z wymienionych poziomów.
Na przykład, odpowiedzialność prawna twórców modeli może być sklasyfikowana jako poziom 1 "użycia" regulacji, ponieważ jest egzekwowana po wdrożeniu, ale mogłaby być również sklasyfikowana jako poziom 2 lub 3 regulacji, ponieważ może pomóc twórcom rozważyć, czy dany model powinien być wdrożony lub wytrenowany.

## Podsumowanie {#conclusions}

W tym artykule przyjrzymy się naszemu 4-poziomowemu modelowi regulacji bezpieczeństwa sztucznej inteligencji.
Korzystając z tego modelu, możemy łatwiej rozważać skuteczność regulacji sztucznej inteligencji na różnych etapach procesu tworzenia sztucznej inteligencji.
Możemy również zobaczyć, że dwa pierwsze poziomy nie oferują wiele ochrony przed (egzystencjalnymi) ryzykami związanymi z sztuczną inteligencją.
Zapobieganie niebezpiecznym uruchomieniom treningowym i regulacja sprzętu oraz algorytmów są o wiele bardziej niezawodnymi sposobami zapewnienia bezpieczeństwa.