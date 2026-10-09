---
title: "الطول"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يمثل قيمة طول CSS بأي وحدة مدعومة بما في ذلك النسبة المئوية والنوع بدون وحدة."
type: docs
weight: 12
url: /ar/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/length/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class Length implements ICssDataType
```

يمثل قيمة طول CSS بأي وحدة مدعومة، بما في ذلك النسبة المئوية
والنوع بدون وحدة. قد تكون القيم عددًا صحيحًا أو عشريًا، سلبية، صفرًا و
موجبة. بنية غير قابلة للتغيير.

*** ** * ** ***


يغطي هذا النوع الأنواع التالية من بيانات CSS:

<https://developer.mozilla.org/en-US/docs/Web/CSS/length>

<https://developer.mozilla.org/en-US/docs/Web/CSS/percentage>

<br />


## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [Length()](#Length--) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [UnitlessZero](#UnitlessZero) | صفر عدد صحيح بدون وحدة - القيمة الافتراضية، نفس القيمة الافتراضية بدون معلمات |
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
|  | [fromValueWithUnit(float value, int unit)](#fromValueWithUnit-float-int-) | ينشئ ويعيد نسخة من نوع Length باستخدام العدد float المحدد |
و الوحدة
|
|  | [fromValueWithUnit(double value, int unit)](#fromValueWithUnit-double-int-) | ينشئ ويعيد نسخة من نوع Length باستخدام العدد double المحدد |
و الوحدة
|
|  | [fromValueWithUnit(int value, int unit)](#fromValueWithUnit-int-int-) | ينشئ ويعيد نسخة من النوع Length بناءً على عدد صحيح محدد |
العدد والوحدة
|
|  | [isUnitlessZero()](#isUnitlessZero--) | يحدد ما إذا كانت هذه النسخة صفرًا بلا وحدة أم لا. |
|
|  | [isDefault()](#isDefault--) | يشير إلى ما إذا كان لهذا الكائن Length قيمة افتراضية \\u2014 بلا وحدة |
صفر.
|
|  | [getUnitType()](#getUnitType--) | يعيد نوع الوحدة لهذا الكائن Length. |
|
|  | [isInteger()](#isInteger--) | يشير إلى ما إذا كانت القيمة الرقمية لهذا الكائن Length هي |
محددة أصلاً ومخزنة كعدد صحيح (INT32)
|
|  | [isFloat()](#isFloat--) | يشير إلى ما إذا كانت القيمة الرقمية لهذا الكائن Length هي |
محددة أصلاً ومخزنة كعدد عائم (FP32)
|
|  | [getFloatValue()](#getFloatValue--) | يعيد قيمة رقمية عائمة للكائن Length. |
|
|  | [getIntegerValue()](#getIntegerValue--) | يعيد قيمة رقمية صحيحة لهذا الكائن Length، إذا كان |
مخزناً داخلياً كعدد صحيح، أو يرمي استثناءً إذا كان
مخزناً أصلاً كعدد عائم.
|
|  | [isAbsolute()](#isAbsolute--) | يحصل على ما إذا كان الطول معطى بوحدات مطلقة. |
|
|  | [isRelative()](#isRelative--) | يحصل على ما إذا كان الطول معطى بوحدات نسبية. |
|
|  | [isZero()](#isZero--) | يحدد ما إذا كانت القيمة الرقمية لهذا الطول عددًا صفرًا |
|
|  | [isNegative()](#isNegative--) | يحدد ما إذا كانت القيمة الرقمية لهذا الطول عددًا سالبًا |
|
|  | [isPositive()](#isPositive--) | يحدد ما إذا كانت القيمة الرقمية لهذا الطول عددًا موجبًا |
|
|  | [isUnitlessNonZero()](#isUnitlessNonZero--) | القيمة من نوع بلا وحدة، لكنها ليست صفرًا - إما موجبة أو سالبة |
number
|
|  | [toPixel()](#toPixel--) | يحوّل الطول إلى عدد من البكسلات إذا كان ذلك ممكنًا. |
|
|  | [to(int unit)](#to-int-) | يحوّل الطول إلى الوحدة المحددة إذا كان ذلك ممكنًا. |
|
|  | [toStringSpecified(int unit)](#toStringSpecified-int-) | يعيد تمثيلًا نصيًا لهذا الطول بالنوع المحدد للوحدة. |
|
|  | [serializeDefault()](#serializeDefault--) | يعيد تمثيلًا نصيًا لهذا الطول في صيغته الأصلية |
الشكل (كما هو مخزن)، دون تحويل قيمة الطول إلى وحدة أخرى
نوع الوحدة
|
|  | [equals(Length other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | يحدد ما إذا كانت هذه القيمة مساوية للطول المحدد الآخر |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان هذا الطول مساويًا للكائن المحدد |
|
|  | [op_Multiply(Length multiplicand, int factor)](#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-) | يضرب الطول المعطى في العامل المحدد |
|
|  | [op_Equality(Length left, Length right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | يفحص مساواة الطولين المعطيين. |
|
|  | [op_Inequality(Length left, Length right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | يفحص عدم مساواة الطولين المعطيين. |
|
|  | [hashCode()](#hashCode--) | يحسب ويعيد قيمة تجزئة (hash-code) لهذا الكائن Length عن طريق الجمع |
قيم تجزئة للقيمة ونوع الوحدة
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


صفر عدد صحيح بدون وحدة - القيمة الافتراضية، نفس القيمة الافتراضية بدون معلمات
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


ينشئ ويعيد نسخة من نوع Length باستخدام العدد float المحدد
و الوحدة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | قيمة | float | \>أي رقم عائم (FP32) |
|
|  | وحدة | int | أي نوع وحدة صالح |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### fromValueWithUnit(double value, int unit) {#fromValueWithUnit-double-int-}
```
public static Length fromValueWithUnit(double value, int unit)
```


ينشئ ويعيد نسخة من نوع Length باستخدام العدد double المحدد
و الوحدة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | قيمة | مزدوج | أي رقم مزدوج (FP64) سيتم تحويله إلى عائم (FP32) |
|
|  | وحدة | int | أي نوع وحدة صالح |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### fromValueWithUnit(int value, int unit) {#fromValueWithUnit-int-int-}
```
public static Length fromValueWithUnit(int value, int unit)
```


ينشئ ويعيد نسخة من النوع Length بناءً على عدد صحيح محدد
العدد والوحدة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | قيمة | int | أي رقم صحيح |
|
|  | وحدة | int | أي نوع وحدة صالح |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - New instance of Length type

### isUnitlessZero() {#isUnitlessZero--}
```
public final boolean isUnitlessZero()
```


يحدد ما إذا كان هذا الكائن صفرًا بلا وحدة أم لا. صفر بلا وحدة
هو القيمة الافتراضية لهذا النوع. نفس خاصية IsDefault.


**Returns:**
boolean
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


يشير إلى ما إذا كان لهذا الكائن Length قيمة افتراضية \\u2014 بلا وحدة
صفر. نفس خاصية IsUnitlessZero.


**Returns:**
boolean
### getUnitType() {#getUnitType--}
```
public final int getUnitType()
```


يعيد نوع الوحدة لهذا الكائن Length.


**Returns:**
int
### isInteger() {#isInteger--}
```
public final boolean isInteger()
```


يشير إلى ما إذا كانت القيمة الرقمية لهذا الكائن Length هي
محددة أصلاً ومخزنة كعدد صحيح (INT32)


**Returns:**
boolean
### isFloat() {#isFloat--}
```
public final boolean isFloat()
```


يشير إلى ما إذا كانت القيمة الرقمية لهذا الكائن Length هي
محددة أصلاً ومخزنة كعدد عائم (FP32)


**Returns:**
boolean
### getFloatValue() {#getFloatValue--}
```
public final float getFloatValue()
```


يعيد قيمة عددية عائمة لكائن Length. لا يرمي استثناءً أبداً
استثناءً - يحول القيمة الصحيحة إلى عائمة إذا لزم الأمر.


**Returns:**
float
### getIntegerValue() {#getIntegerValue--}
```
public final int getIntegerValue()
```


يعيد قيمة رقمية صحيحة لهذا الكائن Length، إذا كان
مخزناً داخلياً كعدد صحيح، أو يرمي استثناءً إذا كان
مخزناً أصلاً كعدد عائم.


**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


يحصل إذا كان الطول معطى بوحدات مطلقة. قد يكون هذا الطول
محول إلى بكسلات.


**Returns:**
boolean
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


يحصل إذا كان الطول معطى بوحدات نسبية. لا يمكن أن يكون هذا الطول
محول إلى بكسلات.


**Returns:**
boolean
### isZero() {#isZero--}
```
public final boolean isZero()
```


يحدد ما إذا كانت القيمة الرقمية لهذا الطول عددًا صفرًا


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


القيمة من نوع بلا وحدة، لكنها ليست صفرًا - إما موجبة أو سالبة
number


**Returns:**
boolean
### toPixel() {#toPixel--}
```
public final float toPixel()
```


يحوّل الطول إلى عدد من البكسلات، إذا أمكن. إذا كان الحالي
الوحدة نسبية، فسيتم رمي استثناء.


**Returns:**
float - عدد البكسلات التي يمثلها الطول الحالي.

### to(int unit) {#to-int-}
```
public final float to(int unit)
```


يحوّل الطول إلى الوحدة المعطاة، إذا أمكن. إذا كانت الحالية أو
الوحدة المعطاة نسبية، فسيتم رمي استثناء.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | وحدة | int | الوحدة التي سيتم التحويل إليها. |
|

**Returns:**
float - القيمة في الوحدة المعطاة للطول الحالي.

### toStringSpecified(int unit) {#toStringSpecified-int-}
```
public final String toStringSpecified(int unit)
```


يعيد تمثيلًا نصيًا لهذا الطول بالنوع المحدد للوحدة.
سيتم تحويل القيمة الرقمية بما يتوافق مع تغيير نوع الوحدة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | وحدة | int | الوحدة المحددة، التي يجب تحويل هذا الكائن إليها قبل تسلسلها إلى سلسلة. يجب أن تكون صالحة. لا يمكن أن تكون بلا وحدة. |
|

**Returns:**
java.lang.String - تمثيل السلسلة

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


يعيد تمثيلًا نصيًا لهذا الطول في صيغته الأصلية
الشكل (كما هو مخزن)، دون تحويل قيمة الطول إلى وحدة أخرى
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
boolean - صحيح إذا كان متساويًا، وإلا خاطئ

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كان هذا الطول مساويًا للكائن المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | obj | java.lang.Object | كائن آخر من نوع Length، يتم تغليفه إلى System.Object أو أي نوع مجرد آخر أو واجهة |
|

**Returns:**
boolean - صحيح إذا كان متساويًا، وإلا خاطئ

### op_Multiply(Length multiplicand, int factor) {#op-Multiply-com.groupdocs.editor.htmlcss.css.datatypes.Length-int-}
```
public static Length op_Multiply(Length multiplicand, int factor)
```


يضرب الطول المعطى في العامل المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | multiplicand | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | Length - المضاعف |
|
|  | العامل | int | عدد صحيح عشوائي - العامل |
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
|  | left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | المعامل الطولي الأيسر. |
|
|  | right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | المعامل الطولي الأيمن. |
|

**Returns:**
boolean - صحيح إذا كان الطولان متساويين، وإلا خاطئ.

### op_Inequality(Length left, Length right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.Length-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static boolean op_Inequality(Length left, Length right)
```


