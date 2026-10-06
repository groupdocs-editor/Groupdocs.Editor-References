---
title: "SvgImage"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثل صورة متجهة واحدة بصيغة SVG (Scalable Vector Graphics) مع بياناتها التعريفية والطرق الإضافية"
type: docs
weight: 12
url: /ar/java/com.groupdocs.editor.htmlcss.resources.images.vector/svgimage/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)
```
public final class SvgImage extends VectorImageResourceBase
```

يمثل صورة متجهة واحدة بصيغة SVG (Scalable Vector Graphics) مع
البيانات الوصفية والطرق الإضافية

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [SvgImage(String name, String content)](#SvgImage-java.lang.String-java.lang.String-) | ينشئ كائن SvgImage جديد من المحتوى، ممثلًا كسلسلة عادية، |
ومع اسم محدد
|
|  | [SvgImage(String name, InputStream binaryContent)](#SvgImage-java.lang.String-java.io.InputStream-) | ينشئ كائن SvgImage جديد من المحتوى، ممثلًا بتدفق بايت، |
ومع اسم محدد
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isValid(String content)](#isValid-java.lang.String-) | يجري فحصًا سطحيًا لمعرفة ما إذا كان المحتوى النصي المتوافق مع XML المحدد |
يمثل صورة SVG
|
|  | [getType()](#getType--) | يعيد ImageType.Svg |
|
|  | [getByteContent()](#getByteContent--) | إرجاع محتوى هذه الصورة SVG كتيار ثنائي |
|
|  | [getTextContent()](#getTextContent--) | إرجاع محتوى هذه الصورة SVG كنص عادي (بتنسيق XML) |
|
|  | [getXmlContent()](#getXmlContent--) | إرجاع محتوى هذه الصورة SVG بصيغتها الأصلية المتوافقة مع XML |
شكل نصي
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | يحفظ هذه الصورة SVG إلى الملف |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | يحفظ هذه الصورة SVG المتجهة إلى صورة PNG نقطية |
|
|  | [dispose()](#dispose--) | يحرّر هذه الصورة النقطية، مفرغًا محتواها وجاعلاً معظم الطرق |
وخصائص غير عاملة
|
### SvgImage(String name, String content) {#SvgImage-java.lang.String-java.lang.String-}
```
public SvgImage(String name, String content)
```


ينشئ كائن SvgImage جديد من المحتوى، ممثلًا كسلسلة عادية،
ومع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم صورة SVG. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات فقط. |
|
|  | المحتوى | java.lang.String | المحتوى كسلسلة عادية، تحتوي على محتوى SVG صالح ومتوافق مع XML. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات فقط. إذا لم يكن محتوى SVG، سيتم رمي استثناء. |
|

### SvgImage(String name, InputStream binaryContent) {#SvgImage-java.lang.String-java.io.InputStream-}
```
public SvgImage(String name, InputStream binaryContent)
```


ينشئ كائن SvgImage جديد من المحتوى، ممثلًا بتدفق بايت،
ومع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم صورة SVG. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات فقط. |
|
|  | binaryContent | java.io.InputStream | المحتوى كتيار بايت. يبدأ القراءة من الموضع الأصلي. لا يمكن أن يكون فارغًا. يجب أن يكون قابلًا للقراءة والتمرير. إذا تم تحرير هذه الحالة، سيتم تحرير هذا التيار أيضًا. |
|

### isValid(String content) {#isValid-java.lang.String-}
```
public static boolean isValid(String content)
```


يجري فحصًا سطحيًا لمعرفة ما إذا كان المحتوى النصي المتوافق مع XML المحدد
يمثل صورة SVG


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | المحتوى | java.lang.String | محتوى XML لصورة SVG كنص بسيط، وليس محتوى مشفر بـ base64 |
|

**Returns:**
منطقي - True إذا كان يمكن اعتبار السلسلة المحددة SVG صالحة من الوهلة الأولى، false إذا لم تكن SVG بالتأكيد

### getType() {#getType--}
```
public ImageType getType()
```


يعيد ImageType.Svg


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


إرجاع محتوى هذه الصورة SVG كتيار ثنائي


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public String getTextContent()
```


إرجاع محتوى هذه الصورة SVG كنص عادي (بتنسيق XML)


**Returns:**
java.lang.String -
### getXmlContent() {#getXmlContent--}
```
public final String getXmlContent()
```


إرجاع محتوى هذه الصورة SVG بصيغتها الأصلية المتوافقة مع XML
شكل نصي


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public void save(String fullPathToFile)
```


يحفظ هذه الصورة SVG إلى الملف


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | المسار الكامل للملف الذي سيتم إنشاؤه (إذا لم يكن موجودًا) أو استبداله (إذا كان موجودًا) بمحتوى هذه الصورة SVG |
|

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public void saveToPng(OutputStream outputPngContent)
```


يحفظ هذه الصورة SVG المتجهة إلى صورة PNG نقطية


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | دفق الإخراج، الذي سيتم كتابة محتوى صورة PNG فيه. لا يمكن أن يكون NULL ويجب أن يكون قابلًا للكتابة. |
|

### dispose() {#dispose--}
```
public void dispose()
```


يحرّر هذه الصورة النقطية، مفرغًا محتواها وجاعلاً معظم الطرق
وخصائص غير عاملة


