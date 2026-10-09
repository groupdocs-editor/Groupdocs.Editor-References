---
title: "EmfImage"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يمثل صورة متجهة واحدة بتنسيق Enhanced metafile (EMF) مع بياناته الوصفية والطرق الإضافية"
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/emfimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase), [com.groupdocs.editor.htmlcss.resources.images.vector.MetaImageBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase)
```
public final class EmfImage extends MetaImageBase
```

يمثل صورة متجهة واحدة بتنسيق Enhanced metafile (EMF) مع
البيانات الوصفية والطرق الإضافية

## المنشئات

| المنشئ | الوصف |
| --- | --- |
|  | [EmfImage(String name, String contentInBase64)](#EmfImage-java.lang.String-java.lang.String-) | ينشئ كائن EmfImage جديد من المحتوى، الممثل كقيمة مشفرة بقاعدة 64 |
سلسلة، ومع اسم محدد
|
|  | [EmfImage(String name, InputStream binaryContent)](#EmfImage-java.lang.String-java.io.InputStream-) | ينشئ كائن EmfImage جديد من المحتوى، الممثل كتيار بايت، |
ومع اسم محدد
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | يتحقق مما إذا كان التيار المحدد صورة EMF صالحة |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | يتحقق مما إذا كان النص المشفر بقاعدة 64 المحدد صورة EMF صالحة |
|
|  | [getType()](#getType--) | يرجع ImageType.Emf |
|
|  | [getByteContent()](#getByteContent--) | يرجع محتوى صورة EMF هذه كتيار ثنائي |
|
|  | [getTextContent()](#getTextContent--) | يرجع محتوى صورة EMF هذه كنص عادي |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | يحفظ صورة EMF هذه إلى الملف |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | يحفظ صورة EMF المتجهة هذه كصورة PNG نقطية |
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | يحفظ صورة EMF المتجهة هذه كصورة SVG متجهة |
|
|  | [dispose()](#dispose--) | يقوم بتحرير صورة EMF هذه عن طريق تحرير محتواها وجعل معظمها |
الطرق والخصائص غير عاملة
|
### EmfImage(String name, String contentInBase64) {#EmfImage-java.lang.String-java.lang.String-}
```
public EmfImage(String name, String contentInBase64)
```


ينشئ كائن EmfImage جديد من المحتوى، الممثل كقيمة مشفرة بقاعدة 64
سلسلة، ومع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم صورة EMF. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات فقط. |
|
|  | contentInBase64 | java.lang.String | المحتوى كسلسلة مشفرة بقاعدة 64. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات فقط. إذا لم يكن محتوى EMF، سيتم رمي استثناء. |
|

### EmfImage(String name, InputStream binaryContent) {#EmfImage-java.lang.String-java.io.InputStream-}
```
public EmfImage(String name, InputStream binaryContent)
```


ينشئ كائن EmfImage جديد من المحتوى، الممثل كتيار بايت،
ومع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم صورة EMF. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات فقط. |
|
|  | binaryContent | java.io.InputStream | المحتوى كتيار بايت. يبدأ القراءة من الموضع الأصلي. لا يمكن أن يكون null. يجب أن يكون قابلًا للقراءة والتمرير. إذا تم تحرير هذه الحالة، سيتم تحرير هذا التيار أيضًا. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


يتحقق مما إذا كان التيار المحدد صورة EMF صالحة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | دفق بايت إدخال. لا يمكن أن يكون NULL، ويجب أن يدعم القراءة والتمرير. |
|

**Returns:**
منطقي - True إذا كان التيار المحدد يحتوي على صورة EMF صالحة، وإلا false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


يتحقق مما إذا كان النص المشفر بقاعدة 64 المحدد صورة EMF صالحة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | سلسلة الإدخال، حيث يُخزن محتوى صورة EMF بترميز base64. لا يمكن أن تكون NULL أو فارغة. |
|

**Returns:**
منطقي - True إذا كانت السلسلة المحددة تحتوي على صورة EMF صالحة، وإلا false

### getType() {#getType--}
```
public ImageType getType()
```


يرجع ImageType.Emf


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


يرجع محتوى صورة EMF هذه كتيار ثنائي


**Returns:**
java.io.InputStream
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


يرجع محتوى صورة EMF هذه كنص عادي


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


يحفظ صورة EMF هذه إلى الملف


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | المسار الكامل للملف، الذي سيتم إنشاؤه (إذا لم يكن موجودًا) أو استبداله (إذا كان موجودًا) بمحتوى صورة EMF هذه |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


يحفظ صورة EMF المتجهة هذه كصورة PNG نقطية


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | دفق إخراج، يُكتب فيه محتوى صورة PNG. لا يمكن أن يكون NULL ويجب أن يكون قابلًا للكتابة. |
|

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public void saveToSvg(OutputStream outputSvgContent)
```


يحفظ صورة EMF المتجهة هذه كصورة SVG متجهة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | دفق إخراج، يُكتب فيه محتوى صورة SVG. لا يمكن أن يكون NULL ويجب أن يكون قابلًا للكتابة. |
|

### dispose() {#dispose--}
```
public void dispose()
```


يقوم بتحرير صورة EMF هذه عن طريق تحرير محتواها وجعل معظمها
الطرق والخصائص غير عاملة


