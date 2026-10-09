---
title: "TextDecorationLineType"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Metin süslemesi çizgi tiplerini (alt çizgi, alt çizgi (underscore), üst çizgi ve çizgili (strikethrough)) temsil eder."
type: docs
weight: 290
url: /tr/net/groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/
---
## TextDecorationLineType structure

Metin süsleme çizgi türlerini temsil eder: alt çizgi (alt tire), üst çizgi ve üstü çizili (çizgi üzeri)

```csharp
public struct TextDecorationLineType : IEquatable<TextDecorationLineType>
```

## Properties

| Name | Açıklama |
| --- | --- |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isinitial) { get; } | Bu örneğin başlangıç değerine sahip olup olmadığını gösterir — None |
| [IsLineThrough](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/islinethrough) { get; } | Satır üstü (strikethrough) özelliğinin etkin olup olmadığını gösterir. |
| [IsOverline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isoverline) { get; } | Üst çizgi özelliğinin etkin olup olmadığını gösterir. |
| [IsUnderline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isunderline) { get; } | Alt çizgi (underscore) özelliğinin etkin olup olmadığını gösterir. |
| [Value](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/value) { get; } | Bu örnekteki tüm bayrakların değerini metin olarak döndürür. |

## Methods

| Name | Açıklama |
| --- | --- |
| static [FromFlags](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/fromflags)(bool, bool, bool) | Belirtilen parametrelerle tanımlanan bayraklarla bir [`TextDecorationLineType`](../textdecorationlinetype) örneği oluşturur ve döndürür. |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/equals#equals_1)(object) | Bu [`TextDecorationLineType`](../textdecorationlinetype) örneğinin belirtilen dönüştürülmemiş değere eşit olup olmadığını gösterir |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/equals#equals)(TextDecorationLineType) | Bu [`TextDecorationLineType`](../textdecorationlinetype) örneğinin belirtilen değere eşit olup olmadığını gösterir |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/gethashcode)() | Bu örneğin bir hash kodunu döndürür |
| override [ToString](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/tostring)() | Bu örnekteki tüm bayrakların değerini metin olarak döndürür. |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/tryparse)(string, out TextDecorationLineType) | Belirtilen bir dizeyi ayrıştırmayı dener ve geçerli bir [`TextDecorationLineType`](../textdecorationlinetype) örneği döndürür |
| [operator +](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_addition) | İki belirtilen satır tipini birleştirir ve bayrakların birleştiği (union) yeni bir sonuç satır tipi üretir |
| [operator /](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_division) | İlk ve ikinci satır tipleri arasındaki kesişimi döndürür; yalnızca her iki operandta aynı anda etkin olan bayraklar etkin olur. Tüm operatörler arasında en yüksek önceliğe sahiptir (birleşim ve farktan daha yüksek) |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_equality) | İki "TextDecorationLineType" değerinin eşit olup olmadığını denetler |
| [explicit operator](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_explicit#op_explicit_1) | Belirli Byte'ı (8-bit oktet) ilgili [`TextDecorationLineType`](../textdecorationlinetype) tipine dönüştürür, dönüşüm geçersizse istisna fırlatır (2 operatör) |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_inequality) | İki "TextDecorationLineType" değerinin eşit olmadığını denetler |
| [operator -](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_subtraction) | İkinci belirtilen satır tipini birinci belirtilen satır tipinden çıkarır ve yalnızca birinci operandta bulunup ikinci operandta bulunmayan bayrakların yer aldığı yeni bir sonuç satır tipi üretir (fark) |

## Alanlar

| Name | Açıklama |
| --- | --- |
| static readonly [LineThrough](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/linethrough) | Metnin her satırının ortasından bir çizgi geçer. |
| static readonly [None](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/none) | Metin süslemesi üretmez. Başlangıç değeri. |
| static readonly [Overline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/overline) | Metnin her satırının üstünde bir çizgi bulunur. |
| static readonly [Underline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/underline) | Metnin her satırı altı çizili. |

### Açıklamalar

Değiştirilemez struct. https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line

### Ayrıca Bakınız

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
