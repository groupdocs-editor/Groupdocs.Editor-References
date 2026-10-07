---
title: "CheckBoxForm"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Представляет поле формы, отображающее флажок."
type: docs
weight: 10
url: /ru/java/com.groupdocs.editor.words.fieldmanagement/checkboxform/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class CheckBoxForm implements IFormField
```

Представляет поле формы, отображающее флажок.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [CheckBoxForm(String stylesheet, String name)](#CheckBoxForm-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса [CheckBoxForm](../../com.groupdocs.editor.words.fieldmanagement/checkboxform) с указанными таблицей стилей и именем. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getStylesheet()](#getStylesheet--) | Получает таблицу стилей, применённую к полю формы. |
|
|  | [getReadonly()](#getReadonly--) | Получает или задаёт значение, указывающее, является ли поле формы только для чтения. |
|
|  | [setReadonly(boolean value)](#setReadonly-boolean-) | Получает или задаёт значение, указывающее, является ли поле формы только для чтения. |
|
|  | [getName()](#getName--) | Получает имя поля формы. |
|
|  | [getType()](#getType--) | Получает тип поля формы, который всегда равен FormFieldType.CheckBox для этого класса. |
|
|  | [getLocaleId()](#getLocaleId--) | Получает или задаёт идентификатор локали поля формы, представляющий культуру или региональные настройки, связанные с полем формы. |
|
|  | [setLocaleId(int value)](#setLocaleId-int-) | Получает или задаёт идентификатор локали поля формы, представляющий культуру или региональные настройки, связанные с полем формы. |
|
|  | [getStatusText()](#getStatusText--) | Получает или задает текст статуса, связанный с элементом формы, источник текста, отображаемого в строке состояния, когда элемент формы находится в фокусе. |
|
|  | [setStatusText(HelpText value)](#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Получает или задает текст статуса, связанный с элементом формы, источник текста, отображаемого в строке состояния, когда элемент формы находится в фокусе. |
|
|  | [getHelpText()](#getHelpText--) | Получает или задаёт справочный текст, связанный с полем формы, источник текста, отображаемого в диалоговом окне, когда поле формы имеет фокус и пользователь нажимает F1. |
|
|  | [setHelpText(HelpText value)](#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Получает или задаёт справочный текст, связанный с полем формы, источник текста, отображаемого в диалоговом окне, когда поле формы имеет фокус и пользователь нажимает F1. |
|
|  | [getValue()](#getValue--) | Получает или задает значение поля формы, которое представляет состояние чекбокса. |
|
|  | [setValue(boolean value)](#setValue-boolean-) | Получает или задает значение поля формы, которое представляет состояние чекбокса. |
|
### CheckBoxForm(String stylesheet, String name) {#CheckBoxForm-java.lang.String-java.lang.String-}
```
public CheckBoxForm(String stylesheet, String name)
```


Инициализирует новый экземпляр класса [CheckBoxForm](../../com.groupdocs.editor.words.fieldmanagement/checkboxform) с указанными таблицей стилей и именем.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | таблица стилей | java.lang.String | Таблица стилей, применяемая к полю формы. |
|
|  | name | java.lang.String | Имя поля формы. |
|

### getStylesheet() {#getStylesheet--}
```
public final String getStylesheet()
```


Получает таблицу стилей, применённую к полю формы.


**Returns:**
java.lang.String
### getReadonly() {#getReadonly--}
```
public final boolean getReadonly()
```


Получает или задаёт значение, указывающее, является ли поле формы только для чтения.


**Returns:**
boolean
### setReadonly(boolean value) {#setReadonly-boolean-}
```
public final void setReadonly(boolean value)
```


Получает или задаёт значение, указывающее, является ли поле формы только для чтения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getName() {#getName--}
```
public final String getName()
```


Получает имя поля формы.


**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


Получает тип поля формы, который всегда равен FormFieldType.CheckBox для этого класса.


**Returns:**
int
### getLocaleId() {#getLocaleId--}
```
public final int getLocaleId()
```


Получает или задаёт идентификатор локали поля формы, представляющий культуру или региональные настройки, связанные с полем формы.

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set the LocaleId property:
>   Set the LocaleId to represent the English (United States) culture
>  checkBoxField.LocaleId = new CultureInfo("en-US").LCID;
>  
>  
> ```

<br />

<br />

*** ** * ** ***

Свойство LocaleId указывает идентификатор локали (LCID), который соответствует определённой культуре или региону.

<br />



**Returns:**
int
### setLocaleId(int value) {#setLocaleId-int-}
```
public final void setLocaleId(int value)
```


Получает или задаёт идентификатор локали поля формы, представляющий культуру или региональные настройки, связанные с полем формы.

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set the LocaleId property:
>   Set the LocaleId to represent the English (United States) culture
>  checkBoxField.LocaleId = new CultureInfo("en-US").LCID;
>  
>  
> ```

<br />

<br />

*** ** * ** ***

Свойство LocaleId указывает идентификатор локали (LCID), который соответствует определённой культуре или региону.

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getStatusText() {#getStatusText--}
```
public final HelpText getStatusText()
```


Получает или задает текст статуса, связанный с элементом формы, источник текста, отображаемого в строке состояния, когда элемент формы находится в фокусе.

<br />

*** ** * ** ***

Если установить значение false, текст статуса не будет применён.

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setStatusText(HelpText value) {#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setStatusText(HelpText value)
```


Получает или задает текст статуса, связанный с элементом формы, источник текста, отображаемого в строке состояния, когда элемент формы находится в фокусе.

<br />

*** ** * ** ***

Если установить значение false, текст статуса не будет применён.

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getHelpText() {#getHelpText--}
```
public final HelpText getHelpText()
```


Получает или задаёт справочный текст, связанный с полем формы, источник текста, отображаемого в диалоговом окне, когда поле формы имеет фокус и пользователь нажимает F1.

<br />

*** ** * ** ***

Если установить значение false, справочный текст не будет применён.

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setHelpText(HelpText value) {#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setHelpText(HelpText value)
```


Получает или задаёт справочный текст, связанный с полем формы, источник текста, отображаемого в диалоговом окне, когда поле формы имеет фокус и пользователь нажимает F1.

<br />

*** ** * ** ***

Если установить значение false, справочный текст не будет применён.

<br />



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getValue() {#getValue--}
```
public final boolean getValue()
```


Получает или задает значение поля формы, которое представляет состояние чекбокса.


**Returns:**
boolean
### setValue(boolean value) {#setValue-boolean-}
```
public final void setValue(boolean value)
```


Получает или задает значение поля формы, которое представляет состояние чекбокса.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

