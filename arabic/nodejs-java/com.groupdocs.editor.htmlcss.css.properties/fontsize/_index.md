---
title: "FontSize"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يمثل حجم الخط كوحدة خاصة أو كقيمة طول تحدد حجم الخط تاريخيًا عرض الحرف الكبير M."
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.editor.htmlcss.css.properties/fontsize/
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

| المنشئ | الوصف |
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
|  | [Larger](#Larger) | حجم نسبي أكبر - الخط سيكون أكبر نسبة إلى حجم الخط للعنصر الأب، تقريبًا بنسبة المستخدمة لفصل كلمات الحجم المطلق أعلاه. |
|
|  | [Smaller](#Smaller) | حجم نسبي أصغر - الخط سيكون أصغر نسبة إلى حجم الخط للعنصر الأب، تقريبًا بنسبة المستخدمة لفصل كلمات الحجم المطلق أعلاه. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isInitial()](#isInitial--) | يشير إلى ما إذا كان هذا الحجم الخطّي له قيمة أولية (Medium) |
|
|  | [getValue()](#getValue--) | يعيد قيمة هذا الحجم الخطّي كسلسلة نصية |
|
|  | [isLengthDefined()](#isLengthDefined--) | يشير إلى ما إذا كان هذا الحجم الخطّي معرفًا بقيمة [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length) |
|
|  | [getLength()](#getLength--) | قيمة طول، إذا كان هذا الحجم الخطّي معرفًا بها، أو يُرمى استثناءً خلاف ذلك |
|
|  | [isAbsoluteSize()](#isAbsoluteSize--) | يشير إلى ما إذا كان هذا الحجم الخطّي معرفًا بحجم مطلق ككلمة مفتاحية، بناءً على حجم الخط الافتراضي للمستخدم (الذي هو medium) |
|
|  | [isRelativeSize()](#isRelativeSize--) | يشير إلى ما إذا كان هذا الحجم الخطّي معرفًا بحجم نسبي ككلمة مفتاحية. |
|
|  | [equals(FontSize other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | يحدد ما إذا كانت نسخة هذا الحجم الخطّي مساوية للمحددة |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كانت نسخة هذا الحجم الخطّي مساوية للمحددة غير المحوّلة |
|
|  | [hashCode()](#hashCode--) | يرجع رمز تجزئة لهذه الحالة |
|
|  | [op_Equality(FontSize first, FontSize second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | يتحقق مما إذا كانت قيمتين "FontSize" متساويتين |
|
|  | [op_Inequality(FontSize first, FontSize second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-) | يتحقق مما إذا كانت قيمتين "FontSize" غير متساويتين |
|
|  | [fromLength(Length length)](#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-) | ينشئ حجم خط من الطول المحدد |
|
|  | [tryParse(String keyword, FontSize[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontSize---) | يحاول التعرف على كلمة مفتاحية محددة كقيمة كلمة مفتاحية صحيحة للخاصية 'font-size' وإرجاعها عند النجاح أو NULL عند الفشل. |
|
### FontSize() {#FontSize--}
```
public FontSize()
```


### Medium {#Medium}
```
public static final FontSize Medium
```


حجم متوسط. قيمة أولية.


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


حجم نسبي أكبر - الخط سيكون أكبر نسبة إلى حجم الخط للعنصر الأب، تقريبًا بنسبة المستخدمة لفصل كلمات الحجم المطلق أعلاه.


### Smaller {#Smaller}
```
public static final FontSize Smaller
```


حجم نسبي أصغر - الخط سيكون أصغر نسبة إلى حجم الخط للعنصر الأب، تقريبًا بنسبة المستخدمة لفصل كلمات الحجم المطلق أعلاه.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


يشير إلى ما إذا كان هذا الحجم الخطّي له قيمة أولية (Medium)


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


يعيد قيمة هذا الحجم الخطّي كسلسلة نصية


**Returns:**
java.lang.String
### isLengthDefined() {#isLengthDefined--}
```
public final boolean isLengthDefined()
```


يشير إلى ما إذا كان هذا الحجم الخطّي معرفًا بقيمة [Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)


**Returns:**
boolean
### getLength() {#getLength--}
```
public final Length getLength()
```


قيمة طول، إذا كان هذا الحجم الخطّي معرفًا بها، أو يُرمى استثناءً خلاف ذلك


**Returns:**
[Length](../../com.groupdocs.editor.htmlcss.css.datatypes/length)
### isAbsoluteSize() {#isAbsoluteSize--}
```
public final boolean isAbsoluteSize()
```


يشير إلى ما إذا كان هذا الحجم الخطّي معرفًا بحجم مطلق ككلمة مفتاحية، بناءً على حجم الخط الافتراضي للمستخدم (الذي هو medium)


**Returns:**
boolean
### isRelativeSize() {#isRelativeSize--}
```
public final boolean isRelativeSize()
```


يشير إلى ما إذا كان هذا الحجم الخطّي معرفًا بحجم نسبي ككلمة مفتاحية. سيكون الخط أكبر أو أصغر بالنسبة إلى حجم خط العنصر الأب، تقريبًا وفق النسبة المستخدمة لفصل كلمات الحجم المطلق.


**Returns:**
boolean
### equals(FontSize other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public final boolean equals(FontSize other)
```


يحدد ما إذا كانت نسخة هذا الحجم الخطّي مساوية للمحددة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | نسخة حجم خط أخرى |
|

**Returns:**
boolean - true إذا كانت متساوية، false وإلا

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كانت نسخة هذا الحجم الخطّي مساوية للمحددة غير المحوّلة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | obj | java.lang.Object | نسخة حجم خط أخرى غير محوّلة، قد تكون null |
|

**Returns:**
boolean - true إذا كانت متساوية، false إذا لم تكن متساوية أو null أو من نوع آخر

### hashCode() {#hashCode--}
```
public int hashCode()
```


يرجع رمز تجزئة لهذه الحالة


**Returns:**
int - Hash-code كعدد صحيح موقع

### op_Equality(FontSize first, FontSize second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Equality(FontSize first, FontSize second)
```


يتحقق مما إذا كانت قيمتين "FontSize" متساويتين


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | القيمة الأولى للتحقق |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | القيمة الثانية للتحقق |
|

**Returns:**
boolean - true إذا كانت متساوية، false وإلا

### op_Inequality(FontSize first, FontSize second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontSize-com.groupdocs.editor.htmlcss.css.properties.FontSize-}
```
public static boolean op_Inequality(FontSize first, FontSize second)
```


يتحقق مما إذا كانت قيمتين "FontSize" غير متساويتين


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | القيمة الأولى للتحقق |
|
|  | second | [FontSize](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | القيمة الثانية للتحقق |
|

**Returns:**
boolean - false إذا كانت متساوية، true وإلا

### fromLength(Length length) {#fromLength-com.groupdocs.editor.htmlcss.css.datatypes.Length-}
```
public static FontSize fromLength(Length length)
```


ينشئ حجم خط من الطول المحدد


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


يحاول التعرف على كلمة مفتاحية محددة كقيمة كلمة مفتاحية صحيحة للخاصية 'font-size' وإرجاعها عند النجاح أو NULL عند الفشل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | keyword | java.lang.String | كلمة مفتاحية للتحليل |
|
|  | result | [FontSize\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontsize) | النتيجة، إذا كان التحليل ناجحًا، أو #Medium.Medium غير ذلك |
|

**Returns:**
boolean - true إذا كان التحليل ناجحًا، false وإلا

