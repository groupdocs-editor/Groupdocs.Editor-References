---
title: "GetConsumptionCredit"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mengambil jumlah kredit yang digunakan."
type: docs
weight: 30
url: /id/net/groupdocs.editor/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

Mengambil jumlah kredit yang digunakan.

```csharp
public static decimal GetConsumptionCredit()
```

### Nilai Kembalian

Jumlah kredit yang sudah digunakan

### Contoh

Contoh berikut menunjukkan cara mengambil jumlah kredit yang dikonsumsi.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### Lihat Juga

* class [Metered](../../metered)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
