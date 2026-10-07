---
title: "ToStringSpecified"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Renvoie une représentation sous forme de chaîne de cette longueur dans le type d'unité spécifié. La valeur numérique sera convertie en fonction du changement de type d'unité."
type: docs
weight: 260
url: /fr/net/groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified/
---
## Length.ToStringSpecified method

Renvoie une représentation sous forme de chaîne de cette longueur dans le type d'unité spécifié. La valeur numérique sera convertie en fonction du changement de type d'unité.

```csharp
public string ToStringSpecified(Unit unit)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| unit | Unit | Unité spécifiée, à laquelle cette instance doit être convertie avant d'être sérialisée en chaîne. Doit être valide. Ne peut pas être sans unité. |

### Valeur de retour

Représentation sous forme de chaîne

### Exceptions

| exception | condition |
| --- | --- |
| InvalidEnumArgumentException | La valeur n'est pas définie |
| ArgumentOutOfRangeException | La valeur sans unité est interdite |

### Voir aussi

* enum [Unit](../../length.unit)
* struct [Length](../../length)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
