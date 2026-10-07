---
title: "EbookDocumentInfo"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Rappresenta i metadati di un documento EBook"
type: docs
weight: 10
url: /it/java/com.groupdocs.editor.metadata/ebookdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EbookDocumentInfo implements IDocumentInfo
```

Rappresenta i metadati di un documento EBook

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EbookDocumentInfo()](#EbookDocumentInfo--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getFormat()](#getFormat--) | Restituisce un formato di questo documento |
|
|  | [getPageCount()](#getPageCount--) | Restituisce il numero di pagine nel caso di MOBI o AZW3 o il numero di capitoli nel caso di ePub. |
|
|  | [getSize()](#getSize--) | Restituisce la dimensione in byte di questo documento eBook |
|
|  | [isEncrypted()](#isEncrypted--) | Poiché i documenti eBook non possono essere crittografati con password, questa proprietà restituisce sempre 'false' |
|
|  | [equals(EbookDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-) | Determina se questa istanza è uguale all'altra istanza specificata di EbookDocumentInfo |
|
### EbookDocumentInfo() {#EbookDocumentInfo--}
```
public EbookDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Restituisce un formato di questo documento


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Restituisce il numero di pagine nel caso di MOBI o AZW3 o il numero di capitoli nel caso di ePub.

<br />

*** ** * ** ***

I documenti eBook di solito non hanno pagine fisse e quindi non hanno un conteggio delle pagine. Nel caso di ePub è possibile calcolare il numero di capitoli. Tuttavia, i formati MOBI e AZW3 non hanno nemmeno capitoli, quindi questo numero è calcolato a partire dalla dimensione standard della pagina impostata su A4 in orientamento verticale.

<br />



**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Restituisce la dimensione in byte di questo documento eBook


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Poiché i documenti eBook non possono essere crittografati con password, questa proprietà restituisce sempre 'false'


**Returns:**
boolean
### equals(EbookDocumentInfo other) {#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-}
```
public final boolean equals(EbookDocumentInfo other)
```


Determina se questa istanza è uguale all'altra istanza specificata di EbookDocumentInfo


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [EbookDocumentInfo](../../com.groupdocs.editor.metadata/ebookdocumentinfo) | Altra istanza di EbookDocumentInfo, che dovrebbe essere verificata per l'uguaglianza con questa |
|

**Returns:**
boolean - True se sono uguali, false se sono diversi

