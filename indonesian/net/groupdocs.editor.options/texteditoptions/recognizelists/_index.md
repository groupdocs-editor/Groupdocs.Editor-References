---
title: "RecognizeLists"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mengizinkan untuk menentukan bagaimana item daftar bernomor dikenali saat dokumen diimpor dari format teks biasa. Nilai default adalah true."
type: docs
weight: 60
url: /id/net/groupdocs.editor.options/texteditoptions/recognizelists/
---
## TextEditOptions.RecognizeLists property

Mengizinkan untuk menentukan bagaimana item daftar bernomor dikenali saat dokumen diimpor dari format teks biasa. Nilai default adalah true.

```csharp
public bool RecognizeLists { get; set; }
```

### Catatan

Jika opsi ini diatur ke false, algoritma pengenalan daftar mendeteksi paragraf daftar, ketika nomor daftar diakhiri dengan titik, kurung tutup kanan, atau simbol bullet (seperti "•", "*", "-" atau "o"). Jika opsi ini diatur ke true, spasi juga digunakan sebagai pembatas nomor daftar: algoritma pengenalan daftar untuk penomoran gaya Arab (1., 1.1.2.) menggunakan baik spasi maupun simbol titik (".").

### Lihat Juga

* class [TextEditOptions](../../texteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
