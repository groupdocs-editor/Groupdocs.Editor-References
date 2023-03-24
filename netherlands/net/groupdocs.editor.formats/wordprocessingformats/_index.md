---
title: WordProcessingFormats
second_title: GroupDocs.Editor voor .NET API-referentie
description: Bevat alle WordProcessingindelingen. Bevat de volgende bestandstypen Doc./wordprocessingformats/doc  Docm./wordprocessingformats/docm  Docx./wordprocessingformats/docx  Dot./wordprocessingformats/dot  Dotm./wordprocessingformats/dotm  Dotx./wordprocessingformats/dotx  FlatOpc./wordprocessingformats/flatopc  Odt./wordprocessingformats/odt  Ott./wordprocessingformats/ott  Rtf./wordprocessingformats/rtf  WordML./wordprocessingformats/wordml . Meer informatie over indelingen voor tekstverwerkinghierhttps//wiki.fileformat.com/wordprocessing .
type: docs
weight: 170
url: /nl/net/groupdocs.editor.formats/wordprocessingformats/
---
## WordProcessingFormats structure

Bevat alle WordProcessing-indelingen. Bevat de volgende bestandstypen: [`Doc`](./doc) , [`Docm`](./docm) , [`Docx`](./docx) , [`Dot`](./dot) , [`Dotm`](./dotm) , [`Dotx`](./dotx) , [`FlatOpc`](./flatopc) , [`Odt`](./odt) , [`Ott`](./ott) , [`Rtf`](./rtf) , [`WordML`](./wordml) . Meer informatie over indelingen voor tekstverwerking[hier](https://wiki.fileformat.com/word-processing) .

```csharp
public struct WordProcessingFormats : IDocumentFormat, IEquatable<WordProcessingFormats>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/wordprocessingformats/extension) { get; } | Retourneert een extensie (zonder voorlooppunt) van deze WordProcessing-indeling in kleine letters |
| [Mime](../../groupdocs.editor.formats/wordprocessingformats/mime) { get; } | Retourneert een MIME-code voor deze indeling |
| [Name](../../groupdocs.editor.formats/wordprocessingformats/name) { get; } | Retourneert een formele volledige naam van deze WordProcessing-indeling |

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/wordprocessingformats/fromextension)(string) | Retourneert instantie van[`WordProcessingFormats`](../wordprocessingformats) structuur, gekoppeld aan de opgegeven bestandsnaamextensie, of genereert een uitzondering als de extensie niet correct kan worden geparseerd |
| [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals)(IDocumentFormat) | Bepaalt of deze instantie gelijk is aan de andere opgegeven IDocumentFormat-instantie |
| override [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals_2)(object) | Bepaalt of deze instantie gelijk is aan het andere gespecificeerde object, dat vermoedelijk een boxed WordProcessingFormats is |
| [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals_1)(WordProcessingFormats) | Bepaalt of deze instantie gelijk is aan de andere opgegeven WordProcessingFormats-instantie |
| override [GetHashCode](../../groupdocs.editor.formats/wordprocessingformats/gethashcode)() | Retourneert een hash-code, die onveranderlijk is voor deze instantie |
| override [ToString](../../groupdocs.editor.formats/wordprocessingformats/tostring)() | Retourneert de naam van dit specifieke formaat, hetzelfde als 'Name' property |
| [operator ==](../../groupdocs.editor.formats/wordprocessingformats/op_equality) | Controleert twee gegeven WordProcessingFormats-instanties op gelijkheid |
| [explicit operator](../../groupdocs.editor.formats/wordprocessingformats/op_explicit#op_explicit) | Retourneert een bytewaarde uit het onderliggende veld van opgegeven WordProcessingFormats-instantie (2 operators) |
| [operator !=](../../groupdocs.editor.formats/wordprocessingformats/op_inequality) | Controleert twee gegeven WordProcessingFormats-instanties op inequality |

## Velden

| Naam | Beschrijving |
| --- | --- |
| static readonly [Doc](../../groupdocs.editor.formats/wordprocessingformats/doc) | MS Word 97-2007 Binary File Format (DOC) vertegenwoordigt documenten gegenereerd door Microsoft Word of andere tekstverwerkingsdocumenten in binaire bestandsindeling. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [Docm](../../groupdocs.editor.formats/wordprocessingformats/docm) | Office Open XML WordProcessingML Macro-Enabled Document (DOCM)-bestanden zijn Microsoft Word 2007 of hoger gegenereerde documenten met de mogelijkheid om macro's uit te voeren. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [Docx](../../groupdocs.editor.formats/wordprocessingformats/docx) | Office Open XML WordProcessingML Macro-Free Document (DOCX) is een bekend formaat voor Microsoft Word-documenten. Geïntroduceerd vanaf 2007 met de release van Microsoft Office 2007, is de structuur van deze nieuwe documentindeling gewijzigd van gewoon binair naar een combinatie van XML en binaire bestanden. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [Dot](../../groupdocs.editor.formats/wordprocessingformats/dot) | MS Word 97-2007-sjabloon zijn sjabloonbestanden die door Microsoft Word zijn gemaakt met vooraf geformatteerde instellingen voor het genereren van verdere DOC- of DOCX-bestanden. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [Dotm](../../groupdocs.editor.formats/wordprocessingformats/dotm) | Office Open XML WordprocessingML Macro-Enabled Template (DOTM) vertegenwoordigt een sjabloonbestand gemaakt met Microsoft Word 2007 of hoger. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [Dotx](../../groupdocs.editor.formats/wordprocessingformats/dotx) | Office Open XML WordprocessingML Macro-Free Template (DOTX) zijn sjabloonbestanden die door Microsoft Word zijn gemaakt met vooraf opgemaakte instellingen voor het genereren van verdere DOCX-bestanden. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [FlatOpc](../../groupdocs.editor.formats/wordprocessingformats/flatopc) | Office Open XML WordprocessingML opgeslagen in een plat XML-bestand in plaats van een ZIP-pakket |
| static readonly [Odt](../../groupdocs.editor.formats/wordprocessingformats/odt) | Open Document-indeling Tekstdocumentbestanden (ODT) zijn type documenten die zijn gemaakt met tekstverwerkingsprogramma's die zijn gebaseerd op de OpenDocument-tekstbestandsindeling. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [Ott](../../groupdocs.editor.formats/wordprocessingformats/ott) | Open Document-indeling Tekstdocumentsjabloon (OTT) vertegenwoordigt sjabloondocumenten die zijn gegenereerd door toepassingen in overeenstemming met de OpenDocument-standaardindeling van OASIS. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [Rtf](../../groupdocs.editor.formats/wordprocessingformats/rtf) | Rich Text Format (RTF) vertegenwoordigt een methode voor het coderen van opgemaakte tekst en afbeeldingen voor gebruik in toepassingen. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [WordML](../../groupdocs.editor.formats/wordprocessingformats/wordml) | Microsoft Office Word 2003 XML-indeling — WordProcessingML of WordML (.XML) |
| static readonly [All](../../groupdocs.editor.formats/wordprocessingformats/all) | Geeft een interne klasse terug, die ontelbare mogelijkheden biedt voor alle bestaande WordProcessing-formaten |

## Andere leden

| Naam | Beschrijving |
| --- | --- |
| class [AllEnumerable](wordprocessingformats.allenumerable) | Implementeert IEnumerable generieke interface, die een 'foreach'-mogelijkheid mogelijk maakt voor de WordProcessingFormats type |

### Opmerkingen

MIME-codes worden uit de gegeven bronnen gehaald: https://filext.com/faq/office_mime_types.html https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

### Zie ook

* interface [IDocumentFormat](../idocumentformat)
* naamruimte [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
