---
title: "AudioType"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mewakili satu format tipe audio yang dapat didukung"
type: docs
weight: 320
url: /id/net/groupdocs.editor.htmlcss.resources.audio/audiotype/
---
## AudioType structure

Mewakili satu tipe audio yang didukung (format)

```csharp
public struct AudioType : IEquatable<AudioType>, IResourceType
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| static [Mp3](../../groupdocs.editor.htmlcss.resources.audio/audiotype/mp3) { get; } | Mewakili format audio MPEG-1 Audio Layer III |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.audio/audiotype/undefined) { get; } | Nilai khusus, yang menandai format audio yang tidak terdefinisi, tidak diketahui, atau tidak didukung |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.audio/audiotype/fileextension) { get; } | Ekstensi nama file (tanpa karakter titik) untuk format audio ini |
| [FormalName](../../groupdocs.editor.htmlcss.resources.audio/audiotype/formalname) { get; } | Nama resmi dari format audio ini |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.audio/audiotype/mimecode) { get; } | Kode MIME untuk format audio ini |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.audio/audiotype/parsefromfilenamewithextension)(string) | Mengembalikan nilai AudioType, yang setara dengan ekstensi nama file, yang diekstrak dari nama file yang ditentukan |
| [Equals](../../groupdocs.editor.htmlcss.resources.audio/audiotype/equals#equals)(AudioType) | Menentukan apakah instance ini sama dengan instance "AudioType" yang ditentukan |
| override [Equals](../../groupdocs.editor.htmlcss.resources.audio/audiotype/equals#equals_1)(object) | Menentukan apakah instance ini sama dengan objek yang tidak dikast secara spesifik, yang kemungkinan merupakan instance "AudioType" lain |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.audio/audiotype/gethashcode)() | Mengembalikan kode hash, yang merupakan angka konstan untuk tipe nilai spesifik ini |
| [operator ==](../../groupdocs.editor.htmlcss.resources.audio/audiotype/op_equality) | Memeriksa apakah dua nilai "AudioType" sama |
| [operator !=](../../groupdocs.editor.htmlcss.resources.audio/audiotype/op_inequality) | Memeriksa apakah dua nilai "AudioType" tidak sama |

### Lihat Juga

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Audio](../../groupdocs.editor.htmlcss.resources.audio)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
