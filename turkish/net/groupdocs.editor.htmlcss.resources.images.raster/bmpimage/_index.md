---
title: "BmpImage"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "BMP BitMap Picture formatındaki bir görüntüyü, meta verileri ve ek yöntemleriyle temsil eder"
type: docs
weight: 490
url: /tr/net/groupdocs.editor.htmlcss.resources.images.raster/bmpimage/
---
## BmpImage class

BMP (BitMap Picture) formatındaki bir görüntüyü meta verileri ve ek yöntemleriyle temsil eder.

```csharp
public sealed class BmpImage : RasterImageResourceBase
```

## Constructors

| Name | Açıklama |
| --- | --- |
| [BmpImage](bmpimage#constructor)(string, Stream) | İçeriği bayt akışı olarak temsil eden ve belirtilen adla yeni bir BmpImage örneği oluşturur |
| [BmpImage](bmpimage#constructor_1)(string, string) | İçeriği base64 kodlu dize olarak temsil eden ve belirtilen adla yeni bir BmpImage örneği oluşturur |

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
| override [Type](../../groupdocs.editor.htmlcss.resources.images.raster/bmpimage/type) { get; } | ImageType.Bmp değerini döndürür |

## Methods

| Name | Açıklama |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/dispose)() | Bu raster görüntüyü serbest bırakır, içeriğini serbest bırakarak çoğu yöntem ve özelliği çalışmaz hâle getirir |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/equals)(IHtmlResource) | Bu örneği belirtilen referans eşitliğiyle kontrol eder. |
| [Save](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/save)(string) | Bu raster görüntüyü belirtilen dosyaya kaydeder |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/bmpimage/isvalid#isvalid)(Stream) | Belirtilen akışın geçerli bir BMP görüntüsü olup olmadığını kontrol eder |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/bmpimage/isvalid#isvalid_1)(string) | Belirtilen base64 kodlu dizgenin geçerli bir BMP görüntüsü olup olmadığını kontrol eder |

## Olaylar

| Name | Açıklama |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/disposed) | Bu raster görüntü serbest bırakıldığında gerçekleşen olay. |

### Ayrıca Bakınız

* class [RasterImageResourceBase](../rasterimageresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
