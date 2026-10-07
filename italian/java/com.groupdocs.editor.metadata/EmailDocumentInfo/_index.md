---
title: "EmailDocumentInfo"
second_title: "GroupDocs.Editor per Java Riferimento API"
description: "Rappresenta i metadati di un documento email di qualsiasi formato email supportato"
type: docs
weight: 11
url: /it/java/com.groupdocs.editor.metadata/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EmailDocumentInfo implements IDocumentInfo
```

Rappresenta i metadati di un documento email di qualsiasi formato email supportato

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmailDocumentInfo()](#EmailDocumentInfo--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getFormat()](#getFormat--) | Restituisce un formato di questo documento email |
|
|  | [getPageCount()](#getPageCount--) | Restituisce sempre 1, perché i documenti email non hanno una visualizzazione paginata |
|
|  | [getSize()](#getSize--) | Restituisce la dimensione in byte di questo documento email |
|
|  | [isEncrypted()](#isEncrypted--) | Poiché i documenti email non possono essere crittografati con password, questa proprietà restituisce sempre 'false' |
|
|  | [equals(EmailDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-) | Determina se questa istanza è uguale all'altra istanza specificata di EmailDocumentInfo |
|
### EmailDocumentInfo() {#EmailDocumentInfo--}
```
public EmailDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Restituisce un formato di questo documento email


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Restituisce sempre 1, perché i documenti email non hanno una visualizzazione paginata


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Restituisce la dimensione in byte di questo documento email


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Poiché i documenti email non possono essere crittografati con password, questa proprietà restituisce sempre 'false'


**Returns:**
boolean
### equals(EmailDocumentInfo other) {#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-}
```
public final boolean equals(EmailDocumentInfo other)
```


Determina se questa istanza è uguale all'altra istanza specificata di EmailDocumentInfo


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [EmailDocumentInfo](../../com.groupdocs.editor.metadata/emaildocumentinfo) | Altra istanza di EmailDocumentInfo, che dovrebbe essere verificata per uguaglianza con questa |
|

**Returns:**
boolean - True se sono uguali, false se sono diversi

