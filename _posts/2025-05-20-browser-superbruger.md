---
title: Browser Superbruger-tips
date: 2025-05-20 20:16:45 +/-0
description: Størstedelen af dette opslag er skrevet af min indre fanatiker. Langt størstedelen på internettet er frit tilgængeligt. "Hvis noget er gratis, er du produktet" har jeg tidligere hørt. Det sker ofte i form af salg af dine data til reklameformål. Sådan var intentionen ikke med internettet. Derfor kæmper jeg imod det ved begrænsning af den data, virksomheder kan sælge om mig.
categories: [Browser]
tags: [browser,chrome,firefox,udvidelser,edge,safari,superbruger]     # TAG names should always be lowercase
image:
  path: https://upload.wikimedia.org/wikipedia/commons/a/a0/Firefox_logo%2C_2019.svg
---

## Adblocking
_I forlængelse af adblokcing kan [Robinsonlisten](#robinsonlisten) også nævnes._
<br>Jeg er træt af reklamer på hjemmesider. Derfor bruger jeg en udvidelse til at fjerne dem.

Jeg har været en kæmpe fan af [UBlock Origin](https://ublockorigin.com/) i længere tid.
<br>Hvorfor lige UBlock Origin? Der er flere grunde. Men den væsentligste er, at det er open source. Det betyder, at alle kan kigge og ændre i kildekoden. Derfor har udvikleren bag heller ikke noget kommercielt formål.

### Hent UBlock Origin
UBlock Origin findes i sin fulde udgave i [Mozilla Firefox](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/) og i en Lite-udgave (som kan bruges i Manifest V3) i [Chrome](https://chromewebstore.google.com/detail/ublock-origin-lite/ddkjiahejlhfcafbddmgiahcphecmpfh) og [Edge](https://microsoftedge.microsoft.com/addons/detail/ublock-origin-lite/cimighlppcgcoapaliogpjjdehbnofhn)

#### Forklaringen bag
Hvorfor skrev jeg Manifest V3 før? Og hvad er Chromium?
* Flere browsere, som er bygget på webteknologien Chromium, har dog forsøgt at lukke ned for denne udvidelse og flere lignende.
* Det er Google, som står bag projektet Chromium, som Google Chrome også er bygget på. Microsoft Edge er også bygget på Chromium.
* UBlock Origin er bygget på en teknologi, som kræver Manifest V2.
* Google har ufaset Manifest V2 i Chromium og forsøger aktivt at få alt over på Manifest V3, som gør adblocking sværere – i nogle tilfælde umuligt.

### I still don't care about cookies
Jeg vil desuden understrege udvidelsen *I still don't care about cookies*, som siger nej til alle statistiske, analytiske, promoverende (indsæt selv flere ord) cookies. Den accepterer kun de cookies, som er nødvendige for at siden fungerer.

Der findes også en udvidelse, som hedder *I don't care about cookies*, men her skriver forfatteren bag den førstnævnte udvidelse:
<br>"This extension has been acquired by [Avast](https://en.wikipedia.org/wiki/Avast) (which itself has been acquired by [Gen Digital Inc.](https://en.wikipedia.org/wiki/Gen_Digital), a large tech conglomerate) and I simply don't trust Avast with my data. Additionally, having it on GitHub allows us to improve the code and add support for websites faster."<br>
*Se kilde og hent udvidelse: [GitHub/OhMyGuus/I-Still-Dont-Care-About-Cookies](https://github.com/OhMyGuus/I-Still-Dont-Care-About-Cookies?tab=readme-ov-file#why-fork)*

### Robinsonlisten
Hvis du er træft af at blive ringet op at telefonsælgere, vil jeg klart anbefale, at man tilmelder sig den GRATIS Robinsonliste. Listen kaldes også for Markedsføringsbeskyttelse. Du forbliver på listen i 100 år, medmindre du aktivt afmelder dig den igen.

<b>Men hvad gør det helt præcis?</b>
<br>Hvis du er optaget på listen, må du ikke blive ringet op af telefonsælgere, medmindre at du giver samtykke til det ved at deltage i konkurrencer på fysiske stande eller hjemmesider.
<br>Hvis du alligevel har tilmeldt dig en konkurrence, kan du i opkaldet til sælgeren sige: "Jeg giver ikke længere samtykke til, at I gemmer mit telefonnummer eller ringer mig op." Du har nu tilbagetrukket dit samtykke og har derfor ret til at blive slettet.

[Listen er gratis. Tilmeld dig listen på borger.dk](https://www.borger.dk/bolig-og-flytning/beskyttelse-mod-reklamer/Robinsonlisten-markedsfoeringsbeskyttelse)

## Adgangskoder
At gemme sine adgangskoder i en digital notesbog (såsom Google Keep, Samsung notes, Apple Notes) er ikke sikkert. Hvis man kigger dig over skylderen eller din kode bliver lækket, kan resten af dine adgangskoder være i fare.<br>
Jeg har her samlet tre forslag til, hvordan du kan gemme dine adgangskoder. Personligt bruger jeg og kan anbefale [Bitwarden](#bitwarden)

### Google Adgangskodeadministrator

|Fungerer godt til|Sammen med|
|---|---|
|Chrome som browser (Windows/Mac)|Android som telefon (endnu bedre med [Gboard](https://play.google.com/store/apps/details?id=com.google.android.inputmethod.latin&hl=da))|

Hvis du bruger disse to løsninger sammen, er dine adgangskoder altid synkroniseret og du kan altid tilgå dem på <https://passwords.google.com>

Læs mere i artiklerne [Gem, administrer og beskyt dine adgangskoder](https://support.google.com/accounts/answer/6208650?hl=da&ref_topic=7188671&sjid=9238301982084630166-EU#zippy=) og [Brug adgangskoder på alle dine enheder](https://support.google.com/accounts/answer/6197437?hl=da&ref_topic=7188671&sjid=9238301982084630166-EU)

### Apple Adgangskoder

|Fungerer godt til|Sammen med|
|---|---|
|Mac som computer|iPhone som telefon|

Apple har deres egen app til administration af adgangskoder.

Læs mere på [Apples hjemmeside](https://support.apple.com/da-dk/104955)

### Bitwarden

|Fungerer godt til|Sammen med|
|---|---|
|Enhver browser|Enhver telefon|

Bitwarden er en adgangskodeadministrator, der kan synkronisere dine adgangskoder på tværs af alle dine enheder. Den understøtter autoudfyld og er helt gratis at bruge. Jeg har ikke premium versionen. Men hvis man ønsker den, koster det $10 om året.

Læs mere på <https://bitwarden.com/products/personal/>

## Genvejstaster
Udvalgte genvejstaster til din browser

Der kan være forskel på genvejstasterne i de forskellige browsere. Herunder er der en liste over de mest almindelige genvejstaster i Chrome, Firefox, Edge og Safari. Listen herunder burde dog gælde for dem alle.

| Windows | Mac | Hvad gør den? |
|---|---|---|
| Ctrl + 0 | Cmd + 0 | Zoom til 100% |
| Ctrl + + | Cmd + + | Zoom ind |
| Ctrl + - | Cmd + - | Zoom ud |
| Ctrl + E | Cmd + Option + F (Chrome/Edge) / Cmd + K (Firefox) | Marker søgefeltet |
| Ctrl + F | Cmd + F | Søg på siden |
| Ctrl + H | Cmd + Y (Chrome/Edge) / Cmd + Shift + H (Firefox) | Åben historik |
| Ctrl + J | Cmd + Shift + J (Chrome/Edge) / Cmd + Option + L (Firefox) | Åben downloads |
| Ctrl + L eller Alt + D | Cmd + L | Marker adresselinjen |
| Ctrl + N | Cmd + N | Åbn nyt vindue |
| Ctrl + Shift + N | Cmd + Shift + N (Chrome/Edge/Safari) / Cmd + Shift + P (Firefox) | Åbn nyt inkognitovindue / privat vindue |
| Ctrl + R eller F5 | Cmd + R | Opdater siden - Hvis siden ikke opdaterer rigtigt, brug da genvejen herunder |
| Ctrl + Shift + R eller Ctrl + F5 | Cmd + Shift + R (Chrome/Edge/Firefox) / Cmd + Option + R (Safari) | Opdater siden (ryd cache) |
| Ctrl + T | Cmd + T | Åbn ny fane |
| Ctrl + Shift + T | Cmd + Shift + T | Åbn den sidst lukkede fane |
| Ctrl + W | Cmd + W | Luk den aktive fane |
| Ctrl + Shift + W | Cmd + Shift + W | Luk vinduet |
| Ctrl + [tal] | Cmd + [tal] | Åbn den fane, som svarer til tallet (fx Ctrl/Cmd + 1 åbner den første fane) |
| Ctrl + Tab / Ctrl + Shift + Tab | Ctrl + Tab / Ctrl + Shift + Tab | Skift til næste/forrige fane (også Safari) |

## Valg af browser
Hvornår har du sidst skiftet browser? Det er ikke lige noget, man gør hver dag.<br>
De mest kendte browsere er Chrome, Edge, Firefox og Safari. Der findes også mange andre browsere, som er bygget på [Chromium](#forklaringen-bag), som fx Brave og Vivaldi.

Generelt for browserne gælder det, at det er hurtige og brugervenlige. Derfor vil jeg kun fokusere forskelle herunder.

Jeg har prøvet både Chrome, Edge og Firefox på forskellige tidspunkter.<br>
<b>Personligt anbefaler jeg [Firefox](#firefox)</b>, da den er open source og fokuserer på privatliv og sikkerhed. Den er også hurtig og har mange nyttige funktioner.

### Chrome
Google Chrome er nok den mest udbredte og kendte browser. Men Google er kendt for at opsnappe så meget data som muligt, og derfor er det ikke den mest privatlivsvenlige browser.
* Fordele
    * Godt integreret med Googles økosystem
    * Mange udvidelser
        * <em>Hvis man bruger forskellige Micorsoft konti, kan man med fordel installere udvidelsen [Microsoft Single Sign On](https://chromewebstore.google.com/detail/microsoft-single-sign-on/ppnbnpeolgkicgegkbkbjmhlideopiji). Dog understøtter [Firefox](#firefox) denne funktion som standard.</em>
* Ulemper
    * Google opsnapper meget data
    * Kan være svært at navigere i indstillingerne

### Edge
Microsoft Edge er den indbyggede browser i Windows 10 og 11. Den er bygget på Chromium og har derfor mange af de samme funktioner som Google Chrome.
* Fordele
    * Godt integreret med Microsofts økosystem
    * Mange udvidelser
    * God downloads-menu
* Ulemper
    * Microsoft opsnapper meget data
    * Noget sværere end Chrome at finde rundt i Indstillinger
    * Du kan ikke tilgå dine adgangskoder andre steder end Edge, hvor du gemmer dem direkte heri

*Eftersom Chrome og Edge er bygget på Chromium, er fordele og ulemper meget ens.*

### Firefox
Mozilla Firefox er en populær open source-browser, der fokuserer på privatliv og sikkerhed. Den har mange nyttige funktioner og et stort udvalg af udvidelser.
* Fordele
    * Privatlivsvenlig, understøtter bl.a. [UBlock Origin](#adblocking)
    * Mange udvidelser, dog færre end Chrome og Edge
    * [Mulighed for at være logget ind med Microsoft konti gennem Windows](https://support.mozilla.org/da/kb/windows-sso)
        * <em>Jeg elsker virkelig denne funktion med Microsoft konti gennem Windows. Så slipper man for at taste sin Microsoft-kode ind hver gang man fx skal ind på Aarhus Universitets systemer. Det er bare super hurtigt.</em><br>![](https://assets-prod.sumo.prod.webservices.mozgcp.net/media/uploads/gallery/images/2023-03-15-05-18-46-bb89d8.png)
    * Downloads-menu med rigtig mange gode indstillinger
* Ulemper
    * Kræver noget tid at sætte sit ind i Indstillingerne for optimal erfaring
    * Nogle hjemmesider kan give fejl ved højere brug af beskyttelse sporingstracking

### Safari
Apple Safari er standardbrowseren på macOS og iOS. Den er hurtig og energieffektiv, men har færre udvidelser end de andre browsere.
* Fordele
    * Virkelig godt integreret med Apples økosystem
    * Indbygget filter til privatliv
* Ulemper
    * Færre udvidelser end de andre browsere
    * Kan give fejl på flere hjemmesider

### Andre browsere
Der findes også mange andre browsere, som er bygget på Chromium, som fx Brave, DuckDuckGo og Vivaldi. De har deres egne fordele og ulemper, men generelt set tilbyder de et højere niveau af privatliv og sikkerhed sammenlignet med de mere etablerede browsere.

---
*Billedkreditering: Mozilla Corporation, MPL 2 <https://www.mozilla.org/en-US/MPL/2.0/>, via Wikimedia Commons*
