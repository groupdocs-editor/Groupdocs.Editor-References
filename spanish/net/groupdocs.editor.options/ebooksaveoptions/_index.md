---
title: "EbookSaveOptions"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Permite especificar opciones personalizadas para generar y guardar el documento en todos los formatos de eBook compatibles: ePub, MOBI y AZW3."
type: docs
weight: 840
url: /es/net/groupdocs.editor.options/ebooksaveoptions/
---
## EbookSaveOptions class

Permite especificar opciones personalizadas para generar y guardar el documento en todos los formatos de libro electrónico compatibles: ePub, MOBI y AZW3.

```csharp
public sealed class EbookSaveOptions : ISaveOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EbookSaveOptions](ebooksaveoptions#constructor)() | Este constructor sin parámetros crea una nueva instancia de EbookSaveOptions con formato de salida ePub (puede modificarse luego mediante la propiedad [`OutputFormat`](./outputformat)). |
| [EbookSaveOptions](ebooksaveoptions#constructor_1)(EBookFormats) | Crea una nueva instancia de [`EbookSaveOptions`](../ebooksaveoptions) con el formato de salida de e-Book obligatorio especificado, mientras que todos los demás parámetros son por defecto. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ExportDocumentProperties](../../groupdocs.editor.options/ebooksaveoptions/exportdocumentproperties) { get; set; } | Especifica si se exportan las propiedades de documento incorporadas y personalizadas en el archivo resultante. El valor predeterminado es `false`. |
| [OutputFormat](../../groupdocs.editor.options/ebooksaveoptions/outputformat) { get; set; } | Especifica el formato del archivo e-Book resultante: IDPF ePub, MOBI o AZW3. |
| [SplitHeadingLevel](../../groupdocs.editor.options/ebooksaveoptions/splitheadinglevel) { get; set; } | Especifica el nivel máximo de encabezados en el que dividir el archivo e-Book. El valor predeterminado es `2`. Configurarlo en `0` desactivará la división, de modo que todo el contenido del e-Book se incorporará en un solo paquete dentro del archivo resultante. |

### Observaciones

Formatos de e-Book compatibles:

1. [ePub](https://docs.fileformat.com/ebook/epub/) (Publicación electrónica)
2. [MOBI](https://docs.fileformat.com/ebook/mobi/) (MobiPocket)
3. [AZW3](https://docs.fileformat.com/ebook/azw3/) (Formato Kindle 8t)

### Ver también

* interface [ISaveOptions](../isaveoptions)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
