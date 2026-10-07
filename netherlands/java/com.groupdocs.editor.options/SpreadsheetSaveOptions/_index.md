---
title: "SpreadsheetSaveOptions"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Staat toe aangepaste opties op te geven voor het genereren en opslaan van Spreadsheet Excel-conforme documenten"
type: docs
weight: 37
url: /nl/java/com.groupdocs.editor.options/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class SpreadsheetSaveOptions implements ISaveOptions
```

Staat toe aangepaste opties op te geven voor het genereren en opslaan van Spreadsheet
(Excel-conforme) documenten

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | Deze parameterloze constructor maakt een nieuw exemplaar van SpreadsheetSaveOptions aan met XLSX-uitvoerformaat (kan vervolgens worden aangepast via |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) eigenschap)
|
|  | [SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)](#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-) | Maakt een nieuw exemplaar van SpreadsheetSaveOptions aan met opgegeven verplichte |
Spreadsheet-uitvoerformaat, terwijl alle andere parameters standaard zijn
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPassword()](#getPassword--) | Staat toe om een wachtwoord op te geven, te wijzigen, te verkrijgen of te verwijderen, die zal worden |
gebruikt om het gegenereerde Spreadsheet-document te coderen, indien dit documentformaat
ondersteunt wachtwoordbeveiliging.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Staat toe om een wachtwoord op te geven, te wijzigen, te verkrijgen of te verwijderen, die zal worden |
gebruikt om het gegenereerde Spreadsheet-document te coderen, indien dit documentformaat
ondersteunt wachtwoordbeveiliging.
|
|  | [getWorksheetNumber()](#getWorksheetNumber--) | Staat toe een bewerkte werkblad in te voegen in een kopie van een bestaande spreadsheet |
in plaats van een nieuwe enkel-werkblad spreadsheet te maken (standaard
gedrag).
|
|  | [setWorksheetNumber(int value)](#setWorksheetNumber-int-) | Staat toe een bewerkte werkblad in te voegen in een kopie van een bestaande spreadsheet |
in plaats van een nieuwe enkel-werkblad spreadsheet te maken (standaard
gedrag).
|
|  | [getInsertAsNewWorksheet()](#getInsertAsNewWorksheet--) | Booleaanse vlag die aangeeft of het bewerkte werkblad moet vervangen |
bestaand werkblad in de oorspronkelijke spreadsheet op de positie, gespecificeerd door
de

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
eigenschap, of het moet worden ingevoegd tussen het bestaande werkblad en
het vorige, zonder de inhoud te vervangen.
|
|  | [setInsertAsNewWorksheet(boolean value)](#setInsertAsNewWorksheet-boolean-) | Booleaanse vlag die aangeeft of het bewerkte werkblad moet vervangen |
bestaand werkblad in de oorspronkelijke spreadsheet op de positie, gespecificeerd door
de

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
eigenschap, of het moet worden ingevoegd tussen het bestaande werkblad en
het vorige, zonder de inhoud te vervangen.
|
|  | [getOutputFormat()](#getOutputFormat--) | Staat toe een Spreadsheet-indeling op te geven, die zal worden gebruikt voor het opslaan van de |
document
|
|  | [setOutputFormat(SpreadsheetFormats value)](#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-) | Staat toe een Spreadsheet-indeling op te geven, die zal worden gebruikt voor het opslaan van de |
document
|
|  | [getWorksheetProtection()](#getWorksheetProtection--) | Staat toe een werkbladbeveiliging in te schakelen voor de uitvoer-Spreadsheet |
document.
|
|  | [setWorksheetProtection(WorksheetProtection value)](#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-) | Staat toe een werkbladbeveiliging in te schakelen voor de uitvoer-Spreadsheet |
document.
|
|  | [getWorksheetNumbersToDelete()](#getWorksheetNumbersToDelete--) | Staat toe een array met 1-gebaseerde nummers van werkbladen op te geven die tijdens het opslaan uit de spreadsheet moeten worden verwijderd, voor het geval dat het bewerkte werkblad in een bestaande spreadsheet wordt ingevoegd. |
|
|  | [setWorksheetNumbersToDelete(int[] value)](#setWorksheetNumbersToDelete-int---) | Staat toe een array met 1-gebaseerde nummers van werkbladen op te geven die tijdens het opslaan uit de spreadsheet moeten worden verwijderd, voor het geval dat het bewerkte werkblad in een bestaande spreadsheet wordt ingevoegd. |
|
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


Deze parameterloze constructor maakt een nieuw exemplaar van SpreadsheetSaveOptions aan met XLSX-uitvoerformaat (kan vervolgens worden aangepast via
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) eigenschap)


### SpreadsheetSaveOptions(SpreadsheetFormats outputFormat) {#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)
```


