---
title: "ExportImagesAsBase64"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Spécifie si les images sont enregistrées au format Base64 dans le fichier de sortie. La valeur par défaut est false."
type: docs
weight: 20
url: /fr/net/groupdocs.editor.options/markdownsaveoptions/exportimagesasbase64/
---
## MarkdownSaveOptions.ExportImagesAsBase64 property

Spécifie si les images sont enregistrées au format Base64 dans le fichier de sortie. La valeur par défaut est `false`.

```csharp
public bool ExportImagesAsBase64 { get; set; }
```

### Remarques

Lorsque cette propriété est définie sur `true`, les données d'images sont exportées directement dans les éléments image ![]() et aucun fichier séparé n'est créé. Cette propriété, si elle est définie sur `true`, a une priorité supérieure à celle de la propriété [`ImagesFolder`](../imagesfolder).

### Voir aussi

* class [MarkdownSaveOptions](../../markdownsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
