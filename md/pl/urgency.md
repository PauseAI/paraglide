---
title: Dlaczego możemy mieć superinteligencję wcześniej niż większość ludzi myśli
description: Zaniżamy postęp AI, a istnieje niewielkie, ale realistyczne prawdopodobieństwo, że jesteśmy bardzo blisko superinteligencji.
date: '2023-05-04'
---

Obecne [najnowocześniejsze](/sota) modele AI są już ponadludzkie w wielu dziedzinach, ale na szczęście nie we wszystkich.
Jeśli osiągniemy superinteligencję, zanim rozwiążemy problem dostosowania, [stajemy przed ryzykiem wyginięcia](/xrisk).
Dlatego posiadanie oszacowanego zakresu czasu, kiedy możemy mieć superinteligencję, jest niezbędne, aby upewnić się, że nie zostaniemy zaskoczeni.
Jeśli nasze przewidywania są zbyt odległe, możemy nie być w stanie przygotować się na czas.

Ale jak daleko jesteśmy?
Kiedy będziemy mieli superinteligencję?
Może to nastąpić wcześniej niż większość ludzi myśli.

## Złożony wzrost wykładniczy {#compounding-exponential-growth}

Modele AI wymagają algorytmów, danych i układów scalonych.
Każdy z tych komponentów szybko się poprawia dzięki ogromnym inwestycjom w AI.
Poprawy w każdym z tych komponentów są _złożone_, prowadząc do wykładniczego wzrostu możliwości AI.

