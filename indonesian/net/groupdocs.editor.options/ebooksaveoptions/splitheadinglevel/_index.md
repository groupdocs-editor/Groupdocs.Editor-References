---
title: "SplitHeadingLevel"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Menentukan tingkat maksimum heading yang akan dipisah pada file eBook. Nilai default adalah 2. Mengaturnya ke 0 akan menonaktifkan pemisahan sehingga semua konten eBook akan dimasukkan ke dalam satu paket di dalam file hasil."
type: docs
weight: 40
url: /id/net/groupdocs.editor.options/ebooksaveoptions/splitheadinglevel/
---
## EbookSaveOptions.SplitHeadingLevel property

Menentukan tingkat maksimum heading yang akan dipisah pada file e-Book. Nilai default adalah `2`. Mengatur menjadi `0` akan menonaktifkan pemisahan, sehingga semua konten e-Book akan dimasukkan ke dalam satu paket di dalam file hasil.

```csharp
public int SplitHeadingLevel { get; set; }
```

### Catatan

Ketika properti ini diatur ke nilai antara 1 hingga 9, dokumen akan dipisah pada paragraf yang diformat menggunakan gaya **Heading 1**, **Heading 2**, **Heading 3**, dll hingga tingkat heading yang ditentukan.

Secara default, hanya paragraf **Heading 1** dan **Heading 2** yang menyebabkan dokumen dipisah. Mengatur properti ini ke nol (atau kurang dari nol) akan membuat dokumen tidak dipisah pada paragraf heading sama sekali.

### Lihat Juga

* class [EbookSaveOptions](../../ebooksaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
