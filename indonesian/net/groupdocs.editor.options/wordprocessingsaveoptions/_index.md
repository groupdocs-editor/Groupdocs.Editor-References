---
title: "WordProcessingSaveOptions"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mengizinkan untuk menentukan opsi khusus untuk menghasilkan dan menyimpan dokumen yang mematuhi WordProcessing setelah mereka diedit"
type: docs
weight: 1240
url: /id/net/groupdocs.editor.options/wordprocessingsaveoptions/
---
## WordProcessingSaveOptions class

Memungkinkan untuk menentukan opsi khusus untuk menghasilkan dan menyimpan dokumen yang mematuhi WordProcessing setelah diedit

```csharp
public sealed class WordProcessingSaveOptions : ICloneable, ISaveOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor)() | Konstruktor tanpa parameter ini membuat instance baru dari WordProcessingSaveOptions dengan format output DOCX (dapat diubah kemudian melalui properti [`OutputFormat`](./outputformat)) |
| [WordProcessingSaveOptions](wordprocessingsaveoptions#constructor_1)(WordProcessingFormats) | Membuat instance baru dari WordProcessingSaveOptions dengan format output WordProcessing yang wajib ditentukan, sementara semua parameter lain menggunakan nilai default |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/wordprocessingsaveoptions/enablepagination) { get; set; } | Mengizinkan untuk mengaktifkan atau menonaktifkan paginasi yang akan digunakan untuk menyimpan dokumen WordProcessing. Jika dokumen asli dibuka dan diedit dalam mode paginasi, opsi ini juga harus diaktifkan. Secara default dinonaktifkan. |
| [FontEmbedding](../../groupdocs.editor.options/wordprocessingsaveoptions/fontembedding) { get; set; } | Bertanggung jawab untuk menyematkan sumber daya font ke dalam dokumen WordProcessing output. Secara default tidak menyematkan font apa pun (NotEmbed). |
| [Locale](../../groupdocs.editor.options/wordprocessingsaveoptions/locale) { get; set; } | Mengizinkan untuk mengatur penggantian locale (bahasa) default untuk dokumen WordProcessing, yang akan diterapkan selama pembuatan. Jika tidak ditentukan (nilai default), MS Word (atau program lain) akan mendeteksi (atau memilih) locale dokumen sesuai dengan pengaturan sendiri atau faktor lain. |
| [LocaleBi](../../groupdocs.editor.options/wordprocessingsaveoptions/localebi) { get; set; } | Mengizinkan untuk mengatur penggantian locale (bahasa) untuk dokumen WordProcessing untuk teks RTL (right-to-left), yang akan diterapkan selama pembuatan. Jika tidak ditentukan (nilai default), MS Word (atau program lain) akan mendeteksi (atau memilih) locale RTL dokumen sesuai dengan pengaturan sendiri atau faktor lain. |
| [LocaleFarEast](../../groupdocs.editor.options/wordprocessingsaveoptions/localefareast) { get; set; } | Mengizinkan untuk mengganti locale (bahasa) untuk dokumen WordProcessing untuk teks Asia Timur, yang akan diterapkan selama pembuatan. Jika tidak ditentukan (nilai default), MS Word (atau program lain) akan mendeteksi (atau memilih) locale Asia Timur dokumen sesuai dengan pengaturan sendiri atau faktor lain. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/wordprocessingsaveoptions/optimizememoryusage) { get; set; } | Mengaktifkan mekanisme optimasi memori selama pembuatan dokumen dari HTML, yang mengurangi kinerja sebagai biaya pengurangan penggunaan memori. Mengatur opsi ini ke true dapat secara signifikan mengurangi konsumsi memori saat menghasilkan dokumen besar dengan biaya waktu penyimpanan yang lebih lambat. Nilai default adalah false (optimasi memori dinonaktifkan demi kinerja yang lebih baik). |
| [OutputFormat](../../groupdocs.editor.options/wordprocessingsaveoptions/outputformat) { get; set; } | Mengizinkan untuk menentukan format WordProcessing, yang akan digunakan untuk menyimpan dokumen |
| [Password](../../groupdocs.editor.options/wordprocessingsaveoptions/password) { get; set; } | Mengizinkan untuk menentukan, memodifikasi, memperoleh, atau menghapus kata sandi, yang akan digunakan untuk mengenkripsi dokumen WordProcessing yang dihasilkan. Tentukan NULL atau string kosong untuk menghapus (membersihkan) kata sandi. |
| [Protection](../../groupdocs.editor.options/wordprocessingsaveoptions/protection) { get; set; } | Mengizinkan untuk mengontrol dan menerapkan opsi perlindungan dokumen untuk dokumen WordProcessing dalam format apa pun, yang mendukung perlindungan dokumen. Secara default NULL - perlindungan dokumen tidak akan digunakan. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Clone](../../groupdocs.editor.options/wordprocessingsaveoptions/clone)() | Membuat dan mengembalikan salinan penuh dari instance kelas WordProcessingSaveOptions ini |

### Catatan

WordProcessingSaveOptions diterapkan dalam situasi ketika ada instance kelas EditableDocument, yang berisi konten dokumen yang telah diedit, dan diperlukan untuk menyimpan konten ini ke dokumen baru dengan format WordProcessing.

### Lihat Juga

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
