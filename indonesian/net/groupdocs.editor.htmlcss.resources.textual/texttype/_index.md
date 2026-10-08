---
title: "TextType"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mewakili satu tipe sumber daya teks yang dapat didukung"
type: docs
weight: 640
url: /id/net/groupdocs.editor.htmlcss.resources.textual/texttype/
---
## TextType structure

Mewakili satu tipe sumber daya teks yang dapat didukung

```csharp
public struct TextType : IEquatable<TextType>, IResourceType
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| static [Css](../../groupdocs.editor.htmlcss.resources.textual/texttype/css) { get; } | Tipe CSS dari sumber tekstual |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.textual/texttype/undefined) { get; } | Nilai khusus, yang menandai sumber tekstual yang tidak terdefinisi, tidak diketahui, atau tidak didukung |
| static [Xml](../../groupdocs.editor.htmlcss.resources.textual/texttype/xml) { get; } | Tipe XML dari sumber tekstual |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.textual/texttype/fileextension) { get; } | Ekstensi file (tanpa karakter titik di depan) dari sumber tekstual tertentu |
| [FormalName](../../groupdocs.editor.htmlcss.resources.textual/texttype/formalname) { get; } | Mengembalikan nama resmi dari tipe sumber tekstual ini |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.textual/texttype/mimecode) { get; } | Kode MIME dari tipe sumber tekstual tertentu |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.textual/texttype/parsefromfilenamewithextension)(string) | Mengembalikan nilai TextType, yang setara dengan ekstensi nama file, yang diekstrak dari nama file yang ditentukan dengan ekstensi atau ekstensi murni |
| override [Equals](../../groupdocs.editor.htmlcss.resources.textual/texttype/equals#equals_1)(object) | Menentukan apakah instance ini sama dengan objek yang tidak dikast secara spesifik, yang kemungkinan adalah instance "TextType" lain |
| [Equals](../../groupdocs.editor.htmlcss.resources.textual/texttype/equals#equals)(TextType) | Menentukan apakah instance ini sama dengan instance "TextType" yang ditentukan |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.textual/texttype/gethashcode)() | Mengembalikan kode hash, yang merupakan angka konstan untuk tipe nilai spesifik ini |
| [operator ==](../../groupdocs.editor.htmlcss.resources.textual/texttype/op_equality) | Mendefinisikan apakah dua instance "TextType" tertentu sama |
| [operator !=](../../groupdocs.editor.htmlcss.resources.textual/texttype/op_inequality) | Mendefinisikan apakah dua instance "TextType" tertentu tidak sama |

### Lihat Juga

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Textual](../../groupdocs.editor.htmlcss.resources.textual)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
