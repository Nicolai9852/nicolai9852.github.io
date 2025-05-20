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
### PDF24
Gratis online program til genbehandling af PDF'er<br>
<https://tools.pdf24.org/en/ocr-pdf>

### iLovePDF
Gratis online program til genbehandling af PDF'er<br>
<https://www.ilovepdf.com/ocr-pdf>

## Offline værktøjer
### OCRmyPDF
OCRmyPDF kræver lidt mere teknisk viden, men jeg har virkelig brugt det meget og nydt det.
Samtidigt er det offline og kan derfor bruges, selv hvis du ikke har internet.

Som udgangspunkt vil du nok komme til at installere det på en Windows-computer.
Jeg anbefaler at følge denne installationsguide: <https://ocrmypdf.readthedocs.io/en/latest/installation.html#native-windows><br>
Herunder har jeg renskrevet på dansk til de vigtigste punkter.

#### Installation af Tesseract og OCRmyPDF
1. Hvis du ikke allerede har, installer winget. Det kan gøres ved at følge denne guide: <https://docs.microsoft.com/en-us/windows/package-manager/winget/>
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
