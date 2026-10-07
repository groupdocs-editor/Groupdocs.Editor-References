---
title: "WordProcessingDocumentInfo"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt metadata van één WordProcessing‑document voor"
type: docs
weight: 17
url: /nl/java/com.groupdocs.editor.metadata/wordprocessingdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class WordProcessingDocumentInfo implements IDocumentInfo
```

Stelt metadata van één WordProcessing‑document voor

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [WordProcessingDocumentInfo()](#WordProcessingDocumentInfo--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getFormat()](#getFormat--) | Geeft een formaat van dit WordProcessing-document terug |
|
|  | [getPageCount()](#getPageCount--) | Geeft het aantal pagina's terug |
|
|  | [getSize()](#getSize--) | Geeft de grootte in bytes van dit WordProcessing-document terug |
|
|  | [isEncrypted()](#isEncrypted--) | Bepaalt of dit specifieke WordProcessing-document versleuteld is en |
vereist een wachtwoord om te openen
|
|  | [generatePreview(int pageIndex)](#generatePreview-int-) | Genereert en geeft een voorbeeld van de geselecteerde pagina in de vorm van een SVG-afbeelding terug |
|
|  | [equals(WordProcessingDocumentInfo other)](#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-) | Bepaalt of deze instantie gelijk is aan de opgegeven andere |
WordProcessingDocumentInfo instantie
|
### WordProcessingDocumentInfo() {#WordProcessingDocumentInfo--}
```
public WordProcessingDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final WordProcessingFormats getFormat()
```


Geeft een formaat van dit WordProcessing-document terug


**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Geeft het aantal pagina's terug


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Geeft de grootte in bytes van dit WordProcessing-document terug


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Bepaalt of dit specifieke WordProcessing-document versleuteld is en
vereist een wachtwoord om te openen


**Returns:**
boolean
### generatePreview(int pageIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int pageIndex)
```


Genereert en geeft een voorbeeld van de geselecteerde pagina in de vorm van een SVG-afbeelding terug


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | pageIndex | int | 0-gebaseerde index van de gewenste pagina. Kan niet kleiner zijn dan 0, mag het aantal pagina's in dit WordProcessing-document niet overschrijden. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the [SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) class

### equals(WordProcessingDocumentInfo other) {#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-}
```
public final boolean equals(WordProcessingDocumentInfo other)
```


Bepaalt of deze instantie gelijk is aan de opgegeven andere
WordProcessingDocumentInfo instantie


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | other | [WordProcessingDocumentInfo](../../com.groupdocs.editor.metadata/wordprocessingdocumentinfo) | Andere WordProcessingDocumentInfo‑instantie, die op gelijkheid met deze moet worden gecontroleerd |
|

**Returns:**
boolean - True als ze gelijk zijn, false als ze ongelijk zijn

