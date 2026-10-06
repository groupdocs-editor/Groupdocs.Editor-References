---
title: "حجم الخط"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثل حجم الخط كوحدة خاصة أو قيمة طول تحدد حجم الخط تاريخيًا بعرض الحرف الكبير M."
type: docs
weight: 10
url: /ar/java/com.groupdocs.editor.htmlcss.css.properties/fontsize/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontSize implements ICssProperty
```

يمثل حجم الخط كوحدة خاصة أو قيمة طول، تحدد حجم الخط (تقليديًا عرض الحرف الكبير \"M\").

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [FontSize()](#FontSize--) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Medium](#Medium) | حجم متوسط. |
|
|  | [XxSmall](#XxSmall) | الحجم المطلق الصغير جدًا |
|
|  | [XSmall](#XSmall) | الحجم المطلق الصغير المتوسط |
|
|  | [Small](#Small) | الحجم المطلق الصغير عادةً |
|
|  | [Large](#Large) | الحجم المطلق الكبير عادةً |
|
|  | [XLarge](#XLarge) | الحجم المطلق الكبير المتوسط |
|
|  | [XxLarge](#XxLarge) | الحجم المطلق الكبير جدًا |
|
|  | [Larger](#Larger) | حجم نسبي أكبر - الخط سيكون أكبر بالنسبة إلى حجم الخط للعنصر الأب، تقريبًا بنسبة تُستخدم لفصل كلمات الحجم المطلق أعلاه. |
|
|  | [Smaller](#Smaller) | حجم نسبي أصغر - الخط سيكون أصغر بالنسبة إلى حجم الخط للعنصر الأب، تقريبًا بنسبة تُستخدم لفصل كلمات الحجم المطلق أعلاه. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isInitial()](#isInitial--) | يشير إلى ما إذا كان لهذا الحجم قيمة مبدئية (متوسط) |
|
|  | [getValue()](#getValue--) | يعيد قيمة هذا الحجم كقيمة نصية |
|
|  | [isLengthDefined()](#isLengthDefined--) | يشير إلى ما إذا كان حجم الخط هذا معرفًا بقيمة [الطول](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |
|
|  | [getLength()](#getLength--) | قيمة طول، إذا تم تعريف حجم الخط هذا بها، أو يُرمى استثناء خلاف ذلك |
|
|  | [isAbsoluteSize()](#isAbsoluteSize--) | يشير إلى ما إذا كان حجم الخط هذا معرفًا بحجم مطلق ككلمة مفتاح، بناءً على حجم الخط الافتراضي للمستخدم (الذي هو متوسط) |
|
|  | [isRelativeSize()](#isRelativeSize--) | يشير إلى ما إذا كان حجم الخط هذا معرفًا بحجم نسبي ككلمة مفتاح. |
|
|  | [equals(FontSize other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | يحدد ما إذا كانت مثيلة حجم الخط هذه مساوية للمحددة |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كانت مثيلة حجم الخط هذه مساوية للمحددة غير المحولة |
|
|  | [hashCode()](#hashCode--) | يرجع رمز تجزئة (hash-code) لهذه الحالة. |
|
|  | [op_Equality(FontSize first, FontSize second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | يفحص ما إذا كانت قيمتي "FontSize" متساويتين |
|
|  | [op_Inequality(FontSize first, FontSize second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | يفحص ما إذا كانت قيمتي "FontSize" غير متساويتين |
|
|  | [fromLength(Length length)](#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | ينشئ حجم الخط من الطول المحدد |
|
|  | [tryParse(String keyword, FontSize[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---) | يحاول التعرف على كلمة مفتاح محددة كقيمة كلمة مفتاح صحيحة للخاصية 'font-size' وإرجاعها عند النجاح أو NULL عند الفشل. |
|
### FontSize() {#FontSize--}
```
public FontSize()
```


### Medium {#Medium}
```
public static final FontSize Medium
```


حجم متوسط. القيمة الأولية.


### XxSmall {#XxSmall}
```
public static final FontSize XxSmall
```


الحجم المطلق الصغير جدًا


### XSmall {#XSmall}
```
public static final FontSize XSmall
```


الحجم المطلق الصغير المتوسط


### Small {#Small}
```
public static final FontSize Small
```


الحجم المطلق الصغير عادةً


### Large {#Large}
```
public static final FontSize Large
```


الحجم المطلق الكبير عادةً


### XLarge {#XLarge}
```
public static final FontSize XLarge
```


الحجم المطلق الكبير المتوسط


### XxLarge {#XxLarge}
```
public static final FontSize XxLarge
```


الحجم المطلق الكبير جدًا


### Larger {#Larger}
```
public static final FontSize Larger
```


حجم نسبي أكبر - الخط سيكون أكبر بالنسبة إلى حجم الخط للعنصر الأب، تقريبًا بنسبة تُستخدم لفصل كلمات الحجم المطلق أعلاه.


### Smaller {#Smaller}
```
public static final FontSize Smaller
```


حجم نسبي أصغر - الخط سيكون أصغر بالنسبة إلى حجم الخط للعنصر الأب، تقريبًا بنسبة تُستخدم لفصل كلمات الحجم المطلق أعلاه.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


يشير إلى ما إذا كان لهذا الحجم قيمة مبدئية (متوسط)


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


يعيد قيمة هذا الحجم كقيمة نصية


**Returns:**
java.lang.String
### isLengthDefined() {#isLengthDefined--}
```
public final boolean isLengthDefined()
```


يشير إلى ما إذا كان حجم الخط هذا معرفًا بقيمة [الطول](../../com.groupdocs.editor.htmlcss.css.datatypes/length)


**Returns:**
boolean
### getLength() {#getLength--}
```
public final Length getLength()
```


قيمة طول، إذا تم تعريف حجم الخط هذا بها، أو يُرمى استثناء خلاف ذلك


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### isAbsoluteSize() {#isAbsoluteSize--}
```
public final boolean isAbsoluteSize()
```


يشير إلى ما إذا كان حجم الخط هذا معرفًا بحجم مطلق ككلمة مفتاح، بناءً على حجم الخط الافتراضي للمستخدم (الذي هو متوسط)


**Returns:**
boolean
### isRelativeSize() {#isRelativeSize--}
```
public final boolean isRelativeSize()
```


يشير إلى ما إذا كان حجم الخط هذا معرفًا بحجم نسبي ككلمة مفتاح. سيكون الخط أكبر أو أصغر بالنسبة إلى حجم خط العنصر الأب، تقريبًا بنسبة تُستخدم لفصل كلمات الحجم المطلق.


**Returns:**
boolean
### equals(FontSize other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public final boolean equals(FontSize other)
```


