---
title: "TextFormField"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يمثل حقل نموذج يقبل إدخال نص."
type: docs
weight: 20
url: /ar/nodejs-java/com.groupdocs.editor.words.fieldmanagement/textformfield/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class TextFormField implements IFormField
```

يمثل حقل نموذج يقبل إدخال نص.

## المنشئات

| المنشئ | الوصف |
| --- | --- |
|  | [TextFormField(String stylesheet, String name)](#TextFormField-java.lang.String-java.lang.String-) | Initializes a new instance of the [TextFormField](../../com.groupdocs.editor.words.fieldmanagement/textformfield) class with the specified stylesheet and name. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getStylesheet()](#getStylesheet--) | يحصل على ورقة الأنماط المطبقة على حقل النموذج. |
|
|  | [getReadonly()](#getReadonly--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان حقل النموذج للقراءة فقط. |
|
|  | [setReadonly(boolean value)](#setReadonly-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان حقل النموذج للقراءة فقط. |
|
|  | [getName()](#getName--) | يحصل على اسم حقل النموذج. |
|
|  | [getType()](#getType--) | Gets the type of the form field, which is always FormFieldType.Text for this class. |
|
|  | [getLocaleId()](#getLocaleId--) | يحصل أو يضبط معرف اللغة لحقل النموذج، الذي يمثل الثقافة أو الإعدادات الإقليمية المرتبطة بحقل النموذج. |
|
|  | [setLocaleId(int value)](#setLocaleId-int-) | يحصل أو يضبط معرف اللغة لحقل النموذج، الذي يمثل الثقافة أو الإعدادات الإقليمية المرتبطة بحقل النموذج. |
|
|  | [getStatusText()](#getStatusText--) | Gets or sets the status text associated with the form field, |
the source of the text that's displayed in the status bar when a form field has the focus.
|
|  | [setStatusText(HelpText value)](#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Gets or sets the status text associated with the form field, |
the source of the text that's displayed in the status bar when a form field has the focus.
|
|  | [getHelpText()](#getHelpText--) | Gets or sets the help text associated with the form field, |
the source of the text that's displayed in a message box when a form field has the focus and the user presses F1.
|
|  | [setHelpText(HelpText value)](#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | Gets or sets the help text associated with the form field, |
the source of the text that's displayed in a message box when a form field has the focus and the user presses F1.
|
|  | [getValue()](#getValue--) | Gets or sets the value of the form field, which represents the text input. |
|
|  | [setValue(String value)](#setValue-java.lang.String-) | Gets or sets the value of the form field, which represents the text input. |
|
|  | [getMaxLength()](#getMaxLength--) | يحصل أو يضبط الحد الأقصى لطول الإدخال لحقل النموذج. |
|
|  | [setMaxLength(int value)](#setMaxLength-int-) | يحصل أو يضبط الحد الأقصى لطول الإدخال لحقل النموذج. |
|
### TextFormField(String stylesheet, String name) {#TextFormField-java.lang.String-java.lang.String-}
```
public TextFormField(String stylesheet, String name)
```


Initializes a new instance of the [TextFormField](../../com.groupdocs.editor.words.fieldmanagement/textformfield) class with the specified stylesheet and name.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | ورقة الأنماط | java.lang.String | The stylesheet to apply to the form field. |
|
|  | الاسم | java.lang.String | The name of the form field. |
|

### getStylesheet() {#getStylesheet--}
```
public final String getStylesheet()
```


يحصل على ورقة الأنماط المطبقة على حقل النموذج.


**Returns:**
java.lang.String
### getReadonly() {#getReadonly--}
```
public final boolean getReadonly()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان حقل النموذج للقراءة فقط.


**Returns:**
boolean
### setReadonly(boolean value) {#setReadonly-boolean-}
```
public final void setReadonly(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كان حقل النموذج للقراءة فقط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getName() {#getName--}
```
public final String getName()
```


يحصل على اسم حقل النموذج.


**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


Gets the type of the form field, which is always FormFieldType.Text for this class.


**Returns:**
int
### getLocaleId() {#getLocaleId--}
```
public final int getLocaleId()
```


يحصل أو يضبط معرف اللغة لحقل النموذج، الذي يمثل الثقافة أو الإعدادات الإقليمية المرتبطة بحقل النموذج.

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set the LocaleId property:
>   Set the LocaleId to represent the English (United States) culture
>  textField.LocaleId = new CultureInfo("en-US").LCID;
>  
>  
> ```

<br />

<br />

*** ** * ** ***

The LocaleId property specifies a locale identifier (LCID) that corresponds to a particular culture or region.

<br />



**Returns:**
int
### setLocaleId(int value) {#setLocaleId-int-}
```
public final void setLocaleId(int value)
```


يحصل أو يضبط معرف اللغة لحقل النموذج، الذي يمثل الثقافة أو الإعدادات الإقليمية المرتبطة بحقل النموذج.

<br />

*** ** * ** ***

> ```
>  The following example demonstrates how to set the LocaleId property:
>   Set the LocaleId to represent the English (United States) culture
>  textField.LocaleId = new CultureInfo("en-US").LCID;
>  
>  
> ```

<br />

<br />

*** ** * ** ***

The LocaleId property specifies a locale identifier (LCID) that corresponds to a particular culture or region.

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getStatusText() {#getStatusText--}
```
public final HelpText getStatusText()
```


Gets or sets the status text associated with the form field,
the source of the text that's displayed in the status bar when a form field has the focus.

<br />

*** ** * ** ***

If set to  false , the status text will not be applied.

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setStatusText(HelpText value) {#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setStatusText(HelpText value)
```


Gets or sets the status text associated with the form field,
the source of the text that's displayed in the status bar when a form field has the focus.

<br />

*** ** * ** ***

If set to  false , the status text will not be applied.

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getHelpText() {#getHelpText--}
```
public final HelpText getHelpText()
```


Gets or sets the help text associated with the form field,
the source of the text that's displayed in a message box when a form field has the focus and the user presses F1.

<br />

*** ** * ** ***

If set to  false , the help text will not be applied.

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setHelpText(HelpText value) {#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setHelpText(HelpText value)
```


Gets or sets the help text associated with the form field,
the source of the text that's displayed in a message box when a form field has the focus and the user presses F1.

<br />

*** ** * ** ***

If set to  false , the help text will not be applied.

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getValue() {#getValue--}
```
public final String getValue()
```


Gets or sets the value of the form field, which represents the text input.


**Returns:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```


Gets or sets the value of the form field, which represents the text input.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getMaxLength() {#getMaxLength--}
```
public final int getMaxLength()
```


يحصل أو يضبط الحد الأقصى لطول الإدخال لحقل النموذج.


**Returns:**
int
### setMaxLength(int value) {#setMaxLength-int-}
```
public final void setMaxLength(int value)
```


يحصل أو يضبط الحد الأقصى لطول الإدخال لحقل النموذج.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

