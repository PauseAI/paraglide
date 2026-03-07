---
title: Regulacja niebezpiecznych zdolności w sztucznej inteligencji
description: Im bardziej zaawansowana staje się sztuczna inteligencja w określonych dziedzinach, tym większe stają się ryzyka. Jak możemy zapobiec pojawieniu się lub rozprzestrzenianiu tych niebezpiecznych zdolności?
---

W tym artykule omówimy:

- Jakie zdolności sztucznej inteligencji mogą być niebezpieczne
- Jak możemy zapobiec pojawieniu się lub rozprzestrzenianiu tych zdolności
- Dlaczego niebezpieczne jest poleganie wyłącznie na [ocenach](/evaluations) jako środku polityki

Wraz ze wzrostem mocy i przydatności modeli sztucznej inteligencji stają się one również bardziej niebezpieczne.
Więc w którym momencie powinniśmy zachować ostrożność?
Jednym z często wymienianych progów jest AGI - lub Sztuczna Inteligencja Ogólna.
Istnieje wiele debat na temat tego, co dokładnie oznacza AGI.
Niektórzy twierdzą, że to moment, w którym sztuczna inteligencja może wykonywać wszystkie zadania poznawcze, które może wykonywać człowiek.
Niektórzy twierdzą, że GPT-4 już jest AGI.
Steve Wozniak definiuje AGI jako pierwszy system, który może wejść do kuchni i zrobić filiżankę kawy.

Z perspektywy bezpieczeństwa definicja AGI nie jest tak ważna.
W rzeczywistości może dać nam fałszywe poczucie bezpieczeństwa, ponieważ możemy myśleć, że jesteśmy bezpieczni, dopóki nie osiągniemy AGI.
Nawet jeśli sztuczna inteligencja nie może zrobić filiżanki kawy, nadal może być niebezpieczna.
To, co się liczy, to _jakie zdolności posiada sztuczna inteligencja_.

W tym artykule zagłębimy się w różne niebezpieczne zdolności i to, co możemy zrobić, aby zapobiec ich pojawieniu się i wyrządzeniu nam szkody.

## Jakie zdolności mogą być niebezpieczne? {#which-capabilities-can-be-dangerous}

