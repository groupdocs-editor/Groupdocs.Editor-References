---
title: "InvalidFormField"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثل تحديث أسماء حقول النموذج غير الصالحة أثناء عملية FormFieldManager.FixInvalidFormFieldNames."
type: docs
weight: 18
url: /ar/java/com.groupdocs.editor.words.fieldmanagement/invalidformfield/
---
**Inheritance:**
java.lang.Object
```
public final class InvalidFormField
```

يمثل تحديث أسماء حقول النموذج غير الصالحة أثناء الـ
FormFieldManager.FixInvalidFormFieldNames
العملية.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [InvalidFormField(String name)](#InvalidFormField-java.lang.String-) | ينشئ مثيلاً جديدًا لفئة [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) باستخدام الاسم المحدد. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getName()](#getName--) | يحصل على الاسم الأصلي لحقل النموذج الذي لا يمكن تعديله خارج |
FormFieldManager
.
|
|  | [getFixedName()](#getFixedName--) | يحصل أو يعيّن الاسم الجديد لحقل النموذج بعد الإصلاح. |
|
|  | [setFixedName(String value)](#setFixedName-java.lang.String-) | يحصل أو يعيّن الاسم الجديد لحقل النموذج بعد الإصلاح. |
|
### InvalidFormField(String name) {#InvalidFormField-java.lang.String-}
```
public InvalidFormField(String name)
```


ينشئ مثيلاً جديدًا لفئة [InvalidFormField](../../com.groupdocs.editor.words.fieldmanagement/invalidformfield) باستخدام الاسم المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | الاسم الأصلي لحقل النموذج. |
|

### getName() {#getName--}
```
public final String getName()
```


يحصل على الاسم الأصلي لحقل النموذج الذي لا يمكن تعديله خارج
FormFieldManager
.


**Returns:**
java.lang.String
### getFixedName() {#getFixedName--}
```
public final String getFixedName()
```


يحصل أو يعيّن الاسم الجديد لحقل النموذج بعد الإصلاح.
هذا الاسم يزيل المعرفات الفريدة المكررة مع حقول النموذج الأخرى ويحدد اسم إشارة مرجعية فريدة.

<br />

*** ** * ** ***

```
 FixedName = String.format("%s_fixed", name); // as default value.
 
```

<br />



**Returns:**
java.lang.String
### setFixedName(String value) {#setFixedName-java.lang.String-}
```
public final void setFixedName(String value)
```


يحصل أو يعيّن الاسم الجديد لحقل النموذج بعد الإصلاح.
هذا الاسم يزيل المعرفات الفريدة المكررة مع حقول النموذج الأخرى ويحدد اسم إشارة مرجعية فريدة.

<br />

*** ** * ** ***

```
 FixedName = string.Format("{0}_fixed", name) // as default value.
 
```

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

