---
title: Length
second_title: GroupDocs.Editor voor .NET API-referentie
description: Vertegenwoordigt een CSSlengtewaarde in elke ondersteunde eenheid inclusief percentage en unitless type. Waarden kunnen integer of float negatief nul en positief zijn. Onveranderlijke structuur.
type: docs
weight: 260
url: /nl/net/groupdocs.editor.htmlcss.css.datatypes/length/
---
## Length structure

Vertegenwoordigt een CSS-lengtewaarde in elke ondersteunde eenheid, inclusief percentage en unitless type. Waarden kunnen integer of float, negatief, nul en positief zijn. Onveranderlijke structuur.

```csharp
public struct Length : ICloneable, ICssDataType, IEquatable<Length>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [FloatValue](../../groupdocs.editor.htmlcss.css.datatypes/length/floatvalue) { get; } | Retourneert een zwevende numerieke waarde van de instantie Length. Gooit nooit een uitzondering - converteert Integer-waarde naar Float indien nodig. |
| [IntegerValue](../../groupdocs.editor.htmlcss.css.datatypes/length/integervalue) { get; } | Retourneert een numerieke gehele waarde van deze instantie Length, als deze intern is opgeslagen als een geheel getal, of genereert een uitzondering, als deze oorspronkelijk is opgeslagen als een zwevend getal. |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.datatypes/length/isabsolute) { get; } | Krijgt als de lengte wordt gegeven in absolute eenheden. Zo'n lengte kan worden omgezet in pixels. |
| [IsFloat](../../groupdocs.editor.htmlcss.css.datatypes/length/isfloat) { get; } | Geeft aan of de numerieke waarde van deze instantie Length oorspronkelijk is opgegeven en opgeslagen als een float (FP32) number |
| [IsInteger](../../groupdocs.editor.htmlcss.css.datatypes/length/isinteger) { get; } | Geeft aan of de numerieke waarde van deze instantie Length oorspronkelijk is opgegeven en opgeslagen als een geheel getal (INT32) number |
| [IsNegative](../../groupdocs.editor.htmlcss.css.datatypes/length/isnegative) { get; } | Bepaalt of de numerieke waarde van deze lengte een negatief getal is |
| [IsPositive](../../groupdocs.editor.htmlcss.css.datatypes/length/ispositive) { get; } | Bepaalt of de numerieke waarde van deze lengte een positief getal is |
| [IsRelative](../../groupdocs.editor.htmlcss.css.datatypes/length/isrelative) { get; } | Krijgt als de lengte wordt gegeven in relatieve eenheden. Zo'n lengte kan niet worden omgezet in pixels. |
| [IsUnitlessNonZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlessnonzero) { get; } | De waarde heeft een eenheidsloos type, maar is geen nul - positief of negatief getal |
| [IsUnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlesszero) { get; } | Bepaalt of deze instantie een nul zonder eenheid is of niet. Eenheid zonder nul is de standaardwaarde van dit type. Hetzelfde als eigenschap IsDefault. |
| [IsZero](../../groupdocs.editor.htmlcss.css.datatypes/length/iszero) { get; } | Bepaalt of de numerieke waarde van deze lengte een nul is number |
| [UnitType](../../groupdocs.editor.htmlcss.css.datatypes/length/unittype) { get; } | Retourneert een eenheidstype van deze instantie Length. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit)(double, Unit) | Creëert en retourneert een instantie van het type Length door opgegeven dubbel getal en unit |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_2)(float, Unit) | Creëert en retourneert een instantie van het type Length op basis van opgegeven float-nummer en unit |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_1)(int, Unit) | Creëert en retourneert een instantie van het type Length door opgegeven geheel getal en unit |
| static [Parse](../../groupdocs.editor.htmlcss.css.datatypes/length/parse)(string) | Parseert en retourneert gespecificeerde tekenreeks als een lengtewaarde, inclusief de numerieke waarde en eenheidsnaam, of genereert een uitzondering op failure |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/length/clone)() | Retourneert een volledige kopie van deze lengte-instantie |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals)(Length) | Definieert of deze waarde gelijk is aan de andere opgegeven lengte |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals_1)(object) | Bepaalt of deze lengte gelijk is aan opgegeven object |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/length/gethashcode)() | Berekent en retourneert een hash-code van deze lengte-instantie door hash-codes van de waarde en het eenheidstype te combineren |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/serializedefault)() | Retourneert een tekenreeksrepresentatie van deze lengte in de oorspronkelijke oorspronkelijke vorm (zoals opgeslagen), zonder de lengtewaarde om te zetten in een andere eenheid type |
| [To](../../groupdocs.editor.htmlcss.css.datatypes/length/to)(Unit) | Converteert de lengte naar de opgegeven eenheid, indien mogelijk. Als de huidige of gegeven eenheid relatief is, wordt er een uitzondering gegenereerd. |
| [ToPixel](../../groupdocs.editor.htmlcss.css.datatypes/length/topixel)() | Converteert de lengte indien mogelijk naar een aantal pixels. Als de huidige eenheid relatief is, wordt er een uitzondering gegenereerd. |
| [ToStringSpecified](../../groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified)(Unit) | Retourneert een tekenreeksrepresentatie van deze lengte in een opgegeven eenheidstype. De numerieke waarde wordt geconverteerd overeenkomstig de wijziging van het eenheidstype. |
| static [GetUnitFromName](../../groupdocs.editor.htmlcss.css.datatypes/length/getunitfromname)(string) | Probeert de opgegeven eenheidsnaam te ontleden en de overeenkomstige waarde van een eenheidsopsomming te retourneren. Geeft als resultaat Unit.Unitless als de juiste eenheid niet kan worden gevonden. |
| static [TryParse](../../groupdocs.editor.htmlcss.css.datatypes/length/tryparse)(string, out Length) | Probeert een opgegeven tekenreeks te ontleden als een lengtewaarde, inclusief de numerieke waarde en eenheidsnaam |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/length/op_equality) | Controleert de gelijkheid van de twee gegeven lengtes. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/length/op_inequality) | Controleert de ongelijkheid van de twee gegeven lengtes. |
| [operator *](../../groupdocs.editor.htmlcss.css.datatypes/length/op_multiply) | Vermenigvuldigt de gegeven lengte met de gegeven factor |

## Velden

| Naam | Beschrijving |
| --- | --- |
| static readonly [FiftyPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/fiftypercents) | 50% |
| static readonly [OneHundredPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/onehundredpercents) | 100% |
| static readonly [UnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/unitlesszero) | Eenheidloos geheel getal nul - standaardwaarde, hetzelfde als standaard parameterloze constructor |
| static readonly [ZeroPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/zeropercents) | 0% |

## Andere leden

| Naam | Beschrijving |
| --- | --- |
| enum [Unit](length.unit) | Alle ondersteunde lengte-eenheden |

### Opmerkingen

Dit type omvat de volgende CSS-gegevenstypen: https://developer.mozilla.org/en-US/docs/Web/CSS/length https://developer.mozilla.org/en-US/docs/Web/ CSS/percentage

### Zie ook

* interface [ICssDataType](../icssdatatype)
* naamruimte [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
