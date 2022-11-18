---
title: Length
second_title: .NET API Başvurusu için GroupDocs.Editor
description: Yüzde ve birimsiz tür dahil olmak üzere herhangi bir desteklenebilir birimdeki bir CSS uzunluk değerini temsil eder. Değerler tamsayı veya değişken negatif sıfır ve pozitif olabilir. Değişmez yapı.
type: docs
weight: 190
url: /tr/net/groupdocs.editor.htmlcss.css.datatypes/length/
---
## Length structure

Yüzde ve birimsiz tür dahil olmak üzere herhangi bir desteklenebilir birimdeki bir CSS uzunluk değerini temsil eder. Değerler tamsayı veya değişken, negatif, sıfır ve pozitif olabilir. Değişmez yapı.

```csharp
public struct Length : ICloneable, IEquatable<  >, IEquatable<Length>
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [FloatValue](../../groupdocs.editor.htmlcss.css.datatypes/length/floatvalue) { get; } | Uzunluk örneğinin kayan bir sayısal değerini döndürür. Asla istisna oluşturmaz - gerekirse Tamsayı değerini Kayan değere dönüştürür. |
| [IntegerValue](../../groupdocs.editor.htmlcss.css.datatypes/length/integervalue) { get; } | Dahili olarak bir tamsayı olarak depolanıyorsa, bu Uzunluk örneğinin bir tamsayı sayısal değerini döndürür, veya orijinal olarak kayan sayı olarak depolandıysa bir istisna atar. |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.datatypes/length/isabsolute) { get; } | Uzunluğun mutlak birimler halinde verilmiş olup olmadığını alır. Böyle bir uzunluk piksele dönüştürülebilir. |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/isdefault) { get; } | Bu Uzunluk örneğinin varsayılan bir değeri olup olmadığını gösterir — birimsiz sıfır. IsUnitlessZero özelliğiyle aynı. |
| [IsFloat](../../groupdocs.editor.htmlcss.css.datatypes/length/isfloat) { get; } | Bu Uzunluk örneğinin sayısal değerinin başlangıçta bir değişken (FP32) numarası olarak belirtilip depolanmadığını gösterir |
| [IsInteger](../../groupdocs.editor.htmlcss.css.datatypes/length/isinteger) { get; } | Bu Uzunluk örneğinin sayısal değerinin başlangıçta bir tamsayı (INT32) numarası olarak belirtilip depolanmadığını gösterir |
| [IsNegative](../../groupdocs.editor.htmlcss.css.datatypes/length/isnegative) { get; } | Bu uzunluğun sayısal değerinin negatif bir sayı olup olmadığını belirler |
| [IsPositive](../../groupdocs.editor.htmlcss.css.datatypes/length/ispositive) { get; } | Bu uzunluğun sayısal değerinin pozitif bir sayı olup olmadığını belirler |
| [IsRelative](../../groupdocs.editor.htmlcss.css.datatypes/length/isrelative) { get; } | Uzunluğun göreli birimlerde verilip verilmediğini alır. Böyle bir uzunluk piksele dönüştürülemez. |
| [IsUnitlessNonZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlessnonzero) { get; } | Değerin türü birimsizdir, ancak sıfır değildir - pozitif veya negatif sayı |
| [IsUnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlesszero) { get; } | Bu örneğin birimsiz sıfır olup olmadığını belirler. Birimsiz sıfır, bu türün varsayılan değeridir. IsDefault özelliğiyle aynı. |
| [IsZero](../../groupdocs.editor.htmlcss.css.datatypes/length/iszero) { get; } | Bu uzunluğun sayısal değerinin sıfır olup olmadığını belirler |
| [UnitType](../../groupdocs.editor.htmlcss.css.datatypes/length/unittype) { get; } | Bu Uzunluk örneğinin birim türünü döndürür. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit)(double, Unit) | Belirtilen çift sayı ve unit ile bir Uzunluk türü örneği oluşturur ve döndürür |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_2)(float, Unit) | Belirtilen değişken sayı ve unit ile bir Uzunluk türü örneği oluşturur ve döndürür |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_1)(int, Unit) | Belirtilen tam sayı ve birim ile bir Uzunluk türü örneği oluşturur ve döndürür |
| static [Parse](../../groupdocs.editor.htmlcss.css.datatypes/length/parse)(string) | Belirtilen dizeyi, sayısal değeri ve birim adı da dahil olmak üzere bir Uzunluk değeri olarak ayrıştırır ve döndürür veya Failure üzerinde bir istisna atar. |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/length/clone)() | Bu Uzunluk örneğinin tam bir kopyasını döndürür |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals)(Length) | Bu değerin belirtilen diğer uzunluk 'ye eşit olup olmadığını tanımlar |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals_1)(object) | Bu uzunluğun belirtilen object değerine eşit olup olmadığını belirler. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/length/gethashcode)() | Değerin ve birim tipinin karma kodlarını birleştirerek bu Uzunluk örneğinin bir karma kodunu hesaplar ve döndürür |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/serializedefault)() | Uzunluk değerini başka bir birim type 'ye dönüştürmeden, orijinal yerel biçiminde (depolandığı şekliyle) bu uzunluğun dize gösterimini döndürür |
| [To](../../groupdocs.editor.htmlcss.css.datatypes/length/to)(Unit) | Mümkünse, uzunluğu verilen birime dönüştürür. Current veya verilen birim göreceli ise, bir istisna atılır. |
| [ToPixel](../../groupdocs.editor.htmlcss.css.datatypes/length/topixel)() | Mümkünse, uzunluğu birkaç piksele dönüştürür. the geçerli birim göreceli ise, bir istisna atılır. |
| [ToStringSpecified](../../groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified)(Unit) | Belirtilen birim türünde bu uzunluğun dize gösterimini döndürür. Sayısal değer, birim tipi değişikliğine karşılık gelecek şekilde dönüştürülecektir. |
| static [GetUnitFromName](../../groupdocs.editor.htmlcss.css.datatypes/length/getunitfromname)(string) | Belirtilen birim adını ayrıştırmaya ve bir Birime karşılık gelen değeri döndürmeye çalışır. Uygun birimi bulamazsa Birimi.Birimsiz döndürür. |
| static [TryParse](../../groupdocs.editor.htmlcss.css.datatypes/length/tryparse)(string, out Length) | Belirtilen bir diziyi, sayısal değeri ve birim adı da dahil olmak üzere bir Uzunluk değeri olarak ayrıştırmaya çalışır |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/length/op_equality) | Verilen iki uzunluğun eşitliğini kontrol eder. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/length/op_inequality) | Verilen iki uzunluğun eşitsizliğini kontrol eder. |

## Alanlar

| İsim | Tanım |
| --- | --- |
| static readonly [FiftyPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/fiftypercents) | %50 |
| static readonly [OneHundredPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/onehundredpercents) | %100 |
| static readonly [UnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/unitlesszero) | Birimsiz tamsayı sıfır - varsayılan değer, varsayılan parametresiz yapıcı ile aynı |
| static readonly [ZeroPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/zeropercents) | %0 |

## Diğer_Üyeler

| İsim | Tanım |
| --- | --- |
| enum [Unit](length.unit) | Tüm desteklenen uzunluk birimleri |

### Notlar

Bu tür, sonraki CSS veri türlerini kapsar: https://developer.mozilla.org/en-US/docs/Web/CSS/length https://developer.mozilla.org/en-US/docs/Web/ CSS/percentage

### Ayrıca bakınız

* ad alanı [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* toplantı [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