يحدد ما إذا كانت مثيلة حجم الخط هذه مساوية للمحددة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | مثيلة حجم الخط الأخرى |
|

**Returns:**
منطقي - true إذا كانت متساوية، false خلاف ذلك

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كانت مثيلة حجم الخط هذه مساوية للمحددة غير المحولة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | obj | java.lang.Object | مثيلة حجم الخط غير المحولة الأخرى، قد تكون null |
|

**Returns:**
منطقي - true إذا كانت متساوية، false إذا لم تكن متساوية أو null أو من نوع آخر

### hashCode() {#hashCode--}
```
public int hashCode()
```


يرجع رمز تجزئة (hash-code) لهذه الحالة.


**Returns:**
int - رمز التجزئة كعدد صحيح موقع

### op_Equality(FontSize first, FontSize second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Equality(FontSize first, FontSize second)
```


يفحص ما إذا كانت قيمتي "FontSize" متساويتين


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | القيمة الأولى للتحقق منها |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | القيمة الثانية للتحقق منها |
|

**Returns:**
منطقي - true إذا كانت متساوية، false خلاف ذلك

### op_Inequality(FontSize first, FontSize second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Inequality(FontSize first, FontSize second)
```


يفحص ما إذا كانت قيمتي "FontSize" غير متساويتين


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | القيمة الأولى للتحقق منها |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | القيمة الثانية للتحقق منها |
|

**Returns:**
منطقي - false إذا كانت متساوية، true خلاف ذلك

### fromLength(Length length) {#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static FontSize fromLength(Length length)
```


ينشئ حجم الخط من الطول المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | length | [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) | قيمة طول، لا يمكن أن تكون بلا وحدة أو سلبية |
|

**Returns:**
[FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) - New FontSize instance

### tryParse(String keyword, FontSize[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---}
```
public static boolean tryParse(String keyword, FontSize[] result)
```


يحاول التعرف على كلمة مفتاح محددة كقيمة كلمة مفتاح صحيحة للخاصية 'font-size' وإرجاعها عند النجاح أو NULL عند الفشل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | كلمة مفتاح | java.lang.String | كلمة مفتاح للتحليل |
|
|  | result | [FontSize\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | النتيجة، إذا كان التحليل ناجحًا، أو #Medium.Medium خلاف ذلك |
|

**Returns:**
منطقي - true إذا كان التحليل ناجحًا، false خلاف ذلك

