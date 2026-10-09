---
title: "EbookDocumentInfo"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Representa los metadatos de un documento EBook"
type: docs
weight: 10
url: /es/nodejs-java/com.groupdocs.editor.metadata/ebookdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class EbookDocumentInfo implements IDocumentInfo
```

Representa los metadatos de un documento EBook

## Constructores

| Constructor | Descripción |
| --- | --- |
| [EbookDocumentInfo()](#EbookDocumentInfo--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFormat()](#getFormat--) | Devuelve un formato de este documento |
|
|  | [getPageCount()](#getPageCount--) | Devuelve el número de páginas en el caso de MOBI o AZW3 o el número de capítulos en el caso de ePub. |
|
|  | [getSize()](#getSize--) | Devuelve el tamaño en bytes de este documento eBook |
|
|  | [isEncrypted()](#isEncrypted--) | Debido a que los documentos eBook no pueden ser encriptados con contraseña, esta propiedad siempre devuelve 'false' |
|
|  | [equals(EbookDocumentInfo other)](#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-) | Determina si esta instancia es igual a la otra instancia especificada de EbookDocumentInfo |
|
### EbookDocumentInfo() {#EbookDocumentInfo--}
```
public EbookDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final DocumentFormatBase getFormat()
```


Devuelve un formato de este documento


**Returns:**
[DocumentFormatBase](../../com.groupdocs.editor.formats.abstraction/documentformatbase)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Devuelve el número de páginas en el caso de MOBI o AZW3 o el número de capítulos en el caso de ePub.

<br />

*** ** * ** ***

Los documentos eBook normalmente no tienen páginas fijas y, por lo tanto, recuento de páginas. En el caso de ePub es posible calcular el número de capítulos. Sin embargo, los formatos MOBI y AZW3 tampoco tienen capítulos, por lo que este número se calcula a partir del tamaño de página estándar establecido en A4 en orientación vertical.

<br />



**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Devuelve el tamaño en bytes de este documento eBook


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Debido a que los documentos eBook no pueden ser encriptados con contraseña, esta propiedad siempre devuelve 'false'


**Returns:**
booleano
### equals(EbookDocumentInfo other) {#equals-com.groupdocs.editor.metadata.EbookDocumentInfo-}
```
public final boolean equals(EbookDocumentInfo other)
```


Determina si esta instancia es igual a la otra instancia especificada de EbookDocumentInfo


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [EbookDocumentInfo](../../com.groupdocs.editor.metadata/ebookdocumentinfo) | Otra instancia de EbookDocumentInfo, que debe ser verificada por igualdad con esta |
|

**Returns:**
boolean - Verdadero si son iguales, falso si son diferentes

