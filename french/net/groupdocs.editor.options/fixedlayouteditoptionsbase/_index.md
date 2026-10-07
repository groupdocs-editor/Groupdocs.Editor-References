---
title: "FixedLayoutEditOptionsBase"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Classe abstraite de base pour les options de tous les documents aux formats à mise en page fixe comme PDF et XPS"
type: docs
weight: 870
url: /fr/net/groupdocs.editor.options/fixedlayouteditoptionsbase/
---
## FixedLayoutEditOptionsBase class

Classe abstraite de base pour les options de tous les documents aux formats à mise en page fixe comme PDF et XPS

```csharp
public abstract class FixedLayoutEditOptionsBase : IEditOptions
```

## Propriétés

| Nom | Description |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/fixedlayouteditoptionsbase/enablepagination) { get; set; } | Permet d'activer (true) ou de désactiver (false) la pagination dans le document HTML résultant. Par défaut, elle est désactivée (false). |
| [Pages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/pages) { get; set; } | Permet de définir une plage de pages à traiter. Par défaut, toutes les pages d'un document à mise en page fixe sont traitées. |
| [SkipImages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/skipimages) { get; set; } | Obtient ou définit le drapeau indiquant si les images doivent être ignorées lors de la conversion du document à mise en page fixe d'entrée vers le HTML résultant. La valeur par défaut est false - les images sont conservées. |

### Voir aussi

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
