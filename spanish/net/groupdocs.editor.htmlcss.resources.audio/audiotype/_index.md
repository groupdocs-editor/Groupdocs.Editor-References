---
title: "AudioType"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Representa un formato de tipo de audio soportable"
type: docs
weight: 320
url: /es/net/groupdocs.editor.htmlcss.resources.audio/audiotype/
---
## AudioType structure

Representa un tipo de audio compatible (formato)

```csharp
public struct AudioType : IEquatable<AudioType>, IResourceType
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [Mp3](../../groupdocs.editor.htmlcss.resources.audio/audiotype/mp3) { get; } | Representa un formato de audio MPEG-1 Audio Layer III |
| static [Undefined](../../groupdocs.editor.htmlcss.resources.audio/audiotype/undefined) { get; } | Valor especial que marca un formato de audio indefinido, desconocido o no soportado |
| [FileExtension](../../groupdocs.editor.htmlcss.resources.audio/audiotype/fileextension) { get; } | Extensión de nombre de archivo (sin el carácter punto) para este formato de audio |
| [FormalName](../../groupdocs.editor.htmlcss.resources.audio/audiotype/formalname) { get; } | Nombre formal de este formato de audio |
| [MimeCode](../../groupdocs.editor.htmlcss.resources.audio/audiotype/mimecode) { get; } | Código MIME para este formato de audio |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.editor.htmlcss.resources.audio/audiotype/parsefromfilenamewithextension)(string) | Devuelve el valor AudioType, que es equivalente a la extensión de nombre de archivo extraída del nombre de archivo especificado |
| [Equals](../../groupdocs.editor.htmlcss.resources.audio/audiotype/equals#equals)(AudioType) | Determina si esta instancia es igual a la instancia "AudioType" especificada |
| override [Equals](../../groupdocs.editor.htmlcss.resources.audio/audiotype/equals#equals_1)(object) | Determina si esta instancia es igual al objeto no casteado especificado, que presumiblemente es otra instancia "AudioType" |
| override [GetHashCode](../../groupdocs.editor.htmlcss.resources.audio/audiotype/gethashcode)() | Devuelve un código hash, que es un número constante para este tipo de valor específico |
| [operator ==](../../groupdocs.editor.htmlcss.resources.audio/audiotype/op_equality) | Comprueba si dos valores "AudioType" son iguales |
| [operator !=](../../groupdocs.editor.htmlcss.resources.audio/audiotype/op_inequality) | Comprueba si dos valores "AudioType" no son iguales |

### Ver también

* interface [IResourceType](../../groupdocs.editor.htmlcss.resources/iresourcetype)
* namespace [GroupDocs.Editor.HtmlCss.Resources.Audio](../../groupdocs.editor.htmlcss.resources.audio)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
