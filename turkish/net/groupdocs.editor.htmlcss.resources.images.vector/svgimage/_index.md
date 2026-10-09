---
title: "SvgImage"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "SVG Scalable Vector Graphics formatında bir vektör görüntüyü, meta veri boyutları ve PNG'ye kaydetme ek yöntemleriyle temsil eder"
type: docs
weight: 580
url: /tr/net/groupdocs.editor.htmlcss.resources.images.vector/svgimage/
---
## SvgImage class

SVG (Scalable Vector Graphics) formatındaki bir vektör görüntüyü, meta verileri (boyutlar) ve ek yöntemleri (PNG olarak kaydetme) ile temsil eder.

```csharp
public sealed class SvgImage : VectorImageResourceBase
```

## Constructors

| Name | Açıklama |
| --- | --- |
| [SvgImage](svgimage#constructor)(string, Stream) | İçeriği bayt akışı olarak temsil eden ve belirtilen adla yeni bir SvgImage örneği oluşturur |
| [SvgImage](svgimage#constructor_1)(string, string) | İçeriği normal bir dize olarak temsil eden ve belirtilen adla yeni bir SvgImage örneği oluşturur |

## Properties

| Name | Açıklama |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | Bu vektör görüntünün en-boy oranını döndürür. |
| override [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/bytecontent) { get; } | Bu SVG görüntüsünün içeriğini orijinal konumda ikili akış olarak döndürür |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | Bu vektör görüntünün ad ve uzantıdan oluşan doğru dosya adını döndürür. Teorik olarak isimden farklı olabilir. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | Bu raster görüntünün serbest bırakılıp bırakılmadığını (`true`) veya (`false`) belirler. |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | Bu vektör görüntünün doğrusal boyutlarını (genişlik ve yükseklik) döndürür. |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | Bu vektör görüntünün adını döndürür. Genellikle dosya uzantısı içermez ve teorik olarak dosya adından farklı olabilir. |
| override [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/textcontent) { get; } | Bu SVG görüntüsünün içeriğini base64 kodlu ikili içerik olarak döndürür (XML formatında ham metin olarak değil) |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/type) { get; } | Döndürür [`Svg`](../../groupdocs.editor.htmlcss.resources.images/imagetype/svg) |
| [XmlContent](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/xmlcontent) { get; } | Bu SVG görüntüsünün içeriğini orijinal XML uyumlu metin biçiminde döndürür |

## Methods

| Name | Açıklama |
| --- | --- |
| override [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/dispose)() | Bu raster görüntüyü serbest bırakır, içeriğini serbest bırakarak çoğu yöntem ve özelliği çalışmaz hâle getirir |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals)(IHtmlResource) | Bu örneği belirtilen referans eşitliğiyle kontrol eder. |
| override [Save](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/save)(string) | Bu SVG görüntüsünü dosyaya kaydeder |
| override [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/savetopng)(Stream) | Bu vektör SVG görüntüsünü raster PNG görüntüsüne kaydeder |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/isvalid)(string) | Belirtilen metinsel XML uyumlu içeriğin bir SVG görüntüsü olup olmadığını yüzeysel olarak denetler |

## Olaylar

| Name | Açıklama |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | Bu raster görüntü serbest bırakıldığında gerçekleşen olay. |

### Ayrıca Bakınız

* class [VectorImageResourceBase](../vectorimageresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
