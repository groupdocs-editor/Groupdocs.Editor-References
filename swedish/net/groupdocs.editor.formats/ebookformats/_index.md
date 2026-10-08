---
title: "EBookFormats"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Innesluter alla eBook-format. Inkluderar följande filtyper Mobi./ebookformats/mobi Epub./ebookformats/epub Azw3./ebookformats/azw3."
type: docs
weight: 80
url: /sv/net/groupdocs.editor.formats/ebookformats/
---
## EBookFormats class

Innesluter alla eBook-format. Inkluderar följande filtyper: [`Mobi`](./mobi), [`Epub`](./epub), [`Azw3`](./azw3).

```csharp
public class EBookFormats : DocumentFormatBase
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Hämtar filändelsen för dokumentformatet. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Hämtar formatfamiljen som dokumentformatet tillhör. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Hämtar det unika identifieraren för formatfamiljen. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Hämtar MIME-typen för dokumentformatet. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Hämtar namnet på formatfamiljen. |
| static [All](../../groupdocs.editor.formats/ebookformats/all) { get; } | Hämtar en uppräkningsbar samling av alla [`EBookFormats`](../ebookformats). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/ebookformats/fromextension)(string) | Hämtar en instans av den angivna typen [`EBookFormats`](../ebookformats) som har den angivna filändelsen. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Bestämmer om denna instans är lika med den angivna [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase)-instansen. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Bestämmer om denna instans är lika med den angivna [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat)-instansen. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Bestämmer om denna instans är lika med den angivna [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase)-instansen. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Returnerar en hashkod för det aktuella objektet. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Returnerar en sträng som representerar det aktuella objektet. |
| [explicit operator](../../groupdocs.editor.formats/ebookformats/op_explicit) | Konverterar en sträng som representerar en filändelse till ett [`EBookFormats`](../ebookformats)-objekt. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| static readonly [Azw3](../../groupdocs.editor.formats/ebookformats/azw3) | AZW3, även känt som Kindle Format 8 (KF8), är den modifierade versionen av det digitala e-bokfilformatet AZW som utvecklats för Amazon Kindle-enheter. Formatet är en förbättring av äldre AZW-filer. Läs mer om detta filformat [här](https://docs.fileformat.com/ebook/azw3/). |
| static readonly [Epub](../../groupdocs.editor.formats/ebookformats/epub) | Electronic Publication (IDPF ePub)-formatet är ett e-bokfilformat som erbjuder ett standardiserat digitalt publiceringsformat för förlag och konsumenter. Läs mer om detta filformat [här](https://docs.fileformat.com/ebook/epub/). |
| static readonly [Mobi](../../groupdocs.editor.formats/ebookformats/mobi) | MOBI är namnet på det format som utvecklats för MobiPocket Reader. Även kallat PRC, AZW. Det används för närvarande av Amazon med ett något annorlunda DRM-schema och kallas AZW. Läs mer om detta filformat [här](https://docs.fileformat.com/ebook/mobi/). |

### Anmärkningar

Läs mer om Mobi-formatet [här](https://docs.fileformat.com/ebook/mobi/), om AZW3-formatet [här](https://docs.fileformat.com/ebook/azw3/), och om ePub-formatet [här](https://docs.fileformat.com/ebook/epub/).

### Se även

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
