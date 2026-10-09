---
title: "TextualDocumentInfo"
second_title: "GroupDocs.Editor för Node.js via Java API-referens"
description: "Representerar metadata för ett textdokument som XML, HTML eller vanlig text TXT"
type: docs
weight: 16
url: /sv/nodejs-java/com.groupdocs.editor.metadata/textualdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class TextualDocumentInfo implements IDocumentInfo
```

Representerar metadata för ett textdokument som XML, HTML eller vanlig text
(TXT)

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getFormat()](#getFormat--) | Returnerar ett format för detta textdokument. |
|
|  | [getPageCount()](#getPageCount--) | Returnerar alltid 1 |
|
|  | [getSize()](#getSize--) | Returnerar storlek i byte (inte antalet tecken) för detta text |
dokument
|
|  | [isEncrypted()](#isEncrypted--) | Returnerar alltid 'false', eftersom textdokument inte kan krypteras. |
|
|  | [getEncoding()](#getEncoding--) | Returnerar det upptäckta sannolika kodningen för textdokumentet |
|
### getFormat() {#getFormat--}
```
public final TextualFormats getFormat()
```


Returnerar ett format för detta textdokument. Kan vara inte 100 % korrekt i
vissa fall.


**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Returnerar alltid 1


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Returnerar storlek i byte (inte antalet tecken) för detta text
dokument


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Returnerar alltid 'false', eftersom textdokument inte kan krypteras.


**Returns:**
boolean
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Returnerar det upptäckta sannolika kodningen för textdokumentet


**Returns:**
java.nio.charset.Charset
