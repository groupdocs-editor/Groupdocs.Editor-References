---
title: "LocaleFarEast"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Memungkinkan untuk mengganti bahasa locale untuk dokumen WordProcessing untuk teks EastAsian yang akan diterapkan selama pembuatannya. Jika tidak ditentukan, nilai default MS Word atau program lain akan mendeteksi atau memilih locale EastAsian dokumen sesuai pengaturan atau faktor lainnya."
type: docs
weight: 60
url: /id/net/groupdocs.editor.options/wordprocessingsaveoptions/localefareast/
---
## WordProcessingSaveOptions.LocaleFarEast property

Mengizinkan untuk mengganti locale (bahasa) untuk dokumen WordProcessing untuk teks Asia Timur, yang akan diterapkan selama pembuatan. Jika tidak ditentukan (nilai default), MS Word (atau program lain) akan mendeteksi (atau memilih) locale Asia Timur dokumen sesuai dengan pengaturan sendiri atau faktor lain.

```csharp
public CultureInfo LocaleFarEast { get; set; }
```

### Catatan

Opsi ini memaksa penerapan locale yang ditentukan ke seluruh teks East-Asian dalam dokumen. Jangan gunakan jika dokumen berisi bagian teks yang berbeda, yang ditulis dalam bahasa yang berbeda.

### Lihat Juga

* class [WordProcessingSaveOptions](../../wordprocessingsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
