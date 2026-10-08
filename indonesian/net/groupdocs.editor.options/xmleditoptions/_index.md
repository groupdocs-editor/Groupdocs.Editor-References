---
title: "XmlEditOptions"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mengizinkan untuk menentukan opsi khusus untuk mengedit dokumen XML (eXtensible Markup Language) dan mengonversinya ke HTML"
type: docs
weight: 1270
url: /id/net/groupdocs.editor.options/xmleditoptions/
---
## XmlEditOptions class

Memungkinkan untuk menentukan opsi khusus untuk mengedit dokumen XML (eXtensible Markup Language) dan mengonversinya ke HTML

```csharp
public sealed class XmlEditOptions : IEditOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [XmlEditOptions](xmleditoptions)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AttributeValuesQuoteType](../../groupdocs.editor.options/xmleditoptions/attributevaluesquotetype) { get; set; } | Mengizinkan untuk menentukan jenis kutipan (tanda kutip tunggal atau ganda) untuk nilai atribut. Tanda kutip ganda adalah default. |
| [Encoding](../../groupdocs.editor.options/xmleditoptions/encoding) { get; set; } | Pengkodean karakter dokumen teks, yang akan diterapkan saat membuka. Secara default null — pengkodean dokumen internal akan diterapkan. |
| [FixIncorrectStructure](../../groupdocs.editor.options/xmleditoptions/fixincorrectstructure) { get; set; } | Mengizinkan untuk mengaktifkan atau menonaktifkan mekanisme perbaikan struktur XML yang rusak. Secara default dinonaktifkan (false). |
| [FormatOptions](../../groupdocs.editor.options/xmleditoptions/formatoptions) { get; } | Mengizinkan penyesuaian format XML, yang akan diterapkan pada struktur XML, ketika direpresentasikan dalam HTML. Format default digunakan dan dapat disesuaikan. Tidak boleh null. |
| [HighlightOptions](../../groupdocs.editor.options/xmleditoptions/highlightoptions) { get; } | Mengizinkan penyesuaian penyorotan XML, yang akan diterapkan pada struktur XML, ketika direpresentasikan dalam HTML. Penyorotan default digunakan dan dapat disesuaikan. Tidak boleh null. |
| [RecognizeEmails](../../groupdocs.editor.options/xmleditoptions/recognizeemails) { get; set; } | Mengizinkan mengaktifkan algoritma pengenalan untuk alamat email dalam nilai atribut |
| [RecognizeUris](../../groupdocs.editor.options/xmleditoptions/recognizeuris) { get; set; } | Mengizinkan mengaktifkan algoritma pengenalan URI |
| [TrimTrailingWhitespaces](../../groupdocs.editor.options/xmleditoptions/trimtrailingwhitespaces) { get; set; } | Mengizinkan mengaktifkan pemotongan spasi putih di akhir dalam teks inner-tag. Secara default dinonaktifkan (false) — spasi putih di akhir akan dipertahankan. |

### Lihat Juga

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
