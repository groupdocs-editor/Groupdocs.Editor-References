---
title: "TextResourceBase"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "الفئة الأساسية لأي مورد نصي مدعوم يحتوي على محتوى نصي وترميز."
type: docs
weight: 11
url: /ar/java/com.groupdocs.editor.htmlcss.resources.textual/textresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class TextResourceBase implements IHtmlResource
```

الفئة الأساسية لأي مورد نصي مدعوم يحتوي على محتوى نصي وترميز.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [TextResourceBase(String name, String textualContent, Charset originalEncoding)](#TextResourceBase-java.lang.String-java.lang.String-java.nio.charset.Charset-) | ينشئ مورد نصي جديد من المحتوى النصي المحدد مع الترميز |
|
|  | [TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)](#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-) | ينشئ مورد نصي جديد من تدفق البايت المحدد مع الترميز |
|
## الحقول

| حقل | الوصف |
| --- | --- |
| [Disposed](#Disposed) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getName()](#getName--) | يرجع اسم هذا المورد النصي بدون امتداد الملف |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | يرجع اسم الملف الصحيح لهذا المورد النصي، والذي يتكون من الاسم |
والامتداد
|
|  | [getEncoding()](#getEncoding--) | يرجع ترميز هذا المورد النصي. |
|
|  | [getByteContent()](#getByteContent--) | يرجع محتوى هذا المورد النصي كتيار بايت مع الأصلي |
الترميز
|
|  | [getTextContent()](#getTextContent--) | يعيد محتوى هذا المورد النصي كسلسلة قياسية |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | يحفظ هذا المورد النصي إلى الملف المحدد |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | يفحص هذه الحالة مع المحدد للمساواة. |
|
|  | [dispose()](#dispose--) | يتخلص من هذا المورد النصي، متخلصًا من محتواه ويجعل معظم |
الطرق والخصائص غير عاملة.
|
|  | [isDisposed()](#isDisposed--) | يحدد ما إذا كان هذا المورد النصي قد تم التخلص منه أم لا |
|
|  | [getType()](#getType--) | في تنفيذ النوع يجب إرجاع معلومات حول نوع النص |
المورد
|
### TextResourceBase(String name, String textualContent, Charset originalEncoding) {#TextResourceBase-java.lang.String-java.lang.String-java.nio.charset.Charset-}
```
public TextResourceBase(String name, String textualContent, Charset originalEncoding)
```


ينشئ مورد نصي جديد من المحتوى النصي المحدد مع الترميز


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | الاسم الإلزامي للمورد، الذي يعمل كمعرف فريد له. عادةً يكون اسم ملف. |
|
|  | المحتوى النصي | java.lang.String | المحتوى النصي للمورد، لا يمكن أن يكون NULL أو فارغًا |
|
|  | الترميز الأصلي | java.nio.charset.Charset | الترميز الأصلي للمورد، لا يمكن أن يكون NULL أو فارغًا |
|

### TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding) {#TextResourceBase-java.lang.String-java.io.InputStream-java.nio.charset.Charset-}
```
public TextResourceBase(String name, InputStream binaryContent, Charset originalEncoding)
```


ينشئ مورد نصي جديد من تدفق البايت المحدد مع الترميز


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | الاسم | java.lang.String | الاسم الإلزامي للمورد، الذي يعمل كمعرف فريد له. عادةً يكون اسم ملف. |
|
|  | binaryContent | java.io.InputStream | المحتوى الثنائي للمورد كتيار بايت. لا يمكن أن يكون NULL، أو مُتخلص منه، ويجب أن يكون قابلاً للقراءة والتمرير. |
|
|  | الترميز الأصلي | java.nio.charset.Charset | الترميز الأصلي للمورد، لا يمكن أن يكون NULL أو فارغًا |
|

### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


يرجع اسم هذا المورد النصي بدون امتداد الملف


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


يرجع اسم الملف الصحيح لهذا المورد النصي، والذي يتكون من الاسم
والامتداد


**Returns:**
java.lang.String
### getEncoding() {#getEncoding--}
```
public final Charset getEncoding()
```


يعيد الترميز لهذا المورد النصي. عادةً يعيد UTF-8.


**Returns:**
java.nio.charset.Charset -
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


يرجع محتوى هذا المورد النصي كتيار بايت مع الأصلي
الترميز


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


يعيد محتوى هذا المورد النصي كسلسلة قياسية


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


يحفظ هذا المورد النصي إلى الملف المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | المسار الكامل للملف، الذي سيتم إنشاؤه أو إعادة كتابته إذا كان موجودًا بالفعل |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


يفحص هذه الحالة مع المحدد للمساواة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | مورد HTML آخر من نوع غير معروف، والذي يُفترض أيضًا أنه من ورثة TextResourceBase |
|

**Returns:**
boolean - يعيد true إذا كانا متساويين، أو false إذا كانا غير متساويين

### dispose() {#dispose--}
```
public final void dispose()
```


يتخلص من هذا المورد النصي، متخلصًا من محتواه ويجعل معظم
الطرق والخصائص غير عاملة. متسامح مع الاستدعاءات المتعددة.


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


يحدد ما إذا كان هذا المورد النصي قد تم التخلص منه أم لا


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract TextType getType()
```


في تنفيذ النوع يجب إرجاع معلومات حول نوع النص
المورد


**Returns:**
[TextType](../../com.groupdocs.editor.htmlcss.resources.textual/texttype)
