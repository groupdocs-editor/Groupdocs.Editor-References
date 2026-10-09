---
title: "VectorImageResourceBase"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Desteklenen herhangi bir vektör görüntü için temel sınıf."
type: docs
weight: 590
url: /tr/net/groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/
---
## VectorImageResourceBase class

Desteklenen herhangi bir vektör görüntü için temel sınıf.

```csharp
public abstract class VectorImageResourceBase : IImageResource
```

## Properties

| Name | Açıklama |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | Bu vektör görüntünün en-boy oranını döndürür. |
| abstract [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/bytecontent) { get; } | Uygulayan tür, bu vektör görüntünün içeriğini bayt akışı olarak döndürmelidir. |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | Bu vektör görüntünün ad ve uzantıdan oluşan doğru dosya adını döndürür. Teorik olarak isimden farklı olabilir. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | Bu raster görüntünün serbest bırakılıp bırakılmadığını (`true`) veya (`false`) belirler. |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | Bu vektör görüntünün doğrusal boyutlarını (genişlik ve yükseklik) döndürür. |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | Bu vektör görüntünün adını döndürür. Genellikle dosya uzantısı içermez ve teorik olarak dosya adından farklı olabilir. |
| abstract [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/textcontent) { get; } | Uygulayan tür, bu vektör görüntünün içeriğini metin biçiminde döndürmelidir: görüntü türüne ilişkin XML'in base64 kodlu hali. |
| abstract [Type](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/type) { get; } | Uygulayan tür, vektör görüntünün türü hakkında bilgi döndürmelidir. |

## Methods

| Name | Açıklama |
| --- | --- |
| abstract [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/dispose)() | Uygulayan tür, bu örneği serbest bırakmalıdır. |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals#equals)(IHtmlResource) | Bu örneği belirtilen referans eşitliğiyle kontrol eder. |
| abstract [Save](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/save)(string) | Uygulayan tür, bu görüntüyü belirtilen yola kaydetmelidir. |
| abstract [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/savetopng)(Stream) | Uygulayan tür, mevcut vektör görüntüyü raster PNG formatında belirtilen bayt akışına kaydetmelidir. |

## Olaylar

| Name | Açıklama |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | Bu raster görüntü serbest bırakıldığında gerçekleşen olay. |

### Ayrıca Bakınız

* interface [IImageResource](../../groupdocs.editor.htmlcss.resources.images/iimageresource)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
