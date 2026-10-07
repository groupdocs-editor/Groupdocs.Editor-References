---
title: "Css"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Permet d'obtenir les ressources de feuilles de style CSS, à la fois externes et intégrées mais pas en ligne, utilisées par ce document HTML"
type: docs
weight: 60
url: /fr/net/groupdocs.editor/editabledocument/css/
---
## EditableDocument.Css property

Permet d'obtenir les ressources de feuilles de style (CSS) (à la fois externes et intégrées, mais pas en ligne), qui sont utilisées par ce document HTML

```csharp
public List<CssText> Css { get; }
```

### Remarques

Cette méthode renvoie une copie superficielle de toutes les ressources de feuilles de style utilisées : `List` est une nouvelle instance à chaque appel, mais les instances de ressources sont les mêmes.

### Voir aussi

* class [CssText](../../../groupdocs.editor.htmlcss.resources.textual/csstext)
* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
