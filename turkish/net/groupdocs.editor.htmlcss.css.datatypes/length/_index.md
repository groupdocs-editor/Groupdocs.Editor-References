---
title: "Uzunluk"
second_title: "GroupDocs.Editor for .NET API Referansı"
description: "Yüzde ve birimsiz tip dahil olmak üzere desteklenen herhangi bir birimde bir CSS uzunluk değerini temsil eder. Değerler tam sayı veya kayan nokta, negatif, sıfır ve pozitif olabilir. Değiştirilemez yapı."
type: docs
weight: 230
url: /tr/net/groupdocs.editor.htmlcss.css.datatypes/length/
---
## Length structure

Yüzde ve birimsiz tip dahil olmak üzere desteklenen herhangi bir birimde bir CSS uzunluk değerini temsil eder. Değerler tam sayı veya kayan nokta, negatif, sıfır ve pozitif olabilir. Değiştirilemez yapı.

```csharp
public struct Length : ICloneable, ICssDataType, IEquatable<Length>
```

## Properties

| Name | Açıklama |
| --- | --- |
| [FloatValue](../../groupdocs.editor.htmlcss.css.datatypes/length/floatvalue) { get; } | Length örneğinin kayan nokta sayısal değerini döndürür. Asla bir istisna fırlatmaz - gerekirse Integer değerini Float'a dönüştürür. |
| [IntegerValue](../../groupdocs.editor.htmlcss.css.datatypes/length/integervalue) { get; } | Bu Length örneğinin tam sayı sayısal değerini döndürür, eğer dahili olarak tam sayı olarak depolanmışsa; aksi takdirde, orijinal olarak kayan nokta sayı olarak depolanmışsa bir istisna fırlatır. |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.datatypes/length/isabsolute) { get; } | Uzunluğun mutlak birimlerde verilip verilmediğini alır. Böyle bir uzunluk piksellere dönüştürülebilir. |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/isdefault) { get; } | Bu Length örneğinin varsayılan bir değere — birimsiz sıfıra sahip olup olmadığını gösterir. Aynı zamanda IsUnitlessZero özelliğiyle eşdeğerdir. |
| [IsFloat](../../groupdocs.editor.htmlcss.css.datatypes/length/isfloat) { get; } | Bu Length örneğinin sayısal değerinin başlangıçta bir float (FP32) sayı olarak belirtilip depolandığını gösterir. |
| [IsInteger](../../groupdocs.editor.htmlcss.css.datatypes/length/isinteger) { get; } | Bu Length örneğinin sayısal değerinin başlangıçta bir tam sayı (INT32) olarak belirtilip depolandığını gösterir. |
| [IsNegative](../../groupdocs.editor.htmlcss.css.datatypes/length/isnegative) { get; } | Bu uzunluğun sayısal değerinin negatif bir sayı olup olmadığını belirler. |
| [IsPositive](../../groupdocs.editor.htmlcss.css.datatypes/length/ispositive) { get; } | Bu uzunluğun sayısal değerinin pozitif bir sayı olup olmadığını belirler. |
| [IsRelative](../../groupdocs.editor.htmlcss.css.datatypes/length/isrelative) { get; } | Uzunluğun göreli birimlerde verilip verilmediğini alır. Böyle bir uzunluk piksellere dönüştürülemez. |
| [IsUnitlessNonZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlessnonzero) { get; } | Değer birimsiz tipe sahiptir, ancak sıfır değildir — pozitif veya negatif bir sayıdır. |
| [IsUnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlesszero) { get; } | Bu örneğin birimsiz sıfır olup olmadığını belirler. Birimsiz sıfır, bu tipin varsayılan değeridir. Aynı zamanda IsDefault özelliğiyle eşdeğerdir. |
| [IsZero](../../groupdocs.editor.htmlcss.css.datatypes/length/iszero) { get; } | Bu uzunluğun sayısal değerinin sıfır olup olmadığını belirler. |
| [UnitType](../../groupdocs.editor.htmlcss.css.datatypes/length/unittype) { get; } | Bu Length örneğinin birim tipini döndürür. |

