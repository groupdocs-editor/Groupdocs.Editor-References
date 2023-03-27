---
title: Length
second_title: GroupDocs.Editor untuk Referensi .NET API
description: Mewakili nilai panjang CSS dalam unit apa pun yang didukung termasuk persentase dan tipe tanpa unit. Nilai dapat berupa bilangan bulat atau float negatif nol dan positif. Struktur yang tidak dapat diubah.
type: docs
weight: 260
url: /id/net/groupdocs.editor.htmlcss.css.datatypes/length/
---
## Length structure

Mewakili nilai panjang CSS dalam unit apa pun yang didukung, termasuk persentase dan tipe tanpa unit. Nilai dapat berupa bilangan bulat atau float, negatif, nol, dan positif. Struktur yang tidak dapat diubah.

```csharp
public struct Length : ICloneable, ICssDataType, IEquatable<Length>
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [FloatValue](../../groupdocs.editor.htmlcss.css.datatypes/length/floatvalue) { get; } | Mengembalikan nilai numerik float dari instance Length. Jangan pernah melempar pengecualian - ubah nilai Integer menjadi Float jika perlu. |
| [IntegerValue](../../groupdocs.editor.htmlcss.css.datatypes/length/integervalue) { get; } | Mengembalikan nilai numerik integer dari instance Length ini, jika disimpan secara internal sebagai integer, atau melontarkan pengecualian, jika awalnya disimpan sebagai float number. |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.datatypes/length/isabsolute) { get; } | Mendapat jika panjang diberikan dalam satuan absolut. Panjang tersebut dapat dikonversi ke piksel. |
| [IsFloat](../../groupdocs.editor.htmlcss.css.datatypes/length/isfloat) { get; } | Menunjukkan apakah nilai numerik dari instance Length ini awalnya ditentukan dan disimpan sebagai float (FP32) number |
| [IsInteger](../../groupdocs.editor.htmlcss.css.datatypes/length/isinteger) { get; } | Menunjukkan apakah nilai numerik dari instance Length ini awalnya ditentukan dan disimpan sebagai angka bilangan bulat (INT32) |
| [IsNegative](../../groupdocs.editor.htmlcss.css.datatypes/length/isnegative) { get; } | Menentukan apakah nilai numerik dari panjang ini adalah angka negatif |
| [IsPositive](../../groupdocs.editor.htmlcss.css.datatypes/length/ispositive) { get; } | Menentukan apakah nilai numerik dari panjang ini adalah bilangan positif |
| [IsRelative](../../groupdocs.editor.htmlcss.css.datatypes/length/isrelative) { get; } | Mendapat jika panjang diberikan dalam satuan relatif. Panjang seperti itu tidak dapat diubah menjadi piksel. |
| [IsUnitlessNonZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlessnonzero) { get; } | Nilai memiliki tipe tanpa unit, tetapi bukan angka nol - positif atau negatif |
| [IsUnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlesszero) { get; } | Menentukan apakah instance ini adalah nol tanpa unit atau tidak. Nol tanpa unit adalah nilai default dari jenis ini. Sama seperti properti IsDefault. |
| [IsZero](../../groupdocs.editor.htmlcss.css.datatypes/length/iszero) { get; } | Menentukan apakah nilai numerik dari panjang ini adalah angka nol |
| [UnitType](../../groupdocs.editor.htmlcss.css.datatypes/length/unittype) { get; } | Mengembalikan tipe unit dari instans Panjang ini. |

## Metode

| Nama | Keterangan |
| --- | --- |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit)(double, Unit) | Membuat dan mengembalikan instance tipe Panjang dengan nomor ganda dan unit yang ditentukan |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_2)(float, Unit) | Membuat dan mengembalikan instance tipe Panjang dengan nomor float dan unit yang ditentukan |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_1)(int, Unit) | Membuat dan mengembalikan instance tipe Panjang dengan nomor integer dan unit yang ditentukan |
| static [Parse](../../groupdocs.editor.htmlcss.css.datatypes/length/parse)(string) | Mem-parsing dan mengembalikan string yang ditentukan sebagai nilai Panjang, termasuk nilai numerik dan nama unitnya, atau melontarkan pengecualian pada failure |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/length/clone)() | Mengembalikan salinan lengkap instance Panjang ini |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals)(Length) | Menentukan apakah nilai ini sama dengan panjang yang ditentukan lainnya |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals_1)(object) | Menentukan apakah panjang ini sama dengan objek yang ditentukan |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/length/gethashcode)() | Menghitung dan mengembalikan kode hash dari instance Length ini dengan menggabungkan kode hash dari nilai dan tipe unit |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/serializedefault)() | Mengembalikan representasi string dengan panjang ini dalam bentuk asli aslinya (seperti yang disimpan), tanpa mengonversi nilai panjang ke tipe unit lain |
| [To](../../groupdocs.editor.htmlcss.css.datatypes/length/to)(Unit) | Mengonversi panjang ke satuan tertentu, jika memungkinkan. Jika current atau unit yang diberikan relatif, maka pengecualian akan dilemparkan. |
| [ToPixel](../../groupdocs.editor.htmlcss.css.datatypes/length/topixel)() | Mengonversi panjang menjadi sejumlah piksel, jika memungkinkan. Jika the unit saat ini relatif, maka pengecualian akan dilemparkan. |
| [ToStringSpecified](../../groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified)(Unit) | Mengembalikan representasi string dengan panjang ini dalam tipe unit yang ditentukan. Nilai numerik akan dikonversi sesuai dengan perubahan tipe unit. |
| static [GetUnitFromName](../../groupdocs.editor.htmlcss.css.datatypes/length/getunitfromname)(string) | Mencoba menguraikan nama unit yang ditentukan dan mengembalikan nilai yang sesuai dari enum Unit. Mengembalikan Unit.Unitless jika tidak dapat menemukan unit yang sesuai. |
| static [TryParse](../../groupdocs.editor.htmlcss.css.datatypes/length/tryparse)(string, out Length) | Mencoba mengurai string tertentu sebagai nilai Panjang, termasuk nilai numerik dan nama unitnya |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/length/op_equality) | Memeriksa kesetaraan dari dua panjang yang diberikan. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/length/op_inequality) | Memeriksa pertidaksamaan dari dua panjang yang diberikan. |
| [operator *](../../groupdocs.editor.htmlcss.css.datatypes/length/op_multiply) | Mengalikan Panjang yang diberikan ke faktor yang diberikan |

## Bidang

| Nama | Keterangan |
| --- | --- |
| static readonly [FiftyPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/fiftypercents) | 50% |
| static readonly [OneHundredPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/onehundredpercents) | 100% |
| static readonly [UnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/unitlesszero) | Bilangan bulat nol tanpa unit - nilai default, sama dengan konstruktor tanpa parameter default |
| static readonly [ZeroPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/zeropercents) | 0% |

## Anggota lainnya

| Nama | Keterangan |
| --- | --- |
| enum [Unit](length.unit) | Semua satuan panjang yang didukung |

### Perkataan

Jenis ini mencakup jenis data CSS berikutnya: https://developer.mozilla.org/en-US/docs/Web/CSS/length https://developer.mozilla.org/en-US/docs/Web/ CSS/persentase

### Lihat juga

* interface [ICssDataType](../icssdatatype)
* ruang nama [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* perakitan [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
