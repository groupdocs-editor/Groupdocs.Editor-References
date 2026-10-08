---
title: "SlideNumber"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Memungkinkan menentukan nomor slide yang harus dibuka untuk diedit."
type: docs
weight: 30
url: /id/net/groupdocs.editor.options/presentationeditoptions/slidenumber/
---
## PresentationEditOptions.SlideNumber property

Memungkinkan menentukan nomor slide yang harus dibuka untuk diedit

```csharp
public int SlideNumber { get; set; }
```

### Catatan

Nomor slide adalah indeks berbasis nol dari sebuah slide, yang memungkinkan menentukan dan memilih satu slide tertentu dari presentasi untuk diedit. Jika kurang dari 0, slide pertama akan dipilih (sama dengan SlideNumber = 0). Jika lebih besar dari jumlah semua slide dalam presentasi, slide terakhir akan dipilih. Jika presentasi input hanya berisi satu slide, opsi ini akan diabaikan, dan slide tunggal tersebut akan diedit. Jika mencoba membuka slide tersembunyi untuk diedit, sementara opsi [`ShowHiddenSlides`](../showhiddenslides) disetel ke 'false', pengecualian akan dilempar.

### Lihat Juga

* class [PresentationEditOptions](../../presentationeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
