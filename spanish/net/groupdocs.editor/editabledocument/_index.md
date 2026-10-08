---
title: "EditableDocument"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Documento intermedio que contiene contenido antes y después de la edición"
type: docs
weight: 10
url: /es/net/groupdocs.editor/editabledocument/
---
## EditableDocument class

Documento intermedio, que contiene contenido antes y después de la edición

```csharp
public sealed class EditableDocument : IAuxDisposable
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AllResources](../../groupdocs.editor/editabledocument/allresources) { get; } | Devuelve una lista de todos los recursos existentes: todas las hojas de estilo, imágenes del HTML y todas las hojas de estilo, fuentes, audio |
| [Audio](../../groupdocs.editor/editabledocument/audio) { get; } | Devuelve una lista de recursos de audio |
| [Css](../../groupdocs.editor/editabledocument/css) { get; } | Permite obtener recursos de hojas de estilo (CSS) (tanto externas como incrustadas, pero no en línea), que son utilizados por este documento HTML |
| [Fonts](../../groupdocs.editor/editabledocument/fonts) { get; } | Permite obtener recursos de fuentes externas, que son utilizados por este documento HTML |
| [Images](../../groupdocs.editor/editabledocument/images) { get; } | Permite obtener recursos de imágenes externas (imágenes raster y vectoriales), que son utilizados por este documento HTML |
| [IsDisposed](../../groupdocs.editor/editabledocument/isdisposed) { get; } | Determina si este documento Editable ya ha sido eliminado (true) o no (false) |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromFile](../../groupdocs.editor/editabledocument/fromfile)(string, string) | Fábrica estática que crea una instancia de EditableDocument a partir de un archivo HTML, especificado mediante la ruta al archivo *.html y una carpeta con recursos vinculados |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup#frommarkup)(string) | Fábrica estática que crea una instancia de [`EditableDocument`](../editabledocument) a partir del marcado HTML especificado |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup#frommarkup_1)(string, IEnumerable&lt;IHtmlResource&gt;) | Fábrica estática que crea una instancia de EditableDocument a partir del marcado HTML especificado y un conjunto de recursos vinculados correspondientes |
| static [FromMarkupAndResourceFolder](../../groupdocs.editor/editabledocument/frommarkupandresourcefolder)(string, string) | Fábrica estática que crea una instancia de EditableDocument a partir de un marcado HTML especificado y de recursos ubicados en la carpeta indicada por la ruta completa |
| [Dispose](../../groupdocs.editor/editabledocument/dispose)() | Elimina esta instancia del documento Editable, descartando su contenido y haciendo que sus métodos y propiedades no funcionen |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent)() | Devuelve el cuerpo del documento HTML (contenido interno entre las etiquetas BODY de apertura y cierre sin esas etiquetas) como una cadena. |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent_1)(string) | Devuelve el cuerpo del documento HTML (contenido interno entre las etiquetas BODY de apertura y cierre sin esas etiquetas) como una cadena, donde los enlaces a los recursos externos contienen la plantilla especificada con marcadores de posición. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent)() | Devuelve el contenido completo del documento HTML como una cadena. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent_1)(string, string) | Devuelve el contenido completo del documento HTML como una cadena, donde los enlaces a los recursos externos contienen la plantilla especificada con marcadores de posición. |
| [GetContent&lt;TStream&gt;](../../groupdocs.editor/editabledocument/getcontent#getcontent_2)(TStream, Encoding) | Devuelve el contenido completo del documento HTML como un flujo de bytes al escribir este contenido en el flujo especificado con la codificación de texto indicada |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent)() | Devuelve el contenido de todas las hojas de estilo externas como una lista de cadenas, donde cada cadena representa una hoja de estilo. Devuelve una lista vacía si no hay CSS para este documento. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent_1)(string, string) | Devuelve el contenido de todas las hojas de estilo externas como una lista de cadenas, donde cada cadena representa una hoja de estilo. El prefijo especificado se aplicará a cada enlace al recurso externo en cada hoja de estilo resultante. Devuelve una lista vacía si no hay CSS para este documento. |
| [GetEmbeddedHtml](../../groupdocs.editor/editabledocument/getembeddedhtml)() | Devuelve todo el contenido de este documento HTML con todos los recursos relacionados en forma de una única cadena, donde todos los recursos están incrustados dentro del marcado HTML en forma codificada en base64. |
| [Save](../../groupdocs.editor/editabledocument/save#save_1)(string) | Guarda este documento HTML en el archivo en la ruta especificada, donde se almacenará el marcado HTML, y en la carpeta adjunta con los recursos. |
| [Save](../../groupdocs.editor/editabledocument/save#save_2)(string, string) | Guarda este documento HTML en el archivo en la ruta especificada, donde se almacenará el marcado HTML, y en la carpeta adjunta con los recursos, que se encuentra en la ruta especificada. |
| [Save](../../groupdocs.editor/editabledocument/save#save)(TextWriter, HtmlSaveOptions) | Guarda el contenido de este [`EditableDocument`](../editabledocument) como documento HTML en el escritor de texto especificado, mientras que el segundo parámetro de opciones permite personalizar el procedimiento de guardado y especificar la devolución de llamada para guardar recursos |

## Eventos

| Nombre | Descripción |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editabledocument/disposed) | Evento, que ocurre cuando este documento Editable se elimina, justo después de terminar el proceso de eliminación |

### Observaciones

Una instancia de la clase `EditableDocument` puede ser producida por el método '[`Edit`](../editor/edit)' o creada por el propio usuario usando fábricas estáticas. `EditableDocument` almacena internamente el documento en su propio formato cerrado, que es compatible (convertible) con todos los formatos de importación y exportación que soporta GroupDocs.Editor. Para que el documento sea editable en cualquier editor WYSIWYG del lado del cliente (como CKEditor o TinyMCE), `EditableDocument` proporciona métodos para generar marcado HTML y producir recursos que pueden ser aceptados por el usuario.

### Ver también

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* namespace [GroupDocs.Editor](../../groupdocs.editor)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
