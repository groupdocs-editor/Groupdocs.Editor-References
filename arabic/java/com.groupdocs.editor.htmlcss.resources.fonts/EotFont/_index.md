---
title: "EotFont"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثل خطًا واحدًا في تنسيق EOT Embedded OpenType"
type: docs
weight: 10
url: /ar/java/com.groupdocs.editor.htmlcss.resources.fonts/eotfont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class EotFont extends FontResourceBase
```

يمثل خطًا واحدًا بتنسيق EOT (Embedded OpenType).

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [EotFont(String name, String contentInBase64)](#EotFont-java.lang.String-java.lang.String-) | ينشئ فئة EotFont جديدة من المحتوى، ممثلاً كسلسلة مشفرة بقاعدة 64 |
سلسلة، ومع اسم محدد
|
|  | [EotFont(String name, InputStream binaryContent)](#EotFont-java.lang.String-java.io.InputStream-) | ينشئ فئة EotFont جديدة من المحتوى، ممثلاً كدفق بايت، و |
بالاسم المحدد
|
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | حجم رأس EOT (بالبايت)، وهو مطلوب للتحقق من صحته |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | يتحقق مما إذا كان الدفق المحدد خط EOT صالح |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | يتحقق مما إذا كانت السلسلة المشفرة بقاعدة 64 المحددة خط EOT صالح |
|
|  | [getType()](#getType--) | يرجع FontType.Eot |
|
### EotFont(String name, String contentInBase64) {#EotFont-java.lang.String-java.lang.String-}
```
public EotFont(String name, String contentInBase64)
```


ينشئ فئة EotFont جديدة من المحتوى، ممثلاً كسلسلة مشفرة بقاعدة 64
سلسلة، ومع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم خط EOT. لا يمكن أن يكون فارغًا أو خاليًا أو يحتوي على مسافات بيضاء. |
|
|  | contentInBase64 | java.lang.String | المحتوى كسلسلة مشفّرة base64. لا يمكن أن تكون فارغة أو خالية أو تحتوي على مسافات بيضاء. إذا لم يكن محتوى EOT، سيتم رمي استثناء. |
|

### EotFont(String name, InputStream binaryContent) {#EotFont-java.lang.String-java.io.InputStream-}
```
public EotFont(String name, InputStream binaryContent)
```


ينشئ فئة EotFont جديدة من المحتوى، ممثلاً كدفق بايت، و
بالاسم المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم خط EOT. لا يمكن أن يكون فارغًا أو خاليًا أو يحتوي على مسافات بيضاء. |
|
|  | binaryContent | java.io.InputStream | المحتوى كتيار بايت. يبدأ القراءة من الموضع الأصلي. لا يمكن أن يكون فارغًا. يجب أن يكون قابلًا للقراءة والتمرير. إذا تم تحرير هذه الحالة، سيتم تحرير هذا التيار أيضًا. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


حجم رأس EOT (بالبايت)، وهو مطلوب للتحقق من صحته


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


يتحقق مما إذا كان الدفق المحدد خط EOT صالح


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | تدفق بايت، من المفترض أنه يحتوي على مورد EOT. |
|

**Returns:**
منطقي - صحيح إذا كان التدفق المحدد يحتوي على خط EOT صالح، خطأ خلاف ذلك.

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


يتحقق مما إذا كانت السلسلة المشفرة بقاعدة 64 المحددة خط EOT صالح


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | محتوى خط EOT المفترض على شكل سلسلة مشفّرة base64. |
|

**Returns:**
منطقي - صحيح إذا كانت السلسلة المحددة تحتوي على خط EOT صالح، خطأ خلاف ذلك.

### getType() {#getType--}
```
public FontType getType()
```


يرجع FontType.Eot


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
