---
title: "TextDecorationLineType"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يمثل أنواع خط الزينة النصية: underline, underscore, overline و line-through (شطب)"
type: docs
weight: 13
url: /ar/nodejs-java/com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class TextDecorationLineType implements ICssProperty
```

يمثل أنواع خط الزينة النصية: تسطير (underscore)، خط فوق (overline)، وخط عبر (strikethrough).

<br />

*** ** * ** ***

هيكل غير قابل للتغيير. مشابه لـ https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line

<br />


## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TextDecorationLineType()](#TextDecorationLineType--) |  |
| [TextDecorationLineType(int value)](#TextDecorationLineType-int-) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [None](#None) | ينتج بدون أي زخرفة للنص. |
|
|  | [Underline](#Underline) | كل سطر نصي تحته خط. |
|
|  | [Overline](#Overline) | كل سطر نصي له خط فوقه. |
|
|  | [LineThrough](#LineThrough) | كل سطر نصي له خط يمر عبر الوسط. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isInitial()](#isInitial--) | يشير إلى ما إذا كانت هذه الحالة لها قيمة مبدئية \\u2014 لا شيء |
|
|  | [isUnderline()](#isUnderline--) | يشير إلى ما إذا كان التحته خط (الشرطة السفلية) مفعلاً |
|
|  | [isOverline()](#isOverline--) | يشير إلى ما إذا كان الخط فوق النص مفعلاً |
|
|  | [isLineThrough()](#isLineThrough--) | يشير إلى ما إذا كان الخط عبر النص (شطب) مفعلاً |
|
|  | [getValue()](#getValue--) | يرجع قيمة جميع العلامات في هذه الحالة كنص |
|
|  | [toString()](#toString--) | يرجع قيمة جميع العلامات في هذه الحالة كنص |
|
|  | [equals(TextDecorationLineType other)](#equals-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | يشير إلى ما إذا كانت هذه الحالة [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) مساوية للمحددة |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | يشير إلى ما إذا كانت هذه الحالة [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) مساوية للمحددة غير محوَّلة |
|
|  | [hashCode()](#hashCode--) | يرجع رمز تجزئة (hash-code) لهذه الحالة |
|
|  | [op_Equality(TextDecorationLineType first, TextDecorationLineType second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | يفحص ما إذا كانت قيمتين "TextDecorationLineType" متساويتين |
|
|  | [op_Inequality(TextDecorationLineType first, TextDecorationLineType second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | يفحص ما إذا كانت قيمتين "TextDecorationLineType" غير متساويتين |
|
|  | [fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)](#fromFlags-boolean-boolean-boolean-) | ينشئ ويعيد حالة [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) مع العلامات، المحددة بالمعلمات المحددة |
|
|  | [tryParse(String input, TextDecorationLineType[] output)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---) | يحاول تحليل سلسلة محددة وإرجاع حالة [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) صالحة |
|
|  | [op_Addition(TextDecorationLineType first, TextDecorationLineType second)](#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | يجمع (يدمج) نوعين محددين من الخطوط وينتج نوع خط جديد ناتج، حيث يتم دمج العلامات (اتحاد) |
|
|  | [op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)](#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | يطرح نوع الخط المحدد الثاني من نوع الخط المحدد الأول وينتج نوع خط جديد ناتج، حيث تكون موجودة فقط تلك العلامات من العامل الأول التي لا توجد في العامل الثاني (فرق) |
|
|  | [op_Division(TextDecorationLineType first, TextDecorationLineType second)](#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-) | يرجع تقاطعًا بين نوعي الخط الأول والثاني، حيث يتم تمكين فقط تلك العلامات التي تم تمكينها في كلا العاملين في آنٍ واحد. |
|
|  | [to_TextDecorationLineType(byte octet)](#to-TextDecorationLineType-byte-) | يحول بايت محدد (ثمانية بتات) إلى [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) المقابل، ويرمي استثناءً إذا كان التحويل غير صالح |
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
| قيمة | int |  |

### None {#None}
```
public static final TextDecorationLineType None
```


ينتج بدون أي زخرفة نصية. القيمة الأولية.


### Underline {#Underline}
```
public static final TextDecorationLineType Underline
```


كل سطر نصي تحته خط.


### Overline {#Overline}
```
public static final TextDecorationLineType Overline
```


كل سطر نصي له خط فوقه.


### LineThrough {#LineThrough}
```
public static final TextDecorationLineType LineThrough
```


كل سطر نصي له خط يمر عبر الوسط.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


يشير إلى ما إذا كانت هذه الحالة لها قيمة مبدئية \\u2014 لا شيء


**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public final boolean isUnderline()
```


يشير إلى ما إذا كان التحته خط (الشرطة السفلية) مفعلاً


**Returns:**
boolean
### isOverline() {#isOverline--}
```
public final boolean isOverline()
```


يشير إلى ما إذا كان الخط فوق النص مفعلاً


**Returns:**
boolean
### isLineThrough() {#isLineThrough--}
```
public final boolean isLineThrough()
```


