---
title: "FormatFamilies"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Representa las diferentes familias de formatos disponibles en el sistema."
type: docs
weight: 110
url: /es/net/groupdocs.editor.formats/formatfamilies/
---
## FormatFamilies class

Representa las diferentes familias de formatos disponibles en el sistema.

```csharp
public class FormatFamilies : FormatFamilyBase
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Obtiene el identificador único de la familia de formato. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Obtiene el nombre de la familia de formato. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Determina si esta instancia es igual a la instancia especificada de [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| override [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(object) | Determina si esta instancia es igual a la instancia especificada de [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/formatfamilybase/gethashcode)() | Devuelve un código hash para el objeto actual. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Devuelve una cadena que representa el objeto actual. |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [EBook](../../groupdocs.editor.formats/formatfamilies/ebook) | Representa la familia de formatos eBook. Obtén más información sobre el formato Mobi [aquí](https://docs.fileformat.com/ebook/mobi/), sobre el formato AZW3 [aquí](https://docs.fileformat.com/ebook/azw3/) y sobre el formato ePub [aquí](https://docs.fileformat.com/ebook/epub/). |
| static readonly [Email](../../groupdocs.editor.formats/formatfamilies/email) | Representa la familia de formatos de correo electrónico. Obtén más información sobre el formato de correos electrónicos [aquí](https://docs.fileformat.com/email/). |
| static readonly [FixedLayout](../../groupdocs.editor.formats/formatfamilies/fixedlayout) | Representa la familia de formatos de diseño fijo. Diversas aplicaciones de visualización o publicación de documentos permiten a los usuarios abrir (Adobe Acrobat, XPS Viewer) y, a veces, editar (Adobe InDesign) documentos de formatos específicos. Estas aplicaciones suelen generar los llamados documentos de formato “página fija”. Este tipo de formato de documento describe con precisión dónde se coloca el contenido del documento en cada página. Internamente, el formato PDF o XPS contiene una descripción de cada página, así como instrucciones de dibujo que especifican la disposición del contenido en la página. Esto es similar a los formatos de imagen, que describen dónde se muestra el contenido, ya sea en forma raster o vectorial. |
| static readonly [Presentation](../../groupdocs.editor.formats/formatfamilies/presentation) | Representa la familia de formatos de presentación. Obtén más información sobre los formatos de presentación [aquí](https://wiki.fileformat.com/presentation). |
| static readonly [Spreadsheet](../../groupdocs.editor.formats/formatfamilies/spreadsheet) | Representa la familia de formatos de hoja de cálculo. Todos los formatos de hoja de cálculo binarios, XML y textuales (excluyendo todos los formatos basados en delimitadores textuales con separadores como CSV, TSV, delimitados por punto y coma, etc.) en los que se puede guardar el libro de trabajo. |
| static readonly [Textual](../../groupdocs.editor.formats/formatfamilies/textual) | Representa la familia de formatos textuales. Agrupa todos los formatos textuales (basados en texto), incluidos los de marcado (XML, HTML) y otros. |
| static readonly [WordProcessing](../../groupdocs.editor.formats/formatfamilies/wordprocessing) | Representa la familia de formatos de procesamiento de texto. Obtén más información sobre los formatos de procesamiento de texto [aquí](https://wiki.fileformat.com/word-processing). |

### Ver también

* class [FormatFamilyBase](../../groupdocs.editor.formats.abstraction/formatfamilybase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
