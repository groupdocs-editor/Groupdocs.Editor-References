---
title: WordProcessingFormats
second_title: Referencia de API de GroupDocs.Editor para .NET
description: Encapsula todos los formatos de procesamiento de textos. Incluye los siguientes tipos de archivo Doc./wordprocessingformats/doc  Docm./wordprocessingformats/docm  Docx./wordprocessingformats/docx  Dot./wordprocessingformats/dot  Dotm./wordprocessingformats/dotm  Dotx./wordprocessingformats/dotx  FlatOpc./wordprocessingformats/flatopc  Odt./wordprocessingformats/odt  Ott./wordprocessingformats/ott  Rtf./wordprocessingformats/rtf  WordML./wordprocessingformats/wordml . Obtenga más información sobre los formatos de procesamiento de textosaquíhttps//wiki.fileformat.com/wordprocessing .
type: docs
weight: 170
url: /es/net/groupdocs.editor.formats/wordprocessingformats/
---
## WordProcessingFormats structure

Encapsula todos los formatos de procesamiento de textos. Incluye los siguientes tipos de archivo: [`Doc`](./doc) , [`Docm`](./docm) , [`Docx`](./docx) , [`Dot`](./dot) , [`Dotm`](./dotm) , [`Dotx`](./dotx) , [`FlatOpc`](./flatopc) , [`Odt`](./odt) , [`Ott`](./ott) , [`Rtf`](./rtf) , [`WordML`](./wordml) . Obtenga más información sobre los formatos de procesamiento de textos[aquí](https://wiki.fileformat.com/word-processing) .

```csharp
public struct WordProcessingFormats : IDocumentFormat, IEquatable<WordProcessingFormats>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/wordprocessingformats/extension) { get; } | Devuelve una extensión (sin carácter de punto inicial) de este formato de procesamiento de textos en minúsculas |
| [Mime](../../groupdocs.editor.formats/wordprocessingformats/mime) { get; } | Devuelve un código MIME para este formato |
| [Name](../../groupdocs.editor.formats/wordprocessingformats/name) { get; } | Devuelve un nombre completo formal de este formato de procesamiento de textos |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/wordprocessingformats/fromextension)(string) | Devuelve instancia de[`WordProcessingFormats`](../wordprocessingformats)estructura, asociada a la extensión de nombre de archivo especificada, o genera una excepción, si la extensión no se puede analizar correctamente |
| [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals)(IDocumentFormat) | Determina si esta instancia es igual a la otra instancia de IDocumentFormat especificada |
| override [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals_2)(object) | Determina si esta instancia es igual al otro objeto especificado, que presumiblemente es de WordProcessingFormats en caja |
| [Equals](../../groupdocs.editor.formats/wordprocessingformats/equals#equals_1)(WordProcessingFormats) | Determina si esta instancia es igual a la otra instancia de WordProcessingFormats especificada |
| override [GetHashCode](../../groupdocs.editor.formats/wordprocessingformats/gethashcode)() | Devuelve un código hash, que es inmutable para esta instancia |
| override [ToString](../../groupdocs.editor.formats/wordprocessingformats/tostring)() | Devuelve el nombre de este formato en particular, igual que la propiedad 'Nombre' |
| [operator ==](../../groupdocs.editor.formats/wordprocessingformats/op_equality) | Comprueba dos instancias dadas de WordProcessingFormats en igualdad |
| [explicit operator](../../groupdocs.editor.formats/wordprocessingformats/op_explicit#op_explicit) | Devuelve un valor de byte del campo subyacente de la instancia de WordProcessingFormats especificada (2 operators) |
| [operator !=](../../groupdocs.editor.formats/wordprocessingformats/op_inequality) | Comprueba dos instancias dadas de WordProcessingFormats en desigualdad |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Doc](../../groupdocs.editor.formats/wordprocessingformats/doc) | El formato de archivo binario (DOC) de MS Word 97-2007 representa documentos generados por Microsoft Word u otros documentos de procesamiento de texto en formato de archivo binario. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/word-processing/doc) . |
| static readonly [Docm](../../groupdocs.editor.formats/wordprocessingformats/docm) | Los archivos Office Open XML WordProcessingML Macro-Enabled Document (DOCM) son documentos generados por Microsoft Word 2007 o superior con la capacidad de ejecutar macros. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/word-processing/docm) . |
| static readonly [Docx](../../groupdocs.editor.formats/wordprocessingformats/docx) | Office Open XML WordProcessingML Macro-Free Document (DOCX) es un formato muy conocido para documentos de Microsoft Word. Introducido a partir de 2007 con el lanzamiento de Microsoft Office 2007, la estructura de este nuevo formato de documento se cambió de binario simple a una combinación de XML y archivos binarios. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/word-processing/docx) . |
| static readonly [Dot](../../groupdocs.editor.formats/wordprocessingformats/dot) | Plantilla de MS Word 97-2007 son archivos de plantilla creados por Microsoft Word para tener configuraciones preformateadas para la generación de más archivos DOC o DOCX. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/word-processing/dot) . |
| static readonly [Dotm](../../groupdocs.editor.formats/wordprocessingformats/dotm) | Office Open XML WordprocessingML Macro-Enabled Template (DOTM) representa un archivo de plantilla creado con Microsoft Word 2007 o superior. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/word-processing/dotm) . |
| static readonly [Dotx](../../groupdocs.editor.formats/wordprocessingformats/dotx) | Office Open XML WordprocessingML Macro-Free Template (DOTX) son archivos de plantilla creados por Microsoft Word para tener configuraciones preformateadas para la generación de más archivos DOCX. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/word-processing/dotx) . |
| static readonly [FlatOpc](../../groupdocs.editor.formats/wordprocessingformats/flatopc) | Office Open XML WordprocessingML almacenado en un archivo XML sin formato en lugar de un paquete ZIP |
| static readonly [Odt](../../groupdocs.editor.formats/wordprocessingformats/odt) | Los archivos de documento de texto en formato de documento abierto (ODT) son un tipo de documentos creados con aplicaciones de procesamiento de textos que se basan en el formato de archivo de texto OpenDocument. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/word-processing/odt) . |
| static readonly [Ott](../../groupdocs.editor.formats/wordprocessingformats/ott) | Formato de documento abierto Plantilla de documento de texto (OTT) representa documentos de plantilla generados por aplicaciones de conformidad con el formato estándar OpenDocument de OASIS. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/word-processing/ott) . |
| static readonly [Rtf](../../groupdocs.editor.formats/wordprocessingformats/rtf) | El formato de texto enriquecido (RTF) representa un método de codificación de texto y gráficos con formato para su uso dentro de las aplicaciones. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/word-processing/rtf) . |
| static readonly [WordML](../../groupdocs.editor.formats/wordprocessingformats/wordml) | Formato XML de Microsoft Office Word 2003: WordProcessingML o WordML (.XML) |
| static readonly [All](../../groupdocs.editor.formats/wordprocessingformats/all) | Devuelve una clase interna que proporciona posibilidades enumerables sobre todos los formatos de procesamiento de textos existentes |

## Otros miembros

| Nombre | Descripción |
| --- | --- |
| class [AllEnumerable](wordprocessingformats.allenumerable) | Implementa la interfaz genérica IEnumerable, que habilita una posibilidad 'foreach' para el tipo WordProcessingFormats |

### Observaciones

Los códigos MIME se toman de los recursos proporcionados: https://filext.com/faq/office_mime_types.html https://docs.microsoft.com/en-us/previous-versions//cc179224(v=technet.10)

### Ver también

* interface [IDocumentFormat](../idocumentformat)
* espacio de nombres [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* asamblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
