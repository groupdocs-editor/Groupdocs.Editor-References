---
title: "WmfImage"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Representa una imagen vectorial en formato WMF Windows MetaFile con sus metadatos y métodos adicionales"
type: docs
weight: 600
url: /es/net/groupdocs.editor.htmlcss.resources.images.vector/wmfimage/
---
## WmfImage class

Representa una imagen vectorial en formato WMF (Windows MetaFile) con sus metadatos y métodos adicionales

```csharp
public sealed class WmfImage : MetaImageBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [WmfImage](wmfimage#constructor)(string, Stream) | Crea una nueva instancia de WmfImage a partir del contenido, representado como flujo de bytes, y con el nombre especificado |
| [WmfImage](wmfimage#constructor_1)(string, string) | Crea una nueva instancia de WmfImage a partir del contenido, representado como cadena codificada en base64, y con el nombre especificado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | Devuelve la relación de aspecto de esta imagen vectorial |
| override [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/bytecontent) { get; } | Devuelve el contenido de esta imagen WMF como un flujo binario |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | Devuelve el nombre de archivo correcto de esta imagen vectorial, que consta de nombre y extensión. Teóricamente puede diferir del nombre. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | Determina si esta imagen rasterizada está descartada (`true`) o no (`false`) |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | Devuelve las dimensiones lineales de esta imagen vectorial (ancho y alto) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | Devuelve el nombre de esta imagen vectorial. Normalmente no contiene la extensión del archivo y teóricamente puede diferir del nombre del archivo. |
| override [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/textcontent) { get; } | Devuelve el contenido de esta imagen WMF como texto plano |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/type) { get; } | Devuelve ImageType.Wmf |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/dispose)() | Descarta esta imagen WMF liberando su contenido y haciendo que la mayoría de sus métodos y propiedades no funcionen |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals)(IHtmlResource) | Comprueba esta instancia con la especificada mediante igualdad de referencia. |
| override [Save](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/save)(string) | Guarda esta imagen WMF en el archivo |
| override [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/savetopng)(Stream) | Guarda esta imagen vectorial WMF en una imagen PNG rasterizada |
| override [SaveToSvg](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/savetosvg)(Stream) | Guarda esta imagen vectorial WMF en una imagen SVG vectorial |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/isvalid#isvalid)(Stream) | Comprueba si el flujo especificado es una imagen WMF válida |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/wmfimage/isvalid#isvalid_1)(string) | Comprueba si la cadena codificada en base64 especificada es una imagen WMF válida |

## Eventos

| Nombre | Descripción |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | Evento que ocurre cuando esta imagen rasterizada se descarta |

### Ver también

* class [MetaImageBase](../metaimagebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
