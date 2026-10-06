---
title: "RasterImageResourceBase"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "الفئة الأساسية لأي صورة نقطية مدعومة مع اسم ثابت، أبعاد، نسبة أبعاد، نوع، حجم ومحتوى."
type: docs
weight: 15
url: /ar/java/com.groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class RasterImageResourceBase implements IImageResource
```

الفئة الأساسية لأي صورة نقطية مدعومة مع اسم ثابت، أبعاد، نسبة
نسبة، نوع، حجم، ومحتوى.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [RasterImageResourceBase()](#RasterImageResourceBase--) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
| [Disposed](#Disposed) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getName()](#getName--) | يرجع اسم هذه الصورة النقطية. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | يرجع اسم الملف الصحيح لهذه الصورة النقطية، والذي يتكون من الاسم و |
الامتداد.
|
|  | [getLinearDimensions()](#getLinearDimensions--) | يرجع الأبعاد الخطية لهذه الصورة النقطية (العرض والارتفاع) |
|
|  | [getAspectRatio()](#getAspectRatio--) | يرجع نسبة الأبعاد لهذه الصورة كعلاقة العرض إلى الارتفاع |
|
|  | [getLength()](#getLength--) | يرجع طول ملف هذه الصورة النقطية بالبايت |
|
|  | [getByteContent()](#getByteContent--) | يرجع محتوى هذه الصورة النقطية كتيار بايت |
|
|  | [getTextContent()](#getTextContent--) | يرجع محتوى هذه الصورة النقطية كنص مشفر بـ base64 |
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | يحفظ هذه الصورة النقطية إلى الملف المحدد |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | يتحقق من مساواة المرجع لهذا الكائن مع المحدد. |
|
|  | [dispose()](#dispose--) | يحرّر هذه الصورة النقطية، مفرغًا محتواها وجاعلاً معظم الطرق |
وخصائص غير عاملة
|
|  | [isDisposed()](#isDisposed--) | يحدد ما إذا كانت صورة الراستر هذه مُتَخلّص منها أم لا |
|
|  | [getType()](#getType--) | في التنفيذ يجب أن يُعيد النوع معلومات حول نوع الراستر |
صورة
|
### RasterImageResourceBase() {#RasterImageResourceBase--}
```
public RasterImageResourceBase()
```


### Disposed {#Disposed}
```
public final Event<EventHandler> Disposed
```


### getName() {#getName--}
```
public final String getName()
```


يرجع اسم صورة الراستر هذه. عادةً لا يحتوي على اسم الملف
الامتداد وقد يختلف نظريًا عن اسم الملف.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


يرجع اسم الملف الصحيح لهذه الصورة النقطية، والذي يتكون من الاسم و
الامتداد. قد يختلف نظريًا عن الاسم.


**Returns:**
java.lang.String
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


يرجع الأبعاد الخطية لهذه الصورة النقطية (العرض والارتفاع)


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


يرجع نسبة الأبعاد لهذه الصورة كعلاقة العرض إلى الارتفاع


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLength() {#getLength--}
```
public final int getLength()
```


يرجع طول ملف هذه الصورة النقطية بالبايت


**Returns:**
int -
### getByteContent() {#getByteContent--}
```
public final InputStream getByteContent()
```


يرجع محتوى هذه الصورة النقطية كتيار بايت


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public final String getTextContent()
```


يرجع محتوى هذه الصورة النقطية كنص مشفر بـ base64


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public final void save(String fullPathToFile)
```


يحفظ هذه الصورة النقطية إلى الملف المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fullPathToFile | java.lang.String | المسار الكامل للملف، الذي سيتم إنشاؤه أو إعادة كتابته |
|

### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


يتحقق من مساواة المرجع لهذا الكائن مع المحدد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource) | مُورِّث آخر لـ IHtmlResource |
|

**Returns:**
منطقي - True إذا كانا متساويين، false إذا كانا غير متساويين

### dispose() {#dispose--}
```
public final void dispose()
```


يحرّر هذه الصورة النقطية، مفرغًا محتواها وجاعلاً معظم الطرق
وخصائص غير عاملة


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


في التنفيذ يجب أن يُعيد النوع معلومات حول نوع الراستر
صورة


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
