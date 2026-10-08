---
title: "TextualFormats"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Encapsula todos los formatos textuales basados en texto, incluidos los de marcado XML HTML y otros. Incluye los siguientes formatos Html./textualformats/html Txt./textualformats/txt Xml./textualformats/xml Md./textualformats/md Json./textualformats/json Mhtml./textualformats/mhtml Chm./textualformats/chm."
type: docs
weight: 140
url: /es/net/groupdocs.editor.formats/textualformats/
---
## TextualFormats class

Encapsula todos los formatos textuales (basados en texto), incluidos los de marcado (XML, HTML) y otros. Incluye los siguientes formatos: [`Html`](./html), [`Txt`](./txt), [`Xml`](./xml), [`Md`](./md), [`Json`](./json), [`Mhtml`](./mhtml), [`Chm`](./chm).

```csharp
public class TextualFormats : DocumentFormatBase
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Obtiene la extensión de archivo del formato de documento. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Obtiene la familia de formato a la que pertenece el formato de documento. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Obtiene el identificador único de la familia de formato. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Obtiene el tipo MIME del formato de documento. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Obtiene el nombre de la familia de formato. |
| static [All](../../groupdocs.editor.formats/textualformats/all) { get; } | Obtiene una colección enumerable de todos los [`TextualFormats`](../textualformats). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/textualformats/fromextension)(string) | Recupera una instancia del tipo especificado [`TextualFormats`](../textualformats) que tiene la extensión de archivo especificada. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Determina si esta instancia es igual a la instancia especificada de [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Determina si esta instancia es igual a la instancia especificada de [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Determina si esta instancia es igual a la instancia especificada de [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Devuelve un código hash para el objeto actual. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Devuelve una cadena que representa el objeto actual. |
| [explicit operator](../../groupdocs.editor.formats/textualformats/op_explicit) | Convierte una cadena que representa una extensión de archivo a un objeto [`TextualFormats`](../textualformats). |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Chm](../../groupdocs.editor.formats/textualformats/chm) | Microsoft Compiled HTML Help es un formato binario de ayuda en línea propietario de Microsoft, que consiste en una colección de páginas HTML, un índice y otras herramientas de navegación. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/web/chm/). |
| static readonly [Html](../../groupdocs.editor.formats/textualformats/html) | El documento HyperText Markup Language (HTML) es la extensión para páginas web creadas para mostrarse en navegadores. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/web/html). |
| static readonly [Json](../../groupdocs.editor.formats/textualformats/json) | JSON (JavaScript Object Notation) es un formato de archivo estándar abierto para compartir datos que utiliza texto legible por humanos para almacenar y transmitir datos. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/web/json/). |
| static readonly [Md](../../groupdocs.editor.formats/textualformats/md) | Markdown es un lenguaje de marcado ligero para crear texto formateado usando un editor de texto plano. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/word-processing/md/). |
| static readonly [Mhtml](../../groupdocs.editor.formats/textualformats/mhtml) | La encapsulación MIME de documentos HTML agregados es un formato de archivo de archivo web utilizado para combinar, en un solo archivo informático, el código HTML y sus recursos complementarios. Obtén más información sobre este formato de archivo [aquí](https://docs.fileformat.com/web/mhtml/). |
| static readonly [Txt](../../groupdocs.editor.formats/textualformats/txt) | El documento de texto plano (TXT) representa un documento de texto que contiene texto plano en forma de líneas. Obtén más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/word-processing/txt). |
| static readonly [Xml](../../groupdocs.editor.formats/textualformats/xml) | Documento eXtensible Markup Language (XML) que es similar a HTML pero diferente al usar etiquetas para definir objetos. Obtenga más información sobre este formato de archivo [aquí](https://wiki.fileformat.com/web/xml). |

### Ver también

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
