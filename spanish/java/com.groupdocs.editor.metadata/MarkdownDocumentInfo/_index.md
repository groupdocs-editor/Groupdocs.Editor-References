---
title: "MarkdownDocumentInfo"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Representa los metadatos de un documento Markdown"
type: docs
weight: 13
url: /es/java/com.groupdocs.editor.metadata/markdowndocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class MarkdownDocumentInfo implements IDocumentInfo
```

Representa los metadatos de un documento Markdown

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFormat()](#getFormat--) | Devuelve un formato de este documento Markdown \u2014 siempre es |
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)
|
|  | [getPageCount()](#getPageCount--) | Devuelve el número de páginas. |
|
|  | [getSize()](#getSize--) | Devuelve el tamaño en bytes de este documento Markdown |
|
|  | [isEncrypted()](#isEncrypted--) | Porque los documentos Markdown no pueden ser encriptados con contraseña, este |
propiedad siempre devuelve 'false'
|
|  | [equals(MarkdownDocumentInfo other)](#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-) | Determina si esta instancia es igual a la otra especificada |
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.
|
### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Devuelve un formato de este documento Markdown \u2014 siempre es
[TextualFormats.Md](../../com.groupdocs.editor.formats/textualformats#Md)


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Devuelve el número de páginas. Los documentos Markdown generalmente no tienen páginas fijas
y por lo tanto el recuento de páginas, así que este número se calcula a partir del tamaño de página estándar
establecido a A4 en orientación vertical.


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Devuelve el tamaño en bytes de este documento Markdown


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Porque los documentos Markdown no pueden ser encriptados con contraseña, este
propiedad siempre devuelve 'false'


**Returns:**
boolean
### equals(MarkdownDocumentInfo other) {#equals-com.groupdocs.editor.metadata.MarkdownDocumentInfo-}
```
public final boolean equals(MarkdownDocumentInfo other)
```


Determina si esta instancia es igual a la otra especificada
[MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) instance.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo) | Otra instancia de [MarkdownDocumentInfo](../../com.groupdocs.editor.metadata/markdowndocumentinfo), que debe ser comprobada por igualdad con esta |
|

**Returns:**
booleano - Verdadero si son iguales, falso si son diferentes

