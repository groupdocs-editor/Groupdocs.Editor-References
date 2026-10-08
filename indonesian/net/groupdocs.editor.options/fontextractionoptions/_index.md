---
title: "FontExtractionOptions"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Opsi ekstraksi font mengontrol font mana yang harus diekstrak dan dari mana"
type: docs
weight: 890
url: /id/net/groupdocs.editor.options/fontextractionoptions/
---
## FontExtractionOptions enumeration

Opsi ekstraksi font mengontrol font mana yang harus diekstrak dan dari mana

```csharp
public enum FontExtractionOptions
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| NotExtract | `0` | Tidak mengekstrak sumber daya font apa pun baik dari dokumen maupun dari sistem. Nilai default. |
| ExtractAllEmbedded | `1` | Mengekstrak semua sumber daya font yang disematkan ke dalam dokumen Word input, terlepas dari apa jenisnya: khusus atau sistem. |
| ExtractEmbeddedWithoutSystem | `2` | Mengekstrak hanya sumber daya font yang disematkan yang bersifat khusus (bukan sistem). |
| ExtractAll | `3` | Mencoba mengekstrak semua font yang digunakan dalam dokumen WordProcessing input, termasuk font sistem. |

### Lihat Juga

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
