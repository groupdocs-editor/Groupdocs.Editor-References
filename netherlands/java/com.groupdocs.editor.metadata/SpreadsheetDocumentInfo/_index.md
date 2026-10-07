---
title: "SpreadsheetDocumentInfo"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt metadata van één Spreadsheet‑document voor"
type: docs
weight: 15
url: /nl/java/com.groupdocs.editor.metadata/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class SpreadsheetDocumentInfo implements IDocumentInfo
```

Stelt metadata van één Spreadsheet‑document voor

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [SpreadsheetDocumentInfo()](#SpreadsheetDocumentInfo--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getFormat()](#getFormat--) | Geeft een formaat van dit Spreadsheet-document terug |
|
|  | [getPageCount()](#getPageCount--) | Geeft het aantal tabbladen terug |
|
|  | [getSize()](#getSize--) | Geeft de grootte in bytes van dit Spreadsheet-document terug |
|
|  | [isEncrypted()](#isEncrypted--) | Geeft aan of dit specifieke Spreadsheet-document versleuteld is en |
vereist een wachtwoord om te openen
|
|  | [generatePreview(int worksheetIndex)](#generatePreview-int-) | Genereert en geeft een voorbeeld van het geselecteerde werkblad terug in de vorm van een SVG-afbeelding |
|
|  | [equals(SpreadsheetDocumentInfo other)](#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-) | Bepaalt of deze instantie gelijk is aan de opgegeven andere |
SpreadsheetDocumentInfo instantie
|
### SpreadsheetDocumentInfo() {#SpreadsheetDocumentInfo--}
```
public SpreadsheetDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final SpreadsheetFormats getFormat()
```


Geeft een formaat van dit Spreadsheet-document terug


**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Geeft het aantal tabbladen terug


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Geeft de grootte in bytes van dit Spreadsheet-document terug


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Geeft aan of dit specifieke Spreadsheet-document versleuteld is en
vereist een wachtwoord om te openen


**Returns:**
boolean
### generatePreview(int worksheetIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int worksheetIndex)
```


Genereert en geeft een voorbeeld van het geselecteerde werkblad terug in de vorm van een SVG-afbeelding


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | worksheetIndex | int | 0-gebaseerde index van het gewenste werkblad. Mag niet kleiner zijn dan 0 en mag het aantal werkbladen in deze spreadsheet niet overschrijden. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the [SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) class

### equals(SpreadsheetDocumentInfo other) {#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-}
```
public final boolean equals(SpreadsheetDocumentInfo other)
```


Bepaalt of deze instantie gelijk is aan de opgegeven andere
SpreadsheetDocumentInfo instantie


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [SpreadsheetDocumentInfo](../../com.groupdocs.editor.metadata/spreadsheetdocumentinfo) | Andere SpreadsheetDocumentInfo instantie, die op gelijkheid met deze moet worden gecontroleerd |
|

**Returns:**
boolean - True als ze gelijk zijn, false als ze ongelijk zijn

