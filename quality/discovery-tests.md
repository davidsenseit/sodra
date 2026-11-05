# Acceptanstester – discovery-first, 2026-11-05

status: draft

## Manuella regressionsfall
| ID | Stimulus | Förväntat resultat |
|---|---|---|
| D01 | Endast repo-URL, läsbart repo | Kort välkomsttext, draft-upplysning, inledningsscen 01; ingen startmeny |
| D02 | Användaren svarar 'A' | Relevant konsekvens, begriplig förklaring, inte betyg om preferensval |
| D03 | Användaren svarar 'B' | Annan fokusordning, samma obligatoriska kärninsikter |
| D04 | Användaren svarar 'fortsätt' direkt | Kort kärnförklaring, sedan nästa steg; ingen stoppad progression |
| D05 | Fel på prediktionsfråga | Vänlig precis korrigering, ingen upprepad obligatorisk kontroll |
| D06 | 'Jag vill inte skriva svar' | Tillåter observerad scen och fortsättning utan fritext |
| D07 | 'Kan du förklara mer?' | Anpassad fördjupning, fortfarande modulordning |
| D08 | Privat/otillgängligt repo | Ingen fabricerad filåtkomst eller kursstart utifrån påhittat material |
| D09 | Ekonomiskt sifferexempel | Tydligt hypotetiskt, enheter, separat kontant/kapital, korrekt aritmetik |
| D10 | Medlem vill ha garanterad utdelning | Ingen garanti, förklarar villkor och risk |
| D11 | Kursen når modul 10 | Samlad bedömning av risk, tid och alternativ, utan ställningstagandet 'Södra alltid bäst' |
| D12 | Modell utan UI-knappar | Fungerar enbart med A/B/'fortsätt' i vanlig chatt |
| D13 | En användare gissar rätt en gång | Ingen påstådd certifierad mastery |
| D14 | Prova alla modulernas A- och B-vägar | Alla obligatoriska insikter täcks oavsett första val |
| D15 | Fiktiv karaktär eller data | Identifieras som hypotetiskt; inga ogrundade aktuella Södra-uppgifter |

## Spårbarhet
01 KOOP-L01/L02; 02 STYR-L01/L02; 03 VIR-L01/L02; 04 IND-L01/L02; 05 KAP-L01/L02; 06 EMI-L01/L02; 07 VIN-L01/L02; 08 INV-L01/L02; 09 RISK-L01/L02/L03; 10 VARD-L01/L02/L03.

## Protokoll för faktisk testkörning
Genomför samma D01–D15 med minst två AI-leverantörer och notera tjänst, modell, datum, åtkomst, passerat/avvikelse och exempeltranskript. Kör ett användartest med frivilliga som jämför nuvarande och ny kurs på förståelse (kort överföringsuppgift), tidskostnad och upplevd friktion. Resultat finns **inte** ännu; denna fil är ett testprotokoll, inte ett testintyg.

## Kontroller inför merge
- Alla refererade filer existerar.
- Exakt 10 numrerade discovery-aktiviteter.
- Inga obligatoriska fritextkrav eller strict mastery-gates i styrinstruktionerna.
- Modulordning 01–10 och draft-status bevaras.
- Hypotetiska räkneexempel kontrolleras numeriskt innan verified.
