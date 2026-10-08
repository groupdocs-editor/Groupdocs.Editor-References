---
title: "FontSize"
second_title: "GroupDocs.Editor voor .NET API-referentie"
description: "Stelt een lettergrootte voor als een speciale eenheid of een lengtemaat die de grootte van het lettertype specificeert, historisch de breedte van de hoofdletter M."
type: docs
weight: 260
url: /nl/net/groupdocs.editor.htmlcss.css.properties/fontsize/
---
## FontSize structure

Stelt een lettergrootte voor als een speciale eenheid of een lengtemaat, die de grootte van het lettertype aangeeft (historisch de breedte van de hoofdletter \"M\").

```csharp
public struct FontSize : IEquatable<FontSize>
```

## Properties

| Name | Beschrijving |
| --- | --- |
| [IsAbsoluteSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isabsolutesize) { get; } | Geeft aan of deze lettergrootte is gedefinieerd met een absolute grootte als een trefwoord, gebaseerd op de standaardlettergrootte van de gebruiker (die medium is). |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontsize/isinitial) { get; } | Geeft aan of deze lettergrootte een beginwaarde heeft (Medium). |
| [IsLengthDefined](../../groupdocs.editor.htmlcss.css.properties/fontsize/islengthdefined) { get; } | Geeft aan of deze lettergrootte is gedefinieerd met een [`Length`](../../groupdocs.editor.htmlcss.css.datatypes/length) waarde. |
| [IsRelativeSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isrelativesize) { get; } | Geeft aan of deze lettergrootte is gedefinieerd met een relatieve grootte als een trefwoord. Het lettertype zal groter of kleiner zijn ten opzichte van de lettergrootte van het bovenliggende element, ongeveer volgens de verhouding die wordt gebruikt om de absolute-grootte trefwoorden te scheiden. |
| [Length](../../groupdocs.editor.htmlcss.css.properties/fontsize/length) { get; } | Een lengtemaat, als deze lettergrootte ermee is gedefinieerd, of anders een uitzondering wordt gegooid. |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontsize/value) { get; } | Retourneert een waarde van deze lettergrootte als een tekenreeks. |

## Methods

| Name | Beschrijving |
| --- | --- |
| static [FromLength](../../groupdocs.editor.htmlcss.css.properties/fontsize/fromlength)(Length) | Maakt een lettergrootte aan vanuit een opgegeven lengte. |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals)(FontSize) | Bepaalt of deze lettergrootte‑instantie gelijk is aan de opgegeven. |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals_1)(object) | Bepaalt of deze lettergrootte‑instantie gelijk is aan de opgegeven, niet-gecastte. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontsize/gethashcode)() | Retourneert een hash‑code voor deze instantie |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontsize/tryparse)(string, out FontSize) | Probeert een opgegeven trefwoord te herkennen als een juiste trefwoordwaarde van 'font-size' en retourneert het bij succes of NULL bij falen. |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_equality) | Controleert of twee \"FontSize\" waarden gelijk zijn. |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_inequality) | Controleert of twee \"FontSize\" waarden niet gelijk zijn. |

## Velden

| Name | Beschrijving |
| --- | --- |
| static readonly [Large](../../groupdocs.editor.htmlcss.css.properties/fontsize/large) | De normaal grote absolute-grootte. |
| static readonly [Larger](../../groupdocs.editor.htmlcss.css.properties/fontsize/larger) | Grotere relatieve grootte - het lettertype zal groter zijn ten opzichte van de lettergrootte van het bovenliggende element, ongeveer volgens de verhouding die hierboven wordt gebruikt om de absolute-grootte trefwoorden te scheiden. |
| static readonly [Medium](../../groupdocs.editor.htmlcss.css.properties/fontsize/medium) | Medium grootte. Beginwaarde. |
| static readonly [Small](../../groupdocs.editor.htmlcss.css.properties/fontsize/small) | De normaal kleine absolute-grootte. |
| static readonly [Smaller](../../groupdocs.editor.htmlcss.css.properties/fontsize/smaller) | Kleinere relatieve grootte - het lettertype zal kleiner zijn ten opzichte van de lettergrootte van het bovenliggende element, ongeveer volgens de verhouding die hierboven wordt gebruikt om de absolute-grootte trefwoorden te scheiden. |
| static readonly [XLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xlarge) | De middelmatig grote absolute-grootte. |
| static readonly [XSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xsmall) | De middelmatig kleine absolute-grootte. |
| static readonly [XxLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxlarge) | De zeer grote absolute-grootte. |
| static readonly [XxSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxsmall) | De zeer kleine absolute grootte |

### Zie ook

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
