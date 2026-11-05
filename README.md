# Södra – öppet pedagogiskt kunskapssystem

Ett AI-oberoende utbildningsunderlag för att upptäcka, förstå och självständigt värdera Södra skogsägarnas ekonomiska förening och dess ekonomiska modell.

**Status:** Tio kunskapsmoduler och upptäcktsbaserade aktiviteter för modul 01–10 är **draft**. Inget innehåll är ännu verifierat för undervisningsbruk. Detta är en testversion, inte en färdiggranskad kurs.

## Starta utbildningen
Klistra in repositoryts URL i en kompatibel AI-assistent som kan läsa GitHub-filer. Assistenten ska läsa [AGENTS.md](AGENTS.md) och [pedagogy/ONBOARDING.md](pedagogy/ONBOARDING.md), ge en kort välkomsthälsning och börja med modul 01 direkt. Ingen kursmeny eller inledande kunskapsenkät. Alla tio moduler behandlas i ordning.

Kursen bygger på **berättelser, utforskande val, konsekvensförklaringar, jämförelser och ekonomiska tankeexperiment** i stället för obligatoriska fritextsvar. Textval som A/B och 'fortsätt' fungerar som minsta gemensamma nämnare även utan klickbara gränssnitt.

**Åtkomst:** En ensam URL garanterar inte att AI-tjänsten kan läsa filerna. Om repositoryt är privat eller åtkomsten saknas ska assistenten ange det tydligt. Testmaterial med `draft` ska aldrig presenteras som verifierade fakta.

**Pedagogisk designversion:** Discovery Learning v0.2.0 (kurslokalt integrerad; inget runtime-beroende). Dokumentationen av visuella verktyg är daterad och inte testintyg.

## Utvecklarstruktur
- [AGENTS.md](AGENTS.md): modellneutral instruktion
- [pedagogy/FRAMEWORK.md](pedagogy/FRAMEWORK.md): pedagogik och progression
- [pedagogy/DISCOVERY-PROTOCOL.md](pedagogy/DISCOVERY-PROTOCOL.md): interaktionsprotokoll och fallback
- [pedagogy/MEMORY.md](pedagogy/MEMORY.md): begreppsbaserad minnesförstärkning
- [pedagogy/VISUAL-LEARNING.md](pedagogy/VISUAL-LEARNING.md): visuella pedagogiska representationer och fallback
- [quality/concept-map.md](quality/concept-map.md): beroenden och naturliga återbesök
- [quality/platform-capabilities.md](quality/platform-capabilities.md): daterad ChatGPT-/Claude-bedömning
- [pedagogy/ASSESSMENT.md](pedagogy/ASSESSMENT.md): icke-blockerande formativ bedömning
- [pedagogy/ONBOARDING.md](pedagogy/ONBOARDING.md): kort introduktion och direktstart
- [discovery/README.md](discovery/README.md): scenarier för modul 01–10
- [knowledge/README.md](knowledge/README.md): ämnesinnehåll och faktastatus
- [exercises/README.md](exercises/README.md): befintliga övningar som intern diagnosbank
- [quality/discovery-tests.md](quality/discovery-tests.md): portabilitets- och pedagogiska acceptanstester
- [docs/decisions/0002-discovery-first-learning.md](docs/decisions/0002-discovery-first-learning.md): arkitekturbeslut

## Principer
Saklighet framför marknadsföring. Tydlig skillnad mellan fakta och hypotetiska scenarier; ekonomiska uppgifter tidsmärks; beräkningar kontrolleras separat. `draft` förblir ogranskat tills en faktisk granskning motiverar `verified`. Alla ändringar går via pull requests och merge kräver projektägarens godkännande.
