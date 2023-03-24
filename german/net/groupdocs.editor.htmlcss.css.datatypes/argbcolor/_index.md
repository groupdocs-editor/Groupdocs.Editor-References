---
title: ArgbColor
second_title: GroupDocs.Editor für .NET-API-Referenz
description: Repräsentiert einen Farbwert im ARGBFormat mit Konvertern und Serialisierern
type: docs
weight: 190
url: /de/net/groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
## ArgbColor structure

Repräsentiert einen Farbwert im ARGB-Format mit Konvertern und Serialisierern

```csharp
public struct ArgbColor : ICssDataType, IEquatable<ArgbColor>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [A](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/a) { get; } | Ruft den Alpha-Teil der Farbe ab. |
| [Alpha](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/alpha) { get; } | Ermittelt den Alpha-Anteil der Farbe in Prozent (0..1). |
| [B](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/b) { get; } | Ruft den blauen Anteil der Farbe ab. |
| [G](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/g) { get; } | Ruft den grünen Anteil der Farbe ab. |
| [IsEmpty](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isempty) { get; } | Nicht initialisierte Farbe – alle 4 Kanäle sind auf 0 gesetzt. Wie Standard und Transparent. |
| [IsFullyOpaque](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullyopaque) { get; } | Gibt an, ob dies[`ArgbColor`](../argbcolor) Instanz ist vollständig undurchsichtig, ohne Transparenz (ihr Alpha-Kanal hat den maximalen Wert) |
| [IsFullyTransparent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullytransparent) { get; } | Gibt an, ob dies[`ArgbColor`](../argbcolor) Instanz ist vollständig transparent – ihr Alpha-Kanal hat den Mindestwert (0), sodass andere R-, G- und B-Kanäle keinen sichtbaren Effekt haben. |
| [IsTranslucent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/istranslucent) { get; } | Gibt an, ob dies[`ArgbColor`](../argbcolor) Beispiel ist durchscheinend (nicht vollständig transparent, aber auch nicht vollständig undurchsichtig) |
| [R](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/r) { get; } | Ruft den roten Teil der Farbe ab. |
| [Value](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/value) { get; } | Ruft den Int32-Wert der Farbe ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgb)(byte, byte, byte) | Erstellt einen[`ArgbColor`](../argbcolor) Wert aus den angegebenen Rot-, Grün- und Blaukanälen, während der Alphakanal vollständig undurchsichtig ist |
| static [FromRgba](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgba)(byte, byte, byte, byte) | Erstellt einen[`ArgbColor`](../argbcolor) Wert aus den angegebenen Rot-, Grün-, Blau- und Alphakanälen |
| static [FromSingleValueRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromsinglevaluergb)(byte) | Erstellt eine vollständig deckende (A=255) Farbe aus einem Einzelwert, die auf alle Kanäle angewendet wird |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals)(ArgbColor) | Prüft zwei[`ArgbColor`](../argbcolor) Farben für Gleichheit |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals_1)(object) | Testet, ob ein anderes Objekt gleich diesem ist[`ArgbColor`](../argbcolor) Instanz. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/gethashcode)() | Gibt einen Hash-Code zurück, der die aktuelle Farbe definiert. |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/serializedefault)() | Serialisiert dies[`ArgbColor`](../argbcolor)Instanz zur am besten geeigneten CSS-Funktionsnotation abhängig von translucency |
| [ToRGB](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgb)() | Serialisiert dies[`ArgbColor`](../argbcolor) Instanz zur 'rgb' CSS-Funktion notation |
| [ToRGBA](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgba)() | Serialisiert dies[`ArgbColor`](../argbcolor) Instanz zur 'rgba' CSS-Funktion notation |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/tostring)() | Gleich wie[`SerializeDefault`](./serializedefault) |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_equality) | Vergleicht zwei Farben und gibt einen booleschen Wert zurück, der angibt, ob die beiden übereinstimmen. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_inequality) | Vergleicht zwei Farben und gibt einen booleschen Wert zurück, der angibt, ob die beiden nicht übereinstimmen. |

## Andere Mitglieder

| Name | Beschreibung |
| --- | --- |
| static class [KnownColors](argbcolor.knowncolors) | Enthält alle "bekannten Farben", die einen festen eindeutigen Namen und Wert in CSS haben standart |

### Bemerkungen

Dieser Typ wurde entwickelt, um für CSS-Operationen nützlich zu sein (aber nicht darauf beschränkt). Siehe mehr: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### Siehe auch

* interface [ICssDataType](../icssdatatype)
* namensraum [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* Montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
