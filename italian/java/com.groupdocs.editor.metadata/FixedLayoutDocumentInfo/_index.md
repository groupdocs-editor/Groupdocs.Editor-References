---
title: "FixedLayoutDocumentInfo"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Rappresenta i metadati di un documento con formato a layout fisso come PDF o XPS"
type: docs
weight: 12
url: /it/java/com.groupdocs.editor.metadata/fixedlayoutdocumentinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class FixedLayoutDocumentInfo extends Struct<FixedLayoutDocumentInfo> implements IDocumentInfo
```

Rappresenta i metadati di un documento con formato a layout fisso come PDF o XPS

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FixedLayoutDocumentInfo()](#FixedLayoutDocumentInfo--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getFormat()](#getFormat--) | Restituisce un formato di questo documento a layout fisso |
|
|  | [getPageCount()](#getPageCount--) | Restituisce il numero di pagine |
|
|  | [getSize()](#getSize--) | Restituisce la dimensione in byte di questo documento a layout fisso |
|
|  | [isEncrypted()](#isEncrypted--) | Determina se questo specifico documento a layout fisso è crittografato e richiede una password per l'apertura |
|
|  | [equals(FixedLayoutDocumentInfo other)](#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-) | Determina se questa istanza è uguale all'altra istanza specificata di FixedLayoutDocumentInfo |
|
### FixedLayoutDocumentInfo() {#FixedLayoutDocumentInfo--}
```
public FixedLayoutDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Restituisce un formato di questo documento a layout fisso


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
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


Restituisce la dimensione in byte di questo documento a layout fisso


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Determina se questo specifico documento a layout fisso è crittografato e richiede una password per l'apertura


**Returns:**
boolean
### equals(FixedLayoutDocumentInfo other) {#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-}
```
public final boolean equals(FixedLayoutDocumentInfo other)
```


Determina se questa istanza è uguale all'altra istanza specificata di FixedLayoutDocumentInfo


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [FixedLayoutDocumentInfo](../../com.groupdocs.editor.metadata/fixedlayoutdocumentinfo) | Altra istanza di FixedLayoutDocumentInfo, che dovrebbe essere confrontata per uguaglianza con questa |
|

**Returns:**
boolean - True se sono uguali, false se sono diversi

