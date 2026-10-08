---
title: "Mp3Audio"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Membuat kelas Mp3Audio baru dari konten MP3 yang direpresentasikan sebagai aliran byte dan dengan nama yang ditentukan."
type: docs
weight: 10
url: /id/net/groupdocs.editor.htmlcss.resources.audio/mp3audio/mp3audio/
---
## Mp3Audio constructor

Membuat kelas Mp3Audio baru dari konten MP3, yang direpresentasikan sebagai aliran byte, dan dengan nama yang ditentukan

```csharp
public Mp3Audio(string name, Stream binaryContent)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | String | Nama konten MP3. Tidak boleh null, kosong, atau spasi. |
| binaryContent | Stream | Konten sebagai aliran byte. Pembacaan dimulai dari posisi asli. Tidak boleh null. Harus dapat dibaca dan dapat dipindahkan (seekable). Jika instance ini dibuang, aliran ini juga akan dibuang. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException |  |

### Lihat Juga

* class [Mp3Audio](../../mp3audio)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Audio](../../../groupdocs.editor.htmlcss.resources.audio)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
