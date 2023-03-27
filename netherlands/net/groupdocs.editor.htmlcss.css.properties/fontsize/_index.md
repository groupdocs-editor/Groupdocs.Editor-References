---
title: FontSize
second_title: GroupDocs.Editor voor .NET API-referentie
description: Vertegenwoordigt een lettergrootte als een speciale eenheid of een lengtewaarde die de grootte van het lettertype specificeert historisch gezien de breedte van de hoofdletter M.
type: docs
weight: 290
url: /nl/net/groupdocs.editor.htmlcss.css.properties/fontsize/
---
## FontSize structure

Vertegenwoordigt een lettergrootte als een speciale eenheid of een lengtewaarde, die de grootte van het lettertype specificeert (historisch gezien de breedte van de hoofdletter "M").

```csharp
public struct FontSize : IEquatable<FontSize>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [IsAbsoluteSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isabsolutesize) { get; } | Geeft aan of deze lettergrootte is gedefinieerd met een absolute grootte als trefwoord, gebaseerd op de standaard lettergrootte van de gebruiker (die medium is) |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontsize/isinitial) { get; } | Geeft aan of deze lettergrootte een beginwaarde heeft (Medium) |
| [IsLengthDefined](../../groupdocs.editor.htmlcss.css.properties/fontsize/islengthdefined) { get; } | Geeft aan of deze lettergrootte is gedefinieerd met een[`Length`](../../groupdocs.editor.htmlcss.css.datatypes/length) waarde |
| [IsRelativeSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isrelativesize) { get; } | Geeft aan of deze lettergrootte is gedefinieerd met een relatieve grootte als trefwoord. Het lettertype zal groter of kleiner zijn in verhouding tot de lettergrootte van het bovenliggende element, ruwweg door de verhouding die wordt gebruikt om de trefwoorden van absolute grootte te scheiden. |
| [Length](../../groupdocs.editor.htmlcss.css.properties/fontsize/length) { get; } | Een lengtewaarde, als deze lettergrootte ermee is gedefinieerd, of anders gegenereerde uitzondering |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontsize/value) { get; } | Retourneert een waarde van deze lettergrootte als een tekenreeks |

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [FromLength](../../groupdocs.editor.htmlcss.css.properties/fontsize/fromlength)(Length) | Creëert een lettergrootte van opgegeven lengte |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals)(FontSize) | Bepaalt of deze font-size instantie gelijk is aan gespecificeerd |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals_1)(object) | Bepaalt of deze font-size instantie gelijk is aan gespecificeerde uncasted |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontsize/gethashcode)() | Retourneert een hash-code voor deze instantie |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontsize/tryparse)(string, out FontSize) | Probeert een opgegeven sleutelwoord te herkennen als een juiste sleutelwoordwaarde van de 'font-size' en retourneert het bij succes of NULL bij falen. |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_equality) | Controleert of twee "FontSize"-waarden gelijk zijn |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_inequality) | Controleert of twee "FontSize"-waarden niet gelijk zijn |

## Velden

| Naam | Beschrijving |
| --- | --- |
| static readonly [Large](../../groupdocs.editor.htmlcss.css.properties/fontsize/large) | De normaal grote absolute grootte |
| static readonly [Larger](../../groupdocs.editor.htmlcss.css.properties/fontsize/larger) | Grotere relatieve grootte - lettertype zal groter zijn in verhouding tot de lettergrootte van het bovenliggende element, ruwweg door de verhouding die wordt gebruikt om de bovenstaande trefwoorden op absolute grootte te scheiden. |
| static readonly [Medium](../../groupdocs.editor.htmlcss.css.properties/fontsize/medium) | Middelgroot. Beginwaarde. |
| static readonly [Small](../../groupdocs.editor.htmlcss.css.properties/fontsize/small) | De normaal kleine absolute grootte |
| static readonly [Smaller](../../groupdocs.editor.htmlcss.css.properties/fontsize/smaller) | Kleinere relatieve grootte - lettertype zal kleiner zijn in verhouding tot de lettergrootte van het bovenliggende element, ruwweg door de verhouding die wordt gebruikt om de bovenstaande trefwoorden van absolute grootte te scheiden. |
| static readonly [XLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xlarge) | De middelmatige grote absolute grootte |
| static readonly [XSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xsmall) | De middelmatige kleine absolute grootte |
| static readonly [XxLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxlarge) | De zeer grote absolute maat |
| static readonly [XxSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxsmall) | De zeer kleine absolute grootte |

### Zie ook

* naamruimte [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
