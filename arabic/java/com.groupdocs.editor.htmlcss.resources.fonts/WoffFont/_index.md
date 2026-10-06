---
title: "WoffFont"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثل خطًا واحدًا في تنسيق WOFF Web Open Font Format"
type: docs
weight: 17
url: /ar/java/com.groupdocs.editor.htmlcss.resources.fonts/wofffont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class WoffFont extends FontResourceBase
```

يمثل خطًا واحدًا بتنسيق WOFF (Web Open Font Format).

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [WoffFont(String name, String contentInBase64)](#WoffFont-java.lang.String-java.lang.String-) | ينشئ فئة WoffFont جديدة من المحتوى، ممثلاً كسلسلة مشفرة بقاعدة 64 |
سلسلة، ومع اسم محدد
|
|  | [WoffFont(String name, InputStream binaryContent)](#WoffFont-java.lang.String-java.io.InputStream-) | ينشئ فئة WoffFont جديدة من المحتوى، ممثلاً كدفق بايت، و |
بالاسم المحدد
|
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | حجم رأس WOFF (بالبايت)، وهو مطلوب للتحقق من صحته |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | يتحقق مما إذا كان الدفق المحدد خط WOFF صالح |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | يتحقق مما إذا كانت السلسلة المشفرة بقاعدة 64 المحددة خط WOFF صالح |
|
|  | [getType()](#getType--) | يرجع FontType.Woff |
|
### WoffFont(String name, String contentInBase64) {#WoffFont-java.lang.String-java.lang.String-}
```
public WoffFont(String name, String contentInBase64)
```


ينشئ فئة WoffFont جديدة من المحتوى، ممثلاً كسلسلة مشفرة بقاعدة 64
سلسلة، ومع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم خط WOFF. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات فقط. |
|
|  | contentInBase64 | java.lang.String | المحتوى كسلسلة مشفرة بقاعدة 64. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات فقط. إذا لم يكن محتوى WOFF، سيتم رمي استثناء. |
|

### WoffFont(String name, InputStream binaryContent) {#WoffFont-java.lang.String-java.io.InputStream-}
```
public WoffFont(String name, InputStream binaryContent)
```


ينشئ فئة WoffFont جديدة من المحتوى، ممثلاً كدفق بايت، و
بالاسم المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم خط WOFF. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات فقط. |
|
|  | binaryContent | java.io.InputStream | المحتوى كتيار بايت. يبدأ القراءة من الموضع الأصلي. لا يمكن أن يكون null. يجب أن يكون قابلًا للقراءة و seakable. إذا تم التخلص من هذه المثيلة، سيتم أيضًا التخلص من هذا التيار. |
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


يتحقق مما إذا كان الدفق المحدد خط WOFF صالح


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | دفق بايت، من المفترض أنه يحتوي على مورد WOFF |
|

**Returns:**
منطقي - صحيح إذا كان الدفق المحدد يحتوي على خط WOFF صالح، خطأ خلاف ذلك

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


يتحقق مما إذا كانت السلسلة المشفرة بقاعدة 64 المحددة خط WOFF صالح


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | محتوى خط WOFF المفترض على شكل سلسلة مشفرة بقاعدة 64 |
|

**Returns:**
منطقي - صحيح إذا كانت السلسلة المحددة تحتوي على خط WOFF صالح، خطأ خلاف ذلك

### getType() {#getType--}
```
public FontType getType()
```


يرجع FontType.Woff


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
