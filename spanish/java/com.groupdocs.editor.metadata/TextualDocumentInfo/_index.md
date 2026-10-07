---
title: "TextualDocumentInfo"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Representa los metadatos de un documento textual como XML, HTML o texto plano TXT"
type: docs
weight: 16
url: /es/java/com.groupdocs.editor.metadata/textualdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class TextualDocumentInfo implements IDocumentInfo
```

Representa los metadatos de un documento textual como XML, HTML o texto plano
(TXT)

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFormat()](#getFormat--) | Devuelve un formato de este documento textual. |
|
|  | [getPageCount()](#getPageCount--) | Siempre devuelve 1 |
|
|  | [getSize()](#getSize--) | Devuelve el tamaño en bytes (no el número de caracteres) de este textual |
documento
|
|  | [isEncrypted()](#isEncrypted--) | Siempre devuelve 'false', ya que los documentos textuales no pueden ser cifrados. |
|
|  | [getEncoding()](#getEncoding--) | Devuelve la codificación detectada presumiblemente del documento de texto |
|
### getFormat() {#getFormat--}
```
public final TextualFormats getFormat()
```


Devuelve un formato de este documento textual. Puede no ser 100% correcto en
algunos casos.


**Returns:**
[TextualFormats](../../com.groupdocs.editor.formats/textualformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Siempre devuelve 1


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Devuelve el tamaño en bytes (no el número de caracteres) de este textual
documento


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Siempre devuelve 'false', ya que los documentos textuales no pueden ser cifrados.


**Returns:**
boolean
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Devuelve la codificación detectada presumiblemente del documento de texto


**Returns:**
java.nio.charset.Charset
