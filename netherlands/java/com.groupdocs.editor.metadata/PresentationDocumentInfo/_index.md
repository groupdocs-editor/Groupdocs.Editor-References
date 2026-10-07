---
title: "PresentationDocumentInfo"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt metadata van één Presentation‑document voor"
type: docs
weight: 14
url: /nl/java/com.groupdocs.editor.metadata/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class PresentationDocumentInfo implements IDocumentInfo
```

Stelt metadata van één Presentation‑document voor

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getFormat()](#getFormat--) | Retourneert een formaat van dit Presentatiedocument |
|
|  | [getPageCount()](#getPageCount--) | Retourneert het aantal dia's in dit Presentatiedocument |
|
|  | [getSize()](#getSize--) | Retourneert de grootte in bytes van dit Presentatiedocument |
|
|  | [isEncrypted()](#isEncrypted--) | Geeft aan of dit specifieke Presentatiedocument versleuteld is en een wachtwoord vereist om te openen |
|
|  | [generatePreview(int slideIndex)](#generatePreview-int-) | Genereert en retourneert een voorbeeld van de geselecteerde dia in de vorm van een SVG-afbeelding |
|
### getFormat() {#getFormat--}
```
public final PresentationFormats getFormat()
```


Retourneert een formaat van dit Presentatiedocument


**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Retourneert het aantal dia's in dit Presentatiedocument


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Retourneert de grootte in bytes van dit Presentatiedocument


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Geeft aan of dit specifieke Presentatiedocument versleuteld is en een wachtwoord vereist om te openen


**Returns:**
boolean
### generatePreview(int slideIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int slideIndex)
```


Genereert en retourneert een voorbeeld van de geselecteerde dia in de vorm van een SVG-afbeelding


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | slideIndex | int | 0-gebaseerde index van de gewenste dia. Kan niet kleiner zijn dan 0, mag het aantal dia's in deze presentatie niet overschrijden. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the SvgImage class

