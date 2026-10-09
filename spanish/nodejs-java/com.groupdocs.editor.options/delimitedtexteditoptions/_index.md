---
title: "DelimitedTextEditOptions"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Opciones para cargar documentos de hoja de cálculo basados en texto CSV basados en tabulaciones, etc. que usan un separador delimitador"
type: docs
weight: 10
url: /es/nodejs-java/com.groupdocs.editor.options/delimitedtexteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class DelimitedTextEditOptions implements IEditOptions
```

Opciones para cargar documentos de hoja de cálculo basados en texto (CSV, basados en tabulaciones, etc.),
que usan un separador (delimitador)


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [DelimitedTextEditOptions(String separator)](#DelimitedTextEditOptions-java.lang.String-) | Crea una instancia de la clase de opciones para texto delimitado con obligatorio |
separador (delimitador)
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | Permite especificar un separador de cadena (delimitador) para texto basado en |
Documentos de hoja de cálculo
|
|  | [setSeparator(String value)](#setSeparator-java.lang.String-) | Permite especificar un separador de cadena (delimitador) para texto basado en |
Documentos de hoja de cálculo
|
|  | [getConvertDateTimeData()](#getConvertDateTimeData--) | Obtiene o establece un valor que indica si la cadena en texto basado |
el documento se convierte a datos de fecha.
|
|  | [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | Obtiene o establece un valor que indica si la cadena en texto basado |
el documento se convierte a datos de fecha.
|
|  | [getConvertNumericData()](#getConvertNumericData--) | Obtiene o establece un valor que indica si la cadena en texto basado |
el documento se convierte a datos numéricos.
|
|  | [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | Obtiene o establece un valor que indica si la cadena en texto basado |
el documento se convierte a datos numéricos.
|
|  | [getTreatConsecutiveDelimitersAsOne()](#getTreatConsecutiveDelimitersAsOne--) | Define si los delimitadores consecutivos deben tratarse como uno. |
|
|  | [setTreatConsecutiveDelimitersAsOne(boolean value)](#setTreatConsecutiveDelimitersAsOne-boolean-) | Define si los delimitadores consecutivos deben tratarse como uno. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Habilita mecanismos de optimización de memoria durante el procesamiento del documento de entrada, |
lo que puede degradar el rendimiento en algunos casos especiales, pero por otro
lado disminuye el uso de memoria.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Habilita mecanismos de optimización de memoria durante el procesamiento del documento de entrada, |
lo que puede degradar el rendimiento en algunos casos especiales, pero por otro
lado disminuye el uso de memoria.
|
### DelimitedTextEditOptions(String separator) {#DelimitedTextEditOptions-java.lang.String-}
```
public DelimitedTextEditOptions(String separator)
```


Crea una instancia de la clase de opciones para texto delimitado con obligatorio
separador (delimitador)


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | separador | java.lang.String | Separador obligatorio (delimitador), que no puede ser NULL o vacío |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


Permite especificar un separador de cadena (delimitador) para texto basado en
Documentos de hoja de cálculo


**Returns:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


Permite especificar un separador de cadena (delimitador) para texto basado en
Documentos de hoja de cálculo


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


Obtiene o establece un valor que indica si la cadena en texto basado
el documento se convierte a datos de fecha. El valor predeterminado es false.


**Returns:**
booleano
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


Obtiene o establece un valor que indica si la cadena en texto basado
el documento se convierte a datos de fecha. El valor predeterminado es false.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


Obtiene o establece un valor que indica si la cadena en texto basado
el documento se convierte a datos numéricos. El valor predeterminado es false.


**Returns:**
booleano
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


Obtiene o establece un valor que indica si la cadena en texto basado
el documento se convierte a datos numéricos. El valor predeterminado es false.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getTreatConsecutiveDelimitersAsOne() {#getTreatConsecutiveDelimitersAsOne--}
```
public final boolean getTreatConsecutiveDelimitersAsOne()
```


Define si los delimitadores consecutivos deben tratarse como uno. Por
el valor predeterminado es falso.


**Returns:**
booleano
### setTreatConsecutiveDelimitersAsOne(boolean value) {#setTreatConsecutiveDelimitersAsOne-boolean-}
```
public final void setTreatConsecutiveDelimitersAsOne(boolean value)
```


Define si los delimitadores consecutivos deben tratarse como uno. Por
el valor predeterminado es falso.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


Habilita mecanismos de optimización de memoria durante el procesamiento del documento de entrada,
lo que puede degradar el rendimiento en algunos casos especiales, pero por otro
lado disminuye el uso de memoria. Útil al procesar documentos enormes y
enfrentando OutOfMemoryException. El valor predeterminado es false (la optimización de memoria está
desactivada por el bien de un mejor rendimiento).


**Returns:**
booleano
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


Habilita mecanismos de optimización de memoria durante el procesamiento del documento de entrada,
lo que puede degradar el rendimiento en algunos casos especiales, pero por otro
lado disminuye el uso de memoria. Útil al procesar documentos enormes y
enfrentando OutOfMemoryException. El valor predeterminado es false (la optimización de memoria está
desactivada por el bien de un mejor rendimiento).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

