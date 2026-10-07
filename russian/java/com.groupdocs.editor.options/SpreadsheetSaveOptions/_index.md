---
title: "SpreadsheetSaveOptions"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Позволяет указать пользовательские параметры для создания и сохранения документов Spreadsheet, совместимых с Excel"
type: docs
weight: 37
url: /ru/java/com.groupdocs.editor.options/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class SpreadsheetSaveOptions implements ISaveOptions
```

Позволяет указать пользовательские параметры для создания и сохранения Spreadsheet
(совместимые с Excel) документы

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | Этот конструктор без параметров создает новый экземпляр SpreadsheetSaveOptions с форматом вывода XLSX (может быть изменён затем через |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) свойство)
|
|  | [SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)](#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-) | Создаёт новый экземпляр SpreadsheetSaveOptions с указанным обязательным |
форматом вывода Spreadsheet, при этом все остальные параметры имеют значения по умолчанию
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getPassword()](#getPassword--) | Позволяет указать, изменить, получить или удалить пароль, который будет |
используется для кодирования сгенерированного документа Spreadsheet, если этот формат документа
поддерживает защиту паролем.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Позволяет указать, изменить, получить или удалить пароль, который будет |
используется для кодирования сгенерированного документа Spreadsheet, если этот формат документа
поддерживает защиту паролем.
|
|  | [getWorksheetNumber()](#getWorksheetNumber--) | Позволяет вставить отредактированный worksheet в копию существующего spreadsheet |
вместо создания нового одно-листового spreadsheet (по умолчанию
поведение).
|
|  | [setWorksheetNumber(int value)](#setWorksheetNumber-int-) | Позволяет вставить отредактированный worksheet в копию существующего spreadsheet |
вместо создания нового одно-листового spreadsheet (по умолчанию
поведение).
|
|  | [getInsertAsNewWorksheet()](#getInsertAsNewWorksheet--) | Булевый флаг, указывающий, должен ли отредактированный worksheet заменять |
существующий worksheet в оригинальном spreadsheet на позиции, указанной
это

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
свойство, либо он должен быть вставлен между существующим worksheet и
предыдущим, без замены его содержимого.
|
|  | [setInsertAsNewWorksheet(boolean value)](#setInsertAsNewWorksheet-boolean-) | Булевый флаг, указывающий, должен ли отредактированный worksheet заменять |
существующий worksheet в оригинальном spreadsheet на позиции, указанной
это

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
свойство, либо он должен быть вставлен между существующим worksheet и
предыдущим, без замены его содержимого.
|
|  | [getOutputFormat()](#getOutputFormat--) | Позволяет указать формат Spreadsheet, который будет использоваться для сохранения |
документа
|
|  | [setOutputFormat(SpreadsheetFormats value)](#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-) | Позволяет указать формат Spreadsheet, который будет использоваться для сохранения |
документа
|
|  | [getWorksheetProtection()](#getWorksheetProtection--) | Позволяет включить защиту worksheet для выходного Spreadsheet |
документа.
|
|  | [setWorksheetProtection(WorksheetProtection value)](#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-) | Позволяет включить защиту worksheet для выходного Spreadsheet |
документа.
|
|  | [getWorksheetNumbersToDelete()](#getWorksheetNumbersToDelete--) | Позволяет указать массив с номерами листов, начинающимися с 1, которые должны быть удалены из spreadsheet при его сохранении, в случае когда отредактированный worksheet вставляется в существующий spreadsheet. |
|
|  | [setWorksheetNumbersToDelete(int[] value)](#setWorksheetNumbersToDelete-int---) | Позволяет указать массив с номерами листов, начинающимися с 1, которые должны быть удалены из spreadsheet при его сохранении, в случае когда отредактированный worksheet вставляется в существующий spreadsheet. |
|
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


Этот конструктор без параметров создает новый экземпляр SpreadsheetSaveOptions с форматом вывода XLSX (может быть изменён затем через
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(SpreadsheetFormats).setOutputFormat(SpreadsheetFormats)) свойство)


### SpreadsheetSaveOptions(SpreadsheetFormats outputFormat) {#SpreadsheetSaveOptions-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public SpreadsheetSaveOptions(SpreadsheetFormats outputFormat)
```


