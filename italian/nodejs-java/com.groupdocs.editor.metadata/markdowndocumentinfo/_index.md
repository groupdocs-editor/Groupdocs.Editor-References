---
title: "MarkdownDocumentInfo"
second_title: "Riferimento API di GroupDocs.Editor per Node.js via Java"
description: "Rappresenta i metadati di un documento Markdown"
type: docs
weight: 13
url: /it/nodejs-java/com.groupdocs.editor.metadata/markdowndocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class MarkdownDocumentInfo implements IDocumentInfo
```

Rappresenta i metadati di un documento Markdown

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getFormat()](#getFormat--) | Restituisce il formato di questo documento Markdown \\u2014 è sempre |
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)
|
|  | [getPageCount()](#getPageCount--) | Restituisce il numero di pagine. |
|
|  | [getSize()](#getSize--) | Restituisce la dimensione in byte di questo documento Markdown |
|
|  | [isEncrypted()](#isEncrypted--) | Poiché i documenti Markdown non possono essere crittografati con password, questo |
proprietà restituisce sempre 'false'
|
|  | [equals(MarkdownDocumentInfo other)](#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-) | Determina se questa istanza è uguale all'altra specificata |
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.
|
### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Restituisce il formato di questo documento Markdown \\u2014 è sempre
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Restituisce il numero di pagine. I documenti Markdown solitamente non hanno pagine fisse
e quindi il conteggio delle pagine, così questo numero è calcolato dalla dimensione standard della pagina
impostato su A4 in orientamento verticale.


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Restituisce la dimensione in byte di questo documento Markdown


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Poiché i documenti Markdown non possono essere crittografati con password, questo
proprietà restituisce sempre 'false'


**Returns:**
boolean
### equals(MarkdownDocumentInfo other) {#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-}
```
public final boolean equals(MarkdownDocumentInfo other)
```


Determina se questa istanza è uguale all'altra specificata
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | other | [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) | Altra istanza di [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) che dovrebbe essere confrontata per uguaglianza con questa |
|

**Returns:**
boolean - True se sono uguali, false se sono diversi

