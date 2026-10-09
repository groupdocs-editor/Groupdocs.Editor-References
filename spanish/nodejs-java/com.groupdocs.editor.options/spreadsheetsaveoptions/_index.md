---
title: "SpreadsheetSaveOptions"
second_title: "Referencia de API de GroupDocs.Editor para Node.js vía Java"
description: "Permite especificar opciones personalizadas para generar y guardar documentos de hoja de cálculo compatibles con Excel"
type: docs
weight: 37
url: /es/nodejs-java/com.groupdocs.editor.options/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class SpreadsheetSaveOptions implements ISaveOptions
```

Permite especificar opciones personalizadas para generar y guardar la hoja de cálculo
(compatibles con Excel) documentos

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | Este constructor sin parámetros crea una nueva instancia de SpreadsheetSaveOptions con formato de salida XLSX (puede modificarse luego a través de |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) property)
|
|  | [SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)](#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-) | Crea una nueva instancia de SpreadsheetSaveOptions con el obligatorio especificado |
formato de salida de hoja de cálculo, mientras que todos los demás parámetros son predeterminados
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getPassword()](#getPassword--) | Permite especificar, modificar, obtener o eliminar una contraseña, que será |
utilizado para codificar el documento de hoja de cálculo generado, si su formato de documento
soporta protección con contraseña.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Permite especificar, modificar, obtener o eliminar una contraseña, que será |
utilizado para codificar el documento de hoja de cálculo generado, si su formato de documento
soporta protección con contraseña.
|
|  | [getWorksheetNumber()](#getWorksheetNumber--) | Permite insertar la hoja de cálculo editada en una copia de la hoja de cálculo existente |
en lugar de crear una nueva hoja de cálculo de una sola hoja (predeterminado
comportamiento).
|
|  | [setWorksheetNumber(int value)](#setWorksheetNumber-int-) | Permite insertar la hoja de cálculo editada en una copia de la hoja de cálculo existente |
en lugar de crear una nueva hoja de cálculo de una sola hoja (predeterminado
comportamiento).
|
|  | [getInsertAsNewWorksheet()](#getInsertAsNewWorksheet--) | Bandera booleana, que especifica si la hoja de cálculo editada debe reemplazar la |
hoja de cálculo existente en la hoja de cálculo original en la posición, especificada por
el

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
propiedad, o debería inyectarse entre la worksheet existente y
la anterior, sin reemplazar su contenido.
|
|  | [setInsertAsNewWorksheet(boolean value)](#setInsertAsNewWorksheet-boolean-) | Bandera booleana, que especifica si la hoja de cálculo editada debe reemplazar la |
hoja de cálculo existente en la hoja de cálculo original en la posición, especificada por
el

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
propiedad, o debería inyectarse entre la worksheet existente y
la anterior, sin reemplazar su contenido.
|
|  | [getOutputFormat()](#getOutputFormat--) | Permite especificar un formato de Spreadsheet, que se utilizará para guardar el  |
documento
|
|  | [setOutputFormat(SpreadsheetFormats value)](#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-) | Permite especificar un formato de Spreadsheet, que se utilizará para guardar el  |
documento
|
|  | [getWorksheetProtection()](#getWorksheetProtection--) | Permite habilitar una protección de worksheet para el Spreadsheet de salida |
documento.
|
|  | [setWorksheetProtection(WorksheetProtection value)](#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-) | Permite habilitar una protección de worksheet para el Spreadsheet de salida |
documento.
|
|  | [getWorksheetNumbersToDelete()](#getWorksheetNumbersToDelete--) | Permite especificar una matriz con números basados en 1 de worksheets que deben eliminarse del spreadsheet durante su guardado, en caso de que la worksheet editada se inserte en un spreadsheet existente. |
|
|  | [setWorksheetNumbersToDelete(int[] value)](#setWorksheetNumbersToDelete-int---) | Permite especificar una matriz con números basados en 1 de worksheets que deben eliminarse del spreadsheet durante su guardado, en caso de que la worksheet editada se inserte en un spreadsheet existente. |
|
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


Este constructor sin parámetros crea una nueva instancia de SpreadsheetSaveOptions con formato de salida XLSX (puede modificarse luego a través de
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) property)


### SpreadsheetSaveOptions(SpreadsheetFormats outputFormat) {#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)
```


