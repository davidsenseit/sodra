# ADR 0001 – AI-neutral, filbaserad utbildningsarkitektur

**Status:** proposed
**Datum:** 2026-11-05

## Kontext
Utbildningen ska fungera i olika AI-tjänster utan egen app eller leverantörsspecifikt format. En URL i sig garanterar inte att modellen får åtkomst till filerna.

## Beslut
Markdown är kanoniskt innehållsformat. README är mänsklig ingång, AGENTS.md ger modellneutral undervisningsstyrning, pedagogy definierar metod och knowledge innehåller faktagranskade moduler. Separata kataloger håller terminologi, övningar och kvalitetsarbete samman. Alla ännu ej granskade ämnesfakta märks draft.

## Konsekvenser
Låg teknisk tröskel och transparent versionshantering; varierande följsamhet mellan modeller och beroende av faktisk läsåtkomst. Därför behövs AI-kompatibilitetstester och tydlig hantering av otillgängligt innehåll.

## Alternativ
Leverantörsspecifika systemprompter och specialbyggd webbapp avvaktas eftersom de ökar inlåsning och underhåll.
