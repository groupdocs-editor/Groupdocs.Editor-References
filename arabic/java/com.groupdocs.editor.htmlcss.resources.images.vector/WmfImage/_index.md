---
title: "WmfImage"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثل صورة متجهة واحدة بصيغة WMF (Windows MetaFile) مع البيانات الوصفية الخاصة بها والطرق الإضافية"
type: docs
weight: 14
url: /ar/java/com.groupdocs.editor.htmlcss.resources.images.vector/wmfimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase), [com.groupdocs.editor.htmlcss.resources.images.vector.MetaImageBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase)
```
public final class WmfImage extends MetaImageBase
```

يمثل صورة متجهة واحدة بصيغة WMF (Windows MetaFile) مع
البيانات الوصفية والطرق الإضافية

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [WmfImage(String name, String contentInBase64)](#WmfImage-java.lang.String-java.lang.String-) | ينشئ كائن WmfImage جديد من المحتوى، ممثلًا بتشفير base64 |
سلسلة، ومع اسم محدد
|
|  | [WmfImage(String name, InputStream binaryContent)](#WmfImage-java.lang.String-java.io.InputStream-) | ينشئ كائن WmfImage جديد من المحتوى، ممثلًا بتدفق بايت، |
ومع اسم محدد
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | يتحقق مما إذا كان التدفق المحدد صورة WMF صالحة |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | يتحقق مما إذا كانت السلسلة المشفرة بـ base64 المحددة صورة WMF صالحة |
|
|  | [getType()](#getType--) | يعيد ImageType.Wmf |
|
|  | [getByteContent()](#getByteContent--) | يعيد محتوى صورة WMF هذه كتدفق ثنائي |
|
|  | [getTextContent()](#getTextContent--) | يعيد محتوى صورة WMF هذه كنص عادي |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | يحفظ صورة WMF هذه إلى الملف |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | يحفظ صورة WMF المتجهة هذه إلى صورة PNG نقطية |
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | يحفظ صورة WMF المتجهة هذه إلى صورة SVG متجهة |
|
|  | [dispose()](#dispose--) | يقوم بتحرير صورة WMF هذه عن طريق تحرير محتواها وجعل معظمها |
الطرق والخصائص غير عاملة
|
### WmfImage(String name, String contentInBase64) {#WmfImage-java.lang.String-java.lang.String-}
```
public WmfImage(String name, String contentInBase64)
```


ينشئ كائن WmfImage جديد من المحتوى، ممثلًا بتشفير base64
سلسلة، ومع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم صورة WMF. لا يمكن أن يكون فارغًا أو NULL أو يحتوي على مسافات بيضاء. |
|
|  | contentInBase64 | java.lang.String | المحتوى كسلسلة مشفرة بـ base64. لا يمكن أن يكون NULL أو فارغًا أو يحتوي على مسافات بيضاء. إذا لم يكن محتوى WMF، سيتم إلقاء استثناء. |
|

### WmfImage(String name, InputStream binaryContent) {#WmfImage-java.lang.String-java.io.InputStream-}
```
public WmfImage(String name, InputStream binaryContent)
```


ينشئ كائن WmfImage جديد من المحتوى، ممثلًا بتدفق بايت،
ومع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم صورة WMF. لا يمكن أن يكون فارغًا أو NULL أو يحتوي على مسافات بيضاء. |
|
|  | binaryContent | java.io.InputStream | المحتوى كتيار بايت. يبدأ القراءة من الموضع الأصلي. لا يمكن أن يكون فارغًا. يجب أن يكون قابلًا للقراءة والتمرير. إذا تم تحرير هذه الحالة، سيتم تحرير هذا التيار أيضًا. |
|

### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


يتحقق مما إذا كان التدفق المحدد صورة WMF صالحة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | تدفق بايت إدخال. لا يمكن أن يكون NULL، ويجب أن يدعم القراءة والتمرير. |
|

**Returns:**
منطقي - True إذا كان التدفق المحدد يحتوي على صورة WMF صالحة، false خلاف ذلك

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


يتحقق مما إذا كانت السلسلة المشفرة بـ base64 المحددة صورة WMF صالحة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | سلسلة الإدخال، حيث يُخزن محتوى صورة WMF بتشفير base64. لا يمكن أن تكون NULL أو فارغة. |
|

**Returns:**
منطقي - True إذا كانت السلسلة المحددة تحتوي على صورة WMF صالحة، false خلاف ذلك

### getType() {#getType--}
```
public ImageType getType()
```


يعيد ImageType.Wmf


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


يعيد محتوى صورة WMF هذه كتدفق ثنائي


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


يعيد محتوى صورة WMF هذه كنص عادي


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
|  | outputPngContent | java.io.OutputStream | دفق الإخراج، الذي سيتم كتابة محتوى صورة PNG فيه. لا يمكن أن يكون NULL ويجب أن يكون قابلًا للكتابة. |
|

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public void saveToSvg(OutputStream outputSvgContent)
```


يحفظ صورة WMF المتجهة هذه إلى صورة SVG متجهة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | دفق الإخراج، الذي سيتم كتابة محتوى صورة SVG فيه. لا يمكن أن يكون NULL ويجب أن يكون قابلًا للكتابة. |
|

### dispose() {#dispose--}
```
public void dispose()
```


يقوم بتحرير صورة WMF هذه عن طريق تحرير محتواها وجعل معظمها
الطرق والخصائص غير عاملة


