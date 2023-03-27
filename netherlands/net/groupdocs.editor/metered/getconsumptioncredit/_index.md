---
title: GetConsumptionCredit
second_title: GroupDocs.Editor voor .NET API-referentie
description: Haalt het aantal verbruikte credits op.
type: docs
weight: 30
url: /nl/net/groupdocs.editor/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

Haalt het aantal verbruikte credits op.

```csharp
public static decimal GetConsumptionCredit()
```

### Winstwaarde

Telling van reeds gebruikte credits

### Voorbeelden

Het volgende voorbeeld laat zien hoe u het aantal verbruikte credits kunt ophalen.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### Zie ook

* class [Metered](../../metered)
* naamruimte [GroupDocs.Editor](../../metered)
* montage [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->