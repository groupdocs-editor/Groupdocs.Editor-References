---
title: "QuoteType"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثل أحرف الاقتباس - الاقتباس المفرد والاقتباس المزدوج"
type: docs
weight: 10
url: /ar/java/com.groupdocs.editor.htmlcss.serialization/quotetype/
---
**Inheritance:**
java.lang.Object
```
public class QuoteType
```

يمثل أحرف الاقتباس - الاقتباس المفرد (') والاقتباس المزدوج (\")

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [QuoteType()](#QuoteType--) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [SingleQuote](#SingleQuote) | الاقتباس المفرد (الحرف U+0027 APOSTROPHE) |
|
|  | [DoubleQuote](#DoubleQuote) | الاقتباس المزدوج (الحرف U+0022 QUOTATION MARK) |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getCode()](#getCode--) | نقطة الشيفرة للحرف الحالي (U+0027 أو U+0022) |
|
|  | [getCharacter()](#getCharacter--) | الحرف لتغليفه بالاقتباس |
|
|  | [getHtmlEncoded()](#getHtmlEncoded--) | حرف مُشفّر بـ HTML |
|
|  | [toString()](#toString--) | يرجع سلسلة "SingleQuote" أو "DoubleQuote" اعتمادًا على القيمة الحالية |
|
|  | [equals(QuoteType other)](#equals-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | يشير إلى ما إذا كانت هذه الحالة من نوع الاقتباس مساوية للمحددة |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | يشير إلى ما إذا كانت هذه الحالة من نوع الاقتباس مساوية للمحددة غير محوّلة |
|
|  | [hashCode()](#hashCode--) | يرجع قيمة تجزئة لهذا الحرف |
|
|  | [op_Equality(QuoteType first, QuoteType second)](#op-Equality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | يفحص ما إذا كانت قيمتي "QuoteType" متساويتين |
|
|  | [op_Inequality(QuoteType first, QuoteType second)](#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | يفحص ما إذا كانت قيمتي "QuoteType" غير متساويتين |
|
|  | [to_Char(QuoteType quote)](#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-) | يحوّل الكائن المحدد من نوع [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) إلى char |
|
|  | [to_QuoteType(char character)](#to-QuoteType-char-) | يحوّل char المحدد إلى [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) المقابل، ويرمي استثناءً إذا كان التحويل غير صالح |
|
### QuoteType() {#QuoteType--}
```
public QuoteType()
```


### SingleQuote {#SingleQuote}
```
public static final QuoteType SingleQuote
```


الاقتباس المفرد (الحرف U+0027 APOSTROPHE)


### DoubleQuote {#DoubleQuote}
```
public static final QuoteType DoubleQuote
```


الاقتباس المزدوج (الحرف U+0022 QUOTATION MARK)


### getCode() {#getCode--}
```
public final int getCode()
```


نقطة الشيفرة للحرف الحالي (U+0027 أو U+0022)


**Returns:**
int
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```


الحرف لتغليفه بالاقتباس


**Returns:**
char
### getHtmlEncoded() {#getHtmlEncoded--}
```
public final String getHtmlEncoded()
```


حرف مُشفّر بـ HTML


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


يرجع سلسلة "SingleQuote" أو "DoubleQuote" اعتمادًا على القيمة الحالية


**Returns:**
java.lang.String -
### equals(QuoteType other) {#equals-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public final boolean equals(QuoteType other)
```


يشير إلى ما إذا كانت هذه الحالة من نوع الاقتباس مساوية للمحددة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | كائن آخر من نوع QuoteType للتحقق |
|

**Returns:**
منطقي - true إذا كانت متساوية، false إذا كانت غير متساوية

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يشير إلى ما إذا كانت هذه الحالة من نوع الاقتباس مساوية للمحددة غير محوّلة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | obj | java.lang.Object | كائن غير محوّل، من المتوقع أن يكون من نوع [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) |
|

**Returns:**
منطقي - true إذا كانت متساوية، false إذا كانت غير متساوية

### hashCode() {#hashCode--}
```
public int hashCode()
```


يرجع قيمة تجزئة لهذا الحرف


**Returns:**
int - رمز التجزئة كعدد صحيح موقع

### op_Equality(QuoteType first, QuoteType second) {#op-Equality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static boolean op_Equality(QuoteType first, QuoteType second)
```


يفحص ما إذا كانت قيمتي "QuoteType" متساويتين


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | القيمة الأولى للتحقق منها |
|
|  | second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | القيمة الثانية للتحقق منها |
|

**Returns:**
منطقي - true إذا كانت متساوية، false خلاف ذلك

### op_Inequality(QuoteType first, QuoteType second) {#op-Inequality-com.groupdocs.editor.htmlcss.serialization.QuoteType-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static boolean op_Inequality(QuoteType first, QuoteType second)
```


يفحص ما إذا كانت قيمتي "QuoteType" غير متساويتين


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | القيمة الأولى للتحقق منها |
|
|  | second | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | القيمة الثانية للتحقق منها |
|

**Returns:**
منطقي - false إذا كانت متساوية، true خلاف ذلك

### to_Char(QuoteType quote) {#to-Char-com.groupdocs.editor.htmlcss.serialization.QuoteType-}
```
public static char to_Char(QuoteType quote)
```


يحوّل الكائن المحدد من نوع [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) إلى char


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | quote | [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) | كائن من نوع Quote للتحويل |
|

**Returns:**
char
### to_QuoteType(char character) {#to-QuoteType-char-}
```
public static QuoteType to_QuoteType(char character)
```


يحوّل char المحدد إلى [QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype) المقابل، ويرمي استثناءً إذا كان التحويل غير صالح


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | حرف | char | حرف اقتباس مفرد (U+0027 APOSTROPHE) أو حرف اقتباس مزدوج (U+0022 QUOTATION MARK). سيتم رمي استثناء إذا تم تحديد أي حرف آخر. |
|

**Returns:**
[QuoteType](../../com.groupdocs.editor.htmlcss.serialization/quotetype)
