---
title: "ExportCidUrls"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Menentukan apakah akan menggunakan URL CID ContentID untuk merujuk sumber daya gambar, font, CSS yang termasuk dalam dokumen MHTML. Nilai default adalah false."
type: docs
weight: 20
url: /id/net/groupdocs.editor.options/mhtmlsaveoptions/exportcidurls/
---
## MhtmlSaveOptions.ExportCidUrls property

Menentukan apakah akan menggunakan URL CID (Content-ID) untuk merujuk sumber daya (gambar, font, CSS) yang termasuk dalam dokumen MHTML. Nilai default adalah `false`.

```csharp
public bool ExportCidUrls { get; set; }
```

### Catatan

Secara default, sumber daya dalam dokumen MHTML dirujuk dengan nama file (misalnya, "image.png"), yang dicocokkan dengan header "Content-Location" pada bagian MIME. Opsi ini mengaktifkan metode alternatif, di mana referensi ke file sumber daya ditulis sebagai URL CID (Content-ID) (misalnya, "cid:image.png") dan dicocokkan dengan header "Content-ID".

Secara teori, tidak seharusnya ada perbedaan antara dua metode referensi tersebut dan keduanya harus berfungsi baik di semua peramban atau agen email. Namun dalam praktik, beberapa agen gagal mengambil sumber daya berdasarkan nama file. Jika peramban atau agen email Anda menolak memuat sumber daya yang termasuk dalam dokumen MTHML (tidak menampilkan gambar atau tidak memuat gaya CSS), coba ekspor dokumen dengan URL CID.

### Lihat Juga

* class [MhtmlSaveOptions](../../mhtmlsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
