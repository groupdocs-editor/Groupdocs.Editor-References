---
title: "FontWeight"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Fontweight özelliği, yazı tipinin ağırlığını veya kalınlığını ayarlar. Mevcut ayarlı fontfamily'ye bağlı olarak kullanılabilir ağırlıklar değişir."
type: docs
weight: 280
url: /tr/net/groupdocs.editor.htmlcss.css.properties/fontweight/
---
## FontWeight structure

Font-weight özelliği, yazı tipinin ağırlığını (veya kalınlığını) ayarlar. Mevcut ayarlı font-family'ye bağlı olarak kullanılabilir ağırlıklar değişir.

```csharp
public struct FontWeight : IEquatable<FontWeight>
```

## Properties

| Name | Açıklama |
| --- | --- |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.properties/fontweight/isabsolute) { get; } | Bu font-weight örneğinin, yazı tipinin ağırlığının (kalınlığının) mutlak değerini tam sayı olarak saklayıp saklamadığını gösterir. |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontweight/isinitial) { get; } | Bu font-size'ın bir ilk değeri (Orta) olup olmadığını gösterir. |
| [IsRelative](../../groupdocs.editor.htmlcss.css.properties/fontweight/isrelative) { get; } | Bu font-weight örneğinin, yazı tipinin ağırlığının (kalınlığının) göreceli bir değerini, ebeveyn öğenin kalınlığına göre saklayıp saklamadığını gösterir. |
| [Number](../../groupdocs.editor.htmlcss.css.properties/fontweight/number) { get; } | Yazı tipinin kalınlığını tanımlayan, 1 ile 1000 arasında (dahil) bir tam sayı döndürür; mevcut kalınlık mutlak değil de göreceli ise bir istisna fırlatır. |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontweight/value) { get; } | Bu font-weight değerini bir dize olarak döndürür. |

## Methods

| Name | Açıklama |
| --- | --- |
| static [FromNumber](../../groupdocs.editor.htmlcss.css.properties/fontweight/fromnumber)(ushort) | Belirtilen sayıdan bir font-weight oluşturur. |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontweight/equals#equals)(FontWeight) | Belirtilen FontWeight örneklerinin eşit olup olmadığını belirler. |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontweight/equals#equals_1)(object) | Bu FontWeight örneğinin belirtilen uncasted nesneye eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontweight/gethashcode)() | Bu örnek için bir hash kodu döndürür |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontweight/tryparse)(string, out FontWeight) | Belirtilen dizeyi ayrıştırmayı dener ve başarılı olursa geçerli bir FontWeight örneği döndürür. |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontweight/op_equality) | İki \"FontWeight\" değerinin eşit olup olmadığını denetler. |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontweight/op_inequality) | İki \"FontWeight\" değerinin eşit olmama durumunu denetler. |

## Alanlar

| Name | Açıklama |
| --- | --- |
| static readonly [Bold](../../groupdocs.editor.htmlcss.css.properties/fontweight/bold) | Kalın yazı tipi ağırlığı. 700 ile aynı. |
| static readonly [Bolder](../../groupdocs.editor.htmlcss.css.properties/fontweight/bolder) | Ebeveyn öğeden bir birim daha ağır bir göreceli yazı tipi ağırlığı. |
| static readonly [Lighter](../../groupdocs.editor.htmlcss.css.properties/fontweight/lighter) | Ebeveyn öğeden bir birim daha hafif bir göreceli yazı tipi ağırlığı. |
| static readonly [Normal](../../groupdocs.editor.htmlcss.css.properties/fontweight/normal) | Normal yazı tipi ağırlığı. 400 ile aynı. |

### Ayrıca Bakınız

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
