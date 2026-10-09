---
title: "TextualDocumentInfo"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Rappresenta i metadati di un documento testuale come XML, HTML o testo semplice TXT"
type: docs
weight: 16
url: /it/nodejs-java/com.groupdocs.editor.metadata/textualdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class TextualDocumentInfo implements IDocumentInfo
```

Rappresenta i metadati di un documento testuale come XML, HTML o testo semplice
(TXT)

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getFormat()](#getFormat--) | Restituisce un formato di questo documento testuale. |
|
|  | [getPageCount()](#getPageCount--) | Restituisce sempre 1 |
|
|  | [getSize()](#getSize--) | Restituisce la dimensione in byte (non il numero di caratteri) di questo documento testuale |
documento
|
|  | [isEncrypted()](#isEncrypted--) | Restituisce sempre 'false', poiché i documenti testuali non possono essere crittografati. |
|
|  | [getEncoding()](#getEncoding--) | Restituisce la codifica presumibilmente rilevata del documento di testo |
|
### getFormat() {#getFormat--}
```
public final TextualFormats getFormat()
```


Restituisce un formato di questo documento testuale. Potrebbe non essere corretto al 100% in
alcuni casi.


**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Restituisce sempre 1


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Restituisce la dimensione in byte (non il numero di caratteri) di questo documento testuale
documento


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Restituisce sempre 'false', poiché i documenti testuali non possono essere crittografati.


**Returns:**
boolean
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Restituisce la codifica presumibilmente rilevata del documento di testo


**Returns:**
java.nio.charset.Charset
