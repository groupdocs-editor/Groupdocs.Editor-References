---
title: op_Explicit
second_title: Referencia de API de GroupDocs.Editor para .NET
description: Repartos especificadosQuoteTypegroupdocs.editor.htmlcss.serialization/quotetype instancia a laChar
type: docs
weight: 90
url: /es/net/groupdocs.editor.htmlcss.serialization/quotetype/op_explicit/
---
## explicit operator {#op_explicit}

Repartos especificados[`QuoteType`](../../quotetype) instancia a laChar

```csharp
public static explicit operator char(QuoteType quote)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| quote | QuoteType | Instancia de tipo de cotización para lanzar |

### Ver también

* struct [QuoteType](../../quotetype)
* espacio de nombres [GroupDocs.Editor.HtmlCss.Serialization](../../quotetype)
* asamblea [GroupDocs.Editor](../../../)

---

## explicit operator {#op_explicit_1}

Repartos específicosChar a la correspondiente[`QuoteType`](../../quotetype) , lanza una excepción si la conversión no es válida

```csharp
public static explicit operator QuoteType(char character)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| character | Char | Un carácter de comillas simples (U+0027 APÓSTROF) o comillas dobles (U+0022 COMILLAS). Se lanzará una excepción si se especifica cualquier otro carácter. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | EspecificadoChar no es ni comillas ni apóstrofe |

### Ver también

* struct [QuoteType](../../quotetype)
* espacio de nombres [GroupDocs.Editor.HtmlCss.Serialization](../../quotetype)
* asamblea [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->