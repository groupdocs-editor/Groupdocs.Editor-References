---
title: "FontStyle"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mendefinisikan bagaimana font harus diberi gaya dengan bentuk normal, miring, atau miring oblique dari keluarga fontnya."
type: docs
weight: 270
url: /id/net/groupdocs.editor.htmlcss.css.properties/fontstyle/
---
## FontStyle structure

Mendefinisikan bagaimana font harus diberi gaya dengan: wajah normal, miring, atau miring oblique dari font-family-nya.

```csharp
public struct FontStyle
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontstyle/isinitial) { get; } | Menunjukkan apakah font-style ini memiliki nilai awal (Normal) |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontstyle/value) { get; } | Mengembalikan nilai font style ini sebagai string |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontstyle/equals#equals)(FontStyle) | Menentukan apakah instance font-style ini sama dengan yang ditentukan |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontstyle/equals#equals_1)(object) | Menentukan apakah instance font-style ini sama dengan yang ditentukan tanpa casting |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontstyle/gethashcode)() | Mengembalikan hash-code untuk instance ini |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontstyle/tryparse)(string, out FontStyle) | Mencoba mengenali kata kunci yang ditentukan sebagai nilai kata kunci yang tepat dari 'font-style' dan mengembalikannya jika berhasil atau NULL jika gagal. |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontstyle/op_equality) | Memeriksa apakah dua nilai "FontStyle" sama |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontstyle/op_inequality) | Memeriksa apakah dua nilai "FontStyle" tidak sama |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| static readonly [Italic](../../groupdocs.editor.htmlcss.css.properties/fontstyle/italic) | Memilih font yang diklasifikasikan sebagai italic. Jika tidak ada versi italic dari font tersebut, yang diklasifikasikan sebagai oblique akan digunakan sebagai gantinya. Jika keduanya tidak tersedia, gaya tersebut disimulasikan secara artifisial. |
| static readonly [Normal](../../groupdocs.editor.htmlcss.css.properties/fontstyle/normal) | Memilih font yang diklasifikasikan sebagai normal dalam sebuah font-family. Nilai awal. |
| static readonly [Oblique](../../groupdocs.editor.htmlcss.css.properties/fontstyle/oblique) | Memilih font yang diklasifikasikan sebagai oblique. Jika tidak ada versi oblique dari font tersebut, yang diklasifikasikan sebagai italic akan digunakan sebagai gantinya. Jika keduanya tidak tersedia, gaya tersebut disimulasikan secara artifisial. |

### Lihat Juga

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
