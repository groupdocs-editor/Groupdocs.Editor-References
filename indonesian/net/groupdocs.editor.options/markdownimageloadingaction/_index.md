---
title: MarkdownImageLoadingAction
second_title: GroupDocs.Editor untuk Referensi .NET API
description: Menentukan mode pemuatan gambar saat membuka untuk mengedit file dalam format Markdown
type: docs
weight: 980
url: /id/net/groupdocs.editor.options/markdownimageloadingaction/
---
## MarkdownImageLoadingAction enumeration

Menentukan mode pemuatan gambar saat membuka untuk mengedit file dalam format Markdown

```csharp
public enum MarkdownImageLoadingAction : byte
```

### Nilai

| Nama | Nilai | Keterangan |
| --- | --- | --- |
| Default | `0` | GroupDocs.Editor akan memuat sumber daya ini seperti biasa |
| Skip | `1` | GroupDocs.Editor akan melewatkan pemuatan gambar ini |
| UserProvided | `2` | GroupDocs.Editor akan menggunakan array byte yang disediakan oleh pengguna di[`SetData`](../markdownimageloadargs/setdata) sebagai data gambar |

### Lihat juga

* ruang nama [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* perakitan [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
