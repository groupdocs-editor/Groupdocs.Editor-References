---
title: "ExtractOnlyUsedFont"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Obtient ou définit une valeur indiquant s'il faut extraire uniquement les ressources de police utilisées dans le contenu textuel du document."
type: docs
weight: 40
url: /fr/net/groupdocs.editor.options/wordprocessingeditoptions/extractonlyusedfont/
---
## WordProcessingEditOptions.ExtractOnlyUsedFont property

Obtient ou définit une valeur indiquant s'il faut extraire uniquement les ressources de police utilisées dans le contenu textuel du document.

```csharp
public bool ExtractOnlyUsedFont { get; set; }
```

### Property Value

`true` si l'extraction doit se limiter uniquement aux ressources de police utilisées dans le contenu texte du document ; sinon, `false`. La valeur par défaut est `false`.

### Remarques

Toutes les polices utilisées dans le document WordProcessing ne sont pas 100 % utilisées directement (appliquées à du texte). Il peut arriver qu’une police soit référencée dans le document et même incorporée, mais qu’elle ne soit appliquée à aucun morceau de texte. Par exemple, une police peut être attachée à un style, mais ce style n’est appliqué à aucune partie du texte. Cette option contrôle la façon de traiter de tels cas.

### Voir aussi

* class [WordProcessingEditOptions](../../wordprocessingeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
