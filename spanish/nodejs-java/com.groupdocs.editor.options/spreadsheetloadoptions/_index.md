---
title: "SpreadsheetLoadOptions"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Contiene opciones para cargar documentos binarios de Spreadsheet Cells compatibles con Excel, como XLSX, ODS, etc."
type: docs
weight: 36
url: /es/nodejs-java/com.groupdocs.editor.options/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class SpreadsheetLoadOptions implements ILoadOptions
```

Contiene opciones para cargar Spreadsheet binario (Cells, compatible con Excel)
documentos como XLS(X), ODS, etc. en la clase Editor

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | Constructor predeterminado sin parámetros - todos los parámetros tienen valores predeterminados |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getPassword()](#getPassword--) | Permite especificar, modificar y obtener la contraseña, que se utilizará para |
abriendo el documento Spreadsheet, si está codificado.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Permite especificar, modificar y obtener la contraseña, que se utilizará para |
abriendo el documento Spreadsheet, si está codificado.
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | Habilita mecanismos de optimización de memoria durante el procesamiento del documento de entrada, |
lo que puede degradar el rendimiento en algunos casos especiales, pero por otro
lado disminuye el uso de memoria.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | Habilita mecanismos de optimización de memoria durante el procesamiento del documento de entrada, |
lo que puede degradar el rendimiento en algunos casos especiales, pero por otro
lado disminuye el uso de memoria.
|
### SpreadsheetLoadOptions() {#SpreadsheetLoadOptions--}
```
public SpreadsheetLoadOptions()
```


Constructor predeterminado sin parámetros - todos los parámetros tienen valores predeterminados


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Permite especificar, modificar y obtener la contraseña, que se utilizará para
abriendo el documento Spreadsheet, si está codificado. Establecer a NULL o vacío
cadena para no usar la contraseña (valor predeterminado).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Permite especificar, modificar y obtener la contraseña, que se utilizará para
abriendo el documento Spreadsheet, si está codificado. Establecer a NULL o vacío
cadena para no usar la contraseña (valor predeterminado).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

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

