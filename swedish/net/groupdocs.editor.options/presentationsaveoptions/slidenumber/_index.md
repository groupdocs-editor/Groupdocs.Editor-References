---
title: "SlideNumber"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Tillåter att infoga en redigerad bild i en befintlig presentation istället för att skapa en ny enkelsidig presentation som standardbeteende. Bildnummer är ett 1-baserat nummer på en bild i presentationen som laddats i Editor-klassen. Om det är 0 (standardvärde) kommer den nya presentationen att skapas med en enda redigerad bild. Om det är större eller mindre än noll och det finns en giltig presentation laddad i Editor-klassen kommer den redigerade bilden som lagras i den inmatade EditableDocument-instansen att infogas i denna presentation."
type: docs
weight: 50
url: /sv/net/groupdocs.editor.options/presentationsaveoptions/slidenumber/
---
## PresentationSaveOptions.SlideNumber property

Tillåter att infoga en redigerad bild i en befintlig presentation istället för att skapa en ny enkelsidig presentation (standardbeteende). Bildnummer är ett 1‑baserat nummer för en bild i presentationen som laddats i Editor‑klassen. Om det är 0 (standardvärde) skapas den nya presentationen med en enda redigerad bild. Om det är större eller mindre än noll, och det finns en giltig presentation laddad i Editor‑klassen, kommer den redigerade bilden, lagrad i den inmatade EditableDocument‑instansen, att infogas i denna presentation.

```csharp
public int SlideNumber { get; set; }
```

### Anmärkningar

SlideNumber heltalsegenskap, om den inte är i standardtillstånd (reserverat värde '0'), representerar ett bildnummer, så den börjar från 1, inte från noll, och dess maximala värde är antalet befintliga bilder i en presentation. Om det angivna värdet är större än antalet bilder kommer GroupDocs.Editor att justera det till den sista bilden. Negativa värden är också tillåtna och räknar bilder från slutet. Till exempel innebär \"-1\" den sista bilden i en presentation, \"-2\" — den näst sista, osv. På samma sätt som med positiva värden, när ett negativt bildnummer överstiger det totala antalet bilder i den givna presentationen, kommer det att justeras till den första bilden. Den [`InsertAsNewSlide`](../insertasnewslide) booleska egenskapen är tätt kopplad till denna.

### Exempel

Given presentation has 5 slides: SlideNumber = 0; — ignore given presentation, create a new presentation and put edited slide into it. SlideNumber = 1; — replace the first slide with edited SlideNumber = 2; — replace the second slide with edited SlideNumber = 5; — replace the last (5th) slide with edited SlideNumber = 6; — replace the last (5th) slide with edited, because 6 is greater then 5 and thus is adjusted SlideNumber = -1; — replace the last (5th) slide with edited, because "-1" means "last existing" SlideNumber = -2; — replace the 4th slide with edited SlideNumber = -3; — replace the 3rd slide with edited SlideNumber = -4; — replace the 2nd slide with edited SlideNumber = -5; — replace the first slide with edited SlideNumber = -6; — replace the first slide with edited, because "-6" is greater then 5 and thus is adjusted

### Se även

* class [PresentationSaveOptions](../../presentationsaveoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
