---
title: "DelimitedTextEditOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "خيارات تحميل مستندات Spreadsheet النصية (CSV، Tab‑based، إلخ) التي تستخدم فاصلًا."
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.editor.options/delimitedtexteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class DelimitedTextEditOptions implements IEditOptions
```

خيارات تحميل مستندات Spreadsheet النصية (CSV، Tab‑based، إلخ)،
التي تستخدم فاصلًا (delimiter)


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## المنشئات

| المنشئ | الوصف |
| --- | --- |
|  | [DelimitedTextEditOptions(String separator)](#DelimitedTextEditOptions-java.lang.String-) | ينشئ نسخة من فئة الخيارات للنص المفصول مع إلزامية |
الفاصل (المحدد)
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | يسمح بتحديد فاصل نصي (المحدد) للملفات النصية |
مستندات جدول البيانات
|
|  | [setSeparator(String value)](#setSeparator-java.lang.String-) | يسمح بتحديد فاصل نصي (المحدد) للملفات النصية |
مستندات جدول البيانات
|
|  | [getConvertDateTimeData()](#getConvertDateTimeData--) | يحصل أو يحدد قيمة تشير إلى ما إذا كانت السلسلة في النصية |
المستند يُحوَّل إلى بيانات تاريخ.
|
|  | [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | يحصل أو يحدد قيمة تشير إلى ما إذا كانت السلسلة في النصية |
المستند يُحوَّل إلى بيانات تاريخ.
|
|  | [getConvertNumericData()](#getConvertNumericData--) | يحصل أو يحدد قيمة تشير إلى ما إذا كانت السلسلة في النصية |
المستند يُحوَّل إلى بيانات رقمية.
|
|  | [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | يحصل أو يحدد قيمة تشير إلى ما إذا كانت السلسلة في النصية |
المستند يُحوَّل إلى بيانات رقمية.
|
|  | [getTreatConsecutiveDelimitersAsOne()](#getTreatConsecutiveDelimitersAsOne--) | يحدد ما إذا كان يجب اعتبار الفواصل المتتالية كفاصل واحد. |
|
|  | [setTreatConsecutiveDelimitersAsOne(boolean value)](#setTreatConsecutiveDelimitersAsOne-boolean-) | يحدد ما إذا كان يجب اعتبار الفواصل المتتالية كفاصل واحد. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | يفعل آليات تحسين الذاكرة أثناء معالجة المستند المدخل، |
التي قد تضعف الأداء في بعض الحالات الخاصة، ولكن من الجانب الآخر
تقلل من استهلاك الذاكرة.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | يفعل آليات تحسين الذاكرة أثناء معالجة المستند المدخل، |
التي قد تضعف الأداء في بعض الحالات الخاصة، ولكن من الجانب الآخر
تقلل من استهلاك الذاكرة.
|
### DelimitedTextEditOptions(String separator) {#DelimitedTextEditOptions-java.lang.String-}
```
public DelimitedTextEditOptions(String separator)
```


ينشئ نسخة من فئة الخيارات للنص المفصول مع إلزامية
الفاصل (المحدد)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الفاصل | java.lang.String | فاصل إلزامي (delimiter) لا يمكن أن يكون NULL أو فارغًا |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


يسمح بتحديد فاصل نصي (المحدد) للملفات النصية
مستندات جدول البيانات


**Returns:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


يسمح بتحديد فاصل نصي (المحدد) للملفات النصية
مستندات جدول البيانات


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


يحصل أو يحدد قيمة تشير إلى ما إذا كانت السلسلة في النصية
المستند يُحوَّل إلى بيانات تاريخ. القيمة الافتراضية هي false.


**Returns:**
boolean
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


يحصل أو يحدد قيمة تشير إلى ما إذا كانت السلسلة في النصية
المستند يُحوَّل إلى بيانات تاريخ. القيمة الافتراضية هي false.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


يحصل أو يحدد قيمة تشير إلى ما إذا كانت السلسلة في النصية
المستند يُحوَّل إلى بيانات رقمية. القيمة الافتراضية هي false.


**Returns:**
boolean
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


يحصل أو يحدد قيمة تشير إلى ما إذا كانت السلسلة في النصية
المستند يُحوَّل إلى بيانات رقمية. القيمة الافتراضية هي false.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getTreatConsecutiveDelimitersAsOne() {#getTreatConsecutiveDelimitersAsOne--}
```
public final boolean getTreatConsecutiveDelimitersAsOne()
```


يحدد ما إذا كان يجب اعتبار الفواصل المتتالية كواحدة. بواسطة
القيمة الافتراضية هي false.


**Returns:**
boolean
### setTreatConsecutiveDelimitersAsOne(boolean value) {#setTreatConsecutiveDelimitersAsOne-boolean-}
```
public final void setTreatConsecutiveDelimitersAsOne(boolean value)
```


يحدد ما إذا كان يجب اعتبار الفواصل المتتالية كواحدة. بواسطة
القيمة الافتراضية هي false.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

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

