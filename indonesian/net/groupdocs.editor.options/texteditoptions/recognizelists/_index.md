---
title: RecognizeLists
second_title: GroupDocs.Editor untuk Referensi .NET API
description: Memungkinkan untuk menentukan bagaimana item daftar bernomor dikenali saat dokumen diimpor dari format teks biasa. Nilai defaultnya adalah true.
type: docs
weight: 60
url: /id/net/groupdocs.editor.options/texteditoptions/recognizelists/
---
## TextEditOptions.RecognizeLists property

Memungkinkan untuk menentukan bagaimana item daftar bernomor dikenali saat dokumen diimpor dari format teks biasa. Nilai defaultnya adalah true.

```csharp
public bool RecognizeLists { get; set; }
```

### Perkataan

Jika opsi ini disetel ke salah, algoritme pengenalan daftar mendeteksi paragraf daftar, ketika nomor daftar diakhiri dengan titik, tanda kurung siku kanan, atau simbol poin (seperti "•", "*", "-", atau "o"). Jika opsi ini disetel ke true, spasi putih juga digunakan sebagai pembatas nomor daftar: algoritme pengenalan daftar untuk penomoran gaya Arab (1., 1.1.2.) menggunakan spasi putih dan simbol titik (".").

### Lihat juga

* class [TextEditOptions](../../texteditoptions)
* ruang nama [GroupDocs.Editor.Options](../../texteditoptions)
* perakitan [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
