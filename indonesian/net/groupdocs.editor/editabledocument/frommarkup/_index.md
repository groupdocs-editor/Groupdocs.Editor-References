---
title: "FromMarkup"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Fabrik statis yang membuat instance dari EditableDocumentgroupdocs.editor/editabledocument dari markup HTML yang ditentukan"
type: docs
weight: 20
url: /id/net/groupdocs.editor/editabledocument/frommarkup/
---
## FromMarkup(string) {#frommarkup}

Fabrik statis, yang membuat instance dari [`EditableDocument`](../../editabledocument) dari markup HTML yang ditentukan

```csharp
public static EditableDocument FromMarkup(string newHtmlContent)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newHtmlContent | String | String, yang berisi markup HTML mentah, yang harus diparsing. Tidak boleh NULL, kosong, atau tidak valid. |

### Nilai Kembalian

Instansi EditableDocument baru yang tidak null

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | String dengan markup HTML mentah input tidak boleh null atau kosong |

### Catatan

Metode statis ini berguna untuk membuat instance [`EditableDocument`](../../editabledocument) dari markup HTML satu string, di mana semua sumber daya disematkan ke dalamnya dengan enkoding base64.

### Lihat Juga

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

---

## FromMarkup(string, IEnumerable&lt;IHtmlResource&gt;) {#frommarkup_1}

Fabrik statis, yang membuat instance EditableDocument dari markup HTML yang ditentukan dan sekumpulan sumber daya terhubung yang sesuai

```csharp
public static EditableDocument FromMarkup(string newHtmlContent, 
    IEnumerable<IHtmlResource> resources)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newHtmlContent | String | String, yang berisi markup HTML mentah, yang harus diparsing. Tidak boleh NULL, kosong, atau tidak valid. |
| resources | IEnumerable`1 | Koleksi semua sumber daya (gambar, stylesheets, fonts), yang digunakan dalam HTML-document, yang ditentukan dalam parameter *newHtmlContent*. Mungkin tidak ada (NULL atau koleksi kosong). |

### Nilai Kembalian

Instansi EditableDocument baru yang tidak null

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | String dengan markup HTML mentah input tidak boleh null atau kosong |

### Lihat Juga

* interface [IHtmlResource](../../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
