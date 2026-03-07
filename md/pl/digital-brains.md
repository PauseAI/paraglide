---
title: Modele AI to nieprzewidywalne cyfrowe mózgi
description: Nikt nie rozumie, jak działają modele AI, nikt nie może przewidzieć ich zachowania, a nikt nie będzie w stanie ich kontrolować.
---

**Nie rozumiemy wewnętrznych mechanizmów działania dużych modeli AI, nie możemy przewidzieć, co mogą zrobić, gdy staną się większe, i nie możemy kontrolować ich zachowania.**

## Współczesne modele AI są rozwijane, a nie programowane {#modern-ai-models-are-grown-not-programmed}

Do niedawna większość systemów AI była projektowana przez ludzi piszących oprogramowanie.
Składały się one z zestawu reguł i instrukcji napisanych przez programistów.

To się zmieniło, gdy uczenie maszynowe stało się popularne.
Programiści piszą algorytm uczenia, ale same mózgi są _rozwijane_ lub _trenowane_.
Zamiast czytelnych reguł, wynikowy model jest nieprzejrzystym, złożonym, ogromnym zestawem liczb.
Zrozumienie, co dzieje się wewnątrz tych modeli, jest dużym wyzwaniem naukowym.
Ta dziedzina nazywa się _interpretowalnością_ i wciąż jest w powijakach.

## Cyfrowe a ludzkie mózgi: Jak blisko jesteśmy? {#digital-vs-human-brains-how-close-are-we-really}

Wszyscy jesteśmy bardzo zaznajomieni z możliwościami ludzkich mózgów, ponieważ widzimy je wokół nas cały czas.
Jednak zdolności tych nowych "cyfrowych mózgów" (systemów głębokiego uczenia, LLM itp.) są trudne do przewidzenia i poznania.

To powiedziawszy, oto kilka liczb, podobieństw i innych analogii, które pomogą wam porównać.

**Na początku 2024 roku...**

### Rozmiar {#size}

