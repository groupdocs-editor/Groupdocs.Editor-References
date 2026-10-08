---
title: "EotFont"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Membuat kelas EotFont baru dari konten yang direpresentasikan sebagai string base64encoded dengan nama yang ditentukan"
type: docs
weight: 10
url: /id/net/groupdocs.editor.htmlcss.resources.fonts/eotfont/eotfont/
---
## EotFont(string, string) {#constructor_1}

Membuat kelas EotFont baru dari konten, yang direpresentasikan sebagai string yang di-encode base64, dan dengan nama yang ditentukan

```csharp
public EotFont(string eotName, string eotContentInBase64)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| eotName | String | Nama font EOT. Tidak boleh null, kosong, atau hanya spasi. |
| eotContentInBase64 | String | Konten sebagai string yang dienkode base64. Tidak boleh null, kosong, atau hanya spasi. Jika bukan konten EOT, pengecualian akan dilempar. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Lihat Juga

* class [EotFont](../../eotfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## EotFont(string, Stream) {#constructor}

Membuat kelas EotFont baru dari konten, yang direpresentasikan sebagai aliran byte, dan dengan nama yang ditentukan

```csharp
public EotFont(string eotName, Stream eotBinaryContent)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| eotName | String | Nama font EOT. Tidak boleh null, kosong, atau hanya spasi. |
| eotBinaryContent | Stream | Konten sebagai aliran byte. Pembacaan dimulai dari posisi asli. Tidak boleh null. Harus dapat dibaca dan dapat dipindahkan (seekable). Jika instance ini dibuang, aliran ini juga akan dibuang. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Lihat Juga

* class [EotFont](../../eotfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
