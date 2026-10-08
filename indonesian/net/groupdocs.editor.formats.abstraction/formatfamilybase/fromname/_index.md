---
title: "FromName"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mengambil sebuah instance dari tipe T yang ditentukan yang memiliki nama yang ditentukan."
type: docs
weight: 60
url: /id/net/groupdocs.editor.formats.abstraction/formatfamilybase/fromname/
---
## FormatFamilyBase.FromName&lt;T&gt; method

Mengambil sebuah instance dari tipe *T* yang ditentukan yang memiliki nama yang ditentukan.

```csharp
public static T FromName<T>(string name)
    where T : FormatFamilyBase
```

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe dari format family. |
| nama | Nama dari format family. |

### Nilai Kembalian

Sebuah instance dari tipe *T* yang ditentukan dengan nama yang ditentukan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| InvalidOperationException | Dilemparkan ketika tidak ada format family yang cocok ditemukan. |

### Lihat Juga

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