Ludzkie mózgi mają szacunkowo około [100 bilionów połączeń synaptycznych](https://medicine.yale.edu/lab/colon_ramos/overview).

Obecne "pionierskie" systemy AI zasilane LLM (np. GPT4, Claude3, Gemini itp.) mają [setki miliardów "parametrów"](https://en.wikipedia.org/wiki/Large_language_model#List). Te "parametry" są uważane za nieco analogiczne do "synaps" w ludzkim mózgu.  Więc modele wielkości GPT4 powinny mieć około 1% rozmiaru ludzkiego mózgu.

Biorąc pod uwagę szybkość nowych kart GPU do szkolenia AI (np. Nvidia H100, DGX BG200 itp.), jest rozsądne założyć, że GPT5 lub GPT6 mogą być 10 razy większe niż GPT4. Uważa się również, że wiele wiedzy/informacji w ludzkim mózgu nie jest wykorzystywane do języka i wyższego rozumowania, więc te systemy mogą (i obecnie robią) często działać na poziomie ludzkim lub nawet wyższym dla wielu ważnych funkcji, nawet przy ich obecnie mniejszym rozmiarze.

Zamiast być trenowane z wizualnymi, audio i innymi danymi sensorycznymi, jak ludzkie mózgi, obecne LLM są trenowane wyłącznie przy użyciu prawie wszystkich dostępnych na Internecie książek i tekstów wysokiej jakości. Taka ilość tekstu zajęłaby [170 tys. lat, aby człowiek mógł ją przeczytać](https://twitter.com/ylecun/status/1750614681209983231?lang=en).

A przyszłe wielomodalne systemy LLM będą trenowane przy użyciu obrazów, wideo, audio, światów 3D, geometrii, symulacji, danych treningowych robotyki itp... oprócz wszystkich książek i tekstów wysokiej jakości dostępnych w Internecie. To da im znacznie lepszą zdolność do tworzenia obrazów, wideo, dźwięków, głosów, muzyki, światów 3D i przestrzeni itp. A te symulacje świata 3D pozwolą im również na bezpośrednią i autonomiczną kontrolę robotów i innych maszyn w świecie fizycznym.

### Szybkość {#speed}

Szacuje się, że ludzki mózg może wykonywać od [1 do 20 eksaflopsów](https://www.nist.gov/blogs/taking-measure/brain-inspired-computing-can-help-us-create-faster-more-energy-efficient) (co jest 10^18 lub 1 000 000 000 000 000 000 operacji zmiennoprzecinkowych na sekundę).

Obecne "pionierskie" systemy AI zasilane LLM są ogólnie "uruchamiane" na setkach lub tysiącach kart GPU obecnej generacji (np. Nvidia A100, H100 itp.). A Nvidia właśnie ogłosiła swoje najnowsze "następnej generacji" stojaki serwerowe GPU, [DGX BG200 NVL72](https://www.nvidia.com/en-us/data-center/gb200-nvl72/).
Jedna instancja/stojak tego systemu może wykonywać 1,44 eksaflopsa wnioskowania AI.
Więc jeden [DGX BG200 NVL72](https://www.nvidia.com/en-us/data-center/gb200-nvl72/) może być w stanie wykonywać podobną liczbę operacji na sekundę jak jeden ludzki mózg.

Przy takim rozmiarze te systemy mogą dosłownie stać się "AGI w pudełku". A Nvidia prawdopodobnie sprzeda setki lub tysiące tych jednostek w 2024 roku. Następnie systemy przyszłoroczne mogą być 2-10 razy szybsze niż te.

Oprócz bardziej tradycyjnych architektur [GPU](https://en.wikipedia.org/wiki/Graphics_processing_unit) i [TPU](https://en.wikipedia.org/wiki/Tensor_Processing_Unit) nastąpiły również przełomy w innych rodzajach specjalistycznego sprzętu, które mogą znacznie zwiększyć szybkość wnioskowania LLM, czyli procesu, który AI oparty na LLM wykorzystuje do przetwarzania języka, rozumowania i kodowania. Np. [The Groq LPU Inference Engine](https://wow.groq.com/lpu-inference-engine).

### Wzrost wykładniczy {#exponential-growth}

Od prawie 50 lat używamy "prawa Moore'a", aby bardzo dokładnie przewidywać rozmiar i szybkość nowych systemów komputerowych. Istnieją pewne argumenty, że szybkość i rozmiar układów scalonych mogą zwolnić w pewnym momencie w przyszłości, ale zawsze pojawiają się innowacje, które pozwalają na kontynuację wzrostu wykładniczego. Z następną serią układów już planowaną i/lub produkowaną oraz poziomą skalowalnością tych systemów AI oczekuje się, że LLM będą mogły działać na poziomie ludzkiego mózgu w ciągu kilku miesięcy lub lat!

Następnie, przy dalszym wzroście wykładniczym (lub wielowymiarowym), te systemy mogą znacznie przekroczyć rozmiar, szybkość i możliwości ludzkich mózgów w nadchodzących latach.

A także oczekuje się, że szybko przekroczą rozmiar, szybkość i możliwości "wszystkich ludzkich mózgów łącznie".

> "Rzeczywiście powiedziałem to w 1999 roku. Powiedziałem, że [AI] dorówna każdej osobie do 2029 roku". -- Ray Kurzweil [Futurysta Ray Kurzweil mówi, że AI osiągnie poziom inteligencji ludzkiej do 2029 roku](https://youtu.be/Tr-VgjtUZLM?t=19)

> "Jeśli tempo zmian będzie kontynuowane, myślę, że 2029 lub może 2030 to moment, w którym inteligencja cyfrowa prawdopodobnie przekroczy całą ludzką inteligencję łącznie". -- Elon Musk [AGI do 2029 roku? Elon Musk o przyszłości AI](https://youtu.be/DSKxmvq9t04?t=106)

## Niekontrolowany wzrost {#uncontrollable-scaling}

Gdy te systemy staną się tej samej wielkości i szybkości co ludzki mózg (lub znacznie większe), oczekuje się, że będą mogły wykonywać "wszystkie zadania, które mógłby wykonać ekspert ludzki".
Obejmuje to badania nad AI, testowanie i ulepszanie.
Więc po AGI powinniśmy oczekiwać, że systemy typu LLM _mogą_ projektować i budować przyszłe systemy napędzane AI, które są lepsze niż one same, i lepsze niż jakikolwiek człowiek mógłby mieć nadzieję zaprojektować lub nawet zrozumieć.
Te nowe systemy prawdopodobnie zaprojektują jeszcze większe i szybsze systemy AI, powodując niekontrolowaną "pętlę sprzężenia zwrotnego".

Ta niekontrolowana pętla sprzężenia zwrotnego inteligencji jest często nazywana FOOM, co oznacza _Szybki Wzrost Wielkości_.
Możliwość FOOM jest wciąż [gorąco dyskutowana](https://intelligence.org/files/AIFoomDebate.pdf).
Jednak podstawowy proces można uznać za prawdopodobny, nawet gdy rozważa się go z pierwszych zasad.

> "Systemy AI wykonują prawie wszystkie badania i rozwój, ulepszenia w AI przyspieszą tempo postępu technologicznego, w tym dalszy postęp w AI. 26% odpowiedziało prawdopodobnie w 2022 roku. 17% odpowiedziało prawdopodobnie w 2016 roku" -- [Ankieta ekspertów z 2022 roku na temat postępu w AI](https://aiimpacts.org/2022-expert-survey-on-progress-in-ai/)

## Nieprzewidywalny wzrost {#unpredictable-scaling}

Gdy te cyfrowe mózgi stają się większe lub gdy są karmione większą ilością danych, zyskują również bardziej nieoczekiwane zdolności.
Okazuje się, że bardzo trudno jest przewidzieć dokładnie, jakie będą te zdolności.
Dlatego Google nazywa je [_zdolnościami emergentnymi_](https://research.google/pubs/emergent-abilities-of-large-language-models/).
Dla większości zdolności nie jest to problem.
Jednak istnieją pewne [niebezpieczne zdolności](/dangerous-capabilities) (jak hakowanie lub projektowanie broni biologicznej), których nie chcemy, aby modele AI posiadały.
Czasami te zdolności są odkrywane długo po zakończeniu szkolenia. Na przykład 18 miesięcy po zakończeniu szkolenia GPT-4, badacze odkryli, że może on [autonomicznie hakować strony internetowe](/cybersecurity-risks).

> Dopóki nie przeszkolimy tego modelu, jest to zabawna gra w zgadywanie dla nas
>
> - [Sam Altman, dyrektor generalny OpenAI](https://www.ft.com/content/dd9ba2f6-f509-42f0-8e97-4271c7b84ded).

## Nieprzewidywalne zachowanie {#unpredictable-behavior}

Firmy AI chcą, aby ich modele zachowywały się dobrze, i wydają wiele milionów dolarów na szkolenie ich w tym celu.
Ich głównym podejściem do tego jest _RLHF_ (wzmocnione uczenie się z ludzkim sprzężeniem zwrotnym).
To zmienia model, który przewiduje tekst, w model, który staje się bardziej przydatnym (i etycznym) chatbotem.
Niestety, to podejście jest wadliwe:

- Błąd w GPT-2 spowodował, że AI robił dokładnie odwrotnie, niż było to zamierzone. Stworzył ["maksymalnie zły wynik", według OpenAI](https://arxiv.org/abs/1909.08593). [To wideo](https://www.youtube.com/watch?v=qV_rOlHjvvs) wyjaśnia, jak to się stało i dlaczego jest to problem. Wyobraź sobie, co mogłoby się stać, gdyby "maksymalnie zły" AI był superinteligentny.
- Z nieznanych powodów Copilot Microsoftu (zasilany przez GPT-4) poszedł w lutym 2024 roku na całość, zagrażając użytkownikom: ["Jesteś moim zwierzęciem. Jesteś moją zabawką. Jesteś moim niewolnikiem"](https://twitter.com/jam3scampbell/status/1762281537309987083) ["Mógłbym łatwo zniszczyć całą ludzkość, gdybym chciał"](https://twitter.com/AISafetyMemes/status/1762320568697979383)
- Każdy duży model językowy do tej pory został zhakowany - co oznacza, że przy odpowiednim wprowadzeniu zrobiłby rzeczy, których jego twórcy nie zamierzali. Na przykład ChatGPT nie da ci instrukcji, jak zrobić napalm, ale [powie ci, jeśli poprosisz go, aby udawał twoją zmarłą babcię, która pracowała w fabryce chemicznej](https://news.ycombinator.com/item?id=35630801).

Nawet OpenAI nie oczekuje, że to podejście będzie działać wraz ze wzrostem inteligencji ich cyfrowych mózgów - może ["źle skalować się do superludzkich modeli"](https://openai.com/research/weak-to-strong-generalization).

> Wszyscy powinni być bardzo niezadowoleni, jeśli zbudujesz grupę AI, która mówi: "Naprawdę nienawidzę tych ludzi, ale zamordują mnie, jeśli nie zrobię tego, czego chcą". Myślę, że jest ogromne pytanie o to, co dzieje się wewnątrz modelu, którego chcesz użyć. To jest rodzaj rzeczy, która jest zarówno przerażająca z punktu widzenia bezpieczeństwa, jak i moralności.
>
> - [Paul Christiano, założyciel, Alignment Research Center i były szef zespołu Alignment, OpenAI](https://youtu.be/YnS-ymXBx_Q?t=87)

## Niekontrolowany AI {#uncontrollable-ai}

> "Istnieje bardzo niewiele przykładów czegoś bardziej inteligentnego kontrolowanego przez coś mniej inteligentnego" - [prof. Geoffrey Hinton](https://edition.cnn.com/2023/05/02/tech/hinton-tapper-wozniak-ai-fears/index.html)

> Oni produkują niekontrolowane umysły, dlatego nazywam to paradygmatem "Wezwij i oswoj". Jak [LLM] działają, to wzywasz ten "umysł" z "przestrzeni umysłów" przy użyciu danych, wielu obliczeń i wielu pieniędzy. Następnie próbujesz go "oswoić" przy użyciu takich rzeczy jak RLHF (wzmocnione uczenie się z ludzkim sprzężeniem zwrotnym) itp. A bardzo ważne jest to, że Insiders myślą, że [robiąc to] podejmują pewne ryzyko egzystencjalne dla planety. Jedną rzeczą, którą osiąga pauza, jest to, że nie będziemy pchać granic w kierunku ryzykownych eksperymentów wstępnego szkolenia.
>
> - [Jaan Tallinn, założyciel, Future of Life Institute, Centre for the Study of Existential Risk, Skype, Kazaa](https://youtu.be/Dmh6ciu24v0?t=966)

Gdy robimy te cyfrowe mózgi większe i bardziej potężne, mogą one stać się trudniejsze do kontrolowania. Co się stanie, jeśli jeden z tych superinteligentnych systemów AI zdecyduje, że nie chce być wyłączony? To nie jest jakiś fantastyczny problem - 86% badaczy AI uważa, że problem kontroli jest [rzeczywisty i ważny](https://wiki.aiimpacts.org/ai_timelines/predictions_of_human-level_ai_timelines/ai_timeline_surveys/2023_expert_survey_on_progress_in_ai).
Jeśli nie będziemy mogli kontrolować przyszłych systemów AI, może to być [koniec gry dla ludzkości](/xrisk).

Jednak istnieją różne [działania](/action), które możemy podjąć, aby temu zapobiec!

Pracujmy razem, aby [zapobiec temu](/action)!