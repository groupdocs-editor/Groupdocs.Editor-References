---
title: "XpsSaveOptions"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Memungkinkan untuk menentukan opsi khusus untuk menghasilkan dan menyimpan dokumen XPS XML Paper Specifications"
type: docs
weight: 1300
url: /id/net/groupdocs.editor.options/xpssaveoptions/
---
## XpsSaveOptions class

Memungkinkan untuk menentukan opsi khusus untuk menghasilkan dan menyimpan dokumen XPS (XML Paper Specifications)

```csharp
public sealed class XpsSaveOptions : ISaveOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [XpsSaveOptions](xpssaveoptions)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/xpssaveoptions/optimizememoryusage) { get; set; } | Mengaktifkan mekanisme optimasi memori selama pembuatan dokumen dari HTML, yang mengurangi kinerja sebagai biaya pengurangan penggunaan memori. Mengatur opsi ini ke true dapat secara signifikan mengurangi konsumsi memori saat menghasilkan dokumen besar dengan biaya waktu penyimpanan yang lebih lambat. Nilai default adalah false (optimasi memori dinonaktifkan demi kinerja yang lebih baik). |

### Catatan

File XPS mewakili file tata letak halaman yang berbasis pada XML Paper Specifications yang dibuat oleh Microsoft. File ini dikembangkan sebagai pengganti format file EMF dan mirip dengan format file PDF, tetapi menggunakan XML dalam informasi tata letak, tampilan, dan pencetakan dokumen.

### Lihat Juga

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
