---
title: "Panjang"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mewakili nilai panjang CSS dalam unit apa pun yang didukung termasuk persentase dan tipe tanpa unit. Nilai dapat berupa integer atau float, nol negatif, dan positif. Struktur tidak dapat diubah."
type: docs
weight: 230
url: /id/net/groupdocs.editor.htmlcss.css.datatypes/length/
---
## Length structure

Mewakili nilai panjang CSS dalam unit apa pun yang didukung, termasuk persentase dan tipe tanpa satuan. Nilai dapat berupa integer atau float, negatif, nol, dan positif. Struktur tidak dapat diubah.

```csharp
public struct Length : ICloneable, ICssDataType, IEquatable<Length>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [FloatValue](../../groupdocs.editor.htmlcss.css.datatypes/length/floatvalue) { get; } | Mengembalikan nilai numerik float dari instance Length. Tidak pernah melempar pengecualian - mengonversi nilai Integer ke Float jika diperlukan. |
| [IntegerValue](../../groupdocs.editor.htmlcss.css.datatypes/length/integervalue) { get; } | Mengembalikan nilai numerik integer dari instance Length ini, jika disimpan secara internal sebagai integer, atau melempar pengecualian, jika awalnya disimpan sebagai angka float. |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.datatypes/length/isabsolute) { get; } | Mendapatkan apakah panjang diberikan dalam unit absolut. Panjang semacam itu dapat dikonversi ke piksel. |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/isdefault) { get; } | Menunjukkan apakah instance Length ini memiliki nilai default — nol tanpa unit. Sama dengan properti IsUnitlessZero. |
| [IsFloat](../../groupdocs.editor.htmlcss.css.datatypes/length/isfloat) { get; } | Menunjukkan apakah nilai numerik dari instance Length ini awalnya ditentukan dan disimpan sebagai angka float (FP32). |
| [IsInteger](../../groupdocs.editor.htmlcss.css.datatypes/length/isinteger) { get; } | Menunjukkan apakah nilai numerik dari instance Length ini awalnya ditentukan dan disimpan sebagai angka integer (INT32). |
| [IsNegative](../../groupdocs.editor.htmlcss.css.datatypes/length/isnegative) { get; } | Menentukan apakah nilai numerik panjang ini adalah angka negatif. |
| [IsPositive](../../groupdocs.editor.htmlcss.css.datatypes/length/ispositive) { get; } | Menentukan apakah nilai numerik panjang ini adalah angka positif. |
| [IsRelative](../../groupdocs.editor.htmlcss.css.datatypes/length/isrelative) { get; } | Mendapatkan apakah panjang diberikan dalam unit relatif. Panjang semacam itu tidak dapat dikonversi ke piksel. |
| [IsUnitlessNonZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlessnonzero) { get; } | Nilai memiliki tipe tanpa unit, tetapi bukan nol - angka positif atau negatif. |
| [IsUnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlesszero) { get; } | Menentukan apakah instance ini adalah nol tanpa unit atau tidak. Nol tanpa unit adalah nilai default tipe ini. Sama dengan properti IsDefault. |
| [IsZero](../../groupdocs.editor.htmlcss.css.datatypes/length/iszero) { get; } | Menentukan apakah nilai numerik panjang ini adalah angka nol. |
| [UnitType](../../groupdocs.editor.htmlcss.css.datatypes/length/unittype) { get; } | Mengembalikan tipe unit dari instance Length ini. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit)(double, Unit) | Membuat dan mengembalikan instance tipe Length dengan angka double dan unit yang ditentukan. |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_2)(float, Unit) | Membuat dan mengembalikan instance tipe Length dengan angka float dan unit yang ditentukan. |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_1)(int, Unit) | Membuat dan mengembalikan instance tipe Length dengan angka integer dan unit yang ditentukan. |
| static [Parse](../../groupdocs.editor.htmlcss.css.datatypes/length/parse)(string) | Menganalisis dan mengembalikan string yang ditentukan sebagai nilai Length, termasuk nilai numeriknya dan nama unit, atau melempar pengecualian jika gagal. |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/length/clone)() | Mengembalikan salinan penuh dari instance Length ini. |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals)(Length) | Mendefinisikan apakah nilai ini sama dengan panjang lain yang ditentukan. |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals_1)(object) | Menentukan apakah panjang ini sama dengan objek yang ditentukan. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/length/gethashcode)() | Menghitung dan mengembalikan hash-code dari instance Length ini dengan menggabungkan hash-code nilai dan tipe unit. |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/serializedefault)() | Mengembalikan representasi string dari panjang ini dalam bentuk asli (sebagaimana disimpan), tanpa mengonversi nilai panjang ke tipe unit lain. |
| [To](../../groupdocs.editor.htmlcss.css.datatypes/length/to)(Unit) | Mengonversi panjang ke unit yang diberikan, jika memungkinkan. Jika unit saat ini atau unit yang diberikan bersifat relatif, maka pengecualian akan dilempar. |
| [ToPixel](../../groupdocs.editor.htmlcss.css.datatypes/length/topixel)() | Mengonversi panjang ke sejumlah piksel, jika memungkinkan. Jika unit saat ini bersifat relatif, maka pengecualian akan dilempar. |
| [ToStringSpecified](../../groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified)(Unit) | Mengembalikan representasi string dari panjang ini dalam tipe unit yang ditentukan. Nilai numerik akan dikonversi sesuai dengan perubahan tipe unit. |
| static [GetUnitFromName](../../groupdocs.editor.htmlcss.css.datatypes/length/getunitfromname)(string) | Mencoba mengurai nama unit yang ditentukan dan mengembalikan nilai yang sesuai dari enum Unit. Mengembalikan Unit.Unitless jika tidak dapat menemukan unit yang tepat. |
| static [TryParse](../../groupdocs.editor.htmlcss.css.datatypes/length/tryparse)(string, out Length) | Mencoba mengurai string yang ditentukan sebagai nilai Length, termasuk nilai numeriknya dan nama unitnya |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/length/op_equality) | Memeriksa kesetaraan dari dua panjang yang diberikan. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/length/op_inequality) | Memeriksa ketidaksamaan dari dua panjang yang diberikan. |
| [operator *](../../groupdocs.editor.htmlcss.css.datatypes/length/op_multiply) | Mengalikan Length yang diberikan dengan faktor yang diberikan. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| static readonly [FiftyPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/fiftypercents) | 50% |
| static readonly [OneHundredPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/onehundredpercents) | 100% |
| static readonly [UnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/unitlesszero) | Integer nol tanpa unit - nilai default, sama dengan konstruktor tanpa parameter default. |
| static readonly [ZeroPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/zeropercents) | 0% |

## Anggota Lain

| Nama | Deskripsi |
| --- | --- |
| enum [Unit](length.unit) | Semua unit panjang yang didukung |

### Catatan

Tipe ini mencakup tipe data CSS berikut: https://developer.mozilla.org/en-US/docs/Web/CSS/length https://developer.mozilla.org/en-US/docs/Web/CSS/percentage

### Lihat Juga

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
