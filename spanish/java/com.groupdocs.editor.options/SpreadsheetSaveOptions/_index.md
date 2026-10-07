---
title: "SpreadsheetSaveOptions"
second_title: "GroupDocs.Editor for Java API Reference"
description: "Permite especificar opciones personalizadas para generar y guardar documentos Spreadsheet compatibles con Excel"
type: docs
weight: 37
url: /es/java/com.groupdocs.editor.options/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class SpreadsheetSaveOptions implements ISaveOptions
```

Permite especificar opciones personalizadas para generar y guardar Spreadsheet
(compatibles con Excel) documentos

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | Este constructor sin parámetros crea una nueva instancia de SpreadsheetSaveOptions con formato de salida XLSX (puede modificarse luego a través de |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) propiedad)
|
|  | [SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)](#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-) | Crea una nueva instancia de SpreadsheetSaveOptions con el obligatorio especificado |
Formato de salida Spreadsheet, mientras que todos los demás parámetros son predeterminados
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getPassword()](#getPassword--) | Permite especificar, modificar, obtener o eliminar una contraseña, que será |
utilizado para codificar el documento Spreadsheet generado, si este formato de documento
admite protección con contraseña.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Permite especificar, modificar, obtener o eliminar una contraseña, que será |
utilizado para codificar el documento Spreadsheet generado, si este formato de documento
admite protección con contraseña.
|
|  | [getWorksheetNumber()](#getWorksheetNumber--) | Permite insertar la hoja de cálculo editada en una copia de la hoja de cálculo existente |
en lugar de crear una nueva hoja de cálculo de una sola hoja (predeterminado
comportamiento).
|
|  | [setWorksheetNumber(int value)](#setWorksheetNumber-int-) | Permite insertar la hoja de cálculo editada en una copia de la hoja de cálculo existente |
en lugar de crear una nueva hoja de cálculo de una sola hoja (predeterminado
comportamiento).
|
|  | [getInsertAsNewWorksheet()](#getInsertAsNewWorksheet--) | Bandera booleana que especifica si la hoja de cálculo editada debe reemplazar la |
hoja de cálculo existente en la hoja de cálculo original en la posición especificada por
el

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
propiedad, o debe inyectarse entre la hoja de cálculo existente y
la anterior, sin reemplazar su contenido.
|
|  | [setInsertAsNewWorksheet(boolean value)](#setInsertAsNewWorksheet-boolean-) | Bandera booleana que especifica si la hoja de cálculo editada debe reemplazar la |
hoja de cálculo existente en la hoja de cálculo original en la posición especificada por
el

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
propiedad, o debe inyectarse entre la hoja de cálculo existente y
la anterior, sin reemplazar su contenido.
|
|  | [getOutputFormat()](#getOutputFormat--) | Permite especificar un formato Spreadsheet, que se utilizará para guardar el |
documento
|
|  | [setOutputFormat(SpreadsheetFormats value)](#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-) | Permite especificar un formato Spreadsheet, que se utilizará para guardar el |
documento
|
|  | [getWorksheetProtection()](#getWorksheetProtection--) | Permite habilitar una protección de hoja de cálculo para el Spreadsheet de salida |
documento.
|
|  | [setWorksheetProtection(WorksheetProtection value)](#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-) | Permite habilitar una protección de hoja de cálculo para el Spreadsheet de salida |
documento.
|
|  | [getWorksheetNumbersToDelete()](#getWorksheetNumbersToDelete--) | Permite especificar una matriz con números basados en 1 de las hojas de cálculo que deben eliminarse del spreadsheet durante su guardado, en caso de que la hoja de cálculo editada se inserte en una hoja de cálculo existente. |
|
|  | [setWorksheetNumbersToDelete(int[] value)](#setWorksheetNumbersToDelete-int---) | Permite especificar una matriz con números basados en 1 de las hojas de cálculo que deben eliminarse del spreadsheet durante su guardado, en caso de que la hoja de cálculo editada se inserte en una hoja de cálculo existente. |
|
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


Este constructor sin parámetros crea una nueva instancia de SpreadsheetSaveOptions con formato de salida XLSX (puede modificarse luego a través de
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) propiedad)


### SpreadsheetSaveOptions(SpreadsheetFormats outputFormat) {#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)
```


