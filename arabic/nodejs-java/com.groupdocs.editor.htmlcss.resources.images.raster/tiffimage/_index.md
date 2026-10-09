---
title: "TiffImage"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يمثل صورة واحدة في تنسيق TIFF Tagged Image File Format مع البيانات الوصفية والطرق الإضافية"
type: docs
weight: 16
url: /ar/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/tiffimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class TiffImage extends RasterImageResourceBase
```

يمثل صورة واحدة في تنسيق TIFF (Tagged Image File Format) مع
البيانات الوصفية والطرق الإضافية


*** ** * ** ***

انظر https://en.wikipedia.org/wiki/TIFF للحصول على التفاصيل. في حالات نادرة جدًا يكون TIFF موجودًا داخل مستندات WordProcessing.

<br />


## المنشئات

| المنشئ | الوصف |
| --- | --- |
|  | [TiffImage(String name, String contentInBase64)](#TiffImage-java.lang.String-java.lang.String-) | ينشئ كائن TiffImage جديد من المحتوى، ممثلًا كـ |
سلسلة مشفرة بقاعدة 64، ومع اسم محدد
|
|  | [TiffImage(String name, InputStream binaryContent)](#TiffImage-java.lang.String-java.io.InputStream-) | ينشئ نسخة جديدة من GifImage من المحتوى، ممثلةً بتدفق بايت، |
ومع اسم محدد
|
| [TiffImage(String name, System.IO.Stream binaryContent)](#TiffImage-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | يتحقق مما إذا كان التدفق المحدد صورة TIFF صالحة |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | يتحقق مما إذا كان النص المشفر بـ base64 المحدد صورة TIFF صالحة |
|
|  | [getType()](#getType--) | يرجع ImageType.Tiff |
|
|  | [getFramesCount()](#getFramesCount--) | يرجع عدد الإطارات (الصور) داخل صورة TIFF هذه. |
|
### TiffImage(String name, String contentInBase64) {#TiffImage-java.lang.String-java.lang.String-}
```
public TiffImage(String name, String contentInBase64)
```


ينشئ كائن TiffImage جديد من المحتوى، ممثلًا كـ
سلسلة مشفرة بقاعدة 64، ومع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم صورة TIFF. لا يمكن أن يكون null أو فارغًا أو يتكون من مسافات فقط. |
|
|  | contentInBase64 | java.lang.String | المحتوى كسلسلة مشفرة بـ base64. لا يمكن أن تكون null أو فارغة أو تتكون من مسافات فقط. إذا لم يكن محتوى TIFF، سيتم رمي استثناء. |
|

### TiffImage(String name, InputStream binaryContent) {#TiffImage-java.lang.String-java.io.InputStream-}
```
public TiffImage(String name, InputStream binaryContent)
```


ينشئ نسخة جديدة من GifImage من المحتوى، ممثلةً بتدفق بايت،
ومع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم صورة GIF. لا يمكن أن يكون فارغًا أو خاليًا أو يحتوي على مسافات فقط. |
|
|  | binaryContent | java.io.InputStream | المحتوى كتيار بايت. يبدأ القراءة من الموضع الأصلي. لا يمكن أن يكون null. يجب أن يكون قابلًا للقراءة والتمرير. إذا تم تحرير هذه الحالة، سيتم تحرير هذا التيار أيضًا. |
|

### TiffImage(String name, System.IO.Stream binaryContent) {#TiffImage-java.lang.String-com.aspose.ms.System.IO.Stream-}
```
public TiffImage(String name, System.IO.Stream binaryContent)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |
| binaryContent | com.aspose.ms.System.IO.Stream |  |

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


يتحقق مما إذا كان التدفق المحدد صورة TIFF صالحة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | تدفق بايت، من المفترض أنه يحتوي على صورة TIFF |
|

**Returns:**
منطقي - True إذا كان التدفق المحدد يحتوي على صورة TIFF صالحة، وإلا false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


يتحقق مما إذا كان النص المشفر بـ base64 المحدد صورة TIFF صالحة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | محتوى صورة TIFF المفترض على شكل سلسلة مشفرة بـ base64 |
|

**Returns:**
منطقي - True إذا كان النص المحدد يحتوي على صورة TIFF صالحة، وإلا false

### getType() {#getType--}
```
public ImageType getType()
```


يرجع ImageType.Tiff


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getFramesCount() {#getFramesCount--}
```
public final int getFramesCount()
```


يرجع عدد الإطارات (الصور) داخل صورة TIFF هذه. لا يمكن أن يكون
أقل من 1.


**Returns:**
int -
