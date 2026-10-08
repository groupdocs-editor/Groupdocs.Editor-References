---
title: "ArgbColor"
second_title: "GroupDocs.Editor voor .NET API-referentie"
description: "Stelt één kleurwaarde voor in 32-bit ARGB-formaat, 8 bits per kanaal inclusief transparantie, met converters en serializers."
type: docs
weight: 160
url: /nl/net/groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
## ArgbColor structure

Stelt een CSS-lengtewaarde voor in 32-bit ARGB-indeling (8 bits per kanaal inclusief transparantie) met converters en serializers

```csharp
public struct ArgbColor : ICssDataType, IEquatable<ArgbColor>
```

## Properties

| Name | Beschrijving |
| --- | --- |
| [A](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/a) { get; } | Haalt het alfa‑gedeelte van de kleur op. |
| [Alpha](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/alpha) { get; } | Haalt het alfa‑gedeelte van de kleur op in procent (0..1). |
| [B](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/b) { get; } | Haalt het blauwe gedeelte van de kleur op. |
| [G](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/g) { get; } | Haalt het groene gedeelte van de kleur op. |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isdefault) { get; } | Geeft aan of deze [`ArgbColor`](../argbcolor) instantie standaard (Transparent) is - alle 4 kanalen zijn ingesteld op 0. |
| [IsEmpty](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isempty) { get; } | Niet-geïnitialiseerde kleur - alle 4 kanalen zijn ingesteld op 0. Hetzelfde als Standaard en Transparent. |
| [IsFullyOpaque](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullyopaque) { get; } | Geeft aan of deze [`ArgbColor`](../argbcolor) instantie volledig ondoorzichtig is, zonder transparantie (het Alpha-kanaal heeft de maximale waarde). |
| [IsFullyTransparent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullytransparent) { get; } | Geeft aan of deze [`ArgbColor`](../argbcolor) instantie volledig transparant is - het Alpha-kanaal heeft de minimale (0) waarde, waardoor de andere R-, G- en B-kanalen geen zichtbaar effect hebben. |
| [IsTranslucent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/istranslucent) { get; } | Geeft aan of deze [`ArgbColor`](../argbcolor) instantie doorschijnend is (niet volledig transparant, maar ook niet volledig ondoorzichtig). |
| [R](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/r) { get; } | Haalt het rode gedeelte van de kleur op. |
| [Value](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/value) { get; } | Haalt de Int32‑waarde van de kleur op. |

## Methods

| Name | Beschrijving |
| --- | --- |
| static [FromRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgb)(byte, byte, byte) | Maakt één [`ArgbColor`](../argbcolor) waarde aan vanuit de opgegeven rood-, groen- en blauwkanalen, terwijl Alpha-kanaal volledig ondoorzichtig is. |
| static [FromRgba](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgba)(byte, byte, byte, byte) | Maakt één [`ArgbColor`](../argbcolor) waarde aan vanuit de opgegeven rood-, groen-, blauw- en Alpha-kanalen. |
| static [FromSingleValueRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromsinglevaluergb)(byte) | Maakt een volledig ondoorzichtige (A=255) kleur aan vanuit één waarde, die op alle kanalen wordt toegepast. |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals)(ArgbColor) | Controleert twee [`ArgbColor`](../argbcolor) kleuren op gelijkheid. |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals_1)(object) | Test of een ander object gelijk is aan deze [`ArgbColor`](../argbcolor) instantie. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/gethashcode)() | Retourneert een hashcode die de huidige kleur definieert. |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/serializedefault)() | Serialiseert deze [`ArgbColor`](../argbcolor) instantie naar de meest geschikte CSS-functienotatie, afhankelijk van de transparantie. |
| [ToRGB](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgb)() | Serialiseert deze [`ArgbColor`](../argbcolor) instantie naar de 'rgb' CSS-functienotatie. |
| [ToRGBA](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgba)() | Serialiseert deze [`ArgbColor`](../argbcolor) instantie naar de 'rgba' CSS-functienotatie. |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/tostring)() | Hetzelfde als [`SerializeDefault`](./serializedefault). |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_equality) | Vergelijkt twee kleuren en retourneert een boolean die aangeeft of de twee overeenkomen. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_inequality) | Vergelijkt twee kleuren en retourneert een boolean die aangeeft of de twee niet overeenkomen. |

## Andere leden

| Name | Beschrijving |
| --- | --- |
| static class [KnownColors](argbcolor.knowncolors) | Bevat alle "bekende kleuren", die een vaste unieke naam en waarde hebben in de CSS-standaard |

### Opmerkingen

Dit type is ontworpen om nuttig te zijn voor (maar niet beperkt tot) CSS-bewerkingen. Zie meer: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### Zie ook

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
