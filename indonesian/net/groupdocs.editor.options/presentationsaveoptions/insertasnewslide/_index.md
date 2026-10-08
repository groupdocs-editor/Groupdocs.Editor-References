---
title: "InsertAsNewSlide"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Bendera boolean yang menentukan apakah slide yang diedit harus menggantikan slide yang ada dalam presentasi asli pada posisi yang ditentukan oleh properti SlideNumbergroupdocs.editor.options/presentationsaveoptions/slidenumber atau harus disisipkan di antara slide yang ada dan slide sebelumnya tanpa mengganti isinya. Secara default adalah false, slide yang ada akan digantikan. Properti ini diabaikan jika nilai properti SlideNumbergroupdocs.editor.options/presentationsaveoptions/slidenumber diatur ke 0."
type: docs
weight: 20
url: /id/net/groupdocs.editor.options/presentationsaveoptions/insertasnewslide/
---
## PresentationSaveOptions.InsertAsNewSlide property

Bendera boolean, yang menentukan apakah slide yang diedit harus menggantikan slide yang ada dalam presentasi asli pada posisi yang ditentukan oleh properti [`SlideNumber`](../slidenumber), atau harus disisipkan di antara slide yang ada dan slide sebelumnya tanpa mengganti isinya. Secara default adalah `false` — slide yang ada akan digantikan. Properti ini diabaikan jika nilai properti [`SlideNumber`](../slidenumber) diatur ke `'0'`.

```csharp
public bool InsertAsNewSlide { get; set; }
```

### Catatan

Secara default slide digantikan. Ini berarti bahwa jika presentasi tersebut memiliki 5 slide, dan [`SlideNumber`](../slidenumber)=4, maka slide ke‑4 akan digantikan dengan slide yang baru diedit, sementara total jumlah slide dalam presentasi (5) tetap tidak berubah. Namun, jika nilai properti ini diatur ke true, slide yang baru diedit akan disisipkan sebagai slide ke‑4, dan semua slide berikutnya akan bergeser ke akhir: slide ke‑4 yang \"old\" menjadi ke‑5, dan slide ke‑5 menjadi ke‑6, sehingga total jumlah slide dalam presentasi akan bertambah satu menjadi 6.

### Lihat Juga

* class [PresentationSaveOptions](../../presentationsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
