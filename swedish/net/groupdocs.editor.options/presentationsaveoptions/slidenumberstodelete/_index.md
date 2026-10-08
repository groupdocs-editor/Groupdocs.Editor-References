---
title: "SlideNumbersToDelete"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Tillåter att ange en array med 1‑baserade bildnummer som ska tas bort från presentationen vid sparning om den redigerade bilden infogas i en befintlig presentation"
type: docs
weight: 60
url: /sv/net/groupdocs.editor.options/presentationsaveoptions/slidenumberstodelete/
---
## PresentationSaveOptions.SlideNumbersToDelete property

Tillåter att ange en array med 1‑baserade bildnummer som ska tas bort från presentationen vid sparande, om den redigerade bilden infogas i en befintlig presentation.

```csharp
public int[] SlideNumbersToDelete { get; set; }
```

### Anmärkningar

När den redigerade bilden sparas inte som en ny en‑bild‑presentation (standardbeteende), utan istället sparas i en befintlig presentation (med hjälp av egenskapen [`SlideNumber`](../slidenumber)), är det också möjligt att ta bort vissa specifika bilder från denna presentation genom att ange deras nummer i denna array.

Som standard är denna array `null` — inga bilder kommer att tas bort. Men när arrayen är icke‑null och inte tom, och den innehåller minst ett giltigt bildnummer, kommer efter att utdata‑Presentation‑dokumentet har genererats med innehållet från den redigerade bilden, bilderna med angivna nummer att tas bort från presentationen precis innan dess innehåll skrivs till utströmmen eller filen.

Bildnummer i denna array är 1‑baserade, inte 0‑baserade; ogiltiga nummer (mindre än 1 eller större än det totala antalet bilder) kommer att ignoreras.

### Se även

* class [PresentationSaveOptions](../../presentationsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
