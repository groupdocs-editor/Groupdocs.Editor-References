---
title: "TextualDocumentInfo"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Représente les métadonnées d'un document textuel comme XML HTML ou texte brut TXT"
type: docs
weight: 780
url: /fr/net/groupdocs.editor.metadata/textualdocumentinfo/
---
## TextualDocumentInfo structure

Représente les métadonnées d'un document textuel comme XML, HTML ou texte brut (TXT)

```csharp
public struct TextualDocumentInfo : IDocumentInfo
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Encoding](../../groupdocs.editor.metadata/textualdocumentinfo/encoding) { get; } | Renvoie l'encodage détecté présumé du document texte |
| [Format](../../groupdocs.editor.metadata/textualdocumentinfo/format) { get; } | Renvoie un format de ce document textuel. Peut ne pas être correct à 100 % dans certains cas. |
| [IsEncrypted](../../groupdocs.editor.metadata/textualdocumentinfo/isencrypted) { get; } | Renvoie toujours ``false``, car les documents textuels ne peuvent pas être chiffrés |
| [PageCount](../../groupdocs.editor.metadata/textualdocumentinfo/pagecount) { get; } | Renvoie toujours 1 |
| [Size](../../groupdocs.editor.metadata/textualdocumentinfo/size) { get; } | Renvoie la taille en octets (et non le nombre de caractères) de ce document textuel |

### Voir aussi

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
