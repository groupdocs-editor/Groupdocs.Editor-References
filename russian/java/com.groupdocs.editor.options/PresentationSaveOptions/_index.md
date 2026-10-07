---
title: "PresentationSaveOptions"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Позволяет задавать пользовательские параметры для создания и сохранения документов Presentation, совместимых с PowerPoint"
type: docs
weight: 34
url: /ru/java/com.groupdocs.editor.options/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PresentationSaveOptions implements ISaveOptions
```

Позволяет задавать пользовательские параметры для создания и сохранения Presentation
(совместимые с PowerPoint) документы

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [PresentationSaveOptions()](#PresentationSaveOptions--) | Этот конструктор без параметров создаёт новый экземпляр PresentationSaveOptions с форматом вывода PPTX (может быть изменён затем через |
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)) property)
|
|  | [PresentationSaveOptions(PresentationFormats outputFormat)](#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-) | Создаёт новый экземпляр PresentationSaveOptions с указанным |
обязательным форматом вывода Presentation, в то время как все остальные параметры
по умолчанию
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getPassword()](#getPassword--) | Позволяет указать, изменить и получить пароль, который будет использоваться для |
кодированием получаемого документа Presentation.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Позволяет задавать, изменять и получать пароль, который будет использоваться для кодирования получаемого документа Presentation. |
|
|  | [getSlideNumber()](#getSlideNumber--) | Позволяет вставлять отредактированный слайд в существующую презентацию вместо создания новой однослайдовой презентации (поведение по умолчанию). |
|
|  | [setSlideNumber(int value)](#setSlideNumber-int-) | Позволяет вставлять отредактированный слайд в существующую презентацию вместо создания новой однослайдовой презентации (поведение по умолчанию). |
|
|  | [getInsertAsNewSlide()](#getInsertAsNewSlide--) | Булевый флаг, указывающий, следует ли заменять отредактированный слайд существующим слайдом в оригинальной презентации на позиции, указанной |
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) property, либо он должен быть вставлен между существующим слайдом и предыдущим, без замены их содержимого.
|
|  | [setInsertAsNewSlide(boolean value)](#setInsertAsNewSlide-boolean-) | Булевый флаг, указывающий, следует ли заменять отредактированный слайд существующим слайдом в оригинальной презентации на позиции, указанной |
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) property, либо он должен быть вставлен между существующим слайдом и предыдущим, без замены их содержимого.
|
|  | [getOutputFormat()](#getOutputFormat--) | Позволяет указать формат Presentation, который будет использоваться для сохранения документа |
|
|  | [setOutputFormat(PresentationFormats value)](#setOutputFormat-com.groupdocs.editor.formats.PresentationFormats-) | Позволяет указать формат Presentation, который будет использоваться для сохранения документа |
|
|  | [getSlideNumbersToDelete()](#getSlideNumbersToDelete--) | Позволяет задать массив с номерами слайдов, начиная с 1, которые должны быть удалены из презентации при её сохранении, если отредактированный слайд вставляется в существующую презентацию. |
|
|  | [setSlideNumbersToDelete(int[] value)](#setSlideNumbersToDelete-int---) | Позволяет задать массив с номерами слайдов, начиная с 1, которые должны быть удалены из презентации при её сохранении, если отредактированный слайд вставляется в существующую презентацию. |
|
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


Этот конструктор без параметров создаёт новый экземпляр PresentationSaveOptions с форматом вывода PPTX (может быть изменён затем через
OutputFormat
(#getOutputFormat.getOutputFormat/#setOutputFormat(PresentationFormats).setOutputFormat(PresentationFormats)) property)


### PresentationSaveOptions(PresentationFormats outputFormat) {#PresentationSaveOptions-com.groupdocs.editor.formats.PresentationFormats-}
```
public PresentationSaveOptions(PresentationFormats outputFormat)
```


Создаёт новый экземпляр PresentationSaveOptions с указанным
обязательным форматом вывода Presentation, в то время как все остальные параметры
по умолчанию


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | outputFormat | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) | Обязательный формат вывода, в котором должен быть сохранён документ Presentation |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Позволяет указать, изменить и получить пароль, который будет использоваться для
кодирование получаемого документа Presentation. По умолчанию равно NULL -
пароль не будет установлен. Установите NULL или пустую строку, чтобы удалить
пароль, если он был установлен ранее.


**Returns:**
java.lang.String -
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Позволяет задавать, изменять и получать пароль, который будет использоваться для кодирования получаемого документа Presentation.
По умолчанию равно NULL — пароль не будет установлен. Установите NULL или пустую строку, чтобы удалить пароль, если он был установлен ранее.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```


