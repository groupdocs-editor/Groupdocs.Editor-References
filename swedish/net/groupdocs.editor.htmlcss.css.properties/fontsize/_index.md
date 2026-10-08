---
title: "FontSize"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Representerar en teckensnittsstorlek som en speciell enhet eller ett längdvärde som specificerar teckensnittets storlek, historiskt bredden på den stora bokstaven M."
type: docs
weight: 260
url: /sv/net/groupdocs.editor.htmlcss.css.properties/fontsize/
---
## FontSize structure

Representerar en teckenstorlek som en speciell enhet eller ett längdvärde, vilket specificerar teckenstorleken (historiskt bredden på den stora \"M\").

```csharp
public struct FontSize : IEquatable<FontSize>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [IsAbsoluteSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isabsolutesize) { get; } | Indikerar om detta font-size är definierat med en absolut storlek som ett nyckelord, baserat på användarens standardteckensnittsstorlek (som är medium) |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontsize/isinitial) { get; } | Indikerar om detta font-size har ett initialt värde (Medium) |
| [IsLengthDefined](../../groupdocs.editor.htmlcss.css.properties/fontsize/islengthdefined) { get; } | Indikerar om detta font-size är definierat med ett [`Length`](../../groupdocs.editor.htmlcss.css.datatypes/length)-värde |
| [IsRelativeSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isrelativesize) { get; } | Indikerar om detta font-size är definierat med en relativ storlek som ett nyckelord. Teckensnittet kommer att vara större eller mindre i förhållande till föräldraelementets teckensnittsstorlek, ungefär enligt den ratio som används för att separera de absoluta storleksnyckelorden. |
| [Length](../../groupdocs.editor.htmlcss.css.properties/fontsize/length) { get; } | Ett längdvärde, om detta font-size definierades med det, annars kastas ett undantag |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontsize/value) { get; } | Returnerar ett värde för denna teckensnittsstorlek som en sträng |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [FromLength](../../groupdocs.editor.htmlcss.css.properties/fontsize/fromlength)(Length) | Skapar ett font-size från angiven längd |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals)(FontSize) | Bestämmer om detta font-size-instans är lika med den angivna |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals_1)(object) | Bestämmer om detta font-size-instans är lika med den angivna utan typkonvertering |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontsize/gethashcode)() | Returnerar en hash‑kod för denna instans |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontsize/tryparse)(string, out FontSize) | Försöker känna igen ett angivet nyckelord som ett korrekt nyckelordsvärde för 'font-size' och returnerar det vid lyckat resultat eller NULL vid misslyckande. |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_equality) | Kontrollerar om två "FontSize"-värden är lika |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_inequality) | Kontrollerar om två "FontSize"-värden inte är lika |

## Fält

| Namn | Beskrivning |
| --- | --- |
| static readonly [Large](../../groupdocs.editor.htmlcss.css.properties/fontsize/large) | Den normalt stora absoluta storleken |
| static readonly [Larger](../../groupdocs.editor.htmlcss.css.properties/fontsize/larger) | Större relativ storlek - teckensnittet blir större i förhållande till föräldraelementets font-size, ungefär enligt förhållandet som används för att separera de absoluta storleksnyckelorden ovan. |
| static readonly [Medium](../../groupdocs.editor.htmlcss.css.properties/fontsize/medium) | Mellanstorlek. Initialt värde. |
| static readonly [Small](../../groupdocs.editor.htmlcss.css.properties/fontsize/small) | Den normalt lilla absoluta storleken |
| static readonly [Smaller](../../groupdocs.editor.htmlcss.css.properties/fontsize/smaller) | Mindre relativ storlek - teckensnittet blir mindre i förhållande till föräldraelementets font-size, ungefär enligt förhållandet som används för att separera de absoluta storleksnyckelorden ovan. |
| static readonly [XLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xlarge) | Den medelmåttigt stora absoluta storleken |
| static readonly [XSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xsmall) | Den medelmåttigt lilla absoluta storleken |
| static readonly [XxLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxlarge) | Den mycket stora absoluta storleken |
| static readonly [XxSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxsmall) | Den mycket lilla absoluta storleken |

### Se även

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
