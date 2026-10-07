---
title: "WordProcessingDocumentInfo"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Representerar metadata för ett ordbehandlingsdokument."
type: docs
weight: 17
url: /sv/java/com.groupdocs.editor.metadata/wordprocessingdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class WordProcessingDocumentInfo implements IDocumentInfo
```

Representerar metadata för ett ordbehandlingsdokument.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WordProcessingDocumentInfo()](#WordProcessingDocumentInfo--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getFormat()](#getFormat--) | Returnerar ett format för detta WordProcessing-dokument |
|
|  | [getPageCount()](#getPageCount--) | Returnerar antalet sidor |
|
|  | [getSize()](#getSize--) | Returnerar storleken i byte för detta WordProcessing-dokument |
|
|  | [isEncrypted()](#isEncrypted--) | Avgör om detta specifika WordProcessing-dokument är krypterat och |
kräver lösenord för öppning
|
|  | [generatePreview(int pageIndex)](#generatePreview-int-) | Genererar och returnerar en förhandsgranskning av den valda sidan i form av en SVG-bild |
|
|  | [equals(WordProcessingDocumentInfo other)](#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-) | Bestämmer om den här instansen är lika med den andra som specificerats |
WordProcessingDocumentInfo-instans
|
### WordProcessingDocumentInfo() {#WordProcessingDocumentInfo--}
```
public WordProcessingDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final WordProcessingFormats getFormat()
```


Returnerar ett format för detta WordProcessing-dokument


**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Returnerar antalet sidor


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Returnerar storleken i byte för detta WordProcessing-dokument


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Avgör om detta specifika WordProcessing-dokument är krypterat och
kräver lösenord för öppning


**Returns:**
boolean
### generatePreview(int pageIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int pageIndex)
```


Genererar och returnerar en förhandsgranskning av den valda sidan i form av en SVG-bild


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | pageIndex | int | 0-baserat index för den önskade sidan. Kan inte vara mindre än 0, kan inte överstiga antalet sidor i detta WordProcessing-dokument. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the [SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) class

### equals(WordProcessingDocumentInfo other) {#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-}
```
public final boolean equals(WordProcessingDocumentInfo other)
```


Bestämmer om den här instansen är lika med den andra som specificerats
WordProcessingDocumentInfo-instans


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [WordProcessingDocumentInfo](../../com.groupdocs.editor.metadata/wordprocessingdocumentinfo) | Annan WordProcessingDocumentInfo-instans som bör jämföras för likhet med denna |
|

**Returns:**
boolean - Sant om de är lika, falskt om de är olika

