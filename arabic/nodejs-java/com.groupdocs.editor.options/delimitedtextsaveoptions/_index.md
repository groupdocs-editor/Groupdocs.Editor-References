---
title: "DelimitedTextSaveOptions"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يحتوي على خيارات لإنشاء وحفظ مستندات جداول البيانات النصية مثل CSV وTab وغيرها التي تستخدم فاصلًا (delimiter)."
type: docs
weight: 11
url: /ar/nodejs-java/com.groupdocs.editor.options/delimitedtextsaveoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.options.ISaveOptions](../../com.groupdocs.editor.options/isaveoptions)
```
public final class DelimitedTextSaveOptions implements ISaveOptions
```

يحتوي على خيارات لإنشاء وحفظ مستندات جداول البيانات النصية
(CSV، Tab-based وغيرها)، التي تستخدم فاصلًا (delimiter)


*** ** * ** ***

https://en.wikipedia.org/wiki/Delimiter-separated_values

<br />


## المنشئات

| المنشئ | الوصف |
| --- | --- |
|  | [DelimitedTextSaveOptions()](#DelimitedTextSaveOptions--) | يقوم هذا المُنشئ بدون معلمات بإنشاء نسخة جديدة من DelimitedTextSaveOptions مع فاصل افتراضي هو الفاصلة المنقوطة (;) (يمكن تعديله لاحقًا عبر |
الفاصل
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) الخاصية)
|
|  | [DelimitedTextSaveOptions(String separator)](#DelimitedTextSaveOptions-java.lang.String-) | ينشئ نسخة من فئة الخيارات للنص المفصول مع إلزامية |
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
|  | [getEncoding()](#getEncoding--) | يسمح بتعيين ترميز لمستند جدول البيانات النصي. |
|
|  | [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | يسمح بتعيين ترميز لمستند جدول البيانات النصي. |
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


يقوم هذا المُنشئ بدون معلمات بإنشاء نسخة جديدة من DelimitedTextSaveOptions مع فاصل افتراضي هو الفاصلة المنقوطة (;) (يمكن تعديله لاحقًا عبر
الفاصل
(#getSeparator.getSeparator/#setSeparator(String).setSeparator(String)) الخاصية)


### DelimitedTextSaveOptions(String separator) {#DelimitedTextSaveOptions-java.lang.String-}
```
public DelimitedTextSaveOptions(String separator)
```


ينشئ نسخة من فئة الخيارات للنص المفصول مع إلزامية
الفاصل (المحدد)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الفاصل | java.lang.String | فاصل سلسلة (المحدد) لمستندات جدول البيانات النصية |
|

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```


يسمح بتحديد فاصل نصي (المحدد) للملفات النصية
مستندات جدول البيانات


**Returns:**
java.lang.String -
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

### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


يسمح بتعيين ترميز لمستند جدول البيانات النصي. بواسطة
الافتراضي (وإذا لم يُحدد) هو UTF8.


**Returns:**
java.nio.charset.Charset -
### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public final void setEncoding(Charset value)
```


يسمح بتعيين ترميز لمستند جدول البيانات النصي. بواسطة
الافتراضي (وإذا لم يُحدد) هو UTF8.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.nio.charset.Charset |  |

### getTrimLeadingBlankRowAndColumn() {#getTrimLeadingBlankRowAndColumn--}
```
public final boolean getTrimLeadingBlankRowAndColumn()
```


يشير إلى ما إذا كان يجب قص الصفوف والأعمدة الفارغة الرائدة مثل
ما يفعله MS Excel


**Returns:**
منطقي -
### setTrimLeadingBlankRowAndColumn(boolean value) {#setTrimLeadingBlankRowAndColumn-boolean-}
```
public final void setTrimLeadingBlankRowAndColumn(boolean value)
```


يشير إلى ما إذا كان يجب قص الصفوف والأعمدة الفارغة الرائدة مثل
ما يفعله MS Excel


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### getKeepSeparatorsForBlankRow() {#getKeepSeparatorsForBlankRow--}
```
public final boolean getKeepSeparatorsForBlankRow()
```


يشير إلى ما إذا كان يجب إخراج الفواصل للصف الفارغ. الافتراضي
القيمة هي false مما يعني أن محتوى الصف الفارغ سيكون فارغًا.


**Returns:**
منطقي -
### setKeepSeparatorsForBlankRow(boolean value) {#setKeepSeparatorsForBlankRow-boolean-}
```
public final void setKeepSeparatorsForBlankRow(boolean value)
```


يشير إلى ما إذا كان يجب إخراج الفواصل للصف الفارغ. الافتراضي
القيمة هي false مما يعني أن محتوى الصف الفارغ سيكون فارغًا.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

