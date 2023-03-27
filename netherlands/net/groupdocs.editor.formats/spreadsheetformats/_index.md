---
title: SpreadsheetFormats
second_title: GroupDocs.Editor voor .NET API-referentie
description: Bevat alle binaire XML en tekstuele spreadsheetindelingen met uitzondering van alle op tekstscheidingstekens gebaseerde indelingen met scheidingstekens zoals CSV TSV door puntkommas gescheiden enz. waarin de werkmap kan worden opgeslagen. Bevat de volgende indelingen Dif./spreadsheetformats/dif  Fods./spreadsheetformats/fods  Ods./spreadsheetformats/ods  Sxc./spreadsheetformats/sxc  Xlam./spreadsheetformats/xlam  Xls./spreadsheetformats/xls  Xlsb./spreadsheetformats/xlsb  Xlsm./spreadsheetformats/xlsm  Xlsx./spreadsheetformats/xlsx  Xlt./spreadsheetformats/xlt  Xltm./spreadsheetformats/xltm  Xltx./spreadsheetformats/xltx . Meer informatie over spreadsheetindelingenhierhttps//wiki.fileformat.com/spreadsheet .
type: docs
weight: 130
url: /nl/net/groupdocs.editor.formats/spreadsheetformats/
---
## SpreadsheetFormats structure

