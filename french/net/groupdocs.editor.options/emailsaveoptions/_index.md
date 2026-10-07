---
title: "EmailSaveOptions"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Permet de spécifier des options personnalisées pour la génération et l'enregistrement de documents de courrier électronique."
type: docs
weight: 860
url: /fr/net/groupdocs.editor.options/emailsaveoptions/
---
## EmailSaveOptions class

Permet de spécifier des options personnalisées pour générer et enregistrer des documents de courrier électronique (email)

```csharp
public sealed class EmailSaveOptions : ISaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [EmailSaveOptions](emailsaveoptions#constructor)() | Initialise une nouvelle instance de la classe [`EmailSaveOptions`](../emailsaveoptions), où toutes les options sont définies à leurs valeurs par défaut. |
| [EmailSaveOptions](emailsaveoptions#constructor_1)(MailMessageOutput) | Initialise une nouvelle instance de la classe [`EmailSaveOptions`](../emailsaveoptions) avec le paramètre [`MailMessageOutput`](./mailmessageoutput). |

## Propriétés

| Nom | Description |
| --- | --- |
| [MailMessageOutput](../../groupdocs.editor.options/emailsaveoptions/mailmessageoutput) { get; set; } | Permet de contrôler quelles parties du message électronique doivent être transférées vers le document email de sortie, qui sera généré et enregistré avec la méthode [`Save`](../../groupdocs.editor/editor/save). |

### Voir aussi

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
