---
title: 4 poziomy regulacji bezpieczeństwa AI
description: Ramy dla myślenia o tym, jak ograniczyć ryzyka związane z potężnymi systemami AI
image: /4levels.png
---

Wraz ze wzrostem możliwości AI rośnie również ryzyko, jakie te systemy stwarzają dla ludzkości.
Wielu naukowców już ostrzegało o [ryzyku wyginięcia ludzkości](/xrisk).

W tym artykule przyjrzymy się naszemu 4-poziomowemu modelowi myślenia o tym, jak bezpieczeństwo AI może być regulowane.

## Rurociąg AI jako ramy dla zarządzania bezpieczeństwem {#ai-pipeline-as-a-framework-for-safety-governance}

Rurociąg tworzenia AI składa się z różnych etapów, z których każdy może być regulowany w inny sposób.
Ten rurociąg składa się z:

- **Sprzętu i algorytmów**, które są wykorzystywane do trenowania modeli AI
- **Uruchomień trenowania**, gdzie sprzęt i algorytmy są wykorzystywane do stworzenia modelu
- **Wdrożenia**, gdzie wytrenowany model jest udostępniany publicznie
- **Użycia**, gdzie wdrożony model jest wykorzystywany przez osoby fizyczne i firmy

Im później w rurociągu regulujemy, tym większe ryzyko podejmujemy.
Jeśli chcemy osiągnąć wysoki poziom bezpieczeństwa, musimy regulować wcześniej w rurociągu.
Dlatego, gdy wspinamy się po 4 poziomach regulacji AI, cofamy się w rurociągu tworzenia AI.

![4 poziomy regulacji bezpieczeństwa AI](/4levels.png)

## Poziom 1: Regulacja użycia {#level-1-regulate-usage}

Przykłady:

- **Zakaz uruchamiania autonomicznych agentów** (takich jak AutoGPT)
- **Zakaz niebezpiecznych instrukcji**

Te środki mają na celu zapobieżenie użytkownikom wykonywania niebezpiecznych lub szkodliwych działań z modelami AI.
Na tym poziomie odpowiedzialność spoczywa na użytkownikach modeli, a nie na twórcach.
Polegamy na tym, że wszyscy użytkownicy będą przestrzegać regulacji, co może być trudne do osiągnięcia.
To zapewnia tylko bardzo niski poziom ochrony przed niebezpieczeństwami AI.

## Poziom 2: Regulacja wdrożenia {#level-2-regulate-deployment}

Przykłady:

- **Wymagania dotyczące testowania przez czerwony zespół**. Oznacza to, że przed wdrożeniem modelu AI jest on testowany przez czerwony zespół, aby sprawdzić, czy może być zhakowany (wyłamany) lub nadużyty.
- **Zakaz wdrożenia i udostępniania** modeli z [niebezpiecznymi możliwościami](/dangerous-capabilities).

Regulując wdrożenia, zapobiegamy udostępnianiu niebezpiecznych modeli.
Oznacza to, że odpowiedzialność spoczywa na twórcach modeli.
Jest to bezpieczniejsza sytuacja niż poziom 1, ponieważ teraz polegamy na mniejszej grupie ludzi, aby działali odpowiedzialnie.

Jednak nadal zezwalamy na niebezpieczne uruchomienia trenowania, więc wypadki w laboratoriach AI (w tym wycieki niebezpiecznych modeli AI lub stworzenie szkodliwego AI) nadal mogą się zdarzyć.

## Poziom 3: Regulacja uruchomień trenowania {#level-3-regulate-training-runs}

Przykłady:

