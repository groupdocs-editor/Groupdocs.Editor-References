---
title: "TtcFont"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Representa una fuente en el formato TTC TrueType Collection"
type: docs
weight: 380
url: /es/net/groupdocs.editor.htmlcss.resources.fonts/ttcfont/
---
## TtcFont class

Representa una fuente en formato TTC (TrueType Collection).

```csharp
public sealed class TtcFont : FontResourceBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TtcFont](ttcfont#constructor)(string, Stream) | Crea una nueva clase TtcFont a partir del contenido, representado como flujo de bytes, y con el nombre especificado |
| [TtcFont](ttcfont#constructor_1)(string, string) | Crea una nueva clase TtcFont a partir del contenido, representado como cadena codificada en base64, y con el nombre especificado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/bytecontent) { get; } | Devuelve el contenido de esta fuente como flujo de bytes |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/filenamewithextension) { get; } | Devuelve el nombre de archivo correcto de este recurso de fuente, que consiste en el nombre y la extensión. Teóricamente puede diferir del nombre. |
| [FontsNumber](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/fontsnumber) { get; } | Número de fuentes en este TTC |
| [HasDsigTable](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/hasdsigtable) { get; } | Indica si este TTC tiene una tabla DSIG. La tabla DSIG puede estar presente solo si el TTC tiene una cabecera versión 2.0. |
| [HeaderVersion](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/headerversion) { get; } | Versión del encabezado TTC, puede ser "1" o "2" |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/isdisposed) { get; } | Determina si esta fuente está eliminada o no |
| [Name](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/name) { get; } | Devuelve el nombre de este recurso de fuente. Normalmente no contiene la extensión del nombre de archivo y teóricamente puede diferir del nombre de archivo. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/textcontent) { get; } | Devuelve el contenido de esta fuente como una cadena codificada en base64. Este valor se almacena en caché después de la primera invocación. |
| override [Type](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/type) { get; } | Devuelve FontType.Ttc |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/dispose)() | Elimina este recurso de fuente, eliminando su contenido y haciendo que la mayoría de los métodos y propiedades no funcionen |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(FontResourceBase) | Comprueba esta instancia con el recurso de fuente especificado por igualdad de referencia |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals)(IHtmlResource) | Comprueba esta instancia con el recurso HTML especificado por igualdad de referencia |
| [Save](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/save)(string) | Guarda esta fuente en el archivo especificado |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/isvalid#isvalid)(Stream) | Comprueba si el flujo especificado es una fuente TTC válida |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/isvalid#isvalid_1)(string) | Comprueba si la cadena codificada en base64 especificada es una fuente TTF válida |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [RequiredHeaderSize](../../groupdocs.editor.htmlcss.resources.fonts/ttcfont/requiredheadersize) | Tamaño del encabezado TTC (en bytes), que es necesario para su validación |

## Eventos

| Nombre | Descripción |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/disposed) | Evento que ocurre cuando esta fuente es eliminada |

### Observaciones

Ver más: https://docs.fileformat.com/font/ttc/

### Ver también

* class [FontResourceBase](../fontresourcebase)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
