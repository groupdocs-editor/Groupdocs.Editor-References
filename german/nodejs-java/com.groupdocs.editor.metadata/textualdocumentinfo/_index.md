---
title: "TextualDocumentInfo"
second_title: "GroupDocs.Editor für Node.js über Java API-Referenz"
description: "Stellt Metadaten eines Textdokuments dar, wie XML, HTML oder Klartext TXT"
type: docs
weight: 16
url: /de/nodejs-java/com.groupdocs.editor.metadata/textualdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class TextualDocumentInfo implements IDocumentInfo
```

Stellt Metadaten eines Textdokuments dar, wie XML, HTML oder Klartext
(TXT)

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getFormat()](#getFormat--) | Gibt ein Format dieses Textdokuments zurück. |
|
|  | [getPageCount()](#getPageCount--) | Gibt immer 1 zurück |
|
|  | [getSize()](#getSize--) | Gibt die Größe in Bytes (nicht die Anzahl der Zeichen) dieses Textes zurück |
Dokument
|
|  | [isEncrypted()](#isEncrypted--) | Gibt immer 'false' zurück, da Textdokumente nicht verschlüsselt werden können. |
|
|  | [getEncoding()](#getEncoding--) | Gibt die erkannte, vermutlich korrekte Kodierung des Textdokuments zurück |
|
### getFormat() {#getFormat--}
```
public final TextualFormats getFormat()
```


Gibt ein Format dieses Textdokuments zurück. Kann in
einigen Fällen nicht zu 100% korrekt sein.


**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Gibt immer 1 zurück


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Gibt die Größe in Bytes (nicht die Anzahl der Zeichen) dieses Textes zurück
Dokument


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Gibt immer 'false' zurück, da Textdokumente nicht verschlüsselt werden können.


**Returns:**
boolesch
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Gibt die erkannte, vermutlich korrekte Kodierung des Textdokuments zurück


**Returns:**
java.nio.charset.Charset
