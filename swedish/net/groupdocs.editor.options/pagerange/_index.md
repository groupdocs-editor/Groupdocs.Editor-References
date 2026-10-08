---
title: "PageRange"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Inkapslar ett sidintervall som kan ha öppna eller slutna gränser. Som standard är det helt öppet och inkluderar alla befintliga sidor. Sidnumrering börjar från 1 och inte från 0."
type: docs
weight: 1030
url: /sv/net/groupdocs.editor.options/pagerange/
---
## PageRange structure

Inkapslar ett sidintervall som kan ha öppna eller slutna gränser. Som standard är det "fullt öppet" – det inkluderar alla befintliga sidor. Sidnumrering börjar på 1, inte på 0.

```csharp
public struct PageRange : IEquatable<PageRange>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Count](../../groupdocs.editor.options/pagerange/count) { get; } | Antalet sidor inom intervallet. Om 0 – sidintervallet sträcker sig till dokumentets slut oavsett hur många sidor det består av. |
| [EndNumber](../../groupdocs.editor.options/pagerange/endnumber) { get; } | Exklusivt slutsidnummer, tills vilket detta sidintervall fortsätter och på vilket det avslutas exklusivt. Om 0 – sidintervallet sträcker sig till dokumentets slut. |
| [IsDefault](../../groupdocs.editor.options/pagerange/isdefault) { get; } | Anger om detta objekt representerar ett standard‑\"fullt öppet\" sidintervall, dvs. om det representerar alla sidor i ett dokument (true) eller inte (false). |
| [StartNumber](../../groupdocs.editor.options/pagerange/startnumber) { get; } | Inkluderande startsidnummer, från vilket detta sidintervall börjar. Om 1 – sidintervallet börjar från den första sidan i ett dokument. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [FromBeginningWithCount](../../groupdocs.editor.options/pagerange/frombeginningwithcount)(ushort) | Skapar ett sidintervall som börjar från den första sidan och har ett angivet antal sidor. |
| static [FromStartPageTillEnd](../../groupdocs.editor.options/pagerange/fromstartpagetillend)(ushort) | Skapar ett sidintervall som börjar från det angivna sidnumret och fortsätter till dokumentets slut. |
| static [FromStartPageTillEndPage](../../groupdocs.editor.options/pagerange/fromstartpagetillendpage)(ushort, ushort) | Skapar ett sidintervall som börjar från det angivna sidnumret (inkluderande) och fortsätter tills det angivna sidnumret (exklusivt). |
| static [FromStartPageWithCount](../../groupdocs.editor.options/pagerange/fromstartpagewithcount)(ushort, ushort) | Skapar ett sidintervall som börjar från det angivna sidnumret och har ett angivet antal sidor, eller obegränsat sidantal (till slutet). |
| [Equals](../../groupdocs.editor.options/pagerange/equals#equals)(PageRange) | Detekterar om detta PageRange‑objekt är lika med det angivna. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| static readonly [AllPages](../../groupdocs.editor.options/pagerange/allpages) | Representerar alla befintliga sidor i ett dokument. Standardvärde. |

### Anmärkningar

Oföränderlig struct som inkapslar ett sidintervall, vilket inte är knutet till något specifikt dokument och kan representera ett sidintervall för vilket dokument som helst.

### Se även

* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
