---
title: "IImageResource"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Herhangi bir raster veya vektör tipinde görüntü kaynağını temsil eder."
type: docs
weight: 470
url: /tr/net/groupdocs.editor.htmlcss.resources.images/iimageresource/
---
## IImageResource interface

Herhangi bir türde, raster veya vektör olan bir görüntü kaynağını temsil eder.

```csharp
public interface IImageResource : IHtmlResource, IImage
```

## Properties

| Name | Açıklama |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images/iimageresource/aspectratio) { get; } | Uygulama tipinde, görüntünün tipine bakılmaksızın belirli bir görüntünün en-boy oranını döndürmelidir. Hem vektör hem raster görüntülerin genişlik ve yükseklik arasında içsel bir en‑boy oranı vardır. |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images/iimageresource/lineardimensions) { get; } | Uygulama tipinde, görüntünün doğrusal boyutlarını döndürmelidir. Raster görüntüler için bu boyutlar piksel cinsinden içsel boyutlardır. Vektör görüntüler ise sabit boyutlara sahip değildir, ancak meta verileri farklı ölçü birimlerinde bazı temel boyutları içerebilir. |
| [Type](../../groupdocs.editor.htmlcss.resources.images/iimageresource/type) { get; } | Uygulama tipinde, belirli bir görüntünün tipini, tüm tipe özgü bilgileri kapsayan belirli bir ImageType örneği olarak döndürmelidir. |

### Açıklamalar

https://developer.mozilla.org/en-US/docs/Web/CSS/image

### Ayrıca Bakınız

* interface [IHtmlResource](../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* interface [IImage](../iimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images](../../groupdocs.editor.htmlcss.resources.images)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
