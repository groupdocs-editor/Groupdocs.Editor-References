---
title: "TextResourceBase"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Clase base para cualquier recurso de texto compatible con contenido textual y codificación"
type: docs
weight: 630
url: /es/net/groupdocs.editor.htmlcss.resources.textual/textresourcebase/
---
## TextResourceBase class

Clase base para cualquier recurso de texto compatible con contenido textual y codificación

```csharp
public abstract class TextResourceBase : IHtmlResource
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/bytecontent) { get; } | Devuelve el contenido de este recurso de texto como flujo de bytes con la codificación original |
| [Encoding](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/encoding) { get; } | Devuelve la codificación de este recurso textual. Normalmente devuelve UTF-8. |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/filenamewithextension) { get; } | Devuelve el nombre de archivo correcto de este recurso de texto, que consiste en el nombre y la extensión |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/isdisposed) { get; } | Determina si este recurso de texto está eliminado o no |
| [Name](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/name) { get; } | Devuelve el nombre de este recurso de texto sin la extensión del archivo |
| [TextContent](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/textcontent) { get; } | Devuelve el contenido de este recurso de texto como una cadena estándar |
| abstract [Type](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/type) { get; } | En la implementación, el tipo debe devolver información sobre el tipo del recurso de texto |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/dispose)() | Elimina este recurso de texto, eliminando su contenido y haciendo que la mayoría de los métodos y propiedades no funcionen. Tolerante a llamadas múltiples. |
| [Equals](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/equals#equals)(IHtmlResource) | Comprueba esta instancia con la especificada en igualdad. |
| [Save](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/save)(string) | Guarda este recurso de texto en el archivo especificado |

## Eventos

| Nombre | Descripción |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.textual/textresourcebase/disposed) | Evento que ocurre cuando este recurso de texto es eliminado |

### Ver también

* interface [IHtmlResource](../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Textual](../../groupdocs.editor.htmlcss.resources.textual)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
