---
title: "PdfSaveOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يسمح بتحديد خيارات مخصصة لإنشاء وحفظ مستندات PDF Portable Document Format"
type: docs
weight: 31
url: /ar/nodejs-java/com.groupdocs.editor.options/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class PdfSaveOptions implements ISaveOptions
```

يسمح بتحديد خيارات مخصصة لإنشاء وحفظ PDF (Portable
Document Format) مستندات

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [PdfSaveOptions()](#PdfSaveOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPassword()](#getPassword--) | كلمة المرور، التي سيتم تطبيقها على مستند PDF المُنشأ ككلمة مرور مستخدم، المطلوبة للفتح. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | كلمة المرور، التي سيتم تطبيقها على مستند PDF المُنشأ ككلمة مرور مستخدم، المطلوبة للفتح. |
|
|  | [getCompliance()](#getCompliance--) | يحدد مستوى التوافق مع معايير PDF للمستندات الناتجة. |
|
|  | [setCompliance(int value)](#setCompliance-int-) | يحدد مستوى التوافق مع معايير PDF للمستندات الناتجة. |
|
|  | [getFontEmbedding()](#getFontEmbedding--) | مسؤول عن تضمين موارد الخطوط في مستند PDF الناتج، والتي تُستخدم في المستند الأصلي. |
|
|  | [setFontEmbedding(int value)](#setFontEmbedding-int-) | مسؤول عن تضمين موارد الخطوط في مستند PDF الناتج، والتي تُستخدم في المستند الأصلي. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | يفعل آليات تحسين الذاكرة أثناء إنشاء المستند من HTML، مما يقلل الأداء كتكلفة لتقليل استهلاك الذاكرة. |
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | يفعل آليات تحسين الذاكرة أثناء إنشاء المستند من HTML، مما يقلل الأداء كتكلفة لتقليل استهلاك الذاكرة. |
|
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


### getPassword() {#getPassword--}
```
public final String getPassword()
```


كلمة المرور، التي سيتم تطبيقها على مستند PDF المُنشأ ككلمة مرور مستخدم، المطلوبة للفتح.
إذا كان NULL أو فارغًا، لن يتم تطبيق كلمة مرور على المستند. وإلا، سيتم تشفير المستند باستخدام RC4 (طول المفتاح 128 بت).
بشكل افتراضي يكون NULL \u2014 لا يتم تطبيق كلمة مرور.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


كلمة المرور، التي سيتم تطبيقها على مستند PDF المُنشأ ككلمة مرور مستخدم، المطلوبة للفتح.
إذا كان NULL أو فارغًا، لن يتم تطبيق كلمة مرور على المستند. وإلا، سيتم تشفير المستند باستخدام RC4 (طول المفتاح 128 بت).
بشكل افتراضي يكون NULL \u2014 لا يتم تطبيق كلمة مرور.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getCompliance() {#getCompliance--}
```
public final int getCompliance()
```


يحدد مستوى التوافق مع معايير PDF للمستندات الناتجة. القيمة الافتراضية هي PdfCompliance.Pdf17.


**Returns:**
int
### setCompliance(int value) {#setCompliance-int-}
```
public final void setCompliance(int value)
```


يحدد مستوى التوافق مع معايير PDF للمستندات الناتجة. القيمة الافتراضية هي PdfCompliance.Pdf17.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getFontEmbedding() {#getFontEmbedding--}
```
public final int getFontEmbedding()
```


مسؤول عن تضمين موارد الخطوط في مستند PDF الناتج، والتي تُستخدم في المستند الأصلي. بشكل افتراضي لا يتم تضمين أي خطوط (NotEmbed).


**Returns:**
int
### setFontEmbedding(int value) {#setFontEmbedding-int-}
```
public final void setFontEmbedding(int value)
```


مسؤول عن تضمين موارد الخطوط في مستند PDF الناتج، والتي تُستخدم في المستند الأصلي. بشكل افتراضي لا يتم تضمين أي خطوط (NotEmbed).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


يفعل آليات تحسين الذاكرة أثناء إنشاء المستند من HTML، مما يقلل الأداء كتكلفة لتقليل استهلاك الذاكرة.
ضبط هذا الخيار على true يمكن أن يقلل بشكل كبير من استهلاك الذاكرة أثناء إنشاء مستندات كبيرة على حساب بطء وقت الحفظ.
القيمة الافتراضية هي false (تم تعطيل تحسين الذاكرة من أجل أداء أفضل).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


يفعل آليات تحسين الذاكرة أثناء إنشاء المستند من HTML، مما يقلل الأداء كتكلفة لتقليل استهلاك الذاكرة.
ضبط هذا الخيار على true يمكن أن يقلل بشكل كبير من استهلاك الذاكرة أثناء إنشاء مستندات كبيرة على حساب بطء وقت الحفظ.
القيمة الافتراضية هي false (تم تعطيل تحسين الذاكرة من أجل أداء أفضل).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

