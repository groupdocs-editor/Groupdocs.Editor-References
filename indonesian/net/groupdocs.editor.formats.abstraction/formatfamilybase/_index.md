---
title: "FormatFamilyBase"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mewakili kelas dasar untuk keluarga format yang menyediakan fungsionalitas umum bagi instance keluarga format."
type: docs
weight: 60
url: /id/net/groupdocs.editor.formats.abstraction/formatfamilybase/
---
## FormatFamilyBase class

Mewakili kelas dasar untuk keluarga format, menyediakan fungsionalitas umum untuk instance keluarga format.

```csharp
public abstract class FormatFamilyBase : IEquatable<FormatFamilyBase>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Mendapatkan pengidentifikasi unik untuk keluarga format. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Mendapatkan nama keluarga format. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals#equals)(FormatFamilyBase) | Menentukan apakah instansi ini sama dengan instansi [`FormatFamilyBase`](../formatfamilybase) yang ditentukan. |
| override [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals#equals_1)(object) | Menentukan apakah instansi ini sama dengan instansi [`FormatFamilyBase`](../formatfamilybase) yang ditentukan. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/formatfamilybase/gethashcode)() | Mengembalikan kode hash untuk objek saat ini. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Mengembalikan string yang merepresentasikan objek saat ini. |
| static [FromName&lt;T&gt;](../../groupdocs.editor.formats.abstraction/formatfamilybase/fromname)(string) | Mengambil sebuah instance dari tipe *T* yang ditentukan yang memiliki nama yang ditentukan. |
| static [FromValue&lt;T&gt;](../../groupdocs.editor.formats.abstraction/formatfamilybase/fromvalue)(int) | Mengambil sebuah instance dari tipe *T* yang ditentukan yang memiliki pengidentifikasi yang ditentukan. |
| static [GetAll&lt;T&gt;](../../groupdocs.editor.formats.abstraction/formatfamilybase/getall)() | Mengambil semua instance dari tipe *T* yang ditentukan yang diturunkan dari [`FormatFamilyBase`](../formatfamilybase). |
| [operator ==](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_equality#op_equality) | Menentukan apakah dua instance [`FormatFamilyBase`](../formatfamilybase) sama. (2 operator) |
| [explicit operator](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_explicit#op_explicit_1) | Mengonversi string yang mewakili nama keluarga format menjadi objek [`FormatFamilyBase`](../formatfamilybase). (2 operator) |
| [implicit operator](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_implicit#op_implicit) | Mengonversi sebuah instance [`FormatFamilyBase`](../formatfamilybase) menjadi integer secara implisit. (2 operator) |
| [operator !=](../../groupdocs.editor.formats.abstraction/formatfamilybase/op_inequality#op_inequality) | Menentukan apakah dua instance [`FormatFamilyBase`](../formatfamilybase) tidak sama. (2 operator) |

### Catatan

Kelas ini bersifat abstrak dan harus diwarisi oleh kelas turunan yang menentukan detail keluarga format yang sebenarnya.

### Lihat Juga

* namespace [GroupDocs.Editor.Formats.Abstraction](../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
