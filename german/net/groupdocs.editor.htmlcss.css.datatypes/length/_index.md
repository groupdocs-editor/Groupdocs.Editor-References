---
title: Length
second_title: GroupDocs.Editor für .NET-API-Referenz
description: Repräsentiert einen CSSLängenwert in jeder unterstützbaren Einheit einschließlich Prozent und einheitsloser Typen. Werte können ganzzahlig oder Gleitkommazahl negativ null und positiv sein. Unveränderliche Struktur.
type: docs
weight: 190
url: /de/net/groupdocs.editor.htmlcss.css.datatypes/length/
---
## Length structure

Repräsentiert einen CSS-Längenwert in jeder unterstützbaren Einheit, einschließlich Prozent und einheitsloser Typen. Werte können ganzzahlig oder Gleitkommazahl, negativ, null und positiv sein. Unveränderliche Struktur.

```csharp
public struct Length : ICloneable, IEquatable<  >, IEquatable<Length>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [FloatValue](../../groupdocs.editor.htmlcss.css.datatypes/length/floatvalue) { get; } | Gibt einen numerischen Float-Wert der Length-Instanz zurück. Löst nie eine Ausnahme aus – wandelt den Integer-Wert bei Bedarf in Float um. |
| [IntegerValue](../../groupdocs.editor.htmlcss.css.datatypes/length/integervalue) { get; } | Gibt einen ganzzahligen numerischen Wert dieser Längeninstanz zurück, wenn er intern als Ganzzahl gespeichert ist, oder löst eine Ausnahme aus, wenn er ursprünglich als Gleitkommazahl gespeichert wurde. |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.datatypes/length/isabsolute) { get; } | Ruft ab, ob die Länge in absoluten Einheiten angegeben ist. Eine solche Länge kann in Pixel umgewandelt werden. |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/isdefault) { get; } | Gibt an, ob diese Längeninstanz einen Standardwert hat – einheitenlose Null. Identisch mit der IsUnitlessZero-Eigenschaft. |
| [IsFloat](../../groupdocs.editor.htmlcss.css.datatypes/length/isfloat) { get; } | Gibt an, ob der numerische Wert dieser Längeninstanz ursprünglich angegeben und als Gleitkommazahl (FP32) gespeichert wurde number |
| [IsInteger](../../groupdocs.editor.htmlcss.css.datatypes/length/isinteger) { get; } | Gibt an, ob der numerische Wert dieser Längeninstanz ursprünglich angegeben und als Ganzzahl (INT32) gespeichert wurde number |
| [IsNegative](../../groupdocs.editor.htmlcss.css.datatypes/length/isnegative) { get; } | Bestimmt, ob der numerische Wert dieser Länge eine negative Zahl ist |
| [IsPositive](../../groupdocs.editor.htmlcss.css.datatypes/length/ispositive) { get; } | Bestimmt, ob der numerische Wert dieser Länge eine positive Zahl ist |
| [IsRelative](../../groupdocs.editor.htmlcss.css.datatypes/length/isrelative) { get; } | Ruft ab, ob die Länge in relativen Einheiten angegeben ist. Eine solche Länge kann nicht in Pixel umgerechnet werden. |
| [IsUnitlessNonZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlessnonzero) { get; } | Der Wert hat einen einheitenlosen Typ, ist aber keine Null - positive oder negative Zahl |
| [IsUnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlesszero) { get; } | Bestimmt, ob diese Instanz eine einheitenlose Null ist oder nicht. Null ohne Einheit ist der Standardwert dieses Typs. Identisch mit IsDefault-Eigenschaft. |
| [IsZero](../../groupdocs.editor.htmlcss.css.datatypes/length/iszero) { get; } | Bestimmt, ob der numerische Wert dieser Länge eine Null ist number |
| [UnitType](../../groupdocs.editor.htmlcss.css.datatypes/length/unittype) { get; } | Gibt einen Einheitentyp dieser Längeninstanz zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit)(double, Unit) | Erstellt und gibt eine Instanz des Längentyps durch die angegebene doppelte Zahl und Einheit zurück |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_2)(float, Unit) | Erstellt und gibt eine Instanz des Längentyps nach angegebener Gleitkommazahl und Einheit zurück |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_1)(int, Unit) | Erstellt und gibt eine Instanz des Längentyps durch die angegebene Ganzzahl und Einheit zurück |
| static [Parse](../../groupdocs.editor.htmlcss.css.datatypes/length/parse)(string) | Analysiert und gibt die angegebene Zeichenfolge als Längenwert zurück, einschließlich ihres numerischen Werts und Einheitennamens, oder löst eine Ausnahme bei Fehler aus |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/length/clone)() | Gibt eine vollständige Kopie dieser Längeninstanz zurück |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals)(Length) | Definiert, ob dieser Wert gleich der anderen angegebenen Länge ist |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals_1)(object) | Bestimmt, ob diese Länge gleich dem angegebenen Objekt ist |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/length/gethashcode)() | Berechnet und gibt einen Hash-Code dieser Längeninstanz zurück, indem Hash-Codes des Werts und der Einheit type kombiniert werden. |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/serializedefault)() | Gibt eine Zeichenfolgendarstellung dieser Länge in ihrer ursprünglichen nativen Form (wie sie gespeichert ist) zurück, ohne den Längenwert in eine andere Einheit umzuwandeln type |
| [To](../../groupdocs.editor.htmlcss.css.datatypes/length/to)(Unit) | Rechnet die Länge wenn möglich in die angegebene Einheit um. Wenn der aktuelle oder die angegebene Einheit relativ ist, wird eine Ausnahme ausgelöst. |
| [ToPixel](../../groupdocs.editor.htmlcss.css.datatypes/length/topixel)() | Wandelt die Länge wenn möglich in eine Anzahl von Pixeln um. Wenn die aktuelle Einheit relativ ist, wird eine Ausnahme ausgelöst. |
| [ToStringSpecified](../../groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified)(Unit) | Gibt eine Zeichenfolgendarstellung dieser Länge im angegebenen Einheitentyp zurück. Der numerische Wert wird entsprechend der Änderung des Einheitentyps konvertiert. |
| static [GetUnitFromName](../../groupdocs.editor.htmlcss.css.datatypes/length/getunitfromname)(string) | Versucht, den angegebenen Einheitennamen zu analysieren und den entsprechenden Wert einer Einheitennummer zurückzugeben. Gibt Unit.Unitless zurück, wenn die entsprechende Einheit nicht gefunden werden kann. |
| static [TryParse](../../groupdocs.editor.htmlcss.css.datatypes/length/tryparse)(string, out Length) | Versucht, eine angegebene Zeichenfolge als Längenwert zu analysieren, einschließlich ihres numerischen Werts und Einheitennamens |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/length/op_equality) | Überprüft die Gleichheit der beiden angegebenen Längen. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/length/op_inequality) | Überprüft die Ungleichheit der beiden angegebenen Längen. |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [FiftyPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/fiftypercents) | 50 % |
| static readonly [OneHundredPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/onehundredpercents) | 100 % |
| static readonly [UnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/unitlesszero) | Ganzzahl ohne Einheit Null - Standardwert, derselbe wie standardmäßiger parameterloser Konstruktor |
| static readonly [ZeroPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/zeropercents) | 0% |

## Andere Mitglieder

| Name | Beschreibung |
| --- | --- |
| enum [Unit](length.unit) | Alle unterstützten Längeneinheiten |

### Bemerkungen

Dieser Typ deckt die nächsten CSS-Datentypen ab: https://developer.mozilla.org/en-US/docs/Web/CSS/length https://developer.mozilla.org/en-US/docs/Web/ CSS/Prozentsatz

### Siehe auch

* namensraum [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* Montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
