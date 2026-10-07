---
title: "SlideNumbersToDelete"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Permet de spécifier un tableau contenant les numéros (basés sur 1) des diapositives qui doivent être supprimées de la présentation lors de son enregistrement dans le cas où la diapositive modifiée est insérée dans une présentation existante"
type: docs
weight: 60
url: /fr/net/groupdocs.editor.options/presentationsaveoptions/slidenumberstodelete/
---
## PresentationSaveOptions.SlideNumbersToDelete property

Permet de spécifier un tableau avec des numéros de diapositives basés sur 1 qui doivent être supprimés de la présentation lors de son enregistrement, dans le cas où la diapositive modifiée est insérée dans une présentation existante

```csharp
public int[] SlideNumbersToDelete { get; set; }
```

### Remarques

Lorsque la diapositive modifiée n'est pas enregistrée comme une nouvelle présentation à diapositive unique (comportement par défaut), mais est enregistrée dans une présentation existante (en utilisant la propriété [`SlideNumber`](../slidenumber)), il est également possible de supprimer certaines diapositives particulières de cette présentation en spécifiant leurs numéros dans ce tableau.

Par défaut, ce tableau est `null` — aucune diapositive ne sera supprimée. Cependant, lorsque ce tableau n'est pas nul et n'est pas vide, et qu'il contient au moins un numéro de diapositive valide, après la génération du document de Présentation de sortie avec le contenu de la diapositive modifiée, les diapositives portant les numéros spécifiés seront supprimées de la présentation juste avant d'écrire son contenu dans le flux ou le fichier de sortie.

Les numéros de diapositive dans ce tableau sont indexés à partir de 1, pas de 0 ; les numéros invalides (inférieurs à 1 ou supérieurs au nombre total de diapositives) seront ignorés.

### Voir aussi

* class [PresentationSaveOptions](../../presentationsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
