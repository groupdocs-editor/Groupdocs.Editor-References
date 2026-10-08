---
title: "PdfEditOptions"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Permite especificar opciones personalizadas para editar documentos PDF"
type: docs
weight: 1050
url: /es/net/groupdocs.editor.options/pdfeditoptions/
---
## PdfEditOptions class

Permite especificar opciones personalizadas para editar documentos PDF

```csharp
public sealed class PdfEditOptions : FixedLayoutEditOptionsBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfEditOptions](pdfeditoptions#constructor)() | Crea y devuelve una nueva instancia de la clase PdfEditOptions, donde todas las opciones están establecidas a sus valores predeterminados |
| [PdfEditOptions](pdfeditoptions#constructor_1)(bool) | Crea y devuelve una nueva instancia de la clase PdfEditOptions con paginación especificada y el resto de opciones con sus valores predeterminados |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/fixedlayouteditoptionsbase/enablepagination) { get; set; } | Permite habilitar (true) o deshabilitar (false) la paginación en el documento HTML resultante. Por defecto está deshabilitada (false). |
| [Pages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/pages) { get; set; } | Permite establecer un rango de páginas a procesar. Por defecto se procesan todas las páginas de un documento de diseño fijo. |
| [SkipImages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/skipimages) { get; set; } | Obtiene o establece la bandera que indica si se deben omitir las imágenes al convertir el documento de diseño fijo de entrada al HTML resultante. Por defecto es false - las imágenes se conservan. |

### Ver también

* class [FixedLayoutEditOptionsBase](../fixedlayouteditoptionsbase)
* namespace [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
