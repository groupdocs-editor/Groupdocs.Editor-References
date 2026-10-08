---
title: "TextDecorationLineType"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Representerar typer av textdekorationens linje understrykning, understreck, överlinje och genomstrykning"
type: docs
weight: 290
url: /sv/net/groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/
---
## TextDecorationLineType structure

Representerar typer av textdekorationens linje: understrykning (underscore), överlinje och genomstrykning (strikethrough)

```csharp
public struct TextDecorationLineType : IEquatable<TextDecorationLineType>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isinitial) { get; } | Indikerar om detta objekt har ett initialt värde — None |
| [IsLineThrough](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/islinethrough) { get; } | Indikerar om genomstrykning (strikethrough) är aktiverad |
| [IsOverline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isoverline) { get; } | Indikerar om överlinje är aktiverad |
| [IsUnderline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isunderline) { get; } | Indikerar om understrykning (underscore) är aktiverad |
| [Value](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/value) { get; } | Returnerar ett värde av alla flaggor i detta objekt som text |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [FromFlags](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/fromflags)(bool, bool, bool) | Skapar och returnerar ett [`TextDecorationLineType`](../textdecorationlinetype)-objekt med flaggor, definierade av de angivna parametrarna |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/equals#equals_1)(object) | Indikerar om detta [`TextDecorationLineType`](../textdecorationlinetype)-objekt är lika med den specificerade okastade |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/equals#equals)(TextDecorationLineType) | Indikerar om detta [`TextDecorationLineType`](../textdecorationlinetype)-objekt är lika med den specificerade |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/gethashcode)() | Returnerar en hashkod för detta objekt |
| override [ToString](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/tostring)() | Returnerar ett värde av alla flaggor i detta objekt som text |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/tryparse)(string, out TextDecorationLineType) | Försöker tolka en specificerad sträng och returnera ett giltigt [`TextDecorationLineType`](../textdecorationlinetype)-objekt |
| [operator +](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_addition) | Kombinerar (slår ihop) två specificerade linjetyper och producerar en ny resulterande linjetyp, där flaggorna slås samman (union) |
| [operator /](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_division) | Returnerar en skärning mellan första och andra linjetyper, där endast de flaggor som är aktiverade samtidigt i båda operanderna är påslagna. Har högsta prioritet bland alla operatorer (högre än union och differens) |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_equality) | Kontrollerar om två "TextDecorationLineType"-värden är lika |
| [explicit operator](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_explicit#op_explicit_1) | Kastar specifik Byte (8-bitars oktett) till motsvarande [`TextDecorationLineType`](../textdecorationlinetype), kastar undantag om omvandlingen är ogiltig (2 operatorer) |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_inequality) | Kontrollerar om två "TextDecorationLineType"-värden inte är lika |
| [operator -](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_subtraction) | Subtraherar den andra specificerade linjetypen från den första specificerade linjetypen och producerar en ny resulterande linjetyp, där endast de flaggor från den första operanden som inte finns i den andra operanden är närvarande (differens) |

## Fält

| Namn | Beskrivning |
| --- | --- |
| static readonly [LineThrough](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/linethrough) | Varje textrad har en linje genom mitten. |
| static readonly [None](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/none) | Producerar ingen textdekoration. Initialvärde. |
| static readonly [Overline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/overline) | Varje textrad har en linje ovanför den. |
| static readonly [Underline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/underline) | Varje textrad är understruken. |

### Anmärkningar

Oföränderlig struct. Liknande https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line

### Se även

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
