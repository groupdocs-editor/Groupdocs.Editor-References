---
title: FontSize
second_title: .NET API Başvurusu için GroupDocs.Editor
description: Yazı tipi boyutunu özel bir birim olarak veya yazı tipi boyutunu belirten bir uzunluk değeri olarak temsil eder tarihsel olarak büyük harfin genişliği M.
type: docs
weight: 290
url: /tr/net/groupdocs.editor.htmlcss.css.properties/fontsize/
---
## FontSize structure

Yazı tipi boyutunu özel bir birim olarak veya yazı tipi boyutunu belirten bir uzunluk değeri olarak temsil eder (tarihsel olarak büyük harfin genişliği "M").

```csharp
public struct FontSize : IEquatable<FontSize>
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [IsAbsoluteSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isabsolutesize) { get; } | Bu yazı tipi boyutunun, kullanıcının varsayılan yazı tipi boyutuna (orta olan) dayalı olarak, anahtar sözcük olarak mutlak bir boyutla tanımlanıp tanımlanmadığını gösterir |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontsize/isinitial) { get; } | Bu yazı tipi boyutunun bir başlangıç değerine sahip olup olmadığını gösterir (Orta) |
| [IsLengthDefined](../../groupdocs.editor.htmlcss.css.properties/fontsize/islengthdefined) { get; } | Bu yazı tipi boyutunun bir ile tanımlanıp tanımlanmadığını gösterir.[`Length`](../../groupdocs.editor.htmlcss.css.datatypes/length) değer |
| [IsRelativeSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isrelativesize) { get; } | Bu yazı tipi boyutunun, anahtar sözcük olarak göreli bir boyutla tanımlanıp tanımlanmadığını gösterir. Yazı tipi, kabaca mutlak boyutlu anahtar kelimeleri ayırmak için kullanılan orana göre, ana öğenin yazı tipi boyutuna göre daha büyük veya daha küçük olacaktır. |
| [Length](../../groupdocs.editor.htmlcss.css.properties/fontsize/length) { get; } | Bu yazı tipi boyutu onunla tanımlandıysa bir uzunluk değeri veya aksi takdirde bir istisna attı |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontsize/value) { get; } | Bu yazı tipi boyutunun bir değerini string olarak döndürür |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [FromLength](../../groupdocs.editor.htmlcss.css.properties/fontsize/fromlength)(Length) | Belirtilen uzunlukta bir yazı tipi boyutu oluşturur |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals)(FontSize) | Bu yazı tipi boyutu örneğinin belirtilen ile eşit olup olmadığını belirler. |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals_1)(object) | Bu yazı tipi boyutu örneğinin belirtilen uncasted ile eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontsize/gethashcode)() | Bu örnek için bir karma kod döndürür |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontsize/tryparse)(string, out FontSize) | Belirli bir anahtar sözcüğü 'font-size' için uygun bir anahtar sözcük değeri olarak tanımaya çalışır ve bunu başarı durumunda veya başarısızlık durumunda NULL olarak döndürür. |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_equality) | İki "FontSize" değerinin eşit olup olmadığını kontrol eder |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_inequality) | İki "FontSize" değerinin eşit olup olmadığını kontrol eder |

## Alanlar

| İsim | Tanım |
| --- | --- |
| static readonly [Large](../../groupdocs.editor.htmlcss.css.properties/fontsize/large) | Normalde büyük olan mutlak-size |
| static readonly [Larger](../../groupdocs.editor.htmlcss.css.properties/fontsize/larger) | Daha büyük göreli boyut - yazı tipi, üst öğenin yazı tipi boyutuna göre, kabaca yukarıdaki mutlak boyutlu anahtar kelimeleri ayırmak için kullanılan orana göre daha büyük olacaktır. |
| static readonly [Medium](../../groupdocs.editor.htmlcss.css.properties/fontsize/medium) | Orta boy. Başlangıç değeri. |
| static readonly [Small](../../groupdocs.editor.htmlcss.css.properties/fontsize/small) | Normalde küçük olan mutlak-size |
| static readonly [Smaller](../../groupdocs.editor.htmlcss.css.properties/fontsize/smaller) | Daha küçük göreli boyut - yazı tipi, üst öğenin yazı tipi boyutuna göre, kabaca yukarıdaki mutlak boyutlu anahtar kelimeleri ayırmak için kullanılan orana göre daha küçük olacaktır. |
| static readonly [XLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xlarge) | Vasat büyük mutlak-size |
| static readonly [XSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xsmall) | Vasat küçük mutlak-size |
| static readonly [XxLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxlarge) | Çok büyük mutlak-size |
| static readonly [XxSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxsmall) | Çok küçük mutlak-size |

### Ayrıca bakınız

* ad alanı [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* toplantı [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
