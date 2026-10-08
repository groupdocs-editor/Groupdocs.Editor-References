---
title: "LocaleBi"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Memungkinkan untuk mengatur bahasa locale yang menggantikan untuk dokumen WordProcessing untuk teks RTL (right-to-left) yang akan diterapkan selama pembuatannya. Jika tidak ditentukan, nilai default MS Word atau program lain akan mendeteksi atau memilih locale RTL dokumen sesuai pengaturan atau faktor lainnya."
type: docs
weight: 50
url: /id/net/groupdocs.editor.options/wordprocessingsaveoptions/localebi/
---
## WordProcessingSaveOptions.LocaleBi property

Mengizinkan untuk mengatur penggantian locale (bahasa) untuk dokumen WordProcessing untuk teks RTL (right-to-left), yang akan diterapkan selama pembuatan. Jika tidak ditentukan (nilai default), MS Word (atau program lain) akan mendeteksi (atau memilih) locale RTL dokumen sesuai dengan pengaturan sendiri atau faktor lain.

```csharp
public CultureInfo LocaleBi { get; set; }
```

### Catatan

Opsi ini memaksa penerapan locale yang ditentukan ke seluruh teks RTL dalam dokumen. Jangan gunakan jika dokumen berisi bagian teks yang berbeda, yang ditulis dalam bahasa yang berbeda.

### Lihat Juga

* class [WordProcessingSaveOptions](../../wordprocessingsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
