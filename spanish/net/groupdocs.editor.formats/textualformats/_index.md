---
title: TextualFormats
second_title: Referencia de API de GroupDocs.Editor para .NET
description: Encapsula todos los formatos textuales basados en texto incluido el marcado XML HTML y otros. Incluye los siguientes formatos Html./textualformats/html  Txt./textualformats/txt  Xml./textualformats/xml . Md./textualformats/md  Json./textualformats/json .
type: docs
weight: 150
url: /es/net/groupdocs.editor.formats/textualformats/
---
## TextualFormats structure

Encapsula todos los formatos textuales (basados en texto), incluido el marcado (XML, HTML) y otros. Incluye los siguientes formatos: [`Html`](./html) , [`Txt`](./txt) , [`Xml`](./xml) . [`Md`](./md) , [`Json`](./json) .

```csharp
public struct TextualFormats : IDocumentFormat, IEquatable<TextualFormats>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Extension](../../groupdocs.editor.formats/textualformats/extension) { get; } | Devuelve una extensión (sin carácter de punto inicial) de este formato de texto en minúsculas |
| [Mime](../../groupdocs.editor.formats/textualformats/mime) { get; } | Devuelve un código MIME para este formato |
| [Name](../../groupdocs.editor.formats/textualformats/name) { get; } | Devuelve un nombre completo formal de este formato textual |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/textualformats/fromextension)(string) | Devuelve instancia de[`TextualFormats`](../textualformats) estructura, asociada a la extensión de nombre de archivo especificada, o genera una excepción, si la extensión no se puede analizar correctamente |
| [Equals](../../groupdocs.editor.formats/textualformats/equals#equals)(IDocumentFormat) | Determina si esta instancia es igual a la otra instancia de IDocumentFormat especificada |
| override [Equals](../../groupdocs.editor.formats/textualformats/equals#equals_2)(object) | Determina si esta instancia es igual al otro objeto especificado, que presumiblemente es de TextualFormats en caja |
| [Equals](../../groupdocs.editor.formats/textualformats/equals#equals_1)(TextualFormats) | Determina si esta instancia es igual a la otra instancia de TextualFormats especificada |
| override [GetHashCode](../../groupdocs.editor.formats/textualformats/gethashcode)() | Devuelve un código hash, que es inmutable para esta instancia |
| override [ToString](../../groupdocs.editor.formats/textualformats/tostring)() | Devuelve el nombre de este formato en particular, igual que la propiedad 'Nombre' |
| [operator ==](../../groupdocs.editor.formats/textualformats/op_equality) | Comprueba dos instancias de TextualFormats dadas en igualdad |
| [operator !=](../../groupdocs.editor.formats/textualformats/op_inequality) | Comprueba dos instancias de TextualFormats dadas en desigualdad |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Chm](../../groupdocs.editor.formats/textualformats/chm) | Microsoft Compiled HTML Help es un formato binario de ayuda en línea propiedad de Microsoft, que consta de una colección de páginas HTML, un índice y otras herramientas de navegación. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/web/chm/) . |
| static readonly [Html](../../groupdocs.editor.formats/textualformats/html) | El documento de lenguaje de marcado de hipertexto (HTML) es la extensión para páginas web creada para mostrarse en los navegadores. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/web/html) . |
| static readonly [Json](../../groupdocs.editor.formats/textualformats/json) | JSON (Notación de objetos de JavaScript) es un formato de archivo estándar abierto para compartir datos que utiliza texto legible por humanos para almacenar y transmitir datos. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/web/json/) . |
| static readonly [Md](../../groupdocs.editor.formats/textualformats/md) | Markdown es un lenguaje de marcado ligero para crear texto con formato mediante un editor de texto sin formato. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/word-processing/md/) . |
| static readonly [Mhtml](../../groupdocs.editor.formats/textualformats/mhtml) | La encapsulación MIME de documentos HTML agregados es un formato de archivo de página web que se utiliza para combinar, en un solo archivo de computadora, el código HTML y sus recursos complementarios. Más información sobre este formato de archivo[aquí](https://docs.fileformat.com/web/mhtml/) . |
| static readonly [Txt](../../groupdocs.editor.formats/textualformats/txt) | Documento de texto sin formato (TXT) representa un documento de texto que contiene texto sin formato en forma de líneas. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/word-processing/txt) . |
| static readonly [Xml](../../groupdocs.editor.formats/textualformats/xml) | Documento de lenguaje de marcado extensible (XML) que es similar a HTML pero diferente en el uso de etiquetas para definir objetos. Más información sobre este formato de archivo[aquí](https://wiki.fileformat.com/web/xml) . |
| static readonly [All](../../groupdocs.editor.formats/textualformats/all) | Devuelve una clase interna, que proporciona posibilidades enumerables sobre todos los formatos textuales existentes. |

## Otros miembros

| Nombre | Descripción |
| --- | --- |
| class [AllEnumerable](textualformats.allenumerable) | Implementa la interfaz genérica IEnumerable, que permite la posibilidad de 'foreach' para los TextualFormats type |

### Ver también

* interface [IDocumentFormat](../idocumentformat)
* espacio de nombres [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* asamblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
