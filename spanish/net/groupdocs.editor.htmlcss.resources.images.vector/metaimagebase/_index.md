---
title: "MetaImageBase"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Clase base abstracta para los formatos de imagen WMF y EMF"
type: docs
weight: 570
url: /es/net/groupdocs.editor.htmlcss.resources.images.vector/metaimagebase/
---
## MetaImageBase class

Clase base abstracta para los formatos de imagen WMF y EMF

```csharp
public abstract class MetaImageBase : VectorImageResourceBase
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AspectRatio](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/aspectratio) { get; } | Devuelve la relación de aspecto de esta imagen vectorial |
| abstract [ByteContent](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/bytecontent) { get; } | En la implementación, el tipo debe devolver el contenido de esta imagen vectorial como flujo de bytes |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/filenamewithextension) { get; } | Devuelve el nombre de archivo correcto de esta imagen vectorial, que consta de nombre y extensión. Teóricamente puede diferir del nombre. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/isdisposed) { get; } | Determina si esta imagen rasterizada está descartada (`true`) o no (`false`) |
| [LinearDimensions](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/lineardimensions) { get; } | Devuelve las dimensiones lineales de esta imagen vectorial (ancho y alto) |
| [Name](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/name) { get; } | Devuelve el nombre de esta imagen vectorial. Normalmente no contiene la extensión del archivo y teóricamente puede diferir del nombre del archivo. |
| abstract [TextContent](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/textcontent) { get; } | En la implementación, el tipo debe devolver el contenido de esta imagen vectorial en forma de texto: codificado en base64 de XML relativo al tipo de imagen |
| abstract [Type](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/type) { get; } | En la implementación, el tipo debe devolver información sobre el tipo de la imagen vectorial |

## Métodos

| Nombre | Descripción |
| --- | --- |
| abstract [Dispose](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/dispose)() | En la implementación, el tipo debe descartar esta instancia |
| [Equals](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/equals)(IHtmlResource) | Comprueba esta instancia con la especificada mediante igualdad de referencia. |
| abstract [Save](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/save)(string) | En la implementación, el tipo debe guardar esta imagen en el disco mediante la ruta especificada |
| abstract [SaveToPng](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/savetopng)(Stream) | En la implementación, el tipo debe guardar la imagen vectorial actual en formato PNG rasterizado en el flujo de bytes especificado |
| abstract [SaveToSvg](../../groupdocs.editor.htmlcss.resources.images.vector/metaimagebase/savetosvg)(Stream) | Al implementar WMF o EMF, el tipo debe guardar una meta‑imagen vectorial actual en formato SVG vectorial al flujo de bytes especificado |

## Eventos

| Nombre | Descripción |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.images.vector/vectorimageresourcebase/disposed) | Evento que ocurre cuando esta imagen rasterizada se descarta |

### Observaciones

Esta clase abstracta es heredada por [`WmfImage`](../wmfimage) y [`EmfImage`](../emfimage)

### Ver también

* class [VectorImageResourceBase](../vectorimageresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Images.Vector](../../groupdocs.editor.htmlcss.resources.images.vector)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
