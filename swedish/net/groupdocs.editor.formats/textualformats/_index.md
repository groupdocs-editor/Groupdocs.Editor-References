---
title: "TextualFormats"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Innesluter alla textbaserade format inklusive markup XML HTML och andra. Inkluderar följande format Html./textualformats/html Txt./textualformats/txt Xml./textualformats/xml Md./textualformats/md Json./textualformats/json Mhtml./textualformats/mhtml Chm./textualformats/chm."
type: docs
weight: 140
url: /sv/net/groupdocs.editor.formats/textualformats/
---
## TextualFormats class

Innesluter alla textbaserade (text-baserade) format, inklusive markup (XML, HTML) och andra. Inkluderar följande format: [`Html`](./html), [`Txt`](./txt), [`Xml`](./xml), [`Md`](./md), [`Json`](./json), [`Mhtml`](./mhtml), [`Chm`](./chm).

```csharp
public class TextualFormats : DocumentFormatBase
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Hämtar filändelsen för dokumentformatet. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Hämtar formatfamiljen som dokumentformatet tillhör. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Hämtar det unika identifieraren för formatfamiljen. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Hämtar MIME-typen för dokumentformatet. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Hämtar namnet på formatfamiljen. |
| static [All](../../groupdocs.editor.formats/textualformats/all) { get; } | Hämtar en uppräkningsbar samling av alla [`TextualFormats`](../textualformats). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/textualformats/fromextension)(string) | Hämtar en instans av den angivna typen [`TextualFormats`](../textualformats) som har den angivna filändelsen. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Bestämmer om denna instans är lika med den angivna [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase)-instansen. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Bestämmer om denna instans är lika med den angivna [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat)-instansen. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Bestämmer om denna instans är lika med den angivna [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase)-instansen. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Returnerar en hashkod för det aktuella objektet. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Returnerar en sträng som representerar det aktuella objektet. |
| [explicit operator](../../groupdocs.editor.formats/textualformats/op_explicit) | Konverterar en sträng som representerar en filändelse till ett [`TextualFormats`](../textualformats)-objekt. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| static readonly [Chm](../../groupdocs.editor.formats/textualformats/chm) | Microsoft Compiled HTML Help är ett Microsoft-ägt binärt format för onlinehjälp, bestående av en samling HTML‑sidor, ett index och andra navigationsverktyg. Läs mer om detta filformat [här](https://docs.fileformat.com/web/chm/). |
| static readonly [Html](../../groupdocs.editor.formats/textualformats/html) | HyperText Markup Language-dokument (HTML) är filändelsen för webbsidor som skapats för visning i webbläsare. Läs mer om detta filformat [här](https://wiki.fileformat.com/web/html). |
| static readonly [Json](../../groupdocs.editor.formats/textualformats/json) | JSON (JavaScript Object Notation) är ett öppet standardfilformat för datadelning som använder människoläsbar text för att lagra och överföra data. Läs mer om detta filformat [här](https://docs.fileformat.com/web/json/). |
| static readonly [Md](../../groupdocs.editor.formats/textualformats/md) | Markdown är ett lättviktigt markup-språk för att skapa formaterad text med en vanlig textredigerare. Läs mer om detta filformat [här](https://docs.fileformat.com/word-processing/md/). |
| static readonly [Mhtml](../../groupdocs.editor.formats/textualformats/mhtml) | MIME‑inkapsling av aggregerade HTML‑dokument är ett webbsidesarkivformat som används för att kombinera, i en enda datorfil, HTML‑koden och dess tillhörande resurser. Läs mer om detta filformat [här](https://docs.fileformat.com/web/mhtml/). |
| static readonly [Txt](../../groupdocs.editor.formats/textualformats/txt) | Plain Text Document (TXT) representerar ett textdokument som innehåller ren text i form av rader. Läs mer om detta filformat [här](https://wiki.fileformat.com/word-processing/txt). |
| static readonly [Xml](../../groupdocs.editor.formats/textualformats/xml) | eXtensible Markup Language-dokument (XML) som liknar HTML men skiljer sig åt genom att använda taggar för att definiera objekt. Läs mer om detta filformat [här](https://wiki.fileformat.com/web/xml). |

### Se även

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
