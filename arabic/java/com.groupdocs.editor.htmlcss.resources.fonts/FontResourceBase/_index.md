---
title: "FontResourceBase"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "الفئة الأساسية لأي نوع خط مدعوم كمورد لوثيقة HTML مع جميع خصائصه."
type: docs
weight: 11
url: /ar/java/com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class FontResourceBase implements IHtmlResource
```

الفئة الأساسية لأي نوع خط مدعوم كمورد لوثيقة HTML.
مع جميع خصائصه.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [FontResourceBase()](#FontResourceBase--) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Disposed](#Disposed) | حدث يحدث عندما يتم التخلص من هذا الخط. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getName()](#getName--) | يرجع اسم مورد هذا الخط. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | يرجع اسم الملف الصحيح لمورد هذا الخط، الذي يتكون من الاسم |
والامتداد.
|
|  | [getByteContent()](#getByteContent--) | يرجع محتوى هذا الخط كتيار بايت |
|
|  | [getTextContent()](#getTextContent--) | يرجع محتوى هذا الخط كسلسلة مشفّرة base64. |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | يحفظ هذا الخط إلى الملف المحدد. |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | يتحقق من هذا المثيل مع المورد HTML المحدد على مساواة المرجع |
|
|  | [equals(FontResourceBase other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-) | يتحقق من هذا المثيل مع مورد الخط المحدد على مساواة المرجع |
|
|  | [dispose()](#dispose--) | يتخلص من مورد هذا الخط، متخلصًا من محتواه وجاعلاً معظم |
الطرق والخصائص غير عاملة
|
|  | [isDisposed()](#isDisposed--) | يحدد ما إذا كان هذا الخط قد تم التخلص منه أم لا. |
|
|  | [getType()](#getType--) | في النوع المنفذ يجب أن يُعيد معلومات حول نوع معين |
مورد الخط ككائن من نوع FontType المحدد، الذي
يحتوي على جميع المعلومات الخاصة بالنوع.
|
### FontResourceBase() {#FontResourceBase--}
```
public FontResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


حدث يحدث عندما يتم التخلص من هذا الخط.


### getName() {#getName--}
```
public final String getName()
```


يرجع اسم مورد هذا الخط. عادةً لا يحتوي على اسم الملف
الامتداد وقد يختلف نظريًا عن اسم الملف.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


يرجع اسم الملف الصحيح لمورد هذا الخط، الذي يتكون من الاسم
والامتداد. نظريًا قد يختلف عن الاسم.


**Returns:**
java.lang.String
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


يرجع محتوى هذا الخط كتيار بايت


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


يرجع محتوى هذا الخط كسلسلة مشفّرة base64. هذه القيمة هي
مخزنة مؤقتًا بعد الاستدعاء الأول.


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


يحفظ هذا الخط إلى الملف المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | المسار الكامل للملف، الذي سيتم إنشاؤه أو إعادة كتابته |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


يتحقق من هذا المثيل مع المورد HTML المحدد على مساواة المرجع


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | مُورّث آخر لواجهة IHtmlResource |
|

**Returns:**
منطقي - True إذا كانا متساويين، false إذا كانا غير متساويين

### equals(FontResourceBase other) {#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-}
```
public final boolean equals(FontResourceBase other)
```


يتحقق من هذا المثيل مع مورد الخط المحدد على مساواة المرجع


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase) | المُوروث الآخر لفئة FontResourceBase المجردة |
|

**Returns:**
منطقي - True إذا كانا متساويين، false إذا كانا غير متساويين

### dispose() {#dispose--}
```
public final void dispose()
```


يتخلص من مورد هذا الخط، متخلصًا من محتواه وجاعلاً معظم
الطرق والخصائص غير عاملة


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


يحدد ما إذا كان هذا الخط قد تم التخلص منه أم لا.


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract FontType getType()
```


في النوع المنفذ يجب أن يُعيد معلومات حول نوع معين
مورد الخط ككائن من نوع FontType المحدد، الذي
يحتوي على جميع المعلومات الخاصة بالنوع.


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
