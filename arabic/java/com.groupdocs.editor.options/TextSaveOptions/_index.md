---
title: "TextSaveOptions"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يسمح بتحديد خيارات مخصصة لإنشاء وحفظ مستندات النص العادي TXT"
type: docs
weight: 41
url: /ar/java/com.groupdocs.editor.options/textsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class TextSaveOptions implements ISaveOptions
```

يسمح بتحديد خيارات مخصصة لإنشاء وحفظ النص العادي (TXT)
المستندات

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TextSaveOptions()](#TextSaveOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | ترميز الأحرف لمستند النص، والذي سيُطبق على |
الحفظ
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | ترميز الأحرف لمستند النص، والذي سيُطبق على |
الحفظ
|
|  | [getAddBidiMarks()](#getAddBidiMarks--) | يحدد ما إذا كان يجب إضافة علامات ثنائية الاتجاه قبل كل تشغيل BiDi عند |
تصدير بتنسيق النص العادي.
|
|  | [setAddBidiMarks(boolean value)](#setAddBidiMarks-boolean-) | يحدد ما إذا كان يجب إضافة علامات ثنائية الاتجاه قبل كل تشغيل BiDi عند |
التصدير بتنسيق النص العادي
|
|  | [getPreserveTableLayout()](#getPreserveTableLayout--) | يحدد ما إذا كان يجب على البرنامج محاولة الحفاظ على تنسيق الجداول |
عند الحفظ بتنسيق النص العادي.
|
|  | [setPreserveTableLayout(boolean value)](#setPreserveTableLayout-boolean-) | يحدد ما إذا كان يجب على البرنامج محاولة الحفاظ على تنسيق الجداول |
عند الحفظ بتنسيق النص العادي.
|
### TextSaveOptions() {#TextSaveOptions--}
```
public TextSaveOptions()
```


### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


ترميز الأحرف لمستند النص، والذي سيُطبق على
الحفظ


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


ترميز الأحرف لمستند النص، والذي سيُطبق على
الحفظ


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.nio.charset.Charset |  |

### getAddBidiMarks() {#getAddBidiMarks--}
```
public final boolean getAddBidiMarks()
```


يحدد ما إذا كان يجب إضافة علامات ثنائية الاتجاه قبل كل تشغيل BiDi عند
تصدير بتنسيق النص العادي. القيمة الافتراضية هي 'false' \u2014 لا تضف علامات BiDi.


**Returns:**
boolean -
### setAddBidiMarks(boolean value) {#setAddBidiMarks-boolean-}
```
public final void setAddBidiMarks(boolean value)
```


يحدد ما إذا كان يجب إضافة علامات ثنائية الاتجاه قبل كل تشغيل BiDi عند
التصدير بتنسيق النص العادي


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getPreserveTableLayout() {#getPreserveTableLayout--}
```
public final boolean getPreserveTableLayout()
```


يحدد ما إذا كان يجب على البرنامج محاولة الحفاظ على تنسيق الجداول
عند الحفظ بتنسيق النص العادي. القيمة الافتراضية هي false.


**Returns:**
boolean -
### setPreserveTableLayout(boolean value) {#setPreserveTableLayout-boolean-}
```
public final void setPreserveTableLayout(boolean value)
```


يحدد ما إذا كان يجب على البرنامج محاولة الحفاظ على تنسيق الجداول
عند الحفظ بتنسيق النص العادي. القيمة الافتراضية هي false.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

