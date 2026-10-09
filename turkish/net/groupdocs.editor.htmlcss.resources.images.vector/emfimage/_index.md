---
title: "EmfImage"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "EMF (Enhanced Metafile) formatında bir vektör görüntüyü, meta verileri ve ek yöntemlerle temsil eder"
type: docs
weight: 560
url: /tr/net/groupdocs.editor.htmlcss.resources.images.vector/emfimage/
---
## EmfImage class

Gelişmiş metafile (EMF) formatındaki bir vektör görüntüyü, meta verileri ve ek yöntemleriyle temsil eder.

```csharp
public sealed class EmfImage : MetaImageBase
```

## Constructors

| Name | Açıklama |
| --- | --- |
| [EmfImage](emfimage#constructor)(string, Stream) | Belirtilen adla ve bayt akışı olarak temsil edilen içerikten yeni bir EmfImage örneği oluşturur |
| [EmfImage](emfimage#constructor_1)(string, string) | Belirtilen adla ve base64 kodlu dize olarak temsil edilen içerikten yeni bir EmfImage örneği oluşturur |

## Properties

| Name | Açıklama |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | Bu vektör görüntünün en-boy oranını döndürür. |
| override [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/bytecontent) { get; } | Bu EMF görüntüsünün içeriğini ikili akış olarak döndürür |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | Bu vektör görüntünün ad ve uzantıdan oluşan doğru dosya adını döndürür. Teorik olarak isimden farklı olabilir. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | Bu raster görüntünün serbest bırakılıp bırakılmadığını (`true`) veya (`false`) belirler. |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | Bu vektör görüntünün doğrusal boyutlarını (genişlik ve yükseklik) döndürür. |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | Bu vektör görüntünün adını döndürür. Genellikle dosya uzantısı içermez ve teorik olarak dosya adından farklı olabilir. |
| override [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/textcontent) { get; } | Bu EMF görüntüsünün içeriğini düz metin olarak döndürür |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/type) { get; } | ImageType.Emf değerini döndürür |

## Methods

| Name | Açıklama |
| --- | --- |
| override [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/dispose)() | Bu EMF görüntüsünü içeriğini serbest bırakarak ve çoğu yöntem ve özelliğini çalışmaz hâle getirerek yok eder. |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals)(IHtmlResource) | Bu örneği belirtilen referans eşitliğiyle kontrol eder. |
| override [Save](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/save)(string) | Bu EMF görüntüsünü dosyaya kaydeder |
| override [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/savetopng)(Stream) | Bu vektör EMF görüntüsünü raster PNG görüntüsüne kaydeder |
| override [SaveToSvg](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/savetosvg)(Stream) | Bu vektör EMF görüntüsünü vektör SVG görüntüsüne kaydeder |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/isvalid#isvalid)(Stream) | Belirtilen akışın geçerli bir EMF görüntüsü olup olmadığını denetler |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/emfimage/isvalid#isvalid_1)(string) | Belirtilen base64 kodlu dizgenin geçerli bir EMF görüntüsü olup olmadığını denetler |

## Olaylar

| Name | Açıklama |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | Bu raster görüntü serbest bırakıldığında gerçekleşen olay. |

### Ayrıca Bakınız

* class [MetaImageBase](../metaimagebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
