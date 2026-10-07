---
title: "PdfSaveOptions"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Permet de spécifier des options personnalisées pour la génération et l'enregistrement de documents PDF Portable Document Format"
type: docs
weight: 1070
url: /fr/net/groupdocs.editor.options/pdfsaveoptions/
---
## PdfSaveOptions class

Permet de spécifier des options personnalisées pour générer et enregistrer des documents PDF (Portable Document Format)

```csharp
public sealed class PdfSaveOptions : ISaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Compliance](../../groupdocs.editor.options/pdfsaveoptions/compliance) { get; set; } | Spécifie le niveau de conformité aux normes PDF pour les documents de sortie. La valeur par défaut est PdfCompliance.Pdf17. |
| [FontEmbedding](../../groupdocs.editor.options/pdfsaveoptions/fontembedding) { get; set; } | Responsable de l'intégration des ressources de polices, utilisées dans le document original, dans le document PDF résultant. Par défaut, aucune police n'est intégrée (NotEmbed). |
| [OptimizeMemoryUsage](../../groupdocs.editor.options/pdfsaveoptions/optimizememoryusage) { get; set; } | Active les mécanismes d'optimisation de la mémoire lors de la génération de documents à partir de HTML, ce qui dégrade les performances en contrepartie d'une réduction de l'utilisation de la mémoire. Activer cette option (true) peut réduire considérablement la consommation de mémoire lors de la génération de gros documents, au prix d'un temps d'enregistrement plus lent. La valeur par défaut est false (l'optimisation de la mémoire est désactivée afin d'obtenir de meilleures performances). |
| [Password](../../groupdocs.editor.options/pdfsaveoptions/password) { get; set; } | Mot de passe qui sera appliqué au document PDF généré comme mot de passe utilisateur, requis pour l'ouverture. Si NULL ou vide, aucun mot de passe ne sera appliqué au document. Sinon, le document sera chiffré avec RC4 (longueur de clé de 128 bits). Par défaut, c'est NULL — le mot de passe n'est pas appliqué. |

### Voir aussi

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