Crea una nueva instancia de SpreadsheetSaveOptions con el obligatorio especificado
formato de salida de hoja de cálculo, mientras que todos los demás parámetros son predeterminados


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | outputFormat | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) | Formato de salida obligatorio, en el que el documento Spreadsheet debe guardarse |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Permite especificar, modificar, obtener o eliminar una contraseña, que será
utilizado para codificar el documento de hoja de cálculo generado, si su formato de documento
admite protección con contraseña. Especifique NULL o una cadena vacía para eliminar
(limpieza) la contraseña.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Permite especificar, modificar, obtener o eliminar una contraseña, que será
utilizado para codificar el documento de hoja de cálculo generado, si su formato de documento
admite protección con contraseña. Especifique NULL o una cadena vacía para eliminar
(limpieza) la contraseña.


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
comportamiento). WorksheetNumber es un número basado en 1 de una worksheet en el
spreadsheet, cargado en la clase Editor. Si es 0 (valor predeterminado), el
nuevo spreadsheet se creará con una única worksheet editada. Si es
mayor o menor que cero, y hay un spreadsheet válido, cargado en
la clase Editor, la worksheet editada, que está representada por la entrada
instancia EditableDocument, se insertará en este spreadsheet.


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
comportamiento). WorksheetNumber es un número basado en 1 de una worksheet en el
spreadsheet, cargado en la clase Editor. Si es 0 (valor predeterminado), el
nuevo spreadsheet se creará con una única worksheet editada. Si es
mayor o menor que cero, y hay un spreadsheet válido, cargado en
la clase Editor, la worksheet editada, que está representada por la entrada
instancia EditableDocument, se insertará en este spreadsheet.


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


Bandera booleana, que especifica si la hoja de cálculo editada debe reemplazar la
hoja de cálculo existente en la hoja de cálculo original en la posición, especificada por
el

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
propiedad, o debería inyectarse entre la worksheet existente y
la anterior, sin reemplazar su contenido. Por defecto es false \\u2014
la worksheet existente será reemplazada. Esta propiedad se ignora, si el valor
de

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
la propiedad se establece en '0'.


*** ** * ** ***

