---
title: SpreadsheetFormats
second_title: GroupDocs.Editor för .NET API-referens
description: Kapslar in alla binära XML och textkalkylbladsformat exklusive alla textavgränsningsbaserade format med avgränsare som CSV TSV semikolonavgränsade etc. där arbetsboken kan sparas. Innehåller följande format Dif./spreadsheetformats/dif  Fods./spreadsheetformats/fods  Ods./spreadsheetformats/ods  Sxc./spreadsheetformats/sxc  Xlam./spreadsheetformats/xlam  Xls./spreadsheetformats/xls  Xlsb./spreadsheetformats/xlsb  Xlsm./spreadsheetformats/xlsm  Xlsx./spreadsheetformats/xlsx  Xlt./spreadsheetformats/xlt  Xltm./spreadsheetformats/xltm  Xltx./spreadsheetformats/xltx . Läs mer om kalkylarksformathärhttps//wiki.fileformat.com/spreadsheet .
type: docs
weight: 130
url: /sv/net/groupdocs.editor.formats/spreadsheetformats/
---
## SpreadsheetFormats structure

Kapslar in alla binära, XML- och textkalkylbladsformat (exklusive alla textavgränsningsbaserade format med avgränsare som CSV, TSV, semikolonavgränsade etc.), där arbetsboken kan sparas. Innehåller följande format: [`Dif`](./dif) , [`Fods`](./fods) , [`Ods`](./ods) , [`Sxc`](./sxc) , [`Xlam`](./xlam) , [`Xls`](./xls) , [`Xlsb`](./xlsb) , [`Xlsm`](./xlsm) , [`Xlsx`](./xlsx) , [`Xlt`](./xlt) , [`Xltm`](./xltm) , [`Xltx`](./xltx) . Läs mer om kalkylarksformat[här](https://wiki.fileformat.com/spreadsheet) .

```csharp
public struct SpreadsheetFormats : IDocumentFormat, IEquatable<SpreadsheetFormats>
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/spreadsheetformats/extension) { get; } | Returnerar ett tillägg (utan inledande punkttecken) av detta kalkylarksformat med gemener |
| [Mime](../../groupdocs.editor.formats/spreadsheetformats/mime) { get; } | Returnerar en MIME-kod för detta format |
| [Name](../../groupdocs.editor.formats/spreadsheetformats/name) { get; } | Returnerar ett formellt fullständigt namn på detta kalkylark format |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/spreadsheetformats/fromextension)(string) | Returnerar instans av[`SpreadsheetFormats`](../spreadsheetformats) struktur, kopplad till angivet filnamnstillägg, eller ger ett undantag, om tillägget inte kan analyseras korrekt |
| [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals)(IDocumentFormat) | Bestämmer om denna instans är lika med den andra specificerade IDocumentFormat-instansen |
| override [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals_2)(object) | Bestämmer om denna instans är lika med det andra angivna objektet, det vill säga antagligen av boxed SpreadsheetFormats |
| [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals_1)(SpreadsheetFormats) | Avgör om denna instans är lika med den andra angivna SpreadsheetFormats-instansen |
| override [GetHashCode](../../groupdocs.editor.formats/spreadsheetformats/gethashcode)() | Returnerar en hash-kod, som är oföränderlig för denna instans |
| [operator ==](../../groupdocs.editor.formats/spreadsheetformats/op_equality) | Kontrollerar två givna SpreadsheetFormats-instanser på equality |
| [operator !=](../../groupdocs.editor.formats/spreadsheetformats/op_inequality) | Kontrollerar två givna SpreadsheetFormats-instanser på inequality |

## Fält

| namn | Beskrivning |
| --- | --- |
| static readonly [Csv](../../groupdocs.editor.formats/spreadsheetformats/csv) | CSV-dokument (Comma Separated Values) representerar vanlig text som innehåller dataposter med kommaseparerade värden. Varje rad i en CSV-fil är en ny post från den uppsättning poster som finns i filen. Läs mer om detta filformat[här](https://docs.fileformat.com/spreadsheet/csv/) . |
| static readonly [Dif](../../groupdocs.editor.formats/spreadsheetformats/dif) | Data Interchange Format (DIF) |
| static readonly [Fods](../../groupdocs.editor.formats/spreadsheetformats/fods) | Flat OpenDocument Spreadsheet (FODS) — lagras som ett enda okomprimerat XML-dokument |
| static readonly [Ods](../../groupdocs.editor.formats/spreadsheetformats/ods) | OpenDocument Spreadsheet (ODS) står för OpenDocument Spreadsheet-dokumentformat som kan redigeras av användaren. Data lagras i ODF-filen i rader och kolumner. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [SpreadsheetML](../../groupdocs.editor.formats/spreadsheetformats/spreadsheetml) | SpreadsheetML — Microsoft Office Excel 2002 och Excel 2003 XML Format |
| static readonly [Sxc](../../groupdocs.editor.formats/spreadsheetformats/sxc) | StarOffice eller OpenOffice.org Calc XML Spreadsheet (SXC) |
| static readonly [Tsv](../../groupdocs.editor.formats/spreadsheetformats/tsv) | TSV-filformatet (Tab-Separated Values) representerar data separerade med flikar i vanligt textformat. Filformatet, liknande CSV, används för att organisera data på ett strukturerat sätt för att importera och exportera mellan olika applikationer. Läs mer om detta filformat[här](https://docs.fileformat.com/spreadsheet/tsv/) . |
| static readonly [Xlam](../../groupdocs.editor.formats/spreadsheetformats/xlam) | Excel-tillägg (XLAM) |
| static readonly [Xls](../../groupdocs.editor.formats/spreadsheetformats/xls) | Excel 97-2003 Binärt filformat (XLS) representerar filer som kan skapas av Microsoft Excel såväl som andra liknande kalkylprogram som OpenOffice Calc eller Apple Numbers. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [Xlsb](../../groupdocs.editor.formats/spreadsheetformats/xlsb) | Excel Binary Workbook (XLSB) specificerar Excel Binary File Format, som är en samling poster och strukturer som specificerar Excel-arbetsbokens innehåll. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [Xlsm](../../groupdocs.editor.formats/spreadsheetformats/xlsm) | Office Open XML Workbook Macro-Enabled (XLSM) är en typ av kalkylbladsfiler som stöder makron. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [Xlsx](../../groupdocs.editor.formats/spreadsheetformats/xlsx) | Office Open XML Workbook Macro-Free (XLSX) representerar dokument som introducerades av Microsoft med lanseringen av Microsoft Office 2007. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [Xlt](../../groupdocs.editor.formats/spreadsheetformats/xlt) | Excel 97-2003 Mall (XLT) representerar mallfiler skapade med Microsoft Excel som är ett kalkylbladsprogram som ingår i Microsoft Office-paketet. Microsoft Office 97-2003 stödde att skapa nya XLT-filer samt att öppna dessa. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [Xltm](../../groupdocs.editor.formats/spreadsheetformats/xltm) | Office Open XML Template Macro-Enabled (XLTM) representerar filer som genereras av Microsoft Excel som makroaktiverade mallfiler. XLTM-filer liknar XLTX i annan struktur än att de senare inte stöder att skapa mallfiler med makron. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/xltm) . |
| static readonly [Xltx](../../groupdocs.editor.formats/spreadsheetformats/xltx) | Office Open XML Template Macro-Free (XLTX)-fil representerar Microsoft Excel-mall som är baserad på Office OpenXML-filformatspecifikationerna. Den används för att skapa en standardmallfil som kan användas för att generera XLSX-filer som uppvisar samma inställningar som anges i XLTX-filen. Läs mer om detta filformat[här](https://wiki.fileformat.com/spreadsheet/xltx) . |
| static readonly [All](../../groupdocs.editor.formats/spreadsheetformats/all) | Returnerar en intern klass som ger otaliga möjligheter över alla befintliga kalkylarksformat |

## Andra medlemmar

| namn | Beskrivning |
| --- | --- |
| class [AllEnumerable](spreadsheetformats.allenumerable) | Implementerar IEnumerable generiskt gränssnitt, som möjliggör en "foreach"-möjlighet för SpreadsheetFormats type |

### Se även

* interface [IDocumentFormat](../idocumentformat)
* namnutrymme [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* hopsättning [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