Crea una nueva instancia de SpreadsheetSaveOptions con el obligatorio especificado
Formato de salida Spreadsheet, mientras que todos los demás parámetros son predeterminados


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | outputFormat | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) | Formato de salida obligatorio, en el que se debe guardar el documento Spreadsheet |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Permite especificar, modificar, obtener o eliminar una contraseña, que será
utilizado para codificar el documento Spreadsheet generado, si este formato de documento
admite protección con contraseña. Especifique NULL o una cadena vacía para eliminar
(limpieza) de la contraseña.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Permite especificar, modificar, obtener o eliminar una contraseña, que será
utilizado para codificar el documento Spreadsheet generado, si este formato de documento
admite protección con contraseña. Especifique NULL o una cadena vacía para eliminar
(limpieza) de la contraseña.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getWorksheetNumber() {#getWorksheetNumber--}
```
public final int getWorksheetNumber()
```


Permite insertar la hoja de cálculo editada en una copia de la hoja de cálculo existente
en lugar de crear una nueva hoja de cálculo de una sola hoja (predeterminado
comportamiento). WorksheetNumber es un número basado en 1 de una hoja de cálculo en el
hoja de cálculo, cargada en la clase Editor. Si es 0 (valor predeterminado), el
se creará una nueva hoja de cálculo con una sola hoja editada. Si es
mayor o menor que cero, y hay una hoja de cálculo válida, cargada en
la clase Editor, la hoja editada, que está representada por la entrada
instancia EditableDocument, se insertará en esta hoja de cálculo.


*** ** * ** ***

> ```
> Given spreadsheet has 5 worksheets:
>  WorksheetNumber  = 0; \u2014 ignore given spreadsheet, create a new spreadsheet and put edited worksheet into it.
>  WorksheetNumber  = 1; \u2014 replace the first worksheet with edited
>  WorksheetNumber  = 2; \u2014 replace the second worksheet with edited
>  WorksheetNumber  = 5; \u2014 replace the last (5th) worksheet with edited
>  WorksheetNumber  = 6; \u2014 replace the last (5th) worksheet with edited, because 6 is greater then 5 and thus is adjusted
>  WorksheetNumber = -1; \u2014 replace the last (5th) worksheet with edited, because "-1" means "last existing"
>  WorksheetNumber = -2; \u2014 replace the 4th worksheet with edited
>  WorksheetNumber = -3; \u2014 replace the 3rd worksheet with edited
>  WorksheetNumber = -4; \u2014 replace the 2nd worksheet with edited
>  WorksheetNumber = -5; \u2014 replace the first worksheet with edited
>  WorksheetNumber = -6; \u2014 replace the first worksheet with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />


*** ** * ** ***

 *WorksheetNumber*  integer property, if it is not in default state (reserved value '0'), represents a worksheet number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last worksheet. Negative values are also allowed and count worksheets from end. For example, "-1" implies last worksheet in a spreadsheet, "-2" \\u2014 last but one, etc. Like with positive values, when negative worksheet number exceeds the total count of worksheets in the given spreadsheet, it will be adjusted to the first worksheet. The  InsertAsNewWorksheet (#getInsertAsNewWorksheet.getInsertAsNewWorksheet/#setInsertAsNewWorksheet(boolean).setInsertAsNewWorksheet(boolean)) boolean property is tightly coupled with this one.

<br />



**Returns:**
int -
### setWorksheetNumber(int value) {#setWorksheetNumber-int-}
```
public final void setWorksheetNumber(int value)
```


Permite insertar la hoja de cálculo editada en una copia de la hoja de cálculo existente
en lugar de crear una nueva hoja de cálculo de una sola hoja (predeterminado
comportamiento). WorksheetNumber es un número basado en 1 de una hoja de cálculo en el
hoja de cálculo, cargada en la clase Editor. Si es 0 (valor predeterminado), el
se creará una nueva hoja de cálculo con una sola hoja editada. Si es
mayor o menor que cero, y hay una hoja de cálculo válida, cargada en
la clase Editor, la hoja editada, que está representada por la entrada
instancia EditableDocument, se insertará en esta hoja de cálculo.


*** ** * ** ***

> ```
> Given spreadsheet has 5 worksheets:
>  WorksheetNumber  = 0; \u2014 ignore given spreadsheet, create a new spreadsheet and put edited worksheet into it.
>  WorksheetNumber  = 1; \u2014 replace the first worksheet with edited
>  WorksheetNumber  = 2; \u2014 replace the second worksheet with edited
>  WorksheetNumber  = 5; \u2014 replace the last (5th) worksheet with edited
>  WorksheetNumber  = 6; \u2014 replace the last (5th) worksheet with edited, because 6 is greater then 5 and thus is adjusted
>  WorksheetNumber = -1; \u2014 replace the last (5th) worksheet with edited, because "-1" means "last existing"
>  WorksheetNumber = -2; \u2014 replace the 4th worksheet with edited
>  WorksheetNumber = -3; \u2014 replace the 3rd worksheet with edited
>  WorksheetNumber = -4; \u2014 replace the 2nd worksheet with edited
>  WorksheetNumber = -5; \u2014 replace the first worksheet with edited
>  WorksheetNumber = -6; \u2014 replace the first worksheet with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />


*** ** * ** ***

 *WorksheetNumber*  integer property, if it is not in default state (reserved value '0'), represents a worksheet number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last worksheet. Negative values are also allowed and count worksheets from end. For example, "-1" implies last worksheet in a spreadsheet, "-2" \\u2014 last but one, etc. Like with positive values, when negative worksheet number exceeds the total count of worksheets in the given spreadsheet, it will be adjusted to the first worksheet. The  InsertAsNewWorksheet (#getInsertAsNewWorksheet.getInsertAsNewWorksheet/#setInsertAsNewWorksheet(boolean).setInsertAsNewWorksheet(boolean)) boolean property is tightly coupled with this one.

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getInsertAsNewWorksheet() {#getInsertAsNewWorksheet--}
```
public final boolean getInsertAsNewWorksheet()
```


Bandera booleana que especifica si la hoja de cálculo editada debe reemplazar la
hoja de cálculo existente en la hoja de cálculo original en la posición especificada por
el

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
propiedad, o debe inyectarse entre la hoja de cálculo existente y
la anterior, sin reemplazar su contenido. Por defecto es false \u2014
la hoja de cálculo existente será reemplazada. Esta propiedad se ignora, si el valor
de

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
la propiedad está establecida en '0'.


*** ** * ** ***

Por defecto la hoja de cálculo se reemplaza. Esto significa que si la hoja de cálculo dada tiene 5 hojas, y WorksheetNumber (#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))=4, entonces la cuarta hoja será reemplazada por la nueva hoja editada, mientras que la cantidad total de hojas en la hoja de cálculo (5) permanecerá sin cambios. Sin embargo, si el valor de esta propiedad se establece en  *true* , la nueva hoja editada se inyectará como cuarta hoja, y todas las hojas subsecuentes se desplazarán al final: \"old\" la cuarta hoja pasa a ser la quinta, y la quinta pasa a ser la sexta, y la cantidad total de hojas en la hoja de cálculo se incrementará en uno y será igual a 6.

<br />



**Returns:**
boolean -
### setInsertAsNewWorksheet(boolean value) {#setInsertAsNewWorksheet-boolean-}
```
public final void setInsertAsNewWorksheet(boolean value)
```


Bandera booleana que especifica si la hoja de cálculo editada debe reemplazar la
hoja de cálculo existente en la hoja de cálculo original en la posición especificada por
el

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
propiedad, o debe inyectarse entre la hoja de cálculo existente y
la anterior, sin reemplazar su contenido. Por defecto es false \u2014
la hoja de cálculo existente será reemplazada. Esta propiedad se ignora, si el valor
de

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
la propiedad está establecida en '0'.


*** ** * ** ***

Por defecto la hoja de cálculo se reemplaza. Esto significa que si la hoja de cálculo dada tiene 5 hojas, y WorksheetNumber (#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))=4, entonces la cuarta hoja será reemplazada por la nueva hoja editada, mientras que la cantidad total de hojas en la hoja de cálculo (5) permanecerá sin cambios. Sin embargo, si el valor de esta propiedad se establece en  *true* , la nueva hoja editada se inyectará como cuarta hoja, y todas las hojas subsecuentes se desplazarán al final: \"old\" la cuarta hoja pasa a ser la quinta, y la quinta pasa a ser la sexta, y la cantidad total de hojas en la hoja de cálculo se incrementará en uno y será igual a 6.

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final SpreadsheetFormats getOutputFormat()
```


Permite especificar un formato Spreadsheet, que se utilizará para guardar el
documento


**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - 
### setOutputFormat(SpreadsheetFormats value) {#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public final void setOutputFormat(SpreadsheetFormats value)
```


Permite especificar un formato Spreadsheet, que se utilizará para guardar el
documento


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) |  |

### getWorksheetProtection() {#getWorksheetProtection--}
```
public final WorksheetProtection getWorksheetProtection()
```


Permite habilitar una protección de hoja de cálculo para el Spreadsheet de salida
documento. Por defecto es NULL - la protección no se aplica. No todos los formatos
admiten protección de hoja de cálculo.


**Returns:**
[WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) - 
### setWorksheetProtection(WorksheetProtection value) {#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-}
```
public final void setWorksheetProtection(WorksheetProtection value)
```


Permite habilitar una protección de hoja de cálculo para el Spreadsheet de salida
documento. Por defecto es NULL - la protección no se aplica. No todos los formatos
admiten protección de hoja de cálculo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) |  |

### getWorksheetNumbersToDelete() {#getWorksheetNumbersToDelete--}
```
public final int[] getWorksheetNumbersToDelete()
```


Permite especificar una matriz con números de hojas basados en 1 que deben eliminarse de la hoja de cálculo durante su guardado, en caso de que la hoja editada se inserte en una hoja de cálculo existente. Cuando la hoja editada se guarda no como una nueva hoja de cálculo de una sola hoja (comportamiento predeterminado), sino que se guarda en una hoja de cálculo existente (usando #getWorksheetNumber().getWorksheetNumber() / #setWorksheetNumber(int).setWorksheetNumber(int)), también es posible eliminar algunas hojas particulares de esta hoja de cálculo especificando sus números en esta matriz. Por defecto esta matriz es  null  \u2014 no se eliminará ninguna hoja. Sin embargo, cuando esta matriz no es nula y no está vacía, y contiene al menos un número de hoja válido, después de que se genere el documento de hoja de cálculo de salida con el contenido de la hoja editada, las hojas con los números especificados se eliminarán de la hoja de cálculo justo antes de escribir su contenido en el flujo de salida o archivo. Los números de hoja en esta matriz son basados en 1, no en 0. Los números inválidos (menores que 1 o mayores que el número total de hojas) serán ignorados.


**Returns:**
int[] - Matriz de números de hoja basados en 1 para eliminar, o  null  si no se debe eliminar nada.

### setWorksheetNumbersToDelete(int[] value) {#setWorksheetNumbersToDelete-int---}
```
public final void setWorksheetNumbersToDelete(int[] value)
```


Permite especificar una matriz con números de hojas basados en 1 que deben eliminarse de la hoja de cálculo durante su guardado, en caso de que la hoja editada se inserte en una hoja de cálculo existente. Los números de hoja en esta matriz son basados en 1. Los números inválidos serán ignorados.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int[] | Matriz de números de hoja basados en 1 para eliminar (puede ser  null  o estar vacía). |
|

