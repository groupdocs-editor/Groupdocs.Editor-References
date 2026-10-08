---
title: "OtfFont"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Buat kelas OtfFont baru dari konten yang direpresentasikan sebagai string yang di-encode base64 dan dengan nama yang ditentukan"
type: docs
weight: 10
url: /id/net/groupdocs.editor.htmlcss.resources.fonts/otffont/otffont/
---
## OtfFont(string, string) {#constructor_1}

Membuat kelas OtfFont baru dari konten, yang direpresentasikan sebagai string yang dienkode base64, dan dengan nama yang ditentukan

```csharp
public OtfFont(string name, string contentInBase64)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | String | Nama font OTF. Tidak boleh null, kosong, atau hanya spasi. |
| contentInBase64 | String | Konten sebagai string yang di-encode base64. Tidak boleh null, kosong, atau hanya spasi. Jika bukan konten OTF, pengecualian akan dilempar. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Lihat Juga

* class [OtfFont](../../otffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## OtfFont(string, Stream) {#constructor}

Membuat kelas OtfFont baru dari konten, yang direpresentasikan sebagai aliran byte, dan dengan nama yang ditentukan

```csharp
public OtfFont(string name, Stream binaryContent)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | String | Nama font OTF. Tidak boleh null, kosong, atau hanya spasi. |
| binaryContent | Stream | Konten sebagai aliran byte. Pembacaan dimulai dari posisi asli. Tidak boleh null. Harus dapat dibaca dan dapat dipindahkan (seekable). Jika instance ini dibuang, aliran ini juga akan dibuang. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException |  |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) |  |

### Lihat Juga

* class [OtfFont](../../otffont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
