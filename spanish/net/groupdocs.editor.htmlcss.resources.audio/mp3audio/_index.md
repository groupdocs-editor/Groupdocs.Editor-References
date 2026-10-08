---
title: "Mp3Audio"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Representa un recurso de audio de formato arbitrario"
type: docs
weight: 330
url: /es/net/groupdocs.editor.htmlcss.resources.audio/mp3audio/
---
## Mp3Audio class

Representa un recurso de audio de formato arbitrario

```csharp
public sealed class Mp3Audio : IEquatable<Mp3Audio>, IHtmlResource
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Mp3Audio](mp3audio)(string, Stream) | Crea una nueva clase Mp3Audio a partir del contenido MP3, representado como flujo de bytes, y con el nombre especificado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ByteContent](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/bytecontent) { get; } | Devuelve el contenido de esta fuente como flujo de bytes |
| [FilenameWithExtension](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/filenamewithextension) { get; } | Devuelve el nombre de archivo correcto de este contenido MP3, que consiste en nombre y extensión. Teóricamente puede diferir del nombre. |
| [IsDisposed](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/isdisposed) { get; } | Determina si este contenido MP3 está descartado o no |
| [Name](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/name) { get; } | Devuelve el nombre de este contenido MP3. Usualmente no contiene la extensión del nombre de archivo y teóricamente puede diferir del nombre de archivo. |
| [TextContent](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/textcontent) { get; } | Devuelve el contenido de este recurso MP3 como cadena codificada en base64. Este valor se almacena en caché después de la primera invocación. |
| [Type](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/type) { get; } | Devuelve un AudioType.Mp3 |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/dispose)() | Descarta este recurso MP3, descartando su contenido y haciendo que la mayoría de los métodos y propiedades no funcionen |
| [Equals](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/equals#equals_1)(IHtmlResource) | Comprueba esta instancia con el recurso HTML especificado por igualdad de referencia |
| [Equals](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/equals#equals)(Mp3Audio) | Comprueba esta instancia con el recurso de fuente especificado por igualdad de referencia |
| [Save](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/save)(string) | Guarda este recurso MP3 en el archivo especificado |
| static [IsValid](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/isvalid)(Stream) | Comprueba si el flujo especificado es un contenido MP3 válido |

## Eventos

| Nombre | Descripción |
| --- | --- |
| event [Disposed](../../groupdocs.editor.htmlcss.resources.audio/mp3audio/disposed) | Evento que ocurre cuando se elimina este contenido MP3 |

### Ver también

* interface [IHtmlResource](../../groupdocs.editor.htmlcss.resources/ihtmlresource)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Audio](../../groupdocs.editor.htmlcss.resources.audio)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
