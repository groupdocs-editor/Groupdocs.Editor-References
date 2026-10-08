---
title: "DocumentFormatBase"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mewakili kelas dasar untuk format dokumen yang menyediakan fungsionalitas umum bagi instansi format."
type: docs
weight: 50
url: /id/net/groupdocs.editor.formats.abstraction/documentformatbase/
---
## DocumentFormatBase class

Mewakili kelas dasar untuk format dokumen, menyediakan fungsionalitas umum untuk instance format.

```csharp
public abstract class DocumentFormatBase : FormatFamilyBase, IDocumentFormat
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Mendapatkan ekstensi file dari format dokumen. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Mendapatkan keluarga format tempat format dokumen ini termasuk. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Mendapatkan pengidentifikasi unik untuk keluarga format. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Mendapatkan tipe MIME dari format dokumen. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Mendapatkan nama keluarga format. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Menentukan apakah instansi ini sama dengan instansi [`FormatFamilyBase`](../formatfamilybase) yang ditentukan. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals#equals_1)(IDocumentFormat) | Menentukan apakah instansi ini sama dengan instansi [`IDocumentFormat`](../idocumentformat) yang ditentukan. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals#equals_2)(object) | Menentukan apakah instansi ini sama dengan instansi [`DocumentFormatBase`](../documentformatbase) yang ditentukan. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Mengembalikan kode hash untuk objek saat ini. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Mengembalikan string yang merepresentasikan objek saat ini. |
| static [FromMime&lt;T&gt;](../../groupdocs.editor.formats.abstraction/documentformatbase/frommime)(string) | Mengambil sebuah instance dari tipe *T* yang ditentukan yang memiliki tipe MIME yang ditentukan. |
| [implicit operator](../../groupdocs.editor.formats.abstraction/documentformatbase/op_implicit) | Mengonversi sebuah instance [`DocumentFormatBase`](../documentformatbase) menjadi string secara implisit. |

### Lihat Juga

* class [FormatFamilyBase](../formatfamilybase)
* interface [IDocumentFormat](../idocumentformat)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
