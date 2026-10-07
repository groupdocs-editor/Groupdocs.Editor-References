---
title: "op_Explicit"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Convertit une chaîne représentant une extension de fichier en un objet SpreadsheetFormatsgroupdocs.editor.formats/spreadsheetformats."
type: docs
weight: 180
url: /fr/net/groupdocs.editor.formats/spreadsheetformats/op_explicit/
---
## SpreadsheetFormats Explicit operator

Convertit une chaîne représentant une extension de fichier en un objet [`SpreadsheetFormats`](../../spreadsheetformats).

```csharp
public static explicit operator SpreadsheetFormats(string extension)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| extension | String | L'extension de fichier à convertir. Si l'extension contient plusieurs points, la partie après le dernier point est utilisée. |

### Valeur de retour

Un objet [`SpreadsheetFormats`](../../spreadsheetformats) correspondant à l'extension de fichier spécifiée.

### Exceptions

| exception | condition |
| --- | --- |
| [SpreadsheetFormats](../../spreadsheetformats) | Lancée lorsque l'extension de fichier spécifiée est nulle. |

### Voir aussi

* class [SpreadsheetFormats](../../spreadsheetformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
