---
title: EditableDocument
second_title: GroupDocs.Editor untuk Referensi .NET API
description: Dokumen perantara berisi konten sebelum dan sesudah diedit
type: docs
weight: 10
url: /id/net/groupdocs.editor/editabledocument/
---
## EditableDocument class

Dokumen perantara, berisi konten sebelum dan sesudah diedit

```csharp
public sealed class EditableDocument : IAuxDisposable
```

## Properti

| Nama | Keterangan |
| --- | --- |
| [AllResources](../../groupdocs.editor/editabledocument/allresources) { get; } | Mengembalikan daftar semua sumber daya yang ada: semua stylesheet, gambar dari HTML dan semua stylesheet, font, audio |
| [Audio](../../groupdocs.editor/editabledocument/audio) { get; } | Mengembalikan daftar sumber daya audio |
| [Css](../../groupdocs.editor/editabledocument/css) { get; } | Mengembalikan daftar sumber daya CSS |
| [Fonts](../../groupdocs.editor/editabledocument/fonts) { get; } | Memungkinkan untuk memperoleh sumber daya font eksternal, yang digunakan oleh dokumen HTML ini |
| [Images](../../groupdocs.editor/editabledocument/images) { get; } | Memungkinkan untuk mendapatkan sumber gambar eksternal (gambar raster dan vektor), yang digunakan oleh dokumen HTML ini |
| [IsDisposed](../../groupdocs.editor/editabledocument/isdisposed) { get; } | Menentukan apakah dokumen yang Dapat Diedit ini sudah dibuang (benar) atau tidak (salah) |

## Metode

| Nama | Keterangan |
| --- | --- |
| static [FromFile](../../groupdocs.editor/editabledocument/fromfile)(string, string) | Pabrik statis, yang membuat instance EditableDocument dari file HTML, yang ditentukan oleh jalur ke file *.html itu sendiri dan folder dengan sumber daya tertaut |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup)(string, IEnumerable&lt;IHtmlResource&gt;) | Pabrik statis, yang membuat instance EditableDocument dari markup HTML tertentu dan kumpulan sumber daya tertaut yang sesuai |
| static [FromMarkupAndResourceFolder](../../groupdocs.editor/editabledocument/frommarkupandresourcefolder)(string, string) | Pabrik statis, yang membuat instance EditableDocument dari markup HTML tertentu dan dari sumber daya, terletak di folder, ditentukan oleh path lengkap |
| [Dispose](../../groupdocs.editor/editabledocument/dispose)() | Membuang instance dokumen yang Dapat Diedit ini, membuang kontennya dan membuat metode dan propertinya tidak berfungsi |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent)() | Mengembalikan isi dokumen HTML (konten dalam antara membuka dan menutup tag BODY tanpa tag ini) sebagai string. |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent_1)(string) | Mengembalikan isi dokumen HTML (konten dalam antara membuka dan menutup tag BODY tanpa tag ini) sebagai string, di mana tautan ke sumber daya eksternal berisi awalan yang ditentukan. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent)() | Mengembalikan keseluruhan konten dokumen HTML sebagai string. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent_1)(string, string) | Mengembalikan keseluruhan konten dokumen HTML sebagai string, di mana tautan ke sumber daya eksternal berisi awalan yang ditentukan. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent)() | Mengembalikan konten semua stylesheet eksternal sebagai daftar string, di mana satu string mewakili satu stylesheet. Mengembalikan daftar kosong, jika tidak ada CSS untuk dokumen ini. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent_1)(string, string) | Mengembalikan konten dari semua stylesheet eksternal sebagai daftar string, di mana satu string mewakili satu stylesheet. Awalan yang ditentukan akan diterapkan ke setiap tautan ke sumber daya eksternal di setiap stylesheet yang dihasilkan. Mengembalikan daftar kosong, jika tidak ada CSS untuk ini dokumen. |
| [GetEmbeddedHtml](../../groupdocs.editor/editabledocument/getembeddedhtml)() | Mengembalikan semua konten dokumen HTML ini dengan semua sumber daya terkait dalam bentuk string tunggal, di mana semua sumber daya disematkan di dalam markup HTML dalam bentuk berenkode base64. |
| [Save](../../groupdocs.editor/editabledocument/save#save)(string) | Menyimpan dokumen HTML ini ke file di jalur yang ditentukan, tempat markup HTML akan disimpan, dan ke folder yang menyertainya dengan sumber daya. |
| [Save](../../groupdocs.editor/editabledocument/save#save_1)(string, string) | Menyimpan dokumen HTML ini ke file di jalur yang ditentukan, tempat markup HTML akan disimpan, dan ke folder yang menyertainya dengan sumber daya, yang terletak di jalur yang ditentukan. |

## Acara

| Nama | Keterangan |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editabledocument/disposed) | Peristiwa, yang terjadi saat dokumen yang Dapat Diedit ini dibuang, tepat setelah menyelesaikan proses pembuangan |

### Perkataan

Instance kelas EditableDocument dapat dihasilkan oleh '[`Edit`](../editor/edit) metode atau dibuat oleh pengguna sendiri menggunakan pabrik statis. EditableDocument secara internal menyimpan dokumen dalam format tertutupnya sendiri, yang kompatibel (dapat dikonversi) dengan semua format impor dan ekspor, yang didukung GroupDocs.Editor. Untuk membuat dokumen dapat diedit di editor sisi klien WYSIWYG mana pun (seperti CKEditor atau TinyMCE), EditableDocument menyediakan metode untuk menghasilkan markup HTML dan menghasilkan sumber daya, yang dapat diterima oleh pengguna.

### Lihat juga

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* ruang nama [GroupDocs.Editor](../../groupdocs.editor)
* perakitan [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
