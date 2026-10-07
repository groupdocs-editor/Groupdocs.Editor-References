---
title: "op_Explicit"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Convertit une chaîne représentant une extension de fichier en un objet PresentationFormatsgroupdocs.editor.formats/presentationformats."
type: docs
weight: 150
url: /fr/net/groupdocs.editor.formats/presentationformats/op_explicit/
---
## PresentationFormats Explicit operator

Convertit une chaîne représentant une extension de fichier en un objet [`PresentationFormats`](../../presentationformats).

```csharp
public static explicit operator PresentationFormats(string extension)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| extension | String | L'extension de fichier à convertir. Si l'extension contient plusieurs points, la partie après le dernier point est utilisée. |

### Valeur de retour

Un objet [`PresentationFormats`](../../presentationformats) correspondant à l'extension de fichier spécifiée.

### Exceptions

| exception | condition |
| --- | --- |
| [PresentationFormats](../../presentationformats) | Lancée lorsque l'extension de fichier spécifiée est nulle. |

### Voir aussi

* class [PresentationFormats](../../presentationformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
