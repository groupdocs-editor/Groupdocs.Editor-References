---
title: "TextDecorationLineType"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثل أنواع خط تزيين النص: underline, underscore, overline و line-through (strikethrough)"
type: docs
weight: 13
url: /ar/java/com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class TextDecorationLineType implements ICssProperty
```

يمثل أنواع خط الزخرفة النصية: تسطير (underscore)، خط فوق (overline)، وخط عبر (strikethrough).

<br />

*** ** * ** ***

هيكل غير قابل للتغيير. مشابه لـ https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line

<br />


## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TextDecorationLineType()](#TextDecorationLineType--) |  |
| [TextDecorationLineType(int value)](#TextDecorationLineType-int-) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [None](#None) | لا ينتج أي تزيين للنص. |
|
|  | [Underline](#Underline) | كل سطر من النص يتم تحته خط. |
|
|  | [Overline](#Overline) | كل سطر من النص يحتوي على سطر فوقه. |
|
|  | [LineThrough](#LineThrough) | كل سطر من النص يحتوي على سطر يمر عبر الوسط. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isInitial()](#isInitial--) | يشير إلى ما إذا كانت هذه الحالة لها قيمة أولية \\u2014 لا شيء |
|
|  | [isUnderline()](#isUnderline--) | يشير إلى ما إذا كان التحتي (الشرطة السفلية) مفعلاً |
|
|  | [isOverline()](#isOverline--) | يشير إلى ما إذا كان الخط العلوي مفعلاً |
|
|  | [isLineThrough()](#isLineThrough--) | يشير إلى ما إذا كان الخط المشطوب (strikethrough) مفعلاً |
|
|  | [getValue()](#getValue--) | يرجع قيمة جميع العلامات في هذه الحالة كنص |
|
|  | [toString()](#toString--) | يرجع قيمة جميع العلامات في هذه الحالة كنص |
|
|  | [equals(TextDecorationLineType other)](#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | يشير إلى ما إذا كانت هذه الحالة [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) مساوية للمحددة |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | يشير إلى ما إذا كانت هذه الحالة [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) مساوية للمحددة غير محوّلة |
|
|  | [hashCode()](#hashCode--) | يرجع رمز تجزئة (hash-code) لهذه الحالة |
|
|  | [op_Equality(TextDecorationLineType first, TextDecorationLineType second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | يفحص ما إذا كانت قيمتين \"TextDecorationLineType\" متساويتين |
|
|  | [op_Inequality(TextDecorationLineType first, TextDecorationLineType second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | يفحص ما إذا كانت قيمتين \"TextDecorationLineType\" غير متساويتين |
|
|  | [fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)](#fromFlags-boolean-boolean-boolean-) | ينشئ ويرجع حالة [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) مع العلامات، المحددة بواسطة المعلمات المحددة |
|
|  | [tryParse(String input, TextDecorationLineType[] output)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---) | يحاول تحليل سلسلة محددة وإرجاع حالة صالحة من نوع [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) |
|
|  | [op_Addition(TextDecorationLineType first, TextDecorationLineType second)](#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | يجمع (يدمج) نوعين من الخطوط المحددة وينتج نوع خط جديد ناتج، حيث يتم دمج العلامات (اتحاد) |
|
|  | [op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)](#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | يطرح نوع الخط المحدد الثاني من نوع الخط المحدد الأول وينتج نوع خط جديد ناتج، حيث توجد فقط تلك العلامات من المعامل الأول التي لا توجد في المعامل الثاني (فرق) |
|
|  | [op_Division(TextDecorationLineType first, TextDecorationLineType second)](#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | يرجع تقاطعًا بين نوعي الخط الأول والثاني، حيث يتم تمكين فقط تلك العلامات التي تم تمكينها في الوقت نفسه في كلا المعاملين. |
|
|  | [to_TextDecorationLineType(byte octet)](#to-TextDecorationLineType-byte-) | يحوّل البايت المحدد (ثمانية بتات) إلى النوع المقابل [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)، ويرمي استثناءً إذا كان التحويل غير صالح |
|
### TextDecorationLineType() {#TextDecorationLineType--}
```
public TextDecorationLineType()
```


### TextDecorationLineType(int value) {#TextDecorationLineType-int-}
```
public TextDecorationLineType(int value)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | int |  |

### None {#None}
```
public static final TextDecorationLineType None
```


ينتج بدون زخرفة نصية. القيمة الأولية.


### Underline {#Underline}
```
public static final TextDecorationLineType Underline
```


كل سطر من النص يتم تحته خط.


### Overline {#Overline}
```
public static final TextDecorationLineType Overline
```


كل سطر من النص يحتوي على سطر فوقه.


### LineThrough {#LineThrough}
```
public static final TextDecorationLineType LineThrough
```


كل سطر من النص يحتوي على سطر يمر عبر الوسط.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


يشير إلى ما إذا كانت هذه الحالة لها قيمة أولية \\u2014 لا شيء


**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


يشير إلى ما إذا كان التحتي (الشرطة السفلية) مفعلاً


**Returns:**
boolean
### isOverline() {#isOverline--}
```
public final boolean isOverline()
```


يشير إلى ما إذا كان الخط العلوي مفعلاً


