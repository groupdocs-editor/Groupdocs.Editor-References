---
title: "RecognizeLists"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Permet de spécifier comment les éléments de listes numérotées sont reconnus lorsque le document est importé depuis un format texte brut. La valeur par défaut est vraie."
type: docs
weight: 60
url: /fr/net/groupdocs.editor.options/texteditoptions/recognizelists/
---
## TextEditOptions.RecognizeLists property

Permet de spécifier comment les éléments de listes numérotées sont reconnus lorsque le document est importé depuis un format texte brut. La valeur par défaut est vraie.

```csharp
public bool RecognizeLists { get; set; }
```

### Remarques

Si cette option est définie sur false, l'algorithme de reconnaissance des listes détecte les paragraphes de listes lorsque les numéros de liste se terminent par un point, une parenthèse fermante ou des symboles de puces (comme "•", "*", "-" ou "o"). Si cette option est définie sur true, les espaces sont également utilisés comme délimiteurs de numéros de liste : l'algorithme de reconnaissance des listes pour la numérotation de style arabe (1., 1.1.2.) utilise à la fois les espaces et le symbole point (".").

### Voir aussi

* class [TextEditOptions](../../texteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
