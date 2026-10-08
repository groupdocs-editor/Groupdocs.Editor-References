---
title: "FontStyle"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Definierar hur teckensnittet ska stylas med ett normalt, kursivt eller snett teckensnitt från dess fontfamily."
type: docs
weight: 270
url: /sv/net/groupdocs.editor.htmlcss.css.properties/fontstyle/
---
## FontStyle structure

Definierar hur teckensnittet ska stiliseras med: en normal, kursiv eller sned (oblique) stil från dess font-family.

```csharp
public struct FontStyle
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontstyle/isinitial) { get; } | Indikerar om detta font-style har ett initialt värde (Normal) |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontstyle/value) { get; } | Returnerar ett värde för detta font style som en sträng |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontstyle/equals#equals)(FontStyle) | Bestämmer om detta font-style-instans är lika med den angivna |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontstyle/equals#equals_1)(object) | Bestämmer om detta font-style-instans är lika med den angivna utan typkonvertering |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontstyle/gethashcode)() | Returnerar en hash‑kod för denna instans |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontstyle/tryparse)(string, out FontStyle) | Försöker känna igen ett angivet nyckelord som ett korrekt nyckelordsvärde för 'font-style' och returnerar det vid lyckat resultat eller NULL vid misslyckande. |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontstyle/op_equality) | Kontrollerar om två \"FontStyle\"‑värden är lika |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontstyle/op_inequality) | Kontrollerar om två \"FontStyle\"‑värden inte är lika |

## Fält

| Namn | Beskrivning |
| --- | --- |
| static readonly [Italic](../../groupdocs.editor.htmlcss.css.properties/fontstyle/italic) | Väljer ett teckensnitt som klassificeras som kursivt. Om ingen kursiv version av teckensnittet finns, används en som klassificeras som sned. Om ingen av dem finns, simuleras stilen artificiellt. |
| static readonly [Normal](../../groupdocs.editor.htmlcss.css.properties/fontstyle/normal) | Väljer ett teckensnitt som klassificeras som normalt inom en font-family. Initialt värde. |
| static readonly [Oblique](../../groupdocs.editor.htmlcss.css.properties/fontstyle/oblique) | Väljer ett teckensnitt som klassificeras som sned. Om ingen sned version av teckensnittet finns, används en som klassificeras som kursivt. Om ingen av dem finns, simuleras stilen artificiellt. |

### Se även

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
