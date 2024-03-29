---
title: FontWeight
second_title: GroupDocs.Editor för .NET API-referens
description: Egenskapen Fontweight anger vikten eller fetheten för teckensnittet. De tillgängliga vikterna beror på typsnittsfamiljen som för närvarande är inställd.
type: docs
weight: 310
url: /sv/net/groupdocs.editor.htmlcss.css.properties/fontweight/
---
## FontWeight structure

Egenskapen Font-weight anger vikten (eller fetheten) för teckensnittet. De tillgängliga vikterna beror på typsnittsfamiljen som för närvarande är inställd.

```csharp
public struct FontWeight : IEquatable<FontWeight>
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.properties/fontweight/isabsolute) { get; } | Indikerar om den här font-weight-instansen lagrar ett absolut värde på teckensnittets vikt (fethet) som ett heltal |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontweight/isinitial) { get; } | Indikerar om den här teckensnittsstorleken har ett initialt värde (Medium) |
| [IsRelative](../../groupdocs.editor.htmlcss.css.properties/fontweight/isrelative) { get; } | Indikerar om den här font-weight-instansen lagrar ett relativt värde på teckensnittets vikt (fethet) - jämfört med fetheten för det överordnade elementet |
| [Number](../../groupdocs.editor.htmlcss.css.properties/fontweight/number) { get; } | Returnerar ett tal - heltalsvärde mellan 1 och 1000, inklusive, som beskriver teckensnittets fethet, eller ger ett undantag, om nuvarande fetstil inte är absolut, utan relativ |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontweight/value) { get; } | Returnerar ett värde för denna teckensnittsvikt som en string |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [FromNumber](../../groupdocs.editor.htmlcss.css.properties/fontweight/fromnumber)(ushort) | Skapar en teckensnittsvikt från specificerat antal |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontweight/equals#equals)(FontWeight) | Avgör om angivna FontWeight-instanser är equal |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontweight/equals#equals_1)(object) | Avgör om denna FontWeight-instans är lika med specificerad uncasted |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontweight/gethashcode)() | Returnerar en hash-kod för denna instans |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontweight/tryparse)(string, out FontWeight) | Försöker att analysera en angiven sträng och returnera en giltig FontWeight-instans på success |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontweight/op_equality) | Kontrollerar om två "FontWeight"-värden är lika |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontweight/op_inequality) | Kontrollerar om två "FontWeight"-värden inte är lika |

## Fält

| namn | Beskrivning |
| --- | --- |
| static readonly [Bold](../../groupdocs.editor.htmlcss.css.properties/fontweight/bold) | Fet teckensnittsvikt. Samma som 700. |
| static readonly [Bolder](../../groupdocs.editor.htmlcss.css.properties/fontweight/bolder) | En relativ teckensnittsvikt tyngre än det överordnade elementet |
| static readonly [Lighter](../../groupdocs.editor.htmlcss.css.properties/fontweight/lighter) | En relativ teckensnittsvikt lättare än det överordnade elementet |
| static readonly [Normal](../../groupdocs.editor.htmlcss.css.properties/fontweight/normal) | Normal teckensnittsvikt. Samma som 400. |

### Se även

* namnutrymme [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* hopsättning [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
