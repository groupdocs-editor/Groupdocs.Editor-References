---
title: Editor
second_title: GroupDocs.Editor untuk Referensi .NET API
description: Kelas utama yang merangkum metode konversi. Kelas Editor menyediakan metode untuk memuat mengedit dan menyimpan dokumen dari semua format yang didukung. Itu sekali pakai jadi gunakan arahan using atau buang sumber dayanya secara manual melalui pemanggilan metode Buang . Pemuatan dokumen dilakukan melalui konstruktor. Pengeditan dokumen  melalui metode Edit dan menyimpan kembali ke dokumen yang dihasilkan setelah diedit  melalui metode Simpan.
type: docs
weight: 20
url: /id/net/groupdocs.editor/editor/
---
## Editor class

Kelas utama, yang merangkum metode konversi. Kelas Editor menyediakan metode untuk memuat, mengedit, dan menyimpan dokumen dari semua format yang didukung. Itu sekali pakai, jadi gunakan arahan 'using' atau buang sumber dayanya secara manual melalui pemanggilan metode 'Buang ()'. Pemuatan dokumen dilakukan melalui konstruktor. Pengeditan dokumen - melalui metode 'Edit', dan menyimpan kembali ke dokumen yang dihasilkan setelah diedit - melalui metode 'Simpan'.

```csharp
public sealed class Editor : IAuxDisposable
```

## Konstruktor

| Nama | Keterangan |
| --- | --- |
| [Editor](editor#constructor)(Func&lt;Stream&gt;) | Menginisialisasi instance Editor baru dengan dokumen masukan tertentu (sebagai aliran) |
| [Editor](editor#constructor_2)(string) | Menginisialisasi instance Editor baru dengan dokumen input yang ditentukan (sebagai jalur file lengkap) |
| [Editor](editor#constructor_1)(Func&lt;Stream&gt;, Func&lt;ILoadOptions&gt;) | Menginisialisasi instance Editor baru dengan dokumen masukan tertentu (sebagai aliran) dengan opsi muatnya |
| [Editor](editor#constructor_3)(string, Func&lt;ILoadOptions&gt;) | Menginisialisasi instance Editor baru dengan dokumen input yang ditentukan (sebagai jalur file lengkap) dengan opsi muatnya |

## Properti

| Nama | Keterangan |
| --- | --- |
| [IsDisposed](../../groupdocs.editor/editor/isdisposed) { get; } | Menunjukkan apakah instance Editor ini sudah dibuang dan tidak dapat digunakan lagi (benar) atau belum dibuang sehingga aktif (salah) |

## Metode

| Nama | Keterangan |
| --- | --- |
| [Dispose](../../groupdocs.editor/editor/dispose)() | Membuang instance Editor ini, sehingga melepaskan semua sumber daya internal dan menjadi tidak tersedia untuk penggunaan lebih lanjut |
| [Edit](../../groupdocs.editor/editor/edit#edit)() | Membuka dokumen yang dimuat sebelumnya untuk diedit menggunakan opsi default dengan membuat dan mengembalikan instance '[`EditableDocument`](../editabledocument) kelas, yang pada gilirannya berisi metode untuk menghasilkan markup HTML dan sumber daya terkait. |
| [Edit](../../groupdocs.editor/editor/edit#edit_1)(IEditOptions) | Membuka dokumen yang dimuat sebelumnya untuk diedit menggunakan opsi khusus format yang ditentukan dengan membuat dan mengembalikan instance '[`EditableDocument`](../editabledocument) kelas, yang pada gilirannya berisi metode untuk menghasilkan markup HTML dan sumber daya terkait. |
| [GetDocumentInfo](../../groupdocs.editor/editor/getdocumentinfo)(string) | Mengembalikan metadata tentang dokumen, yang dimuat ke instance 'Editor' ini |
| [Save](../../groupdocs.editor/editor/save#save)(EditableDocument, Stream, ISaveOptions) | Mengonversi dokumen yang diedit tertentu, direpresentasikan sebagai turunan dari '[`EditableDocument`](../editabledocument) , ke dokumen yang dihasilkan dari format yang ditentukan dan menyimpan kontennya ke stream yang ditentukan |
| [Save](../../groupdocs.editor/editor/save#save_1)(EditableDocument, string, ISaveOptions) | Mengonversi dokumen yang diedit tertentu, direpresentasikan sebagai turunan dari '[`EditableDocument`](../editabledocument) , ke dokumen yang dihasilkan dari format yang ditentukan dan menyimpan kontennya ke file dengan jalur file yang ditentukan |

## Acara

| Nama | Keterangan |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editor/disposed) | Peristiwa, yang terjadi saat instance Editor ini dibuang dengan semua sumber daya internalnya |

### Perkataan

Kelas Editor harus dianggap sebagai titik masuk dan objek akar dari GroupDocs.Editor. Semua operasi dilakukan menggunakan kelas ini. Penggunaan umum kelas Editor untuk melakukan alur pengeditan dokumen lengkap adalah sebagai berikut:

1. Muat dokumen ke dalam instance Editor melalui konstruktornya.
2. Secara opsional, deteksi jenis dokumen menggunakan a[`GetDocumentInfo`](./getdocumentinfo) metode.
3. Buka dokumen untuk diedit dengan memanggil an[`Edit`](./edit)metode dan mendapatkan contoh dari[`EditableDocument`](../editabledocument) kelas dari itu.
4. Mengedit konten dokumen di sisi klien menggunakan editor HTML WYSIWYG apa pun.
5. Membuat instance baru dari[`EditableDocument`](../editabledocument) dari konten dokumen yang diedit.
6. Menyimpan dokumen yang diedit ke beberapa format keluaran dengan memanggil a[`Save`](./save) metode.
7. Membuang instance kelas Editor melalui operator 'menggunakan' atau secara manual.

### Lihat juga

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* ruang nama [GroupDocs.Editor](../../groupdocs.editor)
* perakitan [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
