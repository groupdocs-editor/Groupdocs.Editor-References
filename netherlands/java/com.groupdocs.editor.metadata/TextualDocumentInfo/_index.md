---
title: "TextualDocumentInfo"
second_title: "GroupDocs.Editor for Java API-referentie"
description: "Stelt metadata van één tekstueel document voor, zoals XML, HTML of platte tekst TXT"
type: docs
weight: 16
url: /nl/java/com.groupdocs.editor.metadata/textualdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class TextualDocumentInfo implements IDocumentInfo
```

Stelt metadata van één tekstueel document voor, zoals XML, HTML of platte tekst
(TXT)

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getFormat()](#getFormat--) | Geeft een formaat van dit tekstuele document terug. |
|
|  | [getPageCount()](#getPageCount--) | Geeft altijd 1 terug |
|
|  | [getSize()](#getSize--) | Geeft de grootte in bytes (niet het aantal tekens) van dit tekstuele |
document
|
|  | [isEncrypted()](#isEncrypted--) | Geeft altijd 'false' terug, omdat tekstuele documenten niet versleuteld kunnen worden. |
|
|  | [getEncoding()](#getEncoding--) | Geeft de vermoedelijke gedetecteerde codering van het tekstdocument terug |
|
### getFormat() {#getFormat--}
```
public final TextualFormats getFormat()
```


Geeft een formaat van dit tekstuele document terug. Mogelijk niet 100% correct in
sommige gevallen.


**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Geeft altijd 1 terug


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Geeft de grootte in bytes (niet het aantal tekens) van dit tekstuele
document


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Geeft altijd 'false' terug, omdat tekstuele documenten niet versleuteld kunnen worden.


**Returns:**
boolean
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Geeft de vermoedelijke gedetecteerde codering van het tekstdocument terug


**Returns:**
java.nio.charset.Charset
