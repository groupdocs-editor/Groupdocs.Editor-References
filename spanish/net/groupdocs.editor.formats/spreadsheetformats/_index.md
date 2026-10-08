---
title: "SpreadsheetFormats"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Encapsula todos los formatos binarios XML y textuales de hoja de cálculo, excluyendo todos los formatos textuales basados en delimitadores con separadores como CSV, TSV, delimitados por punto y coma, etc., en los que se puede guardar el libro de trabajo. Incluye los siguientes formatos Xls./spreadsheetformats/xls Xlt./spreadsheetformats/xlt Xlsx./spreadsheetformats/xlsx Xlsm./spreadsheetformats/xlsm Xlsb./spreadsheetformats/xlsb Xltx./spreadsheetformats/xltx Xltm./spreadsheetformats/xltm Xlam./spreadsheetformats/xlam SpreadsheetML./spreadsheetformats/spreadsheetml Ods./spreadsheetformats/ods Fods./spreadsheetformats/fods Sxc./spreadsheetformats/sxc Dif./spreadsheetformats/dif Csv./spreadsheetformats/csv Tsv./spreadsheetformats/tsv. Obtén más información sobre los formatos de hoja de cálculo aquíhttps//wiki.fileformat.com/spreadsheet."
type: docs
weight: 130
url: /es/net/groupdocs.editor.formats/spreadsheetformats/
---
## SpreadsheetFormats class

Encapsula todos los formatos binarios, XML y textuales de hoja de cálculo (excluyendo todos los formatos textuales basados en delimitadores con separadores como CSV, TSV, delimitados por punto y coma, etc.) en los que se puede guardar el libro de trabajo. Incluye los siguientes formatos: [`Xls`](./xls), [`Xlt`](./xlt), [`Xlsx`](./xlsx), [`Xlsm`](./xlsm), [`Xlsb`](./xlsb), [`Xltx`](./xltx), [`Xltm`](./xltm), [`Xlam`](./xlam), [`SpreadsheetML`](./spreadsheetml), [`Ods`](./ods), [`Fods`](./fods), [`Sxc`](./sxc), [`Dif`](./dif), [`Csv`](./csv), [`Tsv`](./tsv). Obtén más información sobre los formatos de hoja de cálculo [aquí](https://wiki.fileformat.com/spreadsheet).

```csharp
public class SpreadsheetFormats : DocumentFormatBase
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Obtiene la extensión de archivo del formato de documento. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Obtiene la familia de formato a la que pertenece el formato de documento. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Obtiene el identificador único de la familia de formato. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Obtiene el tipo MIME del formato de documento. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Obtiene el nombre de la familia de formato. |
| static [All](../../groupdocs.editor.formats/spreadsheetformats/all) { get; } | Obtiene una colección enumerable de todos los [`SpreadsheetFormats`](../spreadsheetformats). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/spreadsheetformats/fromextension)(string) | Recupera una instancia del tipo especificado [`SpreadsheetFormats`](../spreadsheetformats) que tiene la extensión de archivo especificada. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Determina si esta instancia es igual a la instancia especificada de [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Determina si esta instancia es igual a la instancia especificada de [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Determina si esta instancia es igual a la instancia especificada de [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Devuelve un código hash para el objeto actual. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Devuelve una cadena que representa el objeto actual. |
| [explicit operator](../../groupdocs.editor.formats/spreadsheetformats/op_explicit) | Convierte una cadena que representa una extensión de archivo a un objeto [`SpreadsheetFormats`](../spreadsheetformats). |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Csv](../../groupdocs.editor.formats/spreadsheetformats/csv) | Valores separados por comas (CSV). Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/spreadsheet/csv/). |
| static readonly [Dif](../../groupdocs.editor.formats/spreadsheetformats/dif) | Formato de Intercambio de Datos (DIF). |
| static readonly [Fods](../../groupdocs.editor.formats/spreadsheetformats/fods) | Hoja de cálculo OpenDocument plana (FODS). |
| static readonly [Ods](../../groupdocs.editor.formats/spreadsheetformats/ods) | Hoja de cálculo OpenDocument (ODS). Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/spreadsheet/ods). |
| static readonly [SpreadsheetML](../../groupdocs.editor.formats/spreadsheetformats/spreadsheetml) | SpreadsheetML — Formato XML de Microsoft Office Excel 2002 y Excel 2003. |
| static readonly [Sxc](../../groupdocs.editor.formats/spreadsheetformats/sxc) | Hoja de cálculo XML de StarOffice o OpenOffice.org Calc (SXC). |
| static readonly [Tsv](../../groupdocs.editor.formats/spreadsheetformats/tsv) | Valores separados por tabulaciones (TSV). Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/spreadsheet/tsv/). |
| static readonly [Xlam](../../groupdocs.editor.formats/spreadsheetformats/xlam) | Complemento de Excel (XLAM). |
| static readonly [Xls](../../groupdocs.editor.formats/spreadsheetformats/xls) | Formato de archivo binario de Excel 97-2003 (XLS). Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/spreadsheet/xls). |
| static readonly [Xlsb](../../groupdocs.editor.formats/spreadsheetformats/xlsb) | Libro de trabajo binario de Excel (XLSB). Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/spreadsheet/xlsb). |
| static readonly [Xlsm](../../groupdocs.editor.formats/spreadsheetformats/xlsm) | Libro de trabajo Office Open XML con macros habilitadas (XLSM). Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/spreadsheet/xlsm). |
| static readonly [Xlsx](../../groupdocs.editor.formats/spreadsheetformats/xlsx) | Libro de trabajo Office Open XML sin macros (XLSX). Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/spreadsheet/xlsx). |
| static readonly [Xlt](../../groupdocs.editor.formats/spreadsheetformats/xlt) | Plantilla de Excel 97-2003 (XLT). Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/spreadsheet/xlt). |
| static readonly [Xltm](../../groupdocs.editor.formats/spreadsheetformats/xltm) | Plantilla Office Open XML con macros habilitadas (XLTM). Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/spreadsheet/xltm). |
| static readonly [Xltx](../../groupdocs.editor.formats/spreadsheetformats/xltx) | Plantilla Office Open XML sin macros (XLTX). Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/spreadsheet/xltx). |

### Ver también

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
