---
title: "WmfImage"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يمثل صورة متجهة واحدة في تنسيق WMF Windows MetaFile مع بيانات التعريف الخاصة بها والطرق الإضافية"
type: docs
weight: 14
url: /ar/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/wmfimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase), [com.groupdocs.editor.htmlcss.resources.images.vector.MetaImageBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase)
```
public final class WmfImage extends MetaImageBase
```

يمثل صورة متجهة واحدة في تنسيق WMF (Windows MetaFile) مع
البيانات الوصفية والطرق الإضافية

## المنشئات

| المنشئ | الوصف |
| --- | --- |
|  | [WmfImage(String name, String contentInBase64)](#WmfImage-java.lang.String-java.lang.String-) | ينشئ كائن WmfImage جديد من المحتوى، ممثلًا كترميز base64 |
سلسلة، ومع اسم محدد
|
|  | [WmfImage(String name, InputStream binaryContent)](#WmfImage-java.lang.String-java.io.InputStream-) | ينشئ كائن WmfImage جديد من المحتوى، ممثلًا كتيار بايت، |
ومع اسم محدد
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | يتحقق مما إذا كان الدفق المحدد صورة WMF صالحة |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | يتحقق مما إذا كان النص المشفر base64 المحدد صورة WMF صالحة |
|
|  | [getType()](#getType--) | يرجع ImageType.Wmf |
|
|  | [getByteContent()](#getByteContent--) | يرجع محتوى صورة WMF هذه كتيار ثنائي |
|
|  | [getTextContent()](#getTextContent--) | يرجع محتوى صورة WMF هذه كنص عادي |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | يحفظ صورة WMF هذه إلى الملف |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | يحفظ صورة WMF المتجهة هذه إلى صورة PNG نقطية |
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | يحفظ صورة WMF المتجهة هذه إلى صورة SVG متجهة |
|
|  | [dispose()](#dispose--) | يتخلص من صورة WMF هذه عن طريق التخلص من محتواها وجعل معظم |
الطرق والخصائص غير عاملة
|
### WmfImage(String name, String contentInBase64) {#WmfImage-java.lang.String-java.lang.String-}
```
public WmfImage(String name, String contentInBase64)
```


ينشئ كائن WmfImage جديد من المحتوى، ممثلًا كترميز base64
سلسلة، ومع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم صورة WMF. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات بيضاء. |
|
|  | contentInBase64 | java.lang.String | المحتوى كسلسلة مشفرة base64. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات بيضاء. إذا لم يكن محتوى WMF، سيتم رمي استثناء. |
|

### WmfImage(String name, InputStream binaryContent) {#WmfImage-java.lang.String-java.io.InputStream-}
```
public WmfImage(String name, InputStream binaryContent)
```


ينشئ كائن WmfImage جديد من المحتوى، ممثلًا كتيار بايت،
ومع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم صورة WMF. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات بيضاء. |
|
|  | binaryContent | java.io.InputStream | المحتوى كتيار بايت. يبدأ القراءة من الموضع الأصلي. لا يمكن أن يكون null. يجب أن يكون قابلًا للقراءة والتمرير. إذا تم تحرير هذه الحالة، سيتم تحرير هذا التيار أيضًا. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


يتحقق مما إذا كان الدفق المحدد صورة WMF صالحة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | دفق بايت إدخال. لا يمكن أن يكون NULL، ويجب أن يدعم القراءة والتمرير. |
|

**Returns:**
منطقي - True إذا كان الدفق المحدد يحتوي على صورة WMF صالحة، false خلاف ذلك

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


يتحقق مما إذا كان النص المشفر base64 المحدد صورة WMF صالحة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | سلسلة إدخال، حيث يُخزن محتوى صورة WMF بترميز base64. لا يمكن أن تكون NULL أو فارغة. |
|

**Returns:**
منطقي - True إذا كانت السلسلة المحددة تحتوي على صورة WMF صالحة، false خلاف ذلك

### getType() {#getType--}
```
public ImageType getType()
```


يرجع ImageType.Wmf


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


يرجع محتوى صورة WMF هذه كتيار ثنائي


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


يرجع محتوى صورة WMF هذه كنص عادي


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


يحفظ صورة WMF هذه إلى الملف


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | المسار الكامل للملف، الذي سيتم إنشاؤه (إذا لم يكن موجودًا) أو استبداله (إذا كان موجودًا) بمحتوى صورة WMF هذه |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


يحفظ صورة WMF المتجهة هذه إلى صورة PNG نقطية


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | دفق إخراج، يُكتب فيه محتوى صورة PNG. لا يمكن أن يكون NULL ويجب أن يكون قابلًا للكتابة. |
|

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public void saveToSvg(OutputStream outputSvgContent)
```


يحفظ صورة WMF المتجهة هذه إلى صورة SVG متجهة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | دفق إخراج، يُكتب فيه محتوى صورة SVG. لا يمكن أن يكون NULL ويجب أن يكون قابلًا للكتابة. |
|

### dispose() {#dispose--}
```
public void dispose()
```


يتخلص من صورة WMF هذه عن طريق التخلص من محتواها وجعل معظم
الطرق والخصائص غير عاملة


