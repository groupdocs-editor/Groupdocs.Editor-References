---
title: "FromMarkupAndResourceFolder"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Fabrik statis yang membuat sebuah instansi EditableDocument dari markup HTML yang ditentukan dan dari sumber daya yang berada di folder yang ditentukan oleh jalur lengkap"
type: docs
weight: 30
url: /id/net/groupdocs.editor/editabledocument/frommarkupandresourcefolder/
---
## EditableDocument.FromMarkupAndResourceFolder method

Fabrik statis, yang membuat instance EditableDocument dari markup HTML yang ditentukan dan dari sumber daya yang berada di folder, yang ditentukan oleh path lengkap

```csharp
public static EditableDocument FromMarkupAndResourceFolder(string newHtmlContent, 
    string resourceFolderPath)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| newHtmlContent | String | String, yang berisi markup HTML mentah, yang harus diparsing. Tidak boleh NULL, kosong, atau tidak valid. |
| resourceFolderPath | String | Jalur wajib ke folder dengan sumber daya. Semua stylesheet yang berada di folder ini akan digunakan. Tidak boleh NULL atau string kosong, dan folder ini harus ada. |

### Nilai Kembalian

Instansi EditableDocument baru yang tidak null

### Catatan

Fabrik statis ini berguna ketika konten dokumen HTML disajikan sebagai string, tetapi semua sumber daya berada di suatu folder, dan seringkali tautan ke sumber daya ini dalam markup HTML tidak valid dan tidak ada. Saat memanggil metode ini, ia memindai folder yang ditentukan dan secara otomatis menerapkan semua stylesheet yang ditemukan ke dokumen. Metode ini sangat berguna saat memperoleh konten dari berbagai editor HTML, yang biasanya memotong metadata dokumen dan sebagainya.

### Lihat Juga

* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
