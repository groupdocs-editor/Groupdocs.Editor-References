---
title: "SpreadsheetDocumentInfo"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Representa los metadatos de un documento de Hoja de cálculo"
type: docs
weight: 15
url: /es/java/com.groupdocs.editor.metadata/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.metadata.IDocumentInfo](../../com.groupdocs.editor.metadata/idocumentinfo)
```
public class SpreadsheetDocumentInfo implements IDocumentInfo
```

Representa los metadatos de un documento de Hoja de cálculo

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SpreadsheetDocumentInfo()](#SpreadsheetDocumentInfo--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getFormat()](#getFormat--) | Devuelve un formato de este documento Spreadsheet |
|
|  | [getPageCount()](#getPageCount--) | Devuelve el número de pestañas |
|
|  | [getSize()](#getSize--) | Devuelve el tamaño en bytes de este documento Spreadsheet |
|
|  | [isEncrypted()](#isEncrypted--) | Indica si este documento Spreadsheet específico está cifrado y |
requiere contraseña para abrirlo
|
|  | [generatePreview(int worksheetIndex)](#generatePreview-int-) | Genera y devuelve una vista previa de la hoja de cálculo seleccionada en forma de imagen SVG |
|
|  | [equals(SpreadsheetDocumentInfo other)](#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-) | Determina si esta instancia es igual a la otra especificada |
Instancia de SpreadsheetDocumentInfo
|
### SpreadsheetDocumentInfo() {#SpreadsheetDocumentInfo--}
```
public SpreadsheetDocumentInfo()
```


### getFormat() {#getFormat--}
```
public final SpreadsheetFormats getFormat()
```


Devuelve un formato de este documento Spreadsheet


**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats)
### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Devuelve el número de pestañas


**Returns:**
int
### getSize() {#getSize--}
```
public final long getSize()
```


Devuelve el tamaño en bytes de este documento Spreadsheet


**Returns:**
long
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Indica si este documento Spreadsheet específico está cifrado y
requiere contraseña para abrirlo


**Returns:**
boolean
### generatePreview(int worksheetIndex) {#generatePreview-int-}
```
public final SvgImage generatePreview(int worksheetIndex)
```


Genera y devuelve una vista previa de la hoja de cálculo seleccionada en forma de imagen SVG


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | worksheetIndex | int | Índice basado en 0 de la hoja de cálculo deseada. No puede ser menor que 0, no puede exceder el número de hojas en esta hoja de cálculo. |
|

**Returns:**
[SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) - SVG image as the non-null instance of the [SvgImage](../../com.groupdocs.editor.htmlcss.resources.images.vector/svgimage) class

### equals(SpreadsheetDocumentInfo other) {#equals-com.groupdocs.editor.metadata.SpreadsheetDocumentInfo-}
```
public final boolean equals(SpreadsheetDocumentInfo other)
```


Determina si esta instancia es igual a la otra especificada
Instancia de SpreadsheetDocumentInfo


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [SpreadsheetDocumentInfo](../../com.groupdocs.editor.metadata/spreadsheetdocumentinfo) | Otra instancia de SpreadsheetDocumentInfo, que debe verificarse por igualdad con esta |
|

**Returns:**
booleano - Verdadero si son iguales, falso si son diferentes

