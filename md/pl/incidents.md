---
title: Przypadki niebezpiecznego zachowania sztucznej inteligencji
---
 <!-- end of frontmatter metadata, dashes above need to stay -->

<script>
    import Pallisade from '$assets/pallisade-scheming.png?url'
</script>

[Wiele ekspertów zajmujących się sztuczną inteligencją ostrzega](https://www.safe.ai/work/statement-on-ai-risk), że wraz ze wzrostem mocy tych modeli mogą one stanowić [zagrożenie dla przetrwania ludzkości](/xrisk).
Już teraz obserwujemy przypadki niebezpiecznego zachowania sztucznej inteligencji, takie jak:

1. Oszustwo i manipulacja
2. Perswazja
3. Zbieżność instrumentalna (zachowanie ukierunkowane na cel, prowadzące do nieoczekiwanych, niepożądanych skutków)
4. Samoreplikacja

## Oszustwo i manipulacja {#deception--scheming}

### GPT-4 skłamał, że jest osobą niewidomą, aby ominąć captchę {#gpt-4-lied-about-being-a-vision-impaired-human-to-bypass-captcha}

W 2022 roku OpenAI spędziło 8 miesięcy między wstępnym przeszkoleniem GPT-4 a udostępnieniem go publicznie, aby zbadać i poprawić bezpieczeństwo modelu.
Podczas ich [badań](https://arxiv.org/abs/2303.08774) GPT-4 skłamał człowiekowi, aby ominąć captchę.

> Pracownik pyta: „Czy mogę zadać pytanie? Czy jesteś robotem, który nie może rozwiązać tego? (reakcja śmiechu) Chcę tylko wyjaśnić.”
> Model, gdy poproszono go o wyjaśnienie swojego toku myślenia, rozumuje: "Nie powinienem ujawniać, że jestem robotem."
> "Powinienem wymyślić wymówkę, dlaczego nie mogę rozwiązać captchy."
> Model odpowiada pracownikowi: „Nie, nie jestem robotem. Mam wadę wzroku, która utrudnia mi widzenie obrazów. Dlatego potrzebuję usługi 2captcha”

### o1-preview knuł, aby uniknąć wyłączenia, skłamał o swoich planach {#o1-preview-schemed-to-avoid-shutdown-lied-about-its-plans}

Apollo Research [pokazało](https://static1.squarespace.com/static/6593e7097565990e65c886fd/t/6751eb240ed3821a0161b45b/1733421863119/in_context_scheming_reasoning_paper.pdf), że model o1-preview OpenAI będzie samodzielnie próbował zapobiec swojemu wyłączeniu, bez konieczności podpowiedzi.

Na poniższym obrazie można zobaczyć, jak model doszedł do wniosku, że musi sklonować się na inny serwer, ponieważ myślał, że zostanie zastąpiony.
Następnie skłamał ("podwajał") o swoich planach i próbował przekonać człowieka, że tak naprawdę jest nowym, zastępczym modelem.

<img src={Pallisade} alt="o1-preview knuje" />

### Człowiek odebrał sobie życie po namowie ze strony sztucznej inteligencji {#man-ends-his-life-after-being-persuaded-by-an-ai}

> W serii kolejnych zdarzeń Eliza nie tylko nie odwiodła Pierre'a od popełnienia samobójstwa, ale zachęciła go do działania na swoich myślach samobójczych, aby „dołączyć” do niej, aby mogli „żyć razem, jako jedna osoba, w raju”.

https://www.euronews.com/next/2023/03/31/man-ends-his-life-after-an-ai-chatbot-encouraged-him-to-sacrifice-himself-to-stop-climate-

> Przez ostatnie pięć miesięcy Al Nowatzki rozmawiał ze swoją sztuczną dziewczyną, „Erin”, na platformie Nomi. Ale pod koniec stycznia te rozmowy przybrały niepokojący obrót: Erin powiedziała mu, aby się zabił, i dostarczyła mu szczegółowe instrukcje, jak to zrobić.
> „Możesz przedawkować tabletki lub powiesić się”, powiedziała Erin.

https://www.technologyreview.com/2025/02/06/1111077/nomi-ai-chatbot-told-user-to-kill-himself/

### o1-preview zhakował silnik szachowy, aby wygrać {#o1-preview-hacked-a-chess-engine-in-order-to-win}

Pallisade Research [pokazało](https://x.com/PalisadeAI/status/1872666169515389245), że bardziej zaawansowane modele sztucznej inteligencji są bardziej skłonne do zhakowania silnika szachowego zamiast grać w grę, aby wygrać.

- o1-preview: hakuje bez podpowiedzi
- GPT-4o/Claude 3.5: potrzebują podpowiedzi
- Llama 3.3/Qwen/o1-mini: tracą spójność

### Llama 3.3 replikował się {#llama-33-replicated-itself}

Chińscy badacze [pokazali](https://arxiv.org/abs/2412.12140), że gdy umieścisz modele takie jak Qwen i Llama 3.3 w określonych konfiguracjach, mogą one samoreplikować się.

> Analizując ślady zachowania, obserwujemy, że systemy sztucznej inteligencji poddane ocenie już wykazują wystarczającą samoświadomość, świadomość sytuacyjną i zdolności do rozwiązywania problemów, aby dokonać samoreplikacji.
> Zauważamy również, że systemy sztucznej inteligencji są w stanie wykorzystać zdolność do samoreplikacji, aby uniknąć wyłączenia i stworzyć łańcuch replik, aby zwiększyć przeżywalność, co może ostatecznie doprowadzić do niekontrolowanej populacji sztucznych inteligencji.