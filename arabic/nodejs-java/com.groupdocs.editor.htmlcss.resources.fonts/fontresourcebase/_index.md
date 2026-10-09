---
title: "FontResourceBase"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "الفئة الأساسية لأي نوع خط مدعوم كموارد لمستند HTML مع جميع خصائصه"
type: docs
weight: 11
url: /ar/nodejs-java/com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource)
```
public abstract class FontResourceBase implements IHtmlResource
```

الفئة الأساسية لأي نوع خط مدعوم كموارد لمستند HTML
مع جميع خصائصه

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [FontResourceBase()](#FontResourceBase--) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Disposed](#Disposed) | الحدث، الذي يحدث عندما يتم التخلص من هذا الخط |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getName()](#getName--) | يعيد اسم مورد الخط هذا. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | يعيد اسم الملف الصحيح لمورد الخط هذا، والذي يتكون من الاسم |
والامتداد.
|
|  | [getByteContent()](#getByteContent--) | إرجاع محتوى هذا الخط كتيار بايت |
|
|  | [getTextContent()](#getTextContent--) | يعيد محتوى هذا الخط كسلسلة مشفرة بقاعدة 64. |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | يحفظ هذا الخط إلى الملف المحدد |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | يفحص هذه الحالة مع المورد HTML المحدد على مساواة المرجع |
|
|  | [equals(FontResourceBase other)](#equals-com.groupdocs.editor.htmlcss.resources.fonts.FontResourceBase-) | يفحص هذه الحالة مع مورد الخط المحدد على مساواة المرجع |
|
|  | [dispose()](#dispose--) | يتخلص من مورد الخط هذا، ويزيل محتواه ويجعل معظم |
الطرق والخصائص غير عاملة
|
|  | [isDisposed()](#isDisposed--) | يحدد ما إذا كان هذا الخط قد تم التخلص منه أم لا |
|
|  | [getType()](#getType--) | في النوع المنفذ يجب أن يعيد معلومات حول نوع محدد |
مورد الخط ككائن من نوع FontType المحدد، والذي
يحتوي على جميع المعلومات الخاصة بالنوع
|
### FontResourceBase() {#FontResourceBase--}
```
public FontResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


الحدث، الذي يحدث عندما يتم التخلص من هذا الخط


### getName() {#getName--}
```
public final String getName()
```


يعيد اسم مورد الخط هذا. عادةً لا يحتوي على اسم الملف
الامتداد ونظريًا يمكن أن يختلف عن اسم الملف.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


يعيد اسم الملف الصحيح لمورد الخط هذا، والذي يتكون من الاسم
والامتداد. نظريًا قد يختلف عن الاسم.


**Returns:**
java.lang.String
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


إرجاع محتوى هذا الخط كتيار بايت


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


يعيد محتوى هذا الخط كسلسلة مشفرة بقاعدة 64. هذه القيمة هي
مخزنة مؤقتًا بعد الاستدعاء الأول.


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


يحفظ هذا الخط إلى الملف المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | المسار الكامل للملف، الذي سيتم إنشاؤه أو إعادة كتابته |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


يفحص هذه الحالة مع المورد HTML المحدد على مساواة المرجع


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


يفحص هذه الحالة مع مورد الخط المحدد على مساواة المرجع


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [FontResourceBase](../../com.groupdocs.editor.htmlcss.resources.fonts/fontresourcebase) | مُورّث آخر للفئة المجردة FontResourceBase |
|

**Returns:**
منطقي - True إذا كانا متساويين، false إذا كانا غير متساويين

### dispose() {#dispose--}
```
public final void dispose()
```


يتخلص من مورد الخط هذا، ويزيل محتواه ويجعل معظم
الطرق والخصائص غير عاملة


### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


يحدد ما إذا كان هذا الخط قد تم التخلص منه أم لا


**Returns:**
منطقي -
### getType() {#getType--}
```
public abstract FontType getType()
```


في النوع المنفذ يجب أن يعيد معلومات حول نوع محدد
مورد الخط ككائن من نوع FontType المحدد، والذي
يحتوي على جميع المعلومات الخاصة بالنوع


**Returns:**
[FontType](../../com.groupdocs.editor.htmlcss.resources.fonts/fonttype)
