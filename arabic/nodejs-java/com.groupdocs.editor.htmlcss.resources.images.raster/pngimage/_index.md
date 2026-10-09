---
title: "PngImage"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يمثل صورة واحدة بتنسيق PNG Portable Network Graphics مع بياناتها الوصفية والطرق الإضافية"
type: docs
weight: 14
url: /ar/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/pngimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class PngImage extends RasterImageResourceBase
```

يمثل صورة واحدة بتنسيق PNG (Portable Network Graphics) مع
البيانات الوصفية والطرق الإضافية

## المنشئات

| المنشئ | الوصف |
| --- | --- |
|  | [PngImage(String name, String contentInBase64)](#PngImage-java.lang.String-java.lang.String-) | ينشئ كائن PngImage جديد من المحتوى، ممثلًا كـ base64-encoded |
سلسلة، ومع اسم محدد
|
|  | [PngImage(String name, InputStream binaryContent)](#PngImage-java.lang.String-java.io.InputStream-) | ينشئ كائن PngImage جديد من المحتوى، ممثلًا كـ تدفق بايت، |
ومع اسم محدد
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | يتحقق مما إذا كان التدفق المحدد صورة PNG صالحة |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | يتحقق مما إذا كان النص المشفر بـ base64 المحدد صورة PNG صالحة |
|
|  | [getType()](#getType--) | يرجع ImageType.Png |
|
### PngImage(String name, String contentInBase64) {#PngImage-java.lang.String-java.lang.String-}
```
public PngImage(String name, String contentInBase64)
```


ينشئ كائن PngImage جديد من المحتوى، ممثلًا كـ base64-encoded
سلسلة، ومع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم صورة PNG. لا يمكن أن يكون null أو فارغًا أو يتكون من مسافات فقط. |
|
|  | contentInBase64 | java.lang.String | المحتوى كسلسلة مشفرة بـ base64. لا يمكن أن تكون null أو فارغة أو تتكون من مسافات فقط. إذا لم يكن محتوى PNG، سيتم رمي استثناء. |
|

### PngImage(String name, InputStream binaryContent) {#PngImage-java.lang.String-java.io.InputStream-}
```
public PngImage(String name, InputStream binaryContent)
```


ينشئ كائن PngImage جديد من المحتوى، ممثلًا كـ تدفق بايت،
ومع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم صورة PNG. لا يمكن أن يكون null أو فارغًا أو يتكون من مسافات فقط. |
|
|  | binaryContent | java.io.InputStream | المحتوى كتيار بايت. يبدأ القراءة من الموضع الأصلي. لا يمكن أن يكون null. يجب أن يكون قابلًا للقراءة والتمرير. إذا تم تحرير هذه الحالة، سيتم تحرير هذا التيار أيضًا. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


يتحقق مما إذا كان التدفق المحدد صورة PNG صالحة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | تدفق بايت، من المفترض أنه يحتوي على صورة PNG |
|

**Returns:**
منطقي - صحيح إذا كان التدفق المحدد يحتوي على صورة PNG صالحة، خطأ وإلا

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


يتحقق مما إذا كان النص المشفر بـ base64 المحدد صورة PNG صالحة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | محتوى صورة PNG المفترض على شكل سلسلة مشفرة بقاعدة 64 |
|

**Returns:**
منطقي - صحيح إذا كانت السلسلة المحددة تحتوي على صورة PNG صالحة، خطأ وإلا

### getType() {#getType--}
```
public ImageType getType()
```


يرجع ImageType.Png


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
