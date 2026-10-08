---
title: "IHtmlResource"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mewakili satu instance dari sumber daya HTML yang tidak diketahui raster atau vektor gambar stylesheet font teks sumber daya CSS XML audio dll."
type: docs
weight: 430
url: /id/net/groupdocs.editor.htmlcss.resources/ihtmlresource/
---
## IHtmlResource interface

Mewakili satu instance dari sumber daya HTML yang tidak diketahui (gambar raster atau vektor, stylesheet, font, sumber daya teks (CSS, XML), audio, dll.)

```csharp
public interface IHtmlResource : IAuxDisposable, IEquatable<IHtmlResource>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources/ihtmlresource/bytecontent) { get; } | Konten sumber daya HTML dalam bentuk aliran byte |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources/ihtmlresource/filenamewithextension) { get; } | Nama file yang benar dari sumber daya yang ditentukan dengan ekstensi file yang sesuai |
| [Name](../../groupdocs.editor.htmlcss.resources/ihtmlresource/name) { get; } | Nama sumber daya HTML |
| [TextContent](../../groupdocs.editor.htmlcss.resources/ihtmlresource/textcontent) { get; } | Konten sumber daya HTML dalam bentuk string teks yang dienkode base64 untuk sumber daya biner atau teks sederhana untuk sumber daya tekstual |
| [Type](../../groupdocs.editor.htmlcss.resources/ihtmlresource/type) { get; } | Tipe sumber daya HTML |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Save](../../groupdocs.editor.htmlcss.resources/ihtmlresource/save)(string) | Menyimpan sumber daya saat ini ke file yang ditentukan |

### Lihat Juga

* interface [IAuxDisposable](../iauxdisposable)
* namespace [GroupDocs.Editor.HtmlCss.Resources](../../groupdocs.editor.htmlcss.resources)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
