---
title: "MarkdownSaveOptions"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يسمح بتحديد خيارات مخصصة لإنشاء وحفظ مستندات Markdown"
type: docs
weight: 24
url: /ar/java/com.groupdocs.editor.options/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class MarkdownSaveOptions implements ISaveOptions
```

يسمح بتحديد خيارات مخصصة لإنشاء وحفظ مستندات Markdown

<br />

*** ** * ** ***

يجب على المستخدم تطبيق فئة MarkdownSaveOptions عندما يكون هناك مثيل من فئة EditableDocument يحتوي على محتوى مستند مُحرّر، ويتطلب حفظ هذا المحتوى إلى مستند جديد بصيغة Markdown.

<br />


## المنشئات

| منشئ | الوصف |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | يفعل آليات تحسين الذاكرة أثناء إنشاء المستند من HTML، مما يقلل الأداء كتكلفة لتقليل استهلاك الذاكرة. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | يفعل آليات تحسين الذاكرة أثناء إنشاء المستند من HTML، مما يقلل الأداء كتكلفة لتقليل استهلاك الذاكرة. |
|
|  | [getTableContentAlignment()](#getTableContentAlignment--) | يحدد Allow كيفية محاذاة المحتويات في الجداول عند التصدير إلى صيغة Markdown. |
|
|  | [setTableContentAlignment(int value)](#setTableContentAlignment-int-) | يحدد Allow كيفية محاذاة المحتويات في الجداول عند التصدير إلى صيغة Markdown. |
|
|  | [getImagesFolder()](#getImagesFolder--) | يحدد المجلد الفعلي حيث يتم حفظ الصور عند تصدير مستند إلى |
صيغة Markdown.
|
|  | [setImagesFolder(String value)](#setImagesFolder-java.lang.String-) | يحدد المجلد الفعلي حيث يتم حفظ الصور عند تصدير مستند إلى |
صيغة Markdown.
|
|  | [getExportImagesAsBase64()](#getExportImagesAsBase64--) | يحدد ما إذا كانت الصور تُحفظ بصيغة Base64 في ملف الإخراج. |
|
|  | [setExportImagesAsBase64(boolean value)](#setExportImagesAsBase64-boolean-) | يحدد ما إذا كانت الصور تُحفظ بصيغة Base64 في ملف الإخراج. |
|
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```


### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


يفعل آليات تحسين الذاكرة أثناء إنشاء المستند من HTML، مما يقلل الأداء كتكلفة لتقليل استهلاك الذاكرة.
ضبط هذا الخيار على
true
يمكن أن يقلل بشكل كبير من استهلاك الذاكرة أثناء إنشاء مستندات كبيرة على حساب بطء وقت الحفظ.
القيمة الافتراضية هي
false
(تم تعطيل تحسين الذاكرة من أجل أداء أفضل).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


يفعل آليات تحسين الذاكرة أثناء إنشاء المستند من HTML، مما يقلل الأداء كتكلفة لتقليل استهلاك الذاكرة.
ضبط هذا الخيار على
true
يمكن أن يقلل بشكل كبير من استهلاك الذاكرة أثناء إنشاء مستندات كبيرة على حساب بطء وقت الحفظ.
القيمة الافتراضية هي
false
(تم تعطيل تحسين الذاكرة من أجل أداء أفضل).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getTableContentAlignment() {#getTableContentAlignment--}
```
public final int getTableContentAlignment()
```


يحدد Allow كيفية محاذاة المحتويات في الجداول عند التصدير إلى صيغة Markdown.
القيمة الافتراضية هي [MarkdownTableContentAlignment.Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment#Auto).
القيمة: محاذاة محتوى الجدول


**Returns:**
int
### setTableContentAlignment(int value) {#setTableContentAlignment-int-}
```
public final void setTableContentAlignment(int value)
```


يحدد Allow كيفية محاذاة المحتويات في الجداول عند التصدير إلى صيغة Markdown.
القيمة الافتراضية هي [MarkdownTableContentAlignment.Auto](../../com.groupdocs.editor.options/markdowntablecontentalignment#Auto).
القيمة: محاذاة محتوى الجدول


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### getImagesFolder() {#getImagesFolder--}
```
public final String getImagesFolder()
```


يحدد المجلد الفعلي حيث يتم حفظ الصور عند تصدير مستند إلى
صيغة Markdown. القيمة الافتراضية هي null.

<br />

*** ** * ** ***

إذا لم يتم تحديد كل من ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) ولا ExportImagesAsBase64 (#getExportImagesAsBase64.getExportImagesAsBase64/#setExportImagesAsBase64(boolean).setExportImagesAsBase64(boolean)) من قبل المستخدم، فستحاول GroupDocs.Editor تحديد ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) بنفسها وتطبيقه عند النجاح.

<br />



**Returns:**
java.lang.String
### setImagesFolder(String value) {#setImagesFolder-java.lang.String-}
```
public final void setImagesFolder(String value)
```


يحدد المجلد الفعلي حيث يتم حفظ الصور عند تصدير مستند إلى
صيغة Markdown. القيمة الافتراضية هي null.

<br />

*** ** * ** ***

إذا لم يتم تحديد كل من ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) ولا ExportImagesAsBase64 (#getExportImagesAsBase64.getExportImagesAsBase64/#setExportImagesAsBase64(boolean).setExportImagesAsBase64(boolean)) من قبل المستخدم، فستحاول GroupDocs.Editor تحديد ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) بنفسها وتطبيقه عند النجاح.

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getExportImagesAsBase64() {#getExportImagesAsBase64--}
```
public final boolean getExportImagesAsBase64()
```


يحدد ما إذا كانت الصور تُحفظ بتنسيق Base64 في ملف الإخراج. القيمة الافتراضية هي
false
.

<br />

*** ** * ** ***

عند ضبط هذه الخاصية على  true , يتم تصدير بيانات الصور مباشرةً إلى عناصر الصورة ![](../) ولا يتم إنشاء ملفات منفصلة. إذا تم ضبط هذه الخاصية على  true , فإن لها أولوية أعلى من خاصية  MarkdownSaveOptions.ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) الخاصية.

<br />



**Returns:**
boolean
### setExportImagesAsBase64(boolean value) {#setExportImagesAsBase64-boolean-}
```
public final void setExportImagesAsBase64(boolean value)
```


يحدد ما إذا كانت الصور تُحفظ بتنسيق Base64 في ملف الإخراج. القيمة الافتراضية هي
false
.

<br />

*** ** * ** ***

عند ضبط هذه الخاصية على  true , يتم تصدير بيانات الصور مباشرةً إلى عناصر الصورة ![](../) ولا يتم إنشاء ملفات منفصلة. إذا تم ضبط هذه الخاصية على  true , فإن لها أولوية أعلى من خاصية  MarkdownSaveOptions.ImagesFolder (#getImagesFolder.getImagesFolder/#setImagesFolder(String).setImagesFolder(String)) الخاصية.

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

