---
title: Jak oceny bezpieczeństwa AI i testy porównawcze mogą pomóc w zarządzaniu AI
description: Czym są oceny bezpieczeństwa AI i jak mogą przyczynić się do zapobieżenia katastrofalnym ryzykom?
---

## Czym są oceny bezpieczeństwa AI {#what-are-ai-safety-evaluations}

Oceny bezpieczeństwa, zwane również "ewaluacjami", to testy, które mierzą, jak zachowują się modele AI i jak stają się coraz potężniejsze.
W dziedzinie bezpieczeństwa AI, ewaluacje są często projektowane do pomiaru [niebezpiecznych zdolności](/dangerous-capabilities), takich jak zdolności związane z cyberbezpieczeństwem, samoreplikacja i autonomiczne badania AI.

Co ważne, ewaluacje mogą określić, czy AI jest zbyt niebezpieczna, aby ją wdrożyć.
Istnieją pewne _granice bezpieczeństwa_, których żaden model AI nie powinien przekroczyć, na przykład, gdy może...

- **samoreplikować się**. (Np. [RepliBench](https://arxiv.org/abs/2504.18565)). Samoreplikująca się AI mogłaby uciec z laboratorium i rozprzestrzenić się na inne maszyny.
- **tworzyć bardziej potężne modele AI**. Np. [RE-bench](https://metr.org/AI_R_D_Evaluation_Report.pdf). Samoudoskonalająca się AI mogłaby szybko stać się bardziej potężna niż ludzie.

## Zapobieżenie wdrożeniu nie wystarczy {#preventing-deployment-is-not-enough}

Rzeczy mogą pójść źle _nawet przed wdrożeniem_.
Samoreplikacja i samoudoskonalenie mogą nastąpić w laboratorium AI, zanim model zostanie udostępniony publicznie.

Dlatego **potrzebujemy mechanizmu awaryjnego**.
Musimy globalnie wstrzymać rozwój coraz potężniejszych modeli AI, zanim te niebezpieczne zdolności zostaną w pełni rozwinięte.
Ten mechanizm awaryjny powinien być aktywowany, gdy ewaluacje pokazują, że wkraczamy w strefę niebezpieczeństwa.

## Co robią firmy AI {#what-ai-companies-are-doing}

Większość firm AI z pierwszej linii przeprowadza oceny bezpieczeństwa swoich modeli przed ich wdrożeniem i uwzględnia wyniki tych ocen w tzw. "Kartach systemowych".
Większość z nich (z wyjątkiem Meta i Apple) podpisała [Unijny kodeks postępowania w dziedzinie AI](https://digital-strategy.ec.europa.eu/en/policies/contents-code-gpai), który wspomina o "najnowocześniejszych ocenach modeli" (Środek 3.2).

Oznacza to również, że niektóre z tych firm nie przeprowadzają _żadnych_ ocen bezpieczeństwa, a te, które są przeprowadzane, _nie są jeszcze wymagane_ i _nie są ustandaryzowane_.
Innymi słowy, **pilnie potrzebujemy przepisów, które wymagają ustandaryzowanych ocen bezpieczeństwa**.

## Co robią kraje {#what-countries-are-doing}

Wiele rządów poważnie inwestuje w oceny AI/testy porównawcze, aby zmierzyć niebezpieczne zdolności:

- UK AISI stworzył [ramę Inspect](https://github.com/UKGovernmentBEIS/inspect_ai), napisał [Replibench](https://arxiv.org/abs/2504.18565), obecnie inwestuje [15 mln GBP w oceny i granty na badania nad wyrównaniem](https://alignmentproject.aisi.gov.uk/)
- Komisja Europejska ogłasza [przetarg o wartości 10 mln EUR](https://ec.europa.eu/info/funding-tenders/opportunities/portal/screen/opportunities/tender-details/76f9edf2-d9e2-4db2-931e-a72c5ab356d2-CN) oraz [duży grant w ramach programu Horyzont](https://ec.europa.eu/info/funding-tenders/opportunities/portal/screen/opportunities/topic-details/HORIZON-CL4-2025-04-DIGITAL-EMERGING-04). Uruchomiła również [Ogólny kodeks postępowania w dziedzinie AI](https://digital-strategy.ec.europa.eu/en/policies/contents-code-gpai), który obejmuje wymóg przeprowadzania "najnowocześniejszych ocen modeli" (Środek 3.2).
- [Plan działania w dziedzinie AI w USA](https://www.whitehouse.gov/articles/2025/07/white-house-unveils-americas-ai-action-plan/) wspomina o ocenach i kontrolach sprzętowych
- Chiny (Concordia AI + Shanghai AI Lab) właśnie [opublikowały raport z wieloma ocenami](https://substack.com/home/post/p-169741512)
- Inne rządy również pracują nad ocenami

_Fakt, że tak wiele krajów pracuje nad ocenami, stwarza bardzo ważną okazję dla nas_.
Gdyby te kraje i instytucje **używały tych samych testów porównawczych** i miały pewne wspólne **granice bezpieczeństwa**, byłoby to ważne krokiem w kierunku globalnego traktatu.
Ponadto powinniśmy wyraźnie zakomunikować politykom, że gdy przekroczona zostanie granica bezpieczeństwa, nadszedł czas, aby [zatrzymać dalszy rozwój](/proposal).