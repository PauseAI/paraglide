---
title: Dlaczego możemy osiągnąć superinteligencję wcześniej niż większość ludzi myśli
description: Zaniżamy postępy w dziedzinie sztucznej inteligencji, a istnieje niewielka, ale realna szansa, że jesteśmy bardzo blisko superinteligencji.
date: '2023-05-04'
---
Bieżące [modele najnowszej generacji](/sota) są już nadludzkie w wielu dziedzinach, ale na szczęście nie we wszystkich.
Jeśli osiągniemy superinteligencję zanim rozwiążemy problem wyrównania, [zachowujemy ryzyko zagłady](/xrisk).
Dlatego też posiadanie szacowanego zakresu czasowego, w którym możemy osiągnąć superinteligencję, jest niezbędne, aby nie zaskoczyć nas niespodziewanie.
Jeśli nasze prognozy są zbyt odległe, możemy nie być w stanie przygotować się na czas.

Ale jak daleko jesteśmy od tego?
Kiedy będziemy mieli superinteligencję?
Może to być wcześniej niż większość ludzi myśli.

## Wzrost wykładniczy {#compounding-exponential-growth}

Modele sztucznej inteligencji wymagają algorytmów, danych i układów scalonych.
Każdy z tych komponentów ulega szybkiej poprawie dzięki ogromnym inwestycjom w sztuczną inteligencję.
Poprawy w każdym z tych komponentów są _nakładające się_, prowadząc do wykładniczego wzrostu możliwości sztucznej inteligencji.

