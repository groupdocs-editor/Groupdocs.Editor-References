---
title: EBookFormats
second_title: GroupDocs.Editor för .NET API-referens
description: Kapslar in alla eboksformat. Inkluderar följande filtyper Mobi./ebookformats/mobi  Epub./ebookformats/epub  Azw3./ebookformats/azw3
type: docs
weight: 40
url: /sv/net/groupdocs.editor.formats/ebookformats/
---
## EBookFormats structure

Kapslar in alla e-boksformat. Inkluderar följande filtyper: [`Mobi`](./mobi) , [`Epub`](./epub) , [`Azw3`](./azw3)

```csharp
public struct EBookFormats : IDocumentFormat, IEquatable<EBookFormats>
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/ebookformats/extension) { get; } | Returnerar ett tillägg (utan inledande punkttecken) av detta e-boksformat med små bokstäver |
| [Mime](../../groupdocs.editor.formats/ebookformats/mime) { get; } | Returnerar en MIME-kod för detta format |
| [Name](../../groupdocs.editor.formats/ebookformats/name) { get; } | Returnerar ett formellt fullständigt namn på denna e-bok format |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/ebookformats/fromextension)(string) | Returnerar instans av[`EBookFormats`](../ebookformats)struktur, kopplad till angivet filnamnstillägg, eller ger ett undantag, om tillägget inte kan analyseras korrekt |
| [Equals](../../groupdocs.editor.formats/ebookformats/equals#equals)(EBookFormats) | Avgör om denna instans är lika med den andra angivna EBookFormats-instansen |
| [Equals](../../groupdocs.editor.formats/ebookformats/equals#equals_1)(IDocumentFormat) | Bestämmer om denna instans är lika med den andra specificerade IDocumentFormat-instansen |
| override [Equals](../../groupdocs.editor.formats/ebookformats/equals#equals_2)(object) | Bestämmer om den här instansen är lika med det andra angivna objektet, det vill säga antagligen av EBookFormats |
| override [GetHashCode](../../groupdocs.editor.formats/ebookformats/gethashcode)() | Returnerar en hash-kod, som är oföränderlig för denna instans |
| override [ToString](../../groupdocs.editor.formats/ebookformats/tostring)() | Returnerar ett formatnamn för detta format |
| [operator ==](../../groupdocs.editor.formats/ebookformats/op_equality) | Kontrollerar två givna EBookFormats-instanser på equality |
| [operator !=](../../groupdocs.editor.formats/ebookformats/op_inequality) | Kontrollerar två givna EBookFormats-instanser på inequality |

## Fält

| namn | Beskrivning |
| --- | --- |
| static readonly [Azw3](../../groupdocs.editor.formats/ebookformats/azw3) | AZW3, även känd som Kindle Format 8 (KF8), är den modifierade versionen av det digitala filformatet AZW e-bok som utvecklats för Amazon Kindle-enheter. Formatet är en förbättring av äldre AZW-filer. Läs mer om detta filformat[här](https://docs.fileformat.com/ebook/azw3/) . |
| static readonly [Epub](../../groupdocs.editor.formats/ebookformats/epub) | Electronic Publication (ePub)-format är ett e-boksfilformat som tillhandahåller ett standardformat för digitala publikationer för förlag och konsumenter. Läs mer om detta filformat[här](https://docs.fileformat.com/ebook/epub/) . |
| static readonly [Mobi](../../groupdocs.editor.formats/ebookformats/mobi) | MOBI är namnet på formatet som utvecklats för MobiPocket Reader. Det används för närvarande av Amazon med ett något annat DRM-schema och kallas AZW. Läs mer om detta filformat[här](https://docs.fileformat.com/ebook/mobi/) . |
| static readonly [All](../../groupdocs.editor.formats/ebookformats/all) | Returnerar en intern klass som ger otaliga möjligheter över alla befintliga e-boksformat |

## Andra medlemmar

| namn | Beskrivning |
| --- | --- |
| class [AllEnumerable](ebookformats.allenumerable) | Implementerar IEnumerable generiskt gränssnitt, som möjliggör en "foreach"-möjlighet för EBookFormats type |

### Anmärkningar

Lär dig mer om Mobi-format[här](https://docs.fileformat.com/ebook/mobi/) om AZW3-format[här](https://docs.fileformat.com/ebook/azw3/) och om ePub-format[här](https://docs.fileformat.com/ebook/epub/) .

### Se även

* interface [IDocumentFormat](../idocumentformat)
* namnutrymme [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* hopsättning [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->