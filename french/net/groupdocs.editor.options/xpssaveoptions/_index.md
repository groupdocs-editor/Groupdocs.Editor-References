---
title: "XpsSaveOptions"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Permet de spécifier des options personnalisées pour la génération et l'enregistrement de documents XPS (XML Paper Specification)"
type: docs
weight: 1300
url: /fr/net/groupdocs.editor.options/xpssaveoptions/
---
## XpsSaveOptions class

Permet de spécifier des options personnalisées pour générer et enregistrer des documents XPS (XML Paper Specifications)

```csharp
public sealed class XpsSaveOptions : ISaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [XpsSaveOptions](xpssaveoptions)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/xpssaveoptions/optimizememoryusage) { get; set; } | Active les mécanismes d'optimisation de la mémoire lors de la génération de documents à partir de HTML, ce qui dégrade les performances en contrepartie d'une réduction de l'utilisation de la mémoire. Activer cette option (true) peut réduire considérablement la consommation de mémoire lors de la génération de gros documents, au prix d'un temps d'enregistrement plus lent. La valeur par défaut est false (l'optimisation de la mémoire est désactivée afin d'obtenir de meilleures performances). |

### Remarques

Un fichier XPS représente des fichiers de mise en page basés sur les XML Paper Specifications créées par Microsoft. Il a été développé comme remplacement du format de fichier EMF et est similaire au format PDF, mais utilise du XML pour les informations de mise en page, d'apparence et d'impression d'un document.

### Voir aussi

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