Позволяет вставлять отредактированный слайд в существующую презентацию вместо создания новой однослайдовой презентации (поведение по умолчанию).
Номер слайда — это номер, начинающийся с 1, слайда в презентации, загруженной в класс Editor. Если он равен 0 (значение по умолчанию), будет создана новая презентация с единственным отредактированным слайдом. Если он больше или меньше нуля, и существует корректная презентация, загруженная в класс Editor, отредактированный слайд, хранящийся во входном экземпляре EditableDocument, будет вставлен в эту презентацию.

<br />

*** ** * ** ***

> ```
> Given presentation has 5 slides:
>  SlideNumber  = 0; \u2014 ignore given presentation, create a new presentation and put edited slide into it.
>  SlideNumber  = 1; \u2014 replace the first slide with edited
>  SlideNumber  = 2; \u2014 replace the second slide with edited
>  SlideNumber  = 5; \u2014 replace the last (5th) slide with edited
>  SlideNumber  = 6; \u2014 replace the last (5th) slide with edited, because 6 is greater then 5 and thus is adjusted
>  SlideNumber = -1; \u2014 replace the last (5th) slide with edited, because "-1" means "last existing"
>  SlideNumber = -2; \u2014 replace the 4th slide with edited
>  SlideNumber = -3; \u2014 replace the 3rd slide with edited
>  SlideNumber = -4; \u2014 replace the 2nd slide with edited
>  SlideNumber = -5; \u2014 replace the first slide with edited
>  SlideNumber = -6; \u2014 replace the first slide with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />

<br />

*** ** * ** ***

 *SlideNumber*  integer property, if it is not in default state (reserved value '0'), represents a slide number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last slide. Negative values are also allowed and count slides from end. For example, "-1" implies last slide in a presentation, "-2" \\u2014 last but one, etc. Like with positive values, when negative slide number exceeds the total count of slides in the given presentation, it will be adjusted to the first slide. The  InsertAsNewSlide (#getInsertAsNewSlide.getInsertAsNewSlide/#setInsertAsNewSlide(boolean).setInsertAsNewSlide(boolean)) boolean property is tightly coupled with this one.

<br />



**Returns:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```


Позволяет вставлять отредактированный слайд в существующую презентацию вместо создания новой однослайдовой презентации (поведение по умолчанию).
Номер слайда — это номер, начинающийся с 1, слайда в презентации, загруженной в класс Editor. Если он равен 0 (значение по умолчанию), будет создана новая презентация с единственным отредактированным слайдом. Если он больше или меньше нуля, и существует корректная презентация, загруженная в класс Editor, отредактированный слайд, хранящийся во входном экземпляре EditableDocument, будет вставлен в эту презентацию.

<br />

*** ** * ** ***

> ```
> Given presentation has 5 slides:
>  SlideNumber  = 0; \u2014 ignore given presentation, create a new presentation and put edited slide into it.
>  SlideNumber  = 1; \u2014 replace the first slide with edited
>  SlideNumber  = 2; \u2014 replace the second slide with edited
>  SlideNumber  = 5; \u2014 replace the last (5th) slide with edited
>  SlideNumber  = 6; \u2014 replace the last (5th) slide with edited, because 6 is greater then 5 and thus is adjusted
>  SlideNumber = -1; \u2014 replace the last (5th) slide with edited, because "-1" means "last existing"
>  SlideNumber = -2; \u2014 replace the 4th slide with edited
>  SlideNumber = -3; \u2014 replace the 3rd slide with edited
>  SlideNumber = -4; \u2014 replace the 2nd slide with edited
>  SlideNumber = -5; \u2014 replace the first slide with edited
>  SlideNumber = -6; \u2014 replace the first slide with edited, because "-6" is greater then 5 and thus is adjusted
>  
> ```

<br />

<br />

*** ** * ** ***

 *SlideNumber*  integer property, if it is not in default state (reserved value '0'), represents a slide number, so it starts from 1, not from zero, and its max value is the amount of all existing slides in a presentation. However, if specified value is greater then amount of all slides, GroupDocs.Editor will adjust it to mark the last slide. Negative values are also allowed and count slides from end. For example, "-1" implies last slide in a presentation, "-2" \\u2014 last but one, etc. Like with positive values, when negative slide number exceeds the total count of slides in the given presentation, it will be adjusted to the first slide. The  InsertAsNewSlide (#getInsertAsNewSlide.getInsertAsNewSlide/#setInsertAsNewSlide(boolean).setInsertAsNewSlide(boolean)) boolean property is tightly coupled with this one.

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getInsertAsNewSlide() {#getInsertAsNewSlide--}
```
public final boolean getInsertAsNewSlide()
```


Булевый флаг, указывающий, следует ли заменять отредактированный слайд существующим слайдом в оригинальной презентации на позиции, указанной
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) property, либо он должен быть вставлен между существующим слайдом и предыдущим, без замены их содержимого.
По умолчанию false \\u2014 существующий слайд будет заменён. Это свойство игнорируется, если значение
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) свойство установлено в '0'.

<br />

*** ** * ** ***

