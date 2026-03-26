---
title: Ryzyko cyberbezpieczeństwa związane z modelami AI na granicy możliwości
description: Jak AI może być wykorzystywana do hakowania wszystkich urządzeń.
---
 <!-- end of frontmatter metadata, dashes above need to stay -->

Prawie wszystko, co robimy dzisiaj, zależy w jakiś sposób od komputerów.
Płacimy za nasze zakupy, planujemy nasz dzień, kontaktujemy się z naszymi bliskimi i nawet prowadzimy nasze samochody z użyciem komputerów.
I prawie wszystkie z tych komputerów są połączone ze sobą, tworząc ogromną sieć.
To sprawia, że wszyscy jesteśmy narażeni na ataki cybernetyczne.

Bardzo potężne cyberbronie, malware i botnety (takie jak [Stuxnet](https://www.youtube.com/watch?v=nd1x0csO3hU), [Mirai](<https://en.wikipedia.org/wiki/Mirai_(malware)>) i [EMOTET](https://en.wikipedia.org/wiki/Emotet)) zawsze były trudne do stworzenia.
Na przykład, broń cybernetyczna [Pegasus](<https://en.wikipedia.org/wiki/Pegasus_(spyware)>), kosztowała setki milionów dolarów, aby ją rozwinąć.
Znajdowanie tzw. luk w zabezpieczeniach, które jeszcze nie zostały odkryte (zero-day exploitów), wymaga dużej umiejętności i dużo czasu - tylko bardzo wyspecjalizowani hakerzy mogą to zrobić.
Jednakże, gdy AI stanie się wystarczająco zaawansowana, to już nie będzie takie.
Zamiast musieć zatrudniać zespół wysoko wykwalifikowanych ekspertów ds. bezpieczeństwa/hakerów, aby znaleźć luki zero-day, każdy mógłby po prostu użyć znacznie tańszego AI.

## Modele AI mogą samodzielnie znajdować i wykorzystywać luki w zabezpieczeniach {#ai-models-can-autonomously-find-and-exploit-vulnerabilities}

Najnowsze systemy AI już mogą analizować i pisać oprogramowanie.
Mogą [znajdować luki w zabezpieczeniach](https://betterprogramming.pub/i-used-gpt-3-to-find-213-security-vulnerabilities-in-a-single-codebase-cc3870ba9411) w oprogramowaniu i [mogą być wykorzystywane do ich wykorzystania](https://blog.checkpoint.com/2023/03/15/check-point-research-conducts-initial-security-analysis-of-chatgpt4-highlighting-potential-scenarios-for-accelerated-cybercrime/).
GPT-4 już może [samodzielnie hakować strony internetowe](https://arxiv.org/html/2402.06664v1), wykonując zadania tak złożone, jak ekstrakcja schematu bazy danych i iniekcja SQL bez informacji zwrotnej od ludzi, co zostało odkryte 18 miesięcy po zakończeniu szkolenia GPT-4.
GPT-4 już [przewyższa 88%](https://arxiv.org/pdf/2402.11814.pdf) ludzkich hakerów w konkursie CTF.
Może również [samodzielnie wykorzystywać 87% przetestowanych luk w zabezpieczeniach](https://arxiv.org/abs/2404.08144), co jest ogromnym postępem w porównaniu z GPT-3.5 lub modelami open-source, które wszystkie uzyskały 0%.
Zespoły składające się z wielu modeli językowych (LLM) mogą [działać jeszcze lepiej](https://arxiv.org/abs/2406.01637) - są w stanie wykorzystywać rzeczywiste luki zero-day.
Im większe są możliwości AI, tym większe są luki w zabezpieczeniach, które mogą wykryć i exploity, które mogą stworzyć.
Nie są jeszcze tak dobre w tym, jak najlepsi ludzie, więc na razie niebezpieczeństwo jest ograniczone.
Jednakże, możliwości rosną bardzo szybko i mogą skoczyć do przodu w każdej chwili.

Należy zauważyć, że AI umożliwia również całkowicie nowe rodzaje ataków.
Na przykład, AI może być wykorzystywana do [słuchania hasła, które wpisujesz podczas połączenia online](https://beebom.com/ai-crack-password-listening-keyboard-sounds/)
lub do [widzenia ludzi przez ściany za pomocą Wi-Fi](https://www.marktechpost.com/2023/02/15/cmu-researchers-create-an-ai-model-that-can-detect-the-pose-of-multiple-humans-in-a-room-using-only-the-signals-from-wifi/).
AI może być również wykorzystywana do tworzenia [samomodyfikującego się oprogramowania złośliwego (malware)](https://www.hyas.com/blog/blackmamba-using-ai-to-generate-polymorphic-malware), co utrudnia jego wykrycie.

Prawdopodobnie nadejdzie moment, w którym AI będzie lepsza w hakowaniu niż najlepsi ludzcy hakerzy.
To może pójść nie tak w wielu różnych sposobach.

- **Infrastruktura**: Cyberbronie mogą być wykorzystywane do uzyskania dostępu lub wyłączenia krytycznej infrastruktury, takiej jak [rurociągi naftowe](https://en.wikipedia.org/wiki/Colonial_Pipeline_ransomware_attack) lub [sieci energetyczne](https://obr.uk/box/cyber-attacks-during-the-russian-invasion-of-ukraine/).
- **Finanse**: Cyberbronie mogą być wykorzystywane do [kradzieży pieniędzy z banków](https://en.wikipedia.org/wiki/2015%E2%80%932016_SWIFT_banking_hack) lub do [manipulowania rynkiem akcji](https://en.wikipedia.org/wiki/2010_flash_crash).
- **Wojskowość**: Urządzenia takie jak broń i czujniki coraz bardziej zależą od połączeń bezprzewodowych i złożonego oprogramowania.

## Ataki cybernetyczne na dużą skalę {#large-scale-cyberattacks}

Może być możliwe, że tak potężna AI będzie wykorzystywana do stworzenia wirusa, który wykorzystuje wiele luk zero-day.
Wystarczająco wykwalifikowana AI mogłaby analizować i znajdować luki w zabezpieczeniach w kodzie źródłowym wszystkich systemów operacyjnych i innych programów.
Taki wirus mógłby zainfekować każdy komputer, niezależnie od systemu operacyjnego, za pomocą wielu kanałów, takich jak Wi-Fi, Bluetooth, UTP itp.
To mogłoby dać pełną kontrolę nad tymi maszynami i pozwolić kontrolerowi na kradzież danych, wykorzystanie sprzętu do własnych obliczeń, zaszyfrowanie zawartości w celu okupu lub [wyłączenie maszyny całkowicie](https://en.wikipedia.org/wiki/Hardware_Trojan).

Wirus taki mógłby być stworzony jako narzędzie przez przestępców do kradzieży pieniędzy lub jako bardzo destrukcyjna broń cybernetyczna przez naród lub organizację terrorystyczną.
Jednakże, gdy AI staje się bardziej autonomiczna, może być również samodzielnie stworzona i wdrożona przez [niezgodną AI](/xrisk).

Jeśli celem ataku cybernetycznego było wyłączenie urządzeń i infrastruktury, szkody mogłyby być ogromne.
Nasze społeczeństwo coraz bardziej zależy od komputerów i internetu.
Płatności, transport, komunikacja, planowanie, łańcuchy dostaw, sieci energetyczne...
Jeśli nasze urządzenia przestaną działać prawidłowo, wiele części naszego społeczeństwa przestanie działać również.

Ponad [93% ekspertów ds. cyberbezpieczeństwa](https://www.weforum.org/publications/global-cybersecurity-outlook-2023/) uważa, że „zdarzenie cybernetyczne o dużym zasięgu i katastrofalnych skutkach jest prawdopodobne w ciągu najbliższych dwóch lat”.

## Zmniejszanie ryzyka cyberbezpieczeństwa AI {#mitigating-ai-cybersecurity-risks}

Historia powyżej może się zdarzyć tylko wtedy, gdy:

1. **Możliwość znajdowania luk zero-day** się pojawi. Obecne modele już mogą odkryć niektóre luki w zabezpieczeniach, ale to prawdopodobnie poprawi się z nowymi modelami.
2. **Model trafia w ręce złych aktorów**. To może się zdarzyć, jeśli wagi modelu są przecieka, jeśli model jest otwarty lub jeśli jest rozwijany przez złego aktora.
3. **Luki w zabezpieczeniach nie są naprawione** przed wdrożeniem takiej broni cybernetycznej. Niestety, obrońcy są w niekorzystnej sytuacji, jeśli model jest szeroko rozpowszechniony z dwóch powodów:
   1. Naprawa + wydanie + wdrożenie zajmuje znacznie więcej czasu niż atak. Okno podatności jest większe niż czas potrzebny do stworzenia ataku.
   2. Atakujący muszą znaleźć tylko jedną lukę w zabezpieczeniach, podczas gdy obrońcy muszą znaleźć wszystkie.

Istnieją różne środki, które możemy zastosować, aby rozwiązać te problemy:

- **Nie pozwól na szkolenie modeli, które mogą znaleźć luki zero-day**. To jest najskuteczniejszy sposób, aby temu zapobiec. To jest najbezpieczniejsza ścieżka, i to jest to, co [proponujemy](/proposal).
- **Pozwól na wdrożenie lub otwarcie modeli tylko po przeprowadzeniu szczegółowych testów**. Jeśli mają niebezpieczne możliwości, nie wydawaj ich.
- **Wprowadź surowe przepisy dotyczące cyberbezpieczeństwa, aby zapobiec przeciekowi wag modelu**. Jeśli pozwolisz na istnienie niebezpiecznych modeli, upewnij się, że nie wpadną w niepowołane ręce.
- **Wymagaj od firm AI, aby wykorzystywały AI do naprawy luk w zabezpieczeniach**. Jeśli model jest szkolony, aby mógł znaleźć nowe luki w zabezpieczeniach, wykorzystaj to, aby skontaktować się z utrzymującymi oprogramowanie, aby naprawić te luki w zabezpieczeniach. Dać procesowi naprawy wystarczająco dużo czasu przed wdrożeniem modelu. Upewnij się, że wagi nie są przecieka, i chronić model tak, jakby to był kod startowy dla uderzenia nuklearnego. Jeśli to jest zrobione prawidłowo, AI może dramatycznie poprawić cyberbezpieczeństwo wszędzie.