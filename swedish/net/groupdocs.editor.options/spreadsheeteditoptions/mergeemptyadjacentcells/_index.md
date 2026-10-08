---
title: "MergeEmptyAdjacentCells"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "När den är aktiverad kommer de tomma intilliggande horisontella cellerna från inmatnings‑Spreadsheet‑dokumentet att representeras i det redigerbara HTML‑dokumentet som sammanslagna till en enda cell med motsvarande colspan‑attribut. Som standard är den inaktiverad (false)."
type: docs
weight: 40
url: /sv/net/groupdocs.editor.options/spreadsheeteditoptions/mergeemptyadjacentcells/
---
## SpreadsheetEditOptions.MergeEmptyAdjacentCells property

När den är aktiverad kommer de tomma intilliggande horisontella cellerna från inmatnings‑Spreadsheet‑dokumentet att representeras i det redigerbara HTML‑dokumentet som sammanslagna till en enda cell med motsvarande `colspan`‑attribut. Som standard är den inaktiverad (`false`).

```csharp
public bool MergeEmptyAdjacentCells { get; set; }
```

### Anmärkningar

Som standard konverterar GroupDocs.Editor en tabell från inmatnings‑Spreadsheet‑dokumentet till utdata‑HTML‑dokumentet genom att bevara varje cell. Dock kan Spreadsheet‑dokument vara glesa — de kan innehålla stora mängder \"tomma områden\", där många celler är tomma. Detta alternativ, när det är aktiverat, sammanslår sådana tomma celler till en med `colspan`‑attribut i `TD`‑elementet, och kan därmed avsevärt minska storleken på den genererade HTML‑markupen.

### Se även

* class [SpreadsheetEditOptions](../../spreadsheeteditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
