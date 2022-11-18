---
title: ToStringSpecified
second_title: GroupDocs.Editor för .NET API-referens
description: Returnerar en strängrepresentation av denna längd i angiven enhetstyp. Numeriskt värde kommer att konverteras till motsvarande enhetstypsändring.
type: docs
weight: 260
url: /sv/net/groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified/
---
## Length.ToStringSpecified method

Returnerar en strängrepresentation av denna längd i angiven enhetstyp. Numeriskt värde kommer att konverteras till motsvarande enhetstypsändring.

```csharp
public string ToStringSpecified(Unit unit)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| unit | Unit | Angiven enhet, till vilken den här instansen ska konverteras innan den serialiseras till strängen. Bör vara giltig. Kan inte vara enhetslös. |

### Returvärde

Strängrepresentation

### Undantag

| undantag | skick |
| --- | --- |
| InvalidEnumArgumentException | Värdet är inte definierat |
| ArgumentOutOfRangeException | Enhetslöst värde är förbjudet |

### Se även

* enum [Unit](../../length.unit)
* struct [Length](../../length)
* namnutrymme [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../length)
* hopsättning [GroupDocs.Editor](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Editor.dll -->