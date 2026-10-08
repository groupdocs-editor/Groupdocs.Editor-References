---
title: "SvgImage"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Representa una imagen vectorial en formato SVG Scalable Vector Graphics con sus dimensiones de metadatos y métodos adicionales para guardar en PNG"
type: docs
weight: 580
url: /es/net/groupdocs.editor.htmlcss.resources.images.vector/svgimage/
---
## SvgImage class

Representa una imagen vectorial en formato SVG (Scalable Vector Graphics) con sus metadatos (dimensiones) y métodos adicionales (guardado en PNG)

```csharp
public sealed class SvgImage : VectorImageResourceBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SvgImage](svgimage#constructor)(string, Stream) | Crea una nueva instancia de SvgImage a partir del contenido, representado como flujo de bytes, y con el nombre especificado |
| [SvgImage](svgimage#constructor_1)(string, string) | Crea una nueva instancia de SvgImage a partir del contenido, representado como una cadena habitual, y con el nombre especificado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | Devuelve la relación de aspecto de esta imagen vectorial |
| override [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/bytecontent) { get; } | Devuelve el contenido de esta imagen SVG como un flujo binario con la posición original |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | Devuelve el nombre de archivo correcto de esta imagen vectorial, que consta de nombre y extensión. Teóricamente puede diferir del nombre. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | Determina si esta imagen rasterizada está descartada (`true`) o no (`false`) |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | Devuelve las dimensiones lineales de esta imagen vectorial (ancho y alto) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | Devuelve el nombre de esta imagen vectorial. Normalmente no contiene la extensión del archivo y teóricamente puede diferir del nombre del archivo. |
| override [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/textcontent) { get; } | Devuelve el contenido de esta imagen SVG como contenido binario codificado en base64 (no como texto sin formato en formato XML) |
| override [Type](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/type) { get; } | Devuelve [`Svg`](../../groupdocs.editor.htmlcss.resources.images/imagetype/svg) |
| [XmlContent](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/xmlcontent) { get; } | Devuelve el contenido de esta imagen SVG en su forma textual original compatible con XML |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/dispose)() | Descarta esta imagen raster, descartando su contenido y haciendo que la mayoría de los métodos y propiedades no funcionen |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals)(IHtmlResource) | Comprueba esta instancia con la especificada mediante igualdad de referencia. |
| override [Save](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/save)(string) | Guarda esta imagen SVG en el archivo |
| override [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/savetopng)(Stream) | Guarda esta imagen vectorial SVG en una imagen raster PNG |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.images.vector/svgimage/isvalid)(string) | Realiza una comprobación superficial de si el contenido textual compatible con XML especificado representa una imagen SVG |

## Eventos

| Nombre | Descripción |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | Evento que ocurre cuando esta imagen rasterizada se descarta |

### Ver también

* class [VectorImageResourceBase](../vectorimageresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
