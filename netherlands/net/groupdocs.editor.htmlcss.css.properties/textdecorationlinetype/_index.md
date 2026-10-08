---
title: "TextDecorationLineType"
second_title: "GroupDocs.Editor voor .NET API-referentie"
description: "Stelt de typen van de tekstdecoratielijn onderstreping, underscore, overline en doorhaling (strikethrough) voor"
type: docs
weight: 290
url: /nl/net/groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/
---
## TextDecorationLineType structure

Stelt de typen van de tekstdecoratielijn voor: onderstrepen (underscore), overstrepen en doorhalen (strikethrough)

```csharp
public struct TextDecorationLineType : IEquatable<TextDecorationLineType>
```

## Properties

| Name | Beschrijving |
| --- | --- |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isinitial) { get; } | Geeft aan of deze instantie een initiële waarde heeft — None |
| [IsLineThrough](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/islinethrough) { get; } | Geeft aan of doorhalen (strikethrough) is ingeschakeld |
| [IsOverline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isoverline) { get; } | Geeft aan of overline is ingeschakeld |
| [IsUnderline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isunderline) { get; } | Geeft aan of onderstrepen (underscore) is ingeschakeld |
| [Value](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/value) { get; } | Retourneert een waarde van alle vlaggen in deze instantie als tekst |

## Methods

| Name | Beschrijving |
| --- | --- |
| static [FromFlags](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/fromflags)(bool, bool, bool) | Maakt en retourneert een [`TextDecorationLineType`](../textdecorationlinetype)‑instantie met vlaggen, gedefinieerd door de opgegeven parameters |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/equals#equals_1)(object) | Geeft aan of deze [`TextDecorationLineType`](../textdecorationlinetype) instantie gelijk is aan de opgegeven niet-gecastte |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/equals#equals)(TextDecorationLineType) | Geeft aan of deze [`TextDecorationLineType`](../textdecorationlinetype) instantie gelijk is aan de opgegeven |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/gethashcode)() | Retourneert een hashcode van deze instantie |
| override [ToString](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/tostring)() | Retourneert een waarde van alle vlaggen in deze instantie als tekst |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/tryparse)(string, out TextDecorationLineType) | Probeert een opgegeven tekenreeks te parseren en retourneert een geldige [`TextDecorationLineType`](../textdecorationlinetype) instantie |
| [operator +](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_addition) | Combineert (voegt samen) twee opgegeven lijntypen en produceert een nieuw resulterend lijntype, waarbij vlaggen worden samengevoegd (union) |
| [operator /](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_division) | Retourneert een intersectie tussen het eerste en tweede lijntype, waarbij alleen die vlaggen zijn ingeschakeld die tegelijkertijd in beide operanden zijn ingeschakeld. Heeft de hoogste prioriteit van alle operatoren (hoger dan union en difference) |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_equality) | Controleert of twee "TextDecorationLineType" waarden gelijk zijn |
| [explicit operator](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_explicit#op_explicit_1) | Casts een specifieke Byte (8-bit octet) naar de overeenkomstige [`TextDecorationLineType`](../textdecorationlinetype), gooit een uitzondering als de cast ongeldig is (2 operatoren) |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_inequality) | Controleert of twee "TextDecorationLineType" waarden niet gelijk zijn |
| [operator -](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_subtraction) | Trek het tweede opgegeven lijntype af van het eerste opgegeven lijntype en produceer een nieuw resulterend lijntype, waarin alleen die vlaggen van de eerste operand aanwezig zijn die niet in de tweede operand voorkomen (difference) |

## Velden

| Name | Beschrijving |
| --- | --- |
| static readonly [LineThrough](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/linethrough) | Elke tekstregel heeft een lijn door het midden. |
| static readonly [None](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/none) | Produceert geen tekstdecoratie. Initiële waarde. |
| static readonly [Overline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/overline) | Elke tekstregel heeft een lijn erboven. |
| static readonly [Underline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/underline) | Elke tekstregel is onderstreept. |

### Opmerkingen

Onveranderlijke struct. Vergelijkbaar met de https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line

### Zie ook

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
