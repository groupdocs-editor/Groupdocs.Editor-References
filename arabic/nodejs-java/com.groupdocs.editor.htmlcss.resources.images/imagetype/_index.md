---
title: "ImageType"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يمثل تنسيق نوع صورة واحد مدعوم يدعم كل من الصيغ النقطية والمتجهة"
type: docs
weight: 11
url: /ar/nodejs-java/com.groupdocs.editor.htmlcss.resources.images/imagetype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IResourceType](../../com.groupdocs.editor.htmlcss.resources/iresourcetype)
```
public class ImageType implements IResourceType
```

يمثل نوع صورة (تنسيق) قابل للدعم، يدعم كلًا من التنسيقات النقطية والمتجهة.

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ImageType()](#ImageType--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getUndefined()](#getUndefined--) | نوع صورة غير معرف - قيمة خاصة، لا ينبغي أن تحدث عادةً |
|
|  | [getJpeg()](#getJpeg--) | نوع صورة JPEG |
|
|  | [getPng()](#getPng--) | نوع صورة PNG |
|
|  | [getBmp()](#getBmp--) | نوع صورة BMP |
|
|  | [getGif()](#getGif--) | نوع صورة GIF |
|
|  | [getIcon()](#getIcon--) | نوع صورة ICON |
|
|  | [getSvg()](#getSvg--) | نوع صورة متجهة SVG |
|
|  | [getWmf()](#getWmf--) | نوع صورة متجهة WMF (Windows MetaFile) |
|
|  | [getEmf()](#getEmf--) | نوع صورة متجهة EMF (Enhanced MetaFile) |
|
|  | [getTiff()](#getTiff--) | نوع صورة نقطية TIFF (Tagged Image File Format) |
|
|  | [getFormalName()](#getFormalName--) | يرجع اسمًا رسميًا لهذا التنسيق |
|
|  | [isVector()](#isVector--) | يشير إلى ما إذا كان هذا التنسيق المحدد متجهًا (true) أو نقطيًا |
(false)
|
|  | [getFileExtension()](#getFileExtension--) | امتداد الملف (بدون نقطة البداية) لنوع صورة معين |
بحروف صغيرة.
|
|  | [toString()](#toString--) | يرجع خاصية FormalName |
|
|  | [getMimeCode()](#getMimeCode--) | رمز MIME لنوع صورة معين كسلسلة. |
|
|  | [equals(ImageType other)](#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | يحدد ما إذا كانت هذه الحالة مساوية لـ \"ImageType\" المحدد |
حالة
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كانت هذه الحالة مساوية للعنصر غير المحول المحدد، |
والتي من المفترض أنها حالة \"ImageType\" أخرى
|
|  | [op_Equality(ImageType first, ImageType second)](#op-Equality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | يحدد ما إذا كانت حالتا ImageType محددتان متساويتان |
|
|  | [op_Inequality(ImageType first, ImageType second)](#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-) | يحدد ما إذا كانت حالتا ImageType محددتان غير متساويتين |
|
|  | [hashCode()](#hashCode--) | يرجع رمز تجزئة (hash-code)، وهو رقم ثابت لهذا العنصر المحدد |
حالة
|
|  | [parseFromFilenameWithExtension(String filename)](#parseFromFilenameWithExtension-java.lang.String-) | يرجع قيمة ImageType، والتي تعادل امتداد اسم الملف، والتي |
يتم استخراجها من اسم الملف المحدد
|
|  | [parseFromMime(String mimeCode)](#parseFromMime-java.lang.String-) | يرجع قيمة ImageType، والتي تعادل رمز MIME المحدد |
|
### ImageType() {#ImageType--}
```
public ImageType()
```


### getUndefined() {#getUndefined--}
```
public static ImageType getUndefined()
```


نوع صورة غير معرف - قيمة خاصة، لا ينبغي أن تحدث عادةً


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getJpeg() {#getJpeg--}
```
public static ImageType getJpeg()
```


نوع صورة JPEG


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getPng() {#getPng--}
```
public static ImageType getPng()
```


نوع صورة PNG


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getBmp() {#getBmp--}
```
public static ImageType getBmp()
```


نوع صورة BMP


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getGif() {#getGif--}
```
public static ImageType getGif()
```


نوع صورة GIF


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getIcon() {#getIcon--}
```
public static ImageType getIcon()
```


نوع صورة ICON


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getSvg() {#getSvg--}
```
public static ImageType getSvg()
```


نوع صورة متجهة SVG


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getWmf() {#getWmf--}
```
public static ImageType getWmf()
```


نوع صورة متجهة WMF (Windows MetaFile)


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getEmf() {#getEmf--}
```
public static ImageType getEmf()
```


نوع صورة متجهة EMF (Enhanced MetaFile)


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getTiff() {#getTiff--}
```
public static ImageType getTiff()
```


نوع صورة نقطية TIFF (Tagged Image File Format)


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getFormalName() {#getFormalName--}
```
public final String getFormalName()
```


يرجع اسمًا رسميًا لهذا التنسيق الصورة. لا يعيد أبدًا NULL. إذا
كانت الحالة غير تالفة، لا يرمي استثناءً أبدًا.


**Returns:**
java.lang.String
### isVector() {#isVector--}
```
public final boolean isVector()
```


يشير إلى ما إذا كان هذا التنسيق المحدد متجهًا (true) أو نقطيًا
(false)


**Returns:**
boolean
### getFileExtension() {#getFileExtension--}
```
public final String getFileExtension()
```


امتداد الملف (بدون نقطة البداية) لنوع صورة معين
بحروف صغيرة. بالنسبة للنوع Undefined يعيد سلسلة 'unsefined'.


**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


يرجع خاصية FormalName


**Returns:**
java.lang.String -
### getMimeCode() {#getMimeCode--}
```
public final String getMimeCode()
```


رمز MIME لنوع صورة معين كسلسلة. بالنسبة للنوع Undefined
يعيد سلسلة 'unsefined'.


**Returns:**
java.lang.String
### equals(ImageType other) {#equals-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public final boolean equals(ImageType other)
```


يحدد ما إذا كانت هذه الحالة مساوية لـ \"ImageType\" المحدد
حالة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | حالة ImageType أخرى للتحقق من المساواة مع هذه |
|

**Returns:**
منطقي - True إذا كانا متساويين، false إذا كانا غير متساويين

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كانت هذه الحالة مساوية للعنصر غير المحول المحدد،
والتي من المفترض أنها حالة \"ImageType\" أخرى


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | obj | java.lang.Object | مثيل آخر من System.Object، من المفترض أنه من نوع ImageType، للتحقق من المساواة مع هذا |
|

**Returns:**
منطقي - True إذا كانا متساويين، false إذا كانا غير متساويين

### op_Equality(ImageType first, ImageType second) {#op-Equality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Equality(ImageType first, ImageType second)
```


يحدد ما إذا كانت حالتا ImageType محددتان متساويتان


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | المثيل الأول من ImageType للتحقق |
|
|  | second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | المثيل الثاني من ImageType للتحقق |
|

**Returns:**
منطقي - True إذا كانا متساويين، false إذا كانا غير متساويين

### op_Inequality(ImageType first, ImageType second) {#op-Inequality-com.groupdocs.editor.htmlcss.resources.images.ImageType-com.groupdocs.editor.htmlcss.resources.images.ImageType-}
```
public static boolean op_Inequality(ImageType first, ImageType second)
```


يحدد ما إذا كانت حالتا ImageType محددتان غير متساويتين


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | first | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | المثيل الأول من ImageType للتحقق |
|
|  | second | [ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) | المثيل الثاني من ImageType للتحقق |
|

**Returns:**
boolean - True إذا كانت غير متساوية، false إذا كانت متساوية

### hashCode() {#hashCode--}
```
public int hashCode()
```


يرجع رمز تجزئة (hash-code)، وهو رقم ثابت لهذا العنصر المحدد
حالة


**Returns:**
int - عدد صحيح موقّع بحجم 4 بايت

### parseFromFilenameWithExtension(String filename) {#parseFromFilenameWithExtension-java.lang.String-}
```
public static ImageType parseFromFilenameWithExtension(String filename)
```


يرجع قيمة ImageType، والتي تعادل امتداد اسم الملف، والتي
يتم استخراجها من اسم الملف المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | اسم الملف | java.lang.String | اسم ملف عشوائي، يمكن أن يكون مسارًا نسبيًا أو كاملًا |
|

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - ImageType value. Returns ImageType.Undefined, if extension cannot be recognized.

### parseFromMime(String mimeCode) {#parseFromMime-java.lang.String-}
```
public static ImageType parseFromMime(String mimeCode)
```


يرجع قيمة ImageType، والتي تعادل رمز MIME المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | mimeCode | java.lang.String | رمز MIME عشوائي |
|

**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - ImageType value. Returns ImageType.Undefined, if extension cannot be recognized.

