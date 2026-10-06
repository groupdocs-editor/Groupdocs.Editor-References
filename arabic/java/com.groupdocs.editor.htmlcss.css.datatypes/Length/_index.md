---
title: "الطول"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثل قيمة طول CSS بأي وحدة مدعومة بما في ذلك النسبة المئوية والنوع بدون وحدة."
type: docs
weight: 12
url: /ar/java/com.groupdocs.editor.htmlcss.css.datatypes/length/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Length implements ICssDataType
```

يمثل قيمة طول CSS بأي وحدة مدعومة، بما في ذلك النسبة المئوية
والنوع بدون وحدة. قد تكون القيم عددًا صحيحًا أو عشريًا، سلبية أو صفرًا و
موجبة. بنية غير قابلة للتغيير.

*** ** * ** ***


يغطي هذا النوع أنواع بيانات CSS التالية:

<https://developer.mozilla.org/en-US/docs/Web/CSS/length>

<https://developer.mozilla.org/en-US/docs/Web/CSS/percentage>

<br />


## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Length()](#Length--) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [UnitlessZero](#UnitlessZero) | صفر عدد صحيح بدون وحدة - القيمة الافتراضية، وهو نفس القيمة الافتراضية بدون معلمات |
منشئ
|
|  | [OneHundredPercents](#OneHundredPercents) | 100% |
|
|  | [FiftyPercents](#FiftyPercents) | 50% |
|
|  | [ZeroPercents](#ZeroPercents) | 0% |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [fromValueWithUnit(float value, int unit)](#fromValueWithUnit-float-int-) | ينشئ ويعيد كائنًا من النوع Length بناءً على عدد عشري محدد |
و الوحدة
|
|  | [fromValueWithUnit(double value, int unit)](#fromValueWithUnit-double-int-) | ينشئ ويعيد كائنًا من النوع Length بناءً على عدد مزدوج محدد |
و الوحدة
|
|  | [fromValueWithUnit(int value, int unit)](#fromValueWithUnit-int-int-) | ينشئ ويعيد كائنًا من النوع Length بناءً على عدد صحيح محدد |
العدد والوحدة
|
|  | [isUnitlessZero()](#isUnitlessZero--) | يحدد ما إذا كان هذا الكائن صفرًا بدون وحدة أم لا. |
|
|  | [isDefault()](#isDefault--) | يشير إلى ما إذا كان هذا الكائن من النوع Length لديه قيمة افتراضية \u2014 بدون وحدة |
صفر.
|
|  | [getUnitType()](#getUnitType--) | يرجع نوع الوحدة لهذا الكائن من النوع Length. |
|
|  | [isInteger()](#isInteger--) | يشير إلى ما إذا كانت القيمة الرقمية لهذا الكائن من النوع Length |
محددة أصلاً ومخزنة كعدد صحيح (INT32)
|
|  | [isFloat()](#isFloat--) | يشير إلى ما إذا كانت القيمة الرقمية لهذا الكائن من النوع Length |
محددة أصلاً ومخزنة كعدد عشري (FP32)
|
|  | [getFloatValue()](#getFloatValue--) | يرجع قيمة عددية عائمة للكائن من النوع Length. |
|
|  | [getIntegerValue()](#getIntegerValue--) | يرجع قيمة عددية صحيحة لهذا الكائن من النوع Length، إذا كان |
مخزّنًا داخليًا كعدد صحيح، أو يطرح استثناءً إذا كان
مخزنًا أصلاً كعدد عشري.
|
|  | [isAbsolute()](#isAbsolute--) | يحصل إذا كان الطول مُعطى بوحدات مطلقة. |
|
|  | [isRelative()](#isRelative--) | يحصل إذا كان الطول مُعطى بوحدات نسبية. |
|
|  | [isZero()](#isZero--) | يحدد ما إذا كانت القيمة الرقمية لهذا الطول عددًا صفريًا |
|
|  | [isNegative()](#isNegative--) | يحدد ما إذا كانت القيمة الرقمية لهذا الطول عددًا سالبًا |
|
|  | [isPositive()](#isPositive--) | يحدد ما إذا كانت القيمة الرقمية لهذا الطول عددًا موجبًا |
|
|  | [isUnitlessNonZero()](#isUnitlessNonZero--) | القيمة ذات نوع بدون وحدة، لكنها ليست صفرًا - موجبة أو سلبية |
number
|
|  | [toPixel()](#toPixel--) | يحوّل الطول إلى عدد من البكسلات، إذا كان ذلك ممكنًا. |
|
|  | [to(int unit)](#to-int-) | يحوّل الطول إلى الوحدة المعطاة، إذا كان ذلك ممكنًا. |
|
|  | [toStringSpecified(int unit)](#toStringSpecified-int-) | يعيد تمثيلًا نصيًا لهذا الطول بالنوع المحدد للوحدة. |
|
|  | [serializeDefault()](#serializeDefault--) | يعيد تمثيلًا نصيًا لهذا الطول في صيغته الأصلية |
شكل (كما هو مخزن)، دون تحويل قيمة الطول إلى شيء آخر
نوع الوحدة
|
|  | [equals(Length other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | يحدد ما إذا كانت هذه القيمة مساوية للطول المحدد الآخر |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان هذا الطول مساويًا للكائن المحدد |
|
|  | [op_Multiply(Length multiplicand, int factor)](#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-) | يضرب الطول المعطى في العامل المعطى |
|
|  | [op_Equality(Length left, Length right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | يفحص مساواة الطولين المعطيين. |
|
|  | [op_Inequality(Length left, Length right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | يفحص عدم مساواة الطولين المعطيين. |
|
|  | [hashCode()](#hashCode--) | يحسّب ويعيد رمز تجزئة (hash-code) لهذا الكائن Length عن طريق الجمع |
رموز التجزئة للقيمة ونوع الوحدة
|
|  | [deepClone()](#deepClone--) | يعيد نسخة كاملة من هذا الكائن Length |
|
|  | [getUnitFromName(String unitName)](#getUnitFromName-java.lang.String-) | يحاول تحليل اسم الوحدة المحدد وإرجاع القيمة المقابلة لـ |
تعداد الوحدة.
|
|  | [tryParse(String input, Length[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Length---) | يحاول تحليل سلسلة محددة كقيمة Length، بما في ذلك |
القيمة الرقمية واسم الوحدة
|
|  | [parse(String input)](#parse-java.lang.String-) | يحلل ويعيد السلسلة المحددة كقيمة Length، بما في ذلك |
القيمة الرقمية واسم الوحدة، أو يرمي استثناءً عند الفشل
|
### Length() {#Length--}
```
public Length()
```


### UnitlessZero {#UnitlessZero}
```
public static final Length UnitlessZero
```


صفر عدد صحيح بدون وحدة - القيمة الافتراضية، وهو نفس القيمة الافتراضية بدون معلمات
منشئ


### OneHundredPercents {#OneHundredPercents}
```
public static final Length OneHundredPercents
```


100%


### FiftyPercents {#FiftyPercents}
```
public static final Length FiftyPercents
```


50%


### ZeroPercents {#ZeroPercents}
```
public static final Length ZeroPercents
```


0%


### fromValueWithUnit(float value, int unit) {#fromValueWithUnit-float-int-}
```
public static Length fromValueWithUnit(float value, int unit)
```


ينشئ ويعيد كائنًا من النوع Length بناءً على عدد عشري محدد
و الوحدة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | float | \>أي عدد عائم (FP32) |
|
|  | وحدة | int | أي نوع وحدة صالح |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### fromValueWithUnit(double value, int unit) {#fromValueWithUnit-double-int-}
```
public static Length fromValueWithUnit(double value, int unit)
```


ينشئ ويعيد كائنًا من النوع Length بناءً على عدد مزدوج محدد
و الوحدة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | double | أي عدد مزدوج (FP64) سيتم تحويله إلى عائم (FP32) |
|
|  | وحدة | int | أي نوع وحدة صالح |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### fromValueWithUnit(int value, int unit) {#fromValueWithUnit-int-int-}
```
public static Length fromValueWithUnit(int value, int unit)
```


ينشئ ويعيد كائنًا من النوع Length بناءً على عدد صحيح محدد
العدد والوحدة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | int | أي عدد صحيح |
|
|  | وحدة | int | أي نوع وحدة صالح |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### isUnitlessZero() {#isUnitlessZero--}
```
public final boolean isUnitlessZero()
```


يحدد ما إذا كانت هذه الحالة صفرًا بدون وحدة أم لا. صفر بدون وحدة
هي القيمة الافتراضية لهذا النوع. نفس خاصية IsDefault.


**Returns:**
boolean
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


يشير إلى ما إذا كان هذا الكائن من النوع Length لديه قيمة افتراضية \u2014 بدون وحدة
صفر. نفس خاصية IsUnitlessZero.


**Returns:**
boolean
### getUnitType() {#getUnitType--}
```
public final int getUnitType()
```


يرجع نوع الوحدة لهذا الكائن من النوع Length.


**Returns:**
int
### isInteger() {#isInteger--}
```
public final boolean isInteger()
```


يشير إلى ما إذا كانت القيمة الرقمية لهذا الكائن من النوع Length
محددة أصلاً ومخزنة كعدد صحيح (INT32)


**Returns:**
boolean
### isFloat() {#isFloat--}
```
public final boolean isFloat()
```


يشير إلى ما إذا كانت القيمة الرقمية لهذا الكائن من النوع Length
محددة أصلاً ومخزنة كعدد عشري (FP32)


**Returns:**
boolean
### getFloatValue() {#getFloatValue--}
```
public final float getFloatValue()
```


يرجع قيمة عددية عائمة من كائن Length. لا يرمي استثناءً أبداً
استثناء - يحول قيمة Integer إلى Float إذا لزم الأمر.


**Returns:**
float
### getIntegerValue() {#getIntegerValue--}
```
public final int getIntegerValue()
```


يرجع قيمة عددية صحيحة لهذا الكائن من النوع Length، إذا كان
مخزّنًا داخليًا كعدد صحيح، أو يطرح استثناءً إذا كان
مخزنًا أصلاً كعدد عشري.


**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


يحدد ما إذا كان الطول معطى بوحدات مطلقة. قد يكون مثل هذا الطول
محولًا إلى بكسلات.


**Returns:**
boolean
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


يحدد ما إذا كان الطول معطى بوحدات نسبية. لا يمكن أن يكون مثل هذا الطول
محولًا إلى بكسلات.


**Returns:**
boolean
### isZero() {#isZero--}
```
public final boolean isZero()
```


يحدد ما إذا كانت القيمة الرقمية لهذا الطول عددًا صفريًا


**Returns:**
boolean
### isNegative() {#isNegative--}
```
public final boolean isNegative()
```


يحدد ما إذا كانت القيمة الرقمية لهذا الطول عددًا سالبًا


**Returns:**
boolean
### isPositive() {#isPositive--}
```
public final boolean isPositive()
```


يحدد ما إذا كانت القيمة الرقمية لهذا الطول عددًا موجبًا


**Returns:**
boolean
### isUnitlessNonZero() {#isUnitlessNonZero--}
```
public final boolean isUnitlessNonZero()
```


القيمة ذات نوع بدون وحدة، لكنها ليست صفرًا - موجبة أو سلبية
number


**Returns:**
boolean
### toPixel() {#toPixel--}
```
public final float toPixel()
```


يحول الطول إلى عدد من البكسلات إذا كان ذلك ممكنًا. إذا كان الحالي
الوحدة نسبية، فسيتم رمي استثناء.


**Returns:**
float - عدد البكسلات التي يمثلها الطول الحالي.

### to(int unit) {#to-int-}
```
public final float to(int unit)
```


يحول الطول إلى الوحدة المعطاة إذا كان ذلك ممكنًا. إذا كان الحالي أو
الوحدة المعطاة نسبية، فسيتم رمي استثناء.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | وحدة | int | الوحدة المراد التحويل إليها. |
|

**Returns:**
float - القيمة في الوحدة المعطاة للطول الحالي.

### toStringSpecified(int unit) {#toStringSpecified-int-}
```
public final String toStringSpecified(int unit)
```


يعيد تمثيلًا نصيًا لهذا الطول بالنوع المحدد للوحدة.
القيمة الرقمية سيتم تحويلها وفقًا لتغيير نوع الوحدة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | وحدة | int | الوحدة المحددة، التي يجب تحويل هذه الحالة إليها قبل تسلسلها إلى السلسلة. يجب أن تكون صالحة. لا يمكن أن تكون بدون وحدة. |
|

**Returns:**
java.lang.String - تمثيل السلسلة

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


يعيد تمثيلًا نصيًا لهذا الطول في صيغته الأصلية
شكل (كما هو مخزن)، دون تحويل قيمة الطول إلى شيء آخر
نوع الوحدة


**Returns:**
java.lang.String - كائن السلسلة

### equals(Length other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public final boolean equals(Length other)
```


