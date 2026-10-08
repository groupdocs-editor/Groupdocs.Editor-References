---
title: "FromStartPageWithCount"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Skapar ett sidintervall som startar från det angivna sidnumret och har ett specificerat antal sidor eller obegränsat sidantal till slutet."
type: docs
weight: 50
url: /sv/net/groupdocs.editor.options/pagerange/fromstartpagewithcount/
---
## PageRange.FromStartPageWithCount method

Skapar ett sidintervall som börjar från det angivna sidnumret och har ett angivet antal sidor, eller obegränsat sidantal (till slutet).

```csharp
public static PageRange FromStartPageWithCount(ushort startPageNumber, ushort pageCount)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| startPageNumber | UInt16 | Sidnummer, från vilket sidintervallet startar, inklusivt. Sidnummer är 1-baserade, så de måste vara strikt större än noll. |
| pageCount | UInt16 | Antal sidor, måste vara strikt större än noll. Om noll – betyder det alla sidor till slutet av ett dokument. |

### Returvärde

Ny PageRange-instans

### Se även

* struct [PageRange](../../pagerange)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
