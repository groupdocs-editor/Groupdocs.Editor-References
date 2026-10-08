---
title: "MarkdownSaveOptions"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Memungkinkan untuk menentukan opsi khusus untuk menghasilkan dan menyimpan dokumen Markdown"
type: docs
weight: 1000
url: /id/net/groupdocs.editor.options/markdownsaveoptions/
---
## MarkdownSaveOptions class

Memungkinkan untuk menentukan opsi khusus untuk menghasilkan dan menyimpan dokumen Markdown

```csharp
public sealed class MarkdownSaveOptions : ISaveOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ExportImagesAsBase64](../../groupdocs.editor.options/markdownsaveoptions/exportimagesasbase64) { get; set; } | Menentukan apakah gambar disimpan dalam format Base64 ke file output. Defaultnya adalah `false`. |
| [ImagesFolder](../../groupdocs.editor.options/markdownsaveoptions/imagesfolder) { get; set; } | Menentukan folder fisik tempat gambar disimpan saat mengekspor dokumen ke format Markdown. Nilai default adalah null. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/markdownsaveoptions/optimizememoryusage) { get; set; } | Mengaktifkan mekanisme optimasi memori selama pembuatan dokumen dari HTML, yang mengurangi kinerja sebagai konsekuensi dari pengurangan penggunaan memori. Mengatur opsi ini ke `true` dapat secara signifikan mengurangi konsumsi memori saat menghasilkan dokumen besar dengan biaya waktu penyimpanan yang lebih lambat. Nilai default adalah `false` (optimasi memori dinonaktifkan demi kinerja yang lebih baik). |
| [TableContentAlignment](../../groupdocs.editor.options/markdownsaveoptions/tablecontentalignment) { get; set; } | Allow menentukan cara menyelaraskan konten dalam tabel saat mengekspor ke format Markdown. Nilai default adalah Auto. |

### Catatan

Kelas MarkdownSaveOptions harus diterapkan oleh pengguna ketika ada instance kelas EditableDocument, yang berisi konten dokumen yang telah diedit, dan diperlukan untuk menyimpan konten ini ke dokumen baru dengan format Markdown.

### Lihat Juga

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
