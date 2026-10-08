---
title: "EmailDocumentInfo"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Representerar metadata för ett e-postdokument i vilket som helst stödd e-postformat"
type: docs
weight: 720
url: /sv/net/groupdocs.editor.metadata/emaildocumentinfo/
---
## EmailDocumentInfo structure

Representerar metadata för ett e-postdokument i vilket som helst stödd e-postformat

```csharp
public struct EmailDocumentInfo : IDocumentInfo, IEquatable<EmailDocumentInfo>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Format](../../groupdocs.editor.metadata/emaildocumentinfo/format) { get; } | Returnerar ett format för detta e‑postdokument |
| [IsEncrypted](../../groupdocs.editor.metadata/emaildocumentinfo/isencrypted) { get; } | Eftersom e‑postdokument inte kan krypteras med lösenord, returnerar denna egenskap alltid 'false' |
| [PageCount](../../groupdocs.editor.metadata/emaildocumentinfo/pagecount) { get; } | Returnerar alltid 1, eftersom e‑postdokument inte har paginerad vy |
| [Size](../../groupdocs.editor.metadata/emaildocumentinfo/size) { get; } | Returnerar storlek i byte för detta e‑postdokument |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Equals](../../groupdocs.editor.metadata/emaildocumentinfo/equals#equals)(EmailDocumentInfo) | Bestämmer om detta objekt är lika med den andra angivna EmailDocumentInfo-instansen |

### Se även

* interface [IDocumentInfo](../idocumentinfo)
* namespace [GroupDocs.Editor.Metadata](../../groupdocs.editor.metadata)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
