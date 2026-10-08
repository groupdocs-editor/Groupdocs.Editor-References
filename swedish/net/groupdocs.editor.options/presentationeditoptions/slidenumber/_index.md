---
title: "SlideNumber"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Tillåter att ange bildnumren som ska öppnas för redigering"
type: docs
weight: 30
url: /sv/net/groupdocs.editor.options/presentationeditoptions/slidenumber/
---
## PresentationEditOptions.SlideNumber property

Tillåter att ange bildnumren som ska öppnas för redigering.

```csharp
public int SlideNumber { get; set; }
```

### Anmärkningar

Bildnummer är ett nollbaserat index för en bild, som möjliggör att ange och välja en specifik bild från en presentation för redigering. Om värdet är mindre än 0 väljs den första bilden (samma som SlideNumber = 0). Om värdet är större än antalet bilder i presentationen väljs den sista bilden. Om den inmatade presentationen bara innehåller en enda bild ignoreras detta alternativ och den enda bilden redigeras. Om man försöker öppna en dold bild för redigering medan [`ShowHiddenSlides`](../showhiddenslides)-alternativet är satt till 'false', kastas ett undantag.

### Se även

* class [PresentationEditOptions](../../presentationeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
