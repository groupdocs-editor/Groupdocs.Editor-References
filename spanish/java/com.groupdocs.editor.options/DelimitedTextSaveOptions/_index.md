---
title: "DelimitedTextSaveOptions"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Contiene opciones para generar y guardar documentos de hoja de cálculo basados en texto, CSV, basados en tabulaciones, etc., que utilizan un delimitador separador"
type: docs
weight: 11
url: /es/java/com.groupdocs.editor.options/delimitedtextsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class DelimitedTextSaveOptions implements ISaveOptions
```

Contiene opciones para generar y guardar documentos de hoja de cálculo basados en texto
(CSV, basados en tabulaciones, etc.), que utilizan un separador (delimitador)


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [DelimitedTextSaveOptions()](#DelimitedTextSaveOptions--) | Este constructor sin parámetros crea una nueva instancia de DelimitedTextSaveOptions con un separador predeterminado de punto y coma (;) (puede modificarse luego a través de |
Separador
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) propiedad)
|
|  | [DelimitedTextSaveOptions(String separator)](#DelimitedTextSaveOptions-java.lang.String-) | Crea una instancia de la clase de opciones para texto delimitado con obligatorio |
separador (delimitador)
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | Permite especificar un separador de cadena (delimitador) para documentos basados en texto |
documentos Spreadsheet
|
|  | [setSeparator(String value)](#setSeparator-java.lang.String-) | Permite especificar un separador de cadena (delimitador) para documentos basados en texto |
documentos Spreadsheet
|
|  | [getEncoding()](#getEncoding--) | Permite establecer una codificación para el documento de hoja de cálculo basado en texto. |
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Permite establecer una codificación para el documento de hoja de cálculo basado en texto. |
|
|  | [getTrimLeadingBlankRowAndColumn()](#getTrimLeadingBlankRowAndColumn--) | Indica si las filas y columnas en blanco iniciales deben recortarse como |
lo que hace MS Excel
|
|  | [setTrimLeadingBlankRowAndColumn(boolean value)](#setTrimLeadingBlankRowAndColumn-boolean-) | Indica si las filas y columnas en blanco iniciales deben recortarse como |
lo que hace MS Excel
|
|  | [getKeepSeparatorsForBlankRow()](#getKeepSeparatorsForBlankRow--) | Indica si los separadores deben generarse para una fila en blanco. |
|
|  | [setKeepSeparatorsForBlankRow(boolean value)](#setKeepSeparatorsForBlankRow-boolean-) | Indica si los separadores deben generarse para una fila en blanco. |
|
### DelimitedTextSaveOptions() {#DelimitedTextSaveOptions--}
```
public DelimitedTextSaveOptions()
```


Este constructor sin parámetros crea una nueva instancia de DelimitedTextSaveOptions con un separador predeterminado de punto y coma (;) (puede modificarse luego a través de
Separador
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) propiedad)


### DelimitedTextSaveOptions(String separator) {#DelimitedTextSaveOptions-java.lang.String-}
```
public DelimitedTextSaveOptions(String separator)
```


Crea una instancia de la clase de opciones para texto delimitado con obligatorio
separador (delimitador)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | separador | java.lang.String | Separador de cadena (delimitador) para documentos de hoja de cálculo basados en texto |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


Permite especificar un separador de cadena (delimitador) para documentos basados en texto
documentos Spreadsheet


**Returns:**
java.lang.String -
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


Permite especificar un separador de cadena (delimitador) para documentos basados en texto
documentos Spreadsheet


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


Permite establecer una codificación para el documento de hoja de cálculo basado en texto. Por
defecto (y si no se especifica) es UTF8.


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


Permite establecer una codificación para el documento de hoja de cálculo basado en texto. Por
defecto (y si no se especifica) es UTF8.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.nio.charset.Charset |  |

### getTrimLeadingBlankRowAndColumn() {#getTrimLeadingBlankRowAndColumn--}
```
public final boolean getTrimLeadingBlankRowAndColumn()
```


Indica si las filas y columnas en blanco iniciales deben recortarse como
lo que hace MS Excel


**Returns:**
boolean -
### setTrimLeadingBlankRowAndColumn(boolean value) {#setTrimLeadingBlankRowAndColumn-boolean-}
```
public final void setTrimLeadingBlankRowAndColumn(boolean value)
```


Indica si las filas y columnas en blanco iniciales deben recortarse como
lo que hace MS Excel


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getKeepSeparatorsForBlankRow() {#getKeepSeparatorsForBlankRow--}
```
public final boolean getKeepSeparatorsForBlankRow()
```


Indica si los separadores deben generarse para una fila en blanco. Predeterminado
el valor es false, lo que significa que el contenido de la fila en blanco estará vacío.


**Returns:**
boolean -
### setKeepSeparatorsForBlankRow(boolean value) {#setKeepSeparatorsForBlankRow-boolean-}
```
public final void setKeepSeparatorsForBlankRow(boolean value)
```


Indica si los separadores deben generarse para una fila en blanco. Predeterminado
el valor es false, lo que significa que el contenido de la fila en blanco estará vacío.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

