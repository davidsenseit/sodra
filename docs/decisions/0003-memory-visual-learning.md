# ADR 0003 – Minnesmedveten, visuellt behovsstyrd undervisning
status: proposed
date: 2026-11-05
discovery_learning_version: 0.2.0

## Kontext
Den befintliga tio-modulerskursen ger låg interaktionströskel och god narrativ kontinuitet, men hade ingen fullständig begreppskarta för senare återkomster och ingen dokumenterad visuell representationsstrategi. En kvarvarande formulering i bedömningsmatrisen kunde tolkas som kunskapsspärr.

## Beslut
- Behåll modulordning, berättelsedrivet upptäckande, A/B/fortsätt och frivillig fördjupning.
- Planera minnesåterkomster via begreppskarta och sakligt relevanta nya scenarier, utan fasta quizkvoter.
- Visualisera bara där orsakssamband, flöde eller ekonomi blir tydligare; alla obligatoriska insikter har textbaserad fallback.
- Vid utveckling görs daterad dokumentationskontroll av avsedda AI-miljöer; faktisk verktygstillgång kontrolleras endast i session där den kan observeras.
- Inget runtime-beroende till discovery-learning-repositoryt. Kursen innehåller alla egna körinstruktioner.
- Förändra inte kunskapsbankens sakfakta eller status genom denna pedagogiska PR.

## Alternativ och nackdelar
Obligatoriska repetitionsprov ger mer diagnostisk evidens men återintroducerar skrivfriktion. Rik grafik i alla moduler kan öka kognitiv belastning och modellberoende. En central skill hämtad vid varje kursstart kan fallera vid otillgänglighet. De alternativen avvisas för detta användningsfall.

## Validering och begränsning
Statisk filstruktur, täckning och vissa exempelberäkningar kan kontrolleras i utvecklingen. Manuella tester med ChatGPT, Claude och faktiska deltagare återstår. Belagda pedagogiska effekter kan inte hävdas innan sådan uppföljning.
