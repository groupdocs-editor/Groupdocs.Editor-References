---
title: "Images"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Permet d'obtenir les ressources d'images externes raster et vectorielles utilisées par ce document HTML"
type: docs
weight: 80
url: /fr/net/groupdocs.editor/editabledocument/images/
---
## EditableDocument.Images property

Permet d'obtenir les ressources d'images externes (images raster et vectorielles), qui sont utilisées par ce document HTML

```csharp
public List<IImageResource> Images { get; }
```

### Remarques

Cette méthode renvoie une copie superficielle de toutes les ressources d'images utilisées : `List` est une nouvelle instance à chaque appel, mais les instances de ressources sont les mêmes.

### Voir aussi

* interface [IImageResource](../../../groupdocs.editor.htmlcss.resources.images/iimageresource)
* class [EditableDocument](../../editabledocument)
* namespace [GroupDocs.Editor](../../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
