---
title: "EmailEditOptions"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Permet de spécifier des options personnalisées pour l'édition de documents dans les différents formats de courrier électronique"
type: docs
weight: 850
url: /fr/net/groupdocs.editor.options/emaileditoptions/
---
## EmailEditOptions class

Permet de spécifier des options personnalisées pour l’édition de documents dans les différents formats de courrier électronique (email)

```csharp
public sealed class EmailEditOptions : IEditOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [EmailEditOptions](emaileditoptions#constructor)() | Initialise une nouvelle instance de la classe [`EmailEditOptions`](../emaileditoptions), où toutes les options sont définies à leurs valeurs par défaut |
| [EmailEditOptions](emaileditoptions#constructor_1)(MailMessageOutput) | Initialise une nouvelle instance de la classe [`EmailEditOptions`](../emaileditoptions) avec le paramètre [`MailMessageOutput`](./mailmessageoutput) |

## Propriétés

| Nom | Description |
| --- | --- |
| [MailMessageOutput](../../groupdocs.editor.options/emaileditoptions/mailmessageoutput) { get; set; } | Permet de contrôler quelles parties du message électronique doivent être livrées à la sortie [`EditableDocument`](../../groupdocs.editor/editabledocument) puis au HTML généré |

### Voir aussi

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
