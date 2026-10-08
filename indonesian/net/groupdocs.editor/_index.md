---
title: "GroupDocs.Editor"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Namespace GroupDocs.Editor menyediakan kelas untuk mengedit dokumen menggunakan editor WYSIWYG frontend pihak ketiga tanpa aplikasi tambahan apa pun."
type: docs
weight: 10
url: /id/net/groupdocs.editor/
---
Namespace GroupDocs.Editor menyediakan kelas untuk mengedit dokumen menggunakan editor WYSIWYG front-end pihak ketiga tanpa aplikasi tambahan apa pun.

## Kelas

| Kelas | Deskripsi |
| --- | --- |
| [EditableDocument](./editabledocument) | Dokumen menengah, yang berisi konten sebelum dan sesudah penyuntingan |
| [Editor](./editor) | Kelas utama, yang mengenkapsulasi metode konversi. Kelas Editor menyediakan metode untuk memuat, menyunting, dan menyimpan dokumen dalam semua format yang didukung. Kelas ini dapat dibuang, jadi gunakan direktif 'using' atau buang sumber dayanya secara manual melalui pemanggilan metode 'Dispose()'. Memuat dokumen dilakukan melalui konstruktor. Penyuntingan dokumen – melalui metode 'Edit', dan penyimpanan kembali ke dokumen hasil setelah penyuntingan – melalui metode 'Save'. |
| [EncryptedException](./encryptedexception) | Pengecualian yang dilemparkan ketika pengguna mencoba membuka dokumen yang dienkripsi menggunakan X509Certificates. |
| [FormFieldManager](./formfieldmanager) | Kelola Formulir dengan Bidang Formulir Warisan. Bidang formulir warisan adalah jenis bidang yang tersedia di versi Word sebelumnya. Grup Legacy Forms (terlihat setelah Anda mengklik ikon Legacy Tools) mencakup tiga jenis bidang formulir yang dapat Anda sisipkan dalam dokumen: teks, kotak centang, daftar turun‑bawah, tanggal, dll., lihat lebih lanjut [`FormFieldType`](../groupdocs.editor.words.fieldmanagement/formfieldtype). Setiap bidang formulir ini memungkinkan pengguna formulir untuk memilih atau memasukkan informasi dengan tipe yang Anda anggap sesuai. |
| [IncorrectPasswordException](./incorrectpasswordexception) | Pengecualian yang dilemparkan ketika kata sandi yang ditentukan tidak benar. |
| [InvalidFormatException](./invalidformatexception) | Pengecualian yang dilemparkan ketika pengguna mencoba membuka dokumen dengan opsi khusus format yang tidak kompatibel dengan format dokumen asli. |
| [License](./license) | Menyediakan metode untuk melisensikan komponen. Pelajari lebih lanjut tentang lisensi [di sini](https://purchase.groupdocs.com/faqs/licensing). |
| [Metered](./metered) | Menyediakan metode untuk menerapkan lisensi [Metered](https://purchase.groupdocs.com/faqs/licensing/metered). |
| [PasswordRequiredException](./passwordrequiredexception) | Pengecualian yang dilemparkan ketika pengguna mencoba membuka dokumen terenkripsi yang dilindungi kata sandi dalam format tertentu dan tidak menyediakan kata sandi untuk membuka dokumen tersebut. |

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
