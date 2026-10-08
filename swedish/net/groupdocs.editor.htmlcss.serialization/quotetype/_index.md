---
title: "QuoteType"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Representerar citattecken enkelfnutt och dubbelfnutt"
type: docs
weight: 660
url: /sv/net/groupdocs.editor.htmlcss.serialization/quotetype/
---
## QuoteType structure

Representerar citattecken - enkelfnutt (') och dubbelfnutt (\")

```csharp
public struct QuoteType : IEquatable<QuoteType>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Character](../../groupdocs.editor.htmlcss.serialization/quotetype/character) { get; } | Tecken att citera |
| [Code](../../groupdocs.editor.htmlcss.serialization/quotetype/code) { get; } | Kodpunkt för det aktuella tecknet (U+0027 eller U+0022) |
| [HtmlEncoded](../../groupdocs.editor.htmlcss.serialization/quotetype/htmlencoded) { get; } | HTML-kodat tecken |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../groupdocs.editor.htmlcss.serialization/quotetype/equals#equals_1)(object) | Indikerar om denna instans av citattypen är lika med den angivna okastade |
| [Equals](../../groupdocs.editor.htmlcss.serialization/quotetype/equals#equals)(QuoteType) | Indikerar om denna instans av citattypen är lika med den angivna |
| override [GetHashCode](../../groupdocs.editor.htmlcss.serialization/quotetype/gethashcode)() | Returnerar en hashkod för detta tecken |
| override [ToString](../../groupdocs.editor.htmlcss.serialization/quotetype/tostring)() | Returnerar en "SingleQuote"- eller "DoubleQuote"-sträng beroende på det aktuella värdet |
| [operator ==](../../groupdocs.editor.htmlcss.serialization/quotetype/op_equality) | Kontrollerar om två "QuoteType"-värden är lika |
| [explicit operator](../../groupdocs.editor.htmlcss.serialization/quotetype/op_explicit#op_explicit) | Kastar den angivna [`QuoteType`](../quotetype)-instansen till Char (2 operatorer) |
| [operator !=](../../groupdocs.editor.htmlcss.serialization/quotetype/op_inequality) | Kontrollerar om två "QuoteType"-värden inte är lika |

## Fält

| Namn | Beskrivning |
| --- | --- |
| static readonly [DoubleQuote](../../groupdocs.editor.htmlcss.serialization/quotetype/doublequote) | Dubbelfnutt (U+0022-tecken) |
| static readonly [SingleQuote](../../groupdocs.editor.htmlcss.serialization/quotetype/singlequote) | Enkelfnutt (U+0027-tecken) |

### Se även

* namespace [GroupDocs.Editor.HtmlCss.Serialization](../../groupdocs.editor.htmlcss.serialization)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
