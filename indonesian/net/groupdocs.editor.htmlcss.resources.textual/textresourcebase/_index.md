---
title: "TextResourceBase"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Kelas dasar untuk setiap sumber daya teks yang didukung dengan konten teks dan pengkodean"
type: docs
weight: 630
url: /id/net/groupdocs.editor.htmlcss.resources.textual/textresourcebase/
---
## TextResourceBase class

Kelas dasar untuk setiap sumber daya teks yang didukung dengan konten teks dan pengkodean

```csharp
public abstract class TextResourceBase : IHtmlResource
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/bytecontent) { get; } | Mengembalikan konten sumber teks ini sebagai aliran byte dengan enkoding asli |
| [Encoding](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/encoding) { get; } | Mengembalikan enkoding sumber tekstual ini. Biasanya mengembalikan UTF-8. |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/filenamewithextension) { get; } | Mengembalikan nama file yang benar untuk sumber teks ini, yang terdiri dari nama dan ekstensi |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/isdisposed) { get; } | Menentukan apakah sumber teks ini telah dibuang atau tidak |
| [Name](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/name) { get; } | Mengembalikan nama sumber teks ini tanpa ekstensi file |
| [TextContent](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/textcontent) { get; } | Mengembalikan konten sumber teks ini sebagai string standar |
| abstract [Type](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/type) { get; } | Pada tipe yang diimplementasikan harus mengembalikan informasi tentang tipe sumber teks |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/dispose)() | Membuang sumber teks ini, membuang kontennya dan membuat sebagian besar metode serta properti tidak berfungsi. Toleran terhadap pemanggilan berulang. |
| [Equals](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/equals#equals)(IHtmlResource) | Memeriksa kesetaraan instance ini dengan yang ditentukan. |
| [Save](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/save)(string) | Menyimpan sumber teks ini ke file yang ditentukan |

## Peristiwa

| Nama | Deskripsi |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/disposed) | Event, yang terjadi ketika sumber teks ini dibuang |

### Lihat Juga

* interface [IHtmlResource](../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Textual](../../groupdocs.editor.htmlcss.resources.textual)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
