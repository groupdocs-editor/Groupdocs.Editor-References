---
title: "Mp3Audio"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mewakili satu sumber daya audio dengan format apa saja"
type: docs
weight: 330
url: /id/net/groupdocs.editor.htmlcss.resources.audio/mp3audio/
---
## Mp3Audio class

Mewakili satu sumber daya audio dengan format apa saja

```csharp
public sealed class Mp3Audio : IEquatable<Mp3Audio>, IHtmlResource
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [Mp3Audio](mp3audio)(string, Stream) | Membuat kelas Mp3Audio baru dari konten MP3, yang direpresentasikan sebagai aliran byte, dan dengan nama yang ditentukan |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/bytecontent) { get; } | Mengembalikan konten font ini sebagai aliran byte |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/filenamewithextension) { get; } | Mengembalikan nama file yang benar dari konten MP3 ini, yang terdiri dari nama dan ekstensi. Secara teoritis dapat berbeda dari nama. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/isdisposed) { get; } | Menentukan apakah konten MP3 ini telah dibuang atau tidak |
| [Name](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/name) { get; } | Mengembalikan nama konten MP3 ini. Biasanya tidak mengandung ekstensi nama file dan secara teoritis dapat berbeda dari nama file. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/textcontent) { get; } | Mengembalikan konten sumber daya MP3 ini sebagai string yang dienkode base64. Nilai ini di-cache setelah pemanggilan pertama. |
| [Type](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/type) { get; } | Mengembalikan AudioType.Mp3 |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/dispose)() | Membuang sumber daya MP3 ini, membuang kontennya dan membuat sebagian besar metode serta properti tidak berfungsi |
| [Equals](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/equals#equals_1)(IHtmlResource) | Memeriksa instance ini dengan sumber HTML yang ditentukan pada kesetaraan referensi |
| [Equals](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/equals#equals)(Mp3Audio) | Memeriksa instance ini dengan sumber font yang ditentukan pada kesetaraan referensi |
| [Save](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/save)(string) | Menyimpan sumber MP3 ini ke file yang ditentukan |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/isvalid)(Stream) | Memeriksa apakah aliran yang ditentukan adalah konten MP3 yang valid |

## Peristiwa

| Nama | Deskripsi |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/disposed) | Peristiwa, yang terjadi ketika konten MP3 ini dibuang |

### Lihat Juga

* interface [IHtmlResource](../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Audio](../../groupdocs.editor.htmlcss.resources.audio)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
