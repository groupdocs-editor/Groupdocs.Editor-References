---
title: "FixedLayoutFormats"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Representa formatos de documento fixedlayout fixedpage como PDF, excluyendo formatos de imagen rasterizada."
type: docs
weight: 100
url: /es/net/groupdocs.editor.formats/fixedlayoutformats/
---
## FixedLayoutFormats class

Representa formatos de documento de diseño fijo (página fija), como PDF, excluyendo los formatos de imágenes raster.

```csharp
public class FixedLayoutFormats : DocumentFormatBase
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Extension](../../groupdocs.editor.formats.abstraction/documentformatbase/extension) { get; } | Obtiene la extensión de archivo del formato de documento. |
| [FormatFamily](../../groupdocs.editor.formats.abstraction/documentformatbase/formatfamily) { get; } | Obtiene la familia de formato a la que pertenece el formato de documento. |
| [Id](../../groupdocs.editor.formats.abstraction/formatfamilybase/id) { get; } | Obtiene el identificador único de la familia de formato. |
| [Mime](../../groupdocs.editor.formats.abstraction/documentformatbase/mime) { get; } | Obtiene el tipo MIME del formato de documento. |
| [Name](../../groupdocs.editor.formats.abstraction/formatfamilybase/name) { get; } | Obtiene el nombre de la familia de formato. |
| static [All](../../groupdocs.editor.formats/fixedlayoutformats/all) { get; } | Obtiene todas las instancias disponibles de [`FixedLayoutFormats`](../fixedlayoutformats). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromExtension](../../groupdocs.editor.formats/fixedlayoutformats/fromextension)(string) | Recupera una instancia de [`FixedLayoutFormats`](../fixedlayoutformats) que coincida con la extensión de archivo especificada. |
| [Equals](../../groupdocs.editor.formats.abstraction/formatfamilybase/equals)(FormatFamilyBase) | Determina si esta instancia es igual a la instancia especificada de [`FormatFamilyBase`](../../groupdocs.editor.formats.abstraction/formatfamilybase). |
| [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(IDocumentFormat) | Determina si esta instancia es igual a la instancia especificada de [`IDocumentFormat`](../../groupdocs.editor.formats.abstraction/idocumentformat). |
| override [Equals](../../groupdocs.editor.formats.abstraction/documentformatbase/equals)(object) | Determina si esta instancia es igual a la instancia especificada de [`DocumentFormatBase`](../../groupdocs.editor.formats.abstraction/documentformatbase). |
| override [GetHashCode](../../groupdocs.editor.formats.abstraction/documentformatbase/gethashcode)() | Devuelve un código hash para el objeto actual. |
| override [ToString](../../groupdocs.editor.formats.abstraction/formatfamilybase/tostring)() | Devuelve una cadena que representa el objeto actual. |
| [explicit operator](../../groupdocs.editor.formats/fixedlayoutformats/op_explicit) | Convierte explícitamente una cadena de extensión de archivo a una instancia de [`FixedLayoutFormats`](../fixedlayoutformats). |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Pdf](../../groupdocs.editor.formats/fixedlayoutformats/pdf) | Portable Document Format (PDF), introducido por Adobe, proporciona una representación estandarizada de documentos independiente del software, hardware y sistemas operativos. Para obtener más detalles, consulte: [PDF file format](https://docs.fileformat.com/pdf/). |

### Observaciones

Los formatos de diseño fijo especifican con precisión la ubicación y el renderizado del contenido en cada página. Se utilizan comúnmente en aplicaciones de visualización, publicación o edición de documentos como Adobe Acrobat y Adobe InDesign. Estos formatos definen internamente los diseños de página y la posición del contenido mediante gráficos vectoriales e instrucciones de texto.

### Ver también

* class [DocumentFormatBase](../../groupdocs.editor.formats.abstraction/documentformatbase)
* namespace [GroupDocs.Editor.Formats](../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
