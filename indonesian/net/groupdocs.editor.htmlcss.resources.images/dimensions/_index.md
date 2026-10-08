---
title: "Dimensi"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mewakili dimensi linier lebar dan tinggi dari satu gambar raster persegi panjang dalam satuan arbitrer. Struktur tidak dapat diubah."
type: docs
weight: 450
url: /id/net/groupdocs.editor.htmlcss.resources.images/dimensions/
---
## Dimensions structure

Mewakili dimensi linier (lebar dan tinggi) dari satu gambar raster persegi panjang dalam satuan arbitrer. Struktur tidak dapat diubah.

```csharp
public struct Dimensions : ICloneable, IEquatable<Dimensions>
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Dimensions](dimensions)(ushort, ushort) | Membuat instance baru dari lebar dan tinggi yang ditentukan. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| static [Empty](../../groupdocs.editor.htmlcss.resources.images/dimensions/empty) { get; } | Mengembalikan instance Dimensi kosong |
| [Area](../../groupdocs.editor.htmlcss.resources.images/dimensions/area) { get; } | Mengembalikan area (Lebar x Tinggi) |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images/dimensions/aspectratio) { get; } | Rasio aspek dimensi ini sebagai lebar/tinggi |
| [Height](../../groupdocs.editor.htmlcss.resources.images/dimensions/height) { get; } | Mengembalikan tinggi gambar. |
| [IsEmpty](../../groupdocs.editor.htmlcss.resources.images/dimensions/isempty) { get; } | Menentukan apakah instance "Dimensions" ini kosong dan default, yaitu tidak menyimpan lebar dan tinggi yang benar |
| [IsSquare](../../groupdocs.editor.htmlcss.resources.images/dimensions/issquare) { get; } | Menentukan apakah 'Dimensions' yang ditentukan mewakili persegi, yaitu jika lebar sama dengan tinggi |
| [Width](../../groupdocs.editor.htmlcss.resources.images/dimensions/width) { get; } | Mengembalikan lebar gambar |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Clone](../../groupdocs.editor.htmlcss.resources.images/dimensions/clone)() | Mengembalikan salinan penuh dari instance ini |
| [Equals](../../groupdocs.editor.htmlcss.resources.images/dimensions/equals#equals)(Dimensions) | Menentukan apakah instance ini sama dengan instance "Dimensions" yang ditentukan |
| override [Equals](../../groupdocs.editor.htmlcss.resources.images/dimensions/equals#equals_1)(object) | Menentukan apakah instance ini sama dengan objek yang tidak dikast yang ditentukan, yang kemungkinan merupakan instance "Dimensions" lain |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.images/dimensions/gethashcode)() | Mengembalikan hashcode untuk instance ini, yang tidak dapat diubah selama masa hidupnya |
| [ProportionallyResizeForNewHeight](../../groupdocs.editor.htmlcss.resources.images/dimensions/proportionallyresizefornewheight)(ushort) | Membuat dan mengembalikan instance "Dimensions" baru, yang diubah ukurannya secara proporsional dari yang saat ini, berdasarkan tinggi yang ditentukan |
| [ProportionallyResizeForNewWidth](../../groupdocs.editor.htmlcss.resources.images/dimensions/proportionallyresizefornewwidth)(ushort) | Membuat dan mengembalikan instance "Dimensions" baru, yang diubah ukurannya secara proporsional dari yang saat ini, berdasarkan lebar yang ditentukan |
| override [ToString](../../groupdocs.editor.htmlcss.resources.images/dimensions/tostring)() | Mengembalikan representasi string dari "Dimensions" ini |
| [operator ==](../../groupdocs.editor.htmlcss.resources.images/dimensions/op_equality) | Memeriksa apakah dua nilai "Dimensions" sama, yaitu mereka memiliki lebar dan tinggi yang sama, atau keduanya kosong |
| [operator !=](../../groupdocs.editor.htmlcss.resources.images/dimensions/op_inequality) | Memeriksa apakah dua nilai "Dimensions" tidak sama, yaitu lebar dan/atau tinggi yang bersesuaian berbeda |

### Lihat Juga

* namespace [GroupDocs.Editor.HtmlCss.Resources.Images](../../groupdocs.editor.htmlcss.resources.images)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
