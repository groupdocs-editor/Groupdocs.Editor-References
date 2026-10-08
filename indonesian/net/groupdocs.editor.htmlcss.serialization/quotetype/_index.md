---
title: "QuoteType"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mewakili karakter kutip  single quote  dan double quote"
type: docs
weight: 660
url: /id/net/groupdocs.editor.htmlcss.serialization/quotetype/
---
## QuoteType structure

Mewakili karakter kutip - kutip tunggal (') dan kutip ganda (\")

```csharp
public struct QuoteType : IEquatable<QuoteType>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Character](../../groupdocs.editor.htmlcss.serialization/quotetype/character) { get; } | Karakter untuk dikutip |
| [Code](../../groupdocs.editor.htmlcss.serialization/quotetype/code) { get; } | Titik kode dari karakter saat ini (U+0027 atau U+0022) |
| [HtmlEncoded](../../groupdocs.editor.htmlcss.serialization/quotetype/htmlencoded) { get; } | Karakter yang di-encode HTML |

## Metode

| Nama | Deskripsi |
| --- | --- |
| override [Equals](../../groupdocs.editor.htmlcss.serialization/quotetype/equals#equals_1)(object) | Menunjukkan apakah instance tipe kutip ini sama dengan yang ditentukan tanpa cast |
| [Equals](../../groupdocs.editor.htmlcss.serialization/quotetype/equals#equals)(QuoteType) | Menunjukkan apakah instance tipe kutip ini sama dengan yang ditentukan |
| override [GetHashCode](../../groupdocs.editor.htmlcss.serialization/quotetype/gethashcode)() | Mengembalikan hash-code untuk karakter ini |
| override [ToString](../../groupdocs.editor.htmlcss.serialization/quotetype/tostring)() | Mengembalikan string "SingleQuote" atau "DoubleQuote" tergantung pada nilai saat ini |
| [operator ==](../../groupdocs.editor.htmlcss.serialization/quotetype/op_equality) | Memeriksa apakah dua nilai "QuoteType" sama |
| [explicit operator](../../groupdocs.editor.htmlcss.serialization/quotetype/op_explicit#op_explicit) | Meng-cast instance [`QuoteType`](../quotetype) yang ditentukan menjadi Char (2 operator) |
| [operator !=](../../groupdocs.editor.htmlcss.serialization/quotetype/op_inequality) | Memeriksa apakah dua nilai "QuoteType" tidak sama |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| static readonly [DoubleQuote](../../groupdocs.editor.htmlcss.serialization/quotetype/doublequote) | Tanda kutip ganda (karakter U+0022 QUOTATION MARK) |
| static readonly [SingleQuote](../../groupdocs.editor.htmlcss.serialization/quotetype/singlequote) | Tanda kutip tunggal (karakter U+0027 APOSTROPHE) |

### Lihat Juga

* namespace [GroupDocs.Editor.HtmlCss.Serialization](../../groupdocs.editor.htmlcss.serialization)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
