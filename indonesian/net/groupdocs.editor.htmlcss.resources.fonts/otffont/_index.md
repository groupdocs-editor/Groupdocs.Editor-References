---
title: "OtfFont"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mewakili satu font dalam format OTF Open Type Format"
type: docs
weight: 370
url: /id/net/groupdocs.editor.htmlcss.resources.fonts/otffont/
---
## OtfFont class

Mewakili satu font dalam format OTF (Open Type Format).

```csharp
public sealed class OtfFont : FontResourceBase
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [OtfFont](otffont#constructor)(string, Stream) | Membuat kelas OtfFont baru dari konten, yang direpresentasikan sebagai aliran byte, dan dengan nama yang ditentukan |
| [OtfFont](otffont#constructor_1)(string, string) | Membuat kelas OtfFont baru dari konten, yang direpresentasikan sebagai string yang dienkode base64, dan dengan nama yang ditentukan |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/bytecontent) { get; } | Mengembalikan konten font ini sebagai aliran byte |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/filenamewithextension) { get; } | Mengembalikan nama file yang benar untuk sumber daya font ini, yang terdiri dari nama dan ekstensi. Secara teoritis dapat berbeda dari nama. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/isdisposed) { get; } | Menentukan apakah font ini telah dibuang atau tidak |
| [Name](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/name) { get; } | Mengembalikan nama sumber daya font ini. Biasanya tidak mengandung ekstensi nama file dan secara teoritis dapat berbeda dari nama file. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/textcontent) { get; } | Mengembalikan konten font ini sebagai string yang di-encode base64. Nilai ini disimpan dalam cache setelah pemanggilan pertama. |
| override [Type](../../groupdocs.editor.htmlcss.resources.fonts/otffont/type) { get; } | Mengembalikan [`Otf`](../fonttype/otf) |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/dispose)() | Membuang sumber daya font ini, membuang kontennya dan membuat sebagian besar metode serta properti tidak berfungsi |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(FontResourceBase) | Memeriksa instance ini dengan sumber font yang ditentukan pada kesetaraan referensi |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(IHtmlResource) | Memeriksa instance ini dengan sumber HTML yang ditentukan pada kesetaraan referensi |
| [Save](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/save)(string) | Menyimpan font ini ke file yang ditentukan |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/otffont/isvalid#isvalid)(Stream) | Memeriksa apakah aliran yang ditentukan merupakan font OTF yang valid |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/otffont/isvalid#isvalid_1)(string) | Memeriksa apakah string yang dienkode base64 yang ditentukan merupakan font OTF yang valid |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| const [RequiredHeaderSize](../../groupdocs.editor.htmlcss.resources.fonts/otffont/requiredheadersize) | Ukuran header OTF (dalam byte), yang diperlukan untuk validasinya |

## Peristiwa

| Nama | Deskripsi |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/disposed) | Peristiwa, yang terjadi ketika font ini dibuang |

### Lihat Juga

* class [FontResourceBase](../fontresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
