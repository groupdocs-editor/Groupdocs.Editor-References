---
title: "النسبة"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثل نوع بيانات CSS ratio الذي يُستخدم لوصف نسب الأبعاد في استعلامات الوسائط وللصور النقطية من خلال تحديد النسبة بين قيمتين بلا وحدة تُسمى البسط والمقام."
type: docs
weight: 14
url: /ar/java/com.groupdocs.editor.htmlcss.css.datatypes/ratio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Ratio implements ICssDataType
```

يمثل نوع بيانات CSS \"ratio\"، والذي يُستخدم لوصف النسبة
النسب في استعلامات الوسائط وللصور النقطية من خلال تحديد النسبة
بين قيمتين بلا وحدة تُسمى \"numerator\" و\"denominator\". ثابت
بنية.


*** ** * ** ***

https://developer.mozilla.org/en-US/docs/Web/CSS/ratio

<br />


## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Ratio()](#Ratio--) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Single](#Single) | نسبة افتراضية واحدة 1/1 |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getNumerator()](#getNumerator--) | يرجع البسط لهذه النسبة |
|
|  | [getDenominator()](#getDenominator--) | يرجع المقام لهذه النسبة |
|
|  | [calculate()](#calculate--) | يحسب ويعيد هذه النسبة كعدد عشري مفرد |
|
|  | [getInverseRatio()](#getInverseRatio--) | ينشئ ويعيد نسبة معكوسة (مقلوبة) لهذه النسبة |
|
|  | [serializeDefault()](#serializeDefault--) | يسلسِل هذه النسبة إلى سلسلة ويعيدها |
|
|  | [toString()](#toString--) | يرجع تمثيلًا نصيًا لهذه النسبة؛ نفس ما |
"SerializeDefault()"
|
|  | [isDefault()](#isDefault--) | يحدد ما إذا كانت هذه النسبة لها قيمة افتراضية أو هي \"1/1\" (واحدة) |
|
|  | [deepClone()](#deepClone--) | يرجع نسخة كاملة من هذه النسبة |
|
|  | [equals(Ratio other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | يحدد ما إذا كان هذا الكائن مساويًا للعنصر المحدد \"Ratio\" |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | يحدد ما إذا كانت هذه الحالة مساوية للكائن غير المحول المحدد، |
وهو على الأرجح كائن \"Ratio\" آخر
|
|  | [op_Equality(Ratio left, Ratio right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | يقارن نسبتين ويعيد قيمة منطقية تشير إلى ما إذا كانتا متطابقتين. |
|
|  | [op_Inequality(Ratio left, Ratio right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | يقارن نسبتين ويعيد قيمة منطقية تشير إلى ما إذا كانتا غير متطابقتين |
يتطابق.
|
|  | [hashCode()](#hashCode--) | يعيد قيمة hashcode لهذا الكائن، والتي لا يمكن تغييرها خلال |
مدة الحياة
|
|  | [create(int numerator, int denominator)](#create-int-int-) | ينشئ ويعيد كائن Ratio واحد من البسط والمقام المحددين |
المقام
|
### Ratio() {#Ratio--}
```
public Ratio()
```


### Single {#Single}
```
public static final Ratio Single
```


نسبة افتراضية واحدة 1/1


### getNumerator() {#getNumerator--}
```
public final int getNumerator()
```


يرجع البسط لهذه النسبة


**Returns:**
int
### getDenominator() {#getDenominator--}
```
public final int getDenominator()
```


يرجع المقام لهذه النسبة


**Returns:**
int
### calculate() {#calculate--}
```
public final double calculate()
```


يحسب ويعيد هذه النسبة كعدد عشري مفرد


**Returns:**
double - عدد عائم بدقة مزدوجة

### getInverseRatio() {#getInverseRatio--}
```
public final Ratio getInverseRatio()
```


ينشئ ويعيد نسبة معكوسة (مقلوبة) لهذه النسبة


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is an inverse ratio for this one

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


يسلسِل هذه النسبة إلى سلسلة ويعيدها


**Returns:**
java.lang.String - سلسلة بصيغة "numerator/denominator"

### toString() {#toString--}
```
public String toString()
```


يرجع تمثيلًا نصيًا لهذه النسبة؛ نفس ما
"SerializeDefault()"


**Returns:**
java.lang.String - سلسلة بصيغة "numerator/denominator"

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


يحدد ما إذا كانت هذه النسبة لها قيمة افتراضية أو هي \"1/1\" (واحدة)


**Returns:**
boolean
### deepClone() {#deepClone--}
```
public final Ratio deepClone()
```


يرجع نسخة كاملة من هذه النسبة


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is a full and deep copy of this one

### equals(Ratio other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public final boolean equals(Ratio other)
```


يحدد ما إذا كان هذا الكائن مساويًا للعنصر المحدد \"Ratio\"


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | كائن Ratio آخر للتحقق من المساواة مع هذا |
|

**Returns:**
منطقي - True إذا كانا متساويين، false إذا كانا غير متساويين

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


يحدد ما إذا كانت هذه الحالة مساوية للكائن غير المحول المحدد،
وهو على الأرجح كائن \"Ratio\" آخر


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | آخر | java.lang.Object | كائن System.Object آخر، يُفترض أنه من نوع Ratio، للتحقق من المساواة مع هذا |
|

**Returns:**
منطقي - True إذا كانا متساويين، false إذا كانا غير متساويين

### op_Equality(Ratio left, Ratio right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Equality(Ratio left, Ratio right)
```


يقارن نسبتين ويعيد قيمة منطقية تشير إلى ما إذا كانتا متطابقتين.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | النسبة الأولى للاستخدام. |
|
|  | right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | النسبة الثانية للاستخدام. |
|

**Returns:**
boolean - صحيح إذا كانت النسبتان متساويتين، وإلا خطأ.

### op_Inequality(Ratio left, Ratio right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Inequality(Ratio left, Ratio right)
```


يقارن نسبتين ويعيد قيمة منطقية تشير إلى ما إذا كانتا غير متطابقتين
يتطابق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | النسبة الأولى للاستخدام. |
|
|  | right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | النسبة الثانية للاستخدام. |
|

**Returns:**
boolean - صحيح إذا كانت النسبتان غير متساويتين، وإلا خطأ.

### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد قيمة hashcode لهذا الكائن، والتي لا يمكن تغييرها خلال
مدة الحياة


**Returns:**
int - عدد صحيح موقع 4 بايت، غير قابل للتغيير لهذا الكائن

### create(int numerator, int denominator) {#create-int-int-}
```
public static Ratio create(int numerator, int denominator)
```


ينشئ ويعيد كائن Ratio واحد من البسط والمقام المحددين
المقام


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | البسط | int | البسط للنسبة. يجب أن يكون عددًا صحيحًا موجبًا صارمًا. |
|
|  | المقام | int | المقام للنسبة. يجب أن يكون عددًا صحيحًا موجبًا صارمًا. |
|

**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance

