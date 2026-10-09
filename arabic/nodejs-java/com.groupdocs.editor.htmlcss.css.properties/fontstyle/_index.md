---
title: "FontStyle"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يحدد كيفية تنسيق الخط باستخدام شكل عادي أو مائل أو مائل مائل من عائلة الخط الخاصة به."
type: docs
weight: 11
url: /ar/nodejs-java/com.groupdocs.editor.htmlcss.css.properties/fontstyle/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontStyle implements ICssProperty
```

يحدد كيفية تنسيق الخط باستخدام: عادي، مائل، أو مائل مائل من عائلة الخط.

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [FontStyle()](#FontStyle--) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Normal](#Normal) | يختار خطًا مصنفًا كعادي داخل عائلة الخط. |
|
|  | [Italic](#Italic) | يختار خطًا مصنفًا كمائل. |
|
|  | [Oblique](#Oblique) | يختار خطًا مصنفًا كمنحني. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isInitial()](#isInitial--) | يشير إلى ما إذا كان نمط الخط هذا يحتوي على قيمة أولية (عادي) |
|
|  | [getValue()](#getValue--) | يرجع قيمة نمط الخط هذا كسلسلة نصية |
|
|  | [equals(FontStyle other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | يحدد ما إذا كانت هذه الحالة من نمط الخط مساوية للمحددة |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كانت هذه الحالة من نمط الخط مساوية للمحددة غير محوَّلة |
|
|  | [hashCode()](#hashCode--) | يرجع رمز تجزئة لهذه الحالة |
|
|  | [op_Equality(FontStyle first, FontStyle second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | يتحقق مما إذا كانت قيمتي "FontStyle" متساويتين |
|
|  | [op_Inequality(FontStyle first, FontStyle second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | يتحقق مما إذا كانت قيمتي "FontStyle" غير متساويتين |
|
|  | [tryParse(String keyword, FontStyle[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---) | يحاول التعرف على كلمة مفتاحية محددة كقيمة كلمة مفتاحية صحيحة لـ 'font-style' وإرجاعها عند النجاح أو NULL عند الفشل. |
|
### FontStyle() {#FontStyle--}
```
public FontStyle()
```


### Normal {#Normal}
```
public static final FontStyle Normal
```


يختار خطًا مصنفًا كعادي داخل عائلة الخط. القيمة الأولية.


### Italic {#Italic}
```
public static final FontStyle Italic
```


يختار خطًا مصنفًا كمائل. إذا لم يتوفر نسخة مائلة من الخط، يُستخدم نسخة مصنفة كمائل مائل بدلاً منها. إذا لم يتوفر أي منهما، يتم محاكاة النمط صناعيًا.


### Oblique {#Oblique}
```
public static final FontStyle Oblique
```


يختار خطًا مصنفًا كمائل مائل. إذا لم يتوفر نسخة مائلة مائلة من الخط، يُستخدم نسخة مصنفة كمائلة بدلاً منها. إذا لم يتوفر أي منهما، يتم محاكاة النمط صناعيًا.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


يشير إلى ما إذا كان نمط الخط هذا يحتوي على قيمة أولية (عادي)


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


يرجع قيمة نمط الخط هذا كسلسلة نصية


**Returns:**
java.lang.String
### equals(FontStyle other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public final boolean equals(FontStyle other)
```


يحدد ما إذا كانت هذه الحالة من نمط الخط مساوية للمحددة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | مثال آخر لخاصية الخط |
|

**Returns:**
boolean - true إذا كانت متساوية، false وإلا

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كانت هذه الحالة من نمط الخط مساوية للمحددة غير محوَّلة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | obj | java.lang.Object | مثال آخر غير محول لخاصية الخط، قد يكون null |
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

### op_Equality(FontStyle first, FontStyle second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Equality(FontStyle first, FontStyle second)
```


يتحقق مما إذا كانت قيمتي "FontStyle" متساويتين


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | القيمة الأولى للتحقق |
|
|  | second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | القيمة الثانية للتحقق |
|

**Returns:**
boolean - true إذا كانت متساوية، false وإلا

### op_Inequality(FontStyle first, FontStyle second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Inequality(FontStyle first, FontStyle second)
```


يتحقق مما إذا كانت قيمتي "FontStyle" غير متساويتين


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | القيمة الأولى للتحقق |
|
|  | second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | القيمة الثانية للتحقق |
|

**Returns:**
boolean - false إذا كانت متساوية، true وإلا

### tryParse(String keyword, FontStyle[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---}
```
public static boolean tryParse(String keyword, FontStyle[] result)
```


يحاول التعرف على كلمة مفتاحية محددة كقيمة كلمة مفتاحية صحيحة لـ 'font-style' وإرجاعها عند النجاح أو NULL عند الفشل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | keyword | java.lang.String | كلمة مفتاحية للتحليل |
|
|  | result | [FontStyle\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | النتيجة، إذا كان التحليل ناجحًا، أو #Normal.Normal وإلا |
|

**Returns:**
boolean - true إذا كان التحليل ناجحًا، false وإلا

