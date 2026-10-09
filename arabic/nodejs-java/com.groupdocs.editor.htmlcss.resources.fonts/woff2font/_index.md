---
title: "Woff2Font"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يمثل خطًا واحدًا في تنسيق WOFF2 Web Open Font Format"
type: docs
weight: 16
url: /ar/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/woff2font/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class Woff2Font extends FontResourceBase
```

يمثل خطًا واحدًا بتنسيق WOFF2 (Web Open Font Format).

## المنشئات

| المنشئ | الوصف |
| --- | --- |
|  | [Woff2Font(String name, String contentInBase64)](#Woff2Font-java.lang.String-java.lang.String-) | ينشئ فئة Woff2Font جديدة من المحتوى، الممثَّل كبيانات مشفرة بقاعدة 64 |
سلسلة، ومع اسم محدد
|
|  | [Woff2Font(String name, InputStream binaryContent)](#Woff2Font-java.lang.String-java.io.InputStream-) | ينشئ فئة Woff2Font جديدة من المحتوى، الممثَّل كتيار بايت، و |
مع اسم محدد
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
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | يتحقق مما إذا كانت السلسلة المشفرة بقاعدة 64 المحددة خط WOFF2 صالحًا |
|
|  | [getType()](#getType--) | يعيد FontType.Woff2 |
|
### Woff2Font(String name, String contentInBase64) {#Woff2Font-java.lang.String-java.lang.String-}
```
public Woff2Font(String name, String contentInBase64)
```


ينشئ فئة Woff2Font جديدة من المحتوى، الممثَّل كبيانات مشفرة بقاعدة 64
سلسلة، ومع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم خط WOFF2. لا يمكن أن يكون فارغًا أو null أو يحتوي على مسافات بيضاء. |
|
|  | contentInBase64 | java.lang.String | المحتوى كسلسلة مشفرة بقاعدة 64. لا يمكن أن يكون فارغًا أو خاليًا أو يحتوي على مسافات بيضاء. إذا لم يكن محتوى WOFF2، سيتم رمي الاستثناء. |
|

### Woff2Font(String name, InputStream binaryContent) {#Woff2Font-java.lang.String-java.io.InputStream-}
```
public Woff2Font(String name, InputStream binaryContent)
```


ينشئ فئة Woff2Font جديدة من المحتوى، الممثَّل كتيار بايت، و
مع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم خط WOFF2. لا يمكن أن يكون فارغًا أو null أو يحتوي على مسافات بيضاء. |
|
|  | binaryContent | java.io.InputStream | المحتوى كـ byte stream. يبدأ القراءة من الموضع الأصلي. لا يمكن أن يكون null. يجب أن يكون قابلًا للقراءة والبحث. إذا تم التخلص من هذه الحالة، سيتم أيضًا التخلص من هذا التيار. |
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
|  | binaryContent | java.io.InputStream | تدفق بايت، من المفترض أنه يحتوي على مورد WOFF2. |
|

**Returns:**
منطقي - صحيح إذا كان التدفق المحدد يحتوي على خط WOFF2 صالح، وإلا خاطئ.

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


يتحقق مما إذا كانت السلسلة المشفرة بقاعدة 64 المحددة خط WOFF2 صالحًا


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | محتوى الخط WOFF2 المفترض على شكل سلسلة مشفرة بقاعدة 64. |
|

**Returns:**
منطقي - صحيح إذا كانت السلسلة المحددة تحتوي على خط WOFF2 صالح، وإلا خاطئ.

### getType() {#getType--}
```
public FontType getType()
```


يعيد FontType.Woff2


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
