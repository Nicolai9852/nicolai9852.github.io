---
title: Windows Superbruger-tips
date: 2025-04-29 12:56:00 +/-0
description: Her er nogle tips til Windows 11.
categories: [Software, Værktøj]
tags: [windows,microsoft,superbruger]     # TAG names should always be lowercase
image:
  path: https://upload.wikimedia.org/wikipedia/commons/e/e5/Windows11abstract.webp
---



## Genvejstaster
### Udvalgte genvejstaster i Windows

|Genvejstast|Hvad gør den?|Kommentar|
|---|---|---|
|Ctrl + Shift + Esc|Åben jobliste|Det er også muligt at højreklikke på processlinjen og vælge joblisten herfra, så man ikke skal bruge Ctrl + Alt + Delete|
|Win + E|Åben Stifinder||
|Win + I|Åben Indstillinger||
|Win + L|Lås computeren|Efterlad din computer sikkert|
|Win + P|Skift præsentationsvisning|Brugbart hvis du har flere skærme tilkoblet|
|Win + S|Åben Windows Søgning|Alternativt kan du også trykke på Win-tasten og begynde at skrive.|
|Win + V|Åben udklipsholder|Se tekst og billeder, som du har kopieret over den seneste tid|
|Win + .|Åben emoji-vælger||
|Win + Mellemrum|Skrift tastatursprog|Hvis du har flere sprog installeret på dit tastatur, fx Dansk, Engelsk og Græsk, kan du hurtigt skifte mellem dem|
|Win + piletast|Flyt et vindue rundt||
|Prnt Scrn eller Prt Sc|Tag skærmbillede|Se overskriften [Klippeværktøj](#klippeværktøj)|

### Udvalgte genvejstaster i Stifinder

|Genvejstast|Hvad gør den?|Kommentar|
|---|---|---|
|F2|Omdøb fil|Marker en fil og tryk på knappen|
|F5|Opdater vinduet|Kan også bruges i browsere, hvor den især er brugbar som Ctrl + F5|
|Alt + pil op|Gå en mappeniveau op (tilbage)||
|Ctrl + Alt + N|Opret ny mappe||
|Ctrl + F|Søg på siden||
|Ctrl + T|Åben ny fane i Stifinder|Kun for Windows 11|

## Klippeværktøj
Brug Klippeværktøj på Windows til at tage skærmbilleder/screenshots.

Du kan desuden aktivere knappen *Print Scrn* på dit tastatur til at aktivere knappen.
<br>Åben [Windows Indstillinger --> Tilgængelighed --> Tastatur](ms-settings:easeofaccess-keyboard) --> *Brug tasten PrintScrn til at åbne skærmbillede*

![](/assets/img/windows/windows-indstillinger-printscrn.png)

## Navngivning i Stifinder
Har du overvejet, hvordan du navngiver dine filer, så du altid kan finde dem.<br>
I langt de fleste tilfælder er titelen, som noget har på forhånd, nok.<br>
Men hvad med noter fra undervisning, referarter eller regninger, som skal sorteres i rækkefølge?

<b>Her anbefaler jeg altid formattet YYMMDD som det første i filens navn</b> - dvs. år måned dato. 250816 svare til d. 16. august 2025.<br>
Jeg bruger aldrig DDMMYY, fordi det forvrænger sorteringen. Se herunder

### Eksempel på DDMMYY
Normalt sortes filer efter navnet på den. Lad os bruge et eksempel i formattet DDMMYY
* 010124
* 070505
* 150411
* 201125
* 270615

Sådan vil soteringen se ud i Stifinder.<br>
Overvej blot lige, at der kunne sagtens være 100 filer i samme mappe, hvor de ikke er sorteret efter kronologi, men efter de første to tal i datoen.

### Sorteret rigtigt i YYMMDD
Hvis du vil se filerne kronologisk, skal du i stedet opsætte dem YYMMDD
* 070505
* 110415
* 150627
* 240101
* 251120

Bemærk at navnet på filerne er den samme, men de er nu sorteret i en kronologisk rækkefølge.

## Opgrader til Windows 11 (selv hvis kravene ikke lever op til det)
*Kom endelig og spørg, inden du går i gang med denne guide.*

I flere tilfælde kan man opgradere sin computer til Windows 11. Et af de "hårdre" krav er, at computeren skal have en bestemt processor, som skal stå på en liste. Men mange processere kan godt køre Windows 11, selvom de ikke er på listen. Microsoft har dog ikke officielt understøttet det, selvom det vil fungere uden det mindste problem. I dette tilfælde vil jeg altid opgradere computeren. Hvis computeren derimod ikke understøtter TPM 2.0, vil jeg som regel ikke gøre det.

Sæt gerne 1-2 timer af til at gøre det, da det kan tage lang tid at hente Windows 11 ned og installere det.

### Trin 1: Registry-tilføjelse
Vi skal først tilføje en værdi i Windows Registry, som gør det muligt at opgradere til Windows 11.
Du kan enten gøre det hente en fil ned eller gøre det manuelt.

#### Trin 1a: Hentning af fil
1. Hent filen [Windows11BypassCPUCheck](/assets/Windows11BypassCPUCheck.reg)
    1. Jeg har selv lavet filen. Du kan bekræfte det ved at åbne filen i Notesblok eller et andet tekstprogram. Der står kun følgende i den. <br> ![](/assets/img/windows/RegFileScreenshot.png)
    
2. Dobbeltklik på filen og tryk Ja, når du bliver spurgt om at køre den.
3. Sig Ja til at tilføje den i Windows Registry
4. Filen er tilføjet og du skal genstarte computeren

#### Trin 1b: Manuel tilføjelse
I den manuelle tilføjelse skal du selv lægge værdien ind.

1. Tryk på Win + R for at åbne Kør
2. Skriv `regedit` og tryk Enter. Kør som administrator, når du bliver spurgt.
3. Naviger i mapperne til `HKEY_LOCAL_MACHINE\SYSTEM\Setup\MoSetup`
    1. Hvis en mappe ikke findes, oftest `MoSetup`, så højreklik på mappen over og vælg Ny -> Nøgle og skriv navnet på mappen.
4. Højreklik i højre side og vælg Ny --> DWORD (32-bit) værdi
5. Giv den nye værdi navnet `AllowUpgradesWithUnsupportedTPMOrCPU`
6. Dobbeltklik på den nye værdi og sæt værdien til `1`
7. Luk Registry Editor
8. Genstart computeren

### Trin 2: Lav et installationsmedie
Nu skal du lave et installationsmedie, som du kan bruge til at installere Windows 11.
1. Hent [Media Creation Tool](https://www.microsoft.com/da-dk/software-download/windows11) fra Microsofts hjemmeside
2. Find overskriften `Opret installationsmedie til Windows 11` og tryk på `Download nu`-knappen
3. Kør programmet, når det er hentet ned
4. Brug de anbefalede indstillinger for sprog, udgave og arkitektur.
5. Vælg "ISO-fil" og tryk på "Næste"
6. Vælg et sted at gemme filen (jeg forslår Overførsler) og tryk på "Gem"
7. Vent på, at filen bliver hentet ned. Det kan tage et stykke tid.
8. Når filen er hentet ned, kan du lukke programmet ved at trykke Udfør.

### Trin 3: Installer Windows 11 fra ISO-filen
1. Find den hentede ISO-fil og højreklik på den.
2. Vælg "Monter" for at montere den som et drev.
3. Åben Stifinder og find det nye drev, som er blevet oprettet.
4. Find filen `setup.exe` og dobbeltklik på den.
5. Følg installationsguiden.
6. På et af de første billeder er der en blå tekst man kan trykke for at vælge, om den skal installere opdateringer med det samme. Vælg i stedet "Ikke nu", da opdateringerne kan tage lang tid.
7. Når du kommer længere frem, læs at `Behold personlige filer og apps` er valgt. Det er gjort som standard.
8. Du får nu at vide, at din computer ikke lever op til kravene ved en gul advarselstrekant. Det er helt okay. Vi fortsætter alligevel.
9. Tryk på "Installér" og vent på, at installationen er færdig. Det kan tage et stykke tid.

Tillykke, nu bliver WIndows 11 installeret på din computer og du beholder dine filer og programmer.

## Quick Share
Alle kender funktionen AirDrop, som fungerer mellem Apple-enheder. I længere tid har vi ventet på et alternativ mellem Android og Windows. Men nu findes det.
Funktionen hedder "Quick Share" og er helt gratis.

### Installation
Quick Share er indbygget i alle Android telefoner udgivet siden 2015 (Android 6).<br>
Du skal derfor kun hente et program ned til din Windows computer.

1. Quick Share til Windows hentes på Androids hjemmeside: <https://www.android.com/intl/da_dk/better-together/quick-share-app/>
2. Installer nu programmet
3. Log ind på Quick Share med din Google konto
4. Jeg anebfaler, at du sætter synligheden på din computer til "Modtage fra dine enheder"
5. Nu kan du fx åbne et billede på din Android-telefon og trykke på knappen for deling.
7. Tryk på "Quick Share"
8. Du skulle gerne kunne se din computer nu.
    1. Hvis din computer ikke komme frem, kan det skyldes, at dit Wifi blokerer det. Det kan du undgå ved at skifte synligheden på din computer til "Modtage fra alle" i en begrænset periode.

---
*Billedkreditering: MikoSushi000, Public domain, via Wikimedia Commons*
