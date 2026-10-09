---
title: "IImageResource"
second_title: "مرجع API لـ GroupDocs.Editor لـ Node.js عبر Java"
description: "يمثل مورد صورة من أي نوع، نقطي أو متجه"
type: docs
weight: 13
url: /ar/nodejs-java/com.groupdocs.editor.htmlcss.resources.images/iimageresource/
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
|  | [getType()](#getType--) | عند التنفيذ، يجب أن يُعيد النوع نوع صورة محددة كـ |
مثال من ImageType المحدد، الذي يضم جميع المعلومات الخاصة بالنوع
|
|  | [getAspectRatio()](#getAspectRatio--) | عند التنفيذ، يجب أن يُعيد النوع نسبة العرض إلى الارتفاع لصورة معينة |
بغض النظر عن نوعها.
|
|  | [getLinearDimensions()](#getLinearDimensions--) | عند التنفيذ، يجب أن يُعيد النوع الأبعاد الخطية للصورة. |
|
### getType() {#getType--}
```
public abstract ImageType getType()
```


عند التنفيذ، يجب أن يُعيد النوع نوع صورة محددة كـ
مثال من ImageType المحدد، الذي يضم جميع المعلومات الخاصة بالنوع


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getAspectRatio() {#getAspectRatio--}
```
public abstract Ratio getAspectRatio()
```


عند التنفيذ، يجب أن يُعيد النوع نسبة العرض إلى الارتفاع لصورة معينة
بغض النظر عن نوعها. كل من الصور المتجهة والنقطية لديها
نسبة عرض إلى ارتفاع بين عرضها وارتفاعها.


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - 
### getLinearDimensions() {#getLinearDimensions--}
```
public abstract Dimensions getLinearDimensions()
```


عند التنفيذ، يجب أن يُعيد النوع الأبعاد الخطية للصورة. بالنسبة لـ
الصور النقطية، تكون الأبعاد داخلية بوحدات البكسل. الصور المتجهة، في
المقابل، لا تملك أبعادًا ثابتة، لكن بياناتها الوصفية يمكن أن تحتوي على
بعض الأبعاد الأساسية بوحدات قياس مختلفة.


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - 
