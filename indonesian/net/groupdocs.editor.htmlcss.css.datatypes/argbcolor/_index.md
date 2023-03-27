---
title: ArgbColor
second_title: GroupDocs.Editor untuk Referensi .NET API
description: Mewakili satu nilai warna dalam format ARGB dengan konverter dan serializer
type: docs
weight: 190
url: /id/net/groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
## ArgbColor structure

Mewakili satu nilai warna dalam format ARGB dengan konverter dan serializer

```csharp
public struct ArgbColor : ICssDataType, IEquatable<ArgbColor>
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [A](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/a) { get; } | Mendapatkan bagian alfa dari warna. |
| [Alpha](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/alpha) { get; } | Mendapatkan bagian alfa dari warna dalam persen (0..1). |
| [B](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/b) { get; } | Mendapat bagian warna biru. |
| [G](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/g) { get; } | Mendapat bagian warna hijau. |
| [IsEmpty](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isempty) { get; } | Warna tidak diinisialisasi - semua 4 saluran disetel ke 0. Sama seperti Default dan Transparan. |
| [IsFullyOpaque](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullyopaque) { get; } | Menunjukkan apakah ini[`ArgbColor`](../argbcolor) instance sepenuhnya buram, tanpa transparansi (saluran Alpha-nya memiliki nilai maksimal) |
| [IsFullyTransparent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullytransparent) { get; } | Menunjukkan apakah ini[`ArgbColor`](../argbcolor) instance sepenuhnya transparan - saluran Alpha-nya memiliki nilai min (0), jadi saluran R, G, dan B lainnya tidak memiliki efek yang terlihat. |
| [IsTranslucent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/istranslucent) { get; } | Menunjukkan apakah ini[`ArgbColor`](../argbcolor) instance tembus cahaya (tidak sepenuhnya transparan, tetapi juga tidak sepenuhnya buram) |
| [R](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/r) { get; } | Mendapat bagian warna merah. |
| [Value](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/value) { get; } | Mendapatkan nilai warna Int32. |

## Metode

| Nama | Keterangan |
| --- | --- |
| static [FromRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgb)(byte, byte, byte) | Membuat satu[`ArgbColor`](../argbcolor) nilai dari saluran Merah, Hijau, Biru yang ditentukan, sedangkan saluran Alfa sepenuhnya buram |
| static [FromRgba](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgba)(byte, byte, byte, byte) | Membuat satu[`ArgbColor`](../argbcolor) nilai dari saluran Merah, Hijau, Biru, dan Alfa yang ditentukan |
| static [FromSingleValueRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromsinglevaluergb)(byte) | Membuat warna buram sepenuhnya (A=255) dari nilai tunggal, yang akan diterapkan ke semua saluran |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals)(ArgbColor) | Memeriksa dua[`ArgbColor`](../argbcolor) warna untuk persamaan |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals_1)(object) | Menguji apakah objek lain sama dengan ini[`ArgbColor`](../argbcolor) contoh. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/gethashcode)() | Mengembalikan kode hash yang menentukan warna saat ini. |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/serializedefault)() | Membuat serial ini[`ArgbColor`](../argbcolor)instance ke notasi fungsi CSS yang paling sesuai tergantung pada translucency |
| [ToRGB](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgb)() | Membuat serial ini[`ArgbColor`](../argbcolor) contoh ke notasi fungsi CSS 'rgb' |
| [ToRGBA](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgba)() | Membuat serial ini[`ArgbColor`](../argbcolor) contoh ke notasi fungsi CSS 'rgba' |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/tostring)() | Sama seperti[`SerializeDefault`](./serializedefault) |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_equality) | Membandingkan dua warna dan mengembalikan boolean yang menunjukkan jika keduanya cocok. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_inequality) | Membandingkan dua warna dan mengembalikan boolean yang menunjukkan jika keduanya tidak cocok. |

## Anggota lainnya

| Nama | Keterangan |
| --- | --- |
| static class [KnownColors](argbcolor.knowncolors) | Berisi semua "warna yang dikenal", yang memiliki nama dan nilai unik tetap di standart CSS |

### Perkataan

Jenis ini dirancang agar berguna untuk (namun tidak terbatas pada) operasi CSS. Lihat selengkapnya: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### Lihat juga

* interface [ICssDataType](../icssdatatype)
* ruang nama [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* perakitan [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
