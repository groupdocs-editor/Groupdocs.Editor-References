---
title: "PdfSaveOptions"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Memungkinkan menentukan opsi khusus untuk menghasilkan dan menyimpan dokumen PDF Portable Document Format."
type: docs
weight: 1070
url: /id/net/groupdocs.editor.options/pdfsaveoptions/
---
## PdfSaveOptions class

Memungkinkan untuk menentukan opsi khusus untuk menghasilkan dan menyimpan dokumen PDF (Portable Document Format)

```csharp
public sealed class PdfSaveOptions : ISaveOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Compliance](../../groupdocs.editor.options/pdfsaveoptions/compliance) { get; set; } | Menentukan tingkat kepatuhan standar PDF untuk dokumen output. Default adalah PdfCompliance.Pdf17. |
| [FontEmbedding](../../groupdocs.editor.options/pdfsaveoptions/fontembedding) { get; set; } | Bertanggung jawab untuk menyematkan sumber daya font yang digunakan dalam dokumen asli ke dalam dokumen PDF hasil. Secara default tidak menyematkan font apa pun (NotEmbed). |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/pdfsaveoptions/optimizememoryusage) { get; set; } | Mengaktifkan mekanisme optimasi memori selama pembuatan dokumen dari HTML, yang mengurangi kinerja sebagai biaya pengurangan penggunaan memori. Mengatur opsi ini ke true dapat secara signifikan mengurangi konsumsi memori saat menghasilkan dokumen besar dengan biaya waktu penyimpanan yang lebih lambat. Nilai default adalah false (optimasi memori dinonaktifkan demi kinerja yang lebih baik). |
| [Password](../../groupdocs.editor.options/pdfsaveoptions/password) { get; set; } | Kata sandi yang akan diterapkan pada dokumen PDF yang dihasilkan sebagai kata sandi pengguna, diperlukan untuk membuka. Jika NULL atau kosong, tidak ada kata sandi yang akan diterapkan pada dokumen. Jika tidak, dokumen akan dienkripsi dengan RC4 (panjang kunci 128 bit). Secara default adalah NULL — kata sandi tidak diterapkan. |

### Lihat Juga

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
