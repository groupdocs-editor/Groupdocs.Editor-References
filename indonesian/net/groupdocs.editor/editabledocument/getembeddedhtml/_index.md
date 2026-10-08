---
title: "GetEmbeddedHtml"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mengembalikan semua konten dokumen HTML ini beserta semua sumber terkait dalam bentuk satu string di mana semua sumber disematkan di dalam markup HTML dalam bentuk yang dienkode base64."
type: docs
weight: 150
url: /id/net/groupdocs.editor/editabledocument/getembeddedhtml/
---
## EditableDocument.GetEmbeddedHtml method

Mengembalikan semua konten dokumen HTML ini beserta semua sumber daya terkait dalam bentuk satu string, di mana semua sumber daya disematkan di dalam markup HTML dalam bentuk yang dienkode base64.

```csharp
public string GetEmbeddedHtml()
```

### Nilai Kembalian

String, yang tidak NULL atau kosong dalam kondisi apa pun

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ObjectDisposedException | Instansi EditableDocument ini sudah dibuang |

### Catatan

Metode ini mengonversi EditableDocument ini menjadi HTML dan menyerialkannya menjadi satu string, di mana semua sumber daya disematkan ke dalam string bersama dengan markup HTML:

* All images from HTML-&gt;BODY are converted to base64 format and are located in the IMG 'src' attribute
* All stylesheets are stored in the STYLE elements inside HTML-&gt;HEAD sections
* All images from stylesheets are converted to base64 format and located in the appropriate CSS declarations
* All fonts from stylesheets are converted to base64 format and located in the appropriate @font-face at-rules

### Lihat Juga

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
