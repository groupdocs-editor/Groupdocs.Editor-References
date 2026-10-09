---
title: "QuoteType"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Tek tırnak ve çift tırnak karakterlerini temsil eder"
type: docs
weight: 660
url: /tr/net/groupdocs.editor.htmlcss.serialization/quotetype/
---
## QuoteType structure

Tek tırnak (') ve çift tırnak (") karakterlerini temsil eder

```csharp
public struct QuoteType : IEquatable<QuoteType>
```

## Properties

| Name | Açıklama |
| --- | --- |
| [Character](../../groupdocs.editor.htmlcss.serialization/quotetype/character) { get; } | Alıntılamak için karakter |
| [Code](../../groupdocs.editor.htmlcss.serialization/quotetype/code) { get; } | Geçerli karakterin kod noktası (U+0027 veya U+0022) |
| [HtmlEncoded](../../groupdocs.editor.htmlcss.serialization/quotetype/htmlencoded) { get; } | HTML kodlu karakter |

## Methods

| Name | Açıklama |
| --- | --- |
| override [Equals](../../groupdocs.editor.htmlcss.serialization/quotetype/equals#equals_1)(object) | Bu alıntı tipi örneğinin belirtilen dönüştürülmemiş değere eşit olup olmadığını gösterir |
| [Equals](../../groupdocs.editor.htmlcss.serialization/quotetype/equals#equals)(QuoteType) | Bu alıntı tipi örneğinin belirtilen değere eşit olup olmadığını gösterir |
| override [GetHashCode](../../groupdocs.editor.htmlcss.serialization/quotetype/gethashcode)() | Bu karakter için bir hash kodu döndürür |
| override [ToString](../../groupdocs.editor.htmlcss.serialization/quotetype/tostring)() | Geçerli değere bağlı olarak "SingleQuote" veya "DoubleQuote" dizesini döndürür |
| [operator ==](../../groupdocs.editor.htmlcss.serialization/quotetype/op_equality) | İki "QuoteType" değerinin eşit olup olmadığını denetler |
| [explicit operator](../../groupdocs.editor.htmlcss.serialization/quotetype/op_explicit#op_explicit) | Belirtilen [`QuoteType`](../quotetype) örneğini Char tipine dönüştürür (2 operatör) |
| [operator !=](../../groupdocs.editor.htmlcss.serialization/quotetype/op_inequality) | İki "QuoteType" değerinin eşit olmamasını kontrol eder |

## Alanlar

| Name | Açıklama |
| --- | --- |
| static readonly [DoubleQuote](../../groupdocs.editor.htmlcss.serialization/quotetype/doublequote) | Çift tırnak (U+0022 TIRNAK İŞARETİ karakteri) |
| static readonly [SingleQuote](../../groupdocs.editor.htmlcss.serialization/quotetype/singlequote) | Tek tırnak (U+0027 APOSTROP karakteri) |

### Ayrıca Bakınız

* namespace [GroupDocs.Editor.HtmlCss.Serialization](../../groupdocs.editor.htmlcss.serialization)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
