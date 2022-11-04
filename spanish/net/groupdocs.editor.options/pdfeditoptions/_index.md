---
title: PdfEditOptions
second_title: Referencia de API de GroupDocs.Editor para .NET
description: Permite especificar opciones personalizadas para editar documentos PDF
type: docs
weight: 830
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
| [PdfEditOptions](pdfeditoptions#constructor)() | Crea y devuelve una nueva instancia de la clase PdfEditOptions, donde todas las opciones se establecen en sus valores predeterminados |
| [PdfEditOptions](pdfeditoptions#constructor_1)(bool) | Crea y devuelve una nueva instancia de la clase PdfEditOptions con la paginación especificada y todas las demás opciones predeterminadas |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [EnablePagination](../../groupdocs.editor.options/fixedlayouteditoptionsbase/enablepagination) { get; set; } | Permite habilitar (verdadero) o deshabilitar (falso) la paginación en el documento HTML resultante. Por defecto está deshabilitado (falso). |
| [Pages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/pages) { get; set; } | Permite establecer un rango de páginas para procesar. De forma predeterminada, se procesan todas las páginas de un documento de diseño fijo. |
| [SkipImages](../../groupdocs.editor.options/fixedlayouteditoptionsbase/skipimages) { get; set; } | Obtiene o establece el indicador que indica si las imágenes se deben omitir al convertir el documento de diseño fijo de entrada al HTML resultante. El valor predeterminado es falso: las imágenes se conservan. |

### Ver también

* class [FixedLayoutEditOptionsBase](../fixedlayouteditoptionsbase)
* espacio de nombres [GroupDocs.Editor.Options](../../groupdocs.editor.options)
* asamblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->