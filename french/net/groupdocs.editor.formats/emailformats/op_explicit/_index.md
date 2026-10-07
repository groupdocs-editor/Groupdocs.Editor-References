---
title: "op_Explicit"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Convertit une chaîne représentant une extension de fichier en un objet EmailFormatsgroupdocs.editor.formats/emailformats."
type: docs
weight: 150
url: /fr/net/groupdocs.editor.formats/emailformats/op_explicit/
---
## EmailFormats Explicit operator

Convertit une chaîne représentant une extension de fichier en un objet [`EmailFormats`](../../emailformats).

```csharp
public static explicit operator EmailFormats(string extension)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| extension | String | L'extension de fichier à convertir. Si l'extension contient plusieurs points, la partie après le dernier point est utilisée. |

### Valeur de retour

Un objet [`EmailFormats`](../../emailformats) correspondant à l'extension de fichier spécifiée.

### Exceptions

| exception | condition |
| --- | --- |
| [EmailFormats](../../emailformats) | Lancée lorsque l'extension de fichier spécifiée est nulle. |

### Voir aussi

* class [EmailFormats](../../emailformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