**Returns:**
boolean
### isLineThrough() {#isLineThrough--}
```
public final boolean isLineThrough()
```


يشير إلى ما إذا كان الخط المشطوب (strikethrough) مفعلاً


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


يرجع قيمة جميع العلامات في هذه الحالة كنص


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


يرجع قيمة جميع العلامات في هذه الحالة كنص


**Returns:**
java.lang.String
### equals(TextDecorationLineType other) {#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public final boolean equals(TextDecorationLineType other)
```


يشير إلى ما إذا كانت هذه الحالة [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) مساوية للمحددة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | حالة أخرى من نوع [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) |
|

**Returns:**
منطقي -  true  إذا كانت متساوية،  false  غير ذلك

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


يشير إلى ما إذا كانت هذه الحالة [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) مساوية للمحددة غير محوّلة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | java.lang.Object | حالة أخرى من نوع [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)، محوّلة إلى كائن |
|

**Returns:**
منطقي -  true  إذا كانت متساوية،  false  غير ذلك

### hashCode() {#hashCode--}
```
public int hashCode()
```


يرجع رمز تجزئة (hash-code) لهذه الحالة


**Returns:**
int - رمز تجزئة (hash-code) عدد صحيح موقع

### op_Equality(TextDecorationLineType first, TextDecorationLineType second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Equality(TextDecorationLineType first, TextDecorationLineType second)
```


يفحص ما إذا كانت قيمتين \"TextDecorationLineType\" متساويتين


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | المعامل الأول للفحص |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | المعامل الثاني للتحقق |
|

**Returns:**
منطقي -  true  إذا كانت متساوية،  false  غير ذلك

### op_Inequality(TextDecorationLineType first, TextDecorationLineType second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Inequality(TextDecorationLineType first, TextDecorationLineType second)
```


يفحص ما إذا كانت قيمتين \"TextDecorationLineType\" غير متساويتين


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | المعامل الأول للفحص |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | المعامل الثاني للتحقق |
|

**Returns:**
منطقي -  true  إذا كانت غير متساوية،  false  غير ذلك

### fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough) {#fromFlags-boolean-boolean-boolean-}
```
public static TextDecorationLineType fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)
```


ينشئ ويرجع حالة [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) مع العلامات، المحددة بواسطة المعلمات المحددة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | isUnderline | boolean | يحدد ما إذا كانت علامة التسطير مفعلة أم لا |
|
|  | isOverline | boolean | يحدد ما إذا كانت علامة الخط العلوي مفعلة أم لا |
|
|  | isLineThrough | boolean | يحدد ما إذا كانت علامة الخط عبر مفعلة أم لا |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - New [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instance

### tryParse(String input, TextDecorationLineType[] output) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---}
```
public static boolean tryParse(String input, TextDecorationLineType[] output)
```


يحاول تحليل سلسلة محددة وإرجاع حالة صالحة من نوع [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الإدخال | java.lang.String | سلسلة الإدخال |
|
|  | output | [TextDecorationLineType\[\]](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | النتيجة. إذا كان التحليل غير صالح، تكون قيمة #None.None |
|

**Returns:**
منطقي -  true  إذا كان التحليل ناجحًا،  false  عند الفشل

### op_Addition(TextDecorationLineType first, TextDecorationLineType second) {#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Addition(TextDecorationLineType first, TextDecorationLineType second)
```


يجمع (يدمج) نوعين من الخطوط المحددة وينتج نوع خط جديد ناتج، حيث يتم دمج العلامات (اتحاد)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | المعامل الأول لنوع السطر |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | المعامل الثاني لنوع السطر |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the union between specified operands

### op_Subtraction(TextDecorationLineType first, TextDecorationLineType second) {#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)
```


يطرح نوع الخط المحدد الثاني من نوع الخط المحدد الأول وينتج نوع خط جديد ناتج، حيث توجد فقط تلك العلامات من المعامل الأول التي لا توجد في المعامل الثاني (فرق)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | المعامل الأول لنوع السطر |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | المعامل الثاني لنوع السطر |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the difference between the first (minuend) and second (subtrahend) operands

### op_Division(TextDecorationLineType first, TextDecorationLineType second) {#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Division(TextDecorationLineType first, TextDecorationLineType second)
```


يعيد تقاطعًا بين نوعي السطر الأول والثاني، حيث يتم تمكين فقط تلك العلامات التي تم تمكينها في الوقت نفسه في كلا المعاملين. له أعلى أولوية بين جميع العمليات (أعلى من الاتحاد والفرق)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | المعامل الأول لنوع السطر |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | المعامل الثاني لنوع السطر |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the intersection between specified operands

### to_TextDecorationLineType(byte octet) {#to-TextDecorationLineType-byte-}
```
public static TextDecorationLineType to_TextDecorationLineType(byte octet)
```


يحوّل البايت المحدد (ثمانية بتات) إلى النوع المقابل [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)، ويرمي استثناءً إذا كان التحويل غير صالح


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | octet | بايت | أوكتت 8 بت (حقل بت)، حيث تكون البتات الخمسة الأولى صفرًا، بينما تشير البتات الثلاثة الأخيرة إلى العلامات |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)
