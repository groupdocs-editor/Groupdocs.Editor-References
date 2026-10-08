---
title: "EditableDocument"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Dokumen menengah yang berisi konten sebelum dan sesudah penyuntingan"
type: docs
weight: 10
url: /id/net/groupdocs.editor/editabledocument/
---
## EditableDocument class

Dokumen menengah, yang berisi konten sebelum dan sesudah penyuntingan

```csharp
public sealed class EditableDocument : IAuxDisposable
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AllResources](../../groupdocs.editor/editabledocument/allresources) { get; } | Mengembalikan daftar semua sumber daya yang ada: semua stylesheet, gambar dari HTML dan semua stylesheet, font, audio |
| [Audio](../../groupdocs.editor/editabledocument/audio) { get; } | Mengembalikan daftar sumber daya audio |
| [Css](../../groupdocs.editor/editabledocument/css) { get; } | Memungkinkan memperoleh sumber daya stylesheet (CSS) (baik eksternal maupun tersemat, tetapi tidak inline), yang digunakan oleh dokumen HTML ini |
| [Fonts](../../groupdocs.editor/editabledocument/fonts) { get; } | Memungkinkan memperoleh sumber daya font eksternal, yang digunakan oleh dokumen HTML ini |
| [Images](../../groupdocs.editor/editabledocument/images) { get; } | Memungkinkan memperoleh sumber daya gambar eksternal (gambar raster dan vektor), yang digunakan oleh dokumen HTML ini |
| [IsDisposed](../../groupdocs.editor/editabledocument/isdisposed) { get; } | Menentukan apakah dokumen Editable ini sudah dibuang (true) atau tidak (false) |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [FromFile](../../groupdocs.editor/editabledocument/fromfile)(string, string) | Fabrik statis, yang membuat instance EditableDocument dari file HTML, yang ditentukan oleh path ke file *.html itu sendiri dan folder dengan sumber daya yang terhubung |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup#frommarkup)(string) | Fabrik statis, yang membuat instance dari [`EditableDocument`](../editabledocument) dari markup HTML yang ditentukan |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup#frommarkup_1)(string, IEnumerable&lt;IHtmlResource&gt;) | Fabrik statis, yang membuat instance EditableDocument dari markup HTML yang ditentukan dan sekumpulan sumber daya terhubung yang sesuai |
| static [FromMarkupAndResourceFolder](../../groupdocs.editor/editabledocument/frommarkupandresourcefolder)(string, string) | Fabrik statis, yang membuat instance EditableDocument dari markup HTML yang ditentukan dan dari sumber daya yang berada di folder, yang ditentukan oleh path lengkap |
| [Dispose](../../groupdocs.editor/editabledocument/dispose)() | Membuang instance dokumen Editable ini, membuang kontennya dan membuat metode serta propertinya tidak berfungsi |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent)() | Mengembalikan isi badan dokumen HTML (konten dalam antara tag BODY pembuka dan penutup tanpa tag tersebut) sebagai string. |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent_1)(string) | Mengembalikan isi badan dokumen HTML (konten dalam antara tag BODY pembuka dan penutup tanpa tag tersebut) sebagai string, di mana tautan ke sumber daya eksternal berisi templat yang ditentukan dengan placeholder. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent)() | Mengembalikan keseluruhan konten dokumen HTML sebagai string. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent_1)(string, string) | Mengembalikan keseluruhan konten dokumen HTML sebagai string, di mana tautan ke sumber daya eksternal berisi templat yang ditentukan dengan placeholder. |
| [GetContent&lt;TStream&gt;](../../groupdocs.editor/editabledocument/getcontent#getcontent_2)(TStream, Encoding) | Mengembalikan keseluruhan konten dokumen HTML sebagai aliran byte dengan menulis konten ini ke aliran yang ditentukan menggunakan enkoding teks yang ditentukan |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent)() | Mengembalikan konten semua stylesheet eksternal sebagai daftar string, di mana satu string mewakili satu stylesheet. Mengembalikan daftar kosong, jika tidak ada CSS untuk dokumen ini. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent_1)(string, string) | Mengembalikan konten semua stylesheet eksternal sebagai daftar string, di mana satu string mewakili satu stylesheet. Prefiks yang ditentukan akan diterapkan pada setiap tautan ke sumber daya eksternal di setiap stylesheet yang dihasilkan. Mengembalikan daftar kosong, jika tidak ada CSS untuk dokumen ini. |
| [GetEmbeddedHtml](../../groupdocs.editor/editabledocument/getembeddedhtml)() | Mengembalikan semua konten dokumen HTML ini beserta semua sumber daya terkait dalam bentuk satu string, di mana semua sumber daya disematkan di dalam markup HTML dalam bentuk yang dienkode base64. |
| [Save](../../groupdocs.editor/editabledocument/save#save_1)(string) | Menyimpan dokumen HTML ini ke file pada path yang ditentukan, di mana markup HTML akan disimpan, dan ke folder pendamping dengan sumber daya. |
| [Save](../../groupdocs.editor/editabledocument/save#save_2)(string, string) | Menyimpan dokumen HTML ini ke file pada path yang ditentukan, di mana markup HTML akan disimpan, dan ke folder pendamping dengan sumber daya, yang terletak pada path yang ditentukan. |
| [Save](../../groupdocs.editor/editabledocument/save#save)(TextWriter, HtmlSaveOptions) | Menyimpan konten [`EditableDocument`](../editabledocument) ini sebagai dokumen HTML ke penulis teks yang ditentukan, sementara parameter opsi kedua memungkinkan menyesuaikan prosedur penyimpanan dan menentukan callback penyimpanan sumber daya |

## Peristiwa

| Nama | Deskripsi |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editabledocument/disposed) | Peristiwa, yang terjadi ketika dokumen Editable ini dibuang, tepat setelah proses pembuangan selesai |

### Catatan

Instansi kelas `EditableDocument` dapat dihasilkan oleh metode '[`Edit`](../editor/edit)' atau dibuat oleh pengguna sendiri menggunakan pabrik statis. `EditableDocument` secara internal menyimpan dokumen dalam format tertutupnya sendiri, yang kompatibel (dapat dikonversi) dengan semua format impor dan ekspor yang didukung oleh GroupDocs.Editor. Untuk membuat dokumen dapat diedit di editor sisi klien WYSIWYG apa pun (seperti CKEditor atau TinyMCE), `EditableDocument` menyediakan metode untuk menghasilkan markup HTML dan menghasilkan sumber daya, yang dapat diterima oleh pengguna.

### Lihat Juga

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* namespace [GroupDocs.Editor](../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
