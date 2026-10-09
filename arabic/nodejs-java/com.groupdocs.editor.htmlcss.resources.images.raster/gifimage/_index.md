---
title: "GifImage"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يمثل صورة واحدة في تنسيق GIF Graphics Interchange Format مع البيانات الوصفية والطرق الإضافية"
type: docs
weight: 11
url: /ar/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/gifimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class GifImage extends RasterImageResourceBase
```

يمثل صورة واحدة في تنسيق GIF (Graphics Interchange Format) مع
البيانات الوصفية والطرق الإضافية

## المنشئات

| المنشئ | الوصف |
| --- | --- |
|  | [GifImage(String name, String contentInBase64)](#GifImage-java.lang.String-java.lang.String-) | ينشئ نسخة جديدة من GifImage من المحتوى، ممثلةً بترميز base64 |
سلسلة، ومع اسم محدد
|
|  | [GifImage(String name, InputStream binaryContent)](#GifImage-java.lang.String-java.io.InputStream-) | ينشئ نسخة جديدة من GifImage من المحتوى، ممثلةً بتدفق بايت، |
ومع اسم محدد
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | يتحقق مما إذا كان التدفق المحدد صورة GIF صالحة |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | يتحقق مما إذا كانت السلسلة المشفرة بقاعدة 64 المحددة صورة GIF صالحة |
|
|  | [getType()](#getType--) | يرجع ImageType.Gif |
|
|  | [getVersion()](#getVersion--) | يرجع النسخة الداخلية لهذه الصورة GIF (يتم استخراج النسخة من |
الترويسة)
|
### GifImage(String name, String contentInBase64) {#GifImage-java.lang.String-java.lang.String-}
```
public GifImage(String name, String contentInBase64)
```


ينشئ نسخة جديدة من GifImage من المحتوى، ممثلةً بترميز base64
سلسلة، ومع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم صورة GIF. لا يمكن أن يكون فارغًا أو خاليًا أو يحتوي على مسافات فقط. |
|
|  | contentInBase64 | java.lang.String | المحتوى كسلسلة مشفرة بقاعدة 64. لا يمكن أن يكون فارغًا أو خاليًا أو يحتوي على مسافات فقط. إذا لم يكن محتوى GIF، سيتم رمي استثناء. |
|

### GifImage(String name, InputStream binaryContent) {#GifImage-java.lang.String-java.io.InputStream-}
```
public GifImage(String name, InputStream binaryContent)
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

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


يتحقق مما إذا كان التدفق المحدد صورة GIF صالحة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | تدفق بايت، والذي من المفترض أنه يحتوي على صورة GIF |
|

**Returns:**
boolean - صحيح إذا كان التدفق المحدد يحتوي على صورة GIF صالحة، وإلا خاطئ

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


يتحقق مما إذا كانت السلسلة المشفرة بقاعدة 64 المحددة صورة GIF صالحة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | محتوى صورة GIF المفترض على شكل سلسلة مشفرة بقاعدة 64 |
|

**Returns:**
boolean - صحيح إذا كانت السلسلة المحددة تحتوي على صورة GIF صالحة، وإلا خاطئ

### getType() {#getType--}
```
public ImageType getType()
```


يرجع ImageType.Gif


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getVersion() {#getVersion--}
```
public final String getVersion()
```


يرجع النسخة الداخلية لهذه الصورة GIF (يتم استخراج النسخة من
الترويسة)


**Returns:**
java.lang.String
