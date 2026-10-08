---
title: "TtcFont"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Buat kelas TtcFont baru dari konten yang direpresentasikan sebagai string yang di-encode base64 dan dengan nama yang ditentukan"
type: docs
weight: 10
url: /id/net/groupdocs.editor.htmlcss.resources.fonts/ttcfont/ttcfont/
---
## TtcFont(string, string) {#constructor_1}

Membuat kelas TtcFont baru dari konten, yang direpresentasikan sebagai string yang dienkode base64, dan dengan nama yang ditentukan

```csharp
public TtcFont(string name, string contentInBase64)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | String | Nama font TTC. Tidak boleh null, kosong, atau hanya spasi. |
| contentInBase64 | String | Konten sebagai string yang di-encode base64. Tidak boleh null, kosong, atau hanya spasi. Jika bukan konten TTC, pengecualian akan dilempar. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Salah satu string input adalah `null`, kosong, atau hanya spasi |
| [InvalidImageFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidimageformatexception) | Konten dalam argumen *contentInBase64* tidak dapat dikenali sebagai font TTC yang valid |

### Lihat Juga

* class [TtcFont](../../ttcfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

---

## TtcFont(string, Stream) {#constructor}

Membuat kelas TtcFont baru dari konten, yang direpresentasikan sebagai aliran byte, dan dengan nama yang ditentukan

```csharp
public TtcFont(string name, Stream binaryContent)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | String | Nama font TTC. Tidak boleh null, kosong, atau hanya spasi. |
| binaryContent | Stream | Konten sebagai aliran byte. Pembacaan dimulai dari posisi asli. Tidak boleh null. Harus dapat dibaca dan dapat dipindahkan (seekable). Jika instance ini dibuang, aliran ini juga akan dibuang. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Argumen *name* adalah `null`, kosong, atau hanya spasi |
| [InvalidFontFormatException](../../../groupdocs.editor.htmlcss.exceptions/invalidfontformatexception) | Dilempar ketika konten biner yang ditentukan tidak dapat diinterpretasikan dengan benar sebagai font TTF yang valid |

### Lihat Juga

* class [TtcFont](../../ttcfont)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
