---
title: EditableDocument
second_title: GroupDocs.Editor för .NET API-referens
description: Mellanliggande dokument som innehåller innehåll före och efter redigering
type: docs
weight: 10
url: /sv/net/groupdocs.editor/editabledocument/
---
## EditableDocument class

Mellanliggande dokument, som innehåller innehåll före och efter redigering

```csharp
public sealed class EditableDocument : IAuxDisposable
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AllResources](../../groupdocs.editor/editabledocument/allresources) { get; } | Returnerar en lista över alla befintliga resurser: alla stilmallar, bilder från HTML och alla stilmallar, typsnitt, audio |
| [Audio](../../groupdocs.editor/editabledocument/audio) { get; } | Returnerar en lista över ljudresurser |
| [Css](../../groupdocs.editor/editabledocument/css) { get; } | Returnerar en lista över CSS-resurser |
| [Fonts](../../groupdocs.editor/editabledocument/fonts) { get; } | Tillåter att få externa teckensnittsresurser som används av detta HTML-dokument |
| [Images](../../groupdocs.editor/editabledocument/images) { get; } | Gör det möjligt att erhålla externa bildresurser (raster- och vektorbilder), som används av detta HTML-dokument |
| [IsDisposed](../../groupdocs.editor/editabledocument/isdisposed) { get; } | Bestämmer om detta redigerbara dokument redan var bortskaffat (true) eller inte (false) |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [FromFile](../../groupdocs.editor/editabledocument/fromfile)(string, string) | Static factory, som skapar en instans av EditableDocument från en HTML-fil, som anges av en sökväg till själva *.html-filen och en mapp med länkade resurser |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup)(string, IEnumerable&lt;IHtmlResource&gt;) | Statisk fabrik, som skapar en instans av EditableDocument från specificerad HTML-kod och en uppsättning motsvarande länkade resurser |
| static [FromMarkupAndResourceFolder](../../groupdocs.editor/editabledocument/frommarkupandresourcefolder)(string, string) | Statisk fabrik, som skapar en instans av EditableDocument från en specificerad HTML-uppmärkning och från resurser, som finns i mappen, specificerad av hela path |
| [Dispose](../../groupdocs.editor/editabledocument/dispose)() | Kastar den här redigerbara dokumentinstansen, kasserar dess innehåll och gör att dess metoder och egenskaper inte fungerar |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent)() | Returnerar en brödtext i HTML-dokumentet (inre innehåll mellan öppnande och avslutande BODY-taggar utan dessa taggar) som en sträng. |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent_1)(string) | Returnerar en brödtext i HTML-dokumentet (inre innehåll mellan öppnande och avslutande BODY-taggar utan dessa taggar) som en sträng, där länkar till de externa resurserna innehåller specificerat prefix. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent)() | Returnerar det övergripande innehållet i HTML-dokumentet som en sträng. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent_1)(string, string) | Returnerar det övergripande innehållet i HTML-dokumentet som en sträng, där länkar till de externa resurserna innehåller specificerat prefix. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent)() | Returnerar innehållet i alla externa formatmallar som en lista med strängar, där en sträng representerar en formatmall. Returnerar tom lista, om det inte finns någon CSS för detta dokument. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent_1)(string, string) | Returnerar innehållet i alla externa formatmallar som en lista med strängar, där en sträng representerar en formatmall. Specificerat prefix kommer att tillämpas på varje länk till den externa resursen i varje resulterande formatmall. Returnerar tom lista, om det inte finns någon CSS för detta document. |
| [GetEmbeddedHtml](../../groupdocs.editor/editabledocument/getembeddedhtml)() | Returnerar allt innehåll i detta HTML-dokument med alla relaterade resurser i form av en enda sträng, där alla resurser är inbäddade i HTML-uppmärkningen i en base64-kodad form. |
| [Save](../../groupdocs.editor/editabledocument/save#save)(string) | Sparar detta HTML-dokument till filen på angiven sökväg, där HTML-uppmärkning kommer att lagras, och i den medföljande mappen med resurser. |
| [Save](../../groupdocs.editor/editabledocument/save#save_1)(string, string) | Sparar detta HTML-dokument till filen på angiven sökväg, där HTML-uppmärkning kommer att lagras, och i den medföljande mappen med resurser, som finns på angiven sökväg. |

## evenemang

| namn | Beskrivning |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editabledocument/disposed) | Händelse, som inträffar när det här redigerbara dokumentet kasseras, direkt efter att kasseringsprocessen har avslutats |

### Anmärkningar

Förekomst av klassen EditableDocument kan produceras av '[`Edit`](../editor/edit) metod eller skapad av användaren själv med hjälp av statiska fabriker. EditableDocument lagrar dokument internt i sitt eget stängda format, vilket är kompatibelt (konverterbart) med alla import- och exportformat, som GroupDocs.Editor stöder. För att göra dokument redigerbart i alla WYSIWYG-redigerare på klientsidan (som CKEditor eller TinyMCE), tillhandahåller EditableDocument metoder för att generera HTML-uppmärkning och producera resurser, som kan accepteras av användaren.

### Se även

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* namnutrymme [GroupDocs.Editor](../../groupdocs.editor)
* hopsättning [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
