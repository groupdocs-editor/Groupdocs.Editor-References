---
title: "SpreadsheetLoadOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يحتوي على خيارات لتحميل مستندات Spreadsheet Cells المتوافقة مع Excel الثنائية مثل XLSX و ODS إلخ"
type: docs
weight: 36
url: /ar/nodejs-java/com.groupdocs.editor.options/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ILoadOptions](../../com.groupdocs.editor.options/iloadoptions)
```
public final class SpreadsheetLoadOptions implements ILoadOptions
```

يحتوي على خيارات لتحميل مستندات Spreadsheet (Cells، المتوافقة مع Excel) الثنائية
مستندات مثل XLS(X)، ODS إلخ إلى فئة Editor

## المنشئات

| المنشئ | الوصف |
| --- | --- |
|  | [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | منشئ افتراضي بدون معلمات - جميع المعلمات لها قيم افتراضية |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPassword()](#getPassword--) | يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لـ |
فتح مستند Spreadsheet إذا كان مشفرًا.
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لـ |
فتح مستند Spreadsheet إذا كان مشفرًا.
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | يفعل آليات تحسين الذاكرة أثناء معالجة المستند المدخل، |
التي قد تضعف الأداء في بعض الحالات الخاصة، ولكن من الجانب الآخر
تقلل من استهلاك الذاكرة.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | يفعل آليات تحسين الذاكرة أثناء معالجة المستند المدخل، |
التي قد تضعف الأداء في بعض الحالات الخاصة، ولكن من الجانب الآخر
تقلل من استهلاك الذاكرة.
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
فتح مستند Spreadsheet إذا كان مشفرًا. اضبطه على NULL أو فارغ
سلسلة لتجنب استخدام كلمة المرور (القيمة الافتراضية).


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


يسمح بتحديد وتعديل والحصول على كلمة المرور التي ستُستخدم لـ
فتح مستند Spreadsheet إذا كان مشفرًا. اضبطه على NULL أو فارغ
سلسلة لتجنب استخدام كلمة المرور (القيمة الافتراضية).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getOptimizeMemoryUsage() {#getOptimizeMemoryUsage--}
```
public final boolean getOptimizeMemoryUsage()
```


يفعل آليات تحسين الذاكرة أثناء معالجة المستند المدخل،
التي قد تضعف الأداء في بعض الحالات الخاصة، ولكن من الجانب الآخر
تقلل من استهلاك الذاكرة. مفيد عند معالجة مستندات ضخمة و
مواجهة OutOfMemoryException. القيمة الافتراضية هي false (تحسين الذاكرة هو
معطل من أجل أداء أفضل).


**Returns:**
boolean
### setOptimizeMemoryUsage(boolean value) {#setOptimizeMemoryUsage-boolean-}
```
public final void setOptimizeMemoryUsage(boolean value)
```


يفعل آليات تحسين الذاكرة أثناء معالجة المستند المدخل،
التي قد تضعف الأداء في بعض الحالات الخاصة، ولكن من الجانب الآخر
تقلل من استهلاك الذاكرة. مفيد عند معالجة مستندات ضخمة و
مواجهة OutOfMemoryException. القيمة الافتراضية هي false (تحسين الذاكرة هو
معطل من أجل أداء أفضل).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

