---
title: "InputControlsClassName"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Permet de spécifier un nom de classe qui sera placé dans les attributs class de chaque élément HTML représentant un champ du document WordProcessing d’entrée. Par défaut, la valeur est NULL ; les attributs class ne sont pas appliqués."
type: docs
weight: 60
url: /fr/net/groupdocs.editor.options/wordprocessingeditoptions/inputcontrolsclassname/
---
## WordProcessingEditOptions.InputControlsClassName property

Permet de spécifier un nom de classe, qui sera placé dans les attributs 'class' de chaque élément HTML représentant un champ du document WordProcessing d'entrée. Par défaut, il est NULL - les attributs 'class' ne sont pas appliqués.

```csharp
public string InputControlsClassName { get; set; }
```

### Remarques

Presque tous les formats de la famille WordProcessing contiennent des champs — des entités de document spécifiques qui permettent de recueillir des données d’entrée auprès des utilisateurs. Il existe une grande variété de champs : zones de texte, cases à cocher, listes déroulantes, boutons, sélecteurs de date/heure, etc. Tous sont traduits en structures et éléments HTML les plus appropriés, en préservant les données saisies par l’utilisateur si elles sont présentes dans le document d’entrée. Dans certains cas d’utilisation, il suffit de récupérer les données saisies côté client au lieu de modifier l’ensemble du contenu du document. Dans ce cas, il faut identifier les contrôles d’entrée d’une manière ou d’une autre afin de les récupérer avec leurs données côté client. Cette propriété permet de spécifier un nom de classe qui sera appliqué à chaque contrôle d’entrée dans le balisage HTML, de sorte que le code client puisse parcourir la structure du document HTML et collecter les données.

### Voir aussi

* class [WordProcessingEditOptions](../../wordprocessingeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
