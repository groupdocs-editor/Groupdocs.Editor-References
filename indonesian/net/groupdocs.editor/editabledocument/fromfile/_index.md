---
title: "FromFile"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Factory statis yang membuat instance EditableDocument dari file HTML yang ditentukan oleh path ke file .html itu sendiri dan folder dengan sumber daya yang ditautkan"
type: docs
weight: 10
url: /id/net/groupdocs.editor/editabledocument/fromfile/
---
## EditableDocument.FromFile method

Fabrik statis, yang membuat instance EditableDocument dari file HTML, yang ditentukan oleh path ke file *.html itu sendiri dan folder dengan sumber daya yang terhubung

```csharp
public static EditableDocument FromFile(string htmlFilePath, string resourceFolderPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| htmlFilePath | String | String yang berisi path lengkap ke file HTML. Tidak boleh null, harus merupakan path file yang valid, dan file itu sendiri harus ada. |
| resourceFolderPath | String | Path opsional ke folder dengan sumber daya HTML. Jika NULL, tidak valid, atau folder tersebut tidak ada, Editor akan mencoba menemukan folder ini sendiri dengan menganalisis markup HTML |

### Nilai Kembalian

Instansi EditableDocument baru yang tidak null

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentException | Path file HTML, dan/atau path folder sumber daya tidak valid |
| FileNotFoundException | File HTML yang ditentukan tidak dapat ditemukan |

### Lihat Juga

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
