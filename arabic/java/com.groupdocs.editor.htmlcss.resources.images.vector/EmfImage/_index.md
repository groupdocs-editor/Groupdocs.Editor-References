---
title: "EmfImage"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثّل صورة متجهة واحدة بتنسيق ملف ميتا المحسّن EMF مع بياناتها الوصفية والطرق الإضافية"
type: docs
weight: 10
url: /ar/java/com.groupdocs.editor.htmlcss.resources.images.vector/emfimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase), [com.groupdocs.editor.htmlcss.resources.images.vector.MetaImageBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase)
```
public final class EmfImage extends MetaImageBase
```

يمثّل صورة متجهة واحدة بتنسيق ملف ميتا المحسّن (EMF) مع
البيانات الوصفية والطرق الإضافية

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [EmfImage(String name, String contentInBase64)](#EmfImage-java.lang.String-java.lang.String-) | ينشئ كائن EmfImage جديد من المحتوى، مُمثَّلً بترميز base64 |
سلسلة، ومع اسم محدد
|
|  | [EmfImage(String name, InputStream binaryContent)](#EmfImage-java.lang.String-java.io.InputStream-) | ينشئ كائن EmfImage جديد من المحتوى، مُمثَّلً بتدفق بايت، |
ومع اسم محدد
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | يتحقق مما إذا كان التدفق المحدد صورة EMF صالحة |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | يتحقق مما إذا كانت السلسلة المشفّرة بقاعدة 64 المحددة صورة EMF صالحة |
|
|  | [getType()](#getType--) | يرجع ImageType.Emf |
|
|  | [getByteContent()](#getByteContent--) | يرجع محتوى هذه الصورة EMF كتدفق ثنائي |
|
|  | [getTextContent()](#getTextContent--) | يرجع محتوى هذه الصورة EMF كنص عادي |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | يحفظ هذه الصورة EMF إلى الملف |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | يحفظ هذه الصورة المتجهة EMF كصورة PNG نقطية |
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | يحفظ هذه الصورة المتجهة EMF كصورة SVG متجهة |
|
|  | [dispose()](#dispose--) | يُفرغ هذه الصورة EMF عن طريق إفراغ محتواها وجعل معظم |
الطرق والخصائص غير عاملة
|
### EmfImage(String name, String contentInBase64) {#EmfImage-java.lang.String-java.lang.String-}
```
public EmfImage(String name, String contentInBase64)
```


ينشئ كائن EmfImage جديد من المحتوى، مُمثَّلً بترميز base64
سلسلة، ومع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم صورة EMF. لا يمكن أن يكون null أو فارغًا أو يتضمن مسافات فقط. |
|
|  | contentInBase64 | java.lang.String | المحتوى كسلسلة مشفّرة بقاعدة 64. لا يمكن أن يكون null أو فارغًا أو يتضمن مسافات فقط. إذا لم يكن محتوى EMF، سيتم رمي استثناء. |
|

### EmfImage(String name, InputStream binaryContent) {#EmfImage-java.lang.String-java.io.InputStream-}
```
public EmfImage(String name, InputStream binaryContent)
```


ينشئ كائن EmfImage جديد من المحتوى، مُمثَّلً بتدفق بايت،
ومع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم صورة EMF. لا يمكن أن يكون null أو فارغًا أو يتضمن مسافات فقط. |
|
|  | binaryContent | java.io.InputStream | المحتوى كتيار بايت. يبدأ القراءة من الموضع الأصلي. لا يمكن أن يكون فارغًا. يجب أن يكون قابلًا للقراءة والتمرير. إذا تم تحرير هذه الحالة، سيتم تحرير هذا التيار أيضًا. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


يتحقق مما إذا كان التدفق المحدد صورة EMF صالحة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | تدفق بايت إدخال. لا يمكن أن يكون NULL، ويجب أن يدعم القراءة والتمرير. |
|

**Returns:**
منطقي - true إذا كان التدفق المحدد يحتوي على صورة EMF صالحة، false خلاف ذلك

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


يتحقق مما إذا كانت السلسلة المشفّرة بقاعدة 64 المحددة صورة EMF صالحة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | سلسلة إدخال، حيث يُخزن محتوى صورة EMF بترميز base64. لا يمكن أن تكون NULL أو فارغة. |
|

**Returns:**
boolean - صحيح إذا كان النص المحدد يحتوي على صورة EMF صالحة، خطأ بخلاف ذلك

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


يرجع محتوى هذه الصورة EMF كتدفق ثنائي


**Returns:**
java.io.InputStream
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


يرجع محتوى هذه الصورة EMF كنص عادي


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


يحفظ هذه الصورة EMF إلى الملف


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | المسار الكامل للملف، الذي سيتم إنشاؤه (إذا لم يكن موجودًا) أو استبداله (إذا كان موجودًا) بمحتوى صورة EMF هذه |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


يحفظ هذه الصورة المتجهة EMF كصورة PNG نقطية


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | دفق الإخراج، الذي سيتم كتابة محتوى صورة PNG فيه. لا يمكن أن يكون NULL ويجب أن يكون قابلًا للكتابة. |
|

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public void saveToSvg(OutputStream outputSvgContent)
```


يحفظ هذه الصورة المتجهة EMF كصورة SVG متجهة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | دفق الإخراج، الذي سيتم كتابة محتوى صورة SVG فيه. لا يمكن أن يكون NULL ويجب أن يكون قابلًا للكتابة. |
|

### dispose() {#dispose--}
```
public void dispose()
```


يُفرغ هذه الصورة EMF عن طريق إفراغ محتواها وجعل معظم
الطرق والخصائص غير عاملة


