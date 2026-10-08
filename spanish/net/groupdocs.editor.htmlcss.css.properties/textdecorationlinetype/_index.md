---
title: "TextDecorationLineType"
second_title: "GroupDocs.Editor para .NET Referencia de API"
description: "Representa los tipos de línea de decoración de texto: subrayado, guión bajo, sobrelínea y tachado."
type: docs
weight: 290
url: /es/net/groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/
---
## TextDecorationLineType structure

Representa los tipos de línea de decoración de texto: subrayado (guion bajo), sobrelínea y tachado (línea a través)

```csharp
public struct TextDecorationLineType : IEquatable<TextDecorationLineType>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isinitial) { get; } | Indica si esta instancia tiene un valor inicial — Ninguno |
| [IsLineThrough](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/islinethrough) { get; } | Indica si el tachado (line-through) está habilitado |
| [IsOverline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isoverline) { get; } | Indica si la sobrelínea está habilitada |
| [IsUnderline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isunderline) { get; } | Indica si el subrayado (guión bajo) está habilitado |
| [Value](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/value) { get; } | Devuelve un valor de todas las banderas en esta instancia como texto |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [FromFlags](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/fromflags)(bool, bool, bool) | Crea y devuelve una instancia de [`TextDecorationLineType`](../textdecorationlinetype) con banderas, definidas por los parámetros especificados |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/equals#equals_1)(object) | Indica si esta instancia de [`TextDecorationLineType`](../textdecorationlinetype) es igual a la especificada sin convertir |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/equals#equals)(TextDecorationLineType) | Indica si esta instancia de [`TextDecorationLineType`](../textdecorationlinetype) es igual a la especificada |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/gethashcode)() | Devuelve un código hash de esta instancia |
| override [ToString](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/tostring)() | Devuelve un valor de todas las banderas en esta instancia como texto |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/tryparse)(string, out TextDecorationLineType) | Intenta analizar una cadena especificada y devolver una instancia válida de [`TextDecorationLineType`](../textdecorationlinetype) |
| [operator +](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_addition) | Combina (fusiona) dos tipos de línea especificados y produce un nuevo tipo de línea resultante, donde las banderas se combinan (unión) |
| [operator /](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_division) | Devuelve una intersección entre el primer y segundo tipo de línea, donde solo están habilitadas las banderas que están habilitadas simultáneamente en ambos operandos. Tiene la mayor prioridad entre todos los operadores (superior a la unión y la diferencia) |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_equality) | Comprueba si dos valores "TextDecorationLineType" son iguales |
| [explicit operator](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_explicit#op_explicit_1) | Convierte un Byte (octeto de 8 bits) específico al [`TextDecorationLineType`](../textdecorationlinetype) correspondiente, lanza una excepción si la conversión es inválida (2 operadores) |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_inequality) | Comprueba si dos valores "TextDecorationLineType" no son iguales |
| [operator -](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_subtraction) | Resta el segundo tipo de línea especificado del primer tipo de línea especificado y produce un nuevo tipo de línea resultante, donde solo están presentes las banderas del primer operando que no se encuentran en el segundo operando (diferencia) |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [LineThrough](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/linethrough) | Cada línea de texto tiene una línea a través del medio. |
| static readonly [None](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/none) | No produce decoración de texto. Valor inicial. |
| static readonly [Overline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/overline) | Cada línea de texto tiene una línea por encima. |
| static readonly [Underline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/underline) | Cada línea de texto está subrayada. |

### Observaciones

Estructura inmutable. Similar a https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line

### Ver también

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.editor.dll -->
