---
title: "FontType"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mewakili satu jenis font yang didukung"
type: docs
weight: 360
url: /id/net/groupdocs.editor.htmlcss.resources.fonts/fonttype/
---
## FontType structure

Mewakili satu jenis font yang didukung

```csharp
public struct FontType : IEquatable<FontType>, IResourceType
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| static [Eot](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/eot) { get; } | Mewakili tipe font EOT (Embedded OpenType) |
| static [Otf](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/otf) { get; } | Mewakili tipe font OTF (OpenType Font) |
| static [Ttc](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/ttc) { get; } | Mewakili font TrueType Collection (TTC) |
| static [Ttf](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/ttf) { get; } | Mewakili tipe font TTF (TrueType Font) |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/undefined) { get; } | Nilai khusus, yang menandai sumber daya font yang tidak terdefinisi, tidak diketahui, atau tidak didukung |
| static [Woff](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/woff) { get; } | Mewakili tipe font WOFF (Web Open Font Format) |
| static [Woff2](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/woff2) { get; } | Mewakili tipe font WOFF2 (Web Open Font Format versi 2) |
| [CssName](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/cssname) { get; } | Mengembalikan nama yang kompatibel dengan CSS untuk tipe font ini, yang digunakan dalam aturan @font-face |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/fileextension) { get; } | Ekstensi nama file (tanpa karakter titik) untuk tipe font ini |
| [FontFormat](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/fontformat) { get; } | Format font untuk format @font-face |
| [FormalName](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/formalname) { get; } | Mengembalikan nama formal untuk tipe font ini |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/mimecode) { get; } | Kode MIME untuk tipe font tertentu |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [GetFirstDefined](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/getfirstdefined)(params FontType[]) | Mengembalikan tipe font pertama dari set yang ditentukan, yang bukan nilai "Undefined", atau tipe font "Undefined" sebaliknya (ketika semua item adalah "Undefined") |
| static [ParseFromCssName](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/parsefromcssname)(string) | Mengembalikan nilai FontType, yang setara dengan nama yang kompatibel dengan CSS yang ditentukan untuk tipe font |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/parsefromfilenamewithextension)(string) | Mengembalikan nilai FontType, yang setara dengan ekstensi nama file, yang diekstrak dari nama file yang ditentukan |
| static [ParseFromMime](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/parsefrommime)(string) | Mengembalikan nilai FontType, yang setara dengan kode MIME yang ditentukan |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/equals#equals)(FontType) | Menentukan apakah instance ini sama dengan instance "FontType" yang ditentukan |
| override [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/equals#equals_1)(object) | Menentukan apakah instance ini sama dengan objek yang tidak dikast yang ditentukan, yang kemungkinan merupakan instance "FontType" lain |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/gethashcode)() | Mengembalikan kode hash, yang merupakan angka konstan untuk tipe nilai spesifik ini |
| [operator ==](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/op_equality) | Memeriksa apakah dua nilai "FontType" sama |
| [operator !=](../../groupdocs.editor.htmlcss.resources.fonts/fonttype/op_inequality) | Memeriksa apakah dua nilai "FontType" tidak sama |

### Lihat Juga

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
