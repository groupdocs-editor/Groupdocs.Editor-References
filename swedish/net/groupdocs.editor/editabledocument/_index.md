---
title: "EditableDocument"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Mellanliggande dokument som innehåller innehåll före och efter redigering."
type: docs
weight: 10
url: /sv/net/groupdocs.editor/editabledocument/
---
## EditableDocument class

Intermediärt dokument som innehåller innehåll före och efter redigering

```csharp
public sealed class EditableDocument : IAuxDisposable
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [AllResources](../../groupdocs.editor/editabledocument/allresources) { get; } | Returnerar en lista över alla befintliga resurser: alla stilmallar, bilder från HTML och alla stilmallar, typsnitt, ljud. |
| [Audio](../../groupdocs.editor/editabledocument/audio) { get; } | Returnerar en lista över ljudresurser. |
| [Css](../../groupdocs.editor/editabledocument/css) { get; } | Tillåter att hämta stilmallsresurser (CSS) (både externa och inbäddade, men inte inline) som används av detta HTML-dokument. |
| [Fonts](../../groupdocs.editor/editabledocument/fonts) { get; } | Tillåter att hämta externa typsnittresurser som används av detta HTML-dokument. |
| [Images](../../groupdocs.editor/editabledocument/images) { get; } | Tillåter att hämta externa bildresurser (raster- och vektorbilder) som används av detta HTML-dokument. |
| [IsDisposed](../../groupdocs.editor/editabledocument/isdisposed) { get; } | Avgör om detta Editable-dokument redan har frigjorts (true) eller inte (false). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [FromFile](../../groupdocs.editor/editabledocument/fromfile)(string, string) | Statisk fabrik som skapar en instans av EditableDocument från en HTML-fil, som specificeras av en sökväg till själva *.html-filen och en mapp med länkade resurser. |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup#frommarkup)(string) | Statisk fabrik som skapar en instans av [`EditableDocument`](../editabledocument) från specificerad HTML-markup. |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup#frommarkup_1)(string, IEnumerable&lt;IHtmlResource&gt;) | Statisk fabrik som skapar en instans av EditableDocument från specificerad HTML-markup och en uppsättning motsvarande länkade resurser. |
| static [FromMarkupAndResourceFolder](../../groupdocs.editor/editabledocument/frommarkupandresourcefolder)(string, string) | Statisk fabrik som skapar en instans av EditableDocument från en specificerad HTML-markup och från resurser som finns i mappen som specificeras av den fullständiga sökvägen. |
| [Dispose](../../groupdocs.editor/editabledocument/dispose)() | Frigör denna Editable-dokumentinstans, frigör dess innehåll och gör dess metoder och egenskaper oanvändbara. |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent)() | Returnerar en kropp av HTML-dokumentet (innehållet mellan öppnings- och stängningstaggarna BODY utan dessa taggar) som en sträng. |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent_1)(string) | Returnerar en kropp av HTML-dokumentet (innehållet mellan öppnings- och stängningstaggarna BODY utan dessa taggar) som en sträng, där länkar till externa resurser innehåller angiven mall med platshållare. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent)() | Returnerar det totala innehållet i HTML-dokumentet som en sträng. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent_1)(string, string) | Returnerar det totala innehållet i HTML-dokumentet som en sträng, där länkar till externa resurser innehåller angiven mall med platshållare. |
| [GetContent&lt;TStream&gt;](../../groupdocs.editor/editabledocument/getcontent#getcontent_2)(TStream, Encoding) | Returnerar det totala innehållet i HTML-dokumentet som en byte‑ström genom att skriva detta innehåll till den angivna strömmen med angiven textkodning. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent)() | Returnerar innehållet i alla externa stilmallar som en lista med strängar, där en sträng representerar en stilmall. Returnerar en tom lista om det inte finns någon CSS för detta dokument. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent_1)(string, string) | Returnerar innehållet i alla externa stilmallar som en lista med strängar, där en sträng representerar en stilmall. Angivet prefix kommer att tillämpas på varje länk till den externa resursen i varje resulterande stilmall. Returnerar en tom lista om det inte finns någon CSS för detta dokument. |
| [GetEmbeddedHtml](../../groupdocs.editor/editabledocument/getembeddedhtml)() | Returnerar allt innehåll i detta HTML‑dokument med alla relaterade resurser i form av en enda sträng, där alla resurser är inbäddade i HTML markup i base64‑kodad form. |
| [Save](../../groupdocs.editor/editabledocument/save#save_1)(string) | Sparar detta HTML‑dokument till filen på den angivna sökvägen, där HTML‑markup kommer att lagras, och till den medföljande mappen med resurser. |
| [Save](../../groupdocs.editor/editabledocument/save#save_2)(string, string) | Sparar detta HTML‑dokument till filen på den angivna sökvägen, där HTML‑markup kommer att lagras, och till den medföljande mappen med resurser, som ligger på den angivna sökvägen. |
| [Save](../../groupdocs.editor/editabledocument/save#save)(TextWriter, HtmlSaveOptions) | Sparar innehållet i detta [`EditableDocument`](../editabledocument) som HTML‑dokument till den angivna text‑skrivaren, medan den andra options‑parametern möjliggör att anpassa sparproceduren och specificera resurssparnings‑callback. |

## Händelser

| Namn | Beskrivning |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editabledocument/disposed) | Händelse som inträffar när detta Editable document har disponeras, direkt efter att disponeringsprocessen är slutförd. |

### Anmärkningar

En instans av `EditableDocument`‑klassen kan skapas av metoden '[`Edit`](../editor/edit)' eller skapas av användaren själv med hjälp av statiska fabriker. `EditableDocument` lagrar internt dokumentet i sitt eget slutna format, som är kompatibelt (konverterbart) med alla import‑ och exportformat som GroupDocs.Editor stödjer. För att göra dokumentet redigerbart i någon WYSIWYG‑klientside‑redigerare (som CKEditor eller TinyMCE) tillhandahåller `EditableDocument` metoder för att generera HTML‑markup och producera resurser som kan accepteras av användaren.

### Se även

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* namespace [GroupDocs.Editor](../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
