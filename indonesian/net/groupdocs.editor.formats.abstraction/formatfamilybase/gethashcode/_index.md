---
title: "GetHashCode"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mengembalikan kode hash untuk objek saat ini."
type: docs
weight: 40
url: /id/net/groupdocs.editor.formats.abstraction/formatfamilybase/gethashcode/
---
## FormatFamilyBase.GetHashCode method

Mengembalikan kode hash untuk objek saat ini.

```csharp
public override int GetHashCode()
```

### Nilai Kembalian

Kode hash untuk objek saat ini, cocok untuk digunakan dalam algoritma hashing dan struktur data seperti tabel hash.

### Catatan

Metode ini menggantikan GetHashCode. Kode hash dihitung menggunakan properti `Id` dan `Name` objek. Konteks `unchecked` memungkinkan overflow, yang dapat diterima dalam konteks perhitungan kode hash.

### Lihat Juga

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
