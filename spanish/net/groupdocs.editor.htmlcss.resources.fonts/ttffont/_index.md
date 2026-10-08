---
title: "TtfFont"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Representa una fuente en el formato TTF TrueType Font"
type: docs
weight: 390
url: /es/net/groupdocs.editor.htmlcss.resources.fonts/ttffont/
---
## TtfFont class

Representa una fuente en formato TTF (TrueType Font).

```csharp
public sealed class TtfFont : FontResourceBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TtfFont](ttffont#constructor)(string, Stream) | Crea una nueva clase TtfFont a partir del contenido, representado como flujo de bytes, y con el nombre especificado |
| [TtfFont](ttffont#constructor_1)(string, string) | Crea una nueva clase TtfFont a partir del contenido, representado como cadena codificada en base64, y con el nombre especificado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/bytecontent) { get; } | Devuelve el contenido de esta fuente como flujo de bytes |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/filenamewithextension) { get; } | Devuelve el nombre de archivo correcto de este recurso de fuente, que consiste en el nombre y la extensión. Teóricamente puede diferir del nombre. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/isdisposed) { get; } | Determina si esta fuente está eliminada o no |
| [Name](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/name) { get; } | Devuelve el nombre de este recurso de fuente. Normalmente no contiene la extensión del nombre de archivo y teóricamente puede diferir del nombre de archivo. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/textcontent) { get; } | Devuelve el contenido de esta fuente como una cadena codificada en base64. Este valor se almacena en caché después de la primera invocación. |
| override [Type](../../groupdocs.editor.htmlcss.resources.fonts/ttffont/type) { get; } | Devuelve FontType.Ttf |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/dispose)() | Elimina este recurso de fuente, eliminando su contenido y haciendo que la mayoría de los métodos y propiedades no funcionen |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(FontResourceBase) | Comprueba esta instancia con el recurso de fuente especificado por igualdad de referencia |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(IHtmlResource) | Comprueba esta instancia con el recurso HTML especificado por igualdad de referencia |
| [Save](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/save)(string) | Guarda esta fuente en el archivo especificado |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/ttffont/isvalid#isvalid)(Stream) | Comprueba si el flujo especificado es una fuente TTF válida |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/ttffont/isvalid#isvalid_1)(string) | Comprueba si la cadena codificada en base64 especificada es una fuente TTF válida |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [RequiredHeaderSize](../../groupdocs.editor.htmlcss.resources.fonts/ttffont/requiredheadersize) | Tamaño del encabezado TTF (en bytes), que es necesario para su validación |

## Eventos

| Nombre | Descripción |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/disposed) | Evento que ocurre cuando esta fuente es eliminada |

### Ver también

* class [FontResourceBase](../fontresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
