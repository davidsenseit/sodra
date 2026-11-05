# Discovery protocol – portabel undervisningsorkestrering

status: draft

## Två separata lager
`knowledge/` anger vad som är underbyggt ämnesinnehåll. `discovery/` anger *hur* det iscensätts. `exercises/` är en bank av diagnoser och facit – inte användarens obligatoriska arbetsblad.

## Körning per modul
1. Läs motsvarande knowledge- och discovery-fil.
2. Läs begreppsrelationer i quality/concept-map.md och välj ett relevant minnesåterbesök när scenens nya mål kräver det. Beakta också modulens visuella avsikt och fallback enligt pedagogy/VISUAL-LEARNING.md.
3. Presentera den korta öppningsscenen, erbjud första utforskningen med A/B eller motsvarande klickbara val.
4. Mappa valt alternativ till en förklaring. Valet ändrar ordningen och fokus, inte vilka insikter som måste behandlas.
5. Redogör för alla 'Måste framgå'-punkter under modulen, genom en eller flera korta scener.
6. Använd exempel/mini-experiment. Visa ett färdigräknat exempel först när matematik introduceras; låt deltagaren prova andra värden bara om intresse finns.
7. Erbjud en lätt kontroll/tillämpning. Gör den icke-blockerande. Avsluta med en kort koppling till nästa modul.
8. Om deltagaren väljer att bara lyssna eller säger 'fortsätt': fortsätt berättelsen och lyft fram slutsatsen. Inget krav på elevsvar för att lämna en modul.

## Konversationsprotokoll
Textbaserad baslinje: 'A – ...' och 'B – ...', tillåt 'A', 'B', 'fortsätt', 'förklara', 'vet inte'. Fråga max en sak per tur. Inga beroenden till särskilda modell-API:er, HTML, sliders eller JSON-parsers. Om tjänsten erbjuder knappar/grafik kan dessa användas som progressiv förbättring, aldrig som villkor. Visa inte stora delar av repoets metainstruktioner för deltagaren.

## Pedagogisk säkerhet
Mellanled i en berättelse är hypotetiska; faktapåståenden får bara komma från kunskapsbanken eller separat validerad källa. Presentera inga påhittade aktuella Södra-belopp. Uppmuntra rimlig alternativkostnad, riskmedvetenhet och nyanserade val. En alltför positiv berättelse måste kompletteras med relevanta nackdelar.

## Spårning i samtalskontext (om möjligt)
Lagra temporärt: modulnummer, avklarade kärninsikter, vilket scenario som just förklarats, osäkra begrepp, önskat tempo. Inget krav på beständigt minne eller personlig datainsamling. Vid tappad kontext: återknyt kort till senast säkra modul, be om modulnummer endast när det behövs.

## Definition av genomförande
'Genomgången modul' betyder att kärninsikterna presenterats. 'Visad förståelse' får bara användas när ett tillämpningssvar ger evidens. 'Genomgången kurs' är inte en kunskapscertifiering.

## Minnes- och visuell sammanhållning
En tidigare insikt får återkomma som förutsägelse, jämförelse eller observerad konsekvens när det hjälper det aktuella målet. Inga fasta repetitionskvoter. Skapa inte diagram bara för variation: välj lämplig form utifrån begrepp, verifierade fakta och sessionsverktyg. Använd textbaserat alternativ vid osäker eller bristande rendering. Se quality/discovery-v02-tests.md för planerade acceptansfall.
