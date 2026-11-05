# Tvärgående kvalitetsgranskning – kunskapsbank 01–10

status: draft
audit_date: 2026-11-05
scope: repository content and internal consistency
external_primary_source_verification: pending

## Omfattning och verifierad inventering
- Tio kunskapsmoduler: 01–10; samtliga märkta `draft`.
- Fyra övningsfiler med sammanlagt **16** identifierade fråge-ID:n: KOOP-Q001, STYR-Q001, STYR-Q002; VIR-Q001, VIR-Q002, IND-Q001, IND-Q002; KAP-Q001, EMI-Q001, VIN-Q001, VIN-Q002; INV-Q001, INV-Q002, RISK-Q001, VARD-Q001, VARD-Q002.
- Ingen modul ska märkas `verified` enbart för att den finns i `main` eller har ett facit.
- Denna granskning är **inte** en oberoende extern faktagranskning. Publicerade primärkällor och ursprungliga stämmohandlingar måste fortfarande kontrolleras.

## Avvikelser och risker

### Hög prioritet – faktapåståenden och ekonomiska rättigheter
1. Modul 07 återger två olika belopp för förslag respektive stämmobeslut 2026. Kontrollera originalhandling, datum, beslutets beståndsdelar, avrundning och eventuella rättelser innan frågan VIN-Q001 kan verifieras.
2. Modul 05 anger insatsgränser och avdragssatser. Verifiera aktuell stadgeversion, medlemsvillkor, avdragsgrund, eventuell skillnad mellan medlemskategorier och regler för återbetalning. Undvik att presentera gränserna som tidlösa.
3. Modul 06 beskriver ändrad emissionsgrund från 2026. Kontrollera beslutets exakta ikraftträdande, omfattning och vilka vinstdelningsår det påverkar.
4. Modul 02 anger antal skogsbruksområden/fullmäktige. Kontrollera mot gällande organisation och stadgar, inklusive skillnaden mellan medlemsröst lokalt och fullmäktiges röst på föreningsstämman.
5. Modul 03 nämner specifika affärsformer och mätningsvillkor. Verifiera gällande avtalsvillkor och skillnader i volym- och prissättningsmodell. Inga hypotetiska priser får användas som aktuella marknadspriser.
6. Modul 04 namnger verksamhetsgrenar. Kontrollera mot aktuell koncernorganisation och rapportsegment; juridiska enheter, varumärken och affärsområden får inte sammanblandas.

### Medelprioritet – pedagogisk spårbarhet
7. Övningsfilerna har mål och facit, men saknar en gemensam maskinläsbar koppling till specifika lärandemåls-ID:n. Inför stabila mål-ID:n och en matris mål → förklaring → fråga → bedömningskriterium.
8. De första sju modulerna har varierande hänvisningar till fråge-ID:n; modul 08–10 saknar konsekventa direkta länkar till sina frågor. Gör navigeringen enhetlig.
9. Frågorna testar ofta enbart ett exempel. Lägg till nya överföringsuppgifter och felanalys för att möjliggöra mastery learning utan att återanvända facit.
10. Svarsrubriken `facit` ligger i samma fil som frågan. Testa om AI-assistenter faktiskt väntar på elevens svar innan facit avslöjas; vid behov separera elevvy och lärarvy.
11. Rubrikerna `status`, `source_checked_at` och `prepared_at` används inkonsekvent. Fastställ en enhetlig metadata-konvention och dokumentera skillnaden mellan författad, källkontrollerad och verifierad.

### Låg prioritet – dokumentation
12. README beskriver fortfarande fas 1 som nuläge trots tio draft-moduler. Uppdatera status och navigation.
13. ROADMAP:s kryssrutor speglar inte färdigskrivna draft-moduler. Skilj uttryckligen `utkast klart` från `faktagranskat och verifierat`.
14. Ordlistorna överlappar, exempelvis likviditet. Skapa en auktoritativ definition per begrepp och korshänvisa.

## Beräkningskontroller – omräknade
- VIR-Q001: 80 × 650 = 52 000; 80 × 150 = 12 000; netto = 40 000 kr.
- VIR-Q002: 720 − 200 = 520; 680 − 120 = 560; skillnad = 40 kr per m³fub.
- IND-Q001: 2 000 000 − 1 200 000 − 700 000 = 100 000 kr.
- EMI-Q001: 25 000 × 0,04 = 1 000 kr.
- KAP-Q001: 50 000 + 12 000 = 62 000 kr.
- VARD-Q001: 2 500 kr kontant, 1 500 kr emitterat kapital; inte 4 000 kr kontant.
Beräkningarna är aritmetiskt korrekta **givet de hypotetiska antagandena**. De verifierar inte Södras faktiska avtal eller utdelningsregler.

## Föreslagen arbetsordning
1. Källgranska kritiska Södra-specifika påståenden och dokumentera källversioner.
2. Normalisera metadata och mål-/frågekopplingar.
3. Förbättra frågor med nya tillämpningar, motiveringar och bedömningsrubriker.
4. Genomför tvärmodellstester för tillgång till filer, draft-hantering, frågeordning och facit.
5. Gör oberoende sakgranskning och märk enskilda moduler `verified` först efter dokumenterad kontroll.

## Acceptanskriterier för avslut
Alla högt prioriterade avvikelser åtgärdade eller tydligt blockerade, aritmetik kontrollerad, lärandemål spårbara, externa sakuppgifter verifierade mot daterade originalkällor och genomförda AI-/användartester dokumenterade.
