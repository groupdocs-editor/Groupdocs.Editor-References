---
title: "SlideNumbersToDelete"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Memungkinkan untuk menentukan array dengan nomor slide berbasis 1 yang harus dihapus dari presentasi saat penyimpanan jika slide yang diedit disisipkan ke dalam presentasi yang ada."
type: docs
weight: 60
url: /id/net/groupdocs.editor.options/presentationsaveoptions/slidenumberstodelete/
---
## PresentationSaveOptions.SlideNumbersToDelete property

Memungkinkan menentukan array dengan nomor slide berbasis 1 yang harus dihapus dari presentasi saat disimpan, dalam kasus slide yang diedit disisipkan ke dalam presentasi yang ada.

```csharp
public int[] SlideNumbersToDelete { get; set; }
```

### Catatan

Ketika slide yang diedit disimpan bukan sebagai presentasi slide tunggal baru (perilaku default), melainkan disimpan ke dalam presentasi yang ada (menggunakan properti [`SlideNumber`](../slidenumber)), juga dimungkinkan untuk menghapus beberapa slide tertentu dari presentasi ini dengan menentukan nomor mereka dalam array ini.

Secara default array ini adalah `null` — tidak ada slide yang akan dihapus. Namun, ketika array ini tidak null dan tidak kosong, serta berisi setidaknya satu nomor slide yang valid, setelah dokumen Presentation output dihasilkan dengan konten slide yang diedit, slide dengan nomor yang ditentukan akan dihapus dari presentasi tepat sebelum menulis isinya ke aliran output atau file.

Nomor slide dalam array ini berbasis 1, bukan 0; nomor yang tidak valid (kurang dari 1 atau lebih besar dari total jumlah slide) akan diabaikan.

### Lihat Juga

* class [PresentationSaveOptions](../../presentationsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