يشير إلى ما إذا كان الخط عبر النص (شطب) مفعلاً


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
|  | other | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | حالة أخرى [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) |
|

**Returns:**
منطقي -  true  إذا كانت متساوية،  false  وإلا

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


يشير إلى ما إذا كانت هذه الحالة [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) مساوية للمحددة غير محوَّلة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | java.lang.Object | حالة أخرى [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)، محوَّلة إلى كائن |
|

**Returns:**
منطقي -  true  إذا كانت متساوية،  false  وإلا

### hashCode() {#hashCode--}
```
public int hashCode()
```


يرجع رمز تجزئة (hash-code) لهذه الحالة


**Returns:**
int - رمز تجزئة عدد صحيح موقع

### op_Equality(TextDecorationLineType first, TextDecorationLineType second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Equality(TextDecorationLineType first, TextDecorationLineType second)
```


يفحص ما إذا كانت قيمتين "TextDecorationLineType" متساويتين


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | المعامل الأول للتحقق |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | المعامل الثاني للتحقق |
|

**Returns:**
منطقي -  true  إذا كانت متساوية،  false  وإلا

### op_Inequality(TextDecorationLineType first, TextDecorationLineType second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static boolean op_Inequality(TextDecorationLineType first, TextDecorationLineType second)
```


يفحص ما إذا كانت قيمتين "TextDecorationLineType" غير متساويتين


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | المعامل الأول للتحقق |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | المعامل الثاني للتحقق |
|

**Returns:**
boolean -  true  إذا كانت غير متساوية،  false  وإلا

### fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough) {#fromFlags-boolean-boolean-boolean-}
```
public static TextDecorationLineType fromFlags(boolean isUnderline, boolean isOverline, boolean isLineThrough)
```


ينشئ ويعيد حالة [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) مع العلامات، المحددة بالمعلمات المحددة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | isUnderline | boolean | يحدد ما إذا كان علم التسطير مفعلاً أم لا |
|
|  | isOverline | boolean | يحدد ما إذا كان علم الخط العلوي مفعلاً أم لا |
|
|  | isLineThrough | boolean | يحدد ما إذا كان علم الخط المشطوب مفعلاً أم لا |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - New [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) instance

### tryParse(String input, TextDecorationLineType[] output) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType---}
```
public static boolean tryParse(String input, TextDecorationLineType[] output)
```


يحاول تحليل سلسلة محددة وإرجاع حالة [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) صالحة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الإدخال | java.lang.String | سلسلة الإدخال |
|
|  | output | [TextDecorationLineType\[\]](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | النتيجة. إذا كان التحليل غير صالح، تكون قيمة #None.None |
|

**Returns:**
boolean -  true  إذا كان التحليل ناجحًا،  false  عند الفشل

### op_Addition(TextDecorationLineType first, TextDecorationLineType second) {#op-Addition-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Addition(TextDecorationLineType first, TextDecorationLineType second)
```


يجمع (يدمج) نوعين محددين من الخطوط وينتج نوع خط جديد ناتج، حيث يتم دمج العلامات (اتحاد)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | معامل نوع السطر الأول |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | معامل نوع السطر الثاني |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the union between specified operands

### op_Subtraction(TextDecorationLineType first, TextDecorationLineType second) {#op-Subtraction-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Subtraction(TextDecorationLineType first, TextDecorationLineType second)
```


يطرح نوع الخط المحدد الثاني من نوع الخط المحدد الأول وينتج نوع خط جديد ناتج، حيث تكون موجودة فقط تلك العلامات من العامل الأول التي لا توجد في العامل الثاني (فرق)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | معامل نوع السطر الأول |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | معامل نوع السطر الثاني |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the difference between the first (minuend) and second (subtrahend) operands

### op_Division(TextDecorationLineType first, TextDecorationLineType second) {#op-Division-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-com.groupdocs.editor.htmlcss.css.properties.TextDecorationLineType-}
```
public static TextDecorationLineType op_Division(TextDecorationLineType first, TextDecorationLineType second)
```


يرجع تقاطعًا بين نوعي السطر الأول والثاني، حيث يتم تمكين فقط تلك العلامات التي تم تمكينها في الوقت نفسه في كلا المعاملين. له أعلى أولوية بين جميع العوامل (أعلى من الاتحاد والفرق)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | معامل نوع السطر الأول |
|
|  | second | [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) | معامل نوع السطر الثاني |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) - Result of the intersection between specified operands

### to_TextDecorationLineType(byte octet) {#to-TextDecorationLineType-byte-}
```
public static TextDecorationLineType to_TextDecorationLineType(byte octet)
```


يحول بايت محدد (ثمانية بتات) إلى [TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype) المقابل، ويرمي استثناءً إذا كان التحويل غير صالح


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | octet | byte | octet 8 بت (حقل بت)، حيث تكون البتات الخمسة الأولى صفرًا، بينما تشير البتات الثلاث الأخيرة إلى العلامات |
|

**Returns:**
[TextDecorationLineType](../../com.groupdocs.editor.htmlcss.css.properties/textdecorationlinetype)
