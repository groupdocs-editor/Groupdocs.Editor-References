---
title: "EmailDocumentInfo"
second_title: "Référence API GroupDocs.Editor pour .NET"
description: "Représente les métadonnées d'un document e‑mail de tout format e‑mail pris en charge"
type: docs
weight: 720
url: /fr/net/groupdocs.editor.metadata/emaildocumentinfo/
---
## EmailDocumentInfo structure

Représente les métadonnées d'un document e‑mail de tout format e‑mail pris en charge

```csharp
public struct EmailDocumentInfo : IDocumentInfo, IEquatable<EmailDocumentInfo>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/emaildocumentinfo/format) { get; } | Renvoie le format de ce document email |
| [IsEncrypted](../../groupdocs.editor.metadata/emaildocumentinfo/isencrypted) { get; } | Comme les documents email ne peuvent pas être chiffrés avec un mot de passe, cette propriété renvoie toujours 'false' |
| [PageCount](../../groupdocs.editor.metadata/emaildocumentinfo/pagecount) { get; } | Renvoie toujours 1, car les documents email n'ont pas de vue paginée |
| [Size](../../groupdocs.editor.metadata/emaildocumentinfo/size) { get; } | Renvoie la taille en octets de ce document email |

## Méthodes

| Nom | Description |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/emaildocumentinfo/equals#equals)(EmailDocumentInfo) | Détermine si cette instance est égale à l'autre instance spécifiée de EmailDocumentInfo |

### Voir aussi

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.editor.dll -->
