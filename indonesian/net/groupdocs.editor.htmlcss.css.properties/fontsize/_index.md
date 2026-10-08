---
title: "FontSize"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mewakili ukuran font sebagai satuan khusus atau nilai panjang yang menentukan ukuran font, secara historis lebar huruf kapital M."
type: docs
weight: 260
url: /id/net/groupdocs.editor.htmlcss.css.properties/fontsize/
---
## FontSize structure

Mewakili ukuran font sebagai satuan khusus atau nilai panjang, yang menentukan ukuran font (secara historis lebar huruf kapital \"M\").

```csharp
public struct FontSize : IEquatable<FontSize>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [IsAbsoluteSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isabsolutesize) { get; } | Menunjukkan apakah font-size ini didefinisikan dengan ukuran absolut sebagai kata kunci, berdasarkan ukuran font default pengguna (yang adalah medium). |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontsize/isinitial) { get; } | Menunjukkan apakah font-size ini memiliki nilai awal (Medium). |
| [IsLengthDefined](../../groupdocs.editor.htmlcss.css.properties/fontsize/islengthdefined) { get; } | Menunjukkan apakah font-size ini didefinisikan dengan nilai [`Length`](../../groupdocs.editor.htmlcss.css.datatypes/length). |
| [IsRelativeSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isrelativesize) { get; } | Menunjukkan apakah font-size ini didefinisikan dengan ukuran relatif sebagai kata kunci. Font akan menjadi lebih besar atau lebih kecil relatif terhadap ukuran font elemen induk, kira-kira dengan rasio yang digunakan untuk memisahkan kata kunci ukuran absolut. |
| [Length](../../groupdocs.editor.htmlcss.css.properties/fontsize/length) { get; } | Nilai panjang, jika font-size ini didefinisikan dengan nilai tersebut, atau melempar pengecualian sebaliknya. |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontsize/value) { get; } | Mengembalikan nilai ukuran font ini sebagai string. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [FromLength](../../groupdocs.editor.htmlcss.css.properties/fontsize/fromlength)(Length) | Membuat font-size dari panjang yang ditentukan. |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals)(FontSize) | Menentukan apakah instance font-size ini sama dengan yang ditentukan. |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals_1)(object) | Menentukan apakah instance font-size ini sama dengan yang belum di-cast. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontsize/gethashcode)() | Mengembalikan hash-code untuk instance ini |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontsize/tryparse)(string, out FontSize) | Mencoba mengenali kata kunci yang ditentukan sebagai nilai kata kunci yang tepat untuk 'font-size' dan mengembalikannya jika berhasil atau NULL jika gagal. |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_equality) | Memeriksa apakah dua nilai "FontSize" sama. |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_inequality) | Memeriksa apakah dua nilai "FontSize" tidak sama. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| static readonly [Large](../../groupdocs.editor.htmlcss.css.properties/fontsize/large) | Ukuran absolut yang biasanya besar. |
| static readonly [Larger](../../groupdocs.editor.htmlcss.css.properties/fontsize/larger) | Ukuran relatif lebih besar - font akan lebih besar relatif terhadap ukuran font elemen induk, kira-kira dengan rasio yang digunakan untuk memisahkan kata kunci ukuran absolut di atas. |
| static readonly [Medium](../../groupdocs.editor.htmlcss.css.properties/fontsize/medium) | Ukuran medium. Nilai awal. |
| static readonly [Small](../../groupdocs.editor.htmlcss.css.properties/fontsize/small) | Ukuran absolut yang biasanya kecil. |
| static readonly [Smaller](../../groupdocs.editor.htmlcss.css.properties/fontsize/smaller) | Ukuran relatif lebih kecil - font akan lebih kecil relatif terhadap ukuran font elemen induk, kira-kira dengan rasio yang digunakan untuk memisahkan kata kunci ukuran absolut di atas. |
| static readonly [XLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xlarge) | Ukuran absolut besar yang sedang. |
| static readonly [XSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xsmall) | Ukuran absolut kecil yang sedang. |
| static readonly [XxLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxlarge) | Ukuran absolut sangat besar. |
| static readonly [XxSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxsmall) | Ukuran absolut yang sangat kecil |

### Lihat Juga

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
