---
title: "Polices"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Permet d'obtenir les ressources de polices externes utilisées par ce document HTML"
type: docs
weight: 70
url: /fr/net/groupdocs.editor/editabledocument/fonts/
---
## EditableDocument.Fonts property

Permet d'obtenir les ressources de polices externes, qui sont utilisées par ce document HTML

```csharp
public List<FontResourceBase> Fonts { get; }
```

### Remarques

Cette méthode renvoie une copie superficielle de toutes les ressources de polices utilisées : `List` est une nouvelle instance à chaque appel, mais les instances de ressources sont les mêmes.

### Voir aussi

* class [FontResourceBase](../../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase)
* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
