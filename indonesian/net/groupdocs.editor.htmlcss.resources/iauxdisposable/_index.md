---
title: "IAuxDisposable"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Memperluas antarmuka IDisposable standar yang memungkinkan memperoleh keadaan saat ini dari sebuah objek dan berlangganan pada peristiwa pembuangan"
type: docs
weight: 420
url: /id/net/groupdocs.editor.htmlcss.resources/iauxdisposable/
---
## IAuxDisposable interface

Memperluas antarmuka IDisposable standar, memungkinkan memperoleh status terkini dari sebuah objek dan berlangganan pada peristiwa disposing

```csharp
public interface IAuxDisposable : IDisposable
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources/iauxdisposable/isdisposed) { get; } | Menentukan apakah sebuah sumber daya ditutup (true) atau tidak (false) |

## Peristiwa

| Nama | Deskripsi |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources/iauxdisposable/disposed) | Terjadi ketika objek dibuang |

### Lihat Juga

* namespace [GroupDocs.Editor.HtmlCss.Resources](../../groupdocs.editor.htmlcss.resources)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