يحدد ما إذا كانت هذه القيمة مساوية للطول المحدد الآخر


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | كائن آخر من نوع Length |
|

**Returns:**
boolean - صحيح إذا كان متساويًا، وإلا خطأ

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان هذا الطول مساويًا للكائن المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | obj | java.lang.Object | مثال آخر من نوع Length، يتم تغليفه إلى System.Object أو أي نوع تجريدي آخر أو واجهة |
|

**Returns:**
boolean - صحيح إذا كان متساويًا، وإلا خطأ

### op_Multiply(Length multiplicand, int factor) {#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-}
```
public static Length op_Multiply(Length multiplicand, int factor)
```


يضرب الطول المعطى في العامل المعطى


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | multiplicand | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Length - المضاعف |
|
|  | العامل | int | عدد صحيح تعسفي - العامل |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - A new Length - a product of multiplication

### op_Equality(Length left, Length right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static boolean op_Equality(Length left, Length right)
```


يفحص مساواة الطولين المعطيين.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | المعامل الأيسر للـ length. |
|
|  | right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | المعامل الأيمن للـ length. |
|

**Returns:**
boolean - صحيح إذا كان كلا الطولين متساويين، وإلا خطأ.

### op_Inequality(Length left, Length right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static boolean op_Inequality(Length left, Length right)
```


