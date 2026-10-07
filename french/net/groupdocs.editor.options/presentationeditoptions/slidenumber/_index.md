---
title: "SlideNumber"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Permet de spécifier les numéros de diapositives qui doivent être ouverts pour l’édition"
type: docs
weight: 30
url: /fr/net/groupdocs.editor.options/presentationeditoptions/slidenumber/
---
## PresentationEditOptions.SlideNumber property

Permet de spécifier les numéros de diapositives qui doivent être ouverts pour l'édition

```csharp
public int SlideNumber { get; set; }
```

### Remarques

Le numéro de diapositive est un indice basé sur zéro d’une diapositive, qui permet de spécifier et de sélectionner une diapositive particulière d’une présentation à éditer. Si la valeur est inférieure à 0, la première diapositive sera sélectionnée (équivalent à SlideNumber = 0). Si elle est supérieure au nombre total de diapositives de la présentation, la dernière diapositive sera sélectionnée. Si la présentation d’entrée ne contient qu’une seule diapositive, cette option sera ignorée et cette diapositive unique sera éditée. Si l’on tente d’ouvrir pour édition une diapositive masquée alors que l’option [`ShowHiddenSlides`](../showhiddenslides) est définie sur 'false', une exception sera levée.

### Voir aussi

* class [PresentationEditOptions](../../presentationeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