يفحص عدم مساواة الطولين المعطيين.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | left | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | المعامل الطولي الأيسر. |
|
|  | right | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | المعامل الطولي الأيمن. |
|

**Returns:**
boolean - صحيح إذا كان الطولان غير متساويين، وإلا خاطئ.

### hashCode() {#hashCode--}
```
public int hashCode()
```


يحسب ويعيد قيمة تجزئة (hash-code) لهذا الكائن Length عن طريق الجمع
قيم تجزئة للقيمة ونوع الوحدة


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
تعداد الوحدة. يُرجِع LengthUnit.Unitless إذا تعذر العثور على LengthUnit المناسب.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | unitName | java.lang.String | سلسلة تمثل اسم الوحدة |
|

**Returns:**
int - قيمة تعداد الوحدة في أي حالة، LengthUnit.Unitless عندما لا يمكن العثور على وحدة مناسبة

### tryParse(String input, Length[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.datatypes.Length---}
```
public static boolean tryParse(String input, Length[] result)
```


يحاول تحليل سلسلة محددة كقيمة Length، بما في ذلك
القيمة الرقمية واسم الوحدة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الإدخال | java.lang.String | سلسلة الإدخال التي يجب تحليلها |
|
|  | result | [Length\[\]](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | معامل الإخراج الذي يحتوي على نتيجة التحليل. إذا فشل التحليل، يحتوي على قيمة Length افتراضية — صفر بدون وحدة. |
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
|  | الإدخال | java.lang.String | سلسلة الإدخال التي يجب تحليلها |
|

**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) - Valid parsed Length instance

