---
title: "DelimitedTextEditOptions"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "خيارات تحميل مستندات Spreadsheet النصية CSV Tab-based إلخ التي تستخدم فاصلًا"
type: docs
weight: 10
url: /ar/java/com.groupdocs.editor.options/delimitedtexteditoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.IEditOptions](../../com.groupdocs.editor.options/ieditoptions)
```
public final class DelimitedTextEditOptions implements IEditOptions
```

خيارات تحميل مستندات Spreadsheet النصية (CSV، Tab-based إلخ)،
التي تستخدم فاصلًا (delimiter)


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [DelimitedTextEditOptions(String separator)](#DelimitedTextEditOptions-java.lang.String-) | ينشئ مثيلًا لفئة الخيارات للنص المفصول بفواصل مع إلزامية |
فاصل (delimiter)
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getSeparator()](#getSeparator--) | يسمح بتحديد فاصل سلسلة (delimiter) للنصية |
مستندات Spreadsheet
|
|  | [setSeparator(String value)](#setSeparator-java.lang.String-) | يسمح بتحديد فاصل سلسلة (delimiter) للنصية |
مستندات Spreadsheet
|
|  | [getConvertDateTimeData()](#getConvertDateTimeData--) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت السلسلة في النصية |
المستند يُحوَّل إلى بيانات تاريخ.
|
|  | [setConvertDateTimeData(boolean value)](#setConvertDateTimeData-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت السلسلة في النصية |
المستند يُحوَّل إلى بيانات تاريخ.
|
|  | [getConvertNumericData()](#getConvertNumericData--) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت السلسلة في النصية |
المستند يُحوَّل إلى بيانات رقمية.
|
|  | [setConvertNumericData(boolean value)](#setConvertNumericData-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كانت السلسلة في النصية |
المستند يُحوَّل إلى بيانات رقمية.
|
|  | [getTreatConsecutiveDelimitersAsOne()](#getTreatConsecutiveDelimitersAsOne--) | يحدد ما إذا كان يجب معالجة الفواصل المتتالية كواحدة. |
|
|  | [setTreatConsecutiveDelimitersAsOne(boolean value)](#setTreatConsecutiveDelimitersAsOne-boolean-) | يحدد ما إذا كان يجب معالجة الفواصل المتتالية كواحدة. |
|
|  | [getOptimizeMemoryUsage()](#getOptimizeMemoryUsage--) | يفعل آليات تحسين الذاكرة أثناء معالجة مستند الإدخال، |
والتي قد تقلل الأداء في بعض الحالات الخاصة، ولكن من ناحية أخرى
تقليل استهلاك الذاكرة يدويًا.
|
|  | [setOptimizeMemoryUsage(boolean value)](#setOptimizeMemoryUsage-boolean-) | يفعل آليات تحسين الذاكرة أثناء معالجة مستند الإدخال، |
والتي قد تقلل الأداء في بعض الحالات الخاصة، ولكن من ناحية أخرى
تقليل استهلاك الذاكرة يدويًا.
|
### DelimitedTextEditOptions(String separator) {#DelimitedTextEditOptions-java.lang.String-}
```
public DelimitedTextEditOptions(String separator)
```


ينشئ مثيلًا لفئة الخيارات للنص المفصول بفواصل مع إلزامية
فاصل (delimiter)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | فاصل | java.lang.String | الفاصل الإلزامي (delimiter)، لا يمكن أن يكون NULL أو فارغ |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


يسمح بتحديد فاصل سلسلة (delimiter) للنصية
مستندات Spreadsheet


**Returns:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```


يسمح بتحديد فاصل سلسلة (delimiter) للنصية
مستندات Spreadsheet


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String |  |

### getConvertDateTimeData() {#getConvertDateTimeData--}
```
public final boolean getConvertDateTimeData()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كانت السلسلة في النصية
يتم تحويل المستند إلى بيانات التاريخ. الافتراضي هو false.


**Returns:**
boolean
### setConvertDateTimeData(boolean value) {#setConvertDateTimeData-boolean-}
```
public final void setConvertDateTimeData(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كانت السلسلة في النصية
يتم تحويل المستند إلى بيانات التاريخ. الافتراضي هو false.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getConvertNumericData() {#getConvertNumericData--}
```
public final boolean getConvertNumericData()
```


يحصل أو يضبط قيمة تشير إلى ما إذا كانت السلسلة في النصية
يتم تحويل المستند إلى بيانات رقمية. الافتراضي هو false.


**Returns:**
boolean
### setConvertNumericData(boolean value) {#setConvertNumericData-boolean-}
```
public final void setConvertNumericData(boolean value)
```


يحصل أو يضبط قيمة تشير إلى ما إذا كانت السلسلة في النصية
يتم تحويل المستند إلى بيانات رقمية. الافتراضي هو false.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getTreatConsecutiveDelimitersAsOne() {#getTreatConsecutiveDelimitersAsOne--}
```
public final boolean getTreatConsecutiveDelimitersAsOne()
```


يحدد ما إذا كان يجب معالجة الفواصل المتتالية كواحدة. بـ
الافتراضي هو false.


**Returns:**
boolean
### setTreatConsecutiveDelimitersAsOne(boolean value) {#setTreatConsecutiveDelimitersAsOne-boolean-}
```
public final void setTreatConsecutiveDelimitersAsOne(boolean value)
```


يحدد ما إذا كان يجب معالجة الفواصل المتتالية كواحدة. بـ
الافتراضي هو false.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

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

