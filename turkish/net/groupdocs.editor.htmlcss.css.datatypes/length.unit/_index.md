---
title: "Length.Unit"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Desteklenen tüm uzunluk birimleri"
type: docs
weight: 240
url: /tr/net/groupdocs.editor.htmlcss.css.datatypes/length.unit/
---
## Length.Unit enumeration

Desteklenen tüm uzunluk birimleri

```csharp
public enum Unit
```

### Değerler

| Name | Değer | Açıklama |
| --- | --- | --- |
| Unitless | `0` | Birim yok - tanımlı bir uzunluk birimi yok. Varsayılan değer. |
| Px | `1` | Piksel. Görüntüleme cihazına göre. Ekran görüntüsü için genellikle ekranın bir cihaz pikseli (nokta) olarak kabul edilir. |
| Em | `2` | Em. Bu birim, öğenin hesaplanan yazı tipi boyutunu temsil eder. |
| Ex | `3` | Ex (x-uzunluğu). Bu birim, öğenin yazı tipinin x-yüksekliğini temsil eder. 'x' harfi bulunan yazı tiplerinde, bu genellikle küçük harflerin yüksekliğidir; birçok yazı tipinde 1ex ≈ 0.5em. |
| Cm | `4` | Cm. Bir santimetre (10 milimetre). |
| Mm | `5` | Mm. Bir milimetre. |
| In | `6` | In. Bir inç (2.54 santimetre). |
| Pt | `7` | Pt. Bir nokta, bir inçin 1/72'si ya da 0.353 mm'dir. |
| Pc | `8` | Pc. Bir pica (12 nokta). |
| Ch | `9` | Ch. Bu birim, öğenin yazı tipindeki '0' (sıfır, Unicode karakteri U+0030) glifinin genişliğini, daha doğrusu ilerleme ölçüsünü temsil eder. |
| Rem | `10` | Rem. Bu birim, kök öğenin (ör. &lt;html&gt; öğesinin) yazı tipi boyutunu temsil eder. Bu kök öğenin yazı tipi boyutunda kullanıldığında, başlangıç değerini temsil eder. |
| Vw | `11` | Vw - görünüm alanı genişliği. Görünüm alanı genişliğinin 1/100'i. |
| Vh | `12` | Vh - görünüm alanı yüksekliği. Görünüm alanı yüksekliğinin 1/100'i. |
| Vmin | `13` | Vmin. Görünüm alanının yüksekliği ile genişliği arasındaki minimum değerin 1/100'i. |
| Vmax | `14` | Vmax. Görünüm alanının yüksekliği ile genişliği arasındaki maksimum değerin 1/100'i. |
| Percent | `15` | Değer, bağlama bağlı sabit (harici) bir değere göredir. 1% = harici değerin 1/100'ü. |

### Açıklamalar

https://developer.mozilla.org/en-US/docs/Web/CSS/length#Units

### Ayrıca Bakınız

* struct [Length](../length)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
