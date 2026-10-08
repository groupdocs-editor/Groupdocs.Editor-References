---
title: "ToStringSpecified"
second_title: "GroupDocs.Editor för .NET API-referens"
description: "Returnerar en strängrepresentation av denna längd i den angivna enhetstypen. Det numeriska värdet kommer att konverteras i enlighet med enhetsbytet."
type: docs
weight: 260
url: /sv/net/groupdocs.editor.htmlcss.css.datatypes/length/tostringspecified/
---
## Length.ToStringSpecified method

Returnerar en strängrepresentation av denna längd i den angivna enhetstypen. Det numeriska värdet kommer att konverteras i enlighet med enhetsbytet.

```csharp
public string ToStringSpecified(Unit unit)
```

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| enhet | Enhet | Angiven enhet, till vilken detta objekt ska konverteras innan det serialiseras till en sträng. Den bör vara giltig. Får inte vara enhetslös. |

### Returvärde

Strängrepresentation

### Undantag

| undantag | villkor |
| --- | --- |
| InvalidEnumArgumentException | Värdet är inte definierat |
| ArgumentOutOfRangeException | Värde utan enhet är förbjudet |

### Se även

* enum [Unit](../../length.unit)
* struct [Length](../../length)
* namespace [GroupDocs.Editor.HtmlCss.Css.DataTypes](../../../groupdocs.editor.htmlcss.css.datatypes)
* assembly [GroupDocs.Editor](../../../)

<!-- REDIGERA INTE: genererad av xmldocmd för GroupDocs.editor.dll -->
