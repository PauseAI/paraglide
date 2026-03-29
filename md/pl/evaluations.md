---
title: Jak oceny i punkty odniesienia bezpieczeństwa AI mogą przyczynić się do skutecznego zarządzania AI
description: Czym są oceny bezpieczeństwa AI i jak mogą one pomóc w zapobieganiu katastrofalnym ryzykom?
---
## Co to są oceny bezpieczeństwa AI {#what-are-ai-safety-evaluations}

"Ewaluacje" to testy, które mierzą zachowania modeli AI i ich rosnącą potęgę. 
W dziedzinie bezpieczeństwa AI, ewaluacje są często projektowane w celu pomiaru [niebezpiecznych możliwości](/dangerous-capabilities), takich jak zdolności cyberbezpieczeństwa, samoreplikacji i prowadzenia autonomicznych badań AI.

Co ważne, ewaluacje mogą pomóc określić, czy AI jest zbyt niebezpieczna do wdrożenia. 
Istnieją pewne _granice bezpieczeństwa_, których żaden model AI nie powinien przekroczyć, na przykład gdy może...

- **sam się replikować**. (Na przykład [RepliBench](https://arxiv.org/abs/2504.18565)). Samoreplikujący się AI mógłby uciec spod kontroli i rozprzestrzenić się na inne maszyny.
- **tworzyć potężniejsze modele AI**. Na przykład [RE-bench](https://metr.org/AI_R_D_Evaluation_Report.pdf). Samodoskonalący się AI mógłby szybko stać się potężniejszy niż ludzie.

## Zapobieganie wdrożeniu to nie wszystko {#preventing-deployment-is-not-enough}

Ryzyko wystąpienia niepożądanych zdarzeń istnieje _nawet przed wdrożeniem_.
Samoreplikacja i samodoskonalenie mogą nastąpić w laboratorium AI, zanim model będzie dostępny publicznie.

Dlatego **potrzebujemy [Przycisku Pauzy](/building-the-pause-button)**.
Potrzebujemy globalnie zatrzymać rozwój coraz potężniejszych modeli AI, zanim te niebezpieczne możliwości będą w pełni rozwinięte.
Przycisk Pauzy powinien być wciśnięty, gdy ewaluacje wskażą, że zbliżamy się do _granicy bezpieczeństwa_.

## Co robią firmy AI {#what-ai-companies-are-doing}

Większość firm AI z pierwszej linii prowadzi ewaluacje bezpieczeństwa swoich modeli przed ich wdrożeniem i uwzględnia wyniki tych ewaluacji w tzw. "Kartach Systemowych".
Większość z nich (poza Meta i Apple) podpisała [Kodeks Dobrej Praktyki AI UE](https://digital-strategy.ec.europa.eu/en/policies/contents-code-gpai), który wymienia "ewaluacje modeli na poziomie stanu techniki" (Punkt 3.2).

To oznacza również, że niektóre z tych firm nie prowadzą _żadnych_ ewaluacji bezpieczeństwa, a te, które są prowadzone, _nie są jeszcze obligatoryjne_ i _nie są standaryzowane_.
Innymi słowy, **pilnie potrzebujemy regulacji, które wymagają standaryzowanych ewaluacji bezpieczeństwa**.

## Co robią kraje {#what-countries-are-doing}

Kilka rządów inwestuje teraz poważnie w ewaluacje/benchmarks AI, aby zmierzyć niebezpieczne możliwości:

- UK AISI zbudował [ramę Inspect](https://github.com/UKGovernmentBEIS/inspect_ai), napisał [Replibench](https://arxiv.org/abs/2504.18565), inwestuje teraz [15M GBP w granty na badania ewaluacji i wyrównania](https://alignmentproject.aisi.gov.uk/)
- Komisja Europejska uruchamia [przetarg na 10M EUR](https://ec.europa.eu/info/funding-tenders/opportunities/portal/screen/opportunities/tender-details/76f9edf2-d9e2-4db2-931e-a72c5ab356d2-CN), oraz [duży grant w ramach programu Horizon](https://ec.europa.eu/info/funding-tenders/opportunities/portal/screen/opportunities/topic-details/HORIZON-CL4-2025-04-DIGITAL-EMERGING-04). Uruchomiła również [Kodeks Dobrej Praktyki Ogólnego Przeznaczenia AI](https://digital-strategy.ec.europa.eu/en/policies/contents-code-gpai), który zawiera wymóg przeprowadzania "ewaluacji modeli na poziomie stanu techniki" (Punkt 3.2).
- [Plan Działania AI USA](https://www.whitehouse.gov/articles/2025/07/white-house-unveils-americas-ai-action-plan/) wymienia ewaluacje i kontrolę sprzętu
- Chiny (concordia AI + Shanghai AI lab) właśnie [opublikowały raport z wieloma ewaluacjami](https://substack.com/home/post/p-169741512)
- Inne rządy pracują również nad ewaluacjami

_Fakt, że tak wiele krajów pracuje nad ewaluacjami, stwarza bardzo ważną okazję dla nas_.
Jeśli te kraje i instytucje **będą używać tych samych benchmarków** i będą miały pewne wspólne _granice bezpieczeństwa_, to będzie to ważny krok w kierunku globalnego traktatu.
Ponadto powinniśmy jasno komunikować politykom, że gdy zostanie przekroczona _granica bezpieczeństwa_, jest czas, aby [zatrzymać dalszy rozwój](/proposal).