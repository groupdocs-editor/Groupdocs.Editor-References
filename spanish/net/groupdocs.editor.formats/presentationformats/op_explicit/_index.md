---
title: "op_Explicit"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Convierte una cadena que representa una extensión de archivo en un objeto PresentationFormatsgroupdocs.editor.formats/presentationformats."
type: docs
weight: 150
url: /es/net/groupdocs.editor.formats/presentationformats/op_explicit/
---
## PresentationFormats Explicit operator

Convierte una cadena que representa una extensión de archivo en un objeto [`PresentationFormats`](../../presentationformats).

```csharp
public static explicit operator PresentationFormats(string extension)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| extensión | String | La extensión de archivo a convertir. Si la extensión contiene varios puntos, se usa la parte después del último punto. |

### Valor devuelto

Un objeto [`PresentationFormats`](../../presentationformats) correspondiente a la extensión de archivo especificada.

### Excepciones

| excepción | condición |
| --- | --- |
| [PresentationFormats](../../presentationformats) | Se lanza cuando la extensión de archivo especificada es nula. |

### Ver también

* class [PresentationFormats](../../presentationformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
