---
title: "RasterImageResourceBase"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Clase base para cualquier imagen rasterizada compatible con nombre, dimensiones, relación de aspecto, tipo, tamaño y contenido fijos."
type: docs
weight: 540
url: /es/net/groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/
---
## RasterImageResourceBase class

Clase base para cualquier imagen raster compatible con nombre fijo, dimensiones, relación de aspecto, tipo, tamaño y contenido.

```csharp
public abstract class RasterImageResourceBase : IImageResource
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/aspectratio) { get; } | Devuelve una relación de aspecto de esta imagen como la relación ancho/altura |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/bytecontent) { get; } | Devuelve el contenido de esta imagen rasterizada como flujo de bytes |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/filenamewithextension) { get; } | Devuelve el nombre de archivo correcto de esta imagen rasterizada, que consiste en el nombre y la extensión. Teóricamente puede diferir del nombre. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/isdisposed) { get; } | Determina si esta imagen rasterizada está liberada o no |
| [Length](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/length) { get; } | Devuelve la longitud de este archivo de imagen rasterizada en bytes |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/lineardimensions) { get; } | Devuelve las dimensiones lineales de esta imagen rasterizada (ancho y altura) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/name) { get; } | Devuelve el nombre de esta imagen rasterizada. Normalmente no contiene la extensión del archivo y teóricamente puede diferir del nombre del archivo. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/textcontent) { get; } | Devuelve el contenido de esta imagen rasterizada como cadena codificada en base64 |
| abstract [Type](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/type) { get; } | Al implementar, el tipo debe devolver información sobre el tipo de la imagen rasterizada |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/dispose)() | Descarta esta imagen raster, descartando su contenido y haciendo que la mayoría de los métodos y propiedades no funcionen |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/equals#equals)(IHtmlResource) | Comprueba esta instancia con la especificada mediante igualdad de referencia. |
| [Save](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/save)(string) | Guarda esta imagen raster en el archivo especificado |

## Eventos

| Nombre | Descripción |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/disposed) | Evento que ocurre cuando esta imagen rasterizada se descarta |

### Ver también

* interface [IImageResource](../../groupdocs.editor.htmlcss.resources.images/iimageresource)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