Bevat alle binaire, XML- en tekstuele spreadsheetindelingen (met uitzondering van alle op tekstscheidingstekens gebaseerde indelingen met scheidingstekens zoals CSV, TSV, door puntkomma's gescheiden enz.), waarin de werkmap kan worden opgeslagen. Bevat de volgende indelingen: [`Dif`](./dif) , [`Fods`](./fods) , [`Ods`](./ods) , [`Sxc`](./sxc) , [`Xlam`](./xlam) , [`Xls`](./xls) , [`Xlsb`](./xlsb) , [`Xlsm`](./xlsm) , [`Xlsx`](./xlsx) , [`Xlt`](./xlt) , [`Xltm`](./xltm) , [`Xltx`](./xltx) . Meer informatie over spreadsheetindelingen[hier](https://wiki.fileformat.com/spreadsheet) .

```csharp
public struct SpreadsheetFormats : IDocumentFormat, IEquatable<SpreadsheetFormats>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/spreadsheetformats/extension) { get; } | Retourneert een extensie (zonder voorlooppunt) van deze Spreadsheet-indeling in kleine letters |
| [Mime](../../groupdocs.editor.formats/spreadsheetformats/mime) { get; } | Retourneert een MIME-code voor deze indeling |
| [Name](../../groupdocs.editor.formats/spreadsheetformats/name) { get; } | Retourneert een formele volledige naam van deze Spreadsheet-indeling |

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/spreadsheetformats/fromextension)(string) | Retourneert instantie van[`SpreadsheetFormats`](../spreadsheetformats) structuur, gekoppeld aan de opgegeven bestandsnaamextensie, of genereert een uitzondering als de extensie niet correct kan worden geparseerd |
| [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals)(IDocumentFormat) | Bepaalt of deze instantie gelijk is aan de andere opgegeven IDocumentFormat-instantie |
| override [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals_2)(object) | Bepaalt of deze instantie gelijk is aan het andere gespecificeerde object, dat vermoedelijk een boxed SpreadsheetFormats is |
| [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals_1)(SpreadsheetFormats) | Bepaalt of deze instantie gelijk is aan de andere gespecificeerde SpreadsheetFormats instantie |
| override [GetHashCode](../../groupdocs.editor.formats/spreadsheetformats/gethashcode)() | Retourneert een hash-code, die onveranderlijk is voor deze instantie |
| [operator ==](../../groupdocs.editor.formats/spreadsheetformats/op_equality) | Controleert twee gegeven SpreadsheetFormats-instanties op gelijkheid |
| [operator !=](../../groupdocs.editor.formats/spreadsheetformats/op_inequality) | Controleert twee gegeven SpreadsheetFormats-instanties op inequality |

## Velden

| Naam | Beschrijving |
| --- | --- |
| static readonly [Csv](../../groupdocs.editor.formats/spreadsheetformats/csv) | Documenten met door komma's gescheiden waarden (CSV) vertegenwoordigen platte tekst die gegevensrecords met door komma's gescheiden waarden bevat. Elke regel in een CSV-bestand is een nieuwe record uit de reeks records in het bestand. Meer informatie over deze bestandsindeling[hier](https://docs.fileformat.com/spreadsheet/csv/) . |
| static readonly [Dif](../../groupdocs.editor.formats/spreadsheetformats/dif) | Gegevensuitwisselingsformaat (DIF) |
| static readonly [Fods](../../groupdocs.editor.formats/spreadsheetformats/fods) | Flat OpenDocument Spreadsheet (FODS) — opgeslagen als één ongecomprimeerd XML-document |
| static readonly [Ods](../../groupdocs.editor.formats/spreadsheetformats/ods) | OpenDocument Spreadsheet (ODS) staat voor OpenDocument Spreadsheet Documentformaat dat door de gebruiker kan worden bewerkt. Gegevens worden in het ODF-bestand opgeslagen in rijen en kolommen. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [SpreadsheetML](../../groupdocs.editor.formats/spreadsheetformats/spreadsheetml) | SpreadsheetML — Microsoft Office Excel 2002 en Excel 2003 XML-indeling |
| static readonly [Sxc](../../groupdocs.editor.formats/spreadsheetformats/sxc) | StarOffice of OpenOffice.org Calc XML Spreadsheet (SXC) |
| static readonly [Tsv](../../groupdocs.editor.formats/spreadsheetformats/tsv) | Tab-Separated Values (TSV) bestandsformaat vertegenwoordigt gegevens gescheiden door tabs in tekst zonder opmaak. Het bestandsformaat, vergelijkbaar met CSV, wordt gebruikt voor het gestructureerd organiseren van gegevens om te importeren en exporteren tussen verschillende applicaties. Meer informatie over dit bestandsformaat[hier](https://docs.fileformat.com/spreadsheet/tsv/) . |
| static readonly [Xlam](../../groupdocs.editor.formats/spreadsheetformats/xlam) | Excel-invoegtoepassing (XLAM) |
| static readonly [Xls](../../groupdocs.editor.formats/spreadsheetformats/xls) | Excel 97-2003 Binary File Format (XLS) vertegenwoordigt bestanden die kunnen worden gemaakt door Microsoft Excel en andere vergelijkbare spreadsheetprogramma's zoals OpenOffice Calc of Apple Numbers. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [Xlsb](../../groupdocs.editor.formats/spreadsheetformats/xlsb) | Excel binaire werkmap (XLSB) specificeert de Excel binaire bestandsindeling, een verzameling records en structuren die de inhoud van de Excel-werkmap specificeren. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [Xlsm](../../groupdocs.editor.formats/spreadsheetformats/xlsm) | Office Open XML-werkmap Macro-Enabled (XLSM) is een type spreadsheet-bestand dat macro's ondersteunt. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [Xlsx](../../groupdocs.editor.formats/spreadsheetformats/xlsx) | Office Open XML Workbook Macro-Free (XLSX) vertegenwoordigt documenten die door Microsoft zijn geïntroduceerd met de release van Microsoft Office 2007. Meer informatie over deze bestandsindeling[hier](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [Xlt](../../groupdocs.editor.formats/spreadsheetformats/xlt) | Excel 97-2003-sjabloon (XLT) vertegenwoordigt sjabloonbestanden die zijn gemaakt met Microsoft Excel, een spreadsheettoepassing die deel uitmaakt van de Microsoft Office-suite. Microsoft Office 97-2003 ondersteunde het maken van nieuwe XLT-bestanden en het openen ervan. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [Xltm](../../groupdocs.editor.formats/spreadsheetformats/xltm) | Office Open XML Template Macro-Enabled (XLTM) vertegenwoordigt bestanden die door Microsoft Excel worden gegenereerd als macro-enabled sjabloonbestanden. XLTM-bestanden lijken qua structuur op XLTX, behalve dat de laatste geen ondersteuning biedt voor het maken van sjabloonbestanden met macro's. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/spreadsheet/xltm) . |
| static readonly [Xltx](../../groupdocs.editor.formats/spreadsheetformats/xltx) | Office Open XML-sjabloon Macrovrij (XLTX)-bestand vertegenwoordigt Microsoft Excel-sjabloon die is gebaseerd op de Office OpenXML-bestandsformaatspecificaties. Het wordt gebruikt om een standaard sjabloonbestand te maken dat kan worden gebruikt om XLSX-bestanden te genereren met dezelfde instellingen als gespecificeerd in het XLTX-bestand. Meer informatie over dit bestandsformaat[hier](https://wiki.fileformat.com/spreadsheet/xltx) . |
| static readonly [All](../../groupdocs.editor.formats/spreadsheetformats/all) | Geeft een interne klasse terug, die ontelbare mogelijkheden biedt voor alle bestaande spreadsheetformaten |

## Andere leden

| Naam | Beschrijving |
| --- | --- |
| class [AllEnumerable](spreadsheetformats.allenumerable) | Implementeert IEnumerable generieke interface, die een 'foreach'-mogelijkheid mogelijk maakt voor de SpreadsheetFormats type |

### Zie ook

* interface [IDocumentFormat](../idocumentformat)
* naamruimte [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
