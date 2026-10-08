---
title: "op_Explicit"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Convierte una cadena que representa una extensión de archivo a un objeto EBookFormatsgroupdocs.editor.formats/ebookformats."
type: docs
weight: 60
url: /es/net/groupdocs.editor.formats/ebookformats/op_explicit/
---
## EBookFormats Explicit operator

Convierte una cadena que representa una extensión de archivo a un objeto [`EBookFormats`](../../ebookformats).

```csharp
public static explicit operator EBookFormats(string extension)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| extensión | String | La extensión de archivo a convertir. Si la extensión contiene varios puntos, se usa la parte después del último punto. |

### Valor devuelto

Un objeto [`EBookFormats`](../../ebookformats) correspondiente a la extensión de archivo especificada.

### Excepciones

| excepción | condición |
| --- | --- |
| [EBookFormats](../../ebookformats) | Se lanza cuando la extensión de archivo especificada es nula. |

### Ver también

* class [EBookFormats](../../ebookformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
