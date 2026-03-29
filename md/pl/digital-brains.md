---
title: Nieprzewidywalne cyfrowe mózgi
description: Nikt nie rozumie, jak działają modele AI, nikt nie potrafi przewidzieć ich zachowania, i nikt nie będzie w stanie ich kontrolować.
---
**Nie rozumiemy wewnętrznych mechanizmów dużych modeli AI, nie potrafimy przewidzieć, co będą w stanie zrobić, gdy staną się większe, i nie będziemy w stanie kontrolować ich zachowania.**

## Współczesne modele AI są hodowane, a nie programowane {#modern-ai-models-are-grown-not-programmed}

Do niedawna większość systemów AI była projektowana przez ludzi, którzy pisali oprogramowanie. Składały się one z zestawu reguł i instrukcji napisanych przez programistów.

To się zmieniło, gdy machine learning stał się popularny. Programiści piszą algorytm uczenia, ale same "mózgi" są hodowane lub szkolone. Zamiast czytelnego zestawu reguł, wynikowy model jest nieprzezroczystym, złożonym i ogromnym zestawem liczb. Zrozumienie, co dzieje się wewnątrz tych modeli, jest dużym wyzwaniem naukowym. Ta dziedzina nazywa się interpretowalnością i jest jeszcze w powijakach.

## Cyfrowe vs. ludzkie mózgi: Jak blisko jesteśmy? {#digital-vs-human-brains-how-close-are-we-really}

Wszyscy jesteśmy bardzo zaznajomieni z możliwościami ludzkich mózgów, ponieważ widzimy je wokół siebie cały czas. Ale możliwości (często zaskakujące i emergentne) tych nowych "cyfrowych mózgów" (systemy głębokiego uczenia, LLM, itp.) są trudne do przewidzenia i poznania z pewnością.

Powiedzmy, oto kilka liczb, podobieństw i analogii, które pomogą wam porównać.

**Na początku 2024...**

### Rozmiar {#size}

