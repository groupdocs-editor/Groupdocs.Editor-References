---
title: "WordProcessingDocumentInfo"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Rappresenta i metadati di un documento di elaborazione testi"
type: docs
weight: 17
url: /it/java/com.groupdocs.editor.metadata/wordprocessingdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class WordProcessingDocumentInfo implements IDocumentInfo
```

Rappresenta i metadati di un documento di elaborazione testi

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WordProcessingDocumentInfo()](#WordProcessingDocumentInfo--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getFormat()](#getFormat--) | Restituisce un formato di questo documento WordProcessing |
|
|  | [getPageCount()](#getPageCount--) | Restituisce il numero di pagine |
|
|  | [getSize()](#getSize--) | Restituisce la dimensione in byte di questo documento WordProcessing |
|
|  | [isEncrypted()](#isEncrypted--) | Determina se questo specifico documento WordProcessing è crittografato e |
richiede una password per l'apertura
|
|  | [generatePreview(int pageIndex)](#generatePreview-int-) | Genera e restituisce un'anteprima della pagina selezionata sotto forma di immagine SVG |
|
|  | [equals(WordProcessingDocumentInfo other)](#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-) | Determina se questa istanza è uguale all'altra specificata |
istanza di WordProcessingDocumentInfo
|
### WordProcessingDocumentInfo() {#WordProcessingDocumentInfo--}
```
public WordProcessingDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final WordProcessingFormats getFormat()
```


Restituisce un formato di questo documento WordProcessing


**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Restituisce il numero di pagine


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Restituisce la dimensione in byte di questo documento WordProcessing


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Determina se questo specifico documento WordProcessing è crittografato e
richiede una password per l'apertura


**Returns:**
boolean
### generatePreview(int pageIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int pageIndex)
```


Genera e restituisce un'anteprima della pagina selezionata sotto forma di immagine SVG


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | pageIndex | int | Indice basato su 0 della pagina desiderata. Non può essere inferiore a 0, non può superare il numero di pagine in questo documento WordProcessing. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the [SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) class

### equals(WordProcessingDocumentInfo other) {#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-}
```
public final boolean equals(WordProcessingDocumentInfo other)
```


Determina se questa istanza è uguale all'altra specificata
istanza di WordProcessingDocumentInfo


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [WordProcessingDocumentInfo](../../com.groupdocs.editor.metadata/wordprocessingdocumentinfo) | Altra istanza di WordProcessingDocumentInfo, che dovrebbe essere confrontata per uguaglianza con questa |
|

**Returns:**
boolean - True se sono uguali, false se sono diversi

