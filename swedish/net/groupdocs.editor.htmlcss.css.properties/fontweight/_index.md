---
title: "FontWeight"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Fontweight-egenskapen anger vikten eller fetheten för teckensnittet. Tillgängliga vikter beror på den fontfamily som för närvarande är inställd."
type: docs
weight: 280
url: /sv/net/groupdocs.editor.htmlcss.css.properties/fontweight/
---
## FontWeight structure

Font-weight‑egenskapen anger vikten (eller fetheten) på teckensnittet. Tillgängliga vikter beror på den font-family som för närvarande är inställd.

```csharp
public struct FontWeight : IEquatable<FontWeight>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.properties/fontweight/isabsolute) { get; } | Anger om detta font-weight-instans lagrar ett absolut värde för vikten (fetheten) av teckensnittet, som ett heltal |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontweight/isinitial) { get; } | Indikerar om detta font-size har ett initialt värde (Medium) |
| [IsRelative](../../groupdocs.editor.htmlcss.css.properties/fontweight/isrelative) { get; } | Anger om detta font-weight-instans lagrar ett relativt värde för vikten (fetheten) av teckensnittet - jämfört med fetheten hos föräldraelementet |
| [Number](../../groupdocs.editor.htmlcss.css.properties/fontweight/number) { get; } | Returnerar ett tal - heltalsvärde mellan 1 och 1000, inklusive, som beskriver teckensnittets fethet, eller kastar ett undantag om den aktuella fetheten inte är absolut utan relativ |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontweight/value) { get; } | Returnerar ett värde för detta font-weight som en sträng |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [FromNumber](../../groupdocs.editor.htmlcss.css.properties/fontweight/fromnumber)(ushort) | Skapar ett font-weight från angivet tal |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontweight/equals#equals)(FontWeight) | Bestämmer om angivna FontWeight-instanser är lika |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontweight/equals#equals_1)(object) | Bestämmer om detta FontWeight-instans är lika med ett angivet okastat värde |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontweight/gethashcode)() | Returnerar en hash‑kod för denna instans |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontweight/tryparse)(string, out FontWeight) | Försöker tolka en angiven sträng och returnera en giltig FontWeight-instans vid lyckat resultat |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontweight/op_equality) | Kontrollerar om två "FontWeight"-värden är lika |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontweight/op_inequality) | Kontrollerar om två "FontWeight"-värden inte är lika |

## Fält

| Namn | Beskrivning |
| --- | --- |
| static readonly [Bold](../../groupdocs.editor.htmlcss.css.properties/fontweight/bold) | Fet teckensnittsvikt. Samma som 700. |
| static readonly [Bolder](../../groupdocs.editor.htmlcss.css.properties/fontweight/bolder) | En relativ teckensnittsvikt tyngre än föräldraelementet |
| static readonly [Lighter](../../groupdocs.editor.htmlcss.css.properties/fontweight/lighter) | En relativ teckensnittsvikt som är lättare än föräldraelementet |
| static readonly [Normal](../../groupdocs.editor.htmlcss.css.properties/fontweight/normal) | Normal teckensnittsvikt. Samma som 400. |

### Se även

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