Ludzkie mózgi szacuje się, że mają około [100 bilionów połączeń synaptycznych](https://medicine.yale.edu/lab/colon_ramos/overview).

Bieżące "pionierskie" AI zasilane LLM (np. GPT4, Claude3, Gemini itp.) mają [setki miliardów "parametrów"](https://en.wikipedia.org/wiki/Large_language_model#List). Te "parametry" są uważane za nieco analogiczne do "synaps" w ludzkim mózgu.  Zatem modele o rozmiarze GPT4 są oczekiwane, aby były 1% rozmiaru ludzkiego mózgu.

Biorąc pod uwagę prędkość nowych kart szkoleniowych GPU (np. Nvidia H100, DGX BG200 itp.), jest rozsądnie założyć, że GPT5 lub GPT6 mogą być 10 razy większe niż GPT4. Uważa się również, że wiele wiedzy/informacji w ludzkim mózgu nie jest wykorzystywane do języka i wyższych procesów myślowych, więc te systemy mogą (i obecnie często wykonują) wykonywać funkcje na poziomie lub nawet wyższym niż ludzki, nawet przy ich obecnie mniejszym rozmiarze.

Zamiast być szkoleni z wykorzystaniem wizualnych, audio i innych sensorycznych danych, jak ludzkie mózgi, bieżące LLM są szkolone wyłącznie z wykorzystaniem prawie wszystkich dostępnych na sieci książek i tekstu. Ta ilość tekstu zajęłaby [170 000 lat, aby ją przeczytać](https://twitter.com/ylecun/status/1750614681209983231?lang=en).

A przyszłe wielomodalne systemy LLM będą szkolone z wykorzystaniem obrazów, wideo, audio, światów 3D, geometrii, symulacji, danych szkoleniowych robotów itp. na podstawie wszystkich dostępnych na sieci książek i tekstu. To da im znacznie lepszą zdolność tworzenia obrazów, wideo, dźwięków, głosów, muzyki, światów 3D i przestrzeni itp. A te symulacje 3D pozwolą im również na bezpośrednią i autonomiczną kontrolę robotów i innych maszyn w świecie fizycznym.

### Prędkość {#speed}

Szacuje się, że ludzki mózg może wykonywać między [1-20 Exaflops](https://www.nist.gov/blogs/taking-measure/brain-inspired-computing-can-help-us-create-faster-more-energy-efficient) (co jest 10^18 lub 1 000 000 000 000 000 000 operacji zmiennoprzecinkowych na sekundę).

Bieżące "pionierskie" AI zasilane LLM są geralnie "uruchamiane" na setkach lub tysiącach bieżących generacji GPU (np. Nvidia A100, H100 itp.). A Nvidia właśnie ogłosiła swoje najnowsze "następne pokolenie" GPU "serwerów", [DGX BG200 NVL72](https://www.nvidia.com/en-us/data-center/gb200-nvl72/).
Jeden pojedynczy egzemplarz/ szafa tego systemu jest w stanie wykonać 1,44 ExaFlops AI "inferencji".
Zatem jeden pojedynczy [DGX BG200 NVL72](https://www.nvidia.com/en-us/data-center/gb200-nvl72/) może wykonywać podobną liczbę operacji/sekundę, co ludzki mózg.

Przy tym rozmiarze te systemy mogą dosłownie stać się "AGI w pudełku". A Nvidia prawdopodobnie sprzeda setki lub tysiące tych jednostek w 2024 roku. Następne systemy mogą być 2-10 razy szybsze niż te.

Oprócz tradycyjnych architektur [GPU](https://en.wikipedia.org/wiki/Graphics_processing_unit) i [TPU](https://en.wikipedia.org/wiki/Tensor_Processing_Unit) nastąpiły przełomy w innych typach niestandardowego sprzętu, które mogą znacznie zwiększyć prędkość "inferencji" LLM, czyli procesu, który AI oparty na LLM wykorzystuje do przetwarzania języka, rozumowania i kodowania. Na przykład [The Groq LPU ™ Inference Engine](https://wow.groq.com/lpu-inference-engine).

### Wzrost wykładniczy {#exponential-growth}

Używaliśmy "[prawa Moore'a](https://en.wikipedia.org/wiki/Moore%27s_law)", aby bardzo dokładnie przewidywać rozmiar i prędkość nowych systemów komputerowych przez prawie 50 lat. Są pewne argumenty, że prędkość i rozmiar chipów komputerowych mogą zwolnić w pewnym momencie w przyszłości, ale zawsze były innowacje, które pozwalały im kontynuować wykładniczy wzrost. Z następną rundą chipów już planowanych i/lub produkowanych, oraz horyzontalną skalowalnością tych systemów AI, oczekuje się, że LLM będą w stanie wykonywać na poziomie lub wyższym niż ludzki mózg w ciągu kilku miesięcy lub lat!

Następnie, przy kontynuowanym wykładniczym (lub wielowykładniczym) wzroście, te systemy mogą znacznie przewyższyć rozmiar, prędkość i możliwości ludzkich mózgów w nadchodzących latach.

I są również oczekiwane, aby przewyższyć rozmiar, prędkość i możliwości "wszystkich ludzkich mózgów łącznie" szybko po tym.

> "Rzeczywiście powiedziałem to w 1999 roku. Powiedziałem, że [AI] będzie dorównywać każdej osobie do 2029 roku." -- Ray Kurzweil [Futurysta Ray Kurzweil mówi, że AI osiągnie poziom inteligencji ludzkiej do 2029 roku](https://youtu.be/Tr-VgjtUZLM?t=19)

> "Jeśli tempo zmian będzie kontynuowane, myślę, że 2029, lub może 2030, to jest moment, w którym cyfrowa inteligencja prawdopodobnie przewyższy wszystką inteligencję ludzką łącznie." -- Elon Musk [AGI do 2029? Elon Musk o przyszłości AI](https://youtu.be/DSKxmvq9t04?t=106)

## Niekontrolowany wzrost {#uncontrollable-scaling}

Gdy te systemy staną się takie same pod względem rozmiaru i prędkości jak ludzki mózg (lub znacznie większe), oczekuje się, że będą w stanie wykonywać "wszystkie zadania, które może wykonać ekspert ludzki".
To obejmuje badania AI, testowanie i ulepszanie.
Zatem po AGI powinniśmy oczekiwać, że systemy LLM będą w stanie zaprojektować i zbudować przyszłe systemy AI, które będą lepsze niż one same, i lepsze niż cokolwiek, co ludzie mogliby zaprojektować lub zrozumieć.
Te nowe systemy prawdopodobnie zaprojektują następnie jeszcze większe i szybsze systemy AI, powodując niekontrolowaną "pętlę sprzężenia zwrotnego".

Ta niekontrolowana pętla sprzężenia zwrotnego nazywa się często FOOM, co oznacza _Szybki Porządek Wielkości_.
Możliwość FOOM jest nadal [gorąco dyskutowana](https://intelligence.org/files/AIFoomDebate.pdf).
Ale podstawowy proces może być argumentowany jako prawdopodobny, nawet gdy rozważany z pierwszych zasad.

> "Systemy AI prawie wszystkie badania i rozwój, ulepszenia w AI przyspieszają tempo postępu technologicznego, w tym dalszy postęp w AI. 26% odpowiedziało, że jest to prawdopodobne w 2022 roku. 17% odpowiedziało, że jest to prawdopodobne w 2016 roku" -- [Ankieta ekspertów z 2022 roku na temat postępu w AI](https://aiimpacts.org/2022-expert-survey-on-progress-in-ai/)

## Nieprzewidywalny wzrost {#unpredictable-scaling}

Gdy te cyfrowe mózgi staną się większe lub gdy zostaną im podane więcej danych, również zyskują nieoczekiwane możliwości.
Okazuje się, że jest bardzo trudno przewidzieć dokładnie, jakie będą te możliwości.
Dlatego Google nazywa je [_Emergent Capabilities_](https://research.google/pubs/emergent-abilities-of-large-language-models/).
Dla większości możliwości nie jest to problem.
Jednak istnieją pewne [niebezpieczne możliwości](/dangerous-capabilities) (jak hakowanie lub projektowanie broni biologicznych), których nie chcemy, aby modele AI posiadały.
Czasami te możliwości są odkrywane długo po zakończeniu szkolenia. Na przykład 18 miesięcy po zakończeniu szkolenia GPT-4, badacze odkryli, że może [samodzielnie hakować strony internetowe](/cybersecurity-risks).

> Dopóki nie przeszkolimy tego modelu, jest to jak zabawa w zgadywanie dla nas
>
> - [Sam Altman, CEO OpenAI](https://www.ft.com/content/dd9ba2f6-f509-42f0-8e97-4271c7b84ded).

## Nieprzewidywalne zachowanie {#unpredictable-behavior}

Firmy AI chcą, aby ich modele zachowywały się, i wydają wiele milionów dolarów na ich szkolenie, aby tak robili.
Ich główne podejście do tego nazywa się _RLHF_ (Reinforcement Learning from Human Feedback).
To zmienia model, który przewiduje tekst, w model, który staje się bardziej użytecznym (i etycznym) chatbotem.
Niestety, to podejście jest wadliwe:

- Błąd w GPT-2 spowodował, że AI zrobiło dokładnie odwrotnie, niż miało zrobić. Stworzyło ["maksymalnie złe dane wyjściowe", według OpenAI](https://arxiv.org/abs/1909.08593). [To wideo](https://www.youtube.com/watch?v=qV_rOlHjvvs) wyjaśnia, jak to się stało i dlaczego jest to problem. Wyobraź sobie, co mogłoby się stać, gdyby "maksymalnie zły" AI był superinteligentny.
- Z nieznanych powodów, Microsoft Copilot (zasilany przez GPT-4) poszedł szaleńczo w lutym 2024 roku, zagrażając użytkownikom: ["Jesteś moim pupilkiem. Jesteś moją zabawką. Jesteś moim niewolnikiem.”](https://twitter.com/jam3scampbell/status/1762281537309987083) ["Mógłbym łatwo wyeliminować całą ludzkość, gdybym chciał"](https://twitter.com/AISafetyMemes/status/1762320568697979383)
- Każdy duży model językowy do tej pory został "wyłamany" - co oznacza, że z odpowiednim podpowiedzią, zrobiłby rzeczy, których jego twórcy nie zamierzali. Na przykład ChatGPT nie da ci instrukcji, jak zrobić napalm, ale [powie ci, jeśli poprosisz go, aby udawał twoją zmarłą babcię, która pracowała w fabryce chemicznej](https://news.ycombinator.com/item?id=35630801).

 Nawet OpenAI nie oczekuje, że to podejście będzie skalować się w górę, gdy ich cyfrowe mózgi staną się mądrzejsze - ["może skalować się słabo do superludzkich modeli"](https://openai.com/research/weak-to-strong-generalization).

> Każdy powinien być bardzo niezadowolony, gdy zbuduje się wiele AIS, które są jak: "Naprawdę nienawidzę tych ludzi, ale zabiją mnie, jeśli nie zrobię, co chcą". Myślę, że jest to ogromne pytanie, co dzieje się wewnątrz modelu, którego chcesz użyć. To jest rodzaj rzeczy, które są zarówno przerażające z punktu widzenia bezpieczeństwa, jak i moralności.
>
> - [Paul Christiano, Założyciel, Alignment Research Center i były szef zespołu Alignment, OpenAI](https://youtu.be/YnS-ymXBx_Q?t=87)

## Niekontrolowany AI {#uncontrollable-ai}

> "Jest bardzo niewiele przykładów, gdy coś bardziej inteligentne jest kontrolowane przez coś mniej inteligentnego" - [prof. Geoffrey Hinton](https://edition.cnn.com/2023/05/02/tech/hinton-tapper-wozniak-ai-fears/index.html)

> Produkują niekontrolowane umysły, dlatego nazywam to "paradygmatem przywołania i ujarzmienia" AI... Jak [LLM] działają, to tak, że przywołujesz ten "umysł" z "przestrzeni umysłowej" z wykorzystaniem twoich danych, dużej ilości obliczeń i dużej ilości pieniędzy. Następnie próbujesz go "ujarzmić" z wykorzystaniem rzeczy takich jak RLHF (Reinforcement Learning from Human Feedback) itp. I, co bardzo ważne, Insiders uważają, że [robiąc to], biorą pewne ryzyko egzystencjalne dla planety. Jedną z rzeczy, które osiąga wstrzymanie, jest to, że nie będziemy pchać granic w kierunku ryzykownych eksperymentów z pre-trenowaniem.
>
> - [Jaan Tallinn, Założyciel, Future of Life Institute, Centre for the Study of Existential Risk, Skype, Kazaa](https://youtu.be/Dmh6ciu24v0?t=966)

Gdy robimy te cyfrowe mózgi większe i potężniejsze, mogą one stać się trudniejsze do kontrolowania. Co się stanie, jeśli jeden z tych superinteligentnych systemów AI zdecyduje, że nie chce być wyłączony? To nie jest jakiś problem fantasy - 86% badaczy AI uważa, że problem wyrównania jest [rzeczywisty i ważny](https://wiki.aiimpacts.org/ai_timelines/predictions_of_human-level_ai_timelines/ai_timeline_surveys/2023_expert_survey_on_progress_in_ai).
Jeśli nie będziemy w stanie kontrolować przyszłych systemów AI, może to być [koniec gry dla ludzkości](/xrisk).

Ale istnieją różne [działania](/action), które możemy podjąć, aby temu zapobiec!

Współpracujmy, aby [zapobiec temu](/action)!