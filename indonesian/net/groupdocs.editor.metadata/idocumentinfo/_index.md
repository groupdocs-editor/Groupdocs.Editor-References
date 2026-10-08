---
title: "IDocumentInfo"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Antarmuka umum untuk semua pembungkus metadata file"
type: docs
weight: 740
url: /id/net/groupdocs.editor.metadata/idocumentinfo/
---
## IDocumentInfo interface

Antarmuka umum untuk semua pembungkus metadata file

```csharp
public interface IDocumentInfo
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/idocumentinfo/format) { get; } | Dalam tipe implementasi, harus mengembalikan format dokumen sebagai nilai tunggal dari sebuah tipe, yang mewakili satu keluarga format dan mewarisi dari antarmuka IDocumentFormat |
| [IsEncrypted](../../groupdocs.editor.metadata/idocumentinfo/isencrypted) { get; } | Menunjukkan apakah file tertentu terenkripsi dan memerlukan kata sandi untuk dibuka. Untuk tipe dokumen yang tidak dapat dienkripsi (seperti semua berbasis teks) harus selalu mengembalikan 'false'. |
| [PageCount](../../groupdocs.editor.metadata/idocumentinfo/pagecount) { get; } | Dalam tipe implementasi, harus mengembalikan jumlah (angka) halaman atau entitas serupa yang bergantung pada format (tab, slide, dll.). Untuk tipe keluarga tersebut yang tidak memiliki hal serupa (seperti dokumen teks biasa atau XML) harus mengembalikan 1. |
| [Size](../../groupdocs.editor.metadata/idocumentinfo/size) { get; } | Ukuran dokumen dalam byte |

### Lihat Juga

* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
