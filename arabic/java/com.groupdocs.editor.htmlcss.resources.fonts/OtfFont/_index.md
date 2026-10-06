---
title: "OtfFont"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثل خطًا واحدًا في تنسيق OTF Open Type Format"
type: docs
weight: 13
url: /ar/java/com.groupdocs.editor.htmlcss.resources.fonts/otffont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class OtfFont extends FontResourceBase
```

يمثل خطًا واحدًا بتنسيق OTF (Open Type Format).

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [OtfFont(String name, String contentInBase64)](#OtfFont-java.lang.String-java.lang.String-) | ينشئ فئة OtfFont جديدة من المحتوى، الممثل كـ base64 |
سلسلة، ومع اسم محدد
|
|  | [OtfFont(String name, InputStream binaryContent)](#OtfFont-java.lang.String-java.io.InputStream-) | ينشئ فئة OtfFont جديدة من المحتوى، الممثل كتيار بايت، و |
بالاسم المحدد
|
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | حجم رأس OTF (بالبايت)، وهو مطلوب للتحقق من صحته |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | يتحقق مما إذا كان التيار المحدد خط OTF صالحًا |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | يتحقق مما إذا كانت السلسلة المشفرة بـ base64 المحددة خط OTF صالحًا |
|
|  | [getType()](#getType--) | يرجع |
FontType.Otf
([FontType.getOtf](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype#getOtf))
|
### OtfFont(String name, String contentInBase64) {#OtfFont-java.lang.String-java.lang.String-}
```
public OtfFont(String name, String contentInBase64)
```


ينشئ فئة OtfFont جديدة من المحتوى، الممثل كـ base64
سلسلة، ومع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم خط OTF. لا يمكن أن يكون فارغًا أو null أو يحتوي على مسافات فقط. |
|
|  | contentInBase64 | java.lang.String | المحتوى كسلسلة مشفرة بـ base64. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات فقط. إذا لم يكن محتوى OTF، سيتم رمي استثناء. |
|

### OtfFont(String name, InputStream binaryContent) {#OtfFont-java.lang.String-java.io.InputStream-}
```
public OtfFont(String name, InputStream binaryContent)
```


ينشئ فئة OtfFont جديدة من المحتوى، الممثل كتيار بايت، و
بالاسم المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم خط OTF. لا يمكن أن يكون فارغًا أو null أو يحتوي على مسافات فقط. |
|
|  | binaryContent | java.io.InputStream | المحتوى كتيار بايت. يبدأ القراءة من الموضع الأصلي. لا يمكن أن يكون فارغًا. يجب أن يكون قابلًا للقراءة والتمرير. إذا تم تحرير هذه الحالة، سيتم تحرير هذا التيار أيضًا. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


حجم رأس OTF (بالبايت)، وهو مطلوب للتحقق من صحته


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


يتحقق مما إذا كان التيار المحدد خط OTF صالحًا


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | تيار بايت، من المفترض أنه يحتوي على مورد OTF |
|

**Returns:**
منطقي - True إذا كان التيار المحدد يحتوي على خط OTF صالح، وإلا false

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


يتحقق مما إذا كانت السلسلة المشفرة بـ base64 المحددة خط OTF صالحًا


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | محتوى خط OTF المفترض على شكل سلسلة مشفرة بـ base64 |
|

**Returns:**
منطقي - True إذا كانت السلسلة المحددة تحتوي على خط OTF صالح، وإلا false

### getType() {#getType--}
```
public FontType getType()
```


يرجع
FontType.Otf
([FontType.getOtf](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype#getOtf))


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype) - 
