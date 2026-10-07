---
title: "FixedLayoutDocumentInfo"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Representa los metadatos de un documento con formato de diseño fijo como PDF o XPS"
type: docs
weight: 12
url: /es/java/com.groupdocs.editor.metadata/fixedlayoutdocumentinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class FixedLayoutDocumentInfo extends Struct<FixedLayoutDocumentInfo> implements IDocumentInfo
```

Representa los metadatos de un documento con formato de diseño fijo como PDF o XPS

## Constructores

| Constructor | Descripción |
| --- | --- |
| [FixedLayoutDocumentInfo()](#FixedLayoutDocumentInfo--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFormat()](#getFormat--) | Devuelve un formato de este documento de formato de diseño fijo |
|
|  | [getPageCount()](#getPageCount--) | Devuelve el número de páginas |
|
|  | [getSize()](#getSize--) | Devuelve el tamaño en bytes de este documento de formato de diseño fijo |
|
|  | [isEncrypted()](#isEncrypted--) | Determina si este documento de formato de diseño fijo específico está encriptado y requiere contraseña para abrirlo |
|
|  | [equals(FixedLayoutDocumentInfo other)](#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-) | Determina si esta instancia es igual a la otra instancia especificada de FixedLayoutDocumentInfo |
|
### FixedLayoutDocumentInfo() {#FixedLayoutDocumentInfo--}
```
public FixedLayoutDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Devuelve un formato de este documento de formato de diseño fijo


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
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


Devuelve el tamaño en bytes de este documento de formato de diseño fijo


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Determina si este documento de formato de diseño fijo específico está encriptado y requiere contraseña para abrirlo


**Returns:**
boolean
### equals(FixedLayoutDocumentInfo other) {#equals-com.groupdocs.editor.metadata.FixedLayoutDocumentInfo-}
```
public final boolean equals(FixedLayoutDocumentInfo other)
```


Determina si esta instancia es igual a la otra instancia especificada de FixedLayoutDocumentInfo


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [FixedLayoutDocumentInfo](../../com.groupdocs.editor.metadata/fixedlayoutdocumentinfo) | Otra instancia de FixedLayoutDocumentInfo, que debe comprobarse por igualdad con esta |
|

**Returns:**
booleano - Verdadero si son iguales, falso si son diferentes

