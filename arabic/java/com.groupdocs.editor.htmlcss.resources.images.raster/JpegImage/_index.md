---
title: "JpegImage"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثل صورة واحدة بصيغة JPEG Joint Photographic Experts Group مع بياناتها الوصفية والطرق الإضافية"
type: docs
weight: 13
url: /ar/java/com.groupdocs.editor.htmlcss.resources.images.raster/jpegimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class JpegImage extends RasterImageResourceBase
```

يمثل صورة واحدة بصيغة JPEG (Joint Photographic Experts Group) مع
بياناته الوصفية والطرق الإضافية

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [JpegImage(String name, String contentInBase64)](#JpegImage-java.lang.String-java.lang.String-) | ينشئ كائن JpegImage جديد من المحتوى، ممثلًا كـ |
سلسلة مشفرة بقاعدة 64، ومع اسم محدد
|
|  | [JpegImage(String name, InputStream binaryContent)](#JpegImage-java.lang.String-java.io.InputStream-) | ينشئ كائن JpegImage جديد من المحتوى، ممثلًا كـ تدفق بايت، |
ومع اسم محدد
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | يتحقق مما إذا كان التدفق المحدد صورة JPEG صالحة |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | يتحقق مما إذا كان النص المشفر بـ base64 المحدد صورة JPEG صالحة |
|
|  | [getType()](#getType--) | يرجع ImageType.Jpeg |
|
### JpegImage(String name, String contentInBase64) {#JpegImage-java.lang.String-java.lang.String-}
```
public JpegImage(String name, String contentInBase64)
```


ينشئ كائن JpegImage جديد من المحتوى، ممثلًا كـ
سلسلة مشفرة بقاعدة 64، ومع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم صورة JPEG. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات بيضاء. |
|
|  | contentInBase64 | java.lang.String | المحتوى كسلسلة مشفرة base64. لا يمكن أن يكون NULL أو فارغًا أو يحتوي على مسافات بيضاء. إذا لم يكن محتوى JPEG، سيتم رمي استثناء. |
|

### JpegImage(String name, InputStream binaryContent) {#JpegImage-java.lang.String-java.io.InputStream-}
```
public JpegImage(String name, InputStream binaryContent)
```


ينشئ كائن JpegImage جديد من المحتوى، ممثلًا كـ تدفق بايت،
ومع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم صورة JPEG. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات بيضاء. |
|
|  | binaryContent | java.io.InputStream | المحتوى كتيار بايت. يبدأ القراءة من الموضع الأصلي. لا يمكن أن يكون فارغًا. يجب أن يكون قابلًا للقراءة والتمرير. إذا تم تحرير هذه الحالة، سيتم تحرير هذا التيار أيضًا. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


يتحقق مما إذا كان التدفق المحدد صورة JPEG صالحة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | تدفق بايت، من المفترض أنه يحتوي على صورة JPEG |
|

**Returns:**
boolean - True إذا كان التدفق المحدد يحتوي على صورة JPEG صالحة، false otherwise

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


يتحقق مما إذا كان النص المشفر بـ base64 المحدد صورة JPEG صالحة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | محتوى صورة JPEG المفترض في شكل سلسلة مشفرة base64 |
|

**Returns:**
boolean - True إذا كانت السلسلة المحددة تحتوي على صورة JPEG صالحة، false otherwise

### getType() {#getType--}
```
public ImageType getType()
```


يرجع ImageType.Jpeg


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
