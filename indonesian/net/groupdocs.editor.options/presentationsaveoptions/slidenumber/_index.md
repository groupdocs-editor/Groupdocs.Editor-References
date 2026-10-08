---
title: "SlideNumber"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Memungkinkan untuk menyisipkan slide yang diedit ke dalam presentasi yang ada alih-alih membuat presentasi slide tunggal baru (perilaku default). Nomor slide adalah nomor berbasis 1 dari sebuah slide dalam presentasi yang dimuat di kelas Editor. Jika nilainya 0 (nilai default), presentasi baru akan dibuat dengan satu slide yang diedit. Jika nilainya lebih besar atau lebih kecil dari nol dan ada presentasi yang valid dimuat di kelas Editor, slide yang diedit yang disimpan dalam instance EditableDocument input akan disisipkan ke dalam presentasi tersebut."
type: docs
weight: 50
url: /id/net/groupdocs.editor.options/presentationsaveoptions/slidenumber/
---
## PresentationSaveOptions.SlideNumber property

Memungkinkan menyisipkan slide yang diedit ke dalam presentasi yang ada alih-alih membuat presentasi satu slide baru (perilaku default). Nomor slide adalah nomor berbasis 1 dari slide dalam presentasi yang dimuat di kelas Editor. Jika nilainya 0 (nilai default), presentasi baru akan dibuat dengan satu slide yang diedit. Jika nilainya lebih besar atau lebih kecil dari nol, dan ada presentasi yang valid, dimuat di kelas Editor, slide yang diedit, yang disimpan di dalam instance EditableDocument input, akan disisipkan ke dalam presentasi tersebut.

```csharp
public int SlideNumber { get; set; }
```

### Catatan

Properti integer SlideNumber, jika tidak berada dalam keadaan default (nilai cadangan '0'), mewakili nomor slide, sehingga dimulai dari 1, bukan nol, dan nilai maksimumnya adalah jumlah semua slide yang ada dalam sebuah presentasi. Namun, jika nilai yang ditentukan lebih besar daripada jumlah semua slide, GroupDocs.Editor akan menyesuaikannya untuk menandai slide terakhir. Nilai negatif juga diperbolehkan dan menghitung slide dari akhir. Misalnya, "-1" berarti slide terakhir dalam presentasi, "-2" — slide terakhir kedua, dll. Seperti halnya nilai positif, ketika nomor slide negatif melebihi total jumlah slide dalam presentasi yang diberikan, itu akan disesuaikan ke slide pertama. Properti boolean [`InsertAsNewSlide`](../insertasnewslide) sangat terkait dengan properti ini.

### Contoh

Presentasi yang diberikan memiliki 5 slide: SlideNumber = 0; — mengabaikan presentasi yang diberikan, membuat presentasi baru dan menempatkan slide yang diedit di dalamnya. SlideNumber = 1; — mengganti slide pertama dengan yang diedit. SlideNumber = 2; — mengganti slide kedua dengan yang diedit. SlideNumber = 5; — mengganti slide terakhir (ke‑5) dengan yang diedit. SlideNumber = 6; — mengganti slide terakhir (ke‑5) dengan yang diedit, karena 6 lebih besar dari 5 sehingga disesuaikan. SlideNumber = -1; — mengganti slide terakhir (ke‑5) dengan yang diedit, karena "-1" berarti "yang terakhir ada". SlideNumber = -2; — mengganti slide ke‑4 dengan yang diedit. SlideNumber = -3; — mengganti slide ke‑3 dengan yang diedit. SlideNumber = -4; — mengganti slide ke‑2 dengan yang diedit. SlideNumber = -5; — mengganti slide pertama dengan yang diedit. SlideNumber = -6; — mengganti slide pertama dengan yang diedit, karena "-6" lebih besar dari 5 sehingga disesuaikan.

### Lihat Juga

* class [PresentationSaveOptions](../../presentationsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
