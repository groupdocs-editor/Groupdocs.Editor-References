---
title: "MarkdownDocumentInfo"
second_title: "GroupDocs.Editor för Java API-referens"
description: "Representerar metadata för ett Markdown-dokument."
type: docs
weight: 13
url: /sv/java/com.groupdocs.editor.metadata/markdowndocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class MarkdownDocumentInfo implements IDocumentInfo
```

Representerar metadata för ett Markdown-dokument.

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getFormat()](#getFormat--) | Returnerar ett format för detta Markdown-dokument \\u2014 alltid är |
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)
|
|  | [getPageCount()](#getPageCount--) | Returnerar antal sidor. |
|
|  | [getSize()](#getSize--) | Returnerar storlek i byte för detta Markdown-dokument |
|
|  | [isEncrypted()](#isEncrypted--) | Eftersom Markdown-dokument inte kan krypteras med lösenord, gör detta |
egenskap returnerar alltid 'false'
|
|  | [equals(MarkdownDocumentInfo other)](#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-) | Bestämmer om den här instansen är lika med den andra som specificerats |
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.
|
### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Returnerar ett format för detta Markdown-dokument \\u2014 alltid är
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Returnerar antal sidor. Markdown-dokument har vanligtvis inga fasta sidor
och därmed sidantal, så detta tal beräknas från standard sidstorlek
inställd på A4 i stående orientering.


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Returnerar storlek i byte för detta Markdown-dokument


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Eftersom Markdown-dokument inte kan krypteras med lösenord, gör detta
egenskap returnerar alltid 'false'


**Returns:**
boolean
### equals(MarkdownDocumentInfo other) {#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-}
```
public final boolean equals(MarkdownDocumentInfo other)
```


Bestämmer om den här instansen är lika med den andra som specificerats
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) | Annan [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instans som bör kontrolleras för likhet med denna |
|

**Returns:**
boolean - Sant om de är lika, falskt om de är olika

