---
title: "TtfFont"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثل خطًا واحدًا في تنسيق TTF TrueType Font"
type: docs
weight: 15
url: /ar/java/com.groupdocs.editor.htmlcss.resources.fonts/ttffont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class TtfFont extends FontResourceBase
```

يمثل خطًا واحدًا بتنسيق TTF (TrueType Font).

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [TtfFont(String name, String contentInBase64)](#TtfFont-java.lang.String-java.lang.String-) | ينشئ فئة TtfFont جديدة من المحتوى، الممثل كـ base64-encoded |
سلسلة، ومع اسم محدد
|
|  | [TtfFont(String name, InputStream binaryContent)](#TtfFont-java.lang.String-java.io.InputStream-) | ينشئ فئة TtfFont جديدة من المحتوى، الممثل كـ byte stream، و |
بالاسم المحدد
|
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | حجم رأس TTF (بالبايت)، وهو مطلوب للتحقق من صحته |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | يتحقق مما إذا كان التيار المحدد خط TTF صالحًا |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | يتحقق مما إذا كانت السلسلة base64-encoded المحددة خط TTF صالحًا |
|
|  | [getType()](#getType--) | يرجع FontType.Ttf |
|
### TtfFont(String name, String contentInBase64) {#TtfFont-java.lang.String-java.lang.String-}
```
public TtfFont(String name, String contentInBase64)
```


ينشئ فئة TtfFont جديدة من المحتوى، الممثل كـ base64-encoded
سلسلة، ومع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم خط TTF. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات بيضاء. |
|
|  | contentInBase64 | java.lang.String | المحتوى كسلسلة base64-encoded. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات بيضاء. إذا لم يكن محتوى TTF، سيتم رمي استثناء. |
|

### TtfFont(String name, InputStream binaryContent) {#TtfFont-java.lang.String-java.io.InputStream-}
```
public TtfFont(String name, InputStream binaryContent)
```


ينشئ فئة TtfFont جديدة من المحتوى، الممثل كـ byte stream، و
بالاسم المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم خط TTF. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات بيضاء. |
|
|  | binaryContent | java.io.InputStream | المحتوى كتيار بايت. يبدأ القراءة من الموضع الأصلي. لا يمكن أن يكون فارغًا. يجب أن يكون قابلًا للقراءة والتمرير. إذا تم تحرير هذه الحالة، سيتم تحرير هذا التيار أيضًا. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


حجم رأس TTF (بالبايت)، وهو مطلوب للتحقق من صحته


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


يتحقق مما إذا كان التيار المحدد خط TTF صالحًا


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | تيار بايت، من المفترض أنه يحتوي على مورد TTF |
|

**Returns:**
منطقي - صحيح إذا كان الدفق المحدد يحتوي على خط TTF صالح، خطأ خلاف ذلك

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


يتحقق مما إذا كانت السلسلة base64-encoded المحددة خط TTF صالحًا


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | محتوى الخط TTF المفترض على شكل سلسلة مشفرة بقاعدة 64 |
|

**Returns:**
منطقي - صحيح إذا كانت السلسلة المحددة تحتوي على خط TTF صالح، خطأ خلاف ذلك

### getType() {#getType--}
```
public FontType getType()
```


يرجع FontType.Ttf


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
