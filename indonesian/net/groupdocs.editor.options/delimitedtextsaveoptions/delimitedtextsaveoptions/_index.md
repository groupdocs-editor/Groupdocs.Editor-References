---
title: "DelimitedTextSaveOptions"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Konstruktor tanpa parameter ini membuat instance baru dari DelimitedTextSaveOptions dengan pemisah default berupa titik koma; pemisah dapat diubah kemudian melalui properti Separatorgroupdocs.editor.options/delimitedtextsaveoptions/separator."
type: docs
weight: 10
url: /id/net/groupdocs.editor.options/delimitedtextsaveoptions/delimitedtextsaveoptions/
---
## DelimitedTextSaveOptions() {#constructor}

Konstruktor tanpa parameter ini membuat instance baru dari DelimitedTextSaveOptions dengan pemisah default berupa titik koma (; ) (dapat diubah kemudian melalui properti [`Separator`](../separator)).

```csharp
public DelimitedTextSaveOptions()
```

### Lihat Juga

* class [DelimitedTextSaveOptions](../../delimitedtextsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

---

## DelimitedTextSaveOptions(string) {#constructor_1}

Membuat instance kelas opsi untuk teks delimited dengan pemisah (delimiter) wajib

```csharp
public DelimitedTextSaveOptions(string separator)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| separator | String | Pemisah string (delimiter) yang tidak boleh NULL atau kosong. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Dilemparkan ketika pemisah yang ditentukan adalah null atau string kosong. |

### Lihat Juga

* class [DelimitedTextSaveOptions](../../delimitedtextsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
