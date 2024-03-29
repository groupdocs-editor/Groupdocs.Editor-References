---
title: Locale
second_title: GroupDocs.Editor untuk Referensi .NET API
description: Memungkinkan untuk mengatur override lokal default bahasa untuk dokumen WordProcessing yang akan diterapkan selama pembuatannya. Ketika tidak ditentukan nilai default MS Word atau program lain akan mendeteksi atau memilih dokumen locale sesuai ke pengaturannya sendiri atau faktor lain.
type: docs
weight: 40
url: /id/net/groupdocs.editor.options/wordprocessingsaveoptions/locale/
---
## WordProcessingSaveOptions.Locale property

Memungkinkan untuk mengatur override lokal default (bahasa) untuk dokumen WordProcessing, yang akan diterapkan selama pembuatannya. Ketika tidak ditentukan (nilai default), MS Word (atau program lain) akan mendeteksi (atau memilih) dokumen locale sesuai ke pengaturannya sendiri atau faktor lain.

```csharp
public CultureInfo Locale { get; set; }
```

### Perkataan

Opsi ini secara paksa menerapkan lokal yang ditentukan ke keseluruhan teks dalam dokumen. Jangan menggunakannya, jika dokumen berisi bagian teks yang berbeda, yang ditulis dalam bahasa yang berbeda.

### Lihat juga

* class [WordProcessingSaveOptions](../../wordprocessingsaveoptions)
* ruang nama [GroupDocs.Editor.Options](../../wordprocessingsaveoptions)
* perakitan [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
