---
title: "WordProcessingEditOptions"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Memungkinkan untuk menentukan opsi khusus untuk mengedit dokumen dari semua format WordProcessing yang didukung seperti DOCX, RTF, ODT, dll."
type: docs
weight: 1200
url: /id/net/groupdocs.editor.options/wordprocessingeditoptions/
---
## WordProcessingEditOptions class

Memungkinkan untuk menentukan opsi khusus untuk mengedit dokumen dari semua format WordProcessing (kompatibel dengan Words) yang didukung seperti DOC(X), RTF, ODT, dll.

```csharp
public class WordProcessingEditOptions : IEditOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [WordProcessingEditOptions](wordprocessingeditoptions#constructor)() | Membuat dan mengembalikan instance baru dari kelas WordProcessingEditOptions, di mana semua opsi diatur ke nilai default. |
| [WordProcessingEditOptions](wordprocessingeditoptions#constructor_1)(bool) | Membuat dan mengembalikan instance baru dari kelas WordProcessingEditOptions dengan paginasi yang ditentukan dan semua opsi lainnya menggunakan nilai default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [EnableLanguageInformation](../../groupdocs.editor.options/wordprocessingeditoptions/enablelanguageinformation) { get; set; } | Menentukan apakah informasi bahasa diekspor ke markup HTML dalam bentuk atribut HTML 'lang'. Opsi ini mungkin berguna untuk konversi bolak-balik dokumen multi-bahasa. Secara default opsi ini dinonaktifkan (false). |
| [EnablePagination](../../groupdocs.editor.options/wordprocessingeditoptions/enablepagination) { get; set; } | Mengizinkan untuk mengaktifkan atau menonaktifkan paginasi dalam dokumen HTML hasil. Secara default dinonaktifkan (false). |
| [ExtractOnlyUsedFont](../../groupdocs.editor.options/wordprocessingeditoptions/extractonlyusedfont) { get; set; } | Mendapatkan atau menetapkan nilai yang menunjukkan apakah hanya mengekstrak sumber daya font yang digunakan dalam konten teks dokumen. |
| [FontExtraction](../../groupdocs.editor.options/wordprocessingeditoptions/fontextraction) { get; set; } | Bertanggung jawab untuk mengekstrak sumber daya font yang digunakan dalam dokumen WordProcessing input. Secara default tidak mengekstrak font apa pun (NotExtract). |
| [InputControlsClassName](../../groupdocs.editor.options/wordprocessingeditoptions/inputcontrolsclassname) { get; set; } | Memungkinkan untuk menentukan nama kelas, yang akan ditempatkan pada atribut 'class' di setiap elemen HTML yang mewakili suatu bidang dalam dokumen WordProcessing input. Secara default bernilai NULL - atribut 'class' tidak diterapkan. |
| [UseInlineStyles](../../groupdocs.editor.options/wordprocessingeditoptions/useinlinestyles) { get; set; } | Mengontrol dimana menyimpan data styling dan formatting dokumen WordProcessing input: dalam stylesheet eksternal (`false`) atau sebagai gaya inline dalam markup HTML (`true`). Secara default gaya eksternal digunakan (`false`). |

### Lihat Juga

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
