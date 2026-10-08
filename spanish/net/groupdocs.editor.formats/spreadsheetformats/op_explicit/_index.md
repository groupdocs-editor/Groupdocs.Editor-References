---
title: "op_Explicit"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Convierte una cadena que representa una extensión de archivo a un objeto SpreadsheetFormatsgroupdocs.editor.formats/spreadsheetformats."
type: docs
weight: 180
url: /es/net/groupdocs.editor.formats/spreadsheetformats/op_explicit/
---
## SpreadsheetFormats Explicit operator

Convierte una cadena que representa una extensión de archivo a un objeto [`SpreadsheetFormats`](../../spreadsheetformats).

```csharp
public static explicit operator SpreadsheetFormats(string extension)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| extensión | String | La extensión de archivo a convertir. Si la extensión contiene varios puntos, se usa la parte después del último punto. |

### Valor devuelto

Un objeto [`SpreadsheetFormats`](../../spreadsheetformats) que corresponde a la extensión de archivo especificada.

### Excepciones

| excepción | condición |
| --- | --- |
| [SpreadsheetFormats](../../spreadsheetformats) | Se lanza cuando la extensión de archivo especificada es nula. |

### Ver también

* class [SpreadsheetFormats](../../spreadsheetformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
