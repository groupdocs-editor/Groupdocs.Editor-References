---
title: "BmpImage"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثل صورة واحدة بصيغة BMP BitMap Picture مع بياناتها التعريفية والطرق الإضافية"
type: docs
weight: 10
url: /ar/java/com.groupdocs.editor.htmlcss.resources.images.raster/bmpimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class BmpImage extends RasterImageResourceBase
```

يمثل صورة واحدة بصيغة BMP (BitMap Picture) مع بياناتها التعريفية و
الطرق الإضافية

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [BmpImage(String name, String contentInBase64)](#BmpImage-java.lang.String-java.lang.String-) | ينشئ كائن BmpImage جديد من المحتوى، ممثلًا كسلسلة مشفرة بقاعدة 64 |
سلسلة، ومع اسم محدد
|
|  | [BmpImage(String name, InputStream binaryContent)](#BmpImage-java.lang.String-java.io.InputStream-) | ينشئ كائن BmpImage جديد من المحتوى، ممثلًا كتيار بايت، |
ومع اسم محدد
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | يتحقق مما إذا كان التيار المحدد صورة BMP صالحة |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | يتحقق مما إذا كان النص المشفر بـ base64 المحدد صورة BMP صالحة |
|
|  | [getType()](#getType--) | يرجع ImageType.Bmp |
|
### BmpImage(String name, String contentInBase64) {#BmpImage-java.lang.String-java.lang.String-}
```
public BmpImage(String name, String contentInBase64)
```


ينشئ كائن BmpImage جديد من المحتوى، ممثلًا كسلسلة مشفرة بقاعدة 64
سلسلة، ومع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم صورة BMP. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات بيضاء. |
|
|  | contentInBase64 | java.lang.String | المحتوى كنص مشفر بـ base64. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات بيضاء. إذا لم يكن محتوى BMP، سيتم رمي استثناء. |
|

### BmpImage(String name, InputStream binaryContent) {#BmpImage-java.lang.String-java.io.InputStream-}
```
public BmpImage(String name, InputStream binaryContent)
```


ينشئ كائن BmpImage جديد من المحتوى، ممثلًا كتيار بايت،
ومع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم صورة BMP. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات بيضاء. |
|
|  | binaryContent | java.io.InputStream | المحتوى كتيار بايت. يبدأ القراءة من الموضع الأصلي. لا يمكن أن يكون فارغًا. يجب أن يكون قابلًا للقراءة والتمرير. إذا تم تحرير هذه الحالة، سيتم تحرير هذا التيار أيضًا. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


يتحقق مما إذا كان التيار المحدد صورة BMP صالحة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | تيار بايت، من المفترض أنه يحتوي على صورة BMP |
|

**Returns:**
منطقي - صحيح إذا كان التيار المحدد يحتوي على صورة BMP صالحة، وإلا خطأ

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


يتحقق مما إذا كان النص المشفر بـ base64 المحدد صورة BMP صالحة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | محتوى صورة BMP المفترض على شكل نص مشفر بـ base64 |
|

**Returns:**
منطقي - صحيح إذا كان النص المحدد يحتوي على صورة BMP صالحة، وإلا خطأ

### getType() {#getType--}
```
public ImageType getType()
```


يرجع ImageType.Bmp


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
