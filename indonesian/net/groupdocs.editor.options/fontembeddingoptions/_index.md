---
title: "FontEmbeddingOptions"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Opsi penyematan font mengontrol sumber daya font mana yang harus disematkan ke dalam dokumen WordProcessing atau PDF output"
type: docs
weight: 880
url: /id/net/groupdocs.editor.options/fontembeddingoptions/
---
## FontEmbeddingOptions enumeration

Opsi penyematan font mengontrol sumber daya font mana yang harus disematkan ke dalam dokumen WordProcessing atau PDF output

```csharp
public enum FontEmbeddingOptions
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| NotEmbed | `0` | Jangan sematkan sumber daya font apa pun baik dari EditableDocument maupun dari sistem. Nilai default. |
| EmbedAll | `1` | Menganalisis konten dokumen dari EditableDocument input, menemukan semua font yang digunakan dan menyematkannya ke dalam dokumen WordProcessing atau PDF output. Pada awalnya GroupDocs.Editor mengambil font dari sumber daya font dalam EditableDocument. Jika tidak cukup atau tidak ada, maka GroupDocs.Editor mengambil font dari OS. |
| EmbedWithoutSystem | `2` | Sama dengan EmbedAll, tetapi mengecualikan font yang diperlakukan oleh OS sebagai font sistem. |

### Catatan

Opsi penyematan font diterapkan selama penyimpanan dokumen (dari EditableDocument menengah ke format WordProcessing atau PDF output), enum ini termasuk sebagai properti dalam WordProcessingSaveOptions dan PdfSaveOptions, yang harus digunakan.

### Lihat Juga

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
