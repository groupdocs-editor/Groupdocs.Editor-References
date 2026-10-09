---
title: "Oran"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Oranı temsil eden bir CSS veri tipi, medya sorgularında en‑boy oranlarını tanımlamak ve raster görüntülerde payda ve pay olarak adlandırılan iki birimsiz değer arasındaki oranı belirtmek için kullanılır. Değiştirilemez yapı."
type: docs
weight: 250
url: /tr/net/groupdocs.editor.htmlcss.css.datatypes/ratio/
---
## Ratio structure

Medya sorgularında en‑boy oranlarını tanımlamak ve raster görüntülerde \"numerator\" ve \"denominator\" adlı iki birimsiz değer arasındaki oranı belirtmek için kullanılan bir \"ratio\" CSS veri tipini temsil eder. Değiştirilemez yapı.

```csharp
public struct Ratio : ICloneable, ICssDataType, IEquatable<Ratio>
```

## Properties

| Name | Açıklama |
| --- | --- |
| [Denominator](../../groupdocs.editor.htmlcss.css.datatypes/ratio/denominator) { get; } | Bu oranın paydasını döndürür |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/ratio/isdefault) { get; } | Bu oranın varsayılan değere sahip olup olmadığını veya "1/1" (Tek) olup olmadığını belirler |
| [Numerator](../../groupdocs.editor.htmlcss.css.datatypes/ratio/numerator) { get; } | Bu oranın payını döndürür |

## Methods

| Name | Açıklama |
| --- | --- |
| static [Create](../../groupdocs.editor.htmlcss.css.datatypes/ratio/create)(ushort, ushort) | Belirtilen pay ve paydadan bir Ratio örneği oluşturur ve döndürür |
| [Calculate](../../groupdocs.editor.htmlcss.css.datatypes/ratio/calculate)() | Bu oranı tek bir kayan nokta sayısı olarak hesaplar ve döndürür |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/ratio/clone)() | Bu oranın tam bir kopyasını döndürür |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/ratio/equals#equals_1)(object) | Bu örneğin belirtilen tip dönüşümü yapılmamış nesneyle eşit olup olmadığını belirler; bu nesne muhtemelen başka bir "Ratio" örneğidir |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/ratio/equals#equals)(Ratio) | Bu örneğin belirtilen "Ratio" örneğiyle eşit olup olmadığını belirler |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/ratio/gethashcode)() | Bu örnek için ömür boyu değiştirilemeyen bir hash kodu döndürür. |
| [GetInverseRatio](../../groupdocs.editor.htmlcss.css.datatypes/ratio/getinverseratio)() | Bu oran için ters (karşılıklı) bir oran üretir ve döndürür |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/ratio/serializedefault)() | Bu oranı dizeye serileştirir ve döndürür |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/ratio/tostring)() | Bu oranın dize temsili döndürülür; "SerializeDefault()" ile aynı |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/ratio/op_equality) | İki oranı karşılaştırır ve iki oranın eşleşip eşleşmediğini gösteren bir boolean döndürür. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/ratio/op_inequality) | İki oranı karşılaştırır ve iki oranın eşleşmemesi durumunu gösteren bir boolean döndürür. |

## Alanlar

| Name | Açıklama |
| --- | --- |
| static readonly [Single](../../groupdocs.editor.htmlcss.css.datatypes/ratio/single) | Tek varsayılan oran 1/1 |

### Açıklamalar

https://developer.mozilla.org/en-US/docs/Web/CSS/ratio

### Ayrıca Bakınız

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
