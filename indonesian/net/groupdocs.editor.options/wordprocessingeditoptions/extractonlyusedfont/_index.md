---
title: "ExtractOnlyUsedFont"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mendapatkan atau menetapkan nilai yang menunjukkan apakah hanya mengekstrak sumber daya font yang digunakan dalam konten teks dokumen."
type: docs
weight: 40
url: /id/net/groupdocs.editor.options/wordprocessingeditoptions/extractonlyusedfont/
---
## WordProcessingEditOptions.ExtractOnlyUsedFont property

Mendapatkan atau menetapkan nilai yang menunjukkan apakah hanya mengekstrak sumber daya font yang digunakan dalam konten teks dokumen.

```csharp
public bool ExtractOnlyUsedFont { get; set; }
```

### Property Value

`true` jika diperlukan untuk mengekstrak hanya sumber daya font yang digunakan dalam konten teks dokumen; jika tidak, `false`. Nilai default adalah `false`.

### Catatan

Tidak semua font yang digunakan dalam dokumen WordProcessing digunakan secara langsung 100% (diterapkan pada teks). Mungkin ada situasi di mana font direferensikan dalam dokumen dan bahkan dapat disematkan, tetapi tidak diterapkan pada bagian teks manapun. Misalnya, beberapa font dapat terikat pada suatu gaya, tetapi gaya tersebut tidak diterapkan pada bagian teks mana pun. Opsi ini mengontrol cara memproses kasus seperti itu.

### Lihat Juga

* class [WordProcessingEditOptions](../../wordprocessingeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