Por defecto la worksheet se reemplaza. Esto significa que si el spreadsheet dado tiene 5 worksheets, y WorksheetNumber (#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))=4, entonces la worksheet número 4 será reemplazada por la nueva worksheet editada, mientras que la cantidad total de worksheets en el spreadsheet (5) permanecerá sin cambios. Sin embargo, si el valor de esta propiedad se establece en  *true* , la nueva worksheet editada será inyectada como la worksheet número 4, y todas las worksheets subsecuentes se desplazarán al final: \"old\" la worksheet número 4 pasa a ser la 5ª, y la 5ª pasa a ser la 6ª, y la cantidad total de worksheets en el spreadsheet se incrementará en uno y será igual a 6.

<br />



**Returns:**
boolean -
### setInsertAsNewWorksheet(boolean value) {#setInsertAsNewWorksheet-boolean-}
```
public final void setInsertAsNewWorksheet(boolean value)
```


Bandera booleana, que especifica si la hoja de cálculo editada debe reemplazar la
hoja de cálculo existente en la hoja de cálculo original en la posición, especificada por
el

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
propiedad, o debería inyectarse entre la worksheet existente y
la anterior, sin reemplazar su contenido. Por defecto es false \\u2014
la worksheet existente será reemplazada. Esta propiedad se ignora, si el valor
de

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
la propiedad se establece en '0'.


*** ** * ** ***

Por defecto la worksheet se reemplaza. Esto significa que si el spreadsheet dado tiene 5 worksheets, y WorksheetNumber (#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))=4, entonces la worksheet número 4 será reemplazada por la nueva worksheet editada, mientras que la cantidad total de worksheets en el spreadsheet (5) permanecerá sin cambios. Sin embargo, si el valor de esta propiedad se establece en  *true* , la nueva worksheet editada será inyectada como la worksheet número 4, y todas las worksheets subsecuentes se desplazarán al final: \"old\" la worksheet número 4 pasa a ser la 5ª, y la 5ª pasa a ser la 6ª, y la cantidad total de worksheets en el spreadsheet se incrementará en uno y será igual a 6.

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | booleano |  |

### getOutputFormat() {#getOutputFormat--}
```
public final SpreadsheetFormats getOutputFormat()
```


Permite especificar un formato de Spreadsheet, que se utilizará para guardar el 
documento


**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - 
### setOutputFormat(SpreadsheetFormats value) {#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public final void setOutputFormat(SpreadsheetFormats value)
```


Permite especificar un formato de Spreadsheet, que se utilizará para guardar el 
documento


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) |  |

### getWorksheetProtection() {#getWorksheetProtection--}
```
public final WorksheetProtection getWorksheetProtection()
```


Permite habilitar una protección de worksheet para el Spreadsheet de salida
documento. Por defecto es NULL - la protección no se aplica. No todos los formatos
admiten una protección de worksheet.


**Returns:**
[WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) - 
### setWorksheetProtection(WorksheetProtection value) {#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-}
```
public final void setWorksheetProtection(WorksheetProtection value)
```


Permite habilitar una protección de worksheet para el Spreadsheet de salida
documento. Por defecto es NULL - la protección no se aplica. No todos los formatos
admiten una protección de worksheet.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) |  |

### getWorksheetNumbersToDelete() {#getWorksheetNumbersToDelete--}
```
public final int[] getWorksheetNumbersToDelete()
```


Permite especificar una matriz con números basados en 1 de worksheets que deben eliminarse del spreadsheet durante su guardado, en caso de que la worksheet editada se inserte en un spreadsheet existente. Cuando la worksheet editada se guarda no como un nuevo spreadsheet de una sola worksheet (comportamiento predeterminado), sino que se guarda en un spreadsheet existente (usando #getWorksheetNumber().getWorksheetNumber() / #setWorksheetNumber(int).setWorksheetNumber(int)), también es posible eliminar algunas worksheets particulares de este spreadsheet especificando sus números en esta matriz. Por defecto esta matriz es  null  \\u2014 no se eliminarán worksheets. Sin embargo, cuando esta matriz no es null y no está vacía, y contiene al menos un número de worksheet válido, después de que se genere el documento spreadsheet de salida con el contenido de la worksheet editada, las worksheets con los números especificados se eliminarán del spreadsheet justo antes de escribir su contenido al flujo de salida o al archivo. Los números de worksheet en esta matriz son basados en 1, no en 0. Los números inválidos (menores que 1 o mayores que el número total de worksheets) serán ignorados.


**Returns:**
int[] - Matriz de números de hoja de cálculo basados en 1 para eliminar, o  null  si no se debe eliminar nada.

### setWorksheetNumbersToDelete(int[] value) {#setWorksheetNumbersToDelete-int---}
```
public final void setWorksheetNumbersToDelete(int[] value)
```


Permite especificar una matriz con números de hojas de cálculo basados en 1 que deben eliminarse del libro al guardarlo, en caso de que la hoja editada se inserte en un libro existente. Los números de hoja en esta matriz son basados en 1. Los números no válidos se ignorarán.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int[] | Matriz de números de hoja de cálculo basados en 1 para eliminar (puede ser  null  o estar vacía). |
|

