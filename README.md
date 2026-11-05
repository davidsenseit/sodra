# Södra – öppet pedagogiskt kunskapssystem

Ett AI-oberoende utbildningsunderlag för att förstå och självständigt värdera Södra skogsägarnas ekonomiska förening och dess ekonomiska modell.

**Status:** Tio kunskapsmoduler (01–10) och 21 övningar finns som **draft**. Ingen modul är ännu verifierad för undervisningsbruk. Kvalitetsgranskning pågår; repositoryt är ännu inte en färdig kurs.

## Starta utbildningen
Klistra in repositoryts adress i en AI-assistent som kan läsa GitHub-innehållet. När länken är det enda användaren skickar ska assistenten läsa [AGENTS.md](AGENTS.md) och [pedagogy/ONBOARDING.md](pedagogy/ONBOARDING.md), ge en **kort välkomsthälsning** och börja undervisa i modul 01 direkt. Ingen meny, nivåindelning eller inledande fråga om förkunskaper. Alla tio moduler genomförs i ordning.

**Viktigt:** En ensam URL garanterar inte att alla AI-tjänster kan läsa eller följa instruktionerna. Repositoryt måste vara tillgängligt för tjänsten (det är för närvarande privat). Om innehållet inte kan läsas ska assistenten säga det, inte låtsas starta kursen.

**Testversion:** Alla moduler är ännu `draft`. I uttryckligt testläge får de användas som preliminärt undervisningsmaterial med tydlig information om att faktagranskningen inte är klar. De får inte beskrivas som verifierade.

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

## Kvalitetsläge
Den tvärgående [granskningsrapporten](quality/cross-module-audit-2026-11-05.md) listar faktarisker, pedagogiska förbättringar och återstående kontroller. Färdigskrivet utkast är inte detsamma som verifierat undervisningsmaterial.
