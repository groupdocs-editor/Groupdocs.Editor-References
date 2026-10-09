---
title: "WoffFont"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يمثل خطًا واحدًا في تنسيق WOFF Web Open Font Format"
type: docs
weight: 17
url: /ar/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/wofffont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class WoffFont extends FontResourceBase
```

يمثل خطًا واحدًا بتنسيق WOFF (Web Open Font Format).

## المنشئات

| المنشئ | الوصف |
| --- | --- |
|  | [WoffFont(String name, String contentInBase64)](#WoffFont-java.lang.String-java.lang.String-) | ينشئ فئة WoffFont جديدة من المحتوى، الممثل كـ base64-encoded |
سلسلة، ومع اسم محدد
|
|  | [WoffFont(String name, InputStream binaryContent)](#WoffFont-java.lang.String-java.io.InputStream-) | ينشئ فئة WoffFont جديدة من المحتوى، الممثل كـ byte stream، و |
مع اسم محدد
|
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | حجم رأس WOFF (بالبايت)، وهو مطلوب للتحقق من صحته |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | يتحقق مما إذا كان التيار المحدد خطًا صالحًا من نوع WOFF |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | يتحقق مما إذا كانت السلسلة المشفرة بـ base64-encoded المحددة خطًا صالحًا من نوع WOFF |
|
|  | [getType()](#getType--) | يعيد FontType.Woff |
|
### WoffFont(String name, String contentInBase64) {#WoffFont-java.lang.String-java.lang.String-}
```
public WoffFont(String name, String contentInBase64)
```


ينشئ فئة WoffFont جديدة من المحتوى، الممثل كـ base64-encoded
سلسلة، ومع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم خط WOFF. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات فقط. |
|
|  | contentInBase64 | java.lang.String | المحتوى كسلسلة base64-encoded. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات فقط. إذا لم يكن محتوى WOFF، سيتم إلقاء استثناء. |
|

### WoffFont(String name, InputStream binaryContent) {#WoffFont-java.lang.String-java.io.InputStream-}
```
public WoffFont(String name, InputStream binaryContent)
```


ينشئ فئة WoffFont جديدة من المحتوى، الممثل كـ byte stream، و
مع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم خط WOFF. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات فقط. |
|
|  | binaryContent | java.io.InputStream | المحتوى كـ byte stream. يبدأ القراءة من الموضع الأصلي. لا يمكن أن يكون null. يجب أن يكون قابلًا للقراءة والبحث. إذا تم التخلص من هذه الحالة، سيتم أيضًا التخلص من هذا التيار. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


حجم رأس WOFF (بالبايت)، وهو مطلوب للتحقق من صحته


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


يتحقق مما إذا كان التيار المحدد خطًا صالحًا من نوع WOFF


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | Byte stream، من المفترض أنه يحتوي على مورد WOFF |
|

**Returns:**
منطقي - True إذا كان التيار المحدد يحتوي على خط WOFF صالح، وإلا false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


يتحقق مما إذا كانت السلسلة المشفرة بـ base64-encoded المحددة خطًا صالحًا من نوع WOFF


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | محتوى خط WOFF المفترض على شكل سلسلة base64-encoded |
|

**Returns:**
منطقي - True إذا كانت السلسلة المحددة تحتوي على خط WOFF صالح، وإلا false

### getType() {#getType--}
```
public FontType getType()
```


يعيد FontType.Woff


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
