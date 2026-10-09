---
title: "RasterImageResourceBase"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Sabit ad, boyut, en‑boy oranı, tip, boyut ve içerik ile desteklenen herhangi bir raster görüntü için temel sınıf."
type: docs
weight: 540
url: /tr/net/groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/
---
## RasterImageResourceBase class

Sabit ad, boyutlar, en‑boy oranı, tür, boyut ve içerik ile desteklenen herhangi bir raster görüntü için temel sınıf.

```csharp
public abstract class RasterImageResourceBase : IImageResource
```

## Properties

| Name | Açıklama |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/aspectratio) { get; } | Bu görüntünün en-boy oranını genişlik-boy oranı olarak döndürür. |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/bytecontent) { get; } | Bu raster görüntünün içeriğini bayt akışı olarak döndürür. |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/filenamewithextension) { get; } | Bu raster görüntünün ad ve uzantıdan oluşan doğru dosya adını döndürür. Teorik olarak isimden farklı olabilir. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/isdisposed) { get; } | Bu raster görüntünün serbest bırakılıp bırakılmadığını belirler. |
| [Length](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/length) { get; } | Bu raster görüntü dosyasının bayt cinsinden uzunluğunu döndürür. |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/lineardimensions) { get; } | Bu raster görüntünün doğrusal boyutlarını (genişlik ve yükseklik) döndürür. |
| [Name](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/name) { get; } | Bu raster görüntünün adını döndürür. Genellikle dosya uzantısı içermez ve teorik olarak dosya adından farklı olabilir. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/textcontent) { get; } | Bu raster görüntünün içeriğini base64 kodlu dize olarak döndürür. |
| abstract [Type](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/type) { get; } | Uygulayan tip, raster görüntünün tipi hakkında bilgi döndürmelidir |

## Methods

| Name | Açıklama |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/dispose)() | Bu raster görüntüyü serbest bırakır, içeriğini serbest bırakarak çoğu yöntem ve özelliği çalışmaz hâle getirir |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/equals#equals)(IHtmlResource) | Bu örneği belirtilen referans eşitliğiyle kontrol eder. |
| [Save](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/save)(string) | Bu raster görüntüyü belirtilen dosyaya kaydeder |

## Olaylar

| Name | Açıklama |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/disposed) | Bu raster görüntü serbest bırakıldığında gerçekleşen olay. |

### Ayrıca Bakınız

* interface [IImageResource](../../groupdocs.editor.htmlcss.resources.images/iimageresource)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
