---
title: EmailDocumentInfo
second_title: GroupDocs.Editor untuk Referensi .NET API
description: Merupakan metadata dari satu dokumen email dari semua format email yang didukung
type: docs
weight: 720
url: /id/net/groupdocs.editor.metadata/emaildocumentinfo/
---
## EmailDocumentInfo structure

Merupakan metadata dari satu dokumen email dari semua format email yang didukung

```csharp
public struct EmailDocumentInfo : IDocumentInfo, IEquatable<EmailDocumentInfo>
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/emaildocumentinfo/format) { get; } | Mengembalikan format dokumen email ini |
| [IsEncrypted](../../groupdocs.editor.metadata/emaildocumentinfo/isencrypted) { get; } | Karena dokumen email tidak dapat dienkripsi dengan kata sandi, properti ini selalu menghasilkan 'false' |
| [PageCount](../../groupdocs.editor.metadata/emaildocumentinfo/pagecount) { get; } | Selalu mengembalikan 1, karena dokumen email tidak memiliki tampilan halaman |
| [Size](../../groupdocs.editor.metadata/emaildocumentinfo/size) { get; } | Mengembalikan ukuran dalam byte dari dokumen email ini |

## Metode

| Nama | Keterangan |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/emaildocumentinfo/equals#equals)(EmailDocumentInfo) | Menentukan apakah instance ini sama dengan instance EmailDocumentInfo lain yang ditentukan |

### Lihat juga

* interface [IDocumentInfo](../idocumentinfo)
* ruang nama [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* perakitan [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->