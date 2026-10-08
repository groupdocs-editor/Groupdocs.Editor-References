---
title: "op_Explicit"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Convierte una cadena que representa una extensión de archivo a un objeto TextualFormatsgroupdocs.editor.formats/textualformats."
type: docs
weight: 100
url: /es/net/groupdocs.editor.formats/textualformats/op_explicit/
---
## TextualFormats Explicit operator

Convierte una cadena que representa una extensión de archivo a un objeto [`TextualFormats`](../../textualformats).

```csharp
public static explicit operator TextualFormats(string extension)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| extensión | String | La extensión de archivo a convertir. Si la extensión contiene varios puntos, se usa la parte después del último punto. |

### Valor devuelto

Un objeto [`TextualFormats`](../../textualformats) correspondiente a la extensión de archivo especificada.

### Excepciones

| excepción | condición |
| --- | --- |
| [TextualFormats](../../textualformats) | Se lanza cuando la extensión de archivo especificada es nula. |

### Ver también

* class [TextualFormats](../../textualformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
