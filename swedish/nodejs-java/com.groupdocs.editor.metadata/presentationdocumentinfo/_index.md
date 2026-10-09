---
title: "PresentationDocumentInfo"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Representerar metadata för ett presentationsdokument."
type: docs
weight: 14
url: /sv/nodejs-java/com.groupdocs.editor.metadata/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class PresentationDocumentInfo implements IDocumentInfo
```

Representerar metadata för ett presentationsdokument.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getFormat()](#getFormat--) | Returnerar ett format för detta Presentation-dokument |
|
|  | [getPageCount()](#getPageCount--) | Returnerar antalet bilder i detta Presentation-dokument |
|
|  | [getSize()](#getSize--) | Returnerar storlek i byte för detta Presentation-dokument |
|
|  | [isEncrypted()](#isEncrypted--) | Indikerar om detta specifika Presentation-dokument är krypterat och kräver lösenord för att öppnas |
|
|  | [generatePreview(int slideIndex)](#generatePreview-int-) | Genererar och returnerar en förhandsgranskning av den valda bilden i form av en SVG-bild |
|
### getFormat() {#getFormat--}
```
public final PresentationFormats getFormat()
```


Returnerar ett format för detta Presentation-dokument


**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Returnerar antalet bilder i detta Presentation-dokument


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Returnerar storlek i byte för detta Presentation-dokument


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Indikerar om detta specifika Presentation-dokument är krypterat och kräver lösenord för att öppnas


**Returns:**
boolean
### generatePreview(int slideIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int slideIndex)
```


Genererar och returnerar en förhandsgranskning av den valda bilden i form av en SVG-bild


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | slideIndex | int | 0-baserat index för den önskade bilden. Kan inte vara mindre än 0, får inte överstiga antalet bilder i denna presentation. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the SvgImage class

