---
title: "FromNumber"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Crée une épaisseur de police à partir du nombre spécifié"
type: docs
weight: 50
url: /fr/net/groupdocs.editor.htmlcss.css.properties/fontweight/fromnumber/
---
## FontWeight.FromNumber method

Crée un font-weight à partir du nombre spécifié.

```csharp
public static FontWeight FromNumber(ushort number)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nombre | UInt16 | Entier non signé, doit être dans la plage [1..1000] |

### Valeur de retour

Nouvelle instance FontWeight ou exception

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | Le nombre spécifié est hors de la plage [1..1000] |

### Voir aussi

* struct [FontWeight](../../fontweight)
* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
