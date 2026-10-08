---
title: "Locale"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Memungkinkan untuk mengatur penggantian bahasa locale default untuk dokumen WordProcessing yang akan diterapkan selama pembuatannya. Jika tidak ditentukan, nilai default MS Word atau program lain akan mendeteksi atau memilih locale dokumen sesuai pengaturan atau faktor lainnya."
type: docs
weight: 40
url: /id/net/groupdocs.editor.options/wordprocessingsaveoptions/locale/
---
## WordProcessingSaveOptions.Locale property

Mengizinkan untuk mengatur penggantian locale (bahasa) default untuk dokumen WordProcessing, yang akan diterapkan selama pembuatan. Jika tidak ditentukan (nilai default), MS Word (atau program lain) akan mendeteksi (atau memilih) locale dokumen sesuai dengan pengaturan sendiri atau faktor lain.

```csharp
public CultureInfo Locale { get; set; }
```

### Catatan

Opsi ini memaksa penerapan locale yang ditentukan ke seluruh teks dalam dokumen. Jangan gunakan jika dokumen berisi bagian teks yang berbeda, yang ditulis dalam bahasa yang berbeda.

### Lihat Juga

* class [WordProcessingSaveOptions](../../wordprocessingsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
