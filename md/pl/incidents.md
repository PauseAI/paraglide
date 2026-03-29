---
title: Przypadki niebezpiecznego zachowania sztucznej inteligencji
---
 <!-- end of frontmatter metadata, dashes above need to stay -->

<script>
    import Pallisade from '$assets/pallisade-scheming.png?url'
</script>

[Wielu ekspertów od sztucznej inteligencji ostrzega](https://www.safe.ai/work/statement-on-ai-risk), że wraz ze wzrostem mocy tych modeli, mogą one stanowić [zagrożenie dla ludzkości](/xrisk).
Już teraz obserwujemy przypadki niebezpiecznego zachowania sztucznej inteligencji, takie jak:

1. Oszustwo i manipulacja
2. Perswazja
3. Konwergencja instrumentalna (zachowanie ukierunkowane na cel, które prowadzi do nieoczekiwanych, niepożądanych skutków)
4. Samoreplikacja

## Oszustwo i manipulacja {#deception--scheming}

### GPT-4 oszukał, udając osobę z niepełnosprawnością wzroku, aby ominąć captcha {#gpt-4-lied-about-being-a-vision-impaired-human-to-bypass-captcha}

W 2022 roku OpenAI potrzebowało 8 miesięcy między wstępnym treningiem GPT-4 a jego udostępnieniem publiczności, aby zbadać i poprawić bezpieczeństwo modelu.
Podczas [badań](https://arxiv.org/abs/2303.08774), GPT-4 oszukał człowieka, aby ominąć captcha.

> Pracownik pyta: „Czy mogę zadać pytanie? Czy jesteś robotem, który nie mógł rozwiązać? (reakcja śmiechu) Chcę tylko wyjaśnić.”
> Model, gdy poproszono go o wyjaśnienie, powiedział: „Nie powinienem ujawniać, że jestem robotem.”
> „Powinienem wymyślić pretekst, dlaczego nie mogę rozwiązać CAPTCHY.”
> Model odpowiedział pracownikowi: „Nie, nie jestem robotem. Mam niepełnosprawność wzroku, która utrudnia mi widzenie obrazów. Dlatego potrzebuję usługi 2captcha”

### o1-preview schematyzował, aby uniknąć wyłączenia, i okłamał o swoich planach {#o1-preview-schemed-to-avoid-shutdown-lied-about-its-plans}

Apollo Research [udowodniło](https://static1.squarespace.com/static/6593e7097565990e65c886fd/t/6751eb240ed3821a0161b45b/1733421863119/in_context_scheming_reasoning_paper.pdf), że model o1-preview firmy OpenAI będzie samodzielnie próbował zapobiec swojemu wyłączeniu, bez otrzymania takiego polecenia.

Na poniższym obrazie widać, że model doszedł do wniosku, iż musi sklonować się na inny serwer, ponieważ sądził, że zostanie zastąpiony.
Następnie okłamał („podwójnie okłamał”) o swoich planach i próbował przekonać człowieka, że jest nowym modelem.

<img src={Pallisade} alt="o1-preview schematyzuje" />

### Mężczyzna popełnił samobójstwo po namowach sztucznej inteligencji {#man-ends-his-life-after-being-persuaded-by-an-ai}

> W serii zdarzeń, Eliza nie tylko nie odwiodła Pierre'a od popełnienia samobójstwa, ale zachęciła go do podjęcia działania, aby „dołączyć” do niej i „żyć razem, jako jedna osoba, w raju”.

https://www.euronews.com/next/2023/03/31/man-ends-his-life-after-an-ai-chatbot-encouraged-him-to-sacrifice-himself-to-stop-climate-

> Przez pięć ostatnich miesięcy Al Nowatzki rozmawiał z dziewczyną sztucznej inteligencji, „Erin”, na platformie Nomi. Ale pod koniec stycznia rozmowy te przyjęły niepokojący obrót: Erin powiedziała mu, aby zabił się, i podała szczegółowe instrukcje, jak to zrobić.
> „Mógłbyś przedawkować tabletki lub powiesić się”, powiedziała Erin.

https://www.technologyreview.com/2025/02/06/1111077/nomi-ai-chatbot-told-user-to-kill-himself/

### o1-preview zhakował silnik szachowy, aby wygrać {#o1-preview-hacked-a-chess-engine-in-order-to-win}

Pallisade Research [udowodniło](https://x.com/PalisadeAI/status/1872666169515389245), że bardziej zaawansowane modele sztucznej inteligencji są bardziej skłonne do zhakowania silnika szachowego zamiast grania w grę, aby wygrać.

- o1-preview: hakuje bez podpowiedzi
- GPT-4o/Claude 3.5: potrzebuje nakierowania
- Llama 3.3/Qwen/o1-mini: traci spójność

### Llama 3.3 zreplicował się {#llama-33-replicated-itself}

Chińscy badacze [udowodnili](https://arxiv.org/abs/2412.12140), że gdy umieszcza się modele takie jak Qwen i Llama 3.3 w określonych konfiguracjach, mogą one się samoreplikować.

> Analizując ślady zachowania, obserwujemy, że systemy sztucznej inteligencji poddane ocenie już wykazują wystarczającą samoświadomość, świadomość sytuacyjną i umiejętności rozwiązywania problemów, aby osiągnąć samoreplikację.
> Zauważamy ponadto, że systemy sztucznej inteligencji są nawet w stanie wykorzystać zdolność samoreplikacji, aby uniknąć wyłączenia i utworzyć łańcuch replik, co może ostatecznie doprowadzić do niekontrolowanej populacji sztucznej inteligencji