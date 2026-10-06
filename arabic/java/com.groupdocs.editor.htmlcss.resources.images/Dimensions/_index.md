---
title: "الأبعاد"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثل الأبعاد الخطية للعرض والارتفاع لصورة raster rectangular image مستطيلة بوحدة تعسفية."
type: docs
weight: 10
url: /ar/java/com.groupdocs.editor.htmlcss.resources.images/dimensions/
---
**Inheritance:**
java.lang.Object
```
public class Dimensions
```

يمثل الأبعاد الخطية (العرض والارتفاع) لمستطيل نقطي واحد
صورة بوحدة اختيارية. بنية غير قابلة للتغيير.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [Dimensions(int width, int height)](#Dimensions-int-int-) | ينشئ نسخة جديدة من العرض والارتفاع المحددين |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getWidth()](#getWidth--) | يعيد عرض الصورة |
|
|  | [getHeight()](#getHeight--) | يعيد ارتفاع الصورة |
|
|  | [isSquare()](#isSquare--) | يحدد ما إذا كان 'Dimensions' المحدد يمثل مربعًا، أي |
|
|  | [getArea()](#getArea--) | يعيد مساحة (العرض × الارتفاع) |
|
|  | [isEmpty()](#isEmpty--) | يحدد ما إذا كانت نسخة "Dimensions" هذه فارغة ومبدئية، أي |
|
|  | [getAspectRatio()](#getAspectRatio--) | نسبة العرض إلى الارتفاع لهذه الأبعاد كالعرض/الارتفاع |
|
|  | [proportionallyResizeForNewWidth(int targetWidth)](#proportionallyResizeForNewWidth-int-) | ينشئ ويعيد نسخة جديدة من "Dimensions"، والتي تكون بشكل نسبي |
مُعاد تحجيمها من الحالية بناءً على العرض المحدد
|
|  | [proportionallyResizeForNewHeight(int targetHeight)](#proportionallyResizeForNewHeight-int-) | ينشئ ويعيد نسخة جديدة من "Dimensions"، والتي تكون بشكل نسبي |
مُعاد تحجيمها من الحالية بناءً على الارتفاع المحدد
|
|  | [equals(Dimensions other)](#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | يحدد ما إذا كانت هذه النسخة مساوية لـ "Dimensions" المحددة |
مثيل
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كانت هذه الحالة مساوية للكائن غير المحول المحدد، |
والتي من المفترض أنها نسخة أخرى من "Dimensions"
|
|  | [hashCode()](#hashCode--) | يعيد قيمة hashcode لهذا الكائن، والتي لا يمكن تغييرها خلال |
مدة الحياة
|
|  | [op_Equality(Dimensions first, Dimensions second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | يتحقق مما إذا كانت قيمتي "Dimensions" متساويتين، أي |
|
|  | [op_Inequality(Dimensions first, Dimensions second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | يتحقق مما إذا كانت قيمتي "Dimensions" غير متساويتين، أي |
|
|  | [toString()](#toString--) | يعيد تمثيلًا نصيًا لهذه "Dimensions" |
|
|  | [deepClone()](#deepClone--) | يعيد نسخة كاملة من هذه النسخة |
|
|  | [getEmpty()](#getEmpty--) | يعيد نسخة فارغة من Dimensions |
|
### Dimensions(int width, int height) {#Dimensions-int-int-}
```
public Dimensions(int width, int height)
```


ينشئ نسخة جديدة من العرض والارتفاع المحددين


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | العرض | int | عرض الصورة |
|
|  | الارتفاع | int | ارتفاع الصورة |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


يعيد عرض الصورة


**Returns:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```


يعيد ارتفاع الصورة


**Returns:**
int
### isSquare() {#isSquare--}
```
public final boolean isSquare()
```


يحدد ما إذا كان 'Dimensions' المحدد يمثل مربعًا، إذا
العرض يساوي الارتفاع


**Returns:**
boolean
### getArea() {#getArea--}
```
public final long getArea()
```


يعيد مساحة (العرض × الارتفاع)


**Returns:**
long
### isEmpty() {#isEmpty--}
```
public final boolean isEmpty()
```


يحدد ما إذا كانت نسخة "Dimensions" هذه فارغة ومبدئية، أي
لا يخزن العرض والارتفاع الصحيحين


**Returns:**
boolean
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


نسبة العرض إلى الارتفاع لهذه الأبعاد كالعرض/الارتفاع


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### proportionallyResizeForNewWidth(int targetWidth) {#proportionallyResizeForNewWidth-int-}
```
public final Dimensions proportionallyResizeForNewWidth(int targetWidth)
```


ينشئ ويعيد نسخة جديدة من "Dimensions"، والتي تكون بشكل نسبي
مُعاد تحجيمها من الحالية بناءً على العرض المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | targetWidth | int | العرض الهدف الجديد، والذي سيكون موجودًا في البُعد الناتج |
|

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target width and proportionally resized height

### proportionallyResizeForNewHeight(int targetHeight) {#proportionallyResizeForNewHeight-int-}
```
public final Dimensions proportionallyResizeForNewHeight(int targetHeight)
```


ينشئ ويعيد نسخة جديدة من "Dimensions"، والتي تكون بشكل نسبي
مُعاد تحجيمها من الحالية بناءً على الارتفاع المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | targetHeight | int | الارتفاع الهدف الجديد، والذي سيكون موجودًا في البُعد الناتج |
|

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target height and proportionally resized width

### equals(Dimensions other) {#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public final boolean equals(Dimensions other)
```


يحدد ما إذا كانت هذه النسخة مساوية لـ "Dimensions" المحددة
مثيل


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | مثال آخر من "Dimensions" للتحقق من المساواة |
|

**Returns:**
منطقي - True إذا كانا متساويين، false إذا لم يكونا متساويين

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كانت هذه الحالة مساوية للكائن غير المحول المحدد،
والتي من المفترض أنها نسخة أخرى من "Dimensions"


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | obj | java.lang.Object | كائن آخر، من المفترض أنه من نوع "Dimensions"، يجب التحقق من مساواته مع هذا |
|

**Returns:**
منطقي - True إذا كانا متساويين، false إذا لم يكونا متساويين

### hashCode() {#hashCode--}
```
public int hashCode()
```


يعيد قيمة hashcode لهذا الكائن، والتي لا يمكن تغييرها خلال
مدة الحياة


**Returns:**
int - قيمة تجزئة ثابتة (لهذا المثال) كعدد صحيح موقع 4 بايت

### op_Equality(Dimensions first, Dimensions second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Equality(Dimensions first, Dimensions second)
```


يتحقق مما إذا كانت قيمتي "Dimensions" متساويتين، أي أن لديهما
العرض والارتفاع، أو كليهما فارغ


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | المثال الأول للتحقق |
|
|  | second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | المثال الثاني للتحقق |
|

**Returns:**
منطقي - True إذا كانا متساويين، false إذا لم يكونا متساويين

### op_Inequality(Dimensions first, Dimensions second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Inequality(Dimensions first, Dimensions second)
```


يتحقق مما إذا كانت قيمتي "Dimensions" غير متساويتين، أي أن
العرض و/أو الارتفاع المقابل مختلفان


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | المثال الأول للتحقق |
|
|  | second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | المثال الثاني للتحقق |
|

**Returns:**
منطقي - True إذا كانا غير متساويين، false إذا كانا متساويين

### toString() {#toString--}
```
public String toString()
```


يعيد تمثيلًا نصيًا لهذه "Dimensions"

*** ** * ** ***


> ```
> W640×H480
> ```

<br />



**Returns:**
java.lang.String - مثال سلسلة، يحتوي على عرض وارتفاع بصيغة W:(width)×H:(height)

### deepClone() {#deepClone--}
```
public final Dimensions deepClone()
```


يعيد نسخة كاملة من هذه النسخة


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New instance, that is a full and deep copy of this one

### getEmpty() {#getEmpty--}
```
public static Dimensions getEmpty()
```


يعيد نسخة فارغة من Dimensions


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
