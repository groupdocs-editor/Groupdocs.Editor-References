---
title: "PresentationSaveOptions"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Memungkinkan menentukan opsi khusus untuk menghasilkan dan menyimpan dokumen Presentasi yang kompatibel dengan PowerPoint."
type: docs
weight: 1100
url: /id/net/groupdocs.editor.options/presentationsaveoptions/
---
## PresentationSaveOptions class

Memungkinkan untuk menentukan opsi khusus untuk menghasilkan dan menyimpan dokumen Presentasi (kompatibel dengan PowerPoint)

```csharp
public sealed class PresentationSaveOptions : ISaveOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PresentationSaveOptions](presentationsaveoptions#constructor)() | Konstruktor tanpa parameter ini membuat instance baru dari PresentationSaveOptions dengan format output PPTX (dapat diubah kemudian melalui properti [`OutputFormat`](./outputformat)). |
| [PresentationSaveOptions](presentationsaveoptions#constructor_1)(PresentationFormats) | Membuat instance baru dari PresentationSaveOptions dengan format output Presentasi yang wajib ditentukan, sementara semua parameter lain menggunakan nilai default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [InsertAsNewSlide](../../groupdocs.editor.options/presentationsaveoptions/insertasnewslide) { get; set; } | Flag boolean yang menentukan apakah slide yang diedit harus menggantikan slide yang ada dalam presentasi asli pada posisi yang ditentukan oleh properti [`SlideNumber`](./slidenumber), atau harus disisipkan di antara slide yang ada dan slide sebelumnya, tanpa mengganti isinya. Secara default adalah `false` — slide yang ada akan digantikan. Properti ini diabaikan jika nilai properti [`SlideNumber`](./slidenumber) diatur ke `'0'.` |
| [OutputFormat](../../groupdocs.editor.options/presentationsaveoptions/outputformat) { get; set; } | Memungkinkan menentukan format Presentasi yang akan digunakan untuk menyimpan dokumen. |
| [Password](../../groupdocs.editor.options/presentationsaveoptions/password) { get; set; } | Memungkinkan menentukan, memodifikasi, dan memperoleh kata sandi yang akan digunakan untuk mengenkripsi dokumen Presentasi hasil. Secara default adalah NULL — kata sandi tidak akan diatur. Atur ke NULL atau string kosong untuk menghapus kata sandi, jika sebelumnya telah diatur. |
| [SlideNumber](../../groupdocs.editor.options/presentationsaveoptions/slidenumber) { get; set; } | Memungkinkan menyisipkan slide yang diedit ke dalam presentasi yang ada alih-alih membuat presentasi satu slide baru (perilaku default). Nomor slide adalah nomor berbasis 1 dari slide dalam presentasi yang dimuat di kelas Editor. Jika nilainya 0 (nilai default), presentasi baru akan dibuat dengan satu slide yang diedit. Jika nilainya lebih besar atau lebih kecil dari nol, dan ada presentasi yang valid, dimuat di kelas Editor, slide yang diedit, yang disimpan di dalam instance EditableDocument input, akan disisipkan ke dalam presentasi tersebut. |
| [SlideNumbersToDelete](../../groupdocs.editor.options/presentationsaveoptions/slidenumberstodelete) { get; set; } | Memungkinkan menentukan array dengan nomor slide berbasis 1 yang harus dihapus dari presentasi saat disimpan, dalam kasus slide yang diedit disisipkan ke dalam presentasi yang ada. |

### Catatan

Instance dari kelas ini harus diteruskan ke metode  untuk menyimpan presentasi yang diedit ke dalam dokumen akhir dengan format khusus Presentasi tertentu. Semua parameter lain bersifat opsional dan dapat diabaikan, secara default format presentasi yang disimpan adalah PPTX, tetapi dapat diubah melalui konstruktor atau properti.

### Lihat Juga

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
