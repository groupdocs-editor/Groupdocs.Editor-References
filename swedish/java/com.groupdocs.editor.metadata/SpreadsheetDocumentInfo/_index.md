---
title: "SpreadsheetDocumentInfo"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Representerar metadata för ett kalkylbladsdokument."
type: docs
weight: 15
url: /sv/java/com.groupdocs.editor.metadata/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class SpreadsheetDocumentInfo implements IDocumentInfo
```

Representerar metadata för ett kalkylbladsdokument.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [SpreadsheetDocumentInfo()](#SpreadsheetDocumentInfo--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getFormat()](#getFormat--) | Returnerar ett format för detta Spreadsheet-dokument |
|
|  | [getPageCount()](#getPageCount--) | Returnerar antalet flikar |
|
|  | [getSize()](#getSize--) | Returnerar storlek i byte för detta Spreadsheet-dokument |
|
|  | [isEncrypted()](#isEncrypted--) | Anger om detta specifika Spreadsheet-dokument är krypterat och |
kräver lösenord för öppning
|
|  | [generatePreview(int worksheetIndex)](#generatePreview-int-) | Genererar och returnerar en förhandsgranskning av det valda kalkylbladet i form av en SVG-bild |
|
|  | [equals(SpreadsheetDocumentInfo other)](#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-) | Bestämmer om den här instansen är lika med den andra som specificerats |
SpreadsheetDocumentInfo-instans
|
### SpreadsheetDocumentInfo() {#SpreadsheetDocumentInfo--}
```
public SpreadsheetDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final SpreadsheetFormats getFormat()
```


Returnerar ett format för detta Spreadsheet-dokument


**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Returnerar antalet flikar


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Returnerar storlek i byte för detta Spreadsheet-dokument


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Anger om detta specifika Spreadsheet-dokument är krypterat och
kräver lösenord för öppning


**Returns:**
boolean
### generatePreview(int worksheetIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int worksheetIndex)
```


Genererar och returnerar en förhandsgranskning av det valda kalkylbladet i form av en SVG-bild


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | worksheetIndex | int | 0-baserat index för det önskade kalkylbladet. Kan inte vara mindre än 0, får inte överstiga antalet kalkylblad i detta kalkylark. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the [SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) class

### equals(SpreadsheetDocumentInfo other) {#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-}
```
public final boolean equals(SpreadsheetDocumentInfo other)
```


Bestämmer om den här instansen är lika med den andra som specificerats
SpreadsheetDocumentInfo-instans


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [SpreadsheetDocumentInfo](../../com.groupdocs.editor.metadata/spreadsheetdocumentinfo) | Annat SpreadsheetDocumentInfo-instans, som bör kontrolleras för likhet med detta |
|

**Returns:**
boolean - Sant om de är lika, falskt om de är olika

