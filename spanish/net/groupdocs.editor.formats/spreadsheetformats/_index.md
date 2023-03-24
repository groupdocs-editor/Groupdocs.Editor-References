---
title: SpreadsheetFormats
second_title: Referencia de API de GroupDocs.Editor para .NET
description: Encapsula todos los formatos binarios XML y de hojas de cálculo textuales excluyendo todos los formatos textuales basados en delimitadores con separadores como CSV TSV delimitados por punto y coma etc. en los que se puede guardar el libro de trabajo. Incluye los siguientes formatos Dif./spreadsheetformats/dif  Fods./spreadsheetformats/fods  Ods./spreadsheetformats/ods  Sxc./spreadsheetformats/sxc  Xlam./spreadsheetformats/xlam  Xls./spreadsheetformats/xls  Xlsb./spreadsheetformats/xlsb  Xlsm./spreadsheetformats/xlsm  Xlsx./spreadsheetformats/xlsx  Xlt./spreadsheetformats/xlt  Xltm./spreadsheetformats/xltm  Xltx./spreadsheetformats/xltx . Obtenga más información sobre los formatos de hoja de cálculoaquíhttps//wiki.fileformat.com/spreadsheet .
type: docs
weight: 130
url: /es/net/groupdocs.editor.formats/spreadsheetformats/
---
## SpreadsheetFormats structure

