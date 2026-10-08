---
title: "Kata sandi"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Memungkinkan menentukan, mengubah, dan memperoleh kata sandi yang akan digunakan untuk membuka dokumen Presentation jika dienkripsi. Atur ke NULL atau string kosong untuk menghapus kata sandi."
type: docs
weight: 20
url: /id/net/groupdocs.editor.options/presentationloadoptions/password/
---
## PresentationLoadOptions.Password property

Memungkinkan menentukan, memodifikasi, dan memperoleh kata sandi yang akan digunakan untuk membuka dokumen Presentasi, jika dokumen tersebut terenkripsi. Atur ke NULL atau string kosong untuk menghapus kata sandi.

```csharp
public string Password { get; set; }
```

### Catatan

Secara default properti ini memiliki nilai NULL — kata sandi tidak diatur. Jika dokumen Presentation input dilindungi kata sandi, kata sandi wajib dan sebuah pengecualian akan dilempar jika kata sandi tidak diberikan atau tidak valid. Jika dokumen Presentation input TIDAK dilindungi kata sandi, tetapi kata sandi diatur, maka akan diabaikan.

### Lihat Juga

* class [PresentationLoadOptions](../../presentationloadoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
