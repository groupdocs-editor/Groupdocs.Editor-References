---
title: "IImageResource"
second_title: "GroupDocs.Editor Node.js için Java API Referansı"
description: "Herhangi bir tür raster veya vektör olan görüntü kaynağını temsil eder"
type: docs
weight: 13
url: /tr/nodejs-java/com.groupdocs.editor.htmlcss.resources.images/iimageresource/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource), [com.groupdocs.editor.htmlcss.resources.images.IImage](../../com.groupdocs.editor.htmlcss.resources.images/iimage)
```
public interface IImageResource extends IHtmlResource, IImage
```

Herhangi bir türdeki, raster veya vektör, görüntü kaynağını temsil eder.


*** ** * ** ***

https://developer.mozilla.org/en-US/docs/Web/CSS/image

<br />


## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getType()](#getType--) | Uygulamada, tür belirli bir görüntünün tipini bir |
belirli ImageType örneği, tüm tür‑özel bilgileri kapsar
|
|  | [getAspectRatio()](#getAspectRatio--) | Uygulamada, tür belirli bir görüntünün en‑boy oranını döndürmelidir |
türünden bağımsız olarak.
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Uygulamada, tür görüntünün doğrusal boyutlarını döndürmelidir. |
|
### getType() {#getType--}
```
public abstract ImageType getType()
```


Uygulamada, tür belirli bir görüntünün tipini bir
belirli ImageType örneği, tüm tür‑özel bilgileri kapsar


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getAspectRatio() {#getAspectRatio--}
```
public abstract Ratio getAspectRatio()
```


Uygulamada, tür belirli bir görüntünün en‑boy oranını döndürmelidir
türünden bağımsız olarak. Hem vektör hem raster görüntüler doğal olarak
genişlik ve yükseklik arasındaki en‑boy oranına sahiptir.


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - 
### getLinearDimensions() {#getLinearDimensions--}
```
public abstract Dimensions getLinearDimensions()
```


Uygulamada, tür görüntünün doğrusal boyutlarını döndürmelidir. İçin
raster görüntülerde bunlar piksel cinsinden doğal boyutlardır. Vektör görüntülerde ise
tersine, sabit boyutları yoktur, ancak meta verileri şunları içerebilir
farklı ölçü birimlerindeki bazı temel boyutları.


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - 
