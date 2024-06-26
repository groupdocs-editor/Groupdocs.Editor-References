---
title: GetConsumptionQuantity
second_title: GroupDocs.Editor for .NET API Reference
description: Retrieves amount of MBs processed.
type: docs
weight: 40
url: /net/groupdocs.editor/metered/getconsumptionquantity/
---
## Metered.GetConsumptionQuantity method

Retrieves amount of MBs processed.

```csharp
public static decimal GetConsumptionQuantity()
```

### Examples

Following example demonstrates how to retrieve amount of MBs processed.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### See Also

* class [Metered](../../metered)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
