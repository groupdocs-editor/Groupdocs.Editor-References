---
title: "InsertAsNewSlide"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Indicateur booléen qui spécifie si la diapositive modifiée doit remplacer la diapositive existante dans la présentation originale à la position indiquée par la propriété SlideNumbergroupdocs.editor.options/presentationsaveoptions/slidenumber ou si elle doit être insérée entre la diapositive existante et la précédente sans remplacer son contenu. Par défaut, il est false ; la diapositive existante sera remplacée. Cette propriété est ignorée si la valeur de la propriété SlideNumbergroupdocs.editor.options/presentationsaveoptions/slidenumber est définie sur 0."
type: docs
weight: 20
url: /fr/net/groupdocs.editor.options/presentationsaveoptions/insertasnewslide/
---
## PresentationSaveOptions.InsertAsNewSlide property

Indicateur booléen qui spécifie si la diapositive modifiée doit remplacer la diapositive existante dans la présentation originale à la position indiquée par la propriété [`SlideNumber`](../slidenumber), ou si elle doit être insérée entre la diapositive existante et la précédente, sans remplacer son contenu. Par défaut, il est `false` — la diapositive existante sera remplacée. Cette propriété est ignorée si la valeur de la propriété [`SlideNumber`](../slidenumber) est définie sur `'0'`.

```csharp
public bool InsertAsNewSlide { get; set; }
```

### Remarques

Par défaut, la diapositive est remplacée. Cela signifie que si la présentation fournie comporte 5 diapositives et que [`SlideNumber`](../slidenumber)=4, alors la 4ᵉ diapositive sera remplacée par la nouvelle diapositive modifiée, tandis que le nombre total de diapositives dans la présentation (5) restera inchangé. Cependant, si la valeur de cette propriété est définie sur true, la nouvelle diapositive modifiée sera insérée comme 4ᵉ diapositive, et toutes les diapositives suivantes seront décalées vers la fin : la « ancienne » 4ᵉ diapositive devient la 5ᵉ, et la 5ᵉ devient la 6ᵉ, et le nombre total de diapositives dans la présentation sera incrémenté de un pour atteindre 6.

### Voir aussi

* class [PresentationSaveOptions](../../presentationsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
