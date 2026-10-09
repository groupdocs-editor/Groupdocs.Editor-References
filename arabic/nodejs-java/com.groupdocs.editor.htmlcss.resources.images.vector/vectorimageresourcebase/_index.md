---
title: "VectorImageResourceBase"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "الفئة الأساسية لأي صورة متجهية مدعومة."
type: docs
weight: 13
url: /ar/nodejs-java/com.groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.images.IImageResource](../../com.groupdocs.editor.htmlcss.resources.images/iimageresource)
```
public abstract class VectorImageResourceBase implements IImageResource
```

الفئة الأساسية لأي صورة متجهية مدعومة.

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [VectorImageResourceBase()](#VectorImageResourceBase--) |  |
## الحقول

| حقل | الوصف |
| --- | --- |
| [Disposed](#Disposed) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getName()](#getName--) | يعيد اسم هذه الصورة المتجهة. |
|
|  | [getFilenameWithExtension()](#getFilenameWithExtension--) | يعيد اسم الملف الصحيح لهذه الصورة المتجهة، والذي يتكون من الاسم و |
الامتداد.
|
|  | [getAspectRatio()](#getAspectRatio--) | يعيد نسبة العرض إلى الارتفاع لهذه الصورة المتجهة |
|
|  | [getLinearDimensions()](#getLinearDimensions--) | يعيد الأبعاد الخطية لهذه الصورة المتجهة (العرض والارتفاع) |
|
|  | [equals(IHtmlResource other)](#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-) | يتحقق من هذه الحالة مع المحدد على مساواة المرجع. |
|
|  | [isDisposed()](#isDisposed--) | يحدد ما إذا كانت صورة النقطية هذه مُحررة أم لا |
|
|  | [getType()](#getType--) | في التنفيذ يجب أن يُعيد النوع معلومات حول نوع الصورة المتجهة |
صورة
|
|  | [getByteContent()](#getByteContent--) | في التنفيذ يجب أن يُعيد النوع محتوى هذه الصورة المتجهة كبايت |
تدفق
|
|  | [getTextContent()](#getTextContent--) | في التنفيذ يجب أن يُعيد النوع محتوى هذه الصورة المتجهة كنص |
النموذج: مشفر بقاعدة64 من XML يتعلق بنوع الصورة
|
|  | [save(String fullPathToFile)](#save-java.lang.String-) | في التنفيذ يجب أن يقوم النوع بحفظ هذه الصورة إلى القرص بالمسار المحدد |
|
|  | [saveToPng(OutputStream outputPngContent)](#saveToPng-java.io.OutputStream-) | في التنفيذ يجب أن يقوم النوع بحفظ الصورة المتجهة الحالية إلى PNG نقطي |
تنسيق إلى تدفق بايت محدد
|
|  | [dispose()](#dispose--) | في التنفيذ يجب أن يقوم النوع بتحرير هذه المثيلة |
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


يعيد اسم هذه الصورة المتجهة. عادةً لا يحتوي على اسم الملف
الامتداد ونظريًا يمكن أن يختلف عن اسم الملف.


**Returns:**
java.lang.String
### getFilenameWithExtension() {#getFilenameWithExtension--}
```
public final String getFilenameWithExtension()
```


يعيد اسم الملف الصحيح لهذه الصورة المتجهة، والذي يتكون من الاسم و
الامتداد. نظريًا يمكن أن يختلف عن الاسم.


**Returns:**
java.lang.String
### getAspectRatio() {#getAspectRatio--}
```
public final Ratio getAspectRatio()
```


يعيد نسبة العرض إلى الارتفاع لهذه الصورة المتجهة


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio)
### getLinearDimensions() {#getLinearDimensions--}
```
public final Dimensions getLinearDimensions()
```


يعيد الأبعاد الخطية لهذه الصورة المتجهة (العرض والارتفاع)


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions)
### equals(IHtmlResource other) {#equals-com.groupdocs.editor.htmlcss.resources.IHtmlResource-}
```
public final boolean equals(IHtmlResource other)
```


يتحقق من هذه الحالة مع المحدد على مساواة المرجع.


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


يحدد ما إذا كانت صورة النقطية هذه مُحررة أم لا


**Returns:**
منطقي -
### getType() {#getType--}
```
public abstract ImageType getType()
```


في التنفيذ يجب أن يُعيد النوع معلومات حول نوع الصورة المتجهة
صورة


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype) - 
### getByteContent() {#getByteContent--}
```
public InputStream getByteContent()
```


في التنفيذ يجب أن يُعيد النوع محتوى هذه الصورة المتجهة كبايت
تدفق


**Returns:**
java.io.InputStream -
### getTextContent() {#getTextContent--}
```
public abstract String getTextContent()
```


في التنفيذ يجب أن يُعيد النوع محتوى هذه الصورة المتجهة كنص
النموذج: مشفر بقاعدة64 من XML يتعلق بنوع الصورة


**Returns:**
java.lang.String -
### save(String fullPathToFile) {#save-java.lang.String-}
```
public abstract void save(String fullPathToFile)
```


في التنفيذ يجب أن يقوم النوع بحفظ هذه الصورة إلى القرص بالمسار المحدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fullPathToFile | java.lang.String |  |

### saveToPng(OutputStream outputPngContent) {#saveToPng-java.io.OutputStream-}
```
public abstract void saveToPng(OutputStream outputPngContent)
```


في التنفيذ يجب أن يقوم النوع بحفظ الصورة المتجهة الحالية إلى PNG نقطي
تنسيق إلى تدفق بايت محدد


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | outputPngContent | java.io.OutputStream | تيار بايت، يُخزن فيه نسخة PNG من هذه الصورة النقطية. يجب ألا يكون NULL ويجب أن يدعم الكتابة. |
|

### dispose() {#dispose--}
```
public abstract void dispose()
```


في التنفيذ يجب أن يقوم النوع بتحرير هذه المثيلة


