---
title: "IImageResource"
second_title: "GroupDocs.Editor для Node.js через Java API Reference"
description: "Представляет ресурс изображения любого типа: растровый или векторный"
type: docs
weight: 13
url: /ru/nodejs-java/com.groupdocs.editor.htmlcss.resources.images/iimageresource/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource), [com.groupdocs.editor.htmlcss.resources.images.IImage](../../com.groupdocs.editor.htmlcss.resources.images/iimage)
```
public interface IImageResource extends IHtmlResource, IImage
```

Представляет ресурс изображения любого типа, растровый или векторный.


*** ** * ** ***

https://developer.mozilla.org/en-US/docs/Web/CSS/image

<br />


## Методы

| Метод | Описание |
| --- | --- |
|  | [getType()](#getType--) | При реализации тип должен возвращать тип конкретного изображения как |
экземпляр конкретного ImageType, который инкапсулирует всю типо-специфичную информацию
|
|  | [getAspectRatio()](#getAspectRatio--) | При реализации тип должен возвращать соотношение сторон конкретного изображения |
независимо от его типа.
|
|  | [getLinearDimensions()](#getLinearDimensions--) | При реализации тип должен возвращать линейные размеры изображения. |
|
### getType() {#getType--}
```
public abstract ImageType getType()
```


При реализации тип должен возвращать тип конкретного изображения как
экземпляр конкретного ImageType, который инкапсулирует всю типо-специфичную информацию


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getAspectRatio() {#getAspectRatio--}
```
public abstract Ratio getAspectRatio()
```


При реализации тип должен возвращать соотношение сторон конкретного изображения
независимо от его типа. Как векторные, так и растровые изображения имеют внутреннее
соотношение сторон между шириной и высотой.


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - 
### getLinearDimensions() {#getLinearDimensions--}
```
public abstract Dimensions getLinearDimensions()
```


При реализации тип должен возвращать линейные размеры изображения. Для
растровых изображений это внутренние размеры в пикселях. Векторные изображения, в
противоположность, не имеют фиксированных размеров, но их метаданные могут содержать
некоторые базовые размеры в разных единицах измерения.


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - 