- **Cyberbezpieczeństwo**. Gdy sztuczna inteligencja jest w stanie odkryć luki w zabezpieczeniach (zwłaszcza nowe, nieznane), może (być użyta do) [włamania się do systemów](/cybersecurity-risks). Obecne [najnowocześniejsze](/sota) systemy sztucznej inteligencji mogą znaleźć niektóre luki w zabezpieczeniach, ale jeszcze nie na niebezpiecznym, zaawansowanym poziomie. Jednak wraz ze wzrostem zdolności w zakresie cyberbezpieczeństwa wzrasta również potencjalna szkoda, jaką mogą wyrządzić cyberbronie wspomagane przez sztuczną inteligencję. Duże ataki cybernetyczne mogą zakłócić naszą infrastrukturę, wyłączyć płatności i spowodować chaos.
- **Biologiczne**. Projektowanie nowych czynników biologicznych lub pomoc w procesie inżynierii pandemii. Grupa studentów była w stanie użyć chatbota do [wytworzenia wszystkich kroków niezbędnych do stworzenia nowej pandemii](https://arxiv.org/abs/2306.03809). Sztuczna inteligencja zaprojektowana do znalezienia bezpiecznych leków została użyta do odkrycia [40 000 nowych broni chemicznych w ciągu sześciu godzin](https://www.theverge.com/2022/3/17/22983197/ai-new-possible-chemical-weapons-generative-models-vx).
- **Ulepszenia algorytmiczne**. Sztuczna inteligencja, która może znaleźć wydajne algorytmy dla danego problemu, może doprowadzić do rekurencyjnej pętli samodoskonalenia, wirującej szybko poza kontrolą. Nazywa się to _eksplozją inteligencji_. Wynikająca z tego sztuczna inteligencja byłaby niezwykle potężna i mogłaby mieć wszystkie rodzaje innych niebezpiecznych zdolności. Na szczęście żadna sztuczna inteligencja jeszcze nie może sama się ulepszać. Jednak istnieją sztuczne inteligencje, które mogą znaleźć nowe, bardzo wydajne algorytmy (jak [AlphaDev](https://www.deepmind.com/blog/alphadev-discovers-faster-sorting-algorithms)).
- **Oszustwo**. Zdolność do manipulowania ludźmi, w tym inżynierii społecznej. Różne formy oszustwa są [już obecne](https://lethalintelligence.ai/post/ai-hired-human-to-solve-captcha/) w obecnych systemach sztucznej inteligencji. Na przykład CICERO AI firmy Meta (która została opracowana, aby doprowadzić do "lepszej, bardziej naturalnej współpracy między sztuczną inteligencją a człowiekiem") okazała się ekspertem w kłamstwach, oszukującym innych agentów w grze. Sztuczna inteligencja, która może oszukiwać ludzi, może oszukiwać ich podczas przebiegu treningowego. Mogłaby ukryć swoje zdolności lub zamiary.
- **Samoreplikacja**. Jeśli sztuczna inteligencja może tworzyć nowe instancje na innych maszynach, istnieje ryzyko, że rozprzestrzeni się niekontrolowanie, prowadząc do [_przejęcia przez sztuczną inteligencję_](/ai-takeover). Wystarczająco zdolna sztuczna inteligencja mogłaby przewyższyć ludzi i doprowadzić do [wymarcia ludzkości](/xrisk). Należy zauważyć, że mogłoby to nastąpić nawet przed wdrożeniem modelu sztucznej inteligencji.

Ta lista nie jest wyczerpująca, więc istnieją inne niebezpieczne zdolności, które mogłaby mieć sztuczna inteligencja.

## Zapobieganie powstawaniu niebezpiecznych zdolności {#preventing-creation-of-dangerous-capabilities}

Czy możemy zapobiec pojawieniu się tych niebezpiecznych zdolności?
Wraz ze wzrostem rozmiaru sztucznych inteligencji i szkoleniem na większych zbiorach danych zdobywają one nowe umiejętności.
Okazuje się, że bardzo trudno jest przewidzieć, jakie umiejętności się pojawią i jak dobrze sztuczna inteligencja będzie działać.
Z tego powodu często nazywa się je _zdolnościami emergentnymi_.

<!-- Przykład dotyczący teorii umysłu, wykres -->

Nasz obecny paradygmat dużych modeli językowych jest prawie nieodłącznie nieprzewidywalny.
Modele sztucznej inteligencji nie są pisane jak oprogramowanie - są trenowane.
Są to czarne skrzynki składające się z miliardów parametrów numerycznych.
Nikt tak naprawdę nie wie, co dzieje się w środku.
Ta nieprzewidywalność sprawia, że trudno jest powiedzieć, czy przebieg treningowy spowoduje powstanie niebezpiecznej sztucznej inteligencji.
Badania nad interpretacją mogą to zmienić w przyszłości, ale obecnie nie możemy naprawdę wyjaśnić, dlaczego sztuczna inteligencja robi to, co robi.

Więc zapobieganie powstawaniu niebezpiecznych zdolności może być praktycznie wykonane tylko w jeden sposób:
nie buduj coraz potężniejszych systemów sztucznej inteligencji od samego początku.
To byłby najbezpieczniejszy sposób postępowania, ale to nie to, co proponują laboratoria sztucznej inteligencji.

## Zapobieganie rozprzestrzenianiu się niebezpiecznych zdolności {#preventing-the-proliferation-of-dangerous-capabilities}

Obecnie wiele dzieje się w przestrzeni regulacji sztucznej inteligencji.
Wiele z tych propozycji (w tym wszystkie pochodzące z laboratoriów sztucznej inteligencji) polega na **ocenach** (lub _evals_): testach przedwdrożeniowych modeli sztucznej inteligencji.
Przykładem takich podejść opartych na ocenie jest [podejście RSP firmy Anthropic](https://evals.alignment.org/blog/2023-09-26-rsp/#:~:text=An%20RSP%20specifies%20what%20level,capabilities%20until%20protective%20measures%20improve.) lub [podejście Coordinated Pausing](https://www.governance.ai/research-paper/coordinated-pausing-evaluation-based-scheme) firmy GovAI.
Odnosimy się do nich jako [poziom 2 regulacji](/4-levels-of-ai-regulation).
Te oceny nie zapobiegają powstawaniu niebezpiecznych sztucznych inteligencji, ale zapobiegają ich _wdrożeniu_.
Ten rodzaj polityki jest stosunkowo tani i nadal pozwala laboratoriom sztucznej inteligencji kontynuować badania.
Jednak uważamy, że ten sposób postępowania jest bardzo niebezpieczny:

- **Modele mogą być wyciekane**.
  Widzieliśmy to w przypadku modelu LLAMA firmy Meta. Gdy już jest na zewnątrz, nie ma odwrotu.
- **Niektóre zdolności są nawet niebezpieczne w laboratoriach sztucznej inteligencji**.
  Sztuczna inteligencja, która może się samoreplikować, mogłaby na przykład [uciec z laboratorium przed wdrożeniem](https://lethalintelligence.ai/post/ai-escaped-its-container/).
- **Testowanie pod kątem niebezpiecznych zdolności jest trudne**.
  Nie wiemy, jak możemy (bezpiecznie) przetestować, czy sztuczna inteligencja może się samoreplikować, na przykład. Lub jak przetestować, czy oszukuje ludzi
- **Zdolności mogą być dodawane lub odkrywane po treningu**.
  Obejmuje to dostosowanie, jailbreaking i ulepszenia w czasie wykonywania.

Zagłębimy się w ten ostatni punkt bardziej szczegółowo.

## Zdolności mogą być dodawane po treningu {#capabilities-can-be-added-after-training}

### Dostosowanie {#fine-tuning}

Dostosowanie może być użyte do ulepszenia zdolności istniejącego modelu sztucznej inteligencji.
Jest to podobne do treningu, ale jest znacznie szybsze, znacznie tańsze, nie wymaga tak dużej ilości danych i często może być wykonane na sprzęcie konsumenckim.
Dostosowanie zmienia parametry sztucznej inteligencji i jako takie zmienia jej zdolności.
Teraz dostosowanie nie jest tak potężne jak wykonanie pełnego przebiegu treningowego, ale nadal może ulepszyć istniejące zdolności.

### Jailbreaking {#jailbreaking}

Największe sztuczne inteligencje są trenowane na absolutnie ogromnych zbiorach danych.
Większość książek, artykułów naukowych i stron internetowych w Internecie.
Jest wiele nieprzyjemnych rzeczy w tych zbiorach danych.
Sztuczne inteligencje są często dostosowywane przy użyciu techniki zwanej RLHF (Reinforcement Learning from Human Feedback), aby sprawić, by były pomocne i miłe.
W tym procesie sztuczna inteligencja musi nauczyć się nie mówić pewnych rzeczy, jak robienie rasistowskich uwag, wyjaśnianie, jak zrobić bombę lub jak stworzyć nową broń biologiczną.

Ale te zabezpieczenia nie są doskonałe.
Tak zwane "jailbreaking" to technika, w której próbujesz sprawić, by sztuczna inteligencja zignorowała te zabezpieczenia.
Może to być wykonane przez [dołączenie niektórych konkretnych słów lub znaków do wiadomości czatu](https://twitter.com/AIPanicLive/status/1678942758872989696), lub przez [kreatywne przefrazowanie wiadomości](https://twitter.com/_annieversary/status/1647865782741749760).
Nie jest [jasne](https://llm-attacks.org/), czy takie zachowanie może być kiedykolwiek w pełni naprawione.

### Ulepszenia w czasie wykonywania {#runtime-improvements}

Ulepszenia w czasie wykonywania nie wprowadzają zmian w modelu, ale zamiast tego ulepszają sposób, w jaki model jest używany.

Najprostsze z nich to zmiana podpowiedzi.
Nawet niewielkie zmiany w podpowiedziach mogą mieć duży wpływ na wynik modelu.
Dodanie kilku słów do podpowiedzi może poprawić wyniki [o ponad 50%](https://arxiv.org/pdf/2309.03409.pdf).

Ale możemy również używać wszelkiego rodzaju oprogramowania do ulepszenia podstawowego modelu.
Na przykład ludzie znaleźli sposoby na dodanie długoterminowej pamięci do GPT-4, pozwalając modelowi wysyłać zapytania do bazy danych.
Lub rozważ AutoGPT, który pozwala modelowi wywoływać się rekurencyjnie, co oznacza, że może działać autonomicznie przez dowolny okres czasu.
Lub rozważ [Voyager](https://arxiv.org/abs/2305.16291), narzędzie, które umożliwiło GPT-4 granie w Minecraft w pełni autonomicznie. Nawet zdobył diamentowe wyposażenie.

Nie wiemy, jak daleko można rozciągnąć podstawowy model.
Nawet jeśli przestaniemy trenować nowe modele sztucznej inteligencji teraz, prawdopodobnie zobaczymy ważne innowacje, które dodadzą nowe zdolności do istniejących modeli.

## Podsumowanie {#in-conclusion}

Niebezpieczne zdolności sztucznej inteligencji mogą prowadzić do wszelkiego rodzaju problemów: dużych ataków cybernetycznych, inżynierii pandemii i sztucznej inteligencji, która [przejmuje kontrolę](/ai-takeover).
Jest kuszące poleganie na ocenach, aby zapobiec pojawieniu się lub rozprzestrzenianiu tych niebezpiecznych zdolności, ale jest to niebezpieczne podejście:

- Nawet jeśli testujemy modele przed ich wdrożeniem, nadal istnieją sposoby, w których mogą zdobyć niebezpieczne zdolności po wdrożeniu (dostosowanie, jailbreaking, ulepszenia w czasie wykonywania).
- Modele mogą być wyciekane.
- Niektóre zdolności są nawet niebezpieczne w laboratoriach sztucznej inteligencji.

Jedyną bezpieczną opcją jest nie budowanie tych potężnych systemów sztucznej inteligencji od samego początku.
Nie powinniśmy pozwolić na tworzenie tych nieprzewidywalnych, potencjalnie bardzo niebezpiecznych systemów sztucznej inteligencji.
[Niestety, żaden z obecnych projektów nie zapobiega ani nie opóźnia powstania superinteligentnej sztucznej inteligencji.](https://twitter.com/PauseAI/status/1704998018322141496)
Dlatego [wzywamy do wstrzymania](/proposal)!