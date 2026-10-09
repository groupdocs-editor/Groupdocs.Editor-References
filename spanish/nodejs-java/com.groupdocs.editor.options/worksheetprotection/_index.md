---
title: "WorksheetProtection"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Encapsula opciones de protección de hoja de cálculo que permiten proteger una hoja de cálculo en el documento Spreadsheet de salida contra la modificación del tipo especificado con una contraseña especificada."
type: docs
weight: 49
url: /es/nodejs-java/com.groupdocs.editor.options/worksheetprotection/
---
**Inheritance:**
java.lang.Object
```
public final class WorksheetProtection
```

Encapsula opciones de protección de hoja de cálculo, que permiten proteger una hoja de cálculo
en el documento Spreadsheet de salida contra la modificación del tipo especificado con una
contraseña especificada.


*** ** * ** ***

La mayoría de los formatos Spreadsheet, como XLSX, permiten proteger una hoja de cálculo de la edición con contraseña. Esta clase permite habilitar dicha protección y especificar sus opciones.

<br />


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [WorksheetProtection()](#WorksheetProtection--) | Crea una nueva instancia con parámetros predeterminados. |
|
|  | [WorksheetProtection(int protectionType, String password)](#WorksheetProtection-int-java.lang.String-) | Crea una nueva instancia con el tipo de protección de hoja de cálculo especificado y |
contraseña
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getProtectionType()](#getProtectionType--) | Permite especificar un tipo de protección de hoja de cálculo. |
|
|  | [setProtectionType(int value)](#setProtectionType-int-) | Permite especificar un tipo de protección de hoja de cálculo. |
|
|  | [getPassword()](#getPassword--) | Contraseña, que se utiliza para proteger una hoja de cálculo. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Contraseña, que se utiliza para proteger una hoja de cálculo. |
|
### WorksheetProtection() {#WorksheetProtection--}
```
public WorksheetProtection()
```


Crea una nueva instancia con parámetros predeterminados. Si no se modifica y se pasa
a SpreadsheetSaveOptions, no se aplicará protección a la hoja de cálculo


### WorksheetProtection(int protectionType, String password) {#WorksheetProtection-int-java.lang.String-}
```
public WorksheetProtection(int protectionType, String password)
```


Crea una nueva instancia con el tipo de protección de hoja de cálculo especificado y
contraseña


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | protectionType | int | Tipo de protección de hoja de cálculo |
|
|  | contraseña | java.lang.String | Contraseña, que bloquea la protección |
|

### getProtectionType() {#getProtectionType--}
```
public final int getProtectionType()
```


Permite especificar un tipo de protección de hoja de cálculo. Por defecto es 'None' -
la protección no se aplica.


**Returns:**
int
### setProtectionType(int value) {#setProtectionType-int-}
```
public final void setProtectionType(int value)
```


Permite especificar un tipo de protección de hoja de cálculo. Por defecto es 'None' -
la protección no se aplica.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Contraseña, que se utiliza para proteger una hoja de cálculo. Si es NULL o está vacía
cadena, la protección no se aplicará.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Contraseña, que se utiliza para proteger una hoja de cálculo. Si es NULL o está vacía
cadena, la protección no se aplicará.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

