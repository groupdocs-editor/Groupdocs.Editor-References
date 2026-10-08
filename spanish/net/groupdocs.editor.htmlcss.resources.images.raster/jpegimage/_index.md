---
title: "JpegImage"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Representa una imagen en formato JPEG Joint Photographic Experts Group con sus metadatos y métodos adicionales"
type: docs
weight: 520
url: /es/net/groupdocs.editor.htmlcss.resources.images.raster/jpegimage/
---
## JpegImage class

Representa una imagen en formato JPEG (Joint Photographic Experts Group) con sus metadatos y métodos adicionales.

```csharp
public sealed class JpegImage : RasterImageResourceBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [JpegImage](jpegimage#constructor)(string, Stream) | Crea una nueva instancia de JpegImage a partir del contenido, representado como flujo de bytes, y con el nombre especificado |
| [JpegImage](jpegimage#constructor_1)(string, string) | Crea una nueva instancia de JpegImage a partir del contenido, representado como cadena codificada en base64, y con el nombre especificado |

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
| override [Type](../../groupdocs.editor.htmlcss.resources.images.raster/jpegimage/type) { get; } | Devuelve ImageType.Jpeg |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/dispose)() | Descarta esta imagen raster, descartando su contenido y haciendo que la mayoría de los métodos y propiedades no funcionen |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/equals)(IHtmlResource) | Comprueba esta instancia con la especificada mediante igualdad de referencia. |
| [Save](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/save)(string) | Guarda esta imagen raster en el archivo especificado |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/jpegimage/isvalid#isvalid)(Stream) | Comprueba si el flujo especificado es una imagen JPEG válida |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.raster/jpegimage/isvalid#isvalid_1)(string) | Comprueba si la cadena codificada en base64 especificada es una imagen JPEG válida |

## Eventos

| Nombre | Descripción |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.raster/rasterimageresourcebase/disposed) | Evento que ocurre cuando esta imagen rasterizada se descarta |

### Ver también

* class [RasterImageResourceBase](../rasterimageresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Raster](../../groupdocs.editor.htmlcss.resources.images.raster)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
