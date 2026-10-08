---
title: "GetConsumptionQuantity"
second_title: "Referensi API GroupDocs.Editor untuk .NET"
description: "Mengambil jumlah MB yang diproses."
type: docs
weight: 40
url: /id/net/groupdocs.editor/metered/getconsumptionquantity/
---
## Metered.GetConsumptionQuantity method

Mengambil jumlah MB yang diproses.

```csharp
public static decimal GetConsumptionQuantity()
```

### Contoh

Contoh berikut menunjukkan cara mengambil jumlah MB yang diproses.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### Lihat Juga

* class [Metered](../../metered)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- JANGAN SUNTING: dihasilkan oleh xmldocmd untuk GroupDocs.editor.dll -->
