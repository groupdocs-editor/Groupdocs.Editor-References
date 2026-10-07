---
title: "op_Explicit"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Convertit une chaîne représentant une extension de fichier en un objet EBookFormatsgroupdocs.editor.formats/ebookformats."
type: docs
weight: 60
url: /fr/net/groupdocs.editor.formats/ebookformats/op_explicit/
---
## EBookFormats Explicit operator

Convertit une chaîne représentant une extension de fichier en un objet [`EBookFormats`](../../ebookformats).

```csharp
public static explicit operator EBookFormats(string extension)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| extension | String | L'extension de fichier à convertir. Si l'extension contient plusieurs points, la partie après le dernier point est utilisée. |

### Valeur de retour

Un objet [`EBookFormats`](../../ebookformats) correspondant à l'extension de fichier spécifiée.

### Exceptions

| exception | condition |
| --- | --- |
| [EBookFormats](../../ebookformats) | Lancée lorsque l'extension de fichier spécifiée est nulle. |

### Voir aussi

* class [EBookFormats](../../ebookformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
