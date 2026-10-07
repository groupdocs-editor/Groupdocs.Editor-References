---
title: "SpreadsheetEditOptions"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Staat toe om aangepaste opties op te geven voor het bewerken van documenten van alle ondersteunde Spreadsheet Excel‑compatibele formaten."
type: docs
weight: 35
url: /nl/java/com.groupdocs.editor.options/spreadsheeteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public class SpreadsheetEditOptions implements IEditOptions
```

Staat toe om aangepaste opties op te geven voor het bewerken van alle ondersteunde documenten
Spreadsheet (Excel‑compatibele) formaten

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [SpreadsheetEditOptions()](#SpreadsheetEditOptions--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getWorksheetIndex()](#getWorksheetIndex--) | Staat toe om de 0‑gebaseerde index van het werkblad (tabblad) van de invoer op te geven. |
Spreadsheet‑document dat naar HTML moet worden geconverteerd (zie
opmerkingen).
|
|  | [setWorksheetIndex(int value)](#setWorksheetIndex-int-) | Staat toe om de 0‑gebaseerde index van het werkblad (tabblad) van de invoer op te geven. |
Spreadsheet‑document dat naar HTML moet worden geconverteerd (zie
opmerkingen).
|
|  | [getExcludeHiddenWorksheets()](#getExcludeHiddenWorksheets--) | Staat toe om verborgen werkbladen in het invoer‑Spreadsheet‑document uit te sluiten, zodat |
ze volledig worden genegeerd.
|
|  | [setExcludeHiddenWorksheets(boolean value)](#setExcludeHiddenWorksheets-boolean-) | Staat toe om verborgen werkbladen in het invoer‑Spreadsheet‑document uit te sluiten, zodat |
ze volledig worden genegeerd.
|
|  | [getMergeEmptyAdjacentCells()](#getMergeEmptyAdjacentCells--) | Wanneer ingeschakeld, zullen de lege aangrenzende horizontale cellen uit het invoer‑Spreadsheet‑document |
worden weergegeven in het bewerkbare HTML‑document als samengevoegd tot één cel met de bijbehorende
colspan‑attribuut.
|
| [setMergeEmptyAdjacentCells(boolean value)](#setMergeEmptyAdjacentCells-boolean-) |  |
|  | [getExportBogusRowData()](#getExportBogusRowData--) | Wanneer ingeschakeld, bevat de HTML‑tabel in het gegenereerde HTML‑document een lege onderste verborgen rij met |
nul hoogte en lege cellen, waarbij alleen de breedte is gespecificeerd.
|
| [setExportBogusRowData(boolean value)](#setExportBogusRowData-boolean-) |  |
### SpreadsheetEditOptions() {#SpreadsheetEditOptions--}
```
public SpreadsheetEditOptions()
```


### getWorksheetIndex() {#getWorksheetIndex--}
```
public final int getWorksheetIndex()
```


Staat toe om de 0‑gebaseerde index van het werkblad (tabblad) van de invoer op te geven.
Spreadsheet‑document dat naar HTML moet worden geconverteerd (zie
opmerkingen).


*** ** * ** ***

De meeste Spreadsheet‑documenten ondersteunen het concept van tabbladen, d.w.z. ze kunnen meerdere tabbladen hebben. Aan de andere kant ondersteunt het HTML‑formaat zo'n structuur niet. Daarom kan GroupDocs.Editor naar HTML slechts één specifiek tabblad van het invoer‑document converteren, en deze optie maakt het mogelijk dit tabblad op te geven. De tabblad‑index is 0‑gebaseerd, negatieve waarden zijn verboden. Als de opgegeven index groter is dan het aantal tabbladen, wordt een uitzondering gegooid. Als het invoer‑Spreadsheet‑document slechts één tabblad bevat, wordt deze optie genegeerd. Standaardwaarde is 0 (eerste tabblad).

<br />



**Returns:**
int
### setWorksheetIndex(int value) {#setWorksheetIndex-int-}
```
public final void setWorksheetIndex(int value)
```


Staat toe om de 0‑gebaseerde index van het werkblad (tabblad) van de invoer op te geven.
Spreadsheet‑document dat naar HTML moet worden geconverteerd (zie
opmerkingen).


*** ** * ** ***

De meeste Spreadsheet‑documenten ondersteunen het concept van tabbladen, d.w.z. ze kunnen meerdere tabbladen hebben. Aan de andere kant ondersteunt het HTML‑formaat zo'n structuur niet. Daarom kan GroupDocs.Editor naar HTML slechts één specifiek tabblad van het invoer‑document converteren, en deze optie maakt het mogelijk dit tabblad op te geven. De tabblad‑index is 0‑gebaseerd, negatieve waarden zijn verboden. Als de opgegeven index groter is dan het aantal tabbladen, wordt een uitzondering gegooid. Als het invoer‑Spreadsheet‑document slechts één tabblad bevat, wordt deze optie genegeerd. Standaardwaarde is 0 (eerste tabblad).

<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getExcludeHiddenWorksheets() {#getExcludeHiddenWorksheets--}
```
public final boolean getExcludeHiddenWorksheets()
```


Staat toe om verborgen werkbladen in het invoer‑Spreadsheet‑document uit te sluiten, zodat
ze zullen volledig worden genegeerd. Standaard is false - verborgen werkbladen zijn
beschikbaar en worden normaal verwerkt.


*** ** * ** ***

Verschillende binaire Spreadsheet‑formaten (zoals XLSX) ondersteunen het concept van verborgen werkbladen (tabbladen). Een document van zo'n formaat, als het meer dan één werkblad heeft, kan extra verborgen werkbladen bevatten. Standaard zijn dergelijke verborgen werkbladen beschikbaar voor verwerking, maar met deze optie kunnen ze worden genegeerd, alsof deze verborgen werkbladen afwezig zijn en niet bestaan. Wanneer deze optie is ingeschakeld, kun je geen verborgen werkblad selecteren met de eigenschap ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))'.

<br />



**Returns:**
boolean
### setExcludeHiddenWorksheets(boolean value) {#setExcludeHiddenWorksheets-boolean-}
```
public final void setExcludeHiddenWorksheets(boolean value)
```


Staat toe om verborgen werkbladen in het invoer‑Spreadsheet‑document uit te sluiten, zodat
ze zullen volledig worden genegeerd. Standaard is false - verborgen werkbladen zijn
beschikbaar en worden normaal verwerkt.


*** ** * ** ***

Verschillende binaire Spreadsheet‑formaten (zoals XLSX) ondersteunen het concept van verborgen werkbladen (tabbladen). Een document van zo'n formaat, als het meer dan één werkblad heeft, kan extra verborgen werkbladen bevatten. Standaard zijn dergelijke verborgen werkbladen beschikbaar voor verwerking, maar met deze optie kunnen ze worden genegeerd, alsof deze verborgen werkbladen afwezig zijn en niet bestaan. Wanneer deze optie is ingeschakeld, kun je geen verborgen werkblad selecteren met de eigenschap ' WorksheetIndex (#getWorksheetIndex.getWorksheetIndex/#setWorksheetIndex(int).setWorksheetIndex(int))'.

<br />



**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getMergeEmptyAdjacentCells() {#getMergeEmptyAdjacentCells--}
```
public boolean getMergeEmptyAdjacentCells()
```


Wanneer ingeschakeld, zullen de lege aangrenzende horizontale cellen uit het invoer‑Spreadsheet‑document
worden weergegeven in het bewerkbare HTML‑document als samengevoegd tot één cel met de bijbehorende
colspan‑attribuut. Standaard is uitgeschakeld (false).


Standaard converteert GroupDocs.Editor een tabel van het invoer‑Spreadsheet‑document naar de uitvoer
HTML‑document door elke cel te behouden. Echter, de Spreadsheet‑documenten kunnen schaars zijn \\u2014 ze
kunnen een enorme hoeveelheid "lege gebieden" bevatten, waar veel cellen leeg zijn. Deze optie, wanneer
ingeschakeld, voegt zulke lege cellen samen tot één met een colspan‑attribuut in het TD‑element,
en kan daardoor de grootte van de geproduceerde HTML-markup aanzienlijk verkleinen.


**Returns:**
boolean
### setMergeEmptyAdjacentCells(boolean value) {#setMergeEmptyAdjacentCells-boolean-}
```
public void setMergeEmptyAdjacentCells(boolean value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### getExportBogusRowData() {#getExportBogusRowData--}
```
public boolean getExportBogusRowData()
```


Wanneer ingeschakeld, bevat de HTML‑tabel in het gegenereerde HTML‑document een lege onderste verborgen rij met
nul hoogte en lege cellen, waarbij alleen breedte is gespecificeerd. Deze rij met lege cellen bevat
exacte breedtewaarden voor elke kolom en verbetert de terugwaartse conversie van HTML naar Spreadsheet. Door
standaard is ingeschakeld (true).


**Returns:**
boolean
### setExportBogusRowData(boolean value) {#setExportBogusRowData-boolean-}
```
public void setExportBogusRowData(boolean value)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

