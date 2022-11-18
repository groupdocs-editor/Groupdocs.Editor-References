---
title: Length
second_title: GroupDocs.Editor för .NET API-referens
description: Representerar ett CSSlängdvärde i valfri enhet som stöds inklusive procent och enhetslös typ. Värden kan vara heltal eller flytande negativ noll och positiv. Oföränderlig struktur.
type: docs
weight: 190
url: /sv/net/groupdocs.editor.htmlcss.css.datatypes/length/
---
## Length structure

Representerar ett CSS-längdvärde i valfri enhet som stöds, inklusive procent och enhetslös typ. Värden kan vara heltal eller flytande, negativ, noll och positiv. Oföränderlig struktur.

```csharp
public struct Length : ICloneable, IEquatable<  >, IEquatable<Length>
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [FloatValue](../../groupdocs.editor.htmlcss.css.datatypes/length/floatvalue) { get; } | Returnerar ett flytande numeriskt värde för Length-instansen. Kastar aldrig ett undantag - konverterar heltalsvärde till Float om det behövs. |
| [IntegerValue](../../groupdocs.editor.htmlcss.css.datatypes/length/integervalue) { get; } | Returnerar ett heltals numeriskt värde för denna Length-instans, om det är internt lagrat som ett heltal, eller ger ett undantag, om det ursprungligen lagrades som ett flyttal. |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.datatypes/length/isabsolute) { get; } | Får om längden anges i absoluta enheter. En sådan längd kan konverteras till pixlar. |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/isdefault) { get; } | Indikerar om denna Length-instans har ett standardvärde — noll utan enhet. Samma som egenskapen IsUnitlessZero. |
| [IsFloat](../../groupdocs.editor.htmlcss.css.datatypes/length/isfloat) { get; } | Indikerar om det numeriska värdet för denna Length-instans ursprungligen specificerades och lagrades som ett flytande (FP32) nummer |
| [IsInteger](../../groupdocs.editor.htmlcss.css.datatypes/length/isinteger) { get; } | Indikerar om det numeriska värdet för denna Length-instans ursprungligen specificerades och lagrades som ett heltal (INT32) number |
| [IsNegative](../../groupdocs.editor.htmlcss.css.datatypes/length/isnegative) { get; } | Bestämmer om det numeriska värdet för denna längd är ett negativt tal |
| [IsPositive](../../groupdocs.editor.htmlcss.css.datatypes/length/ispositive) { get; } | Bestämmer om det numeriska värdet för denna längd är ett positivt tal |
| [IsRelative](../../groupdocs.editor.htmlcss.css.datatypes/length/isrelative) { get; } | Får om längden anges i relativa enheter. En sådan längd kan inte konverteras till pixlar. |
| [IsUnitlessNonZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlessnonzero) { get; } | Värdet har enhetslös typ, men är inte en nolla - positivt eller negativt tal |
| [IsUnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlesszero) { get; } | Bestämmer om denna instans är en enhetslös nolla eller inte. Unitless noll är standardvärdet av denna typ. Samma som IsDefault-egenskapen. |
| [IsZero](../../groupdocs.editor.htmlcss.css.datatypes/length/iszero) { get; } | Bestämmer om det numeriska värdet för denna längd är ett nolltal |
| [UnitType](../../groupdocs.editor.htmlcss.css.datatypes/length/unittype) { get; } | Returnerar en enhetstyp av denna Length-instans. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit)(double, Unit) | Skapar och returnerar en instans av typen Length med angivet dubbeltal och unit |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_2)(float, Unit) | Skapar och returnerar en instans av typen Length efter angivet flytnummer och unit |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_1)(int, Unit) | Skapar och returnerar en instans av typen Length efter specificerat heltal och unit |
| static [Parse](../../groupdocs.editor.htmlcss.css.datatypes/length/parse)(string) | Analyserar och returnerar specificerad sträng som ett Length-värde, inklusive dess numeriska värde och enhetsnamn, eller kastar ett undantag på failure |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/length/clone)() | Returnerar en fullständig kopia av denna Length-instans |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals)(Length) | Definierar om detta värde är lika med den andra specificerade length |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals_1)(object) | Bestämmer om denna längd är lika med specificerat objekt |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/length/gethashcode)() | Beräknar och returnerar en hash-kod av denna Length-instans genom att kombinera hash-koder för värdet och enhetstypen |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/serializedefault)() | Returnerar en strängrepresentation av denna längd i dess ursprungliga ursprungliga form (såsom den är lagrad), utan att konvertera längdvärdet till någon annan enhetstyp |
| [To](../../groupdocs.editor.htmlcss.css.datatypes/length/to)(Unit) | Konverterar längden till den givna enheten, om möjligt. Om den aktuella eller den givna enheten är relativ, kommer ett undantag att skapas. |
| [ToPixel](../../groupdocs.editor.htmlcss.css.datatypes/length/topixel)() | Konverterar längden till ett antal pixlar, om möjligt. Om den aktuella enheten är relativ, kommer ett undantag att skapas. |
| [ToStringSpecified](../../groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified)(Unit) | Returnerar en strängrepresentation av denna längd i angiven enhetstyp. Numeriskt värde kommer att konverteras till motsvarande enhetstypsändring. |
| static [GetUnitFromName](../../groupdocs.editor.htmlcss.css.datatypes/length/getunitfromname)(string) | Försöker att analysera specificerat enhetsnamn och returnera motsvarande värde på en Unit enum. Returnerar Unit.Unitless om inte kan hitta lämplig enhet. |
| static [TryParse](../../groupdocs.editor.htmlcss.css.datatypes/length/tryparse)(string, out Length) | Försöker tolka en angiven sträng som ett längdvärde, inklusive dess numeriska värde och enhetsnamn |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/length/op_equality) | Kontrollerar likheten mellan de två givna längderna. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/length/op_inequality) | Kontrollerar olikheten mellan de två givna längderna. |

## Fält

| namn | Beskrivning |
| --- | --- |
| static readonly [FiftyPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/fiftypercents) | 50% |
| static readonly [OneHundredPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/onehundredpercents) | 100% |
| static readonly [UnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/unitlesszero) | Unitless heltal noll - standardvärde, samma som standard parameterless constructor |
| static readonly [ZeroPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/zeropercents) | 0% |

## Andra medlemmar

| namn | Beskrivning |
| --- | --- |
| enum [Unit](length.unit) | Alla längdenheter som stöds |

### Anmärkningar

Den här typen täcker nästa CSS-datatyper: https://developer.mozilla.org/en-US/docs/Web/CSS/length https://developer.mozilla.org/en-US/docs/Web/ CSS/procent

### Se även

* namnutrymme [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* hopsättning [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
