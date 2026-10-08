---
title: "EmailDocumentInfo"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mewakili metadata satu dokumen email dalam format email apa pun yang didukung"
type: docs
weight: 720
url: /id/net/groupdocs.editor.metadata/emaildocumentinfo/
---
## EmailDocumentInfo structure

Mewakili metadata satu dokumen email dalam format email apa pun yang didukung

```csharp
public struct EmailDocumentInfo : IDocumentInfo, IEquatable<EmailDocumentInfo>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/emaildocumentinfo/format) { get; } | Mengembalikan format dari dokumen email ini |
| [IsEncrypted](../../groupdocs.editor.metadata/emaildocumentinfo/isencrypted) { get; } | Karena dokumen email tidak dapat dienkripsi dengan kata sandi, properti ini selalu mengembalikan 'false' |
| [PageCount](../../groupdocs.editor.metadata/emaildocumentinfo/pagecount) { get; } | Selalu mengembalikan 1, karena dokumen email tidak memiliki tampilan berhalaman |
| [Size](../../groupdocs.editor.metadata/emaildocumentinfo/size) { get; } | Mengembalikan ukuran dalam byte dari dokumen email ini |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/emaildocumentinfo/equals#equals)(EmailDocumentInfo) | Menentukan apakah instance ini sama dengan instance EmailDocumentInfo lain yang ditentukan |

### Lihat Juga

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
