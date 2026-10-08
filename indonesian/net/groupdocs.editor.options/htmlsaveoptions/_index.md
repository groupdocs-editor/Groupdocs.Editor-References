---
title: "HtmlSaveOptions"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Memungkinkan untuk menentukan opsi khusus untuk menyimpan instance EditableDocument../groupdocs.editor/editabledocument ke format HTML"
type: docs
weight: 900
url: /id/net/groupdocs.editor.options/htmlsaveoptions/
---
## HtmlSaveOptions class

Memungkinkan untuk menentukan opsi khusus untuk menyimpan instance [`EditableDocument`](../../groupdocs.editor/editabledocument) ke format HTML

```csharp
public sealed class HtmlSaveOptions
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [HtmlSaveOptions](htmlsaveoptions)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AttributeValueDelimiter](../../groupdocs.editor.options/htmlsaveoptions/attributevaluedelimiter) { get; set; } | Mengontrol delimiter mana yang akan digunakan di sekitar nilai atribut dalam elemen HTML: tanda kutip tunggal (nilai default) atau tanda kutip ganda |
| [EmbedStylesheetsIntoMarkup](../../groupdocs.editor.options/htmlsaveoptions/embedstylesheetsintomarkup) { get; set; } | Mengontrol dimana menyimpan stylesheet CSS: sebagai sumber eksternal (`false`), atau menyematkannya ke dalam markup HTML, di dalam elemen STYLE pada bagian HTML-&gt;HEAD (`true`) |
| [HtmlTagCase](../../groupdocs.editor.options/htmlsaveoptions/htmltagcase) { get; set; } | Mengontrol bagaimana nama tag HTML akan muncul dalam markup HTML: Semua huruf kecil (nilai default), Semua huruf besar, atau Huruf pertama kapital |
| [SavingCallback](../../groupdocs.editor.options/htmlsaveoptions/savingcallback) { get; set; } | Antarmuka, yang harus diimplementasikan oleh pengguna akhir untuk menyimpan semua sumber daya HTML eksternal. Properti ini **must** tidak boleh `null`, jika tidak GroupDocs.Editor akan melempar pengecualian saat menyimpan [`EditableDocument`](../../groupdocs.editor/editabledocument) ke format HTML. |

### Lihat Juga

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
