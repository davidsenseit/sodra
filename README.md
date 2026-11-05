# Södra – öppet pedagogiskt kunskapssystem

Ett AI-oberoende utbildningsunderlag för att förstå och självständigt värdera Södra skogsägarnas ekonomiska förening och dess ekonomiska modell.

**Status:** Grundstruktur och pedagogiskt ramverk (fas 1). Ämnesmoduler och verifierade kunskapskontroller återstår. Repositoryt är inte ännu en komplett kurs.

## För användare
En kompatibel AI-assistent med faktisk åtkomst till repositoryt kan använda [AGENTS.md](AGENTS.md) som undervisningsinstruktion, [pedagogy/FRAMEWORK.md](pedagogy/FRAMEWORK.md) som pedagogiskt ramverk och verifierade ämnesmoduler under `knowledge/`. Att enbart klistra in en GitHub-URL ger inte garanterad åtkomst i alla AI-tjänster. Om assistenten inte kan läsa filerna behöver användaren tillhandahålla dem.

Förslag på startfråga: ”Använd undervisningsinstruktionerna i detta repository för att lära mig förstå Södras ekonomiska modell. Börja med att kartlägga mina förkunskaper.”

## För utvecklare
- [AGENTS.md](AGENTS.md): AI-neutral instruktion och undervisningsprotokoll
- [ROADMAP.md](ROADMAP.md): faser, prioriteringar och acceptanskriterier
- [pedagogy/FRAMEWORK.md](pedagogy/FRAMEWORK.md): metodval och progression
- [pedagogy/ASSESSMENT.md](pedagogy/ASSESSMENT.md): bedömning och återkoppling
- [knowledge/README.md](knowledge/README.md): kunskapsmoduler och faktastatus
- [glossary/README.md](glossary/README.md): terminologisk styrning
- [exercises/README.md](exercises/README.md): övningar och facit
- [quality/README.md](quality/README.md): kvalitetssäkring och AI-tester
- [docs/decisions/0001-learning-architecture.md](docs/decisions/0001-learning-architecture.md): arkitekturbeslut

## Principer
Saklighet framför marknadsföring. Fakta skiljs från antaganden och tolkningar. Föränderlig ekonomisk information tidsmärks. `draft` är inte faktagranskat; `verified` används först efter granskning. Beräkningar kontrolleras separat. Material skrivs självständigt med respekt för upphovsrätt.

Bidrag sker via avgränsade issues och pull requests. Merge kräver projektägarens godkännande.
