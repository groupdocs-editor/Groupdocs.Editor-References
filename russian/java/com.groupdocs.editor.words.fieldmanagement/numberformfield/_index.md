---
title: "NumberFormField"
second_title: "GroupDocs.Editor for Java API Справка"
description: "Представляет поле формы, принимающее числовой ввод."
type: docs
weight: 19
url: /ru/java/com.groupdocs.editor.words.fieldmanagement/numberformfield/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class NumberFormField implements IFormField
```

Представляет поле формы, принимающее числовой ввод.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [NumberFormField(String stylesheet, String name)](#NumberFormField-java.lang.String-java.lang.String-) | Инициализирует новый экземпляр класса [NumberFormField](../../com.groupdocs.editor.words.fieldmanagement/numberformfield) с указанными таблицей стилей и именем. |
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
|  | [getType()](#getType--) | Получает тип элемента формы, который для этого класса всегда равен FormFieldType.Number. |
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
|  | [getValue()](#getValue--) | Получает или задает значение элемента формы, представляющее число. |
|
|  | [setValue(float value)](#setValue-float-) | Получает или задает значение элемента формы, представляющее число. |
|
|  | [getMaxLength()](#getMaxLength--) | Получает или задаёт максимальную длину ввода для поля формы. |
|
|  | [setMaxLength(int value)](#setMaxLength-int-) | Получает или задаёт максимальную длину ввода для поля формы. |
|
### NumberFormField(String stylesheet, String name) {#NumberFormField-java.lang.String-java.lang.String-}
```
public NumberFormField(String stylesheet, String name)
```


Инициализирует новый экземпляр класса [NumberFormField](../../com.groupdocs.editor.words.fieldmanagement/numberformfield) с указанными таблицей стилей и именем.


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


Получает тип элемента формы, который для этого класса всегда равен FormFieldType.Number.


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
>  numberField.LocaleId = new CultureInfo("en-US").LCID;
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
>  numberField.LocaleId = new CultureInfo("en-US").LCID;
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
public final float getValue()
```


Получает или задает значение элемента формы, представляющее число.


**Returns:**
float
### setValue(float value) {#setValue-float-}
```
public final void setValue(float value)
```


Получает или задает значение элемента формы, представляющее число.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### getMaxLength() {#getMaxLength--}
```
public final int getMaxLength()
```


Получает или задаёт максимальную длину ввода для поля формы.


**Returns:**
int
### setMaxLength(int value) {#setMaxLength-int-}
```
public final void setMaxLength(int value)
```


Получает или задаёт максимальную длину ввода для поля формы.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

