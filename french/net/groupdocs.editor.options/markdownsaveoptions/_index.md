---
title: "MarkdownSaveOptions"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Permet de spécifier des options personnalisées pour générer et enregistrer des documents Markdown"
type: docs
weight: 1000
url: /fr/net/groupdocs.editor.options/markdownsaveoptions/
---
## MarkdownSaveOptions class

Permet de spécifier des options personnalisées pour générer et enregistrer des documents Markdown

```csharp
public sealed class MarkdownSaveOptions : ISaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [ExportImagesAsBase64](../../groupdocs.editor.options/markdownsaveoptions/exportimagesasbase64) { get; set; } | Spécifie si les images sont enregistrées au format Base64 dans le fichier de sortie. La valeur par défaut est `false`. |
| [ImagesFolder](../../groupdocs.editor.options/markdownsaveoptions/imagesfolder) { get; set; } | Spécifie le dossier physique où les images sont enregistrées lors de l'exportation d'un document au format Markdown. La valeur par défaut est null. |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/markdownsaveoptions/optimizememoryusage) { get; set; } | Active les mécanismes d'optimisation de la mémoire lors de la génération de documents à partir de HTML, ce qui dégrade les performances en contrepartie d'une réduction de l'utilisation de la mémoire. Régler cette option sur `true` peut réduire considérablement la consommation de mémoire lors de la génération de gros documents au prix d'un temps d'enregistrement plus lent. La valeur par défaut est `false` (l'optimisation de la mémoire est désactivée pour de meilleures performances). |
| [TableContentAlignment](../../groupdocs.editor.options/markdownsaveoptions/tablecontentalignment) { get; set; } | Permet de spécifier comment aligner le contenu dans les tableaux lors de l'exportation au format Markdown. La valeur par défaut est Auto. |

### Remarques

La classe MarkdownSaveOptions doit être appliquée par l'utilisateur lorsqu'il existe une instance de la classe EditableDocument, qui contient le contenu d'un document modifié, et qu'il est nécessaire d'enregistrer ce contenu dans un nouveau document au format Markdown.

### Voir aussi

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
