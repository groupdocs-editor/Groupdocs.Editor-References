---
title: "SvgImage"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Membuat instance SvgImage baru dari konten yang direpresentasikan sebagai string biasa dan dengan nama yang ditentukan"
type: docs
weight: 10
url: /id/net/groupdocs.editor.htmlcss.resources.images.vector/svgimage/svgimage/
---
## SvgImage(string, string) {#constructor_1}

Membuat instance SvgImage baru dari konten, yang direpresentasikan sebagai string biasa, dan dengan nama yang ditentukan

```csharp
public SvgImage(string name, string content)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | String | Nama gambar SVG. Tidak boleh null, kosong, atau spasi. |
| konten | String | Konten sebagai string biasa, yang berisi konten SVG yang valid dan mematuhi XML. Tidak boleh null, kosong, atau spasi. Jika bukan konten SVG, pengecualian akan dilemparkan. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Beberapa parameter tidak valid |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) | *content* argumen berisi konten SVG yang tidak valid |

### Lihat Juga

* class [SvgImage](../../svgimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

---

## SvgImage(string, Stream) {#constructor}

Membuat instance SvgImage baru dari konten, yang direpresentasikan sebagai aliran byte, dan dengan nama yang ditentukan

```csharp
public SvgImage(string name, Stream binaryContent)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | String | Nama gambar SVG. Tidak boleh null, kosong, atau spasi. |
| binaryContent | Stream | Konten sebagai aliran byte. Pembacaan dimulai dari posisi asli. Tidak boleh null. Harus dapat dibaca dan dapat dipindahkan (seekable). Jika instance ini dibuang, aliran ini juga akan dibuang. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Lihat Juga

* class [SvgImage](../../svgimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
