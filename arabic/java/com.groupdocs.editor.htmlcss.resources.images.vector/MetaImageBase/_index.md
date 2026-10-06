---
title: "MetaImageBase"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "الفئة المجردة الأساسية لتنسيقات صور WMF و EMF"
type: docs
weight: 11
url: /ar/java/com.groupdocs.editor.htmlcss.resources.images.vector/metaimagebase/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.images.vector.VectorImageResourceBase](../../com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase)
```
public abstract class MetaImageBase extends VectorImageResourceBase
```

الفئة المجردة الأساسية لتنسيقات صور WMF و EMF

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [MetaImageBase(String name, String contentInBase64, boolean isWmf)](#MetaImageBase-java.lang.String-java.lang.String-boolean-) | منشئ عام، الذي يُحضّر لإنشاء نسخة WMF أو EMF من |
سلسلة مشفرة base64
|
|  | [MetaImageBase(String name, InputStream binaryContent, boolean isWmf)](#MetaImageBase-java.lang.String-java.io.InputStream-boolean-) | منشئ عام، الذي يُحضّر لإنشاء نسخة WMF أو EMF من |
تدفق بايت
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isValidWmf(InputStream binaryContent)](#isValidWmf-java.io.InputStream-) | يحدد ما إذا كان تدفق البايت المحدد يحتوي على صورة WMF صالحة |
|
|  | [isValidWmf(String contentInBase64)](#isValidWmf-java.lang.String-) | يحدد ما إذا كانت السلسلة المحددة تحتوي على صورة WMF صالحة، والتي هي |
مشفر بـ base64
|
|  | [isValidEmf(InputStream binaryContent)](#isValidEmf-java.io.InputStream-) | يحدد ما إذا كان تدفق البايت المحدد يحتوي على صورة EMF صالحة |
|
|  | [isValidEmf(String contentInBase64)](#isValidEmf-java.lang.String-) | يحدد ما إذا كانت السلسلة المحددة تحتوي على صورة EMF صالحة، والتي هي |
مشفر بـ base64
|
|  | [saveToSvg(OutputStream outputSvgContent)](#saveToSvg-java.io.OutputStream-) | في التنفيذ يجب على النوع حفظ الـ vector meta-image الحالي إلى |
تنسيق SVG المتجه إلى تدفق البايت المحدد
|
### MetaImageBase(String name, String contentInBase64, boolean isWmf) {#MetaImageBase-java.lang.String-java.lang.String-boolean-}
```
public MetaImageBase(String name, String contentInBase64, boolean isWmf)
```


منشئ عام، الذي يُحضّر لإنشاء نسخة WMF أو EMF من
سلسلة مشفرة base64


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم إلزامي |
|
|  | contentInBase64 | java.lang.String | المحتوى كسلسلة base64. يجب ألا يكون NULL أو فارغًا. |
|
|  | isWmf | boolean | true لـ WMF، false لـ EMF |
|

### MetaImageBase(String name, InputStream binaryContent, boolean isWmf) {#MetaImageBase-java.lang.String-java.io.InputStream-boolean-}
```
public MetaImageBase(String name, InputStream binaryContent, boolean isWmf)
```


منشئ عام، الذي يُحضّر لإنشاء نسخة WMF أو EMF من
تدفق بايت


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم إلزامي |
|
|  | binaryContent | java.io.InputStream | المحتوى كتدفق بايت. يجب أن يكون صالحًا. |
|
|  | isWmf | boolean | true لـ WMF، false لـ EMF |
|

### isValidWmf(InputStream binaryContent) {#isValidWmf-java.io.InputStream-}
```
public static boolean isValidWmf(InputStream binaryContent)
```


يحدد ما إذا كان تدفق البايت المحدد يحتوي على صورة WMF صالحة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | تدفق البايت المدخل. يجب أن يكون صالحًا. |
|

**Returns:**
boolean - يُرجع 'true' إذا كان صالحًا و 'false' إذا كان غير صالح

### isValidWmf(String contentInBase64) {#isValidWmf-java.lang.String-}
```
public static boolean isValidWmf(String contentInBase64)
```


يحدد ما إذا كانت السلسلة المحددة تحتوي على صورة WMF صالحة، والتي هي
مشفر بـ base64


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | سلسلة، يُفترض أنها تحتوي على صورة WMF مشفرة base64 |
|

**Returns:**
boolean - يُرجع 'true' إذا كان صالحًا و 'false' إذا كان غير صالح

### isValidEmf(InputStream binaryContent) {#isValidEmf-java.io.InputStream-}
```
public static boolean isValidEmf(InputStream binaryContent)
```


يحدد ما إذا كان تدفق البايت المحدد يحتوي على صورة EMF صالحة


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | تدفق البايت المدخل. يجب أن يكون صالحًا. |
|

**Returns:**
boolean - يُرجع 'true' إذا كان صالحًا و 'false' إذا كان غير صالح

### isValidEmf(String contentInBase64) {#isValidEmf-java.lang.String-}
```
public static boolean isValidEmf(String contentInBase64)
```


يحدد ما إذا كانت السلسلة المحددة تحتوي على صورة EMF صالحة، والتي هي
مشفر بـ base64


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | سلسلة، يُفترض أنها تحتوي على صورة EMF مُشفّرة بقاعدة 64 |
|

**Returns:**
boolean - يُرجع 'true' إذا كان صالحًا و 'false' إذا كان غير صالح

### saveToSvg(OutputStream outputSvgContent) {#saveToSvg-java.io.OutputStream-}
```
public abstract void saveToSvg(OutputStream outputSvgContent)
```


في التنفيذ يجب على النوع حفظ الـ vector meta-image الحالي إلى
تنسيق SVG المتجه إلى تدفق البايت المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | outputSvgContent | java.io.OutputStream | تدفق بايت، يُخزن فيه نسخة SVG من هذه الصورة الوصفية المتجهة. يجب ألا يكون NULL ويجب أن يدعم الكتابة. |
|

