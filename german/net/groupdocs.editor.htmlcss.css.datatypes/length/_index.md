---
title: "Length"
second_title: "GroupDocs.Editor für .NET API-Referenz"
description: "Stellt einen CSS-Längenwert in jeder unterstützten Einheit dar, einschließlich Prozent und einheitenlosem Typ. Werte können ganzzahlig oder Fließkomma, negativ, null oder positiv sein. Unveränderliche Struktur."
type: docs
weight: 230
url: /de/net/groupdocs.editor.htmlcss.css.datatypes/length/
---
## Length structure

Stellt einen CSS-Längenwert in jeder unterstützbaren Einheit dar, einschließlich Prozent und einheitenlosem Typ. Werte können ganzzahlig oder Fließkomma, negativ, null oder positiv sein. Unveränderliche Struktur.

```csharp
public struct Length : ICloneable, ICssDataType, IEquatable<Length>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [FloatValue](../../groupdocs.editor.htmlcss.css.datatypes/length/floatvalue) { get; } | Gibt einen Fließkomma-Numerischen Wert der Length-Instanz zurück. Wirft niemals eine Ausnahme – konvertiert bei Bedarf den Integer-Wert zu Float. |
| [IntegerValue](../../groupdocs.editor.htmlcss.css.datatypes/length/integervalue) { get; } | Gibt einen ganzzahligen numerischen Wert dieser Length-Instanz zurück, falls er intern als Integer gespeichert ist, oder wirft eine Ausnahme, falls er ursprünglich als Fließkommazahl gespeichert war. |
| [IsAbsolute](../../groupdocs.editor.htmlcss.css.datatypes/length/isabsolute) { get; } | Ermittelt, ob die Länge in absoluten Einheiten angegeben ist. Eine solche Länge kann in Pixel umgerechnet werden. |
| [IsDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/isdefault) { get; } | Gibt an, ob diese Length-Instanz einen Standardwert — einheitenloses Null — hat. Entspricht der Eigenschaft IsUnitlessZero. |
| [IsFloat](../../groupdocs.editor.htmlcss.css.datatypes/length/isfloat) { get; } | Gibt an, ob der numerische Wert dieser Length-Instanz ursprünglich als Fließkomma (FP32)-Zahl angegeben und gespeichert wurde |
| [IsInteger](../../groupdocs.editor.htmlcss.css.datatypes/length/isinteger) { get; } | Gibt an, ob der numerische Wert dieser Length-Instanz ursprünglich als Ganzzahl (INT32)-Zahl angegeben und gespeichert wurde |
| [IsNegative](../../groupdocs.editor.htmlcss.css.datatypes/length/isnegative) { get; } | Bestimmt, ob der numerische Wert dieser Länge eine negative Zahl ist |
| [IsPositive](../../groupdocs.editor.htmlcss.css.datatypes/length/ispositive) { get; } | Bestimmt, ob der numerische Wert dieser Länge eine positive Zahl ist |
| [IsRelative](../../groupdocs.editor.htmlcss.css.datatypes/length/isrelative) { get; } | Ermittelt, ob die Länge in relativen Einheiten angegeben ist. Eine solche Länge kann nicht in Pixel umgerechnet werden. |
| [IsUnitlessNonZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlessnonzero) { get; } | Der Wert hat einen einheitenlosen Typ, ist aber keine Null – positive oder negative Zahl |
| [IsUnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/isunitlesszero) { get; } | Bestimmt, ob diese Instanz ein einheitenloses Null ist oder nicht. Ein einheitenloses Null ist der Standardwert dieses Typs. Entspricht der Eigenschaft IsDefault. |
| [IsZero](../../groupdocs.editor.htmlcss.css.datatypes/length/iszero) { get; } | Bestimmt, ob der numerische Wert dieser Länge eine Null ist |
| [UnitType](../../groupdocs.editor.htmlcss.css.datatypes/length/unittype) { get; } | Gibt den Einheitstyp dieser Length-Instanz zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit)(double, Unit) | Erstellt und gibt eine Instanz des Length-Typs zurück, basierend auf einer angegebenen double-Zahl und Einheit |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_2)(float, Unit) | Erstellt und gibt eine Instanz des Length-Typs zurück, basierend auf einer angegebenen float-Zahl und Einheit |
| static [FromValueWithUnit](../../groupdocs.editor.htmlcss.css.datatypes/length/fromvaluewithunit#fromvaluewithunit_1)(int, Unit) | Erstellt und gibt eine Instanz des Length-Typs zurück, basierend auf einer angegebenen Ganzzahl und Einheit |
| static [Parse](../../groupdocs.editor.htmlcss.css.datatypes/length/parse)(string) | Parst und gibt die angegebene Zeichenkette als Length-Wert zurück, einschließlich ihres numerischen Werts und Einheitnamens, oder wirft bei einem Fehler eine Ausnahme. |
| [Clone](../../groupdocs.editor.htmlcss.css.datatypes/length/clone)() | Gibt eine vollständige Kopie dieser Length-Instanz zurück |
| [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals)(Length) | Definiert, ob dieser Wert gleich der anderen angegebenen Länge ist |
| override [Equals](../../groupdocs.editor.htmlcss.css.datatypes/length/equals#equals_1)(object) | Bestimmt, ob diese Länge gleich dem angegebenen Objekt ist |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.datatypes/length/gethashcode)() | Berechnet und gibt einen Hashcode dieser Length-Instanz zurück, indem die Hashcodes des Werts und des Einheitstyps kombiniert werden |
| [SerializeDefault](../../groupdocs.editor.htmlcss.css.datatypes/length/serializedefault)() | Gibt eine Zeichenkettenrepräsentation dieser Länge in ihrer ursprünglichen nativen Form (wie sie gespeichert ist) zurück, ohne den Längenwert in einen anderen Einheitstyp zu konvertieren |
| [To](../../groupdocs.editor.htmlcss.css.datatypes/length/to)(Unit) | Konvertiert die Länge in die angegebene Einheit, falls möglich. Wenn die aktuelle oder angegebene Einheit relativ ist, wird eine Ausnahme ausgelöst. |
| [ToPixel](../../groupdocs.editor.htmlcss.css.datatypes/length/topixel)() | Konvertiert die Länge in eine Anzahl von Pixeln, falls möglich. Wenn die aktuelle Einheit relativ ist, wird eine Ausnahme ausgelöst. |
| [ToStringSpecified](../../groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified)(Unit) | Gibt eine Zeichenkettenrepräsentation dieser Länge im angegebenen Einheitstyp zurück. Der numerische Wert wird entsprechend der Änderung des Einheitstyps konvertiert. |
| static [GetUnitFromName](../../groupdocs.editor.htmlcss.css.datatypes/length/getunitfromname)(string) | Versucht, den angegebenen Einheitnamen zu parsen und den entsprechenden Wert eines Unit-Enums zurückzugeben. Gibt Unit.Unitless zurück, wenn keine passende Einheit gefunden wird. |
| static [TryParse](../../groupdocs.editor.htmlcss.css.datatypes/length/tryparse)(string, out Length) | Versucht, eine angegebene Zeichenkette als Length-Wert zu parsen, einschließlich ihres numerischen Werts und Einheitnamens |
| [operator ==](../../groupdocs.editor.htmlcss.css.datatypes/length/op_equality) | Überprüft die Gleichheit der beiden angegebenen Längen. |
| [operator !=](../../groupdocs.editor.htmlcss.css.datatypes/length/op_inequality) | Überprüft die Ungleichheit der beiden angegebenen Längen. |
| [operator *](../../groupdocs.editor.htmlcss.css.datatypes/length/op_multiply) | Multipliziert die gegebene Length mit dem angegebenen Faktor |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [FiftyPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/fiftypercents) | 50% |
| static readonly [OneHundredPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/onehundredpercents) | 100% |
| static readonly [UnitlessZero](../../groupdocs.editor.htmlcss.css.datatypes/length/unitlesszero) | Einheitenlose Ganzzahl Null – Standardwert, derselbe wie der parameterlose Standardkonstruktor |
| static readonly [ZeroPercents](../../groupdocs.editor.htmlcss.css.datatypes/length/zeropercents) | 0% |

## Weitere Mitglieder

| Name | Beschreibung |
| --- | --- |
| enum [Unit](length.unit) | Alle unterstützten Längeneinheiten |

### Hinweise

Dieser Typ umfasst die folgenden CSS‑Datentypen: https://developer.mozilla.org/en-US/docs/Web/CSS/length https://developer.mozilla.org/en-US/docs/Web/CSS/percentage

### Siehe auch

* interface [ICssDataType](../icssdatatype)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
