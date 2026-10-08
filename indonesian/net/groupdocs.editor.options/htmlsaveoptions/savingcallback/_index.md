---
title: "SavingCallback"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Antarmuka yang harus diimplementasikan oleh pengguna akhir untuk menyimpan semua sumber daya HTML eksternal. Properti ini tidak boleh null, jika tidak GroupDocs.Editor akan melempar pengecualian saat menyimpan EditableDocumentgroupdocs.editor/editabledocument ke format HTML."
type: docs
weight: 50
url: /id/net/groupdocs.editor.options/htmlsaveoptions/savingcallback/
---
## HtmlSaveOptions.SavingCallback property

Antarmuka, yang harus diimplementasikan oleh pengguna akhir untuk menyimpan semua sumber daya HTML eksternal. Properti ini **harus** tidak `null`, jika tidak GroupDocs.Editor akan melempar pengecualian saat menyimpan [`EditableDocument`](../../../groupdocs.editor/editabledocument) ke format HTML.

```csharp
public IHtmlSavingCallback SavingCallback { get; set; }
```

### Catatan

Jika nilai properti [`EmbedStylesheetsIntoMarkup`](../embedstylesheetsintomarkup) diatur ke `true`, semua stylesheet akan disematkan ke dalam markup HTML dan oleh karena itu tidak akan diteruskan ke callback penyimpanan ini.

### Lihat Juga

* interface [IHtmlSavingCallback](../../ihtmlsavingcallback)
* class [HtmlSaveOptions](../../htmlsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
