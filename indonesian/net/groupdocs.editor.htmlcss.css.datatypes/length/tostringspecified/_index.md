---
title: "ToStringSpecified"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mengembalikan representasi string dari panjang ini dalam tipe unit yang ditentukan. Nilai numerik akan dikonversi sesuai dengan perubahan tipe unit."
type: docs
weight: 260
url: /id/net/groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified/
---
## Length.ToStringSpecified method

Mengembalikan representasi string dari panjang ini dalam tipe unit yang ditentukan. Nilai numerik akan dikonversi sesuai dengan perubahan tipe unit.

```csharp
public string ToStringSpecified(Unit unit)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| satuan | Satuan | Satuan yang ditentukan, ke mana instance ini harus dikonversi sebelum diserialisasi ke string. Harus valid. Tidak boleh tanpa satuan. |

### Nilai Kembalian

Representasi string

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| InvalidEnumArgumentException | Nilai tidak didefinisikan |
| ArgumentOutOfRangeException | Nilai tanpa satuan dilarang |

### Lihat Juga

* enum [Unit](../../length.unit)
* struct [Length](../../length)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
