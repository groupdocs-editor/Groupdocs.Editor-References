---
title: "Boyutlar"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Tek bir raster dikdörtgen görüntünün genişlik ve yükseklik lineer boyutlarını isteğe bağlı bir birimde temsil eder. Değiştirilemez yapı."
type: docs
weight: 450
url: /tr/net/groupdocs.editor.htmlcss.resources.images/dimensions/
---
## Dimensions structure

Bir raster dikdörtgen görüntünün doğrusal boyutlarını (genişlik ve yükseklik) isteğe bağlı bir birimde temsil eder. Değiştirilemez yapı.

```csharp
public struct Dimensions : ICloneable, IEquatable<Dimensions>
```

## Constructors

| Name | Açıklama |
| --- | --- |
| [Dimensions](dimensions)(ushort, ushort) | Belirtilen genişlik ve yükseklikten yeni bir örnek oluşturur. |

## Properties

| Name | Açıklama |
| --- | --- |
| static [Empty](../../groupdocs.editor.htmlcss.resources.images/dimensions/empty) { get; } | Boş bir Dimensions örneği döndürür |
| [Area](../../groupdocs.editor.htmlcss.resources.images/dimensions/area) { get; } | Bir alan döndürür (Genişlik x Yükseklik) |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images/dimensions/aspectratio) { get; } | Bu boyutların en‑boy oranı genişlik/yükseklik olarak |
| [Height](../../groupdocs.editor.htmlcss.resources.images/dimensions/height) { get; } | Görüntünün yüksekliğini döndürür. |
| [IsEmpty](../../groupdocs.editor.htmlcss.resources.images/dimensions/isempty) { get; } | Bu "Dimensions" örneğinin boş ve varsayılan olup olmadığını belirler; yani doğru genişlik ve yüksekliği saklamaz. |
| [IsSquare](../../groupdocs.editor.htmlcss.resources.images/dimensions/issquare) { get; } | Belirtilen 'Dimensions' nesnesinin kare olup olmadığını belirler, yani genişliğin yüksekliğe eşit olup olmadığını. |
| [Width](../../groupdocs.editor.htmlcss.resources.images/dimensions/width) { get; } | Görüntünün genişliğini döndürür. |

## Methods

| Name | Açıklama |
| --- | --- |
| [Clone](../../groupdocs.editor.htmlcss.resources.images/dimensions/clone)() | Bu örneğin tam bir kopyasını döndürür. |
| [Equals](../../groupdocs.editor.htmlcss.resources.images/dimensions/equals#equals)(Dimensions) | Bu örneğin belirtilen "Dimensions" örneğiyle eşit olup olmadığını belirler. |
| override [Equals](../../groupdocs.editor.htmlcss.resources.images/dimensions/equals#equals_1)(object) | Bu örneğin belirtilen tip dönüşümü yapılmamış nesneyle eşit olup olmadığını belirler; bu nesne muhtemelen başka bir "Dimensions" örneğidir. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.images/dimensions/gethashcode)() | Bu örnek için ömür boyu değiştirilemeyen bir hash kodu döndürür. |
| [ProportionallyResizeForNewHeight](../../groupdocs.editor.htmlcss.resources.images/dimensions/proportionallyresizefornewheight)(ushort) | Belirtilen yüksekliğe göre mevcut örnekten orantılı olarak yeniden boyutlandırılan yeni bir "Dimensions" örneği oluşturur ve döndürür. |
| [ProportionallyResizeForNewWidth](../../groupdocs.editor.htmlcss.resources.images/dimensions/proportionallyresizefornewwidth)(ushort) | Belirtilen genişliğe göre mevcut örnekten orantılı olarak yeniden boyutlandırılan yeni bir "Dimensions" örneği oluşturur ve döndürür. |
| override [ToString](../../groupdocs.editor.htmlcss.resources.images/dimensions/tostring)() | Bu "Dimensions" nesnesinin string temsilini döndürür. |
| [operator ==](../../groupdocs.editor.htmlcss.resources.images/dimensions/op_equality) | İki "Dimensions" değerinin eşit olup olmadığını kontrol eder; yani genişlik ve yükseklikleri eşit ya da her ikisi de boş ise. |
| [operator !=](../../groupdocs.editor.htmlcss.resources.images/dimensions/op_inequality) | İki "Dimensions" değerinin eşit olmadığını kontrol eder; yani ilgili genişlik ve/veya yükseklikleri farklıdır. |

### Ayrıca Bakınız

* namespace [GroupDocs.Editor.HtmlCss.Resources.Images](../../groupdocs.editor.htmlcss.resources.images)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
