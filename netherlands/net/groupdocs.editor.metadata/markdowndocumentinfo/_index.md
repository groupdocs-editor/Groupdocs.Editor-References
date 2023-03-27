---
title: MarkdownDocumentInfo
second_title: GroupDocs.Editor voor .NET API-referentie
description: Vertegenwoordigt metadata van één Markdowndocument
type: docs
weight: 750
url: /nl/net/groupdocs.editor.metadata/markdowndocumentinfo/
---
## MarkdownDocumentInfo structure

Vertegenwoordigt metadata van één Markdown-document

```csharp
public struct MarkdownDocumentInfo : IDocumentInfo, IEquatable<MarkdownDocumentInfo>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/markdowndocumentinfo/format) { get; } | Retourneert een indeling van dit Markdown-document — altijd zo[`Md`](../../groupdocs.editor.formats/textualformats/md) |
| [IsEncrypted](../../groupdocs.editor.metadata/markdowndocumentinfo/isencrypted) { get; } | Omdat Markdown-documenten niet met een wachtwoord kunnen worden versleuteld, retourneert deze eigenschap altijd ``vals` |
| [PageCount](../../groupdocs.editor.metadata/markdowndocumentinfo/pagecount) { get; } | Retourneert het aantal pagina's. Markdown-documenten hebben meestal geen vaste pagina's en dus het aantal pagina's, dus dit aantal wordt berekend op basis van het standaard paginaformaat dat is ingesteld op A4 in staande richting. |
| [Size](../../groupdocs.editor.metadata/markdowndocumentinfo/size) { get; } | Retourneert de grootte in bytes van dit Markdown-document |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/markdowndocumentinfo/equals#equals)(MarkdownDocumentInfo) | Bepaalt of deze instantie gelijk is aan de andere opgegeven[`MarkdownDocumentInfo`](../markdowndocumentinfo) instantie. |

### Zie ook

* interface [IDocumentInfo](../idocumentinfo)
* naamruimte [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->