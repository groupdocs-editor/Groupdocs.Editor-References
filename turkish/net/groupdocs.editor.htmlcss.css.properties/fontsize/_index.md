---
title: "FontSize"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Yazı tipi boyutunu özel bir birim veya uzunluk değeri olarak temsil eder; bu değer tarihsel olarak büyük M harfinin genişliğini belirtir."
type: docs
weight: 260
url: /tr/net/groupdocs.editor.htmlcss.css.properties/fontsize/
---
## FontSize structure

Bir yazı tipi boyutunu özel bir birim veya uzunluk değeri olarak temsil eder; bu, yazı tipinin boyutunu (tarihsel olarak büyük "M" harfinin genişliği) belirtir.

```csharp
public struct FontSize : IEquatable<FontSize>
```

## Properties

| Name | Açıklama |
| --- | --- |
| [IsAbsoluteSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isabsolutesize) { get; } | Bu font-size'ın, kullanıcının varsayılan yazı tipi boyutuna (ortadır) dayalı olarak bir anahtar kelimeyle mutlak bir boyut olarak tanımlanıp tanımlanmadığını gösterir. |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontsize/isinitial) { get; } | Bu font-size'ın bir ilk değeri (Orta) olup olmadığını gösterir. |
| [IsLengthDefined](../../groupdocs.editor.htmlcss.css.properties/fontsize/islengthdefined) { get; } | Bu font-size'ın bir [`Length`](../../groupdocs.editor.htmlcss.css.datatypes/length) değeriyle tanımlanıp tanımlanmadığını gösterir. |
| [IsRelativeSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isrelativesize) { get; } | Bu font-size bu değerle tanımlanmışsa bir uzunluk değeri; aksi takdirde bir istisna fırlatılır. |
| [Length](../../groupdocs.editor.htmlcss.css.properties/fontsize/length) { get; } | Bu yazı tipi boyutunun değerini bir dize olarak döndürür. |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontsize/value) { get; } | Belirtilen uzunluktan bir font-size oluşturur. |

## Methods

| Name | Açıklama |
| --- | --- |
| static [FromLength](../../groupdocs.editor.htmlcss.css.properties/fontsize/fromlength)(Length) | Bu font-size örneğinin belirtilenle eşit olup olmadığını belirler. |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals)(FontSize) | Bu font-size örneğinin belirtilen tip dönüşümü yapılmamış (uncasted) değerle eşit olup olmadığını belirler. |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals_1)(object) | Belirtilen anahtar kelimeyi 'font-size' için uygun bir anahtar kelime değeri olarak tanımaya çalışır ve başarılı olursa döndürür, başarısız olursa NULL döndürür. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontsize/gethashcode)() | Bu örnek için bir hash kodu döndürür |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontsize/tryparse)(string, out FontSize) | İki \"FontSize\" değerinin eşit olup olmadığını kontrol eder. |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_equality) | İki \"FontSize\" değerinin eşit olmama durumunu kontrol eder. |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_inequality) | Normalde büyük mutlak boyut |

## Alanlar

| Name | Açıklama |
| --- | --- |
| static readonly [Large](../../groupdocs.editor.htmlcss.css.properties/fontsize/large) | Daha büyük göreceli boyut - yazı tipi, ebeveyn öğenin font-size'ına göre daha büyük olacaktır; bu, yukarıdaki mutlak boyut anahtar kelimelerini ayırmak için kullanılan oranla yaklaşık olarak belirlenir. |
| static readonly [Larger](../../groupdocs.editor.htmlcss.css.properties/fontsize/larger) | Orta boyut. İlk değer. |
| static readonly [Medium](../../groupdocs.editor.htmlcss.css.properties/fontsize/medium) | Normalde küçük mutlak boyut |
| static readonly [Small](../../groupdocs.editor.htmlcss.css.properties/fontsize/small) | Daha küçük göreceli boyut - yazı tipi, ebeveyn öğenin font-size'ına göre daha küçük olacaktır; bu, yukarıdaki mutlak boyut anahtar kelimelerini ayırmak için kullanılan oranla yaklaşık olarak belirlenir. |
| static readonly [Smaller](../../groupdocs.editor.htmlcss.css.properties/fontsize/smaller) | Orta derecede büyük mutlak boyut |
| static readonly [XLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xlarge) | Orta derecede küçük mutlak boyut |
| static readonly [XSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xsmall) | Çok büyük mutlak boyut |
| static readonly [XxLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxlarge) | Çok büyük mutlak boyut |
| static readonly [XxSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxsmall) | Çok küçük mutlak boyut |

### Ayrıca Bakınız

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
