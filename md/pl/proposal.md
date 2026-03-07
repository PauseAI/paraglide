---
title: Propozycja PauseAI
description: Wprowadzenie tymczasowego wstrzymania szkolenia najpotężniejszych ogólnych systemów sztucznej inteligencji.
---

**Wprowadźmy tymczasowe wstrzymanie szkolenia najpotężniejszych ogólnych systemów sztucznej inteligencji**, aż do czasu, gdy będziemy wiedzieć, jak je budować bezpiecznie i utrzymać pod demokratyczną kontrolą.

_Wersja: 4 lutego 2025 r._

Poszczególne kraje mogą i powinny wprowadzić tę środek _już teraz_.
Szczególnie Stany Zjednoczone (lub Kalifornia, w szczególności) powinny wprowadzić wstrzymanie, ponieważ jest to siedziba praktycznie wszystkich wiodących firm zajmujących się sztuczną inteligencją.
Wielu naukowców i liderów branży [zgadza się, że wstrzymanie jest konieczne](https://futureoflife.org/open-letter/pause-giant-ai-experiments/), a opinia publiczna w USA również silnie popiera wstrzymanie ([64%](https://www.campaignforaisafety.org/usa-ai-x-risk-perception-tracker/) - [69%](https://today.yougov.com/topics/technology/survey-results/daily/2023/04/03/ad825/2)).

Jednak nie możemy oczekiwać, że kraje lub firmy zaryzykują swoją przewagę konkurencyjną, wstrzymując szkolenie sztucznej inteligencji na długi czas, jeśli inne kraje lub firmy nie zrobią tego samego.
Dlatego potrzebujemy **globalnego wstrzymania**.

Zobaczmy, co jest potrzebne, aby do tego dojść.

## Droga do traktatu {#getting-to-a-treaty}

Międzynarodowe porozumienie jest zazwyczaj ustanawiane poprzez szczyt, na którym spotykają się przywódcy krajów, aby omówić problem i podjąć decyzję.
Mieliśmy już [trzy szczyty dotyczące bezpieczeństwa sztucznej inteligencji](/summit).

Głównym celem tych szczytów powinien być **traktat**.
Jednak do tej pory szczyty nie były skuteczne w produkcji czegoś prawnie wiążącego.
A budowanie traktatu jest powolne i podatne na weta.
Możemy [nie mieć czasu](/urgency), aby czekać na tradycyjne procesy tworzenia traktatów.

Dlatego potrzebujemy nowego **procesu tworzenia traktatów**:

- Udział zarówno **USA, jak i Chin** jest kluczowy.
- Musi być **odporny na weta** ze strony jakiegokolwiek kraju.
- Musi być **szybki**. Normalne procesy tworzenia traktatów trwają lata, a my [możemy nie mieć tego czasu](/urgency).
- Skala tego procesu tworzenia traktatów jest bezprecedensowa i wymaga poparcia ze strony wszystkich krajów.

Sam traktat powinien zawierać następujące **środki**:

### Środki traktatu {#treaty-measures}

- **Utwórz międzynarodową agencję bezpieczeństwa sztucznej inteligencji**, podobną do MAEA. Agencja ta będzie odpowiedzialna za:
  - Udzielanie zgody na _wdrożenia_. Będzie to obejmować testy penetracyjne / [oceny modeli](/evaluations).
  - Udzielanie zgody na _nowe szkolenia_ modeli sztucznej inteligencji powyżej określonego rozmiaru (np. 1 miliard parametrów).
  - Okresowe spotkania w celu omówienia postępów w badaniach nad bezpieczeństwem sztucznej inteligencji.

- **Zezwalaj na szkolenie ogólnych systemów sztucznej inteligencji tylko wtedy, gdy ich bezpieczeństwo może być zagwarantowane**.
  - Przez ogólne modele sztucznej inteligencji rozumiemy modele, które są albo 1) większe niż 10^12 parametrów, 2) mają więcej niż 10^25 FLOPs użytych do szkolenia lub 3) mają zdolności, które przekraczają wynik 86% w teście MMLU. Należy zauważyć, że nie dotyczy to _wąskich_ systemów sztucznej inteligencji, takich jak rozpoznawanie obrazów stosowane w diagnostyce raka.
  - Możliwe jest, że problem dostosowania sztucznej inteligencji _nigdy nie zostanie rozwiązany_ - może być nierozwiązywalny. W takim przypadku nigdy nie powinniśmy zezwalać na szkolenie takich systemów.
  - **Weryfikuj**, że te niebezpieczne szkolenia nie mają miejsca. Można to zrobić na [wiele sposobów](https://arxiv.org/abs/2408.16074): [śledzenie kart graficznych](https://arxiv.org/abs/2303.11341), zachęcanie sygnalistów, monitorowanie energii, inspekcje centrów danych, wywiad finansowy, inspekcje zakładów produkcyjnych półprzewodników, inspekcje deweloperów sztucznej inteligencji, śledzenie lokalizacji chipów i raportowanie oparte na chipach. [Łańcuch dostaw chipów sztucznej inteligencji](https://www.governance.ai/post/computing-power-and-the-governance-of-ai) jest wysoce scentralizowany, co umożliwia globalny nadzór.
  - Wymagaj [nadzoru podczas szkoleń](https://www.alignmentforum.org/posts/Zfk6faYvcf5Ht7xDx/compute-thresholds-proposed-rules-to-mitigate-risk-of-a-lab).
  - Nawet jeśli możemy zbudować kontrolowaną, bezpieczną sztuczną inteligencję, buduj i wdrażaj taką technologię tylko z **silną demokratyczną kontrolą**. Superinteligencja jest zbyt potężna, aby być kontrolowana przez jedną firmę lub kraj.

- **Zezwalaj na wdrożenie modeli dopiero po stwierdzeniu, że nie mają [niebezpiecznych zdolności](/dangerous-capabilities)**. (Ocena przedwdrożeniowa)
  - Będziemy potrzebować standardów i niezależnych testów penetracyjnych, aby określić, czy model ma niebezpieczne zdolności.
  - Lista niebezpiecznych zdolności może zmieniać się w czasie, wraz z rozwojem zdolności sztucznej inteligencji.
  - Należy zauważyć, że całkowite poleganie na ocenach modeli [nie jest wystarczające](/4-levels-of-ai-regulation).

Wprowadzenie wstrzymania _może_ się nie powieść, jeśli nie zostanie wykonane prawidłowo.
Przeczytaj więcej o [tym, jak można zminimalizować te ryzyka](/mitigating-pause-failures).

Aby uzyskać więcej informacji na temat tego, jak łańcuch dostaw chipów sztucznej inteligencji może być wykorzystany do globalnego nadzoru, przeczytaj [Budowanie przycisku wstrzymania](/building-the-pause-button).

## Inne środki, które skutecznie spowalniają {#other-measures-that-effectively-slow-down}

- **Zakaz szkolenia systemów sztucznej inteligencji na materiałach chronionych prawem autorskim**. Pomaga to w kwestiach praw autorskich, spowalnia rosnącą nierówność i spowalnia postęp w kierunku superinteligencji.
- **Pociągaj twórców modeli sztucznej inteligencji do odpowiedzialności** za przestępstwa popełnione przy użyciu ich systemów sztucznej inteligencji. Daje to twórcom modeli więcej motywacji, aby upewnić się, że ich modele są bezpieczne.

## Długoterminowa polityka {#long-term-policy}

W chwili pisania, szkolenie modelu o rozmiarze GPT-3 kosztuje miliony dolarów.
To sprawia, że bardzo trudno jest szkolić takie modele, a to ułatwia egzekwowanie kontroli nad szkoleniem przy użyciu śledzenia kart graficznych.
Jednak koszt szkolenia modelu maleje wykładniczo dzięki ulepszeniom sprzętu i nowym algorytmom szkolenia.

Nadejdzie moment, w którym potencjalnie superinteligentne modele sztucznej inteligencji będą mogły być szkolone za kilka tysięcy dolarów lub mniej, być może nawet na sprzęcie konsumenckim.
Musimy być przygotowani na to.
Powinniśmy rozważyć następujące polityki:

- **Ogranicz publikację algorytmów szkolenia / ulepszeń środowiska uruchomieniowego**. Czasami publikowany jest nowy algorytm, który sprawia, że szkolenie jest znacznie bardziej efektywne. Architektura Transformer, na przykład, umożliwiła praktycznie wszystkie ostatnie postępy w sztucznej inteligencji. Takie skoki zdolności mogą wystąpić w dowolnym momencie, a powinniśmy rozważyć ograniczenie publikacji takich algorytmów, aby zminimalizować ryzyko nagłego skoku zdolności. Istnieją również innowacje, które umożliwiają [decentralizowane szkolenia](https://www.primeintellect.ai/blog/opendiloco). Podobnie, niektóre innowacje środowiska uruchomieniowego mogą drastycznie zmienić to, co można zrobić z istniejącymi modelami. Zakaz publikacji takich algorytmów może być wprowadzony przy użyciu podobnych środków, jakimi zakazujemy innych form informacji, takich jak nielegalne media pornograficzne.
- **Ogranicz postęp zdolności zasobów obliczeniowych**. Jeśli szkolenie superinteligencji stanie się możliwe na sprzęcie konsumenckim, jesteśmy w kłopotach. Powinniśmy rozważyć ograniczenie postępu zdolności sprzętu (np. poprzez ograniczenia litografii, projektowania chipów i nowych paradygmatów obliczeniowych, takich jak chipy fotoniczne i obliczenia kwantowe).

## Pomóż nam osiągnąć to {#help-us-achieve-this}

[Dołącz](/join) do ruchu, aby współpracować lub [działać](/action) samodzielnie!