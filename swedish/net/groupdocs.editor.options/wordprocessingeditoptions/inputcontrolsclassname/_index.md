---
title: "InputControlsClassName"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Tillåter att ange ett klassnamn som kommer att placeras i klassattributen i varje HTML-element som representerar ett fält i det inkommande WordProcessing-dokumentet. Som standard är NULL, klassattribut tillämpas inte."
type: docs
weight: 60
url: /sv/net/groupdocs.editor.options/wordprocessingeditoptions/inputcontrolsclassname/
---
## WordProcessingEditOptions.InputControlsClassName property

Tillåter att ange ett klassnamn som kommer att placeras i 'class'-attributen i varje HTML‑element som representerar ett fält i det inmatade WordProcessing-dokumentet. Som standard är NULL – 'class'-attributen tillämpas inte.

```csharp
public string InputControlsClassName { get; set; }
```

### Anmärkningar

Nästan alla format från WordProcessing-formatfamiljen innehåller fält — specifika dokumentenheter som möjliggör att hämta indata från användare. Det finns ett brett utbud av fält: textrutor, kryssrutor, kombinationsrutor, rullgardinslistor, knappar, datum-/tidväljare osv. Alla dessa översätts till de mest lämpliga HTML‑strukturerna och -elementen, med bevarande av den angivna användardatan om den finns i indokumentet. I specifika användningsfall krävs det bara att samla in den angivna datan på klientsidan istället för att redigera hela dokumentinnehållet. För ett sådant fall måste inmatningskontroller identifieras på något sätt för att kunna hämta dem med deras data på klientsidan. Denna egenskap gör det möjligt att ange ett klassnamn som kommer att tillämpas på varje inmatningskontroll i HTML‑markup, så att klientkoden kan traversera HTML‑dokumentstrukturen och samla data.

### Se även

* class [WordProcessingEditOptions](../../wordprocessingeditoptions)
* namespace [GroupDocs.Editor.Options](../../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
