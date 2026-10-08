---
title: "op_Explicit"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Convierte la instancia especificada de QuoteTypegroupdocs.editor.htmlcss.serialization/quotetype al Char."
type: docs
weight: 100
url: /es/net/groupdocs.editor.htmlcss.serialization/quotetype/op_explicit/
---
## explicit operator {#op_explicit}

Convierte la instancia especificada de [`QuoteType`](../../quotetype) al Char.

```csharp
public static explicit operator char(QuoteType quote)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| cita | QuoteType | Instancia de tipo Quote para convertir |

### Ver también

* struct [QuoteType](../../quotetype)
* namespace [GroupDocs.Editor.HtmlCss.Serialization](../../../groupdocs.editor.htmlcss.serialization)
* assembly [GroupDocs.Editor](../../../)

---

## explicit operator {#op_explicit_1}

Convierte un Char específico al [`QuoteType`](../../quotetype) correspondiente, lanza una excepción si la conversión no es válida.

```csharp
public static explicit operator QuoteType(char character)
```

| Parameter | Type | Descripción |
| --- | --- | --- |
| carácter | Carácter | Una comilla simple (U+0027 APOSTROPHE) o una comilla doble (U+0022 QUOTATION MARK) carácter. Se lanzará una excepción si se especifica cualquier otro carácter. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | El Carácter especificado no es ni una comilla ni un apóstrofe |

### Ver también

* struct [QuoteType](../../quotetype)
* namespace [GroupDocs.Editor.HtmlCss.Serialization](../../../groupdocs.editor.htmlcss.serialization)
* assembly [GroupDocs.Editor](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
