---
title: "PngImage"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثل صورة واحدة بصيغة PNG Portable Network Graphics مع بياناتها التعريفية والطرق الإضافية"
type: docs
weight: 14
url: /ar/java/com.groupdocs.editor.htmlcss.resources.images.raster/pngimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class PngImage extends RasterImageResourceBase
```

يمثل صورة واحدة بصيغة PNG (Portable Network Graphics) مع
البيانات الوصفية والطرق الإضافية

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [PngImage(String name, String contentInBase64)](#PngImage-java.lang.String-java.lang.String-) | ينشئ كائن PngImage جديد من المحتوى، ممثلًا كسلسلة مشفرة بقاعدة 64 |
سلسلة، ومع اسم محدد
|
|  | [PngImage(String name, InputStream binaryContent)](#PngImage-java.lang.String-java.io.InputStream-) | ينشئ كائن PngImage جديد من المحتوى، ممثلًا كتدفق بايت، |
ومع اسم محدد
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | يتحقق مما إذا كان التدفق المحدد صورة PNG صالحة |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | يتحقق مما إذا كانت السلسلة المشفرة بقاعدة 64 المحددة صورة PNG صالحة |
|
|  | [getType()](#getType--) | يرجع ImageType.Png |
|
### PngImage(String name, String contentInBase64) {#PngImage-java.lang.String-java.lang.String-}
```
public PngImage(String name, String contentInBase64)
```


ينشئ كائن PngImage جديد من المحتوى، ممثلًا كسلسلة مشفرة بقاعدة 64
سلسلة، ومع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم صورة PNG. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات بيضاء. |
|
|  | contentInBase64 | java.lang.String | المحتوى كسلسلة مشفرة بقاعدة 64. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات بيضاء. إذا لم يكن محتوى PNG، سيتم رمي استثناء. |
|

### PngImage(String name, InputStream binaryContent) {#PngImage-java.lang.String-java.io.InputStream-}
```
public PngImage(String name, InputStream binaryContent)
```


ينشئ كائن PngImage جديد من المحتوى، ممثلًا كتدفق بايت،
ومع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم صورة PNG. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات بيضاء. |
|
|  | binaryContent | java.io.InputStream | المحتوى كتيار بايت. يبدأ القراءة من الموضع الأصلي. لا يمكن أن يكون فارغًا. يجب أن يكون قابلًا للقراءة والتمرير. إذا تم تحرير هذه الحالة، سيتم تحرير هذا التيار أيضًا. |
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
boolean - True إذا كان التدفق المحدد يحتوي على صورة PNG صالحة، false خلاف ذلك

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


يتحقق مما إذا كانت السلسلة المشفرة بقاعدة 64 المحددة صورة PNG صالحة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | محتوى صورة PNG المفترض على شكل سلسلة مشفرة بقاعدة 64 |
|

**Returns:**
boolean - True إذا كانت السلسلة المحددة تحتوي على صورة PNG صالحة، false خلاف ذلك

### getType() {#getType--}
```
public ImageType getType()
```


يرجع ImageType.Png


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
