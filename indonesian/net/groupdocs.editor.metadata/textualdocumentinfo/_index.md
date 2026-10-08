---
title: "TextualDocumentInfo"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mewakili metadata dari satu dokumen teks seperti XML HTML atau teks biasa TXT"
type: docs
weight: 780
url: /id/net/groupdocs.editor.metadata/textualdocumentinfo/
---
## TextualDocumentInfo structure

Mewakili metadata satu dokumen teks seperti XML, HTML, atau teks biasa (TXT)

```csharp
public struct TextualDocumentInfo : IDocumentInfo
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Encoding](../../groupdocs.editor.metadata/textualdocumentinfo/encoding) { get; } | Mengembalikan encoding yang terdeteksi kemungkinan dari dokumen teks |
| [Format](../../groupdocs.editor.metadata/textualdocumentinfo/format) { get; } | Mengembalikan format dokumen tekstual ini. Mungkin tidak 100% tepat dalam beberapa kasus. |
| [IsEncrypted](../../groupdocs.editor.metadata/textualdocumentinfo/isencrypted) { get; } | Selalu mengembalikan ``false``, karena dokumen tekstual tidak dapat dienkripsi |
| [PageCount](../../groupdocs.editor.metadata/textualdocumentinfo/pagecount) { get; } | Selalu mengembalikan 1 |
| [Size](../../groupdocs.editor.metadata/textualdocumentinfo/size) { get; } | Mengembalikan ukuran dalam byte (bukan jumlah karakter) dari dokumen tekstual ini |

### Lihat Juga

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
