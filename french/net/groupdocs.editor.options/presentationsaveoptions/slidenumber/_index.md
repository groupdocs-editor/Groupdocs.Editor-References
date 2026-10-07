---
title: "SlideNumber"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Permet d'insérer la diapositive modifiée dans une présentation existante au lieu de créer une nouvelle présentation à diapositive unique (comportement par défaut). Le numéro de diapositive est un nombre basé sur 1 d'une diapositive dans la présentation chargée dans la classe Editor. S'il est 0 (valeur par défaut), la nouvelle présentation sera créée avec une seule diapositive modifiée. S'il est supérieur ou inférieur à zéro et qu'une présentation valide est chargée dans la classe Editor, la diapositive modifiée stockée dans l'instance d'EditableDocument d'entrée sera insérée dans cette présentation."
type: docs
weight: 50
url: /fr/net/groupdocs.editor.options/presentationsaveoptions/slidenumber/
---
## PresentationSaveOptions.SlideNumber property

Permet d'insérer une diapositive modifiée dans une présentation existante au lieu de créer une nouvelle présentation à diapositive unique (comportement par défaut). Le numéro de diapositive est un nombre basé sur 1 de la diapositive dans la présentation, chargée dans la classe Editor. S'il est 0 (valeur par défaut), la nouvelle présentation sera créée avec une seule diapositive modifiée. S'il est supérieur ou inférieur à zéro, et qu'il existe une présentation valide chargée dans la classe Editor, la diapositive modifiée, stockée dans l'instance d'EditableDocument d'entrée, sera insérée dans cette présentation.

```csharp
public int SlideNumber { get; set; }
```

### Remarques

Propriété entière SlideNumber, si elle n'est pas dans l'état par défaut (valeur réservée '0'), représente un numéro de diapositive, donc elle commence à 1, pas à zéro, et sa valeur maximale est le nombre total de diapositives existantes dans une présentation. Cependant, si la valeur spécifiée est supérieure au nombre total de diapositives, GroupDocs.Editor l'ajustera pour désigner la dernière diapositive. Les valeurs négatives sont également autorisées et comptent les diapositives à partir de la fin. Par exemple, "-1" indique la dernière diapositive d'une présentation, "-2" — l'avant‑dernière, etc. Comme pour les valeurs positives, lorsque le numéro de diapositive négatif dépasse le nombre total de diapositives de la présentation donnée, il sera ajusté à la première diapositive. La propriété booléenne [`InsertAsNewSlide`](../insertasnewslide) est étroitement liée à celle‑ci.

### Exemples

Une présentation donnée possède 5 diapositives : SlideNumber = 0 ; — ignore la présentation donnée, crée une nouvelle présentation et y place la diapositive modifiée. SlideNumber = 1 ; — remplace la première diapositive par la diapositive modifiée SlideNumber = 2 ; — remplace la deuxième diapositive par la diapositive modifiée SlideNumber = 5 ; — remplace la dernière (5ᵉ) diapositive par la diapositive modifiée SlideNumber = 6 ; — remplace la dernière (5ᵉ) diapositive par la diapositive modifiée, car 6 est supérieur à 5 et est donc ajusté SlideNumber = -1 ; — remplace la dernière (5ᵉ) diapositive par la diapositive modifiée, car "-1" signifie "dernière existante" SlideNumber = -2 ; — remplace la 4ᵉ diapositive par la diapositive modifiée SlideNumber = -3 ; — remplace la 3ᵉ diapositive par la diapositive modifiée SlideNumber = -4 ; — remplace la 2ᵉ diapositive par la diapositive modifiée SlideNumber = -5 ; — remplace la première diapositive par la diapositive modifiée SlideNumber = -6 ; — remplace la première diapositive par la diapositive modifiée, car "-6" est supérieur à 5 et est donc ajusté

### Voir aussi

* class [PresentationSaveOptions](../../presentationsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
