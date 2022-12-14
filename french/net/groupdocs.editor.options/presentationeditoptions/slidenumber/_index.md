---
title: SlideNumber
second_title: Référence de l'API GroupDocs.Editor pour .NET
description: Permet de spécifier les numéros des diapositives qui doivent être ouvertes pour lédition
type: docs
weight: 30
url: /fr/net/groupdocs.editor.options/presentationeditoptions/slidenumber/
---
## PresentationEditOptions.SlideNumber property

Permet de spécifier les numéros des diapositives, qui doivent être ouvertes pour l'édition

```csharp
public int SlideNumber { get; set; }
```

### Remarques

Le numéro de diapositive est un index de base zéro d'une diapositive, qui permet de spécifier et de sélectionner une diapositive particulière d'une présentation à modifier. Si inférieur à 0, la première diapositive sera sélectionnée (identique à SlideNumber = 0). Si le nombre de toutes les diapositives de la présentation est supérieur, la dernière diapositive sera sélectionnée. Si la présentation d'entrée ne contient qu'une seule diapositive, cette option sera ignorée et cette diapositive unique sera modifiée. Si vous essayez d'ouvrir pour modifier une diapositive masquée, alors que[`ShowHiddenSlides`](../showhiddenslides) option est définie sur 'false', l'exception sera levée.

### Voir également

* class [PresentationEditOptions](../../presentationeditoptions)
* espace de noms [GroupDocs.Editor.Options](../../presentationeditoptions)
* Assemblée [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