Создаёт новый экземпляр SpreadsheetSaveOptions с указанным обязательным
форматом вывода Spreadsheet, при этом все остальные параметры имеют значения по умолчанию


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | outputFormat | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) | Обязательный формат вывода, в котором должен сохраняться документ Spreadsheet |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Позволяет указать, изменить, получить или удалить пароль, который будет
используется для кодирования сгенерированного документа Spreadsheet, если этот формат документа
поддерживает защиту паролем. Укажите NULL или пустую строку для удаления
(очистка) пароля.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Позволяет указать, изменить, получить или удалить пароль, который будет
используется для кодирования сгенерированного документа Spreadsheet, если этот формат документа
поддерживает защиту паролем. Укажите NULL или пустую строку для удаления
(очистка) пароля.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getWorksheetNumber() {#getWorksheetNumber--}
```
public final int getWorksheetNumber()
```


Позволяет вставить отредактированный worksheet в копию существующего spreadsheet
вместо создания нового одно-листового spreadsheet (по умолчанию
поведение). WorksheetNumber — это номер листа, начинающийся с 1, в
таблице, загруженной в классе Editor. Если он равен 0 (значение по умолчанию), то
будет создана новая таблица с единственным отредактированным листом. Если он
больше или меньше нуля, и существует действительная таблица, загруженная в
класс Editor, отредактированный лист, представленный входным
экземпляром EditableDocument, будет вставлен в эту таблицу.


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


Позволяет вставить отредактированный worksheet в копию существующего spreadsheet
вместо создания нового одно-листового spreadsheet (по умолчанию
поведение). WorksheetNumber — это номер листа, начинающийся с 1, в
таблице, загруженной в классе Editor. Если он равен 0 (значение по умолчанию), то
будет создана новая таблица с единственным отредактированным листом. Если он
больше или меньше нуля, и существует действительная таблица, загруженная в
класс Editor, отредактированный лист, представленный входным
экземпляром EditableDocument, будет вставлен в эту таблицу.


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
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getInsertAsNewWorksheet() {#getInsertAsNewWorksheet--}
```
public final boolean getInsertAsNewWorksheet()
```


Булевый флаг, указывающий, должен ли отредактированный worksheet заменять
существующий worksheet в оригинальном spreadsheet на позиции, указанной
это

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
свойство, либо он должен быть вставлен между существующим worksheet и
предыдущим, без замены его содержимого. По умолчанию false \\u2014
существующий лист будет заменён. Это свойство игнорируется, если значение
из

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
свойство установлено в '0'.


*** ** * ** ***

По умолчанию лист заменяется. Это означает, что если у данной таблицы 5 листов, и WorksheetNumber (#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))=4, то 4‑й лист будет заменён новым отредактированным листом, при этом общее количество листов в таблице (5) останется без изменений. Однако, если значение этого свойства установлено в  *true* , новый отредактированный лист будет вставлен как 4‑й лист, и все последующие листы будут сдвинуты в конец: \"old\" 4‑й лист становится 5‑м, а 5‑й становится 6‑м, и общее количество листов в таблице будет увеличено на один и станет равным 6.

<br />



**Returns:**
boolean -
### setInsertAsNewWorksheet(boolean value) {#setInsertAsNewWorksheet-boolean-}
```
public final void setInsertAsNewWorksheet(boolean value)
```


Булевый флаг, указывающий, должен ли отредактированный worksheet заменять
существующий worksheet в оригинальном spreadsheet на позиции, указанной
это

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
свойство, либо он должен быть вставлен между существующим worksheet и
предыдущим, без замены его содержимого. По умолчанию false \\u2014
существующий лист будет заменён. Это свойство игнорируется, если значение
из

WorksheetNumber
(#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))
свойство установлено в '0'.


*** ** * ** ***

По умолчанию лист заменяется. Это означает, что если у данной таблицы 5 листов, и WorksheetNumber (#getWorksheetNumber.getWorksheetNumber/#setWorksheetNumber(int).setWorksheetNumber(int))=4, то 4‑й лист будет заменён новым отредактированным листом, при этом общее количество листов в таблице (5) останется без изменений. Однако, если значение этого свойства установлено в  *true* , новый отредактированный лист будет вставлен как 4‑й лист, и все последующие листы будут сдвинуты в конец: \"old\" 4‑й лист становится 5‑м, а 5‑й становится 6‑м, и общее количество листов в таблице будет увеличено на один и станет равным 6.

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final SpreadsheetFormats getOutputFormat()
```


Позволяет указать формат Spreadsheet, который будет использоваться для сохранения
документа


**Returns:**
[SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) - 
### setOutputFormat(SpreadsheetFormats value) {#setOutputFormat-com.groupdocs.editor.formats.SpreadsheetFormats-}
```
public final void setOutputFormat(SpreadsheetFormats value)
```


Позволяет указать формат Spreadsheet, который будет использоваться для сохранения
документа


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [SpreadsheetFormats](../../com.groupdocs.editor.formats/spreadsheetformats) |  |

### getWorksheetProtection() {#getWorksheetProtection--}
```
public final WorksheetProtection getWorksheetProtection()
```


Позволяет включить защиту worksheet для выходного Spreadsheet
документ. По умолчанию NULL — защита не применяется. Не все форматы
поддерживают защиту листа.


**Returns:**
[WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) - 
### setWorksheetProtection(WorksheetProtection value) {#setWorksheetProtection-com.groupdocs.editor.options.WorksheetProtection-}
```
public final void setWorksheetProtection(WorksheetProtection value)
```


Позволяет включить защиту worksheet для выходного Spreadsheet
документ. По умолчанию NULL — защита не применяется. Не все форматы
поддерживают защиту листа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WorksheetProtection](../../com.groupdocs.editor.options/worksheetprotection) |  |

### getWorksheetNumbersToDelete() {#getWorksheetNumbersToDelete--}
```
public final int[] getWorksheetNumbersToDelete()
```


Позволяет указать массив с номерами листов, начинающимися с 1, которые следует удалить из таблицы при её сохранении, если отредактированный лист вставляется в существующую таблицу. Когда отредактированный лист сохраняется не как новая однолистовая таблица (поведение по умолчанию), а сохраняется в существующей таблице (используя #getWorksheetNumber().getWorksheetNumber() / #setWorksheetNumber(int).setWorksheetNumber(int)), также можно удалить некоторые конкретные листы из этой таблицы, указав их номера в этом массиве. По умолчанию этот массив равен  null  \\u2014 листы не будут удалены. Однако, когда массив не null и не пустой, и содержит хотя бы один действительный номер листа, после генерации выходного документа таблицы с содержимым отредактированного листа, листы с указанными номерами будут удалены из таблицы непосредственно перед записью её содержимого в выходной поток или файл. Номера листов в этом массиве начинаются с 1, а не с 0. Недопустимые номера (меньше 1 или больше общего количества листов) будут игнорироваться.


**Returns:**
int[] — массив номеров листов, начинающихся с 1, для удаления, или  null  если ничего не следует удалять.

### setWorksheetNumbersToDelete(int[] value) {#setWorksheetNumbersToDelete-int---}
```
public final void setWorksheetNumbersToDelete(int[] value)
```


Позволяет указать массив с номерами листов, начинающимися с 1, которые следует удалить из таблицы при её сохранении, если отредактированный лист вставляется в существующую таблицу. Номера листов в этом массиве начинаются с 1. Недопустимые номера будут игнорироваться.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | int[] | Массив номеров листов, начинающихся с 1, для удаления (может быть  null  или пустым). |
|

