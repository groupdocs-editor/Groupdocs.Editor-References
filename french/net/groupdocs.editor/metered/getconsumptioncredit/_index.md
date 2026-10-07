---
title: "GetConsumptionCredit"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Récupère le nombre de crédits consommés."
type: docs
weight: 30
url: /fr/net/groupdocs.editor/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

Récupère le nombre de crédits consommés.

```csharp
public static decimal GetConsumptionCredit()
```

### Valeur de retour

Nombre de crédits déjà utilisés

### Exemples

L'exemple suivant montre comment récupérer le nombre de crédits consommés.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### Voir aussi

* class [Metered](../../metered)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
