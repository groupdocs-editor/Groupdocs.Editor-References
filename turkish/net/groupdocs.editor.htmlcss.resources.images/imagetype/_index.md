---
title: "ImageType"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Hem raster hem vektör formatlarını destekleyen bir görüntü tipi biçimini temsil eder."
type: docs
weight: 480
url: /tr/net/groupdocs.editor.htmlcss.resources.images/imagetype/
---
## ImageType structure

Desteklenebilir bir görüntü türünü (formatını) temsil eder, raster ve vektör formatlarını destekler.

```csharp
public struct ImageType : IEquatable<ImageType>, IResourceType
```

## Properties

| Name | Açıklama |
| --- | --- |
| static [Bmp](../../groupdocs.editor.htmlcss.resources.images/imagetype/bmp) { get; } | BMP görüntü tipi |
| static [Emf](../../groupdocs.editor.htmlcss.resources.images/imagetype/emf) { get; } | EMF (Enhanced MetaFile) vektör görüntü tipi |
| static [Gif](../../groupdocs.editor.htmlcss.resources.images/imagetype/gif) { get; } | GIF görüntü tipi |
| static [Icon](../../groupdocs.editor.htmlcss.resources.images/imagetype/icon) { get; } | ICON görüntü tipi |
| static [Jpeg](../../groupdocs.editor.htmlcss.resources.images/imagetype/jpeg) { get; } | JPEG görüntü tipi |
| static [Png](../../groupdocs.editor.htmlcss.resources.images/imagetype/png) { get; } | PNG görüntü tipi |
| static [Svg](../../groupdocs.editor.htmlcss.resources.images/imagetype/svg) { get; } | SVG vektör görüntü türü |
| static [Tiff](../../groupdocs.editor.htmlcss.resources.images/imagetype/tiff) { get; } | TIFF (Tagged Image File Format) raster görüntü türü |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.images/imagetype/undefined) { get; } | Tanımsız görüntü türü - normalde ortaya çıkmaması gereken özel bir değer |
| static [Wmf](../../groupdocs.editor.htmlcss.resources.images/imagetype/wmf) { get; } | WMF (Windows MetaFile) vektör görüntü türü |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.images/imagetype/fileextension) { get; } | Belirli bir görüntü türünün dosya uzantısı (başındaki nokta olmadan) küçük harflerle. Tanımsız tip için 'unsefined' dizesi döndürülür. |
| [FormalName](../../groupdocs.editor.htmlcss.resources.images/imagetype/formalname) { get; } | Bu görüntü formatının resmi adını döndürür. Asla NULL döndürmez. Örnek bozulmamışsa, asla bir istisna fırlatmaz. |
| [IsVector](../../groupdocs.editor.htmlcss.resources.images/imagetype/isvector) { get; } | Bu belirli formatın vektör (true) mı yoksa raster (false) mı olduğunu gösterir |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.images/imagetype/mimecode) { get; } | Belirli bir görüntü türünün MIME kodunu dize olarak verir. Tanımsız tip için 'unsefined' dizesi döndürülür. |

## Methods

| Name | Açıklama |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images/imagetype/parsefromfilenamewithextension)(string) | Belirtilen dosya adından çıkarılan dosya uzantısına eşdeğer olan ImageType değerini döndürür |
| static [ParseFromMime](../../groupdocs.editor.htmlcss.resources.images/imagetype/parsefrommime)(string) | Belirtilen MIME koduna eşdeğer olan ImageType değerini döndürür |
| [Equals](../../groupdocs.editor.htmlcss.resources.images/imagetype/equals#equals)(ImageType) | Bu örneğin belirtilen "ImageType" örneğiyle eşit olup olmadığını belirler |
| override [Equals](../../groupdocs.editor.htmlcss.resources.images/imagetype/equals#equals_1)(object) | Bu örneğin belirtilen tip dönüşümü yapılmamış nesneyle, muhtemelen başka bir "ImageType" örneğiyle eşit olup olmadığını belirler |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.images/imagetype/gethashcode)() | Bu belirli örnek için değiştirilemez bir sayı olan hash kodunu döndürür |
| override [ToString](../../groupdocs.editor.htmlcss.resources.images/imagetype/tostring)() | FormalName özelliğini döndürür |
| [operator ==](../../groupdocs.editor.htmlcss.resources.images/imagetype/op_equality) | İki belirli ImageType örneğinin eşit olup olmadığını tanımlar |
| [operator !=](../../groupdocs.editor.htmlcss.resources.images/imagetype/op_inequality) | İki belirli ImageType örneğinin eşit olmama durumunu tanımlar |

### Ayrıca Bakınız

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images](../../groupdocs.editor.htmlcss.resources.images)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
