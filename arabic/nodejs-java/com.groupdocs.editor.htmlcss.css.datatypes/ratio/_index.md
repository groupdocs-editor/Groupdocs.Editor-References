---
title: "النسبة"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يمثل نوع بيانات CSS ratio الذي يُستخدم لوصف نسب الأبعاد في استعلامات الوسائط وللصور النقطية عن طريق تحديد النسبة بين قيمتين بلا وحدة تُسمى البسط والمقام."
type: docs
weight: 14
url: /ar/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/ratio/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Ratio implements ICssDataType
```

يمثل نوع بيانات CSS "ratio"، الذي يُستخدم لوصف النسبة
النسب في استعلامات الوسائط وللصور النقطية عن طريق تحديد النسبة
بين قيمتين بلا وحدة تُسمى "numerator" و"denominator". ثابت
هيكل.


*** ** * ** ***

https://developer.mozilla.org/en-US/docs/Web/CSS/ratio

<br />


## المنشئات

| المنشئ | الوصف |
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
|  | [calculate()](#calculate--) | يحسب ويرجع هذه النسبة كعدد نقطي مفرد |
|
|  | [getInverseRatio()](#getInverseRatio--) | ينشئ ويرجع نسبة معكوسة (متبادلة) لهذه النسبة |
|
|  | [serializeDefault()](#serializeDefault--) | يسلسل هذه النسبة إلى سلسلة ويعيدها |
|
|  | [toString()](#toString--) | يرجع تمثيلًا نصيًا لهذه النسبة؛ نفس كـ |
"SerializeDefault()"
|
|  | [isDefault()](#isDefault--) | يحدد ما إذا كانت هذه النسبة لها قيمة افتراضية أو هي "1/1" (واحدة) |
|
|  | [deepClone()](#deepClone--) | إرجاع نسخة كاملة من هذه النسبة |
|
|  | [equals(Ratio other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | يحدد ما إذا كانت هذه الحالة مساوية للمثيل المحدد من "Ratio" |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | يحدد ما إذا كانت هذه الحالة مساوية للعنصر غير المحول المحدد، |
والتي من المفترض أنها مثيل آخر من "Ratio"
|
|  | [op_Equality(Ratio left, Ratio right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | يقارن نسبتين ويعيد قيمة منطقية تشير إلى ما إذا كانتا متطابقتين. |
|
|  | [op_Inequality(Ratio left, Ratio right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-) | يقارن نسبتين ويعيد قيمة منطقية تشير إلى ما إذا كانتا لا |
تتطابق.
|
|  | [hashCode()](#hashCode--) | إرجاع قيمة hashcode لهذه الحالة، والتي لا يمكن تغييرها خلال |
عمرها
|
|  | [create(int numerator, int denominator)](#create-int-int-) | ينشئ ويعيد مثيلًا واحدًا من Ratio من البسط المحدد و |
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


يحسب ويرجع هذه النسبة كعدد نقطي مفرد


**Returns:**
double - عدد عائم بدقة مزدوجة

### getInverseRatio() {#getInverseRatio--}
```
public final Ratio getInverseRatio()
```


ينشئ ويرجع نسبة معكوسة (متبادلة) لهذه النسبة


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is an inverse ratio for this one

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


يسلسل هذه النسبة إلى سلسلة ويعيدها


**Returns:**
java.lang.String - سلسلة بصيغة "numerator/denominator"

### toString() {#toString--}
```
public String toString()
```


يرجع تمثيلًا نصيًا لهذه النسبة؛ نفس كـ
"SerializeDefault()"


**Returns:**
java.lang.String - سلسلة بصيغة "numerator/denominator"

### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


يحدد ما إذا كانت هذه النسبة لها قيمة افتراضية أو هي "1/1" (واحدة)


**Returns:**
boolean
### deepClone() {#deepClone--}
```
public final Ratio deepClone()
```


إرجاع نسخة كاملة من هذه النسبة


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance, that is a full and deep copy of this one

### equals(Ratio other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public final boolean equals(Ratio other)
```


يحدد ما إذا كانت هذه الحالة مساوية للمثيل المحدد من "Ratio"


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | مثيل Ratio آخر للتحقق من المساواة مع هذا |
|

**Returns:**
منطقي - True إذا كانا متساويين، false إذا كانا غير متساويين

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


يحدد ما إذا كانت هذه الحالة مساوية للعنصر غير المحول المحدد،
والتي من المفترض أنها مثيل آخر من "Ratio"


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | آخر | java.lang.Object | مثيل System.Object آخر، والذي من المفترض أنه من نوع Ratio، للتحقق من المساواة مع هذا |
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
boolean - صحيح إذا كانت النسبتين متساويتين، وإلا خطأ.

### op_Inequality(Ratio left, Ratio right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-com.groupdocs.editor.htmlcss.css.datatypes.Ratio-}
```
public static boolean op_Inequality(Ratio left, Ratio right)
```


يقارن نسبتين ويعيد قيمة منطقية تشير إلى ما إذا كانتا لا
تتطابق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | left | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | النسبة الأولى للاستخدام. |
|
|  | right | [Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) | النسبة الثانية للاستخدام. |
|

**Returns:**
boolean - صحيح إذا كانت النسبتين غير متساويتين، وإلا خطأ.

### hashCode() {#hashCode--}
```
public int hashCode()
```


إرجاع قيمة hashcode لهذه الحالة، والتي لا يمكن تغييرها خلال
عمرها


**Returns:**
int - عدد صحيح موقّع بحجم 4 بايت، وهو غير قابل للتغيير لهذه الحالة

### create(int numerator, int denominator) {#create-int-int-}
```
public static Ratio create(int numerator, int denominator)
```


ينشئ ويعيد مثيلًا واحدًا من Ratio من البسط المحدد و
المقام


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | البسط | int | البسط للنسبة. يجب أن يكون عددًا صحيحًا موجبًا تمامًا. |
|
|  | المقام | int | المقام للنسبة. يجب أن يكون عددًا صحيحًا موجبًا تمامًا. |
|

**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - New Ratio instance

