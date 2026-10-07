---
title: "FromName"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Récupère une instance du type T spécifié qui possède le nom spécifié."
type: docs
weight: 60
url: /fr/net/groupdocs.editor.formats.abstraction/formatfamilybase/fromname/
---
## FormatFamilyBase.FromName&lt;T&gt; method

Récupère une instance du type spécifié *T* qui possède le nom spécifié.

```csharp
public static T FromName<T>(string name)
    where T : FormatFamilyBase
```

| Paramètre | Description |
| --- | --- |
| T | Le type de famille de format. |
| nom | Le nom de la famille de format. |

### Valeur de retour

Une instance du type *T* spécifié avec le nom spécifié.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Lancée lorsqu'aucune famille de format correspondante n'est trouvée. |

### Voir aussi

* class [FormatFamilyBase](../../formatfamilybase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
