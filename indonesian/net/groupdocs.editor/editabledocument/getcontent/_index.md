---
title: "GetContent"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mengembalikan keseluruhan konten dokumen HTML sebagai aliran byte dengan menulis konten ini ke aliran yang ditentukan menggunakan enkoding teks yang ditentukan"
type: docs
weight: 130
url: /id/net/groupdocs.editor/editabledocument/getcontent/
---
## GetContent&lt;TStream&gt;(TStream, Encoding) {#getcontent_2}

Mengembalikan keseluruhan konten dokumen HTML sebagai aliran byte dengan menulis konten ini ke aliran yang ditentukan menggunakan enkoding teks yang ditentukan

```csharp
public TStream GetContent<TStream>(TStream storage, Encoding encoding)
    where TStream : Stream
```

| Parameter | Deskripsi |
| --- | --- |
| TStream | Implementasi apa pun dari Stream |
| storage | Aliran byte non-null, yang mendukung penulisan |
| encoding | Encoding teks non-null, yang harus diterapkan saat menulis konten teks ke *storage* yang ditentukan |

### Nilai Kembalian

Instansi dari *storage* yang ditentukan

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | Salah satu argumen masukan bernilai null |
| ArgumentException | Stream yang ditentukan tidak dapat ditulisi |

### Lihat Juga

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetContent() {#getcontent}

Mengembalikan keseluruhan konten dokumen HTML sebagai string.

```csharp
public string GetContent()
```

### Nilai Kembalian

String yang berisi konten dokumen HTML

### Lihat Juga

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetContent(string, string) {#getcontent_1}

Mengembalikan keseluruhan konten dokumen HTML sebagai string, di mana tautan ke sumber daya eksternal berisi templat yang ditentukan dengan placeholder.

```csharp
public string GetContent(string externalImagesTemplate, string externalCssTemplate)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| externalImagesTemplate | String | Melalui parameter ini pengguna dapat menentukan templat string dengan satu placeholder, yang akan diterapkan pada tautan ke semua gambar eksternal dalam elemen IMG, yang akan muncul dalam string HTML hasil. Jika NULL atau kosong, templat tidak akan ditambahkan, dan nama file murni akan muncul dalam markup HTML hasil. Jika templat tidak valid, akan diperlakukan sebagai awalan, sehingga nama file akan digabungkan ke akhir templat tersebut. |
| externalCssTemplate | String | Melalui parameter ini dapat menentukan templat string dengan satu placeholder, yang akan ditambahkan ke tautan semua stylesheet eksternal dalam elemen LINK, yang akan ada dalam string HTML hasil. Jika NULL atau kosong, templat tidak akan ditambahkan, dan nama file murni akan muncul dalam markup HTML hasil. Jika templat tidak valid, akan diperlakukan sebagai awalan, sehingga nama file akan digabungkan ke akhir templat. |

### Nilai Kembalian

String yang berisi konten dokumen HTML dengan tautan, disesuaikan dengan sumber daya eksternal

### Lihat Juga

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