يفحص عدم مساواة الطولين المعطيين.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | المعامل الأيسر للـ length. |
|
|  | right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | المعامل الأيمن للـ length. |
|

**Returns:**
boolean - صحيح إذا كان كلا الطولين غير متساويين، وإلا خطأ.

### hashCode() {#hashCode--}
```
public int hashCode()
```


يحسّب ويعيد رمز تجزئة (hash-code) لهذا الكائن Length عن طريق الجمع
رموز التجزئة للقيمة ونوع الوحدة


**Returns:**
int - عدد صحيح

### deepClone() {#deepClone--}
```
public final Length deepClone()
```


يعيد نسخة كاملة من هذا الكائن Length


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New separate instance of this Length, that is absolutely identical to this one

### getUnitFromName(String unitName) {#getUnitFromName-java.lang.String-}
```
public static int getUnitFromName(String unitName)
```


يحاول تحليل اسم الوحدة المحدد وإرجاع القيمة المقابلة لـ
تعداد Unit. يُرجع LengthUnit.Unitless إذا تعذر العثور على LengthUnit المناسب.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | unitName | java.lang.String | String، التي تمثل اسم وحدة |
|

**Returns:**
int - قيمة تعداد Unit في أي حالة، LengthUnit.Unitless عندما لا يمكن العثور على وحدة مناسبة

### tryParse(String input, Length[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Length---}
```
public static boolean tryParse(String input, Length[] result)
```


يحاول تحليل سلسلة محددة كقيمة Length، بما في ذلك
القيمة الرقمية واسم الوحدة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الإدخال | java.lang.String | سلسلة الإدخال string، التي يجب تحليلها |
|
|  | result | [Length\[\]](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | معامل الإخراج، الذي يحتوي على نتيجة التحليل. إذا فشل التحليل، يحتوي على قيمة Length افتراضية — صفر بدون وحدة. |
|

**Returns:**
boolean - صحيح إذا كان التحليل ناجحًا، خطأ إذا فشل

### parse(String input) {#parse-java.lang.String-}
```
public static Length parse(String input)
```


يحلل ويعيد السلسلة المحددة كقيمة Length، بما في ذلك
القيمة الرقمية واسم الوحدة، أو يرمي استثناءً عند الفشل


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الإدخال | java.lang.String | سلسلة الإدخال string، التي يجب تحليلها |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - Valid parsed Length instance

