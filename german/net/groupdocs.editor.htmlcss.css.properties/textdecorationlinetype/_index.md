---
title: "TextDecorationLineType"
second_title: "GroupDocs.Editor für .NET API-Referenz"
description: "Stellt die Typen der Textdekoration dar: Unterstreichung, Unterstrich, Oberstreichung und Durchstreichung"
type: docs
weight: 290
url: /de/net/groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/
---
## TextDecorationLineType structure

Stellt Typen der Textdekoration dar: Unterstreichung (Unterstrich), Oberstreichung und Durchstreichung (Strikethrough)

```csharp
public struct TextDecorationLineType : IEquatable<TextDecorationLineType>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [IsInitial](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isinitial) { get; } | Gibt an, ob diese Instanz einen Anfangswert hat — None |
| [IsLineThrough](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/islinethrough) { get; } | Gibt an, ob Durchstreichen (Strikethrough) aktiviert ist |
| [IsOverline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isoverline) { get; } | Gibt an, ob Oberstreichung aktiviert ist |
| [IsUnderline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/isunderline) { get; } | Gibt an, ob Unterstreichung (Unterstrich) aktiviert ist |
| [Value](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/value) { get; } | Gibt einen Wert aller Flags in dieser Instanz als Text zurück |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromFlags](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/fromflags)(bool, bool, bool) | Erstellt und gibt eine [`TextDecorationLineType`](../textdecorationlinetype) Instanz mit Flags zurück, die durch die angegebenen Parameter definiert sind |
| override [Equals](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/equals#equals_1)(object) | Gibt an, ob diese [`TextDecorationLineType`](../textdecorationlinetype) Instanz gleich dem angegebenen nicht gecasteten Wert ist |
| [Equals](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/equals#equals)(TextDecorationLineType) | Gibt an, ob diese [`TextDecorationLineType`](../textdecorationlinetype) Instanz gleich dem angegebenen ist |
| override [GetHashCode](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/gethashcode)() | Gibt einen Hash-Code dieser Instanz zurück |
| override [ToString](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/tostring)() | Gibt einen Wert aller Flags in dieser Instanz als Text zurück |
| static [TryParse](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/tryparse)(string, out TextDecorationLineType) | Versucht, einen angegebenen String zu analysieren und eine gültige [`TextDecorationLineType`](../textdecorationlinetype) Instanz zurückzugeben |
| [operator +](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_addition) | Kombiniert (vereint) zwei angegebene Linientypen und erzeugt einen neuen resultierenden Linientyp, bei dem die Flags zusammengeführt (Vereinigung) werden |
| [operator /](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_division) | Gibt die Schnittmenge zwischen dem ersten und zweiten Linientyp zurück, wobei nur jene Flags aktiviert sind, die in beiden Operanden gleichzeitig aktiviert sind. Hat die höchste Priorität aller Operatoren (höher als Vereinigung und Differenz) |
| [operator ==](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_equality) | Überprüft, ob zwei "TextDecorationLineType"-Werte gleich sind |
| [explicit operator](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_explicit#op_explicit_1) | Wandelt ein bestimmtes Byte (8‑Bit‑Oktett) in den entsprechenden [`TextDecorationLineType`](../textdecorationlinetype) um, wirft eine Ausnahme, wenn die Umwandlung ungültig ist (2 Operatoren) |
| [operator !=](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_inequality) | Überprüft, ob zwei "TextDecorationLineType"‑Werte nicht gleich sind |
| [operator -](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/op_subtraction) | Subtrahiert den zweiten angegebenen Linientyp vom ersten angegebenen Linientyp und erzeugt einen neuen resultierenden Linientyp, bei dem nur jene Flags des ersten Operanden vorhanden sind, die im zweiten Operanden nicht vorkommen (Differenz) |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [LineThrough](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/linethrough) | Jede Textzeile hat eine Linie durch die Mitte. |
| static readonly [None](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/none) | Erzeugt keine Textdekoration. Anfangswert. |
| static readonly [Overline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/overline) | Jede Textzeile hat eine Linie darüber. |
| static readonly [Underline](../../groupdocs.editor.htmlcss.css.properties/textdecorationlinetype/underline) | Jede Textzeile ist unterstrichen. |

### Hinweise

Unveränderliche Struktur. Ähnlich wie die https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line

### Siehe auch

* namespace [GroupDocs.Editor.HtmlCss.Css.Properties](../../groupdocs.editor.htmlcss.css.properties)
* assembly [GroupDocs.Editor](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.editor.dll -->
