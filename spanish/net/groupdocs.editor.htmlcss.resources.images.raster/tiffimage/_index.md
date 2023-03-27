---
title: TiffImage
second_title: Referencia de API de GroupDocs.Editor para .NET
description: Representa una imagen en formato TIFF Tagged Image File Format con sus metadatos y métodos adicionales
type: docs
weight: 560
url: /es/net/groupdocs.editor.htmlcss.resources.images.raster/tiffimage/
---
## TiffImage class

Representa una imagen en formato TIFF (Tagged Image File Format) con sus metadatos y métodos adicionales

```csharp
public sealed class TiffImage : RasterImageResourceBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TiffImage](tiffimage#constructor)(string, Stream) | Crea una nueva instancia de GifImage a partir del contenido, representada como flujo de bytes y con el nombre especificado |
| [TiffImage](tiffimage#constructor_1)(string, string) | Crea una nueva instancia de TiffImage a partir del contenido, representada como una cadena codificada en base64 y con el nombre especificado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/aspectratio) { get; } | Devuelve una relación de aspecto de esta imagen como la relación ancho-alto |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/bytecontent) { get; } | Devuelve el contenido de esta imagen ráster como flujo de bytes |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/filenamewithextension) { get; } | Devuelve el nombre de archivo correcto de esta imagen ráster, que consta de nombre y extensión. Teóricamente puede diferir del nombre. |
| [FramesCount](../../groupdocs.editor.htmlcss.resources.images.raster/tiffimage/framescount) { get; } | Devuelve una cantidad de fotogramas (imágenes) dentro de esta imagen TIFF. No puede ser inferior a 1. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/isdisposed) { get; } | Determina si esta imagen ráster se elimina o no |
| [Length](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/length) { get; } | Devuelve la longitud de este archivo de imagen ráster en bytes |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/lineardimensions) { get; } | Devuelve las dimensiones lineales de esta imagen ráster (ancho y alto) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/name) { get; } | Devuelve el nombre de esta imagen ráster. Por lo general, no contiene la extensión de nombre de archivo y, en teoría, puede diferir de filename. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/textcontent) { get; } | Devuelve el contenido de esta imagen ráster como cadena codificada en base64 |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.raster/tiffimage/type) { get; } | Devuelve TipoImagen.Tiff |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/dispose)() | Elimina esta imagen ráster, eliminando su contenido y haciendo que la mayoría de los métodos y propiedades no funcionen |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/equals)(IHtmlResource) | Comprueba esta instancia con la igualdad de referencia especificada. |
| [GenerateBitmap](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/generatebitmap)() | Genera y devuelve una nueva instancia de 'System.Drawing.Bitmap' a partir de esta imagen ráster. |
| [ReduceToNewHeight](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/reducetonewheight)(ushort) | Crea y devuelve un nuevo recurso de imagen reducido del mismo tipo, pero con una nueva altura reducida especificada y un ancho proporcionalmente reducido. |
| [Save](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/save)(string) | Guarda esta imagen ráster en el archivo especificado |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/tiffimage/isvalid#isvalid)(Stream) | Comprueba si el flujo especificado es una imagen TIFF válida |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/tiffimage/isvalid#isvalid_1)(string) | Comprueba si la cadena codificada en base64 especificada es una imagen TIFF válida |

## Eventos

| Nombre | Descripción |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/disposed) | Evento, que ocurre cuando se desecha esta imagen ráster |

### Observaciones

Ver https://en.wikipedia.org/wiki/TIFF para más detalles. En casos muy raros, TIFF está presente dentro de los documentos de WordProcessing.

### Ver también

* class [RasterImageResourceBase](../rasterimageresourcebase)
* espacio de nombres [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../groupdocs.editor.htmlcss.resources.images.raster)
* asamblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