Encapsula todos los formatos binarios, XML y de hojas de cálculo textuales (excluyendo todos los formatos textuales basados en delimitadores con separadores como CSV, TSV, delimitados por punto y coma, etc.), en los que se puede guardar el libro de trabajo. Incluye los siguientes formatos: [`Dif`](./dif) , [`Fods`](./fods) , [`Ods`](./ods) , [`Sxc`](./sxc) , [`Xlam`](./xlam) , [`Xls`](./xls) , [`Xlsb`](./xlsb) , [`Xlsm`](./xlsm) , [`Xlsx`](./xlsx) , [`Xlt`](./xlt) , [`Xltm`](./xltm) , [`Xltx`](./xltx) . Obtenga más información sobre los formatos de hoja de cálculo[aquí](https://wiki.fileformat.com/spreadsheet) .

```csharp
public struct SpreadsheetFormats : IDocumentFormat, IEquatable<SpreadsheetFormats>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/spreadsheetformats/extension) { get; } | Devuelve una extensión (sin carácter de punto inicial) de este formato de hoja de cálculo en minúsculas |
| [Mime](../../groupdocs.editor.formats/spreadsheetformats/mime) { get; } | Devuelve un código MIME para este formato |
| [Name](../../groupdocs.editor.formats/spreadsheetformats/name) { get; } | Devuelve un nombre completo formal de este formato de hoja de cálculo |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/spreadsheetformats/fromextension)(string) | Devuelve instancia de[`SpreadsheetFormats`](../spreadsheetformats) estructura, asociada a la extensión de nombre de archivo especificada, o genera una excepción, si la extensión no se puede analizar correctamente |
| [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals)(IDocumentFormat) | Determina si esta instancia es igual a la otra instancia de IDocumentFormat especificada |
| override [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals_2)(object) | Determina si esta instancia es igual al otro objeto especificado, que presumiblemente es de SpreadsheetFormats en caja |
| [Equals](../../groupdocs.editor.formats/spreadsheetformats/equals#equals_1)(SpreadsheetFormats) | Determina si esta instancia es igual a la otra instancia de SpreadsheetFormats especificada |
| override [GetHashCode](../../groupdocs.editor.formats/spreadsheetformats/gethashcode)() | Devuelve un código hash, que es inmutable para esta instancia |
| [operator ==](../../groupdocs.editor.formats/spreadsheetformats/op_equality) | Comprueba dos instancias dadas de SpreadsheetFormats en igualdad |
| [operator !=](../../groupdocs.editor.formats/spreadsheetformats/op_inequality) | Comprueba dos instancias dadas de SpreadsheetFormats en desigualdad |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Csv](../../groupdocs.editor.formats/spreadsheetformats/csv) | Los documentos de valores separados por comas (CSV) representan texto sin formato que contienen registros de datos con valores separados por comas. Cada línea en un archivo CSV es un nuevo registro del conjunto de registros contenidos en el archivo. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/spreadsheet/csv/) . |
| static readonly [Dif](../../groupdocs.editor.formats/spreadsheetformats/dif) | Formato de intercambio de datos (DIF) |
| static readonly [Fods](../../groupdocs.editor.formats/spreadsheetformats/fods) | Hoja de cálculo OpenDocument plana (FODS): almacenada como un único documento XML sin comprimir |
| static readonly [Ods](../../groupdocs.editor.formats/spreadsheetformats/ods) | Hoja de cálculo OpenDocument (ODS) significa formato de documento de hoja de cálculo OpenDocument que puede editar el usuario. Los datos se almacenan dentro del archivo ODF en filas y columnas. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/spreadsheet/ods) . |
| static readonly [SpreadsheetML](../../groupdocs.editor.formats/spreadsheetformats/spreadsheetml) | SpreadsheetML: formato XML de Microsoft Office Excel 2002 y Excel 2003 |
| static readonly [Sxc](../../groupdocs.editor.formats/spreadsheetformats/sxc) | StarOffice u OpenOffice.org Calcular hoja de cálculo XML (SXC) |
| static readonly [Tsv](../../groupdocs.editor.formats/spreadsheetformats/tsv) | El formato de archivo de valores separados por tabulaciones (TSV) representa datos separados por tabulaciones en formato de texto sin formato. El formato de archivo, similar a CSV, se utiliza para la organización de datos de forma estructurada con el fin de importar y exportar entre diferentes aplicaciones. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/spreadsheet/tsv/) . |
| static readonly [Xlam](../../groupdocs.editor.formats/spreadsheetformats/xlam) | Complemento de Excel (XLAM) |
| static readonly [Xls](../../groupdocs.editor.formats/spreadsheetformats/xls) | El formato de archivo binario (XLS) de Excel 97-2003 representa archivos que se pueden crear con Microsoft Excel, así como con otros programas de hojas de cálculo similares, como OpenOffice Calc o Apple Numbers. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/spreadsheet/xls) . |
| static readonly [Xlsb](../../groupdocs.editor.formats/spreadsheetformats/xlsb) | Libro binario de Excel (XLSB) especifica el formato de archivo binario de Excel, que es una colección de registros y estructuras que especifican el contenido del libro de Excel. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/spreadsheet/xlsb) . |
| static readonly [Xlsm](../../groupdocs.editor.formats/spreadsheetformats/xlsm) | Office Open XML Workbook Macro-Enabled (XLSM) es un tipo de archivo de hoja de cálculo que admite macros. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/spreadsheet/xlsm) . |
| static readonly [Xlsx](../../groupdocs.editor.formats/spreadsheetformats/xlsx) | Office Open XML Workbook Macro-Free (XLSX) representa documentos introducidos por Microsoft con el lanzamiento de Microsoft Office 2007. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/spreadsheet/xlsx) . |
| static readonly [Xlt](../../groupdocs.editor.formats/spreadsheetformats/xlt) | Plantilla de Excel 97-2003 (XLT) representa archivos de plantilla creados con Microsoft Excel, que es una aplicación de hoja de cálculo que forma parte del paquete Microsoft Office. Microsoft Office 97-2003 admitía la creación de nuevos archivos XLT y su apertura. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/spreadsheet/xlt) . |
| static readonly [Xltm](../../groupdocs.editor.formats/spreadsheetformats/xltm) | Plantilla XML abierta de Office habilitada para macros (XLTM) representa archivos generados por Microsoft Excel como archivos de plantilla habilitados para macros. Los archivos XLTM son similares a XLTX en estructura, excepto que el último no admite la creación de archivos de plantilla con macros. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/spreadsheet/xltm) . |
| static readonly [Xltx](../../groupdocs.editor.formats/spreadsheetformats/xltx) | El archivo de plantilla XML abierta de Office sin macros (XLTX) representa la plantilla de Microsoft Excel que se basa en las especificaciones de formato de archivo OpenXML de Office. Se utiliza para crear un archivo de plantilla estándar que se puede utilizar para generar archivos XLSX que muestren la misma configuración que se especifica en el archivo XLTX. Obtenga más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/spreadsheet/xltx) . |
| static readonly [All](../../groupdocs.editor.formats/spreadsheetformats/all) | Devuelve una clase interna que proporciona posibilidades enumerables sobre todos los formatos de hoja de cálculo existentes |

## Otros miembros

| Nombre | Descripción |
| --- | --- |
| class [AllEnumerable](spreadsheetformats.allenumerable) | Implementa la interfaz genérica IEnumerable, que permite una posibilidad 'foreach' para los formatos de hoja de cálculo tipo |

### Ver también

* interface [IDocumentFormat](../idocumentformat)
* espacio de nombres [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* asamblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
