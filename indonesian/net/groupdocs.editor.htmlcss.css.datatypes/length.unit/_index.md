---
title: "Length.Unit"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Semua unit panjang yang didukung"
type: docs
weight: 240
url: /id/net/groupdocs.editor.htmlcss.css.datatypes/length.unit/
---
## Length.Unit enumeration

Semua unit panjang yang didukung

```csharp
public enum Unit
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Unitless | `0` | Tanpa satuan - tidak ada satuan panjang yang didefinisikan. Nilai default. |
| Px | `1` | Pixel. Relatif terhadap perangkat tampilan. Untuk tampilan layar, biasanya satu pixel (titik) perangkat. |
| Em | `2` | Em. Unit ini mewakili ukuran font yang dihitung dari elemen. |
| Ex | `3` | Ex (x-length). Unit ini mewakili tinggi-x dari font elemen. Pada font dengan huruf 'x', biasanya ini adalah tinggi huruf kecil dalam font; 1ex ≈ 0,5em pada banyak font. |
| Cm | `4` | Cm. Satu sentimeter (10 milimeter). |
| Mm | `5` | Mm. Satu milimeter. |
| In | `6` | In. Satu inci (2.54 sentimeter). |
| Pt | `7` | Pt. Satu poin adalah 1/72 inci atau 0.353 mm. |
| Pc | `8` | Pc. Satu pica (12 poin). |
| Ch | `9` | Ch. Unit ini mewakili lebar, atau lebih tepatnya ukuran maju, dari glif '0' (nol, karakter Unicode U+0030) dalam font elemen. |
| Rem | `10` | Rem. Unit ini mewakili ukuran font dari elemen akar (misalnya ukuran font dari elemen &lt;html&gt;). Ketika digunakan pada ukuran font elemen akar ini, ia mewakili nilai awalnya. |
| Vw | `11` | Vw - lebar viewport. 1/100 lebar viewport. |
| Vh | `12` | Vh - tinggi viewport. 1/100 tinggi viewport. |
| Vmin | `13` | Vmin. 1/100 nilai minimum antara tinggi dan lebar viewport. |
| Vmax | `14` | Vmax. 1/100 nilai maksimum antara tinggi dan lebar viewport. |
| Percent | `15` | Nilai ini relatif terhadap nilai tetap (eksternal), yang bergantung pada konteks. 1% = 1/100 nilai eksternal. |

### Catatan

https://developer.mozilla.org/en-US/docs/Web/CSS/length#Units

### Lihat Juga

* struct [Length](../length)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
