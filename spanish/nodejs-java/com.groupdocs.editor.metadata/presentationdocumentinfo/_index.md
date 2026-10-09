---
title: "PresentationDocumentInfo"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Representa los metadatos de un documento de presentación"
type: docs
weight: 14
url: /es/nodejs-java/com.groupdocs.editor.metadata/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class PresentationDocumentInfo implements IDocumentInfo
```

Representa los metadatos de un documento de presentación

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFormat()](#getFormat--) | Devuelve un formato de este documento Presentation |
|
|  | [getPageCount()](#getPageCount--) | Devuelve el número de diapositivas de este documento Presentation |
|
|  | [getSize()](#getSize--) | Devuelve el tamaño en bytes de este documento Presentation |
|
|  | [isEncrypted()](#isEncrypted--) | Indica si este documento de Presentation específico está cifrado y requiere contraseña para abrirse |
|
|  | [generatePreview(int slideIndex)](#generatePreview-int-) | Genera y devuelve una vista previa de la diapositiva seleccionada en forma de imagen SVG |
|
### getFormat() {#getFormat--}
```
public final PresentationFormats getFormat()
```


Devuelve un formato de este documento Presentation


**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Devuelve el número de diapositivas de este documento Presentation


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Devuelve el tamaño en bytes de este documento Presentation


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Indica si este documento de Presentation específico está cifrado y requiere contraseña para abrirse


**Returns:**
booleano
### generatePreview(int slideIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int slideIndex)
```


Genera y devuelve una vista previa de la diapositiva seleccionada en forma de imagen SVG


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | slideIndex | int | Índice basado en 0 de la diapositiva deseada. No puede ser menor que 0, no puede exceder el número de diapositivas en esta presentación. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the SvgImage class

