---
title: ToStringSpecified
second_title: GroupDocs.Editor für .NET-API-Referenz
description: Gibt eine Zeichenfolgendarstellung dieser Länge im angegebenen Einheitentyp zurück. Der numerische Wert wird entsprechend der Änderung des Einheitentyps konvertiert.
type: docs
weight: 260
url: /de/net/groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified/
---
## Length.ToStringSpecified method

Gibt eine Zeichenfolgendarstellung dieser Länge im angegebenen Einheitentyp zurück. Der numerische Wert wird entsprechend der Änderung des Einheitentyps konvertiert.

```csharp
public string ToStringSpecified(Unit unit)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| unit | Unit | Angegebene Einheit, in die diese Instanz konvertiert werden soll, bevor sie in den String. serialisiert wird. Sollte gültig sein. Kann nicht einheitenlos sein. |

### Rückgabewert

Zeichenfolgendarstellung

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| InvalidEnumArgumentException | Wert ist nicht definiert |
| ArgumentOutOfRangeException | Einheitsloser Wert ist verboten |

### Siehe auch

* enum [Unit](../../length.unit)
* struct [Length](../../length)
* namensraum [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../length)
* Montage [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->