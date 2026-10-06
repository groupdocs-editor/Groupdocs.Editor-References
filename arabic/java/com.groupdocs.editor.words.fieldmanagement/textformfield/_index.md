---
title: "TextFormField"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثل حقل نموذج يقبل إدخال نص."
type: docs
weight: 20
url: /ar/java/com.groupdocs.editor.words.fieldmanagement/textformfield/
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

| منشئ | الوصف |
| --- | --- |
|  | [TextFormField(String stylesheet, String name)](#TextFormField-java.lang.String-java.lang.String-) | ينشئ مثيلاً جديدًا من الفئة [TextFormField](../../com.groupdocs.editor.words.fieldmanagement/textformfield) باستخدام ورقة الأنماط والاسم المحددين. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getStylesheet()](#getStylesheet--) | يحصل على ورقة الأنماط المطبقة على حقل النموذج. |
|
|  | [getReadonly()](#getReadonly--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان حقل النموذج للقراءة فقط. |
|
|  | [setReadonly(boolean value)](#setReadonly-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان حقل النموذج للقراءة فقط. |
|
|  | [getName()](#getName--) | يحصل على اسم حقل النموذج. |
|
|  | [getType()](#getType--) | يحصل على نوع حقل النموذج، والذي يكون دائمًا FormFieldType.Text لهذه الفئة. |
|
|  | [getLocaleId()](#getLocaleId--) | يحصل أو يعيّن معرف اللغة لحقل النموذج، والذي يمثل الثقافة أو الإعدادات الإقليمية المرتبطة بحقل النموذج. |
|
|  | [setLocaleId(int value)](#setLocaleId-int-) | يحصل أو يعيّن معرف اللغة لحقل النموذج، والذي يمثل الثقافة أو الإعدادات الإقليمية المرتبطة بحقل النموذج. |
|
|  | [getStatusText()](#getStatusText--) | يحصل أو يضبط نص الحالة المرتبط بحقل النموذج، |
مصدر النص المعروض في شريط الحالة عندما يكون حقل النموذج في حالة التركيز.
|
|  | [setStatusText(HelpText value)](#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | يحصل أو يضبط نص الحالة المرتبط بحقل النموذج، |
مصدر النص المعروض في شريط الحالة عندما يكون حقل النموذج في حالة التركيز.
|
|  | [getHelpText()](#getHelpText--) | يحصل أو يضبط نص المساعدة المرتبط بحقل النموذج، |
مصدر النص المعروض في مربع الرسالة عندما يكون حقل النموذج في حالة التركيز ويضغط المستخدم على F1.
|
|  | [setHelpText(HelpText value)](#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | يحصل أو يضبط نص المساعدة المرتبط بحقل النموذج، |
مصدر النص المعروض في مربع الرسالة عندما يكون حقل النموذج في حالة التركيز ويضغط المستخدم على F1.
|
|  | [getValue()](#getValue--) | يحصل أو يضبط قيمة حقل النموذج، التي تمثل مدخل النص. |
|
|  | [setValue(String value)](#setValue-java.lang.String-) | يحصل أو يضبط قيمة حقل النموذج، التي تمثل مدخل النص. |
|
|  | [getMaxLength()](#getMaxLength--) | يحصل أو يضبط الحد الأقصى لطول المدخل لحقل النموذج. |
|
|  | [setMaxLength(int value)](#setMaxLength-int-) | يحصل أو يضبط الحد الأقصى لطول المدخل لحقل النموذج. |
|
### TextFormField(String stylesheet, String name) {#TextFormField-java.lang.String-java.lang.String-}
```
public TextFormField(String stylesheet, String name)
```


ينشئ مثيلاً جديدًا من الفئة [TextFormField](../../com.groupdocs.editor.words.fieldmanagement/textformfield) باستخدام ورقة الأنماط والاسم المحددين.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | ورقة الأنماط | java.lang.String | ورقة الأنماط لتطبيقها على حقل النموذج. |
|
|  | الاسم | java.lang.String | اسم حقل النموذج. |
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


يحصل أو يعيّن قيمة تشير إلى ما إذا كان حقل النموذج للقراءة فقط.


**Returns:**
boolean
### setReadonly(boolean value) {#setReadonly-boolean-}
```
public final void setReadonly(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كان حقل النموذج للقراءة فقط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

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


يحصل على نوع حقل النموذج، والذي يكون دائمًا FormFieldType.Text لهذه الفئة.


**Returns:**
int
### getLocaleId() {#getLocaleId--}
```
public final int getLocaleId()
```


يحصل أو يعيّن معرف اللغة لحقل النموذج، والذي يمثل الثقافة أو الإعدادات الإقليمية المرتبطة بحقل النموذج.

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

خاصية LocaleId تحدد معرف اللغة (LCID) الذي يتطابق مع ثقافة أو منطقة معينة.

<br />



**Returns:**
int
### setLocaleId(int value) {#setLocaleId-int-}
```
public final void setLocaleId(int value)
```


يحصل أو يعيّن معرف اللغة لحقل النموذج، والذي يمثل الثقافة أو الإعدادات الإقليمية المرتبطة بحقل النموذج.

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

خاصية LocaleId تحدد معرف اللغة (LCID) الذي يتطابق مع ثقافة أو منطقة معينة.

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getStatusText() {#getStatusText--}
```
public final HelpText getStatusText()
```


يحصل أو يضبط نص الحالة المرتبط بحقل النموذج،
مصدر النص المعروض في شريط الحالة عندما يكون حقل النموذج في حالة التركيز.

<br />

*** ** * ** ***

إذا تم تعيينها إلى false ، لن يتم تطبيق نص الحالة.

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setStatusText(HelpText value) {#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setStatusText(HelpText value)
```


يحصل أو يضبط نص الحالة المرتبط بحقل النموذج،
مصدر النص المعروض في شريط الحالة عندما يكون حقل النموذج في حالة التركيز.

<br />

*** ** * ** ***

إذا تم تعيينها إلى false ، لن يتم تطبيق نص الحالة.

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getHelpText() {#getHelpText--}
```
public final HelpText getHelpText()
```


يحصل أو يضبط نص المساعدة المرتبط بحقل النموذج،
مصدر النص المعروض في مربع الرسالة عندما يكون حقل النموذج في حالة التركيز ويضغط المستخدم على F1.

<br />

*** ** * ** ***

إذا تم تعيينها إلى false ، لن يتم تطبيق نص المساعدة.

<br />



**Returns:**
[HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext)
### setHelpText(HelpText value) {#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-}
```
public final void setHelpText(HelpText value)
```


يحصل أو يضبط نص المساعدة المرتبط بحقل النموذج،
مصدر النص المعروض في مربع الرسالة عندما يكون حقل النموذج في حالة التركيز ويضغط المستخدم على F1.

<br />

*** ** * ** ***

إذا تم تعيينها إلى false ، لن يتم تطبيق نص المساعدة.

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [HelpText](../../com.groupdocs.editor.words.fieldmanagement/helptext) |  |

### getValue() {#getValue--}
```
public final String getValue()
```


يحصل أو يضبط قيمة حقل النموذج، التي تمثل مدخل النص.


**Returns:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```


يحصل أو يضبط قيمة حقل النموذج، التي تمثل مدخل النص.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getMaxLength() {#getMaxLength--}
```
public final int getMaxLength()
```


يحصل أو يضبط الحد الأقصى لطول المدخل لحقل النموذج.


**Returns:**
int
### setMaxLength(int value) {#setMaxLength-int-}
```
public final void setMaxLength(int value)
```


يحصل أو يضبط الحد الأقصى لطول المدخل لحقل النموذج.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

