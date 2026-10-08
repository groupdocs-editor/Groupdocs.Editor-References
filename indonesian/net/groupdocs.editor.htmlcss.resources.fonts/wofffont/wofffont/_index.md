---
title: "WoffFont"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Buat kelas WoffFont baru dari konten yang direpresentasikan sebagai string yang di-encode base64 dan dengan nama yang ditentukan"
type: docs
weight: 10
url: /id/net/groupdocs.editor.htmlcss.resources.fonts/wofffont/wofffont/
---
## WoffFont(string, string) {#constructor_1}

Membuat kelas WoffFont baru dari konten, yang direpresentasikan sebagai string yang dienkode base64, dan dengan nama yang ditentukan

```csharp
public WoffFont(string name, string contentInBase64)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | String | Nama font WOFF. Tidak boleh null, kosong, atau hanya spasi. |
| contentInBase64 | String | Konten sebagai string yang di-encode base64. Tidak boleh null, kosong, atau hanya spasi. Jika bukan konten WOFF, pengecualian akan dilempar. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Lihat Juga

* class [WoffFont](../../wofffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## WoffFont(string, Stream) {#constructor}

Membuat kelas WoffFont baru dari konten, yang direpresentasikan sebagai aliran byte, dan dengan nama yang ditentukan

```csharp
public WoffFont(string name, Stream binaryContent)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | String | Nama font WOFF. Tidak boleh null, kosong, atau hanya spasi. |
| binaryContent | Stream | Konten sebagai aliran byte. Pembacaan dimulai dari posisi asli. Tidak boleh null. Harus dapat dibaca dan dapat di-seek. Jika instance ini dibuang, aliran ini juga akan dibuang. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Lihat Juga

* class [WoffFont](../../wofffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
