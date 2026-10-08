---
title: "EbookDocumentInfo"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Representerar metadata för ett eBook-dokument"
type: docs
weight: 710
url: /sv/net/groupdocs.editor.metadata/ebookdocumentinfo/
---
## EbookDocumentInfo structure

Representerar metadata för ett e-bokdokument

```csharp
public struct EbookDocumentInfo : IDocumentInfo, IEquatable<EbookDocumentInfo>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/ebookdocumentinfo/format) { get; } | Returnerar ett format för denna e-Book |
| [IsEncrypted](../../groupdocs.editor.metadata/ebookdocumentinfo/isencrypted) { get; } | Eftersom e-Book-dokument inte kan krypteras med lösenord, returnerar denna egenskap alltid 'false' |
| [PageCount](../../groupdocs.editor.metadata/ebookdocumentinfo/pagecount) { get; } | Returnerar antal sidor i fallet MOBI eller AZW3 eller antal kapitel i fallet ePub. |
| [Size](../../groupdocs.editor.metadata/ebookdocumentinfo/size) { get; } | Returnerar storlek i byte för detta eBook-dokument |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/ebookdocumentinfo/equals#equals)(EbookDocumentInfo) | Bestämmer om detta objekt är lika med den andra angivna EbookDocumentInfo-instansen |

### Se även

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