- **Więcej układów scalonych**. ChatGPT został przeszkolony na [10 000](https://www.fierceelectronics.com/sensors/chatgpt-runs-10k-nvidia-training-gpus-potential-thousands-more) specjalistycznych układach scalonych. Meta ogłosiła, że [będzie posiadać 600 000](https://www.datacenterdynamics.com/en/news/meta-to-operate-600000-gpus-by-year-end/) nowych układów scalonych do szkolenia swoich następnych modeli sztucznej inteligencji w tym roku.
- **Szybsze układy scalone**. Każdego roku układy scalone stają się szybsze dzięki nowym architekturom i innowacjom w litografii. Układy scalone, których używa Meta, są 10-krotnie szybsze niż układy scalone użyte do ChatGPT. Widzimy również wyspecjalizowane urządzenia, takie jak układy scalone Groq, które są [13-krotnie szybsze](https://mezha.media/en/2024/02/22/groq-s-new-ai-chip-offers-to-increase-chatgpt-speed-by-13-times/) niż konkurencja. W dłuższej perspektywie [architektury trójwartościowe](https://arxiv.org/pdf/2402.17764.pdf) lub [układy scalone fotoniczne](https://www.nature.com/articles/s41566-024-01394-2) mogą sprawić, że układy scalone staną się jeszcze szybsze.
- **Więcej danych**. GPT3 został przeszkolony na [45 TB](https://community.openai.com/t/what-is-the-size-of-the-training-set-for-gpt-3/360896) tekstu, GPT4 użył około 20-krotnie więcej. Firmy sztucznej inteligencji używają również [ogromnych ilości danych wideo](https://www.404media.co/nvidia-ai-scraping-foundational-model-cosmos-project/), danych audio i generują [syntetyczne dane do szkolenia tych modeli](https://arxiv.org/pdf/2401.10020). Wcześniej uważano, że użycie syntetycznych danych do szkolenia jest niemożliwe z powodu załamania modelu, ale [ostatnie postępy](https://arxiv.org/abs/2406.07515) pokazują, że zapobieganie załamaniu modelu jest możliwe.
- **Lepsze dane**. Artykuł "Podręczniki są wszystkim, czego potrzebujesz" [pokazał](https://arxiv.org/abs/2306.11644), że użycie wysokiej jakości syntetycznych danych może drastycznie poprawić wydajność modelu, nawet jeśli użyto znacznie mniej danych i obliczeń.
- **Lepsze algorytmy**. Architektura Transformer umożliwiła bieżącą rewolucję w modelach językowych. Nowe architektury mogą umożliwić podobne skoki wydajności. Na przykład model Mamba [pokazuje](https://arxiv.org/abs/2312.00752) 5-krotnie szybszy przepływ danych.
- **Lepsze środowiska wykonawcze**. Środowiska wykonawcze Agentic, Retrieval Augmented Generation lub po prostu inteligentne wprowadzanie danych (przykładowo za pomocą [Grafu Myśli](https://arxiv.org/abs/2305.16582)) mogą mieć ogromny wpływ na możliwości tych modeli.

Całkiem możliwe, że _po prostu skalowanie_ wystarczy, aby osiągnąć [niebezpieczne możliwości](/dangerous-capabilities) w ciągu roku lub dwóch, ale ze wszystkimi tymi nakładającymi się czynnikami, może to nastąpić nawet szybciej.

## Osiągnięliśmy poziom ludzki w wielu dziedzinach w 2023 roku {#we-reached-human-level-performance-in-many-domains-in-2023}

W 2022 roku badacze sztucznej inteligencji uważali, że zajmie to [17 lat](https://aiimpacts.org/2022-expert-survey-on-progress-in-ai/), zanim sztuczna inteligencja będzie w stanie napisać bestseller New York Timesa.
Rok później chiński profesor [wygrał konkurs pisarski](https://www.scmp.com/news/china/science/article/3245725/chinese-professor-used-ai-write-science-fiction-novel-then-it-won-national-award) z powieścią napisaną przez sztuczną inteligencję.

Na Metaculus [przewidywania społeczności dotyczące (słabej) AGI](https://www.metaculus.com/questions/3479/date-weakly-general-ai-is-publicly-known/) były ustalone na 2057 rok, a teraz jest to 2027 rok.

Teraz, przejdźmy do definicji AGI użytej w tym badaniu:

- Wynik >90% w teście Winograd Schema Challenge
- Wynik >75% w teście SAT
- Przejście testu Turinga
- Ukończenie Montezumy'ego zemsty

GPT-4 uzyskał [wynik 94,4% w teście Winograd Schema Challenge](https://d-kz.medium.com/evaluating-gpt-3-and-gpt-4-on-the-winograd-schema-challenge-reasoning-test-e4de030d190d) i [wynik 93% w teście SAT z czytania, 89% w teście SAT z matematyki](https://www.cnbc.com/2023/03/14/openai-announces-gpt-4-says-beats-90percent-of-humans-on-sat.html).
Nie przeszedł testu Turinga, ale prawdopodobnie nie z powodu braku możliwości.
To dlatego, że GPT-4 został wyrafinowany, aby nie wprowadzać ludzi w błąd. Nie jest to dobre dla biznesu, jeśli twoja sztuczna inteligencja mówi ludziom, że jest naprawdę osobą.
To pozostawia tylko Montezumę'ego zemstę.
Nie jest to nie do pomyślenia, że może to być ukończone przez inteligentne ustawienie GPT-4, używając czegoś takiego jak AutoGPT do analizy ekranu i generowania poprawnych danych wejściowych.
W maju 2023 roku [GPT-4 był w stanie napisać kod, aby uzyskać diamentowy sprzęt w Minecraft](https://the-decoder.com/minecraft-bot-voyager-programs-itself-using-gpt-4/).
Krótko mówiąc: GPT-4 spełnił 2/4 kryteriów z pewnością, a pozostałe dwa są w zasięgu.

**Jesteśmy tam, ludzie.
Już mamy (słabą) AGI.**
Nie zajęło nam 35 lat, zajęło nam trzy.
Byliśmy błędni o czynnik 10.

## Dlaczego większość ludzi zaniża postępy sztucznej inteligencji {#why-most-underestimate-the-progress-of-ai}

Istnieje wiele powodów, dla których ludzie zaniżają postępy sztucznej inteligencji.

- **Trudno nadążyć**. Prawie codziennie widzimy nowe przełomy w sztucznej inteligencji. Jest to prawie niemożliwe, aby nadążyć za tempem postępu. Nie jesteś sam, jeśli czujesz, że spadasz za nimi.
- **Stawiamy poprzeczkę coraz wyżej**. W latach 90. ludzie uważali, że święty Graal sztucznej inteligencji to coś, co może grać w szachy. Kiedy sztuczna inteligencja pokonała Kasparowa, następnym wyzwaniem było Go. Teraz mamy maszyny, które uzyskują wynik w [99,9 percentylu testów inteligencji](https://bgr.com/tech/chatgpt-took-an-iq-test-and-its-score-was-sky-high/), mogą [tłumaczyć 26 języków](https://bgr.com/tech/chatgpt-took-an-iq-test-and-its-score-was-sky-high/) i [wygrywać konkursy fotograficzne](https://www.scientificamerican.com/article/how-my-ai-image-won-a-major-photography-competition/), a jednak wciąż zadajemy pytania w rodzaju "Kiedy sztuczna inteligencja osiągnie poziom ludzki?". Już przewyższa nas w wielu dziedzinach, ale zawsze koncentrujemy się na coraz mniejszej liczbie rzeczy, które możemy robić lepiej.
- **Lubimy myśleć, że jesteśmy wyjątkowi**. Ludzie lubią czuć, że są wyjątkowi. Jeśli sztuczna inteligencja może robić to, co my, nie jesteśmy już wyjątkowi. To trudna pigułka do połknięcia, a [mózg ma wiele mechanizmów obronnych, aby uniknąć tego](psychology-of-x-risk).
- **Jesteśmy bardzo źli w szacowaniu wzrostu wykładniczego**. Mamy tendencję do systematycznego i przewidywalnego zaniżania, jak wzrost wykładniczy kumuluje się w czasie. To zostało udowodnione w [badaniach naukowych](https://www.researchgate.net/figure/Underestimation-of-exponential-growth-a-shows-the-participants-prediction-of-the_fig4_351171143).

Na szczęście istnieją jeszcze rzeczy, których sztuczna inteligencja nie potrafi zrobić.
Nie może [hakować lepiej niż najlepsi hakerzy](/cybersecurity-risks), i nie może prowadzić badań nad sztuczną inteligencją tak dobrze jak najlepsi badacze sztucznej inteligencji.
**Kiedy osiągniemy którykolwiek z tych progów, będziemy w nowej fazie zwiększonego ryzyka**.

Więc kiedy osiągniemy punkt, w którym sztuczna inteligencja może robić wszystkie te rzeczy na poziomie nadludzkim?
Kiedy będziemy mieli _superinteligencję_?

## Prog Ilii {#the-ilya-threshold}

Uważam, że kluczowym punktem, który powinniśmy rozważyć, jest **punkt, w którym sztuczna inteligencja jest bardziej zdolna do prowadzenia badań nad sztuczną inteligencją niż ktoś taki jak Ilya Sutskever** (były główny naukowiec w OpenAI).
Sztuczna inteligencja, która może wnosić znaczący wkład w algorytmy i architektury sztucznej inteligencji, jest prawdopodobnie w stanie poprawiać się sama.
Zważmy ten punkt potencjalnej samopoprawy _progiem Ilii_.
Kiedy osiągnie ten próg, sztuczna inteligencja może poprawiać się sama, ponieważ została wyraźnie poinstruowana, aby to zrobić, lub dlatego, że bycie mądrzejszym jest użytecznym podcelem dla innych celów (sztuczne inteligencje [już tworzą własne podcele](https://github.com/Significant-Gravitas/Auto-GPT)).
Te iteracje mogą trwać tygodnie (szkolenie GPT-3 zajęło 34 dni), ale jest również możliwe, że jakiś rodzaj poprawy w czasie wykonywania zostanie zaimplementowany, który poczyni znaczne postępy w ciągu kilku minut: [Wybuch Inteligencji](https://www.youtube.com/watch?v=5qfIgCiYlfY).

Więc jak daleko jesteśmy od progu Ilii?
Zasadniczo trudno przewidzieć, [kiedy pojawiają się pewne możliwości](https://arxiv.org/abs/2206.07682), ponieważ modele językowe rozwijają się, ale do tej pory widzieliśmy wiele możliwości, które wcześniej uważano za odległe.
[Najnowsze modele sztucznej inteligencji](/sota) już biją większość ludzkich programistów, więc nie jest to nie do pomyślenia, że przyszłe modele, lepsze układy scalone, więcej danych i lepsze algorytmy wszystkie przyczynią się do osiągnięcia progu Ilii.
Nie mamy pojęcia, jak wyrównać taką sztuczną inteligencję (nawet [OpenAI przyznaje to](https://youtu.be/L_Guz73e6fw?t=1477)), a konsekwencje posiadania niewyrównanej superinteligencji będą prawdopodobnie [katastrofalne](/xrisk).

## Działaj {#act}

Nikt nie wie na pewno, kiedy osiągniemy próg Ilii.
Ale [stawką jest zbyt wysoka](/xrisk), aby przyjmować, że mamy dużo czasu.
Musimy działać na małą szansę, że możemy być oddaleni o kilka miesięcy.
Musimy [wstrzymać rozwój sztucznej inteligencji na granicy](/proposal) już teraz.
To od nas zależy, aby [podjąć działanie](/action) i upewnić się, że nie zostaniemy zaskoczeni.