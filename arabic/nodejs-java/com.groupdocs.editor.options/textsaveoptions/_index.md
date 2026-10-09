---
title: "TextSaveOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يسمح بتحديد خيارات مخصصة لإنشاء وحفظ مستندات نصية عادية بصيغة TXT"
type: docs
weight: 41
url: /ar/nodejs-java/com.groupdocs.editor.options/textsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class TextSaveOptions implements ISaveOptions
```

يسمح بتحديد خيارات مخصصة لإنشاء وحفظ نص عادي (TXT)
المستندات

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TextSaveOptions()](#TextSaveOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getEncoding()](#getEncoding--) | ترميز الأحرف لمستند النص، والذي سيُطبق على |
حفظه
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | ترميز الأحرف لمستند النص، والذي سيُطبق على |
حفظه
|
|  | [getAddBidiMarks()](#getAddBidiMarks--) | يحدد ما إذا كان يجب إضافة علامات ثنائية الاتجاه قبل كل تشغيل BiDi عند |
تصدير بصيغة نص عادي.
|
|  | [setAddBidiMarks(boolean value)](#setAddBidiMarks-boolean-) | يحدد ما إذا كان يجب إضافة علامات ثنائية الاتجاه قبل كل تشغيل BiDi عند |
تصدير بصيغة نص عادي
|
|  | [getPreserveTableLayout()](#getPreserveTableLayout--) | يحدد ما إذا كان يجب على البرنامج محاولة الحفاظ على تنسيق الجداول |
عند الحفظ بصيغة نص عادي.
|
|  | [setPreserveTableLayout(boolean value)](#setPreserveTableLayout-boolean-) | يحدد ما إذا كان يجب على البرنامج محاولة الحفاظ على تنسيق الجداول |
عند الحفظ بصيغة نص عادي.
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
حفظه


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


ترميز الأحرف لمستند النص، والذي سيُطبق على
حفظه


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.nio.charset.Charset |  |

### getAddBidiMarks() {#getAddBidiMarks--}
```
public final boolean getAddBidiMarks()
```


يحدد ما إذا كان يجب إضافة علامات ثنائية الاتجاه قبل كل تشغيل BiDi عند
تصدير بصيغة نص عادي. القيمة الافتراضية هي 'false' \\u2014 لا تضف علامات BiDi.


**Returns:**
منطقي -
### setAddBidiMarks(boolean value) {#setAddBidiMarks-boolean-}
```
public final void setAddBidiMarks(boolean value)
```


يحدد ما إذا كان يجب إضافة علامات ثنائية الاتجاه قبل كل تشغيل BiDi عند
تصدير بصيغة نص عادي


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getPreserveTableLayout() {#getPreserveTableLayout--}
```
public final boolean getPreserveTableLayout()
```


يحدد ما إذا كان يجب على البرنامج محاولة الحفاظ على تنسيق الجداول
عند الحفظ بصيغة نص عادي. القيمة الافتراضية هي false.


**Returns:**
منطقي -
### setPreserveTableLayout(boolean value) {#setPreserveTableLayout-boolean-}
```
public final void setPreserveTableLayout(boolean value)
```


يحدد ما إذا كان يجب على البرنامج محاولة الحفاظ على تنسيق الجداول
عند الحفظ بصيغة نص عادي. القيمة الافتراضية هي false.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

