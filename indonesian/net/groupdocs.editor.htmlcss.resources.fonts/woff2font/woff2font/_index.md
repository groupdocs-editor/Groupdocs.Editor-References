---
title: "Woff2Font"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Membuat kelas Woff2Font baru dari konten yang direpresentasikan sebagai string yang dienkode base64 dan dengan nama yang ditentukan"
type: docs
weight: 10
url: /id/net/groupdocs.editor.htmlcss.resources.fonts/woff2font/woff2font/
---
## Woff2Font(string, string) {#constructor_1}

Membuat kelas Woff2Font baru dari konten, yang direpresentasikan sebagai string yang di-encode base64, dan dengan nama yang ditentukan

```csharp
public Woff2Font(string name, string contentInBase64)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | String | Nama font WOFF2. Tidak boleh null, kosong, atau hanya spasi. |
| contentInBase64 | String | Konten sebagai string yang dienkode base64. Tidak boleh null, kosong, atau hanya spasi. Jika bukan konten WOFF2, akan dilemparkan pengecualian. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Lihat Juga

* class [Woff2Font](../../woff2font)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## Woff2Font(string, Stream) {#constructor}

Membuat kelas Woff2Font baru dari konten, yang direpresentasikan sebagai aliran byte, dan dengan nama yang ditentukan

```csharp
public Woff2Font(string name, Stream binaryContent)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | String | Nama font WOFF2. Tidak boleh null, kosong, atau hanya spasi. |
| binaryContent | Stream | Konten sebagai aliran byte. Pembacaan dimulai dari posisi asli. Tidak boleh null. Harus dapat dibaca dan dapat di-seek. Jika instance ini dibuang, aliran ini juga akan dibuang. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Lihat Juga

* class [Woff2Font](../../woff2font)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