## Methods

| Name | Açıklama |
| --- | --- |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit)(double, Unit) | Belirtilen double sayı ve birim ile bir Length tipi örneği oluşturur ve döndürür. |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_2)(float, Unit) | Belirtilen float sayı ve birim ile bir Length tipi örneği oluşturur ve döndürür. |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_1)(int, Unit) | Belirtilen tam sayı ve birim ile bir Length tipi örneği oluşturur ve döndürür. |
| static [Parse](../../groupdocs.editor.htmlcss.css.datatypes/length/parse)(string) | Belirtilen dizeyi bir Length değeri olarak ayrıştırır ve döndürür; sayısal değeri ve birim adını içerir, başarısızlıkta bir istisna fırlatır. |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/length/clone)() | Bu Length örneğinin tam bir kopyasını döndürür. |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals)(Length) | Bu değerin diğer belirtilen uzunluğa eşit olup olmadığını tanımlar. |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals_1)(object) | Bu uzunluğun belirtilen nesneye eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/length/gethashcode)() | Bu Length örneğinin değer ve birim tipinin hash kodlarını birleştirerek bir hash kodu hesaplar ve döndürür. |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/serializedefault)() | Bu uzunluğun, uzunluk değeri başka bir birim tipine dönüştürülmeden, orijinal yerel biçiminde (saklandığı şekilde) bir dize temsili döndürür. |
| [To](../../groupdocs.editor.htmlcss.css.datatypes/length/to)(Unit) | Uzunluğu mümkünse verilen birime dönüştürür. Mevcut ya da verilen birim göreli ise bir istisna fırlatılacaktır. |
| [ToPixel](../../groupdocs.editor.htmlcss.css.datatypes/length/topixel)() | Uzunluğu mümkünse piksel sayısına dönüştürür. Mevcut birim göreli ise bir istisna fırlatılacaktır. |
| [ToStringSpecified](../../groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified)(Unit) | Bu uzunluğun belirtilen birim tipinde bir dize temsili döndürür. Sayısal değer, birim tipindeki değişikliğe karşılık gelecek şekilde dönüştürülecektir. |
| static [GetUnitFromName](../../groupdocs.editor.htmlcss.css.datatypes/length/getunitfromname)(string) | Belirtilen birim adını ayrıştırmaya çalışır ve bir Unit enum'ının karşılık gelen değerini döndürür. Uygun bir birim bulunamazsa Unit.Unitless döndürür. |
| static [TryParse](../../groupdocs.editor.htmlcss.css.datatypes/length/tryparse)(string, out Length) | Belirtilen bir dizeyi bir Length değeri olarak ayrıştırmaya çalışır; sayısal değeri ve birim adını içerir. |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/length/op_equality) | Verilen iki uzunluğun eşitliğini kontrol eder. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/length/op_inequality) | Verilen iki uzunluğun eşitsizliğini kontrol eder. |
| [operator *](../../groupdocs.editor.htmlcss.css.datatypes/length/op_multiply) | Verilen Length'i verilen faktörle çarpar. |

## Alanlar

| Name | Açıklama |
| --- | --- |
| static readonly [FiftyPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/fiftypercents) | 50% |
| static readonly [OneHundredPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/onehundredpercents) | 100% |
| static readonly [UnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/unitlesszero) | Birim olmayan tam sayı sıfır - varsayılan değer, parametresiz varsayılan yapıcıyla aynı. |
| static readonly [ZeroPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/zeropercents) | 0% |

## Diğer Üyeler

| Name | Açıklama |
| --- | --- |
| enum [Unit](length.unit) | Desteklenen tüm uzunluk birimleri |

### Açıklamalar

Bu tür, aşağıdaki CSS veri tiplerini kapsar: https://developer.mozilla.org/en-US/docs/Web/CSS/length https://developer.mozilla.org/en-US/docs/Web/CSS/percentage

### Ayrıca Bakınız

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- DÜZENLEMEYİN: GroupDocs.editor.dll için xmldocmd tarafından oluşturuldu -->
