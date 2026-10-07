---
title: "FromMime"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Récupère une instance du type T spécifié qui possède le type MIME spécifié."
type: docs
weight: 60
url: /fr/net/groupdocs.editor.formats.abstraction/documentformatbase/frommime/
---
## DocumentFormatBase.FromMime&lt;T&gt; method

Récupère une instance du type spécifié *T* qui possède le type MIME spécifié.

```csharp
public static T FromMime<T>(string mime)
    where T : DocumentFormatBase
```

| Paramètre | Description |
| --- | --- |
| T | Le type de format de document. |
| mime | Le type MIME du format de document. |

### Valeur de retour

Une instance du type *T* spécifié avec le type MIME spécifié.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Lancée lorsqu'aucun format de document correspondant n'est trouvé. |

### Voir aussi

* class [DocumentFormatBase](../../documentformatbase)
* namespace [GroupDocs.Editor.Formats.Abstraction](../../../groupdocs.editor.formats.abstraction)
* assembly [GroupDocs.Editor](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
