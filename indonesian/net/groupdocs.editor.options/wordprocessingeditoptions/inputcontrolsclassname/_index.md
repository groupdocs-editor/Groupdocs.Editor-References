---
title: "InputControlsClassName"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Memungkinkan untuk menentukan nama kelas yang akan ditempatkan pada atribut class di setiap elemen HTML yang mewakili suatu bidang dalam dokumen WordProcessing input. Secara default adalah NULL, atribut class tidak diterapkan."
type: docs
weight: 60
url: /id/net/groupdocs.editor.options/wordprocessingeditoptions/inputcontrolsclassname/
---
## WordProcessingEditOptions.InputControlsClassName property

Memungkinkan untuk menentukan nama kelas, yang akan ditempatkan pada atribut 'class' di setiap elemen HTML yang mewakili suatu bidang dalam dokumen WordProcessing input. Secara default bernilai NULL - atribut 'class' tidak diterapkan.

```csharp
public string InputControlsClassName { get; set; }
```

### Catatan

Hampir semua format dari keluarga format WordProcessing berisi field — entitas dokumen spesifik yang memungkinkan memperoleh data input dari pengguna. Ada berbagai macam field: kotak teks, kotak centang, kotak kombo, daftar drop‑down, tombol, pemilih tanggal/waktu, dll. Semua ini diterjemahkan ke dalam struktur dan elemen HTML yang paling sesuai, sambil mempertahankan data pengguna yang dimasukkan, jika ada dalam dokumen input. Dalam kasus penggunaan tertentu hanya diperlukan mengumpulkan data yang dimasukkan di sisi klien alih‑alih mengedit seluruh konten dokumen. Untuk kasus tersebut diperlukan mengidentifikasi kontrol input dengan cara tertentu untuk mengambilnya beserta datanya di sisi klien. Properti ini memungkinkan menentukan nama kelas yang akan diterapkan pada setiap kontrol input dalam markup HTML, sehingga kode klien dapat menelusuri struktur dokumen HTML dan mengumpulkan data.

### Lihat Juga

* class [WordProcessingEditOptions](../../wordprocessingeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