Maakt een nieuw exemplaar van SpreadsheetSaveOptions aan met opgegeven verplichte
Spreadsheet-uitvoerformaat, terwijl alle andere parameters standaard zijn


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | outputFormat | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) | Verplicht uitvoerformaat waarin het Spreadsheet-document moet worden opgeslagen. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Staat toe om een wachtwoord op te geven, te wijzigen, te verkrijgen of te verwijderen, die zal worden
gebruikt om het gegenereerde Spreadsheet-document te coderen, indien dit documentformaat
ondersteunt wachtwoordbeveiliging. Geef NULL of een lege tekenreeks op om te verwijderen.
(opschonen) van het wachtwoord.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Staat toe om een wachtwoord op te geven, te wijzigen, te verkrijgen of te verwijderen, die zal worden
gebruikt om het gegenereerde Spreadsheet-document te coderen, indien dit documentformaat
ondersteunt wachtwoordbeveiliging. Geef NULL of een lege tekenreeks op om te verwijderen.
(opschonen) van het wachtwoord.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### getWorksheetNumber() {#getWorksheetNumber--}
```
public final int getWorksheetNumber()
```


Staat toe een bewerkte werkblad in te voegen in een kopie van een bestaande spreadsheet
in plaats van een nieuwe enkel-werkblad spreadsheet te maken (standaard
gedrag). WorksheetNumber is een 1-gebaseerd nummer van een werkblad in de
spreadsheet, geladen in de Editor-klasse. Als het 0 is (standaardwaarde), de
zal een nieuwe spreadsheet worden aangemaakt met één bewerkt werkblad. Als het
groter of kleiner dan nul is, en er is een geldige spreadsheet, geladen in
de Editor-klasse, het bewerkte werkblad, dat wordt weergegeven door de invoer
EditableDocument-instantie, zal in deze spreadsheet worden ingevoegd.


*** ** * ** ***

> ```
> Given spreadsheet has 5 worksheets:
>  WorksheetNumber  = 0; \u2014 ignore given spreadsheet, create a new spreadsheet and put edited worksheet into it.
>  WorksheetNumber  = 1; \u2014 replace the first worksheet with edited
>  WorksheetNumber  = 2; \u2014 replace the second worksheet with edited
>  WorksheetNumber  = 5; \u2014 replace the last (5th) worksheet with edited
>  WorksheetNumber  = 6; \u2014 replace the last (5th) worksheet with edited, because 6 is greater then 5 and thus is adjusted
>  WorksheetNumber = -1; \u2014 replace the last (5th) worksheet with edited, because "-1" means "last existing"
>  WorksheetNumber = -2; \u2014 replace the 4th worksheet with edited
>  WorksheetNumber = -3; \u2014 replace the 3rd worksheet with edited
>  WorksheetNumber = -4; \u2014 replace the 2nd worksheet with edited
>  WorksheetNumber = -5; \u2014 replace the first worksheet with edited
>  WorksheetNumber = -6; \u2014 replace the first worksheet with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />


*** ** * ** ***

 *WorksheetNumber*  integer property, if it is not in default state (reserved value '0'), represents a worksheet number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last worksheet. Negative values are also allowed and count worksheets from end. For example, "-1" implies last worksheet in a spreadsheet, "-2" \\u2014 last but one, etc. Like with positive values, when negative worksheet number exceeds the total count of worksheets in the given spreadsheet, it will be adjusted to the first worksheet. The  InsertAsNewWorksheet (#getInsertAsNewWorksheet.getInsertAsNewWorksheet/#setInsertAsNewWorksheet(boolean).setInsertAsNewWorksheet(boolean)) boolean property is tightly coupled with this one.

<br />



**Returns:**
int -
### setWorksheetNumber(int value) {#setWorksheetNumber-int-}
```
public final void setWorksheetNumber(int value)
```


Staat toe een bewerkte werkblad in te voegen in een kopie van een bestaande spreadsheet
in plaats van een nieuwe enkel-werkblad spreadsheet te maken (standaard
gedrag). WorksheetNumber is een 1-gebaseerd nummer van een werkblad in de
spreadsheet, geladen in de Editor-klasse. Als het 0 is (standaardwaarde), de
zal een nieuwe spreadsheet worden aangemaakt met één bewerkt werkblad. Als het
groter of kleiner dan nul is, en er is een geldige spreadsheet, geladen in
de Editor-klasse, het bewerkte werkblad, dat wordt weergegeven door de invoer
EditableDocument-instantie, zal in deze spreadsheet worden ingevoegd.


*** ** * ** ***

> ```
> Given spreadsheet has 5 worksheets:
>  WorksheetNumber  = 0; \u2014 ignore given spreadsheet, create a new spreadsheet and put edited worksheet into it.
>  WorksheetNumber  = 1; \u2014 replace the first worksheet with edited
>  WorksheetNumber  = 2; \u2014 replace the second worksheet with edited
>  WorksheetNumber  = 5; \u2014 replace the last (5th) worksheet with edited
>  WorksheetNumber  = 6; \u2014 replace the last (5th) worksheet with edited, because 6 is greater then 5 and thus is adjusted
>  WorksheetNumber = -1; \u2014 replace the last (5th) worksheet with edited, because "-1" means "last existing"
>  WorksheetNumber = -2; \u2014 replace the 4th worksheet with edited
>  WorksheetNumber = -3; \u2014 replace the 3rd worksheet with edited
>  WorksheetNumber = -4; \u2014 replace the 2nd worksheet with edited
>  WorksheetNumber = -5; \u2014 replace the first worksheet with edited
>  WorksheetNumber = -6; \u2014 replace the first worksheet with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />


