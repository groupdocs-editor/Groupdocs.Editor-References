---
title: "TextualDocumentInfo"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Representa los metadatos de un documento textual como XML, HTML o texto plano TXT"
type: docs
weight: 16
url: /es/nodejs-java/com.groupdocs.editor.metadata/textualdocumentinfo/
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
|  | [getSize()](#getSize--) | Devuelve el tamaño en bytes (no el número de caracteres) de este texto |
documento
|
|  | [isEncrypted()](#isEncrypted--) | Siempre devuelve 'false', ya que los documentos textuales no pueden ser encriptados. |
|
|  | [getEncoding()](#getEncoding--) | Devuelve la codificación presumiblemente detectada del documento de texto |
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


Devuelve el tamaño en bytes (no el número de caracteres) de este texto
documento


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Siempre devuelve 'false', ya que los documentos textuales no pueden ser encriptados.


**Returns:**
booleano
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Devuelve la codificación presumiblemente detectada del documento de texto


**Returns:**
java.nio.charset.Charset
