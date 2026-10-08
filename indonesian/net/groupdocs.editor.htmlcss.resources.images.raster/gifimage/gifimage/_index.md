---
title: "GifImage"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Membuat instance GifImage baru dari konten yang direpresentasikan sebagai string yang di-encode base64 dan dengan nama yang ditentukan"
type: docs
weight: 10
url: /id/net/groupdocs.editor.htmlcss.resources.images.raster/gifimage/gifimage/
---
## GifImage(string, string) {#constructor_1}

Membuat instance GifImage baru dari konten, yang direpresentasikan sebagai string yang di-encode base64, dan dengan nama yang ditentukan

```csharp
public GifImage(string name, string contentInBase64)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | String | Nama gambar GIF. Tidak boleh null, kosong, atau spasi putih. |
| contentInBase64 | String | Konten sebagai string yang di-encode base64. Tidak boleh null, kosong, atau spasi putih. Jika bukan konten GIF, pengecualian akan dilemparkan. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Lihat Juga

* class [GifImage](../../gifimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

---

## GifImage(string, Stream) {#constructor}

Membuat instance GifImage baru dari konten, yang direpresentasikan sebagai aliran byte, dan dengan nama yang ditentukan

```csharp
public GifImage(string name, Stream binaryContent)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | String | Nama gambar GIF. Tidak boleh null, kosong, atau spasi putih. |
| binaryContent | Stream | Konten sebagai aliran byte. Pembacaan dimulai dari posisi asli. Tidak boleh null. Harus dapat dibaca dan dapat dipindahkan (seekable). Jika instance ini dibuang, aliran ini juga akan dibuang. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Lihat Juga

* class [GifImage](../../gifimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
