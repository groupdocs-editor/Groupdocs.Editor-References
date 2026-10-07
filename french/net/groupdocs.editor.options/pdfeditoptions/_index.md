---
title: "PdfEditOptions"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Permet de spécifier des options personnalisées pour l’édition de documents PDF"
type: docs
weight: 1050
url: /fr/net/groupdocs.editor.options/pdfeditoptions/
---
## PdfEditOptions class

Permet de spécifier des options personnalisées pour l’édition de documents PDF

```csharp
public sealed class PdfEditOptions : FixedLayoutEditOptionsBase
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfEditOptions](pdfeditoptions#constructor)() | Crée et renvoie une nouvelle instance de la classe PdfEditOptions, où toutes les options sont définies à leurs valeurs par défaut |
| [PdfEditOptions](pdfeditoptions#constructor_1)(bool) | Crée et renvoie une nouvelle instance de la classe PdfEditOptions avec la pagination spécifiée et toutes les autres options par défaut |

## Propriétés

| Nom | Description |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/fixedlayouteditoptionsbase/enablepagination) { get; set; } | Permet d'activer (true) ou de désactiver (false) la pagination dans le document HTML résultant. Par défaut, elle est désactivée (false). |
| [Pages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/pages) { get; set; } | Permet de définir une plage de pages à traiter. Par défaut, toutes les pages d'un document à mise en page fixe sont traitées. |
| [SkipImages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/skipimages) { get; set; } | Obtient ou définit le drapeau indiquant si les images doivent être ignorées lors de la conversion du document à mise en page fixe d'entrée vers le HTML résultant. La valeur par défaut est false - les images sont conservées. |

### Voir aussi

* class [FixedLayoutEditOptionsBase](../fixedlayouteditoptionsbase)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
