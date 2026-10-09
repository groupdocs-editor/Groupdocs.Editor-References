---
title: "CurrentDateFormField"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يمثل حقل نموذج يعرض التاريخ الحالي."
type: docs
weight: 11
url: /ar/nodejs-java/com.groupdocs.editor.words.fieldmanagement/currentdateformfield/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.words.fieldmanagement.IFormField](../../com.groupdocs.editor.words.fieldmanagement/iformfield)
```
public final class CurrentDateFormField implements IFormField
```

يمثل حقل نموذج يعرض التاريخ الحالي.

## المنشئات

| المنشئ | الوصف |
| --- | --- |
|  | [CurrentDateFormField(String stylesheet, String name)](#CurrentDateFormField-java.lang.String-java.lang.String-) | ينشئ مثيلاً جديدًا من الفئة [CurrentDateFormField](../../com.groupdocs.editor.words.fieldmanagement/currentdateformfield) بالورقة النمطية والاسم المحددين. |
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
|  | [getType()](#getType--) | يحصل على نوع حقل النموذج، والذي يكون دائمًا FormFieldType.CurrentDate لهذا الصنف. |
|
|  | [getLocaleId()](#getLocaleId--) | يحصل أو يضبط معرف اللغة لحقل النموذج، الذي يمثل الثقافة أو الإعدادات الإقليمية المرتبطة بحقل النموذج. |
|
|  | [setLocaleId(int value)](#setLocaleId-int-) | يحصل أو يضبط معرف اللغة لحقل النموذج، الذي يمثل الثقافة أو الإعدادات الإقليمية المرتبطة بحقل النموذج. |
|
|  | [getStatusText()](#getStatusText--) | يحصل أو يضبط نص الحالة المرتبط بحقل النموذج، مصدر النص المعروض في شريط الحالة عندما يكون حقل النموذج في التركيز. |
|
|  | [setStatusText(HelpText value)](#setStatusText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | يحصل أو يضبط نص الحالة المرتبط بحقل النموذج، مصدر النص المعروض في شريط الحالة عندما يكون حقل النموذج في التركيز. |
|
|  | [getHelpText()](#getHelpText--) | يحصل أو يضبط نص المساعدة المرتبط بحقل النموذج، مصدر النص المعروض في مربع رسالة عندما يكون حقل النموذج في التركيز ويضغط المستخدم F1. |
|
|  | [setHelpText(HelpText value)](#setHelpText-com.groupdocs.editor.words.fieldmanagement.HelpText-) | يحصل أو يضبط نص المساعدة المرتبط بحقل النموذج، مصدر النص المعروض في مربع رسالة عندما يكون حقل النموذج في التركيز ويضغط المستخدم F1. |
|
|  | [getValue()](#getValue--) | يحصل أو يضبط قيمة حقل النموذج، التي تمثل التاريخ الحالي. |
|
|  | [setValue(Date value)](#setValue-java.util.Date-) | يحصل أو يضبط قيمة حقل النموذج، التي تمثل التاريخ الحالي. |
|
### CurrentDateFormField(String stylesheet, String name) {#CurrentDateFormField-java.lang.String-java.lang.String-}
```
public CurrentDateFormField(String stylesheet, String name)
```


ينشئ مثيلاً جديدًا من الفئة [CurrentDateFormField](../../com.groupdocs.editor.words.fieldmanagement/currentdateformfield) بالورقة النمطية والاسم المحددين.


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


يحصل على نوع حقل النموذج، والذي يكون دائمًا FormFieldType.CurrentDate لهذا الصنف.


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
>  currentTimeField.LocaleId = new CultureInfo("en-US").LCID;
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
>  currentTimeField.LocaleId = new CultureInfo("en-US").LCID;
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


يحصل أو يضبط نص الحالة المرتبط بحقل النموذج، مصدر النص المعروض في شريط الحالة عندما يكون حقل النموذج في التركيز.

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


يحصل أو يضبط نص الحالة المرتبط بحقل النموذج، مصدر النص المعروض في شريط الحالة عندما يكون حقل النموذج في التركيز.

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


يحصل أو يضبط نص المساعدة المرتبط بحقل النموذج، مصدر النص المعروض في مربع رسالة عندما يكون حقل النموذج في التركيز ويضغط المستخدم F1.

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


يحصل أو يضبط نص المساعدة المرتبط بحقل النموذج، مصدر النص المعروض في مربع رسالة عندما يكون حقل النموذج في التركيز ويضغط المستخدم F1.

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
public final Date getValue()
```


يحصل أو يضبط قيمة حقل النموذج، التي تمثل التاريخ الحالي.


**Returns:**
java.util.Date
### setValue(Date value) {#setValue-java.util.Date-}
```
public final void setValue(Date value)
```


يحصل أو يضبط قيمة حقل النموذج، التي تمثل التاريخ الحالي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.util.Date |  |

