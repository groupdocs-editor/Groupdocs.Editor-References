---
title: "FromStartPageTillEndPage"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Skapar ett sidintervall som startar från det angivna sidnumret inklusivt och fortsätter tills det angivna sidnumret exklusivt."
type: docs
weight: 40
url: /sv/net/groupdocs.editor.options/pagerange/fromstartpagetillendpage/
---
## PageRange.FromStartPageTillEndPage method

Skapar ett sidintervall som börjar från det angivna sidnumret (inkluderande) och fortsätter tills det angivna sidnumret (exklusivt).

```csharp
public static PageRange FromStartPageTillEndPage(ushort startPageNumber, ushort endPageNumber)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| startPageNumber | UInt16 | Sidnummer, från vilket sidintervallet startar, inklusivt. Sidnummer är 1-baserade, så de måste vara strikt större än noll. |
| endPageNumber | UInt16 | Sidnummer, tills vilket sidintervallet fortsätter, exklusivt. Sidnummer är 1-baserade, så de måste vara strikt större än noll, och också strikt större än *startPageNumber*. |

### Se även

* struct [PageRange](../../pagerange)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
