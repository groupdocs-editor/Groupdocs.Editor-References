---
title: "FontResourceBase"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Clase base para cualquier tipo de fuente compatible como recurso para el documento HTML con todas sus propiedades."
type: docs
weight: 350
url: /es/net/groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/
---
## FontResourceBase class

Clase base para cualquier tipo de fuente compatible como recurso para el documento HTML con todas sus propiedades.

```csharp
public abstract class FontResourceBase : IEquatable<FontResourceBase>, IHtmlResource
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/bytecontent) { get; } | Devuelve el contenido de esta fuente como flujo de bytes |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/filenamewithextension) { get; } | Devuelve el nombre de archivo correcto de este recurso de fuente, que consiste en el nombre y la extensión. Teóricamente puede diferir del nombre. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/isdisposed) { get; } | Determina si esta fuente está eliminada o no |
| [Name](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/name) { get; } | Devuelve el nombre de este recurso de fuente. Normalmente no contiene la extensión del nombre de archivo y teóricamente puede diferir del nombre de archivo. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/textcontent) { get; } | Devuelve el contenido de esta fuente como una cadena codificada en base64. Este valor se almacena en caché después de la primera invocación. |
| abstract [Type](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/type) { get; } | En el tipo de implementación debe devolver información sobre el tipo de recurso de fuente específico como una instancia del tipo FontType específico, que encapsula toda la información específica del tipo |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/dispose)() | Elimina este recurso de fuente, eliminando su contenido y haciendo que la mayoría de los métodos y propiedades no funcionen |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals#equals)(FontResourceBase) | Comprueba esta instancia con el recurso de fuente especificado por igualdad de referencia |
| [Equals](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/equals#equals_1)(IHtmlResource) | Comprueba esta instancia con el recurso HTML especificado por igualdad de referencia |
| [Save](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/save)(string) | Guarda esta fuente en el archivo especificado |

## Eventos

| Nombre | Descripción |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.fonts/fontresourcebase/disposed) | Evento que ocurre cuando esta fuente es eliminada |

### Ver también

* interface [IHtmlResource](../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Fonts](../../groupdocs.editor.htmlcss.resources.fonts)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
