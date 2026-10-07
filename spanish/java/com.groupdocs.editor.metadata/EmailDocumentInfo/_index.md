---
title: "EmailDocumentInfo"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Representa los metadatos de un documento de correo electrónico de cualquier formato de correo soportado"
type: docs
weight: 11
url: /es/java/com.groupdocs.editor.metadata/emaildocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EmailDocumentInfo implements IDocumentInfo
```

Representa los metadatos de un documento de correo electrónico de cualquier formato de correo soportado

## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmailDocumentInfo()](#EmailDocumentInfo--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFormat()](#getFormat--) | Devuelve un formato de este documento de correo electrónico |
|
|  | [getPageCount()](#getPageCount--) | Siempre devuelve 1, porque los documentos de correo electrónico no tienen vista paginada |
|
|  | [getSize()](#getSize--) | Devuelve el tamaño en bytes de este documento de correo electrónico |
|
|  | [isEncrypted()](#isEncrypted--) | Porque los documentos de correo electrónico no pueden ser encriptados con contraseña, esta propiedad siempre devuelve 'false' |
|
|  | [equals(EmailDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-) | Determina si esta instancia es igual a la otra instancia especificada de EmailDocumentInfo |
|
### EmailDocumentInfo() {#EmailDocumentInfo--}
```
public EmailDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Devuelve un formato de este documento de correo electrónico


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Siempre devuelve 1, porque los documentos de correo electrónico no tienen vista paginada


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Devuelve el tamaño en bytes de este documento de correo electrónico


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Porque los documentos de correo electrónico no pueden ser encriptados con contraseña, esta propiedad siempre devuelve 'false'


**Returns:**
boolean
### equals(EmailDocumentInfo other) {#equals-com.groupdocs.editor.metadata.EmailDocumentInfo-}
```
public final boolean equals(EmailDocumentInfo other)
```


Determina si esta instancia es igual a la otra instancia especificada de EmailDocumentInfo


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [EmailDocumentInfo](../../com.groupdocs.editor.metadata/emaildocumentinfo) | Otra instancia de EmailDocumentInfo, que debe verificarse por igualdad con esta |
|

**Returns:**
booleano - Verdadero si son iguales, falso si son diferentes

