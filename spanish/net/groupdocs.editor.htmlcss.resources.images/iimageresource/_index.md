---
title: "IImageResource"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Representa un recurso de imagen de cualquier tipo, raster o vectorial"
type: docs
weight: 470
url: /es/net/groupdocs.editor.htmlcss.resources.images/iimageresource/
---
## IImageResource interface

Representa un recurso de imagen de cualquier tipo, raster o vectorial.

```csharp
public interface IImageResource : IHtmlResource, IImage
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images/iimageresource/aspectratio) { get; } | En la implementación, el tipo debe devolver la relación de aspecto de una imagen particular sin importar su tipo. Tanto las imágenes vectoriales como raster tienen una relación de aspecto intrínseca entre su ancho y su altura. |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images/iimageresource/lineardimensions) { get; } | En la implementación, el tipo debe devolver las dimensiones lineales de la imagen. Para las imágenes raster son dimensiones intrínsecas en píxeles. Las imágenes vectoriales, por otro lado, no tienen dimensiones fijas, pero sus metadatos pueden contener algunas dimensiones básicas en diferentes unidades de medida. |
| [Type](../../groupdocs.editor.htmlcss.resources.images/iimageresource/type) { get; } | En la implementación, el tipo debe devolver el tipo de una imagen específica como una instancia de ImageType específico, que encapsula toda la información específica del tipo |

### Observaciones

https://developer.mozilla.org/en-US/docs/Web/CSS/image

### Ver también

* interface [IHtmlResource](../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* interface [IImage](../iimage)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images](../../groupdocs.editor.htmlcss.resources.images)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
