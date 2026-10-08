---
title: "WordProcessingFormats"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Encapsula todos los formatos de procesamiento de texto. Incluye los siguientes tipos de archivo"
type: docs
weight: 150
url: /es/net/groupdocs.editor.formats/wordprocessingformats/
---
## WordProcessingFormats class

Encapsula todos los formatos de procesamiento de texto. Incluye los siguientes tipos de archivo:

* [`Doc`](./doc)
* [`Docm`](./docm)
* [`Docx`](./docx)
* [`Dot`](./dot)
* [`Dotm`](./dotm)
* [`Dotx`](./dotx)
* [`FlatOpc`](./flatopc)
* [`Odt`](./odt)
* [`Ott`](./ott)
* [`Rtf`](./rtf)
* [`WordML`](./wordml)

Obtén más información sobre los formatos de procesamiento de texto [aquí](https://wiki.fileformat.com/word-processing).

```csharp
public class WordProcessingFormats : DocumentFormatBase
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Obtiene la extensión de archivo del formato de documento. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Obtiene la familia de formato a la que pertenece el formato de documento. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Obtiene el identificador único de la familia de formato. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Obtiene el tipo MIME del formato de documento. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Obtiene el nombre de la familia de formato. |
| static [All](../../groupdocs.editor.formats/wordprocessingformats/all) { get; } | Obtiene una colección enumerable de todos los [`WordProcessingFormats`](../wordprocessingformats). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/wordprocessingformats/fromextension)(string) | Recupera una instancia del tipo especificado [`WordProcessingFormats`](../wordprocessingformats) que tiene la extensión de archivo especificada. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Determina si esta instancia es igual a la instancia especificada de [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Determina si esta instancia es igual a la instancia especificada de [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Determina si esta instancia es igual a la instancia especificada de [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Devuelve un código hash para el objeto actual. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Devuelve una cadena que representa el objeto actual. |
| [explicit operator](../../groupdocs.editor.formats/wordprocessingformats/op_explicit) | Convierte una cadena que representa una extensión de archivo a un objeto [`WordProcessingFormats`](../wordprocessingformats). |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Doc](../../groupdocs.editor.formats/wordprocessingformats/doc) | El formato de archivo binario de MS Word 97-2007 (DOC) representa documentos generados por Microsoft Word u otros documentos de procesamiento de texto en formato binario. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/word-processing/doc). |
| static readonly [Docm](../../groupdocs.editor.formats/wordprocessingformats/docm) | Los archivos Office Open XML WordProcessingML Macro-Enabled Document (DOCM) son documentos generados por Microsoft Word 2007 o superior con la capacidad de ejecutar macros. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/word-processing/docm). |
| static readonly [Docx](../../groupdocs.editor.formats/wordprocessingformats/docx) | Office Open XML WordProcessingML Macro-Free Document (DOCX) es un formato bien conocido para documentos de Microsoft Word. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/word-processing/docx). |
| static readonly [Dot](../../groupdocs.editor.formats/wordprocessingformats/dot) | MS Word 97-2007 Template (DOT) son archivos de plantilla creados por Microsoft Word para tener configuraciones preformateadas para la generación de futuros archivos DOC o DOCX. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/word-processing/dot). |
| static readonly [Dotm](../../groupdocs.editor.formats/wordprocessingformats/dotm) | Office Open XML WordprocessingML Macro-Enabled Template (DOTM) representa archivos de plantilla creados con Microsoft Word 2007 o superior. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/word-processing/dotm). |
| static readonly [Dotx](../../groupdocs.editor.formats/wordprocessingformats/dotx) | Office Open XML WordprocessingML Macro-Free Template (DOTX) son archivos de plantilla creados por Microsoft Word para tener configuraciones preformateadas para la generación de futuros archivos DOCX. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/word-processing/dotx). |
| static readonly [FlatOpc](../../groupdocs.editor.formats/wordprocessingformats/flatopc) | Office Open XML WordprocessingML almacenado en un archivo XML plano en lugar de un paquete ZIP. |
| static readonly [Odt](../../groupdocs.editor.formats/wordprocessingformats/odt) | Los archivos Open Document Format Text Document (ODT) son un tipo de documentos creados con aplicaciones de procesamiento de texto basadas en el formato de archivo OpenDocument Text. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/word-processing/odt). |
| static readonly [Ott](../../groupdocs.editor.formats/wordprocessingformats/ott) | Open Document Format Text Document Template (OTT) representa documentos de plantilla generados por aplicaciones que cumplen con el formato estándar OpenDocument de OASIS. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/word-processing/ott). |
| static readonly [Rtf](../../groupdocs.editor.formats/wordprocessingformats/rtf) | Rich Text Format (RTF) representa un método de codificación de texto formateado y gráficos para su uso dentro de aplicaciones. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/word-processing/rtf). |
| static readonly [WordML](../../groupdocs.editor.formats/wordprocessingformats/wordml) | Microsoft Office Word 2003 XML Format — WordProcessingML o WordML (.XML). |

### Ver también

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