По умолчанию слайд заменяется. Это означает, что если у данной презентации 5 слайдов, и SlideNumber (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))=4, то 4‑й слайд будет заменён новым отредактированным слайдом, при этом общее количество слайдов в презентации (5) останется без изменений. Однако если значение этого свойства установлено в  *true* , новый отредактированный слайд будет вставлен как 4‑й слайд, а все последующие слайды сместятся в конец: «старый» 4‑й слайд станет 5‑м, а 5‑й — 6‑м, и общее количество слайдов в презентации увеличится на один и станет равным 6.

<br />



**Returns:**
boolean
### setInsertAsNewSlide(boolean value) {#setInsertAsNewSlide-boolean-}
```
public final void setInsertAsNewSlide(boolean value)
```


Булевый флаг, указывающий, следует ли заменять отредактированный слайд существующим слайдом в оригинальной презентации на позиции, указанной
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) property, либо он должен быть вставлен между существующим слайдом и предыдущим, без замены их содержимого.
По умолчанию false \\u2014 существующий слайд будет заменён. Это свойство игнорируется, если значение
SlideNumber
(#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int)) свойство установлено в '0'.

<br />

*** ** * ** ***

По умолчанию слайд заменяется. Это означает, что если у данной презентации 5 слайдов, и SlideNumber (#getSlideNumber.getSlideNumber/#setSlideNumber(int).setSlideNumber(int))=4, то 4‑й слайд будет заменён новым отредактированным слайдом, при этом общее количество слайдов в презентации (5) останется без изменений. Однако если значение этого свойства установлено в  *true* , новый отредактированный слайд будет вставлен как 4‑й слайд, а все последующие слайды сместятся в конец: «старый» 4‑й слайд станет 5‑м, а 5‑й — 6‑м, и общее количество слайдов в презентации увеличится на один и станет равным 6.

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getOutputFormat() {#getOutputFormat--}
```
public final PresentationFormats getOutputFormat()
```


Позволяет указать формат Presentation, который будет использоваться для сохранения документа

<br />

*** ** * ** ***

Формат вывода обычно задаётся в конструкторе этого класса, поскольку он обязателен. Это свойство позволяет получить или изменить формат вывода позже, когда экземпляр класса [PresentationSaveOptions](../../com.groupdocs.editor.options/presentationsaveoptions) уже создан.

<br />



**Returns:**
[PresentationFormats](../../com.groupdocs.editor.formats/presentationformats)
### setOutputFormat(PresentationFormats value) {#setOutputFormat-com.groupdocs.editor.formats.PresentationFormats-}
```
public final void setOutputFormat(PresentationFormats value)
```


Позволяет указать формат Presentation, который будет использоваться для сохранения документа

<br />

*** ** * ** ***

Формат вывода обычно задаётся в конструкторе этого класса, поскольку он обязателен. Это свойство позволяет получить или изменить формат вывода позже, когда экземпляр класса [PresentationSaveOptions](../../com.groupdocs.editor.options/presentationsaveoptions) уже создан.

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PresentationFormats](../../com.groupdocs.editor.formats/presentationformats) |  |

### getSlideNumbersToDelete() {#getSlideNumbersToDelete--}
```
public final int[] getSlideNumbersToDelete()
```


Позволяет указать массив с номерами слайдов, начинающимися с 1, которые должны быть удалены из презентации при её сохранении, если отредактированный слайд вставляется в существующую презентацию. Когда отредактированный слайд сохраняется не как новая однослайдовая презентация (поведение по умолчанию), а вместо этого сохраняется в существующей презентации (используя #getSlideNumber().getSlideNumber() / #setSlideNumber(int).setSlideNumber(int)), также возможно удалить некоторые конкретные слайды из этой презентации, указав их номера в этом массиве. По умолчанию этот массив равен  null  \u2014 слайды не будут удаляться. Однако когда массив не null и не пуст, и содержит хотя бы один корректный номер слайда, после генерации выходного документа Presentation с содержимым отредактированного слайда, слайды с указанными номерами будут удалены из презентации непосредственно перед записью её содержимого в выходной поток или файл. Номера слайдов в этом массиве начинаются с 1, а не с 0. Неверные номера (меньше 1 или больше общего количества слайдов) будут игнорироваться.


**Returns:**
int[] — массив номеров слайдов, начинающихся с 1, которые следует удалить, или  null  если ничего не нужно удалять.

### setSlideNumbersToDelete(int[] value) {#setSlideNumbersToDelete-int---}
```
public final void setSlideNumbersToDelete(int[] value)
```


Позволяет указать массив с номерами слайдов, начинающимися с 1, которые должны быть удалены из презентации при её сохранении, если отредактированный слайд вставляется в существующую презентацию. Номера слайдов в этом массиве начинаются с 1. Неверные номера будут игнорироваться.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | int[] | Массив номеров слайдов, начинающихся с 1, для удаления (может быть  null  или пустым). |
|

