---
title: TextualFormats
second_title: GroupDocs.Editor för .NET API-referens
description: Kapslar in alla textbaserade textbaserade format inklusive uppmärkning XML HTML och andra. Innehåller följande format Html./textualformats/html  Txt./textualformats/txt  Xml./textualformats/xml . Md./textualformats/md  Json./textualformats/json .
type: docs
weight: 150
url: /sv/net/groupdocs.editor.formats/textualformats/
---
## TextualFormats structure

Kapslar in alla textbaserade (textbaserade) format, inklusive uppmärkning (XML, HTML) och andra. Innehåller följande format: [`Html`](./html) , [`Txt`](./txt) , [`Xml`](./xml) . [`Md`](./md) , [`Json`](./json) .

```csharp
public struct TextualFormats : IDocumentFormat, IEquatable<TextualFormats>
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/textualformats/extension) { get; } | Returnerar ett tillägg (utan inledande punkttecken) av detta textformat med gemener |
| [Mime](../../groupdocs.editor.formats/textualformats/mime) { get; } | Returnerar en MIME-kod för detta format |
| [Name](../../groupdocs.editor.formats/textualformats/name) { get; } | Returnerar ett formellt fullständigt namn på detta textformat |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/textualformats/fromextension)(string) | Returnerar instans av[`TextualFormats`](../textualformats)struktur, kopplad till angivet filnamnstillägg, eller ger ett undantag, om tillägget inte kan analyseras korrekt |
| [Equals](../../groupdocs.editor.formats/textualformats/equals#equals)(IDocumentFormat) | Bestämmer om denna instans är lika med den andra specificerade IDocumentFormat-instansen |
| override [Equals](../../groupdocs.editor.formats/textualformats/equals#equals_2)(object) | Avgör om den här instansen är lika med det andra angivna objektet, det vill säga antagligen av textualFormats |
| [Equals](../../groupdocs.editor.formats/textualformats/equals#equals_1)(TextualFormats) | Avgör om denna instans är lika med den andra angivna TextualFormats-instansen |
| override [GetHashCode](../../groupdocs.editor.formats/textualformats/gethashcode)() | Returnerar en hash-kod, som är oföränderlig för denna instans |
| override [ToString](../../groupdocs.editor.formats/textualformats/tostring)() | Returnerar namnet på detta specifika format, samma som "Namn" egenskap |
| [operator ==](../../groupdocs.editor.formats/textualformats/op_equality) | Kontrollerar två givna TextualFormats-instanser på equality |
| [operator !=](../../groupdocs.editor.formats/textualformats/op_inequality) | Kontrollerar två givna TextualFormats-instanser på inequality |

## Fält

| namn | Beskrivning |
| --- | --- |
| static readonly [Chm](../../groupdocs.editor.formats/textualformats/chm) | Microsoft Compiled HTML Help är ett Microsofts egenutvecklade binära hjälpformat online, som består av en samling HTML-sidor, ett index och andra navigeringsverktyg. Läs mer om detta filformat[här](https://docs.fileformat.com/web/chm/) . |
| static readonly [Html](../../groupdocs.editor.formats/textualformats/html) | HyperText Markup Language Document (HTML) är tillägget för webbsidor som skapats för visning i webbläsare. Läs mer om detta filformat[här](https://wiki.fileformat.com/web/html) . |
| static readonly [Json](../../groupdocs.editor.formats/textualformats/json) | JSON (JavaScript Object Notation) är ett öppet standardfilformat för att dela data som använder läsbar text för att lagra och överföra data. Läs mer om detta filformat[här](https://docs.fileformat.com/web/json/) . |
| static readonly [Md](../../groupdocs.editor.formats/textualformats/md) | Markdown är ett lättviktigt märkningsspråk för att skapa formaterad text med en vanlig textredigerare. Läs mer om detta filformat[här](https://docs.fileformat.com/word-processing/md/) . |
| static readonly [Mhtml](../../groupdocs.editor.formats/textualformats/mhtml) | MIME-inkapsling av aggregerade HTML-dokument är ett webbsidearkivformat som används för att kombinera HTML-koden och dess kompletterande resurser i en enda datorfil. Läs mer om detta filformat[här](https://docs.fileformat.com/web/mhtml/) . |
| static readonly [Txt](../../groupdocs.editor.formats/textualformats/txt) | Plain Text Document (TXT) representerar ett textdokument som innehåller ren text i form av rader. Läs mer om detta filformat[här](https://wiki.fileformat.com/word-processing/txt) . |
| static readonly [Xml](../../groupdocs.editor.formats/textualformats/xml) | eXtensible Markup Language-dokument (XML) som liknar HTML men skiljer sig från att använda taggar för att definiera objekt. Läs mer om detta filformat[här](https://wiki.fileformat.com/web/xml) . |
| static readonly [All](../../groupdocs.editor.formats/textualformats/all) | Returnerar en intern klass som ger otaliga möjligheter över alla befintliga textformat. |

## Andra medlemmar

| namn | Beskrivning |
| --- | --- |
| class [AllEnumerable](textualformats.allenumerable) | Implementerar IEnumerable generiskt gränssnitt, som möjliggör en "foreach"-möjlighet för TextualFormats type |

### Se även

* interface [IDocumentFormat](../idocumentformat)
* namnutrymme [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* hopsättning [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
