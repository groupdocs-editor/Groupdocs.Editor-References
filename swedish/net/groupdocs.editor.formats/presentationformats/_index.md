---
title: PresentationFormats
second_title: GroupDocs.Editor för .NET API-referens
description: Kapslar in alla presentationsformat. Inkluderar följande format Odp./presentationformats/odp  Otp./presentationformats/otp  Pot./presentationformats/pot  Potm./presentationformats/potm  Potx./presentationformats/potx  Pps./presentationformats/pps  Ppsm./presentationformats/ppsm  Ppsx./presentationformats/ppsx  Ppt./presentationformats/ppt  Ppt95./presentationformats/ppt95  Pptm./presentationformats/pptm  Pptx./presentationformats/pptx. Läs mer om presentationsformathärhttps//wiki.fileformat.com/presentation .
type: docs
weight: 110
url: /sv/net/groupdocs.editor.formats/presentationformats/
---
## PresentationFormats structure

Kapslar in alla presentationsformat. Inkluderar följande format: [`Odp`](./odp) , [`Otp`](./otp) , [`Pot`](./pot) , [`Potm`](./potm) , [`Potx`](./potx) , [`Pps`](./pps) , [`Ppsm`](./ppsm) , [`Ppsx`](./ppsx) , [`Ppt`](./ppt) , [`Ppt95`](./ppt95) , [`Pptm`](./pptm) , [`Pptx`](./pptx). Läs mer om presentationsformat[här](https://wiki.fileformat.com/presentation) .

```csharp
public struct PresentationFormats : IDocumentFormat, IEquatable<PresentationFormats>
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/presentationformats/extension) { get; } | Returnerar ett tillägg (utan inledande punkttecken) av detta presentationsformat med små bokstäver |
| [Mime](../../groupdocs.editor.formats/presentationformats/mime) { get; } | Returnerar en MIME-kod för detta format |
| [Name](../../groupdocs.editor.formats/presentationformats/name) { get; } | Returnerar ett formellt fullständigt namn på denna presentation format |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/presentationformats/fromextension)(string) | Returnerar instans av[`PresentationFormats`](../presentationformats) struktur, kopplad till angivet filnamnstillägg, eller ger ett undantag, om tillägget inte kan analyseras korrekt |
| [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals)(IDocumentFormat) | Bestämmer om denna instans är lika med den andra specificerade IDocumentFormat-instansen |
| override [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals_2)(object) | Avgör om den här instansen är lika med det andra angivna objektet, det vill säga antagligen av boxed PresentationFormats |
| [Equals](../../groupdocs.editor.formats/presentationformats/equals#equals_1)(PresentationFormats) | Avgör om denna instans är lika med den andra angivna PresentationFormats-instansen |
| override [GetHashCode](../../groupdocs.editor.formats/presentationformats/gethashcode)() | Returnerar en hash-kod, som är oföränderlig för denna instans |
| [operator ==](../../groupdocs.editor.formats/presentationformats/op_equality) | Kontrollerar två givna PresentationFormats-instanser på equality |
| [operator !=](../../groupdocs.editor.formats/presentationformats/op_inequality) | Kontrollerar två givna PresentationFormats-instanser på inequality |

## Fält

| namn | Beskrivning |
| --- | --- |
| static readonly [Odp](../../groupdocs.editor.formats/presentationformats/odp) | OpenDocument Presentation (ODP)-fil representerar presentationsfilformat som används av OpenOffice.org i OASISOpen-standarden. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/odp) . |
| static readonly [Otp](../../groupdocs.editor.formats/presentationformats/otp) | OpenDocument Presentation Mall-fil (OTP) representerar presentationsmallfiler skapade av applikationer i OASIS OpenDocument standardformat. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/otp) . |
| static readonly [Pot](../../groupdocs.editor.formats/presentationformats/pot) | Microsoft PowerPoint 97-2003 Presentation Template-fil (POT) representerar Microsoft PowerPoint-mallfiler skapade av PowerPoint 97-2003-versioner. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/pot) . |
| static readonly [Potm](../../groupdocs.editor.formats/presentationformats/potm) | Microsoft Office Open XML PresentationML Macro-Enabled Template (POTM) är filer med stöd för makron. POTM-filer skapas med PowerPoint 2007 eller senare och innehåller standardinställningar som kan användas för att skapa ytterligare presentationsfiler. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/potm) . |
| static readonly [Potx](../../groupdocs.editor.formats/presentationformats/potx) | Microsoft Office Open XML PresentationML Macro-Free Template (POTX)-fil representerar Microsoft PowerPoint-mallpresentationer som skapats med Microsoft PowerPoint 2007 och senare. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/potx) . |
| static readonly [Pps](../../groupdocs.editor.formats/presentationformats/pps) | Microsoft PowerPoint 97-2003 SlideShow-filer (PPS) skapas med hjälp av Microsoft PowerPoint för bildspel. PPS-filläsning och skapande stöds av Microsoft PowerPoint 97-2003. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/pps) . |
| static readonly [Ppsm](../../groupdocs.editor.formats/presentationformats/ppsm) | Microsoft Office Open XML PresentationML Macro-Enabled SlideShow-filer (PPSM) skapas med Microsoft PowerPoint 2007 eller högre. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/ppsm) . |
| static readonly [Ppsx](../../groupdocs.editor.formats/presentationformats/ppsx) | Microsoft Office Open XML PresentationML Macro-Free SlideShow (PPSX)-filen skapas med Microsoft PowerPoint 2007 och senare för bildspelsändamål. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/ppsx) . |
| static readonly [Ppt](../../groupdocs.editor.formats/presentationformats/ppt) | PowerPoint-presentation (.ppt) representerar en PowerPoint-fil som består av en samling bilder för visning som bildspel. Den anger det binära filformatet som används av Microsoft PowerPoint 97-2003. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/ppt) . |
| static readonly [Ppt95](../../groupdocs.editor.formats/presentationformats/ppt95) | Microsoft PowerPoint 95-presentation (PPT) |
| static readonly [Pptm](../../groupdocs.editor.formats/presentationformats/pptm) | Microsoft Office Open XML PresentationML Macro-Enabled Document-filer (PPTM) som skapats med Microsoft PowerPoint 2007 eller senare versioner. De liknar PPTX-filer med skillnaden att den laterala inte kan köra makron även om de kan innehålla makron. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/pptm) . |
| static readonly [Pptx](../../groupdocs.editor.formats/presentationformats/pptx) | PowerPoint Open XML Presentation (.pptx) är en presentationsfil skapad med det populära Microsoft PowerPoint-programmet. Till skillnad från den tidigare versionen av presentationsfilformatet PPT som var binärt, är PPTX-formatet baserat på Microsoft PowerPoints öppna XML-presentationsfilformat. Läs mer om detta filformat[här](https://wiki.fileformat.com/presentation/pptx) . |
| static readonly [All](../../groupdocs.editor.formats/presentationformats/all) | Returnerar en intern klass som ger otaliga möjligheter över alla befintliga presentationsformat |

## Andra medlemmar

| namn | Beskrivning |
| --- | --- |
| class [AllEnumerable](presentationformats.allenumerable) | Implementerar IEnumerable generiskt gränssnitt, som möjliggör en "foreach"-möjlighet för PresentationFormats type |

### Se även

* interface [IDocumentFormat](../idocumentformat)
* namnutrymme [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* hopsättning [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