- **Więcej układów scalonych**. ChatGPT został opracowany na [10 000](https://www.fierceelectronics.com/sensors/chatgpt-runs-10k-nvidia-training-gpus-potential-thousands-more) specjalistycznych układów scalonych. Meta ogłosiła, że będzie miała 600 000 następnej generacji układów scalonych do trenowania swoich następnych modeli AI w tym roku.
- **Szybsze układy scalone**. Co roku układy scalone stają się szybsze dzięki nowym architekturom i innowacjom w dziedzinie litografii. Układy scalone, których używa Meta, są 10 razy szybsze niż te używane w ChatGPT. Widzimy również wyspecjalizowane sprzęty, takie jak układy Groq, które są [13 razy szybsze](https://mezha.media/en/2024/02/22/groq-s-new-ai-chip-offers-to-increase-chatgpt-speed-by-13-times/) niż konkurencja. W dłuższej perspektywie [architektury trójkowe](https://arxiv.org/pdf/2402.17764.pdf) lub [układy fotoniczne](https://www.nature.com/articles/s41566-024-01394-2) mogą sprawić, że układy scalone będą jeszcze szybsze.
- **Więcej danych**. GPT3 został opracowany na [45 TB](https://community.openai.com/t/what-is-the-size-of-the-training-set-for-gpt-3/360896) tekstu, GPT4 użył około 20 razy więcej. Firmy AI używają teraz również [ogromnych ilości danych wideo](https://www.404media.co/nvidia-ai-scraping-foundational-model-cosmos-project/), danych audio i nawet [generują syntetyczne dane do trenowania tych modeli](https://arxiv.org/pdf/2401.10020). Wcześniej pomysł użycia syntetycznych danych do trenowania był uważany za niemożliwy ze względu na upadek modelu, ale [najnowsze postępy](https://arxiv.org/abs/2406.07515) pokazują, że zapobieganie upadkowi modelu jest możliwe.
- **Lepsze dane**. Artykuł "Textbooks are all you need" [pokazał](https://arxiv.org/abs/2306.11644), że użycie wysokiej jakości syntetycznych danych może znacznie poprawić wydajność modelu, nawet jeśli użytych jest znacznie mniej danych i mocy obliczeniowej.
- **Lepsze algorytmy**. Architektura Transformer umożliwiła obecną rewolucję LLM. Nowe architektury mogą umożliwić podobne skoki możliwości. Model Mamba, na przykład, [pokazuje](https://arxiv.org/abs/2312.00752) 5-krotnie szybszy przepływ danych.
- **Lepsze środowiska uruchomieniowe**. Środowiska uruchomieniowe Agentic, Retrieval Augmented Generation lub nawet po prostu sprytne podpowiedzi (za pomocą [Graph of Thought](https://arxiv.org/abs/2305.16582), na przykład) mogą mieć ogromny wpływ na możliwości tych modeli.

Jest całkowicie możliwe, że _po prostu skalowanie_ doprowadzi nas do [niebezpiecznych możliwości](/dangerous-capabilities) w ciągu roku lub dwóch, ale ze wszystkimi tymi czynnikami złożonymi, może to nastąpić nawet wcześniej.

## Osiągnęliśmy poziom ludzki w wielu dziedzinach w 2023 roku {#we-reached-human-level-performance-in-many-domains-in-2023}

W 2022 roku badacze AI myśleli, że zajmie to [17 lat](https://aiimpacts.org/2022-expert-survey-on-progress-in-ai/), zanim AI będzie w stanie napisać bestseller New York Timesa.
Rok później chiński profesor [wygrał konkurs literacki](https://www.scmp.com/news/china/science/article/3245725/chinese-professor-used-ai-write-science-fiction-novel-then-it-won-national-award) z książką napisaną przez AI.

Na Metaculus, [przewidywanie społeczności dotyczące (słabego) AGI](https://www.metaculus.com/questions/3479/date-weakly-general-ai-is-publicly-known/) wynosiło 2057 tylko kilka lat temu, a teraz wynosi 2027.

Teraz, zanurzmy się w definicji AGI użytej w tym badaniu:

- Wynik >90% w teście Winograd Schema Challenge
- Wynik >75% w teście SAT
- Przejście testu Turinga
- Ukończenie gry Montezuma's Revenge

GPT-4 osiąga [94,4% w teście Winograd Schema Challenge](https://d-kz.medium.com/evaluating-gpt-3-and-gpt-4-on-the-winograd-schema-challenge-reasoning-test-e4de030d190d) i [93% w teście czytania SAT, 89% w teście matematyki SAT](https://www.cnbc.com/2023/03/14/openai-announces-gpt-4-says-beats-90percent-of-humans-on-sat.html).
Nie przeszedł testu Turinga, ale prawdopodobnie nie ze względu na brak możliwości.
To dlatego, że GPT-4 został dostosowany do nie wprowadzania ludzi w błąd. Nie jest dobrze dla biznesu, jeśli Twój AI mówi ludziom, że jest naprawdę osobą.
To pozostawia tylko Montezuma's Revenge.
Nie jest nie do pomyślenia, że może być ukończona przez sprytny zestaw GPT-4, używając czegoś takiego jak AutoGPT do analizy ekranu i generowania poprawnych danych wejściowych.
W maju 2023 roku [GPT-4 był w stanie napisać kod, aby uzyskać diamentowe wyposażenie w Minecraft](https://the-decoder.com/minecraft-bot-voyager-programs-itself-using-gpt-4/).
W skrócie: GPT-4 spełnił 2/4 kryteriów z pewnością, z pozostałymi dwoma w zasięgu.

**Jesteśmy tam, ludzie.
Już mamy (słabe) AGI.**
Nie zajęło nam to 35 lat, zajęło nam to trzy.
Byliśmy o czynnik 10 za daleko.

## Dlaczego większość zaniża postęp AI {#why-most-underestimate-the-progress-of-ai}

Istnieje wiele powodów, dla których ludzie zaniżają postęp AI.

- **Trudno jest nadążyć**. Prawie codziennie widzimy nowe przełomy w AI. Jest prawie niemożliwe, aby nadążyć za tempem postępu. Nie jesteś sam, jeśli czujesz, że zostajesz w tyle.
- **Przesuwamy słupki**. W latach 90. ludzie myśleli, że święty Graal AI to coś, co może grać w szachy. Kiedy AI pokonał Kasparowa, jego następnym wyzwaniem było Go. Teraz mamy maszyny, które osiągają [99,9 percentyl w testach IQ](https://bgr.com/tech/chatgpt-took-an-iq-test-and-its-score-was-sky-high/), mogą [tłumaczyć 26 języków](https://bgr.com/tech/chatgpt-took-an-iq-test-and-its-score-was-sky-high/) i [wygrywać konkursy fotograficzne](https://www.scientificamerican.com/article/how-my-ai-image-won-a-major-photography-competition/), a jednak wciąż zadajemy pytania takie jak "Kiedy AI osiągnie poziom ludzki?". Już przewyższa nas w wielu dziedzinach, ale zawsze skupiamy się na coraz mniejszej liczbie rzeczy, które jeszcze możemy robić lepiej.
- **Lubimy myśleć, że jesteśmy wyjątkowi**. Ludzie lubią czuć, że są wyjątkowi. Jeśli AI może robić to, co my, nie jesteśmy już wyjątkowi. To trudna pigułka do przełknięcia, a [mózg ma wiele mechanizmów obronnych, aby uniknąć tego](psychology-of-x-risk).
- **Jesteśmy naprawdę źli w wykładniczym wzroście**. Mamy tendencję do strukturalnego i przewidywalnego zaniżania, jak wykładniczy wzrost kumuluje się w czasie. To zostało pokazane w [badaniach naukowych](https://www.researchgate.net/figure/Underestimation-of-exponential-growth-a-shows-the-participants-prediction-of-the_fig4_351171143).

Na szczęście nadal są rzeczy, których AI jeszcze nie może zrobić.
Nie może [zhakować lepiej niż najlepsi hakerzy](/cybersecurity-risks), i nie może prowadzić badań nad AI tak dobrze jak najlepsi badacze AI.
**Kiedy osiągniemy któryś z tych progów, będziemy w nowym reżimie zwiększonego ryzyka**.

Więc kiedy osiągniemy punkt, w którym AI może robić wszystkie te rzeczy na poziomie ponadludzkim?
Kiedy będziemy mieli _superinteligencję_?

## Próg Ilya {#the-ilya-threshold}

Myślę, że kluczowym punktem, który powinniśmy rozważyć, jest **punkt, w którym AI jest bardziej zdolny do prowadzenia badań nad AI niż ktoś taki jak Ilya Sutskever** (były główny naukowiec w OpenAI).
AI, który może wnosić znaczący wkład w algorytmy i architektury AI, prawdopodobnie będzie w stanie ulepszyć się.
Nazwijmy ten punkt potencjalnej samopoprawy _próg Ilya_.
Kiedy osiągnie ten poziom, AI może się ulepszyć, ponieważ został wyraźnie poinstruowany, aby to zrobić, lub dlatego, że bycie mądrzejszym jest przydatnym podcelem dla innych celów (AI już [tworzą własne podcele](https://github.com/Significant-Gravitas/Auto-GPT)).
Te iteracje mogą zająć tygodnie (trenowanie GPT-3 zajęło 34 dni), ale jest również możliwe, że zostanie wdrożona jakaś forma ulepszenia środowiska uruchomieniowego, która sprawi, że znaczny postęp nastąpi w ciągu kilku minut: [eksplozja inteligencji](https://www.youtube.com/watch?v=5qfIgCiYlfY).

Więc jak daleko jesteśmy od progu Ilya?
Jest to fundamentalnie trudne do przewidzenia, [kiedy pewne możliwości pojawią się](https://arxiv.org/abs/2206.07682) wraz ze skalowaniem LLM, ale do tej pory widzieliśmy wiele możliwości, które wcześniej uważano za odległe.
[Najnowsze modele AI](/sota) już biją większość ludzkich programistów, więc nie jest nie do pomyślenia, że przyszłe modele, lepsze układy scalone, więcej danych i lepsze algorytmy wszystko przyczynią się do osiągnięcia progu Ilya.
Nie mamy pojęcia, jak dostosować taką AI (nawet [OpenAI przyznaje to](https://youtu.be/L_Guz73e6fw?t=1477)), a konsekwencje posiadania niedostosowanej superinteligencji są prawdopodobnie [katastrofalne](/xrisk).

## Działaj {#act}



Nikt nie wie na pewno, kiedy osiągniemy próg Ilya.
Ale [stawką jest zbyt wiele](/xrisk), aby zakładać, że mamy dużo czasu.
Musimy działać na małe prawdopodobieństwo, że możemy być miesiące od tego.
Musimy [wstrzymać rozwój AI](/proposal) już teraz.
To zależy od każdego z nas, aby [podjąć działanie](/action) i upewnić się, że nie zostaniemy zaskoczeni.