- **Wymaganie dowodu bezpieczeństwa** przed udzieleniem pozwolenia na trenowanie określonego modelu. Może to obejmować formalny dowód zgodności. [Ten post opisuje niektóre z obecnych problemów z bezpieczeństwem](https://www.lesswrong.com/posts/mnoc3cKY3gXMrTybs/a-list-of-core-ai-safety-problems-and-how-i-hope-to-solve).
- Ustawienie **pułapu skali dla trenowania nowych modeli** (np. maksymalna liczba flops użytych). Mogłoby to również obejmować proces fine-tuningu.
- **Wymaganie licencji** na trenowanie modeli AI (powyżej określonego rozmiaru / z określonymi możliwościami).
- **Zakaz trenowania na niebezpiecznych typach danych**. Niektóre typy danych trenowania mogą prowadzić do [niebezpiecznych możliwości](/dangerous-capabilities), takich jak hakowanie lub tworzenie broni biologicznej. Moglibyśmy zakazać trenowania na danych, które zawierają tego typu wiedzę.
- **Zakaz trenowania na danych chronionych prawem autorskim**. Nie dotyczy to bezpośrednio niebezpiecznych danych, ale ogranicza ilość danych, które mogą być użyte, co oznacza, że daje nam czas na rozwiązanie problemu budowy bezpiecznych modeli AI.

Regulując uruchomienia trenowania, zapobiegamy tworzeniu niebezpiecznych modeli.
Zapobiega to wypadkom w laboratoriach AI, które przestrzegają regulacji.

Jednak nadal zezwalamy na dystrybucję sprzętu i algorytmów, które mogą być użyte do trenowania niebezpiecznych modeli, więc nadal polegamy na twórcach tych modeli, aby działali odpowiedzialnie.

## Poziom 4: Regulacja sprzętu i algorytmów {#level-4-regulate-hardware--algorithms}

Przykłady:

- **Ograniczenie dystrybucji sprzętu do trenowania**. Specjalistyczny sprzęt do trenowania modeli AI szybko staje się najważniejszym produktem producentów chipów. Łańcuch dostaw dla tego sprzętu jest bardzo scentralizowany, a sprzęt jest bardzo drogi. Oznacza to, że jest [relatywnie łatwy do regulacji](https://arxiv.org/abs/2303.11341) dystrybucja tego sprzętu.
- **Zakaz publikowania nowych architektur trenowania**. Nowe architektury trenowania AI mogą prowadzić do dramatycznych wzrostów możliwości. Model Transformer, na przykład, umożliwił praktycznie wszystkie ostatnie postępy w AI. Moglibyśmy ograniczyć publikowanie takich architektur, aby zapobiec nagłym skokom możliwości.

Regulując również sprzęt i algorytmy, czynimy nie tylko nielegalnym, ale także bardzo trudnym trenowanie niebezpiecznych modeli.
Daje nam to najlepszą ochronę przed ryzykami związanymi z AI.

## Ograniczenia {#limitations}

Należy zauważyć, że ten model nie jest doskonały i nie wszystkie możliwe rodzaje regulacji AI mieszczą się w jednym z wymienionych poziomów.
Na przykład, odpowiedzialność prawna twórców modeli może być klasyfikowana jako regulacja typu "użycie" na poziomie 1, ponieważ jest egzekwowana po wdrożeniu, ale mogłaby być również klasyfikowana jako regulacja typu 2 lub 3, ponieważ może pomóc twórcom rozważyć, czy dany model powinien być wdrożony lub trenowany w pierwszej kolejności.

## Wnioski {#conclusions}

W tym artykule przyjrzeliśmy się naszemu 4-poziomowemu modelowi myślenia o tym, jak bezpieczeństwo AI może być regulowane.
Używając tego modelu, możemy łatwiej rozumować o skuteczności regulacji AI na różnych etapach rurociągu tworzenia AI.
Możemy również zobaczyć, że pierwsze dwa poziomy nie oferują dużej ochrony przed (egzystencjalnymi) ryzykami związanymi z AI.
Zapobieganie niebezpiecznym uruchomieniom trenowania i regulacja sprzętu i algorytmów są o wiele bardziej niezawodnymi sposobami zapewnienia bezpieczeństwa.