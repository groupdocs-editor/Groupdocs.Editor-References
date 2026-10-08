---
title: "XmlFormatOptions"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Innehåller alternativ som möjliggör justering av formateringen av XML-dokument när det representeras som HTML."
type: docs
weight: 1280
url: /sv/net/groupdocs.editor.options/xmlformatoptions/
---
## XmlFormatOptions class

Innehåller alternativ som möjliggör att justera formateringen av XML-dokumentet när det visas som HTML

```csharp
public sealed class XmlFormatOptions : IEditOptions
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [EachAttributeFromNewline](../../groupdocs.editor.options/xmlformatoptions/eachattributefromnewline) { get; set; } | När den är aktiverad placeras varje attribut‑värde‑par i varje XML‑element på en ny rad. Som standard är den falsk (inaktiverad) – alla attribut‑värde‑par placeras på en enda rad. |
| [IsDefault](../../groupdocs.editor.options/xmlformatoptions/isdefault) { get; } | Indikerar om denna instans av XML‑formateringsalternativ har ett standardvärde. |
| [LeafTextNodesOnNewline](../../groupdocs.editor.options/xmlformatoptions/leaftextnodesonnewline) { get; set; } | När den är aktiverad kommer lövtextnoder (textinnehåll inuti XML-element som inte har några barn) att renderas på en ny rad med större vänsterindrag. Som standard är false (inaktiverad) — lövtextnoder placeras på samma rad som sina föräldrar, utan nytt indrag. |
| [LeftIndent](../../groupdocs.editor.options/xmlformatoptions/leftindent) { get; set; } | Tillåter att ange ett avstånd för vänsterindraget på varje ny rad. Kan inte vara ett enhetslöst icke‑nollvärde. Som standard är 10pt. |

### Se även

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
