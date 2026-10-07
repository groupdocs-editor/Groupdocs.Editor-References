---
title: "IImageResource"
second_title: "GroupDocs.Editor Java için API Referansı"
description: "Herhangi bir raster veya vektör türündeki görüntü kaynağını temsil eder"
type: docs
weight: 13
url: /tr/java/com.groupdocs.editor.htmlcss.resources.images/iimageresource/
---
**All Implemented Interfaces:**
[com.groupdocs.editor.htmlcss.resources.IHtmlResource](../../com.groupdocs.editor.htmlcss.resources/ihtmlresource), [com.groupdocs.editor.htmlcss.resources.images.IImage](../../com.groupdocs.editor.htmlcss.resources.images/iimage)
```
public interface IImageResource extends IHtmlResource, IImage
```

Herhangi bir türdeki, raster veya vektör olan görüntü kaynağını temsil eder.


*** ** * ** ***

https://developer.mozilla.org/en-US/docs/Web/CSS/image

<br />


## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getType()](#getType--) | Uygulamada, belirli bir görüntünün türünü bir |
tüm tür‑özel bilgileri kapsayan belirli ImageType örneği
|
|  | [getAspectRatio()](#getAspectRatio--) | Uygulamada, belirli bir görüntünün en‑boy oranını döndürmelidir |
türünden bağımsız olarak.
|
|  | [getLinearDimensions()](#getLinearDimensions--) | Uygulamada, görüntünün doğrusal boyutlarını döndürmelidir. |
|
### getType() {#getType--}
```
public abstract ImageType getType()
```


Uygulamada, belirli bir görüntünün türünü bir
tüm tür‑özel bilgileri kapsayan belirli ImageType örneği


**Returns:**
[ImageType](../../com.groupdocs.editor.htmlcss.resources.images/imagetype)
### getAspectRatio() {#getAspectRatio--}
```
public abstract Ratio getAspectRatio()
```


Uygulamada, belirli bir görüntünün en‑boy oranını döndürmelidir
türünden bağımsız olarak. Hem vektör hem raster görüntülerin içsel
genişlik ve yükseklik arasındaki en‑boy oranı.


**Returns:**
[Ratio](../../com.groupdocs.editor.htmlcss.css.datatypes/ratio) - 
### getLinearDimensions() {#getLinearDimensions--}
```
public abstract Dimensions getLinearDimensions()
```


Uygulamada, görüntünün doğrusal boyutlarını döndürmelidir. İçin
raster görüntülerde bunlar piksel cinsinden içsel boyutlardır. Vektör görüntülerde ise
karşıt olarak sabit boyutları yoktur, ancak meta verileri içerebilir
farklı ölçü birimlerinde bazı temel boyutları.


**Returns:**
[Dimensions](../../com.groupdocs.editor.htmlcss.resources.images/dimensions) - 
