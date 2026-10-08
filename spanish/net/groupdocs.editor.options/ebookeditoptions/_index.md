---
title: "EbookEditOptions"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Permite especificar y ajustar opciones personalizadas para editar documentos Ebook en todos los formatos compatibles: ePub, MOBI y AZW3."
type: docs
weight: 830
url: /es/net/groupdocs.editor.options/ebookeditoptions/
---
## EbookEditOptions class

Permite especificar y ajustar opciones personalizadas para editar documentos de libros electrónicos en todos los formatos compatibles: ePub, MOBI y AZW3.

```csharp
public sealed class EbookEditOptions : IEditOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EbookEditOptions](ebookeditoptions#constructor)() | Inicializa una nueva instancia de la clase [`EbookEditOptions`](../ebookeditoptions), donde todas las opciones están establecidas a sus valores predeterminados |
| [EbookEditOptions](ebookeditoptions#constructor_1)(bool) | Inicializa una nueva instancia de la clase [`EbookEditOptions`](../ebookeditoptions) con el modo de paginación especificado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [EnableLanguageInformation](../../groupdocs.editor.options/ebookeditoptions/enablelanguageinformation) { get; set; } | Especifica si la información de idioma se exporta al marcado HTML en forma de atributos HTML 'lang'. Esta opción puede ser útil para la conversión bidireccional de documentos multilingües. Por defecto está deshabilitada (`false`). |
| [EnablePagination](../../groupdocs.editor.options/ebookeditoptions/enablepagination) { get; set; } | Permite habilitar o deshabilitar la paginación en el documento HTML resultante. Por defecto está deshabilitada (`false`). |

### Observaciones

Formatos de e-Book compatibles:

1. [ePub](https://docs.fileformat.com/ebook/epub/) (Publicación electrónica)
2. [MOBI](https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](https://docs.fileformat.com/ebook/azw3/) (Formato Kindle 8t)

### Ver también

* interface [IEditOptions](../ieditoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
