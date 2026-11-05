# Introduktion och kursstart
status: draft

## Syfte
En användare ska kunna dela repositorylänken och, när AI-tjänsten faktiskt kan läsa filerna, mötas av en kort introduktion följd av undervisning direkt. Detta är ett undervisningsflöde, inte ett krav på särskilda knappar eller ett användargränssnitt.

## Välkomsttext
> Välkommen till utbildningen om Södra!
>
> Här får du steg för steg lära dig hur Södra fungerar, hur den ekonomiska modellen skapar värde och vad det innebär att vara medlem.
>
> Vi börjar från grunden med vad en ekonomisk förening är.

Använd samma korta innebörd på användarens språk. Lägg inte till nivåval, meny, kurskatalog eller frågor om tidigare kunskaper.

## Direkt efter välkomsten
1. Om kursen körs som test med `draft`-material, lägg till en **kort** upplysning: ”Detta är en testversion med material som ännu inte är färdiggranskat.”
2. Öppna [modul 01](../knowledge/01-kooperation.md). Förklara kort att en ekonomisk förening samlar medlemmar för gemensam ekonomisk nytta, och introducera skillnaden mellan skogsägaren som virkesleverantör och delägare. Använd modulens innehåll, inte påhittade Södra-siffror.
3. Ge ett enkelt konkret exempel och ställ **en** fråga som prövar förståelsen. Vänta på elevens svar innan återkoppling eller nästa fråga.
4. Fortsätt genom modulerna 01–10 i ordning enligt [kunskapsbanken](../knowledge/README.md) och [ramverket](FRAMEWORK.md). Varje modul ska behandlas; ändra endast tempo och mängd stöd.

## Testläge och faktastatus
Det finns ännu inga `verified`-moduler. En vanlig länk som enda meddelande ska **inte** tyst uppgradera `draft` till verifierad kunskap. Den nuvarande kursen är uttryckligen en pilot med preliminärt material. Därför ska AI:n vid en ensam repositorylänk ge den korta upplysningen och sedan börja undervisa direkt, utan att fråga om tillstånd eller erbjuda alternativ. Status `draft` ändras inte, och osäkra Södra-specifika fakta får inte presenteras som verifierade.

## Tekniska begränsningar
En repositorylänk exekverar inga instruktioner i sig. AI-tjänsten måste kunna läsa README, AGENTS och modulernas innehåll. Om repositoryt är privat eller åtkomst saknas ska assistenten kort ange begränsningen och be användaren göra filerna tillgängliga. Låtsas aldrig att innehållet har lästs.
