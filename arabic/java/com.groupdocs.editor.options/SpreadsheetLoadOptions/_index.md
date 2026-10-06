---
title: "SpreadsheetLoadOptions"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يحتوي على خيارات لتحميل مستندات Spreadsheet Cells المتوافقة مع Excel الثنائية مثل XLSX و ODS وغيرها."
type: docs
weight: 36
url: /ar/java/com.groupdocs.editor.options/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class SpreadsheetLoadOptions implements ILoadOptions
```

يحتوي على خيارات لتحميل Spreadsheet الثنائية (Cells، المتوافقة مع Excel)
المستندات مثل XLS(X)، ODS وغيرها إلى فئة Editor

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | منشئ افتراضي بدون معلمات - جميع المعلمات لها قيم افتراضية |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPassword()](#getPassword--) | يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لـ |
فتح مستند Spreadsheet، إذا كان مشفراً.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لـ |
فتح مستند Spreadsheet، إذا كان مشفراً.
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | يفعل آليات تحسين الذاكرة أثناء معالجة مستند الإدخال، |
والتي قد تقلل الأداء في بعض الحالات الخاصة، ولكن من ناحية أخرى
تقليل استهلاك الذاكرة يدويًا.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | يفعل آليات تحسين الذاكرة أثناء معالجة مستند الإدخال، |
والتي قد تقلل الأداء في بعض الحالات الخاصة، ولكن من ناحية أخرى
تقليل استهلاك الذاكرة يدويًا.
|
### SpreadsheetLoadOptions() {#SpreadsheetLoadOptions--}
```
public SpreadsheetLoadOptions()
```


منشئ افتراضي بدون معلمات - جميع المعلمات لها قيم افتراضية


### getPassword() {#getPassword--}
```
public final String getPassword()
```


يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لـ
فتح مستند Spreadsheet، إذا كان مشفرًا. اضبطه على NULL أو فارغ
سلسلة لتجنب استخدام كلمة المرور (القيمة الافتراضية).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لـ
فتح مستند Spreadsheet، إذا كان مشفرًا. اضبطه على NULL أو فارغ
سلسلة لتجنب استخدام كلمة المرور (القيمة الافتراضية).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


يفعل آليات تحسين الذاكرة أثناء معالجة مستند الإدخال،
والتي قد تقلل الأداء في بعض الحالات الخاصة، ولكن من ناحية أخرى
تقليل استهلاك الذاكرة يدويًا. مفيد عند معالجة المستندات الضخمة و
مواجهة OutOfMemoryException. القيمة الافتراضية هي false (تحسين الذاكرة
معطل من أجل أداء أفضل).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


يفعل آليات تحسين الذاكرة أثناء معالجة مستند الإدخال،
والتي قد تقلل الأداء في بعض الحالات الخاصة، ولكن من ناحية أخرى
تقليل استهلاك الذاكرة يدويًا. مفيد عند معالجة المستندات الضخمة و
مواجهة OutOfMemoryException. القيمة الافتراضية هي false (تحسين الذاكرة
معطل من أجل أداء أفضل).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

