---
title: "SplitHeadingLevel"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Anger den maximala rubriknivån vid vilken e‑bokfilen ska delas. Standardvärdet är 2. Att sätta den till 0 inaktiverar delning så allt innehåll i e‑boken integreras i ett enda paket i den resulterande filen."
type: docs
weight: 40
url: /sv/net/groupdocs.editor.options/ebooksaveoptions/splitheadinglevel/
---
## EbookSaveOptions.SplitHeadingLevel property

Anger den maximala rubriknivån vid vilken e‑bokfilen ska delas upp. Standardvärdet är `2`. Att sätta den till `0` inaktiverar uppdelning, så allt innehåll i e‑boken kommer att integreras i ett enda paket i den resulterande filen.

```csharp
public int SplitHeadingLevel { get; set; }
```

### Anmärkningar

När denna egenskap sätts till ett värde mellan 1 och 9 kommer dokumentet att delas vid stycken formaterade med **Heading 1**, **Heading 2**, **Heading 3** osv. stilar upp till den angivna rubriknivån.

Som standard orsakar endast **Heading 1**- och **Heading 2**-stycken att dokumentet delas. Att sätta denna egenskap till noll (eller mindre än noll) gör att dokumentet inte delas vid rubrikstycken alls.

### Se även

* class [EbookSaveOptions](../../ebooksaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
