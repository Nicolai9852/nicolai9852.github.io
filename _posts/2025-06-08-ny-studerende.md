---
title: Ny studerende
date: 2025-06-08 18:02:00 +/-0
description: Velkommen til teologistudiet! Denne guide er til dig, som er ny studerende. Hjemmesiden er en samling over de spørgsmål, jeg selv ønskede svar på, da jeg startede, samt tekniske spørgsmål, som jeg har fået gennem min studietid. Herunder er samlet de væsenligste til at komme i gang. Du skal også være velkommen til blot at surfe rundt.
categories: [Universitet]
tags: [word,microsoft,office,universitet,zotero,eksamen]     # TAG names should always be lowercase
pin: true
---

## Adblocking
Er du træt af reklamer?
Slip hurtigt af med dem i mit opslag om [Adblocking](/posts/browser-superbruger#adblocking).

## Akribi
Jeg er ikke super dygtig til retskrivning. Det kommer denne hjemmeside heller ikke til at handle om. Den vil i stedet fokuseret på tekniske tips og tricks.
Hvis du er teolog eller teologistuderende, vil jeg anbefale, at du kigger på [akribi.dk](https://akribi.dk/), som er en side af Kasper Berholt.<br>
Siden indeholder det væsenligste (og mere til) af relevant materiale, når du skal skrive fagteologisk.

## Bogkøb
Overvej at købe bøger sammen fra fx [Bibelselskabet](https://bibelselskabet.dk) eller [Rahbeks Antikvariat](https://bog-rahbek.dk/). Begge boghandler har tidligere givet fri fragt og 10% rabat, når man bestiller mere end 10 eksemplarer.<br>
Vi har tidligere bestilt:
* Novum Testamentum Graece (et Latine) fra Bibelselskabet
* Themelion fra Rahbeks Antikvariat
* A Concise Greek-English Dictionary of the New Testamen Revised Edition

Skriv til Bibelselskabet på [netbutik@bibelselskabet.dk](mailto:netbutik@bibelselskabet.dk) og Rahbeks Antikvariat på [birgit@bog-rahbek.dk](mailto:birgit@bog-rahbek.dk) for spørg dem ad.

## Kalender
### FIUC-Aarhus (Menighedsfakultetet)
Der findes ikke nogen fælles kalender for undervisningen på FIUC-Aarhus. Du kan derfor selv lave en.

### Aarhus Universitet
Du kan synkronisere din AU kalender med din personlige kalender

1. Åben <https://timetable.au.dk>
2. Tryk på de to pile i den højre side
3. Vælg din kalender-type i menuen
   1. Hvis du ikke vil se fx Sprogcafe i din kalender, kan du trykke "Vælg timeplaner" --> Vælg Aktivitetstyper i bunden (du kan få behov for at zoome ud fra skærmen) --> fravælg "Praktisk" --> tryk "Luk"
4. Tryk nu "Næste"
5. Kopiér linket og indsæt det i din personlige kalender.
6. Tillykke, din AU kalender er nu synkroniseret med din private kalender.

<!--
## Noter
Har du overvejet, hvordan du vil holde styr på dine noter?<br>
Jeg kan klart anbefale [Obsidian](/posts/obsidian).
-->

Jeg startede med at skrive mine noter i OneNote, men jeg følte mig begrænset af funktionerne.<br>
Det føler jeg derimod ikke med Obsidian - det er næsten OneNote på steroider.

## Printer på Menighedsfakultetet
Du kan få behov for at printe på Menighedsfakultetet, hvis du læser på FIUC-Aarhus. Sådan installerer du printeren

### Windows
1. Hent driveren <b>PCL 6 Driver</b> på <https://support.ricoh.com/bb/html/dr_ut_e/rc3/model/imc3010/imc3010.htm>
2. Installer driveren til computeren
3. Undervejs i installationen af driveren skal du trykke "Min printer er ikke på listen"
4. Her skal du indskrive at finde printeren ved hjælp af IP-adressen som er `10.0.100.26`
5. Når du er færdig, kan du finde den i Windows Indstillinger --> Bluetooth og enheder --> Printere og scannere
6. Hvis printeren ikke fremgår af listen, skal du
    1. Vælg "Tilføj en printer ved hjælp af en IP-adresse eller et værtsnavn"
    2. Vælg enhedstypen som "Automatisk søgning"
    3. Skriv IP-adressen `10.0.100.26`, efterlad portnavn tom og tryk Næste
    4. Hvis der står `10.0.100.26_1` i portnavnet, er printeren allerede installeret.
    5. Du skal installere driveren med printeren. Vælg i menuen producent "Ricoh" og driveren "RICOH IM C3010 PCL 6"
    6. Printeren skulle gerne installere nu.
7. Husk at give den et navn, fx MF Bibliotek. Du kan omdøbe en printers navn under Ydereligere printerindstillinger --> Omdøb
8. Eftersom print koster penge, skal du tilføje dit Vennenr./Givernr.
9. Find printeren under Windows Indstillinger --> Bluetooth og enheder --> Printere og scannere og tryk på den
10. Vælg nu "Udskriftsindstillinger"
11. Under fanene "Grundlæggende" vælger du knappen "Brugerkodeindstilling..."
12. Her skriver du dit Vennenr./Givernr. ind
13. Tryk nu OK begge gange
14. Tjek også at efterbehandleren er slået til. Den kan hæfte sider sammen, hvis du får brug for det.
15. Gå tilbage til menuen for "Printere og scannere" i Windows Indstillinger og vælger printeren.
16. Tryk nu "Printeregenskaber"
17. Vælg menupunktet "Tilbehør"
18. Sørg for at flueben er sat i "Efterbehandler SR3310". Hvis det ikke er sat, skal du sætte det.
19. Tryk OK
20. Du er klar til at printe

### Mac
1. Hent driveren ned til din Mac. Sørg for at vælge den rigtige version af din Mac: <https://support.ricoh.com/bb/html/dr_ut_e/rc3/model/mpc3004/mpc3004.htm>
2. Installer driveren ved at dobbeltklikke på den og gå hele installtionsprocessen igennem.
3. Åben Systemindstillinger og find menupunktet for "Printere og scannere"
4. Tryk "Tilføj printer, scanner eller fax"
5. Vælg det miderste ikon (globussen) i den nye boks, som er kommet frem
6. Under "Adresse" skriver du `10.0.100.26`
7. Under "Navn" skriver du fx `MF Bibliotek` - det blot din egen navngivning af printeren
8. Under menuen "Brug" skal du trykke "Vælg Software" og søg efter "RICOH MP 3504 PS"
9. Tryk "OK" og derefter "Tilføj"
10. Efter printeren er blevet slået til, skal du vælge den i Systemindstillinger og trykke "Indstillinger og forsyninger"
11. Vælg "Indstillinger" (den i midten)
12. Vælg under "Efterbehandler" SR3130.
13. Tryk nu OK begge gang.
14. Vælg nu et dokument, som du vil printe
15. Tryk Cmd + P som genvejstasten til print.
16. Under punktet "Joblog", skal du sætte flueben i "Aktiver brugerkode" og skrive dit MF Vennenr./Givernr. - Dog kun i feltet for Brugerkode.
17. Tryk OK
18. Vent med at printe - i stedet skal du under "Forudindstillinger" i toppen af printboksen trykke "Gem aktuelle indstillinger som forudindstillinger"
19. Kald den fx "Min printkonto på MF" og gem den kun på denne printer.
20. Du er nu klar til at printe.

## Teologisk begreber
Jeg har forsøgt at lave en mindre liste over teologiske buzzwords, som kan være gode, når man starter på teologistudiet.

| Begreb         | Betydning                                                     |
| -------------- | ------------------------------------------------------------- |
| Apoftegme      | Noget med ørkenfortællinger                                   |
| Apokalyptik    | Læren om endetiden                                            |
| Apologetik     | Trosforsvar                                                   |
| Diaspora       | En gruppe af religiøse menensker (ofte brugt om jøder), som lever i landflygtighed, men stadigvæk praktiserer deres religion |
| Doxologi       | Læren om lovprisning (i gudstjenesten)                        |
| Ekklesiologi   | Læren om den kristne kirke og menigheden                      |
| Eksegese       | Udlæsning af en bibelsk tekst                                 |
| Eskatologi     | Læren om de sidste tider                                      |
| Hedning        | Bruges ofte i Bibelen om du er jøde eller 'ikke-jøde' (hedning)<br> Kan også bruges i tilfælde af kategoriseringer af jøder, kristne og hedninger |
| Homiletik      | Læren om prædiken                                             |
| Hymnologi      | Læren om kristne salmer og sange                              |
| Kristologi     | Læren om hvem Kristus var og er                               |
| Missiologi     | Læren om kristendommens udspredelse                           |
| Partikularisme | Guds udvælgelse af Israel til at være sit folk                |
| Parusi         | Et begreb om Jeus nærvær eller anden genkomst                 |
| Soteriologi    | Læren om frelsen                                              |
| Theodicé       | Læren om Guds retfærdighed i lyset af lidelse                 |

## Tips til enkelte fag
Da jeg selv både går på Menighedsfakultetet (FIUC-Aarhus) og Aarhus Universitet, er mine fag adskilt og semesterplanen for fagene herunder kan derfor også være forskellig.

Altid som hovedregel - forbered dig og følg med til undervisningen.

### Indføring i Bibelen
_Kursus på FIUC-Aarhus, 1. semester_ <br>

Det fremgår af _Tilladte hjælpemidler til eksamen, side 2, Kriterier for tillatte hjelpemidler punkt 2_ ved Fjellhaug, at:<br>
"Det tillates understrekninger av ord og tall. Flere farger kan brukes, men det skal ikke forekomme håndskrift i hjelpemidlet. Unntaket for denne regelen gjelder eksamen i språkfagene gresk og hebraisk, hvor ingen form for understrekning eller notater er tillatt (jf. liste E)"

Begynd så tidligt som muligt at lave understregninger i din Bibel. Brug evt. de forskellige farver til at hjælpe dig med at huske bestemte ting.

### Etik og religionsfilosofi 1
_Kursus på Aarhus Universitet, 1. semester_ <br>

Såfremt at "Den etiske fordring" stadigvæk bruges, vil jeg anbefale at anskaffe [Kompendium til K.E. Løgstrup: Den etiske fordring](https://klim.dk/bog/kompendium-til-k-e-loegstrup-den-etiske-fordring/), hvis man har svært ved at forstå "Den etiske fordring". Den giver nogle  vigtige nedslag over kapitlerne, så det kan være lettere at forstå Løgstrup.

### Græsk 1 & 2 samt Latin 1 & 2
_Kursus på Aarhus Universitet, hhv. 1.-2. og 2.-3. semester_

<i>Se desuden opslaget om [Studieværktøjer](/posts/studieværktøjer/#sprogværktøj-til-græsk-og-latin), hvor der er en liste over elektroniske hjælpemidler.</i>

Du skal lave en del morfologisk analyse i disse kurser. Det kommer nok oftest til at ske i hånden.<br>
Lav derfor et system, som gør at du hurtigt kan skrive ting ned. Det kan samtidigt også hjælpe dig til at skrive hurtigere [til den mundtlige eksamen på hhv. 3. og 4. semester](#græsk-3-samt-latin-3). Jeg giver følgende eksempler. 

|Forkortelse|Betydning|
|---|---|
|A|Aktiv|
|Adj|Adjektiv|
|Akk|Akkusativ|
|Aor|Aorist|
|Gen|Genitiv|
|Imp|Imperfektum|
|Impera|Imperativ|
|I eller Ind|Indikativ|
|Inf|Infinitiv|
|Konj|Konjuktiv|
|Nom|Nominativ|
|P|Præsens|
|p|Passiv|
|Part|Participium|
|Pl|Pluralis|
|Sg|Singularis|

Jeg har også en bestemt rækkefølge, så jeg ikke blander forskellige ting sammen:<br>
TID MODUS DIATESE PERSON TAL<br>
Eksempelvis: `P I A 3 sg` giver `Præsens Indikativ Aktiv 3. person singularis`

### Græsk 3 samt Latin 3
_Kursus på Aarhus Universitet på 3. og 4. semester_

Eksamen er 60 minutter forberedelse og 20 minutters eksamination.

* Brug læseferien på at genlæse nogle af bøger.
    * Græsk
        * Themelion
        * Nytestamentlig græsk
    * Latin
        * Latinsk grammatik på dansk for at 
* Lave prøveeksamener. Sæt en time af og se hvor meget du kan derefter.
    * Oplæsning
    * Oversættelse
    * Morfologisk analyse
    * Syntaktisk analyse
    * Andre termer
* Brug evt. nogle af [sprogværktøjerne](/posts/studieværktøjer/#sprogværktøj-til-græsk-og-latin) til hjælp i forberedelsen.

### Nytestamentlig eksegese af synoptisk evangelium
_Kursus på FIUC-Aarhus, 4. semester_

Da prøvenformen er den samme for [Indføringen i Bibelen](#indføring-i-bibelen), henviser jeg dertil igen.<br>
Brug evt. både din græske og danske Bibel og lav den samme understregning i begge, sådan at du kan lave krydstjek mellem dem.

## Word
Du har helt sikkert skrevet en opgave i Word før. Men har du styr på, hvordan du bruger de forskellige funktioner?
<br>[Læs mere omkring brugen af funktioner i Word](/posts/word-superbruger/)

## Zotero
Zotero er et program, som kan holde styr på dine referencer, når du skriver en opgave. Når du er færdig, kan den også danne litteraturlisten for dig.
<br>[Læs mere om brugen af Zotero](/posts/zotero)
