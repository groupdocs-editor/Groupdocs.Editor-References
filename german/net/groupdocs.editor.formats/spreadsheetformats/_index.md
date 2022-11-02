---
title: SpreadsheetFormats
second_title: GroupDocs.Editor für .NET-API-Referenz
description: Kapselt alle Binär XML und Texttabellenformate mit Ausnahme aller auf Texttrennzeichen basierenden Formate mit Trennzeichen wie CSV TSV Semikolongetrennt usw. in denen die Arbeitsmappe gespeichert werden kann. Enthält die folgenden Formate Dif./spreadsheetformats/dif  Fods./spreadsheetformats/fods  Ods./spreadsheetformats/ods  Sxc./spreadsheetformats/sxc  Xlam./spreadsheetformats/xlam  Xls./spreadsheetformats/xls  Xlsb./spreadsheetformats/xlsb  Xlsm./spreadsheetformats/xlsm  Xlsx./spreadsheetformats/xlsx  Xlt./spreadsheetformats/xlt  Xltm./spreadsheetformats/xltm  Xltx./spreadsheetformats/xltx . Erfahren Sie mehr über Tabellenkalkulationsformatehierhttps//wiki.fileformat.com/spreadsheet .
type: docs
weight: 130
url: /de/net/groupdocs.editor.formats/spreadsheetformats/
---
## SpreadsheetFormats structure

