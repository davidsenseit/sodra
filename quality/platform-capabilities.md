# Plattformskapabiliteter – daterad utvecklingssnapshot
status: draft
checked_at: 2026-11-05
source_type: official_provider_documentation
runtime_tested: false

## Evidensnivåer
`documented` = i officiell dokumentation; `available` = exponerat i aktuell session; `tested` = fungerade i faktisk körning; `blocked` = dokumenterat/observerat hinder; `unknown` = otillräckligt underlag. Dokumenterat betyder inte testat.

| Målmiljö | Dokumenterat | Villkor och begränsning | Evidens |
|---|---|---|---|
| ChatGPT webb/app | Interaktiva stapel-, linje-, cirkel- och punktdiagram i vissa svar/dataanalys | Plan, modell, aktiverade funktioner och format varierar; godtyckliga skräddarsydda reglage kan inte antas | documented, not tested |
| Claude web/Desktop | Artifacts för diagram, dokument, dashboards och mindre interaktiva verktyg | Aktiverad kapacitet/organisationsinställningar och plan; API/andra klienter ska inte antas fungera identiskt | documented, not tested |
| Claude visualiserad chatt | HTML/SVG-baserade diagram och enkla interaktiva visualiseringar | Beta- och klientberoende | documented, not tested |
| Generisk kompatibel textmodell | A/B/fortsätt, texttabeller och beräknade exempel | Kräver att repository kan läsas | design baseline, not runtime tested |

## Officiella källor vid denna kontroll
- ChatGPT data analysis: https://help.openai.com/en/articles/9213685-extracting-insights-with-chatgpt-data-analysis (webbkontroll 2026-11-05).
- ChatGPT release notes: https://help.openai.com/en/articles/6825453-chatgpt-release-notes (webbkontroll 2026-11-05).
- Claude Artifacts: https://support.claude.com/en/articles/17153992-what-are-artifacts-and-how-do-i-use-them (webbkontroll 2026-11-05).
- Claude visual content: https://support.claude.com/en/articles/13641943-visual-and-interactive-content (webbkontroll 2026-11-05).

## Kurslokala körregler
Skapa endast interaktiv grafik när den aktuella AI-tjänsten faktiskt exponerar ett lämpligt verktyg. Kort kontroll vid kursstart, ingen stor plattformsresearch före första scenen. Vid osäkerhet: enkel text eller tabell. Redovisa inte utförda verktygstester förrän de faktiskt genomförts.

## Ny kontroll
Vid större plattformsförändring, nytt utvecklingsprojekt, misstänkt inaktuell information eller konkret verktygsfel: kontrollera de aktuella officiella källorna igen och dokumentera datum, miljö och resultat. Detta är inte en automatisk bakgrundsbevakning.
