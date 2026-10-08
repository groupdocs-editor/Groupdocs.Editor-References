---
title: "FromMime"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mengambil sebuah instance dari tipe T yang ditentukan yang memiliki tipe MIME yang ditentukan."
type: docs
weight: 60
url: /id/net/groupdocs.editor.formats.abstraction/documentformatbase/frommime/
---
## DocumentFormatBase.FromMime&lt;T&gt; method

Mengambil sebuah instance dari tipe *T* yang ditentukan yang memiliki tipe MIME yang ditentukan.

```csharp
public static T FromMime<T>(string mime)
    where T : DocumentFormatBase
```

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe format dokumen. |
| mime | Tipe MIME dari format dokumen. |

### Nilai Kembalian

Sebuah instance dari tipe *T* yang ditentukan dengan tipe MIME yang ditentukan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| InvalidOperationException | Dilemparkan ketika tidak ada format dokumen yang cocok ditemukan. |

### Lihat Juga

* class [DocumentFormatBase](../../documentformatbase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
