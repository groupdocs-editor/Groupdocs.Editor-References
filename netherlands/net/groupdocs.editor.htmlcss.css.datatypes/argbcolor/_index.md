---
title: ArgbColor
second_title: GroupDocs.Editor voor .NET API-referentie
description: Vertegenwoordigt één kleurwaarde in ARGBindeling met converters en serializers
type: docs
weight: 190
url: /nl/net/groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
## ArgbColor structure

Vertegenwoordigt één kleurwaarde in ARGB-indeling met converters en serializers

```csharp
public struct ArgbColor : ICssDataType, IEquatable<ArgbColor>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [A](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/a) { get; } | Haalt het alfagedeelte van de kleur op. |
| [Alpha](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/alpha) { get; } | Krijgt het alfadeel van de kleur in procenten (0..1). |
| [B](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/b) { get; } | Krijgt het blauwe deel van de kleur. |
| [G](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/g) { get; } | Krijgt het groene deel van de kleur. |
| [IsEmpty](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isempty) { get; } | Niet-geïnitialiseerde kleur - alle 4 de kanalen zijn ingesteld op 0. Zelfde als standaard en transparant. |
| [IsFullyOpaque](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullyopaque) { get; } | Geeft aan of dit[`ArgbColor`](../argbcolor) instantie is volledig ondoorzichtig, zonder transparantie (het alfakanaal heeft een maximale waarde) |
| [IsFullyTransparent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullytransparent) { get; } | Geeft aan of dit[`ArgbColor`](../argbcolor) instantie is volledig transparant - het alfakanaal heeft de min (0) waarde, dus andere R-, G- en B-kanalen hebben geen zichtbaar effect. |
| [IsTranslucent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/istranslucent) { get; } | Geeft aan of dit[`ArgbColor`](../argbcolor) instantie is doorschijnend (niet volledig transparant, maar ook niet volledig ondoorzichtig) |
| [R](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/r) { get; } | Krijgt het rode deel van de kleur. |
| [Value](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/value) { get; } | Krijgt de Int32-waarde van de kleur. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [FromRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgb)(byte, byte, byte) | Maakt er een aan[`ArgbColor`](../argbcolor) waarde van gespecificeerde rode, groene en blauwe kanalen, terwijl het alfakanaal volledig ondoorzichtig is |
| static [FromRgba](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgba)(byte, byte, byte, byte) | Maakt er een aan[`ArgbColor`](../argbcolor) waarde van opgegeven rode, groene, blauwe en alfakanalen |
| static [FromSingleValueRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromsinglevaluergb)(byte) | Creëert een volledig dekkende (A=255) kleur op basis van een enkele waarde, die wordt toegepast op alle kanalen |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals)(ArgbColor) | Controleert twee[`ArgbColor`](../argbcolor) kleuren voor gelijkheid |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals_1)(object) | Test of een ander object hieraan gelijk is[`ArgbColor`](../argbcolor) instantie. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/gethashcode)() | Retourneert een hash-code die de huidige kleur definieert. |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/serializedefault)() | Serialiseert dit[`ArgbColor`](../argbcolor)instantie naar de meest geschikte CSS-functienotatie, afhankelijk van translucency |
| [ToRGB](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgb)() | Serialiseert dit[`ArgbColor`](../argbcolor) bijvoorbeeld naar de 'rgb' CSS-functie notation |
| [ToRGBA](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgba)() | Serialiseert dit[`ArgbColor`](../argbcolor) bijvoorbeeld naar de 'rgba' CSS-functie notation |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/tostring)() | Zelfde als[`SerializeDefault`](./serializedefault) |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_equality) | Vergelijkt twee kleuren en retourneert een Booleaanse waarde die aangeeft of de twee overeenkomen. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_inequality) | Vergelijkt twee kleuren en retourneert een Booleaanse waarde die aangeeft of de twee niet overeenkomen. |

## Andere leden

| Naam | Beschrijving |
| --- | --- |
| static class [KnownColors](argbcolor.knowncolors) | Bevat alle "bekende kleuren", die een vaste unieke naam en waarde hebben in CSS-standaard |

### Opmerkingen

Dit type is ontworpen om nuttig te zijn voor (maar niet beperkt tot) CSS-bewerkingen. Zie meer: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### Zie ook

* interface [ICssDataType](../icssdatatype)
* naamruimte [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
