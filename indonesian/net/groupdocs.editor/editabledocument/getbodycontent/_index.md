---
title: "GetBodyContent"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mengembalikan isi tubuh dokumen HTML antara tag BODY pembuka dan penutup tanpa tag tersebut sebagai string."
type: docs
weight: 120
url: /id/net/groupdocs.editor/editabledocument/getbodycontent/
---
## GetBodyContent() {#getbodycontent}

Mengembalikan isi badan dokumen HTML (konten dalam antara tag BODY pembuka dan penutup tanpa tag tersebut) sebagai string.

```csharp
public string GetBodyContent()
```

### Nilai Kembalian

String, yang berisi tubuh dokumen HTML (tanpa tag BODY pembuka dan penutup)

### Catatan

Sebagian besar editor WYSIWYG biasanya beroperasi dengan konten dalam BODY dokumen dan tidak dapat memproses informasi meta dari blok HEAD dengan benar. Metode ini dirancang untuk kasus tersebut. Overload ini tidak memungkinkan penyesuaian URI untuk permintaan sumber daya eksternal.

### Lihat Juga

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetBodyContent(string) {#getbodycontent_1}

Mengembalikan isi badan dokumen HTML (konten dalam antara tag BODY pembuka dan penutup tanpa tag tersebut) sebagai string, di mana tautan ke sumber daya eksternal berisi templat yang ditentukan dengan placeholder.

```csharp
public string GetBodyContent(string externalImagesTemplate)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| externalImagesTemplate | String | Melalui parameter ini pengguna dapat menentukan templat string dengan satu placeholder, yang akan diterapkan pada tautan ke semua gambar eksternal dalam elemen IMG, yang akan muncul dalam string HTML hasil. Jika NULL atau kosong, templat tidak akan ditambahkan, dan nama file murni akan muncul dalam markup HTML hasil. Jika templat tidak valid, akan diperlakukan sebagai awalan, sehingga nama file akan digabungkan ke akhir templat tersebut. |

### Nilai Kembalian

String, yang berisi tubuh dokumen HTML (tanpa tag BODY pembuka dan penutup) dengan tautan, disesuaikan untuk gambar eksternal

### Catatan

Sebagian besar editor WYSIWYG biasanya beroperasi dengan konten dalam BODY dokumen dan tidak dapat memproses informasi meta dari blok HEAD dengan benar. Metode ini dirancang untuk kasus tersebut. Overload ini memungkinkan penyesuaian URI untuk permintaan sumber daya eksternal.

### Lihat Juga

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
