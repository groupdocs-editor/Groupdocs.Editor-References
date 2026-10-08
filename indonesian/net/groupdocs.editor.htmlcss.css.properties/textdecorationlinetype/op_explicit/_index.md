---
title: "op_Explicit"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mengubah Byte 8bit octet tertentu menjadi TextDecorationLineType yang sesuai groupdocs.editor.htmlcss.css.properties/textdecorationlinetype, melempar pengecualian jika konversi tidak valid"
type: docs
weight: 180
url: /id/net/groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_explicit/
---
## explicit operator {#op_explicit_1}

Mengubah Byte (octet 8-bit) tertentu menjadi [`TextDecorationLineType`](../../textdecorationlinetype) yang sesuai, melempar pengecualian jika konversi tidak valid

```csharp
public static explicit operator TextDecorationLineType(byte octet)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| oktet | Byte | Sebuah oktet 8-bit (bitfield), di mana 5 bit terdepan bernilai nol, sementara 3 bit terakhir menunjukkan flag |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentOutOfRangeException | *oktet* yang ditentukan memiliki nilai tidak valid |

### Lihat Juga

* struct [TextDecorationLineType](../../textdecorationlinetype)
* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../../)

---

## explicit operator {#op_explicit}

Mengubah instance [`TextDecorationLineType`](../../textdecorationlinetype) yang ditentukan menjadi oktet yang setara (bitfield 8-bit)

```csharp
public static explicit operator byte(TextDecorationLineType input)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| input | TextDecorationLineType | Instance [`TextDecorationLineType`](../../textdecorationlinetype) untuk diubah |

### Lihat Juga

* struct [TextDecorationLineType](../../textdecorationlinetype)
* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
