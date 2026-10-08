---
title: "QuoteType"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Representa los caracteres de comilla simple y comilla doble"
type: docs
weight: 660
url: /es/net/groupdocs.editor.htmlcss.serialization/quotetype/
---
## QuoteType structure

Representa caracteres de comilla - comilla simple (') y comilla doble (")

```csharp
public struct QuoteType : IEquatable<QuoteType>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Character](../../groupdocs.editor.htmlcss.serialization/quotetype/character) { get; } | Carácter a entrecomillar |
| [Code](../../groupdocs.editor.htmlcss.serialization/quotetype/code) { get; } | Punto de código del carácter actual (U+0027 o U+0022) |
| [HtmlEncoded](../../groupdocs.editor.htmlcss.serialization/quotetype/htmlencoded) { get; } | Carácter codificado en HTML |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../groupdocs.editor.htmlcss.serialization/quotetype/equals#equals_1)(object) | Indica si esta instancia del tipo de comilla es igual al especificado sin conversión |
| [Equals](../../groupdocs.editor.htmlcss.serialization/quotetype/equals#equals)(QuoteType) | Indica si esta instancia del tipo de comilla es igual al especificado |
| override [GetHashCode](../../groupdocs.editor.htmlcss.serialization/quotetype/gethashcode)() | Devuelve un código hash para este carácter |
| override [ToString](../../groupdocs.editor.htmlcss.serialization/quotetype/tostring)() | Devuelve la cadena "SingleQuote" o "DoubleQuote" según el valor actual |
| [operator ==](../../groupdocs.editor.htmlcss.serialization/quotetype/op_equality) | Comprueba si dos valores "QuoteType" son iguales |
| [explicit operator](../../groupdocs.editor.htmlcss.serialization/quotetype/op_explicit#op_explicit) | Convierte la instancia especificada de [`QuoteType`](../quotetype) al Char (2 operadores) |
| [operator !=](../../groupdocs.editor.htmlcss.serialization/quotetype/op_inequality) | Comprueba si dos valores "QuoteType" no son iguales |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [DoubleQuote](../../groupdocs.editor.htmlcss.serialization/quotetype/doublequote) | Comilla doble (carácter U+0022 MARCA DE COMILLAS) |
| static readonly [SingleQuote](../../groupdocs.editor.htmlcss.serialization/quotetype/singlequote) | Comilla simple (carácter U+0027 APÓSTROFE) |

### Ver también

* namespace [GroupDocs.Editor.HtmlCss.Serialization](../../groupdocs.editor.htmlcss.serialization)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
