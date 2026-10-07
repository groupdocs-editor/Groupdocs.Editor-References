---
title: "SpreadsheetDocumentInfo"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Rappresenta i metadati di un documento di Foglio di calcolo"
type: docs
weight: 15
url: /it/java/com.groupdocs.editor.metadata/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class SpreadsheetDocumentInfo implements IDocumentInfo
```

Rappresenta i metadati di un documento di Foglio di calcolo

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SpreadsheetDocumentInfo()](#SpreadsheetDocumentInfo--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getFormat()](#getFormat--) | Restituisce un formato di questo documento Spreadsheet |
|
|  | [getPageCount()](#getPageCount--) | Restituisce il numero di schede |
|
|  | [getSize()](#getSize--) | Restituisce la dimensione in byte di questo documento Spreadsheet |
|
|  | [isEncrypted()](#isEncrypted--) | Indica se questo specifico documento Spreadsheet è crittografato e |
richiede una password per l'apertura
|
|  | [generatePreview(int worksheetIndex)](#generatePreview-int-) | Genera e restituisce un'anteprima del foglio di lavoro selezionato sotto forma di immagine SVG |
|
|  | [equals(SpreadsheetDocumentInfo other)](#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-) | Determina se questa istanza è uguale all'altra specificata |
istanza di SpreadsheetDocumentInfo
|
### SpreadsheetDocumentInfo() {#SpreadsheetDocumentInfo--}
```
public SpreadsheetDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final SpreadsheetFormats getFormat()
```


Restituisce un formato di questo documento Spreadsheet


**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Restituisce il numero di schede


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Restituisce la dimensione in byte di questo documento Spreadsheet


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Indica se questo specifico documento Spreadsheet è crittografato e
richiede una password per l'apertura


**Returns:**
boolean
### generatePreview(int worksheetIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int worksheetIndex)
```


Genera e restituisce un'anteprima del foglio di lavoro selezionato sotto forma di immagine SVG


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | worksheetIndex | int | Indice basato su 0 del foglio di lavoro desiderato. Non può essere inferiore a 0, non può superare il numero di fogli di lavoro in questo spreadsheet. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the [SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) class

### equals(SpreadsheetDocumentInfo other) {#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-}
```
public final boolean equals(SpreadsheetDocumentInfo other)
```


Determina se questa istanza è uguale all'altra specificata
istanza di SpreadsheetDocumentInfo


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [SpreadsheetDocumentInfo](../../com.groupdocs.editor.metadata/spreadsheetdocumentinfo) | Altra istanza di SpreadsheetDocumentInfo, che dovrebbe essere verificata per uguaglianza con questa |
|

**Returns:**
boolean - True se sono uguali, false se sono diversi

