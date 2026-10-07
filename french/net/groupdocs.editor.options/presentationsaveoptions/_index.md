---
title: "PresentationSaveOptions"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Permet de spécifier des options personnalisées pour la génération et l'enregistrement de documents Presentation compatibles PowerPoint"
type: docs
weight: 1100
url: /fr/net/groupdocs.editor.options/presentationsaveoptions/
---
## PresentationSaveOptions class

Permet de spécifier des options personnalisées pour générer et enregistrer des documents de présentation (PowerPoint-compatible)

```csharp
public sealed class PresentationSaveOptions : ISaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PresentationSaveOptions](presentationsaveoptions#constructor)() | Ce constructeur sans paramètres crée une nouvelle instance de PresentationSaveOptions avec le format de sortie PPTX (peut ensuite être modifié via la propriété [`OutputFormat`](./outputformat)) |
| [PresentationSaveOptions](presentationsaveoptions#constructor_1)(PresentationFormats) | Crée une nouvelle instance de PresentationSaveOptions avec le format de sortie Presentation obligatoire spécifié, tandis que tous les autres paramètres sont par défaut |

## Propriétés

| Nom | Description |
| --- | --- |
| [InsertAsNewSlide](../../groupdocs.editor.options/presentationsaveoptions/insertasnewslide) { get; set; } | Drapeau booléen qui spécifie si la diapositive modifiée doit remplacer la diapositive existante dans la présentation originale à la position spécifiée par la propriété [`SlideNumber`](./slidenumber), ou si elle doit être insérée entre la diapositive existante et la précédente, sans remplacer son contenu. Par défaut, c'est `false` — la diapositive existante sera remplacée. Cette propriété est ignorée si la valeur de la propriété [`SlideNumber`](./slidenumber) est définie à `'0'. |
| [OutputFormat](../../groupdocs.editor.options/presentationsaveoptions/outputformat) { get; set; } | Permet de spécifier un format Presentation qui sera utilisé pour enregistrer le document |
| [Password](../../groupdocs.editor.options/presentationsaveoptions/password) { get; set; } | Permet de spécifier, modifier et obtenir le mot de passe qui sera utilisé pour coder le document Presentation résultant. Par défaut, c'est NULL — le mot de passe ne sera pas défini. Définissez-le sur NULL ou une chaîne vide pour supprimer le mot de passe, s'il avait été défini auparavant. |
| [SlideNumber](../../groupdocs.editor.options/presentationsaveoptions/slidenumber) { get; set; } | Permet d'insérer une diapositive modifiée dans une présentation existante au lieu de créer une nouvelle présentation à diapositive unique (comportement par défaut). Le numéro de diapositive est un nombre basé sur 1 de la diapositive dans la présentation, chargée dans la classe Editor. S'il est 0 (valeur par défaut), la nouvelle présentation sera créée avec une seule diapositive modifiée. S'il est supérieur ou inférieur à zéro, et qu'il existe une présentation valide chargée dans la classe Editor, la diapositive modifiée, stockée dans l'instance d'EditableDocument d'entrée, sera insérée dans cette présentation. |
| [SlideNumbersToDelete](../../groupdocs.editor.options/presentationsaveoptions/slidenumberstodelete) { get; set; } | Permet de spécifier un tableau avec des numéros de diapositives basés sur 1 qui doivent être supprimés de la présentation lors de son enregistrement, dans le cas où la diapositive modifiée est insérée dans une présentation existante |

### Remarques

Une instance de cette classe doit être passée à la méthode  afin d'enregistrer la présentation modifiée dans le document final d'un format spécifique à Presentation. Tous les autres paramètres sont optionnels et peuvent être omis ; par défaut, le format de la présentation enregistrée est PPTX, mais il peut être changé via le constructeur ou la propriété.

### Voir aussi

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
