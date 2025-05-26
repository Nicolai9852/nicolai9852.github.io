---
title: Browser Superbruger-tips
date: 2025-05-20 20:16:45 +/-0
categories: [Browser]
tags: [browser,chrome,firefox,udvidelser,edge,safari,superbruger]     # TAG names should always be lowercase
---

## Adblocking
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
*Kilde: [GitHub/OhMyGuus/I-Still-Dont-Care-About-Cookies](https://github.com/OhMyGuus/I-Still-Dont-Care-About-Cookies?tab=readme-ov-file#why-fork)*

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
<b>Personligt anbefaler jeg Firefox</b>, da den er open source og fokuserer på privatliv og sikkerhed. Den er også hurtig og har mange nyttige funktioner.

### Chrome
Google Chrome er nok den mest udbredte og kendte browser. Men Google er kendt for at opsnappe så meget data som muligt, og derfor er det ikke den mest privatlivsvenlige browser.

|Fordele|Ulemper|
|---|---|
|Godt integreret med Googles økosystem|Google opsnapper meget data|
|Mange udvidelser|Kan være svært at navigere i indstillingerne|

<em>Hvis man bruger forskellige Micorsoft konti, kan man med fordel installere udvidelsen [Microsoft Single Sign On](https://chromewebstore.google.com/detail/microsoft-single-sign-on/ppnbnpeolgkicgegkbkbjmhlideopiji). Dog understøtter [Firefox](#firefox) denne funktion som standard.</em>

### Edge
Microsoft Edge er den indbyggede browser i Windows 10 og 11. Den er bygget på Chromium og har derfor mange af de samme funktioner som Google Chrome.

|Fordele|Ulemper|
|---|---|
|Godt integreret med Microsofts økosystem|Microsoft opsnapper meget data|
|Mange udvidelser|Kan være svært at navigere i indstillingerne|
|God downloads-menu||

*Eftersom Chrome og Edge er bygget på Chromium, er fordele og ulemper meget ens.*

### Firefox
Mozilla Firefox er en populær open source-browser, der fokuserer på privatliv og sikkerhed. Den har mange nyttige funktioner og et stort udvalg af udvidelser.

|Fordele|Ulemper|
|---|---|
|Privatlivsvenlig, understøtter bl.a. [UBlock Origin](#adblocking)|Ikke integreret med noget økosystem|
|Mange udvidelser|Kan være svære at navigere i indstillingerne|
|[Mulighed for at være logget ind med Microsoft konti gennem Windows](https://support.mozilla.org/da/kb/windows-sso)|Nogle hjemmesider kan give fejl|
|Fantastisk downloads-menu||

<em>Jeg elsker virkelig denne funktion med Microsoft konti gennem Windows. Så slipper man for at taste sin Microsoft-kode ind hver gang man fx skal ind på Aarhus Universitets systemer. Det er bare super hurtigt.</em>
![](https://assets-prod.sumo.prod.webservices.mozgcp.net/media/uploads/gallery/images/2023-03-15-05-18-46-bb89d8.png)

### Safari
Apple Safari er standardbrowseren på macOS og iOS. Den er hurtig og energieffektiv, men har færre udvidelser end de andre browsere.

|Fordele|Ulemper|
|---|---|
|Virkelig godt integreret med Apples økosystem|Færre udvidelser end de andre browsere|
|Indbygget filter til privatliv|Kan give fejl på flere hjemmesider|

### Andre browsere
Der findes også mange andre browsere, som er bygget på Chromium, som fx Brave, DuckDuckGo og Vivaldi. De har deres egne fordele og ulemper, men generelt set tilbyder de et højere niveau af privatliv og sikkerhed sammenlignet med de mere etablerede browsere.
