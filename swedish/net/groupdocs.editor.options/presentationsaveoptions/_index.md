---
title: "PresentationSaveOptions"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Tillåter att ange anpassade alternativ för att generera och spara Presentation PowerPointcompatible dokument"
type: docs
weight: 1100
url: /sv/net/groupdocs.editor.options/presentationsaveoptions/
---
## PresentationSaveOptions class

Tillåter att ange anpassade alternativ för generering och sparande av Presentation (PowerPoint-compatible)-dokument

```csharp
public sealed class PresentationSaveOptions : ISaveOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PresentationSaveOptions](presentationsaveoptions#constructor)() | Denna parameterlösa konstruktor skapar en ny instans av PresentationSaveOptions med PPTX‑utdataformat (kan sedan ändras via egenskapen [`OutputFormat`](./outputformat)) |
| [PresentationSaveOptions](presentationsaveoptions#constructor_1)(PresentationFormats) | Skapar en ny instans av PresentationSaveOptions med angivet obligatoriskt Presentation‑utdataformat, medan alla andra parametrar har standardvärden |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [InsertAsNewSlide](../../groupdocs.editor.options/presentationsaveoptions/insertasnewslide) { get; set; } | Booleskt flagga som anger om den redigerade bilden ska ersätta den befintliga bilden i originalpresentationen på den position som anges av egenskapen [`SlideNumber`](./slidenumber), eller om den ska infogas mellan den befintliga bilden och den föregående utan att ersätta dess innehåll. Standardvärdet är `false` — den befintliga bilden kommer att ersättas. Denna egenskap ignoreras om värdet för egenskapen [`SlideNumber`](./slidenumber) är satt till `'0'`. |
| [OutputFormat](../../groupdocs.editor.options/presentationsaveoptions/outputformat) { get; set; } | Tillåter att ange ett Presentation‑format som ska användas för att spara dokumentet |
| [Password](../../groupdocs.editor.options/presentationsaveoptions/password) { get; set; } | Tillåter att ange, ändra och hämta lösenordet som kommer att användas för att koda det resulterande Presentation‑dokumentet. Standardvärdet är NULL – lösenordet kommer inte att sättas. Sätt till NULL eller en tom sträng för att ta bort lösenordet om det tidigare har satts. |
| [SlideNumber](../../groupdocs.editor.options/presentationsaveoptions/slidenumber) { get; set; } | Tillåter att infoga en redigerad bild i en befintlig presentation istället för att skapa en ny enkelsidig presentation (standardbeteende). Bildnummer är ett 1‑baserat nummer för en bild i presentationen som laddats i Editor‑klassen. Om det är 0 (standardvärde) skapas den nya presentationen med en enda redigerad bild. Om det är större eller mindre än noll, och det finns en giltig presentation laddad i Editor‑klassen, kommer den redigerade bilden, lagrad i den inmatade EditableDocument‑instansen, att infogas i denna presentation. |
| [SlideNumbersToDelete](../../groupdocs.editor.options/presentationsaveoptions/slidenumberstodelete) { get; set; } | Tillåter att ange en array med 1‑baserade bildnummer som ska tas bort från presentationen vid sparande, om den redigerade bilden infogas i en befintlig presentation. |

### Anmärkningar

En instans av denna klass bör skickas till ‑metoden för att spara den redigerade presentationen i det slutgiltiga dokumentet i ett presentationsspecifikt format. Alla andra parametrar är valfria och kan utelämnas; som standard är formatet för den sparade presentationen PPTX, men det kan ändras via konstruktor eller egenskap.

### Se även

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
