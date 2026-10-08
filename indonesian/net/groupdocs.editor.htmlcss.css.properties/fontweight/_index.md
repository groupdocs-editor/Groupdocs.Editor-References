---
title: "FontWeight"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Properti Fontweight mengatur berat atau ketebalan font. Berat yang tersedia tergantung pada fontfamily yang saat ini diatur."
type: docs
weight: 280
url: /id/net/groupdocs.editor.htmlcss.css.properties/fontweight/
---
## FontWeight structure

Properti font-weight menentukan berat (atau ketebalan) font. Berat yang tersedia tergantung pada font-family yang saat ini diatur.

```csharp
public struct FontWeight : IEquatable<FontWeight>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.properties/fontweight/isabsolute) { get; } | Menunjukkan apakah instance font-weight ini menyimpan nilai absolut dari berat (ketebalan) font, sebagai bilangan bulat. |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontweight/isinitial) { get; } | Menunjukkan apakah font-size ini memiliki nilai awal (Medium). |
| [IsRelative](../../groupdocs.editor.htmlcss.css.properties/fontweight/isrelative) { get; } | Menunjukkan apakah instance font-weight ini menyimpan nilai relatif dari berat (ketebalan) font - dibandingkan dengan ketebalan elemen induk. |
| [Number](../../groupdocs.editor.htmlcss.css.properties/fontweight/number) { get; } | Mengembalikan sebuah angka - nilai integer antara 1 dan 1000, inklusif, yang menggambarkan ketebalan font, atau melemparkan pengecualian, jika ketebalan saat ini tidak absolut, melainkan relatif. |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontweight/value) { get; } | Mengembalikan nilai font-weight ini sebagai string. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [FromNumber](../../groupdocs.editor.htmlcss.css.properties/fontweight/fromnumber)(ushort) | Membuat font-weight dari angka yang ditentukan. |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontweight/equals#equals)(FontWeight) | Menentukan apakah instance FontWeight yang ditentukan sama. |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontweight/equals#equals_1)(object) | Menentukan apakah instance FontWeight ini sama dengan yang tidak dikast. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontweight/gethashcode)() | Mengembalikan hash-code untuk instance ini |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontweight/tryparse)(string, out FontWeight) | Mencoba mengurai string yang ditentukan dan mengembalikan instance FontWeight yang valid jika berhasil. |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontweight/op_equality) | Memeriksa apakah dua nilai "FontWeight" sama. |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontweight/op_inequality) | Memeriksa apakah dua nilai "FontWeight" tidak sama. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| static readonly [Bold](../../groupdocs.editor.htmlcss.css.properties/fontweight/bold) | Berat font tebal. Sama dengan 700. |
| static readonly [Bolder](../../groupdocs.editor.htmlcss.css.properties/fontweight/bolder) | Satu berat font relatif lebih berat daripada elemen induk. |
| static readonly [Lighter](../../groupdocs.editor.htmlcss.css.properties/fontweight/lighter) | Satu berat font relatif lebih ringan daripada elemen induk. |
| static readonly [Normal](../../groupdocs.editor.htmlcss.css.properties/fontweight/normal) | Berat font normal. Sama dengan 400. |

### Lihat Juga

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
