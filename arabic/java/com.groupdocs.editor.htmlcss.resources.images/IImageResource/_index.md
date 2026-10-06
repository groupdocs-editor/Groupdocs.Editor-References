---
title: "IImageResource"
second_title: "مرجع API لـ GroupDocs.Editor لجافا"
description: "يمثل مورد صورة من أي نوع، نقطي أو متجه"
type: docs
weight: 13
url: /ar/java/com.groupdocs.editor.htmlcss.resources.images/iimageresource/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource), [com.groupdocs.editor.htmlcss.resources.images.IImage](../../com.groupdocs.editor.htmlcss.resources.images/iimage)
```
public interface IImageResource extends IHtmlResource, IImage
```

يمثل مورد صورة من أي نوع، نقطية أو متجهة.


*** ** * ** ***

https://developer.mozilla.org/en-US/docs/Web/CSS/image

<br />


## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getType()](#getType--) | في التنفيذ يجب أن تُعيد النوع نوع صورة محددة كـ |
مثيل من ImageType المحدد، الذي يضم جميع المعلومات الخاصة بالنوع
|
|  | [getAspectRatio()](#getAspectRatio--) | في التنفيذ يجب أن تُعيد النوع نسبة العرض إلى الارتفاع لصورة معينة |
بغض النظر عن نوعها.
|
|  | [getLinearDimensions()](#getLinearDimensions--) | في التنفيذ يجب أن تُعيد النوع أبعاد الصورة الخطية. |
|
### getType() {#getType--}
```
public abstract ImageType getType()
```


في التنفيذ يجب أن تُعيد النوع نوع صورة محددة كـ
مثيل من ImageType المحدد، الذي يضم جميع المعلومات الخاصة بالنوع


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getAspectRatio() {#getAspectRatio--}
```
public abstract Ratio getAspectRatio()
```


في التنفيذ يجب أن تُعيد النوع نسبة العرض إلى الارتفاع لصورة معينة
بغض النظر عن نوعها. كل من الصور المتجهة والنقطية لديها
نسبة عرض إلى ارتفاع داخلية بين عرضها وارتفاعها.


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - 
### getLinearDimensions() {#getLinearDimensions--}
```
public abstract Dimensions getLinearDimensions()
```


في التنفيذ يجب أن تُعيد النوع أبعاد الصورة الخطية. بالنسبة لـ
الصور النقطية، تكون الأبعاد داخلية بوحدات البكسل. الصور المتجهة، في
المقابل، لا تملك أبعادًا ثابتة، لكن بياناتها الوصفية يمكن أن تحتوي على
بعض الأبعاد الأساسية بوحدات قياس مختلفة.


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - 