Kapselt alle Binär-, XML- und Texttabellenformate (mit Ausnahme aller auf Texttrennzeichen basierenden Formate mit Trennzeichen wie CSV, TSV, Semikolon-getrennt usw.), in denen die Arbeitsmappe gespeichert werden kann. Enthält die folgenden Formate: [`Dif`](./dif) , [`Fods`](./fods) , [`Ods`](./ods) , [`Sxc`](./sxc) , [`Xlam`](./xlam) , [`Xls`](./xls) , [`Xlsb`](./xlsb) , [`Xlsm`](./xlsm) , [`Xlsx`](./xlsx) , [`Xlt`](./xlt) , [`Xltm`](./xltm) , [`Xltx`](./xltx) . Erfahren Sie mehr über Tabellenkalkulationsformate[hier](https://wiki.fileformat.com/spreadsheet) .

```csharp
public struct SpreadsheetFormats : IDocumentFormat, IEquatable<SpreadsheetFormats>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/spreadsheetformats/extension) { get; } | Gibt eine Erweiterung (ohne führenden Punkt) dieses Spreadsheet-Formats in Kleinbuchstaben zurück |
| [Mime](../../groupdocs.editor.formats/spreadsheetformats/mime) { get; } | Gibt einen MIME-Code für dieses Format zurück |
| [Name](../../groupdocs.editor.formats/spreadsheetformats/name) { get; } | Gibt einen formalen vollständigen Namen dieses Tabellenkalkulationsformats zurück |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/spreadsheetformats/fromextension)(string) | Gibt eine Instanz von zurück[`SpreadsheetFormats`](../spreadsheetformats)Struktur, die der angegebenen Dateinamenerweiterung zugeordnet ist, oder löst eine Ausnahme aus, wenn die Erweiterung nicht richtig analysiert werden kann |
| [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals)(IDocumentFormat) | Bestimmt, ob diese Instanz gleich dem anderen angegebenen IDocumentFormat ist instance |
| override [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals_2)(object) | Bestimmt, ob diese Instanz gleich dem anderen angegebenen Objekt ist, das vermutlich ein geschachteltes SpreadsheetFormats ist |
| [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals_1)(SpreadsheetFormats) | Bestimmt, ob diese Instanz gleich den anderen angegebenen SpreadsheetFormats ist instance |
| override [GetHashCode](../../groupdocs.editor.formats/spreadsheetformats/gethashcode)() | Gibt einen Hash-Code zurück, der für diese Instanz unveränderlich ist |
| [operator ==](../../groupdocs.editor.formats/spreadsheetformats/op_equality) | Prüft zwei angegebene SpreadsheetFormats-Instanzen auf Gleichheit |
| [operator !=](../../groupdocs.editor.formats/spreadsheetformats/op_inequality) | Prüft zwei angegebene SpreadsheetFormats-Instanzen auf Ungleichheit |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [Csv](../../groupdocs.editor.formats/spreadsheetformats/csv) | CSV-Dokumente (Comma Separated Values) stellen einfachen Text dar, der Datensätze mit kommagetrennten Werten enthält. Jede Zeile in einer CSV-Datei ist ein neuer Datensatz aus der Gruppe von Datensätzen, die in der Datei enthalten sind. Erfahren Sie mehr über dieses Dateiformat[hier](https://docs.fileformat.com/spreadsheet/csv/) . |
| static readonly [Dif](../../groupdocs.editor.formats/spreadsheetformats/dif) | Datenaustauschformat (DIF) |
| static readonly [Fods](../../groupdocs.editor.formats/spreadsheetformats/fods) | Flat OpenDocument Spreadsheet (FODS) – gespeichert als einzelnes unkomprimiertes XML-Dokument |
| static readonly [Ods](../../groupdocs.editor.formats/spreadsheetformats/ods) | OpenDocument Spreadsheet (ODS) steht für OpenDocument Spreadsheet-Dokumentformat, das vom Benutzer bearbeitet werden kann. Daten werden in der ODF-Datei in Zeilen und Spalten gespeichert. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [SpreadsheetML](../../groupdocs.editor.formats/spreadsheetformats/spreadsheetml) | SpreadsheetML – Microsoft Office Excel 2002 und Excel 2003 XML-Format |
| static readonly [Sxc](../../groupdocs.editor.formats/spreadsheetformats/sxc) | StarOffice oder OpenOffice.org Calc XML-Tabelle (SXC) |
| static readonly [Tsv](../../groupdocs.editor.formats/spreadsheetformats/tsv) | Tab-Separated Values (TSV)-Dateiformat stellt durch Tabulatoren getrennte Daten im Nur-Text-Format dar. Das Dateiformat, ähnlich wie CSV, wird zur strukturierten Organisation von Daten verwendet, um sie zwischen verschiedenen Anwendungen zu importieren und zu exportieren. Erfahren Sie mehr über dieses Dateiformat[hier](https://docs.fileformat.com/spreadsheet/tsv/) . |
| static readonly [Xlam](../../groupdocs.editor.formats/spreadsheetformats/xlam) | Excel-Add-In (XLAM) |
| static readonly [Xls](../../groupdocs.editor.formats/spreadsheetformats/xls) | Excel 97-2003 Binary File Format (XLS) stellt Dateien dar, die von Microsoft Excel sowie anderen ähnlichen Tabellenkalkulationsprogrammen wie OpenOffice Calc oder Apple Numbers erstellt werden können. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [Xlsb](../../groupdocs.editor.formats/spreadsheetformats/xlsb) | Excel Binary Workbook (XLSB) gibt das Excel Binary File Format an, bei dem es sich um eine Sammlung von Datensätzen und Strukturen handelt, die den Inhalt von Excel-Arbeitsmappen angeben. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [Xlsm](../../groupdocs.editor.formats/spreadsheetformats/xlsm) | Office Open XML Workbook Macro-Enabled (XLSM) ist eine Art von Tabellenkalkulationsdatei, die Makros unterstützt. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [Xlsx](../../groupdocs.editor.formats/spreadsheetformats/xlsx) | Office Open XML Workbook Macro-Free (XLSX) stellt Dokumente dar, die von Microsoft mit der Veröffentlichung von Microsoft Office 2007 eingeführt wurden. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [Xlt](../../groupdocs.editor.formats/spreadsheetformats/xlt) | Excel 97-2003-Vorlage (XLT) stellt Vorlagendateien dar, die mit Microsoft Excel erstellt wurden, einer Tabellenkalkulationsanwendung, die Teil der Microsoft Office-Suite ist. Microsoft Office 97-2003 unterstützte das Erstellen neuer XLT-Dateien sowie das Öffnen dieser. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [Xltm](../../groupdocs.editor.formats/spreadsheetformats/xltm) | Office Open XML Template Macro-Enabled (XLTM) stellt Dateien dar, die von Microsoft Excel als Makro-aktivierte Vorlagendateien generiert werden. XLTM-Dateien ähneln XLTX in ihrer Struktur, abgesehen davon, dass letztere das Erstellen von Vorlagendateien mit Makros nicht unterstützen. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/spreadsheet/xltm) . |
| static readonly [Xltx](../../groupdocs.editor.formats/spreadsheetformats/xltx) | Die XLTX-Datei (Office Open XML Template Macro-Free) stellt eine Microsoft Excel-Vorlage dar, die auf den Office OpenXML-Dateiformatspezifikationen basiert. Es wird verwendet, um eine Standardvorlagendatei zu erstellen, die zum Generieren von XLSX-Dateien verwendet werden kann, die dieselben Einstellungen wie in der XLTX-Datei angegeben aufweisen. Erfahren Sie mehr über dieses Dateiformat[hier](https://wiki.fileformat.com/spreadsheet/xltx) . |
| static readonly [All](../../groupdocs.editor.formats/spreadsheetformats/all) | Gibt eine interne Klasse zurück, die aufzählbare Möglichkeiten über alle existierenden Spreadsheet-Formate bietet |

## Andere Mitglieder

| Name | Beschreibung |
| --- | --- |
| class [AllEnumerable](spreadsheetformats.allenumerable) | Implementiert die generische IEnumerable-Schnittstelle, die eine „Foreach“-Möglichkeit für das SpreadsheetFormats type ermöglicht |

### Siehe auch

* interface [IDocumentFormat](../idocumentformat)
* namensraum [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* Montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
