---
title: "FromValue"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mengambil sebuah instance dari tipe T yang ditentukan yang memiliki pengidentifikasi yang ditentukan."
type: docs
weight: 70
url: /id/net/groupdocs.editor.formats.abstraction/formatfamilybase/fromvalue/
---
## FormatFamilyBase.FromValue&lt;T&gt; method

Mengambil sebuah instance dari tipe *T* yang ditentukan yang memiliki pengidentifikasi yang ditentukan.

```csharp
public static T FromValue<T>(int value)
    where T : FormatFamilyBase
```

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe dari format family. |
| nilai | Pengidentifikasi dari format family. |

### Nilai Kembalian

Sebuah instance dari tipe *T* yang ditentukan dengan pengidentifikasi yang ditentukan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| InvalidOperationException | Dilemparkan ketika tidak ada format family yang cocok ditemukan. |

### Lihat Juga

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
