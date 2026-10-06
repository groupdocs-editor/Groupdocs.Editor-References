---
title: "XpsSaveOptions"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يسمح بتحديد خيارات مخصصة لإنشاء وحفظ مستندات XPS XML Paper Specifications"
type: docs
weight: 54
url: /ar/java/com.groupdocs.editor.options/xpssaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class XpsSaveOptions implements ISaveOptions
```

يسمح بتحديد خيارات مخصصة لإنشاء وحفظ مستندات XPS (مواصفات ورق XML).

<br />

*** ** * ** ***

ملف XPS يمثل ملفات تخطيط الصفحات التي تستند إلى مواصفات ورق XML التي أنشأتها Microsoft. تم تطويره كبديل لتنسيق ملف EMF وهو مشابه لتنسيق ملف PDF، لكنه يستخدم XML في تخطيط ومظهر ومعلومات الطباعة للمستند.

<br />


## المنشئات

| منشئ | الوصف |
| --- | --- |
| [XpsSaveOptions()](#XpsSaveOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getFontEmbedding()](#getFontEmbedding--) | مسؤول عن تضمين موارد الخطوط في مستند XPS الناتج، والتي تُستخدم في المستند الأصلي. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | يفعل آليات تحسين الذاكرة أثناء إنشاء المستند من HTML، مما يقلل الأداء كتكلفة لتقليل استهلاك الذاكرة. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | يفعل آليات تحسين الذاكرة أثناء إنشاء المستند من HTML، مما يقلل الأداء كتكلفة لتقليل استهلاك الذاكرة. |
|
### XpsSaveOptions() {#XpsSaveOptions--}
```
public XpsSaveOptions()
```


### getFontEmbedding() {#getFontEmbedding--}
```
public final byte getFontEmbedding()
```


مسؤول عن تضمين موارد الخطوط في مستند XPS الناتج، والتي تُستخدم في المستند الأصلي.
بشكل افتراضي لا يتم تضمين أي خطوط (NotEmbed).


**Returns:**
بايت
### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


يفعل آليات تحسين الذاكرة أثناء إنشاء المستند من HTML، مما يقلل الأداء كتكلفة لتقليل استهلاك الذاكرة.
ضبط هذا الخيار على true يمكن أن يقلل بشكل كبير من استهلاك الذاكرة أثناء إنشاء مستندات كبيرة على حساب وقت حفظ أبطأ.
القيمة الافتراضية هي false (تم تعطيل تحسين الذاكرة من أجل أداء أفضل).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


يفعل آليات تحسين الذاكرة أثناء إنشاء المستند من HTML، مما يقلل الأداء كتكلفة لتقليل استهلاك الذاكرة.
ضبط هذا الخيار على true يمكن أن يقلل بشكل كبير من استهلاك الذاكرة أثناء إنشاء مستندات كبيرة على حساب وقت حفظ أبطأ.
القيمة الافتراضية هي false (تم تعطيل تحسين الذاكرة من أجل أداء أفضل).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

