---
title: "ArgbColor"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يمثل قيمة لون واحدة بصيغة ARGB مع محولات ومسلسلات."
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype)
```
public class ArgbColor extends Struct<ArgbColor> implements ICssDataType
```

يمثل قيمة لون واحدة بصيغة ARGB مع محولات ومسلسلات.

<br />

*** ** * ** ***

تم تصميم هذا النوع ليكون مفيدًا لـ (ولكن ليس محصورًا في) عمليات CSS. راجع المزيد: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

<br />


## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ArgbColor()](#ArgbColor--) |  |
| [ArgbColor(int r, int g, int b)](#ArgbColor-int-int-int-) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [fromRgba(int red, int green, int blue, int alpha)](#fromRgba-int-int-int-int-) | ينشئ قيمة واحدة من نوع [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) من القنوات المحددة الأحمر، الأخضر، الأزرق، وألفا |
|
|  | [fromRgb(int red, int green, int blue)](#fromRgb-int-int-int-) | ينشئ قيمة واحدة من نوع [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) من القنوات المحددة الأحمر، الأخضر، الأزرق، بينما قناة ألفا تكون غير شفافة تمامًا |
|
|  | [fromSingleValueRgb(byte value)](#fromSingleValueRgb-byte-) | ينشئ لونًا غير شفاف تمامًا (A=255) من قيمة واحدة، تُطبق على جميع القنوات |
|
|  | [fromColor(Color color)](#fromColor-java.awt.Color-) | ينشئ قيمة واحدة من نوع [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) من [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) المحدد |
|
|  | [getValue()](#getValue--) | يحصل على قيمة Int32 للون. |
|
|  | [getA()](#getA--) | يحصل على الجزء ألفا من اللون. |
|
|  | [getAlpha()](#getAlpha--) | يحصل على الجزء ألفا من اللون كنسبة مئوية (0..1). |
|
|  | [getR()](#getR--) | يحصل على الجزء الأحمر من اللون. |
|
|  | [getG()](#getG--) | يحصل على الجزء الأخضر من اللون. |
|
|  | [getB()](#getB--) | يحصل على الجزء الأزرق من اللون. |
|
|  | [isEmpty()](#isEmpty--) | لون غير مبدئ - جميع القنوات الأربعة مضبوطة على 0. |
|
|  | [isDefault()](#isDefault--) | يشير إلى ما إذا كانت هذه الحالة من [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) هي الافتراضية (شفافة) - جميع القنوات الأربعة مضبوطة على 0 |
|
|  | [isFullyTransparent()](#isFullyTransparent--) | يشير إلى ما إذا كانت هذه الحالة من [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) شفافة تمامًا - قناة ألفا لديها القيمة الدنيا (0)، لذا لا تؤثر القنوات R و G و B بشكل مرئي. |
|
|  | [isTranslucent()](#isTranslucent--) | يشير إلى ما إذا كانت هذه الحالة من [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) نصف شفافة (ليست شفافة تمامًا، لكنها ليست غير شفافة تمامًا) |
|
|  | [isFullyOpaque()](#isFullyOpaque--) | يشير إلى ما إذا كانت هذه الحالة من [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) غير شفافة تمامًا، بدون شفافية (قناة ألفا لديها القيمة القصوى) |
|
|  | [toSystemColor()](#toSystemColor--) | يحوّل قيمة هذه الحالة من [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) إلى حالة [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) ويعيدها |
|
|  | [toRGBA()](#toRGBA--) | يقوم بتسلسل هذه الحالة من [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) إلى تدوين دالة CSS 'rgba' |
|
|  | [toRGB()](#toRGB--) | يقوم بتسلسل هذه الحالة من [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) إلى تدوين دالة CSS 'rgb' |
|
|  | [serializeDefault()](#serializeDefault--) | يقوم بتسلسل هذه الحالة من [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) إلى أنسب تدوين لدالة CSS حسب الشفافية |
|
|  | [toString()](#toString--) | نفس ما هو في #serializeDefault.serializeDefault |
|
|  | [op_Equality(ArgbColor left, ArgbColor right)](#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | يقارن لونين ويعيد قيمة منطقية تشير إلى ما إذا كان اللونان متطابقين. |
|
|  | [op_Inequality(ArgbColor left, ArgbColor right)](#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | يقارن لونين ويعيد قيمة منطقية تشير إلى ما إذا كان اللونان غير متطابقين. |
|
|  | [equals(ArgbColor other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-) | يفحص مساواة لونين من [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) |
|
|  | [equals(ICssDataType other)](#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-) | يفحص مساواة لونين من [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) |
|
|  | [equals(Object other)](#equals-java.lang.Object-) | يختبر ما إذا كان كائن آخر يساوي هذه الحالة من [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor). |
|
|  | [hashCode()](#hashCode--) | يعيد رمز تجزئة يحدد اللون الحالي. |
|
### ArgbColor() {#ArgbColor--}
```
public ArgbColor()
```


### ArgbColor(int r, int g, int b) {#ArgbColor-int-int-int-}
```
public ArgbColor(int r, int g, int b)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| r | int |  |
| g | int |  |
| b | int |  |

### fromRgba(int red, int green, int blue, int alpha) {#fromRgba-int-int-int-int-}
```
public static ArgbColor fromRgba(int red, int green, int blue, int alpha)
```


ينشئ قيمة واحدة من نوع [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) من القنوات المحددة الأحمر، الأخضر، الأزرق، وألفا


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | أحمر | int | قيمة قناة الأحمر |
|
|  | أخضر | int | قيمة قناة الأخضر |
|
|  | أزرق | int | قيمة قناة الأزرق |
|
|  | ألفا | int | قيمة قناة الألفا |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value

### fromRgb(int red, int green, int blue) {#fromRgb-int-int-int-}
```
public static ArgbColor fromRgb(int red, int green, int blue)
```


ينشئ قيمة واحدة من نوع [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) من القنوات المحددة الأحمر، الأخضر، الأزرق، بينما قناة ألفا تكون غير شفافة تمامًا


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | أحمر | int | قيمة قناة الأحمر |
|
|  | أخضر | int | قيمة قناة الأخضر |
|
|  | أزرق | int | قيمة قناة الأزرق |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) value

### fromSingleValueRgb(byte value) {#fromSingleValueRgb-byte-}
```
public static ArgbColor fromSingleValueRgb(byte value)
```


ينشئ لونًا غير شفاف تمامًا (A=255) من قيمة واحدة، تُطبق على جميع القنوات


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | قيمة | byte | قيمة بايت، نفسها لقنوات الأحمر والأخضر والأزرق |
|

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - New [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) instance

### fromColor(Color color) {#fromColor-java.awt.Color-}
```
public static ArgbColor fromColor(Color color)
```


ينشئ قيمة واحدة من نوع [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) من [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| لون | java.awt.Color |  |

**Returns:**
[ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) - 
### getValue() {#getValue--}
```
public final int getValue()
```


يحصل على قيمة Int32 للون.


**Returns:**
int
### getA() {#getA--}
```
public final int getA()
```


يحصل على الجزء ألفا من اللون.


**Returns:**
int
### getAlpha() {#getAlpha--}
```
public final double getAlpha()
```


يحصل على الجزء ألفا من اللون كنسبة مئوية (0..1).


**Returns:**
مزدوج
### getR() {#getR--}
```
public final int getR()
```


يحصل على الجزء الأحمر من اللون.


**Returns:**
int
### getG() {#getG--}
```
public final int getG()
```


يحصل على الجزء الأخضر من اللون.


**Returns:**
int
### getB() {#getB--}
```
public final int getB()
```


يحصل على الجزء الأزرق من اللون.


**Returns:**
int
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


لون غير مبدئ - جميع القنوات الأربعة مضبوطة على 0. نفس ما هو في Default و Transparent.


**Returns:**
boolean
### isDefault() {#isDefault--}
```
public final boolean isDefault()
```


يشير إلى ما إذا كانت هذه الحالة من [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) هي الافتراضية (شفافة) - جميع القنوات الأربعة مضبوطة على 0


**Returns:**
boolean
### isFullyTransparent() {#isFullyTransparent--}
```
public final boolean isFullyTransparent()
```


يشير إلى ما إذا كانت هذه الحالة من [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) شفافة تمامًا - قناة ألفا لديها القيمة الدنيا (0)، لذا لا تؤثر القنوات R و G و B بشكل مرئي.


**Returns:**
boolean
### isTranslucent() {#isTranslucent--}
```
public final boolean isTranslucent()
```


يشير إلى ما إذا كانت هذه الحالة من [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) نصف شفافة (ليست شفافة تمامًا، لكنها ليست غير شفافة تمامًا)


**Returns:**
boolean
### isFullyOpaque() {#isFullyOpaque--}
```
public final boolean isFullyOpaque()
```


يشير إلى ما إذا كانت هذه الحالة من [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) غير شفافة تمامًا، بدون شفافية (قناة ألفا لديها القيمة القصوى)


**Returns:**
boolean
### toSystemColor() {#toSystemColor--}
```
public final Color toSystemColor()
```


يحوّل قيمة هذه الحالة من [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) إلى حالة [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) ويعيدها


**Returns:**
[Color](../../java.awt/color) - New [Color](../../com.groupdocs.editor.htmlcss.css.specificdeclarations.font/color) instance

### toRGBA() {#toRGBA--}
```
public final String toRGBA()
```


يقوم بتسلسل هذه الحالة من [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) إلى تدوين دالة CSS 'rgba'


**Returns:**
java.lang.String - سلسلة بتنسيق 'rgba(r, g, b, a)'

### toRGB() {#toRGB--}
```
public final String toRGB()
```


يقوم بتسلسل هذه الحالة من [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) إلى تدوين دالة CSS 'rgb'


**Returns:**
java.lang.String - سلسلة بتنسيق 'rgb(r, g, b)'

### serializeDefault() {#serializeDefault--}
```
public final String serializeDefault()
```


يقوم بتسلسل هذه الحالة من [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) إلى أنسب تدوين لدالة CSS حسب الشفافية


**Returns:**
java.lang.String - سلسلة بتنسيق 'rgba(r, g, b, a)' أو 'rgb(r, g, b)'

### toString() {#toString--}
```
public String toString()
```


نفس ما هو في #serializeDefault.serializeDefault


**Returns:**
java.lang.String - نفس قيمة الإرجاع كما في #serializeDefault.serializeDefault

### op_Equality(ArgbColor left, ArgbColor right) {#op-Equality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public static boolean op_Equality(ArgbColor left, ArgbColor right)
```


يقارن لونين ويعيد قيمة منطقية تشير إلى ما إذا كان اللونان متطابقين.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | left | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | اللون الأول للاستخدام. |
|
|  | right | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | اللون الثاني للاستخدام. |
|

**Returns:**
boolean - صحيح إذا كان اللونان متساويين، وإلا خطأ.

### op_Inequality(ArgbColor left, ArgbColor right) {#op-Inequality-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public static boolean op_Inequality(ArgbColor left, ArgbColor right)
```


يقارن لونين ويعيد قيمة منطقية تشير إلى ما إذا كان اللونان غير متطابقين.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | left | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | اللون الأول للاستخدام. |
|
|  | right | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | اللون الثاني للاستخدام. |
|

**Returns:**
boolean - صحيح إذا كان اللونان غير متساويين، وإلا خطأ.

### equals(ArgbColor other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ArgbColor-}
```
public final boolean equals(ArgbColor other)
```


يفحص مساواة لونين من [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) | اللون الآخر [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) |
|

**Returns:**
boolean - صحيح إذا كان اللونان متساويين، وإلا خطأ.

### equals(ICssDataType other) {#equals-com.groupdocs.editor.htmlcss.css.datatypes.ICssDataType-}
```
public final boolean equals(ICssDataType other)
```


يفحص مساواة لونين من [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [ICssDataType](../../com.groupdocs.editor.htmlcss.css.datatypes/icssdatatype) | اللون الآخر [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor) ، محول إلى ICssDataType |
|

**Returns:**
boolean - صحيح إذا كان اللونان متساويين، وإلا خطأ.

### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


يختبر ما إذا كان كائن آخر يساوي هذه الحالة من [ArgbColor](../../com.groupdocs.editor.htmlcss.css.datatypes/argbcolor).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | آخر | java.lang.Object | الكائن للاختبار معه. |
|

**Returns:**
boolean - صحيح إذا كان الكائنان متساويين، وإلا خطأ.

### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد رمز تجزئة يحدد اللون الحالي.


**Returns:**
int - القيمة الصحيحة للـ hashcode.

