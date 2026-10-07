---
title: "op_Explicit"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Convertit une chaîne représentant une extension de fichier en un objet WordProcessingFormatsgroupdocs.editor.formats/wordprocessingformats."
type: docs
weight: 140
url: /fr/net/groupdocs.editor.formats/wordprocessingformats/op_explicit/
---
## WordProcessingFormats Explicit operator

Convertit une chaîne représentant une extension de fichier en un objet [`WordProcessingFormats`](../../wordprocessingformats).

```csharp
public static explicit operator WordProcessingFormats(string extension)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| extension | String | L'extension de fichier à convertir. Si l'extension contient plusieurs points, la partie après le dernier point est utilisée. |

### Valeur de retour

Un objet [`WordProcessingFormats`](../../wordprocessingformats) correspondant à l'extension de fichier spécifiée.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque l'extension de fichier spécifiée est nulle. |

### Voir aussi

* class [WordProcessingFormats](../../wordprocessingformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
