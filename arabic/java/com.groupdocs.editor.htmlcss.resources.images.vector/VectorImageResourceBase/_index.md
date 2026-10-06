---
title: "VectorImageResourceBase"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "الفئة الأساسية لأي صورة متجهة مدعومة"
type: docs
weight: 13
url: /ar/java/com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class VectorImageResourceBase implements IImageResource
```

الفئة الأساسية لأي صورة متجهة مدعومة

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [VectorImageResourceBase()](#VectorImageResourceBase--) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
| [Disposed](#Disposed) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getName()](#getName--) | يرجع اسم هذه الصورة المتجهة. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | يرجع اسم الملف الصحيح لهذه الصورة المتجهة، والذي يتكون من الاسم و |
الامتداد.
|
|  | [getAspectRatio()](#getAspectRatio--) | يرجع نسبة العرض إلى الارتفاع لهذه الصورة المتجهة |
|
|  | [getLinearDimensions()](#getLinearDimensions--) | يرجع الأبعاد الخطية لهذه الصورة المتجهة (العرض والارتفاع) |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | يتحقق من مساواة المرجع لهذا الكائن مع المحدد. |
|
|  | [isDisposed()](#isDisposed--) | يحدد ما إذا كانت صورة الراستر هذه مُتَخلّص منها أم لا |
|
|  | [getType()](#getType--) | في النوع المنفذ يجب أن يُعيد معلومات حول نوع المتجه |
صورة
|
|  | [getByteContent()](#getByteContent--) | في النوع المنفذ يجب أن يُعيد محتوى هذه الصورة المتجهة كبايت |
دفق
|
|  | [getTextContent()](#getTextContent--) | في النوع المنفذ يجب أن يُعيد محتوى هذه الصورة المتجهة كنص |
النموذج: مشفر بقاعدة64 من XML بخصوص نوع الصورة
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | في النوع المنفذ يجب أن يحفظ هذه الصورة على القرص بالمسار المحدد |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | في النوع المنفذ يجب أن يحفظ الصورة المتجهة الحالية إلى PNG النقطي |
تنسيق إلى دفق البايت المحدد
|
|  | [dispose()](#dispose--) | في النوع المنفذ يجب أن يحرّر هذه المثيل |
|
### VectorImageResourceBase() {#VectorImageResourceBase--}
```
public VectorImageResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


يرجع اسم هذه الصورة المتجهة. عادةً لا يحتوي على اسم ملف
الامتداد وقد يختلف نظريًا عن اسم الملف.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


يرجع اسم الملف الصحيح لهذه الصورة المتجهة، والذي يتكون من الاسم و
الامتداد. قد يختلف نظريًا عن الاسم.


**Returns:**
java.lang.String
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


يرجع نسبة العرض إلى الارتفاع لهذه الصورة المتجهة


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


يرجع الأبعاد الخطية لهذه الصورة المتجهة (العرض والارتفاع)


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


يتحقق من مساواة المرجع لهذا الكائن مع المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | مثيل آخر من الصورة المتجهة |
|

**Returns:**
منطقي - True إذا كانا متساويين، false إذا كانا غير متساويين

### isDisposed() {#isDisposed--}
```
public final boolean isDisposed()
```


يحدد ما إذا كانت صورة الراستر هذه مُتَخلّص منها أم لا


**Returns:**
boolean -
### getType() {#getType--}
```
public abstract ImageType getType()
```


في النوع المنفذ يجب أن يُعيد معلومات حول نوع المتجه
صورة


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


في النوع المنفذ يجب أن يُعيد محتوى هذه الصورة المتجهة كبايت
دفق


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


في النوع المنفذ يجب أن يُعيد محتوى هذه الصورة المتجهة كنص
النموذج: مشفر بقاعدة64 من XML بخصوص نوع الصورة


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


في النوع المنفذ يجب أن يحفظ هذه الصورة على القرص بالمسار المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fullPathToFile | java.lang.String |  |

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public abstract void saveToPng(OutputStream outputPngContent)
```


في النوع المنفذ يجب أن يحفظ الصورة المتجهة الحالية إلى PNG النقطي
تنسيق إلى دفق البايت المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | دفق البايت، الذي سيتم تخزين نسخة PNG من هذه الصورة النقطية فيه. لا يجب أن يكون NULL ويجب أن يدعم الكتابة. |
|

### dispose() {#dispose--}
```
public abstract void dispose()
```


في النوع المنفذ يجب أن يحرّر هذه المثيل


