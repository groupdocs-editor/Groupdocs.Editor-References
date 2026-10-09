---
title: "FontWeight"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "خاصية Font-weight تحدد وزن الخط أو سمكه."
type: docs
weight: 12
url: /ar/nodejs-java/com.groupdocs.editor.htmlcss.css.properties/fontweight/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.editor.htmlcss.css.properties.ICssProperty
```
public class FontWeight implements ICssProperty
```

خاصية Font-weight تحدد وزن الخط (أو سمكه). الأوزان المتاحة تعتمد على عائلة الخط (font-family) المحددة حاليًا.

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [FontWeight()](#FontWeight--) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Lighter](#Lighter) | وزن خط نسبي أخف من العنصر الأب |
|
|  | [Bolder](#Bolder) | وزن خط نسبي أثقل من العنصر الأب |
|
|  | [Normal](#Normal) | وزن خط عادي. |
|
|  | [Bold](#Bold) | وزن خط غامق. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isInitial()](#isInitial--) | يشير إلى ما إذا كان هذا الحجم الخطّي له قيمة أولية (Medium) |
|
|  | [getNumber()](#getNumber--) | يرجع عددًا - قيمة صحيحة بين 1 و 1000، شاملة، تصف سمك الخط، أو يطرح استثناءً إذا كان سمك الخط الحالي ليس مطلقًا بل نسبيًا |
|
|  | [isAbsolute()](#isAbsolute--) | يشير إلى ما إذا كانت هذه الحالة من font-weight تخزن قيمة مطلقة لوزن (سمك) الخط كعدد صحيح |
|
|  | [isRelative()](#isRelative--) | يشير إلى ما إذا كانت هذه الحالة من font-weight تخزن قيمة نسبية لوزن (سمك) الخط - مقارنةً بسمك العنصر الأب |
|
|  | [getValue()](#getValue--) | يرجع قيمة هذا font-weight كسلسلة نصية |
|
|  | [equals(FontWeight other)](#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | يحدد ما إذا كانت كائنات FontWeight المحددة متساوية |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كانت هذه الحالة من FontWeight متساوية مع المحددة غير المحولة |
|
|  | [hashCode()](#hashCode--) | يرجع رمز تجزئة لهذه الحالة |
|
|  | [op_Equality(FontWeight first, FontWeight second)](#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | يفحص ما إذا كانت قيمتين "FontWeight" متساويتين |
|
|  | [op_Inequality(FontWeight first, FontWeight second)](#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-) | يفحص ما إذا كانت قيمتين "FontWeight" غير متساويتين |
|
|  | [fromNumber(int number)](#fromNumber-int-) | ينشئ font-weight من رقم محدد |
|
|  | [tryParse(String input, FontWeight[] result)](#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---) | يحاول تحليل سلسلة محددة وإرجاع كائن FontWeight صالح عند النجاح |
|
### FontWeight() {#FontWeight--}
```
public FontWeight()
```


### Lighter {#Lighter}
```
public static final FontWeight Lighter
```


وزن خط نسبي أخف من العنصر الأب


### Bolder {#Bolder}
```
public static final FontWeight Bolder
```


وزن خط نسبي أثقل من العنصر الأب


### Normal {#Normal}
```
public static final FontWeight Normal
```


وزن الخط العادي. يساوي 400.


### Bold {#Bold}
```
public static final FontWeight Bold
```


وزن الخط الغامق. يساوي 700.


### isInitial() {#isInitial--}
```
public final boolean isInitial()
```


يشير إلى ما إذا كان هذا الحجم الخطّي له قيمة أولية (Medium)


**Returns:**
boolean
### getNumber() {#getNumber--}
```
public final int getNumber()
```


يرجع عددًا - قيمة صحيحة بين 1 و 1000، شاملة، تصف سمك الخط، أو يطرح استثناءً إذا كان سمك الخط الحالي ليس مطلقًا بل نسبيًا


**Returns:**
int
### isAbsolute() {#isAbsolute--}
```
public final boolean isAbsolute()
```


يشير إلى ما إذا كانت هذه الحالة من font-weight تخزن قيمة مطلقة لوزن (سمك) الخط كعدد صحيح


**Returns:**
boolean
### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


يشير إلى ما إذا كانت هذه الحالة من font-weight تخزن قيمة نسبية لوزن (سمك) الخط - مقارنةً بسمك العنصر الأب


**Returns:**
boolean
### getValue() {#getValue--}
```
public final String getValue()
```


يرجع قيمة هذا font-weight كسلسلة نصية


**Returns:**
java.lang.String
### equals(FontWeight other) {#equals-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public final boolean equals(FontWeight other)
```


يحدد ما إذا كانت كائنات FontWeight المحددة متساوية


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | كائن FontWeight آخر للتحقق من المساواة |
|

**Returns:**
منطقي - true إذا كانت متساوية، false إذا كانت غير متساوية

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كانت هذه الحالة من FontWeight متساوية مع المحددة غير المحولة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | obj | java.lang.Object | كائن FontWeight غير محول آخر، قد يكون null |
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

### op_Equality(FontWeight first, FontWeight second) {#op-Equality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Equality(FontWeight first, FontWeight second)
```


يفحص ما إذا كانت قيمتين "FontWeight" متساويتين


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | القيمة الأولى للتحقق |
|
|  | second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | القيمة الثانية للتحقق |
|

**Returns:**
boolean - true إذا كانت متساوية، false وإلا

### op_Inequality(FontWeight first, FontWeight second) {#op-Inequality-com.groupdocs.editor.htmlcss.css.properties.FontWeight-com.groupdocs.editor.htmlcss.css.properties.FontWeight-}
```
public static boolean op_Inequality(FontWeight first, FontWeight second)
```


يفحص ما إذا كانت قيمتين "FontWeight" غير متساويتين


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | القيمة الأولى للتحقق |
|
|  | second | [FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | القيمة الثانية للتحقق |
|

**Returns:**
boolean - false إذا كانت متساوية، true وإلا

### fromNumber(int number) {#fromNumber-int-}
```
public static FontWeight fromNumber(int number)
```


ينشئ font-weight من رقم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | number | int | عدد صحيح غير موقع، يجب أن يكون ضمن النطاق [1..1000] |
|

**Returns:**
[FontWeight](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) - New FontWeight instance or exception

### tryParse(String input, FontWeight[] result) {#tryParse-java.lang.String-com.groupdocs.editor.htmlcss.css.properties.FontWeight---}
```
public static boolean tryParse(String input, FontWeight[] result)
```


يحاول تحليل سلسلة محددة وإرجاع كائن FontWeight صالح عند النجاح


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الإدخال | java.lang.String | السلسلة النصية المدخلة للتحليل |
|
|  | result | [FontWeight\[\]](../../com.groupdocs.editor.htmlcss.css.properties/fontweight) | قيمة FontWeight صالحة عند النجاح أو #Normal.Normal عند الفشل |
|

**Returns:**
منطقي - نجاح (true) أو فشل (false) التحليل

