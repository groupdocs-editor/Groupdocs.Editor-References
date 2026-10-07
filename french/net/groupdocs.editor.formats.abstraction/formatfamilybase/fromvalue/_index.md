---
title: "FromValue"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Récupère une instance du type T spécifié qui possède l'identifiant spécifié."
type: docs
weight: 70
url: /fr/net/groupdocs.editor.formats.abstraction/formatfamilybase/fromvalue/
---
## FormatFamilyBase.FromValue&lt;T&gt; method

Récupère une instance du type spécifié *T* qui possède l'identifiant spécifié.

```csharp
public static T FromValue<T>(int value)
    where T : FormatFamilyBase
```

| Paramètre | Description |
| --- | --- |
| T | Le type de famille de format. |
| valeur | L'identifiant de la famille de format. |

### Valeur de retour

Une instance du type *T* spécifié avec l'identifiant spécifié.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Lancée lorsqu'aucune famille de format correspondante n'est trouvée. |

### Voir aussi

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
