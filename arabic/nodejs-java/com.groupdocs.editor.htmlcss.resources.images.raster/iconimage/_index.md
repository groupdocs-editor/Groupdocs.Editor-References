---
title: "IconImage"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يمثل صورة واحدة بتنسيق ICON مع بياناته الوصفية والطرق الإضافية"
type: docs
weight: 12
url: /ar/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.raster/iconimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.raster.RasterImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase)
```
public final class IconImage extends RasterImageResourceBase
```

يمثل صورة واحدة بتنسيق ICON مع بياناته الوصفية والطرق الإضافية

## المنشئات

| المنشئ | الوصف |
| --- | --- |
|  | [IconImage(String name, String contentInBase64)](#IconImage-java.lang.String-java.lang.String-) | ينشئ مثيلًا جديدًا من IconImage من المحتوى، ممثلًا كـ |
سلسلة مشفرة بقاعدة 64، ومع اسم محدد
|
|  | [IconImage(String name, InputStream binaryContent)](#IconImage-java.lang.String-java.io.InputStream-) | ينشئ مثيلًا جديدًا من IconImage من المحتوى، ممثلًا كتيار بايت، |
ومع اسم محدد
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | يتحقق مما إذا كان التيار المحدد صورة ICON صالحة |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | يتحقق مما إذا كانت السلسلة المشفرة بقاعدة 64 المحددة صورة ICON صالحة |
|
|  | [getType()](#getType--) | يرجع ImageType.Icon |
|
|  | [getNumberOfImages()](#getNumberOfImages--) | يرجع عدد الصور الموجودة في ملف ICON هذا |
|
### IconImage(String name, String contentInBase64) {#IconImage-java.lang.String-java.lang.String-}
```
public IconImage(String name, String contentInBase64)
```


ينشئ مثيلًا جديدًا من IconImage من المحتوى، ممثلًا كـ
سلسلة مشفرة بقاعدة 64، ومع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم صورة ICON. لا يمكن أن يكون فارغًا أو null أو يحتوي على مسافات بيضاء. |
|
|  | contentInBase64 | java.lang.String | المحتوى كسلسلة مشفرة بقاعدة 64. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات بيضاء. إذا لم يكن محتوى ICON، سيتم رمي استثناء. |
|

### IconImage(String name, InputStream binaryContent) {#IconImage-java.lang.String-java.io.InputStream-}
```
public IconImage(String name, InputStream binaryContent)
```


ينشئ مثيلًا جديدًا من IconImage من المحتوى، ممثلًا كتيار بايت،
ومع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم صورة ICON. لا يمكن أن يكون فارغًا أو null أو يحتوي على مسافات بيضاء. |
|
|  | binaryContent | java.io.InputStream | المحتوى كتيار بايت. يبدأ القراءة من الموضع الأصلي. لا يمكن أن يكون null. يجب أن يكون قابلًا للقراءة والتمرير. إذا تم تحرير هذه الحالة، سيتم تحرير هذا التيار أيضًا. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


يتحقق مما إذا كان التيار المحدد صورة ICON صالحة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | تدفق بايت، والذي من المفترض أنه يحتوي على صورة ICON |
|

**Returns:**
boolean - صحيح إذا كان التدفق المحدد يحتوي على صورة ICON صالحة، وإلا خاطئ

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


يتحقق مما إذا كانت السلسلة المشفرة بقاعدة 64 المحددة صورة ICON صالحة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | محتوى صورة ICON المفترض على شكل سلسلة مشفرة بقاعدة 64 |
|

**Returns:**
boolean - صحيح إذا كانت السلسلة المحددة تحتوي على صورة ICON صالحة، وإلا خاطئ

### getType() {#getType--}
```
public ImageType getType()
```


يرجع ImageType.Icon


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getNumberOfImages() {#getNumberOfImages--}
```
public final int getNumberOfImages()
```


يرجع عدد الصور الموجودة في ملف ICON هذا


**Returns:**
int
