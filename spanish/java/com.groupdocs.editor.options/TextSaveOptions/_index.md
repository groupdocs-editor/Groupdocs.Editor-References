---
title: "TextSaveOptions"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Permite especificar opciones personalizadas para generar y guardar documentos de texto plano TXT"
type: docs
weight: 41
url: /es/java/com.groupdocs.editor.options/textsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class TextSaveOptions implements ISaveOptions
```

Permite especificar opciones personalizadas para generar y guardar texto plano (TXT)
documentos

## Constructores

| Constructor | Descripción |
| --- | --- |
| [TextSaveOptions()](#TextSaveOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | Codificación de caracteres del documento de texto, que se aplicará a su |
guardado
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Codificación de caracteres del documento de texto, que se aplicará a su |
guardado
|
|  | [getAddBidiMarks()](#getAddBidiMarks--) | Especifica si se deben agregar marcas bidireccionales antes de cada ejecución BiDi cuando |
se exporta en formato de texto plano.
|
|  | [setAddBidiMarks(boolean value)](#setAddBidiMarks-boolean-) | Especifica si se deben agregar marcas bidireccionales antes de cada ejecución BiDi cuando |
exportando en formato de texto plano
|
|  | [getPreserveTableLayout()](#getPreserveTableLayout--) | Especifica si el programa debe intentar preservar el diseño de las tablas |
al guardar en formato de texto plano.
|
|  | [setPreserveTableLayout(boolean value)](#setPreserveTableLayout-boolean-) | Especifica si el programa debe intentar preservar el diseño de las tablas |
al guardar en formato de texto plano.
|
### TextSaveOptions() {#TextSaveOptions--}
```
public TextSaveOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Codificación de caracteres del documento de texto, que se aplicará a su
guardado


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Codificación de caracteres del documento de texto, que se aplicará a su
guardado


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.nio.charset.Charset |  |

### getAddBidiMarks() {#getAddBidiMarks--}
```
public final boolean getAddBidiMarks()
```


Especifica si se deben agregar marcas bidireccionales antes de cada ejecución BiDi cuando
exportando en formato de texto plano. El valor predeterminado es 'false' \\u2014 no agregar marcas BiDi.


**Returns:**
boolean -
### setAddBidiMarks(boolean value) {#setAddBidiMarks-boolean-}
```
public final void setAddBidiMarks(boolean value)
```


Especifica si se deben agregar marcas bidireccionales antes de cada ejecución BiDi cuando
exportando en formato de texto plano


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getPreserveTableLayout() {#getPreserveTableLayout--}
```
public final boolean getPreserveTableLayout()
```


Especifica si el programa debe intentar preservar el diseño de las tablas
al guardar en formato de texto plano. El valor predeterminado es false.


**Returns:**
boolean -
### setPreserveTableLayout(boolean value) {#setPreserveTableLayout-boolean-}
```
public final void setPreserveTableLayout(boolean value)
```


Especifica si el programa debe intentar preservar el diseño de las tablas
al guardar en formato de texto plano. El valor predeterminado es false.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

