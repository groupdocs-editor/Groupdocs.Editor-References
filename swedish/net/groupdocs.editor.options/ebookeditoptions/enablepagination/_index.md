---
title: "EnablePagination"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Tillåter att aktivera eller inaktivera paginering i det resulterande HTML‑dokumentet. Standard är false (inaktiverad)."
type: docs
weight: 30
url: /sv/net/groupdocs.editor.options/ebookeditoptions/enablepagination/
---
## EbookEditOptions.EnablePagination property

Tillåter att aktivera eller inaktivera paginering i det resulterande HTML‑dokumentet. Som standard är det inaktiverat (`false`).

```csharp
public bool EnablePagination { get; set; }
```

### Anmärkningar

I sin essens är de flesta e-bokformat internt ett flödesformat som Office Open XML, där innehållet är en helhet och delas upp i kapitel men inte i sidor. Däremot innehåller det viss sid‑specifik information som sidnummer, fotnoter, sidhuvuden/sidfötter med mera. Vissa e-boksläsare delar upp e-boksinnehållet i sidor, medan andra (särskilt mobila) – inte gör det. Detta alternativ låter dig kontrollera hur e-boksinnehållet ska representeras i HTML/CSS under redigering – i flytläge (`false`) eller paginerat läge (`true`).

### Se även

* class [EbookEditOptions](../../ebookeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
