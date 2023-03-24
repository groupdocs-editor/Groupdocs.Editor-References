---
title: FontStyle
second_title: GroupDocs.Editor för .NET API-referens
description: Definierar hur teckensnittet ska utformas med ett normalt kursivt eller snett ansikte från dess teckensnittsfamilj.
type: docs
weight: 300
url: /sv/net/groupdocs.editor.htmlcss.css.properties/fontstyle/
---
## FontStyle structure

Definierar hur teckensnittet ska utformas med: ett normalt, kursivt eller snett ansikte från dess teckensnittsfamilj.

```csharp
public struct FontStyle
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontstyle/isinitial) { get; } | Indikerar om denna typsnittsstil har ett initialt värde (Normal) |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontstyle/value) { get; } | Returnerar ett värde för denna typsnittsstil som en string |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontstyle/equals#equals)(FontStyle) | Avgör om den här fontstilsinstansen är lika med specific |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontstyle/equals#equals_1)(object) | Avgör om den här fontstilsinstansen är lika med specificerad uncasted |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontstyle/gethashcode)() | Returnerar en hash-kod för denna instans |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontstyle/tryparse)(string, out FontStyle) | Försöker känna igen ett specificerat nyckelord som ett korrekt nyckelordsvärde för "font-style" och returnerar det vid framgång eller NULL vid misslyckande. |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontstyle/op_equality) | Kontrollerar om två "FontStyle"-värden är lika |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontstyle/op_inequality) | Kontrollerar om två "FontStyle"-värden inte är lika |

## Fält

| namn | Beskrivning |
| --- | --- |
| static readonly [Italic](../../groupdocs.editor.htmlcss.css.properties/fontstyle/italic) | Väljer ett teckensnitt som klassificeras som kursivt. Om det inte finns någon kursiv version av ansiktet används istället en som klassificeras som sned. Om ingetdera är tillgängligt simuleras stilen artificiellt. |
| static readonly [Normal](../../groupdocs.editor.htmlcss.css.properties/fontstyle/normal) | Väljer ett teckensnitt som klassificeras som normalt inom en teckensnittsfamilj. Initialt värde. |
| static readonly [Oblique](../../groupdocs.editor.htmlcss.css.properties/fontstyle/oblique) | Väljer ett teckensnitt som klassificeras som sned. Om ingen sned version av ansiktet finns tillgänglig används istället en som klassificeras som kursiv. Om ingetdera är tillgängligt simuleras stilen artificiellt. |

### Se även

* namnutrymme [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* hopsättning [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->