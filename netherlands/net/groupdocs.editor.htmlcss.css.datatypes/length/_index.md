---
title: "Lengte"
second_title: "GroupDocs.Editor voor .NET API-referentie"
description: "Stelt een CSS-lengtewaarde voor in elke ondersteunde eenheid, inclusief procenten en eenheidloos type. Waarden kunnen geheel getal of float, negatief, nul en positief zijn. Onveranderlijke structuur."
type: docs
weight: 230
url: /nl/net/groupdocs.editor.htmlcss.css.datatypes/length/
---
## Length structure

Stelt een CSS-lengtewaarde voor in elke ondersteunde eenheid, inclusief percentage en eenheidloze type. Waarden kunnen geheel getal of float zijn, negatief, nul en positief. Onveranderlijke structuur.

```csharp
public struct Length : ICloneable, ICssDataType, IEquatable<Length>
```

## Properties

| Name | Beschrijving |
| --- | --- |
| [FloatValue](../../groupdocs.editor.htmlcss.css.datatypes/length/floatvalue) { get; } | Retourneert een float numerieke waarde van de Length‑instantie. Werpt nooit een uitzondering – converteert een Integer‑waarde naar Float indien nodig. |
| [IntegerValue](../../groupdocs.editor.htmlcss.css.datatypes/length/integervalue) { get; } | Retourneert een geheel getal numerieke waarde van deze Length‑instantie, als deze intern als een geheel getal is opgeslagen, of werpt een uitzondering, als deze oorspronkelijk als een float‑getal was opgeslagen. |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.datatypes/length/isabsolute) { get; } | Geeft aan of de lengte is opgegeven in absolute eenheden. Zo'n lengte kan naar pixels worden geconverteerd. |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/isdefault) { get; } | Geeft aan of deze Length‑instantie een standaardwaarde heeft — eenheidloze nul. Hetzelfde als de IsUnitlessZero‑eigenschap. |
| [IsFloat](../../groupdocs.editor.htmlcss.css.datatypes/length/isfloat) { get; } | Geeft aan of de numerieke waarde van deze Length‑instantie oorspronkelijk is gespecificeerd en opgeslagen als een float (FP32)‑getal. |
| [IsInteger](../../groupdocs.editor.htmlcss.css.datatypes/length/isinteger) { get; } | Geeft aan of de numerieke waarde van deze Length‑instantie oorspronkelijk is gespecificeerd en opgeslagen als een geheel getal (INT32). |
| [IsNegative](../../groupdocs.editor.htmlcss.css.datatypes/length/isnegative) { get; } | Bepaalt of de numerieke waarde van deze lengte een negatief getal is. |
| [IsPositive](../../groupdocs.editor.htmlcss.css.datatypes/length/ispositive) { get; } | Bepaalt of de numerieke waarde van deze lengte een positief getal is. |
| [IsRelative](../../groupdocs.editor.htmlcss.css.datatypes/length/isrelative) { get; } | Geeft aan of de lengte is opgegeven in relatieve eenheden. Zo'n lengte kan niet naar pixels worden geconverteerd. |
| [IsUnitlessNonZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlessnonzero) { get; } | De waarde heeft een eenheidloos type, maar is geen nul – een positief of negatief getal. |
| [IsUnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlesszero) { get; } | Bepaalt of deze instantie een eenheidloze nul is of niet. Eenheidloze nul is de standaardwaarde van dit type. Hetzelfde als de IsDefault‑eigenschap. |
| [IsZero](../../groupdocs.editor.htmlcss.css.datatypes/length/iszero) { get; } | Bepaalt of de numerieke waarde van deze lengte een nulgetal is. |
| [UnitType](../../groupdocs.editor.htmlcss.css.datatypes/length/unittype) { get; } | Retourneert een eenheidstype van deze Length‑instantie. |

## Methods

| Name | Beschrijving |
| --- | --- |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit)(double, Unit) | Maakt en retourneert een instantie van het Length‑type op basis van een opgegeven double‑getal en eenheid. |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_2)(float, Unit) | Maakt en retourneert een instantie van het Length‑type op basis van een opgegeven float‑getal en eenheid. |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_1)(int, Unit) | Maakt en retourneert een instantie van het Length‑type op basis van een opgegeven geheel getal en eenheid. |
| static [Parse](../../groupdocs.editor.htmlcss.css.datatypes/length/parse)(string) | Parseert en retourneert de opgegeven string als een Length‑waarde, inclusief de numerieke waarde en eenheidsnaam, of werpt een uitzondering bij falen. |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/length/clone)() | Retourneert een volledige kopie van deze Length‑instantie. |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals)(Length) | Bepaalt of deze waarde gelijk is aan de andere opgegeven lengte. |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals_1)(object) | Bepaalt of deze lengte gelijk is aan het opgegeven object. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/length/gethashcode)() | Bereken en retourneer een hash‑code van deze Length‑instantie door de hash‑codes van de waarde en het eenheidstype te combineren. |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/serializedefault)() | Retourneert een tekenreeksrepresentatie van deze lengte in de oorspronkelijke native vorm (zoals opgeslagen), zonder de lengtewaarde naar een andere eenheid te converteren. |
| [To](../../groupdocs.editor.htmlcss.css.datatypes/length/to)(Unit) | Converteert de lengte naar de opgegeven eenheid, indien mogelijk. Als de huidige of opgegeven eenheid relatief is, wordt er een uitzondering gegooid. |
| [ToPixel](../../groupdocs.editor.htmlcss.css.datatypes/length/topixel)() | Converteert de lengte naar een aantal pixels, indien mogelijk. Als de huidige eenheid relatief is, wordt er een uitzondering gegooid. |
| [ToStringSpecified](../../groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified)(Unit) | Retourneert een tekenreeksrepresentatie van deze lengte in het opgegeven eenheidstype. Numerieke waarde wordt geconverteerd overeenkomstig de wijziging van het eenheidstype. |
| static [GetUnitFromName](../../groupdocs.editor.htmlcss.css.datatypes/length/getunitfromname)(string) | Probeert de opgegeven eenheidsnaam te parseren en de overeenkomstige waarde van een Unit-enum te retourneren. Retourneert Unit.Unitless als er geen geschikte eenheid gevonden kan worden. |
| static [TryParse](../../groupdocs.editor.htmlcss.css.datatypes/length/tryparse)(string, out Length) | Probeert een opgegeven tekenreeks te parseren als een Length-waarde, inclusief de numerieke waarde en eenheidsnaam. |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/length/op_equality) | Controleert de gelijkheid van de twee opgegeven lengtes. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/length/op_inequality) | Controleert de ongelijkheid van de twee opgegeven lengtes. |
| [operator *](../../groupdocs.editor.htmlcss.css.datatypes/length/op_multiply) | Vermenigvuldigt de opgegeven Length met de gegeven factor. |

## Velden

| Name | Beschrijving |
| --- | --- |
| static readonly [FiftyPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/fiftypercents) | 50% |
| static readonly [OneHundredPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/onehundredpercents) | 100% |
| static readonly [UnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/unitlesszero) | Unitless integer nul - standaardwaarde, hetzelfde als de standaard parameterloze constructor. |
| static readonly [ZeroPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/zeropercents) | 0% |

## Andere leden

| Name | Beschrijving |
| --- | --- |
| enum [Unit](length.unit) | Alle ondersteunde lengteenheden |

### Opmerkingen

Dit type omvat de volgende CSS-datatypen: https://developer.mozilla.org/en-US/docs/Web/CSS/length https://developer.mozilla.org/en-US/docs/Web/CSS/percentage

### Zie ook

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
