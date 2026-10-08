---
title: "TextDecorationLineType"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mewakili tipe-tipe garis dekorasi teks underline, underscore, overline, dan linethrough (strikethrough)."
type: docs
weight: 290
url: /id/net/groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/
---
## TextDecorationLineType structure

Mewakili jenis garis dekorasi teks: underline (garis bawah), overline, dan line-through (garis coret)

```csharp
public struct TextDecorationLineType : IEquatable<TextDecorationLineType>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isinitial) { get; } | Menunjukkan apakah instance ini memiliki nilai awal — None. |
| [IsLineThrough](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/islinethrough) { get; } | Menunjukkan apakah line-through (strikethrough) diaktifkan. |
| [IsOverline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isoverline) { get; } | Menunjukkan apakah overline diaktifkan. |
| [IsUnderline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isunderline) { get; } | Menunjukkan apakah underline (underscore) diaktifkan. |
| [Value](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/value) { get; } | Mengembalikan nilai semua flag dalam instance ini sebagai teks. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [FromFlags](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/fromflags)(bool, bool, bool) | Membuat dan mengembalikan instance [`TextDecorationLineType`](../textdecorationlinetype) dengan flag, yang didefinisikan oleh parameter yang ditentukan |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/equals#equals_1)(object) | Menunjukkan apakah instance [`TextDecorationLineType`](../textdecorationlinetype) ini sama dengan yang tidak dikastakan yang ditentukan |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/equals#equals)(TextDecorationLineType) | Menunjukkan apakah instance [`TextDecorationLineType`](../textdecorationlinetype) ini sama dengan yang ditentukan |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/gethashcode)() | Mengembalikan kode hash dari instance ini |
| override [ToString](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/tostring)() | Mengembalikan nilai semua flag dalam instance ini sebagai teks. |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/tryparse)(string, out TextDecorationLineType) | Mencoba mengurai string yang ditentukan dan mengembalikan instance [`TextDecorationLineType`](../textdecorationlinetype) yang valid |
| [operator +](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_addition) | Menggabungkan (menggabungkan) dua tipe garis yang ditentukan dan menghasilkan tipe garis baru, di mana flag digabungkan (union) |
| [operator /](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_division) | Mengembalikan interseksi antara tipe garis pertama dan kedua, di mana hanya flag yang diaktifkan secara bersamaan pada kedua operand. Memiliki prioritas tertinggi di antara semua operator (lebih tinggi daripada union dan difference) |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_equality) | Memeriksa apakah dua nilai "TextDecorationLineType" sama |
| [explicit operator](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_explicit#op_explicit_1) | Mengkast Byte (oktet 8-bit) tertentu ke [`TextDecorationLineType`](../textdecorationlinetype) yang sesuai, melempar pengecualian jika casting tidak valid (2 operator) |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_inequality) | Memeriksa apakah dua nilai "TextDecorationLineType" tidak sama |
| [operator -](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_subtraction) | Mengurangi tipe garis kedua yang ditentukan dari tipe garis pertama yang ditentukan dan menghasilkan tipe garis baru, di mana hanya flag dari operand pertama yang tidak terdapat pada operand kedua yang ada (difference) |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| static readonly [LineThrough](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/linethrough) | Setiap baris teks memiliki garis melintang di tengah. |
| static readonly [None](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/none) | Tidak menghasilkan dekorasi teks. Nilai awal. |
| static readonly [Overline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/overline) | Setiap baris teks memiliki garis di atasnya. |
| static readonly [Underline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/underline) | Setiap baris teks digarisbawahi. |

### Catatan

Struct tak dapat diubah. Mirip dengan https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line

### Lihat Juga

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
