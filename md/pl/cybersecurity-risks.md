---
title: Ryzyka bezpieczeństwa cybernetycznego związane z modelami AI nowej generacji
description: Jak AI może być wykorzystana do zhakowania wszystkich urządzeń.
---

Praktycznie wszystko, co robimy dzisiaj, jest w jakiś sposób zależne od komputerów. Płacimy za zakupy, planujemy nasze dni, kontaktujemy się z bliskimi i nawet prowadzimy samochody za pomocą komputerów. I praktycznie wszystkie te komputery są połączone ze sobą. To sprawia, że wszyscy jesteśmy podatni na ataki cybernetyczne.

Bardzo potężne cyberbronie, złośliwe oprogramowanie i botnety (takie jak [Stuxnet](https://www.youtube.com/watch?v=nd1x0csO3hU), [Mirai](<https://pl.wikipedia.org/wiki/Mirai_(z%C5%82o%C5%9Bliwe_oprogramowanie)>) i [EMOTET](https://pl.wikipedia.org/wiki/Emotet)) zawsze były trudne do stworzenia. Na przykład [cyberbroń Pegasus](<https://pl.wikipedia.org/wiki/Pegasus_(oprogramowanie_szpiegowskie)>), kosztowała setki milionów dolarów do rozwoju. Znalezienie tzw. exploitów zero-day (podatności, które jeszcze nie zostały odkryte) wymaga wielu umiejętności i czasu - tylko wyspecjalizowani hakerzy mogą to zrobić. Jednak, gdy AI stanie się wystarczająco zaawansowana, nie będzie to już problem. Zamiast zatrudniać zespół wysoko wykwalifikowanych ekspertów ds. bezpieczeństwa/hakerów, aby znaleźć luki w zabezpieczeniach, każdy mógłby po prostu użyć znacznie tańszej AI.

## Modele AI mogą samodzielnie znaleźć i wykorzystać luki w zabezpieczeniach {#ai-models-can-autonomously-find-and-exploit-vulnerabilities}

Najnowsze systemy AI mogą już analizować i pisać oprogramowanie. Mogą [znaleźć luki w zabezpieczeniach](https://betterprogramming.pub/i-used-gpt-3-to-find-213-security-vulnerabilities-in-a-single-codebase-cc3870ba9411) w oprogramowaniu i [mogą być użyte do ich wykorzystania](https://blog.checkpoint.com/2023/03/15/check-point-research-conducts-initial-security-analysis-of-chatgpt4-highlighting-potential-scenarios-for-accelerated-cybercrime/). GPT-4 może już [samodzielnie zhakować strony internetowe](https://arxiv.org/html/2402.06664v1), wykonując zadania tak złożone jak wydobycie schematu bazy danych i wstrzykiwanie kodu SQL bez informacji zwrotnych od człowieka, co zostało odkryte 18 miesięcy po zakończeniu szkolenia GPT-4. GPT-4 już [przewyższa 88%](https://arxiv.org/pdf/2402.11814.pdf) ludzkich hakerów w konkursie CTF. Może również [samodzielnie wykorzystać 87% testowanych luk w zabezpieczeniach](https://arxiv.org/abs/2404.08144), co jest ogromnym krokiem naprzód w porównaniu z GPT-3.5 lub modelami open-source, które wszystkie uzyskały 0%. Zespoły wielu LLM [działają jeszcze lepiej](https://arxiv.org/abs/2406.01637) - mogą wykorzystać rzeczywiste luki w zabezpieczeniach zero-day. W miarę wzrostu możliwości AI, wzrasta również liczba luk w zabezpieczeniach, które mogą wykryć i stworzyć. Nie są jeszcze tak dobrzy w tym, jak najlepsi ludzie, więc obecnie niebezpieczeństwo jest ograniczone. Jednak możliwości szybko rosną i mogą skoczyć dość nagle.

Należy zauważyć, że AI umożliwia również zupełnie nowe rodzaje ataków. Na przykład AI może być użyta do [usłyszenia hasła, które wpisałeś podczas rozmowy online](https://beebom.com/ai-crack-password-listening-keyboard-sounds/), lub użyć [Wi-Fi, aby zobaczyć ludzi przez ściany](https://www.marktechpost.com/2023/02/15/cmu-researchers-create-an-ai-model-that-can-detect-the-pose-of-multiple-humans-in-a-room-using-only-the-signals-from-wifi/). AI może być również użyta do stworzenia [samomodyfikującego się złośliwego oprogramowania](https://www.hyas.com/blog/blackmamba-using-ai-to-generate-polymorphic-malware), co sprawia, że jest znacznie trudniejsze do wykrycia.

Prawdopodobnie nadejdzie moment, w którym AI będzie lepsza w hakowaniu niż najlepsi ludzcy hakerzy. To może pójść źle na wiele sposobów.

- **Infrastruktura**: Cyberbronie mogą być użyte do uzyskania dostępu lub wyłączenia krytycznej infrastruktury, takiej jak [rurociągi naftowe](https://pl.wikipedia.org/wiki/Atak_ransomware_na_Colonial_Pipeline) lub [sieci energetyczne](https://obr.uk/box/cyber-attacks-during-the-russian-invasion-of-ukraine/).
- **Finanse**: Cyberbronie mogą być użyte do [kradzieży pieniędzy z banków](https://pl.wikipedia.org/wiki/Atak_hakerski_na_SWIFT_w_2015_i_2016_roku) lub do [manipulowania rynkiem akcji](https://pl.wikipedia.org/wiki/Flash_crash_w_2010_roku).
- **Wojskowość**: Urządzenia takie jak broń i czujniki są coraz bardziej zależne od łączności bezprzewodowej i złożonego oprogramowania.

## Duże ataki cybernetyczne {#large-scale-cyberattacks}

Możliwe jest, że tak potężna AI zostanie użyta do stworzenia wirusa, który wykorzystuje dużą liczbę luk w zabezpieczeniach zero-day. Wystarczająco zdolna AI mogłaby analizować i znaleźć luki w zabezpieczeniach w kodzie źródłowym wszystkich systemów operacyjnych i innych oprogramowań. Taki wirus mógłby zainfekować dowolny komputer, niezależnie od systemu operacyjnego, poprzez wiele kanałów, takich jak Wi-Fi, Bluetooth, UTP itp. To mogłoby dać pełną kontrolę nad tymi maszynami i pozwolić kontrolerowi na kradzież danych, użycie sprzętu do własnych obliczeń, zaszyfrowanie zawartości w celu okupu lub [całkowite wyłączenie maszyny](https://pl.wikipedia.org/wiki/Hardware_Trojan).

Wirus taki mógłby być stworzony jako narzędzie przez przestępców do kradzieży pieniędzy lub jako bardzo destrukcyjna broń cybernetyczna przez naród lub organizację terrorystyczną. Jednak w miarę jak AI staje się bardziej agentywna, mogłaby również być samodzielnie stworzona i rozmieszczona przez [źle ustawioną AI](/xrisk).

Jeśli celem ataku cybernetycznego było wyłączenie urządzeń i infrastruktury, szkody mogłyby być ogromne. Nasze społeczeństwo jest coraz bardziej zależne od komputerów i Internetu. Płatności, transport, komunikacja, planowanie, łańcuchy dostaw, sieci energetyczne... Jeśli nasze urządzenia nie działają prawidłowo, wiele części naszego społeczeństwa również przestaje działać.

Ponad [93% ekspertów ds. bezpieczeństwa cybernetycznego](https://www.weforum.org/publications/global-cybersecurity-outlook-2023/) uważa, że „daleko idące, katastrofalne zdarzenie cybernetyczne jest prawdopodobne w ciągu najbliższych dwóch lat”.

## Zmniejszanie ryzyka bezpieczeństwa cybernetycznego AI {#mitigating-ai-cybersecurity-risks}

Historia powyżej może się wydarzyć tylko wtedy, gdy:

1. **Możliwość znalezienia luk w zabezpieczeniach zero-day** pojawi się. Obecne modele mogą już odkrywać niektóre luki w zabezpieczeniach, ale prawdopodobnie ulegnie to poprawie wraz z nowszymi modelami.
2. **Model trafia w ręce złych aktorów**. Może to się stać, jeśli wagi modelu zostaną wyciekłe, jeśli model zostanie udostępniony jako open-source lub jeśli zostanie opracowany przez złośliwego aktora.
3. **Luki w zabezpieczeniach nie zostaną załatane** przed wdrożeniem takiej cyberbroni. Niestety, obrońcy są w niekorzystnej sytuacji, jeśli model jest szeroko rozpowszechniony z dwóch powodów:
   1. Łatanie + wydanie + wdrożenie zajmuje znacznie więcej czasu niż atak. Okno podatności jest większe niż czas potrzebny do stworzenia ataku.
   2. Atakujący muszą znaleźć tylko jedną lukę w zabezpieczeniach, podczas gdy obrońcy muszą znaleźć wszystkie.

Istnieją różne środki, które możemy wdrożyć, aby rozwiązać te problemy:

- **Nie zezwalaj na szkolenie modeli, które mogą znaleźć luki w zabezpieczeniach zero-day**. Jest to najskuteczniejszy sposób, aby temu zapobiec. Jest to najbezpieczniejsza ścieżka i to, co [proponujemy](/proposal).
- **Zezwalaj na wdrożenie lub udostępnienie modeli jako open-source tylko po przeprowadzeniu szczegółowych testów**. Jeśli mają niebezpieczne zdolności, nie udostępniaj ich.
- **Nakładaj surowe przepisy dotyczące bezpieczeństwa cybernetycznego, aby zapobiec wyciekom wag modelu**. Jeśli zezwalasz na istnienie niebezpiecznych modeli, upewnij się, że nie trafią w złe ręce.
- **Wymagaj od firm AI, aby używały AI do naprawiania luk w zabezpieczeniach**. Jeśli model jest wyszkolony, aby znaleźć nowe luki w zabezpieczeniach, użyj go, aby skontaktować się z osobami odpowiedzialnymi za oprogramowanie, aby załatać te luki. Daj procesowi łatania wystarczająco dużo czasu, zanim model zostanie udostępniony. Upewnij się, że wagi nie zostaną wyciekłe i chronij model tak, jakby był kodem startowym dla uderzenia nuklearnego. Jeśli to zostanie zrobione prawidłowo, AI może znacznie poprawić bezpieczeństwo cybernetyczne wszędzie.