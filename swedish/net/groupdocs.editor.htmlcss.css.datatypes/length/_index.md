---
title: "Length"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Representerar ett CSS‑längdvärde i någon stödjande enhet inklusive procent och enhetlös typ. Värden kan vara heltal eller flyttal, negativt noll och positivt. Oföränderlig struktur."
type: docs
weight: 230
url: /sv/net/groupdocs.editor.htmlcss.css.datatypes/length/
---
## Length structure

Representerar ett CSS-längdvärde i någon stödbar enhet, inklusive procent och enhetstyp utan enhet. Värden kan vara heltal eller flyttal, negativa, noll och positiva. Oföränderlig struktur.

```csharp
public struct Length : ICloneable, ICssDataType, IEquatable<Length>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [FloatValue](../../groupdocs.editor.htmlcss.css.datatypes/length/floatvalue) { get; } | Returnerar ett flyttal‑numeriskt värde för Length‑instansen. Kastar aldrig ett undantag – konverterar heltalsvärde till flyttal om nödvändigt. |
| [IntegerValue](../../groupdocs.editor.htmlcss.css.datatypes/length/integervalue) { get; } | Returnerar ett heltals‑numeriskt värde för denna Length‑instans, om det internt lagras som ett heltal, annars kastar ett undantag om det ursprungligen lagrades som ett flyttal. |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.datatypes/length/isabsolute) { get; } | Hämtar om längden är given i absoluta enheter. En sådan längd kan konverteras till pixlar. |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/isdefault) { get; } | Indikerar om detta Length‑objekt har ett standardvärde — enhetslöst noll. Samma som egenskapen IsUnitlessZero. |
| [IsFloat](../../groupdocs.editor.htmlcss.css.datatypes/length/isfloat) { get; } | Indikerar om det numeriska värdet för detta Length‑objekt ursprungligen angavs och lagrades som ett flyttal (FP32). |
| [IsInteger](../../groupdocs.editor.htmlcss.css.datatypes/length/isinteger) { get; } | Indikerar om det numeriska värdet för detta Length‑objekt ursprungligen angavs och lagrades som ett heltal (INT32). |
| [IsNegative](../../groupdocs.editor.htmlcss.css.datatypes/length/isnegative) { get; } | Bestämmer om det numeriska värdet för denna längd är ett negativt tal. |
| [IsPositive](../../groupdocs.editor.htmlcss.css.datatypes/length/ispositive) { get; } | Bestämmer om det numeriska värdet för denna längd är ett positivt tal. |
| [IsRelative](../../groupdocs.editor.htmlcss.css.datatypes/length/isrelative) { get; } | Hämtar om längden är given i relativa enheter. En sådan längd kan inte konverteras till pixlar. |
| [IsUnitlessNonZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlessnonzero) { get; } | Värdet har enhetslös typ, men är inte noll – ett positivt eller negativt tal. |
| [IsUnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlesszero) { get; } | Bestämmer om detta objekt är en enhetslös noll eller inte. Enhetslös noll är standardvärdet för denna typ. Samma som egenskapen IsDefault. |
| [IsZero](../../groupdocs.editor.htmlcss.css.datatypes/length/iszero) { get; } | Bestämmer om det numeriska värdet för denna längd är noll. |
| [UnitType](../../groupdocs.editor.htmlcss.css.datatypes/length/unittype) { get; } | Returnerar en enhetstyp för detta Length‑objekt. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit)(double, Unit) | Skapar och returnerar en instans av Length‑typen med angivet double‑värde och enhet. |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_2)(float, Unit) | Skapar och returnerar en instans av Length‑typen med angivet float‑värde och enhet. |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_1)(int, Unit) | Skapar och returnerar en instans av Length‑typen med angivet heltalsvärde och enhet. |
| static [Parse](../../groupdocs.editor.htmlcss.css.datatypes/length/parse)(string) | Analyserar och returnerar den angivna strängen som ett Length‑värde, inklusive dess numeriska värde och enhetsnamn, eller kastar ett undantag vid fel. |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/length/clone)() | Returnerar en fullständig kopia av detta Length‑objekt. |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals)(Length) | Definierar om detta värde är lika med den andra angivna längden. |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals_1)(object) | Bestämmer om denna längd är lika med det angivna objektet. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/length/gethashcode)() | Beräknar och returnerar en hash‑kod för detta Length‑objekt genom att kombinera hash‑koderna för värdet och enhetstypen. |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/serializedefault)() | Returnerar en strängrepresentation av denna längd i dess ursprungliga form (så som den lagras), utan att konvertera längdvärdet till någon annan enhetstyp. |
| [To](../../groupdocs.editor.htmlcss.css.datatypes/length/to)(Unit) | Konverterar längden till den angivna enheten, om möjligt. Om den aktuella eller angivna enheten är relativ, kastas ett undantag. |
| [ToPixel](../../groupdocs.editor.htmlcss.css.datatypes/length/topixel)() | Konverterar längden till ett antal pixlar, om möjligt. Om den aktuella enheten är relativ, kastas ett undantag. |
| [ToStringSpecified](../../groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified)(Unit) | Returnerar en strängrepresentation av denna längd i den angivna enhetstypen. Det numeriska värdet kommer att konverteras i enlighet med enhetsbytet. |
| static [GetUnitFromName](../../groupdocs.editor.htmlcss.css.datatypes/length/getunitfromname)(string) | Försöker tolka det angivna enhetsnamnet och returnera motsvarande värde i Unit‑enumen. Returnerar Unit.Unitless om en lämplig enhet inte kan hittas. |
| static [TryParse](../../groupdocs.editor.htmlcss.css.datatypes/length/tryparse)(string, out Length) | Försöker tolka en angiven sträng som ett Length‑värde, inklusive dess numeriska värde och enhetsnamn. |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/length/op_equality) | Kontrollerar likheten mellan de två angivna längderna. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/length/op_inequality) | Kontrollerar ojämlikheten mellan de två angivna längderna. |
| [operator *](../../groupdocs.editor.htmlcss.css.datatypes/length/op_multiply) | Multiplicerar den angivna längden med den angivna faktorn |

## Fält

| Namn | Beskrivning |
| --- | --- |
| static readonly [FiftyPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/fiftypercents) | 50% |
| static readonly [OneHundredPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/onehundredpercents) | 100% |
| static readonly [UnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/unitlesszero) | Enhetslöst heltal noll – standardvärde, samma som standardkonstruktorn utan parametrar |
| static readonly [ZeroPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/zeropercents) | 0% |

## Övriga medlemmar

| Namn | Beskrivning |
| --- | --- |
| enum [Unit](length.unit) | Alla stödda längdenheter |

### Anmärkningar

Denna typ omfattar följande CSS-datatyper: https://developer.mozilla.org/en-US/docs/Web/CSS/length https://developer.mozilla.org/en-US/docs/Web/CSS/percentage

### Se även

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
