---
title: "FontStyle"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يحدد كيف يجب تنسيق الخط باستخدام شكل عادي أو مائل أو مائل (oblique) من عائلة الخط الخاصة به."
type: docs
weight: 11
url: /ar/java/com.groupdocs.editor.htmlcss.css.properties/fontstyle/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontStyle implements ICssProperty
```

يحدد كيفية تنسيق الخط باستخدام: عادي، مائل، أو مائل مائل من font-family الخاص به.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [FontStyle()](#FontStyle--) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Normal](#Normal) | يختار خطًا مصنفًا كعادي داخل عائلة الخط. |
|
|  | [Italic](#Italic) | يختار خطًا مصنفًا كمائل. |
|
|  | [Oblique](#Oblique) | يختار خطًا مصنفًا كمنحني (oblique). |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isInitial()](#isInitial--) | يشير إلى ما إذا كان هذا الـfont-style له قيمة أولية (Normal) |
|
|  | [getValue()](#getValue--) | يرجع قيمة هذا نمط الخط كسلسلة. |
|
|  | [equals(FontStyle other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | يحدد ما إذا كانت هذه الحالة من الـfont-style مساوية للمحددة. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كانت هذه الحالة من الـfont-style مساوية للمحددة غير محولة. |
|
|  | [hashCode()](#hashCode--) | يرجع رمز تجزئة (hash-code) لهذه الحالة. |
|
|  | [op_Equality(FontStyle first, FontStyle second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | يتحقق مما إذا كانت قيمتين "FontStyle" متساويتين |
|
|  | [op_Inequality(FontStyle first, FontStyle second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-) | يتحقق مما إذا كانت قيمتين "FontStyle" غير متساويتين |
|
|  | [tryParse(String keyword, FontStyle[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---) | يحاول التعرف على كلمة مفتاحية محددة كقيمة كلمة مفتاحية صحيحة للـ'font-style' وإرجاعها عند النجاح أو NULL عند الفشل. |
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


يختار خطًا مصنفًا كمائل. إذا لم يتوفر نسخة مائلة من الخط، يتم استخدام نسخة مصنفة كمنحني (oblique) بدلاً منها. إذا لم يتوفر أي منهما، يتم محاكاة النمط صناعيًا.


### Oblique {#Oblique}
```
public static final FontStyle Oblique
```


يختار خطًا مصنفًا كمنحني (oblique). إذا لم يتوفر نسخة منحنيّة من الخط، يتم استخدام نسخة مصنفة كمائلة بدلاً منها. إذا لم يتوفر أي منهما، يتم محاكاة النمط صناعيًا.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


يشير إلى ما إذا كان هذا الـfont-style له قيمة أولية (Normal)


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


يرجع قيمة هذا نمط الخط كسلسلة.


**Returns:**
java.lang.String
### equals(FontStyle other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public final boolean equals(FontStyle other)
```


يحدد ما إذا كانت هذه الحالة من الـfont-style مساوية للمحددة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | مثيل آخر للـfont-style |
|

**Returns:**
منطقي - true إذا كانت متساوية، false خلاف ذلك

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كانت هذه الحالة من الـfont-style مساوية للمحددة غير محولة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | obj | java.lang.Object | مثال آخر غير محول من نوع font-style، قد يكون null |
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

### op_Equality(FontStyle first, FontStyle second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Equality(FontStyle first, FontStyle second)
```


يتحقق مما إذا كانت قيمتين "FontStyle" متساويتين


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | القيمة الأولى للتحقق منها |
|
|  | second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | القيمة الثانية للتحقق منها |
|

**Returns:**
منطقي - true إذا كانت متساوية، false خلاف ذلك

### op_Inequality(FontStyle first, FontStyle second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontStyle-com.groupdocs.editor.htmlcss.css.properties.FontStyle-}
```
public static boolean op_Inequality(FontStyle first, FontStyle second)
```


يتحقق مما إذا كانت قيمتين "FontStyle" غير متساويتين


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | القيمة الأولى للتحقق منها |
|
|  | second | [FontStyle](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | القيمة الثانية للتحقق منها |
|

**Returns:**
منطقي - false إذا كانت متساوية، true خلاف ذلك

### tryParse(String keyword, FontStyle[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontStyle---}
```
public static boolean tryParse(String keyword, FontStyle[] result)
```


يحاول التعرف على كلمة مفتاحية محددة كقيمة كلمة مفتاحية صحيحة للـ'font-style' وإرجاعها عند النجاح أو NULL عند الفشل.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | كلمة مفتاح | java.lang.String | كلمة مفتاح للتحليل |
|
|  | result | [FontStyle\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontstyle) | النتيجة، إذا كان التحليل ناجحًا، أو #Normal.Normal خلاف ذلك |
|

**Returns:**
منطقي - true إذا كان التحليل ناجحًا، false خلاف ذلك

