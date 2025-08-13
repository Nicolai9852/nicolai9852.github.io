---
title: OCR-scanning
date: 2025-05-20 09:16:00 +/-0
description: Jeg elsker at kunne markere og søge i mine indscannede dokumenter. Hvordan retter man det, hvis det ikke kan lade sig gøre?
categories: [Software, Værktøj]
tags: [browser,software,windows]     # TAG names should always be lowercase
---

Hvis du scanner en tekst ind, kan mange scannere i dag genkende tekstens sprog og gøre den søgbar.<br>
Men hvad gør du, hvis dette ikke er tilfældet?

Her er nogle værktøjer, som kan hjælpe dig med at gøre dine indscannede dokumenter søgbare.

## Online værktøjer
For langt de fleste vil det være tilstrækkeligt at bruge et online værktøj.
Disse værktøjer kræver ikke installation og kan bruges direkte i din browser.

### PDF24
PDF24 er mit go-to værktøj, hvis jeg er på farten og skal have lavet en hurtig OCR-scanning.
<https://tools.pdf24.org/en/ocr-pdf>

Husk at vælge sprog, når du uploader din fil og outputtype som PDF.

*Umiddelbart ligner det, at PDF24 bygger deres motor på [OCRmyPDF](#ocrmypdf). Det kan du også installere på din egen computer.*

### iLovePDF
iLovePDF er et andet godt alternativ til OCR-scanning af PDF'er. Men indstillingerne er mere begrænsede ift. PDF24.
Du kan dog stadig vælge sprog.
<https://www.ilovepdf.com/ocr-pdf>

## Offline værktøjer (mere advanceret)
### OCRmyPDF
OCRmyPDF kræver lidt mere teknisk viden, men jeg har virkelig brugt det meget og nydt det.
Samtidigt er det offline og kan derfor bruges, selv hvis du ikke har internet.<br>
Du har desuden mere frihed over indstillingerne.

Som udgangspunkt vil du nok komme til at installere det på en Windows-computer.
Jeg anbefaler at følge denne installationsguide: <https://ocrmypdf.readthedocs.io/en/latest/installation.html#native-windows><br>
Herunder har jeg renskrevet på dansk til de vigtigste punkter.

#### Installation af Tesseract og OCRmyPDF
1. Start med at installere Appinstallation. Du kan hente den fra <https://apps.microsoft.com/detail/9NBLGGH4NNS1?hl=da-dk&gl=DK&ocid=pdpshare>
   1. Når du installerer Appinstallation, vil den installere Winget (Windows Package Manager) automatisk. (Winget er et helt fantastisk værktøj til at installere programmer på Windows super let!)
2. Herefter kan du installere Python med kommandoen `winget install -e --id Python.Python.3.11`
3. Herefter kan du installere Tesseract med kommandoen `winget install -e --id UB-Mannheim.TesseractOCR`
4. Nu skal du installere Ghostscript fra deres hjemmeside <https://ghostscript.com/releases/gsdnld.html>
5. Nu kan du installere OCRmyPDF med kommandoen `py -m pip install ocrmypdf`
6. Til sidst `py -m ocrmypdf`

#### Installation af sprogpakker
Nu kan du hente den danske sprogpakke (eller evt. andre pakker ned) til brug. Jeg følger vejledningen fra <https://ocrmypdf.readthedocs.io/en/latest/languages.html>
1. Åben <https://github.com/tesseract-ocr/tessdata/> og find den sprogpakke, du har brug for. I de fleste tilfælde vil det være `dan.traineddata` til dansk. Det direkte link er <https://github.com/tesseract-ocr/tessdata/blob/main/dan.traineddata>
2. Tryk på "Download raw file" i højre hjørne
3. Flyt den downloadede fil til mappen `C:\Program Files\Tesseract-OCR\tessdata`

Nu er du klar til at bruge OCRmyPDF.

#### Brug af OCRmyPDF
1. Åben en kommandoprompt (cmd, PowerShell eller Windows Terminal)
2. Skriv `ocrmypdf -l SPROG --output-type pdf LOKATION_INPUT_FIL LOKATION_OUTPUT_FIL`
   1. Eksempel: `ocrmypdf -l dan --output-type pdf "C:\Users\Bruger\Downloads\Dokument.pdf" "C:\Users\Bruger\Downloads\Dokument.pdf"`
      1. Hvis du bruger det samme navn til input og output, vil det overskrive det gamle dokument.
   2. Angiv flere sprog ved bruge af -l dan+eng
   3. Tilføj evt. --force-ocr for at tvinge OCR på alle sider
   4. Tilføj evt. --deskew for at rette skæve sider
   5. Tilføj evt. --rotate-pages for at rette forkerte indscannede rotationer
