---
title: "TtcFont"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يمثل خطًا واحدًا في تنسيق مجموعة TrueType TTC"
type: docs
weight: 14
url: /ar/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/ttcfont/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
```
public final class TtcFont extends FontResourceBase
```

يمثل خطًا واحدًا بتنسيق TTC (TrueType Collection).


المزيد: https://docs.fileformat.com/font/ttc/

## المنشئات

| المنشئ | الوصف |
| --- | --- |
|  | [TtcFont(String name, String contentInBase64)](#TtcFont-java.lang.String-java.lang.String-) | ينشئ فئة TtcFont جديدة من المحتوى، الممثَّل كقيمة base64 |
سلسلة، ومع اسم محدد
|
|  | [TtcFont(String name, InputStream binaryContent)](#TtcFont-java.lang.String-java.io.InputStream-) | ينشئ فئة TtcFont جديدة من المحتوى، الممثَّل كتيار بايت، و |
مع اسم محدد
|
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [RequiredHeaderSize](#RequiredHeaderSize) | حجم رأس TTC (بالبايت)، وهو مطلوب للتحقق من صلاحيته |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isValid(InputStream binaryContent)](#isValid-java.io.InputStream-) | يتحقق مما إذا كان التيار المحدد خط TTC صالحًا |
|
|  | [isValid(String contentInBase64)](#isValid-java.lang.String-) | يتحقق مما إذا كانت السلسلة المشفرة بـ base64 المحددة خط TTC صالح |
|
|  | [getType()](#getType--) | يرجع FontType.Ttc |
|
|  | [getHeaderVersion()](#getHeaderVersion--) | إصدار رأس TTC، قد يكون "1" أو "2" |
|
|  | [getFontsNumber()](#getFontsNumber--) | عدد الخطوط في هذا TTC |
|
|  | [getHasDsigTable()](#getHasDsigTable--) | يشير إلى ما إذا كان هذا TTC يحتوي على جدول DSIG. |
|
### TtcFont(String name, String contentInBase64) {#TtcFont-java.lang.String-java.lang.String-}
```
public TtcFont(String name, String contentInBase64)
```


ينشئ فئة TtcFont جديدة من المحتوى، الممثَّل كقيمة base64
سلسلة، ومع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم خط TTC. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات. |
|
|  | contentInBase64 | java.lang.String | المحتوى كسلسلة مشفرة بـ base64. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات. إذا لم يكن محتوى TTC، سيتم رمي استثناء. |
|

### TtcFont(String name, InputStream binaryContent) {#TtcFont-java.lang.String-java.io.InputStream-}
```
public TtcFont(String name, InputStream binaryContent)
```


ينشئ فئة TtcFont جديدة من المحتوى، الممثَّل كتيار بايت، و
مع اسم محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | اسم خط TTC. لا يمكن أن يكون null أو فارغًا أو يحتوي على مسافات. |
|
|  | binaryContent | java.io.InputStream | المحتوى كتيار بايت. يبدأ القراءة من الموضع الأصلي. لا يمكن أن يكون null. يجب أن يكون قابلًا للقراءة والتمرير. إذا تم تحرير هذه الحالة، سيتم تحرير هذا التيار أيضًا. |
|

### RequiredHeaderSize {#RequiredHeaderSize}
```
public static final int RequiredHeaderSize
```


حجم رأس TTC (بالبايت)، وهو مطلوب للتحقق من صلاحيته


### isValid(InputStream binaryContent) {#isValid-java.io.InputStream-}
```
public static boolean isValid(InputStream binaryContent)
```


يتحقق مما إذا كان التيار المحدد خط TTC صالحًا


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | binaryContent | java.io.InputStream | تيار بايت، من المفترض أنه يحتوي على مورد TTC |
|

**Returns:**
منطقي - صحيح إذا كان الدفق المحدد يحتوي على خط TTC صالح، وإلا خطأ

### isValid(String contentInBase64) {#isValid-java.lang.String-}
```
public static boolean isValid(String contentInBase64)
```


يتحقق مما إذا كانت السلسلة المشفرة بـ base64 المحددة خط TTC صالح


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | contentInBase64 | java.lang.String | محتوى خط TTC المفترض على شكل سلسلة مشفرة بقاعدة 64 |
|

**Returns:**
منطقي - صحيح إذا كانت السلسلة المحددة تحتوي على خط TTC صالح، وإلا خطأ

### getType() {#getType--}
```
public FontType getType()
```


يرجع FontType.Ttc


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
### getHeaderVersion() {#getHeaderVersion--}
```
public byte getHeaderVersion()
```


إصدار رأس TTC، قد يكون "1" أو "2"


**Returns:**
byte
### getFontsNumber() {#getFontsNumber--}
```
public long getFontsNumber()
```


عدد الخطوط في هذا TTC


**Returns:**
long
### getHasDsigTable() {#getHasDsigTable--}
```
public boolean getHasDsigTable()
```


يشير إلى ما إذا كان هذا TTC يحتوي على جدول DSIG. قد يكون جدول DSIG موجودًا
فقط إذا كان TTC يحتوي على Header الإصدار 2.0.


**Returns:**
boolean
