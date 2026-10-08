---
title: "SaveOneResource"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Metode instance yang dipicu selama pemanggilan metode Savegroupdocs.editor/editabledocument/save dan yang harus diimplementasikan oleh pengguna akhir untuk memperoleh dan menyimpan sumber daya HTML yang disediakan, kemudian mengembalikan tautan ke sumber daya ini kembali ke pemanggil."
type: docs
weight: 10
url: /id/net/groupdocs.editor.options/ihtmlsavingcallback/saveoneresource/
---
## IHtmlSavingCallback.SaveOneResource method

Metode instance, yang dipicu selama pemanggilan metode [`Save`](../../../groupdocs.editor/editabledocument/save) dan yang harus diimplementasikan oleh pengguna akhir untuk memperoleh dan menyimpan sumber daya HTML yang disediakan, kemudian mengembalikan tautan ke sumber daya ini kembali ke pemanggil.

```csharp
public string SaveOneResource(IHtmlResource resource)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sumber daya | IHtmlResource | Sumber daya HTML dari jenis apa pun (gambar dan font, mungkin stylesheet jika tidak disematkan dalam markup HTML), yang diberikan oleh GroupDocs.Editor ke implementasi antarmuka yang didefinisikan pengguna, diperoleh oleh pengguna, dan pengguna dapat melakukan prosedur apa pun yang diperlukan seperti menyimpan, mengirim, mengonversinya, dll. GroupDocs.Editor tidak akan pernah memberikan sumber daya HTML `null` ke metode ini. |

### Nilai Kembalian

Sebuah tautan (referensi) ke sumber daya, yang diperoleh dalam parameter *resource*, yang harus diberikan pengguna ke GroupDocs.Editor, sehingga GroupDocs.Editor akan menempatkan tautan ini ke dalam markup HTML.

### Catatan

GroupDocs.Editor mengharapkan bahwa implementasi metode ini yang didefinisikan pengguna tidak melempar pengecualian selama eksekusi. Namun, ketika pengecualian terjadi, GroupDocs.Editor akan menuliskan nilai properti [`FilenameWithExtension`](../../../groupdocs.editor.htmlcss.resources/ihtmlresource/filenamewithextension) ke dalam markup HTML.

### Lihat Juga

* interface [IHtmlResource](../../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* interface [IHtmlSavingCallback](../../ihtmlsavingcallback)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
