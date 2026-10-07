---
title: "SpreadsheetFormats"
second_title: "GroupDocs.Editor für .NET API-Referenz"
description: "Fasst alle binären XML- und textuellen Tabellenkalkulationsformate zusammen, ausgenommen alle textbasierten, durch Trennzeichen getrennten Formate mit Separatoren wie CSV, TSV, semikolonbegrenzte usw., in denen die Arbeitsmappe gespeichert werden kann. Enthält die folgenden Formate Xls./spreadsheetformats/xls Xlt./spreadsheetformats/xlt Xlsx./spreadsheetformats/xlsx Xlsm./spreadsheetformats/xlsm Xlsb./spreadsheetformats/xlsb Xltx./spreadsheetformats/xltx Xltm./spreadsheetformats/xltm Xlam./spreadsheetformats/xlam SpreadsheetML./spreadsheetformats/spreadsheetml Ods./spreadsheetformats/ods Fods./spreadsheetformats/fods Sxc./spreadsheetformats/sxc Dif./spreadsheetformats/dif Csv./spreadsheetformats/csv Tsv./spreadsheetformats/tsv. Erfahren Sie mehr über Tabellenkalkulationsformate hierhttps//wiki.fileformat.com/spreadsheet."
type: docs
weight: 130
url: /de/net/groupdocs.editor.formats/spreadsheetformats/
---
## SpreadsheetFormats class

Fasst alle binären, XML- und textuellen Tabellenkalkulationsformate zusammen (ausgenommen alle textbasierten, durch Trennzeichen getrennten Formate mit Separatoren wie CSV, TSV, semikolonbegrenzte usw.), in denen die Arbeitsmappe gespeichert werden kann. Enthält die folgenden Formate: [`Xls`](./xls), [`Xlt`](./xlt), [`Xlsx`](./xlsx), [`Xlsm`](./xlsm), [`Xlsb`](./xlsb), [`Xltx`](./xltx), [`Xltm`](./xltm), [`Xlam`](./xlam), [`SpreadsheetML`](./spreadsheetml), [`Ods`](./ods), [`Fods`](./fods), [`Sxc`](./sxc), [`Dif`](./dif), [`Csv`](./csv), [`Tsv`](./tsv). Erfahren Sie mehr über Tabellenkalkulationsformate [hier](https://wiki.fileformat.com/spreadsheet).

```csharp
public class SpreadsheetFormats : DocumentFormatBase
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Ermittelt die Dateierweiterung des Dokumentformats. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Ermittelt die Formatfamilie, zu der das Dokumentformat gehört. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Ermittelt die eindeutige Kennung für die Formatfamilie. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Ermittelt den MIME-Typ des Dokumentformats. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Ermittelt den Namen der Formatfamilie. |
| static [All](../../groupdocs.editor.formats/spreadsheetformats/all) { get; } | Gibt eine aufzählbare Sammlung aller [`SpreadsheetFormats`](../spreadsheetformats) zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/spreadsheetformats/fromextension)(string) | Ruft eine Instanz des angegebenen Typs [`SpreadsheetFormats`](../spreadsheetformats) ab, die die angegebene Dateierweiterung besitzt. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Bestimmt, ob diese Instanz gleich der angegebenen [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase)-Instanz ist. |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Bestimmt, ob diese Instanz gleich der angegebenen [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat)-Instanz ist. |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Bestimmt, ob diese Instanz gleich der angegebenen [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase)-Instanz ist. |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Gibt einen Hashcode für das aktuelle Objekt zurück. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Gibt eine Zeichenkette zurück, die das aktuelle Objekt darstellt. |
| [explicit operator](../../groupdocs.editor.formats/spreadsheetformats/op_explicit) | Konvertiert einen String, der eine Dateierweiterung darstellt, in ein [`SpreadsheetFormats`](../spreadsheetformats)-Objekt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [Csv](../../groupdocs.editor.formats/spreadsheetformats/csv) | Kommagetrennte Werte (CSV). Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/spreadsheet/csv/). |
| static readonly [Dif](../../groupdocs.editor.formats/spreadsheetformats/dif) | Datenaustauschformat (DIF). |
| static readonly [Fods](../../groupdocs.editor.formats/spreadsheetformats/fods) | Flaches OpenDocument-Tabellenkalkulationsformat (FODS). |
| static readonly [Ods](../../groupdocs.editor.formats/spreadsheetformats/ods) | OpenDocument-Tabellenkalkulation (ODS). Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/spreadsheet/ods). |
| static readonly [SpreadsheetML](../../groupdocs.editor.formats/spreadsheetformats/spreadsheetml) | SpreadsheetML — Microsoft Office Excel 2002 und Excel 2003 XML-Format. |
| static readonly [Sxc](../../groupdocs.editor.formats/spreadsheetformats/sxc) | StarOffice- oder OpenOffice.org Calc XML-Tabellenkalkulation (SXC). |
| static readonly [Tsv](../../groupdocs.editor.formats/spreadsheetformats/tsv) | Tabulatorgetrennte Werte (TSV). Erfahren Sie mehr über dieses Dateiformat [hier](https://docs.fileformat.com/spreadsheet/tsv/). |
| static readonly [Xlam](../../groupdocs.editor.formats/spreadsheetformats/xlam) | Excel-Add-In (XLAM). |
| static readonly [Xls](../../groupdocs.editor.formats/spreadsheetformats/xls) | Excel 97-2003 Binärdateiformat (XLS). Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/spreadsheet/xls). |
| static readonly [Xlsb](../../groupdocs.editor.formats/spreadsheetformats/xlsb) | Excel-Binärarbeitsmappe (XLSB). Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/spreadsheet/xlsb). |
| static readonly [Xlsm](../../groupdocs.editor.formats/spreadsheetformats/xlsm) | Office Open XML-Arbeitsmappe mit Makros (XLSM). Erfahren Sie mehr über dieses Dateiformat [hier](https://wiki.fileformat.com/spreadsheet/xlsm). |
| static readonly [Xlsx](../../groupdocs.editor.formats/spreadsheetformats/xlsx) | Office Open XML-Arbeitsmappe ohne Makros (XLSX). Erfahren Sie mehr über dieses Dateiformat [here](https://wiki.fileformat.com/spreadsheet/xlsx). |
| static readonly [Xlt](../../groupdocs.editor.formats/spreadsheetformats/xlt) | Excel 97-2003-Vorlage (XLT). Erfahren Sie mehr über dieses Dateiformat [here](https://wiki.fileformat.com/spreadsheet/xlt). |
| static readonly [Xltm](../../groupdocs.editor.formats/spreadsheetformats/xltm) | Office Open XML-Vorlage mit Makros (XLTM). Erfahren Sie mehr über dieses Dateiformat [here](https://wiki.fileformat.com/spreadsheet/xltm). |
| static readonly [Xltx](../../groupdocs.editor.formats/spreadsheetformats/xltx) | Office Open XML-Vorlage ohne Makros (XLTX). Erfahren Sie mehr über dieses Dateiformat [here](https://wiki.fileformat.com/spreadsheet/xltx). |

### Siehe auch

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
