---
title: "WordProcessingDocumentInfo"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Representa los metadatos de un documento de procesamiento de texto"
type: docs
weight: 17
url: /es/java/com.groupdocs.editor.metadata/wordprocessingdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class WordProcessingDocumentInfo implements IDocumentInfo
```

Representa los metadatos de un documento de procesamiento de texto

## Constructores

| Constructor | Descripción |
| --- | --- |
| [WordProcessingDocumentInfo()](#WordProcessingDocumentInfo--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFormat()](#getFormat--) | Devuelve un formato de este documento WordProcessing |
|
|  | [getPageCount()](#getPageCount--) | Devuelve el número de páginas |
|
|  | [getSize()](#getSize--) | Devuelve el tamaño en bytes de este documento WordProcessing |
|
|  | [isEncrypted()](#isEncrypted--) | Determina si este documento WordProcessing específico está encriptado y |
requiere contraseña para abrirlo
|
|  | [generatePreview(int pageIndex)](#generatePreview-int-) | Genera y devuelve una vista previa de la página seleccionada en forma de imagen SVG |
|
|  | [equals(WordProcessingDocumentInfo other)](#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-) | Determina si esta instancia es igual a la otra especificada |
Instancia de WordProcessingDocumentInfo
|
### WordProcessingDocumentInfo() {#WordProcessingDocumentInfo--}
```
public WordProcessingDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final WordProcessingFormats getFormat()
```


Devuelve un formato de este documento WordProcessing


**Returns:**
[WordProcessingFormats](../../com.groupdocs.editor.formats/wordprocessingformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Devuelve el número de páginas


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Devuelve el tamaño en bytes de este documento WordProcessing


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Determina si este documento WordProcessing específico está encriptado y
requiere contraseña para abrirlo


**Returns:**
boolean
### generatePreview(int pageIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int pageIndex)
```


Genera y devuelve una vista previa de la página seleccionada en forma de imagen SVG


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | pageIndex | int | Índice basado en 0 de la página deseada. No puede ser menor que 0, no puede exceder el número de páginas de este documento WordProcessing. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the [SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) class

### equals(WordProcessingDocumentInfo other) {#equals-com.groupdocs.editor.metadata.WordProcessingDocumentInfo-}
```
public final boolean equals(WordProcessingDocumentInfo other)
```


Determina si esta instancia es igual a la otra especificada
Instancia de WordProcessingDocumentInfo


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [WordProcessingDocumentInfo](../../com.groupdocs.editor.metadata/wordprocessingdocumentinfo) | Otra instancia de WordProcessingDocumentInfo, que debe comprobarse por igualdad con esta |
|

**Returns:**
booleano - Verdadero si son iguales, falso si son diferentes

