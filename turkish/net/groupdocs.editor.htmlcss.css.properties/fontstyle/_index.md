---
title: "FontStyle"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Yazı tipinin font ailesinden normal, italik veya eğik bir yüz ile nasıl biçimlendirilmesi gerektiğini tanımlar."
type: docs
weight: 270
url: /tr/net/groupdocs.editor.htmlcss.css.properties/fontstyle/
---
## FontStyle structure

Yazı tipinin font-family'sinden normal, italik veya eğik bir yüz ile nasıl stilleneceğini tanımlar.

```csharp
public struct FontStyle
```

## Properties

| Name | Açıklama |
| --- | --- |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontstyle/isinitial) { get; } | Bu font-style'ın bir başlangıç değeri (Normal) olup olmadığını gösterir |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontstyle/value) { get; } | Bu font stilinin değerini dize olarak döndürür |

## Methods

| Name | Açıklama |
| --- | --- |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontstyle/equals#equals)(FontStyle) | Bu font-style örneğinin belirtilenle eşit olup olmadığını belirler |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontstyle/equals#equals_1)(object) | Bu font-style örneğinin belirtilen tip dönüşümü yapılmamış değerle eşit olup olmadığını belirler |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontstyle/gethashcode)() | Bu örnek için bir hash kodu döndürür |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontstyle/tryparse)(string, out FontStyle) | Belirtilen anahtar kelimeyi 'font-style' için uygun bir anahtar kelime değeri olarak tanımaya çalışır ve başarılı olursa döndürür, başarısız olursa NULL döndürür. |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontstyle/op_equality) | İki "FontStyle" değerinin eşit olup olmadığını denetler |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontstyle/op_inequality) | İki "FontStyle" değerinin eşit olmamasını denetler |

## Alanlar

| Name | Açıklama |
| --- | --- |
| static readonly [Italic](../../groupdocs.editor.htmlcss.css.properties/fontstyle/italic) | İtalik olarak sınıflandırılmış bir yazı tipini seçer. Eğer yüzün italik sürümü mevcut değilse, bunun yerine eğik (oblique) olarak sınıflandırılmış bir sürüm kullanılır. Hiçbiri mevcut değilse, stil yapay olarak simüle edilir. |
| static readonly [Normal](../../groupdocs.editor.htmlcss.css.properties/fontstyle/normal) | Bir yazı tipi ailesi içinde normal olarak sınıflandırılmış bir yazı tipini seçer. İlk değer. |
| static readonly [Oblique](../../groupdocs.editor.htmlcss.css.properties/fontstyle/oblique) | Eğik (oblique) olarak sınıflandırılmış bir yazı tipini seçer. Eğer yüzün eğik sürümü mevcut değilse, bunun yerine italik olarak sınıflandırılmış bir sürüm kullanılır. Hiçbiri mevcut değilse, stil yapay olarak simüle edilir. |

### Ayrıca Bakınız

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
