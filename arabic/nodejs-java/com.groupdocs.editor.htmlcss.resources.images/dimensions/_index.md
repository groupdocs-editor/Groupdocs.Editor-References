---
title: "Dimensions"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يمثل الأبعاد الخطية للعرض والارتفاع لصورة نقطية مستطيلة واحدة بوحدة عشوائية."
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.editor.htmlcss.resources.images/dimensions/
---
**Inheritance:**
java.lang.Object
```
public class Dimensions
```

يمثل الأبعاد الخطية (العرض والارتفاع) لصورة نقطية مستطيلة واحدة
صورة بوحدة عشوائية. بنية غير قابلة للتغيير.

## المنشئات

| المنشئ | الوصف |
| --- | --- |
|  | [Dimensions(int width, int height)](#Dimensions-int-int-) | ينشئ مثيلًا جديدًا من العرض والارتفاع المحددين |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getWidth()](#getWidth--) | يعيد عرض الصورة |
|
|  | [getHeight()](#getHeight--) | يعيد ارتفاع الصورة |
|
|  | [isSquare()](#isSquare--) | يحدد ما إذا كانت 'Dimensions' المحددة تمثل مربعًا، أي |
|
|  | [getArea()](#getArea--) | يعيد مساحة (العرض × الارتفاع) |
|
|  | [isEmpty()](#isEmpty--) | يحدد ما إذا كان هذا المثيل "Dimensions" فارغًا ومبدئيًا، أي |
|
|  | [getAspectRatio()](#getAspectRatio--) | نسبة العرض إلى الارتفاع لهذه الأبعاد كالعرض/الارتفاع |
|
|  | [proportionallyResizeForNewWidth(int targetWidth)](#proportionallyResizeForNewWidth-int-) | ينشئ ويعيد مثيلًا جديدًا "Dimensions"، وهو بشكل نسبي |
معاد تحجيمه من الحالي، بناءً على العرض المحدد
|
|  | [proportionallyResizeForNewHeight(int targetHeight)](#proportionallyResizeForNewHeight-int-) | ينشئ ويعيد مثيلًا جديدًا "Dimensions"، وهو بشكل نسبي |
معاد تحجيمه من الحالي، بناءً على الارتفاع المحدد
|
|  | [equals(Dimensions other)](#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | يحدد ما إذا كان هذا المثيل مساويًا لـ "Dimensions" المحددة |
حالة
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كانت هذه الحالة مساوية للعنصر غير المحول المحدد، |
والذي من المفترض أنه مثيل آخر من "Dimensions"
|
|  | [hashCode()](#hashCode--) | إرجاع قيمة hashcode لهذه الحالة، والتي لا يمكن تغييرها خلال |
عمرها
|
|  | [op_Equality(Dimensions first, Dimensions second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | يفحص ما إذا كانت قيمتا "Dimensions" متساويتين، أي |
|
|  | [op_Inequality(Dimensions first, Dimensions second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-) | يتحقق مما إذا كانت قيمتي "Dimensions" غير متساويتين، أي. |
|
|  | [toString()](#toString--) | إرجاع تمثيل نصي لهذا "Dimensions" |
|
|  | [deepClone()](#deepClone--) | إرجاع نسخة كاملة من هذه الحالة |
|
|  | [getEmpty()](#getEmpty--) | إرجاع حالة Dimensions فارغة |
|
### Dimensions(int width, int height) {#Dimensions-int-int-}
```
public Dimensions(int width, int height)
```


ينشئ مثيلًا جديدًا من العرض والارتفاع المحددين


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


يحدد ما إذا كان 'Dimensions' المحدد يمثل مربعًا، أي إذا
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


يحدد ما إذا كان هذا المثيل "Dimensions" فارغًا ومبدئيًا، أي
لا يخزن العرض والارتفاع بشكل صحيح


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


ينشئ ويعيد مثيلًا جديدًا "Dimensions"، وهو بشكل نسبي
معاد تحجيمه من الحالي، بناءً على العرض المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | targetWidth | int | العرض الهدف الجديد، الذي سيكون موجودًا في البُعد الناتج |
|

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target width and proportionally resized height

### proportionallyResizeForNewHeight(int targetHeight) {#proportionallyResizeForNewHeight-int-}
```
public final Dimensions proportionallyResizeForNewHeight(int targetHeight)
```


ينشئ ويعيد مثيلًا جديدًا "Dimensions"، وهو بشكل نسبي
معاد تحجيمه من الحالي، بناءً على الارتفاع المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | targetHeight | int | الارتفاع الهدف الجديد، الذي سيكون موجودًا في البُعد الناتج |
|

**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New "Dimensions" instance with specified target height and proportionally resized width

### equals(Dimensions other) {#equals-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public final boolean equals(Dimensions other)
```


يحدد ما إذا كان هذا المثيل مساويًا لـ "Dimensions" المحددة
حالة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | مثال آخر لـ "Dimensions" للتحقق من المساواة |
|

**Returns:**
منطقي - True إذا كانت متساوية، false إذا لم تكن متساوية

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كانت هذه الحالة مساوية للعنصر غير المحول المحدد،
والذي من المفترض أنه مثيل آخر من "Dimensions"


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | obj | java.lang.Object | كائن آخر، من المفترض أنه من نوع "Dimensions"، يجب التحقق من مساواته مع هذا |
|

**Returns:**
منطقي - True إذا كانت متساوية، false إذا لم تكن متساوية

### hashCode() {#hashCode--}
```
public int hashCode()
```


إرجاع قيمة hashcode لهذه الحالة، والتي لا يمكن تغييرها خلال
عمرها


**Returns:**
int - قيمة تجزئة ثابتة (لهذه الحالة) كعدد صحيح موقّع من 4 بايت

### op_Equality(Dimensions first, Dimensions second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.Dimensions-com.groupdocs.editor.htmlcss.resources.images.Dimensions-}
```
public static boolean op_Equality(Dimensions first, Dimensions second)
```


يتحقق مما إذا كانت قيمتي "Dimensions" متساويتين، أي أن لديها
العرض والارتفاع، أو كلاهما فارغ


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | المثال الأول للتحقق |
|
|  | second | [Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) | المثال الثاني للتحقق |
|

**Returns:**
منطقي - True إذا كانت متساوية، false إذا لم تكن متساوية

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
boolean - True إذا كانت غير متساوية، false إذا كانت متساوية

### toString() {#toString--}
```
public String toString()
```


إرجاع تمثيل نصي لهذا "Dimensions"

*** ** * ** ***


> ```
> W640×H480
> ```

<br />



**Returns:**
java.lang.String - كائن سلسلة يحتوي على عرض وارتفاع بصيغة W:(width)×H:(height) format

### deepClone() {#deepClone--}
```
public final Dimensions deepClone()
```


إرجاع نسخة كاملة من هذه الحالة


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - New instance, that is a full and deep copy of this one

### getEmpty() {#getEmpty--}
```
public static Dimensions getEmpty()
```


إرجاع حالة Dimensions فارغة


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
