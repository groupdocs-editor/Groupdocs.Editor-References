---
title: SlideNumber
second_title: GroupDocs.Editor untuk Referensi .NET API
description: Memungkinkan untuk menentukan nomor slide yang harus dibuka untuk diedit
type: docs
weight: 30
url: /id/net/groupdocs.editor.options/presentationeditoptions/slidenumber/
---
## PresentationEditOptions.SlideNumber property

Memungkinkan untuk menentukan nomor slide, yang harus dibuka untuk diedit

```csharp
public int SlideNumber { get; set; }
```

### Perkataan

Nomor slide adalah indeks slide berbasis nol, yang memungkinkan untuk menentukan dan memilih satu slide tertentu dari presentasi untuk diedit. Jika lebih kecil dari 0, slide pertama akan dipilih (sama dengan SlideNumber = 0). Jika lebih besar dari jumlah semua slide dalam presentasi, slide terakhir akan dipilih. Jika presentasi masukan hanya berisi satu slide, opsi ini akan diabaikan, dan satu slide ini akan diedit. Jika mencoba membuka untuk mengedit slide tersembunyi, sementara[`ShowHiddenSlides`](../showhiddenslides) opsi diatur ke 'false', pengecualian akan dibuang.

### Lihat juga

* class [PresentationEditOptions](../../presentationeditoptions)
* ruang nama [GroupDocs.Editor.Options](../../presentationeditoptions)
* perakitan [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->