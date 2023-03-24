---
title: FontSize
second_title: GroupDocs.Editor für .NET-API-Referenz
description: Stellt eine Schriftgröße als spezielle Einheit oder einen Längenwert dar der die Größe der Schrift angibt historisch gesehen die Breite des Großbuchstabens M.
type: docs
weight: 290
url: /de/net/groupdocs.editor.htmlcss.css.properties/fontsize/
---
## FontSize structure

Stellt eine Schriftgröße als spezielle Einheit oder einen Längenwert dar, der die Größe der Schrift angibt (historisch gesehen die Breite des Großbuchstabens „M“).

```csharp
public struct FontSize : IEquatable<FontSize>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [IsAbsoluteSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isabsolutesize) { get; } | Gibt an, ob diese Schriftgröße mit einer absoluten Größe als Schlüsselwort definiert ist, basierend auf der Standardschriftgröße des Benutzers (die mittel ist) |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/fontsize/isinitial) { get; } | Gibt an, ob diese Schriftgröße einen Anfangswert hat (Medium) |
| [IsLengthDefined](../../groupdocs.editor.htmlcss.css.properties/fontsize/islengthdefined) { get; } | Gibt an, ob diese Schriftgröße mit a definiert ist[`Length`](../../groupdocs.editor.htmlcss.css.datatypes/length) wert |
| [IsRelativeSize](../../groupdocs.editor.htmlcss.css.properties/fontsize/isrelativesize) { get; } | Gibt an, ob diese Schriftgröße mit einer relativen Größe als Schlüsselwort definiert ist. Die Schriftart wird relativ zur Schriftgröße des übergeordneten Elements größer oder kleiner, ungefähr um das Verhältnis, das verwendet wird, um die Schlüsselwörter mit absoluter Größe zu trennen. |
| [Length](../../groupdocs.editor.htmlcss.css.properties/fontsize/length) { get; } | Ein Längenwert, wenn diese Schriftgröße damit definiert wurde, oder warf sonst eine Ausnahme |
| [Value](../../groupdocs.editor.htmlcss.css.properties/fontsize/value) { get; } | Gibt einen Wert dieser Schriftgröße als Zeichenfolge zurück |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromLength](../../groupdocs.editor.htmlcss.css.properties/fontsize/fromlength)(Length) | Erstellt eine Schriftgröße aus der angegebenen Länge |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals)(FontSize) | Bestimmt, ob diese Schriftgrößeninstanz gleich der angegebenen ist |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/fontsize/equals#equals_1)(object) | Bestimmt, ob diese Schriftgrößeninstanz gleich dem angegebenen uncasted ist |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/fontsize/gethashcode)() | Gibt einen Hash-Code für diese Instanz zurück |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/fontsize/tryparse)(string, out FontSize) | Versucht, ein angegebenes Schlüsselwort als richtigen Schlüsselwortwert der 'Schriftgröße' zu erkennen und es bei Erfolg oder NULL bei Misserfolg zurückzugeben. |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_equality) | Überprüft, ob zwei „FontSize“-Werte gleich sind |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/fontsize/op_inequality) | Prüft, ob zwei „FontSize“-Werte ungleich sind |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [Large](../../groupdocs.editor.htmlcss.css.properties/fontsize/large) | Die normalerweise große absolute Größe |
| static readonly [Larger](../../groupdocs.editor.htmlcss.css.properties/fontsize/larger) | Größere relative Größe - Die Schriftart wird relativ zur Schriftgröße des übergeordneten Elements größer, ungefähr um das Verhältnis, das verwendet wird, um die Schlüsselwörter für die absolute Größe oben zu trennen. |
| static readonly [Medium](../../groupdocs.editor.htmlcss.css.properties/fontsize/medium) | Mittlere Größe. Anfangswert. |
| static readonly [Small](../../groupdocs.editor.htmlcss.css.properties/fontsize/small) | Die normalerweise kleine absolute Größe |
| static readonly [Smaller](../../groupdocs.editor.htmlcss.css.properties/fontsize/smaller) | Kleinere relative Größe – Die Schriftart wird im Verhältnis zur Schriftgröße des übergeordneten Elements kleiner, ungefähr um das Verhältnis, das verwendet wird, um die Schlüsselwörter für die absolute Größe oben zu trennen. |
| static readonly [XLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xlarge) | Die mittelmäßige große Absolutgröße |
| static readonly [XSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xsmall) | Die mittelmäßige kleine Absolutgröße |
| static readonly [XxLarge](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxlarge) | Die sehr große absolute Größe |
| static readonly [XxSmall](../../groupdocs.editor.htmlcss.css.properties/fontsize/xxsmall) | Die sehr kleine absolute Größe |

### Siehe auch

* namensraum [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* Montage [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->
