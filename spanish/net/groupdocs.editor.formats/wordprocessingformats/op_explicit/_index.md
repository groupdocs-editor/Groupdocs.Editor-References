---
title: "op_Explicit"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Convierte una cadena que representa una extensión de archivo en un objeto WordProcessingFormatsgroupdocs.editor.formats/wordprocessingformats."
type: docs
weight: 140
url: /es/net/groupdocs.editor.formats/wordprocessingformats/op_explicit/
---
## WordProcessingFormats Explicit operator

Convierte una cadena que representa una extensión de archivo en un objeto [`WordProcessingFormats`](../../wordprocessingformats).

```csharp
public static explicit operator WordProcessingFormats(string extension)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| extensión | String | La extensión de archivo a convertir. Si la extensión contiene varios puntos, se usa la parte después del último punto. |

### Valor devuelto

Un objeto [`WordProcessingFormats`](../../wordprocessingformats) correspondiente a la extensión de archivo especificada.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Se lanza cuando la extensión de archivo especificada es nula. |

### Ver también

* class [WordProcessingFormats](../../wordprocessingformats)
* namespace [GroupDocs.Editor.Formats](../../../groupdocs.editor.formats)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
