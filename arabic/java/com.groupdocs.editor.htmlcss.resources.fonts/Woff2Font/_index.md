---
title: "Woff2Font"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثل خطًا واحدًا في تنسيق WOFF2 Web Open Font Format"
type: docs
weight: 16
url: /ar/java/com.groupdocs.editor.htmlcss.resources.fonts/woff2font/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class Woff2Font extends FontResourceBase
```

يمثل خطًا واحدًا بتنسيق WOFF2 (Web Open Font Format).

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [Woff2Font(String name, String contentInBase64)](#Woff2Font-java.lang.String-java.lang.String-) | ينشئ فئة Woff2Font جديدة من المحتوى، الممثل كـ base64-encoded |
سلسلة، ومع اسم محدد
|
|  | [Woff2Font(String name, InputStream binaryContent)](#Woff2Font-java.lang.String-java.io.InputStream-) | ينشئ فئة Woff2Font جديدة من المحتوى، الممثل كـ byte stream، و |
بالاسم المحدد
|
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | حجم رأس WOFF2 (بالبايت)، وهو مطلوب للتحقق من صحته |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | يتحقق مما إذا كان التيار المحدد خط WOFF2 صالحًا |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | يتحقق مما إذا كانت السلسلة base64-encoded المحددة خط WOFF2 صالحًا |
|
|  | [getType()](#getType--) | يرجع FontType.Woff2 |
|
### Woff2Font(String name, String contentInBase64) {#Woff2Font-java.lang.String-java.lang.String-}
```
public Woff2Font(String name, String contentInBase64)
```


ينشئ فئة Woff2Font جديدة من المحتوى، الممثل كـ base64-encoded
سلسلة، ومع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم خط WOFF2. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات بيضاء. |
|
|  | contentInBase64 | java.lang.String | المحتوى كسلسلة base64-encoded. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات بيضاء. إذا لم يكن محتوى WOFF2، سيتم رمي استثناء. |
|

### Woff2Font(String name, InputStream binaryContent) {#Woff2Font-java.lang.String-java.io.InputStream-}
```
public Woff2Font(String name, InputStream binaryContent)
```


ينشئ فئة Woff2Font جديدة من المحتوى، الممثل كـ byte stream، و
بالاسم المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم خط WOFF2. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات بيضاء. |
|
|  | binaryContent | java.io.InputStream | المحتوى كتيار بايت. يبدأ القراءة من الموضع الأصلي. لا يمكن أن يكون null. يجب أن يكون قابلًا للقراءة و seakable. إذا تم التخلص من هذه المثيلة، سيتم أيضًا التخلص من هذا التيار. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


حجم رأس WOFF2 (بالبايت)، وهو مطلوب للتحقق من صحته


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


يتحقق مما إذا كان التيار المحدد خط WOFF2 صالحًا


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | تيار بايت، من المفترض أنه يحتوي على مورد WOFF2 |
|

**Returns:**
منطقي - True إذا كان التيار المحدد يحتوي على خط WOFF2 صالح، false otherwise

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


يتحقق مما إذا كانت السلسلة base64-encoded المحددة خط WOFF2 صالحًا


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | محتوى الخط WOFF2 المفترض في شكل سلسلة base64-encoded |
|

**Returns:**
منطقي - True إذا كانت السلسلة المحددة تحتوي على خط WOFF2 صالح، false otherwise

### getType() {#getType--}
```
public FontType getType()
```


يرجع FontType.Woff2


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
