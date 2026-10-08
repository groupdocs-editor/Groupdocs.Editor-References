---
title: "Rasio"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mewakili tipe data CSS rasio yang digunakan untuk menggambarkan rasio aspek dalam kueri media dan untuk gambar raster dengan menunjukkan proporsi antara dua nilai tanpa satuan yang disebut pembilang dan penyebut. Struct tak dapat diubah."
type: docs
weight: 250
url: /id/net/groupdocs.editor.htmlcss.css.datatypes/ratio/
---
## Ratio structure

Mewakili tipe data CSS "ratio", yang digunakan untuk menggambarkan rasio aspek dalam media query dan untuk gambar raster dengan menunjukkan proporsi antara dua nilai tanpa satuan yang disebut "numerator" dan "denominator". Struct tidak dapat diubah.

```csharp
public struct Ratio : ICloneable, ICssDataType, IEquatable<Ratio>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Denominator](../../groupdocs.editor.htmlcss.css.datatypes/ratio/denominator) { get; } | Mengembalikan penyebut dari rasio ini |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/ratio/isdefault) { get; } | Menentukan apakah rasio ini memiliki nilai default atau merupakan \"1/1\" (Tunggal) |
| [Numerator](../../groupdocs.editor.htmlcss.css.datatypes/ratio/numerator) { get; } | Mengembalikan pembilang dari rasio ini |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [Create](../../groupdocs.editor.htmlcss.css.datatypes/ratio/create)(ushort, ushort) | Membuat dan mengembalikan satu instance Rasio dari pembilang dan penyebut yang ditentukan |
| [Calculate](../../groupdocs.editor.htmlcss.css.datatypes/ratio/calculate)() | Menghitung dan mengembalikan rasio ini sebagai satu angka floating point tunggal |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/ratio/clone)() | Mengembalikan salinan lengkap dari rasio ini |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/ratio/equals#equals_1)(object) | Menentukan apakah instance ini sama dengan objek yang tidak dikast yang ditentukan, yang kemungkinan adalah instance \"Rasio\" lain |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/ratio/equals#equals)(Ratio) | Menentukan apakah instance ini sama dengan instance \"Rasio\" yang ditentukan |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/ratio/gethashcode)() | Mengembalikan hashcode untuk instance ini, yang tidak dapat diubah selama masa hidupnya |
| [GetInverseRatio](../../groupdocs.editor.htmlcss.css.datatypes/ratio/getinverseratio)() | Menghasilkan dan mengembalikan rasio invers (resiprokal) untuk rasio ini |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/ratio/serializedefault)() | Menyerialkan rasio ini ke string dan mengembalikannya |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/ratio/tostring)() | Mengembalikan representasi string dari rasio ini; sama dengan \"SerializeDefault()\" |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/ratio/op_equality) | Membandingkan dua rasio dan mengembalikan boolean yang menunjukkan apakah keduanya cocok. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/ratio/op_inequality) | Membandingkan dua rasio dan mengembalikan nilai boolean yang menunjukkan apakah keduanya tidak cocok. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| static readonly [Single](../../groupdocs.editor.htmlcss.css.datatypes/ratio/single) | Rasio default tunggal 1/1 |

### Catatan

https://developer.mozilla.org/en-US/docs/Web/CSS/ratio

### Lihat Juga

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
