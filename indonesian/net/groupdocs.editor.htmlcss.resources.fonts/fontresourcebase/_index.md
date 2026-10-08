---
title: "FontResourceBase"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Kelas dasar untuk semua tipe font yang didukung sebagai sumber daya untuk dokumen HTML dengan semua propertinya."
type: docs
weight: 350
url: /id/net/groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/
---
## FontResourceBase class

Kelas dasar untuk semua tipe font yang didukung sebagai sumber daya untuk dokumen HTML dengan semua propertinya.

```csharp
public abstract class FontResourceBase : IEquatable<FontResourceBase>, IHtmlResource
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/bytecontent) { get; } | Mengembalikan konten font ini sebagai aliran byte |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/filenamewithextension) { get; } | Mengembalikan nama file yang benar untuk sumber daya font ini, yang terdiri dari nama dan ekstensi. Secara teoritis dapat berbeda dari nama. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/isdisposed) { get; } | Menentukan apakah font ini telah dibuang atau tidak |
| [Name](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/name) { get; } | Mengembalikan nama sumber daya font ini. Biasanya tidak mengandung ekstensi nama file dan secara teoritis dapat berbeda dari nama file. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/textcontent) { get; } | Mengembalikan konten font ini sebagai string yang di-encode base64. Nilai ini disimpan dalam cache setelah pemanggilan pertama. |
| abstract [Type](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/type) { get; } | Tipe yang mengimplementasikan harus mengembalikan informasi tentang tipe sumber daya font tertentu sebagai instance dari tipe FontType tertentu, yang mengenkapsulasi semua info spesifik tipe |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/dispose)() | Membuang sumber daya font ini, membuang kontennya dan membuat sebagian besar metode serta properti tidak berfungsi |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals#equals)(FontResourceBase) | Memeriksa instance ini dengan sumber font yang ditentukan pada kesetaraan referensi |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals#equals_1)(IHtmlResource) | Memeriksa instance ini dengan sumber HTML yang ditentukan pada kesetaraan referensi |
| [Save](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/save)(string) | Menyimpan font ini ke file yang ditentukan |

## Peristiwa

| Nama | Deskripsi |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/disposed) | Peristiwa, yang terjadi ketika font ini dibuang |

### Lihat Juga

* interface [IHtmlResource](../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
