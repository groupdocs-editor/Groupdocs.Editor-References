---
title: "op_Explicit"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Convierte una cadena que representa una extensión de archivo a un objeto EmailFormatsgroupdocs.editor.formats/emailformats."
type: docs
weight: 150
url: /es/net/groupdocs.editor.formats/emailformats/op_explicit/
---
## EmailFormats Explicit operator

Convierte una cadena que representa una extensión de archivo a un objeto [`EmailFormats`](../../emailformats).

```csharp
public static explicit operator EmailFormats(string extension)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| extensión | String | La extensión de archivo a convertir. Si la extensión contiene varios puntos, se usa la parte después del último punto. |

### Valor devuelto

Un objeto [`EmailFormats`](../../emailformats) correspondiente a la extensión de archivo especificada.

### Excepciones

| excepción | condición |
| --- | --- |
| [EmailFormats](../../emailformats) | Se lanza cuando la extensión de archivo especificada es nula. |

### Ver también

* class [EmailFormats](../../emailformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
