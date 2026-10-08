---
title: "LocaleId"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mendapatkan atau mengatur ID lokal bidang formulir yang mewakili budaya atau pengaturan regional yang terkait dengan bidang formulir."
type: docs
weight: 30
url: /id/net/groupdocs.editor.words.fieldmanagement/currenttimeformfield/localeid/
---
## CurrentTimeFormField.LocaleId property

Mendapatkan atau mengatur ID lokal bidang formulir, yang mewakili budaya atau pengaturan regional yang terkait dengan bidang formulir.

```csharp
public int LocaleId { get; set; }
```

### Catatan

Properti LocaleId menentukan pengidentifikasi lokal (LCID) yang sesuai dengan budaya atau wilayah tertentu.

### Contoh

Contoh berikut menunjukkan cara mengatur properti LocaleId:

```csharp
Set the LocaleId to represent the English (United States) culture
currentTimeField.LocaleId = new CultureInfo("en-US").LCID;
```

### Lihat Juga

* class [CurrentTimeFormField](../../currenttimeformfield)
* namespace [GroupDocs.Editor.Words.FieldManagement](../../../groupdocs.editor.words.fieldmanagement)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
