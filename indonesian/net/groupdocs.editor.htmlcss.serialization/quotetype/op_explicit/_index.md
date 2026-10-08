---
title: "op_Explicit"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mengubah instance QuoteTypegroupdocs.editor.htmlcss.serialization/quotetype yang ditentukan menjadi Char"
type: docs
weight: 100
url: /id/net/groupdocs.editor.htmlcss.serialization/quotetype/op_explicit/
---
## explicit operator {#op_explicit}

Mengubah instance [`QuoteType`](../../quotetype) yang ditentukan menjadi Char

```csharp
public static explicit operator char(QuoteType quote)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kutipan | QuoteType | Instance tipe kutipan untuk diubah |

### Lihat Juga

* struct [QuoteType](../../quotetype)
* namespace [GroupDocs.Editor.HtmlCss.Serialization](../../../groupdocs.editor.htmlcss.serialization)
* assembly [GroupDocs.Editor](../../../)

---

## explicit operator {#op_explicit_1}

Mengubah Char tertentu menjadi [`QuoteType`](../../quotetype) yang sesuai, melempar pengecualian jika konversi tidak valid

```csharp
public static explicit operator QuoteType(char character)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| karakter | Karakter | Sebuah tanda kutip tunggal (U+0027 APOSTROPHE) atau tanda kutip ganda (U+0022 QUOTATION MARK). Pengecualian akan dilemparkan jika karakter lain ditentukan. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentOutOfRangeException | Karakter yang ditentukan bukan tanda kutip maupun apostrof. |

### Lihat Juga

* struct [QuoteType](../../quotetype)
* namespace [GroupDocs.Editor.HtmlCss.Serialization](../../../groupdocs.editor.htmlcss.serialization)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
