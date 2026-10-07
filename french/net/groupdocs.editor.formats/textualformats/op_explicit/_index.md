---
title: "op_Explicit"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Convertit une chaîne représentant une extension de fichier en un objet TextualFormatsgroupdocs.editor.formats/textualformats."
type: docs
weight: 100
url: /fr/net/groupdocs.editor.formats/textualformats/op_explicit/
---
## TextualFormats Explicit operator

Convertit une chaîne représentant une extension de fichier en un objet [`TextualFormats`](../../textualformats).

```csharp
public static explicit operator TextualFormats(string extension)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| extension | String | L'extension de fichier à convertir. Si l'extension contient plusieurs points, la partie après le dernier point est utilisée. |

### Valeur de retour

Un objet [`TextualFormats`](../../textualformats) correspondant à l'extension de fichier spécifiée.

### Exceptions

| exception | condition |
| --- | --- |
| [TextualFormats](../../textualformats) | Lancée lorsque l'extension de fichier spécifiée est nulle. |

### Voir aussi

* class [TextualFormats](../../textualformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
