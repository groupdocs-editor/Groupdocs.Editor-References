---
title: "PresentationDocumentInfo"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Rappresenta i metadati di un documento di Presentazione"
type: docs
weight: 14
url: /it/nodejs-java/com.groupdocs.editor.metadata/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class PresentationDocumentInfo implements IDocumentInfo
```

Rappresenta i metadati di un documento di Presentazione

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getFormat()](#getFormat--) | Restituisce un formato di questo documento Presentation |
|
|  | [getPageCount()](#getPageCount--) | Restituisce il numero di diapositive in questo documento Presentation |
|
|  | [getSize()](#getSize--) | Restituisce la dimensione in byte di questo documento Presentation |
|
|  | [isEncrypted()](#isEncrypted--) | Indica se questo specifico documento Presentation è crittografato e richiede una password per l'apertura |
|
|  | [generatePreview(int slideIndex)](#generatePreview-int-) | Genera e restituisce un'anteprima della diapositiva selezionata sotto forma di immagine SVG |
|
### getFormat() {#getFormat--}
```
public final PresentationFormats getFormat()
```


Restituisce un formato di questo documento Presentation


**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Restituisce il numero di diapositive in questo documento Presentation


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Restituisce la dimensione in byte di questo documento Presentation


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Indica se questo specifico documento Presentation è crittografato e richiede una password per l'apertura


**Returns:**
boolean
### generatePreview(int slideIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int slideIndex)
```


Genera e restituisce un'anteprima della diapositiva selezionata sotto forma di immagine SVG


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | slideIndex | int | Indice basato su zero della diapositiva desiderata. Non può essere inferiore a 0, non può superare il numero di diapositive in questa presentazione. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the SvgImage class

