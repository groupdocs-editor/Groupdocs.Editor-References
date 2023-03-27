---
title: Ratio
second_title: GroupDocs.Editor voor .NET API-referentie
description: Vertegenwoordigt een ratio CSSgegevenstype dat wordt gebruikt voor het beschrijven van beeldverhoudingen in mediaquerys en voor rasterafbeeldingen door de verhouding aan te geven tussen twee eenheidsloze waarden die teller en noemer worden genoemd. Onveranderlijke structuur.
type: docs
weight: 280
url: /nl/net/groupdocs.editor.htmlcss.css.datatypes/ratio/
---
## Ratio structure

Vertegenwoordigt een "ratio" CSS-gegevenstype, dat wordt gebruikt voor het beschrijven van beeldverhoudingen in mediaquery's en voor rasterafbeeldingen door de verhouding aan te geven tussen twee eenheidsloze waarden die "teller" en "noemer" worden genoemd. Onveranderlijke structuur.

```csharp
public struct Ratio : ICloneable, ICssDataType, IEquatable<Ratio>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Denominator](../../groupdocs.editor.htmlcss.css.datatypes/ratio/denominator) { get; } | Geeft een noemer van deze ratio terug |
| [Numerator](../../groupdocs.editor.htmlcss.css.datatypes/ratio/numerator) { get; } | Geeft een teller terug van deze ratio |

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [Create](../../groupdocs.editor.htmlcss.css.datatypes/ratio/create)(ushort, ushort) | Maakt en retourneert één Ratio-instantie van opgegeven teller en noemer |
| [Calculate](../../groupdocs.editor.htmlcss.css.datatypes/ratio/calculate)() | Berekent en retourneert deze verhouding als een enkel getal met drijvende komma |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/ratio/clone)() | Retourneert een volledige kopie van deze ratio |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/ratio/equals#equals_1)(object) | Bepaalt of deze instantie gelijk is aan het gespecificeerde niet-gecaste object, dat vermoedelijk een andere "Ratio"-instantie is |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/ratio/equals#equals)(Ratio) | Bepaalt of deze instantie gelijk is aan opgegeven "Ratio" instantie |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/ratio/gethashcode)() | Retourneert een hashcode voor deze instantie, die tijdens de levensduur niet kan worden gewijzigd |
| [GetInverseRatio](../../groupdocs.editor.htmlcss.css.datatypes/ratio/getinverseratio)() | Genereert en retourneert een inverse (reciproke) ratio voor deze ratio |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/ratio/serializedefault)() | Serialiseert deze verhouding naar de tekenreeks en retourneert it |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/ratio/tostring)() | Geeft een tekenreeksrepresentatie van deze verhouding; hetzelfde als "SerializeDefault()" |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/ratio/op_equality) | Vergelijkt twee ratio's en retourneert een Booleaanse waarde die aangeeft of de twee overeenkomen. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/ratio/op_inequality) | Vergelijkt twee ratio's en retourneert een Booleaanse waarde die aangeeft of de twee niet overeenkomen. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| static readonly [Single](../../groupdocs.editor.htmlcss.css.datatypes/ratio/single) | Enkele standaardverhouding 1/1 |

### Opmerkingen

https://developer.mozilla.org/en-US/docs/Web/CSS/ratio

### Zie ook

* interface [ICssDataType](../icssdatatype)
* naamruimte [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->