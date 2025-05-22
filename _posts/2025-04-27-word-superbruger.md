---
title: Word Superbruger-tips
date: 2025-04-27 18:16:45 +/-0
categories: [Software, Skrivning]
tags: [word,microsoft,office,zotero,superbruger]     # TAG names should always be lowercase
image:
  path: https://upload.wikimedia.org/wikipedia/commons/f/fd/Microsoft_Office_Word_%282019%E2%80%93present%29.svg
---

*Denne guide gælder i princippet også for Google Docs. Der kan dog være afvigelser ift. genvejstaster*

## Genvejstaster
Udvalgte genvejstaster på Windows og Mac

[Se den fuilde vejledning til genvejstaster for Windows](https://support.microsoft.com/da-dk/office/tastaturgenveje-i-word-95ef89dd-7142-4b50-afb2-f762f663ceb2#picktab=windows)
<br>[Se den fulde vejledning til genvejstaster for Mac](https://support.microsoft.com/da-dk/office/tastaturgenveje-i-word-95ef89dd-7142-4b50-afb2-f762f663ceb2#picktab=macos)

|Windows|Mac|Hvad gør den?|
|---|---|---|
|Ctrl + A|Cmd + A|Marker alt|
|Ctrl + B|Cmd + B|Søge-funktion|
|Ctrl + C|Cmd + C|Kopier indhold|
|Ctrl + F|Cmd + F|Fed skrift|
|Ctrl + K|Cmd + K|Kursiv skrift|
|Ctrl + S|Cmd + S|Gem dokument|
|Ctrl + V|Cmd + V|Indsæt indhold|
|Ctrl + Shift + V|Cmd + Shift + V|Indsæt kun tekst (især brugbar hvis du kopier indhold fra en hjemmeside)|
|Ctrl + X|Cmd + X|Klip indhold|
|Ctrl + Z|Cmd + Z|Fortryd|
|Ctrl + Y|Cmd + Y|Fortryd fortryd|
|Ctrl + 0|Cmd + 0|Sæt zoom til 100%|
|Ctrl + Enter|Cmd + Enter|Lav ny side|
|Ctrl + Tilbage-tasten|Cmd + Tilbage-tasten|Slet hele ord bagud|
|Ctrl + Del|Mangler på Mac|Slet hele ord foran|
|Ctrl + Enter|Cmd + Enter|Indsæt sideskift
|Shift + Enter|Shift + Enter|Indsæt mindre linjeskift|
|Enter|Enter|Indsæt nyt afsnit (større linjeskift)|
|Ctrl + piletast|Cmd + piletast|Flyt hop frem og tilbage mellem hele ord|
|Ctrl + Shift + piletast|Cmd + Shift + piletast|Marker hele ord|

## Overskrifter
Overskrifter kan være svære at finde ud af.<br>
Vælger jeg den rigtige? Synes jeg, at den skal se anderledes ud?<br>
Denne guide kan være med til at give svar på det. Bemærk, at jeg undervejs bruger ordet "Header", som er det englske term for overskrift og bruges ifm. hjemmesider.

### Hvilken overskrift skal jeg vælge?
Jeg skrev i 2025 en artikel [omkring overskrifter på hjemmesider](https://support.kirkenettet.dk/hc/da/articles/25972341258130-Overskrifter-p%C3%A5-hjemmesider), som også er brugbar for dokumenter i den akademiske skrivning <br>
Stukturen af overskrifter i et dokument og en hjemmeside er den samme.
Nogle hovedpunkter er:
* En tommelfingerregel vedr. overskrifter: Hvis du har flere Header 1 (Overskrift 1) end Header 2 (Overskrift 2), har du for mange Header 1.
    * Forklaringen bag: På hjemmesider må man ikke bruge Header 1 mere end en gang på den samme side. Det skyldes optimering af søgningen (SEO) og skærmlæsere/webtilgængelighed. I dokumenter må man gerne bruge Header 1 mere end en gang, så længe det har karakter af nyt indhold. Det gælder bl.a. dagbogsindlæg eller kapitelinddeling. Hvis man bruger overskrifter inde i et kapitel, skal det være Overskrift 2 eller en af lavere grad.
    * Se desuden <https://webaim.org/techniques/word/#headings>
* Du må aldrig gå mere end et trin ned. Du må gerne gå fra Header 2 til 3 - men aldrig fra Header 2 direkte til Header 4
* Du må gerne gå mere end et trin op hver gang, fx må du gerne gå fra Header 4 til Header 2

### Opdatering af alle overskrifter på en gang
<b>Dette punkt er vigtigt for en flot opstillet opgave og kan spare dig meget tid.</b><br>
Du må som udgangspunkt ikke ændre formateringen på en overskrift uden at gøre det på alle andre.
Det vil sige, at hvis du synes, at en overskrift skal have en anden størelse, farve eller lign, bør du følge denne guide.

1. Vælg en af dine typografier i toppen af dit Word-dokument. Det kunne fx være Overskrift 2.
2. Højreklik og tryk *Rediger*
   ![](/assets/img/word-overskrift2-rediger.png)
3. Lav nu om i overskriften som du har lyst til
   1. Du kan ændre ting som font, skriftstørrelse, farve m.m.
4. Sæt som regel altid flueben i *Opdater automatisk*
   ![](/assets/img/word-overskrift2-opdater.png)
5. Overvej om dette skal være generelt for dine dokumenter eller kun dette. Du kan enten vælge *Kun i dette dokument* eller *Nye dokumenter baseret på skabelonen*
6. Tryk OK

Hvis vi følger eksemplet, vil alle dine Overskrift 2'er bliver opdateret med den nye formattering

## Referencehåndtering
[Se min vejledning om Zotero](/posts/zotero)

## Når du er færdig
Når du er færdig med at skrive en opgave, skal du eksportere dit dokument rigtigt.

1. Åben Filer --> Eksporter --> Opret PDF-XPS-dokument. Her trykker du på knappen "Opret PDF/XPS"
2. Som standard er indstillingerne for "Åben fil efter publicering" og "Standard (online publicering og udskrivning)" valgt. Det er fint.
3. Tryk nu på knappen til højre i dialogboksen, hvor der står "Indstillinger"
![](/assets/img/word-pdf-export-diagbox.png)
4. Her skal du være opmærksom på følgende indstillinger
    1. Sideområde: Som udgangspunkt skal den være sat til "Alle"
    2. Hvad skal udgives: "Dokument"
    3. Medtag oplysninger, der ikke udgives
        1. Sæt flueben i "Opret bogmærker ved hjælp af: Overskrifter"
        2. Sæt flueben i "Dokumentegenskaber"
        3. Sæt flueben i "Koder til dokumentstruktur for tilgængelighed"
    4. PDF-indstillinger:
        1. Sæt flueben i "Bitmaptekst, når skrifttyper ikke er integreret"
![](/assets/img/word-pdf-export-settings.png)



---
*Billedkreditering: Microsoft Corporation, Public domain, via Wikimedia Commons*
