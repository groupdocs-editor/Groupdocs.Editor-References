---
title: "DelimitedTextSaveOptions"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يحتوي على خيارات لإنشاء وحفظ مستندات جداول البيانات النصية مثل CSV وTab وغيرها التي تستخدم فاصلًا محددًا."
type: docs
weight: 11
url: /ar/java/com.groupdocs.editor.options/delimitedtextsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class DelimitedTextSaveOptions implements ISaveOptions
```

يحتوي على خيارات لإنشاء وحفظ مستندات جداول البيانات النصية
(CSV، Tab-based إلخ)، التي تستخدم فاصلًا (delimiter)


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [DelimitedTextSaveOptions()](#DelimitedTextSaveOptions--) | يقوم هذا المُنشئ بدون معلمات بإنشاء نسخة جديدة من DelimitedTextSaveOptions مع فاصل افتراضي هو الفاصلة المنقوطة (;) (يمكن تعديلها لاحقًا عبر |
الفاصل
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) الخاصية)
|
|  | [DelimitedTextSaveOptions(String separator)](#DelimitedTextSaveOptions-java.lang.String-) | ينشئ مثيلًا لفئة الخيارات للنص المفصول بفواصل مع إلزامية |
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
|  | [getEncoding()](#getEncoding--) | يسمح بتعيين ترميز لمستند جداول البيانات النصية. |
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | يسمح بتعيين ترميز لمستند جداول البيانات النصية. |
|
|  | [getTrimLeadingBlankRowAndColumn()](#getTrimLeadingBlankRowAndColumn--) | يشير إلى ما إذا كان يجب قص الصفوف والأعمدة الفارغة الرائدة مثل |
ما يفعله MS Excel
|
|  | [setTrimLeadingBlankRowAndColumn(boolean value)](#setTrimLeadingBlankRowAndColumn-boolean-) | يشير إلى ما إذا كان يجب قص الصفوف والأعمدة الفارغة الرائدة مثل |
ما يفعله MS Excel
|
|  | [getKeepSeparatorsForBlankRow()](#getKeepSeparatorsForBlankRow--) | يشير إلى ما إذا كان يجب إخراج الفواصل للصف الفارغ. |
|
|  | [setKeepSeparatorsForBlankRow(boolean value)](#setKeepSeparatorsForBlankRow-boolean-) | يشير إلى ما إذا كان يجب إخراج الفواصل للصف الفارغ. |
|
### DelimitedTextSaveOptions() {#DelimitedTextSaveOptions--}
```
public DelimitedTextSaveOptions()
```


يقوم هذا المُنشئ بدون معلمات بإنشاء نسخة جديدة من DelimitedTextSaveOptions مع فاصل افتراضي هو الفاصلة المنقوطة (;) (يمكن تعديلها لاحقًا عبر
الفاصل
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) الخاصية)


### DelimitedTextSaveOptions(String separator) {#DelimitedTextSaveOptions-java.lang.String-}
```
public DelimitedTextSaveOptions(String separator)
```


ينشئ مثيلًا لفئة الخيارات للنص المفصول بفواصل مع إلزامية
فاصل (delimiter)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | فاصل | java.lang.String | فاصل السلسلة (delimiter) لمستندات جداول البيانات النصية |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


يسمح بتحديد فاصل سلسلة (delimiter) للنصية
مستندات Spreadsheet


**Returns:**
java.lang.String -
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

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


يسمح بتعيين ترميز لمستند جداول البيانات النصية. بواسطة
الافتراضي (وإذا لم يتم تحديده) هو UTF8.


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


يسمح بتعيين ترميز لمستند جداول البيانات النصية. بواسطة
الافتراضي (وإذا لم يتم تحديده) هو UTF8.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.nio.charset.Charset |  |

### getTrimLeadingBlankRowAndColumn() {#getTrimLeadingBlankRowAndColumn--}
```
public final boolean getTrimLeadingBlankRowAndColumn()
```


يشير إلى ما إذا كان يجب قص الصفوف والأعمدة الفارغة الرائدة مثل
ما يفعله MS Excel


**Returns:**
boolean -
### setTrimLeadingBlankRowAndColumn(boolean value) {#setTrimLeadingBlankRowAndColumn-boolean-}
```
public final void setTrimLeadingBlankRowAndColumn(boolean value)
```


يشير إلى ما إذا كان يجب قص الصفوف والأعمدة الفارغة الرائدة مثل
ما يفعله MS Excel


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getKeepSeparatorsForBlankRow() {#getKeepSeparatorsForBlankRow--}
```
public final boolean getKeepSeparatorsForBlankRow()
```


يشير إلى ما إذا كان يجب إخراج الفواصل للصف الفارغ. الافتراضي
القيمة هي false مما يعني أن محتوى الصف الفارغ سيكون فارغًا.


**Returns:**
boolean -
### setKeepSeparatorsForBlankRow(boolean value) {#setKeepSeparatorsForBlankRow-boolean-}
```
public final void setKeepSeparatorsForBlankRow(boolean value)
```


يشير إلى ما إذا كان يجب إخراج الفواصل للصف الفارغ. الافتراضي
القيمة هي false مما يعني أن محتوى الصف الفارغ سيكون فارغًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

