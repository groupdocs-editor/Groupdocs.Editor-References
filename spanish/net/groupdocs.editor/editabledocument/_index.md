---
title: EditableDocument
second_title: Referencia de API de GroupDocs.Editor para .NET
description: Documento intermedio que contiene contenido antes y después de editar
type: docs
weight: 10
url: /es/net/groupdocs.editor/editabledocument/
---
## EditableDocument class

Documento intermedio, que contiene contenido antes y después de editar

```csharp
public sealed class EditableDocument : IAuxDisposable
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AllResources](../../groupdocs.editor/editabledocument/allresources) { get; } | Devuelve una lista de todos los recursos existentes: todas las hojas de estilo, imágenes de HTML y todas las hojas de estilo, fuentes |
| [Audio](../../groupdocs.editor/editabledocument/audio) { get; } | Devuelve una lista de recursos de audio |
| [Css](../../groupdocs.editor/editabledocument/css) { get; } | Devuelve una lista de recursos CSS |
| [Fonts](../../groupdocs.editor/editabledocument/fonts) { get; } | Permite obtener recursos de fuentes externas, que son utilizadas por este documento HTML |
| [Images](../../groupdocs.editor/editabledocument/images) { get; } | Permite obtener recursos de imágenes externas (imágenes raster), que son utilizadas por este documento HTML |
| [IsDisposed](../../groupdocs.editor/editabledocument/isdisposed) { get; } | Determina si este documento Editable ya fue eliminado (verdadero) o no (falso) |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromFile](../../groupdocs.editor/editabledocument/fromfile)(string, string) | Fábrica estática, que crea una instancia de EditableDocument a partir de un archivo HTML, que se especifica mediante una ruta al propio archivo *.html y una carpeta con recursos vinculados |
| static [FromMarkup](../../groupdocs.editor/editabledocument/frommarkup)(string, IEnumerable&lt;IHtmlResource&gt;) | Fábrica estática, que crea una instancia de EditableDocument a partir del marcado HTML especificado y un conjunto de recursos vinculados correspondientes |
| static [FromMarkupAndResourceFolder](../../groupdocs.editor/editabledocument/frommarkupandresourcefolder)(string, string) | Fábrica estática, que crea una instancia de EditableDocument a partir de un marcado HTML específico y de recursos, ubicados en la carpeta, especificada por la ruta completa |
| [Dispose](../../groupdocs.editor/editabledocument/dispose)() | Elimina esta instancia de documento Editable, eliminando su contenido y haciendo que sus métodos y propiedades no funcionen |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent)() | Devuelve el cuerpo del documento HTML (contenido entre abrir y cerrar las etiquetas BODY sin estas etiquetas) como una cadena. |
| [GetBodyContent](../../groupdocs.editor/editabledocument/getbodycontent#getbodycontent_1)(string) | Devuelve el cuerpo del documento HTML (contenido entre abrir y cerrar las etiquetas BODY sin estas etiquetas) como una cadena, donde los enlaces a los recursos externos contienen el prefijo especificado. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent)() | Devuelve el contenido general del documento HTML como una cadena. |
| [GetContent](../../groupdocs.editor/editabledocument/getcontent#getcontent_1)(string, string) | Devuelve el contenido general del documento HTML como una cadena, donde los enlaces a los recursos externos contienen el prefijo especificado. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent)() | Devuelve el contenido de todas las hojas de estilo externas como una lista de cadenas, donde una cadena representa una hoja de estilo. Devuelve una lista vacía, si no hay CSS para este documento. |
| [GetCssContent](../../groupdocs.editor/editabledocument/getcsscontent#getcsscontent_1)(string, string) | Devuelve el contenido de todas las hojas de estilo externas como una lista de cadenas, donde una cadena representa una hoja de estilo. El prefijo especificado se aplicará a cada enlace al recurso externo en cada hoja de estilo resultante. Devuelve una lista vacía, si no hay CSS para esto documento. |
| [GetEmbeddedHtml](../../groupdocs.editor/editabledocument/getembeddedhtml)() | Devuelve todo el contenido de este documento HTML con todos los recursos relacionados en forma de una sola cadena, donde todos los recursos están incrustados dentro del marcado HTML en una forma codificada en base64. |
| [Save](../../groupdocs.editor/editabledocument/save#save)(string) | Guarda este documento HTML en el archivo de la ruta especificada, donde se almacenará el marcado HTML, y en la carpeta adjunta con recursos. |
| [Save](../../groupdocs.editor/editabledocument/save#save_1)(string, string) | Guarda este documento HTML en el archivo en la ruta especificada, donde se almacenará el marcado HTML, y en la carpeta adjunta con recursos, que se encuentra en la ruta especificada. |

## Eventos

| Nombre | Descripción |
| --- | --- |
| event [Disposed](../../groupdocs.editor/editabledocument/disposed) | Evento, que ocurre cuando se elimina este documento Editable, justo después de finalizar el proceso de eliminación |

### Observaciones

La instancia de la clase EditableDocument puede ser producida por el '[`Edit`](../editor/edit) o creado por el propio usuario utilizando fábricas estáticas. EditableDocument almacena internamente el documento en su propio formato cerrado, que es compatible (convertible) con todos los formatos de importación y exportación, que admite GroupDocs.Editor. Para hacer que el documento sea editable en cualquier editor WYSIWYG del lado del cliente (como CKEditor o TinyMCE), EditableDocument proporciona métodos para generar marcado HTML y producir recursos que pueden ser aceptados por el usuario.

### Ver también

* interface [IAuxDisposable](../../groupdocs.editor.htmlcss.resources/iauxdisposable)
* espacio de nombres [GroupDocs.Editor](../../groupdocs.editor)
* asamblea [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
