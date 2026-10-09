---
title: "ArgbColor"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Dönüştürücüler ve serileştiricilerle birlikte şeffaflığı da içeren, kanal başına 8 bit olmak üzere 32 bit ARGB formatında bir renk değerini temsil eder."
type: docs
weight: 160
url: /tr/net/groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
## ArgbColor structure

Dönüştürücüler ve serileştiricilerle birlikte 32-bit ARGB formatında (saydamlık dahil her kanalda 8 bit) bir renk değerini temsil eder

```csharp
public struct ArgbColor : ICssDataType, IEquatable<ArgbColor>
```

## Properties

| Name | Açıklama |
| --- | --- |
| [A](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/a) { get; } | Rengin alfa kısmını alır. |
| [Alpha](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/alpha) { get; } | Rengin alfa kısmını yüzde olarak alır (0..1). |
| [B](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/b) { get; } | Rengin mavi kısmını alır. |
| [G](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/g) { get; } | Rengin yeşil kısmını alır. |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isdefault) { get; } | Bu [`ArgbColor`](../argbcolor) örneğinin varsayılan (Şeffaf) olup olmadığını gösterir - tüm 4 kanal 0 olarak ayarlanmıştır. |
| [IsEmpty](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isempty) { get; } | Başlatılmamış renk - tüm 4 kanal 0 olarak ayarlanmıştır. Varsayılan ve Şeffaf ile aynı. |
| [IsFullyOpaque](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullyopaque) { get; } | Bu [`ArgbColor`](../argbcolor) örneğinin tamamen opak olup olmadığını gösterir, şeffaflık yoktur (Alfa kanalı maksimum değere sahiptir). |
| [IsFullyTransparent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullytransparent) { get; } | Bu [`ArgbColor`](../argbcolor) örneğinin tamamen şeffaf olup olmadığını gösterir - Alfa kanalı minimum (0) değere sahiptir, bu yüzden diğer R, G ve B kanalları görünür bir etki yapmaz. |
| [IsTranslucent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/istranslucent) { get; } | Bu [`ArgbColor`](../argbcolor) örneğinin yarı saydam olup olmadığını gösterir (tamamen şeffaf değil, ancak tamamen opak da değildir). |
| [R](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/r) { get; } | Rengin kırmızı kısmını alır. |
| [Value](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/value) { get; } | Rengin Int32 değerini alır. |

## Methods

| Name | Açıklama |
| --- | --- |
| static [FromRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgb)(byte, byte, byte) | Belirtilen Kırmızı, Yeşil ve Mavi kanallarından bir [`ArgbColor`](../argbcolor) değeri oluşturur, Alpha kanalı tamamen opaktır. |
| static [FromRgba](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgba)(byte, byte, byte, byte) | Belirtilen Kırmızı, Yeşil, Mavi ve Alpha kanallarından bir [`ArgbColor`](../argbcolor) değeri oluşturur. |
| static [FromSingleValueRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromsinglevaluergb)(byte) | Tek bir değerden (A=255) tamamen opak bir renk oluşturur; bu değer tüm kanallara uygulanır. |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals)(ArgbColor) | İki [`ArgbColor`](../argbcolor) rengin eşitliğini kontrol eder. |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals_1)(object) | Başka bir nesnenin bu [`ArgbColor`](../argbcolor) örneğiyle eşit olup olmadığını test eder. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/gethashcode)() | Mevcut rengi tanımlayan bir hash kodu döndürür. |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/serializedefault)() | Bu [`ArgbColor`](../argbcolor) örneğini saydamlığa bağlı olarak en uygun CSS fonksiyon gösterimine serileştirir. |
| [ToRGB](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgb)() | Bu [`ArgbColor`](../argbcolor) örneğini 'rgb' CSS fonksiyon gösterimine serileştirir. |
| [ToRGBA](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgba)() | Bu [`ArgbColor`](../argbcolor) örneğini 'rgba' CSS fonksiyon gösterimine serileştirir. |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/tostring)() | Aynı [`SerializeDefault`](./serializedefault) ile. |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_equality) | İki rengi karşılaştırır ve iki rengin eşleşip eşleşmediğini belirten bir boolean döndürür. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_inequality) | İki rengi karşılaştırır ve iki rengin eşleşmediğini belirten bir boolean döndürür. |

## Diğer Üyeler

| Name | Açıklama |
| --- | --- |
| static class [KnownColors](argbcolor.knowncolors) | CSS standartta sabit benzersiz adı ve değeri olan tüm \"known colors\" öğelerini içerir |

### Açıklamalar

Bu tip, (ancak bununla sınırlı olmamak üzere) CSS işlemleri için faydalı olacak şekilde tasarlanmıştır. Daha fazla bilgi: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### Ayrıca Bakınız

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
