---
title: "ArgbColor"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mewakili satu nilai warna dalam format ARGB 32bit, 8 bit per saluran termasuk transparansi, dengan konverter dan serializer."
type: docs
weight: 160
url: /id/net/groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
## ArgbColor structure

Mewakili nilai panjang CSS dalam format 32-bit ARGB (8 bit per kanal termasuk transparansi) dengan konverter dan serializer

```csharp
public struct ArgbColor : ICssDataType, IEquatable<ArgbColor>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [A](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/a) { get; } | Mendapatkan bagian alfa dari warna. |
| [Alpha](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/alpha) { get; } | Mendapatkan bagian alfa dari warna dalam persentase (0..1). |
| [B](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/b) { get; } | Mendapatkan bagian biru dari warna. |
| [G](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/g) { get; } | Mendapatkan bagian hijau dari warna. |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isdefault) { get; } | Menunjukkan apakah instance [`ArgbColor`](../argbcolor) ini adalah default (Transparent) - semua 4 saluran diatur ke 0 |
| [IsEmpty](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isempty) { get; } | Warna yang belum diinisialisasi - semua 4 saluran diatur ke 0. Sama dengan Default dan Transparent. |
| [IsFullyOpaque](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullyopaque) { get; } | Menunjukkan apakah instance [`ArgbColor`](../argbcolor) ini sepenuhnya opak, tanpa transparansi (saluran Alpha-nya memiliki nilai maksimum) |
| [IsFullyTransparent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullytransparent) { get; } | Menunjukkan apakah instance [`ArgbColor`](../argbcolor) ini sepenuhnya transparan - saluran Alpha-nya memiliki nilai minimum (0), sehingga saluran R, G, dan B lainnya tidak berpengaruh secara visual. |
| [IsTranslucent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/istranslucent) { get; } | Menunjukkan apakah instance [`ArgbColor`](../argbcolor) ini tembus (tidak sepenuhnya transparan, tetapi juga tidak sepenuhnya opak) |
| [R](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/r) { get; } | Mendapatkan bagian merah dari warna. |
| [Value](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/value) { get; } | Mendapatkan nilai Int32 dari warna. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [FromRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgb)(byte, byte, byte) | Membuat satu nilai [`ArgbColor`](../argbcolor) dari saluran Merah, Hijau, Biru yang ditentukan, sementara saluran Alpha sepenuhnya tidak transparan |
| static [FromRgba](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgba)(byte, byte, byte, byte) | Membuat satu nilai [`ArgbColor`](../argbcolor) dari saluran Merah, Hijau, Biru, dan Alpha yang ditentukan |
| static [FromSingleValueRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromsinglevaluergb)(byte) | Membuat warna yang sepenuhnya tidak transparan (A=255) dari satu nilai, yang akan diterapkan ke semua saluran |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals)(ArgbColor) | Memeriksa dua warna [`ArgbColor`](../argbcolor) untuk kesetaraan |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals_1)(object) | Menguji apakah objek lain sama dengan instance [`ArgbColor`](../argbcolor) ini. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/gethashcode)() | Mengembalikan kode hash yang mendefinisikan warna saat ini. |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/serializedefault)() | Menyerialkan instance [`ArgbColor`](../argbcolor) ini ke notasi fungsi CSS yang paling tepat tergantung pada tingkat transparansi |
| [ToRGB](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgb)() | Menyerialkan instance [`ArgbColor`](../argbcolor) ini ke notasi fungsi CSS 'rgb' |
| [ToRGBA](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgba)() | Menyerialkan instance [`ArgbColor`](../argbcolor) ini ke notasi fungsi CSS 'rgba' |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/tostring)() | Sama dengan [`SerializeDefault`](./serializedefault) |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_equality) | Membandingkan dua warna dan mengembalikan nilai boolean yang menunjukkan apakah keduanya cocok. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_inequality) | Membandingkan dua warna dan mengembalikan nilai boolean yang menunjukkan apakah keduanya tidak cocok. |

## Anggota Lain

| Nama | Deskripsi |
| --- | --- |
| static class [KnownColors](argbcolor.knowncolors) | Berisi semua "known colors", yang memiliki nama unik tetap dan nilai dalam standar CSS |

### Catatan

Tipe ini dirancang agar berguna untuk (tetapi tidak terbatas pada) operasi CSS. Lihat selengkapnya: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### Lihat Juga

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