*** ** * ** ***

 *WorksheetNumber*  integer property, if it is not in default state (reserved value '0'), represents a worksheet number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last worksheet. Negative values are also allowed and count worksheets from end. For example, "-1" implies last worksheet in a spreadsheet, "-2" \\u2014 last but one, etc. Like with positive values, when negative worksheet number exceeds the total count of worksheets in the given spreadsheet, it will be adjusted to the first worksheet. The  InsertAsNewWorksheet (#getInsertAsNewWorksheet.getInsertAsNewWorksheet/#setInsertAsNewWorksheet(boolean).setInsertAsNewWorksheet(boolean)) boolean property is tightly coupled with this one.

<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getInsertAsNewWorksheet() {#getInsertAsNewWorksheet--}
```
public final boolean getInsertAsNewWorksheet()
```


Booleaanse vlag die aangeeft of het bewerkte werkblad moet vervangen
bestaand werkblad in de oorspronkelijke spreadsheet op de positie, gespecificeerd door
de

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
eigenschap, of het moet worden ingevoegd tussen het bestaande werkblad en
de vorige, zonder de inhoud te vervangen. Standaard is false \\u2014
bestaand werkblad zal worden vervangen. Deze eigenschap wordt genegeerd, als waarde
van

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
eigenschap is ingesteld op '0'.


*** ** * ** ***

Standaard wordt het werkblad vervangen. Dit betekent dat als de gegeven spreadsheet 5 werkbladen heeft, en WorksheetNumber (#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))=4, dan zal het 4e werkblad worden vervangen door het nieuwe bewerkte werkblad, terwijl het totale aantal werkbladen in de spreadsheet (5) ongewijzigd blijft. Echter, als de waarde van deze eigenschap is ingesteld op *true*, zal het nieuwe bewerkte werkblad worden ingevoegd als het 4e werkblad, en zullen alle volgende werkbladen naar het einde worden verschoven: \"oud\" 4e werkblad wordt 5e, en 5e wordt 6e, en het totale aantal werkbladen in de spreadsheet wordt met één verhoogd tot 6.

<br />



**Returns:**
boolean -
### setInsertAsNewWorksheet(boolean value) {#setInsertAsNewWorksheet-boolean-}
```
public final void setInsertAsNewWorksheet(boolean value)
```


Booleaanse vlag die aangeeft of het bewerkte werkblad moet vervangen
bestaand werkblad in de oorspronkelijke spreadsheet op de positie, gespecificeerd door
de

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
eigenschap, of het moet worden ingevoegd tussen het bestaande werkblad en
de vorige, zonder de inhoud te vervangen. Standaard is false \\u2014
bestaand werkblad zal worden vervangen. Deze eigenschap wordt genegeerd, als waarde
van

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
eigenschap is ingesteld op '0'.


*** ** * ** ***

Standaard wordt het werkblad vervangen. Dit betekent dat als de gegeven spreadsheet 5 werkbladen heeft, en WorksheetNumber (#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))=4, dan zal het 4e werkblad worden vervangen door het nieuwe bewerkte werkblad, terwijl het totale aantal werkbladen in de spreadsheet (5) ongewijzigd blijft. Echter, als de waarde van deze eigenschap is ingesteld op *true*, zal het nieuwe bewerkte werkblad worden ingevoegd als het 4e werkblad, en zullen alle volgende werkbladen naar het einde worden verschoven: \"oud\" 4e werkblad wordt 5e, en 5e wordt 6e, en het totale aantal werkbladen in de spreadsheet wordt met één verhoogd tot 6.

<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final SpreadsheetFormats getOutputFormat()
```


Staat toe een Spreadsheet-indeling op te geven, die zal worden gebruikt voor het opslaan van de
document


**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - 
### setOutputFormat(SpreadsheetFormats value) {#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public final void setOutputFormat(SpreadsheetFormats value)
```


Staat toe een Spreadsheet-indeling op te geven, die zal worden gebruikt voor het opslaan van de
document


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) |  |

### getWorksheetProtection() {#getWorksheetProtection--}
```
public final WorksheetProtection getWorksheetProtection()
```


Staat toe een werkbladbeveiliging in te schakelen voor de uitvoer-Spreadsheet
document. Standaard is NULL - bescherming wordt niet toegepast. Niet alle formaten
ondersteunen een werkbladbeveiliging.


**Returns:**
[WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) - 
### setWorksheetProtection(WorksheetProtection value) {#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-}
```
public final void setWorksheetProtection(WorksheetProtection value)
```


Staat toe een werkbladbeveiliging in te schakelen voor de uitvoer-Spreadsheet
document. Standaard is NULL - bescherming wordt niet toegepast. Niet alle formaten
ondersteunen een werkbladbeveiliging.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) |  |

### getWorksheetNumbersToDelete() {#getWorksheetNumbersToDelete--}
```
public final int[] getWorksheetNumbersToDelete()
```


Staat toe een array met 1-gebaseerde nummers van werkbladen op te geven die uit de spreadsheet moeten worden verwijderd tijdens het opslaan, voor het geval dat het bewerkte werkblad in een bestaande spreadsheet wordt ingevoegd. Wanneer het bewerkte werkblad niet wordt opgeslagen als een nieuwe enkele-werkblad-spreadsheet (standaardgedrag), maar in plaats daarvan wordt opgeslagen in een bestaande spreadsheet (met behulp van #getWorksheetNumber().getWorksheetNumber() / #setWorksheetNumber(int).setWorksheetNumber(int)), is het ook mogelijk om bepaalde werkbladen uit deze spreadsheet te verwijderen door hun nummers in deze array op te geven. Standaard is deze array  null  \\u2014 er worden geen werkbladen verwijderd. Echter, wanneer deze array niet‑null en niet‑leeg is, en ten minste één geldig werkbladnummer bevat, worden na het genereren van het uitvoer‑spreadsheet‑document met de inhoud van het bewerkte werkblad de werkbladen met de opgegeven nummers uit de spreadsheet verwijderd vlak voor het schrijven van de inhoud naar de uitvoerstroom of het bestand. Werkbladnummers in deze array zijn 1‑gebaseerd, niet 0‑gebaseerd. Ongeldige nummers (kleiner dan 1 of groter dan het totale aantal werkbladen) worden genegeerd.


**Returns:**
int[] - Array van 1‑gebaseerde werkbladnummers om te verwijderen, of  null  als er niets moet worden verwijderd.

### setWorksheetNumbersToDelete(int[] value) {#setWorksheetNumbersToDelete-int---}
```
public final void setWorksheetNumbersToDelete(int[] value)
```


Staat toe een array met 1‑gebaseerde nummers van werkbladen op te geven die tijdens het opslaan uit de spreadsheet moeten worden verwijderd, voor het geval dat het bewerkte werkblad in een bestaande spreadsheet wordt ingevoegd. Werkbladnummers in deze array zijn 1‑gebaseerd. Ongeldige nummers worden genegeerd.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | int[] | Array van 1‑gebaseerde werkbladnummers om te verwijderen (kan  null  of leeg zijn). |
|

