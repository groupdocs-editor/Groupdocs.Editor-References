---
title: "WordProcessingEditOptions"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Tillåter att ange anpassade alternativ för redigering av dokument i alla stödjade WordProcessing Wordscompliant-format som DOCX, RTF, ODT etc."
type: docs
weight: 1200
url: /sv/net/groupdocs.editor.options/wordprocessingeditoptions/
---
## WordProcessingEditOptions class

Tillåter att ange anpassade alternativ för redigering av dokument i alla stödjade WordProcessing (Words-compliant)-format, såsom DOC(X), RTF, ODT etc.

```csharp
public class WordProcessingEditOptions : IEditOptions
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [WordProcessingEditOptions](wordprocessingeditoptions#constructor)() | Skapar och returnerar en ny instans av WordProcessingEditOptions‑klassen, där alla alternativ är satta till sina standardvärden |
| [WordProcessingEditOptions](wordprocessingeditoptions#constructor_1)(bool) | Skapar och returnerar en ny instans av klassen WordProcessingEditOptions med angiven paginering och standardvärden för alla andra alternativ |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [EnableLanguageInformation](../../groupdocs.editor.options/wordprocessingeditoptions/enablelanguageinformation) { get; set; } | Anger om språkinformation exporteras till HTML-markupen i form av 'lang'-HTML-attribut. Detta alternativ kan vara användbart för rundresa‑konvertering av flerspråkiga dokument. Som standard är det inaktiverat (false). |
| [EnablePagination](../../groupdocs.editor.options/wordprocessingeditoptions/enablepagination) { get; set; } | Tillåter att aktivera eller inaktivera paginering i det resulterande HTML-dokumentet. Standard är inaktiverad (false). |
| [ExtractOnlyUsedFont](../../groupdocs.editor.options/wordprocessingeditoptions/extractonlyusedfont) { get; set; } | Hämtar eller anger ett värde som indikerar om endast teckensnittresurser som används i dokumentets textinnehåll ska extraheras. |
| [FontExtraction](../../groupdocs.editor.options/wordprocessingeditoptions/fontextraction) { get; set; } | Ansvarig för att extrahera teckensnittresurser som används i det inmatade WordProcessing-dokumentet. Som standard extraheras inga teckensnitt (NotExtract). |
| [InputControlsClassName](../../groupdocs.editor.options/wordprocessingeditoptions/inputcontrolsclassname) { get; set; } | Tillåter att ange ett klassnamn som kommer att placeras i 'class'-attributen i varje HTML‑element som representerar ett fält i det inmatade WordProcessing-dokumentet. Som standard är NULL – 'class'-attributen tillämpas inte. |
| [UseInlineStyles](../../groupdocs.editor.options/wordprocessingeditoptions/useinlinestyles) { get; set; } | Styr var stil‑ och formateringsdata för det inmatade WordProcessing-dokumentet lagras: i extern stilmall (`false`) eller som inbäddade stilar i HTML-markupen (`true`). Som standard används externa stilar (`false`). |

### Se även

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
