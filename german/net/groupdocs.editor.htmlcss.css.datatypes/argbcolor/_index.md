---
title: "ArgbColor"
second_title: "GroupDocs.Editor für .NET API-Referenz"
description: "Stellt einen Farbwert im 32‑Bit‑ARGB‑Format dar, 8 Bit pro Kanal einschließlich Transparenz, mit Konvertern und Serialisierern"
type: docs
weight: 160
url: /de/net/groupdocs.editor.htmlcss.css.datatypes/argbcolor/
---
## ArgbColor structure

Stellt einen Farbwert im 32-Bit-ARGB-Format (8 Bit pro Kanal einschließlich Transparenz) mit Konvertern und Serialisierern dar

```csharp
public struct ArgbColor : ICssDataType, IEquatable<ArgbColor>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [A](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/a) { get; } | Liefert den Alpha‑Teil der Farbe. |
| [Alpha](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/alpha) { get; } | Liefert den Alpha‑Teil der Farbe in Prozent (0..1). |
| [B](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/b) { get; } | Liefert den Blau‑Teil der Farbe. |
| [G](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/g) { get; } | Liefert den Grün‑Teil der Farbe. |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isdefault) { get; } | Gibt an, ob diese [`ArgbColor`](../argbcolor)-Instanz standardmäßig (Transparent) ist – alle 4 Kanäle sind auf 0 gesetzt |
| [IsEmpty](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isempty) { get; } | Nicht initialisierte Farbe – alle 4 Kanäle sind auf 0 gesetzt. Gleichbedeutend mit Standard und Transparent. |
| [IsFullyOpaque](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullyopaque) { get; } | Gibt an, ob diese [`ArgbColor`](../argbcolor)-Instanz vollständig undurchsichtig ist, ohne Transparenz (ihr Alpha‑Kanal hat den Maximalwert). |
| [IsFullyTransparent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/isfullytransparent) { get; } | Gibt an, ob diese [`ArgbColor`](../argbcolor)-Instanz vollständig transparent ist – ihr Alpha‑Kanal hat den Minimalwert (0), sodass die anderen R‑, G‑ und B‑Kanäle keinen sichtbaren Effekt haben. |
| [IsTranslucent](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/istranslucent) { get; } | Gibt an, ob diese [`ArgbColor`](../argbcolor)-Instanz transluzent ist (weder vollständig transparent noch vollständig undurchsichtig). |
| [R](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/r) { get; } | Liefert den Rot‑Teil der Farbe. |
| [Value](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/value) { get; } | Liefert den Int32‑Wert der Farbe. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgb)(byte, byte, byte) | Erstellt einen [`ArgbColor`](../argbcolor)-Wert aus den angegebenen Rot‑, Grün‑ und Blau‑Kanälen, wobei der Alpha‑Kanal vollständig undurchsichtig ist. |
| static [FromRgba](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromrgba)(byte, byte, byte, byte) | Erstellt einen [`ArgbColor`](../argbcolor)-Wert aus den angegebenen Rot‑, Grün‑, Blau‑ und Alpha‑Kanälen. |
| static [FromSingleValueRgb](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/fromsinglevaluergb)(byte) | Erstellt eine vollständig undurchsichtige (A=255) Farbe aus einem einzelnen Wert, der auf alle Kanäle angewendet wird. |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals)(ArgbColor) | Überprüft zwei [`ArgbColor`](../argbcolor)-Farben auf Gleichheit. |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/equals#equals_1)(object) | Prüft, ob ein anderes Objekt dieser [`ArgbColor`](../argbcolor)-Instanz gleich ist. |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/gethashcode)() | Gibt einen Hash‑Code zurück, der die aktuelle Farbe definiert. |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/serializedefault)() | Serialisiert diese [`ArgbColor`](../argbcolor)-Instanz in die am besten geeignete CSS‑Funktionsnotation, abhängig von der Transparenz. |
| [ToRGB](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgb)() | Serialisiert diese [`ArgbColor`](../argbcolor)-Instanz in die CSS‑Funktionsnotation 'rgb'. |
| [ToRGBA](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/torgba)() | Serialisiert diese [`ArgbColor`](../argbcolor)-Instanz in die CSS‑Funktionsnotation 'rgba'. |
| override [ToString](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/tostring)() | Dasselbe wie [`SerializeDefault`](./serializedefault) |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_equality) | Vergleicht zwei Farben und gibt einen booleschen Wert zurück, der angibt, ob die beiden übereinstimmen. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/argbcolor/op_inequality) | Vergleicht zwei Farben und gibt einen booleschen Wert zurück, der angibt, ob die beiden nicht übereinstimmen. |

## Weitere Mitglieder

| Name | Beschreibung |
| --- | --- |
| static class [KnownColors](argbcolor.knowncolors) | Enthält alle "bekannten Farben", die einen festen eindeutigen Namen und Wert im CSS-Standard haben |

### Hinweise

Dieser Typ ist dafür ausgelegt, für (aber nicht beschränkt auf) CSS-Operationen nützlich zu sein. Weitere Informationen: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### Siehe auch

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
