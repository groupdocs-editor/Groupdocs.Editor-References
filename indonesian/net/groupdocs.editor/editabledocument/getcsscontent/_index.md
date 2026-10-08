---
title: "GetCssContent"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mengembalikan konten semua stylesheet eksternal sebagai daftar string di mana satu string mewakili satu stylesheet. Mengembalikan daftar kosong jika tidak ada CSS untuk dokumen ini."
type: docs
weight: 140
url: /id/net/groupdocs.editor/editabledocument/getcsscontent/
---
## GetCssContent() {#getcsscontent}

Mengembalikan konten semua stylesheet eksternal sebagai daftar string, di mana satu string mewakili satu stylesheet. Mengembalikan daftar kosong, jika tidak ada CSS untuk dokumen ini.

```csharp
public List<string> GetCssContent()
```

### Nilai Kembalian

Daftar string, di mana setiap string berisi konten satu dokumen CSS

### Lihat Juga

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## GetCssContent(string, string) {#getcsscontent_1}

Mengembalikan konten semua stylesheet eksternal sebagai daftar string, di mana satu string mewakili satu stylesheet. Prefiks yang ditentukan akan diterapkan pada setiap tautan ke sumber daya eksternal di setiap stylesheet yang dihasilkan. Mengembalikan daftar kosong, jika tidak ada CSS untuk dokumen ini.

```csharp
public List<string> GetCssContent(string externalImagesPrefix, string externalFontsPrefix)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| externalImagesPrefix | String | Melalui parameter ini dapat ditentukan awalan, yang akan ditambahkan ke tautan semua gambar eksternal, yang akan muncul dalam deklarasi CSS pada string CSS yang dihasilkan. Jika NULL atau kosong, awalan tidak akan ditambahkan. |
| externalFontsPrefix | String | Melalui parameter ini dapat ditentukan awalan, yang akan ditambahkan ke tautan semua font eksternal dalam aturan @font-face pada string CSS yang dihasilkan. Jika NULL atau kosong, awalan tidak akan ditambahkan. |

### Nilai Kembalian

Daftar string, di mana setiap string berisi konten satu dokumen CSS

### Lihat Juga

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
