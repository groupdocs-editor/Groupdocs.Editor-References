---
title: "Editor"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Kelas utama yang mengenkapsulasi metode konversi. Kelas Editor menyediakan metode untuk memuat, mengedit, dan menyimpan dokumen dalam semua format yang didukung. Kelas ini dapat dibuang sehingga gunakan pernyataan using atau buang sumber dayanya secara manual melalui pemanggilan metode Dispose. Pemuatan dokumen dilakukan melalui konstruktor. Pengeditan dokumen melalui metode Edit dan penyimpanan kembali ke dokumen hasil setelah pengeditan melalui metode Save."
type: docs
weight: 20
url: /id/net/groupdocs.editor/editor/
---
## Editor class

Kelas utama, yang mengenkapsulasi metode konversi. Kelas Editor menyediakan metode untuk memuat, menyunting, dan menyimpan dokumen dalam semua format yang didukung. Kelas ini dapat dibuang, jadi gunakan direktif 'using' atau buang sumber dayanya secara manual melalui pemanggilan metode 'Dispose()'. Memuat dokumen dilakukan melalui konstruktor. Penyuntingan dokumen – melalui metode 'Edit', dan penyimpanan kembali ke dokumen hasil setelah penyuntingan – melalui metode 'Save'.

```csharp
public sealed class Editor : IAuxDisposable
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Editor](editor#constructor)(DocumentFormatBase) | Menginisialisasi instance baru dari kelas [`Editor`](../editor) dan membuat dokumen kosong baru berdasarkan format yang ditentukan. |
| [Editor](editor#constructor_1)(Stream) | Menginisialisasi instance Editor baru dengan dokumen input yang ditentukan (sebagai aliran). |
| [Editor](editor#constructor_3)(string) | Menginisialisasi instance Editor baru dengan dokumen input yang ditentukan (sebagai jalur file lengkap) dan pengaturan Editor. |
| [Editor](editor#constructor_2)(Stream, ILoadOptions) | Menginisialisasi instance Editor baru dengan dokumen input yang ditentukan (sebagai aliran) beserta opsi pemuatannya. |
| [Editor](editor#constructor_4)(string, ILoadOptions) | Menginisialisasi instance Editor baru dengan dokumen input yang ditentukan (sebagai jalur file lengkap) beserta opsi pemuatannya. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [FormFieldManager](../../groupdocs.editor/editor/formfieldmanager) { get; } | Memberikan akses ke fungsionalitas untuk mengelola bidang formulir dalam dokumen. |
| [IsDisposed](../../groupdocs.editor/editor/isdisposed) { get; } | Menunjukkan apakah instance Editor ini sudah dibuang dan tidak dapat digunakan lagi (true) atau belum dibuang sehingga masih aktif (false). |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Dispose](../../groupdocs.editor/editor/dispose)() | Membuang instance Editor ini, sehingga melepaskan semua sumber daya internal dan menjadi tidak tersedia untuk penggunaan selanjutnya. |
| [Edit](../../groupdocs.editor/editor/edit#edit)() | Buka dokumen yang telah dimuat sebelumnya untuk diedit menggunakan opsi default dengan menghasilkan dan mengembalikan instance kelas '[`EditableDocument`](../editabledocument)', yang pada gilirannya berisi metode untuk menghasilkan markup HTML dan sumber daya terkait. |
| [Edit](../../groupdocs.editor/editor/edit#edit_1)(IEditOptions) | Buka dokumen yang telah dimuat sebelumnya untuk diedit menggunakan opsi khusus format yang ditentukan dengan menghasilkan dan mengembalikan instance kelas '[`EditableDocument`](../editabledocument)', yang pada gilirannya berisi metode untuk menghasilkan markup HTML dan sumber daya terkait. |
| [GetDocumentInfo](../../groupdocs.editor/editor/getdocumentinfo)(string) | Mengembalikan metadata tentang dokumen yang dimuat ke instance 'Editor' ini. |
| [Save](../../groupdocs.editor/editor/save#save)(Stream) | Simpan konten dokumen saat ini ke aliran output yang ditentukan. |
| [Save](../../groupdocs.editor/editor/save#save_3)(EditableDocument, string) | Mengonversi dokumen yang diedit yang ditentukan, yang direpresentasikan sebagai instance '[`EditableDocument`](../editabledocument)', menjadi dokumen hasil dengan format yang ditentukan dari ekstensi nama file, dan menyimpan kontennya ke file dengan jalur file yang ditentukan. |
| [Save](../../groupdocs.editor/editor/save#save_1)(Stream, WordProcessingSaveOptions) | Mengonversi dokumen asli setelah dimodifikasi (misalnya, [`FormFieldManager`](./formfieldmanager)), menjadi dokumen hasil dengan format yang ditentukan dan menyimpan kontennya ke aliran yang disediakan. |
| [Save](../../groupdocs.editor/editor/save#save_2)(EditableDocument, Stream, ISaveOptions) | Mengonversi dokumen yang diedit yang ditentukan, yang direpresentasikan sebagai instance '[`EditableDocument`](../editabledocument)', menjadi dokumen hasil dengan format yang ditentukan dan menyimpan kontennya ke aliran yang ditentukan. |
| [Save](../../groupdocs.editor/editor/save#save_4)(EditableDocument, string, ISaveOptions) | Mengonversi dokumen yang diedit yang ditentukan, yang direpresentasikan sebagai instance '[`EditableDocument`](../editabledocument)', menjadi dokumen hasil dengan format yang ditentukan dan menyimpan kontennya ke file dengan jalur file yang ditentukan. |

## Peristiwa

| Nama | Deskripsi |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editor/disposed) | Peristiwa yang terjadi ketika instance Editor ini dibuang bersama semua sumber daya internalnya. |

### Catatan

Kelas Editor harus dianggap sebagai titik masuk dan objek akar dari GroupDocs.Editor. Semua operasi dilakukan menggunakan kelas ini. Penggunaan tipikal kelas Editor untuk melakukan alur kerja penyuntingan dokumen lengkap adalah sebagai berikut:

1. Muat dokumen ke dalam instance Editor melalui konstruktornya.
2. Secara opsional, deteksi tipe dokumen menggunakan metode [`GetDocumentInfo`](./getdocumentinfo).
3. Buka dokumen untuk diedit dengan memanggil metode [`Edit`](./edit) dan memperoleh instance kelas [`EditableDocument`](../editabledocument) darinya.
4. Mengedit konten dokumen di sisi klien menggunakan editor HTML WYSIWYG apa pun.
5. Membuat instance baru dari [`EditableDocument`](../editabledocument) dari konten dokumen yang telah diedit.
6. Menyimpan dokumen yang telah diedit ke format output tertentu dengan memanggil metode [`Save`](./save).
7. Membuang instance kelas Editor melalui operator 'using' atau secara manual.

### Lihat Juga

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* namespace [GroupDocs.Editor](../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
